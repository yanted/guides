# Ruby guidelines

## Formatting

* Never ever use tabs to indent, always 2 spaces
* Indent continued lines 2 spaces
* Indent private methods equal to public methods

## Code

### Plain ruby

* Avoid methods with more than 5 lines
* Avoid classes with more than 100 lines
* Avoid methods with more than 4 parameters
* Avoid explicit return statements
* Don't use `self` explicitly anywhere except class methods (`def self.method`)
  and assignments (`self.attribute =`)
* Prefer `detect` over `find`
* Prefer `inject` over `reduce`
* Prefer `map` over `collect`
* Prefer `select` over `find_all`
* Prefer single quotes for strings
* Use `_ `for unused block parameters
* Use `%{} `for single-line strings needing interpolation and double-quotes
* Use `&&` and `||` for Boolean expressions
* Use `{...}` for single-line blocks. Use do..end for multi-line blocks
* Use `?` suffix for predicate methods
* Use `CamelCase` for classes and modules, `snake_case` for variables and methods,
  `SCREAMING_SNAKE_CASE` for constants
* Use `def self.method`, not `def Class.method` or `class << self`
* Use `def` with parentheses when there are arguments
* Use `each`, not `for`, for iteration
* Use heredocs for multi-line strings

### Rails

* Avoid `member` and `collection` routes
* Avoid passing more than 1 object to the view in a controller action
* Don't use protected controller methods
* Name date columns with `_on` suffixes
* Name datetime columns with `_at` suffixes
* Name initializers for their gem name
* Order ActiveRecord associations alphabetically by attribute name
* Order ActiveRecord validations alphabetically by attribute name
* Order controller contents: filters, public methods, private methods
* Order model contents: constants, macros, public methods, private methods
* Put application-wide partials in the `app/views/application` directory
* Use `def self.method`, not the `scope :method` DSL
* Use the default `render 'partial'` syntax over `render partial: 'partial'`
* Avoid the `:except` option in routes
* Order resourceful routes alphabetically by name
* Use the `:only` option to explicitly state exposed routes
