# 🧵 Fabric Defect Classification with CNN

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)

> **Author:** Ritik Ghoghari
- > • [GitHub](https://github.com/Ritikghoghari)
- > • [LinkedIn]((http://linkedin.com/in/ritik-ghoghari-951ab229b))  
> Deep learning approach for detecting and classifying fabric types and defects using convolutional neural networks.

---

## 📌 Overview
Fabric quality inspection is an essential part of textile manufacturing. Traditional manual inspection is time-consuming and prone to errors.  
This project introduces an **automated fabric classification system** using **Convolutional Neural Networks (CNNs)** to identify fabric types and possible defects by analyzing image texture, color, and patterns.

**Key Benefits:**
- 🚀 Faster inspection vs. manual checking  
- ✅ More accurate classification through deep learning  
- 📦 Scalable solution for textile quality control  

---

## 📂 Dataset
The dataset is sourced from **Kaggle**:  
[Fabric Dataset – by Ayesha Rafique](https://www.kaggle.com/datasets/ayesharafique/fabric-dataset)

**Structure:**

📁 FabricDataset
┣ 📂 Train
┃ ┣ 📂 Class1
┃ ┣ 📂 Class2
┃ ┗ ...
┗ 📂 Test
┣ 📂 Class1
┣ 📂 Class2
┗ ...

## ⚙️ Usage

### 1️⃣ Clone this repository
git clone https://github.com/yourusername/fabric-defect-classification.git
cd fabric-defect-classification

### 2️⃣ Open the Jupyter Notebook
jupyter notebook Fabric_Defect_Classification.ipynb

### 3️⃣ Run the notebook
The notebook will:

- 📥 Download the dataset using kagglehub
- 🖼 Preprocess and augment images
- 🧠 Train the CNN model with early stopping
- 📊 Evaluate using confusion matrix and classification report


### 🙌 Acknowledgements
- Dataset: Fabric Dataset – Kaggle
- Framework: TensorFlow
- Author: Ritik Ghoghari
