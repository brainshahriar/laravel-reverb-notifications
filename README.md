<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Setup Instructions
1. Clone the repository
2. Copy example.env to .env
3. Run `composer install`
4. Run `npm install`
5. Create a database named `funwithreverb`.
6. Migrate the database with:
   ```
   php artisan migrate
   ```
7. Seed the database with:
   ```
   php artisan db:seed
   ```
8. Run the development server with:
   ```
   php artisan serve
   ```
9. For Vite/frontend, run:
   ```
   npm run dev
   ```
10. Start the Reverb service with:
   ```
   php artisan reverb:start
   ```
11. Start the queue listener with:
   ```
   php artisan queue:listen
   ```
12. Login with an editor account in one browser and a chief editor account in another browser using the common password `password`.
13. Delete any data from the editor account, and the chief editor will receive a notification.
