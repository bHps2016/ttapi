# ttapi -> tt APi 文档

## 首页
### 1. 个人偏好选择+推荐美食展示

+ url: /api/pefer
+ method: POST
+ post data:(个人偏好选择)
```
    {
        "type": 1(饭)/2(面)/3(稀食),
    }
```
+ return value:(推荐美食展示)
```
    {
        "img": 菜图片的url,
        "name": 菜的名字,
    }
```
