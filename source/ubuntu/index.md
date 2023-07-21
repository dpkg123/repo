---
title: Ubuntu dde repo
date: 2023-07-20 23:56:26
---
# 这是一个ubuntu dde repo
### 如何使用
如果系统是ubuntu20.04,输入
```bash
$ sudo  echo 'deb https://repo-pied-three.vercel.app/ubuntu focal main' > /etc/apt/sources.list.d/1.list
```
如果是ubuntu22.0,输入
```bash
$ sudo  echo 'deb https://repo-pied-three.vercel.app/ubuntu jammy main' > /etc/apt/sources.list.d/1.list
```
后执行
```bash
$ sudo apt update
```
本仓库支持`amd64,arm64`架构
