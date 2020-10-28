---
title: TCP/IP
date: 2020-10-21 13:17
tags: 
- 计算机网络
---

*TCP/IP就是IP、TCP、HTTP等协议的集合。是由IETF所推进的一种协议。*
协议就是计算机之间约定好的用于通信的方式，如同同学之间用相同的语言才能沟通一个道理。不同计算机之间通过协议传递信息，同一计算机的不同分层之间通过接口传递信息。

关于几个计算机网络层的理解：
以发送电子邮件为例
+ 应用层，在写完电子邮件并且选定收件人这个过程就是应用层
+ 表示层，不同邮箱软件之间关于数据格式的处理就是表示层（把特定的数据格式转为网络的通用格式）
+ 会话层，假定要发送多封邮件，是建立一次链接发送一封邮件然后断开重复或者是一次性把所有邮件发出去，是会话层决定的。
+ 传输层，在两个主机之间创建逻辑上的通信链接是传输层的主要作用。*会话层决定的是建立和断开链接的时机，而传输层进行的是实际的建立和断开链接。*如果数据没有送达，传输层会负责进行重发。
+ 网络层，根据目的地址将数据从发送端发送到接收端。
+ 数据链路层，在传输媒介互连的设备之间进行数据处理。数据链路层只负责发送一个分段内的数据。
+ 物理层，将数据的0，1转换为物哩信息传输给物哩的传输介质。