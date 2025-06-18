# Midas

This repository contains the project for the JPMC Advanced Software Engineering Forage program.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Build and Run](#build-and-run)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Midas is a Java-based project developed as part of the J.P. Morgan Chase Advanced Software Engineering Forage program. It is structured as a Maven application and may include multiple services.

## Getting Started

These instructions will help you set up and run the project locally.

### Prerequisites

- Java 17 or higher
- Maven 3.6+
- Git

### Clone the repository

```bash
git clone https://github.com/Nand255/forage-midas.git
cd forage-midas
```

## Project Structure

- `src/` - Main source code for the application.
- `services/` - (If present) Contains microservices or modular components.
- `application.yml` - Main configuration file.
- `pom.xml` - Maven build configuration.
- `.mvn/`, `mvnw`, `mvnw.cmd` - Maven wrapper files for consistent builds.

## Configuration

Application settings can be found and customized in `application.yml`.

## Build and Run

To build the project, use Maven:

```bash
./mvnw clean install
```

To run the application (adjust the command if the main class or module differs):

```bash
./mvnw spring-boot:run
```

Or run the built JAR (after build):

```bash
java -jar target/*.jar
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is for educational purposes as part of a JPMC Forage program. Please check with the repository owner for licensing details.
