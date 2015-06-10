# DDPush

## DDPush是什么

DDPush (Dimension Door Push)，任意门推送，是一款开源免费的单机千万级实时信息推送服务器，使用Java语言开发，具有简单、稳定、高性能、高容量等特点，适用于互联网、移动互联网、物联网、Android、智能设备、硬件设备等各种环境。

## DDPush可以做什么

### 移动互联网信息推送
DDPush可实时推送信息到各种Android、Windows等手机和平板（即“透传”），并支持双向通信。DDPush支持自定义信息，信息的格式和内容可由开发者自行定义
### IM实时消息系统核心组件
通过集成DDPush，可以开发各种IM实时消息系统，例如：聊天系统、社交App等。
### 物联网设备控制与交互
DDPush可作为一个实时控制中心，控制物联网中的各种硬件设备（硬件需支持网络通信），与之双向通信。

## DDPush有什么优势

### 开源、免费
DDPush采用Apache License Version 2.0开源协议，可放心使用，只要您保留其许可证信息。
### 容量高，速度快，要求低
DDPush在线部分主要采用UDP协议（同时支持TCP协议），支撑1000万终端在线的服务器，最少只需要4G内存（不考虑变长自定义信息的情况下），单个主流双核CPU使用率低于75%。即：一部普通PC台式机的配置。
DDPush推送部分采取TCP协议和Java NIO非阻塞网络技术，普通PC可支持至少数千台应用服务器同时长连接推送信息到终端，每秒推送信息的速度在1万条以上
### 终端设备流量少，省电
采用DDPush，智能手机等终端设备在线一个月（空载的情况下），只需几百KB的上载流量，下载流量甚至可调节到为零。
DDPush提供的Android手机App示例demo，连续在线48小时耗电少于0.5 mAh（使用2G网络GPRS连接，经360省电王测试  >>>详情）

## DDPush基于什么技术

DDPush基于自有的二进制网络传输协议（基于TCP和UDP），因此客户端可以支持各种类型的终端设备，包括各种智能手机、平板、智能设备、物联网硬件，和各种终端操作系统（包括: Android, Windows, Linux等）。
DDPush使用Java语言开发，因此服务端可运行在各种操作系统和服务器上。
![DDPush](http://jsbd.github.io/images/ddpush.jpg)

---

## 项目由来
项目和文档来自[DDPush官网](http://www.ddpush.net/)，之前和DDPush作者联系建议将项目迁移到Github上无果（作者本人很低调，没有这个打算，接下来So~~~~），个人觉得DDPush项目很优秀，遂决定将作者官网DDPush相关的资料迁移此处，希望能帮助跟我一样喜欢这个项目的开发者。

## 项目计划
1.继续保持原作者发布项目的风格，文档与作者官网保持同步，定期更新....（需要众多DDPush爱好者的支持和整理）

2.欢迎大家提ISSUE，一起来完善强大这个项目，开发更多的功能。
