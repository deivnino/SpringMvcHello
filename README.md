# SpringMvcHello

This repository contains a simple Spring MVC application that serves web content. The application demonstrates the use of Spring Boot, Thymeleaf, and Maven for building and running a web application.

## Features

- Serves a greeting message based on the provided name.
- Uses Thymeleaf for rendering HTML templates.
- Includes Spring Boot DevTools for development convenience.

## Installation

To set up and run the project, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/deivnino/SpringMvcHello.git
   cd SpringMvcHello
   ```

2. **Build the project using Maven:**
   ```sh
   mvn clean install
   ```

3. **Run the application:**
   ```sh
   mvn spring-boot:run
   ```

4. **Access the application:**
   Open a web browser and navigate to `http://localhost:8080`. You should see the index page with a link to the greeting page.

## Usage

- To get a greeting message, click on the "here" link on the index page or navigate to `http://localhost:8080/greeting`.
- You can provide a name as a query parameter to customize the greeting message. For example, `http://localhost:8080/greeting?name=John` will display "Hello, John!".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
