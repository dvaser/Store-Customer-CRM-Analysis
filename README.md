# PROJECT's KAGGLE LINK : 
***https://www.kaggle.com/code/dvaser/store-customer-crm-analysis/***

<a href="https://www.kaggle.com/code/dvaser/store-customer-crm-analysis/">
    <img src="https://github.com/user-attachments/assets/68757500-76b7-46a4-984b-43c1f219788f" style="width:75%;"></img>
</a>

# STORE CUSTOMER CRM ANALYSIS

## What will you learn from this project?
<img src="https://github.com/user-attachments/assets/6be63b1e-326a-4bf6-b376-9b56bfd60eb4" style="width:50%;"></img>
* Data Preparation
* Data Cleaning
* RFM Analysis
    * Calculate RFM Metrics
    * Calculate RFM Scores
    * Creating & Analysing RFM Segments
* CLTV Analysis
    * Average Order Value
    * Purchase Frequency
    * Repeat Rate & Churn Rate
    * Profit Margin
    * Customer Value
    * Customer Lifetime Value
    * Segmentation

## Introduction
* ***RFM Analysis:*** It is a technique used to segment customer behaviour. It helps to determine marketing and sales strategies by segmenting customers based on their buying habits.

  <img src="https://github.com/user-attachments/assets/d5802193-5b71-4c84-81d9-7a4b10597426" style="width:50%;"></img>

    * Recency (Yenilik): It is the period from the customer's last contact with the company, that is, from the customer's last purchase to today.(Recency = Today's date - Last purchase date)
    * Frequency (Sıklık): Shows how often the customer shops.
    * Monetary (Parasal Değer): It is the total expenditure made by the customer in their shopping.

  <img src="https://github.com/user-attachments/assets/6abf369a-f933-4f2e-a5a4-42f12d1d6b1c" style="width:50%;"></img>

* ***Customer Lifetime Value (CLTV):*** is considered to be the monetary value that a customer will bring to a company during its relationship and communication with that company.

  <img src="https://github.com/user-attachments/assets/fbc5fee7-b854-4e32-a994-f776818fb443" style="width:50%;"></img>

---

## Analysis Content
1. [Python Libraries](#1)
2. [Data Content](#2)
3. [Read & Analyse Data](#3)
4. [Data Distributions](#4)
5. [Data Preparation (Box Plot Analysis)](#5)
6. [Data Cleaning & Analysis](#6)
7. [RFM (Recency, Frequency, Monetary)](#7)
8. [RFM Scores](#8)
9. [RFM Segmentation](#9)
10. [RFM Analysis (Heatmap)](#10)
11. [CLTV (Customer Lifetime Value)](#11)
12. [CLTV Scores](#12)
13. [CLTV Segmentation](#13)
14. [CLTV Analysis](#14)
15. [Conclusion](#15)

---

<a id='2'></a>
## Data Content
* This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.
    
    * ***InvoiceNo:*** Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation. 
    * ***StockCode:*** Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product. 
    * ***Description:*** Product (item) name. Nominal. 
    * ***Quantity:*** The quantities of each product (item) per transaction. Numeric.	
    * ***InvoiceDate:*** Invice date and time. Numeric. The day and time when a transaction was generated. 
    * ***UnitPrice:*** Unit price. Numeric. Product price per unit in sterling (Â£). 
    * ***CustomerID:*** Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer. 
    * ***Country:*** Country name. Nominal. The name of the country where a customer resides.

* Online Retail II Official Website: https://archive.ics.uci.edu/dataset/502/online+retail+ii
