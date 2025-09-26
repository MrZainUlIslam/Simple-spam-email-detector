# Spam Email Detector

A machine learning system that detects spam emails based on text content analysis.

## What This Project Does

This project analyzes email text content and predicts whether an email is spam or legitimate (ham). It's designed to help filter unwanted emails automatically.

## Features

- Cleans and preprocesses email text
- Trains a machine learning classification model  
- Tests accuracy on real email data
- Predicts spam/ham for new emails
- Shows prediction confidence scores

## Technologies Used

- Python - Main programming language
- Pandas - For handling data
- Scikit-learn - For machine learning
- Naive Bayes - The classification algorithm
- TF-IDF - For text vectorization

## How to Use

### Method 1: Jupyter Notebook (Recommended)
1. Download `spam_detection.ipynb` and `spam_dataset.csv`
2. Open the notebook in Jupyter
3. Make sure the CSV file is in the same folder
4. Run each cell step by step

### Method 2: Python Script
1. Copy the code into a Python file
2. Install required packages:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter nltk
