This project is a Java-based Online Reservation System with MySQL database integration.
It allows users to book, cancel, and view train reservations through a simple console-based interface.
The project demonstrates JDBC connectivity, SQL database handling, and object-oriented programming concepts in Java.

Features:
Book a new reservation
Cancel an existing reservation
View all reservations
Data stored securely in MySQL database

Tech Stack:
. Programming Language: Java
. Database: MySQL
. Connector: JDBC


Installation & Setup:
1. Clone the repository:
           git clone https://github.com/mdzulfikar-dev/OnlineReservationSystem.git
           cd online-reservation-system
2. Create a MySQL Database: 
          CREATE DATABASE DetailsOfPassenger;
3. Create the Required Table:
          Use the following SQL commands to create the table:
               CREATE TABLE reservations (
                   pnr_number INT PRIMARY KEY,
                   passenger_name VARCHAR(100) NOT NULL,
                   train_number VARCHAR(20) NOT NULL,
                   class_type VARCHAR(20) NOT NULL,
                   journey_date VARCHAR(20) NOT NULL,
                   from_station VARCHAR(50) NOT NULL,
                   to_station VARCHAR(50) NOT NULL
               );
  
