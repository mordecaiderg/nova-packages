# Nova packages

Software for [Nova](https://github.com/mordecaiderg/nova), the hobby operating system: Nova's
default package source. Install from Nova's Terminal with `pkg install NAME`, or from the Store.

`index.json` lists the packages (the format is in Nova's `docs/PACKAGES.md`); the package files
themselves are in the [`packages` release](../../releases/tag/packages). This repository is
written by Nova's `make publish`: don't edit it by hand.

| Package | Name | Version | Category | Download | About |
|---|---|---|---|---|---|
| Dash | `dash` | 0.5.13.5-1 | System | 225 KB | dash, a small POSIX shell; also /bin/sh |
| Dropbear SSH | `dropbear` | 2026.94-1 | Internet | 922 KB | Dropbear SSH: a server (dropbear), client (dbclient), scp and dropbearkey |
| Noto Fonts | `fonts-noto` | 2026.10.26-1 | System | 20084 KB | Noto fonts: Chinese, Japanese, Korean, many more scripts, symbols and color emoji |
| Kilo | `kilo` | 0.0.0+323d93b-1 | Utilities | 70 KB | kilo, a small text editor for the terminal |
| Ladybird | `ladybird` | 2026.10.18+7a8a84e0-14 | Internet | 129178 KB | A web browser with its own engine: today's web, JavaScript and all |
| Lua | `lua` | 5.4.7-1 | Development | 164 KB | Lua 5.4, a small and fast scripting language |
| GNU Make | `make` | 4.4.1-1 | Development | 161 KB | GNU make 4.4.1, which builds programs from makefiles |
| MicroPython | `micropython` | 1.29.0-1 | Development | 844 KB | MicroPython 1.29, a lean Python 3 |
| Nova | `nova` | 2026.11.01.1509 | System | 43341 KB | Nova itself: the kernel and the system every app runs on |
| NVIDIA Graphics | `nvidia` | 570.144-13 | System | 59576 KB | NVIDIA's open GPU driver, for GeForce RTX 30 and 40 cards |
| NVIDIA Vulkan | `nvidia-vulkan` | 26.2.6-15 | System | 13433 KB | Vulkan and OpenGL ES for NVIDIA cards (Mesa's NVK, Google's ANGLE): vktest and gltest check the card, vkcube spins a cube |
| Python | `python` | 3.14.8-1 | Development | 9874 KB | Python 3.14, the reference implementation (CPython) |
| YipYap Server | `yipyap-server` | 0.2.5+9e7e443-1 | Internet | 1271 KB | Run your own Discord-style chat server, with a web client for any browser |
