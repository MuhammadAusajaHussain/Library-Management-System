# 📚 Library Management System

A web-based Library Management System built using **Spring Boot**, **Thymeleaf**, and **Oracle Database**, designed to simplify library operations for both users and administrators. This system supports book reservation, fine management, user profile control, and real-time database integration with Oracle using JDBC.

## 🚀 Features

### 👤 User Features
- User registration and secure login/logout
- Book search and reservation
- Reservation cancellation before expiry
- Fine viewing and payment
- Profile viewing and editing
- View borrowing and reservation history

### 🛠️ Admin Features
- Role-based admin dashboard
- Manage books (add, update, delete, view)
- Manage genres and categories
- Manage user accounts and profiles
- View and cancel reservations
- Handle overdue items and fines

## 🛠️ Tech Stack

- **Frontend:** HTML, Thymeleaf
- **Backend:** Java, Spring Boot
- **Database:** Oracle DB (via JDBC)
- **Tools:** Maven, Spring JDBC, Visual Studio Code / IntelliJ

## ⚙️ Installation & Setup

### Prerequisites
- Java 11+
- Maven
- Oracle Database (18c or above)
- IDE (like IntelliJ IDEA or VS Code)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
   ```

2. Configure `application.properties`:
   - Set your Oracle DB connection string, username, and password.

3. Create required tables:
   - Use the provided SQL script or run triggers and schema manually.

4. Build and run the application:
   ```bash
   mvn spring-boot:run
   ```

5. Open in browser:
   ```
   http://localhost:8080/
   ```

## 🧪 Testing

- Includes unit testing for key services and integration testing for controller-layer functionalities.
- Tested across modern web browsers for responsiveness and performance.

## 📸 Snapshots

- Login
![image](https://github.com/user-attachments/assets/2b6338c7-3aa6-49fb-b699-f237654c8f13)

- Register
![image](https://github.com/user-attachments/assets/f2a46e5b-8a9f-4b1f-aef0-ee838d4e2c75)

- Admin Dashboard
![image](https://github.com/user-attachments/assets/9913b3b3-06db-4d0c-a9b1-5382ce382b26)

- Manage Users
![image](https://github.com/user-attachments/assets/7f251eec-91cf-466c-937b-985c57b3592a)

- Manage Books
![image](https://github.com/user-attachments/assets/e0316641-a5a8-4209-8a7d-642f2d1cebab)

- User Dashboard, Manage Books/Users, Reserve Books, Overdue & Fine pages.


## 🙌 Contributors

- [Ammar Hyder (22K-4816)]()
- [Muhammad Ausaja Hussain (22K-5186)](https://github.com/ausajahussain)

---

> This project was developed as part of our **Database Systems** course at FAST NUCES Karachi.
