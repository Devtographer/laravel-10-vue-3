1. Install Laravel

```Shell
composer create-project laravel/laravel projectname
```

2. Install Laravel/Breeze

```Shell
composer require laravel/breeze --dev
```

3. Run the Breeze install command:

```Shell
php artisan breeze:install vue
```

4. Run the node server

```Shell
npm run dev
```

If you see this error:

```Shell
sh: vite: command not found'
```

run:

```Shell
npm install
```

and rerun the node server

```Shell
npm run dev
```

5. Run the Laravel server

```Shell
php artisan serve
```
