# 🏨 Hotel Reservation System

A console-based **Hotel Reservation System** built using **Java, JDBC, and MySQL**. The application allows users to manage hotel reservations through a simple command-line interface.

## ✨ Features

* 🛏️ Reserve a room
* 📋 View all reservations
* 🔍 Find room number using reservation details
* ✏️ Update reservations
* 🗑️ Delete reservations
* 🚪 Exit the application

## 🛠️ Technologies Used

* **Java**
* **JDBC**
* **MySQL**
* **MySQL Connector/J**

## 🗄️ Database

The application uses a MySQL database named `hotel_db` with a `reservations` table.

```sql
CREATE DATABASE hotel_db;

USE hotel_db;

CREATE TABLE reservations (
    reservation_id INT AUTO_INCREMENT PRIMARY KEY,
    guest_name VARCHAR(100) NOT NULL,
    room_number INT NOT NULL,
    contact_number VARCHAR(20) NOT NULL,
    reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

## 🚀 How to Run

1. Clone the repository.
2. Create the `hotel_db` database and `reservations` table.
3. Configure your MySQL username and password in the application.
4. Add the MySQL JDBC driver to the project.
5. Run `HotelReservationSystem.java`.

## 📚 Concepts Practiced

* Java Classes & Methods
* Exception Handling
* JDBC
* `Connection`
* `Statement`
* `ResultSet`
* SQL CRUD Operations
* User Input using `Scanner`

## Usage 📋
Upon running the application, you'll be presented with a menu to choose your desired operation (reservation, viewing, editing, or exiting).

Follow the prompts to input reservation details, view current reservations, edit existing bookings, and more.

## 👨‍💻 Author

**Priyanshu**

Built as a Java + JDBC learning project to practice database connectivity and CRUD operations.
