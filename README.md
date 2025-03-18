# Pizza Palace Sales Analysis

## 📊 Project Overview

This project analyzes and visualizes key aspects of Pizza Palace's sales data to identify key insights into its business performance, including customer behavior, purchasing patterns, and sales trends. The goal is to provide actionable recommendations for improving their sales and profitability.

---

## 🎯 Objectives

- Analyze overall sales performance, quantity, and revenue.
- Identify best-selling pizza types and categories.
- Examine sales trends over time (monthly and yearly).
- Evaluate the impact of pizza size on total sales and revenue.
- Discover patterns in customer purchasing behavior.
- Provide recommendations to optimize sales and increase profitability.

---

## 📂 Dataset Overview

The dataset contains order details from Pizza Palace. Key columns include:

- **Order Details:**

  - `order_details_id`: Unique identifier for each order.
  - `date`: Date of the order.
  - `time`: Time when the order was placed.

- **Product Info:**

  - `pizza_type_id`: Unique identifier for each type of pizza.
  - `category`: Category to which the pizza belongs, such as Chicken, Veg, Classic, etc.
  - `name`: Name of the pizza ordered.

- **Order Info:**

  - `quantity`: Quantity of pizzas ordered.
  - `size`: Size of the pizza (S, M, L).
  - `price`: Price per pizza, based on size and category.
  - `tax_amount`: Tax charged on the order based on the tax rate and price of the pizza.
  - `total_amount`: Total amount paid by the customer, calculated as:
    - `Total_amount = (Quantity * Price) + Tax_amount`

---

## 📈 Key Insights & Visuals

### 1. **Most Popular Pizza Types**

- **Top 3 Bestsellers:**
  - Thai Chicken Pizza (12.3%)
  - Barbeque Chicken Pizza (9.8%)
  - Five Cheese Pizza (8.4%)

### 2. **Quantity of Pizzas Ordered by Size, Category, and Type**

- **Large Pizzas:** Highest quantity ordered (55%)
- **Category-wise:** Classic and Chicken pizzas lead in quantity ordered
- **Pizza Type-wise:** Consistent demand across various pizza types

### 3. **Total Revenue Generated Over Time**

- **Total Revenue:** $819K
- **Peak Revenue Periods:** Weekends and holidays

### 4. **Average Price of Pizzas by Size, Category, and Type**

- **Average Price by Size:**
  - Small: $8.50
  - Medium: $12.75
  - Large: $16.90
- **Category-wise Price Variation:** Classic and Chicken pizzas have higher average prices

### 5. **Sales Trend Analysis Over Time**

- **Sales Growth:** Steady increase from January to December 2015
- **Time-based Analysis:**
  - **Peak Ordering Times:** Highest order volume occurs between **12 PM - 3 PM** with 23K orders, followed by a secondary peak around **6 PM - 9 PM** contributing 21K orders.
  - **Orders by Day of the Week:**
    - **Friday** has the highest number of orders (8.11K orders), followed by **Saturday** (7.36K) and **Thursday** (7.32K).
    - **Sunday** records the lowest orders (5.92K orders).
  - **Monthly Sales Trend:**
    - Consistent sales between **$70K to $80K** every month.
    - **March and September** record slightly higher sales at ~$79.8K and ~$78.5K respectively.

### 6. **Sales Trend by Pizza Type, Size, and Category**

- Consistent growth observed in all categories, with large-sized pizzas showing the most demand
- Seasonal spikes observed during festive periods

### 7. **Most Profitable Pizza Types**

- **Top 3 Profitable Pizzas:**
  - Thai Chicken Pizza ($98K)
  - Barbeque Chicken Pizza ($86K)
  - Five Cheese Pizza ($75K)

### 8. **Price Variation by Time of Day**

- Higher average spending during evening hours
- Lower average spending during lunch hours

### 9. **Effect of Pizza Size on Revenue**

- Large pizzas contribute 55% of the total revenue
- Medium and small pizzas contribute 30% and 15%, respectively

---

## 🛠️ Technologies Used

- **Power BI:** Data visualization and interactive dashboard creation
- **Excel:** Data preprocessing and cleaning

---

## 📌 Challenges Faced

- Handling large datasets with multiple order entries
- Ensuring data consistency and validation
- Balancing visualization clarity and information density

---

## 🚀 Future Enhancements

- Implement predictive modeling to forecast future sales
- Analyze customer segmentation for targeted marketing
- Introduce loyalty programs to encourage repeat orders

---

## 🎥 Dashboard Walkthrough

The interactive Power BI dashboard includes:

- Overview page with key performance metrics
- Category-wise and size-wise performance analysis
- Sales trend analysis over time

---

## 📚 Conclusion

This project provides valuable insights into Pizza Palace's sales performance, highlighting key factors that can improve decision-making, enhance customer satisfaction, and optimize profitability.

