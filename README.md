# Symfony Docker

A [Docker Compose](https://www.docker.com/products/docker-compose) project to create Symfony applications.

## Usage

1. clone this repository
1. make a copy of the `.env.dist` file called `.env`
1. adjust the settings inside `.env`. Pay special attention to `DOCUMENT_ROOT`, which must point to the root of your Symfony project
1. run `docker-compose up -d`

