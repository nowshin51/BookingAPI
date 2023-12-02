### BookingAPI
This project utilizes Postman to interact with the Booking API available at https://restful-booker.herokuapp.com/booking/. An environment named "AssignmentEnvironment" has been configured to facilitate the execution of collections, including variables such as url for storing the common part of the URL, myID for capturing generated IDs, and AccessData for authentication with credentials (username: 'admin', password: 'admin123').

## Project Overview
The aim of this project is to demonstrate the use of Postman for API testing and interaction with the Booking API. It includes various API requests such as GET, POST, PUT, PATCH, and DELETE.

## Features
# Environment Setup: Configured "AssignmentEnvironment" to streamline collection execution.
# URL Variable: Utilizes the url variable to store the common part of the API URL.
# ID Tracking: Uses the myID variable to capture generated IDs from API responses.
# Authentication: AccessData variable contains the username and password for authentication.
Requirements
Postman: Ensure you have Postman installed on your system.
Newman: For generating reports through the command line.
Usage
Import the provided Postman collection and environment into your Postman application.
Select the "AssignmentEnvironment" for the collection to utilize the predefined variables.
Configure any additional settings or parameters required for the requests.
Execute the collection to perform the desired API operations.
Collection Endpoints
GET Data: Retrieves data from the API.
POST CustomerInfo: Creates new customer information.
POST Authentication: Handles user authentication.
PUT UpdateInfo: Updates existing information.
PATCH PartialUpdate: Partially updates existing data.
DELETE DeleteInfo: Deletes specific information.
Report Generation with Newman
Newman Tool: Use Newman for command-line execution of collections and report generation.

Command: Example command to run the collection and generate a report:

bash
Copy code
newman run YourCollection.json -e YourEnvironment.json --reporters cli,html --reporter-html-export report.html
Notes
Authentication: Use the provided credentials for authentication in API requests.
Environment Configuration: Adjust the environment variables as required for your use case.
Contributors
Your Name
Acknowledgments
Special thanks to the creators of the Booking API, Postman, and Newman for facilitating API testing and automation.

   
