# 🧸中国联通话费小组件cookie获取

中国联通话费小组件cookie获取

## 配置说明

### Surge/ShadowRocket小火箭

安装模块

```ini
https://raw.githubusercontent.com/jyucoeng/Scripts4Me/main/rewrite/10010/10010.sgmodule
```


### Quantumult X

配置文件

```ini
[MITM]
hostname =  m.client.10010.com

[rewrite_local]
https:\/\/m\.client\.10010\.com\/(.*)\/smartwisdomCommon  url script-request-header     https://raw.githubusercontent.com/dompling/Script/master/10010/index.js

```

## 获取Cookies

获取方式：打开  中国联通 app 【官方版】-> 点击首页的剩余流量，会弹一个cookie 写入成功的提示，只要出现这个提示即可


