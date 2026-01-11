Java期末大作业设计文档
小组成员：杨志炜、赵子航、邱柏豪
一.项目概述
此项目是基于springboot框架的web项目——健身房管理系统。

二.项目总体设计

1.设计结构
系统层次结构图如下：


主要功能如下：

管理员登录模块

会员管理模块

教练管理模块

课程管理模块

器材管理模块

物品遗失管理模块

商品管理模块

信息统计模块

2.涉及技术框架：

web框架：SpringBoot
数据库框架：Sping Data JPA
数据库：MySql
项目构建工具：Maven
前端模板：JSP
安全框架：Shiro
前端框架：BootStrap,Layui
数据图表：ECharts

3.本项目所用环境：

开发工具：IDEA
编程语言：JDK1.8,HTML,CSS,JS，jQuery
数据库：mysql


三.系统主要页面展示

登录界面


数据统计界面



会员列表界面


会员私教课程界面


普通课程列表界面


器材信息管理界面


物品遗失归还界面


商品列表界面



四．项目实施

1.环境搭建
JDK1.8
Maven仓库配置
IDEA
MySQL数据库与sql文件（gym.sql）

2.项目结构


3.项目应用运行
①本地数据库（MySQL)创建数据库（gym_db），运行gym.sql的sql代码，完成数据表结构及数据的创建与插入。
②在resource/application.properties中修改本地的信息（端口号；MySQL数据库的url、username和password）。
③运行GymMSApplication.java(springboot），运行成功后，在浏览器访问localhost:8090（端口号在②中配置）。
④访问网址后会进入登录界面（login.jsp）。管理员登录（账号：admin）（密码：admin123）。如果想添加管理员，可以在gym.sql中insert账号密码到adminuser表中。
⑤进入系统后可以操作各种功能，项目完成。

五．总结

此健身房管理系统基于springboot框架的web项目，我们完成了基本功能以及拓展功能的实现。在项目完成的过程中遇到i一些问题，我们通过小组讨论、ai协助、csdn资料浏览等解决了问题，最终成功部署运行此应用。
此项目让我们对springboot框架有了更深刻的理解，熟悉了其用法；并且学习了一些前端技术框架（BootStrap、Layui）、还有一个安全框架（Shiro）。
总体来说，这个项目是成功的，让我们更深刻领悟JavaWeb开发，在这方面有了一些进步。
