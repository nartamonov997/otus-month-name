# Получение названия месяца по его номеру

## Требования
- PHP 7.4

## Установка

```bash
$ composer require nartamonov997/otus-hw3-month-name
```

## Использование

```php
<?php
$processor = new MonthProcessor();
echo processor->getMonthName(1); // Январь
```