# Backend Circle Assessment

Welcome to the **Backend Circle** Assessment!  
This document contains the **questions and model answers** for Backend track, divided by **difficulty level**:

- **Beginner** → Basic C# and SQL.  
- **Intermediate** → OOP, Joins, Exception handling.  
- **Advanced** → APIs, Security, REST, Design Patterns.  

Each level has **10 questions** (mix of MCQ + Written).  

---

## 🔹 Level 1 – Beginner (Basic C# + Simple Database)

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

3. **(MCQ)** Default access modifier for class members in C#?  
   - a) public  
   - b) private  
   - c) internal  
   - **Answer:** b)  

4. **(Written)** What is the difference between a Class and an Object in C#?  
   - **Answer:** A class is a blueprint; an object is an instance of that class.  

5. **(MCQ)** Which SQL command is used to insert new data into a table?  
   - a) INSERT  
   - b) ADD  
   - c) APPEND  
   - **Answer:** a)  

6. **(Written)** Write a SQL query to select all rows from a table named `Students`.  
   - **Answer:**  
   ```sql
   SELECT * FROM Students;

7. **(MCQ)** How many Primary Keys can a table have?
   - a) 1
   - b) 2
   - c) Unlimited
   - **Answer:** a)

8. **(Written)** What is the difference between DELETE and TRUNCATE?
   - **Answer:** DELETE removes rows (can use WHERE), TRUNCATE removes all rows and resets identity.

9. **(MCQ)** Which data type is a value type in C#?
   - a) string
   - b) int
   - c) object
   - **Answer:** b)

10. **(Written)** Explain the role of a Database in a backend system.
    - **Answer:** Stores and organizes data, allows retrieval and modification efficiently.

## 🔹 Level 2 – Intermediate (OOP + SQL Joins + Exceptions)

1. **(Written)**) Explain Encapsulation in Object-Oriented Programming.
   - **Answer:** Hiding internal details of a class and exposing only necessary parts.

2. **(MCQ)** Which keyword is used to handle exceptions in C#?
   - a) try/catch
   - b) throw/catch
   - c) error/handle
   - **Answer:** a)

3. **(Written)** What is the difference between an Interface and an Abstract Class in C#?
   - **Answer:** Interface = contract with no implementation, Abstract Class = can have both abstract and concrete methods.

4. **(MCQ)** Which of the following supports multiple inheritance in C#?
   - a) Classes
   - b) Abstract classes
   - c) Interfaces
   - **Answer:** c)

5. **(Written)** Write a SQL query to get all customers with their orders from Customers and Orders.
   - **Answer:**
   ```sql
   SELECT Customers.Name, Orders.OrderId
   FROM Customers
   INNER JOIN Orders ON Customers.CustomerId = Orders.CustomerId;

6. **(MCQ)** Which SQL keyword is used to combine rows from two or more tables based on a related column?
   - a) JOIN
   - b) MERGE
   - c) UNION
   - **Answer:** a)

7. **(Written)** What is Normalization in databases?
   - **Answer:** Organizing data to reduce redundancy and improve consistency.

8. **(MCQ)** In C#, which keyword is used to inherit from a class?
   - a) implements
   - b) extends
   - c) : (colon)
   - **Answer:** c)

9. **(Written)** Explain the difference between Value Types and Reference Types.
   - **Answer:** Value types store data directly, reference types store memory references.

10. **(MCQ)** What does the using statement in C# do?
   - a) Imports libraries only
   - b) Ensures resources are disposed after use
   - c) Declares a variable
   - **Answer:** b)


