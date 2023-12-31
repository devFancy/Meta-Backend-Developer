# Self-review: Record deletion

1. The correct command to remove a record from a table is:
    ```sql
    DROP FROM
    ```
    - False
    - True
    ```
    Answer: False
    Explanation: The DROP command is used to drop an existing database or a table in a database. The right command is DELETE FROM
    ```

2. You can delete all records of data from a table without deleting the table itself using the SQL command
    ```sql
    DELETE FROM
    ```
    - False
    - True
    ```
    Answer: True
    Explanation: This SQL statement deletes all records of data from a table, without deleting the table.
    ```

3. You can delete the record of the player assigned the number seven from the table `“Players”` using the following SQL syntax:
    ```sql
    DELETE FROM players WHERE playerNumber = seven;
    ```
    - False
    - True
    ```
    Answer: False
    Explanation: The correct syntax to delete the record of data where the player number is 7 is: DELETE FROM players WHERE playerNumber = 7;
    ```

4. You can delete all records from a table called `“Players”` where the value of City is equal to `“London”` using the following SQL syntax:
    ```sql
    DELETE FROM players WHERE city = “London”
    ```
    - False
    - True
    ```
    Answer: True
    Explanation: This is the right SQL statement to delete all the records from the player’s table where the city = 'London'.
    ```