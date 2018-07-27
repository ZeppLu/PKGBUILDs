PKGBUILDs
============

A collection of PKGBUILDs (along with other files needed by `makepkg`) written by myself (and for myself mainly).


shadowsocks-optimization
---------------

Optimize shadowsocks server on Linux, based on [this](https://shadowsocks.org/en/config/advanced.html) and [this](https://github.com/shadowsocks/shadowsocks/wiki/Optimizing-Shadowsocks). This package installs those `*.conf` files for you, and help you patch shadowsocks's `*.service` files (currently only `shadowsocks-libev-server@.service`, because that's all what I need).

