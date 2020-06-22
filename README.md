# 仿饿了么的vue项目

## 项目启动：

1. npm install	下载模块
2. npm start	启动项目
3. 下载配合该项目的后台项目vm-server
4. util的sms_util中加入自己使用的容联云id、令牌等信息，此处因个人信息并未上传
5. 之后步骤同1、2，启动后台服务器

## 描述

目前是无错误的稳定版本，已将eslint的提示错误也修正了。

第三方库的使用：

- mintUI构建界面，better-scroll库实现页面滑动
- 使用vue-router开发单页应用
- 使用axios向后台发送请求，使用mockjs模拟后台数据接口
- 使用vuex管理组件共享数据

已实现的功能有：


- 账号密码登陆或手机号验证码登陆
- 首页轮播、商家列表及总购物车
- 商家商品、评价、信息界面展现，实现购物车加购功能
- 刷新购物车数据保存的功能



也许还有一些错误或者可以优化的地方，欢迎和我交流，共同学习，一起改进。

