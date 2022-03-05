# site-monitering

## What app
Check the health of your site.

## Procedure
Setup
```
$ docker-compose build
$ docker-compose up -d
$ docker exec -it php bash
[root@XXXX]# composer install
[root@XXXX]# cp .env.example .env
```

Access browser 
```
http://localhost/
```