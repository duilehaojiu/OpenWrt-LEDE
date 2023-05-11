<div align="center">
  <h1>OpenWrt-LEDE</h1>
树莓派3B+/Raspberry Pi 3B+的基于Lean编译的OpenWrt/LEDE固件，固件基本纯净自用同时也欢迎大家试用。
</div>

***
![image](https://github.com/duilehaojiu/OpenWrt-LEDE/assets/114590024/d3f66a27-c924-47d6-9dd3-762517c9263e)

## 说明
- 固件来源：本地自编译于[Lean的源码仓库](https://github.com/coolsnowwolf/lede)
- 固件版本：OpenWrt R23.5.1 | 内核版本：5.15.110
- 固件默认开启WiFi，overlay大小为1.5G请选择合适大小的储存卡刷写固件~~现在应该很少有低于4G的储存卡吧~~
- 固件默认管理地址：`10.0.0.1`**如无法进入管理地址**请尝试`192.168.1.1`
- 默认用户：`root`默认密码：`password`
## 固件内容
- 固件内带有iPhoneUSB共享网络驱动(个人需求)，无安卓USB共享网络驱动，如有需求请自行安装。
- 固件内留存的插件仅有：磁盘管理插件DiskMan、FTP服务插件、动态DNS插件
- 固件编译后带Argon主题，但与常见的Argon主题有所差别可能是由于主题版本过低，可以自行到[Argon源码仓库下载](https://github.com/jerrykuku/luci-theme-argon/releases/tag/v1.7.3)更新:[下载地址](https://github.com/jerrykuku/luci-theme-argon/releases/tag/v1.7.3)**版本号请选择1.7.3**
- Argon主题设置插件请下载安装0.8版本：<https://github.com/jerrykuku/luci-app-argon-config/releases/tag/v0.8-beta>
- 不知道何种原因最新版本的Argon主题它的自定义主题设置插件argon-config不会生效，所以选择这两个版本以求同时生效，如不使用主题设置插件可选择最新Argon主题安装。
## 注意
- OpenClash、PassWall请按照官方仓库要求自行安装依赖
- PassWall[下载](https://github.com/xiaorouji/openwrt-passwall/releases)
下载-a53.zip解压后安装，然后再安装插件与汉化包
- OpenClash[下载](https://github.com/vernesong/OpenClash/releases)
