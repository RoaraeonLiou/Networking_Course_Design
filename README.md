# Networking_Course_Design
### 项目功能
实现了某企业网络的规划设计，每个部门均归属于一个VLAN，所有部门包括会议室和领导办公室之间可以互相通信，并且除了会议室之外都可以与外网通信。由于研发部的计算机数多余所分配到的子网中的IP数，所以针对于研发部采用了专用IP地址，在公司路由器中实现了NAT技术，使得研发部可以与外部网络通信。除服务器之外，其他公司内部计算机都通过DHCP的方式动态获取IP地址。实现了DNS服务器、web服务器、FTP服务器和EMAIL服务器。在网络安全方面使用了防火墙技术、ACL技术和VPN技术。

### 实现方法
（1）使用Cisco Packet Tracer 6.2软件来实现网络拓扑图的连接与配置。

（2）使用VLAN技术实现VLAN的划分。

（3）使用RIP路由协议和默认网关，实现不同VLAN之间的通信。

（4）使用DHCP技术实现动态分配IP地址。

（5）使用NAT技术解决研发部IP地址不足的问题。

（6）使用ACL实现会议室对外部网络的访问控制。

（7）使用防火墙限制外部主机对内部网络的访问。

（8）使用VPN技术解决员工出差时需要访问内部网络的需求。

