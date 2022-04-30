# VS CODE rest client plugin使用

\
\- 根據上一支API的回覆可以利用JsonPath的方式帶到下一支API[ https://www.tpisoftware.com/tpu/articleDetails/2316](https://www.tpisoftware.com/tpu/articleDetails/2316)\
\
\
線上JSON PATH的工具

```
### get all users
# @name users
GET http://..../users HTTP/1.1
content-type: application/json

[
{
"user":{
"id":"1234"
}

}
]
### get users by id
GET ..../{{users.response.body.$[0].user.id}}
也可以放進變數中
"{{users.response.body.$[0].user.id}}" //注意有雙引號

或是指給另一個變數
@userID = {{users.response.body.$[0].user.id}}
```



