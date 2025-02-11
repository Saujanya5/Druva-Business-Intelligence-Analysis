# 🏆 Druva Business Intelligence Analysis

## 📌 Project Overview
This project analyzes Druva's customer accounts, revenue patterns, and license usage to derive meaningful insights. The goal is to help the business understand account behavior, revenue growth, and storage utilization trends.

📄 **[View the Full Report (PDF)](Business Intelligence Analysis.pdf)**

---

## 📂 Dataset Structure

### **1️⃣ Accounts Table**
| Column Name         | Description                                        |
|---------------------|----------------------------------------------------|
| ACCOUNT_ID         | Unique identifier for Druva customer accounts.     |
| REGION            | Region where the customer is located.               |
| INDUSTRY         | Industry to which the customer belongs.             |
| NUMBER_OF_EMPLOYEES | Number of employees in the customer account.      |
| CUSTOMER_SINCE     | Date when the account became a paying customer.    |

---

### **2️⃣ ARR (Annual Recurring Revenue) Table**
| Column Name         | Description                                                 |
|---------------------|-------------------------------------------------------------|
| ACCOUNT_ID         | Unique identifier for Druva customer accounts.               |
| ARR_MONTH         | The month of the recorded ARR.                                |
| ENDPOINTS_ARR      | ARR from the endpoints product.                             |
| EDITION           | Edition of the endpoints product (Enterprise, Elite, etc.).  |
| NON_ENDPOINTS_ARR | ARR outside of endpoints products.                           |
| NUMBER_OF_PRODUCTS | Total number of Druva products used by the customer.        |

---

### **3️⃣ Total License Usage Table**
| Column Name         | Description                                                      |
|---------------------|------------------------------------------------------------------|
| SNAPSHOT_DATE     | Date of observed product usage.                                 |
| ACCOUNT_ID       | Unique identifier for Druva customer accounts.                   |
| CUSTOMER_ID      | Unique identifier for the customer.                              |
| ACTIVE_USERS_ENDPOINT | Number of active users for the endpoints product.          |
| LICENSED_USERS_ENDPOINT | Total licensed users for the endpoints product.         |
| LICENSED_STORAGE | Total amount of storage purchased for endpoints.                 |
| FRONT_END_STORAGE | Total source size data being protected by Druva.                |
| DEDUPED_STORAGE  | Amount of data stored after deduplication in Druva's platform.   |

---

## 📊 Key Insights from Analysis

- **Customer Distribution**: The majority (68%) of Druva's customers are from the Americas, followed by APAC (17%) and EMEA (15%).
- **Revenue Growth**: ARR increased by **1.64%** in 2023, driven by the **Enterprise Edition (30.23M)** and the **Manufacturing industry (14.6M)**.
- **License Utilization**: Improved from **76.5% in 2021** to **81% in 2023**, showing better alignment with customer needs.
- **Storage Optimization**: The **deduplication ratio is 4.2x**, meaning every 4.2 TB of source data requires only 1 TB of actual storage.


## 🚀 Business Recommendations

✅ Expand presence in **APAC & EMEA** to tap into new growth opportunities.  
✅ Focus on the **Manufacturing industry**, which generates the highest ARR.  
✅ Investigate ARR decline in the **Media & Publishing sector** to identify retention strategies.  
✅ Optimize **license allocation & storage management** to enhance cost efficiency.  

---

## 🛠 Technologies Used

- **SQL** for data extraction and transformation
- **Snowflake** for data storage and querying 
- **Power BI** for dashboard creation & visualization
- **Excel** for initial data processing and analysis

---

## 📢 Future Enhancements

- 📊 **Predictive Analysis**: Implement machine learning to forecast ARR trends.  
- 🔍 **Churn Analysis**: Identify at-risk accounts and propose retention strategies.  
- 📈 **Interactive Dashboard**: Create a dynamic Power BI dashboard for live tracking.

---

 
