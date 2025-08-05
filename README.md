# نظام إدارة المخازن والمستودعات (Inventory Management System)

## Overview
This is an Arabic inventory management system with support for multiple branches, product categories, sales tracking, and RFID integration.

## Features
- Product management (add, edit, delete)
- Category management
- Inventory tracking
- Sales recording and reporting
- Branch management
- RFID tag integration
- User management with role-based access control

## How to Run
1. Install the requirements:
```
pip install -r requirements.txt
```

2. Run the application:
```
streamlit run app.py
```

3. Default login:
- Username: admin
- Password: admin123

## Deployment Notes
- The application creates a SQLite database in the `data` folder
- All static assets and database files are stored in subdirectories for better organization
- The application includes RTL (Right-to-Left) support for Arabic text

## Requirements
See requirements.txt for the full list of dependencies.