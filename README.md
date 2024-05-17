# Sentiment Analysis on Twitter Dataset

## Overview

This project is part of the internship program at Prodigy Infotech, focused on Natural Language Processing (NLP). It analyzes a Twitter sentiment dataset obtained from Kaggle. The dataset contains tweets along with their corresponding sentiment labels, providing an opportunity to explore and model the sentiment of tweets as positive, negative, or neutral.

## Table of Contents

- [Data Loading](#data-loading)
- [Data Exploration](#data-exploration)
- [Text Preprocessing](#text-preprocessing)
- [Sentiment Analysis Model](#sentiment-analysis-model)

## Data Loading

The project starts with loading necessary libraries and importing the dataset using pandas.

```python
import pandas as pd

# Loading the dataset
data = pd.read_csv('/kaggle/input/twitter-sentiment-dataset/train.csv')
