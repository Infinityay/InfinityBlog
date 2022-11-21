---
title: Hexo的折腾之路
date: 2022-11-21 19:38:45
updated: 2022-11-21 20:15:55
tags: Hexo
description: 记录了本站的建站过程与不断debug，updated的折腾之路
---

## 不正确的日期显示

**问题：**用 Netlify 实现部署网站的时候，网站上所有博客显示的更新日期都为最近一次commit的时间。由于是云函数部署，所有的文章的更新时间都会改变，目前只能通过为文章添加`updated`字段再提交才能避免这种情况。

解决方法：在 `YAML fronter matter` 上加入 `updated`字段

**参考链接：**

[hexo自动更新文章修改时间 - yyyz - 博客园 (cnblogs.com)](https://www.cnblogs.com/yyyzyyyz/p/15792199.html)