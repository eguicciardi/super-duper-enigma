# Notes

This are my day to day notes and snippets for commands there's no chance I can remember. Divided by topic.

## Docker

### Remove Docker unused data

```bash
docker system prune
```

## NGINX

### Reload config

```bash
docker exec -it <CONTAINER_NAME> nginx -s reload # On Docker
nginx -s reload # Non-Docker
```

## MongoDB

### Import BSON file into a collection

```bash
 mongorestore --host <HOST> --port 27017 --db <DB_NAME> --collection <COLLECTION_NAME> --username <USERNAME> --password <PASSWORD> --authenticationDatabase admin <PATH_TO_BSON_FILE>
```