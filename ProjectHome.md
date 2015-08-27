This stem extension for PHP provides stemming capability for a variety of languages using Dr. M.F. Porter's Snowball API.

It has a much simpler API than the stem extension found in pecl.

### Example ###
```
<?php
  echo stemword('cats', 'english', 'UTF_8');  # cat
  echo stemword('stemming', 'english', 'UTF_8');  # stem
?>
```

### Installation ###
[See here](http://code.google.com/p/php-stemmer/wiki/Installation)