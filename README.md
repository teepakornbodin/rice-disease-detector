# 🌾 Doctor Rice

AI-powered rice leaf disease detection web application  
Mini Project for **EN811300 - Fundamental of Computer Programming**

## 📌 About The Project

Doctor Rice is a web application that helps identify rice leaf diseases using Artificial Intelligence.

Rice leaf diseases often have very similar symptoms, making them difficult to diagnose without agricultural expertise. This project aims to assist farmers by providing a fast and accurate disease detection system through image classification.

---

## 🎯 Problem Statement

Rice farmers often struggle to correctly identify leaf diseases.

As a result:

- Incorrect treatment may be applied
- Unnecessary chemical use increases
- Crop damage may worsen
- Production loss can occur

Doctor Rice was developed to solve this problem using machine learning.

---

## 💡 Solution

This system allows users to:

1. Upload an image of a rice leaf
2. Let the AI model analyze the image
3. Predict the disease type
4. Display the result instantly on the website

---

## 🛠 Technologies Used

### Dataset Preparation
- Google Dataset Sources
- Roboflow

### Machine Learning
- TensorFlow
- Python

Training Configuration:
- Image Size: **150 x 150 x 3**
- Batch Size: **64**
- Epochs: **14**

### Web Development
- Flask
- HTML
- CSS
- JavaScript

---

## 📂 Project Structure

```bash
DoctorRice/
│
├── app.py
├── model.h5
│
├── templates/
│   ├── base.html
│   └── index.html
│
├── static/
│   ├── main.css
│   └── main.js
│
└── README.md
```

---

## ⚙ How It Works

### 1. Dataset Collection
Collected rice leaf disease images from online sources.

### 2. Data Labeling
Used Roboflow to:

- Label disease regions
- Classify disease categories

### 3. Model Training
Trained an AI model using TensorFlow.

### 4. Flask Integration
Connected the trained `.h5` model to Flask backend.

### 5. Prediction
Uploaded image is processed and predicted by the AI model.

### 6. Result Display
Prediction result is sent to frontend and displayed on the webpage.

---

## 🚀 Features

✅ Upload rice leaf images  
✅ AI disease prediction  
✅ Fast result display  
✅ Simple web interface

---

## 🌱 Benefits

- Helps farmers identify diseases faster
- Reduces incorrect chemical usage
- Improves crop management
- Supports smarter agriculture

---

## 🎥 Demo

YouTube Demo:  
https://youtu.be/BbOewtC8EXk

---

## 👨‍💻 Developer

**Teepakornbodin Intasoy**  
Student ID: 663040116-9

Khon Kaen University  
Computer Engineering

---

## 📖 Course Information

Mini Project for:

**EN811300 - Fundamental of Computer Programming**

---

## 🙏 Acknowledgements

Special thanks to:

- Khon Kaen University
- TensorFlow
- Roboflow
- Open-source dataset providers

---

## ⭐ Future Improvements

- Improve model accuracy
- Support more rice diseases
- Mobile-friendly interface
- Deploy online for public access
