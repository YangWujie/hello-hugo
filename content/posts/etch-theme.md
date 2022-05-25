---
title: "Etch主题"
date: 2022-05-25T09:30:46+08:00
draft: false
author: 杨武杰
year: "2022"
month: "2022/05"
categories:
- 工具
tags:
- Hugo
---
用**git submodule**安装了Hugo主题etch。
<!--more-->
这样，这个试验网站已经有两个主题了。虽然Hugo只能生成静态网站，但是否可以在部署时用多个主题同时生成多套网页呢？感觉应该是可以的。

etch的汉化。在Hugo site主目录里创建名为i18n的文件夹，把themes/etch/i18n/en.toml拷贝到新创建的文件夹，然后翻译汉化即可。目前，这个文件名只能是en.toml。如果允许同时存在多个语言文件，然后能自动选择就好了。

不知道在github上部署时，git submodule会不会有问题？