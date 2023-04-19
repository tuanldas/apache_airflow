# Apache Airflow

## Build docker image

```
docker compose up -d
```

## Create User

```
docker compose exec -it airflow-worker bash

airflow users  create --role Admin --username admin --email admin --firstname admin --lastname admin --password admin
```
