# Customer Segmentation using K-Means Clustering

An unsupervised machine learning project that segments mall customers into distinct groups based on their purchasing behavior, demographics, and spending scores using the K-Means clustering algorithm.

---

## 📊 Project Overview
Understanding customer behavior is crucial for targeted marketing strategies. This project analyzes customer data to identify natural groupings (clusters) using three main features:
- **Age**
- **Annual Income (k$)**
- **Spending Score (1-100)**

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook (`.ipynb`)
- **Libraries:**
  - `pandas` (Data manipulation & cleaning)
  - `scikit-learn` (Machine Learning / K-Means algorithm)
  - `matplotlib` (Data visualization & plotting)

---

## ⚙️ How It Works (Workflow)
1. **Data Loading:** Imports the `Mall_Customers.csv` dataset containing 200 customer records.
2. **Feature Selection:** Extracts relevant numerical features (`Age`, `Annual Income`, and `Spending Score`).
3. **Model Training:** Applies **K-Means Clustering** initialized with `n_clusters=4` and a fixed `random_state=42` for reproducibility.
4. **Cluster Analysis:** Assigns each customer to a cluster and calculates the mean metrics for each group to understand their characteristics.
5. **Visualization:** Generates a scatter plot mapping Annual Income against Spending Score, color-coded by cluster segments.

---

## 📈 Cluster Insights (Summary)
The dataset was segmented into **4 distinct customer clusters**:
- **Cluster 0:** Moderate age, moderate income, and moderate spending score.
- **Cluster 1:** Younger age group with high annual income and high spending score (Target/Premium shoppers).
- **Cluster 2:** Young customers with lower annual income but high spending scores.
- **Cluster 3:** Older customers with high annual income but low spending scores (Conservative shoppers).

---

## 🚀 How to Run the Project
1. Clone this repository or download the files.
2. Open the notebook (`Customer_Segmentation.ipynb`) in **Google Colab** or any local Jupyter Notebook environment.
3. Ensure the `Mall_Customers.csv` dataset is uploaded to your environment.
4. Run the cells sequentially to reproduce the analysis and output files (`Customer_Segmentation_Result.csv`).
