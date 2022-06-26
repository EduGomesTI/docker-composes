# Docker-Composes

## Sonarqube

Para iniciar: docker-compose -f sonarqube-compose.yaml up -d

Para parar: docker-compose -f sonarqube-compose.yaml down

localhost:9000

Login: admin

Senha: admin

## MongoDB

Para iniciar: docker-compose -f mongodb-compose.yaml up -d

Para parar: docker-compose -f mongodb-compose.yaml down

StringConnection: mongodb://mongouser:mongopwd@localhost:27017/?authMechanism=DEFAULT&authSource=admin

## SQL Server

Para iniciar: docker-compose -f sqlserver-compose.yaml up -d

Para parar: docker-compose -f sqlserver-compose.yaml down

localhost:1433

Login: SA

Senha: mssql1Ipw

## Postgres

Para iniciar: docker-compose -f postgres-compose.yaml up -d

Para parar: docker-compose -f postgres-compose.yaml down

login: user

Senha: S3cret
