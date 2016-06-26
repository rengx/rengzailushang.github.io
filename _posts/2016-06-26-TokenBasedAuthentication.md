---
img :
  url : 20160626tokenbasedauthentication_jwtwork.png
title : 基于Token的认证和基于声明的标识
digest : 基于Token的认证和基于声明的标识，JWT定义了一种在客户端和服务器之间轻便和独立的（compact and self-contained）传递信息的方法。
---

#### 基于Token的认证和基于声明的标识

> http://codelife.me/blog/2014/03/26/token-based-authentication-and-claims-based-identity/

#### JWT
JWT定义了一种在客户端和服务器之间轻便和独立的（compact and self-contained）传递信息的方法。传递的信息做了数字签名（HMAC或者RSA），是被验证和可信的。s

- **compact**: smaller size, can be sent through an URL, POST parameter, or inside an HTTP header.

- **self-contained**: The payload contains all the required information about the user, avoiding the need to query the database more than once.

##### JWT Scenarios
- Authentication
alse sso
- Information Exchange

##### How do JWT work?
![](index_files/jwtwork.png)

#### 各抒己见
https://www.v2ex.com/t/148426

#### 细节实现

##### token的存储和传递
如果access token 和 refreh token，应该存储在哪，用户中心，还是业务应用？
存储在业务应用的话，侵入性太强；

token在每次请求中是如何传递的，可以是http header，这样的话使用requestwrap和responsewrap

##### token的一个使用介绍
http://www.haomou.net/2014/08/13/2014_web_token/

##### token benifits
http://stackoverflow.com/questions/1592534/what-is-token-based-authentication


