# E-Invoice Generator

This is an E-Invoice Generator application built using Python's Tkinter library. It allows users to create and manage invoices for products, including features to add, delete, and print invoices.

## Features

- **User-Friendly Interface**: Easy-to-use graphical interface for generating invoices.
- **Product Management**: Add and remove products from the invoice.
- **PDF Generation**: Generate invoices in PDF format.
- **Customer Information**: Input customer name and contact details for invoices.
- **Discount and Tax Calculation**: Automatically calculates the total amount considering discounts and taxes.

## Requirements

- Python 3.x
- Tkinter (comes pre-installed with Python)
- ReportLab (`pip install reportlab`)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd InvoiceGenerator
## Install the required packages if not already installed:
    pip install reportlab

Create a directory for storing generated invoices:

    mkdir diectory:\InvoiceGenerator
## Usage
# Run the application:
    python invoice_generator.py
# Add Product: Click on "Add New Item" to input product details such as name, quantity, rate, tax percentage, and discount percentage.

# Delete Product: Select a product from the list and click "Remove Selected Item" to delete it.

# Print Invoice: Click "Print Invoice" to generate a PDF invoice containing all added products, customer details, and total amounts.

# About Developer: Click "About Developer" to learn more about the developer.



