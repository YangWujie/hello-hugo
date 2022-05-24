---
title: "Hugo的评论系统"
date: 2022-05-24T10:14:39+08:00
draft: false
author: 杨武杰
year: "2022"
month: "2022/05"
categories:
- 工具
tags:
- hugo
- disqus
---
Hugo内建了Disqus支持，但Disqus被屏蔽了。
<!--more-->
[Hugo文档](https://gohugo.io/content-management/comments/)给出了一些替代方案，对我这样的穷人来说，[Utterances](https://utteranc.es/)似乎较为可行。

根据Utterances的文档，测试过程很顺利，评论显示出来了。不过Utterances显示的是英文，和我的中文网站有点不搭调。在搜索解决方案的过程中，发现了一个更活跃，似乎更合乎我的需要的一个开源项目[giscus](https://giscus.app/zh-CN)。从Utterances向giscus迁移的理由可参看[Moving from utterances to giscus](https://shipit.dev/posts/from-utterances-to-giscus.html)。
