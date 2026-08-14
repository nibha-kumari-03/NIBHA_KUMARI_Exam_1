# Sales Data Exploratory Data Analysis (EDA)

## Dataset
https://drive.google.com/file/d/1cIHA8izG7r-duw34m8HEeMjHmkq2cHzt/view?usp=sharing

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a sales dataset using Python to identify sales trends, customer behavior, order patterns, fulfilment performance, and inventory insights.

##  Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Analysis Performed

### 1. Data Cleaning

* Checked and handled missing values.
* Removed duplicate orders based on **Order ID and ASIN**.
* Converted date columns into the appropriate format.
* Filled missing values using suitable methods such as median, mode, and categorical labels.

### 2. Sales Analysis

* Analyzed monthly revenue trends.
* Identified best-selling product categories.
* Studied seasonal sales patterns.
* Calculated Average Order Value (AOV).
* Identified top-performing states and cities.

### 3. Customer Analysis

* Compared **B2B vs B2C** customers.
* Analyzed order volume, AOV, total sales, cancellation rates, and average quantity purchased.

### 4. Order & Fulfilment Analysis

* Analyzed order cancellation trends.
* Compared Amazon and Merchant fulfilment.
* Studied shipping service levels and order status.
* Identified fulfilment areas that may require improvement.

### 5. Inventory & Product Analysis

* Identified high-demand product categories.
* Analyzed average quantity ordered.
* Identified top-selling SKUs.
* Examined cancelled orders by category and SKU.

## Key Insights

* Sales and revenue were analyzed across different months to identify trends and seasonality.
* Product categories and SKUs were compared to identify high-demand products.
* B2B and B2C customers showed differences in purchasing behavior.
* Cancellation patterns were analyzed by customer type, fulfilment method, category, SKU, and shipping service.
* The analysis provides useful insights for **sales planning, inventory management, customer targeting, and order fulfilment improvement**.

## Project Structure

```text
Sales-EDA/
│
|__Photos
├── NIBHA_KUMARI_exam-1.ipynb
└── README.md
```

## Conclusion

This project demonstrates how **Python-based EDA** can be used to transform raw sales data into actionable business insights and support better decision-making in sales, inventory, customer management, and fulfilment operations.
