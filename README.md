# Online-virtual-test
# Online Virtual Test Project

## Introduction
This project is an **Online Virtual Test** system developed in Java. It allows users to create, manage, and take online tests. The system includes both an administrative interface and a user interface, providing robust functionality for test creation, management, and evaluation.

## Features
- **User Authentication**: Secure login for administrators and students.
- **Test Creation and Management**: Administrators can create, edit, and delete tests.
- **Automated Grading**: Automated grading system for objective questions.
- **Result Management**: View and manage test results.

## Technology Stack
- **Programming Language**: Java
- **Frontend**: JSP, JavaScript
- **Backend**: Java Servlets, JSP
- **Database**: MySQL
- **IDE**: Eclipse IDE
- **Web Server**: Apache Tomcat 9
- **Text Editor**: Sublime Text
- **Supported Operating Systems**: Windows, Linux
- **Web Browsers**: Google Chrome, Mozilla Firefox

## Installation

### Prerequisites
- **Operating System**: Windows or Linux
- **JDK**: Ensure Java Development Kit (JDK) is installed.
- **Eclipse IDE**: Install Eclipse IDE for Java EE Developers.
- **Apache Tomcat 9**: Download and configure Apache Tomcat 9.
- **MySQL**: Install MySQL and set up the necessary databases.
- **Web Browser**: Install Chrome or Firefox for the best experience.
- **Text Editor**: Optionally, install Sublime Text for code editing.

### Steps to Set Up the Project
1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```

2. **Set up MySQL Database**:
    - Create a new database in MySQL.
    - Run the provided SQL scripts in the `/database` folder to set up the tables and initial data.

3. **Import the project into Eclipse IDE**:
    - Open Eclipse IDE.
    - Go to `File > Import > Existing Projects into Workspace`.
    - Select the cloned repository.

4. **Configure Tomcat Server**:
    - In Eclipse, go to `Servers` tab.
    - Right-click and select `New > Server > Apache > Tomcat v9.0 Server`.
    - Choose the Tomcat installation directory.
    - Add the project to the server and save.

5. **Build and Deploy the Project**:
    - Right-click on the project in Eclipse.
    - Select `Run As > Run on Server`.
    - Choose the configured Tomcat server.

6. **Access the Application**:
    - Open your web browser (Chrome or Firefox).
    - Navigate to `http://localhost:8080/OnlineVirtualTest`.

## Usage
- **Admin Interface**: Login using admin credentials to create, manage tests, and view results.
- **Student Interface**: Login using student credentials to take tests and view grades.

## Contribution
If you wish to contribute to this project, please fork the repository and create a pull request with your proposed changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- **JDK** for the Java programming environment.
- **Eclipse IDE** for development support.
- **Tomcat** for providing the web server environment.
- **MySQL** for database management.
- **Sublime Text** for code editing.
- **Google Chrome & Mozilla Firefox** for web browsing.

---

**Disclaimer**: This project is for educational purposes only.
