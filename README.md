# sit737-2025-prac4p

Task 4.1P – Documentation

This project is a basic calculator microservice built using Node.js and Express. It includes four API endpoints to perform arithmetic operations: addition, subtraction, multiplication, and division. Additionally, the microservice uses the Winston logging library to track incoming requests and errors, which is useful for development and troubleshooting.

Step-by-Step Instructions

Microservice Development
1. Initialize a Node.js Project
•	Open the terminal and create a new project folder. Then run the following commands:
npm init -y
npm install express
2. Create the Express Application
Create a file called index.js and set up a basic Express server that listens on port 3040.
3. Design and Implement API Endpoints
	Four GET endpoints were created: /addition, /subtraction, /multiplication, /division
4. Add Input Validation and Error Handling
The service checks for valid number inputs and handles division by zero errors with appropriate messages.
Adding Winston Logging

1. Install Winston
Run npm install winston
2. Configure Winston Logger
Logs errors to error.log, all info-level logs to combined.log, and console logs during development.
3. Log Request Information
Logs operation type, input values, and errors.

Run the Application
Start the server with node index.js
Test the Endpoints
ex: Use browser to test the end points;
http://localhost:3040/addition?n1=10&n2=5
http://localhost:3040/substraction?n1=10&n2=3
http://localhost:3040/division?n1=10&n2=5
http://localhost:3040/multiplication?n1=100&n2=4



  

