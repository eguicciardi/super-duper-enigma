# Notes

## MongoDB

### Import BSON file into a collection

```bash
 mongorestore --host <HOST> --port 27017 --db <DB_NAME> --collection <COLLECTION_NAME> --username <USERNAME> --password <PASSWORD> --authenticationDatabase admin <PATH_TO_BSON_FILE>
```
