###### 接口功能

> 调查问卷

###### URL

> http://xxx.com/internal/questionnaire/submit

###### 返回格式

> JSON

###### HTTP请求方式

> POST

###### 请求参数
>
|字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|userId|Long|UserID|
|questionnaireId|long|ID|
|questions|数组|答案数组|

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
    "userId":1, 
    "questionnaireId":1, 
    "questions":[{"id": 1, "questionnaireId": 1, "answer": "A"}]
}

```
>
```JSON

{
    "code":200, 
    "message":"成功", 
    "data":{
      "questionnaire": {"id": 1, "status":"待填写", "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"},
      "questions": [{"id": 1, "questionnaireId": 1, "tital": "头痛", "answer": "","options": [{"questionId": 1, "Tag": "A", "name": "从无"}]}]
    }
}

```
