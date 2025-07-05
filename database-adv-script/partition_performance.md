# Partitioning Performance Report

## Before Partitioning
- Query: SELECT * FROM bookings WHERE start_date BETWEEN '2020-01-01' AND '2020-12-31'
- Time: 900ms

## After Partitioning
- Same query returned in 210ms

### Conclusion
Partitioning dramatically improved query performance on date filters.
