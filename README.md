# Check-in Bot

## JD

1. 在`Settings`-`Secrets`里面添加`JD_COOKIE`

2. 多条cookie用`&`隔开,支持无数条cookie


```
备注:
如何获取 Cookie：
电脑登录网页 https://bean.m.jd.com ，打开调试模式（F12），刷新页面，然后复制 Cookie。

只需要
pt_key=****
和
pt_pin=***
的部分

如有两个账号,则 JD_COOKIE 里面要填写的内容为
pt_key=****;pt_pin=***&pt_key=****;pt_pin=***
```
