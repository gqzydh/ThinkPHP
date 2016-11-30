# ThinkPHP

>ThinkPHP 是一个免费开源的，快速、简单的面向对象的 轻量级PHP开发框架 ，创立于2006年初，遵循Apache2开源协议发布，是为了敏捷WEB应用开发和简化企业应用开发而诞生的。ThinkPHP从诞生以来一直秉承简洁实用的设计原则，在保持出色的性能和至简的代码的同时，也注重易用性。并且拥有众多的原创功能和特性，在社区团队的积极参与下，在易用性、扩展性和性能方面不断优化和改进，已经成长为国内最领先和最具影响力的WEB应用开发框架，众多的典型案例确保可以稳定用于商业以及门户级的开发。

## 全面的WEB开发特性支持

最新的ThinkPHP为WEB应用开发提供了强有力的支持，这些支持包括：

*  MVC支持-基于多层模型（M）、视图（V）、控制器（C）的设计模式
*  ORM支持-提供了全功能和高性能的ORM支持，支持大部分数据库
*  模板引擎支持-内置了高性能的基于标签库和XML标签的编译型模板引擎
*  RESTFul支持-通过REST控制器扩展提供了RESTFul支持，为你打造全新的URL设计和访问体验
*  云平台支持-提供了对新浪SAE平台和百度BAE平台的强力支持，具备“横跨性”和“平滑性”，支持本地化开发和调试以及部署切换，让你轻松过渡，打造全新的开发体验。
*  CLI支持-支持基于命令行的应用开发
*  RPC支持-提供包括PHPRpc、HProse、jsonRPC和Yar在内远程调用解决方案
*  MongoDb支持-提供NoSQL的支持
*  缓存支持-提供了包括文件、数据库、Memcache、Xcache、Redis等多种类型的缓存支持

## 安全性

框架在系统层面提供了众多的安全特性，确保你的网站和产品安全无忧。这些特性包括：

*  XSS安全防护

*  表单自动验证
*  强制数据类型转换
*  输入数据过滤
*  表单令牌验证
*  防SQL注入
*  图像上传检测

   ​

   ​

   ​

## 目录结构##

- index.php - 入口文件
- README.md - README文件
- composer.json - composer定义文件   
- Application - 应用目录/系统应用
  - Common - 公共的模块目录
  - Home - 前台网站模块
    - Common - 公共函数目录
    - Conf - 配置文件
    - Contriller
    - Model - 数据
    - View
    - index.html
  - Runtime
- Public - 资源文件目录/html-css-js-images
- ThinkPHP - 框架目录
  - Common - 核心公共函数目录
  - Conf - 核心配置目录
  - Language - 核心语音包目录
  - Library - 框架类目录
    - Think - 核心Think类库包目录
    - Behavior - 行为类库目录
    - Vendor - 等三方类库目录
    - …… - 更多类库目录
  - Mode - 框架应用模式目录
  - Tpl - 系统模板目录
  - LICENSE.txt - 框架授权协议文件
  - Logo.png - 框架Logo文件
  - README.txt - 框架README文件
  - thinkphp.php - 框架入口文件