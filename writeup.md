<h1 align="center">🤖 Personal Expense Tracker</h1>

---

## 1. Abstract

Managing personal finances effectively is an important aspect of daily life. Many individuals find it difficult to keep track of their spending habits. The Personal Expense Tracker is a Python-based application designed to help users record, manage, and analyze their daily expenses. The system allows users to add expenses, view expense records, set a budget, visualize spending patterns using graphs, and store expense data in a CSV file. This project demonstrates how simple programming tools can be used to create a practical financial management solution.

---

## 2. Introduction

Tracking personal expenses helps individuals understand how their money is spent and encourages better financial planning. Without proper tracking, it becomes difficult to identify unnecessary spending or stay within a budget.

The Personal Expense Tracker is a command-line application developed using Python. It provides users with an easy way to store and analyze expense data. The application allows users to record expenses with details such as date, category, amount, and description. The system also provides graphical visualization to help users better understand their spending patterns.

---

## 3. Objectives

The main objectives of this project are:

* To develop a simple and efficient expense tracking system using Python.
* To allow users to record daily expenses with different categories.
* To provide a way to monitor spending against a defined budget.
* To visualize expense data using graphical charts.
* To store and retrieve expense records using CSV files.

---

## 4. Technologies Used

| Technology       | Purpose                             |
| ---------------- | ----------------------------------- |
| Python           | Core programming language           |
| CSV              | Data storage format                 |
| Matplotlib       | Graph visualization                 |
| Jupyter Notebook | Development environment             |
| GitHub           | Version control and project hosting |

---

## 5. System Modules

The project consists of several modules that handle different functionalities.

### 5.1 Expense Management Module

This module allows users to add, view, and delete expense records. Each expense contains the following fields:

* Date
* Category
* Amount
* Description

### 5.2 Budget Management Module

Users can define a monthly budget. The system calculates the total expenses and compares them with the set budget to determine whether the user is within their spending limit.

### 5.3 Data Storage Module

Expense records are stored in a CSV file. This allows the program to save data permanently and load it again when the program is restarted.

### 5.4 Data Visualization Module

The system uses the Matplotlib library to generate graphs that show how expenses are distributed across different categories.

---

## 6. System Workflow

The workflow of the application is as follows:

1. The program starts and loads previously saved expenses from the CSV file.
2. A menu is displayed to the user with different options.
3. The user selects an option such as adding an expense or viewing expenses.
4. The program processes the request and updates the expense list.
5. Data can be saved back to the CSV file.
6. The user can generate graphs to analyze spending patterns.

---

## 7. Features of the System

The application provides the following features:

* Add new expenses with details
* View all recorded expenses
* Set and track a monthly budget
* Save expenses to a CSV file
* Load previously saved expenses automatically
* Generate expense graphs by category
* Delete specific expenses
* Clear all expense records

---

## 8. Advantages

* Simple and easy to use
* Helps monitor daily spending
* Provides visual insights through graphs
* Stores data for future reference
* Lightweight application with minimal requirements

---

## 9. Limitations

* The application works only through a command-line interface
* It does not support multiple users
* Limited financial analysis features
* No database integration

---

## 10. Future Enhancements

The following improvements can be added in future versions:

* Graphical User Interface (GUI) using Tkinter
* Mobile or web-based application
* Database integration using MySQL or SQLite
* Category-based monthly reports
* Exporting reports to Excel or PDF
* Advanced analytics for financial planning

---

## 11. Conclusion

The Personal Expense Tracker is a simple yet effective application that demonstrates how Python can be used to build practical tools for everyday problems. By allowing users to record and analyze their expenses, the system helps improve financial awareness and encourages better budgeting habits. This project also highlights the usefulness of data visualization and file handling in Python for building real-world applications.
