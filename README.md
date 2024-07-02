# Pizza Sales Analysis

This project involves analyzing the pizza sales dataset of a company. The dataset comprises four files: `pizza_types`, `pizza`, `orders`, and `order_details`. Using SQL queries, various analyses were conducted to retrieve insights about the sales.

## Dataset Description

- **`pizza_types`**:
  - `pizza_type_id` (Primary Key)
  - `name`
  - `category`
  - `ingredients`

- **`pizzas`**:
  - `pizza_id` (Primary Key)
  - `pizza_type_id` (Foreign Key referencing `pizza_types`)
  - `size`
  - `price`

- **`orders`**:
  - `order_id` (Primary Key)
  - `date`
  - `time`

- **`order_details`**:
  - `order_detail_id` (Primary Key)
  - `order_id` (Foreign Key referencing `orders`)
  - `pizza_id` (Foreign Key referencing `pizza`)
  - `quantity`

### 1. Retrieve the Total Number of Orders Placed

### 2. Calculate the Total Revenue Generated from Pizza Sales

### 3. Identify the Highest-Priced Pizza

### 4. Identify the Most Common Pizza Size Ordered

### 5. List the Top 5 Most Ordered Pizza Types Along with Their Quantities

### 6. Join the Necessary Tables to Find the Total Quantity of Each Pizza Category Ordered

### 7. Determine the Distribution of Orders by Hour of the Day

### 8. Join Relevant Tables to Find the Category-Wise Distribution of Pizzas

### 9. Group the Orders by Date and Calculate the Average Number of Pizzas Ordered Per Day

### 10. Determine the Top 3 Most Ordered Pizza Types Based on Revenue

### 11. Calculate the Percentage Contribution of Each Pizza Type to Total Revenue

### 12. Analyze the Cumulative Revenue Generated Over Time
