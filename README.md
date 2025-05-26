# Interpretable Machine Learning for Early Detection of Lower Back Pain

## 📘 Project Overview

This project was developed as part of a Master’s coursework at **King’s College London**. It aims to design an interpretable machine learning model for early detection and explanation of lower back pain risks using symptom-based data.

The study compares the performance of a **Graph Neural Network (GNN)** with a traditional **K-Nearest Neighbors (KNN)** classifier, leveraging a publicly available dataset from Kaggle.

---

## 🎯 Objectives

- Build a deep learning model using Graph Neural Networks (GNN) to predict the risk of lower back pain.
- Compare the performance of GNN with the KNN algorithm.
- Provide model interpretability for enhanced understanding of the predictions.

---

## 👨‍🎓 Author

- **Name**: Yu-Ju Yang (Harry Yang)
- **University**: King’s College London
- **Faculty**: Faculty of Natural, Mathematical & Engineering Sciences
- **Department**: Department of Engineering
- **Program**: MSc in Robotics

---

## 🗂 Project Structure

```text
LowerBackPain/
├── Advanced_GNN.ipynb # Implementation and experiments using Graph Neural Networks
├── KNN.ipynb # Implementation and comparison with K-Nearest Neighbors
├── Dataset_spine_clean.csv # Cleaned dataset used in the experiments
└── README.md # Project documentation
```

---

## 🔗 Dataset

The dataset used in this project is publicly available on Kaggle:

🔗 [Lower Back Pain Symptoms Dataset](https://www.kaggle.com/datasets/sammy123/lower-back-pain-symptoms-dataset/data)

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HarryYang0512/LowerBackPain.git
   ```
2. **Install dependencies**:  
   *(Use a virtual environment if possible)*
```text
  numpy>=1.21.0
  pandas>=1.3.0
  scikit-learn>=0.24.0
  matplotlib>=3.4.0
  seaborn>=0.11.0
  torch>=1.10.0
  torch-geometric>=2.0.0
  jupyter
```

---

📊 Results Summary

| Model | Accuracy | Precision | Recall | F1 Score |   AUC    |
|-------|----------|-----------|--------|----------|----------|
| GNN   | 0.9586   | 0.9721    | 0.9301 | 0.9470   | 0.9959   |
| KNN   | 0.92     | 0.90      | 0.91   | 0.90     | 0.91     |

---

📬 Contact
GitHub: HarryYang0512
Email: harryang99@gmail.com
