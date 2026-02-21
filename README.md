# OIB-SIP Data Analytics Internship  
## Task 1 – Customer Segmentation Using K-Means Clustering  

---

## 📖 Project Overview  

This project was completed as part of the AICTE OIB-SIP Data Analytics Internship.  
The objective of this task is to analyze customer purchasing behavior and segment customers into meaningful groups using K-Means Clustering.

Customer segmentation helps businesses understand different types of customers and design targeted marketing strategies.

---

## 🎯 Problem Statement  

To analyze customer behavior and segment customers based on:

- Income
- Total Spending
- Recency of purchase

The goal is to identify high-value and low-value customer groups and generate business-driven insights.

---

## 📊 Dataset Description  

- Total Records: 2205 customers  
- Total Features: 39  
- Key Attributes Used:
  - Income  
  - Total Spending  
  - Recency  

The dataset was clean and contained no missing values.

---

## ⚙️ Steps Performed  

1. Data Loading using Pandas  
2. Data Understanding & Descriptive Statistics  
3. Feature Selection (Income & Total Spending)  
4. Applying K-Means Clustering  
5. Segmentation into 4 clusters  
6. Data Visualization using Scatter Plot  
7. Interpretation of cluster behavior  

---

## 🛠 Tools & Technologies Used  

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn (K-Means Clustering)  
- Jupyter Notebook  

---

## 📈 Cluster Distribution  

- Cluster 0 – 578 customers  
- Cluster 1 – 510 customers  
- Cluster 2 – 337 customers  
- Cluster 3 – 596 customers  

---

## 🔍 Cluster Analysis  

1. *Cluster 0* – Low Income, Low Spending  
2. *Cluster 1* – High Income, High Spending  
3. *Cluster 2* – Very High Income (Premium Customers)  
4. *Cluster 3* – Medium Income, Moderate Spending  

---

## 💡 Key Insights  

- Cluster 2 generates the highest revenue despite having fewer customers  
- Cluster 0 contributes the least revenue  
- Majority of customers fall under moderate spending category  
- Premium customers require focused retention strategies  

---

## 📌 Business Recommendations  

- Provide loyalty rewards for premium customers (Cluster 2)  
- Offer premium deals for high-income customers (Cluster 1)  
- Provide discount campaigns for low-income segment (Cluster 0)  
- Improve engagement strategies for moderate customers (Cluster 3)  

---

## ✅ Conclusion  

The project successfully segmented customers into four distinct groups using K-Means clustering.  
The analysis provided meaningful business insights that can help improve marketing strategies and customer targeting.

---

## 📂 Files Included  

- Customer_Segmentation.ipynb  
- Dataset file  
- Presentation PPT
