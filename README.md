# About finch-mwaa-local-runner

This repository provides a command line interface (CLI) utility that replicates an Amazon Managed Workflows for Apache Airflow (MWAA) environment locally, that has been customised for those who want to use Finch.


You can view the original project [here](https://github.com/aws/aws-mwaa-local-runner).

## To use this repo

1. You will need to install [Finch](https://github.com/runfinch/finch)

2. You will need to start a Finch VM

```
finch vm start
```

3. You will need to create a volume from PostgreSQL using the following command

```
finch volume create pgdata
```

4. You can now use  **mwaa-finch-local-runner** command as per usual. It will use Finch rather than Docker and Docker Compose.

