# Multi-Class Classification-of-Ocular-Diseases
Multiclassification problem solved using deep learning.

## Introduction
According to a recent World Health Organization (WHO) report on vision, Chronic Ocular Diseases (COD) such as:
*Myopia
*Diabetic retinopathy
*Glaucoma
*Cataract
*AMD
*Hypertension
*Other diseases
can affect the eye and may even lead to severe vision impairment or blindness. Furthermore, diagnosis of these diseases is time-consuming and vastly dependent on ophthalmologists' experience.This project aims to develop a highly accurate and reliable ocular disease multi-classification system using deep learning. The system will enable early treatment, prevent further damage to vision, and improve patient outcomes using fundus image. The patient's funds image is submitted and then it is classified into one of the seven ocular diseases or normal fundus image.

### Work Flow
![image](https://github.com/AsmaaYaser26/Multi-Classification-of-Ocular-Diseases/blob/main/work%20flow.jpg)

## Description 
### data 
Used dataset called ODIR-5K from Kaggle : https://www.kaggle.com/datasets/tanjemahamed/odir5k-classification
Performed some data augmentation on the dataset: 
https://www.kaggle.com/datasets/asmaayaser/original-data-set-project
For training the model some preprocessing was done such as : rescaling and resizing. Then it is split to 80% training set 10% validation data and 10% test data.

### Model 
Depended on the priciple of transfer learning which used a pretrained model [ xception ] imported from keras and used to train the model over 20 epoch and used SGD optimizer and learning rate=0.01.

### Model Evaluation 
Used evaluation metrics : accuracy, confusion matrix, classification report
The acheived accuracy was 97%

### Saving the model 
Saved the trained model as h5 file.





