---
title: 設定「Wallpaper」
nav_order: 7042
has_children: false
parent: 如何
---


# 設定「Wallpaper」



## 圖形使用者介面操作

可以在「桌面」按下「滑鼠右鍵」，會出現一個選單，

其中有兩個選項如下：

* Change wallpaper...
* Desktop appearance...

選擇「`Change wallpaper...`」，就會出現一個「設定程式」。

也就是透過「`cosmic-settings wallpaper`」這個「圖形使用者介面程式」來操作

``` sh
cosmic-settings wallpaper
```

> 執行「`grep '^Exec=' /usr/share/applications/com.system76.CosmicSettings.Wallpaper.desktop`」可以找到上面的指令。


> 若是直接啟動「`cosmic-settings`」，則是要切換到分頁「`System Settings / Desktop / Wallpaper`」。




## 相關設定檔

* 設定片段：[~/.config/cosmic/com.system76.CosmicBackground/v1/all](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicBackground/v1/all#L3)

```
    source: Path("/usr/share/backgrounds/cosmic/orion_nebula_nasa_heic0601a.jpg"),
```
