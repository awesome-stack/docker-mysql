# Docker compose template for MySQL and Metabase

## Requirements
* Docker
* Docker Compose

## Run
```
docker-compose up -d
```
* Metabase: http://localhost:3000
* MySQL: 
    - `mysql -h localhost --port 3306 --protocol tcp -u root -proot`
    - `mysql -h localhost --port 3306 --protocol tcp -u app -papp`
