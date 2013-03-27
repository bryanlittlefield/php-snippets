php Snippets
============

Some helpful Php Snippets


#### Truncate Long Titles to the Nearest Whole Word Using PHP strrpos
---------------------------
```php 
<?php echo substr( $string, 0, strpos($string, ' ', 35) ); ?></p>
```
