# 📚 Library Management System

A full-stack **Library Management System** built using **Java, Spring Boot, Spring Data JPA, MySQL, Thymeleaf, HTML, CSS, Bootstrap, and JavaScript**. The application automates library operations such as book management, student registration, book issue/return, and inventory tracking through a secure and user-friendly interface.

---

## 🚀 Features

- 🔐 Secure Admin Login Authentication
- 📖 Add, Update, Delete, and Search Books
- 👨‍🎓 Student Registration & Management
- 📚 Issue Books to Students
- 🔄 Return Books with Status Update
- 📅 Due Date Tracking
- 📊 Dashboard with Library Statistics
- 🔍 Search Books by Title, Author, or ID
- 📦 Real-time Book Availability Management
- 🚪 Secure Logout Functionality
- 💾 Persistent Data Storage using MySQL

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Frontend
- Thymeleaf
- HTML5
- CSS3
- Bootstrap
- JavaScript

### Database
- MySQL

### Tools
- IntelliJ IDEA / Eclipse
- Maven
- Git & GitHub

---

## 📂 Project Structure

```
Library-Management-System
│── src
│   ├── main
│   │   ├── java
│   │   ├── resources
│   │   └── templates
│── pom.xml
│── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Library-Management-System.git
```

### 2. Navigate to Project

```bash
cd Library-Management-System
```

### 3. Configure MySQL Database

Create a database:

```sql
CREATE DATABASE library_db;
```

Update the database credentials in:

```
src/main/resources/application.properties
```

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=root
spring.datasource.password=your_password
```

### 4. Run the Application

```bash
mvn spring-boot:run
```

or run the `LibraryManagementApplication.java` file directly from your IDE.

---

## 📸 Application Screenshots

### Loading Screen

![Loading](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/31d70921-d5ab-4fd7-907f-61e68e28da49)

---

### Login Page

![Login](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/7668e6d6-eed4-43e4-8dfa-a54c0b37d359)

---

### Dashboard

![Home](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/cdc516a9-17fb-4da6-bc1f-27b704360530)

---

### Add New Book

![Add Book](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/819581a7-a91e-4650-a50c-04a6eaf7d513)

---

### Student Registration

![Student Registration](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/b6b2d0e1-0187-4f50-a662-4c735ba50d33)

---

### Book Issue

![Issue Book](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/d7f240ee-e93f-4a04-b3b8-27dfbb9cf814)

---

### Book Return

![Return Book](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/8aef7cf9-15e2-4e6d-aa62-b854e8a43fd7)

---

### Logout

![Logout](https://github.com/sudhirkumar85/Library-Management-System-Project/assets/84500245/1b224c1e-2ca2-448e-8f87-220a8662245a)

---

## 🎯 Key Functionalities

- Admin authentication
- Book inventory management
- Student registration
- Book issue and return workflow
- Automatic availability tracking
- Search and filtering
- Database persistence
- Responsive user interface

---

## 📈 Future Enhancements

- Email notifications for due dates
- Fine calculation for late returns
- QR Code / Barcode integration
- Role-based access (Admin & Student)
- REST API support
- Docker deployment
- Cloud deployment (AWS/Render)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Rajan Kumar**

- GitHub: https://github.com/Rajan263
- LinkedIn: https://linkedin.com/in/rajan-kumar263

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub. It helps others discover the project and supports future improvements.



