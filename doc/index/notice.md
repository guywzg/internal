###### 接口功能

> 通知公告列表

###### URL

> http://xxx.com/internal/notice/list

###### 返回格式

> JSON

###### HTTP请求方式

> GET

###### 请求参数
>
|字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|pageSize|int|每页条数|
|pageNow|int|当前请求页|

###### 返回结果
>
|字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|total|int|总条数|
|pages|int|总页数|
|pageSize|int|每页条数|
|pageNow|int|当前页|
|data|数组|通知公告对象数组|

###### 接口示例

```JSON

{
    "total":56, 
    "pages":5, 
    "pageSize":10,
    "pageNow":0,
    "data":[
    
        {"id": 1, "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"},
        {"id": 2, "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"}, 
        {"id": 3, "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"}
    
    ]
}

```
