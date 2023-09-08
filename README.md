# SentimentalAnalysis
# Analyzing User Sentiments and Performance of Threads: An Instagram App Reviews Study
This project demonstrates sentiment analysis using a Support Vector Machine ,TF-IDF vectorizer model to classify text data into three categories: positive, negative, or neutral. The application is deployed using Streamlit Cloud and can also be run on a local host server.

## Table of Contents

- [Demo](#demo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Model and Data](#model-and-data)


## Demo

You can access the live demo of this sentiment analysis tool at https://sentimentalanalysis-eflxk4fvn6jiwfkkq6lhrt.streamlit.app/ or by running it locally on your machine.

## Getting Started

### Prerequisites

Before you begin, make sure you have the following dependencies installed:
- Python (>= 3.6)
- Streamlit
- scikit-learn
- pickle
- spaCy
- nltk

You can install these packages using pip
## Installation
Clone this repository to your local machine:
### In bash
git clone https://github.com/HarithaBangaru/SentimentalAnalysis.git
cd sentiment-analysis

## Usage
To run the sentiment analysis tool locally, execute the following command:
### streamlit run deployment.py
This will start the Streamlit app on your local host, and you can access it via your web browser at http://localhost:8501.
## Model and Data
The sentiment analysis model **(svm_model.pkl)** was trained using scikit-learn on a labeled dataset of text data. The **TF-IDF vectorizer (tfidf_vectorizer.pkl)** was used to convert text data into numerical features.
## Deployment
The application is deployed using Streamlit Cloud and can be accessed here
link : https://sentimentalanalysis-eflxk4fvn6jiwfkkq6lhrt.streamlit.app/

## Technology Stack
- Python
- NLP
- WordCloud
- Synthetic Minority Over-sampling Technique
- Streamlit
- SVC
- TF-IDF vectorizer
- DecisionTreeClassifier
- RandomForestClassifier
- AdaBoostClassifier
