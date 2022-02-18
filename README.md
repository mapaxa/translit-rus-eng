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
$service = new Mapaxa\TranslitPackage\TranslitService('мама мыла раму');
echo $service->run();
```
