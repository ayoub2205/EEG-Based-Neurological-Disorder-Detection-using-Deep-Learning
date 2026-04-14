# 🧠 EEG-Based Neurological Disorder Detection using Deep Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Deep%20Learning-CNN%20%2B%20RNN-orange" />
  <img src="https://img.shields.io/badge/Framework-Django%20REST-green?logo=django" />
  <img src="https://img.shields.io/badge/Frontend-React-blue?logo=react" />
  <img src="https://img.shields.io/badge/Domain-Biomedical%20AI-red" />
  <img src="https://img.shields.io/badge/Status-Research%20Project-success" />
</p>

>  End-to-end AI system for automated detection of neurological disorders from EEG signals using hybrid CNN-RNN architectures with a full-stack web interface.

---

## Overview

Neurological disorders are complex and often difficult to diagnose due to the noisy and high-dimensional nature of EEG signals.
This project presents a **complete intelligent system** that leverages **Deep Learning** to automatically analyze EEG signals and detect multiple neurological conditions.

###  Key Contributions

*  End-to-end pipeline (EEG → AI → Web App)
*  Hybrid Deep Learning (CNN + RNN)
*  Multi-disease detection system
*  Full-stack deployment (Django + React)
*  Real-world biomedical application

---

##  Objectives

* Develop a **robust deep learning pipeline** for EEG signal classification
* Detect multiple neurological disorders automatically
* Build an **interactive AI-powered diagnostic assistant**
* Provide a scalable solution for healthcare applications

---

##  Targeted Disorders

*  ADHD (Attention Deficit Hyperactivity Disorder)
*  Epilepsy
*  Alzheimer’s Disease
*  Sleep Disorders

---

##  System Architecture

`<h3> Menu</h3>
<p align="center">
  <img src="https://raw.githubusercontent.com/ayoub2205/FindUs-Facial-Recognition-for-Missing-Persons/main/images/img1.png" width="1200"/>

### 🔹 Pipeline Steps

1. **Data Input**

   * EEG signals (CSV / multi-channel)

2. **Preprocessing**

   * Noise filtering
   * Normalization
   * Segmentation
   * Artifact removal

3. **Model Inference**

   * CNN → Spatial feature extraction
   * RNN (LSTM / GRU) → Temporal modeling

4. **Output**

   * Predicted disorder
   * Confidence score

---

##  Model Architectures

| Model Type | Application               |
| ---------- | ------------------------- |
| CNN + LSTM | ADHD, Alzheimer           |
| CNN + GRU  | Epilepsy, Sleep Disorders |

### 💡 Why Hybrid Models?

* CNN → captures spatial EEG patterns
* RNN → captures temporal dependencies
* Combined → improves performance on sequential biomedical signals

---

##  Datasets

* CHB-MIT EEG Dataset (Epilepsy)
* Sleep-EDF Expanded Dataset
* ADHD EEG Dataset
* Alzheimer EEG Dataset

---

##  Performance

* High classification accuracy across multiple disorders
* Robust against noisy EEG signals
* Fast inference (suitable for real-time usage)

📌 Detailed metrics available in the report

---

## 🖥️ Web Application

### 🔹 Features

* Upload EEG data (CSV format)
* Automatic preprocessing
* Real-time prediction
* Confidence score visualization
* Multi-disorder detection

### 🔹 Tech Stack

**Backend**

* Django REST Framework

**Frontend**

* React.js

**AI / Data**

* Python
* TensorFlow / PyTorch
* MNE (EEG processing)

---

## 📂 Project Structure

```
├── backend/        # Django REST API
├── frontend/       # React application
├── models/         # Trained models
├── notebooks/      # Experiments & training
├── data_sample/    # Sample EEG data
├── docs/           # Report & documentation
├── README.md
└── requirements.txt
```

---

##  Getting Started

###  Backend

```bash
cd backend
pip install -r requirements.txt
python manage.py runserver
```

###  Frontend

```bash
cd frontend
npm install
npm start
```

---

##  Demo

👉 Add screenshots or demo video (recommended)

---

##  Documentation

📘 Full report available:

```
/docs/Rapport.pdf
```

---

## 🔐 Ethical Considerations

* This system is a **decision-support tool**, not a replacement for clinicians
* EEG data must be handled with strict privacy and security standards

---

## 🔮 Future Improvements

* Real-time EEG integration
* Explainable AI (XAI)
* Model optimization
* Clinical validation
* Cloud deployment

---

## 👨‍💻 Author

**Ayoub Chhibat**
Master’s Degree in Embedded Systems & Digital Services
Specialization: AI • Deep Learning • Biomedical Signal Processing

---

## ⭐ Support

If you find this project useful:

* ⭐ Star the repository
* 🔁 Share it with the AI community

---

## 📬 Contact

Open to collaboration, research opportunities, and AI projects 🚀
