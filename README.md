# Nikola_Apple-Store-Data-Analysis


Author: Nikola Nikolic 

Date: 31/08/2023

This Project will follow the six step data analysis process: 
### ❓ [Ask](#1-ask)
### 💻 [Prepare](#2-prepare)
### 🛠 [Process](#3-process)
### 📊 [Analyze](#4-analyze)
### 📋 [Share](#5-share)
### 🧗‍♀️ [Act](#6-act)


## 1. Ask 
An app store is any digital storefront intended to allow search and review of software titles or other media offered for sale electronically. My client is an aspiring app developer who has asked me to run an analysis on which applications perform the best, in order to decide for himself which app niche he should invest his time to enter. I will aim to answer my clients most common questions, those of which include: 
 - What app categories are most popular?
 - What price should I set?
 - How can I maximise user ratings?

Currently the stakeholders that I must account for are:
 - The client
 - The clients customers
 - The appstore community

## 2. Prepare (aka Exploratory Data Analysis)
Step 0

I am utilising Sqlite online which unfortunately has a limit of 4mb per upload, therefore, I had to seperate the data and use the UNION ALL statement to combine it again. 
```
CREATE TABLE applestore_description_combined AS 

SELECT * FROM appleStore_description1 

UNION ALL 

SELECT * FROM appleStore_description2

UNION ALL

SELECT * FROM appleStore_description3

UNION ALL

SELECT * FROM appleStore_description4

```

Step 1

I will check the number of unique apps in both data sets (AppleStore and appleStore_description_combined). This is done as a discrepancy in either table would mean that the data set is not clean and thus has the potential to negatively impact our in depth analysis. 









