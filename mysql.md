# MySQL guidelines

* Use `id` for primary keys, not `user_id` or `primary`
* Avoid tables with more than 20 columns
* Index frequently queries columns if it boosts performance
* Don't introduce indexes without really thinking about them
* Use `snake_case` for table and column names
* Name date columns `_at` and time columns `_on`
* Name relation columns after their relation in singular (e.g. `user` in `albums` table: `user_id`)
* Avoid more than one `left join` in a single query
* Always place primary column first
* Always place relation columns next
* Always place "normal" columns next
* Always place boolean columns next
* Always place date and time columns last:

```
  Table: albums
  id, user_id, title, description, public, created_at, updated_at
```
