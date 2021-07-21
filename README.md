# Spring Security Authorization with JWT

[![Java CI with Maven](https://github.com/hemrajanilavesh/spring-security-json-web-token/actions/workflows/maven.yml/badge.svg?branch=main)](https://github.com/hemrajanilavesh/spring-security-json-web-token/actions/workflows/maven.yml)

- First Call `POST` endpoint `/authenticate` along with below Request Body. Response will be JSON Web Token

```
    {
        "username": "foo",
        "password": "foo"       
    }
```
 
- Then Call `GET` endpoint `/hello` and pass JWT in the `Authorization` header. Response will be `<h1>Hello, World!</h1>`
