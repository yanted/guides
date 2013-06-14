# Javascript guidelines

## Formating

* Never ever use tabs to indent, always 2 spaces
* Indent continued lines 2 spaces

## Code

* Avoid semicolons unless necessary
* Prefer multiple `var` statements over leading `,`
* Use trailing commas in arrays and objects
* Use namespaces, don't clutter global namespace unless necessary
* Use `CamelCase` for prototypes, `smallCamelCase` for variables and
  functions, `SCREAMING_SNAKE_CASE` for constants
* Avoid functions with more than 15 lines
* Avoid prototype definitions with more than 200 lines
* Avoid functions with more than 4 parameters
* Avoid functions with more than 3 return values in callback
* Prefer single quotes for strings
* Prefer an asynchronous workflow over a synchronous one
* Avoid more than 3 nested callbacks
* Never pass `setTimeout` a string to call
* Use `return` as early as possible
* Use named closures if it adds value
* Use events freely
