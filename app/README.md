# App

## Requirements:

- Symfony 6.2.*
- PHP 8.1 or higher;

## Tools:

- EasyAdmin: ułatwienie przy tworzeniu panelu użytkownika
- Twig: od początku pracy w Symfony korzystan z twig

## Get Started:

```
composer install
npm install
npm run dev
symfony server:start -d
symfony console doctrine:database:create
symfony console make:migration
symfony console doctrine:migrations:migrate
```