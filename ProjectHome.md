**路由表信息将每24小时自动更新一次, 下载地址在: http://chnroutes-dl.appspot.com/**


**代码库将迁移到: [github](http://github.com/fivesheep/chnroutes)**



因为一些众所周知的原因, 来自中国大陆的网民想要访问非本国资源时总会那么的不方便, 这促使了海外vpn供应商在中国的繁荣. 使用海外vpn访问已经成为一些需要经常访问海外资源的中国网民的必要装备. 但通常这些vpn都是有流量限制的, 除此之外一些中国内部的资源也限制海外的ip访问.
本项目的就是提供一些启动脚本给vpn用户, 在vpn拨号之后修过路由表,让他们在使用vpn访问国外资源的同时, 能用非vpn线路高速访问本国资源.




[使用方法](http://code.google.com/p/chnroutes/wiki/Usage)


Due to well-known reasons, it's always inconvenient for Chinese netizens and foreigners who live in China to access information physically outside of China via internet. Timeouts and connection resets are the most common results you will get when you trying to visit websites that are hosted in other countries. That leads to the growth of a new business which is called climb-the-wall or crack-the-wall. That is to use some kind of technologies such as encrypted proxy and VPN to bypass censorship.
This project is created for those who uses VPN to combat censorship. It will generate some shell scripts to modify the routing table to split the chinese and non-chinese IPs. This gives VPN users the best experience by keeping domestic traffic efficient and only sending request through the VPN that need to.