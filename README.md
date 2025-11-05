# 🎙️ Emotion Recognition from Speech using Deep Learning

## 📘 Overview
This project presents a **Speech Emotion Recognition (SER)** system capable of identifying human emotions such as **Angry**, **Disgust**, **Happy**, **Neutral**, **Sad**, and **Scared** from voice signals.  
The proposed model uses a **hybrid CNN–LSTM deep learning architecture** to capture both spectral and temporal dependencies in speech features.  
It is developed as part of the **NLP Course Project at VIT Vellore** and demonstrates how AI systems can perceive emotional states through acoustic cues.

---

## 🧩 Motivation
Emotion plays a crucial role in human communication. Enabling machines to detect and respond to emotions can enhance **human–computer interaction**, **mental health assessment**, and **empathetic virtual assistants**.  
Despite progress in deep learning, challenges such as **cross-speaker variability**, **dataset imbalance**, and **overfitting to acted speech** persist.  
This project addresses these limitations through:
- **Multi-corpus training** using diverse datasets  
- **Feature normalization** for consistent scaling  
- **Hybrid modeling** to jointly learn local spectral and long-term temporal emotion cues  

---
## 📘 Requirements
In order to execute the **"NLP_project_output (2).ipynb"** in local machine:
- Delete mount google drive cell
- Download **"feature_scaler.pkl", "label_encoder.pkl", "emotion_recognition_model.h5"** onto your local machine
- In "NLP_project_output (2).ipynb" Update these paths **MUST match the output paths from your local machine**
'''
 DRIVE_PATH = "/content/drive/MyDrive/"                                   
 MODEL_PATH = os.path.join(DRIVE_PATH, "emotion_recognition_model.h5")    
 SCALER_PATH = os.path.join(DRIVE_PATH, "feature_scaler.pkl")             
 ENCODER_PATH = os.path.join(DRIVE_PATH, "label_encoder.pkl")             
'''
- Run the notebook
