# Knowledge Check: Operators

The chinook database deployed on the Coursera platform contains a table called `"invoices"`. The table itself contains a column called "Total" that shows the total amount to be paid by each customer. The `"Total"` data column and its values is as follows:
```
+-------+
| Total |
+-------+
|  1.98 |
|  3.96 |
|  5.94 |
|  8.91 |
| 13.86 |
|  0.99 |
|  1.98 |
|  1.98 |
|  3.96 |
|  5.94 |
|  8.91 |
| 13.86 |
|  0.99 |
|  1.98 |
|  1.98 |
|  3.96 |
|  5.94 |
|  8.91 |
| 13.86 |
|  0.99 |
|  1.98 |
|  1.98 |
|  3.96 |
|  5.94 |
|  8.91 |
+-------+
```

__Note:__ All questions in this quiz require you to query the `Total` column from the `invoices` table with the use of a SQL `SELECT` statement and a suitable operator. An example of such a statement is as follows:
```sql
select total % 0.75 from invoices;
```

1. Add a `0.25` cent service fee to each value in the `Total` column. Complete the task using a SQL `SELECT` statement that includes a suitable operator. The output of your statement should be as follows:
    ```
    +-------+
    |  2.23 |
    |  4.21 |
    |  6.19 |
    |  9.16 |
    | 14.11 |
    |  1.24 |
    |  2.23 |
    |  2.23 |
    |  4.21 |
    |  6.19 |
    |  9.16 |
    | 14.11 |
    |  1.24 |
    |  2.23 |
    |  2.23 |
    |  4.21 |
    |  6.19 |
    |  9.16 |
    | 14.11 |
    |  1.24 |
    |  2.23 |
    |  2.23 |
    |  4.21 |
    |  6.19 |
    |  9.16 |
    +-------+
    ```

   Answer:
    ```sql
    SELECT total + 0.25 FROM invoices;
    ```

2. Apply a discount to your customers' totals by deducting 0.15 cent from each value in the `Total` column. Complete the task using a SQL `SELECT` statement that includes a suitable operator. The output of your statement should be as follows:
    ```
    +-------+
    |  1.83 |
    |  3.81 |
    |  5.79 |
    |  8.76 |
    | 13.71 |
    |  0.84 |
    |  1.83 |
    |  1.83 |
    |  3.81 |
    |  5.79 |
    |  8.76 |
    | 13.71 |
    |  0.84 |
    |  1.83 |
    |  1.83 |
    |  3.81 |
    |  5.79 |
    |  8.76 |
    | 13.71 |
    |  0.84 |
    |  1.83 |
    |  1.83 |
    |  3.81 |
    |  5.79 |
    |  8.76 |
    +-------+
    ```

   Answer:
    ```sql
    SELECT total - 0.15 FROM invoices;
    ```

3. Double the value of each record in the `Total` column. Complete the task using a SQL `SELECT` statement that includes a suitable operator. The output of your statement should be as follows:
    ```
    +-------+
    |  3.96 |
    |  7.92 |
    | 11.88 |
    | 17.82 |
    | 27.72 |
    |  1.98 |
    |  3.96 |
    |  3.96 |
    |  7.92 |
    | 11.88 |
    | 17.82 |
    | 27.72 |
    |  1.98 |
    |  3.96 |
    |  3.96 |
    |  7.92 |
    | 11.88 |
    | 17.82 |
    | 27.72 |
    |  1.98 |
    |  3.96 |
    |  3.96 |
    |  7.92 |
    | 11.88 |
    | 17.82 |
    +-------+
    ```

   Answer:
    ```sql
    SELECT total * 2 FROM invoices;
    ```

4. Deduct 50% from each value in the `Total` column. Complete the task using a SQL `SELECT` statement that includes a suitable operator. The output of your statement should be as follows:
    ```
    +-------+
    |  0.99 |
    |  1.98 |
    |  2.97 |
    | 4.455 |
    |  6.93 |
    | 0.495 |
    |  0.99 |
    |  0.99 |
    |  1.98 |
    |  2.97 |
    | 4.455 |
    |  6.93 |
    | 0.495 |
    |  0.99 |
    |  0.99 |
    |  1.98 |
    |  2.97 |
    | 4.455 |
    |  6.93 |
    | 0.495 |
    |  0.99 |
    |  0.99 |
    |  1.98 |
    |  2.97 |
    | 4.455 |
    +-------+
    ```

   Answer:
    ```sql
    SELECT total / 2 FROM invoices;
    ```

5. Divide each value in the `Total` column by 2. Complete the task using a SQL `SELECT` statement that includes a suitable operator (Hint: Try using the modulus sign `%`).
   Answer:
    ```sql
    SELECT total % 2 FROM invoices;
    ```