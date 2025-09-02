一、项目介绍

本项目为基于 Spring Boot + Vue 的民谣网站系统，分为 管理员（后台） 与 普通用户/游客两类角色。系统已实现的主要功能如下：

管理员（后台）
基本：登录、登出、修改密码、获取/修改个人信息（session/token 鉴权）
用户管理：分页查询、列表、查看详情、新增、修改、删除、重置密码
歌曲管理：后台分页/详情/新增/修改/删除
论坛管理：帖子分页/详情/新增/修改/删除
资讯/公告管理：CRUD、后台分页/详情
留言与歌曲留言管理：CRUD、后台分页/详情
收藏管理：收藏记录的查看与管理

账户：注册、登录、退出、密码重置
浏览：公开列表与详情（歌曲 、论坛 、资讯 、留言 ）
交互：前端新增（发帖、歌曲添加 、留言 等）、评论/留言、对内容点赞/踩
收藏：收藏/取消收藏歌曲
文件：头像/文件上传
前端体验：富文本编辑（发布/编辑帖子、资讯等）

二、项目技术
编程语言：Java 
后端框架：Spring Boot 2.2.2, Spring MVC,MyBatis-Plus / MyBatis,MySQL,Fastjson，Hutool, Apache Commons,
前端框架：Vue 2 + vue-router，Element UI，axios，vue-quill-editor（富文本），vue-cli

三、运行环境
JDK版本：1.8及以上都可以
操作系统：Windows7/10、MacOS
开发工具：IDEA、Ecplise、MyEclipse都可以
数据库: MySQL5.5/5.7/8.0版本都可以
npm版本：6.14.13及以上都可以
Redis版本：3.2.100及以上都可以


四、数据库配置文件
文件名：application.yml
编码类型：utf8

