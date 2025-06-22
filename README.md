# 🛍️ Customer Segmentation using K-Means Clustering

This project performs **customer segmentation** using the **K-Means Clustering** algorithm on the `Mall_Customers.csv` dataset. The goal is to group mall customers based on their **annual income** and **spending score**, helping businesses to understand customer behavior and make data-driven marketing decisions.

---

## 📊 Problem Statement

Businesses often face the challenge of treating all customers the same. But in reality, customers are diverse in how much they earn and how they spend. This project segments customers into distinct groups so companies can:
- Target ads more effectively
- Personalize services
- Boost customer retention

---

## 💡 Features Used for Clustering

- **Annual Income (k$)**
- **Spending Score (1–100)**

---

## 🧪 Steps Involved

1. **Data Preprocessing**
   - Checking for missing and duplicate values
   - Exploratory Data Analysis (EDA)
   - Selecting relevant features for clustering

2. **Finding Optimal Clusters**
   - Used the **Elbow Method** to determine the best number of clusters (found to be `7`)

3. **Modeling**
   - Applied `KMeans` clustering with `n_clusters=7`
   - Visualized clusters using a 2D scatter plot

4. **Cluster Interpretation**
   - Identified clusters like high-income low spenders, low-income high spenders, average customers, etc.

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer_segmentation.git
   cd customer_segmentation
    ```
2. Install the required dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the script:
   ```
   python customer_segmentation.py
   ```
