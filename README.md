# WechatDevToolsHttpCall
[![Build Status](https://www.travis-ci.org/bluecatlee/WechatDevToolsHttpCall.svg?branch=master)](https://www.travis-ci.org/bluecatlee/WechatDevToolsHttpCall)

基于微信开发者工具HTTP调用的微信小程序上传中间件

项目背景：
    多家机构需要使用同一套小程序,并且每一家的小程序不应完全一样,为了简化小程序的发布流程,采用了半自动化的方式,用户只需要在各自的管理后台进行版本选择、
  配置修改之后就可以上传代码.

1.微信开发者工具仅支持windows macOs;
2.微信开发者工具必须提前并始终打开 否则HTTP调用将无效;
3.微信开发者工具不能同时多人登录，否则会踢出先登录的人，因此提供了服务访问限制的功能;
4.此中间件只提供微信开发者登录、打开项目、获取预览二维码、上传小程序等重要功能。

附:
 微信开发者工具HTTP调用API文档 https://developers.weixin.qq.com/miniprogram/dev/devtools/http.html
