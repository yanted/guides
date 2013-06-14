# PHP guidelines

## Formatting

* Never ever use tabs to indent, always 4 spaces
* Indent continued lines 4 spaces
* Use spaces around colon in conditions and loops
* Throughout PHP 5
* Zend coding style, strict

## Code

* Avoid methods with more than 10 lines
* Avoid classes with more than 100 lines
* Avoid methods with more than 4 parameters
* Prefer single quotes for strings
* No short tags
* Use `CamelCase` for classes, `smallCamelCase` for variables and methods,
  `SCREAMING_SNAKE_CASE` for constants
* Avoid unnecessary `return` and `else` statements
* Prefer `array_key_exists` over `isset`
* Prefer `require_once` over `include_once`
* Prefer `implode` over concatenating strings
* Prefer colon syntax for conditions and loops within `phtml` templates:

```php
<ul>
  <?php foreach ($items as $item) : ?>
     <li><?php echo $item->getName(); ?></li>
  <?php endforeach; ?>
</ul>
```

* Use constants when possible
* Avoid unnecessary doc blocks without useful content
* Use exceptions for error handling
* Use type hinting and defaults in method definitions
* Avoid passing by reference
