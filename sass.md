# SASS guidelines

## Formatting

* Never ever use tabs to indent, always 2 spaces
* Indent continued lines 2 spaces
* One selector per line
* Use one space between property and value (`color: #000000`)
* Leave a blank line between rule sets
* Keep selectors as short and descriptive as possible
* Namespace common class name (`button-danger` over `danger`)
* Break into as many small files as makes sense

## Code

* Use `sass` style (no braces or semicolons)
* List `@extends` first
* List `@include` last before nested selectors
* List nested selectors last
* Don't nest more than 3 levels deep
* Don't nest more than 50 lines
* Never commit `.css` files
* Name media queries
* Import shame file last if necessary
