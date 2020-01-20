---
layout: w
title: nginx windows部署vue
date: 2020-01-20 10:23:12
tags:
---

## niginx在windows下部署vue
1、打包vue项目 npm run build
2、将打包生成的dist文件夹拷贝到niginx按装目录下
3、修改nginx.conf配置文件，修改访问的根目录为dist
`location /｛  
	root dist;  
	index index.html index.htm;  
｝`
4、nginx命令启动服务
5、修改后使用nginx -s reload命令

