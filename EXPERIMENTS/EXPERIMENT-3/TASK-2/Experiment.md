(Experiment 3 - Task 2)

Name: ABHINEET

UID: 24BCS10039

## Aim

To count the number of students in each city using an aggregate query.

## Question

Write a query to count the number of students per city from the `students` table.

## SQL Queries Used

```sql
SELECT city,
	   COUNT(*) AS student_count
FROM students
GROUP BY city
ORDER BY city;
```

## Output

```text
┌─────────┬──────────────┐
│ city    │ student_count│
├─────────┼──────────────┤
│ Delhi   │ <n1>         │
│ Mumbai  │ <n2>         │
│ Kolkata │ <n3>         │
│ Chennai │ <n4>         │
└─────────┴──────────────┘

Replace `<n1>`, `<n2>`, ... with the counts returned by your database.
```

## Output Screenshot

No screenshot provided.

## Image Explanation

The query counts rows in `students` where `city = 'Delhi'` and returns the total as a single scalar value.

## Result

The SQL query returns the number of students located in Delhi when executed against the `students` table.

