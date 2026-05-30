# 📊 Synent Task 5: Sales Analysis Project

## 📌 Project Overview

This project was completed as part of the **Synent Technologies Data Science Internship Program**.

The objective of this project is to analyze retail sales data and uncover meaningful business insights through data cleaning, exploratory data analysis (EDA), statistical summaries, and data visualization. The analysis helps identify sales trends, profit drivers, customer behavior, and opportunities for business growth.

---

## 🎯 Objectives

* Analyze overall sales performance
* Identify top-performing categories and sub-categories
* Evaluate regional sales and profit trends
* Study the impact of discounts on profitability
* Generate actionable business recommendations
* Create visual reports for decision-making

---

## 🗂 Dataset Information

**Dataset:** Sample Superstore Dataset

The dataset contains information about:

* Orders
* Customers
* Products
* Sales
* Profit
* Quantity
* Discounts
* Regions
* Categories

### Key Features

| Column        | Description             |
| ------------- | ----------------------- |
| Order ID      | Unique order identifier |
| Order Date    | Date of order           |
| Customer Name | Customer information    |
| Segment       | Customer segment        |
| Category      | Product category        |
| Sub-Category  | Product sub-category    |
| Sales         | Revenue generated       |
| Quantity      | Units sold              |
| Discount      | Discount applied        |
| Profit        | Profit earned           |
| Region        | Sales region            |
| State         | Customer location       |

---

## 🛠 Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* YData Profiling

### Environment

* Jupyter Notebook

---

## 🔄 Data Science Workflow

### 1. Data Collection

* Loaded sales dataset
* Verified dataset structure

### 2. Data Cleaning

* Missing value analysis
* Duplicate removal
* Datatype conversion
* Date formatting

### 3. Exploratory Data Analysis (EDA)

* Sales analysis
* Profit analysis
* Regional analysis
* Customer segment analysis
* Category-wise analysis

### 4. Data Visualization

<table border="1" cellpadding="10" style="text-align: center; border-collapse: collapse;">
     <thead>
    <tr>
      <th>Monthly Revenue Trend | Line Charts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img width="1031" height="563" alt="download" src="https://github.com/user-attachments/assets/54b1cf29-81c9-4a3b-9d7a-6ce8170c2c43" alt="Bar Charts" width="100" height="100"/>
      </td>
  </tbody>
</table>


<table border="1" cellpadding="10" style="text-align: center; border-collapse: collapse;">
  <thead>
    <tr>
      <th>Top Selling Products | Bar Charts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img width="876" height="614" alt="download" src="https://github.com/user-attachments/assets/83526dbf-ab47-4a1f-acd4-fad7543d3f7e" alt="Top Selling Products" width="100" height="100"/>
      </td>
  </tbody>
   </table>
  
<table border="1" cellpadding="10" style="text-align: center; border-collapse: collapse;">
     <thead>
    <tr>
      <th>Region Wise Profit | Bar Charts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img width="721" height="507" alt="download" src="https://github.com/user-attachments/assets/9fb6015e-6db1-43c5-97da-c157f382d9e1" alt="Region Wise Profit" width="100" height="100"/>
      </td>
  </tbody>
</table>

<table border="1" cellpadding="10" style="text-align: center; border-collapse: collapse;">
     <thead>
    <tr>
      <th>Category Wise Sales | Bar Charts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img width="721" height="507" alt="download" src="https://github.com/user-attachments/assets/9fb6015e-6db1-43c5-97da-c157f382d9e1" alt="Category Wise Sales" width="100" height="100"/>
      </td>
  </tbody>
</table>
  
<table border="1" cellpadding="10" style="text-align: center; border-collapse: collapse;">
  <thead>
    <tr>
      <th> Sales Distribution | Bar Charts </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img width="713" height="470" alt="download" src="https://github.com/user-attachments/assets/a75b8ef3-6be6-44f5-87eb-3fca53fb8258" alt="Sales Distribution" width="100" height="100"/>
      </td>
  </tbody>
   </table>
  
<table border="1" cellpadding="10" style="text-align: center; border-collapse: collapse;">
     <thead>
    <tr>
      <th> Profit Distribution | Bar Charts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img width="713" height="470" alt="download" src="https://github.com/user-attachments/assets/2326e39c-f09e-4f38-8c96-60e75c590019" alt="Profit Distribution" width="100" height="100"/>
      </td>
  </tbody>
</table>

<table border="1" cellpadding="10" style="text-align: center; border-collapse: collapse;">
     <thead>
    <tr>
      <th> Sales vs Profit | Bar Charts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img width="716" height="470" alt="download" src="https://github.com/user-attachments/assets/576b7638-7465-49b6-ab6e-0980da025e07" alt="Bar Charts" width="100" height="100"/>
      </td>
  </tbody>
</table>


### 5. Business Insights

* Identified profit-driving categories
* Evaluated regional performance
* Measured discount impact
* Generated recommendations

---

## 📈 Key Insights

### Sales Performance

* Technology category generated the highest sales.
* Consumer segment contributed significantly to revenue.

### Profitability Analysis

* High discounts negatively impacted profit margins.
* Some products generated strong sales but low profits.

### Regional Analysis

* Western region showed strong sales performance.
* Certain regions required pricing optimization.

### Customer Analysis

* Consumer customers were the primary revenue source.
* Corporate customers delivered stable profitability.

---

## 💡 Business Recommendations

* Reduce excessive discounts on low-margin products.
* Focus marketing efforts on high-performing regions.
* Promote profitable categories aggressively.
* Improve inventory planning using sales trends.
* Monitor loss-making products regularly.

---

## 📊 Visualizations Included

* Sales by Category
* Profit by Category
* Regional Sales Analysis
* Regional Profit Analysis
* Monthly Sales Trend
* Discount vs Profit Analysis
* Correlation Heatmap

---

## 📂 Project Structure

```text
synent-task5-salesanalysis-bhupendra/
│
├── Sales_Analysis.ipynb
├── Sample-Superstore.csv
├── Profiling_Report.html
├── images/
├── README.md
└── requirements.txt
```

---

## 🚀 Installation & Usage

### Clone Repository

```bash
git clone https://github.com/bktechnology513/synent-task5-salesanalysis-bhupendra.git
```

### Navigate to Project

```bash
cd synent-task5-salesanalysis-bhupendra
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn ydata-profiling
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```bash
Sales_Analysis.ipynb
```

---

## 📋 Deliverables

✅ Data Cleaning

✅ Exploratory Data Analysis

✅ Data Visualization

✅ Business Insights

✅ Sales Report

✅ Internship Project Submission

---

## 🎓 Internship Details

**Organization:** Synent Technologies

**Domain:** Data Science

**Project:** Sales Analysis

**Task Number:** Task 5

**Intern:** Bhupendra Kumar

---

## 👨‍💻 Author

### Bhupendra Kumar

🔗 GitHub: https://github.com/bktechnology513

🔗Youtube: https://www.youtube.com/@bktechnology513

🔗 LinkedIn: Add Your LinkedIn Profile

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Your support helps motivate future data science and analytics projects.

---

### Project Status

✅ Completed Successfully
