# MQTT3.1.1协议中文版

by [shirdonl](https://github.com/shirdonl)

## 文档地址

- [MQTT协议中文版](https://mcxiaoke.gitbooks.io/mqtt-cn/content/)
- [PDF和ePub下载](https://www.gitbook.com/book/mcxiaoke/mqtt-cn/details)
- [中文翻译项目](https://github.com/shirdonl/mqtt_cn)

## 概述

MQTT是一个客户端服务端架构的发布/订阅模式的消息传输协议。它的设计思想是轻巧、开放、简单、规范，易于实现。这些特点使得它对很多场景来说都是很好的选择，特别是对于受限的环境如机器与机器的通信（M2M）以及物联网环境（IoT）。

## 说明

>MQTT英文原版协议提供了Word格式和HTML格式，我翻译的时候用的Word文档，之前一直提供的是Word文档转换的HTML和PDF供浏览和下载，最近花时间整理了Markdown版本，可以更方便的分章节在线浏览了，转换为Markdown后部分表格的格式不太对，会逐步用图片代替。

## 目录

**发现任何翻译问题或格式问题欢迎提PR帮忙完善。**

- [说明](README.md)
- [前言](mqtt/00-Preface.md)
- [目录](mqtt/00-Contents.md)
- [第一章 - MQTT介绍](mqtt/01-Introduction.md)
- [第二章 – MQTT控制报文格式](mqtt/02-ControlPacketFormat.md)
- [第三章 – MQTT控制报文](mqtt/03-ControlPackets.md)
	- [3.1 CONNECT – 连接服务端](mqtt/0301-CONNECT.md)
	- [3.2 CONNACK – 确认连接请求](mqtt/0302-CONNACK.md)
	- [3.3 PUBLISH – 发布消息](mqtt/0303-PUBLISH.md)
	- [3.4 PUBACK –发布确认](mqtt/0304-PUBACK.md)
	- [3.5 PUBREC – 发布收到（QoS 2，第一步）](mqtt/0305-PUBREC.md)
	- [3.6 PUBREL – 发布释放（QoS 2，第二步）](mqtt/0306-PUBREL.md)
	- [3.7 PUBCOMP – 发布完成（QoS 2，第三步）](mqtt/0307-PUBCOMP.md)
	- [3.8 SUBSCRIBE - 订阅主题](mqtt/0308-SUBSCRIBE.md)
	- [3.9 SUBACK – 订阅确认](mqtt/0309-SUBACK.md)
	- [3.10 UNSUBSCRIBE –取消订阅](mqtt/0310-UNSUBSCRIBE.md)
	- [3.11 UNSUBACK – 取消订阅确认](mqtt/0311-UNSUBACK.md)
	- [3.12 PINGREQ – 心跳请求](mqtt/0312-PINGREQ.md)
	- [3.13 PINGRESP – 心跳响应](mqtt/0313-PINGRESP.md)
	- [3.14 DISCONNECT –断开连接](mqtt/0314-DISCONNECT.md)
- [第四章 – 操作行为](mqtt/04-OperationalBehavior.md)
- [第五章 – 安全](mqtt/05-Security.md)
- [第六章 – 使用WebSocket](mqtt/06-WebSocket.md)
- [第七章 – 一致性目标](mqtt/07-Conformance.md)
- [附录B - 强制性规范声明](mqtt/08-AppendixB.md)

------

## 许可协议

- [署名-非商业性使用-相同方式共享 4.0 国际](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

------

## 联系方式

* Blog: <http://www.shirdon.com>
* Github: <https://github.com/shirdonl>

## 开源项目

* A go library for TP-Link HS100 and HS110 WiFi smart plug: <https://github.com/shirdonl/TP-Link-HS110>

------


