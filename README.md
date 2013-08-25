Quota
=====

Quota plugin for Framanews (Tiny Tiny RSS)
https://github.com/framasoft/framanews_quota.git

Licensed under GNU GPL version 2

Copyright (c) 2013 Luc Didry

## Requirements

* tt-rss v1.9 or be working from trunk at:
https://github.com/gothfox/Tiny-Tiny-RSS

##Install:
Go to your ttrss dir and:
```shell
cd plugins
git clone https://github.com/framasoft/framanews_quota.git
```

Enable plugin in config.php and put:

```php
define('FEED_QUOTA', 100);
```

in your config.php;
