# Custom Nginx

## Container Variables

```
NGINX_PORT: Nginx listening port
PROXY_TARGET: Nginx proxy target
```

## Build
```
docker build -t custom-nginx .
```

## Run
```
docker-compose up -d
```