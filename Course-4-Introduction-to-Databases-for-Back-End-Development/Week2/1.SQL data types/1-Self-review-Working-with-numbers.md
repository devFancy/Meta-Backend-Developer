# Self review: Working with numbers

1. Identify the correct data type for the Product Price column in the following table.
   | Product ID | Product Price |
   |------------|---------------|
   | P1         | 13.50         |
   | P2         | 22.75         |
    - product_price DECIMAL
    - product_price TINYINT
    - product_price STRING
    - product_price INT
    ```
    Answer: product_price DECIMAL
    Explanation: A decimal should be used as the data type in this column as the price may include a fraction value.
    ```

2. A `“customer id”` column in a customer table is expected to include thousands of customers and the data type should be numeric only. What data type should you use to define this column?
    - customerID DECIMAL
    - customerID INT
    - customerID TINYINT
    ```
    Answer: customerID INT
    Explanation: Integer is a numeric data type that can be used for big whole numbers, which are required here.
    ```

3. The data type for the “Number of students” column in the following table must be defined as an INTEGER data type to ensure that only numeric values are accepted.
   | Course      | Number of students |
   |-------------|--------------------|
   | Computing   | 50                 |
   | Design      | 30                 |
   | Engineering | 40                 |
    - True
    - False
    ```
    Answer: True
    Explanation: You should only have whole numbers in this column.
    ```

4. Which of the following pieces of data are examples of a DECIMAL data type? Select all correct answers.
    - 50.00
    - 550
    - 455
    - 75.50
    ```
    Answer: 50.00, 75.50
    Explanation: 50.00 is a number with a 0.00 fraction.
                 75.50 is a number with a 0.50 fraction.
    ```

5. The integer data type stores both negative and positive numbers.
    - True
    - False
    ```
    Answer: True
    Explanation: An integer is a whole number data type that can have a positive, negative or zero value.
    ```