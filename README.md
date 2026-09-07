# SpringAiDemo

SpringAiDemo is a sample Spring Boot project demonstrating integration with AI services and common Spring features.

## Features

- Spring Boot application structure
- Example AI integration (placeholder)
- REST APIs with controllers
- Configuration and profiles
- Unit and integration test setup

## Getting Started

### Prerequisites

- Java 17+
- Maven 3.6+
- (Optional) Docker

### Build and Run

1. Build the project:

   mvn clean package

2. Run the application:

   mvn spring-boot:run

Or run the generated jar:

   java -jar target/*.jar

### Configuration

Configuration properties are in src/main/resources/application.yml. Use profiles to override settings for different environments (e.g., application-dev.yml).

## Example API

The application exposes REST endpoints under /api. See controller classes in src/main/java for specifics.

## Contributing

Contributions are welcome. Please open issues or submit pull requests.

## License

This project is provided as-is.
