                # FOOD-PANDA-DATA-ANALYSIS

Welcome to my new project on Foodpanda Dataset Analysis . This repository explores and analyzes data from Foodpanda to uncover patterns in customer behavior, order trends, delivery logistics, and more.

Exploring 6,000+ food delivery records to uncover patterns in customer behavior, delivery trends, churn, and satisfaction.

This project performs an in-depth exploratory analysis on a simulated **Foodpanda** dataset containing over 6,000 food delivery orders. Using Python and data science tools, we uncover:

- Trends in food ordering behavior
 
- Churn analysis based on customer activity

- Delivery performance insights (delays, cancellations)

- Restaurant and dish popularity

- Payment patterns and loyalty metrics

The dataset includes **6,000 rows** and **20 columns**, each representing individual food delivery orders. Here's a breakdown of the features:

| Column Name        | Description |
|--------------------|-------------|
| `customer_id`      | Unique identifier for each customer |
| `gender`           | Gender of the customer (Male, Female, Other) |
| `age`              | Age group (Teenager, Adult, Senior) |
| `city`             | Customer's city (e.g. Lahore, Islamabad) |
| `signup_date`      | Date the customer signed up |
| `order_id`         | Unique identifier for the order |
| `order_date`       | Date when the order was placed |
| `restaurant_name`  | Name of the restaurant |
| `dish_name`        | Food item ordered |
| `category`         | Food category (e.g., Fast Food, Italian, Dessert) |
| `quantity`         | Quantity of items ordered |
| `price`            | Total price of the order |
| `payment_method`   | Payment method used (Cash, Card, Wallet) |
| `order_frequency`  | Number of orders the customer has placed |
| `last_order_date`  | Most recent order date for the customer |
| `loyalty_points`   | Points earned through repeat usage |
| `churned`          | Customer status: Active / Inactive |
| `rating`           | Rating given by the customer (1–5) |
| `rating_date`      | Date when the rating was submitted |
| `delivery_status`  | Delivery outcome (Delivered, Delayed, Cancelled) |

foodpanda-dataset-analysis/

├── data/

│ ├── foodpanda_raw.csv

│ └── foodpanda_cleaned.csv

│ └── foodpanda_eda.ipynb

│ └── visualizations and plots

└── README.md

 Tools & Libraries Used

  
- **Pandas** – data cleaning and transformation  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – visualizations  
- **PowerBI** – to create an attractive dashboard

