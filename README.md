---

## **📊 Bank Marketing Risk Analysis**

### 🚀 **Project Overview**
This project analyzes **Portuguese bank telemarketing data** to predict whether customers will subscribe to a term deposit. The dataset contains customer demographics, campaign details, and previous interactions. Using a **Naïve Bayes model**, we aim to classify potential subscribers based on key predictors.  

📌 **Key Highlights**
- 🏦 **Business Problem:** Improve marketing efficiency by targeting customers likely to subscribe.  
- 🔍 **Feature Engineering:** Data cleaning, variable selection, and preprocessing.  
- 🏆 **Modeling Approach:** Naïve Bayes classification for prediction.  
- 📊 **Evaluation Metrics:** Accuracy, Precision, Recall, AUC (ROC Curve).  

---

## **📂 Project Structure**
```
📂 bank-marketing-risk-analysis/
 ├── 📂 data/ (Datasets)
 │   ├── bank_data.csv *(Raw data file)*
 │   ├── cleaned_bank_data.table *(Cleaned dataset after preprocessing)*
 │  
 ├── 📂 notebooks/ *(Completely run in Knime, You can Jupyter Notebooks & R scripts for model building)*
 │   ├── bank_marketing_analysis.knwf *(Exploratory Data Analysis & Model Training)*
 │   ├── mbank_marketing_analysis.knwf *(Confusion Matrix, ROC Curve, AUC computation)*
 │  
 ├── 📂 images/ *(Screenshots & visualizations for better insights)*
 │   ├── workflow.png *(KNIME Workflow Overview)*
 │   ├── confusion_matrix.png *(Confusion Matrix from model evaluation)*
 │   ├── roc_curve.png *(ROC Curve graph for classification performance)*
 │   ├── model_metrics.png *(Precision, Recall, Specificity results)*
 │  
 ├── 📂 models/ *(Stored machine learning models if applicable)*
 │   ├── bank_marketing_analysis.knwf *(Saved trained model for reuse)*
 │  
 ├── 📜 README.md *(Project documentation and guide)*
 ├── 📜 requirements.txt *(Knime)*
 ├── 📜 LICENSE *( Open Source)*
```

---

## **📌 Process & Methodology**
### **Step 1: Data Preprocessing & Exploration**
- 📥 **Dataset Import:** Raw bank marketing data loaded into KNIME.
- 🔍 **Exploratory Data Analysis (EDA):** Checked for missing values, outliers, and variable distributions.
- ⚙️ **Feature Selection:** Removed **duration** since it leaks prediction.
- 🔄 **Data Splitting:** Partitioned into **70% training** and **30% validation**.

## 📌 Workflow Overview:
![Workflow](https://raw.githubusercontent.com/EvidenceM290/-Bank-Marketing-Risk-Analysis/main/images/Model%20Flow.png)

---

### **Step 2: Model Training & Prediction**
- 📊 **Naïve Bayes Model:** Used KNIME's **Naïve Bayes Learner** to train the model.
- 🔢 **Prediction:** Applied the model to predict the probability of subscription.

---

### **Step 3: Model Evaluation**
- 📊 **Confusion Matrix Analysis**
  - Accuracy: **88.5%**
  - True Positive Rate (Recall for `y=1`): **29.7%**
  - False Positive Rate: **3.9%**
  - Specificity (True Negative Rate): **96.1%**
  - Precision: **51.7%**
  - Prevalence (subscription rate in dataset): **11.8%**

## 📌 Confusion Matrix Output:
![Confusion Matrix](https://raw.githubusercontent.com/EvidenceM290/-Bank-Marketing-Risk-Analysis/main/images/Confusion%20Matrix%20from%20model%20evaluation.png)


---

### **Step 4: ROC Curve & AUC**
- 📈 **ROC Curve Analysis**  
  - The **AUC score = 0.765**, indicating a decent predictive capability.  
  - The **closer AUC is to 1, the better the classification performance**.

## 📌 ROC Curve Visualization:
![ROC Curve](https://raw.githubusercontent.com/EvidenceM290/-Bank-Marketing-Risk-Analysis/main/images/ROC%20Curve%20graph%20for%20classification%20performance.png)

---

### **Step 5: Summary of Model Metrics**
- The Naïve Bayes model performs **well in identifying non-subscribers (Specificity = 96.1%)** but has **lower recall for predicting actual subscribers**.
- **Precision = 51.7%**, meaning that when the model predicts a subscription, it is correct **about 51.7% of the time**.
- **Recommendations:**
  - Consider **alternative models (Logistic Regression, Decision Trees)** for improved recall.
  - Tune **threshold settings** to balance recall and precision.

## 📌 Model Performance Metrics:
![Model Metrics](https://raw.githubusercontent.com/EvidenceM290/-Bank-Marketing-Risk-Analysis/main/images/Model%20Metrics.png)

---

## **📬 Connect With Me**
🔗 **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/evidence-madhume-874540204/)  
📂 **GitHub Portfolio:** [My Git Hub Portfolio](https://github.com/EvidenceM290/EvidenceM290/)  
---
