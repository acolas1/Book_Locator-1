Book Locator
=======

CIS4301 DB Project


<b>Make sure the following appears in all of you php files in order to connect to the database:</b>

```php
#!/usr/local/bin/php
<?php require ('../connect.php'); ?>

<?php
...

Some PHP...

...
?>

<?php oci_close($connection); ?>
```
