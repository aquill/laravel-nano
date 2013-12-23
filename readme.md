laravel-nano
============

A simplified version of the Laravel framework (3.0.0).

Laravel nano Change Log
-----------------------

### 12-23, 2013

- Move `public/index.php` to `index.php`.
- Updated `paths.php`.
- Rename `application` to `app`.
- Rename `config/application.php` to `config/app.php`.
- Move `storage` to `app/storage`.
- Replace `Config::get(application.*)` to `Config::get(app.*)`.
- Added eloquent model classes `Laravel\Database\Eloquent`.
- Updated `Auth` class `Laravel\Auth`.
- Added auth drivers classes `Laravel\Auth\Drivers`.
- Updated `Controller::response` method to routes controllers.
- Updated `Database::connection` method.
- Added `type_em` method in `Grammar`.
- Remove all `sqlsrver `.