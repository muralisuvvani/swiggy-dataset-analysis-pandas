Swiggy Dataset Analysis (Pandas Only)

- This project is an end-to-end data analysis of the Swiggy All-India menu dataset using only Pandas.
The goal is to demonstrate strong data wrangling, exploration, and business insight generation without relying on visualization libraries.

--  Dataset

Source: Swiggy All-India Menu dataset (191k+ records, 9 columns)
Columns:
state, city, restaurant_name, location, category, dish_name, price, rating, rating_count

--- Workflow

-- Data Cleaning & Preprocessing

Handled duplicates, missing values, and outliers
Standardized column names to snake_case
Ensured correct datatypes and value ranges

-- Exploratory Data Analysis

State, city, location, category, dish distribution
Pricing, ratings, rating counts summary
Correlation among numeric variables

-- Q&A with Pandas (10+)

Which state gets the most orders?
Which city has the least orders?
Top 5 dishes by order count
Which categories dominate?
Price vs. Rating relationship
Top 10 locations by orders
Most popular dish per category
More...

-- Business Insights

Karnataka → Highest orders, Sikkim → Lowest
“Recommended” category dominates demand
Choco Lava Cake is the most ordered dish
Premium pricing doesn’t guarantee better ratings
More ratings generally → higher ratings

--  Outcomes

- A cleaned dataset ready for analysis
- 10+ Pandas-only Q&A with code and results
- Business interpretation for decision-making
  
-- Use case: Food delivery apps can optimize menus, pricing, and promotions by understanding order trends

--  Tech Stack
Language: Python
Libraries: Pandas, NumPy
Platform: Jupyter Notebook / Google Colab
