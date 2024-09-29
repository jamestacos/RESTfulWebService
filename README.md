# Lab Assignment 1
## Spring Boot and RESTful Web Services

This is a simple application that utilizes Spring Boot, an open-sourced microservice-based Java web framework. Attached above are the files that are required to run the application from start to finish. Postman, a software platform designed to build and test APIs, is used to see how the application is making a request, response, and helps with debugging issues.

### Screenshots of Postman request and response
- Default case
<img width="1440" alt="Screen Shot 2024-09-29 at 3 55 42 AM" src="https://github.com/user-attachments/assets/858fe8ae-e1fb-49d2-b932-05adc15e0ce1">

- Custom name case
<img width="1438" alt="Screen Shot 2024-09-29 at 3 59 19 AM" src="https://github.com/user-attachments/assets/6bea2234-5897-4db6-934e-fddf84d6fe90">

### To run the application:
- Clone this repo
- Open an IDE (IntelliJ IDEA, Eclipse, etc.)
- Import simple-rest-service as a MAVEN project
- Run the program by accessing the SimpleRestServiceApplication class under src/main/java/com.example.simplerestservice
- Navigate to http://localhost:8080/greeting on a new browser to see results

### Postman API Validation
- Go to Postman website and create new workbench
- Enter http://localhost:8080/greeting to make a GET request
- Validate the response returned to Postman
