# jjapps
what's JJ Apps

jjapps是我的个人全套微服务

包含：

- mysite 我的个人主页网站
- mgek 我的项目介绍网站
- blog 我的个人博客
- mgek doc 我的个人项目在线文档
- resume 我的个人简历
- jjservice 微服务管理页
- jjgo 统一化的api接口
- jjmail 邮件处理服务
- jjalarm 服务监控报警程序
- jjbox 代替ftp的多协议文件存储服务
- jjblog 博客一键部署服务
- soblogd 博客数据库迁移工具
- pan 个人云盘的python实现
- jjcli 终端工具用于管理微服务
- 其他正在开发中

这些服务使用不同语言编写 彼此依赖共同构成我的个人服务。

## mysite

我的个人主页

主要由python html css实现，上面包含了我的个人简介，我的博客，相册，视频vlog，想法，留言板等，记录着我的生活。

地址：[renj.io](http://renj.io)

## mgek

用来展示我的个人项目的网站，现在可能新的项目直接放在github了，但是这个网站应该上的项目介绍应该更为详细直观

地址：[mgek](http://mgek.cc)

## mgek doc

独立的个人在线文档，基于marked渲染技术，方便md文档的在线查看

地址：[mgek doc](http://doc.mgek.cc)

## resume

我的个人简历

除了找工作用到了其他时候也没人看

地址：[resume](http://me.renj.io)

## jj系应用

## jjservice

集成化的网页端微服务管理页面，用于管理所有的微服务

地址：[jjservice](http://app.renj.io)

## jjgo

理想是集成所有服务的api接口 构造rest接口服务。现在看来实现的不够完全，仅集成了jjmail jjbox 服务

地址：[jjgo](http://api.renj.io)

## jjmail

邮件处理服务，主要用于发送订阅类和报警类邮件

## jjbox

一个支持ftp http 协议的云存储服务

开发中

## jjalarm

定时扫描报警服务，主要用于监控微服务的状态，监控ssh等端口的异常登陆

## jjblog

一键博客部署程序

它不是一个静态博客生成工具，而是一个基于md文件的动态博客

使用rest接口和前端页面交互，支持快捷的博客文章部署，文章搜索，标签分类，留言，文字统计，访问统计等，详情请见github