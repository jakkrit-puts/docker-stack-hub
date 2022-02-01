# Create for WordPress + MySQL + PHPMyAdmin + Nginx

## structure project
```
WordPressDocker
   |-- mysql
   |-- nginx
      |-- nginx.conf
   |-- wordpress
   |-- docker-compose.yml
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

```
