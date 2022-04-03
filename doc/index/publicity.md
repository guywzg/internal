###### 接口功能

> 环保宣传列表

###### URL

> http://xxx.com/internal/publicity/list

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
|data|数组|环保宣传对象数组|

###### 接口示例

```JSON

{
    "total":56, 
    "pages":5, 
    "pageSize":10,
    "pageNow":0,
    "data":[
    
        {"id": 1, "img":"http://xxx.com/3.jpg", "title":"绿色出行，节能减排我出力", "date":"2022/04/12"},
        {"id": 2, "img":"http://xxx.com/3.jpg", "title":"新年添新衣，旧衣捐出去", "date":"2022/04/12"}, 
        {"id": 3, "img":"http://xxx.com/3.jpg", "title":"治气，日争夜抢；攻坚，丝毫不让！", "date":"2022/04/12"}
    
    ]
}

```
