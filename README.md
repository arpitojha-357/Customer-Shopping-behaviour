# 🛍️ Customer Shopping Behavior Analysis Dashboard  

### 🎯 *Analyzing shopping trends and customer insights using Python, SQL, and Power BI.*

---

## 📊 Project Overview  
This project provides a **comprehensive analysis of customer shopping behavior**, combining the power of **Python for data preparation**, **SQL for analytical querying**, and **Power BI for data visualization**.  
It aims to uncover actionable insights around **spending patterns, customer demographics, product preferences, and subscription behavior**, driving **data-backed business decisions**.

---

## 🧩 Dataset Summary  
| Attribute | Description |
|------------|-------------|
| **Total Rows** | 3,900 |
| **Total Columns** | 18 |
| **Key Attributes** | Age, Gender, Subscription Status, Item Purchased, Category, Purchase Amount, Review Rating, Discount Applied, Frequency of Purchases, Shipping Type |
| **Missing Data** | 37 missing values in Review Rating column (imputed using median) |

---

## 🔍 Project Workflow  

### **1️⃣ Python – Data Preparation & Cleaning**
- Imported the dataset using **pandas**.  
- Conducted initial exploration with `.info()` and `.describe()`.  
- Imputed missing values in *Review Rating* using category-wise median.  
- Standardized column names for clarity.  
- Created new engineered features:
  - `age_group`
  - `purchase_frequency_days`
- Integrated the cleaned dataset into **PostgreSQL** for SQL-based querying.  

---

### **2️⃣ SQL – Business Transaction Analysis**
Data-driven insights were derived through SQL queries such as:  
- Revenue contribution by **Gender** and **Age Group**.  
- **Top 5 Products** by review rating.  
- **Subscription impact** on customer spending and revenue.  
- **Shipping method** comparison (Standard vs Express).  
- Identification of **discount-dependent products**.  
- **Customer segmentation**: New, Returning, Loyal customers.  

---

### **3️⃣ Power BI – Dashboard Visualization**
An interactive **Power BI dashboard** was developed to visualize all major insights and KPIs:  

#### 🔹 Key Metrics:
- 🧍 **Total Customers:** 3.9K  
- 💰 **Average Purchase Amount:** $59.76  
- ⭐ **Average Review Rating:** 3.71  
- 📦 **Top Product Categories:** Clothing, Accessories, Footwear, Outerwear  
- 🎯 **Subscription Impact:** +68% higher spending among subscribers  

#### 🔹 Dashboard Features:
- Revenue & Sales by Category  
- Revenue by Age Group  
- Customer Segmentation Overview  
- Shipping Type Performance  
- Discount vs Non-Discount Purchase Analysis  

---

## 🧠 Insights Generated  
- **Female customers** generate slightly higher total revenue than male customers.  
- **Express shipping users** spend **12% more per purchase**.  
- **Subscribers** account for **45% of total revenue** and have **68% higher spending**.  
- **Adults aged 25–40** contribute the highest revenue share.  
- **Clothing** dominates all product categories in both volume and revenue.  

---

## 💡 Business Recommendations  
✅ **Boost Subscriptions:** Highlight exclusive offers for subscribers.  
✅ **Introduce Loyalty Programs:** Reward repeat buyers for sustained engagement.  
✅ **Targeted Marketing:** Focus on express-shipping users and high-value segments.  
✅ **Product Positioning:** Prioritize top-rated products in promotional campaigns.  

---

## 🧰 Tech Stack  
| Tool | Purpose |
|------|----------|
| **Python (pandas, numpy)** | Data cleaning and preparation |
| **MySQL (SQL)** | Business analysis and querying |
| **Power BI** | Visualization and dashboard creation |
| **Excel/CSV** | Data extraction and transformation |

---

## 🚀 Outcome  
This project demonstrates how **data analytics and visualization** can transform raw customer data into **strategic business insights**.  
It equips organizations to **optimize marketing efforts**, **enhance customer engagement**, and **improve decision-making** using a unified analytical approach.

---

## 🌐 Dashboard Preview  
![Customer Behavior Dashboard](https://github.com/Shivam4410/Customer-Shopping-Behavior-Analysis/blob/main/BI%20Dashboard.png)

---

## 👨‍💻 Developed by  
**Arpit Ojha**  
Aspiring Data Analyst | Skilled in Power BI, Python, SQL, and Excel  


---

> ⚡ *“Turning raw data into actionable business intelligence through modern analytics.”*
