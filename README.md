## centos7_greennet
本仓库是放置centos7上科学上网用到的一些脚本和配置文件.

### shadowsocks
1. `shadowsocks.sh`,来自[https://teddysun.com/342.html](https://teddysun.com/342.html)
2. myport使用示例:
将myport下载下来，增加可执行权限，然后移动到`/usr/local/sbin`目录。
```
增加端口:
myport add 4444

删除端口:
myport remove 4444
```

### ocserv
1. `ocserv-install-script-for-centos7.sh`来源[ocserv](https://github.com/travislee8964/Ocserv-install-script-for-CentOS-RHEL-7)
2. `my_no_route.txt` 我的不需要route，也即大部分国内ip.
3. `ocserv.conf`包含上面no route设置后的配置文件.

参考
1. [https://github.com/CNMan/ocserv-cn-no-route](https://github.com/CNMan/ocserv-cn-no-route)
2. [https://www.logcg.com/archives/1343.html](https://www.logcg.com/archives/1343.html)


### Cisco AnyConnect VPN
[下载](https://cnlic.com/share/client.html)
