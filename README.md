# Network Attack Detection using CICIDS2017 + RAPIDS + SMOTE

This repository implements a GPU-accelerated machine learning pipeline for multi-class network attack detection using the CICIDS2017 dataset. It includes advanced techniques such as SMOTE oversampling, downsampling, and performance benchmarking on a multi-class classification task.

---

## Project Structure

```
.
├── video                      # introduce all the main steps of this project
├── SMOTE.ipynb                # Main pipeline script using SMOTE and downsampling
├──Hierarchical.ipynb          # Hierarchical module
├──valilla.ipynb               # BaseLine module
├──stratified sampling.ipynb   # Stratified Sampling module
├── Group 1 – AI-Driven MITRE ATT&CK Framework.pptx  #presentation
└── README.md                   # Project description and usage instructions
```

---

##  Features

- **Dataset**: CICIDS2017 (Monday–Friday sessions)
- **Model**: GPU-accelerated `cuML.LogisticRegression`
- **Preprocessing**:
  - Label unification
  - Train/test split
- **Sampling Strategy**:
  - SMOTE oversampling for rare attack classes (e.g., Heartbleed, SQLi)
  - Downsampling dominant classes to balance dataset
- **Evaluation**:
  - Confusion matrix
  - Precision-Recall (PR) curve
  - Per-class Average Precision (AP) metrics
- **Visualization**: Matplotlib-based export of model evaluation plots

---

## ⚙️ Dependencies

Google colab

```bash
scikit-learn　Version: 1.6.1
Summary: A set of python modules for machine learning and data mining

GCC RUNTIME LIBRARY EXCEPTION　Version 3.1, 31 March 200

Name: tqdm　Version: 4.67.1
Summary: Fast, Extensible Progress Meter

NVIDIA-SMI 550.54.15 Driver Version: 550.54.15 CUDA Version: 12.
```


---

## 👤 Author

Graduate Student

Guanhua Zhao

Honghao Yu

Hongxia Zhou

Ming Zhao

---