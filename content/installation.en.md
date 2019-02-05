---
title: Installation
disableToc: true
---

In this section, we will introduce the installation methods through cmd line or package manager of TeX Live 2018.

## Cmd Line Method

Run command line as administrator, the installation commands is 

```shell
tlmgr option repository http://mirror.ctan.org/systems/texlive/tlnet
tlmgr install elegantpaper
```

If you want to update or uninstall package, you can use 

```shell
tlmgr update elegantpaper
tlmgr uninstall elegantpaper 
```

## Package Mananger Method

Search tlmgr in windows, and open TeX Live Manager,

<center><img src="/image/tlmgr.png" width="600"></center>

click tlmgr and choose __Load standard net repository: http://mirror.ctan.org/systems/texlive/tlnet__ ：

<center><img src="/image/tlmgr-1.png" width="600"></center>

type the package name in the blank, and select the package you want to install/update/uninstall and click the action you wish.

<center><img src="/image/tlmgr-paper.png" width="600"></center>

Complete.

