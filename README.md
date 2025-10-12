# AI Resume Screening Project

An automated resume classification system that uses Natural Language Processing (NLP) and Machine Learning to categorize resumes into different job domains, streamlining the recruitment process.

## Project Overview

This project implements a machine learning solution to automatically classify resumes into predefined job categories such as Data Science, Software Engineering, HR, Testing, and more. The system helps recruiters quickly identify candidate specializations and improve hiring efficiency.

## Features

- **Text Preprocessing**: Automated cleaning and processing of resume text data
- **TF-IDF Vectorization**: Converts textual resumes into numerical features
- **Multi-class Classification**: Predicts job categories using Logistic Regression
- **Data Visualization**: Interactive visualizations of word distributions and category patterns
- **Custom Prediction**: Ability to input new resume text and receive instant classification

## Technical Stack

- **Programming Language**: Python
- **Data Processing**: pandas, numpy
- **Machine Learning**: scikit-learn
- **Natural Language Processing**: nltk
- **Data Visualization**: seaborn, matplotlib, wordcloud
- **Dataset**: Resume Dataset from Kaggle

## Dataset

The project uses the [Resume Dataset](https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset) by Snehaanbhawal from Kaggle, containing labeled resumes across multiple job categories.

## Model Performance

- **Algorithm**: Logistic Regression
- **Accuracy**: 95% on test data
- **Preprocessing**: Comprehensive text cleaning and TF-IDF vectorization
- **Evaluation**: Cross-validation and classification metrics


