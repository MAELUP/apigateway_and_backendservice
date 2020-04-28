Test
- curl http://nodeapp.backend:8081/getUsers 
- curl http://192.168.145.158:8081/getUsers 

------------------------------------------------------

เครื่อง API Gateway 
้- ตั้ง hostname nginx.apigateway
- แล้วให้เอา config แต่ละตัวใน api-gateway ไปลงแต่ละที่
- hosts ไปที่ /etc/hosts
- nginx ไปที่ /etc/nginx

------------------------------------------------------

เครื่อง backend service 
- hostname nodeapp.backend 
- hosts ไปที่ /etc/hosts
- nginx ไปที่ /etc/ngin
- node-app รันที่ในนี้ก็ได้
- ไม่ต้อง npm install เพราะในนี้มี node module แล้ว
