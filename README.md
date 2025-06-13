# Identifying-Entities-in-Healthcare-Data

You are well versed with the multiple text processing and syntactic processing steps such as those given below:

Lexical processing
Regular expressions
Text cleaning steps
Feature creation using the Bag-of-Words model and TF-IDF
Model building
Syntactic processing
PoS tagging
Parsing
NER
Custom NER and CRF
You have learnt how these techniques can be used to solve basic Natural Language Processing-related problems in the previous modules. Now, it is time to put this understanding to test. 

 

In industry, Name Entity Recognition or NER has many dynamic applications such as:

Search engines like Google
Question answering systems like chatbot
Medical and healthcare domain
Text summarisation

This assignment is meant to enhance your knowledge on NER. Here, you will understand the application of NER in healthcare.


# Problem Statement

There are four datasets provided to you to process, which are as follows:

train_sent
test_sent
train_label
test_label
You have the train and the test datasets; the train dataset is used to train the CRF model, and the test dataset is used to evaluate the built model.
![image](https://github.com/user-attachments/assets/934903c5-07bd-4e3b-aa37-8bce66712f95)

![image](https://github.com/user-attachments/assets/f52b830b-f819-4e08-b498-7f5480c284de)

In this assignment, you need to perform the following broad steps:

You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
After that, you need to define the features to build the CRF model.
Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
Once the features are computed, you need to define the target variable and then build the CRF model.
Then, you need to perform the evaluation using a test data set.
After that, you need to create a dictionary in which diseases are keys and treatments are values.

# Expected Tasks
There are eight major tasks that you need to perform to complete the assignment. They are as follows:

Data preprocessing
Concept identification
Defining the features for CRF
Getting the features words and sentences
Defining input and target variables
Building the model
Evaluating the model
Identifying the diseases and predicted treatment using a custom NER


