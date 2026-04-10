# 🧠 NLP Preprocessing Engine

A robust and modular NLP preprocessing pipeline designed to clean, normalize, and analyze real-world noisy text data. This project is built as part of a Data Science Internship assignment.

## 🚀 Project Overview

Raw text data from real-world sources is often messy and unstructured.  
This project builds a **cleaning and preprocessing engine** that converts noisy text into meaningful tokens suitable for Machine Learning and NLP tasks.

## 🎯 Objectives

- Clean and normalize raw text data  
- Handle noisy patterns like emojis, URLs, and numbers  
- Convert text into structured tokens  
- Perform token-level analysis  
- Build a reusable NLP preprocessing pipeline  

## ⚙️ Features

- Remove numbers from text  
- Convert text to lowercase  
- Remove URLs and email patterns  
- Handle repeated characters (soooo → soo)  
- Remove extra spaces  
- Remove very short tokens (≤2 characters except "no", "not")  
- Clean emojis and special characters  
- Tokenization and normalization  
- Frequency and statistical analysis  

## 📁 Project Structure

```
nlp-preprocessing-engine/
│
├── NLP_Preprocessing_Engine.ipynb   # Main notebook
├── README.md                        # Project documentation
├── requirements.txt                 # Dependencies (if any)
└── .gitignore                       # Ignored files
```

## 🧪 Sample Input
Get 100% FREE access now!!!
I absolutely looooved this product 😍😍
Worst service ever... 0/10
Visit https://openai.com now!
Nooooo this is baaad!!!
OK OK OK I got it
Win $$$ now!!! Limited offer!!!

## 🔧 Core Functions
1. Text Preprocessing
```
def preprocess_text(text):
    pass
```
Handles:  
- Cleaning text
- Removing noise
- Token generation


2. Full Pipeline
```
def full_pipeline(text_list):
    pass
```
Returns:
- Clean tokens
- Clean sentences

  
3. Token Analytics
- Total tokens
- Unique tokens
- Average token length

  
4. Frequency Analysis
- Top 10 most frequent words
- Top 5 least frequent words

## 📊 Output Example
Input:
```
I absolutely looooved this product 😍😍
```
Output:
```
Tokens: ['i', 'absolutely', 'loooved', 'this', 'product']
Clean Sentence: i absolutely loooved this product
```

## 🛠️ Tech Stack
Python 3  
Regular Expressions (re)  
Collections (Counter)  
Jupyter Notebook / Google Colab  

## 📌 Learning Outcomes
NLP text preprocessing techniques
Handling real-world noisy data
Tokenization and normalization
Building reusable pipelines
Basic text analytics
