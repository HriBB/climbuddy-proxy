# ClimBuddy Nginx Proxy

## Add Cloudflare's nameservers

```
edna.ns.cloudflare.com
frank.ns.cloudflare.com
```

## Records

```
www.climb.si
api.gym.climb.si
gym.climb.si	climbuddy-gym.netlify.app.
api.climb.si
admin.climb.si
```

## Setup docker

- [Install docker](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04)
- [Install docker compose](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-22-04)

## Nginx proxy with letsencrypt

- [Nginx Proxy](https://github.com/nginx-proxy/nginx-proxy)
- [Acme Companion](https://github.com/nginx-proxy/acme-companion)
- [Acme companion docker-compose.yml](https://github.com/nginx-proxy/acme-companion/blob/main/docs/Docker-Compose.md)
