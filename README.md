# Project Training - Spring Boot

This project is a Spring Boot service that accepts JSON over HTTP and stores user data (id, name, age, email) in a pseudo-database (in-memory map).

## Requirements
- Java 17+
- Maven 3.9+

## Run
```bash
mvn spring-boot:run
```

The service starts at `http://localhost:8080`.

## API
- `POST /users` - Create or replace a user
- `GET /users` - List users
- `GET /users/{id}` - Fetch a user by id

## Example .http
See [requests/users.http](requests/users.http) for sample requests.
