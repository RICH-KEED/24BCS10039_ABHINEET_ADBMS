(Experiment 3 - Task 2)

Name: ABHINEET

UID: 24BCS10039

## Aim

To count the number of students residing in the city 'Delhi' using an aggregate query.

## Question

Write a query to count the number of records in the `students` table where the `city` is 'Delhi'.

## SQL Queries Used

```sql
Select Count(*) 
from students
where city = 'Delhi';
```

## Output

```text
The query returns a single integer representing the number of students from Delhi, for example:

┌───────┐
│ count │
├───────┤
│  <n>  │
└───────┘

Replace `<n>` with the actual count returned by your database.
```

## Output Screenshot

No screenshot provided.

## Image Explanation

The query counts rows in `students` where `city = 'Delhi'` and returns the total as a single scalar value.

## Result

The SQL query returns the number of students located in Delhi when executed against the `students` table.

