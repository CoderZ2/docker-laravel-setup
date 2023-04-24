# Docker, PHP, laravel Setup

#### Let's get started

```
docker compose up -d --build
```

### Please do following step before getting started

```
docker compose exec php sh
```
```
composer install
```
```
npm install
```

```
cp.env.example .env
```

```
php artisan key:generate
```

```
npm run dev
```


#### Database setup configruation for .env file

```
DB_CONNECTION=mysql
DB_HOST=172.19.0.1
DB_PORT=3307
DB_DATABASE=docker_laravel
DB_USERNAME=root
DB_PASSWORD=root
```
 
#### Copy below url and enter in browser

```
http://localhost:8090
```
