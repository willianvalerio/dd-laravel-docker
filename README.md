# dd-laravel-docker
A simple environment with Datadog, Laravel, Redis and Mongo dockerized

## Up and Running

Export your Datadog API key:

```bash
export DD_API_KEY=YOUR_DD_API_KEY
```

Start containers and install depencies with composer:
```docker
docker-compose up -d
docker-compose exec php composer install
```

Open the URL in your browser: http://localhost:8000/