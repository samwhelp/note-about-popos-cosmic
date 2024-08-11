---
title: 設定
nav_order: 2000
has_children: true
---


# 設定




## 微調腳本

| 微調腳本 |
| -------- |
| [Popos Cosmic Config](https://github.com/samwhelp/popos-cosmic-adjustment/tree/main/prototype/main/cosmic-config/Main) |




## 按鍵綁定

| 按鍵綁定 |
| --- |
| [鍵盤按鍵綁定](https://samwhelp.github.io/note-about-popos-cosmic/read/config/keybind.html) |
| [滑鼠按鍵綁定](https://samwhelp.github.io/note-about-popos-cosmic/read/config/mousebind.html) |




## Source

* cosmic-comp / data / [keybindings.ron](https://github.com/pop-os/cosmic-comp/blob/master/data/keybindings.ron)
* cosmic-panel / data / [default_schema](https://github.com/pop-os/cosmic-panel/tree/master/data/default_schema)
* cosmic-bg / data / [v1](https://github.com/pop-os/cosmic-bg/tree/master/data/v1)
* cosmic-settings / resources / [default_schema](https://github.com/pop-os/cosmic-settings/tree/master/resources/default_schema)
* cosmic-settings-daemon / data / [system_actions.ron](https://github.com/pop-os/cosmic-settings-daemon/blob/master/data/system_actions.ron)
* cosmic-applets / cosmic-app-list / data / [default_schema](https://github.com/pop-os/cosmic-applets/tree/master/cosmic-app-list/data/default_schema/com.system76.CosmicAppList/v1)


執行

``` sh
dpkg -S /usr/share/cosmic
```

顯示

```
cosmic-applets, cosmic-bg, cosmic-comp, cosmic-panel, cosmic-settings, cosmic-settings-daemon: /usr/share/cosmic
```



執行

``` sh
dpkg -S /usr/share/cosmic
```

顯示

```
com.system76.CosmicAppList
com.system76.CosmicBackground
com.system76.CosmicPanel
com.system76.CosmicPanel.Dock
com.system76.CosmicPanel.Panel
com.system76.CosmicSettings.Shortcuts
com.system76.CosmicTheme.Dark
com.system76.CosmicTheme.Dark.Builder
com.system76.CosmicTheme.Light
com.system76.CosmicTheme.Light.Builder
com.system76.CosmicTheme.Mode
```
