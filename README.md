# Innomatics-Research-Labs-Advanced-GenAI-Internship-Food-Delivery-Data-Analysis
🍽️ Food Delivery Data Analysis Project

📌 Project Overview:
This project focuses on analyzing a food delivery platform’s data by combining multiple datasets from different sources and formats. The objective is to simulate a real-world data integration and analytics workflow using Python and Pandas.
The project demonstrates how transactional data, user data, and restaurant master data can be merged and analyzed to extract meaningful business insights.

📂 Datasets Used:
The project uses the following datasets:
orders.csv
Contains transactional order-level data such as order ID, user ID, restaurant ID, order date, and order amount.
users.json
Contains user master data including user ID, city, and membership type (Gold / Regular).
restaurants.sql
Contains restaurant master data such as restaurant ID, cuisine type, and rating.

🔗 Data Integration:
The datasets were merged using LEFT JOINs to ensure that all orders are retained:
orders.user_id → users.user_id
orders.restaurant_id → restaurants.restaurant_id
The final merged dataset contains 10,000 rows, with each row representing an individual order.

🛠️ Tools & Technologies:
Python
Pandas
Jupyter Notebook (Google Colab)
GitHub
