# Nginx Proxy Redirect

Simple Nginx redirect fork to allow fast troubleshooting.

It intends only to:
- Define listening nginx port 
- Setup a proxy target

## Container Variables

```
NGINX_PORT: Nginx listening port
PROXY_TARGET: Nginx proxy target
```

## Build
```
docker-compose build
```

## Run
```
docker-compose up -d
```