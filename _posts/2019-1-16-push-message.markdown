---
layout:     post
title:      "使用adb导出手机崩溃日志"
subtitle:   " \"adb的使用\""
date:       2019-01-16 15:00:00
author:     "Lanxiaofan"
catalog: true
tags:
    - Android
    - adb导出手机崩溃日志
---


## 使用adb导出手机崩溃日志

* 确保手机连接上电脑 <br>
* 键盘上按下window+R键，输入cmd，打开dos控制窗口 <br>
* dos窗口下输入cd data/anr  <br> 进入手机目录如下（注意不要使用data/data，进入其他目录，因为直接操作data/data目录下的一些文件需要手机root权限），输入完成后回车后如下
![](/img/in-post/post-20190116-push-message.png)
最后导出traces.txt文件至一个目录下，这里是d:/app目录（注意接下来的操作需要返回dos主目录下C:\ Users\XX，输入下面的命令） <br>
* adb   pull   /data/anr/traces.txt   d:/app <br><br>

如果仍然失败可以使用chmod   777   /data/data更改权限后再重复以上操作

---



