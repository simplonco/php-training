# PHP
>_[Training](https://github.com/simplonco/training) / PHP_

![PHP](php.png)

## Exercises

* [Cooking data with PHP!](https://github.com/simplonco/Cooking-data-with-PHP)
* [Send Mail Form](https://github.com/simplonco/php-send-mail-form)
* [Challenges](https://github.com/simplonco/php-challenges) _(Experimental)_

## Resources

* [PHP The Right Way](http://www.phptherightway.com/) :uk:
* [How to install LAMP](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04) :uk:
* [How to install PHPMyAdmin](https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-16-04) :uk:
* [PHP Official Manual](http://php.net/manual/en/index.php) :uk:
* [Learn PHP in Y minutes](https://learnxinyminutes.com/docs/php/) :uk:
* [Learn PHP in Y minutes](https://learnxinyminutes.com/docs/fr-fr/php/) :fr:

### Google Docs

* https://docs.google.com/a/simplon.co/document/d/1RvkdTdjyl0Z6mY5cU-DV0y39BJNkgUC_Gwcb0KySmiI
* https://docs.google.com/document/d/1wIrS26TAZYIFIJ8o11sj-ZvhgbVgBlTdyN8-41RiZ_0

_To be continued.._

## Code snippets

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

### PHP Setup :tada:!

```markdown
# Install LAMP
sudo apt-get install tasksel
sudo tasksel install lamp-server
# Fix a permission issue
sudo chown -R simplonco:simplonco /var/www/html
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
