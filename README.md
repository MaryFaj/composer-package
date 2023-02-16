## Транслитератор строк

Осуществляет транслитерацию букв кириллицы в строке на латиницу.

## Требования

- PHP 7.0

## Установка

```bash
$ composer require mfatjanova/composer-package
```

## Использование

```
<?php
$transliterator = new Transliterator();
echo $transliterator->getTransliterate('строка тест'); // stroka test
```
