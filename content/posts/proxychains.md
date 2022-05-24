---
title: "Linux命令行代理ProxyChains"
date: 2022-05-23T17:08:33+08:00
draft: false
author: 杨武杰
year: "2022"
month: "2022/05"
categories:
- 工具
tags:
- Linux
- 代理
- 命令行
- ProxyChains
---
ProxyChains是Linux下的命令行代理工具，支持HTTP、 SOCKS4和SOCKS5类型的代理服务器，可配置多个代理。
<!--more-->
[proxychains](https://github.com/rofl0r/proxychains-ng/) 通过一个预先装载的动态库(dlsym(), LD_PRELOAD)截获动态链接的网络函数，并将其重定向到代理服务器。它仅支持TCP(不支持UDP和ICMP)。

在ubuntu下，ProxyChains 有两个版本：proxychains和proxychains4，建议使用proxychains4。

安装后，配置很简单，可参考 **/etc/proxychains4.conf**。

