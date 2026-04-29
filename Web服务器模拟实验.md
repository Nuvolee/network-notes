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
| 设备  | IP地址 | DNS |
|---|---|---|
| 客户端 | 192.168.1.1 | 192.168.1.3 |
| 百度服务器  | 192.168.1.2 | 无 |
| DNS服务器 | 192.168.1.3 | 无 |


- 服务器功能配置
| 设备 | 服务类型 | 配置内容 |
|---|---|---|
| 百度服务器  | HTTP Server | 启用HTTP服务，网站根目录：C:\Test（存放网页文件）|
| DNS服务器 | DNS Server  | 域名：www.baidu.com → 192.168.1.2 |




# 测试与验证
客户端于HttpClient获取www.baidu.com
<img width="1101" height="764" alt="20264292" src="https://github.com/user-attachments/assets/332a6047-c4dc-4575-8b66-2831cce5d89d" />




