# 简OS启动盘制作工具

Deepin Boot Maker is a tool that helps user to create a bootable usb stick quick and easy, it is designed to support deepin install iso, but it works for all ubuntu live install iso too.

![screenshot](https://raw.githubusercontent.com/linuxdeepin/deepin-boot-maker/master/docs/deepin-boot-maker.png)

## 依赖

Deepin Boot Maker is designed to support Windows/Linux/Mac platforms. It has no external dependencies on Windows and Mac OS. On Linux, you need packages below:

```bash
#For release based on debian
sudo apt-get install p7zip-full mtools syslinux syslinux-common
```

官方支持平台：

- Deepin 2015

- Mac OSX 10.12

- Windows 7 32/64位、Windows 8 32/64位。

## 安装

- Official binary release

The only binary release is from Deepin OS iso for now. You can download iso from: https://www.deepin.org/original/deepin-boot-maker/. Or you can find binary file on the root of iso.

- 存储库安装

If you are deepin user, you can install Deepin Boot Maker from repository:

```bash
sudo apt-get install deepin-boot-maker
```

- 编译与安装

有关详细信息，请参阅[INSTALL](INSTALL.md)。

## Getting help

Any usage issues can ask for help via

* [Gitter](https://gitter.im/orgs/linuxdeepin/rooms)
* [IRC channel](https://webchat.freenode.net/?channels=deepin)
* [Forum](https://bbs.deepin.org)
* [WiKi](https://wiki.deepin.org/)

## Getting involved

We encourage you to report issues and contribute changes

* [开发者代码贡献指南](https://github.com/linuxdeepin/developer-center/wiki/Contribution-Guidelines-for-Developers) (中文)

## 协议

Deepin Boot Maker is licensed under [GPLv3](LICENSE).

## Credits and references

1. [UNetbootin](https://github.com/unetbootin/unetbootin): this projects is derived form unetbootin, but now there are big differences between them.
