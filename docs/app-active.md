##激活当前设备
===
###请求方式
---

**POST** `http://open.kaolafm.com/v1/app/active`

###认证参数
---
| 参数名称 | 类型    | 是否必需 |描述
|:------- |-------:|:------:|:----|
| appid   | string |   是   |应用id
| sign    | string |   是   |签名


###请求参数
---

| 参数名称 | 类型    | 是否必需 |描述
|:------- |-------:|:------:|:----|
| deviceid  | string |   是   |设备唯一id（可使用手机udid,mac地址,vin等）

###返回参数
---

| 参数名称 | 类型    | 描述 
|:------- |-------:|:------:|
| openid   | string |   标识指定设备的标识  |

###结果样例
---
    {
      "result": {
          "openid": "100000017370150"
      },
      "requestId": "zcrzd94051416455268317671"
    }

    


###错误信息

请参考错误代码释义