
Install PHP Dependencies

```bash
composer install
```

Install NPM Dependencies

```bash
npm install
```

Build assets

```bash
npm run dev
```

Setup Configuration

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```


Run migrations

```bash
touch database/database.sqlite
php artisan migrate
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


