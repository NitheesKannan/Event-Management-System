# Event Management System – BookMyEvent

## 📌 Project Overview

BookMyEvent is a web-based Event Management System developed to simplify event creation, event registration, and transaction management. The application provides separate interfaces for administrators and participants, allowing administrators to manage events and participants to register for available events.

The project uses Java Servlets for backend processing, HTML and CSS for the user interface, and MySQL for database operations.

## ✨ Features

- **Admin Login:** Secure access to event management functions.
- **Participant Registration:** New users can create an account.
- **Participant Login:** Existing users can log in to the application.
- **Create Events:** Administrators can add new events with details such as event name, coordinator, registration fee, and venue.
- **View Events:** Display available event details.
- **Delete Events:** Remove events from the system.
- **Event Registration:** Participants can register for events.
- **Payment Interface:** Provides a payment-related page for event registration.
- **Transaction Management:** View transaction details.
- **Email Functionality:** Includes email-related functionality using Java Mail.

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Java, Java Servlets
- **Database:** MySQL
- **Database Connectivity:** JDBC
- **Server:** Apache Tomcat

## 📂 Project Structure

```text
EventManagementSystem/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/event/
│       │       ├── CreateEvent.java
│       │       ├── DeleteEvent.java
│       │       ├── Fetch.java
│       │       ├── FetchAD.java
│       │       ├── FetchTransaction.java
│       │       ├── GeneTicket.java
│       │       ├── SendEmailServlet.java
│       │       ├── StoreLogin.java
│       │       └── Verify.java
│       └── webapp/
│           ├── index.html
│           ├── Alogin.html
│           ├── Plogin.html
│           ├── Psignup.html
│           ├── EventDetails.html
│           ├── CreateE.html
│           ├── Registration.html
│           ├── Payment.html
│           ├── TransactionDetails.html
│           ├── styles.css
│           ├── total.css
│           └── WEB-INF/
│               └── web.xml
└── README.md
```

## ⚙️ Prerequisites

Make sure you have installed:

- Java Development Kit (JDK)
- Eclipse IDE or another Java IDE
- Apache Tomcat compatible with the Servlet API used by the project
- MySQL Server
- MySQL Connector/J

## 👥 User Roles

### Administrator
- Log in to the admin interface.
- Create and view events.
- Delete events.
- View transaction details.

### Participant
- Register for a new account.
- Log in to the application.
- View available events.
- Register for events.
- Access the payment interface.

## 🎯 Project Objective

The main objective of this project is to develop a centralized web application that makes event management easier by organizing event information, participant registration, and transaction records in one place.

## 👨‍💻 Author

**Nithees Kannan S**

GitHub: https://github.com/NitheesKannan


This project is intended for educational and learning purposes. Add a license file if you wish to distribute it under specific license terms.
