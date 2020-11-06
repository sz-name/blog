---
layout:     post
title:      nginx 教程
subtitle:   centos7  linux nginx
date:       2020-04-8
author:     qxkbwl
header-img: img/post-bg-ios9-web.jpg
catalog: 	 true
tags:
    - centos7
    - linux
    - linux服务
    - centos
    - 服务管理
    - nginx
---
>nginx

# nginx.conf
* worker_processes  #进程数
* worker_connections    #连接数
* sendfile  #数据优化，直接走内核
* keepalive_timeout #长连接超时时间
* gzip #压缩数据，但是cpu会提升
* 