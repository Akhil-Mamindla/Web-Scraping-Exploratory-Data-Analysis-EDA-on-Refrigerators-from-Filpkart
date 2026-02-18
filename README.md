## 🧊 Flipkart Refrigerator Data Analysis using Web Scraping

### 📌 Project Overview

This project involves scraping refrigerator product data from the Flipkart website and performing detailed Exploratory Data Analysis (EDA) to understand pricing trends, brand competitiveness, and customer preferences.

The project simulates a real-world Data Analyst task — collecting raw web data, transforming it into a structured dataset, and generating actionable business insights.

---

### 📊 Dataset Information

- **Source:** Flipkart  
- **Rows:** 984  
- **Columns:** 6  
- **Attributes:** Brand, Price, Capacity, Ratings, Stars, Door Type  

---

## 🚀 Project Workflow

### 1️⃣ Web Scraping

- Sent HTTP requests using `Requests`
- Parsed HTML content using `BeautifulSoup`
- Extracted 984 product listings
- Structured raw HTML into a clean dataset

---

### 2️⃣ Data Cleaning & Transformation

- Removed null values
- Converted Price, Capacity, Ratings, and Stars into numeric format
- Handled missing values using `fillna()`
- Standardized text formats for accurate comparison

---

### 3️⃣ Exploratory Data Analysis (EDA)

EDA was performed at three levels:

#### 🔹 Univariate Analysis

- Brand distribution
- Refrigerator door type distribution
- Count of products per configuration

#### 🔹 Bivariate Analysis

- Brand vs Price
- Brand vs Ratings
- Capacity vs Price relationship
- Ratings vs Star category

#### 🔹 Multivariate Analysis

- Price trends across brand and capacity
- Feature correlation analysis
- Market segmentation patterns

---

## 📈 Key Insights

- Most brands dominate the mid-price segment, while Samsung, LG, Godrej, and Haier extend into premium pricing.
- Higher star ratings are generally associated with higher prices.
- Single-door and double-door refrigerators are the most commonly available types.
- Larger capacity refrigerators are significantly more expensive.
- Strong positive correlation observed between capacity and price.

---

## 🛠️ Tools & Technologies

- Python  
- Requests  
- BeautifulSoup  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 💼 Skills Demonstrated

✔ Web Scraping  
✔ Data Cleaning & Wrangling  
✔ Exploratory Data Analysis  
✔ Data Visualization  
✔ Business Insight Generation  
✔ Real-world Data Handling  





