🌐 Hyperlocal Marketplace

A platform that connects local vendors, customers, and admins, enabling smooth shop discovery, online ordering, and vendor management in hyperlocal regions.

🚀 Project Overview

The Hyperlocal Marketplace allows:

🛒 Customers → browse products & order from nearby shops

🧑‍🔧 Vendors → upload products, manage orders

👩‍💼 Admins → verify vendors, monitor marketplace activity

Built with PHP + MySQL, following a clean and secure architecture.

🔥 Key Features
👩‍💼 Admin

Approve or reject vendor applications

Manage vendors, customers, shops

View orders & system activity

Generate vendor IDs

🧑‍🔧 Vendor

Register & upload shop license (PDF)

Add products with images

Manage stock (In/Out of stock)

Accept or reject orders

👤 Customer

Create account & login

Browse shops & categories

View product details

Place orders

Track order status

🛠 Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	PHP
Database	MySQL
Server	XAMPP
📁 Project Structure
hyperlocal_marketplace/
│── backend/
│   ├── admin/
│   ├── vendor/
│   ├── customer/
│   ├── orders/
│   ├── config.php
│   └── database.sql
│
│── frontend/
│   ├── admin/
│   ├── vendor/
│   ├── customer/
│   └── index.html
│
└── uploads/
    ├── licenses/
    └── products/

⚙️ Setup Instructions
1️⃣ Move project to XAMPP

Place it inside:

C:\xampp\htdocs\

2️⃣ Start Apache & MySQL

Open XAMPP → Start Apache and MySQL

3️⃣ Create Database

Go to:
👉 http://localhost:8080/phpmyadmin

Steps:
✔ Create DB named hyperlocal_db
✔ Import → backend/database.sql

4️⃣ Run the project

Frontend:

http://localhost:8080/hyperlocal_marketplace/frontend/index.html


Admin login:

http://localhost:8080/hyperlocal_marketplace/backend/admin/login_admin.php

Email: admin@local.com
Password: admin123

✨ Future Enhancements

AI-based shop recommendation

Cart + checkout system

Online UPI payments

Vendor analytics

Delivery partner module

👩‍💻 Authors

Anushree R

Umashree B L

Monika V
