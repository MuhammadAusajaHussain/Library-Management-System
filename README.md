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
- **Login Page**
![image](https://github.com/user-attachments/assets/6bd2dc99-b34b-4faf-9268-fca5f39e1975)

- **Registration Page**
![image](https://github.com/user-attachments/assets/0957db4d-4920-4988-acc4-66e8c2b0053a)

- **Admin Home Page**
![image](https://github.com/user-attachments/assets/9bda023e-753f-4bdc-b00f-45870f645513)

- **Manage Users**
![image](https://github.com/user-attachments/assets/ed7db79f-b8bb-46e4-8e1c-22bcc26772b6)

- **Manage Books**
![image](https://github.com/user-attachments/assets/99356e44-2134-4149-8aa1-7e3374a9ec3c)

- **View/Edit Books**
![image](https://github.com/user-attachments/assets/b150b88a-0f4b-42e2-ba9d-a648e2750f78)

- **Edit User**
![image](https://github.com/user-attachments/assets/e5d9525a-4f20-4331-b05f-08dd4cf46a99)

- **View Reservation**
![image](https://github.com/user-attachments/assets/f01ee1d0-dbc0-4ec8-a72b-f91a99d130a4)

- **OverDue**
![image](https://github.com/user-attachments/assets/f2854309-dd53-40bb-b4f5-cf912f2f26e9)

- **Manage Fine**
![image](https://github.com/user-attachments/assets/b44750f3-3575-4937-882d-0b4b11d490a7)

- **User Home**
![image](https://github.com/user-attachments/assets/19dd16b7-b466-4f01-89e3-8ef168e3ea0a)

- **View Profile**
![image](https://github.com/user-attachments/assets/95ca82ec-13eb-4f7a-923a-fa638630cc26)

- **Edit Profile**
![image](https://github.com/user-attachments/assets/37c59524-23c2-41c4-bb4a-03f609e6a294)

- **Borrow Books**
![image](https://github.com/user-attachments/assets/a6246db9-35d0-430a-bf51-751a8460153d)

- **Reserved Books**
![image](https://github.com/user-attachments/assets/3d99f18d-b68b-4364-a26a-54b4464b7e6e)

- **Reserve Books**
![image](https://github.com/user-attachments/assets/e32e7d92-79cd-4320-9e67-6dcff2f0e6e9)

- **Return Books**
![image](https://github.com/user-attachments/assets/be58eb3c-0108-46c4-972f-a5a19e30629d)

- **Check/Pay**
![image](https://github.com/user-attachments/assets/ae7f9043-09d1-4dd1-a3ce-e668d70632f0)

- **Fine**
![image](https://github.com/user-attachments/assets/490aa6c6-055f-4d19-9868-90de7919c9a8)

## 🙌 Contributors
- [Ammar Hyder](https://github.com/ammar-hyder)
- [Muhammad Ausaja Hussain](https://github.com/MuhammadAusajaHussain/)

---

> This project was developed as part of our **Database Systems** course at FAST NUCES Karachi.
