# 📊 Bank Marketing Risk Analysis

🚀 **Project Overview**
This project analyzes **Portuguese bank telemarketing data** to predict whether customers will subscribe to a term deposit. Using **Naïve Bayes classification**, we optimized marketing strategies based on customer behavior.

📌 **Key Highlights**
- 🏦 **Data Source:** Bank direct marketing campaign dataset (Moro et al., 2014)
- 🧹 **Data Cleaning:** Missing value handling, outlier detection
- 🔍 **Feature Engineering:** Derived features for better model accuracy
- 🏆 **Modeling Approach:** Naïve Bayes classification
- 📊 **Evaluation Metrics:** ROC AUC, Precision, Recall, F1-Score

## 📂 Project Structure


---

### **💡 What Each Folder Contains**
| 📂 Folder Name  | Contents & Purpose |
|----------------|-------------------|
| **`data/`** | Stores raw and cleaned datasets (e.g., CSV, Excel files) |
| **`notebooks/`** | Contains Jupyter Notebooks or R scripts for analysis and modeling |
| **`images/`** | Screenshots, graphs, and visualizations (ROC curve, confusion matrix, etc.) |
| **`models/`** | Saved trained models (e.g., `.pkl`, `.h5`, `.sav` files) |
| **`README.md`** | Main project documentation explaining the project |
| **`requirements.txt`** | List of Python dependencies for easy setup |
| **`LICENSE`** | (Optional) Licensing information for open-source projects |

---
## 📈 Results & Visualizations
Here are some key insights from our analysis:

### 🔹 **Confusion Matrix**
![Confusion Matrix](images/confusion_matrix.png)

### 🔹 **ROC Curve**
![ROC Curve](images/roc_curve.png)

📌 **Key Takeaway:** The model achieved an **AUC of 0.84**, meaning it effectively differentiates between likely and unlikely subscribers.

## 🔧 How to Run the Project
### 1️⃣ Clone this Repository
```sh
git clone https://github.com/EvidenceM290/bank-marketing-risk-analysis.git
cd bank-marketing-risk-analysis
