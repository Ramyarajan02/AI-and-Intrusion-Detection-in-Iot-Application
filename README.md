# 🚨 AI-Based Intrusion Detection in IoT Applications

This project focuses on enhancing the security of **IoT (Internet of Things)** networks through **Artificial Intelligence-based Intrusion Detection Systems (IDS)**. By leveraging **Machine Learning (ML)** and **Deep Learning (DL)** techniques, we aim to detect and classify network intrusions in real-time across multiple benchmark datasets.

---

## 🔒 Project Overview

With the rapid proliferation of IoT devices, cybersecurity risks have grown significantly. Traditional security solutions are often ineffective due to the lightweight and resource-constrained nature of IoT environments. This project proposes **AI-powered IDS models** that are accurate, efficient, and suitable for IoT ecosystems.

---

## 🧠 Models Implemented

### ✅ Machine Learning Models (Scikit-learn)
- Random Forest
- Support Vector Machine (SVM)
- Decision Tree

### 🔁 Deep Learning Models (TensorFlow/Keras)
- Artificial Neural Networks (ANN)

---

## 📂 Datasets Used

| Dataset       | Attack Types Included                                  |
|---------------|--------------------------------------------------------|
| UNSW-NB15     | Fuzzers, DoS, Exploits, Recon, Shellcode, Worm, etc.  |
| CIC-IDS2017   | DDoS, Brute Force, PortScan, Web, Botnet, Infiltration |
| NSL-KDD       | Probe, DoS, U2R, R2L                                   |

Each dataset enables comprehensive evaluation across diverse real-world intrusion scenarios.

---

## 🔧 Methodology

1. **Data Preprocessing**
   - Data cleaning and normalization
   - Label encoding for categorical features

2. **Feature Selection**
   - Correlation filtering
   - Feature importance (Random Forest)

3. **Model Training**
   - Hyperparameter tuning using Grid Search + Cross-Validation

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

5. **Comparison**
   - ML vs DL in terms of **accuracy** and **resource efficiency**

---

## 📊 Results Summary

| Dataset       | ML Accuracy | DL Accuracy |
|---------------|-------------|-------------|
| UNSW-NB15     | 92.12%      | 92.30%      |
| CIC-IDS2017   | 100%        | 100%        |
| NSL-KDD       | 98.85%      | 97.19%      |

### 🔍 Key Observations
- **Random Forest** offered the best tradeoff between **accuracy**, **speed**, and **interpretability**.
- **Deep Learning models** can capture complex patterns but require more **computational resources** and training time.

---



