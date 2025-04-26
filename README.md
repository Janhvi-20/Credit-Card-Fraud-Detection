# Credit Card Fraud Detection

## Overview  
This project implements a machine learning-based credit card fraud detection system using Isolation Forest, Local Outlier Factor (LOF), and Support Vector Machine (SVM). The models are trained and evaluated on a dataset containing 269,312 transaction records, achieving the following accuracies:  
- **Isolation Forest:** 99.7%  
- **Local Outlier Factor:** 99.6%  
- **Support Vector Machine:** 70.46%  

A detailed Exploratory Data Analysis (EDA) was performed to understand the dataset, address class imbalance, and preprocess the data for optimal model performance.

---

## Project Structure  
### 1. **Data Exploration and Preprocessing**  
- Conducted detailed EDA to uncover patterns, correlations, and anomalies.  
- Addressed class imbalance through resampling techniques.  
- Scaled numerical features using standardization for better model performance.  

### 2. **Models and Methodologies**  
#### Isolation Forest  
- An unsupervised anomaly detection algorithm that isolates anomalies by randomly selecting features and splitting data.  
- Achieved an accuracy of **99.7%**, demonstrating high precision in identifying fraud.  

#### Local Outlier Factor (LOF)  
- A density-based method that detects anomalies by comparing the local density of a point with its neighbors.  
- Achieved an accuracy of **99.6%**, making it highly effective in fraud detection.  

#### Support Vector Machine (SVM)  
- A supervised learning algorithm with an RBF kernel used for classification.  
- Achieved an accuracy of **70.46%**, highlighting challenges in imbalanced datasets.  

### 3. **Evaluation Metrics**  
- Precision, recall, and F1-score were used to evaluate model performance.  
- Confusion matrices provided insights into false positives and false negatives.

---

## Results  
The project highlights the efficacy of Isolation Forest and LOF in detecting fraudulent transactions with high accuracy. SVM's performance was limited, indicating the importance of selecting appropriate algorithms for imbalanced datasets.

---

## Tech Stack  
- **Languages & Libraries:** Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook, Git  

---

## How to Use  
1. Clone this repository:  
   ```bash
   git clone <repository_url>
   pip install -r requirements.txt
   jupyter notebook main.ipynb
