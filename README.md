# Podman Drupal

Stack for running a local containerised development instance of Drupal with a MariaDB database and phpmyadmin for database admin.

## Prerequisites

Podman and podman-compose must be installed on the local development machine

Environment variables need to be set for database connectivity. These are used in the compose file for setting creating secrets that are used for database connectivity.

```shell
export MYSQL_PASSWORD=<VALUE>
export MYSQL_ROOT_PASSWORD=<VALUE>
```

## Running the environment

Start the stack

```shell
podman compose up -d
```

## Stopping the environment

Stop the stack

```shell
podman compose down
```
