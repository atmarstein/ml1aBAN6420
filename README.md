# Policy Management System

## Overview
This project is a simple **Policy Management System** for an insurance company. It manages policyholders, insurance products, and payments. The system allows policy managers to:

- Register, suspend, and reactivate policyholders.
- Create, update, and remove/suspend policy products.
- Process payments, send reminders, and apply penalties.
- Display policyholder details after payment.

## Project Structure
The system is implemented using **Python** and consists of the following files:

- **policyholder.py** – Defines the `Policyholder` class for managing policyholders.
- **product.py** – Defines the `Product` class for managing insurance products.
- **payment.py** – Defines the `Payment` class for handling payments.
- **main.py** – Demonstrates the functionality by creating policyholders, assigning them products, processing payments, and displaying their details.

## How to Run the Program
Follow these steps to run the project:

1. Ensure you have **Python 3.x** installed on your system.
2. Download and extract the project files if needed.
3. Open a terminal or command prompt in the project folder.
4. Run the following command:
   ```bash
   python main.py
   ```
5. The output will display the registered policyholders, payment details, and account statuses.

## Example Output
```
Policyholder 1 Details:
Name: Maruf AJimati, ID: 101, Status: Active
Payment Details: Payment of 50000 successfully processed for Policyholder ID: 101

Policyholder 2 Details:
Name: Bob Williams, ID: 102, Status: Active
Payment Details: Payment of 70000 successfully processed for Policyholder ID: 102
```
