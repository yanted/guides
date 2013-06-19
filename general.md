# General coding guidelines

## Formatting

* Avoid inline comments, use if code can't be simplified to explain itself
* Break long lines after 80 characters, try to keep lines shorter in general
* Delete trailing whitespace
* Don't include spaces after `(`, `[` or before `]`, `)`
* Use spaces around operators, after commas, after colons and semicolons, around
  `{` and before `}`.
* Don't misspell
* Don't vertically align tokens on consecutive lines
* If you break up an argument list, keep the arguments on their own lines and
  closing parenthesis on its own line
* If you break up a hash, keep the elements on their own lines and closing curly
  brace on its own line
* Use an empty line between methods
* Use newlines around multi-line blocks.
* Use Unix-style line endings (`\n`).
* Use uppercase for SQL key words and lowercase for SQL identifiers

## Naming

* Avoid abbreviations
* Never use types in names (like `user_array` or `$arrUser`)
* Name the enumeration parameter the singular of the collection
* Name variables, methods, and classes to reveal intent
* Treat acronyms as words in names (`XmlHttpRequest` not `XMLHTTPRequest`), even
  if the acronym is the entire name (`class Html` not `class HTML`)

## Organization

* Order methods so that caller methods are earlier in the file than the methods they call
* Order methods so that methods are as close as possible to other methods they call

## Code

* Never expose more to the public api than necessary, prefer `private` over
  `protected` over `public`
