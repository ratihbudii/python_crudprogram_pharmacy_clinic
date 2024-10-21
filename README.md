# Python CRUD Application for Pharmacy Clinic

A comprehensive Python application for managing Product Stock data with Create, Read, Update, and Delete (CRUD) operations.

## Business Understanding

This clinic operates a pharmacy unit with two main stakeholders: the clinic owner and the pharmacist. In 2023, the Ministry of Health (Kemenkes) introduced a new regulation that requires all clinics and similar healthcare facilities to integrate their internal systems with the centralized system of the Ministry, known as SATUSEHAT. The current system used by the clinic, which relies on Microsoft Excel, cannot easily integrate with the centralized system.

As a solution, the clinic’s pharmacy needs a warehouse management program that can be seamlessly integrated with SATUSEHAT, ensuring that drug inventory data can be recorded and reported automatically in compliance with Kemenkes' standards. In this case, using Python as the development platform offers a viable alternative due to its flexibility and ability to build integrated systems.

**Benefits:**

* The accuracy of stock products is always updated at any time when there is an inbound or outbound stocks so that it can be used as material for decision-making
* Monitor product stock management

**Target Users:**

This application is designed for Pharmacy and Business Owner within the organization to facilitate their Task and Activities related to medicine product and medicine product stocks.

## Features

* **Show Product:**
    * Display the Product IDs, Product Names, Product Stocks, Price of Products, and Supplier Names we work with.
    * User-friendly format
* **Add Product:**
    * Add new Product (it can be a medical essentials or medicine drugs) entries with essential details like
      [Product ID, Product Name, Product Stocks, Product Price, Product Supplier Name].
    * User-friendly format
* **Edit Product:**
    * Edit data such as product name and price if there is a typo when entering additional product data in the "add product" feature.
    * The product ID will not be replaced because it must be set when adding a product in the "add product" feature. 
    * User-friendly format.
    * Provide clear confirmation or error messages based on update success or failure.
* **Update Product:**
    * Modify existing Product Stocks data to reflect changes in available stocks.
    * Stock will automatically be updated when there is an inbound stocks and or outbound stocks.
    * Provide clear confirmation or error messages based on update success or failure.
* **Delete Product:**
    * This feature aims to remove products (in the form of medical essentials and/or medicine drugs) whose suppliers are no longer cooperating with pharmacies or clinics.
* **Summary Product Stocks:**
    * This feature aims to provide conclusions to clinic owners and pharmacists that the availability of stock unit that needs to be filled within a week (7 days).
    * This feature also designed to assist pharmacists and clinic owners in monitoring their product inventory, allowing them to determine which products need to be restocked for the upcoming week.
    * This feature provides a clear and concise summary of low-stock products, serving as a valuable resource for decision-making in restocking. 
    * By utilizing this feature, pharmacies can maintain optimal product availability and avoid stock shortages.

## Installation

1. **Prerequisites:**
    * Python version 3.12.5 
    * Prettytables in library

2. **Installation:**
    ```bash
    git clone https://github.com/ratihbudii/python_crudprogram_pharmacy_clinic.git
    cd <python_crudprogram_pharmacy_clinic>
    pip install prettytable # For table in show product list and summary product stocks feature
    ```


## Usage

1. **Run the application:**
    ```bash
    python main.py
    ```

2. **CRUD Operations:**
    * **Create:** Add a new Product record, for example, a new Product Medicine in a Product Medicine management system, providing details like Product ID, Medicine Name, Stock, Price, Supplier Name.
    * **Read:** Retrieve product information by Product ID, Medicine Name, Stock, Price, Supplier Name.
    * **Update:** Modify product information and or product stocks.
    * **Delete:** Remove a product record from the system.

## Data Model
This project utilizes a Dictionary to represent Product data. The following fields are typically stored:
   * Product ID: String - ID of product
   * Medicine Name: String - Name of the medicine
   * Stock: Integer - Stock of the product
   * Price: Integer - Price of the product
   * Supplier Name: String - Name of the supplier

## Contributing
We welcome contributions to this project! Please feel free to open a pull request, sent to ratih.budi97@gmail.com or submit an issue if you encounter any problems or have suggestions for improvements.

