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
Programming Language: Python, HTML, CSS, JavaScript  

## Model Training
The model is trained using TensorFlow on a dataset of potato leaf images. The dataset is split into training and validation sets. Various image augmentation techniques are used to enhance the model's performance.

## Usage

### Access the Frontend:

Open your web browser and navigate to http://localhost:3000.  

Upload an Image:  
Click on the upload button and select a leaf photo.  

View Predictions:  
The application will display the predicted disease type along with the confidence level.
