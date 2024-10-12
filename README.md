# BAN6420-Mod3_Ass_PolicyManagementSystem-SodiqOtunba
BAN6420-PolicyManagementSystem-Milestone1 Assignment -SodiqOtunba LearID 154046

## Overview
The Policyholder Management System is a Python-based application that allows for the management of policyholders, their products, and payments. The system can register new policyholders, assign them products, process payments, and display policyholder details. Each policyholder is assigned a unique policyholder ID upon registration, and different products can be added to each policyholder account. This project showcases basic object-oriented programming (OOP) concepts, error handling, and class-level operations.

## Features
- **Register Policyholders:** Register new policyholders and assign them a unique ID.
- **Manage Products:** Add and remove products, assign them to policyholders.
- **Process Payments:** Handle payments for policyholders.
- **Display Details:** Display policyholder details including registered products and payment history.
- **Error Handling:** Handle errors like duplicate policyholder registration or invalid operations.

# Technologies Used
  - Python 3.x
## Installation
1.  Clone the repository:
  ```bash
  git clone https://github.com/yourusername/BAN6420-Mod3_Ass_PolicyManagementSystem-SodiqOtunba.git
```
# Usage
1. Run the main.py script to start the application:
```bash
  python main.py
```
2. The application will prompt you to register two policyholders and then perform operations like adding products and processing payments.

Example of registering policyholders:
```bash
Please enter the names of two policyholders, separated by a comma: Alice, Bob
Registered policyholder Alice with ID 1234
Registered policyholder Bob with ID 5678
```
3. After registration, the system will assign products and process payments for each policyholder, displaying the results.

# Main Components
## 1. PolicyHolder Class
This class manages the registration, suspension, reactivation, and product assignment for policyholders.

  - **register():** Registers a new policyholder and generates a unique ID.
  - **add_product(product):** Adds a product to the policyholder's account.
  - **display_details():** Displays the details of a policyholder, including products.
## 2. Product Class
This class handles the management of products that can be assigned to policyholders.

  - **add_product():** Adds a product to the product list.
  - **remove_product():** Removes a product from the list.
  - **display_products():** Displays the registered products with their prices.
## 3. Payment Class
This class handles the payment processing for each policyholder.

  - **process_payment():** Processes a payment for a given policyholder.
## 4. main.py
This is the main script that ties everything together. It registers policyholders, assigns them products, processes payments, and displays details.

## Output Example
```bash
Please enter the names of two policyholders, separated by a comma: Alice, Bob
Registered policyholder Alice with ID 1234
Registered policyholder Bob with ID 5678
Product 'Life Insurance' added successfully.
Product 'Health Insurance' added successfully.
Added product 'Life Insurance' to policyholder Alice's account
Added product 'Health Insurance' to policyholder Bob's account
Processed payment of ₦500.00 for policyholder ID 1234
Processed payment of ₦1500.00 for policyholder ID 5678

Policyholder 1 details:
Policyholder: Alice (ID: 1234)
Status: Active
Products:
 - Life Insurance

Policyholder 2 details:
Policyholder: Bob (ID: 5678)
Status: Active
Products:
 - Life Insurance

```
For policy holder registered to same product


# Future Enhancements
- Add support for more than two policyholders at a time.
- Implement a database to store policyholder, product, and payment information persistently.
- Expand the system to allow updates to policyholder and product details.

## Thank You 
