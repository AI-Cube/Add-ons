# 智慧家庭立方: HiCloud

通过frp隧道，使局域网中的homeassistant可以通过公网访问。

## 关于

[frp](https://github.com/fatedier/frp/blob/master/README_zh.md)是一个可用于内网穿透的高性能的反向代理应用。

本Add-on可以连接到frp服务，实现http或者tcp的反向代理。

缺省配置对应于一台公网上的测试服务器，仅供测试。如果你需要稳定的反向代理服务，需要在公网上搭建自己的frps服务。