## Working with `docker compose config`

```bash
docker compose config
dcoker compose config --services

docker compose  -f compose_location.yaml config


docker compose down
docker compose down -v



docker compose config --services | grep "^peer"
docker compose up $(docker compose config --services | grep "^peer") -d
```
# Docker-Compose-Config
