# Podman Drupal

Set environment variables for database connectivity. These are used in the compose file for setting database connectivity.

```shell
export MYSQL_PASSWORD=<VALUE>
export MYSQL_ROOT_PASSWORD=<VALUE>
```

Start the stack

```shell
podman compose up -d
```
