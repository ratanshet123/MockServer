# MockServer1

A mock server with CRUD operations built using Spring Boot.

## Prerequisites

- Java 17 or higher
- Maven
- Git
- Eclipse IDE

## Getting Started

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/MockServer1.git
cd MockServer1


-----------------------------------------------------------------------



```bash 
Import the Project into Eclipse
Open Eclipse.
Import the project:
Go to File > Import.
Select Maven > Existing Maven Projects.
Click Next.
Browse to the directory where you cloned the project.
Select the project and click Finish.
--------------------------------------------------------------------------------


##Set Up and Install Dependencies
Build the project:

Right-click on the project in the Project Explorer.
Select Run As > Maven build....
In the Goals field, enter clean package.
Click Run.
Run the application locally:
--------------------------------------------------------------------
Right-click on the project in the Project Explorer.
Select Run As > Spring Boot App.
--------------------------------------------------------------------------
# MySQL Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/your-database-name
spring.datasource.username=your-username
spring.datasource.password=your-password
spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect
spring.jpa.hibernate.ddl-auto=update
----------------------------------------------------------------------------
Running Tests
To run the tests for this project:

Right-click on the project in the Project Explorer.
Select Run As > Maven test.
Endpoints
Students
GET /students: Get all students.
GET /students/{usn}: Get a student by USN.
POST /students: Add a new student.
PUT /students/{usn}: Update a student's details.
DELETE /students/{usn}: Delete a student 


