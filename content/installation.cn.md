---
title: 安装方法
disableToc: false
---

本节以 TeX Live 2018 为例，介绍如何通过命令行或者包管理工具安装模板（包）。

## 命令行方式安装

以管理员权限打开命令行，在命令行输入下面命令即可安装 elegantpaper 模板。

```shell
tlmgr option repository http://mirror.ctan.org/systems/texlive/tlnet
tlmgr install elegantpaper
```

升级和卸载分别使用

```shell
tlmgr update elegantpaper
tlmgr uninstall elegantpaper 
```

## 包管理工具方式安装

在 Windows 里面搜索 tlmgr，找到 TeX Live Manager 并打开：

<center><img src="/image/tlmgr.png" width="600"></center>

然后通过菜单 tlmgr 选择 __Load standard net repository: http://mirror.ctan.org/systems/texlive/tlnet__：

<center><img src="/image/tlmgr-1.png" width="600"></center>

然后在__匹配__框内输入包的名字，比如 `elegantpaper`，在搜索结果中勾选需要安装/更新/卸载的包：

<center><img src="/image/tlmgr-2.png" width="600"></center>


