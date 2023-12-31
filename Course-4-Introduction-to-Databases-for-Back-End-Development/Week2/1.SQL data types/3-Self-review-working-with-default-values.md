# Self review: Working with default values

1. A soccer club in London wants to create a table within their database to hold data on each player. Since most of the players are from London, the club can set `“London”` as the default value in the `“City”` column. Can you identify the correct SQL syntax to set London as the default value for this column?
    -   ```sql
        City DEFAULT VARCHAR(30) "London"
        ```
    -   ```sql
        City VARCHAR(30) DEFAULT "London"
        ```
    ```
    Answer: City VARCHAR(30) DEFAULT "London"
    Explanation: The DEFAULT keyword should always be used before the default value.
    ```

2. The skill level of all new players within a soccer club must automatically be set at Level 1. Can you identify the correct SQL syntax to set each new player’s skill level using the DEFAULT keyword?
    -   ```sql
        level INT DEFAULT 1;
        ```
    -   ```sql
        DEFAULT level INT 1;
        ```
    ```
    Answer: level INT DEFAULT 1;
    Explanation: This is the right SQL syntax to set the players DEFAULT level to 1.
    ```

3. The following SQL statement creates a table in a soccer club database called `"Players"`. It also adds two default values to the table: club with a default value of `"Newport FC"`, and city with default value of `"Newport"`.
    ```sql
    CREATE TABLE Players (playerName VARCHAR(50), club VARCHAR (10) DEFAULT "Newport FC", city VARCHAR (100) DEFAULT "Newport");
    ```
    - False
    - True
    ```
    Answer: True
    Explanation: This is the right SQL syntax to create the players table with the DEFAULT values for the club and the city.
    ```

4. Database default constraints are used to limit the value of data that can be stored in a table.
    - False
    - True
    ```
    Answer: True
    Explanation: This ensures the accuracy and reliability of data that’s held in the table.
    ```

5. You are creating a new members table in the sports club database. The table must have two columns with the following default values: city `'London'` and gender `'female'`. How many instances of the DEFAULT keyword does your SQL statement require?
    - Two DEFAULT keywords.
    - One DEFAULT keyword.
    ```
    Answer: Two DEFAULT keywords.
    Explanation: Your statement requries two DEFAULT keywords. One DEFAULT keyword should be declared for the city value, and another for the gender value.
    ```