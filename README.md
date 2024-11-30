# Hotel Management System

The **Hotel Management System** is a Python-based application developed with a Tkinter user interface and MySQL for database management. It provides a streamlined solution for managing hotel operations, including guest check-ins, check-outs, and customer data retrieval.

## 📋 Project Overview

This application is designed to simplify hotel management processes by offering:

- **Check-in and Check-out**: Effortlessly manage guest arrivals and departures.
- **Guest Information Management**: Store, retrieve, and update customer data.
- **Centralized Database**: Use MySQL for secure and reliable data handling.

## ✨ Features

1. **Guest Check-in**: Register new guests with details such as name, room preferences, and check-in dates.
2. **Check-out**: Process departures, calculate bills, and update guest records.
3. **Customer Information Lookup**: Retrieve details of current and past guests.
4. **Room Status Tracking**: Monitor room availability and occupancy.

## 🛠️ Prerequisites

Before setting up, ensure you have the following:

- **Python 3.x** installed.
- **MySQL Server** and the `mysql-connector-python` library:
  ```bash
  pip install mysql-connector-python

- **Tkinter** (pre-installed with Python for GUI development).

## 🚀 Installation Guide

1. **Clone or Download** the repository:

   ```bash
   git clone https://github.com/Abhishek-A2077/hotelmanagementsystem.git
   cd hotelmanagementsystem
   ```
2. **Set Up the Database**:

- Create a MySQL database for the project.
- Import the provided SQL script:

   ```bash
   mysql -u username -p database_name < setup.sql

3. **Configure Database Connection**:
- Update the database connection details in the Python script:

   ```bash
   db = mysql.connector.connect(
    host="localhost",
    user="your_username",
    password="your_password",
    database="your_database_name"
   )

4. **Run the Application**:

   ```bash
   python hotel_management.py

## 📖 Usage Instructions

- **Check-in**: Enter guest details and click "Check-in."
- **Check-out**: Select a guest, finalize billing, and click "Check-out."
- **Search Guests**: Use the guest's name or room number to find specific details.

## 🤝 Contributing

Contributions to enhance this project are welcome! To contribute:

1. Fork this repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name

3. Commit changes: 

   ```bash 
   git commit -m "Add your feature description"

4. Push changes:

   ```bash 
   git push origin feature/your-feature-name
 
5. Submit a pull request. 

## 📝 License

This project is licensed under the **MIT License**.

## 📧 Contact 
For questions or suggestions, please contact **Abhishek-A2077** via GitHub.
