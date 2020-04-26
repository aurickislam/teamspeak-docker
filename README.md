# teamspeak-docker

##### Run standalone teamspeak server container:
```shell script
docker-compose up -d
```

##### Remove standalone teamspeak server container:
```shell script
docker-compose down -v
```

---

##### Run teamspeak server container with MariaDB:
```shell script
docker-compose -f docker-compose-mariadb.yml up -d
```

##### Remove teamspeak server container without deleting data:
```shell script
docker-compose -f docker-compose-mariadb.yml down
```

##### Remove teamspeak server container with data:
```shell script
docker-compose -f docker-compose-mariadb.yml down -v
```
