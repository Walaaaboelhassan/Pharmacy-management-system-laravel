Complete Pharmacy Management System
Features
Products: Manage and track your inventory.
Product Categories: Organize products into categories.
Purchases: Record and manage product purchases.
Sales: Track sales transactions.
Suppliers: Maintain a list of product suppliers.
Reports: Generate various reports.
Access Control: Define roles and permissions.
Users: Manage user accounts.
User Profile: Update personal profile information.
Settings: Configure application settings.
Application Backup: Backup and restore application data.
Dashboard: Overview of key metrics and data.
Stock Notifications: Receive alerts for low stock levels.
Installation Guide
Follow these steps to set up the application:

Clone the Repository

bash
Copy code
git clone https://github.com/MusheAbdulHakim/Pharmacy-management-system.git
Navigate to the Project Directory

bash
Copy code
cd Pharmacy-management-system
Install PHP Dependencies

bash
Copy code
composer install
Install JavaScript Dependencies

bash
Copy code
npm install
npm run dev
Create the Database

Set Up the Environment File
Rename .env.example to .env or copy it and place it in the project root directory. You can use the following command to copy it:

bash
Copy code
cp .env.example .env
Generate the Application Key

bash
Copy code
php artisan key:generate
Configure the Database Connection
Update the .env file with your database credentials:

plaintext
Copy code
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=doccure
DB_USERNAME=root
DB_PASSWORD=
Run Database Migrations
Import the SQL file located in the database folder or run migrations with:

bash
Copy code
php artisan migrate --seed
Start the Development Server

bash
Copy code
php artisan serve
Access the Application
Open the URL provided in your terminal, typically:

plaintext
Copy code
http://127.0.0.1:8000
Admin Login Credentials
Email: admin@admin.com
Password: admin
Theme
You can view the theme used here.

Usage Instructions
Profile:

Each user has a personal profile that can be updated via the edit button.
Change your password by selecting the password tab and entering a new password. Ensure the old password is correctly entered.
Users:

View and manage all users in the system.
Add new users, edit existing ones, or delete users as needed.
Export or print user data using the export data button.
Access Control:

Manage user roles and permissions.
Create new roles, assign permissions, and edit or delete existing roles.
Suppliers:

List and manage product suppliers.
Add, edit, or delete supplier details.
Sales:

Track all sales transactions.
Add new sales, or delete existing ones.
Export or print sales data through the export data dropdown menu.
Purchases:

Record and manage product purchases.
Add, edit, or delete purchase records.
Export or print purchase data.
Products:

Manage your inventory of products.
Add new products, edit existing ones, or delete them.
Out of Stock: Automatically tracked when a product's quantity reaches zero.
Expired: Products past their expiry date are automatically listed here.
Categories:

Manage product categories.
Add, edit, or delete categories.
How to Add and Sell Products
Add Product Category: Define the category for your product.
Add Product Supplier: Record the supplier details.
Make a Purchase: Add purchase records for the product.
Add Product: Include the product in your inventory.
Start Selling: Begin selling the product.
Stock Management: Update product quantities or make new purchases when notified of stock changes.

thank you
walaa zidan