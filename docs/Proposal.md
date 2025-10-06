Project Title:
E-Shop Analyzer



Problem Statement:
Online shopping is the “new norm” or new normal, and keeping track of the amount of sales, revenue, top-selling products, customer spending patterns, order statuses and so many more is getting harder and more complex as the technology advances. This can show greater effect when data is provided using things like JSON files, which are raw data and especially hard to manually analyze the raw data efficiently.

As our problems add up, so do the solutions for our issues. Our projects’ goal is to effectively help in analyzing things related to e-commerce so people who sell online can have an easier time checking the data of their online shop. Our project's goal is to make a python program which can effectively analyze, process, and summarize given information or data from a given raw JSON file. The JSON file contains details such as customers, order dates, payment methods, product categories, and total amounts.

This project can effectively increase efficiency and improve the quality of life of online shoppers and sellers alike since it helps in analyzing data and information for faster processing. In the long run, this saves time and manpower in analyzing data, while using things like raw files such as JSON which are hard to analyze manually so much easier.



Project Objectives:
To analyze and summarize e-commerce order data from a JSON file using Python to reveal patterns and key insights.

To develop an interactive, menu-driven program that allows users to explore summaries such as total revenue, top products, and customer details.

To apply and strengthen Python programming skills in file handling, data processing, and logical problem-solving through real-world data analysis.



Planned  Features:
Sales Summary – Displays the total number of orders, overall revenue, and the average order value from the dataset.

Top-Selling Products – Identifies and lists the top 3 products based on the total quantity sold.

Category Sales Report – Summarizes total sales and number of items sold for each product category (e.g., Electronics, Accessories).

Order Status Tracker – Lists all orders that are still Pending or Shipped to help monitor delivery progress.

Profit Margin – Analyzes price to production cost ratio and total items sold to calculate the most profitable items.

Customer Search Tool – Allows users to search for a customer’s name to view their orders, total spending, and payment method.



Planned Input and Output:
Inputs
User menu choice – to select which feature or analysis to run.
Customer name – for searching specific customer orders and spending.

Outputs
Overall sales summary – total number of orders, total revenue, and average order value.
Top-selling products – list of the top 3 most purchased items.
Category sales report – total quantity sold and revenue per category.
Order status list – orders that are Pending or Shipped, including customer names and total amounts.
Customer order details – products purchased, total spending, and payment method for a specific customer.


Logic Plan:
Start Program

Load JSON file "ecommerce_orders.json"

Display Main Menu:
1. Show overall sales summary
2. Show top 3 best-selling products
3. Show sales by product category
4. Show pending or shipped orders
5. Search customer order details
6. Show payment method summary
7. Exit program

Repeat until user chooses Exit:
    Ask for user choice

    If choice == 1:
        - Count total number of orders
        - Sum all total_amount values
        - Compute average order value
        - Display results

    Else if choice == 2:
        - Loop through all items
        - Add up quantities per product
        - Sort by total quantity sold
        - Display top 3 best-selling products

    Else if choice == 3:
        - Group items by category
        - Calculate total sales and quantity for each category
        - Display category summary

    Else if choice == 4:
        - Filter orders where status is "Pending" or "Shipped"
        - Display order_id, customer name, and total_amount

    Else if choice == 5:
        - Ask user to input customer name
        - Search for matching orders
        - Display total spent, products bought, and payment method

    Else if choice == 6:
        - Count how many orders used each payment method
        - Display payment summary

    Else if choice == 7:
        - Display "Exiting program..."
        - End loop

    Else:
        - Display "Invalid option, please try again."

End Program



