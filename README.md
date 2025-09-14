# Backend Circle Assessment

Welcome to the **Backend Circle** Assessment!  
This document contains the **questions and model answers** for Backend track, divided by **difficulty level**:

- **Beginner** → Basic C# and SQL.  
- **Intermediate** → OOP, Joins, Exception handling.  
- **Advanced** → APIs, Security, REST, Design Patterns.  

Each level has **10 questions** (mix of MCQ + Written).  

---

## 🔹 Level 1 – Beginner (Basic C# + Simple Database + Git)

1. **(MCQ)** What is the main difference between Frontend and Backend in web development?  
   - a) Frontend is responsible for storing and managing data, while Backend focuses on styling and presentation.  
   - b) Frontend runs on the client side (what users see and interact with), while Backend runs on the server side (processing requests, handling data, and business logic).  
   - c) Frontend handles databases, while Backend is only about animations and layouts.  
   - **Answer:** b)  

2. **(MCQ)** Which keyword is used to declare a class in C#?  
   - a) object  
   - b) class  
   - c) struct  
   - **Answer:** b)  

3. **(MCQ)** What is the default access modifier for class members in C#?  
   - a) public  
   - b) private  
   - c) internal  
   - **Answer:** b)  

4. **(Written)** What is the difference between a Class and an Object in C#?  
   - **Answer:** A class is a blueprint for creating objects; an object is an instance of a class.  

5. **(MCQ)** How many Primary Keys can a table have?  
   - a) 0  
   - b) 1  
   - c) One per column  
   - **Answer:** b)  

6. **(Written)** What is the difference between DELETE and TRUNCATE in SQL?  
   - **Answer:**  
     - DELETE removes specific rows (can use WHERE) and can be rolled back.  
     - TRUNCATE removes all rows, resets identity values, and is faster but cannot filter rows.  

7. **(MCQ)** Which data type is a value type in C#?  
   - a) string  
   - b) int  
   - c) object  
   - **Answer:** b)  

8. **(Written)** Explain the role of a Database in a backend system.  
   - **Answer:** A database stores and organizes data, allowing efficient retrieval, modification, and management.  

9. **(MCQ)** In Git, which command is used to check the current state of the repository?  
   - a) git push  
   - b) git status  
   - c) git init  
   - **Answer:** b)  

10. **(Written)** Write a SQL query to select all rows from a table named `Students`.  
   - **Answer:**  
   ```sql
   SELECT * FROM Students;
   ```

## 🔹 Level 2 – Intermediate (OOP + SQL Joins + Exceptions + Git)

1. **(Written)** Explain Encapsulation in Object-Oriented Programming.  
   - **Answer:** Encapsulation is the principle of hiding the internal details of a class and exposing only the necessary parts through public methods or properties. It improves security, flexibility, and maintainability.  

2. **(MCQ)** Which keywords are used to handle exceptions in C#?  
   - a) try/catch  
   - b) throw/catch  
   - c) error/handle  
   - **Answer:** a)  

3. **(Written)** What is the difference between an Interface and an Abstract Class in C#?  
   - **Answer:**  
     - Interface: Defines a contract with no implementation; classes must implement all members.  
     - Abstract Class: Can have both abstract methods (no body) and concrete methods (with body).  

4. **(MCQ)** Which feature allows multiple inheritance in C#?  
   - a) Classes  
   - b) Abstract classes  
   - c) Interfaces  
   - **Answer:** c)  

5. **(Written)** What is Normalization in databases?  
   - **Answer:** Normalization is the process of organizing data to reduce redundancy, enforce integrity, and improve consistency in a database.  

6. **(MCQ)** In C#, which symbol is used for class inheritance?  
   - a) implements  
   - b) extends  
   - c) : (colon)  
   - **Answer:** c)  

7. **(Written)** Explain the difference between Value Types and Reference Types in C#.  
   - **Answer:**  
     - Value Types: Store the actual data directly (e.g., int, bool).  
     - Reference Types: Store a reference (memory address) to the data (e.g., class, object).  

8. **(MCQ)** What does the `using` statement in C# do?  
   - a) Imports namespaces only  
   - b) Ensures resources are disposed of after use  
   - c) Declares a variable  
   - **Answer:** b)  

9. **(Written)** In Git, what is the difference between `git fetch` and `git pull`?  
   - **Answer:**  
     - `git fetch`: Downloads changes from the remote repository but does not merge them into the local branch.  
     - `git pull`: Fetches changes and merges them directly into the current branch.  

10. **(Written)** Write a SQL query to retrieve all customers with their corresponding orders from `Customers` and `Orders`.  
   - **Answer:**  
   ```sql
   SELECT Customers.Name, Orders.OrderId
   FROM Customers
   INNER JOIN Orders 
   ON Customers.CustomerId = Orders.CustomerId;
   ```

## 🔹 Level 3 – Advanced (APIs + Security + Design Patterns + Git)

1. **(Written)** What is REST in web development, and why is it important for backend systems?  
   - **Answer:** REST (Representational State Transfer) is an architectural style for building web services that use stateless communication over HTTP. It is important because it provides scalability, simplicity, and interoperability between systems.  

2. **(MCQ)** Which HTTP method is commonly used to update an existing resource in REST APIs?  
   - a) GET  
   - b) POST  
   - c) PUT  
   - d) DELETE  
   - **Answer:** c) PUT  

3. **(Written)** Explain the difference between Authentication and Authorization.  
   - **Answer:**  
     - Authentication: Verifies the identity of a user (who they are).  
     - Authorization: Determines the permissions and access rights of an authenticated user (what they can do).  

4. **(MCQ)** Which of the following is the most secure way to store user passwords?  
   - a) Plain text in the database  
   - b) Encrypted using reversible encryption  
   - c) Hashed with a strong algorithm (e.g., bcrypt, SHA-256 with salt)  
   - **Answer:** c)  

5. **(Written)** What is Dependency Injection and why is it useful in backend development?  
   - **Answer:** Dependency Injection (DI) is a design pattern where objects receive their dependencies from an external source rather than creating them internally. It promotes loose coupling, easier testing, and better maintainability.  

6. **(MCQ)** Which design pattern is commonly used to ensure only one instance of a class exists?  
   - a) Singleton  
   - b) Factory  
   - c) Observer  
   - **Answer:** a)  

7. **(Written)** Explain the difference between Synchronous and Asynchronous programming in C#.  
   - **Answer:**  
     - Synchronous: Tasks run one after another; the next task waits until the current one finishes.  
     - Asynchronous: Tasks can run concurrently without blocking execution, improving performance and responsiveness.  

8. **(MCQ)** In Git, what does the command `git rebase` do?  
   - a) Creates a new branch  
   - b) Moves or combines commits onto a new base commit  
   - c) Deletes a branch  
   - **Answer:** b)  

9. **(Written)** What is the difference between SQL Injection and Parameterized Queries?  
   - **Answer:**  
     - SQL Injection: A security vulnerability where malicious input is injected into a query.  
     - Parameterized Queries: Prevent SQL Injection by safely binding variables to queries instead of concatenating strings.  

10. **(Written)** Write a SQL query to get the top 5 highest salaries from an `Employees` table.  
   - **Answer:**  
   ```sql
   SELECT TOP 5 Salary
   FROM Employees
   ORDER BY Salary DESC;


