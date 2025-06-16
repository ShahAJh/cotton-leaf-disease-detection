# 🌿 Cotton Leaf Disease Classification using Deep Learning

This repository contains a Deep Learning project focused on classifying cotton leaf diseases using a custom-collected image dataset. The project was developed as part of the **Machine Learning and Deep Learning** course during the **2024/2025 academic year** of the Master's in Artificial Intelligence program.

---

## 📂 Project Structure


---

## 📌 Project Description

This project aims to develop and evaluate CNN-based models to accurately detect and classify multiple **cotton leaf diseases**. A custom dataset was collected and annotated in collaboration with agronomists and validated using the Plantix app. Models such as SimpleCNN, DeepCNN, ResNet50, and VGG16 were trained and compared using accuracy, F1-score, and confusion matrices.

---

## 🔬 Dataset

- **Classes (5 total):**
  - Bacterial Blight
  - Cotton Leaf Curl Virus (CLCV)
  - Mealy Bug
  - Whiteflies
  - Healthy

- **Image Count**: Manually collected and balanced using augmentation techniques.

- **Labeling**: Verified by an agronomist and cross-validated with Plantix.

---

## ⚙️ Models Used

- ✅ Simple CNN (Baseline)
- ✅ Deep CNN (4-layer custom architecture)
- ✅ ResNet50 (Pretrained, fine-tuned)
- ✅ VGG16 (Pretrained, fine-tuned)

---

## 📈 Results Summary

| Model       | Accuracy | F1-Score |
|-------------|----------|----------|
| SimpleCNN   | 85.2%    | 84.6%    |
| DeepCNN     | 90.6%    | 91.3%    |
| ResNet50    | 93.0%    | 93.0%    |
| VGG16       | **94.5%**| **94.5%**|

---

## 📊 Visualizations

- Accuracy vs Epoch Graphs  
- Confusion Matrices  
- Evaluation Metric Comparison  
- Class Distribution Graph  
