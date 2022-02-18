# Transliterator from ru to en

Краткое описание пакета

## Requirements

- php7.4

## Insatallation

```bash
$ composer require mapaxa/translit-rus-eng
```

## Usage

```php
<?php 
$transliterator = new Transliterator();
echo $transliterator->run('someWordInRussian');
```
