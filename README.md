# Zuz's Invity Postgres (Docker)

### Start

```
docker-compose up -d
```

### Stop

```
docker-compose down
```

### Stop & Remove Data

```
docker-compose down --volumes
```

### Logs

```
docker-compose logs -f
```

### Test Connection

```
psql "host=127.0.0.1 port=5432 user=invity_api_db_user password=invity_api_db_pass dbname=invity_api_db_dev"
```
