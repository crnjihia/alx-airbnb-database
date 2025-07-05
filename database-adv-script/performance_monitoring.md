# Performance Monitoring

## Tools Used
- EXPLAIN ANALYZE
- SHOW PROFILE

## Example
EXPLAIN ANALYZE SELECT * FROM bookings WHERE user_id = 123;

## Suggestions
- Add indexes on foreign key columns.
- Consider vertical partitioning on payments table.

## Adjustments
- Added indexes and partitioning on bookings.
- Removed redundant columns from queries.
