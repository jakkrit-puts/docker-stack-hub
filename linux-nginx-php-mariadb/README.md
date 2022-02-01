# Custom Image LEMP Stack (Linux+NGINX+PHP+MariaDB)

## structure project
```
----
LEMPDocker
   mariadb
       |--data
       |--initdb
          |-- db.sql
   nginx
       |-- conf
            |-- nginx.conf
       |-- conf.d
            |-- default.conf
   php
       |-- Dockerfile
   public_html
       |-- index.php
       |-- info.php
   docker-compose.yml
```

## command
```
เช็คความถูกต้องของไฟล์ docker-compose.yml
---
$ docker-compose config
$ docker-compose config -q

การรัน docker-compose.yml เพื่อสร้าง images และ containers
---
$ docker-compose up -d

ลองตรวจสอบ container ที่รันอยู่
---
$ docker-compose ps

กรณีต้องการ Rebuid ตัว images และ container ใหม่
---
$ docker-compose up -d  --build  
```
