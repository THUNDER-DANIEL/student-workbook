# Day 4 - CONNECTING TO A MYSQL DATABASE

Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

In a SQL table, what is the difference between information in a row and information in a column?

        Rows house user set up varibles and values(Name, Address,Phone Numeber).
        Columns hold DB data-information example : id numbers

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

        CREATE TABLE characters ( id INT NOT NULL AUTO_INCREMENT, name VARCHAR(255) NOT NULL, age VARCHAR(255) NOT NULL, description VARCHAR(255) NOT NULL, PRIMARY KEY (id) )

What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;

        *DELETE FROM is used to target s specific row/colum from a table

        *DROP TABLE will delete the whole table as well as it's rows/col and the information forever.

https://github.com/ThurberDaniel/AllSpice
