
### Registration
```
POST https://blog-platform.kata.academy/api/users/
{
  "user": {
    "username": "anton",
    "email": "antonydvoininow@outlook.com",
    "password": "my_best_password"
  }
}
```

### Authentication
```
POST https://blog-platform.kata.academy/api/user/users/login/
{
    "user": {
      "email": "antonydvoininow@outlook.com",
      "password": "my_best_password"
    }
}
```

###  Get Current User
```
GET https://blog-platform.kata.academy/api/user/
-H Authorization: Token eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY3NjM5MjljY2UxОGQwMWIwMDJiNjYzNSIsInVzZXJuYW1lIjoiYW50b24iLCJleHAiOjE3Mzk3NjI4NDUsImlhdCI6MTczNDU3ODg0NX0.0E8h2_unnHHfQhevGPqq9Mpy_U0j90ylVаMbTEYb1mo
```

<br/>

![screenshot](https://github.com/anton-dv/rest/blob/main/screenshot1.png)

![screenshot](https://github.com/anton-dv/rest/blob/main/screenshot2.png)

![screenshot](https://github.com/anton-dv/rest/blob/main/screenshot3.png)
