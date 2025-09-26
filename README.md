# Demo cookie_session_auth
## Cài đặt
1. cd cookie_session_auth
2. npm start
3. node app.js
![alt](./cookie_session_auth/public/img/A1.png)
![alt](./cookie_session_auth/public/img/image.png)

## Test với POSTMAN 
4. Post: http://localhost:3000/auth/register
5. body -> raw -> nhập: {"username": "admin", "password": "12345"}
![alt](./cookie_session_auth/public/img/image%20copy.png)
6. Post: http://localhost:3000/auth/login
![alt](./cookie_session_auth/public/img/image%20copy%204.png)
7. Get: http://localhost:3000/auth/logout
![alt](./cookie_session_auth/public/img/image%20copy%205.png)
8. GET: http://localhost:3000/auth/profile
![alt](./cookie_session_auth/public/img/image%20copy%206.png)
## Test với MONGODB
9. Kết nối với localhost:27017
10. Chọn sessionAuth
11. users
![alt](./cookie_session_auth/public/img/image%20copy%202.png)
12. sessions
![alt](./cookie_session_auth/public/img/image%20copy%203.png)