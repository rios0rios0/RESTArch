<h1 align="center">REST Arch</h1>
<p align="center">
    <a href="https://github.com/rios0rios0/rest-arch/releases/latest">
        <img src="https://img.shields.io/github/release/rios0rios0/rest-arch.svg?style=for-the-badge&logo=github" alt="Latest Release"/></a>
    <a href="https://github.com/rios0rios0/rest-arch/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/rios0rios0/rest-arch.svg?style=for-the-badge&logo=github" alt="License"/></a>
</p>

A RESTful architecture reference project built with Java and Spring Boot, demonstrating clean REST service patterns.

## Features

- Spring Boot-based REST service skeleton
- Maven build system with Java 8 support
- Pre-configured application properties and test setup

## Project Structure

```
src/
  main/
    java/com/services/RestService.java    # REST service implementation
    resources/application.properties      # Application configuration
  test/
    java/com/ApplicationTest.java         # Application tests
pom.xml                                   # Maven project descriptor
```

## Installation

```bash
git clone https://github.com/rios0rios0/rest-arch.git
cd rest-arch
mvn clean install
```

## Usage

Run the application with:

```bash
mvn spring-boot:run
```

The REST service will start on the default Spring Boot port.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.
