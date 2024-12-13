# Skin Disease Detection using CNN
Capstone Project | Bangkit Academy 2024  

## Overview
This project is part of the capstone requirements for Bangkit Academy's Machine Learning Path. Our team of three members has developed a machine learning model that utilizes Convolutional Neural Networks (CNN) to detect and classify skin diseases.  

The project aims to assist dermatologists and healthcare providers by offering a reliable automated solution for early detection of various skin conditions, thereby improving diagnosis efficiency and patient outcomes.  

---

## Team Members
1. Ferry Amaludin (M229B4KY1496) - Machine Learning
2. Nurul Najwa Sabilla (M496B4KX3452 ) -  Machine Learning
3. Tedy Hermawanto (M262B4KY4306) - Machine Learning 

---

## Problem Statement
Skin diseases affect millions of people worldwide, but early detection remains a challenge due to a lack of access to skilled dermatologists. Misdiagnosis or delayed diagnosis can lead to severe consequences for patients.  

This project addresses the problem by building a deep learning-based model that detects and classifies skin diseases using images. The solution is fast, efficient, and accessible, making it a valuable tool for healthcare.  

---

## Objectives
1. To develop a CNN model capable of classifying various skin diseases.  
2. To ensure high accuracy and reliability of predictions using transfer learning techniques.  
3. To create a user-friendly interface for uploading images and receiving diagnosis results.  

---

## Dataset
We used the ISIC Skin Disease Image Dataset [In this link](https://api.isic-archive.com/collections/65/) from ISIC, which contains labeled images of skin lesions. The dataset includes the following categories:  
- squamous cell carcinoma
- pigmented benign keratosis
- basal cell carcinoma
- melanoma
- seborrheic keratosis
- nevus
- actinic keratosis

Dataset size: ~2.5 GB  

---

## Methodology
1. Data Preprocessing:  
   - Image resizing and normalization.  
   - Augmentation to improve generalization.  

2. Model Development:  
   - A CNN-based architecture was developed and trained.  
   - We incorporated transfer learning using pre-trained models with MobileNet to enhance performance.  

3. Evaluation:  
   - Metrics such as accuracy, make with Hyperparameter tuning to get better model's performance.  
   - Confusion matrix and accuracy plots were visualized for further analysis.  

4. Deployment:  
   - The trained model was deployed in a web-based application for real-world usage.  
   - Users can upload skin images and receive predictions instantly.
   - Users can ask to chatbot for get answer about images detections.

---

## Technologies Used
- Programming Language: Python  
- Frameworks: TensorFlow, Keras  
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Sklearn, ISIC CLI.
- Deployment: Flask or FastAPI (backend),Kotlin for android applications

---

## How to Run the Project
1. Clone this repository.  
   ```bash
   git clone [https://github.com/epialert/machine-learning.git]
   ```  
   open the file github what's you clone with this link
2. Install required dependencies:  
   ```bash
   pip install isic-cli
   pip install Pandas
   pip install Matplotlib
   pip install TensorFlow
   ```  
3. Run the model application:  
   Run application model with .ipynb

4. Upload a skin image to the interface and view the prediction results.  

---

## Results
Our CNN model achieved the following performance on the test dataset:  
- Accuracy: better accuracy%

---

## Future Work
- Improve model accuracy by collecting and incorporating more diverse datasets.  
- Expand the model to detect additional skin diseases.  
- Integrate the solution with mobile applications for better accessibility.  

---

## Acknowledgments
We would like to thank Bangkit Academy 2024 for providing guidance and resources throughout this project. We also extend our gratitude to the ISIC Archive for the dataset used in this project.  

---

## License
This project is licensed under the capstone project.  

---
