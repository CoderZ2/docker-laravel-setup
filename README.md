### Start Building Docker

```
docker compose up -d
```

Open cmd and install require dependicies

```
docker compose exec php sh
```
```
composer install
```
```
npm install
```

Database setup configruation for .env file

```
DB_CONNECTION=mysql
DB_HOST=172.19.0.1
DB_PORT=3307
DB_DATABASE=docker_laravel
DB_USERNAME=root
DB_PASSWORD=root
```
 
Open the browser and type below url

```
http://localhost:8090
```
