---
title: 開啟應用程式 (常用的)
nav_order: 5013
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 開啟應用程式 (常用的)

* [常用的應用程式](#常用的應用程式)
* [常用的應用程式 (預設)](#常用的應用程式-預設)




## 常用的應用程式

| 按鍵組合          | 功能           | 執行指令                        |
| ----------------- | -------------- | ------------------------------- |
| `Alt + Shift + f` | 開啟檔案管理器 | `cosmic-files`                        |
| `Alt + Shift + g` | 開啟檔案管理器 | `thunar`                    |
| `Alt + Shift + e` | 開啟文字編輯器 | `cosmic-edit`                      |
| `Alt + Shift + b` | 開啟網頁瀏覽器 | `firefox --new-tab about:blank` |
| `Alt + Shift + s` | 開啟系統設定   | `cosmic-settings`               |




* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L109-L148)

```
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "f",
        description: Some("LaunchFileManager"),
    ): Spawn("cosmic-files"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "g",
        description: Some("LaunchFileManager_1"),
    ): Spawn("thunar"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "e",
        description: Some("LaunchTextEditor"),
    ): Spawn("cosmic-edit"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "b",
        description: Some("LaunchWebBrowser"),
    ): Spawn("firefox --new-tab about:blank"),
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "s",
        description: Some("LaunchSystemSettings"),
    ): Spawn("cosmic-settings"),
```




## 常用的應用程式 (預設)

| 按鍵組合          | 功能           | 執行指令                        |
| ----------------- | -------------- | ------------------------------- |
| `Win + f` | 開啟檔案管理器 | `xdg-open ~`                        |
| `Win + b` | 開啟網頁瀏覽器 | `xdg-open http://` |
| `Win + t` | 開啟終端機     | `cosmic-term` |


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L11)

```
    HomeFolder: "xdg-open ~",
```




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L45)

```
    WebBrowser: "xdg-open http://",
```




* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L37)

```
    Terminal: "cosmic-term",
```



* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults#L98-L101)

```
    (modifiers: [Super], key: "b"): System(WebBrowser),
    (modifiers: [Super], key: "f"): System(HomeFolder),
    (modifiers: [Super], key: "t"): System(Terminal),
```



> 不過目前「`Win + b`」被我停用了

* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L64-L69)

```
    (
        modifiers: [
            Super,
        ],
        key: "b",
    ): Disable,
```




> 而「`Win + f`」改成「`Fullscreen`」

* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L206-L211)

```
    (
        modifiers: [
            Super,
        ],
        key: "f",
    ): Fullscreen,
```




> 而「`Win + t`」改成「`ToggleSticky`」

* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L173-L178)

```
    (
        modifiers: [
            Super,
        ],
        key: "t",
    ): ToggleSticky,
```
