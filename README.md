# OIBSIP_DataScience_Task2

## 📌 Objective
The objective of this task was to perform **Customer Segmentation** on an online retail dataset using **RFM analysis** and **K-Means clustering** to identify meaningful customer groups for targeted marketing.

## 📂 Files in this Repository
- `third.ipynb` → Jupyter Notebook containing code and analysis.  
- `Online Retail.xlsx` (dataset, if allowed to upload).  

## ⚙️ Steps Performed
1. Imported and cleaned dataset.  
   - Removed missing values (e.g., CustomerID).  
   - Filtered out invalid transactions (negative prices/quantities).  
   - Created a new feature `TotalPrice`.  
2. Performed **RFM (Recency, Frequency, Monetary) analysis**.  
3. Standardized features using **StandardScaler**.  
4. Applied **K-Means clustering** to segment customers.  
5. Evaluated clusters with **Silhouette Score**.  
6. Generated business insights and recommendations.  

## 🛠️ Tools & Libraries Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- scikit-learn (KMeans, StandardScaler, silhouette_score)  

## 📊 Outcomes
- Customers were segmented into distinct groups based on their **RFM values**.  
- Example segments:  
  - **High Monetary + Low Recency** → Loyal high spenders, target with loyalty rewards.  
  - **Low Frequency + High Recency** → Customers at risk of churn, reactivate with discounts.  
  - **Low Monetary + Low Frequency** → Low-value customers, target with bulk offers.  

## 🎥 Demo
(A short demo video link if recorded)

## ✨ Recommendations
- Use segmentation results to design **personalized marketing campaigns**.  
- Offer **loyalty programs** for high spenders.  
- Provide **discounts or win-back offers** to re-engage inactive customers.  
