<h1 align="center">Skin Cancer Classification using Computer Aided Diagnosis</h1>

# Abstract

Skin cancer is a prevalent type of cancer worldwide, and early diagnosis is critical for effective treatment. Our system uses a deep learning model trained on a vast dataset of skin images to classify skin cancer into its different types.The system can be accessed through a user-friendly web interface, where users can upload skin images and receive a diagnosis in real-time. Our skin cancer classification system has the potential to improve early detection rates and enhance patient outcomes.After integrating in workflow Dermatologists and healthcare professionals can make more informed decisions about the diagnosis and treatment of skin lesions.

# Introduction

Skin cancer is a serious and growing health concern, affecting millions of people worldwide. Early detection and accurate diagnosis are crucial for improving patient outcomes, yet current diagnostic methods can be time-consuming and error-prone. This is where machine learning comes in - by leveraging large amounts of data and powerful algorithms, machine learning has the potential to revolutionize the field of skin cancer classification.

## The problem we tried to solve

_The first step to identify whether the skin lesion is malignant or benign for a dermatologist is to do a skin biopsy. In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. This project aims to shorten the current gap to just a couple of days by providing the predictive model using **Computer-Aided Diagnosis (CAD)**. The approach uses **Convolutional Neural Network (CNN)** to classify seven types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively._

## Motivation

A dermatologist will perform a skin biopsy to determine if the skin lesion is benign or malignant (cancerous).
The dermatologist removes a portion of the skin lesion during the skin biopsy and studies it under a microscope.
Obtaining a dermatologist appointment and receiving a biopsy report currently takes around a week or more.
The goal of this research is to use computer-aided diagnosis (CAD) to provide a prediction model that will reduce the present gap to a matter of days.
The method analyses photos of outlier lesions to classify nine different forms of skin cancer using convolutional neural networks (CNN). This gap closing has the potential to favourably affect millions of individuals.
We aim to reach a high level of accuracy and generalization on unseen data, which is an important factor for clinical adoption.

## Data Set

https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000


## Steps to run this Repository
1. Download the zip folder in your system / device.
2. Extract the folder and run it in an IDE (for eg: VS Code).
3. Open a new terminal and make sure your path is correct (....\skin-cancer-classification-main)
4. In the terminal write "npm install" or "npm i". 
5. After installing dependencies if there are any issues or vulnerablities then in the terminal write "npm audit fix --force". This should resolve any issues in dependencies.
6. Making sure the path is correct again, enter command "node index.js" in the terminal
7. The server will start and you can access the web interface by going to "http://localhost:3000"
8. Make sure you use "http", and not "https" for accessing the web as it may not function as intended.
9. You can upload images of skin lesions and get the classification result in real-time.
10. Also to assist the users we have included an FAQ section in the About Page of our website so that any common queries could be answered. 
11. Please use the page to assist yourself in using the website and how to get results by uploading images or skin lesions.

## library versions used

numpy==1.26.4        
pandas==1.5.3          
scikit-learn==1.6.0                 
tensorflow==your_version              
torch==2.5.1+cu118            
torchvision==0.20.1+cu118             
matplotlib==3.9.2              
scipy==1.10.1             
Pillow==9.5.0               
tqdm==4.66.6                  
joblib==1.2.0                   
streamlit==1.21.0                  
flask==2.2.2                     

These are some library versions used for the project.
For a full list of dependencies, refer to `requirements.txt`.