# Spam_Filtering using Machine Learning

This project aims to classify emails as spam or ham (non-spam) using Natural Language Processing (NLP) techniques and machine learning algorithms. The goal is to build a robust model that can accurately identify spam emails to improve email filtering systems.

##Table of contents
-Introduction(#introduction)
-Dataset(#dataset)
-Data Preprocessing(#data-preprocessing)
-Model Architecture(#model-architecutre)
-Training(#training)
-Evaluation(#evaluation)
-Results(#results)
-Conclusion(#conclusion)

##Dataset
The dataset used for this project contains various features like 
-v1
-v2
-unnamed2
-unnamed3
-unnamed4
You can find the dataset in spam.csv file

##Data Preprocessing
-**Corpus** : Assigning training data as a corpus
-**Vectorizer** : Applied Count vectorizer on corpus
-**Label Encoder** : Applied Label Encoder on test data

##Model Architecture
-**Logistic Model** : Used logistic regression
-**Multinomial Naive Bayes** : Used Multinomial NB which is much simpler & efficient than Logistic Regression
-**Support Vector Machine** : Effective for higher dimensional spaces.Used SVC

##Training
-**Test size** : 20% of data id used for testing
-**Randome state** : 42

##Evaluation
-**Metrics** :  Evaluated the model using Accuracy, Precision, Recall, F1-Score and Confusion matrix

##Results
-**Logistic Regression** 
-Accuracy : 97%
-Precision : 100%
-Recall : 84%
-F1-score : 91%

-**Multinomial Naive Bayes**
-Accuracy : 97%
-Precision : 91%
-Recall : 93%
-F1-score : 92%

-**Support Vector Machine**
-Accuracy : 97%
-Precision : 100
-Recall : 84%
-F1-score : 91%

##Conclusion
Using Multinomial Naive Bayes is much more efficient than the rest of the two models i.e Logistic Regression Model,Support Vector Machine Model
