
## Tripsia

Hotel management system for Pakistan

- [Installation](#installation)
- [Testing](#testing)
- [Linting](#linting)

## Installation
Run following commands:
```shell script
composer install
npm install
php artisan:migrate
php db:seed
```

## Testing
```shell script
./vendor/bin/phpunit
```

## Linting
**To check linting on a specific file**
```shell script
./vendor/bin/phpcs file_path
```

**To fix linting**
```shell script
./vendor/bin/php-cs-fixer fix file_path --config .php_cs
```
## Booking.com Hotels
**Url to download csv for booking.com hotels for Pakistan**
[https://testpakitrips.nanosoftplus.com//scraper/booking](https://testpakitrips.nanosoftplus.com//scraper/booking)



Git Clone from repo
composer install 
npm install
php artisan migrate:fresh --seed --force
make a "installed" file 
and then php artisan serve
