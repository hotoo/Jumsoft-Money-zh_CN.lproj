
# Jumsoft Money 简体中文语言包

> 提醒：安装前请先确定 Money 版本，版本不同 Layout 可能也不相同，强制安装可能会导致选单消失。
> 如果安装导致异常，卸载即可。
>
> 目前最新版简体中文语言包是 v4.5.4 版。

## 安装(Install)

### 命令行安装方式

```
$ sudo git clone https://github.com/hotoo/Jumsoft-Money-zh_CN.lproj.git /Applications/Money.app/Contents/Resources/zh_CN.lproj
```

### 手动安装方式

* 确定已安装 Money 对应版本，在「应用程序」里邮件选中 Money 并选择「显示包内容」，
  打开「Contents」＞「Resources」目录。
* （或在 Finder 选择「前往」＞「前往文件夹」＞「/Applications/Money.app/Contents/Resources」）
* 新建「zh_CN.lproj」文件夹（如果文件夹不存在）
* 将此项目所有的文件拷贝到「zh_CN.lproj」中

## 卸载(Uninstall)

### 命令行卸载

```
$ sudo rm -rf /Applications/Money.app/Contents/Resources/zh_CN.lproj
```

### 手动卸载

删除『/Applications/Money.app/Contents/Resources/zh_CN.lproj』目录即可。

## 使用(Usage)

安装后，重新启动 Money.app 即可生效。
