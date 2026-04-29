---
title: 网络通信基础
date: 2026-04-21
category: eNSP实训
tags:
  - 实训
  - 运维
keywords:
  - eNSP基础命令
---

# 网络拓扑
<img width="525" height="345" alt="20264211" src="https://github.com/user-attachments/assets/238313ef-cba9-4879-9c50-20370962959a" />

- 1.修改R1名称并配置IP地址。
- 2.修改R2名称并配置IP地址。
- 3.互Ping



# 配置实现

- R1
```
  system-view
  undo info enable
  sysname R1

  int g0/0/1
  ip add 10.1.1.1 24
```

- R2
```
  system-view
  undo info enable
  sysname R2

  int g0/0/0
  ip add 10.1.1.2 24
```


# 结果验证
<img width="1194" height="831" alt="20264212" src="https://github.com/user-attachments/assets/b1081c48-8ec4-4703-b1e8-77235bce24c9" />
<img width="1194" height="831" alt="20264213" src="https://github.com/user-attachments/assets/238168e4-4367-4cb5-92e1-8cc60f11ae36" />
