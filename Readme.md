# 🚀 Garbage Classification Using Transfer Learning – Internship Project

Welcome to the complete garbage classification project, where I built and fine-tuned a transfer learning model using EfficientNetV2 backbones, trained on a multi-class garbage dataset, and deployed the model into a functional Android application.

---

## 📅 Project Timeline Overview
| Week | Focus |
|------|-------|
| Week 1 | Dataset preparation and initial setup |
| Week 2 | Model compilation, training, evaluation, and Gradio deployment |
| Week 3 | Dataset balancing, class weights, and confusion matrix analysis |
| Final Week | Model fine-tuning, TensorFlow Lite conversion, and Android app deployment |

---

# 📁 Dataset
The dataset used for this project was sourced from Kaggle:  
👉 **[Garbage Classification Dataset – Kaggle Link](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)**

---

# ✅ Week 1: Dataset Preparation and Initial Setup
- Loaded and explored the garbage classification dataset.
- Performed dataset splitting into training, validation, and test sets.
- Set up necessary imports and verified data loading with image previews.
- Plotted class distributions to identify dataset imbalance.

---

# ✅ Week 2: Model Building, Training, and Gradio Deployment
- Built a transfer learning model using **EfficientNetV2B2**.
- Compiled the model with categorical crossentropy loss and Adam optimizer.
- Trained the model on a balanced dataset using class weights to handle imbalance.
- Evaluated model accuracy and visualized training progress.
- Developed a **Gradio-based web interface** for real-time image classification inside Jupyter Notebook.

---

# ✅ Week 3: Dataset Balancing and Performance Evaluation
- Computed **class weights** based on dataset imbalance to improve model fairness.
- Applied **targeted data augmentation** to minority classes.
- Analyzed the **confusion matrix and classification report** to ensure balanced per-class performance.
- Visualized predictions on the test dataset to assess real-world applicability.

---

# ✅ Final Week: Model Fine-Tuning and Android App Deployment
- Switched to **EfficientNetV2B3** backbone to explore higher accuracy potential.
- Increased the number of training epochs with early stopping.
- Unfrozen additional layers for **fine-tuning the transfer learning backbone** with a smaller learning rate.
- Converted the trained model to **TensorFlow Lite (.tflite)** for mobile deployment.
- Integrated the TensorFlow Lite model into a simple **Android application**.

---

# 📱 Android App: Garbage Classifier

### Features:
- Select images from the phone gallery.
- Perform **on-device garbage classification** using the TensorFlow Lite model.
- Display the predicted garbage class and confidence score in the app.

👉 **[Android App Repository](https://github.com/Kuru07/Garbage-Classifier.git)**  
👉 **[Download APK (Google Drive)](https://drive.google.com/drive/folders/1GklhDnnUoHpD0U5y4US-HeP4UU-461lc)**

---

# 🔮 Future Scope
- Add real-time camera input for live garbage classification.
- Deploy the Android app to the Google Play Store.
- Optimize the TensorFlow Lite model for faster inference using GPU delegates.
- Experiment with cross-platform support using Flutter or Compose Multiplatform.

---

## 🙋‍♂️ Author
**Kumarakuru Annamalai**  
GitHub: [github.com/Kuru07](https://github.com/Kuru07)  
LinkedIn: [linkedin.com/in/kumarakuru-annamalai](https://www.linkedin.com/in/kumarakuru-annamalai/)

---
