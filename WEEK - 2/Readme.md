# 🚀 Garbage Classification – Week 2 (Internship)

This repository documents the progress for **Week 2** of my internship project focused on garbage classification using **EfficientNetV2B2** with Transfer Learning.

---

## ✅ Week 2 Progress

### 🔹 Model Development:
- Built a transfer learning model using **EfficientNetV2B2** as the backbone.
- Compiled the model with:
  - **Loss Function:** Categorical Crossentropy
  - **Optimizer:** Adam
  - **Metrics:** Accuracy

### 🔹 Model Training:
- Trained the model on the augmented and balanced dataset using class weights.
- Used early stopping and validation monitoring to prevent overfitting.
- Evaluated model performance using training and validation accuracy and loss plots.

---

## 🔍 Model Evaluation:
- Achieved satisfactory accuracy on both training and validation datasets.
- Visualized per-epoch accuracy and loss to ensure proper learning trends.
- Performed custom image testing to validate the model’s real-world prediction capability.

---

## 🧪 Custom Image Predictions:
- Implemented a testing pipeline to:
  - Upload and preprocess custom images.
  - Predict the garbage class using the trained model.
  - Visualize both the actual and predicted class in the notebook.

---

## 🌐 Gradio Deployment:
- Built an interactive **Gradio web interface** to make predictions accessible via an easy-to-use UI.
- Enabled image upload and real-time class prediction with confidence score display.
- Ensured the model is directly usable inside Jupyter Notebook using Gradio’s local server.

---

## 📂 Files in This Week:
- Trained model file: `garbage_classifier_model.keras`
- Jupyter Notebook: Model training, evaluation, and Gradio deployment
- Gradio app for image classification

---

## 🔜 Next Steps:
- Further fine-tune the EfficientNetV2B2 layers to boost accuracy.
- Explore cloud deployment options for public access (Streamlit Cloud or Gradio sharing links).
- Perform more extensive custom image testing.

---
