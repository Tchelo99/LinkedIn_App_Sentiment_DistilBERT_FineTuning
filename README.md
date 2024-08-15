# LinkedIn App Review Sentiment Analysis
## Overview
This repository contains two key components for analyzing sentiments expressed in LinkedIn app reviews. The project aims to evaluate user feedback by leveraging state-of-the-art NLP techniques to gain insights into user experiences and satisfaction levels.

## Files
### 1. LinkedIn App Reviews Sentiment Analysis: Exploratory Data Analysis
This file provides a comprehensive exploration of app reviews sentiment analysis, covering the following aspects:

#### Objective: Evaluate and understand the sentiments in user reviews of mobile applications. This analysis helps developers and businesses to prioritize feature updates and maintain a positive user community.

#### Process:

* Data Collection: Gather a dataset of app reviews.
* Data Preprocessing: Clean the dataset by retaining relevant columns, removing NaN values, and performing exploratory data analysis (EDA).
* Sentiment Labeling: Use tools like TextBlob or NLTK to label sentiments as Positive, Negative, or Neutral.
* Sentiment Distribution: Analyze the overall distribution of sentiments in the dataset.
* Sentiment vs. App Version: Explore the relationship between sentiments and the author app version.
* Text Analysis: Identify common themes or words in different sentiment categories.
### 2. LinkedIn_App_Review_Sentiment_Analysis_Large_Scale_Fine_Tuning_of_DistilBERT
This file focuses on the implementation of a sentiment analysis model using DistilBERT:

#### Objective: Develop a robust sentiment analysis model for LinkedIn app reviews using a dataset of 322,642 user reviews.

#### Approach:

* Model: Fine-tune DistilBERT, a lightweight transformer model, on the dataset.
* Data Handling: Implement a custom dataset class for efficient text data handling and use data loaders for batching.
* Training: Train the model with a linear learning rate schedule using PyTorch and the Hugging Face Transformers library.
* Evaluation: Assess model performance using standard classification metrics.
* Outcome: The fine-tuned model can accurately predict the sentiment of new LinkedIn app reviews, offering scalable insights into user feedback.
 
