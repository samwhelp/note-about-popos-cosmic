---
title: 停用按鍵綁定「Super」開啟「Main Menu」
nav_order: 7022
has_children: false
parent: 如何
---


# 停用按鍵綁定「Super」開啟「Main Menu」




## 說明

* [預設的設定](#預設的設定)
* [如何停用](#如何停用)




## 預設的設定

| 按鍵組合          | 功能         | 執行指令                     |
| ----------------- | ------------- | --------------------------- |
| `Win`     | 開啟「應用程式主選單」 | `cosmic-launcher`                 |


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults#L106)

```
    (modifiers: [Super]): System(Launcher),
```


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L19)

```
    Launcher: "cosmic-launcher",
```




## 如何停用

* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L2-L6)

```
    (
        modifiers: [
            Super,
        ],
    ): Disable,
```
