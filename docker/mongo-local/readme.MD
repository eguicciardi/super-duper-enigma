# Local MongoDB

For local development only, **NOT MEANT TO BE USED IN PRODUCTION OR STAGING!!!**

## Basic stuff

```bash
docker compose up -d # Boot
docker compose down # Shutdown
```

This is the connection string to be used in Compass or in the env file of an application.

```bash
mongodb://root:password@localhost:27017/COLLECTION_NAME?authsource=admin
```
