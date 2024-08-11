---
title: Package
nav_order: 8010
has_children: true
parent: 探索
---


# Package




## Link

* GitHub / pop-os / [cosmic-epoch](https://github.com/pop-os/cosmic-epoch)




## 初步探索

執行

``` sh
dpkg -l '*cosmic*'
```

顯示

```
Desired=Unknown/Install/Remove/Purge/Hold
| Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
|/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
||/ Name                      Version                            Architecture Description
+++-=========================-==================================-============-=======================================================
ii  cosmic-app-library        0.1.0~1722624912~24.04~1416b80     amd64        Cosmic App Library
ii  cosmic-applets            0.1.0~1722629707~24.04~0720bdb     amd64        Cosmic Applets
ii  cosmic-bg                 0.1.0~1722429839~24.04~e5637fc     amd64        Cosmic Background
ii  cosmic-comp               0.1~1722855532~24.04~4748916       amd64        Wayland compositor of pop-os cosmic shell
ii  cosmic-edit               0.1.0~1722606123~24.04~df5d109     amd64        Cosmic Text Editor
ii  cosmic-files              0.1.0~1722811269~24.04~190029a     amd64        Cosmic File Manager
ii  cosmic-greeter            0.1.0~1722623698~24.04~cc744b0     amd64        Cosmic Greeter
ii  cosmic-greeter-daemon     0.1.0~1722623698~24.04~cc744b0     amd64        Cosmic Greeter daemon
ii  cosmic-icons              0.1.0~1722778845~24.04~f93dcdf     amd64        Cosmic Icons
ii  cosmic-launcher           0.1.0~1722530694~24.04~d84fda0     amd64        Cosmic Launcher
ii  cosmic-notifications      0.1.0~1722531142~24.04~e9abef5     amd64        Cosmic Notifications
ii  cosmic-osd                0.1.0~1721052322~24.04~27fc5e5     amd64        Cosmic OSD
ii  cosmic-panel              0.1.0~1722616034~24.04~47c6720     amd64        XDG Shell Wrapper Panel for COSMIC
ii  cosmic-randr              0.1.0~1722404448~24.04~71fabbb     amd64        Display and configure wayland display outputs
ii  cosmic-screenshot         0.1.0~1721939965~24.04~031eb66     amd64        Cosmic Screenshot Utility
ii  cosmic-session            0.1.0~1722449840~24.04~c3de3d2     amd64        The session for the COSMIC desktop
ii  cosmic-settings           0.1.0~1722874443~24.04~648c4e2     amd64        Settings application for the COSMIC desktop environment
ii  cosmic-settings-daemon    0.1.0~1722625060~24.04~362c77f     amd64        Cosmic settings daemon
ii  cosmic-store              0.1.0~1722797935~24.04~639a17c     amd64        Cosmic App Store
ii  cosmic-term               0.1.0~1722700023~24.04~be808b5     amd64        COSMIC Terminal
ii  cosmic-wallpapers         1.0.0~1719415313~24.04~0f2f16d     all          COSMIC Wallpapers
ii  cosmic-workspaces         0.1.0~1722539184~24.04~c1acf0c     amd64        Cosmic workspaces
ii  pop-de-cosmic             3.0.0~1722527140~24.04~74ff568     amd64        Pop!_OS metapackage for COSMIC-related dependencies.
ii  xdg-desktop-portal-cosmic 0.1.0pop1~1722606217~24.04~41c1e7c amd64        Cosmic backend for xdg-desktop-portal
```


執行

``` sh
dpkg -S /usr/share/cosmic
```

顯示

```
cosmic-applets, cosmic-bg, cosmic-comp, cosmic-panel, cosmic-settings, cosmic-settings-daemon: /usr/share/cosmic
```



## Cosmic Package

| Cosmic Package |
| -------------- |
| [pop-de-cosmic](pop-de-cosmic) |
| [xdg-desktop-portal-cosmic](xdg-desktop-portal-cosmic) |




| Cosmic Package |
| -------------- |
| [cosmic-greeter](cosmic-greeter) |
| [cosmic-greeter-daemon](cosmic-greeter-daemon) |
| [cosmic-session](cosmic-session) |




| Cosmic Package |
| -------------- |
| [cosmic-comp](cosmic-comp) |
| [cosmic-settings](cosmic-settings) |
| [cosmic-settings-daemon](cosmic-settings-daemon) |




| Cosmic Package |
| -------------- |
| [cosmic-panel](cosmic-panel) |
| [cosmic-applets](cosmic-applets) |



| Cosmic Package |
| -------------- |
| [cosmic-bg](cosmic-bg) |
| [cosmic-notifications](cosmic-notifications) |
| [cosmic-osd](cosmic-osd) |



| Cosmic Package |
| -------------- |
| [cosmic-launcher](cosmic-launcher) |
| [cosmic-workspaces](cosmic-workspaces) |
| [cosmic-app-library](cosmic-app-library) |
| [cosmic-screenshot](cosmic-screenshot) |
| [cosmic-randr](cosmic-randr) |




| Cosmic Package |
| -------------- |
| [cosmic-term](cosmic-term) |
| [cosmic-files](cosmic-files) |
| [cosmic-edit](cosmic-edit) |
| [cosmic-store](cosmic-store) |




| Cosmic Package |
| -------------- |
| [cosmic-icons](cosmic-icons) |
| [cosmic-wallpapers](cosmic-wallpapers) |
