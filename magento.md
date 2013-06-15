# Magento guidelines

* Never ever introduce core hacks
* Never ever introduce include hacks
* Always overwrite as less of a class/method as possible
* Always try to use `parent` instead of copy/pasting a whole method
* Always document why a method was overwritten, e.g.:

```php
/**
 * Overwritten in order to add a "gross_price" column to the export"
 */
public function doExport($products)
{
   // code...
}
```

* Never comment out child blocks (e.g. `<?php // echo $this->getChildHtml('x'); ?>`)
* Always think about your extension's API first, then start to implement it
* Never use the database for layout changes
* Always use [EcomDev_PHPUnit](http://github.com/IvanChepurnyi/EcomDev_PHPUnit) for testing
* Always use [modman](http://github.com/colinmollenhour/modman) for standalone extensions
* Always develop under different versions for different developers for standalone extensions
* Keep templates small
* Keep extensions small
  ([single responsibility principle](http://en.wikipedia.org/wiki/Single_responsibility_principle))
* Keep controllers small, use helpers, blocks and models for logic
* Never copy doc blocks when overwriting files
* Add a folder under `lib` if necessary, don't clutter the extension
* Don't care about the big names in the scene, they usually have the worst code
