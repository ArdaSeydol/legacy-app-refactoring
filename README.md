# LINQ Practice Tests

This project contains 20 LINQ query exercises with unit tests based on sample data (`Emp`, `Dept`, `Salgrade`).  
It is designed to improve proficiency with LINQ through practical and testable examples.

## Tests Included
- Filtering, projection, joins
- Aggregation (MIN, MAX, AVG)
- Subqueries, groupings
- Self-joins and nested queries

## Sample Schema Overview
The LINQ queries are based on a classic HR-style schema:
- `Emp`: Employee table with fields like `ename`, `sal`, `mgr`
- `Dept`: Department info
- `Salgrade`: Salary grade classifications

## Tech Stack
- C#
- LINQ
- xUnit (for unit testing)

## How to Run
Make sure xUnit is installed and run tests via Test Explorer in Visual Studio  
or using the CLI:

```bash
dotnet test
