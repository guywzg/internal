###### 接口功能

> 随手拍

###### URL

> http://xxx.com/internal/snapshot/submit

###### 返回格式

> JSON

###### HTTP请求方式

> POST

###### 请求参数
>
|字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|title|String|标题|
|type|int|类型|
|dateTime|Date|发生时间|
|location|String|位置|
|longitude|Stirng|经度|
|latitude|Stirng|纬度|
|content|Stirng|事件描述|
|userId|Long|UserID|

###### 返回结果
>
|字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|code|int|code|
|message|String|描述|
|data|Object|随手拍对象|

###### 接口示例

```JSON

{
    "code":200, 
    "message":"成功", 
    "data":{"id": 1, "userId":1, "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"}
}

```
