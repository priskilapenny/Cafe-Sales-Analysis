# Cafe-Sales-Analysis
## Project Overview
This project analyzes transaction data to uncover sales trends and product performance. The analysis aims to answer key business questions such as which products generate the most sales, when sales performance is strongest, and which products are popular across different order types.

<img width="1857" height="900" alt="dashboard_screenshot" src="https://github.com/user-attachments/assets/b44da8bd-4ae8-4a5f-a436-e0e96d3ffc5a" />


## Business Question
1. How is overall sales performance?
2. Which products drive sales?
3. When are the strongest and the lowest sales?
4. Which products are more popular across different order types?

## Tools
- Microsoft Excel
    - Power Query (data cleaning & transformation)
    - Pivot Table & Pivot Charts
    - Dashboard creation

## Dataset
This project uses a dataset sourced from Kaggle. The dataset contains:
1. Transaction ID: a unique identifier for each transaction.
2. Item: the name of the item purchased.
3. Quantity: the number of items purchased.
4. Price per Unit: the price of a single unit of the item.
5. Total Spent: total amount of the transaction.
6. Payment Method: the payment method used.
7. Order Type: type of the transaction (In-store/takeaway).
8. Transaction Date: date of the transaction.

## Data Cleaning & Preparation
1. Check for duplicate values
2. Check missing values
3. Check for invalid values
4. Replace missing and invalid values with an appropriate value
5. Standardize date value
6. Improve date readability by creating a new column for the month and day of the week

## Data Analysis
- Count of Transaction
- Sum of Revenue
- Count of Item Sold
- Average Transaction Value
- Average Quantity per Transaction
- Top-selling items by revenue
- Top-selling items by quantity
- Relation of items and order type
- Monthly trend
- Day of Week trend

## Key Findings & Insight
- The best-selling item is salad with 2340 servings sold and leads revenue with $117.000
- Cookie is the second-highest in sales by quantity, but the lowest revenue contribution
- The peak revenue month is January
- The lowest revenue months are February and May, with $37K of revenue
- Thursday and Sunday are the peak revenue days of the week
- The lowest revenue day of the week is Wednesday
- Product demand is relatively balanced, with only a slight gap for certain items across order types

## Recommendation
- Need to increase the stock of the high-demand product’s ingredient.
- Evaluate the pricing strategy of the high-volume, low-revenue item.
- Launch promotions during the low sales season.
- Considering minor differences in demand across order types when planning promotions.
