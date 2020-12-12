---
title: Docker_Jekyll_Blog
published: true
---


### 1）获取Jekyll Docker
```
docker pull jekyll/jekyll
```
### 2）运行Docker，并设置端口映射
```
docker run -it -p 4000:4000 -v /Volumes/MacFile/Blog/:/srv/jekyll/ jekyll/jekyll:latest /bin/bash
```
/Volumes/MacFile/Blog/ 是存储Blog文件的本地目录
### 3）启动jekyll服务
```
jekyll server
```
在本地浏览器输入：127.0.0.1:4000 可访问Blog.


