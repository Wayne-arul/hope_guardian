# Hope Guardian: Your Mental Health Companion

![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

## Introduction

**Hope Guardian**: A groundbreaking program harnessing the power of ChatGPT API and OpenAI API to provide unwavering support for your mental well-being. It offers personalized guidance, invaluable tips, and effective emotional coping strategies. 

## Overview

Hope Guardian is designed to empower individuals facing mental health challenges. By leveraging the ChatGPT API and the OpenAI API, it provides tailored support and guidance. The program is dedicated to offering practical tips, aiding in the cultivation of healthy habits, and motivating self-improvement. Hope Guardian bridges the gap in the mental health landscape, catering to those who may not require full-fledged therapy or medication but still need a strong support system. Remember, it is not intended as a replacement for therapy or medication.

## Key Features

### 1. Actionable Guidance

Hope Guardian offers actionable and insightful tips to help you navigate your mental health journey effectively.

### 2. Encouragement for Personal Growth

We provide constant encouragement and motivation to aid in your personal growth and development.

### 3. Promoting Healthy Habits

Discover guidance and strategies for adopting and maintaining a lifestyle that prioritizes mental well-being.

### 4. Shifting Focus from Negative Thoughts

Hope Guardian suggests ways to divert your attention from negative thoughts, fostering a positive mindset.

### 5. Assistance in Managing Rumination

Our program assists in recognizing and redirecting harmful rumination, promoting mental clarity and peace.

## Installation

Follow next steps in order to obtain the power of Personal-ChatGPT

### Step 1 - Git clone

```
git clone https://github.com/Wayne-arul/hope_guardian.git
```

### Step 2 - Install required packages.

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip3 install langchain openai chromadb tiktoken unstructured requests duckduckgo-search google-search-results
```

### Step 3 - Update OpenAI API Key


Modify `env.py.copy` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `env.py`.

### Step 4 - Place your own personal DATA

Place your own data into `data/`.


## Example usage

### Example of hope guardian
Test reading `data/cognitive-behavioural-therapy` file.

```
> python hope_guardian.py "I'm feeling anxious about my upcoming job interview."
 It's totally normal to feel anxious about a job interview. I mean, you're putting yourself out there and hoping to make a good impression. But there are a few things you can do to calm your nerves and feel more confident.

First, take some time to practice answering common interview questions. This will help you feel more prepared and less likely to panic. You can also do some research on the company and the position you're interviewing for. This will show the interviewer that you're serious about the job and have taken the time to learn about them.

On the day of the interview, get a good night's sleep and eat a healthy breakfast. This will give you the energy you need to focus and do your best. And be sure to arrive early so you have time to relax and collect your thoughts.

Remember, the interviewer is just as interested in getting to know you as you are in getting to know them. So be yourself, be confident, and let your personality shine through.

Is there anything else I can help you with today?
```




