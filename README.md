# Task Manager Backend

This project is a simple Task Manager built with Spring Boot.

## Description

Task Manager is a web application for managing tasks and users. It provides a RESTful API for creating, viewing, editing, and deleting tasks, as well as managing users.

## Features

- Create new tasks
- View list of tasks
- Edit and delete tasks
- Create new users
- Get user information

## Technologies

- Java 11
- Spring Boot
- Spring Data JPA
- PostgreSQL

## Installation and Running

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/task-manager-backend.git
    ```

2. Navigate to the project directory:

    ```bash
    cd task-manager-backend
    ```

3. Change database settings in the `src/main/resources/application.properties` file.

4. Build the project using Maven:

    ```bash
    mvn clean install
    ```

5. Run the application:

    ```bash
    mvn spring-boot:run
    ```

6. Once the application is running, it will be accessible at [http://localhost:8080](http://localhost:8080).

## Using the API

- **Get all tasks:** `GET /api/tasks`
- **Create a new task:** `POST /api/tasks`
- **Get user by ID:** `GET /api/users/{id}`
- **Create a new user:** `POST /api/users`

## License

This project is licensed under the [MIT License](LICENSE).
