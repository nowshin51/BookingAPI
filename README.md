## BookingAPI
This project utilizes Postman to interact with the Booking API available at https://restful-booker.herokuapp.com/booking/. An environment named "AssignmentEnvironment" has been configured to facilitate the execution of collections, including variables such as url for storing the common part of the URL, myID for capturing generated IDs, and AccessData for authentication with credentials (username: 'admin', password: 'admin123').

## Project Overview
The aim of this project is to demonstrate the use of Postman for API testing and interaction with the Booking API. It includes various API requests such as GET, POST, PUT, PATCH, and DELETE.

## Features
 1. Environment Setup: Configured "AssignmentEnvironment" to streamline collection execution.
 2.  URL Variable: Utilizes the url variable to store the common part of the API URL.
 3. ID Tracking: Uses the myID variable to capture generated IDs from API responses.
 4. Authentication: AccessData variable contains the username and password for authentication.
 
## Requirements
1. Postman: Ensure you have Postman installed on your system.
2. Newman: For generating reports through the command line.

## Usage
1. Import the provided Postman collection and environment into your Postman application.
2. Select the "AssignmentEnvironment" for the collection to utilize the predefined variables.
3. Configure any additional settings or parameters required for the requests.
4. Execute the collection to perform the desired API operations.

## Collection Endpoints
1. GET Data: Retrieves data from the API.
2. POST CustomerInfo: Creates new customer information.
3. POST Authentication: Handles user authentication.
4. PUT UpdateInfo: Updates existing information.
5. PATCH PartialUpdate: Partially updates existing data.
6. DELETE DeleteInfo: Deletes specific information.
 
## Report Generation with Newman
   
1. Newman Tool: Use Newman for command-line execution of collections and report generation.

2. Command: Example command to run the collection and generate a report:

```bash
Copy code
newman run YourCollection.json -e YourEnvironment.json --reporters cli,html --reporter-html-export report.html
```
## Notes
1. Authentication: Use the provided credentials for authentication in API requests.
2. Environment Configuration: Adjust the environment variables as required for your use case.

   
