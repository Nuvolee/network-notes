---
title: Web服务器模拟实验（eNSP）
date: 2026-04-29
tags:
  - 实训
  - 运维
keywords:
  - HTTP服务
  - 服务器搭建
---



# 🖥️ 拓扑设计
<img width="1062" height="546" alt="20264291" src="https://github.com/user-attachments/assets/e781b5f3-ecb2-482b-a5b6-e56df1fd99a0" />


# ⚙️ 配置说明

- 基础网络配置
|设备|IP|DNS|
|---|---|---|
|客户端|192.168.1.1|192.168.1.3|
|百度服务器|192.168.1.2|-|
|DNS服务器|192.168.1.3|-|


- 服务器功能配置
|设备|服务类型|配置|
|---|---|---|
|百度服务器|HTTPServer|启用HTTP服务，根目录：C:\Test|
|DNS服务器|DNSServer|www.baidu.com→192.168.1.2|



# 🔎测试与验证
客户端于HttpClient获取www.baidu.com
<img width="1101" height="764" alt="20264292" src="https://github.com/user-attachments/assets/332a6047-c4dc-4575-8b66-2831cce5d89d" />




