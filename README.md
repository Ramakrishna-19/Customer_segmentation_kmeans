# Customer Segmentation using K-Means Clustering

This project performs customer segmentation using the K-Means clustering algorithm on a mall customer dataset. The goal is to group customers based on their purchasing behavior, allowing businesses to target specific customer groups more effectively.

## 🧠 Objective

To identify distinct customer segments based on **Annual Income** and **Spending Score**, enabling targeted marketing strategies and better business decisions.

## 📊 Dataset

- **Source:** Mall Customers Dataset
- **Features used:**
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## 🔧 Tools & Libraries

- Python
- Pandas
- Seaborn & Matplotlib (for visualization)
- Scikit-learn (for KMeans & StandardScaler)

## 📈 Workflow

1. Loaded the mall customer dataset.
2. Visualized income and spending distributions.
3. Standardized features to prepare for clustering.
4. Used the **Elbow Method** to determine the optimal number of clusters (`k`).
5. Applied **K-Means Clustering** to segment customers.
6. Visualized clusters and interpreted customer group behaviors.

## 💡 Insights

- Identified distinct customer segments:
  - **High income, high spenders** (loyal customers)
  - **Low income, high spenders** (deal seekers)
  - **Average income and average spenders**
  - **Low spenders**
- These clusters can help businesses tailor promotions, loyalty programs, and product offerings.

## 📂 Files Included

- `Customer_Segmentation.ipynb` – Full Jupyter Notebook with code, visualizations, and analysis.
- `README.md` – Project overview and documentation.

## 📌 Future Improvements

- Include additional features like `Age`, `Gender`, or `Frequency`.
- Try other clustering algorithms (e.g., DBSCAN, Hierarchical).
- Create an interactive dashboard with Streamlit or Power BI.

---

