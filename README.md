# Docker, PHP, Laravel Setup

## Getting Started

To get started with this setup, run the following command:

```
docker compose up -d --build
```

## Installing Required Dependencies

Once you have the Docker container up and running, you can install the required dependencies by executing the following commands

```
docker compose exec php sh
```

```
composer install
```

```
npm install
```

After installing the dependencies, copy the .env.example file to .env:

```
cp .env.example .env
```

Then generate an application key:

```
npm run dev
```

## Database Setup Configuration for .env File

Update the .env file with the following database configuration:

```
DB_CONNECTION=mysql
DB_HOST=172.19.0.1
DB_PORT=3307
DB_DATABASE=docker_laravel
DB_USERNAME=root
DB_PASSWORD=root
```

## Viewing Your Laravel Application

Once everything is set up, you can view your Laravel application by entering the following URL in your browser:

```
http://localhost:8090
```
