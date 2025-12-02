# Spring Framework Tutorials

Welcome to the Spring Framework Tutorials repository. This repo contains a set of example projects and guides to help you learn and explore the Spring Framework. It includes Spring Boot applications, REST API examples, Docker and Postgres setups, and Swagger API documentation.

## Table of Contents

- [Overview](#overview)
- [Structure](#structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Included Tutorials](#included-tutorials)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository is designed as a practical learning toolkit for Spring Framework and Spring Boot. Each tutorial focuses on a specific concept or feature, allowing you to explore the Spring ecosystem in a modular and hands-on way. Whether you are learning Spring for the first time or reinforcing your skills, these tutorials provide a clear and structured approach.

## Structure

Each tutorial exists in its own folder to keep the projects isolated and easy to navigate:

\`\`\`
Tutorial 1/ spring-annotations
Tutorial 3/ fcc-spring-boot-3-main
Tutorial 4/ docker-compose-spring-boot-postgres-master
Tutorial 5/ Spring-Tutorial-5-master / kbe-rest-brewery-main
Tutorial 6/ spring-boot-swagger-3-example-master
\`\`\`

Additional files like `.gitignore` sit at the repo root.

## Getting Started

### 1. Clone the repository  
\`\`\`bash
git clone https://github.com/AlexanderBadenhorst/Spring_Framework_Tutorials.git
\`\`\`

### 2. Navigate into the tutorial you want to run  
\`\`\`bash
cd "Tutorial 3/ fcc-spring-boot-3-main"
\`\`\`

### 3. Build and run the application  
Depending on the project, use Maven or Gradle.

Maven:  
\`\`\`bash
./mvnw spring-boot:run
\`\`\`

Gradle:  
\`\`\`bash
./gradlew bootRun
\`\`\`

### 4. Tutorials with Docker  
Some tutorials require Docker and Docker Compose. Start the services by running:

\`\`\`bash
docker-compose up
\`\`\`

Follow any tutorial-specific instructions inside that folder if additional setup is required.

## Usage

Each tutorial demonstrates a specific feature or setup. You can study the code to understand core Spring concepts, run the projects to see how frameworks and dependencies work together, copy snippets or configurations into your own applications, or use these tutorials to prepare for more advanced Spring Boot development.

## Included Tutorials

- **Spring Annotations**  
  Introduction to core Spring annotations, dependency injection, and component scanning.

- **Spring Boot 3 Starter Template**  
  A clean project foundation using modern Spring Boot.

- **Docker + Postgres + Spring Boot**  
  Containerized Spring Boot app with PostgreSQL via Docker Compose.

- **REST Brewery API**  
  Demonstrates REST endpoints, DTOs, validation, and service layers.

- **Swagger / OpenAPI 3 Integration**  
  Live API documentation with Swagger UI.

*(More tutorials will be added as the repository grows.)*

## Technologies Used

- Java  
- Spring Framework and Spring Boot  
- Maven or Gradle  
- Docker and Docker Compose  
- PostgreSQL  
- Swagger (OpenAPI 3)

## Contributing

Contributions are welcome. To contribute:

- Keep tutorials in separate folders  
- Maintain consistent structure and naming  
- Add a README or notes for new tutorials  
- Write clean and readable code  

Pull requests are appreciated.

## License

This project is open-source. You are free to use it for personal learning and experimentation.
