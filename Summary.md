
Inventory Management System: 

Author: Apurva Banerjee

Overview:
The Inventory Management System is a Python-based project designed to efficiently manage inventory in a store or warehouse. This system utilizes the tkinter module to provide a Graphical User Interface (GUI), along with other Python libraries for database management, file handling, and real-time operations.
This project comprises 8 Python scripts, each fulfilling a specific functionality of the Inventory Management System. These scripts are interconnected to create a seamless user experience. The modules and their functionalities are described below:

Python Scripts:


1. dashboard.py
This script acts as the central dashboard of the Inventory Management System, providing navigation options to access different modules like Employee, Supplier, Product, Category, and Sales. Key features include:
Buttons, labels, and images for navigation.
Real-time updates on inventory operations.
A dynamic interface that reflects changes performed in other modules.


2. employee.py
This module manages all employee-related data. Key features include:
Adding, editing, and deleting employee records.
Searching employees by email, name, or contact.
Displaying detailed employee data.

3. supplier.py
This module manages supplier details. Key features include:
Adding, editing, and deleting supplier information.
Searching suppliers using invoice numbers.
Ensuring smooth supplier management.

4. product.py
This module handles product-related operations. Key features include:
Adding, editing, and deleting products.
Tracking product availability.
Searching products by category, supplier, or name.

5. category.py
This module manages product categories. Key features include:
Adding and deleting product categories.
Linking products with their respective categories (e.g., iPhone under Phones).

6. sales.py
This module maintains sales records. Key features include:
Storing and displaying bills using invoice numbers.
Tracking sales summaries.

7. create_db.py
This script sets up the SQLite3 database for the entire system. It must be run before any other script to initialize the database tables. Key features include:
Creation of tables for Employees, Suppliers, Products, Categories, and Sales.
Ensuring database readiness for system operations.

8. billing.py
This module handles the billing process. Key features include:
Managing customer details and purchased products.
Applying discounts and calculating total amounts.
Generating and saving bills.
Integrating a calculator for billing operations.

Detailed Steps:
Initialize Database: Run the create_db.py script to set up the database.
Launch Dashboard: Run the dashboard.py script to access the main interface.
Add Employees: Navigate to the Employee module to add, edit, or delete employee records.
Add Suppliers: Navigate to the Supplier module to manage supplier data.
Add Products: Use the Product module to manage inventory items.
Manage Categories: Use the Category module to organize products.
Handle Billing: Use the billing.py script to manage customer billing operations.
Track Sales: Use the Sales module to view and analyze billing records.

Pre-Requisites:
Ensure the following Python packages are installed:
time: pip install time
Pillow: pip install pillow
sqlite3: Pre-installed with Python.
os: Pre-installed with Python.

Configuration:
Before running the dashboard.py script, ensure the following:
Run create_db.py to initialize the database.
Create two folders in the project directory:
images: Store project-related images here.
bill: Bills generated during operations will be saved here.

Key Features:
User Authentication: Ensures secure access to the system.
Data Validation: Verifies inputs to maintain data integrity.
Low-Stock Alerts: Notifies users about inventory shortages.
Graphical User Interface: Intuitive GUI for better usability.
Sales Summary Reports: Provides insights into sales performance.

This project showcases the integration of Python modules to create a functional, user-friendly inventory management system suitable for small to medium-scale businesses.
