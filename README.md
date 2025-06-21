# 🗑️ Garbage Classification using Transfer Learning

## 🧠 Project Overview
This project applies deep learning (transfer learning) to classify garbage images into various categories like plastic, metal, glass, etc. using MobileNetV2.

## 🔧 Technologies Used
- Python
- TensorFlow / Keras
- Google Colab
- MobileNetV2 (pretrained)

## 📁 Dataset
Dataset was provided by the internship LMS platform and uploaded manually in ZIP format.

## 🎯 Project Workflow
1. Dataset extracted and loaded using `ImageDataGenerator`
2. MobileNetV2 base model used with frozen layers
3. Custom classification head added for garbage classes
4. Model trained for 5 epochs
5. Accuracy and loss metrics plotted

## ✅ Improvements Made
- Clear markdown and code comments
- Training/validation data split
- Visualization of accuracy
- Model summary for clarity
- Clean notebook structure
