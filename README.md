# E-Commerce Sales — Exploratory Data Analysis (EDA)
### DecodesLab Data Analytics Internship — Project 2 | Batch 2026

---

## 📌 Project Overview
This project performs a full Exploratory Data Analysis on the
cleaned e-commerce orders dataset from Project 1. Following the
IPO Framework (Input → Process → Output), the analysis uncovers
patterns, trends, distributions, and actionable business insights
to support data-driven decision making.

---

## 🎯 Objective
To explore and analyze the cleaned e-commerce dataset in order to
uncover patterns, trends, distributions, and business insights that
can support data-driven decision making.

---

## 🛠️ Tools & Technologies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (VS Code)
- openpyxl

---

## 📂 Dataset
- **File:** cleaned_dataset.xlsx
- **Source:** DecodesLab Internship — Project 1 output
- **Rows:** 1,200
- **Columns:** 14
- **Domain:** E-Commerce Orders

---

## 📊 Analysis Structure
| Step | Description |
|------|-------------|
| Step 1 | Import Libraries |
| Step 2 | Load & Inspect Dataset |
| Step 3 | Descriptive Statistics |
| Step 4 | Univariate Analysis |
| Step 5 | Bivariate Analysis |
| Step 6 | Correlation Analysis |
| Step 7 | Executive Summary |

---

## 🔑 Key Findings
1. TotalPrice is right-skewed — median (823) is more reliable than mean (1053)
2. Only 19% of orders are delivered — Cancelled + Returned = 42% 🚨
3. Facebook customers spend most despite Instagram driving most traffic
4. Credit Card users are highest spenders across all payment methods
5. UnitPrice is strongest revenue driver (correlation: 0.72 with TotalPrice)
6. Monitor generates highest revenue despite Printer being top seller by volume
7. Coupon codes show zero price impact — discount system needs investigation
8. Cart-to-purchase gap exists — ItemsInCart weakly correlates with TotalPrice (0.39)

---

## 💡 Lesson Learned
Data doesn't always tell the obvious story. Instagram drives the
most traffic but Facebook drives the most revenue. Printer sells
the most units but Monitor generates the most value. Numbers need
context to become insights.

---

## ▶️ How to Run

1. Clone the repository
   git clone https://github.com/ume1088/DecodeLabs_Internship_Task2
2. Install required libraries
   pip install -r requirements.txt
3. Place `cleaned_dataset.xlsx` in the project folder

4. Open the notebook
  jupyter notebook
5. Run all cells from top to bottom

---

## 📁 Output
- Notebook contains all visualizations inline
- Executive summary included at end of notebook

---

## 👩‍💻 About the Author
**Ume Habiba**
BS Information Technology — Semester 6
Rawalpindi, Pakistan

Passionate about data cleaning, EDA, and building data-driven
solutions. Currently completing a Data Analytics Internship at
DecodesLab while actively building a freelance portfolio on
LinkedIn.

🔗 GitHub: github.com/ume1088

🔗 LinkedIn: www.linkedin.com/in/ume-habiba-88313537b

📧 umehabiba1088@gmail.com
