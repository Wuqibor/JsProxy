# JsProxy
**这是一个使用 JavaScript For Nodejs 规范语法 编写的,搭建于Cloudflare的Workers服务的一个支持内容替换的反向代理**

----

## 折腾

之前我在Github以及很多地方找过JsProxy，找到了很多项目
比如这个原作者的项目，很多都是基于他修改的：

[https://github.com/xiaoyang-liu-cs/booster.js](https://github.com/xiaoyang-liu-cs/booster.js "xiaoyang-liu-cs")

但是原版的最新版虽然功能很丰富但是没有内容替换

即使有些修改版有这个功能但无法替换链接内容，还是会回源
~~或者是我打开的姿势不对？~~

无解，于是根据作者的版本修改后有了此物

>本版本内容替换可避免回源问题并且支持完整POST提交(原版木有)!

## 部署

>注：基于Cloudlare的Workers无服务器程序服务

把fd.js的内容部署到Workers即可

js内有详细注释自行修改

## 其它

Bilibili:Wuqibor
Email:admin@wuqibor.gq
QQ:1722302509
