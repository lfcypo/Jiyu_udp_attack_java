# 极域电子教室数据包攻击脚本Java实现

### gitee项目地址：https://gitee.com/adminhuang-lfc/Jiyu_udp_attack_java

#### 介绍
极域电子教室数据包(udp)重放攻击的 **java实现** 

#### 软件架构
zuluJDK1.8

#### 安装教程

这是一个java类 内部已经定义好了方法 您可以直接在您的项目中使用<br>
同时提供两个简化版的py代码，在/python文件夹里

#### 使用说明

1.  getLocalIp() ｜获取本地ip<br>
2.  jiyuUdpSendCmd    ｜发送命令(目标ip， 目标监听端口， 要发送的命令)<br>
3.  jiyuUdpSendMsg    ｜发送消息(目标ip， 目标监听端口， 要发送的消息)<br>
4.  jiyuUdpSendShutdown           ｜远程关机(目标ip， 目标监听端口)<br>
5.  jiyuUdpSendReboot             ｜远程重启(目标ip， 目标监听端口)<br>
6.  jiyuUdpSendBroken    ｜远程使对方电脑崩溃(目标ip， 目标监听端口, 验证) 其中最后一个参数需传入true才可执行<br>
（第二到第五个方法运行完毕后都会返回一个布尔类型，true为执行成功，false为执行失败）

#### 致谢

1.  ht0Ruial    ｜大佬提供的python代码与思路   https://github.com/ht0Ruial/Jiyu_udp_attack<br>
2.  Huang       ｜java代码的实现<br>
3.  Hu          ｜在背后给我很大的支持<br>


#### TODO

1.  实现自动获取极域的监听端口
2.  用java写一个界面

#### 免责声明
使用本开源项目中的任何文件造成的任何不良后果由使用者承担，与本开源项目作者及代码托管平台无关

