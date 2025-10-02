---
title: 設定「Application Appearance」
nav_order: 7040
has_children: false
parent: 如何
---


# 設定「Application Appearance」




## 執行指令

舉例如下：

``` sh

gsettings set org.gnome.desktop.interface gtk-theme 'Arc-Dark'

gsettings set org.gnome.desktop.interface icon-theme 'Papirus-Dark'

gsettings set org.gnome.desktop.interface cursor-theme 'breeze_cursors'

```


## 圖形使用者介面操作

可以在「桌面」按下「滑鼠右鍵」，會出現一個選單，

其中有兩個選項如下：

* Change wallpaper...
* Desktop appearance...

選擇「`Desktop appearance...`」，就會出現一個「設定程式」。

也就是透過「`cosmic-settings appearance`」這個「圖形使用者介面程式」來操作

``` sh
cosmic-settings appearance
```

> 執行「`grep '^Exec=' /usr/share/applications/com.system76.CosmicSettings.Appearance.desktop`」可以找到上面的指令。


> 若是直接啟動「`cosmic-settings`」，則是要切換到分頁「`System Settings / Desktop / Appearance`」，其中有一個項目「`Icons and toolkit theming`」。




## 如何探索

執行

``` sh
gsettings list-recursively | grep theme
```

顯示

```
org.freedesktop.ibus.panel custom-theme 'Adwaita'
org.freedesktop.ibus.panel use-custom-theme false
org.gnome.desktop.interface cursor-theme 'Pop'
org.gnome.desktop.interface gtk-key-theme 'Default'
org.gnome.desktop.interface gtk-theme 'adw-gtk3-dark'
org.gnome.desktop.interface icon-theme 'Cosmic'
org.gnome.desktop.sound theme-name 'freedesktop'
org.gnome.desktop.wm.preferences theme 'Adwaita'
```




## Themes


### icon-theme / package

> Run: `apt-cache search icon-theme`


> Search: [icon-theme](https://packages.ubuntu.com/search?keywords=icon-theme&searchon=names)

* [papirus-icon-theme](https://packages.ubuntu.com/noble/papirus-icon-theme)
* [numix-icon-theme](https://packages.ubuntu.com/noble/numix-icon-theme)
* [numix-icon-theme-circle](https://packages.ubuntu.com/noble/numix-icon-theme-circle)


執行下面指令安裝

``` sh
sudo apt-get install papirus-icon-theme numix-icon-theme numix-icon-theme-circle
```


### icon-theme / source

* [GreyStone](https://github.com/SethStormR/GreyStone)
* [Delight-2](https://github.com/SethStormR/Delight-2)
