# 📊 Power BI – Basic Visualizations Project

## 🎯 Project Objective
This project is created to **learn and demonstrate basic Power BI visualizations** using a simple sales dataset.  
The main goal is to understand:
- Which visual to use 📌
- Which columns go where 🧩
- Why that visual is useful 💡

This project is **beginner-friendly** and does **not use DAX**, focusing only on visuals.

---

## 📁 Dataset Used
**File:** `data/visual_demo_data.xlsx`

### Columns in Dataset
| Column Name | Description |
|------------|-------------|
| Month | Month of sales |
| Sales | Actual sales value |
| Target | Target sales value |
| Category | Product category (A, B, C) |

---

## 🗂️ Project Folder Structure
powerbi-basic-visuals/
│
├── data/
│ └── visual_demo_data.xlsx
├── powerbi/
│ └── PowerBI_Basic_Visuals.pbix
├── screenshots/
│ └── visualization images
└── README.md


---

## 📊 Visualizations Explained

### 1️⃣ Table – *Sales Data Table*
📌 **Why this visual?**  
Used to display **raw data** clearly.

🧩 **Columns Used**
- Rows: Month, Sales, Target, Category

💡 **Insight**
- Helps users understand the dataset before analyzing charts

---

### 2️⃣ Bar Chart – *Sales vs Target*
📌 **Why this visual?**  
Best for **comparing two values**.

🧩 **Columns Used**
- Y-Axis: Month  
- X-Axis: Sales (Sum), Target (Sum)

💡 **Insight**
- Shows whether sales met or missed targets

---

### 3️⃣ Bar Chart – *Sales by Month*
📌 **Why this visual?**  
Best for **ranking and comparison**.

🧩 **Columns Used**
- Y-Axis: Month  
- X-Axis: Sales (Sum)

💡 **Insight**
- Identifies highest and lowest performing months

---

### 4️⃣ Line Chart – *Sales and Target Trend*
📌 **Why this visual?**  
Used to show **trends over time**.

🧩 **Columns Used**
- X-Axis: Month  
- Y-Axis: Sales (Sum), Target (Sum)

💡 **Insight**
- Understands upward/downward trends month by month

---

### 5️⃣ Stacked Column Chart – *Monthly Sales by Category*
📌 **Why this visual?**  
Shows **composition over time**.

🧩 **Columns Used**
- X-Axis: Month  
- Y-Axis: Sales (Sum)  
- Legend: Category

💡 **Insight**
- Shows how each category contributes to total sales per month

---

### 6️⃣ Pie Chart – *Sales Contribution by Category*
📌 **Why this visual?**  
Used for **part-to-whole comparison**.

🧩 **Columns Used**
- Values: Sales (Sum)  
- Legend: Category

💡 **Insight**
- Shows percentage contribution of each category

---

### 7️⃣ Donut Chart – *Sales Distribution by Category*
📌 **Why this visual?**  
Alternative to pie chart with better readability.

🧩 **Columns Used**
- Values: Sales (Sum)  
- Legend: Category

💡 **Insight**
- Same as pie chart, visually cleaner

---

### 8️⃣ Card – *Total Sales*
📌 **Why this visual?**  
Used to highlight **key KPIs**.

🧩 **Columns Used**
- Values: Sales (Sum)

💡 **Insight**
- Shows total sales at a glance

---

### 9️⃣ Slicer – *Filter by Category*
📌 **Why this visual?**  
Adds **interactivity**.

🧩 **Columns Used**
- Field: Category

💡 **Insight**
- Allows users to filter all visuals by category

---

## 🛠️ Tools Used
- 🟡 Power BI Desktop  
- 🟢 Microsoft Excel  
- 🐙 GitHub  

---

## ✅ Key Learnings
- Understanding Power BI visual types
- Choosing the right visual for the right question
- Basic report layout and formatting
- Using GitHub for portfolio projects

---

✨ *This project is part of my Power BI learning journey and serves as a visual reference for beginners.*
