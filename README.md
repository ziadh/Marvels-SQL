# Marvel Characters Database

This repository contains SQL code for creating a database table called "marvels" and performing various queries on the data. The "marvels" table stores information about different Marvel characters such as their name, popularity, alignment, gender, height, weight, hometown, and various attributes related to their abilities.

## Table Structure

The "marvels" table has the following columns:

- ID: An integer representing the unique identifier for each character.
- name: Text field storing the name of the character.
- popularity: An integer indicating the popularity rating of the character.
- alignment: Text field indicating the alignment (good, bad, or neutral) of the character.
- gender: Text field representing the gender of the character.
- height_m: Numeric field representing the height of the character in meters.
- weight_kg: Numeric field representing the weight of the character in kilograms.
- hometown: Text field indicating the hometown or place of origin of the character.
- intelligence: Integer field representing the intelligence level of the character.
- strength: Integer field representing the strength level of the character.
- speed: Integer field representing the speed level of the character.
- durability: Integer field representing the durability level of the character.
- energy_Projection: Integer field representing the energy projection level of the character.
- fighting_Skills: Integer field representing the fighting skills level of the character.

## Skills Demonstrated

The SQL code in this repository demonstrates the following skills:

- Creating a database table using the `CREATE TABLE` statement.
- Inserting data into the table using the `INSERT INTO` statement.
- Retrieving all records from the table using the `SELECT * FROM` statement.
- Performing aggregations to find the average height of the Marvel characters using the `AVG` function and `GROUP BY` clause.
- Filtering records based on a condition using the `WHERE` clause.
- Sorting records based on a specific column using the `ORDER BY` clause.
- Adding a new column to the table using the `ALTER TABLE` statement.
- Using the `CASE` statement to assign values to a new column based on certain conditions.
- Grouping records based on a specific column using the `GROUP BY` clause.

## Queries

The SQL code in this repository includes the following queries:

1. Find the average height for all Marvel characters.
2. Find the name and popularity of Marvel characters where their popularity is greater than 10.
3. Add a new column for Marvel characters categorizing them as "smart" or "dumb" based on their intelligence level.

Please refer to the SQL code for more details on how these queries are executed.
