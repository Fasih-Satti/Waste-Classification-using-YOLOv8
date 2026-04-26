# Waste Classification using YOLOv8

An AI-powered waste classification system using **YOLOv8** and **Streamlit** for real-time object detection and automated recycling support. The system detects and classifies waste into multiple categories using computer vision and deep learning.

---

## 🚀 Project Overview

This project aims to automate waste management by classifying waste into different categories using a trained YOLOv8 model. It provides a user-friendly Streamlit interface for real-time detection using images, videos, or live camera feed.

---

## 🧠 Features

- Real-time waste detection using YOLOv8  
- Streamlit web interface for easy interaction  
- Supports image, video, and webcam input  
- Detects multiple waste categories  
- High accuracy object detection using deep learning  

---

## ♻️ Waste Categories

The model can classify the following types of waste:

- Plastic  
- Glass  
- Metal  
- Paper  
- Cardboard  
- Biodegradable  

---

## 🛠️ Tech Stack

- Python  
- YOLOv8 (Ultralytics)  
- Streamlit  
- OpenCV  
- PyTorch  

---

## 📁 Project Structure
Waste-Classification-using-YOLOv8/
│
├── results/                          # Output images
├── streamlit-detection-tracking-app/
│   ├── app.py                        # Main Streamlit app
│   ├── helper.py                     # Helper functions
│   ├── settings.py                   # Configurations
│   └── weights/                      # YOLOv8 trained models
│
├── waste_YOLOv8.ipynb                # Training notebook
└── README.md

## ▶️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/Fasih-Satti/Waste-Classification-using-YOLOv8.git
cd Waste-Classification-using-YOLOv8
2. Install dependencies
pip install -r requirements.txt
3. Run Streamlit app
streamlit run app.py
📊 Dataset

The dataset is collected from Roboflow and contains over 6000 labeled images with bounding boxes for different waste categories.
