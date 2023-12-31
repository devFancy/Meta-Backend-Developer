# Knowledge check: Database schema

1. The term database schema refers to the organization of data as a blueprint of how data should be organized and related.

   - True
   - False

   ```
   Answer: True
   Explanation: In general, the term database schema refers to the blueprint that illustrates the organization, grouping and relationship of information in the database.
   ```

2. Identify the essential parts of a database schema. Select all that apply.

   - Tables
   - Composite key
   - Foreign key
   - Relationships between tables

   ```
   Answer: Tables, Foreign key, Relationships between tables
   Explanation: Tables are the main components of the database schema.
                Correct! Attributes define the information required in each table.
                Relationships between tables show how data are related in the database.
   ```

3. A key advantage of a database conceptual schema is that it provides a clear view of how data is stored in database, which makes it easier to build and secure.

   - True
   - False

   ```
   Answer: True
   Explanation: This is a major advantage of creating a database conceptual schema.
   ```

4. The foreign key is used to connect tables in a database schema.

   - True
   - False

   ```
   Answer: False
   Explanation: The foreign key is used to connect tables in a database schema.
   ```

5. A bookstore schema including two tables: customers and orders, which are implemented as follows:

   ```sql
   CREATE TABLE Customers( CustomerID int NOT NULL, Name VARCHAR(50), PRIMARY KEY (CustomerID));

   CREATE TABLE Orders ( OrderID int NOT NULL, CustomerID int, PRIMARY KEY (OrderID), FOREIGN KEY (CustomerID) REFERENCES customers(CustomersID));
   ```

   The two tables are connected through the `OrderID` attribute, because no order can be placed without a customer placing an order.

   - True
   - False

   ```
   Answer: False
   Explanation: The CustomerID is defined as a foreign key in this schema.
   ```
