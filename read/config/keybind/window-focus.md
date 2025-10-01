---
title: 視窗聚焦切換
nav_order: 5022
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗聚焦切換




## 主題

* [功能](#功能)
* [相關指令](#相關指令)




## 功能

* [切換視窗](#切換視窗)




## 切換視窗

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + a` | 聚焦切換到上一個視窗 | `System(WindowSwitcherPrevious)` (cosmic 內建) |
| `Win + s` | 聚焦切換到下一個視窗 | `System(WindowSwitcher)` (cosmic 內建) |


> 一般預設「`Alt + Tab`」聚焦切換到下一個視窗。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L260-L270)

```
    (
        modifiers: [
            Super,
        ],
        key: "a",
    ): System(WindowSwitcherPrevious),
    (
        modifiers: [
            Super,
        ],
        key: "s",
    ): System(WindowSwitcher),
```


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L46-L49)

```
    /// Opens the (alt+tab) window switcher
    WindowSwitcher: "cosmic-launcher alt-tab",
    /// Opens the (alt+shift+tab) window switcher
    WindowSwitcherPrevious: "cosmic-launcher shift-alt-tab",
```




## 相關指令

* [cosmic-launcher](https://samwhelp.github.io/note-about-popos-cosmic/read/explore/command/cosmic-launcher.html)
