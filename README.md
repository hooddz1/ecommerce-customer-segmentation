# 🛒 E-Commerce Customer Segmentation (RFM Analysis)

## 📌 Project Overview
This project analyzes Brazilian E-Commerce data (Olist Dataset) to segment customers based on their purchasing behavior. The goal is to identify high-value customers ("Champions") and at-risk customers to optimize marketing strategies.

**Tools Used:** Python (Pandas), RFM Analysis, Tableau.

## 📊 The Dashboard
Check out the interactive dashboard here:
👉 **https://public.tableau.com/views/BrazilianolistE-CommerceCustomerSegmentation/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link**

*(Saran: Masukkan Screenshot Dashboard kamu di sini biar visual)*
<img width="1653" height="735" alt="image" src="https://github.com/user-attachments/assets/63419412-e2d7-44ac-b6ba-ca292f4085e6" />


## 🔍 Key Insights
1.  **The Pareto Principle:** Only **X%** of customers ("Champions" & "Loyal") contribute to **Y%** of total revenue.
2.  **Retention Alert:** A significant portion of customers are in the "At Risk" segment, indicating a need for immediate re-engagement campaigns.
3.  **High Value:** The average spend of a "Champion" is **$295**, compared to just **$104** for "Potential" customers.

## ⚙️ Methodology
1.  **Data Cleaning:** Handled missing values and converted data types.
2.  **Feature Engineering:** Created RFM metrics (Recency, Frequency, Monetary) from transaction history.
3.  **Scoring:** Used Quintiles (1-5 scale) to score customers based on their RFM values.
4.  **Segmentation:** Grouped customers into 5 categories (Champions, Loyal, Potential, At Risk, Lost).

## 📂 File Structure
- `notebook.ipynb`: The Python code for data processing and RFM scoring.
- `rfm_analysis_result.csv`: The processed dataset used for visualization.
