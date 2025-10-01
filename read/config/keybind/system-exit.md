---
title: 離開
nav_order: 5001
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 離開




## 主題

* [功能](#功能)
* [Command](#command)
* [Source](#source)




## 功能

* [關機](#關機)
* [登出](#登出)
* [鎖定螢幕](#鎖定螢幕)




## 關機

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Alt + Shift + z` | 關機 | `System(PowerOff)` (cosmic 內建) |


> 執行關機，會先顯示確認對話框。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L215-L221)

```
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "z",
    ): System(PowerOff),
```


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L33)

```
    PowerOff: "cosmic-osd shutdown",
```




## 登出

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Alt + Shift + x` | 登出 | `System(LogOut)` (cosmic 內建) |


> 執行登出，會先顯示確認對話框。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L222-L228)

```
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "x",
    ): System(LogOut),
```


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L13)

```
    LogOut: "cosmic-osd log-out",
```




## 鎖定螢幕

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Alt + Shift + l` | 鎖定螢幕 | `System(LockScreen)` (cosmic 內建) |


> 執行鎖定螢幕。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L229-L235)

```
    (
        modifiers: [
            Alt,
            Shift,
        ],
        key: "l",
    ): System(LockScreen),
```


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions#L21)

```
    LockScreen: "loginctl lock-session",
```




## Command

* [cosmic-osd](https://samwhelp.github.io/note-about-popos-cosmic/read/explore/command/cosmic-osd.html)




## Source

* cosmic-comp / data / [keybindings.ron](https://github.com/pop-os/cosmic-comp/blob/master/data/keybindings.ron)
* cosmic-settings-daemon / data / [system_actions.ron](https://github.com/pop-os/cosmic-settings-daemon/blob/master/data/system_actions.ron)
* [/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults)
* [/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/system_actions)
