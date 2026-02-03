# FullStackProject

This is a Spring Boot backend project, part of a full stack application.

## Features
- REST API endpoint at `/api/test` that returns a test message.

## Getting Started

### Prerequisites
- Java 17 or later
- Maven 3.6+

### Running the Application

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd FullStackProject
   ```
3. Build and run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

The application will start on [http://localhost:8080](http://localhost:8080).

### Test the API
Visit [http://localhost:8080/api/test](http://localhost:8080/api/test) in your browser or use curl:
```bash
curl http://localhost:8080/api/test
```

## Project Structure
- `src/main/java/com/aman/FullStackProject/` - Java source code
- `src/main/resources/` - Application resources
- `src/test/java/com/aman/FullStackProject/` - Test code

## License
This project is licensed under the MIT License.

