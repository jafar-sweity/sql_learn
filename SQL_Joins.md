# SQL Course - Part 4: SQL Joins

## Essential SQL Joins

- INNER JOIN: Explains INNER JOIN and its usage.

## Defining Relationships

- One-to-Many
- One-to-One
- Many-to-Many

## OUTER JOIN

- Can obtain records from other tables, even if matches are not found.
- Includes LEFT JOIN and FULL JOIN.

## CROSS JOIN

- Creates all possible combinations of two tables.
- No need to specify ON or USING with CROSS JOIN.

## SELF JOIN

- Tables joined with themselves.
- Used to compare parts of the same table.

## Set Theory for SQL Joins

- SQL has three main set operations:
  1. UNION
  2. INTERSECT
  3. EXCEPT

### UNION

- Takes two tables as input and returns all records from both tables.
- If two records are identical, UNION only returns them once.

### INTERSECT

- Takes two tables as input and returns records that exist in both tables.

### EXCEPT

- Identifies records present in one table but not the other.

## Subquerying with Semi-Joins and Anti-Joins

- Semi-join chooses records in the first table where a condition is met in the second table.
- Anti-join chooses records in the first table where col1 does NOT find a match in col2.

## Types of Joins

- INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN, CROSS JOIN.
- Semi-joins, anti-joins, and self-joins.

## Set Operations

- A different way to join data in SQL.

