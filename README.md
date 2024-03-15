# Airflow

## echo -e "AIRFLOW_UID=$(id -u)" > .env if lnux machine else echo AIRFLOW_UID=50000

### docker compose up airflow-init         --run database migration

#### docker compose up -d                   ---start all services

##### docker compose down --volumes --rmi all
