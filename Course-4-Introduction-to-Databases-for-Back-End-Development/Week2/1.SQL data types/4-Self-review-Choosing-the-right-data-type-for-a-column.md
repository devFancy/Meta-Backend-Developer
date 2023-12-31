# Self review: Choosing the right data type for a column

1. A soccer club’s database includes a `“Players”` table. The table contains a `“Player number”` column that records the jersey number of each player in the team. Each jersey number is a whole number. Identify the correct data type for this column.
    - TINYINT
    - DECIMAL
    ```
    Answer: TINYINT
    Explanation: TINYINT is an integer data type that accepts whole numbers only.
    ```

2. In a sports club database, the “Players” table includes a date of birth column that records the date of birth for each player. The right SQL data type to define the player date of birth is DOB VARCHAR(100).
    - True
    - False
    ```
    Answer: False
    Explanation: The Date is the right data type in this case.
    ```

3. Which one of the following SQL statements makes use of the correct data types to create a `"Players"` table in a soccer club’s database?
    -   ```sql
        CREATE TABLE players (playerNumber Decimal, fullName VARCHAR(100), date_of_birth DATE);
        ```
    -   ```sql
        CREATE TABLE players (playerNumber INT, fullName VARCHAR(100), date_of_birth CHAR);
        ```
    -   ```sql
        CREATE TABLE players (playerNumber INT, fullName VARCHAR(100), date_of_birth DATE);
        ```
    ```
    Answer: CREATE TABLE players (playerNumber INT, fullName VARCHAR(100), date_of_birth DATE);
    Explanation: All columns have been defined with suitable data types.
    ```

4. A soccer club’s database includes a staff table with three columns: username, full name and title. The username contains alphanumeric values such as: `“Staff001”` and has a fixed length of eight characters. Select the right SQL syntax.
    -   ```sql
        username CHAR(8)
        ```
    -   ```sql
        username VARCHAR(8)
        ```
    ```
    Answer: username CHAR(8)
    Explanation: Because the username has a fixed length of 7 characters.
    ```

5. The following SQL statement can be used to create a table called `“Players”`, with a default value of `“Miami”` for the city column.
    ```sql
    CREATE TABLE players (playerName VARCHAR(100), city VARCHAR(50) DEFAULT “Miami”, age INT);
    ```
    - True
    - False
    ```
    Answer: True
    Explanation: This SQL statement can be used to create a table called “Players”, with a default value of “Miami” for the city column.
    ```