# TCP/IP协议 
## 什么是TCP/IP 
- TCP/IP是因特网的通信协议。
## TCP/IP协议的应用
- 浏览器和服务器
- E-Mail
- 因特网地址
## TCP/IP协议
- TCP (传输控制协议) - 应用程序之间通信
- UDP (用户数据报协议) - 应用程序之间的简单通信
- IP (网际协议) - 计算机之间的通信
- ICMP (因特网消息控制协议) - 针对错误和状态
- DHCP (动态主机配置协议) - 针对动态寻址
## TCP使用固定链接
- 当应用程序希望通过 TCP 与另一个应用程序通信时，它会发送一个通信请求。这个请求必须被送到一个*确切的地址*。
- TCP 将在两个应用程序之间建立一个全双工 (full-duplex) 的通信，这个全双工的通信将占用两个计算机之间的通信线路，直到它被一方或双方关闭为止
## IP协议
- IP是在TCP/IP协议中网络层的主要协议，任务是仅仅根据源主机和目的主机的地址传送数据
> IP 是无连接的。IP 用于计算机之间的通信。
> IP 是无连接的通信协议。它不会占用两个正在通信的计算机之间的通信线路。这样，IP 就降低了对网络线路的需求。每条线可以同时满足许多不同的计算机> 之间的通信需要。
> 通过 IP，消息（或者其他数据）被分割为小的独立的包，并通过因特网在计算机之间传送。
> IP 负责将每个包路由至它的目的地。

> IP 路由器
> 当一个 IP 包从一台计算机被发送，它会到达一个 IP 路由器。
> IP 路由器负责将这个包路由至它的目的地，直接地或者通过其他的路由器。
> 在一个相同的通信中，一个包所经由的路径可能会和其他的包不同。而路由器负责根据通信量、网络中的错误或者其他参数来进行正确地寻址。

##TCP/IP相互协作
- TCP 和 IP 在一起协同工作。
- TCP 负责应用软件（比如您的浏览器）和网络软件之间的通信。
- IP 负责计算机之间的通信。
- TCP 负责将数据分割并装入 IP 包，然后在它们到达的时候重新组合它们。
- IP 负责将包发送至接受者。
## TCP/IP 寻址
- TCP/IP 使用 32 个比特或者 4 组 0 到 255 之间的数字来为计算机编址。
## IP地址
- 每个计算机必须有一个 IP 地址才能够连入因特网。
- 每个 IP 包必须有一个地址才能够发送到另一台计算机。
### IP 地址包含 4 组数字
- TCP/IP 使用 4 组数字来为计算机编址。每个计算机必须有一个唯一的 4 组数字的地址。
- 每组数字必须在 0 到 255 之间，并由点号隔开，比如：192.168.1.60。
- 11/21/2017 7:15:37 PM 
