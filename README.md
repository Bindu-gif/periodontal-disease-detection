# 🧠 Deep Learning-Based Automatic Diagnosis of Periodontal Diseases from X-rays

This project is part of our final submission for the **AI in Healthcare** course. It applies advanced deep learning techniques to improve early diagnosis of periodontal diseases using dental X-ray images.

We trained a YOLOv5-based image classification model to detect cavities with high accuracy and incorporated Grad-CAM visualizations to enhance transparency and interpretability of predictions. The project demonstrates the practical use of AI for diagnostic support in dental care, especially in underserved areas.

---

## 🎥 Video Presentation
[Watch our 8-minute demo on YouTube](https://youtu.be/109-I9Ij9Jg)

---

## 📁 Included Files
- `periodontal_model_training.py` – Python script for model training and Grad-CAM visualization  
- `Periodontal_Project_Final.pdf` – Final slide presentation summarizing the project  
- Grad-CAM output images (optional - add here if needed)

---

## 📊 Project Overview
- **Model:** YOLOv5s (Ultralytics)
- **Dataset:** 2,000 annotated dental X-ray images
- **Source:** Roboflow public dataset
- **Achieved Accuracy:** 91.1%
- **Tools Used:** Google Colab, PyTorch, OpenCV, Matplotlib, Grad-CAM

---

## 💡 Problem Addressed

Early diagnosis of periodontal diseases is often delayed due to:
- Shortage of trained dental professionals in rural or low-resource areas  
- Human error in X-ray interpretation  
- Time constraints in clinical workflows

---

## 🎯 Proposed Solution

Our model enables:
- Fast and accurate detection of dental cavities  
- Grad-CAM heatmaps to show “why” the model made its prediction  
- Transparent and trustworthy AI integration in clinical decision-making  
- Potential for real-time deployment via web or mobile interface

---

## 🧠 Architecture & Method
- Fine-tuned YOLOv5s pretrained on ImageNet  
- CSPNet backbone for efficient feature learning  
- Grad-CAM applied to final conv layers for visual explanations  
- Trained for 40 epochs with improved learning rate and batch settings

---

## 🔍 Dataset Details
- Source: [Roboflow Universe](https://universe.roboflow.com)  
- Labels: `with_cavity`, `without_cavity`  
- Train/Validation/Test split with augmentation  
- Preprocessing: Resized to 128×128, normalized

---

## ✨ Key Highlights
- High model performance (91.1% accuracy)  
- Explainable AI via Grad-CAM  
- Low-code, cloud-executable pipeline (Google Colab)  
- Transferable methodology for other radiographic disease detection

---

## 📚 References
- Cantu et al., 2020 – Detection of Dental Caries using CNNs  
- Selvaraju et al., 2017 – Grad-CAM (IEEE ICCV)  
- Roboflow Universe – Public medical imaging datasets  
- Ultralytics – YOLOv5s classification framework

---

👩‍⚕️ **Developed by Shamiso Mubatsa and Bindu Mamillapalli**  
🎓 *Master’s in Health Informatics – Michigan Technological University*
