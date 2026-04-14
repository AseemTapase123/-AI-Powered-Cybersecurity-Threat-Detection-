# 🛡 AI-Powered Cybersecurity Threat Detection 

## 📌 Project Overview
This project is an AI-based Intrusion Detection System (IDS) that uses Machine Learning to classify network traffic as **normal or malicious**.  

It is built using the **NSL-KDD dataset** and simulates a real-world **Security Operations Center (SOC)** environment for cyber threat monitoring and analysis.

---

## 🎯 Objective
To design an AI-powered system capable of detecting cyber threats and anomalies in network traffic, similar to real-world SOC and SIEM systems used in cybersecurity industries.

---

## 📊 Dataset Used
- **NSL-KDD Dataset (Kaggle)**
- Contains labeled network traffic data:
  - Normal traffic
  - Attack categories (DoS, Probe, R2L, U2R)

---

## 🧠 Machine Learning Approach
- Algorithm: **Random Forest Classifier**
- Preprocessing:
  - Label Encoding for categorical features
  - Standard Scaling for numerical stability
- Evaluation Metrics:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## ⚙️ System Workflow
1. Load NSL-KDD dataset  
2. Clean and preprocess data  
3. Encode categorical variables  
4. Scale features using StandardScaler  
5. Train ML model (Random Forest)  
6. Evaluate model performance  
7. Save trained model for reuse (`.pkl` files)  


---

## 📈 Results
- Achieved high accuracy on test dataset
- Successfully classified network traffic into normal and attack categories
- Effective detection of anomalous patterns using ML

---

## 🔐 Real-World Use Cases
- Intrusion Detection Systems (IDS)
- Security Operations Center (SOC) simulation
- Network traffic monitoring
- Cybersecurity threat intelligence systems

---

## ☁️ Model Download
Due to GitHub file size limitations, the trained model is hosted externally:

👉 Download Model Here:
https://drive.google.com/file/d/1Ms5xe3Y1SrMA55RnM2AF9aN2x0VjT9Pm/view?usp=sharing

---

## 🛠 Tech Stack
- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 👨‍💻 Author
**Aseem Tapase**  

---

## 🚀 Future Enhancements
- Deep Learning-based IDS (LSTM/ANN)
- Real-time network traffic monitoring
- Streamlit-based SOC dashboard
- API deployment for live predictions
- Integration with SIEM tools

---

## ⭐ Project Highlight
This project demonstrates how Machine Learning can be applied in **cybersecurity domains** to build intelligent threat detection systems similar to those used in enterprise SOC environments.
