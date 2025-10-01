---
title: 鍵盤按鍵綁定一覽表
nav_order: 9010
has_children: false
parent: 一覽表
---


# 鍵盤按鍵綁定一覽表

> 概覽 / [工作流程](https://samwhelp.github.io/note-about-popos-cosmic/read/guide/workflow)

> [鍵盤按鍵綁定說明](https://samwhelp.github.io/note-about-popos-cosmic/read/config/keybind.html)

> 如何 / [設定「按鍵綁定」](https://samwhelp.github.io/note-about-popos-cosmic/read/howto/config-keybind.html)




## 主題

* [系統操作](#系統操作)
* [開啟應用程式](#開啟應用程式)
* [視窗操作](#視窗操作)
* [切換](#切換)
* [相關連結](#相關連結)




## 系統操作


## 系統操作 / 離開系統

| 按鍵組合           | 功能    | 執行指令                         |
| ------------------ | ----- | -------------------------------- |
| `Alt + Shift + z`  | 關機  | `cosmic-osd shutdown` |
| `Alt + Shift + x`  | 登出  | `cosmic-osd log-out`  |
| `Alt + Shift + l`  | 鎖定螢幕  | `loginctl lock-session`  |




## 開啟應用程式


## 開啟應用程式 / 透過「應用程式啟動器」

| 按鍵組合     | 功能                                 | 設定項目                                                |
| ----------- | ----------------------------------- | ----------------------------------------------------- |
| `Alt + F1`  | `開啟「應用程式啟動主選單(Main Menu)」`  | `cosmic-app-library` |
| `Alt + F2`  | `開啟「應用程式啟動器(Runner)」`        | `cosmic-launcher`  |

> 在『[停用按鍵綁定「Super」開啟「Main Menu」](https://samwhelp.github.io/note-about-popos-cosmic/read/howto/disable-keybind-open-main-menu.html)』這篇有提到原本預設是綁定「`Super`」。為了避免干擾，所以被我停用了。




## 開啟應用程式 / Terminal

| 按鍵組合           | 功能           | 執行指令           |
| ------------------ | -------------- | ------------------ |
| `Alt + Enter`      | 開啟 Terminal  | `cosmic-term`  |
| `Alt + Shift + a`  | 開啟 Terminal  | `cosmic-term`  |
| `Alt + Ctrl + a`   | 開啟 Terminal  | `xfce4-terminal`           |
| `Alt + Shift + t`  | 開啟 Terminal  | `qterminal`   |
| `Alt + Ctrl + t`   | 開啟 Terminal  | `lxterminal`        |




## 開啟應用程式 / 常用的應用程式

| 按鍵組合           | 功能            | 執行指令                         |
| ------------------ | --------------- | -------------------------------- |
| `Alt + Shift + f`  | 開啟檔案管理器  | `cosmic-files`             |
| `Alt + Shift + g`  | 開啟檔案管理器  | `thunar`                     |
| `Alt + Shift + e`  | 開啟文字編輯器  | `cosmic-edit`              |
| `Alt + Shift + b`  | 開啟網頁瀏覽器  | `firefox --new-tab about:blank`  |
| `Alt + Shift + s`  | 開啟系統設定    | `cosmic-settings`                |




## 視窗操作

| 按鍵組合   | 功能                               | 設定項目                       |
| ---------- | ---------------------------------- | ------------------------------ |
| `Alt + Space`  | 顯示「視窗功能選單」  | `無`            |
| `Win + q`  | 關閉視窗                           | `Close`                |
| `Win + f`  | 視窗全螢幕                         | `Fullscreen`           |
| `Win + w`  | 視窗最大化                         | `Maximize`             |
| `Win + x`  | 視窗最小化                         | `Minimize`             |
| `Win + d`  | 切換顯示桌面                         | `無`             |
| `Win + e`  | 開始「視窗移動」                   | `無`                 |
| `Win + r`  | 開始「視窗更改大小」               | `Resizing(Outwards)`               |
| `Win + y`  | 視窗內容區塊收合                   | `無`                |
| `Win + t`  | 視窗保持永遠在最上方               | `ToggleSticky`  |
| `Win + z`  | 在最近聚焦過的兩個視窗切換               | `無`  |


> 一般預設「`Alt + F4`」綁定「`視窗關閉`」

> 一般預設「`F11`」綁定「`視窗全螢幕`」




## 切換

## 切換 / 視窗

| 按鍵組合     | 功能                    | 執行指令                                       |
| ------------ | ----------------------- | ---------------------------------------------- |
| `Win + a`    | 聚焦切換到「前面一個視窗」  | `cosmic-launcher shift-alt-tab`              |
| `Win + s`    | 聚焦切換到「後面一個視窗」  | `cosmic-launcher alt-tab`                        |

> 一般預設「`Alt + Tab`」綁定「`視窗聚焦切換`」




## 切換 / 工作空間

| 按鍵組合   | 功能                  | 設定項目                            |
| ---------- | --------------------- | ----------------------------------- |
| `Alt + a`  | 切換到「上一個工作空間」  | `PreviousWorkspace`   |
| `Alt + s`  | 切換到「下一個工作空間」  | `NextWorkspace`  |




## 切換 / 概覽


| 按鍵組合   | 功能                  | 執行指令                            |
| ---------- | --------------------- | ----------------------------------- |
| `Win + Tab`  | 工作空間視窗概覽  | `cosmic-workspaces`   |
| `Win + grave`  | `開啟「應用程式啟動主選單(Main Menu)」`  | `cosmic-app-library` |

> `grave` 指的是「`」，在「~」底下。




## 切換 / 視窗 Layout

| 按鍵組合  | 功能       |
| --------- | ---------- |
| `Win + v` | 切換整體視窗狀態 |
| `Win + Esc` | 切換單一視窗狀態 |
| `Win + o`         | 視窗平鋪導向 |
| `Win + z`         | 開始視窗位置交換 |




## 相關連結

| 相關連結 |
| ------- |
| [鍵盤按鍵綁定](https://samwhelp.github.io/note-about-popos-cosmic/read/config/keybind.html) |
