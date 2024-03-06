# 📝 Credit Risk Analysis Repository 

## Overview

Welcome to our Credit Risk Analysis Repository! Here, we delve into the intricate world of credit risk assessment 📊. Our objective is to analyze credit data and extract valuable insights to aid in risk management and decision-making processes.

## Dataset 📈

For our analysis, we've sourced our dataset from Kaggle. It contains a comprehensive set of features related to credit applicants and loan characteristics. Here are the columns included in our dataset:

* person_age: Age of the individual (years)
* person_income: Income of the individual (USD)
* person_home_ownership: Home ownership status ('RENT', 'OWN', 'MORTGAGE')
* person_emp_length: Employment length (years)
* loan_intent: Purpose of the loan ('PERSONAL', 'EDUCATION', 'MEDICAL', etc.)
* loan_grade: Grade of the loan ('A', 'B', 'C', 'D', 'E', 'F', 'G')
* loan_amnt: Loan amount (USD)
* loan_int_rate: Loan interest rate (%)
* loan_status: Loan status (1 for default, 0 for non-default)
* loan_percent_income: Loan amount as a percentage of income
* cb_person_default_on_file: Default history on file ('Y' for yes, 'N' for no)
* cb_person_cred_hist_length: Credit history length (years)

## Files 📁

- [`credit_risk_data.csv`](https://github.com/Analyticalgeek/Data-Analysis-Projects/blob/main/Credit%20Risk/Data/credit_risk_dataset.csv): Our main dataset, the heartbeat of our analysis.
- [`final.csv`](https://github.com/Analyticalgeek/Data-Analysis-Projects/blob/main/Credit%20Risk/Data/final.csv): The final datset after data cleaning and Preprocessing.
- [`credit risk analytics Data cleaning.ipynb`](https://github.com/Analyticalgeek/Data-Analysis-Projects/blob/main/Credit%20Risk/Notebooks/Credit%20Risk%20Analytics%20Data%20Cleaning.ipynb): The jupyter Notebook version  of the python script where the data cleaning and Preprocessing is done
- [`credit risk Exploratory Data Analysis.ipynb`](https://github.com/Analyticalgeek/Data-Analysis-Projects/blob/main/Credit%20Risk/Notebooks/Credit%20Risk%20Exploratory%20Data%20Analysis.ipynb): The jupyter version of the python script where the Exploratory Data analysis is done.
- `README.md` (you're here!): Your guide to this exhilarating journey through Credit Risk Data Analytics.

## Requirements 🛠️

Ensure you have the following Python libraries installed:

- pandas 🐼
- numpy 🔢
- matplotlib 📊
- seaborn 📈

Install them with a below code:

```
pip install pandas numpy matplotlib seaborn
```

## Analysis 🧐

Analysis revealed fascinating insights into Black Friday sales:

**1.Revenue Generated** : jaw-dropping total revenue of **$5,017,668,378**!

**2.Average Revenue**: Each shopper spent an average of **$9333.86**

**3.Total Customers**: We had a bustling crowd of **5891** shoppers join the Black Friday sales!

**4.Inventory Highlights**: store has a **3623** products.

**5.Gender Distribution**: *Gender Distribution In Sales*

<p align="center">
  <img src="Genderdistribution.png" alt="Gender Distribution" /><br>
</p>


**5.Top Spender**: User ID **1004277**  is the top spender in the Black Friday sales.

**6.Hot-Selling Product**: Product ID **P00265242** is the ultimate crowd-pleaser.

**7.Most Revenue generated Product**: Product ID **P00025442** is the most revenue generated product

<br>

<p align="center">
  <img src="top_10_revenue_products.png" alt="Top 10 Highest Revenue Generated Products" /><br>
  <em>Caption: Top 10 Highest Revenue Generated Products</em>
</p>

<br>

**8.Product Frequently Bought by Both Genders**: Product ID **P00265242**

**9.Most Revenue Generated Product Among Females**: The Product ID **P00255842** among female shoppers.

**10.Most Revenue Generated Product Among Males**: The Product ID **P00025442** which is also hot selling product.

**11.Popular product among all age groups**: The Product ID **P00265242**

**12.Age Insights**: The **26-35 age group dominated** the shopping scene, closely followed by the 36-45 age bracket.
<br>
<p align="center">
  <img src="Agegroups.png" alt="Different Age groups in Sales" /><br>
  <em>Caption: Different Age groups in Black Friday Sales</em>
</p>
<br>

**13.City**: City 'C' saw the most action, while **City 'B' raked in the most revenue**. Cities 'A' and 'C' were hotspots for the 26-35 age group.

**14.Marital Status**: Users with Marital Status '0' are more in number.

**15.Product Category**: Category 5 Products are purchased more, while **Category 1** stole the show **in revenue generation.**

**16.Occupation**: Occupation 4 has generated the highest Revenue
<br>
<p align="center">
  <img src="Occupations.png" alt="Occupations" /><br>
  <em>Caption: Occupations with Total Purchase Amount</em>
</p>
<br>


## Conclusion 🎇

This analysis offers a deep dive into the dynamics of Black Friday sales, uncovering key insights that can guide businesses in tailoring their strategies to maximize revenue and shopper satisfaction 🚀.

---
