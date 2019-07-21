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
* PHP Intelephense
* PHP Namespace Resolver
* PHP DocBlocker
* PHP Debug
```
/etc/php/7.3/cli/conf.d/20-xdebug.ini
```
```bash
xdebug.remote_enable = 1
xdebug.remote_autostart = 1
```
* PHPUnit Test Explorer

### Extensiones Laravel

* Laravel Blade Snippets
* Laravel goto view
* laravel-goto-controller
