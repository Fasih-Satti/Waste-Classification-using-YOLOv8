# 🗑️ Waste Classification using YOLOv8

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-purple?style=for-the-badge&logo=pytorch&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An AI-powered waste classification system using **YOLOv8** and **Streamlit** for real-time object detection and automated recycling support. The system detects and classifies waste into multiple categories using computer vision and deep learning.

</div>

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Waste Categories](#️-waste-categories)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Installation & Setup](#️-installation--setup)
- [Dataset](#-dataset)

---

## 🚀 Project Overview

This project aims to automate waste management by classifying waste into different categories using a trained **YOLOv8** model. It provides a user-friendly **Streamlit** interface for real-time detection using images, videos, or live camera feed.

> ♻️ Helping make recycling smarter, faster, and more accurate with deep learning.

---

## 🧠 Features

| Feature | Description |
|---|---|
| 🎯 Real-time Detection | Waste detection powered by YOLOv8 |
| 🖥️ Web Interface | Easy-to-use Streamlit dashboard |
| 📷 Multiple Inputs | Supports image, video, and webcam |
| 🏷️ Multi-class | Detects several waste categories |
| 🔬 Deep Learning | High accuracy object detection |

---

## ♻️ Waste Categories

The model can classify the following types of waste:

| # | Category | Description |
|---|---|---|
| 1 | 🧴 Plastic | Bottles, bags, containers |
| 2 | 🫙 Glass | Bottles, jars, broken glass |
| 3 | 🥫 Metal | Cans, foil, scrap metal |
| 4 | 📄 Paper | Newspapers, office paper |
| 5 | 📦 Cardboard | Boxes, packaging material |
| 6 | 🍃 Biodegradable | Food waste, organic matter |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.8+ | Core programming language |
| YOLOv8 (Ultralytics) | Object detection model |
| Streamlit | Web application interface |
| OpenCV | Image & video processing |
| PyTorch | Deep learning framework |

---

## 📁 Project Structure

```
Waste-Classification-using-YOLOv8/
│
├── results/                               # Output images after detection
│
├── streamlit-detection-tracking-app/
│   ├── app.py                             # Main Streamlit application
│   ├── helper.py                          # Helper/utility functions
│   ├── settings.py                        # App configurations & constants
│   └── weights/                           # Trained YOLOv8 model weights
│       └── best.pt
│
├── waste_YOLOv8.ipynb                     # Model training notebook
├── requirements.txt                       # Python dependencies
└── README.md
```

---

## ▶️ Installation & Setup

### Prerequisites

- Python 3.8 or higher
- pip package manager
- Webcam *(optional, for live detection)*

### 1. Clone the Repository

```bash
git clone https://github.com/Fasih-Satti/Waste-Classification-using-YOLOv8.git
cd Waste-Classification-using-YOLOv8
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Navigate to the App Directory

```bash
cd streamlit-detection-tracking-app
```

### 4. Run the Streamlit App

```bash
streamlit run app.py
```

> The app will open automatically in your browser at `http://localhost:8501`

---

## 📊 Dataset

The dataset was collected from **[Roboflow](https://roboflow.com/)** and contains:

- 📸 **6,000+** labeled images
- 🏷️ Bounding box annotations for all waste categories
- 🔀 Pre-split into train / validation / test sets

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open a [pull request](https://github.com/Fasih-Satti/Waste-Classification-using-YOLOv8/pulls) or submit an [issue](https://github.com/Fasih-Satti/Waste-Classification-using-YOLOv8/issues).

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">
Made with ❤️ by <a href="https://github.com/Fasih-Satti">Fasih Satti</a>
</div>
