## Installation
1. Clone the repository.
2. Run `composer install`.
3. Copy & setup `.env` file.
4. Create database & Change `DB_DATABASE` in `.env`.
5. Migrate the Database `php artisan migrate`.
6. Run `php artisan key:generate`
7. Run `php artisan db:seed` (This will generate super-admin & basic settings [required]).

##### Default Login Credential for super admin
| Username | Password |
|----------|----------|
| super    | 123456   |
