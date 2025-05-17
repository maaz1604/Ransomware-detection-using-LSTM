# 🛡️ Ransomware Detection using LSTM

This project focuses on detecting ransomware using a deep learning approach, specifically Long Short-Term Memory (LSTM) networks. It classifies software behavior as **benign** or **ransomware** based on sequences of API calls—an effective method for identifying ransomware early in the execution cycle.

## 🚀 Live Demo
Try the interactive demo here:  
👉 [Hugging Face Space](https://huggingface.co/spaces/pratham12345/ransomwaredetector)

---

## 📌 Overview

With the increasing threat of ransomware, proactive detection techniques are essential. Traditional methods rely on static signatures or manual rule-based analysis. This project adopts a behavioral approach by modeling API call sequences using LSTM to capture temporal patterns typical in ransomware activity.

---

## 🔍 How It Works

- API call sequences are used as input, representing the runtime behavior of software.
- These sequences are tokenized and passed into an LSTM model.
- The model learns to distinguish patterns typical of ransomware versus benign programs.
- Output is a binary classification: **0 (benign)** or **1 (ransomware)**.

---

## 📈 Results

- Achieved over **95% accuracy** on test datasets.
- Model effectively generalizes to unseen samples due to sequential learning.

---

## 🧠 Tech Stack

- **Deep Learning:** TensorFlow, Keras
- **Data Processing:** NumPy, Pandas
- **Visualization:** Seaborn, Matplotlib
- **Deployment:** Hugging Face Spaces (Gradio Interface)

---

## 📁 Dataset

We used a publicly available dataset consisting of API call traces labeled as either ransomware or benign. Preprocessing included:
- Sequence tokenization
- Padding/truncation
- Label encoding

---

## 💡 Features

- Sequence-based classification using LSTM
- Robust to obfuscated static patterns
- Lightweight and suitable for deployment

---

## ⚙️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ransomware-detection-lstm.git
   cd ransomware-detection-lstm

