# Basic CRUD API

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen) 
A foundational **Create, Read, Update, Delete (CRUD)** API with a complete frontend, built as an academic project using **Spring Boot** for the backend. This application demonstrates the core functionalities for managing `Students` and `Employees` data.

---

## 🚀 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What you need to install the software:

* **Java Development Kit (JDK) 8 or higher**
* **Maven** (for managing dependencies and building the project)
* **Eclipse IDE** (as the project was developed using it, though other IDEs like IntelliJ IDEA can also be used)
* **A SQL Database** (e.g., MySQL, PostgreSQL, H2 - based on `script.sql` and `test.script` presence, likely a relational database)

### Installation

A step-by-step guide to get your development environment running:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Kaiky404/basic-crud-api.git](https://github.com/Kaiky404/basic-crud-api.git)
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd basic-crud-api
    ```
3.  **Import the project into Eclipse:**
    * Open Eclipse.
    * Go to `File` > `Import...` > `Maven` > `Existing Maven Projects`.
    * Browse to the `basic-crud-api` directory and click `Finish`.
4.  **Configure your database:**
    * Locate the `src/main/resources/application.properties` file.
    * Update the database connection properties (e.g., `spring.datasource.url`, `spring.datasource.username`, `spring.datasource.password`) to match your local database setup.
    * Execute the `script.sql` file (and potentially `test.script` if it's for initial data or testing) in your chosen SQL database to create the necessary tables.
5.  **Run the application:**
    * Right-click on the main application file (e.g., `BasicCrudApiApplication.java` in `src/main/java/...`) in Eclipse.
    * Select `Run As` > `Spring Boot App`.
    * The backend API should now be running, typically on `http://localhost:8080` (or whatever port you configured in `application.properties`).
    * The frontend (HTML files) will likely be served by Spring Boot as well, accessible via the root URL or specific paths.

---

## 🛠️ Built With

* **Java**
* **Spring Boot** - Framework for building the backend API
* **Maven** - Dependency Management
* **Eclipse IDE** - Development Environment
* **HTML** - For the complete frontend interface
* **SQL Database** (e.g., H2, MySQL, PostgreSQL - specific to your setup)

---

## ✨ Features

* **Complete CRUD Operations:** Fully functional Create, Read, Update, and Delete operations for both `Students` and `Employees`.
* **Spring Boot Backend:** Robust and efficient backend built with the Spring Boot framework.
* **Full Frontend Integration:** Includes a complete frontend (HTML) to interact with the API.
* **Relational Database Integration:** Persistent data storage using a SQL database.
* **Modular Design:** Organized code structure for clarity and maintainability.

---

## 🤝 Contributing

We welcome contributions! If you have suggestions or find bugs, please feel free to open an issue or submit a pull request.

1.  Fork the repository.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
*(If you haven't created one, please add a `LICENSE` file to your repository.)*

---

## 🧑‍💻 Authors

* **Kaiky de M. B. Viana** - [Kaiky404](https://github.com/Kaiky404)
* **Eduarda de Oliveira Santos** - [EduardaOliveiraSantos](https://github.com/EduardaOliveiraSantos)
