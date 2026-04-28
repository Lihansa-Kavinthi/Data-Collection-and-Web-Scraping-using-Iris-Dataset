# 🌸 Iris Data Preprocessing Pipeline 📊

This repository contains a streamlined Python pipeline within a Jupyter Notebook designed to clean and prep the classic Iris dataset for Machine Learning.

---

### 🚀 Overview
The `datacollecting.ipynb` script transforms raw botanical data into a high-quality format. By handling messy data early, we ensure that any model trained on this dataset is both accurate and robust.

### ✨ Key Features
* **🧹 Smart Cleaning**: Automatically detects and removes missing records to maintain data quality.
* **🚫 Outlier Removal**: Uses the **Interquartile Range (IQR)** method to filter out statistical "noise."
* **🔢 Label Encoding**: Converts categorical species names into numerical values ($0, 1, 2$) for algorithm compatibility.
* **⚖️ Feature Scaling**: Applies `StandardScaler` to ensure all measurements have a mean of $0$ and a variance of $1$.

---

### 🛠️ Technical Stack
* **Pandas**: For data manipulation and CSV handling.
* **Scikit-Learn**: For preprocessing, encoding, and standardization.

---
### 📂 How to Run

1. Ensure `iris.csv` is in the same folder as the notebook.
2. Install the requirements:

```bash
pip install pandas scikit-learn
