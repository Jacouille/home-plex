# home-plex
Self host a Plex server with Docker

- ```bash
    docker network create home-plex
    ```
- ```bash
    docker compose --env-file .env.local up -d
    ```