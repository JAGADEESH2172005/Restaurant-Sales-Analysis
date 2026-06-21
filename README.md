# 🍽️ Restaurant Sales Analysis Dashboard

## 📖 Introduction

The Restaurant Sales Analysis Dashboard is a Business Intelligence project developed to analyze restaurant sales data and uncover actionable insights. The project leverages data analytics techniques and interactive dashboarding to help businesses understand customer behavior, sales trends, payment preferences, and restaurant performance.

Using historical transaction data stored in Parquet format, the dashboard provides a comprehensive view of business performance through visually appealing and interactive reports.

---

## 🎯 Problem Statement

Restaurant businesses generate large volumes of transactional data daily. Analyzing this data manually is time-consuming and often fails to reveal important business patterns.

The objective of this project is to:

- Monitor overall sales performance.
- Identify peak revenue-generating periods.
- Understand customer ordering preferences.
- Analyze payment trends.
- Compare restaurant performance.
- Support strategic business decision-making through data visualization.

---

## 🏢 Business Requirements

The management team requires answers to the following questions:

- What is the total revenue generated?
- Which restaurants generate the highest revenue?
- Which order type is most popular?
- What payment modes are preferred by customers?
- Which time slots contribute the most revenue?
- What is the Average Order Value (AOV)?
- How do sales vary across different days?

The dashboard addresses all these business requirements effectively.

---

## 📂 Dataset Overview

The dataset contains restaurant transaction records collected from multiple restaurant outlets.

### Data Attributes

| Attribute | Description |
|------------|------------|
| fseName | Restaurant Name |
| revenue | Revenue Generated |
| orderTypes | Type of Order |
| payment_mode | Payment Method |
| invoicePaymentStatus | Payment Status |
| status | Order Status |
| day_name | Day of Transaction |
| time_slot | Time Slot |
| order_id | Unique Order Identifier |

### Dataset Format

- File Format: Parquet (.parquet)
- Data Type: Structured Data
- Domain: Food & Restaurant Industry

---

## 🧹 Data Preparation

Before analysis, the dataset was prepared to ensure accuracy and consistency.

### Activities Performed

- Data inspection
- Missing value handling
- Duplicate record verification
- Data type validation
- Data standardization
- Quality checks

The cleaned dataset was then used for exploratory analysis and dashboard creation.

---

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to understand the underlying patterns and trends within the dataset.

### Revenue Analysis

- Total Revenue Generated
- Revenue Distribution
- Revenue by Time Slot
- Revenue by Restaurant

### Order Analysis

- Total Orders
- Orders by Type
- Order Distribution

### Payment Analysis

- Revenue by Payment Method
- Payment Usage Frequency

### Restaurant Performance Analysis

- Top Performing Restaurants
- Revenue Contribution by Restaurant
- Average Order Value Analysis

---

## 📈 Dashboard Features

### KPI Cards

The dashboard displays key business metrics:

✅ Total Revenue

✅ Total Orders

✅ Average Order Value (AOV)

---

### Interactive Filters

Users can dynamically filter reports using:

- Order Type
- Payment Mode
- Invoice Payment Status
- Order Status

---

### Visualizations Included

#### Revenue Analysis

- Revenue by Time Slot
- Revenue by Restaurant

#### Order Analysis

- Orders by Order Type

#### Payment Analysis

- Revenue by Payment Mode
- Payment Distribution by Day

#### Detailed Performance Table

- Restaurant-wise Revenue
- Total Orders
- Average Order Value

---

## 🔍 Key Insights

### Revenue Insights

- Afternoon sales contribute the highest revenue.
- Night sales contribute the lowest revenue.
- Revenue distribution varies significantly among restaurants.

### Customer Ordering Insights

- Dine-In is the most preferred order type.
- Takeaway contributes a significant portion of orders.
- Delivery orders account for a smaller percentage.

### Payment Insights

- UPI is the dominant payment mode.
- Cash remains a widely used payment option.
- Card and gateway payments contribute a smaller share.

### Business Insights

- A few restaurants contribute a major portion of total revenue.
- Average Order Value helps measure customer spending behavior.
- Peak business activity occurs during specific time slots.

---

## 🛠️ Technology Stack

### Data Processing

- Python
- Pandas
- NumPy

### Data Visualization

- Power BI

### Data Storage

- Parquet File Format

### Development Environment

- Jupyter Notebook
- VS Code

---

## 📸 Dashboard Preview

<img width="741" height="415" alt="Screenshot 2026-06-21 180931" src="https://github.com/user-attachments/assets/de89f798-dc05-4d5a-aab8-35cf23dcb567" />


---

## 📁 Project Structure

```text
Restaurant-Sales-Analysis/
│
├── Data/
│   ├── Restaurant_Sales.parquet          # Raw dataset
│   └── Restaurant_Sales_Cleaned.xlsx     # Cleaned dataset
│
├── Analysis/
│   └── Restaurant_Sales_Analysis.ipynb   # Data Cleaning & EDA
│
├── Dashboard/
│   └── Restaurant_Sales_Dashboard.pbix   # Power BI Dashboard
│
├── Images/
│   └── dashboard.png                     # Dashboard Screenshot
│
└── README.md                             # Project Documentation
```
## 🚀 Project Workflow

1. Data Collection
2. Data Cleaning & Validation
3. Exploratory Data Analysis
4. Business Insight Generation
5. Dashboard Development
6. Performance Monitoring

---

## 📌 Business Impact

This dashboard helps restaurant management:

- Monitor sales performance in real-time.
- Identify high-performing restaurants.
- Understand customer purchasing behavior.
- Improve operational efficiency.
- Support data-driven decision-making.

---

## 🎓 Learning Outcomes

Through this project, the following skills were applied:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Business Intelligence
- Dashboard Design
- Data Visualization
- KPI Development
- Business Insight Generation
- Power BI Reporting

---

## 🔮 Future Enhancements

- Sales Forecasting using Machine Learning
- Customer Segmentation
- Profitability Analysis
- Real-Time Dashboard Integration
- Customer Retention Analysis
- Restaurant Recommendation System

---

## 👨‍💻 Author

### Jagadeesh Mannuru

Aspiring Data Analyst | Power BI Developer | Python Enthusiast

**Skills:** Python, SQL, Power BI, Data Analytics, Data Visualization

---

⭐ If you found this project useful, consider giving it a star on GitHub.
