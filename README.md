# 🗑️ Waste Classifier using VGG16

A Deep Learning-based Waste Classification system that uses **VGG16** for identifying types of waste (e.g., recyclable, biodegradable, trash). The model is deployed with a lightweight **HTML, CSS, and JavaScript** frontend for ease of use and accessibility.

---

## 📌 Project Overview

This project uses **transfer learning** with the pre-trained **VGG16** model to classify waste images into three useful categories. It aims to support eco-friendly practices by simplifying waste management and encouraging proper disposal.

### 🚀 Features

- 🌐 Web-based interface using HTML, CSS, and JavaScript
- 🤖 Deep Learning model (VGG16) for image classification
- 📷 Upload or capture image for real-time prediction
- 📊 Displays prediction result and confidence score
- ♻️ Supports recyclable, biodegradable, and trash categories

---

## 🧠 Model Details

- **Base Model**: VGG16 (pre-trained on ImageNet)
- **Fine-Tuned**: Last few layers retrained on the custom waste dataset
- **Output Classes**:
  - Recyclable
  - Biodegradable
  - Trash

---

## 📁 Dataset Used

We used a publicly available dataset from Kaggle for training the VGG16 model.

📦 **Dataset**: [Municipal Solid Waste Dataset – Kaggle](https://www.kaggle.com/datasets/elinachen717/municipal-solid-waste-dataset)

This dataset contains images of waste categorized into multiple classes including:
- Biodegradable Waste
- Glass
- Metal
- Paper
- Plastic
- Textile
- Others

We regrouped them into 3 categories for our use case:
- **Recyclable** → Paper, Plastic, Glass, Metal  
- **Biodegradable** → Biodegradable Waste  
- **Trash** → Textile, Others, and anything not recyclable or biodegradable

---

## 💻 How to Run the Project

### 🔧 Option 1: Run Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/sambasivagudala369/waste-classifier-vgg16.git
   cd waste-classifier-vgg16

![image](https://github.com/user-attachments/assets/21815183-c758-4c59-ba1d-24ca15c4aba2)

## Demo Link : https://drive.google.com/file/d/1WdZ4C9mNzsmMvDdCgeTCB27QUu6M-tUw/view?usp=sharing
