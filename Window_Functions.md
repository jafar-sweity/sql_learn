# SQL Course - Part 6: Window Functions

## Window Function

- Perform calculations on an already generated result set (a WINDOW).
- Can be used to perform aggregate calculations.

## What is a Window Function

- OVER(): This clause tells SQL to 'pass this aggregate value over this existing result set'.
- RANK() -> OVER().

## Key Differences

- Processed after every part of the query except ORDER BY.
- Not available in SQLite.

## Window Partitions

- OVER and PARTITION BY.
- Sliding window keywords.
- ROWS BETWEEN <start> AND <finish>.

## Window Function

- Perform an operation across a set of rows related to the current row.
- Similar to GROUP BY aggregate functions, but all rows remain in the output.

## Common Window Functions

- ROW_NUMBER() OVER()
- ORDER BY subclauses to OVER()
- Ordering in and outside OVER()
- LAG(column, n) OVER(...), LEAD(column, n) OVER(...)
- Fetching values from preceding or following rows.
- Assigning ordinal ranks.
- Running totals, moving averages.

## Paging: Splitting data into approximately equal chunks.

- NTILE(n): Splits the data into n approximately equal pages.

## Aggregate Window Functions and Frames

## Frames

- RANGE BETWEEN UNBOUNDED PRECEDING AND UNBOUNDED FOLLOWING.

## How to Define a Frame

- ROWS BETWEEN: ROWS BETWEEN [START] AND [FINISH].
- START AND FINISH can be one of 3 clauses: PRECEDING, CURRENT ROW, FOLLOWING.
