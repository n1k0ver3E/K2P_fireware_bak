# K2P_Fireware_bak K2P固件备份

### 0x00 备份一览

```
1 - K2P_V22.8.5.189.bin -- K2p降级的官版系统稳定版 固件
2 - breed
3 - openwrt -- 自用的openwrt_cc_v1.7.2系统固件，此版非纯净版，已预装酸酸乳，推荐下载16m
4 - ipks -- 自用的支持k2p的固件(ChinaDNS, DNS-forwarder, 酸酸及全部相关依赖)
5 - padavan -- 收集的一些稳定(yanglap)的老毛子固件，本人自用 hanwckfK2P_nano-5.0.trx
```

### 0x01 使用说明
0. 安装ipks需保证各固件版本彼此兼容，本机是A2版K2P，系统：``openwrt_cc_1.7.2``，可放心安装以上ipks。
1. 通过安装以上ipks并正确设置，可实现透明代理，配合dnsforwarder实现TCP协议DNS代理解析，实际使用效果比在终端进行Pac 白名单更加稳定。
2. 以上ipks 均有配置ipk和luci ipk, 请将两个ipk一并安装。

### 0x02 其他资源
1. [设置DNS转发实现ChinaDNS](https://github.com/aa65535/openwrt-chinadns/wiki/Use-DNS-Forwarder).
2. [Wiki: Luci-app-shadowsocks 设置及说明](https://github.com/shadowsocks/luci-app-shadowsocks/wiki)
3. 其他详细教程请访问恩山论坛。
