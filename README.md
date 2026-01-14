# Exercise: SQL CASE Statements

**This repo now includes practice with SQL CASE WHEN statements** — building on aggregate functions from Exercise 2.

## What is CASE?
The CASE statement lets you add if/then/else logic in SQL queries.  
There are two main forms:

1. **Simple CASE** (compares one value to many possibilities)
```sql
CASE column_name
    WHEN value1 THEN 'Result 1'
    WHEN value2 THEN 'Result 2'
    ELSE 'Other'
END
