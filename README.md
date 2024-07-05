# Student-Registration-System-Java
A Java-based student registration system with MySQL database integration, featuring user login, registration, and management functionalities. Created for practice and skill enhancement in Java and database management.


Here's details for your GitHub project:

---

# Student Registration System

## Project Description
A student registration system developed in Java using NetBeans, featuring user login, registration, and management functionalities. This project utilizes a MySQL database for data storage and management.

## Features
- User Authentication (Login and Logout)
- Student Registration
- Student Information Management (Add, Update, Delete, Search)
- User-Friendly Interface

## Setup Instructions

### Prerequisites
- Java Development Kit (JDK) installed
- NetBeans IDE installed
- MySQL Server installed

### Project Setup

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/Student-Registration-System-Java.git
   ```

2. **Open the Project in NetBeans**
   - Open NetBeans IDE.
   - Navigate to `File -> Open Project`.
   - Select the cloned project folder `SkillInternational` and open it.

3. **Import the Database**
   - Open MySQL Workbench or any other MySQL client.
   - Create a new database named `student`.
   - Import the database dump file located in the `Dump20240705` folder.
     ```sh
     mysql -u yourusername -p student < path/to/Dump20240705/dumpfile.sql
     ```

4. **Update Database Connection Details**
   - In NetBeans, navigate to the `Database` package in the project.
   - Open the `db` class.
   - Update the MySQL username, password, and database name as required.

     ```java
     // Example db class configuration
     String url = "jdbc:mysql://localhost:3306/student";
     String username = "yourusername";
     String password = "yourpassword";
     ```

5. **Run the Project**
   - Right-click the project in NetBeans and select `Run`.

## Usage
- On running the project, the login form will appear.
- Use the credentials `Admin` and `Skills@123` to log in.
- After logging in, the registration form will be displayed, allowing you to manage student records.

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.

---
