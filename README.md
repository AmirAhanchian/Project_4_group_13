# Project 4 - Team 13

# Overview

The purpose of this analysis is to create a machine learning model which can determine whether an email is spam or not spam (ham) based on the contents (text) of the email. 

Using a sample of over 5,000 emails, we analyzed the data to determine how frequently each word appeared in the sample of emails. For words which appeared less than 50 times in the total sample, we removed these from the analysis as not highly representative or relevant. 

We implemented a TensorFlow and Keras model initially, then attempted to optimize the model by adding additional hidden layers and neurons and increasing the number of epochs. Then we ran the same dataset through other machine learning models to determine which model would provide the best results for our dataset. 

Source dataset: https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv

# Results

TensorFlow & Keras: 
* 'accuracy': 0.9420289993286133
* 'precision': 0.8589954972267151
* 'recall': 0.9429894089698792
* 'f1_score': 0.8901594877243042

TensorFlow & Keras Optimized with additional hidden layers and epochs: 
* 'accuracy': 0.9700483083724976
* 'precision': 0.9141188859939575
* 'recall': 0.9727393388748169
* 'f1_score': 0.9385428428649902

KNN: 
* 'accuracy': 0.8521739130434782
*  'precision': 0.8117335990190067
*  'recall': 0.8425263157894737
*  'f1_score': 0.8240165631469979

 SVM: 
* 'accuracy': 0.7951690821256039
*  'precision': 0.8001954056731864
*  'recall': 0.6530877192982456
*  'f1_score': 0.6739983121961656

Naive Bayes: 
* 'accuracy': 0.9458937198067633
* 'precision': 0.9217855203936884
* 'recall': 0.9507017543859648
* 'f1_score': 0.9345427933829044

 Decision Tree: 
* 'accuracy': 0.9304347826086956
* 'precision': 0.907299951306606
* 'recall': 0.9226315789473685
* 'f1_score': 0.914484012228373

Random Forest: 
* 'accuracy': 0.9681159420289855
* 'precision': 0.9587098393574297
* 'recall': 0.9616842105263157
* 'f1_score': 0.960182144393499

Logistic Regression: 
* 'accuracy': 0.966183574879227
* 'precision': 0.9515306122448979
* 'recall': 0.9657894736842105
* 'f1_score': 0.9583009583009583

# Summary

In the end, 

Presentation link: https://docs.google.com/presentation/d/1Ts_Mu0gXb1KT8fXRL4XLajtWNGITV1_NODrj53k0ews/edit?usp=sharing

