# simple-lets-encrypt-docker-compose-sample

Sample `docker-compose.yml` that shows how to use [letsencrypt-nginx-proxy-companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion).

This `docker-compose.yml` starts up a wordpress instance backed by a db container. You **MUST** update the following variables: `VIRTUAL_HOST`, `LETSENCRYPT_HOST`, `LETSENCRYPT_EMAIL` in order for SSL to work. See [letsencrypt-nginx-proxy-companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion) for more info.

