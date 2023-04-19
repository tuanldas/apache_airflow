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

## providers

[Providers Connections](https://registry.astronomer.io/providers)

```
Edit env

_PIP_ADDITIONAL_REQUIREMENTS=apache-airflow-providers-airbyte
```
