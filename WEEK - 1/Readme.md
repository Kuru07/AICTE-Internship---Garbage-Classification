# 🗑️ Garbage Classification – Internship Week 1

This project is part of my internship and focuses on building a machine learning pipeline to classify different types of garbage using **EfficientNetV2B2** with **Transfer Learning** in TensorFlow/Keras.

---

## 📅 Week 1 Deliverables

### ✅ Tasks Completed
- Setup of the Jupyter Notebook environment
- Uploaded and extracted the image dataset (.zip format)
- Verified dataset folder structure and class-wise organization
- Visualized sample images from each class for inspection
- Analyzed class distribution using bar chart visualization
- Created preprocessing pipeline using `ImageDataGenerator`
- Applied augmentation techniques for minority classes
- Computed class weights to address dataset imbalance

---

## 📁 Dataset Structure

The dataset was structured in class-wise folders after extraction:
garbage_data/
├── glass/
├── paper/
├── metal/
├── cardboard/
├── trash/
├── plastic/


Each folder represents a unique garbage class and contains images corresponding to that category.

---

## 📊 Class Distribution Analysis

Class distribution was visualized to assess imbalance between categories. This helped inform decisions on data augmentation and balancing strategies for training.

---

## 🧼 Preprocessing Highlights

- Images resized to **260x260** to match EfficientNetV2B2 input requirements
- Preprocessing applied using `preprocess_input` from TensorFlow
- Augmentation enabled for training set to improve model generalization
- Dataset split into 80% training and 20% validation

---

## ⚖️ Class Balancing Strategy

To handle imbalance between class samples:
- **Data Augmentation** was applied to increase effective sample size for minority classes
- **Class Weights** were computed to penalize the model for misclassifying underrepresented classes during training

---

## 🧠 Concepts Covered

- Dataset organization and inspection
- Image classification fundamentals
- Transfer learning and feature extraction
- Data preprocessing and augmentation
- Imbalanced dataset handling

---



