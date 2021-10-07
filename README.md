# docker-compose-laravel

## Usage

- `docker-compose up -d --build site`.
- `docker-compose run --rm composer update`
- `docker-compose run --rm npm run dev`
- `docker-compose run --rm artisan migrate`


## Using BrowserSync with Laravel Mix

```javascript
.browserSync({
    proxy: 'nginx',
    open: false,
    port: 3000,
});
```

```bash
docker-compose run --rm --service-ports npm run watch
```
