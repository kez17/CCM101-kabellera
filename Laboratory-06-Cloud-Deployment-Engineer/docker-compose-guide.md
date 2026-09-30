# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block is used to describe the containers required by the application. The Compose configuration in this activity contains an `app` service for Nextcloud and a `database` service for MariaDB.

## How Did the Nextcloud App Container Find the Database?

Nextcloud gets the database location from its environment configuration. The value assigned to `MYSQL_HOST` is `database`, which corresponds to the MariaDB service name in the Compose file. This allows Nextcloud to communicate with the database service without manually entering a container IP address.

## What is the Difference Between `docker run` and `docker-compose up -d`?

`docker run` is commonly used when creating and starting a Docker container individually, with the required settings included in the command. In contrast, `docker-compose up -d` takes the service definitions from `docker-compose.yml` and starts the containers described there. The detached mode allows the containers to continue running in the background.
