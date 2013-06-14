# Coffeescript guidelines

## Formatting

* Never ever use tabs to indent, always 2 spaces
* Indent continued lines 2 spaces

## Code

* Initialize arrays using `[]`
* Initialize empty objects and hashes using `{}`
* Use `CamelCase` for classes, `smallCamelCase` for variables and
  functions, `SCREAMING_SNAKE_CASE` for constants,
  `_single_leading_underscore` for private variables and functions.
* Prefer `is` to `==` or `===`
* Prefer `or` and `and` to `||` and `&&`
* Avoid functions with more than 10 lines
* Avoid prototype definitions with more than 100 lines
* Avoid functions with more than 4 parameters
* Avoid functions with more than 3 return values in callback
* Prefer single quotes for strings
* Prefer an asynchronous workflow over a synchronous one
* Avoid more than 3 nested callbacks
* Avoid explicit `return`
