SMS Spam Detection Project:
This project aims to develop a text classification model to differentiate between legitimate (ham) and spam messages in SMS data. We will utilize machine learning techniques to build and evaluate several models based on a dataset of SMS messages labeled as either "ham" (legitimate) or "spam".

Dataset Details
Dataset Name: SMS Spam Collection
Source: Messages are sourced from various datasets including the Grumbletext Web site, NUS SMS Corpus, Caroline Tag’s PhD Thesis, and SMS Spam Corpus v.0.1 Big.
Number of Instances: 5,573 SMS messages
Columns:
v1: Label indicating whether the message is "ham" or "spam".
v2: Raw text content of the SMS messages.
Project Tasks
Data Analysis:

Explore and visualize the dataset to understand its distribution and characteristics.
Preprocess the text data by cleaning, tokenizing, and vectorizing it for machine learning models.
Model Building:

Implement various text classification models such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM).
Train and evaluate each model using appropriate performance metrics.
Performance Evaluation:

Compare the performance of models based on metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
Select the best-performing model for detecting SMS spam.
Recommendations:

Provide insights and recommendations based on the evaluation results.
Discuss potential improvements or future work for enhancing the spam detection system.
Setup Instructions
To reproduce the project, follow these steps:

Ensure you have Python 3.x installed along with pip.
Install necessary Python packages:
pip install -r requirements.txt
Run the Jupyter Notebook:

Launch Jupyter Notebook to view and execute the project:

jupyter notebook
Open SMS_Spam_Detection.ipynb and run each cell sequentially to perform data analysis, build models, and evaluate their performance.
Explore the Results:

Review the final model selection, evaluation metrics, and conclusions within the notebook.
Customize or extend the project as needed for further experimentation or improvements.
