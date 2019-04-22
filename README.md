## docker network test

```
$ docker-compose -f docker-compose.app.yml up
$ docker-compose -f docker-compose.base.yml up

$ docker exec -it ${container_id} sh

# in alpine
/ # apk add --update mysql-client
/ # mysql -u root -h db_mysql -p
```
