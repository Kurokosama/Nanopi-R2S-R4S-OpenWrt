## OpenWrt Firmwares for NanoPi-R4S
### ⚠ WARNING: USE IT UNDER YOUR OWN RISK.
### Non-profit Uses Only / 仅供个人学习使用.
- - -
My personal customized OpenWrt firmware built by Github Action. A fork from CTCGFW. Hereby thanks for their awesome work! <br/>
OpenWrt Version: 18.06
- - -
## Introduction
- ### Usage
1. Default login address is [192.168.1.1](192.168.1.1), username / password: `root` / `password`.<br/>
 Please change the login password **as soon as possible** once you logined.
2. Once you flashed the firmware into SD card, you may simply use "Upgrade" function<br/>
 in LuCI (no need to decompress the **.gz** archive) if you want to update the firmware.
3. No support for the USB Wifi adapter. Recommend to use a wireless router in AP mode for Wifi access.
4. Support both Offload ~~and Shortcut-FE~~, but you can only enable one at once.<br/>
 Reboot is suggested if you switched from one to another.
5. Allow change the min/max CPU frequency for better performance or saving power, default is balanced mode.
7. Only Bootstrap themes included.

- - -
## Support original developer if you like
[AFDian @CN\_SZTL](https://afdian.net/@CN\_SZTL/plan)
- - -
## Announcement
### License
[GNU General Public License v3.0](https://github.com/1715173329/nanopi-r4s-openwrt/blob/master/LICENSE)
### Source Code
[project-openwrt/openwrt](https://github.com/project-openwrt/openwrt)
