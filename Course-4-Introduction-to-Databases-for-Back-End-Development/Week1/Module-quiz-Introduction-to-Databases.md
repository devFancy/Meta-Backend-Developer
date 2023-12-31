# Module quiz: Introduction to Databases

1. What is the most used database type in computing?
    - Relational Database
    - Flat File Database
    - NoSQL Database
    ```
    Answer: Relational Database
    Explanation: Relational databases are the most popular type of databases because of their simplicity, robustness and scalability.
    ```

2. Which one of the following is an advantage of storing data in tables?
    - Tables offer the ability to encrypt data.
    - Tables provide a simple and clear view of data
    - Tables let you store large amounts of data.
    ```
    Answer: Tables provide a simple and clear view of data
    Explanation: Tables are a very good technique to organize data as it provides a simple and clear view of data in the database.
    ```

3. In a bookshop database, the complete information about one specific book is referred to as a ______________.
    - Column
    - Table
    - Record
    ```
    Answer: Record
    Explanation: In a bookshop database, a record of data contains all available information about a specific book.
    ```

4. What makes SQL a very popular database language? Select all that apply.
    - SQL works with different relational database management systems.
    - SQL requires very little coding skills to use.
    - SQL is a portable programming language.
    ```
    Answer: SQL works with different relational database management systems.
            SQL requires very little coding skills to use.
            SQL is a portable programming language.
    Explanation: SQL can be used with different relational database management systems.
                 SQL requires less coding skill in comparison with other programming languages.
                 SQL can be used with any laptop or computer that has MySQL installed.
    ```

5. Which SQL command is used to update data in a database table?
    - MODIFY command
    - UPDATE command
    - EDIT command
    ```
    Answer: UPDATE command
    Explanation: The UPDATE command is used to modify or update data contained within a table in the database.
    ```

6. Which of the following database management systems uses the SQL language? Select all that apply.
    - PostgreSQL
    - MySQL
    - Oracle
    ```
    Answer: PostgreSQL, MySQL, Oracle
    Explanation: PostgreSQL database management system uses SQL.
                 MySQL database management system uses SQL.
                 Oracle database management system uses SQL.
    ```

7. What is the importance of a candidate key in a database?
    - A candidate key can be used to encrypt data in a table.
    - A candidate key can be used to uniquely identify rows in a table.
    - A candidate key can be used to drop a table.
    ```
    Answer: A candidate key can be used to uniquely identify rows in a table.
    Explanation: A candidate key is a column that contains unique value in each row of the table, which makes it suitable to be chosen as a primary key.
    ```

8. In the following student table, which attribute could be used as a primary key?
   | Student first name | Student last  name | Mobile number |
   |--------------------|--------------------|---------------|
   | Carl               | Merlo              | 07445532123   |
   | Mark               | Nero               | 07456532327   |
    - Mobile number
    - Student last name
    - Student first name
    ```
    Answer: Mobile number
    Explanation: Since the mobile phone number is unique for each student, then it can be chosen as primary key.
    ```

9. CREATE TABLE student is the right syntax to create a student table in SQL.
    - False
    - True
    ```
    Answer: True
    Explanation: This is the right way to create a student table in SQL.
    ```

10. Choose the right syntax to create a club database in SQL. Select all correct answers.
    -   ```sql
        CREATE DATABASE CLUB
        ```
    -   ```sql
        create club database
        ```
    -   ```sql
        create database club
        ```
    -   ```sql
        CREATE CLUB DATABASE
        ```
    ```
    Answer: CREATE DATABASE CLUB
            create database club
    Explanation: You can use capital letters as SQL is not a case sensitive language.
                 You can use small letters as SQL is not a case sensitive language, however, the convention is to use capital letters for the SQL commands and keywords.
    ```