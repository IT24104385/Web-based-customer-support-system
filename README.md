# Web-based Customer Support System

This project is a minimal Spring Boot starter for building a customer support portal. It includes Spring MVC, Thymeleaf for server-rendered pages, and Spring Data JPA for persistence with a MySQL database.

## Getting Started

1. Ensure you have Java 17 and Maven installed.
2. Update the database credentials in `src/main/resources/application.properties` to match your local environment.
3. Run the application:

```bash
mvn spring-boot:run
```

Visit <http://localhost:8080> for the home page and <http://localhost:8080/login> for the login page.

## Project Structure

```
.
├── pom.xml
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── group09
│   │   │           └── customersupport
│   │   │               ├── CustomerSupportApplication.java
│   │   │               └── controllers
│   │   │                   └── HomeController.java
│   │   └── resources
│   │       ├── application.properties
│   │       ├── static
│   │       │   └── css
│   │       │       └── main.css
│   │       └── templates
│   │           ├── home.html
│   │           └── login.html
│   └── test
│       └── java
│           └── com
│               └── group09
│                   └── customersupport
│                       └── SmokeTest.java
└── .github
    └── workflows
        └── ci.yml
```

## Database Configuration

The default MySQL connection URL points to `support_db` with username `root` and password `yourpassword`. Update the values in `application.properties` to match your local database credentials. You can also create an `application-local.properties` file (ignored by Git) for machine-specific overrides.
