# Extensiones Visual Studio Code

## General

* GitLens
* Local History
```json
"files.exclude": {
    "**/.history": true
},
"files.watcherExclude": {
    "**/.history/*/**": true
},
"search.exclude": {
    "**/.history": true
}
```
* IntelliJ IDEA Keybindings

## PHP

>Necesitamos tener instalado en entorno local:

* PHP 7.3
* Composer

### Extensiones PHP

* phpcs
  * https://github.com/squizlabs/PHP_CodeSniffer
  ```json
      "phpcs.executablePath": "~/.composer/vendor/bin/phpcs",
      "phpcs.standard": "PSR2",
  ```
* php cs fixer
  * https://github.com/FriendsOfPHP/PHP-CS-Fixer
  ```json
      "php-cs-fixer.executablePath": "~/.composer/vendor/bin/php-cs-fixer",
      "php-cs-fixer.rules": "@PSR2"
  ```
* PHP Intelephense
* PHP Namespace Resolver
* PHP DocBlocker
* PHP Getters & Setters
* PHP Debug

### Extensiones Laravel

* Laravel Blade Snippets
* Laravel goto view
* laravel-goto-controller
