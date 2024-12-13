# Expense Tracker
## Project Overview
Expense Tracker is a Java-based desktop application designed to help users manage and analyze personal expenses. 
The application leverages PostgreSQL for data storage, JavaFX for the user interface, and JDBC for database connectivity.
It allows users to add, view, update, delete, and filter expense records based on categories and dates.

## Features
- Add Expenses: Input description, amount, category, and date for an expense.
- View All Expenses: Display all recorded expenses in a structured format.
## Filter Records:
- By Month: View expenses for a specific month.
- By Category: Filter expenses by predefined categories (e.g., Food, Transport, Health).
- Update Expenses: Modify existing records based on a unique description.
- Delete Expenses: Remove a specific expense or delete all records.
  
## Technologies Used
- Programming Language: Java (11+)
- User Interface: JavaFX
- Database: PostgreSQL
- Integration: JDBC
- Tools: Git for version control
  
## Project Structure
The project is organized as follows:

- Database Layer: Handles data storage and retrieval using PostgreSQL.
- User Interface: Built with JavaFX to provide an intuitive experience.
- Integration Layer: JDBC is used to establish communication between the Java application and the database.
  
## How to Run the Project
1. Prerequisites
Before running the application, ensure the following are installed:

JDK 11 or higher
PostgreSQL (set up with appropriate credentials)
Any IDE (IntelliJ IDEA, Eclipse, etc.)
2. Setting Up the Database
Create a PostgreSQL database named expense_tracker.
Execute the provided SQL script to create the necessary tables and insert sample data.
3. Configure the Application
Update the database connection details (URL, username, password) in the configuration file.
4. Run the Application
Open the project in your IDE.
Run the main application file to launch the graphical interface.

## How to Use the Application
### Add Expense:
Enter the description, amount, category, and date in the provided fields.
Click "Add Expense" to save the record.

### View All Expenses:
Click "View All Expenses" to display a list of all records.

### Filter Records:
By Month: Enter the month (e.g., 2024-06) and click "Filter by Month".
By Category: Select a category from the dropdown menu and click "Filter by Category".

### Update Expenses:
Enter the description of an existing record.
Modify the fields (amount, date, or category) and click "Update Expense".

### Delete Records:
Delete by Description: Provide the description and click "Delete Expense".

### Delete All:
Click "Delete All Expenses" to clear the database.

## Future Improvements
- Add graphical charts for better visualization of expenses.
- Implement user authentication for personalized tracking.
- Include recurring expenses and income tracking features.
- Develop a mobile version of the application.
