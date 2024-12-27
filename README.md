# EXPENSES_TRACKER
This Python script is a comprehensive Expense Tracker application. It allows users to manage their personal finances by adding, viewing, editing, and analyzing their expenses. Here’s a summary of its functionality and features:

Classes and Their Responsibilities
Expenses
Represents an individual expense with attributes: 
description: What the expense is for.
amount: The cost of the expense.
category: The type or grouping of the expense (e.g., "Groceries").

# ExpenseTracker

The main class that manages the user's expenses and supports various operations: 
Adding new expenses or recurring expenses.
Viewing, editing, and removing expenses.
Saving and loading expenses from a JSON file.
Sorting expenses by amount, description, or category.
Generating a pie chart to visualize expenses by category.
Setting and monitoring a monthly budget.

Features:
# 1.Add Expense
Add a single expense with a description, amount, and category.
Prevents negative expense amounts.
# 2.View Expenses
Display a list of all recorded expenses with detailed information.
# 3.Edit Expense
Modify existing expenses by their description or category.
Update one or more of the fields: description, amount, or category.
# 4.Remove Expense
Delete expenses based on their description or category.
# 5.Save and Load
Save expenses to a JSON file for persistence.
Load expenses from a previously saved file.
# 6.Pie Chart Visualization
Generate a pie chart of expenses by category.
Annotates the chart with the most and least expensive categories.
