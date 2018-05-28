---
title: 备忘-hexo命令
date: 2018-05-17 19:50:23
tags: hexo
toc: true
---

# hexo备忘录

个人博客管理工具 hexo 使用。有时长时间不用，会忘记怎么用，在这里简单记下！

首先，hexo已经安装过一次，整体环境放在github上，即使换电脑了，可以很快还原！

<!-- more -->

## 初始环境：

git上面，关于hexo共有三个库。

h-hexo_init 执行命令的仓库，可以运行最重要！有好的配置才更新上去，平时别去动他！！别搞得不能运行！！！

h-hexo_source 生成前的原始文件

qianyuqianxun.github.com 生成后的展示文件

## 常用命令如下：

可以将常用的放cmd工具里，然后放代码仓库(bitbacket)上

命令|备注|是否原生命令
-|-|-
cdhexo        |进入hexo主文件夹|N
hexo new ***  |新建博客|Y
hexo g        |生成博客|Y
hexo s        |本地服务启动，可以[预览](http://localhost:4000/)|Y
hexo d        |发布博客到github|Y
lshexo        |查看博客列表|N
cdblog        |进入博客文件夹|N

## Quick Start

Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)
