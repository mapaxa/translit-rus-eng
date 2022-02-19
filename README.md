# Transliterator from rus to eng



## Requirements

- php7.4

## Insatallation

```bash
$ composer require mapaxa/translit-rus-eng
```

## Usage

```php
<?php 
$translit = new TranslitService('Мама мыла раму', ' ');
echo $translit->run();
```
