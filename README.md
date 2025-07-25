# Studapp


# StudentApp

A menu-driven Java console application for managing student records using **Maven**, **JPA**, and **Hibernate 7.x**. 
This project supports basic **CRUD operations** (Create, Read, Update, Delete) with an in-memory H2 database.


** Features

- Add a new student
- View student by ID
- List all students
- Update student details
- Delete a student
- Uses JPA with Hibernate 7.x and H2 in-memory database


** Technologies Used

- Java 17+ (or higher)
- Maven
- JPA (Jakarta Persistence API)
- Hibernate ORM 7.x
- H2 Database (in-memory)
- Console (Scanner-based) user interface


/**/ Project Structure

```

StudentApp/
├── pom.xml
├── src/
│   └── main/
│       ├── java/
│       │   └── com/example/studentapp/
│       │       ├── Main.java
│       │       ├── dao/StudentDAO.java
│       │       ├── entity/Student.java
│       │       └── util/JPAUtil.java
│       └── resources/
│           └── META-INF/
│               └── persistence.xml


# Run

### 1. Clone the Repository

git clone https://github.com/your-username/StudentApp.git
cd StudentApp

2. Build the Project

Make sure Maven is installed, then:

mvn clean install


3. Run the App

mvn exec:java -Dexec.mainClass="com.example.studentapp.Main"


```bash
javac -d target/classes src/main/java/com/example/studentapp/**/*.java
java -cp target/classes com.example.studentapp.Main


 Example Output

```
==== Student Management ====
1. Add Student
2. View Student by ID
3. View All Students
4. Update Student
5. Delete Student
0. Exit
Enter choice: _



## 🙋‍♂️ Author

--- shreyas kabane
	--- github https://github.com/shreyas-k00/project-s
