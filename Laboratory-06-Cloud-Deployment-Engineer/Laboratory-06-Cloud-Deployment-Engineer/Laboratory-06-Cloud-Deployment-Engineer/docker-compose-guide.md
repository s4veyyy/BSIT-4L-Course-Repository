# Docker Compose Guide

## What Is Docker Compose?

Docker Compose is a tool that allows me to define and manage multiple containers using a single YAML configuration file. Instead of running each container separately, I can configure the services in `docker-compose.yml` and deploy them together.

## Understanding the Services Block

The `services:` block defines the containers that make up the application. In this mission, it contains two services: `database`, which uses the MariaDB image, and `app`, which uses the Nextcloud image.

## Connecting Nextcloud to MariaDB

The Nextcloud container finds the database using the `MYSQL_HOST=database` environment variable. The value `database` matches the service name in the Compose file, allowing Nextcloud to connect to MariaDB through Docker's internal network.

## Environment Variables

Environment variables configure the database credentials and connection details. For example, `MYSQL_DATABASE` specifies the database name, while `MYSQL_USER` and `MYSQL_PASSWORD` specify the database username and password used by the application.

## docker run vs. docker-compose up -d

The `docker run` command is commonly used to start an individual container with options specified directly in the terminal. In comparison, `docker-compose up -d` reads the `docker-compose.yml` file and starts the configured services together in the background.

## Deployment and Verification Commands

    docker-compose up -d

This command creates and starts the services defined in the Compose file.

    docker-compose ps

This command displays the status of the Compose containers.

    docker-compose down

This command stops and removes the containers created for the Compose project.
