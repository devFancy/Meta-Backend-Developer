# Knowledge check: Update and Delete

1. Which of the following statements is the correct command syntax to update a table in SQL?
    -   ```sql
        UPDATE Table table_name
        ```
    -   ```sql
        UPDATE table_name
        ```
    -   ```sql
        UPDATE column
        ```
    ```
    Answer: UPDATE table_name
    Explanation: This is the right way to use the UPDATE command.
    ```

2. What is the missing SQL keyword in the following SQL statement to update the customer’s table?
    ```sql
    UPDATE Customers
    ___ ContactName = 'Jack Molly'
    WHERE CustomerID = 10;
    ```
    -   ```sql
        SET
        ```
    -   ```sql
        ANY
        ```
    ```
    Answer: SET
    Explanation: SET is the right keyword in SQL to update the contact name with a new value. 
    ```

3. Which of the following SQL statements can be used to update data for a student in the `“Students”` table?
    -   ```sql
        UPDATE students SET name = 'Karl' AND ID = 18;
        ```
    -   ```sql
        UPDATE students SET name = 'Karl' WHERE ID = 18;
        ```
    -   ```sql
        UPDATE students WHERE ID = 18 SET name = 'Karl';
        ```
    ```
    Answer: UPDATE students SET name = 'Karl' WHERE ID = 18;
    Explanation: This is the right syntax to update the student’s name in the “Students” table.
    ```

4. The following table contains data about customers. The customer data should be removed completely, but without deleting the table. Identify which statement can be used to delete all records of data from the customers table without deleting the table itself.
   | Customer ID | Customer Name |
   |-------------|---------------|
   | C1          | Karl          |
   | C2          | Jack          |
    -   ```sql
        DROP TABLE customers
        ```
    -   ```sql
        DELETE FROM customers;
        ```
    ```
    Answer: DELETE FROM customers;
    Explanation: This SQL statement deletes all rows in the "customers" table, without deleting the table.
    ```

5. The `'WHERE'` keyword is used in SQL to specify a condition to update or delete data from a table.
    - True
    - False
    ```
    Answer: True
    Explanation: WHERE is used to identify those records that fulfil a specified condition.
    ```