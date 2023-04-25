# Docker, PHP, laravel Setup

#### Let's get started

```
docker compose up -d --build
```

### Install requires dependencies

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
 
#### Enter in your browser

```
http://localhost:8090
```
