---
title: Git操作
date: 2022-11-19 19:26:11
update: 2022-11-20 10:30:33
tags: git
description: 学习Git的一些常用操作
mathjax: false
---

## Hello, Git

I'm learning git now!

## git 本地操作

`git init` 在当前文件夹创建git仓库

`git add . ` 添加所有工作区文件到缓冲区

`git status` 获取仓库状态

`git log` 查看最近提交日志

`git commit -m "输入你的备注，关于这次提交的信息"`

## git 远程操作

`git push origin main`  推送当地git库到github

`git remote -v`  查看当前本地库关联的远程库信息

`git clone "远程仓库地址"`  将远程仓库克隆到当前文件夹

## 一键上传

git add .

git commit -m 'revise blog'

git push origin main

## 本地调试Hexo (和 Git 无关)

`hexo clean` 

`hexo g`

`hexo s`

## 遇到的坑

### 1.	VPN 引发的问题

`kex_exchange_identification: Connection closed by remote host Connection closed by 127.0.0.1 port 22 fatal: Could not read from remote repository.`  

解决方法：

**关掉 VPN**
