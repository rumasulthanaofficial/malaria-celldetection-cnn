# malaria-celldetection-cnn
# 🦠 Malaria Cell Detection Using CNN

This project is a machine learning-based web application that uses **Convolutional Neural Networks (CNNs)** to detect **malaria-infected blood cells** from microscope images. Built using Python, TensorFlow, and deployed with **Streamlit**, the application provides a fast, accurate, and user-friendly interface to assist in early malaria diagnosis.

---

## 📌 Features

- Upload blood cell images (JPG/PNG)
- Predict whether the cell is **Parasitized (infected)** or **Uninfected (healthy)**
- Streamlit-based web interface
- Model trained on real-world dataset from Kaggle
- Achieved **92.4% accuracy**

---

## 📊 Dataset

- Source: Kaggle Malaria Cell Images Dataset
- Contains two classes:
  - `Parasitized`: Malaria-infected cell images
  - `Uninfected`: Healthy cell images

---

## 🧹 Data Preparation

- **Preprocessing**: Image resizing, normalization, brightness/contrast adjustments
- **Labeling**: Parasitized vs Uninfected
- **Splitting**:
  - 89% training
  - 11% testing
- **Balancing**: Equal number of infected and healthy images to prevent model bias

---

## 🧠 Model Architecture

- Implemented using **CNN (Convolutional Neural Networks)**
- Techniques used:
  - **Data Augmentation**
  - **Normalization**
  - **Validation Split (20%)**
- Built using **TensorFlow** and **Keras**

---

## 📈 Evaluation Metrics

- **Accuracy**: 92.4%
- **Loss**: 0.205
- **Precision**: 97% for infected cells
- **Recall**: 92% for infected cells, 97% for healthy cells
- **F1-Score**: Balanced precision and recall

---

## 🌐 Deployment

- **Framework**: Streamlit
- **Usage**:
  1. Upload an image (JPG or PNG)
  2. App processes it through the trained model
  3. Outputs prediction (Infected/Healthy) and confidence score

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Streamlit**
- **Matplotlib, NumPy, Pandas**
- **Scikit-learn**
- **Kaggle Dataset**

---

## 🚀 How to Run Locally

streamlit run app.py
