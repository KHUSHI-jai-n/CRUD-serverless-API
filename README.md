# CRUD-serverless-API

This project demonstrates the implementation of a serverless REST API with full CRUD (Create, Read, Update, Delete) functionality using AWS services including Lambda, API Gateway, and DynamoDB.

Architecture:
![diagram-export-9-11-2024-11_55_23-AM](https://github.com/user-attachments/assets/d5ac538e-2820-43c9-b66b-9194c23ad89b)

Features:
Serverless Architecture- Utilizes AWS Lambda for executing backend logic, making the application scalable and cost-efficient.
API Gateway- Acts as the entry point for all API requests, routing them to the Lambda function.
DynamoDB Integration- DynamoDB is used as the persistent data store, efficiently handling employee records.
CRUD Operations-
GET /status: Returns the operational status of the service.
GET /employee?employeeId={id}: Fetches a single employee record by employee ID.
GET /employees: Retrieves all employee records.
POST /employee: Adds a new employee record.
PATCH /employee: Updates an existing employee record.
DELETE /employee: Deletes an employee record.
