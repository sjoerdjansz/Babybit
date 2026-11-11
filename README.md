# Babybit

Babybit is een klein testproject, gebouwd in [Laravel](https://laravel.com), om basisinformatie rondom een baby bij te houden, zoals verschonen en voeden.

Het diende vooral het doel om Laravel wat beter te leren kennen (routing, controllers, Blade, Eloquent, migraties en authenticatie).

## Vereisten

- PHP 8.3+
- Composer
- Node.js en npm

## Installatie

1. Clone de repository en ga naar de projectmap.
2. Draai de setup. Die installeert de dependencies, maakt `.env` aan, genereert de app-key, draait de migraties en bouwt de assets:

   ```bash
   composer run setup
   ```

## Lokaal draaien

```bash
composer run dev
```

Dit start de webserver, de queue, de logs en Vite tegelijk. De app is daarna bereikbaar op http://localhost:8000.

Na het pullen van nieuwe wijzigingen werk je de database bij met:

```bash
php artisan migrate
```

## Tests

```bash
composer run test
```
