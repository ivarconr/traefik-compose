# traefik-compose

Before you start docker needs a network called "web":

`docker network create web`


Start traefik:
```
cd traefik
docker compose up
```

Start edge (uses labels for discovery):

```
cd unleash-edge
docker compose up
```
