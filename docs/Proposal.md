E-Shop Analyzer: A Menu-Driven Python Program for E-commerce Data Analysis

Project Proposal

Project Description
The E-Shop Analyzer is a Python-based, menu-driven application designed to analyze e-commerce order data stored in a JSON file. The program reads structured transaction data and converts it into meaningful summaries such as total sales, best-selling products, category-based reports, pending orders, and customer-specific order details.
This project demonstrates the practical use of Python programming concepts such as file handling, loops, dictionaries, functions, and conditional statements to analyze real-world e-commerce data.

Problem Statement
E-commerce platforms generate large volumes of transaction data that are commonly stored in raw formats such as JSON. Manually reviewing these files to track sales, customer purchases, and order statuses is inefficient and time-consuming.
This project aims to address this problem by providing an automated Python program that processes e-commerce data and presents clear and organized summaries to users.

Project Objectives
The objectives of this project are to:

    Load and process e-commerce order data from a JSON file.

    Display a sales summary including total sales and average order value.

    Identify the top three best-selling products.

    Summarize sales and quantity by product category.

    Display orders that are not yet delivered.

    Allow users to search orders by customer name.

    Apply Python programming concepts in a real-world data analysis scenario.


Scope and Limitations

Scope

    The program analyzes data from a local JSON file.

    Output is displayed through a text-based, menu-driven interface.

    The system provides basic sales and customer analysis.

Limitations
    
    The system does not include a graphical user interface (GUI).

    Data visualization such as charts or graphs is not included.

    The program assumes that the JSON file is properly formatted.

    Customer searches require an exact name match.

System Features

    Sales Summary
     Displays the total number of orders, total sales amount, and average order value.

    Top-Selling Products
     Displays the top three products based on quantity sold.

    Category Summary
     Allows the user to input a product category and view total sales and quantity sold.

    Pending Orders Viewer
     Displays all orders that are not marked as Delivered.

    Customer Order Search
     Allows users to search for customer orders and view detailed purchase information.

    Exit Program
     Safely exits the program.


Input and Output

Input

    JSON file containing e-commerce order data

    User menu selections

    Customer name or category input

Output

    Sales summary reports

    List of best-selling products

    Category-based sales summaries

    Detailed order information

    List of pending orders

Program Logic Overview

    Load the JSON file using Python’s json module.

    Display a main menu with available analysis options.

    Accept user input and execute the corresponding function.

    Process data using loops, dictionaries, and conditional statements.

    Display formatted results.

    Repeat the process until the user exits the program.

Tools and Technologies Used

    Programming Language: Python

    Data Format: JSON
    
    Library Used: json

Development Environment: Visual Studio Code / Python IDLE

Expected Output
The program outputs organized and readable summaries that allow users to quickly understand sales performance, customer purchases, and order statuses without manually inspecting raw JSON data.
Conclusion
The E-Shop Analyzer is a practical application of Python programming for real-world data analysis. By transforming raw JSON e-commerce data into meaningful insights, the project improves efficiency and demonstrates essential programming skills suitable for a Computer Science 2 final project.

Pseudo Code:

    START
    
    LOAD e-commerce data from JSON file
    
    REPEAT
        DISPLAY main menu
        INPUT user choice
    
        IF choice = 1 THEN
            DISPLAY sales summary
        ELSE IF choice = 2 THEN
            DISPLAY top-selling products
        ELSE IF choice = 3 THEN
            ASK for category
            DISPLAY category summary
        ELSE IF choice = 4 THEN
            DISPLAY pending orders
        ELSE IF choice = 5 THEN
            ASK for customer name
            DISPLAY customer orders
        ELSE IF choice = 6 THEN
            DISPLAY exit message
            END program
        ELSE
            DISPLAY invalid choice message
        END IF
    
    UNTIL user exits
    
    END


