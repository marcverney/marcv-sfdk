# Symfony Docker

A [Docker Compose](https://www.docker.com/products/docker-compose) project to create Symfony applications.

## Usage

- clone this repository
- make a copy of the `.env.dist` file called `.env`
- adjust the settings inside `.env`. Pay special attention to `DOCUMENT_ROOT`, which must point to the root of your Symfony project
- run `docker-compose up -d`

