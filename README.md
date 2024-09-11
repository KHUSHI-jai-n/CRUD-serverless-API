# CRUD-serverless-API

This project demonstrates the implementation of a serverless REST API with full CRUD (Create, Read, Update, Delete) functionality using AWS services including Lambda, API Gateway, and DynamoDB.

Architecture:


![diagram-export-9-11-2024-12_10_01-PM](https://github.com/user-attachments/assets/42081c10-f6f4-434f-800a-d3b324edbd5f)

Features:

1. Serverless Architecture- Utilizes AWS Lambda for executing backend logic, making the application scalable and cost-efficient.

2. API Gateway- Acts as the entry point for all API requests, routing them to the Lambda function.

3. DynamoDB Integration- DynamoDB is used as the persistent data store, efficiently handling employee records.

4. CRUD Operations-

        GET /status: Returns the operational status of the service.
      
        GET /employee?employeeId={id}: Fetches a single employee record by employee ID.
      
        GET /employees: Retrieves all employee records.
      
        POST /employee: Adds a new employee record.
      
        PATCH /employee: Updates an existing employee record.
      
        DELETE /employee: Deletes an employee record.
