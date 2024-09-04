Travel Insurance Management System
Overview
The Travel Insurance Management System is a Java-based application designed to manage travel insurance policies, claims, and traveler details. It allows users to add, update, retrieve, and delete records related to insurance policies, claims, and travelers. The application is built using Core Java, MySQL, and JDBC, and is structured following the DAO (Data Access Object) design pattern.

Features
Policy Management: Create, retrieve, update, and delete insurance policies.
Traveler Management: Add, update, view, and remove traveler details.
Claim Management: Register, view, update, and delete insurance claims.
Project Structure
The project is organized into the following packages:

com.cts.main_package: Contains the MainClass that serves as the entry point of the application.
com.cts.travelinsurance.dao: Contains DAO interfaces and their implementations for interacting with the database.
com.cts.travelinsurance.exception: Custom exceptions like ClaimNotFoundException, PolicyNotFoundException, and TravelerNotFoundException.
com.cts.travelinsurance.model: Contains model classes (Policy, Claim, and Traveler) representing the database entities.
com.cts.travelinsurance.service: Contains service classes that handle the business logic for managing policies, claims, and travelers.
com.cts.travelinsurance.util: Contains utility classes such as DBConnection for establishing database connections.
Prerequisites
Java JDK 8 or later
MySQL Server
NetBeans IDE
MySQL JDBC Driver
Setup Instructions
1. Clone the Repository
sh
Copy code
git clone https://github.com/YourUsername/TravelInsuranceManagementSystem.git
cd TravelInsuranceManagementSystem
2. Set Up the MySQL Database
Open MySQL Workbench or any MySQL client.
Create a database named travelinsurance.
Run the SQL scripts provided in the /sql directory to set up the required tables (e.g., Policy, Claim, Traveler).
3. Open the Project in NetBeans
Launch NetBeans IDE.
Go to File > Open Project.
Navigate to the cloned project directory and select it.
Wait for NetBeans to load and index the project.
4. Configure the MySQL JDBC Driver
Right-click on the project in the NetBeans Project Explorer.
Select Properties.
Go to Libraries and ensure the MySQL JDBC driver (mysql-connector-java-8.0.28.jar) is added to the classpath.
5. Run the Project
In the NetBeans Project Explorer, locate the MainClass.java file under com.cts.main_package.
Right-click on MainClass.java and select Run File.
The console will display a menu to manage policies, travelers, and claims.
6. Test the Application
Select an option from the menu (e.g., 1 for Policy Management).
Follow the on-screen instructions to add, view, update, or delete records.
The application interacts with the MySQL database in real-time, ensuring persistence of data.
Usage
Option 1: Policy Management
Add new policies, view existing policies, update policy details, and delete policies.
Option 2: Traveler Management
Register travelers, retrieve traveler details, update traveler information, and remove travelers.
Option 3: Claim Management
Register insurance claims, view claim details, update claims, and delete claims.
Contact
For any inquiries or issues, please contact Pranjal Piparsania at pranjalpiparsania@gmail.com.
