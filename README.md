* [English](#chromium-with-ssl-vpn)
* [简体中文](#chromium浏览器)

# Chromium浏览器

直接内置翻墙代理的Google Chromium浏览器。

![](screenshot.png)

最新版本：[73.0.3683.67](https://github.com/jjqqkk/chromium/releases/tag/73.0.3683.67)

[Chromium](https://github.com/chromium/chromium)是Google Chrome浏览器的开源版本，两者共享大部分代码。新的开发和改进先通过Chromium项目完成，大约通过6周测试后再由Google官方发布，因此Chromium是Chrome先行版本。

## Windows (10/8/7)

[内置VPN版本](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-windows-73.0.3683.67.zip)

[备用下载地址](http://167.99.163.129/Chromium-windows-73.0.3683.67.zip)

[原始版本，可安装插件](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-windows-novpn.zip)

### 使用方法

下载zip文件后解压缩，从解压后目录里运行**chromium.exe**。

## Mac

[内置VPN版本](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-mac-73.0.3683.67.zip)

[备用下载地址](http://167.99.163.129/Chromium-mac-73.0.3683.67.zip)

[原始版本，可安装插件](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-mac-novpn.zip)

### 使用方法

下载zip文件后解压缩，直接得到App。由于签名问题，首次运行，按住Control点图标，从菜单里打开App。之后直接双击图标即可运行。


## 如何解决Windows版本崩溃？
[issue #78](https://github.com/jjqqkk/chromium/issues/78) Thanks [leoxxnet](https://github.com/leoxxnet)





# Chromium with SSL VPN

Chromium with SSL VPN lets you unblock websites directly in the browser.

![](screenshot.png)

Latest version: [73.0.3683.67](https://github.com/jjqqkk/chromium/releases/tag/73.0.3683.67)

Chromium is the open source project behind the Google Chrome browser. It is a fully functional browser and also widely used by other parties to create their own browsers. Many vendors use the code in a similar manner as Google, while others simply build it as-is and release browsers with the Chromium name.

This build takes advantage of the [VPN](https://developer.chrome.com/extensions/vpnProvider) and [Proxy](https://developer.chrome.com/extensions/proxy) API developed by Google. 

## Windows 10/8/7

[Built-in VPN](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-windows-73.0.3683.67.zip)

[Backup download site](http://167.99.163.129/Chromium-windows-73.0.3683.67.zip)

[Original Chromium](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-windows-novpn.zip)

## macOS

[Built-in VPN](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-mac-73.0.3683.67.zip)

[Backup download site](http://167.99.163.129/Chromium-mac-73.0.3683.67.zip)

[Original Chromium](https://github.com/jjqqkk/chromium/releases/download/73.0.3683.67/Chromium-mac-novpn.zip)


## How to upgrade Chromium?

We will follow [Google's release schedule](https://chromiumdash.appspot.com/schedule) and post the binaries on the [releases](https://github.com/jjqqkk/chromium/releases) page.

Users are free to download newer versions. There will be no conflict to having two Chromium on the same computer.

## How to uninstall Chromium?

Simply delete the folder on Windows, or the app on macOS.
