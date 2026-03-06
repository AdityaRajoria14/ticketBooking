🎟️ Train Ticket Booking System

A console-based Train Ticket Booking System built using Java and Gradle.
This project simulates a simple train ticket reservation system where users can view trains and book tickets.

The project demonstrates core Java backend concepts such as object-oriented design, service layers, and local data storage using JSON files.

🚀 Features
View available trains
Book train tickets
Manage users
Store data using local JSON files
Modular service-based architecture

🛠️ Tech Stack
Java
Gradle
JSON (Local Storage)

📂 Project Structure
ticketBooking
│
├── app
│   ├── build.gradle
│   └── src
│       ├── main
│       │   └── java/ticket/booking
│       │       ├── App.java
│       │       ├── entities
│       │       │   ├── Ticket.java
│       │       │   ├── Train.java
│       │       │   └── User.java
│       │       ├── service
│       │       │   ├── TrainService.java
│       │       │   └── UserBookingService.java
│       │       ├── util
│       │       │   └── UserServiceUtil.java
│       │       └── localDB
│       │           ├── trains.json
│       │           └── users.json
│       │
│       └── test
│           └── java/ticket/booking
│               └── AppTest.java
📚 Key Concepts Used

Object-Oriented Programming (OOP)
Layered Architecture (Entities, Services, Utilities)
JSON-based local data storage
Gradle build system
