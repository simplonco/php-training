# PHP
>_[Training](https://github.com/simplonco/training) / PHP_

![PHP](php.png)

## Subsections

* _Training / PHP / **[POO](https://github.com/simplonco/poo-training)**_
* _Training / PHP / **[PDO](https://github.com/simplonco/pdo-training)**_
* _Training / PHP / **[Symfony](https://github.com/simplonco/symfony-training)**_
* _Training / PHP / **[Wordpress](https://github.com/simplonco/wordpress-training)**_

## Training

* [PHP Basics](https://github.com/simplonco/php-training/blob/master/training/Tutoriel-PHP-Introduction.pdf) _Fundamental of PHP_ :elephant:
* [MySQL Basics](https://github.com/simplonco/php-training/blob/master/training/Tutoriel-MySQL-Introduction.pdf) _Fundamental of MySQL_

### TODO

* https://github.com/simplonco/php-training-ajax
* https://github.com/simplonco/php-simplonreunion

## Starters

* [The variables](https://github.com/simplonco/php-exercises-variable) _Starting php with the variables_
* [The circumstances](https://github.com/simplonco/php-exercises-circumstances) _Starting php with the circumstances_
* [The loop](https://github.com/simplonco/php-exercises-loop) _Starting php with the loop_
* [The function](https://github.com/simplonco/php-exercises-function) _Starting php with the function_
* [The array](https://github.com/simplonco/php-exercises-array) _Starting php with the array_
* [The parameters](https://github.com/simplonco/php-exercises-paramUrl) _Starting php with the parameters_
* [The forms](https://github.com/simplonco/php-exercises-form) _Starting php with the forms_
* [The global variable, $session](https://github.com/simplonco/php-exercises-globalVariable) _Starting php with the session and global variable_
* [The date](https://github.com/simplonco/php-exercises-date) _Starting php with the date_

## Exercises

* [Introduction to programming](https://github.com/simplonco/php-introduction) (PHP) :elephant:
* [PHP Recall](https://github.com/simplonco/php-training-base) _Review the basics of PHP_
* [Cooking data with PHP](https://github.com/simplonco/php-cooking-data) _Learn how to play with the dictionary and an example dataset of movies in PHP! :egg:_
* [Send Mail Form](https://github.com/simplonco/php-send-mail-form) _Send mails with a simple HTML form and a PHP backend! :mailbox:_
* [Chocolate cookies](https://github.com/simplonco/chocolate-cookies)
* [Challenges](https://github.com/simplonco/php-challenges) _It will maybe hurt a bit, but for your good! :cactus:_

## Projects

* [MiniChat II - The Return](https://github.com/simplonco/project-minichat-II-the-return/) _RrrRrrRrrRrr RrrRrr Rrr :cat:_
* [Fork](https://github.com/simplonco/fork) _Choose your learning path for the next months.._
* [Galactic Space Combat](https://github.com/simplonco/galactic-space-combat) _Un projet interpromo d'une semaine !_
* [Push to production like a PRO!](https://github.com/simplonco/push-me-to-prod-like-a-pro) _Learn how to put a real app online_

### ATS-SPC _(Montreuil - Promo 5)_

* https://github.com/simplonco/ATS-SPC-A
* https://github.com/simplonco/ATS-SPC-B
* https://github.com/simplonco/ATS-SPC-C
* https://github.com/simplonco/ATS-SPC-D

## Resources

### Official Documentation

* [The PHP Official Manual](http://php.net/manual/en/index.php) :gb:
* [Le Manuel PHP Officiel](http://php.net/manual/fr/index.php) :fr:

### Big Books

* [PHP The Right Way](http://www.phptherightway.com/) :gb:

### Learn X in Y minutes

* [Learn PHP in Y minutes](https://learnxinyminutes.com/docs/php/) :gb:
* [Apprendre PHP en Y minutes](https://learnxinyminutes.com/docs/fr-fr/php/) :fr:

### Digital Ocean Tutorials

* [How to install LAMP](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04) :gb:
* [How to install LLMP](https://www.digitalocean.com/community/tutorials/how-to-install-the-llmp-stack-linux-lighttpd-mysql-and-php-on-ubuntu-12-04) :gb:
* [How To Change Your PHP Settings](https://www.digitalocean.com/community/tutorials/how-to-change-your-php-settings-on-ubuntu-14-04) :gb:
* [How to install PHPMyAdmin](https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-16-04) :gb:

### OpenClassrooms

* [Concevez votre site web avec PHP et MySQL](https://openclassrooms.com/courses/concevez-votre-site-web-avec-php-et-mysql) :fr:
* [Programmez en orienté objet en PHP](https://openclassrooms.com/courses/programmez-en-oriente-objet-en-php) :fr:

### POO

* http://creersonsiteweb.net/page-php-programmation-orientee-objet
* http://www.bestcours.com/525-pdf-php-programmation-objet-telecharger
* http://www.tutorialspoint.com/php/php_object_oriented.htm

### Awesome lists

* [Awesome PHP](https://github.com/ziadoz/awesome-php) :sunglasses:
* [Awesome Composer](https://github.com/jakoch/awesome-composer) :sunglasses:

### IDEs

* [PHPStorm](https://www.jetbrains.com/phpstorm/)
* [Nuclide](https://nuclide.io/)

### Google Docs, GitHub & Miscellanous (Work in Progress)

* https://docs.google.com/a/simplon.co/document/d/1RvkdTdjyl0Z6mY5cU-DV0y39BJNkgUC_Gwcb0KySmiI
* https://docs.google.com/document/d/1wIrS26TAZYIFIJ8o11sj-ZvhgbVgBlTdyN8-41RiZ_0
* https://github.com/simplonco/sql-first-steps
* https://github.com/simplonco/symfony-training
* https://www.grafikart.fr/formations/php
* http://www.lephpfacile.com/cours/
* http://sql.sh/

http://www.fran6art.com/wordpress/creez-votre-theme-wordpress-de-a-a-z/

_To be continued.._

## Code snippets

### PHP Setup :tada:!

```shell
# Install LAMP
sudo apt-get install tasksel
sudo tasksel install lamp-server
# Fix permission issues
sudo adduser $(whoami) www-data
sudo chown -R www-data:www-data /var/www
sudo chmod -R g+rwx /var/www/
# Finally: don't forget to login / logout
```

### Read apache2 logs

```shell
# Switch to root
sudo su
# Go in the apache2 logs folder
cd /var/log/apache2/
# Display all logs
tail -f *.log
```

### What's mean LAMP?

```markdown
# LAMP: Linux Apache MySQL PHP

*apache2: Handle HTTP Request | nginx
*php5: Templating language | python | ruby
*mysql: Local Database (SQL) | postgresql | mongodb | rethinkdb
```

### Where is my PHP?

```php
<!-- HTML CODE -->
<?php
    ...
?>
<!-- HTML CODE -->
```

### URLS, PROTOCOLS & REQUESTS

```markdown
# URLS

http://www.google.com/doodle/page.html

# PROTOCOLS

* http
* ftp
* ssh

# REQUESTS

HTTPS = HTTP + SSL

METHODS:
- GET
- POST

## Google example of GET method
?gferd=cr&ei=eVpRV5r4Ooru8wfn-bqwAQ&gwsrd=ssl#q=test

?...=...&...=...&...=...

https://www.google.fr/?q=cookie
https://www.google.fr/?q=pizza
```

### `index.php`

```php
<?php
if ($_POST['password'] != "cookie") { // => database
    header('Location: form.html');
} else {
?>
<!DOCTYPE>
<html>
    <head>
        <meta charset="utf8" />
        <title>PHP Test</title>
    </head>
    <body>
        <h1>Welcome <?php echo $_POST['name']; ?>!</h1>
    </body>
</html>
<?php
}
?>
```

### `form.html`

```php
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf8"/>
        <title>PHP Form Example</title>
    </head>
    <body>
        <form action="index.php" method="POST">
            <input name="name" type="text" />
            <input name="password" type="password" />
            <input value="login" type="submit" />
        </form>
    </body>
</html>
```
