# 🐾 Dog vs Cat Image Classification using SVM

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![scikit-learn](https://img.shields.io/badge/scikit--learn-SVM-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview

This project is a Machine Learning-powered web application that classifies images as either **Dog 🐶** or **Cat 🐱** using a **Support Vector Machine (SVM)** classifier.

Developed during my **Machine Learning Internship at SkillCraft Technology**, this project demonstrates the complete ML workflow including data preprocessing, feature extraction, model training, evaluation, model persistence, and deployment through an interactive Streamlit interface.

The application allows users to upload an image and instantly receive a prediction along with confidence scores.

---

## ✨ Key Features

### 🧠 Machine Learning Classification

* Binary image classification using Support Vector Machine (SVM)
* RBF Kernel for handling non-linear decision boundaries
* Probability estimation for confidence scoring

### ⚙️ Data Preprocessing Pipeline

* Image resizing to fixed dimensions
* Grayscale conversion
* Feature vector generation
* Data normalization using StandardScaler

### 📊 Model Evaluation

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

### 🌐 Interactive Web Application

* Built using Streamlit
* Image upload functionality
* Real-time predictions
* Confidence visualization
* User-friendly interface

### 💾 Model Persistence

* Trained model saved using Pickle
* Fast loading during deployment
* Reusable prediction pipeline

---

## 🛠️ Tech Stack

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| Python       | Core Programming Language |
| scikit-learn | SVM Model Training        |
| OpenCV       | Image Processing          |
| NumPy        | Numerical Computation     |
| Pandas       | Data Handling             |
| Matplotlib   | Data Visualization        |
| Seaborn      | Evaluation Charts         |
| Streamlit    | Web Application           |
| Pickle       | Model Serialization       |

---

## 📂 Project Structure

```text
Dog-vs-Cat-Classifier-ML-Project/
│
├── app.py
├── train_model.py
├── model.pkl
├── metrics.json
├── requirements.txt
├── README.md
│
├── dataset/
   ├── cats/
   └── dogs/

---

## 🔄 Workflow

### Step 1: Image Preprocessing

```text
Input Image
      ↓
Grayscale Conversion
      ↓
Resize (64 × 64)
      ↓
Flatten
      ↓
Feature Vector
      ↓
StandardScaler
```

### Step 2: Model Training

```text
Processed Features
         ↓
Support Vector Machine (SVM)
         ↓
Model Training
         ↓
Evaluation
         ↓
Model Saving (.pkl)
```

### Step 3: Prediction

```text
Upload Image
      ↓
Preprocessing
      ↓
Loaded Model
      ↓
Dog / Cat Prediction
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Dog-vs-Cat-Classifier-ML-Project.git
cd Dog-vs-Cat-Classifier-ML-Project
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Train the Model

```bash
python train_model.py
```

### Launch Streamlit Application

```bash
streamlit run app.py
```

---

## 📈 Model Evaluation Metrics

The trained model is evaluated using multiple performance metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

Performance improves with larger datasets and proper hyperparameter tuning.

---

## 📸 Sample Output

### Upload Image

User uploads a Dog or Cat image.

### Prediction

```text
Prediction: Dog 🐶
Confidence: 91.4%
```

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

* Machine Learning Model Development
* Image Classification
* Data Preprocessing
* Feature Engineering
* Model Evaluation
* Streamlit Deployment
* Building End-to-End ML Applications
* GitHub Project Documentation

---

## 🚀 Future Enhancements

* CNN-based Deep Learning Model
* Transfer Learning (ResNet, VGG16)
* Hyperparameter Optimization
* Cross Validation
* Real-Time Webcam Prediction
* Docker Deployment
* FastAPI Integration
* Multi-Class Image Classification

---

## 🙏 Acknowledgements

* SkillCraft Technology
* Kaggle Dogs vs Cats Dataset
* scikit-learn Documentation
* Streamlit Community

---

## 👩‍💻 Author

### Akshita Dhiman

Machine Learning & AI Enthusiast

Passionate about building intelligent systems using Machine Learning, Deep Learning, and Data Science.

⭐ If you found this project useful, consider giving it a star.


