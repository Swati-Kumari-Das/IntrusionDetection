# Intrusion Detection System (IDS) Using Machine Learning  

An intelligent **Intrusion Detection System (IDS)** built with **Machine Learning** to classify network traffic as normal or malicious.  
The project leverages the **KDD Cup 1999 dataset** and applies multiple ML algorithms to detect **DoS, R2L, U2R, and Probe attacks** with **99%+ accuracy**.  

---

## 🚀 Features  
- Detects **known and unknown cyberattacks** using supervised ML models  
- Implements multiple algorithms:  
  - Gaussian Naïve Bayes  
  - Decision Tree  
  - Random Forest  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
- Optimized data preprocessing (feature selection, normalization, categorical encoding, class balancing)  
- **Real-time intrusion detection dashboard** with Gradio interface  
- Evaluation using Accuracy, Precision, Recall, F1-score, and ROC-AUC  
- Visualizations of feature importance, correlation heatmaps, and model performance  

---

## 🛠 Tech Stack  
- **Programming Language:** Python  
- **ML Libraries:** Scikit-learn, XGBoost, TensorFlow/Keras (optional), Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Traffic Analysis Tools:** Wireshark, PyShark  
- **UI & Deployment:** Gradio, Google Colab  
- **Version Control:** Git, GitHub  

---

---

## 📊 Results  
- **Random Forest & Decision Tree models achieved 99%+ accuracy** on test data  
- Significantly reduced **false positives and false negatives** through feature selection & dataset balancing  
- Real-time Gradio dashboard enables quick attack classification with model confidence scores  

---

## 📘 Dataset  

**Required files from KDD Cup 1999 dataset:**  
1. `kddcup.names`  
2. `training_attack_types`  
3. `kddcup.data_10_percent`  

Place these files in the `data/` directory of the project.  
[Download the dataset here](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)


---

## 🔮 Future Scope  
- Integration with **Deep Learning models** for anomaly detection  
- Support for **encrypted traffic analysis**  
- Cloud-based deployment for **enterprise-scale monitoring**  
- Integration with **SIEM systems** for automated threat response  
- Implement **Explainable AI (SHAP/LIME)** for interpretability  
