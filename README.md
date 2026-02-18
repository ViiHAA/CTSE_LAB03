# Current Trends in Software Engineering (SE4010)
## DevOps Lab 3 - Building a Spring Boot Microservice with In-Memory Database & Swagger
--

## Tech Used
- JDK 24
- Maven
- Spring Boot
- H2 Database
- Swagger UI

---

## How to run

### Requirements
- JDK 17 or higher version
- Maven

### Steps

1. Clone my repo
```bash
git clone https://github.com/ViiHAA/CTSE_LAB03.git
```
2. Run the app
```bash
.\mvnw spring-boot:run
```

3. Host will start at `http:localhost:8080`

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/products` | Create a new product |
| GET | `/products` | Get all products |
| GET | `/products/{id}` | Get a product by ID |
| DELETE | `/products/{id}` | Delete a product by ID |
