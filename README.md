# Inventory Management System

## Overview
This project is an **Inventory Management System** developed in **C#** with **SQL** as the backend database. The system allows users to manage products, track inventory levels, and monitor restocking requirements. It is designed for small to medium-sized businesses looking to streamline inventory tracking and improve operational efficiency.

## Features
- **Add, Edit, Delete Products**: Easily manage products in the inventory.
- **View Stock Levels**: Keep track of stock levels for each product.
- **Restocking Alerts**: Get notified when items fall below a predefined threshold.
- **Search & Filter Products**: Quickly locate products by name, category, or stock status.
- **Reports**: Generate inventory reports to monitor stock movements and assess inventory health.

## Technologies Used
- **Frontend**: C# (.NET Framework)
- **Backend**: SQL Server
- **Database Management**: SQL scripts for creating and managing tables

## Setup Instructions

### Prerequisites
- **.NET Framework** installed (compatible version as per your project requirements).
- **SQL Server** for the database.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mvelo-dev/inventory-management-system.git
   ```
2. **Set Up the Database**:
   - Open SQL Server Management Studio.
   - Run the provided SQL script `inventory_database.sql` to create the necessary tables and seed data.
3. **Configure Connection String**:
   - Update the connection string in `app.config` with your SQL Server credentials.

4. **Build and Run**:
   - Open the project in Visual Studio.
   - Build and run the application.

## Usage
1. **Launch the Application**: Start the application from Visual Studio or the executable.
2. **Manage Inventory**: Use the interface to add, update, or remove products as needed.
3. **View Reports**: Access reporting features to generate and export reports.

## Database Schema
- **Products**: Stores information about each product, including name, category, price, and stock level.
- **Stock Movements**: Logs all stock changes for auditing purposes.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is open source and available under the [MIT License](LICENSE).

---
