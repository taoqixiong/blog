title: Linux 开机挂载硬盘
author: 梓喵
tags:
  - Linux
  - 折腾
categories: []
date: 2017-05-26 00:33:00
---
在 /etc/fstab 中添加
```bash
/dev/sda1 /data1 ext4 defaults 0 0
```