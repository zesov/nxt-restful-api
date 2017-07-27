#nxt restful api
odoo restful api

Odoo 的RESTful风格接口模块

# 特性

# 使用
1. 下载源码
2. 将整个nxt_restful_api目录放到你的addons目录下，
3. 更新模块列表，安装模块，
4. 通过RESTful方式访问接口
```
	1. 获取token, http://host/api/v1.0/get_token?a=login&s=passwd&d=database
	2. 通过get/post/put方式访问Odoo数据和方法: /api/v1.0/<string:model>
```



详细说明：...



## 接口名称

### 1) 请求地址

>http://d10c.y.appnxt.com/api/v1.0/get_token?a=admin&s=admin&d=d10c

### 2) 调用方式：HTTP get

### 3) 接口描述：

* 接口描述详情

### 4) 请求参数:

#### GET参数:
|字段名称       |字段说明         |类型            |必填            |备注     |
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|a|用户名|string|Y|-|
|s|密码|string|Y|-|
|d|数据库|string|Y|-|



### 5) 请求返回结果:

```
{
    "token": "aHR0cDovL2QxMC5hcHBueHQuY29tLGQxMGMsYWRtaW4sMSwxNTAxMTYxMDk3",
    "message": "",
    "success": true
}
```


### 6) 请求返回结果参数说明:
|字段名称       |字段说明         |类型            |必填            |备注     |
| -------------|:--------------:|:--------------:|:--------------:| ------:|
|token|token|string|Y|-|
|message|消息|string|Y|-|
|success|成功标志|string|Y|-|



Odoo交流QQ群: 19794653
网址: http://appnxt.com
