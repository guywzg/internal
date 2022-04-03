###### 接口功能

> 首页

###### URL

> http://xxx.com/internal/index

###### 返回格式

> JSON

###### HTTP请求方式

> GET
###### 请求参数
>

###### 返回结果
>
|返回字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|banner|数组|轮播图对象数组|
|weather|数组|气象信息对象数组|
|news|数组|新闻对象数组|

###### 接口示例

```JSON

{
    "banner":[
    
        {"image":"http://xxx.com/1.jpg","url":"http://xxx.com/xxxx/1"},
        {"image":"http://xxx.com/2.jpg","url":"http://xxx.com/xxxx/2"}
    
    ], 
    "weather":[
        {"id": 1, "town": "杨舍镇", "aqi": 40, "level": "优"},
        {"id": 1, "town": "杨舍镇", "aqi": 40, "level": "优"},
        {"id": 1, "town": "杨舍镇", "aqi": 40, "level": "优"}
    ], 
    "news":[
    
        {"id": 1, "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"},
        {"id": 2, "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"}, 
        {"id": 3, "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"}
    
    ]
}

```
