# php-tips

## vscode

## plugins

### php cs
https://marketplace.visualstudio.com/items?itemName=ikappas.phpcs

Install globally:
```
composer global require squizlabs/php_codesniffer
```

or by project

```
composer require --working-dir=tools/php_codesniffer  --dev squizlabs/php_codesniffer

``` 

### php cs fixer
https://marketplace.visualstudio.com/items?itemName=junstyle.php-cs-fixer

In each project install by composer:
```
mkdir --parents tools/php-cs-fixer
composer require --working-dir=tools/php-cs-fixer friendsofphp/php-cs-fixer
```
