---
layout: “w
title: spring boot学习
date: 2020-01-19 18:19:15
tags:
---

## spring boot学习

### spring boot由来
传统的EJB标准配置繁多，过于臃肿。需要web容器调用EJB容器的方式，造成性能不佳。
基于此出现了spring框架，具有很多优点：
1、IOC，降低资源耦合，侵入性降低。
2、AOP，通过配置可以减少重复性代码，能够更加专注于业务代码开发。
整合了其他流行的框架，简化了主流技术的使用。

在spring的基础上，通过注解方式简化了spring框架的开发，开发了spring boot框架。其优点如下：
1、创建独立的spring应用程序。
2、嵌入tomcat、Jetty，无需部署war文件。
3、约定大于配置，尽可能自动配置，也提供了方便修改默认配置的功能。
4、通过maven方式进行包管理和项目构建。

### 开发环境
Eclipse可以安装spring Tool Suite（STS）插件创建项目
IntelliJ Idea 可以通过Spring Initializr创建项目


