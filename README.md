# 🎓 EazySchool

A modern **Spring Boot-based** school management system offering secure, scalable, and modular components to manage educational workflows like student registrations, class enrollments, and staff roles.

---

## 🚀 About the Project

**EazySchool** is a robust and modular **school management platform** built using modern Spring technologies. The system is designed to streamline the management of school-related operations, such as handling students, courses, enrollments, and user roles. By leveraging the power of **Spring Boot**, **Spring Security**, and **Spring Data JPA**, the application offers secure role-based authentication and efficient data handling with MySQL. It also implements **Spring AOP** to facilitate logging and performance monitoring for better traceability. Whether you're managing teachers, students, or system admins — EazySchool provides a **complete backend solution** that is extendable and production-ready.

---

## ✨ Features

- ✅ **Role-Based Authentication** (Admin, Teacher, Student)
- 🔐 **Spring Security** for secure access management
- 🔄 **Spring AOP** for logging and performance tracking
- 💾 **Spring Data JPA + Hibernate** for ORM
- 📊 **Spring JDBC** for lightweight DB access
- 🏫 Manage Students, Courses, Enrollments, Users

---

## 🛠️ Tech Stack

| Layer        | Technology                                     |
|--------------|------------------------------------------------|
| **Backend**  | Spring Boot, Spring Security, Spring AOP       |
|              | Spring Data JPA, Spring JDBC, Hibernate        |
| **Database** | MySQL                                          |
| **Build**    | Maven                                          |
| **Auth**     | Session + Role-Based Access (Spring Sec)  |

---

## 🧰 Project Structure

```
EazySchool/
│
├── src/
│   └── main/
│       ├── java/com/eazyschool/
│       │   ├── controllers/
│       │   ├── services/
│       │   ├── models/
│       │   ├── config/
│       │   └── repository/
│       └── resources/
│           ├── application.properties
│           └── templates/
│
├── pom.xml
├── README.md
└── .gitignore
```

---

## ⚙️ Setup & Installation

### 🔁 Clone the Repository
```bash
git clone https://github.com/beingnikil07/EazySchool.git
cd EazySchool
```

### 🧩 Configure Database
Edit `application.properties` with your MySQL credentials:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/eazyschool
spring.datasource.username=root
spring.datasource.password=yourpassword
```

### 🛠️ Build & Run
```bash
mvn clean install
mvn spring-boot:run
```

### 🌐 Access
Open your browser:  
[http://localhost:8080](http://localhost:8080)

---

## 🔑 Default Login Credentials

| Role   | Email/Username         | Password  |
|--------|------------------------|-----------|
| Admin  | admin@eazyschool.com   | nik@123   |
| User   | student_username       | your_pass |

---

## 📸 Screenshots (Optional)
```
screenshots/
├── login.png
├── dashboard.png
├── student-list.png
```

---

## 🤝 Contributing

Want to improve EazySchool?  
- Fork the repository
- Create a new branch
- Submit a Pull Request

We welcome all contributions — code, ideas, or documentation!

---

## 📜 License

Distributed under the **MIT License**.  
See `LICENSE` for more information.

---

## 🙋‍♂️ Author

**👨 Nikil Kumar**  
📧 [beingnikil07@gmail.com](mailto:beingnikil07@gmail.com)  
🔗 [GitHub](https://github.com/beingnikil07)  
🔗 [LinkedIn](https://www.linkedin.com/in/nikilkumar07/)  
🌐 [Portfolio](https://nikhilrana07.vercel.app/) 

> If you found this project helpful, don’t forget to ⭐ the repo!
