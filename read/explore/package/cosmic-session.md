---
title: cosmic-session
nav_order: 8010
has_children: false
parent: Package
grand_parent: 探索
---


# cosmic-session

執行

``` sh
dpkg -L cosmic-session
```

顯示

```
/.
/usr
/usr/bin
/usr/bin/cosmic-session
/usr/bin/start-cosmic
/usr/lib
/usr/lib/systemd
/usr/lib/systemd/user
/usr/lib/systemd/user/cosmic-session.target
/usr/share
/usr/share/applications
/usr/share/applications/cosmic-mimeapps.list
/usr/share/doc
/usr/share/doc/cosmic-session
/usr/share/doc/cosmic-session/changelog.gz
/usr/share/doc/cosmic-session/copyright
/usr/share/glib-2.0
/usr/share/glib-2.0/schemas
/usr/share/glib-2.0/schemas/50_cosmic-session.gschema.override
/usr/share/wayland-sessions
/usr/share/wayland-sessions/cosmic.desktop
```

``` sh
apt-cache show cosmic-session
```

```
Package: cosmic-session
Architecture: amd64
Version: 0.1.0~1722449840~24.04~c3de3d2
Priority: optional
Section: admin
Maintainer: System76 <info@system76.com>
Installed-Size: 5912
Depends: dconf-gsettings-backend | gsettings-backend, libc6 (>= 2.34), libgcc-s1 (>= 4.2), cosmic-app-library, cosmic-applets, cosmic-bg, cosmic-comp, cosmic-greeter, cosmic-icons, cosmic-launcher, cosmic-notifications, cosmic-osd, cosmic-panel, cosmic-randr, cosmic-screenshot, cosmic-settings, cosmic-settings-daemon, cosmic-workspaces, pop-fonts, switcheroo-control, xdg-desktop-portal-cosmic, xwayland
Recommends: cosmic-edit, cosmic-files, cosmic-store, cosmic-term, cosmic-wallpapers
Filename: pool/noble/cosmic-session/c3de3d24dd200d5f8a19a26de56590472f461574/cosmic-session_0.1.0~1722449840~24.04~c3de3d2_amd64.deb
Size: 1643856
MD5sum: 0aadc5e99ac482c3f124aaa4f5a23269
SHA1: e466dd0d84d890fe19ecf5155e9f39eabb5720e2
SHA256: a1ef73879a41b3739da0e08ed382168e05ba9aa646449113aabef7ac1333397a
SHA512: f17b6f713f6d97e19a4cb2b7229b61eabd798ca69eec22de5633e45a1c6e9ee2e8055da444d04b8f8213ee0b6e24bf50a4e6c1c5d08e0d0f578a22d2eac9afa4
Homepage: https://github.com/pop-os/cosmic-session
Description: The session for the COSMIC desktop
Description-md5: 

```
