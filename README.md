# Telecom Management System - SQL

## Project Description
This project implements a SQL-based **Telecom Management System** for handling customer accounts, service plans, payments, benefits, and technical support tickets. It includes stored procedures, functions, and views to support both administrative tasks (e.g., account-plan management, cashback calculations) and customer actions (e.g., login validation, usage tracking). The system adheres to strict SQL guidelines with predefined data types, naming conventions, and error handling.

### Key Features
- **Admin Functions**:
  - Link accounts to service plans  
  - Track cashback and payments  
  - Manage benefits and resolved tickets  

- **Customer Functions**:
  - Login authentication  
  - View plan usage and subscriptions  
  - Redeem vouchers and track rewards  

- **Database Structure**:
  - Supports **Post Paid**, **Prepaid**, and **Pay-as-you-go** accounts  
  - Enforces constraints (e.g., default values, status types)  

## Setup Instructions
1. **Database Creation**:  
   Run the `createAllTables` stored procedure to initialize the database.  

2. **Data Retrieval**:  
   Use predefined views (e.g., `allCustomerAccounts`, `allServicePlans`) to fetch data.  

3. **Testing**:  
   Execute stored procedures (e.g., `Account_Plan`, `Initiate_plan_payment`) to validate functionality.  
