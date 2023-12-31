# Bootstrap all templates meta-template
Bastille template to bootstrap all of our jail templates.

* https://github.com/jail-templates/basics
* https://github.com/jail-templates/vnstat
* https://github.com/jail-templates/apache-http
* https://github.com/jail-templates/apache-https
* https://github.com/jail-templates/php
* https://github.com/jail-templates/php-8.0
* https://github.com/jail-templates/php-8.1
* https://github.com/jail-templates/php-8.2
* https://github.com/jail-templates/php-8.3
* https://github.com/jail-templates/mariadb
* https://github.com/jail-templates/mariadb-10.5
* https://github.com/jail-templates/mariadb-10.6
* https://github.com/jail-templates/mariadb-10.11
* https://github.com/jail-templates/famp-http
* https://github.com/jail-templates/famp-https
* https://github.com/jail-templates/wordpress

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/all
```

## Apply template
```
bastille template $JAIL jail-templates/all
```

## Support
Templates will be maintained until their respective software version is end-of-life. Repositories will then be archived and removed from any meta-templates.

If you have a question, suggestion or find a bug, please let us know via an Issues in the relevant repository or send us an email.

## License
All templates are distributed under the 3-Clause BSD License. See `LICENSE` in every template repository for more information.