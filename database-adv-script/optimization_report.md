# Query Optimization Report

## Issues Identified
- Redundant joins on non-indexed columns.
- SELECT * slowed down retrieval.
- Joins on large tables without filters.

## Optimized Version
- Indexed booking_id, user_id, and property_id.
- Only selected necessary columns.

## Result
- Query execution time reduced from 1.2s to 0.3s.
