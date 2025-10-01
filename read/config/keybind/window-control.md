---
title: 視窗基本操作
nav_order: 5020
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗基本操作

* [關閉視窗](#關閉視窗)
* [全螢幕](#全螢幕)
* [最大化](#最大化)
* [最小化](#最小化)




## 關閉視窗

| 按鍵組合          | 功能     | 執行指令         |
| ----------------- | -------- | ---------------- |
| `Win + q`         | 關閉視窗 | `Close` (cosmic 內建) |


> 一般「關閉視窗」的按鍵綁定是在「`Alt + F4`」。


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults#L6)

```
    (modifiers: [Super], key: "q"): Close,
```




## 全螢幕

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + f` | 全螢幕 | `Fullscreen` (cosmic 內建) |


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L230-L235)

```
    (
        modifiers: [
            Super,
        ],
        key: "f",
    ): Fullscreen,
```




## 最大化

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + w` | 最大化 | `Maximize` (cosmic 內建) |


> 也可以在「視窗標題列」，使用「滑鼠左鍵」，點選兩下，切換視窗最大化。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L236-L241)

```
    (
        modifiers: [
            Super,
        ],
        key: "w",
    ): Maximize,
```




## 最小化

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + x` | 最小化 | `Minimize` (cosmic 內建) |


> 也可以在「視窗標題列」，找到「最小化」按鈕。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L242-L247)

```
    (
        modifiers: [
            Super,
        ],
        key: "x",
    ): Minimize,
```
