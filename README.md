# Laravel 8 + CoreUI + Livewire + Datatables

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/aRhez0903/Laravel-8-Livewire-CoreUI-Datatables/issues)

## About Laravel 8 + CoreUI + Livewire Datatables

## Whats Inside
- Laravel Core UI - (https://github.com/HZ-HBO-ICT/Laravel-CoreUI)
- Laravel Permisson (https://github.com/spatie/laravel-permission)
- Livewire Datatables (https://github.com/mediconesystems/livewire-datatables)

Include simple Data Table with Livewire (CRUD).

## Installation
### First clone or download this repository
```shell
git clone https://github.com/aRhez0903/Laravel-8-Livewire-CoreUI-Datatables.git
```

After clone or download this repository, next step is install all dependency required by laravel and laravel-mix.

```shell
# install composer-dependency
composer install
# install npm package
npm install
# build dev 
npm run dev


### Next Step
Before we start web server make sure we already generate app key, configure `.env` file and do migration.

```shell
# create copy of .env
cp .env.example .env
# create laravel key
php artisan key:generate
# laravel migrate & seed some data
php artisan migrate:fresh --seed
```

## Contributing
Thank you for considering contributing to this repo!

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
