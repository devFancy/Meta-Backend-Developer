# Knowledge check: Defining keys

1. Which column can be used as the primary key in the following student table?
   | StudentName | Date Of Birth | Email |
   |-------------|---------------|-------------------|
   | Tim | 19/03/2000 | tim.k@email.com |
   | Mark | 20/05/1999 | mark.f@email.com |
   | Mark | 10/03/2001 | mark.g@email.com |
   | Peter | 19/03/2000 | peter.s@email.com |

   - Email
   - Student name
   - Date of Birth

   ```
   Answer: Email
   Explanation: This column is the right choice because it contains unique values in each row of the table.
   ```

2. What type of primary key is used in the following `Sales` table?
   | Customer ID | Order ID | Product Code | Quantity |
   |-------------|----------|--------------|----------|
   | Cu01 | Or10 | Pro123 | 10 |
   | Cu02 | Or11 | Pro153 | 12 |
   | Cu01 | Or10 | Pro124 | 16 |
   | Cu02 | Or12 | Pro123 | 11 |

   - A primary key represented by the `Customer ID` column.
   - A composite primary key represented by `Customer ID` and `Product Code` columns.

   ```
   Answer: A composite primary key represented by Customer ID and Product Code columns.
   Explanation: There’s no single column that can be used as a primary key. So, the best approach is to use multiple columns as a composite primary key.
   ```

3. You need to create a table for staff members in a college. You must define the email address column as the primary key. Can the following SQL syntax be used to complete this task?

   ```sql
   CREATE TABLE Staff( Email VARCHAR(200) NOT NULL, Name varchar(255) NOT NULL, CONSTRAINT PK_Email PRIMARY KEY (Email));
   ```

   - Yes
   - No

   ```
   Answer: Yes
   Explanation: The constraint has been used in a proper way to define the email address as a primary key.
   ```

4. The following SQL code defines three primary keys: `SalesID`, `CustomerID` and `ProductID`.

   ```sql
   CONSTRAINT SalesID PRIMARY KEY (customerID, proudctID)
   ```

   - True
   - False

   ```
   Answer: False
   Explanation: In this example there is only ONE PRIMARY KEY (SalesID). However, the VALUE of the primary key is made up of TWO COLUMNS (customerID +productID).
   ```

5. Which of the following statements is the correct SQL syntax to define a foreign key that links the orders table with the customers table in the following diagram?

   <img src="./images/img1.png" width=500>

   - ```sql
     CREATE TABLE Orders ( OrderID int NOT NULL, CustomerID int, PRIMARY KEY (OrderID), FOREIGN KEY (CustomerID) REFERENCES Customers(OrderID));
     ```
   - ```sql
     CREATE TABLE Orders ( OrderID int NOT NULL, CustomerID int, PRIMARY KEY (OrderID), FOREIGN KEY (CustomerID) REFERENCES Customers(CustomerID));
     ```

   ```
   Answer: CREATE TABLE Orders ( OrderID int NOT NULL, CustomerID int, PRIMARY KEY (OrderID), FOREIGN KEY (CustomerID) REFERENCES Customers(CustomerID));
   Explanation: In this example the SQL statement creates a FOREIGN KEY on the "customerID" column when the "Orders" table is created.
   ```
