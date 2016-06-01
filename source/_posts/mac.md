title: UNIX 好用滴命令
categories:
- unix
tags:
- unix
- mac
---

# MAC 

**禁止连接wifi自动弹窗认证窗口**

```
sudo defaults write /Library/Preferences/SystemConfiguration/com.apple.captive.control Active -boolean false
```

**连续按键，快速连续触发**

我们在打命令或者编辑文本滴时候，经常会用到方向键，linux 下方向键是非常快滴，运行如下命令，就可以让方向键移动移动速度很快了~

```
defaults write NSGlobalDomain KeyRepeat -int 3
```


