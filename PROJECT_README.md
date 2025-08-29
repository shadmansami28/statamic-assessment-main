# Statamic-Assesment


# Chase-create

`mkdir storage`
`mkdir storage\app`
`mkdir storage\app\public`
`mkdir storage\framework`
`mkdir storage\framework\cache`
`mkdir storage\framework\cache\data`
`mkdir storage\framework\sessions`
`mkdir storage\framework\views`
`mkdir storage\logs`
`mkdir bootstrap\cache`

## Installation

1. Clone this repository
2. Run `composer install`
3. Run `npm install`
4. Copy `.env.example` to `.env` and configure your database to sqlite
5. You need to change your env file line number 23 to `DB_DATABASE=database/database.sqlite`
6. Then run `type nul > database\database.sqlite`
7. Then run `php artisan migrate`
8. Then run `php artisan key:generate`
9. Then install`php artisan statamic:install`
10. Run `php please make:user` to create an admin user
11. Run ` npm run dev` to compile assets
12. It will just run the project but with out the database you will got errors and as it is a public repository I didn't shared my database but I will attach a video of the project how it looks.

## Features Included

- Blog post listing with pagination
- Responsive card layouts
- Dark/light mode toggle
- Image galleries with Swiper.js
- [Add your other features]