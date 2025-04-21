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

- Login, Register, Admin/User Dashboards, Manage Books/Users, Reserve Books, Overdue & Fine pages.

## 📈 Future Enhancements

- Mobile app version
- Notification system (email/SMS)
- ML-based book recommendations
- QR Code scanning for book identification
- Analytics dashboard for Admin
- Multi-language support

## 🙌 Contributors

- [Ammar Hyder (22K-4816)]()
- [Muhammad Ausaja Hussain (22K-5186)](https://github.com/ausajahussain)

---

> This project was developed as part of our **Database Systems** course at FAST NUCES Karachi.
