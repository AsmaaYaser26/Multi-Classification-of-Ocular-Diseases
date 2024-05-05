# Multi-Classification-of-Ocular-Diseases
Multiclassification problem solved using deep learning.

## About the project 
This project aims to develop a highly accurate and reliable ocular disease multi-classification system using deep learning. The system will enable early treatment, prevent further damage to vision, and improve patient outcomes. 

## Problem Statement
According to a recent World Health Organization (WHO) report on vision, at least 2.2 billion individuals worldwide suffer from vision impairment. Chronic Ocular Diseases (COD) such as myopia, diabetic retinopathy, glaucoma, and cataract can affect the eye and may even lead to severe vision impairment or blindness. Furthermore, diagnosis of these diseases is time-consuming and vastly dependent on ophthalmologists' experience.

## Proposed Solution 
An easy, accurate, reliable and less time consuming multicalssification system based on deep learning approach and only one test which is fundus image aquiring . A funds image is submitted and then the result is returned if it is one of seven ocular diseases or normal fundus image.

### Work Flow
![image](https://github.com/AsmaaYaser26/Multi-Classification-of-Ocular-Diseases/blob/main/work%20flow.jpg)

## Description 
### data 
Used dataset called ODIR-5K from Kaggle : https://www.kaggle.com/datasets/tanjemahamed/odir5k-classification
Performed some data augmentation on the dataset so it becomed balanced : 
https://www.kaggle.com/datasets/asmaayaser/original-data-set-project

For training the model some preprocessing was done such as : rescaling and resizing. Then it is split to 80% training set 10% validation data and 10% test data.

### Model 
Depended on the priciple of transfer learning which used a pretrained model [ xception ] imported from keras and used to train the model over 20 epoch and used SGD optimizer and learning rate=0.01.

### Model Evaluation 
Used evaluation metrics : accuracy, confusion matrix, classification report 

### Saving the model 
Saved the trained model as h5 file.





