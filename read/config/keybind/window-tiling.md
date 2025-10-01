---
title: 視窗平鋪操作
nav_order: 5021
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 視窗平鋪操作

* [切換整體視窗狀態](#切換整體視窗狀態)
* [切換單一視窗狀態](#切換單一視窗狀態)
* [視窗平鋪導向](#視窗平鋪導向)
* [開始視窗位置交換](#開始視窗位置交換)
* [視窗合併或解離](#視窗合併或解離)
* [視窗固定](#視窗固定)




## 切換整體視窗狀態

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + v` | 切換整體視窗狀態 | `ToggleTiling` (cosmic 內建) |


> 將「整體視窗」，切換成「`Tiling`」或「`Floating`」。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L179-L184)

```
    (
        modifiers: [
            Super,
        ],
        key: "v",
    ): ToggleTiling,
```




## 切換單一視窗狀態

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + Esc` | 切換單一視窗狀態 | `ToggleWindowFloating` (cosmic 內建) |


> 當「整體視窗」在「`Tiling`」狀態時，將「單一視窗」切換成「`Tiling`」或「`Floating`」。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L185-L190)

```
    (
        modifiers: [
            Super,
        ],
        key: "Escape",
    ): ToggleWindowFloating,
```




## 視窗平鋪導向

| 按鍵組合          | 功能     | 執行指令         |
| ----------------- | -------- | ---------------- |
| `Win + o`         | 視窗平鋪導向 | `ToggleOrientation` (cosmic 內建) |


> 當「整體視窗」在「`Tiling`」狀態時，切換視窗平鋪導向。


* 設定片段：[/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/sample/default-schema/Main/asset/overlay/usr/share/cosmic/com.system76.CosmicSettings.Shortcuts/v1/defaults#L82)

```
    (modifiers: [Super], key: "o"): ToggleOrientation,
```




## 開始視窗位置交換

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + z` | 開始視窗位置交換 | `SwapWindow` (cosmic 內建) |


> 當「整體視窗」在「`Tiling`」狀態時，按住「`Win + z`」不動，此時就可使用「上下左右鍵」或「kjhl鍵」，跟「目前視窗」交換位置。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L209-L214)

```
    (
        modifiers: [
            Super,
        ],
        key: "z",
    ): SwapWindow,
```




## 視窗合併或解離

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + c` | 視窗合併或解離 | `ToggleStacking` (cosmic 內建) |


> 將視窗合併或解離。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L191-L196)

```
    (
        modifiers: [
            Super,
        ],
        key: "c",
    ): ToggleStacking,
```




## 視窗固定

| 按鍵組合  | 功能       | 執行指令                      |
| --------- | ---------- | ----------------------------- |
| `Win + t` | 視窗固定 | `ToggleSticky` (cosmic 內建) |


> 將視窗固定。


* 設定片段：[~/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom](https://github.com/samwhelp/popos-cosmic-adjustment/blob/main/prototype/main/cosmic-config/full/Main/asset/overlay/etc/skel/.config/cosmic/com.system76.CosmicSettings.Shortcuts/v1/custom#L197-L202)

```
    (
        modifiers: [
            Super,
        ],
        key: "t",
    ): ToggleSticky,
```
