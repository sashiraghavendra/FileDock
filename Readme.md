FileDock – Spring Boot File Upload & Download REST API
Overview
FileDock is a Spring Boot REST API for uploading and downloading files. It supports single and multiple file uploads, generates download links, and stores files locally.
________________________________________
Features
•	Upload single or multiple files
•	Download files by filename
•	Configurable local storage
•	Automatic folder creation
•	JSON responses for uploaded files
•	Exception handling
________________________________________
Technologies
Java 17+, Spring Boot, Maven, HTML, CSS, JavaScript
________________________________________
API Endpoints
•	POST /uploadFile – Upload single file
•	POST /uploadMultipleFiles – Upload multiple files
•	GET /downloadFile/{fileName} – Download file
________________________________________
Configuration
In application.properties:
file.upload-dir=uploads
server.port=8080
________________________________________
Running the Project
cd "project-directory-path"
mvn clean install
mvn spring-boot:run
Server runs at http://localhost:8080

# FileDock
