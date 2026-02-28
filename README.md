# Association Rules Assignment

## Introduction

This project is based on Association Rule Mining using the Apriori algorithm.  
The dataset used is Online Retail dataset.  
The main aim is to find which products are frequently purchased together.

---

## Dataset

Dataset Name: Online Retail.xlsx  

Columns in dataset:
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

The dataset contains transaction data of an online retail store.

---

## Steps Performed

1. Loaded the dataset in Google Colab.
2. Removed missing values.
3. Removed cancelled invoices.
4. Removed negative quantity values.
5. Removed duplicate records.
6. Filtered data for United Kingdom.
7. Converted data into basket format.
8. Applied Apriori algorithm.
9. Generated association rules using lift.

---

## Concepts Used

- Support  
- Confidence  
- Lift  
- Apriori Algorithm  
- Market Basket Analysis  

---

## Result

After applying the Apriori algorithm, frequent itemsets were generated.  
Association rules were created using lift metric.  
The rules show which products are commonly bought together.

This analysis can help in cross-selling and product recommendation.

---

## Tools Used

- Python
- Pandas
- MLxtend
- Google Colab

## Files Included
- Jupyter Notebook (.ipynb) with complete implementation
- Online retail dataset (Excel file)


