###### 接口功能

> 调查问卷详情

###### URL

> http://xxx.com/internal/questionnaire/detail

###### 返回格式

> JSON

###### HTTP请求方式

> GET

###### 请求参数
>
|字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|id|int|ID|

###### 返回结果
>
|字段|字段类型|说明|
| :-----: |  :-----: | :-----: |
|data|Object|调查问卷详情|

###### 接口示例

```JSON

{
  "data":{
      "questionnaire": {"id": 1, "status":"待填写", "img":"http://xxx.com/3.jpg", "title":"央视聚焦！苏州这道“无形隔声墙”，巧治城市噪声污染", "date":"2022/04/12"},
      "questions": [{"id": 1, "questionnaireId": 1, "tital": "头痛", "answer": "","options": [{"questionId": 1, "Tag": "A", "name": "从无"}]}]
  }
}

```
