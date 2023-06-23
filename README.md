Tutorial Authentication Dengan Laravel, Inertia.js dan React.js

https://santrikoding.com/tutorial-authentication-dengan-laravel-inertiajs-dan-reactjs-1-installasi-dan-persiapan-laravel

composer create-project --prefer-dist laravel/laravel:9.3.0 inertia-react-auth

php artisan serve

composer require inertiajs/inertia-laravel

php artisan inertia:middleware

npm install

npm install @inertiajs/inertia@0.11.0

npm install @inertiajs/inertia-react@0.8.1

npm install @inertiajs/progress@0.2.7

npm install react@17.0.2 react-dom@17.0.2

npm run dev

php artisan make:controller Auth/RegisterController

php artisan route:list

http://127.0.0.1:8000/register

php artisan make:controller Auth/LoginController

php artisan make:controller DashboardController -i

