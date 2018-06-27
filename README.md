# shadowsocks-install
搬运秋水逸冰大神的SS install
## centos 7
### 安装

```bash
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-libev.sh
chmod +x shadowsocks-libev.sh
./shadowsocks-libev.sh
```

> 安装过程中会提示配置端口、密码、加密方式。

### 卸载

```bash
./shadowsocks-libev.sh uninstall
```

### 控制

```bash
/etc/init.d/shadowsocks start  # 启动
/etc/init.d/shadowsocks stop  # 停止
/etc/init.d/shadowsocks restart  # 重启
/etc/init.d/shadowsocks status # 查看状态
```
