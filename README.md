# TP-Link Archer C7 v2 firmware with 9k MTU support

OpenWrt has troubles setting MTU over 4070 on devices targeting ar71xx platform.

See
* https://dev.archive.openwrt.org/ticket/18296
* https://forum.openwrt.org/t/lede-on-archer-c7-jumbo-frame-not-working/1339

This build contains possible fix for the issue. The source code can be found here: https://github.com/alexbat98/openwrt/tree/ar8327n_jumbo
