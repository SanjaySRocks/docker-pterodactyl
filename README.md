# docker-pterodactyl

Configuration for running pterodactyl in docker container


### Panel Install

```docker-compose up -d```

### Add User

``` docker-compose run --rm panel php artisan p:user:make```


### Useful Help:-

Panel - nginx proxy + cloudflare proxy + ssl

Node - no nginx proxy + no cloudflare proxy + custom ssl + not behind proxy + 8080
