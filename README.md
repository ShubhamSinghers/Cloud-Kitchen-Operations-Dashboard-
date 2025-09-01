# 🍴 Cloud Kitchen Operations Dashboard  

This project provides an **interactive Power BI dashboard** that analyzes and visualizes the operational performance of a cloud kitchen.  
It helps track **sales, delivery performance, revenue trends, customer satisfaction, and staff efficiency** to support data-driven decision-making.  

---

## 📌 Project Summary  
- Developed an **end-to-end BI solution** using Python (for data cleaning) and Power BI (for visualization).  
- Analyzed **500+ cloud kitchen order records** to uncover operational inefficiencies.  
- Built a **dynamic dashboard** to help management optimize kitchen processes, delivery efficiency, and menu strategy.  

---

## 📊 Features of the Dashboard  
✅ **KPIs:** Avg. customer rating, prep time, delivery duration, order value  
✅ **Comparisons:** Kitchen staff & delivery partner efficiency  
✅ **Forecasting:** Order volume predictions using Power BI analytics  
✅ **Menu Composition:** Item popularity insights (Biryani, Burger, Pizza, etc.)  
✅ **Time Trends:** Demand patterns by day, week, and time slot  
✅ **Interactive Controls:** Slicers & filters for user-driven analysis  

---

## 🛠️ Tools & Technologies  
- **Power BI** → Dashboard design & DAX calculations  
- **Python (pandas, matplotlib)** → Data cleaning & preprocessing  
- **Excel / CSV** → Raw data storage  
- **GitHub** → Version control & project sharing  

---

## 🧹 Data Preparation & Cleaning (Python)  
The raw dataset contained typical business issues, including missing values, inconsistent formats, and duplicates.  

Steps performed:  
- Standardized dates & times (`OrderTime`, `PrepStart`, `DeliveryTime`)  
- Removed duplicates & handled null values (median imputation/domain estimation)  
- Standardized text fields (staff, partner, menu items)  
- Converted numeric fields (`OrderValue`, `CustomerRating`) to correct types  
- Computed new metrics (prep time, delivery time, total duration)  
- Exported the cleaned dataset for visualization  

---

## 📈 Dashboard Insights  
- ⏱️ **Prep Time:** Avg. ~17 mins, with variability across staff → training needed  
- 🚴 **Delivery Time:** Avg. ~34 mins, differences across delivery partners → optimize routing/incentives  
- ⭐ **Customer Ratings:** Avg. 2.25/5 → highlight inconsistency in service quality  
- 📦 **Menu Composition:** Biryani, Burger, Pizza are bestsellers; low-demand items need marketing/menu adjustment  
- 📊 **Demand Trends:** Evening & weekends peak → plan staffing & promotions accordingly  

---

## 💡 Recommendations  
- Standardise kitchen procedures & train slower staff  
- Introduce **performance tracking** for delivery partners  
- Collect customer feedback & address top complaints (taste, packaging, timeliness)  
- Adjust staffing & inventory during peak days  
- Redesign menu strategy around high & low demand items  

---

## 🖼️ PYTHON CODE PREVIEW 

### 🔹Data Generation   
![PYTHON_CODE](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/f56ce3b8c8787be0b43f94f85ef785a348269828/Snap.png)  

### 🔹data exploration and quality checks
![Dashboard 2](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/f56ce3b8c8787be0b43f94f85ef785a348269828/Snap%20(2).png)  

### 🔹  Data Cleaning & Preparation
![Dashboard 3](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/f56ce3b8c8787be0b43f94f85ef785a348269828/Snap%20(1).png)  

## 🖼️ Dashboard Preview  

### 🔹 cloud_kitchen operation Dashboard
![Dashboard 1](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/17b14950e00465093d0c6fdb4745993ed9feb37b/cloud_kitchen%20operation%20Dashboard-1.png)

---

## 📂 Project Files
- [cloud_kitchen operation Dashboard.pbix](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/17b14950e00465093d0c6fdb4745993ed9feb37b/cloud_kitchen%20operation%20Dashboard.pbix) → Power BI file  
- [Cloud-Kitchen-Operations-Dashboard](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/17b14950e00465093d0c6fdb4745993ed9feb37b/cloud_kitchen%20operation%20Dashboard-1.png) → Dashboard screenshot  
- [README.md](README.md) → Documentation  

## 📊 Dataset
- **[Messy Orders (CSV)](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/17b14950e00465093d0c6fdb4745993ed9feb37b/messy_cloud_kitchen_500%20(1).csv)** – raw dataset with duplicates & nulls.  
- **[Clean Orders (CSV)](https://github.com/ShubhamSinghers/Cloud-Kitchen-Operations-Dashboard-/blob/17b14950e00465093d0c6fdb4745993ed9feb37b/cleaned_cloud_kitchen_500.csv)** – after cleaning in Python.

## 🤝 Connect
If you enjoyed this project, please feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/shubham-singh1s/) or explore more of my projects on [GitHub](https://github.com/ShubhamSinghers).


