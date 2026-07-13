# 📚 Young Adult Romance Books Data Analysis

## 📌 Project Overview

This project demonstrates an end-to-end Data Analytics workflow using Web Scraping, Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, and Automated PDF Report Generation.

The dataset was collected from the Crossword website's Young Adult Romance book collection using Selenium Web Scraping. The extracted data includes book details such as title, author, original price, selling price, and discount information.

---

## 🎯 Project Objectives

* Collect book data from a live website using Selenium.
* Create a structured dataset for analysis.
* Clean and preprocess the data using Pandas.
* Analyze pricing and discount trends.
* Create visualizations using Matplotlib and Seaborn.
* Generate a professional PDF report using ReportLab.
* Derive business insights and recommendations.

---

## 🛠️ Technologies Used

* Python
* Selenium
* Pandas
* NumPy
* Matplotlib
* Seaborn
* ReportLab
* Jupyter Notebook

---

## 📂 Dataset Information

The dataset contains the following fields:

| Column Name    |
| -------------- |
| Sl No          |
| Book Name      |
| Author Name    |
| Original Price |
| Selling Price  |
| Discount       |
| Profit         |

---

## 🔍 Data Collection

Data was extracted from the Crossword Young Adult Romance collection using Selenium WebDriver.

### Extracted Attributes

* Book Name
* Author Name
* Original Price
* Selling Price
* Discount Information

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Removed duplicate records
* Handled missing values
* Converted price columns to numeric format
* Created Profit/Discount calculation column
* Verified data quality

---

## 📊 Exploratory Data Analysis

### Key Business Questions Solved

1. Total number of books available
2. Total original price value
3. Total selling price value
4. Total discount amount
5. Average original price
6. Average selling price
7. Highest selling book
8. Top discounted book
9. Top 5 expensive books
10. Price distribution analysis

---

## 📈 Visualizations

The project includes the following visualizations:

### 1. Top 10 Most Expensive Books

Shows the highest-priced books based on selling price.

### 2. Selling Price Distribution

Displays how books are distributed across different price ranges.

### 3. Profit / Discount Distribution

Analyzes discount patterns across books.

### 4. Top Discounted Books

Highlights books receiving the highest discounts.

### 5. Original Price vs Selling Price Analysis

Compares actual and discounted pricing.

---

## 📄 Automated PDF Report

A professional PDF report was generated using ReportLab containing:

* Executive Summary
* Key Business Questions
* Statistical Analysis
* Visualizations
* Insights
* Recommendations
* Conclusion

---

## 📊 Key Findings

* Several books receive significant discounts.
* Premium-priced books contribute heavily to overall revenue.
* Most books are concentrated within a moderate price range.
* Discount strategies appear to be consistently applied across products.
* Customer affordability is improved through promotional pricing.

---

## 💡 Business Recommendations

* Focus marketing efforts on highly discounted books.
* Promote premium books for higher revenue generation.
* Maintain competitive pricing within popular price ranges.
* Optimize inventory based on demand trends.
* Use author popularity analysis for future stocking decisions.

---

## 📁 Project Structure

```text
Young_Adult_Romance_Project
│
├── Data
│   └── Young_Adult_Romance_Books.xlsx
│
├── Images
│   ├── top_expensive_books.png
│   ├── selling_price_distribution.png
│   ├── profit_distribution.png
│
├── Reports
│   └── Young_Adult_Romance_Report.pdf
│
├── notebooks
│   └── analysis.ipynb
│
└── README.md
```

---

## 🚀 How to Run

### Install Dependencies

```bash
pip install selenium pandas numpy matplotlib seaborn reportlab openpyxl
```

### Run Web Scraping

```bash
python scraping.py
```

### Run Analysis

```bash
python analysis.py
```

### Generate PDF Report

```bash
python report.py
```

---

## 📚 Learning Outcomes

This project helped develop practical skills in:

* Web Scraping
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Report Automation
* Business Insight Generation
* Python Programming

---

## 👨‍💻 Author

Arun Kumar Sahu

Master of Computer Applications (MCA)

Aspiring Data Analyst | Python | SQL | Power BI | Excel
