# Meta package for all templates
Bastille template to bootstrap all jail templates in these repositories.

* basics
* vnstat
* apache-http
* apache-https
* php (latest)
* php 8.0
* php 8.1
* php 8.2
* php 8.3
* mariadb (latest)
* mariadb-10.5
* mariadb-10.6
* mariadb-10.11
* famp-http (apache-http, php, mariadb)
* famp-https (apache-https, php, mariadb)

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/famp
```

## Apply template
```
bastille template $JAIL jail-templates/famp
```
