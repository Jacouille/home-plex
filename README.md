# home-plex
Self host a Plex server with Docker

[Guides](https://trash-guides.info/)
[hotio containers](https://hotio.dev/containers)



Create the folowing file structure in the root of this repo
- data
    - media
        - movies
        - tv
    - torrents
        - movies
        - tv

- ```bash
    docker network create home-plex
    ```
- ```bash
    docker compose --env-file .env.local up -d
    ```