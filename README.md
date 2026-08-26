# Affiliate Site

A Laravel 10 web application for an **affiliate/content-driven business workflow**, built with Laravel authentication, database-backed application logic, and API-ready foundations.

## Tech Stack

- PHP 8.1+
- Laravel 10
- Laravel Sanctum
- Laravel Breeze
- MySQL / Laravel Eloquent
- Guzzle HTTP client
- PHPUnit
- Laravel Sail
- SweetAlert

## Engineering Areas

- User authentication and protected application areas
- Database-backed business workflows
- REST/API authentication foundations with Sanctum
- Validation and server-side business logic
- HTTP integrations with Guzzle
- Automated testing setup with PHPUnit
- Containerized local development with Laravel Sail

## Run Locally

```bash
git clone https://github.com/Shraban-7/affiliate_site.git
cd affiliate_site
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
npm install
npm run build
php artisan serve
```

## Project Status

An earlier Laravel 10 project demonstrating practical business-application development. My current professional focus is **backend-focused Laravel engineering**, with deeper emphasis on API architecture, SQL performance, testing, queues, Redis, Docker, and CI/CD.

## Author

**Shraban Hossain**

- GitHub: https://github.com/Shraban-7
- Portfolio: https://www.devshraban.com/
- LinkedIn: https://www.linkedin.com/in/shakuat-shraban/
