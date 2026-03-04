# Ferns-and-Petals-Excel-Sales-Dashboard


# 📊 Dashboard Preview

<img width="940" height="435" alt="image" src="https://github.com/user-attachments/assets/1feea9c1-5e83-4655-bb6b-d831f92b2c3e" />


---

# 📌 Project Objective

Ferns & Petals specializes in delivering gifts for occasions such as:

- Diwali
- Raksha Bandhan
- Holi
- Valentine's Day
- Birthdays
- Anniversaries

The goal of this project is to analyze the company’s dataset to help answer **important business questions** that can improve sales strategy and customer satisfaction.

---

# 🧠 Business Questions Answered

1. What is the **total revenue generated**?
2. What is the **average order delivery time**?
3. How do **monthly sales change throughout the year**?
4. Which **products generate the highest revenue**?
5. How much do **customers spend on average**?
6. How do **different product categories perform**?
7. Which **cities place the most orders**?
8. Does **order quantity affect delivery time**?
9. Which **occasions generate the highest revenue**?
10. Which **products are most popular during specific occasions**?

---

# 📁 Dataset

The project uses **three datasets**.

| Dataset | Description |
|------|-------------|
| Customers | Customer information |
| Orders | Order details including order and delivery time |
| Products | Product details including price |

---

# ⚙️ Data Analysis Process

## 1️⃣ Data Extraction
Imported all CSV files into Excel and converted them into structured tables.

---

## 2️⃣ Data Cleaning

- Checked for missing values
- Fixed data formatting
- Standardized columns

---

## 3️⃣ Data Transformation

Created additional analytical columns:

- Order Month
- Order Hour
- Delivery Month
- Delivery Hour
- Order Delivered Days

`Order Delivered Days` calculates the **number of days required for delivery**.

---

## 4️⃣ Data Modeling

Merged **Orders** and **Products** tables using:

```

Product ID

```

This allowed retrieving the **Price (INR)** column for revenue calculations.

All tables were loaded into the **Excel Data Model** and relationships were created.
<img width="940" height="523" alt="image" src="https://github.com/user-attachments/assets/0e8eb487-ca66-4c73-a81f-fc1ccf12401e" />


---

## 5️⃣ Data Analysis

Used **Pivot Tables** to analyze:

- Revenue trends
- Customer spending
- Product performance
- City order distribution
- Delivery time analysis

---

## 6️⃣ Dashboard Creation

Created an **interactive Excel dashboard** containing:

- Revenue KPI
- Monthly Sales Chart
- Top Products Chart
- Category Sales Chart
- Top Cities Chart
- Occasion Revenue Comparison
- Product Popularity Slicer

---

# 📈 Key Insights

## 💰 Total Revenue

```

₹3,520,984

```

---

## 🚚 Average Delivery Time

```

5.53 Days

```

On average, orders take **5–6 days** to be delivered.

---

## 💳 Average Customer Spending

```

₹3520

```

Customers spend approximately **₹3520 per order**.

---

# 📊 Analysis Visualizations

## Monthly Sales Performance

<img width="698" height="515" alt="image" src="https://github.com/user-attachments/assets/3c59e742-bf53-4136-86cc-af30db34f335" />




---

## Top 10 Products by Revenue

<img width="701" height="438" alt="image" src="https://github.com/user-attachments/assets/6a475882-f848-43a4-9581-6c77af9d273a" />


---

## Sales by Category

<img width="465" height="365" alt="image" src="https://github.com/user-attachments/assets/31aa77c9-83ff-4286-9825-9647e7ebcc34" />


---

## Top 10 Cities by Orders

<img width="479" height="465" alt="image" src="https://github.com/user-attachments/assets/f89033d9-4342-4b79-902f-e162c883a95a" />


---

## Revenue by Occasion

![Occasion Revenue](screenshots/occasion_revenue.png)

---

## Product Popularity by Occasion

<img width="534" height="353" alt="image" src="https://github.com/user-attachments/assets/c13aab43-a50a-4bfb-bd7a-d8bbab34b130" />


---

# 🔎 Order Quantity vs Delivery Time

Analysis shows **no strong correlation** between order quantity and delivery time.

This indicates that **larger orders do not significantly delay deliveries**.

---

# 🛠 Tools Used

| Tool | Purpose |
|-----|--------|
| Microsoft Excel | Data Analysis |
| Pivot Tables | Data Aggregation |
| Excel Data Model | Data Relationships |
| Charts & Visualizations | Dashboard Creation |

---

# 📂 Project Structure

```

FNP-Sales-Analysis
│
├── dataset
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
│
├── dashboard
│   └── fnp_sales_dashboard.xlsx
│
├── screenshots
│   ├── dashboard.png
│   ├── monthly_sales.png
│   ├── top_products.png
│   ├── category_sales.png
│   ├── cities_orders.png
│   ├── occasion_revenue.png
│   └── product_popularity.png
│
└── README.md

```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- Pivot Table Analysis
- Dashboard Development
- Business Insight Generation

---

# 📌 Project Outcome

This project demonstrates how raw business data can be transformed into **actionable insights using Excel analytics**.

The final dashboard helps businesses:

- Monitor revenue performance
- Understand customer spending behavior
- Identify top-performing products
- Analyze delivery efficiency

---

# 👨‍💻 Author

**Pratham Baraskar**

Aspiring **Data Scientist / Data Analyst**

📍 India

---

# ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to explore the dashboard!
