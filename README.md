# 🐱🐶 Cats vs Dogs Image Classification using SVM

This project implements a **Cats vs Dogs image classification system** using a **Support Vector Machine (SVM)** in Python.  
Images are processed using OpenCV, converted to grayscale, resized, and classified into **Cat** or **Dog** categories.

The project is suitable for **machine learning beginners**, **college assignments**, and **mini-project submissions**.

---

## 📌 Features

- Dataset directory validation
- Image preprocessing (grayscale + resize)
- Train–test split
- SVM-based image classification
- Accuracy evaluation and classification report
- Visualization of sample predictions

---

## 📂 Project Structure

Cats-vs-Dogs-SVM/
│
├── dataset/
│ ├── cats/
│ │ ├── cat1.jpg
│ │ ├── cat2.jpg
│ │ └── ...
│ ├── dogs/
│ ├── dog1.jpg
│ ├── dog2.jpg
│ └── ...
│
├── svm_cats_dogs.py
├── requirements.txt
└── README.md

yaml
Copy code

---

## 📊 Dataset Format

- Dataset folder name **must be `dataset`**
- Two subfolders inside `dataset`:
  - `cats` → Cat images
  - `dogs` → Dog images
- Supported formats: `.jpg`, `.png`, `.jpeg`

---

## ⚙️ Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/Cats-vs-Dogs-SVM.git
cd Cats-vs-Dogs-SVM
Step 2: Install Required Libraries
bash
Copy code
pip install -r requirements.txt
▶️ How to Run
bash
Copy code
python svm_cats_dogs.py
