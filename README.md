[English](README_en.md)

# JJQQKK上网助手

JJQQKK上网助手通过两种方式科学上网：

* 自带VPN，启动之后加密所有网络活动
* 集成开发版Chrome浏览器（Chromium），内置VPN代理

JJQQKK支持Windows和macOS。

操作系统版本要求：

- Windows: 32/64位的Windows 10/8/7
- macOS: 最低要求10.12


## 下载JJQQKK

### Windows安装包

[下载地址一](http://185.44.107.177/28.msi)

[下载地址二](http://5.1.70.141/28.msi)

运行msi安装程序，安装之后双击桌面图标，启动程序。

首次使用，请务必安装OpenVPN驱动。每个步骤都采用默认设置即可。

![](images/windows-install-driver.png)

JJQQKK每次启动时会自动下载最新版Chromium浏览器。

![](images/windows-getting-chrome.png)

通过桌面任务栏图标操作JJQQKK。

![](images/windows-tray.png)


### macOS安装包

[下载地址一](http://185.44.107.177/28.pkg)

[下载地址二](http://5.1.70.141/28.pkg)


macOS用户安装pkg之后，系统自动运行JJQQKK，通过顶端任务栏图标使用JJQQKK。

![](images/mac-icon.png)



## 常见问题

**无法安装插件**

由于内置的代理组件无法完美兼容Chrome Extension，这款浏览器屏蔽了插件系统，以防止安装插件之后彻底毁坏代理能力。未来会有其他解决方案。

**无法登录Google和使用同步功能**

出于安全考虑，Chromium没有配置Google API，所以无法像Chrome一样登录浏览器。打开浏览器时会提示"missing API key"。

**是否提供64位Windows版本**

Windows版本Chromium默认使用32位编译，完美支持所有32位和64位系统，不存在兼容性问题。32位浏览器运行文件更小。所以如果没有功能方面的明显差异，只提供32位Windows浏览器。


## 避免失联

电邮：hi@jjqqkk.icu

可通过电邮获得最新软件下载地址。


## 拍照分享

![](images/readme.png)