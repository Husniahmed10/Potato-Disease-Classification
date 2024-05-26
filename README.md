# Potato-Disease-Classification

## Overview

This project leverages machine learning and deep learning techniques to classify potato leaves into three categories: Late Blight, Early Blight, and Healthy. By analyzing images of potato leaves, the model predicts the disease type and provides a confidence level for its prediction. The application consists of a backend powered by FastAPI, a frontend built with React.js, and a TensorFlow model for image classification.

## Features

### Image Classification:
Upload a leaf photo and get an instant prediction of its health status.

### Disease Categories:
 Late Blight  
 Early Blight  
 Healthy  
 
### Confidence Level: 
Get a confidence score for each prediction to understand the model's certainty.

### Interactive UI: 
User-friendly interface for uploading images and viewing results.

### RESTful API: 
Backend service using FastAPI to handle requests and serve predictions.

## Technologies Used
Frontend: React.js   
Backend: FastAPI  
Machine Learning Framework: TensorFlow, Keras  
Programming Language: Python

## Model Training
The model is trained using TensorFlow on a dataset of potato leaf images. The dataset is split into training and validation sets. Various image augmentation techniques are used to enhance the model's performance.  
Dataset Link: https://www.kaggle.com/datasets/arjuntejaswi/plant-village

## Usage

### Access the Frontend:

Open your web browser and navigate to http://localhost:3000.  

Upload an Image:  
Click on the upload button and select a leaf photo.  

View Predictions:  
The application will display the predicted disease type along with the confidence level.  

![Screenshot 2024-05-25 203037](https://github.com/Husniahmed10/Potato-Disease-Classification/assets/141121519/76185cc8-8c3b-427c-bcf3-9a9a4c965701)  
![Screenshot 2024-05-25 203852](https://github.com/Husniahmed10/Potato-Disease-Classification/assets/141121519/c263b53d-3633-4544-95ce-614e1d292b64)  
![Screenshot 2024-05-25 203918](https://github.com/Husniahmed10/Potato-Disease-Classification/assets/141121519/a96bef5b-6aed-4061-bf5b-7d2ba46c888a)   
![Screenshot 2024-05-25 203944](https://github.com/Husniahmed10/Potato-Disease-Classification/assets/141121519/4fe7c17e-c84d-4944-a3f6-f9c01f64d755)





