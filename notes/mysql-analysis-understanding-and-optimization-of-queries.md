# MySQL: Analysis, understanding and optimization of queries
> Michael Moussa

## Requirements
* [MySQL 5.7][1]
* [Sakila Sample Database][2]

# Notes
* Composite indexes prevent result ordering as an extra step.
* Remove extra indexes which come up in the `possible_keys` column in an `EXPLAIN` query. It is preferred to keep a single composite index.
* Use `SHOW WARNINGS` to display warnings from recent queries.

[1]: https://dev.mysql.com/doc/relnotes/mysql/5.7/en/
[2]: https://dev.mysql.com/doc/sakila/en/
