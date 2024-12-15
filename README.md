# TaskManager

TaskManager is a Spring Boot application that performs a variety of tasks, including managing tasks in memory, performing mathematical operations, handling string manipulations, and providing responses in JSON format.

---

## Features

### Task Management
- Add, retrieve, and delete tasks stored in memory using a `HashMap` or `List`.

### Mathematical Operations
- Perform basic calculations:
  - Addition
  - Subtraction
  - Multiplication
  - Division

### String Manipulations
- Reverse a string.
- Count vowels and consonants in a string.
- Convert a string to uppercase or lowercase.

### Custom Exception Handling
- Gracefully handle errors with custom exceptions and HTTP status codes.

---

## Project Structure

```plaintext
src
├── main
│   ├── java
│   │   └── com.example.taskmanager
│   │       ├── controller      # REST controllers for API endpoints
│   │       ├── service         # Business logic and services
│   │       ├── model           # Data models for tasks
│   │       └── exception       # Custom exceptions and handlers
│   ├── resources
│   │   └── application.properties  # Spring Boot configuration
