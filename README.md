# CRUD App with React.js and Spring Boot

This repository contains a CRUD (Create, Read, Update, Delete) application built using React.js for the frontend and Spring Boot for the backend.

## Features

- Create, Read, Update, and Delete operations on data.
- Frontend built with React.js, providing a responsive and interactive user interface.
- Backend powered by Spring Boot, offering RESTful APIs for data manipulation.
- Uses a database (e.g., MySQL, PostgreSQL, MongoDB) for persistent data storage.

## Installation

### Prerequisites

- Node.js and npm installed globally on your machine.
- Java Development Kit (JDK) installed, preferably JDK 8+.
- Your preferred IDE or text editor for development (e.g., IntelliJ IDEA, VS Code).

### Steps

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/PrathmeshMSutar/ReactJS-Spring-Boot-CRUD_Full-Stack-Application/
    ```

2. Navigate to the project directory:

    ```bash
    cd crud-app
    ```

3. Install frontend dependencies:

    ```bash
    cd frontend
    npm install
    ```

4. Install backend dependencies:

    ```bash
    cd ../backend
    ./mvnw install
    ```

## Usage

1. Start the backend server:

    ```bash
    cd ../backend
    ./mvnw spring-boot:run
    ```

2. Start the frontend development server:

    ```bash
    cd ../frontend
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to use the application.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any bugs or feature requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to the creators of React.js and Spring Boot for providing excellent frameworks for building web applications.
