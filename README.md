# Sentiment Analysis

A machine learning project to analyze the sentiment of Amazon Fine Food Reviews. This project leverages the Kaggle dataset and provides a Jupyter notebook to preprocess, train, and evaluate sentiment analysis models.

## Features

- Dataset: Amazon Fine Food Reviews from Kaggle (https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews?resource=download)
- Exploratory Data Analysis (EDA)
- Text preprocessing and cleaning
- Sentiment classification model
- Visualization of insights

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Project Structure](#project-structure)

## Introduction

Sentiment analysis helps identify the emotional tone behind text, such as customer reviews. This project utilizes the "Amazon Fine Food Reviews" dataset from Kaggle to classify reviews as positive, negative, or neutral.

## Installation

1. Clone this repository:
   
   ```bash
   git clone https://github.com/45Aditya/Sentiment-Analysis.git
   cd sentiment-analysis
3. Download the dataset from Kaggle:
- Visit the dataset page: Amazon Fine Food Reviews.
- Extract the downloaded .zip file.
- Place the Reviews.csv file in the following directory structure:
  
  ```bash
  ./input/amazon-fine-food-reviews/Reviews.csv

 ## Project Structure

 ```bash
    sentiment-analysis/
    ├── input/
    │   └── amazon-fine-food-reviews/
    │       └── Reviews.csv         # The dataset file
    |__ sentiment-analysis.ipynb    # Jupyter notebook for analysis
