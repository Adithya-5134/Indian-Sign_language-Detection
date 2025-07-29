# 🤟 Indian Sign Language Recognition using Deep Learning 📷

## 📌 **Project Overview**
Welcome to the **Indian Sign Language Recognition** project! This deep learning-based system classifies hand gestures into corresponding Indian Sign Language alphabets. It is designed to support communication for the hearing and speech impaired.

## 📂 **Dataset Information**

📄 **Dataset Source:** Custom Indian Sign Language image dataset  
🧷 **Classes:** Multiple gesture classes representing sign language alphabets

## 🖼️ **Image Features**

Each image captures a hand gesture representing a specific alphabet. The model learns visual features such as:
- Finger position and orientation  
- Hand contour and shape  
- Background contrast and lighting variations

## 🔍 **Model Implementation**

📜 **File:** PRAICP_1000_IndiSignLang.ipynb

🛠️ **Steps Followed:**
- 🧹 **Data Preprocessing** – Resizing, normalization, grayscale conversion
- 📊 **EDA (Exploratory Data Analysis)** – Visualizing class samples and distributions
- 🧠 **Model Building** – Custom CNN architecture for multi-class classification
- 🎯 **Model Evaluation** – Accuracy metrics, loss visualization
- 🖐️ **Prediction** – Classifying unseen hand gestures in real time or from uploaded images

## 🤖 **Deep Learning Architecture**

- 📦 Convolutional Layers for feature extraction
- 🌀 Max Pooling for spatial reduction
- 🔁 Flatten + Dense Layers for classification
- 💧 Dropout for regularization
- 🧠 Softmax Activation for multi-class output

## 📉 **Metrics Used**

- 📌 Training & Validation Accuracy
- 📌 Training & Validation Loss
- 📌 Confusion Matrix
- 📌 Classification Report (Precision, Recall, F1-Score)

## 🧪 **Technologies Used**

- TensorFlow / Keras
- NumPy & Pandas
- OpenCV
- Matplotlib & Seaborn
- Jupyter Notebook

## 🔑 **Key Insights**

- 🤖 CNN successfully distinguishes between multiple hand gestures.
- 📈 The model shows strong generalization with minimal overfitting.
- 🧪 Effective preprocessing and augmentation improved robustness.

## 🎯 **Conclusion**

This project showcases how deep learning can bridge communication gaps using computer vision. The system can be further enhanced and deployed in educational or assistive tools to support sign language understanding in real-time applications.

---
