php
===

php settings

Скачиваем: http://pear.php.net/manual/en/installation.getting.php

```
php go-pear.phar
```

```
pear channel-discover pear.phpunit.de
pear channel-discover pear.symfony-project.com
pear update-channels
pear install --alldeps phpunit/PHPUnit
```