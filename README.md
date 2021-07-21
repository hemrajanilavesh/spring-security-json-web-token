# Spring Security Authorization with JWT

- First Call `POST` endpoint `/authenticate` along with below Request Body. Response will be JSON Web Token

```
    {
        "username": "foo",
        "password": "foo"       
    }
```
 
- Then Call `GET` endpoint `/hello` and pass JWT in the `Authorization` header. Response will be `<h1>Hello, World!</h1>`