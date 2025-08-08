# Rental-Car-Application
# 🚗 Car Rental Service Application

A Java-based Car Rental Service Management System that allows users to book, manage, and return rental cars efficiently. This application simulates a real-world car rental platform with features for customers, admins, and vehicle management.

## 🛠️ Tech Stack

- **Java** (Core Java, OOPs)
- **JDBC / MySQL** (or any DB of your choice)
- **Java Swing** (for GUI) *(Optional)*
- **Apache Maven** *(Optional)*
- **JUnit** (for testing)

## 📌 Features

### 🧑 For Customers:
- User Registration & Login
- Browse Available Cars
- Book/Rent a Car
- Return a Car
- View Rental History

### 👨‍💼 For Admin:
- Login Dashboard
- Add/Remove Cars
- View All Rentals
- Manage Customers
- Car Availability Management

## 📂 Project Structure

CarRentalApp/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ ├── model/
│ │ │ ├── dao/
│ │ │ ├── service/
│ │ │ └── ui/
│ └── test/
│ └── java/
│ └── tests/
├── resources/
│ └── application.properties
├── README.md
└── pom.xml (if using Maven)


## 🔧 How to Run

### Prerequisites:
- Java 8 or higher installed
- MySQL or any relational DB
- IDE like IntelliJ IDEA / Eclipse / VS Code
- JDBC driver
- Maven (if applicable)

### Steps:

1. Clone the repo:
    ```bash
    git clone https://github.com/your-username/car-rental-service.git
    cd car-rental-service
    ```

2. Configure the database:
    - Create a database (e.g., `car_rental_db`)
    - Import `schema.sql` and `data.sql` (if provided)
    - Update DB credentials in `application.properties` or hardcoded in the DAO class.

3. Compile and run:
    ```bash
    javac Main.java
    java Main
    ```
    or use your IDE to run the `Main.java` file.

> If using Maven:
```bash
mvn clean install
mvn exec:java

