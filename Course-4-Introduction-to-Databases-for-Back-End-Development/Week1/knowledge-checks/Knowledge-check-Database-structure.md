# Knowledge check: Database structure

1. What term is used to describe the complete information about one specific staff member in a college database that contains data about staff?
    - Record
    - Table
    - Column
    ```
    Answer: Record
    Explanation: Each row of the table will have a record of information that refers to a specific staff.
    ```

2. What is the minimum number of tables that must be present in a relational database?
    - One table
    - Two tables
    - Three tables
    ```
    Answer: One table
    Explanation: A relational database must include at least one table. Otherwise, there will be no place to store data.
    ```

3. What is the name of the attribute that is chosen in the database to uniquely identify each record in a table?
    - Secondary Key
    - Foreign Key
    - Primary Key
    ```
    Answer: Primary Key
    Explanation: The primary key includes unique values in each row and is used to identify each record of a table.
    ```

4. Which attribute could be used as a primary key in the following customer table?
   | Customer first name | Customer last  name | Customer email address  |
   |---------------------|---------------------|-------------------------|
   | Carl                | Anderson            | carl.anderson@email.com |
   | Mark                | Jacky               | mark.jacky@email.com    |

    - Customer first name
    - Customer last name
    - Customer email address
    ```
    Answer: Customer email address
    Explanation: This is the only attribute in the customer table that can be used as primary key because each customer has a unique email address.
    ```

5. Which of the following keys can you select as the primary key in a relational database? Select all that apply.
    - Candidate Key
    - Foreign Key
    - Alternate key
    - Composite Key
    ```
    Answer: Candidate Key, Alternate key, Composite Key
    Explanation: A candidate key has unique values in each row of the table.
                 Alternate key has unique values in each row of the table, which makes it suitable to be chosen as a primary key.
                 The Composite key is composed of multiple columns to form a unique value in each row of the table, which makes it suitable to be chosen as a primary key.
    ```