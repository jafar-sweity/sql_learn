# SQL Course - Part 8: Final Chapter - Functions for Manipulating Data in PostgreSQL

## Common Data Types

- Text Data Type: CHAR, VARCHAR, TEXT.
- Numeric Data Types: INT, DECIMAL.
- Date/Time Data Types: DATE, TIME, TIMESTAMP, INTERVAL.
- Arrays.

## Some Info on Creating Tables and Inserting Data

- Create Table Example.
- Insert Example.

## Working with Date/Time Functions and Operators

- Overview of basic arithmetic operators.
- Adding and subtracting date/time data types.
- Calculating time periods with AGE.
- Retrieving the current timestamp: SELECT NOW(), CURRENT_TIMESTAMP(...).
- CAST() function.

## Extracting and Transforming Date/Time Data

- EXTRACT(field FROM source), DATE_PART('field', source), DATE_TRUNC().

## Reformatting String and Character Data

- String Concatenation Operator.
- CONCAT().
- Changing the case of strings: UPPER(...), LOWER(), INITCAP(...), REPLACE(column, 'to change', 'new change'), REVERSE(...).

## Parsing String and Character Data

- CHAR_LENGTH(), LENGTH().
- Finding the position of a character in a string: POSITION('...' IN ...).
- Parsing string data: LEFT(...), RIGHT(...).
- Extracting a substring of character data: SUBSTRING().

## Truncating and Padding String Data

- Removing white space from strings: TRIM([leading | trailing, both] [characters] FROM string).
- Padding strings with character data: LPAD(string, count, 'char'), RPAD(...).
