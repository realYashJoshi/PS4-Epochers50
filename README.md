**EPOCHERS 50 PS4**

**Project Title**
Question Answering with XGBoost and DistilBERT

**Description**
This project combines traditional machine learning with state-of-the-art natural language processing (NLP) techniques to answer questions from a given context. I used an XGBoost classifier to predict whether a question can be answered from a provided paragraph and utilized the DistilBERT model for question answering when possible.

**Table of Contents**
Usage
Data Preprocessing
Training
Question Answering Model
Results
Contributing
Acknowledgments

**Usage**
To use this project:

Preprocess your data using the provided scripts if necessary.

Train the XGBoost model by running the training script.

Use the trained model to predict whether a question can be answered from a given paragraph.

If the XGBoost prediction is 'Yes', use the DistilBERT-based question answering model to extract the answer.

View the results in the generated CSV file.

**Data Preprocessing**
Data preprocessing involves cleaning and transforming our data to prepare it for training and testing. In this project, I performed text preprocessing, such as lowercasing and removing special characters.

**Training**
Training the XGBoost model involves specifying hyperparameters, splitting the dataset, and fitting the model to our training data.

**Question Answering Model**
The DistilBERT-based question answering model is responsible for extracting answers from a given paragraph. It uses a Bert tokenizer for processing input.

**Results**
The results of predictions are stored in a CSV file with the following fields:

Question
Paragraph
Answer_start (Start index of the answer within the paragraph)
Answer_text (The extracted answer)

**Acknowledgments**
I'd like to acknowledge the following sources and libraries that contributed to this project:
XGBoost for the traditional machine learning classifier.
Transfer Learning via  DistilBERT model and tokenizer.
Dataset provided as a part of problem statement i.e training data.csv
**Team Members**
1.Harsh Mahire
2.Yash Joshi
3.Priyansh Verma
4.Varad Dahake
5.Rajeev Shete

