This project demonstrates an end-to-end machine learning pipeline to detect web attacks from network traffic data using a Random Forest Classifier. It leverages a dataset containing various types of network traffic and classifies them into benign or malicious activities.

---

Dataset

The dataset used:  
**Thursday-WorkingHours-Morning-WebAttacks.pcap_ISCX.csv**  
Part of the CIC-IDS2017 dataset – a widely used benchmark for intrusion detection tasks.

---
Features

- Data preprocessing and cleaning  
- Train-test split  
- Baseline model training using **Random Forest**  
- Model evaluation (accuracy, precision, recall, F1-score, confusion matrix)  
- Handling **class imbalance** using `class_weight`  
- Feature importance visualization  
- Hyperparameter tuning using **GridSearchCV**

---

Results

- **Accuracy:** 99.57%  
- Improved minority class detection using balanced class weights  
- Most important features identified for model performance  
- Optimized parameters using grid search:  
  - `max_depth=10`  
  - `min_samples_split=5`  
  - `n_estimators=100`

---

Requirements

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- seaborn  
- matplotlib  
- Jupyter or Google Colab
