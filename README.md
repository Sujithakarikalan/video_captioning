# Deep Learning-Based CCTV Video Captioning for Intelligent Surveillance

## 📌 Overview

This project presents an AI-powered surveillance system that automatically generates meaningful text descriptions from CCTV videos using Deep Learning. The system analyzes surveillance footage, understands the visual scene, recognizes human activities, and generates natural language captions describing the events occurring in the video.

Example:

Input:
- CCTV video showing a person entering a building carrying a backpack.

Output:
- "A person enters the building carrying a backpack."

---

# 🚀 Features

- CCTV video analysis
- Automatic frame extraction
- Visual feature extraction
- Human action recognition
- Automatic caption generation
- Intelligent surveillance assistance

---

# 🎯 Problem Statement

Manual monitoring of CCTV surveillance footage is time-consuming and inefficient. Security personnel must continuously observe long hours of video recordings to identify important events. This project automates the surveillance process by analyzing CCTV videos and generating descriptive captions using deep learning models, enabling faster event understanding and efficient surveillance monitoring.

---

# 🛠 Technologies Used

- Python
- OpenCV
- PyTorch
- Hugging Face Transformers
- NumPy
- Pandas
- Streamlit / Flask
- Git
- GitHub

---

# 🤖 Deep Learning Models Used

| Model | Purpose |
|---------|----------|
| Video Swin Transformer | Extracts visual features from CCTV video frames |
| SlowFast | Recognizes human actions and motion |
| T5 Transformer | Generates natural language captions from extracted features |

---

# 📂 Dataset

The project uses publicly available benchmark datasets:

- MSVD (Microsoft Video Description Dataset)
- MSR-VTT (Microsoft Research Video-to-Text Dataset)

---

# ⚙️ Workflow

CCTV Video
↓
Frame Extraction (OpenCV)
↓
Video Swin Transformer
(Visual Feature Extraction)
↓
SlowFast
(Action Recognition)
↓
Feature Fusion
↓
T5 Transformer
(Caption Generation)
↓
Generated Caption

---

# 📋 Implementation Steps

### Step 1
Load the CCTV video.

### Step 2
Extract video frames using OpenCV.

### Step 3
Preprocess the extracted frames.

### Step 4
Extract visual features using the Video Swin Transformer.

### Step 5
Recognize human actions using the SlowFast model.

### Step 6
Combine visual and action features.

### Step 7
Generate captions using the T5 Transformer.

### Step 8
Display the generated caption.

---

# 📁 Project Structure

CCTV-Video-Captioning/

├── dataset/

├── preprocessing/

├── models/

│ ├── video_swin.py

│ ├── slowfast.py

│ ├── t5_caption.py

├── training/

├── testing/

├── app.py

├── requirements.txt

└── README.md

---

# 📊 Evaluation Metrics

- BLEU
- METEOR
- ROUGE-L
- CIDEr

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/CCTV-Video-Captioning.git
