[![](https://framagit.org/assets/favicon-075eba76312e8421991a0c1f89a89ee81678bcde72319dd3e8047e2a47cd3a42.ico)](https://framagit.org)

![English:](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Flag_of_the_United_Kingdom.svg/20px-Flag_of_the_United_Kingdom.svg.png) **Framasoft uses GitLab** for the development of its free softwares. Our Github repositories are only mirrors.
If you want to work with us, **fork us on [framagit.org](https://framagit.org)**. (no registration needed, you can sign in with your Github account)

![Français :](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Flag_of_France.svg/20px-Flag_of_France.svg.png) **Framasoft utilise GitLab** pour le développement de ses logiciels libres. Nos dépôts Github ne sont que des miroirs.
Si vous souhaitez travailler avec nous, **forkez-nous sur [framagit.org](https://framagit.org)**. (l'inscription n'est pas nécessaire, vous pouvez vous connecter avec votre compte Github)
* * *

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