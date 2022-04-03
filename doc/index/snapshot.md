###### 接口功能

> 随手拍

###### URL

> http://xxx.com/internal/snapshot/index

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
|data|Object|随手拍首页信息|

###### 接口示例

```JSON

{
    "banner":[
    
        {"image":"http://xxx.com/1.jpg","url":"http://xxx.com/xxxx/1"},
        {"image":"http://xxx.com/2.jpg","url":"http://xxx.com/xxxx/2"}
    
    ], 
    "data":{ "content" : ""}
}

```
