# 🌿 Plant Disease Detection System for Sustainable Agriculture

A deep learning–powered web application that detects and classifies plant diseases from leaf images to assist farmers and agriculturists in taking timely action.
## 🚀 Live Demo

🔗 [Click here to view the hosted app](https://plant-disease-detection-v.streamlit.app/)

---

## 🚀 Demo
Upload a leaf image to identify diseases in crops like Tomato, Apple, Grape, and more. The system uses a trained CNN model to predict one of 38+ plant disease classes with high accuracy.

## 🧠 Features
- Built with **TensorFlow/Keras** for image classification.
- Real-time **disease prediction** via **Streamlit web app**.
- Supports over **38 plant disease categories**.
- Intuitive user interface with image previews and predictions.
- Supports **sustainable agriculture** by enabling early intervention.

## 🛠️ Technologies Used
- Python, TensorFlow, Keras, OpenCV
- Streamlit (for UI)
- Numpy, Pandas, Seaborn, Matplotlib
- Scikit-learn

## 🧪 How It Works
1. Users upload a leaf image via the Streamlit app.
2. The image is resized and preprocessed using OpenCV.
3. The trained CNN model (`trained_plant_disease_model.keras`) processes the image.
4. The model returns the predicted class (e.g., Tomato___Leaf_Mold).
5. The result is displayed on the UI along with the uploaded image.

## 📊 Dataset
This project uses the [Dataset](), which contains over 50,000 labeled images of healthy and diseased plant leaves across 38 categories.
## ⚙️ How to Run Locally

```bash
git clone https://github.com/yourusername/plantdisease.git
cd plantdisease
pip install -r requirements.txt
streamlit run main.py
