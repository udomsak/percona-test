# docker-compose file สำหรับ build environment mysql ไว้ใช้สำหรับ test

## Requirement

- docker-compose
- docker

## Run

``` docker-compose up phpmyadmin ``` 

## หมายเหตุ

- พอร์ทเปิด เฉพาะ tcp 8080 ถ้าต้องการเปลี่ยนสามารถเปลียนได้ในไฟล์ docker-compose.yml 
- ค่าคอนฟิกของ username & password ให้ตั้งค่าใน config.env


