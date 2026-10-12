# Medical Store Management System

A Python-based Medical Store Management System designed to simplify and organize the basic operations of a medical store. The system provides a menu-driven interface for managing medicines, suppliers, sales, categories, and supplier orders.

## Features

- Manage medicine records
- Add and view medicines
- Add, view, search, update, and delete supplier records
- Record and view sales
- Search sales records
- Add, view, and delete medicine categories
- Create, view, and search supplier orders
- Simple and user-friendly menu-driven interface

## Modules

### Medicines

The Medicines module manages information such as:

- Medicine ID
- Medicine Name
- Manufacturer
- Category
- Price
- Quantity
- Expiry Date

### Suppliers

The Suppliers module manages:

- Supplier ID
- Supplier Name
- Phone Number
- Email

Available operations:

- View
- Add
- Search
- Update
- Delete

### Sales

The Sales module records:

- Sale ID
- Customer Name
- Medicine
- Quantity
- Total Price
- Sale Date

Available operations:

- View
- Make Sale
- Search

### Categories

The Categories module manages:

- Category ID
- Category Name

Available operations:

- View
- Add
- Delete

### Supplier Orders

The Supplier Orders module manages:

- Order ID
- Supplier ID
- Order Date
- Total Cost

Available operations:

- View
- Create
- Search

## Technologies Used

- Python
- Lists
- Dictionaries
- Conditional Statements
- Loops
- Menu-Driven Programming

## How to Run

1. Install Python on your computer.
2. Clone or download this repository.
3. Open the project folder in VS Code or any Python-supported IDE.
4. Open the Python file.
5. Run the program.
python "Medical Store Management.py"
6. Follow the menu options displayed on the screen.

## Project Structure

```text
Medical-Store-Management/
├── medical_store_management.py
├── README.md
├── TESTING.md
├── requirements.txt
├── Project_Report.docx
├── Project_Statement.pdf
├── Flowchart.png
└── screenshots/
```

## How the System Works

The Medical Store Management System is a menu-driven Python application designed to manage basic medical store operations.

The system is divided into six main modules:

1. **Medicines:** View and add medicine records.
2. **Suppliers:** View, add, search, update, and delete supplier records.
3. **Sales:** View, create, and search sales records.
4. **Categories:** View, add, and delete medicine categories.
5. **Supplier Orders:** View, create, and search supplier orders.
6. **Exit:** Close the application.

The program uses Python data structures to store and manage records during execution. Data is stored in memory and is not permanently saved after the program closes.

Future Improvements
MySQL or SQLite database integration
Graphical User Interface (GUI)
User login and authentication
Automatic stock updates after sales
Medicine expiry alerts
Low-stock notifications
Billing and invoice generation
Permanent data storage

Author

[Raol Divyaba Pruthvirajsinh]

Project Information

Project: Medical Store Management System
Language: Python
Institution: [Vellore Institute of Technology, Bhopal]
Year: [2026]
