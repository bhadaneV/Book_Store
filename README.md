# Online Book Store

An Online Book Store web application built using **Spring Boot**, **Thymeleaf**, and supports **both MySQL and H2 databases**. It allows users to register, browse, search, purchase, rate, and review books.
---

## 📅 Project Features

* User Registration & Login
* Role-based View Management (Admin, User)
* Book Listing, Adding, Editing & Deleting
* Book Details with Ratings and Reviews
* Order Management System
* SweetAlert Integration for Stylish Alerts
* Dual DB Support: MySQL & H2 (In-memory)

---

## 🚀 Technology Stack

* **Java 17**
* **Spring Boot 3.1.3**
* **Spring Data JPA (CRUD Repository)**
* **Thymeleaf**
* **MySQL** & **H2** Database
* **SweetAlert2** for Dialogs
* **Eclipse IDE** / **Visual Studio Code**

---

## ⚙️ Installation and Setup

### Prerequisites:

* Java JDK 17
* Maven
* MySQL Database (optional)

### Clone the Repository

```bash
git clone https://github.com/SLoharkar/Online-Book-Store.git
```

### Open in Your IDE

* Import as a Maven Project in Eclipse or VS Code

### Database Configuration

Configure your database connection in `application.properties` for either:

#### MySQL (Example):

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/bookstore
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

#### H2 (In-Memory):

```properties
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.h2.console.enabled=true
```

### Run the Application

```bash
mvn spring-boot:run
```

Navigate to: `http://localhost:8080`

---

## 🎬 Website Trailer

Watch a live walkthrough:
[Project Trailer on GitHub](https://github.com/SLoharkar/Online-Book-Store/assets/68845746/6cfab389-498e-42ad-82d2-2c26738284f8)

---

## 📷 Website Screenshots

The project includes over 40 UI screenshots covering:

* Login and Registration
* Admin and User Dashboards
* Book Listings & Details
* Order Management
* Alerts and Modals

All screenshots are located in the `Screenshots/` directory.

---

## 📊 Folder Structure (Simplified)

```
online-book-store/
├── src/main/java/
├── src/main/resources/
│   ├── templates/        # Thymeleaf HTML templates
│   └── application.properties
├── Screenshots/
├── pom.xml
└── README.md
```
## ✅ License

This project is open-source and available under the MIT License.
