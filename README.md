## Inventory Management & Billing System -- Python Console Application

## Project Overview

A comprehensive Python-based system for managing product inventory and processing customer bills. This application provides a command-line interface for store owners to manage products, process sales, and generate reports.

------------------------------------------------------------------------------------------------------------------------------------------
## Project Structure

INVENTORY MANAGMENT/
│
├── inventory.csv
├── main.py
└── sales.csv

------------------------------------------------------------------------------------------------------------------------------------------
## Features

 Inventory Management - Add, update, delete, and search products
 
 Billing & Checkout - Process sales with shopping cart functionality
 
 Sales Reports - Generate daily sales and transaction reports
 
 Stock Alerts - Get low stock notifications with custom thresholds
 
 Data Persistence - Auto-save to CSV files 
 
 Bill Generation - Export receipts in TXT or CSV formats
 
------------------------------------------------------------------------------------------------------------------------------------------
## Data Storage

Inventory File (inventory.csv)

Columns: product_id, name, price, stock_quantity

Sales Records (sales.csv)

Columns: datetime, total_amount, discount, final_amount, items

Bill Receipts (bill_YYYYMMDD_HHMMSS.[txt/csv])

Individual transaction receipts

------------------------------------------------------------------------------------------------------------------------------------------
## Checkout Process

Add items to cart with quantities

View cart to verify items

Checkout to complete sale

Optionally save bill as TXT or CSV

------------------------------------------------------------------------------------------------------------------------------------------

## Reports & Analytics

Daily Sales Reports - View transactions and revenue by date
 
Low Stock Alerts - Get warnings for products below threshold
 
Sales Analytics - Track total sales, discounts, and final amounts

------------------------------------------------------------------------------------------------------------------------------------------
##  Main Menu Options

1. Product Management
Complete inventory control for adding, updating, deleting, and searching products. Maintain your product catalog with pricing and stock levels.

2. Billing System
Process customer sales with shopping cart functionality. Add items, manage quantities, and complete checkout with automatic inventory updates.

3. Reports & Analytics
Generate daily sales reports and low stock alerts. Track transaction history and monitor business performance with detailed analytics.

4. Exit System
Safely close the application while ensuring all data is properly saved and secured for the next session.
------------------------------------------------------------------------------------------------------------------------------------------
