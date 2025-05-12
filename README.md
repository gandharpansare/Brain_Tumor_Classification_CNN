# **Brain Tumor Classification using Convolutional Neural Networks (CNN)** 🧠  

## **Overview**  
This project implements a **Convolutional Neural Network (CNN)** to classify brain MRI scans into four categories: **Glioma Tumor, Meningioma Tumor, Pituitary Tumor, and No Tumor**. The model is designed to automate the **tumor detection process**, aiding radiologists in **early diagnosis** and **treatment planning**.  

---

## **Dataset**  
- **Source:** [Brain Tumor MRI Dataset on Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)  
- **Size:** Approximately 7,000 MRI images  
- **Classes:** Glioma Tumor, Meningioma Tumor, Pituitary Tumor, No Tumor  
- **Format:** JPG images, organized into training and testing sets  

---

## **Project Files**  

📂 Brain_Tumor_Classification_CNN

│── Brain Tumors and Mental Health.docx # Project report

│── README.md # Project documentation

│── brain-tumor-classification-using-cnn.ipynb # Jupyter notebook for training and evaluation

│── brain-tumor-classification-using-cnn.pdf # PDF export of the notebook

│── brain-tumor-classification-using-cnn.html # HTML export of the notebook

---

## **Key Features**  
✔️ **Data Preprocessing** – Resized MRI images, applied data augmentation, and normalized pixel values.  
✔️ **Transfer Learning** – Utilized **ResNet18** for feature extraction.  
✔️ **Custom Classification Layer** – Fine-tuned the final layers for multi-class classification.  
✔️ **Model Evaluation** – Calculated accuracy, precision, recall, and F1-score.  
✔️ **Visualization** – Included confusion matrices and loss curves for performance analysis.  

---

## **Results**  
- **Overall Accuracy:** 91% on test data  
- **High Precision and Recall** for Pituitary and No Tumor classes  
- **Confusion Matrix** to visualize model performance across all classes  

---

## **Future Work**    
- Deploy the model as a web application for real-time tumor detection  

---

## **Contributors**  
- **Gandhar Ravindra Pansare** (**Indiana University, Bloomington**)
- **Guided by Professor Krista Li**  

---

## **License**  
This project is open-source under the **MIT License**.  

---
