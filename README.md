# Workforce Management

This is a Spring Boot application for workforce task management.  
It demonstrates creating, updating, assigning, and fetching tasks.

## Author
MD GULAM ABDUL QUADIR
Email: mail4abdulquadir@gmail.com 

## Requirements
- Java 17+
- Gradle
- Spring Tool Suite / IntelliJ / VS Code

## How to Run
1. Clone the repository:
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

2. Build the project:
   ./gradlew clean build

3. Run the application:
   ./gradlew bootRun



The application will start at:
http://localhost:8080

API Endpoints

1. Get Task by ID
   GET /task-mgmt/{id}

2. Create Task
   POST /task-mgmt/create

3. Update Task
   POST /task-mgmt/update

4. Assign by Reference
   POST /task-mgmt/assign-by-ref

5. Fetch Tasks by Date
   POST /task-mgmt/fetch-by-date/v2
