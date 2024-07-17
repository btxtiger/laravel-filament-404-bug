# Filament Custom Page 404 bug

Route `/admin/hello` is not accessible, it returns 404 page.

## Steps to reproduce
```bash
composer install
php artisan serve

# Open http://localhost:8000/admin
Credentials:
User: admin@admin.local
Password: j
```
