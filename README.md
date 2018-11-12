Shadowsocks
---
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/crayonxiaoxing/onekeyProxy/master/proxy/shadowsocks.sh && chmod +x shadowsocks.sh && ./shadowsocks.sh
```

MTProxy
---
``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/crayonxiaoxing/onekeyProxy/master/proxy/mt_proxy.sh && chmod +x mt_proxy.sh && ./mt_proxy.sh
```

Socks5 Install
---
```
yum -y install wget curl
wget https://raw.githubusercontent.com/crayonxiaoxing/onekeyProxy/master/socks5.sh;bash socks5.sh

socks5 安装/卸载  `socks5 {install|uninstall}`
socks5 用户 添加/删除/列出  `socks5 user {add|del|list}`
socks5 启动/停止/重启/查看状态  `socks5 {start|stop|restart|status}`
socks5 更新/查看信息  `socks5 {update|info}`



