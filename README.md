# postgres-hstore docker image

Postgres 9.3/9.4/9.5/9.6 with hstore extension enabled based on the official [Docker PostgreSQL image](https://github.com/docker-library/postgres/).

Useful when you must have hstore enabled in your CI pipeline, but don't want to lose time with adding hstore during every single CI run.

### Available images:

```
mislavcimpersak/postgres_hstore:9.3
mislavcimpersak/postgres_hstore:9.4
mislavcimpersak/postgres_hstore:9.5
mislavcimpersak/postgres_hstore:9.6
```

Available on [docker hub](https://hub.docker.com/r/mislavcimpersak/postgres_hstore/).

--------

Credit for the original script for enabling hstore goes to [aidanlister](https://github.com/aidanlister/postgres-hstore).
