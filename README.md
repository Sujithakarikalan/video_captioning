# Deep Learning-Based CCTV Video Captioning for Intelligent Surveillance

## 📌 Overview

This project aims to develop an intelligent deep learning-based surveillance system that automatically analyzes CCTV videos and generates meaningful textual descriptions of the events occurring in the scene.

The proposed system reduces manual monitoring by detecting important objects, understanding the visual scene, and generating natural language captions for surveillance videos.

---

## 🚀 Current Progress

✔ Literature Survey Completed

✔ Research Gap Identified

✔ Methodology Designed





---

## 🎯 Problem Statement

Traditional CCTV surveillance systems continuously record large amounts of video data, making manual monitoring difficult and time-consuming. Existing systems mainly detect objects but do not provide meaningful textual descriptions of surveillance events.

This project proposes an intelligent deep learning-based solution to automatically analyze CCTV videos and generate descriptive captions for efficient surveillance.

---

## 🛠 Technologies Used

- Python
- OpenCV
- PyTorch
- Ultralytics YOLOv8
- NumPy
- Pandas
- Google Colab
- Git
- GitHub

---

## 🤖 Deep Learning Models

### Module 1 (Completed)

**YOLOv8**

Purpose:
- Object Detection


### Future Modules

- Feature Extraction
- Caption Generation Model
- Performance Evaluation

---

## 📂 Dataset

### Current Dataset

**VisDrone2019-DET**

Used for training the YOLOv8 object detection model.

Classes:

- Pedestrian
- People
- Bicycle
- Car
- Van
- Truck
- Tricycle
- Awning-Tricycle
- Bus
- Motorcycle

---

## ⚙️ Proposed Workflow

CCTV Video

↓

Frame Extraction

↓

YOLOv8 Object Detection

↓

Feature Extraction

↓

Scene Understanding

↓

Caption Generation

↓

Generated Caption

---

## 📋 Project Modules

### Module 1
Video Input & Frame Extraction

### Module 2
Object Detection using YOLOv8

### Module 3
Feature Extraction

### Module 4
Caption Generation

### Module 5
Performance Evaluation

---

## 📁 Project Structure

```
YOLO_Project/

│── dataset/

│   ├── train/

│   ├── valid/

│   └── original/

│
│── models/

│── results/

│── notebooks/

│── data.yaml

│── requirements.txt

│── README.md
```

---

## 📊 Evaluation Metrics

The complete system will be evaluated using:

- BLEU
- METEOR
- ROUGE-L
- CIDEr

The object detection model is evaluated using:

- Precision
- Recall
- mAP@0.5
- mAP@0.5:0.95

---

## 🚀 Current Implementation

The first implementation focuses on training a YOLOv8 object detection model using the VisDrone dataset.

Completed tasks:

- Dataset Preparation
- Annotation Conversion
- YOLO Dataset Configuration
- data.yaml Creation
- YOLOv8 Training

---

## 📌 Future Work

- Complete Feature Extraction Module

- Integrate Video Caption Generation Model

- Build End-to-End CCTV Captioning System

- Develop Web Interface for Real-Time Surveillance

---

