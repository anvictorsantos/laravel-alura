# Back-end

## Pré-requisitos
* PHP 8.0.24
    * extensões:
        * curl
        * openssl
        * pdo_mysql
        * pdo_sqlite
* Composer version 2.4.2
## Projeto Setup
```
* Rodar na raiz do projeto:
    * composer install
    * cp .env.example .env
    * php artisan key:generate
    * touch database/database.sqlite
    * php artisan migrate
```

### Startar projeto local
```
php artisan serve
```
