This project is a Java-based Online Reservation System with MySQL database integration.
It allows users to book, cancel, and view train reservations through a simple console-based interface.
The project demonstrates JDBC connectivity, SQL database handling, and object-oriented programming concepts in Java.

**Features**

     Book a new reservation
     Cancel an existing reservation  
     View all reservations
     Data stored securely in MySQL database
     
**Tech Stack**
1. Programming Language: Java
2. Database: MySQL
3. Connector: JDBC

**Installation & Setup**
1. Clone the repository:
           git clone https://github.com/mdzulfikar-dev/OnlineReservationSystem.git
   
           cd online-reservation-system  
          
        

          
        
3. Create a MySQL Database and it also contains reaservations table:

           ```sql
           CREATE DATABASE DetailsOfPassenger;
           CREATE TABLE reservations (
                   pnr_number INT PRIMARY KEY,
                   passenger_name VARCHAR(100) NOT NULL,
                   train_number VARCHAR(20) NOT NULL,
                   class_type VARCHAR(20) NOT NULL,
                   journey_date VARCHAR(20) NOT NULL,
                   from_station VARCHAR(50) NOT NULL,
                   to_station VARCHAR(50) NOT NULL
           );
           
4. **Update Database Credentials in Code**

          String url = "jdbc:mysql://localhost:3306/DetailsOfPassenger";
          String username = "your-username";
          String password = "your-password";  
        
5. **Run the Project**

          - Open the project in your IDE (IntelliJ, Eclipse).  
          - Compile and run OnlineReservation.java.
6. **Usage**

           Run the program.
           Follow the menu to:
                   1. Book a new reservation
                   2. Cancel reservation
                   3. View reservations
                   4. Exit
   
7. **Contributing**

             Contributing Feel free to contribute to this project by creating issues, suggesting improvements, or submitting pull requests. Your contributions are greatly appreciated! 
        


   
   
   
           

     
          


              
                                                                                           
