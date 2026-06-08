# Smart Banking Management System

## Objective

Develop a secure banking application that allows customers to manage accounts, transfer money, apply for loans, and view transactions.

Administrators can manage customers, accounts, loans, and monitor system activities.

## Technologies

Frontend:
- React
- Redux Toolkit
- Material UI

Backend:
- Java 21
- Spring Boot
- Spring Security
- JWT

Database:
- MySQL

Cloud:
- AWS EC2
- AWS RDS
- AWS S3

DevOps:
- Docker
- GitHub Actions

## User Roles

1. Admin
2. Customer

## Admin Features

- Login
- Dashboard
- View Customers
- Add Customer
- Edit Customer
- Delete Customer
- Create Bank Accounts
- Approve Loans
- Reject Loans
- View Transactions
- View Audit Logs

## Customer Features

- Register
- Login
- View Profile
- Update Profile
- View Accounts
- Deposit Money
- Withdraw Money
- Transfer Money
- View Transaction History
- Apply for Loan
- Track Loan Status

  ## Security

- JWT Authentication
- Password Encryption
- Role Based Access

## Performance

- API response under 2 seconds

## Reliability

- Exception Handling
- Logging

## Scalability

- Deployable on AWS

## Database Tables

### users

- id
- name
- email
- password
- role

### customers

- id
- user_id
- phone
- address
- aadhaar

### accounts

- id
- customer_id
- account_number
- account_type
- balance
- status

### transactions

- id
- account_id
- type
- amount
- transaction_date

### loans

- id
- customer_id
- amount
- status

### audit_logs

- id
- action
- user_id
- timestamp
