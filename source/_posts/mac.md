title: UNIX 好用滴命令
categories:
- unix
tags:
- unix
- mac
---

# MAC 

禁止连接wifi自动弹窗认证窗口

```
sudo defaults write /Library/Preferences/SystemConfiguration/com.apple.captive.control Active -boolean false
```