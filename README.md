# Awin PHP


PHP library for the Awin API.

You can get your apiToken here: [https://ui.awin.com/awin-api](https://ui.awin.com/awin-api)

See full doc: [http://wiki.awin.com/index.php/Publisher_API](http://wiki.awin.com/index.php/Publisher_API)

Fork for [https://www.darf-ich-mit.de](https://www.darf-ich-mit.de)


## Install

Via Composer

``` bash
$ composer require yuzu-co/awin-php
```

## Usage

``` php
$apiToken = 'XXXXX'
$client = new Yuzu\Awin\Client($apiToken);
```

## Tests

```php
php composer tests
```


## TODO

* GET commissiongroups missing 
* GET transactions by ID missing 
* GET reports missing