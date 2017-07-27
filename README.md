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

接口名称 get查询接口
1) 请求地址
http://host/api/v1.0/res.partner?token=ae92b9de797e342771d45dd2c72602d71ccea3ab&per_page=80&page=1&fields=['name','mobile']
2) 调用方式：HTTP get
3) 接口描述：
接口描述详情
4) 请求参数:
GET参数:

5) 请求返回结果:
{
    "per_page": 80,
    "total": 1199,
    "result": [
        {
            "mobile": "903",
            "id": 1,
            "name": "116150"
        },
        {
            "mobile": "900",
            "id": 2,
            "name": "111702"
        },
        {
            "mobile": "11103090",
            "id": 3,
            "name": "116129"
        }
        ……
    ],
    "page": 1
}
6) 请求返回结果参数说明:



http://appnxt.com


Odoo开发实施交流QQ群: 19794653
