# Nova packages

Software for [Nova](https://github.com/mordecaiderg/nova), the hobby operating system: Nova's
default package source. Install from Nova's Terminal with `pkg install NAME`, or from the Store.

`index.json` lists the packages (the format is in Nova's `docs/PACKAGES.md`); the package files
themselves are in the [`testing` release](../../releases/tag/testing). This repository is
written by Nova's `make publish`: don't edit it by hand.

| Package | Name | Version | Category | Download | About |
|---|---|---|---|---|---|
| Nova | `nova` | 2026.11.11.2214 | System | 45771 KB | Nova itself: the kernel and the system every app runs on |
| NVIDIA Graphics | `nvidia` | 570.144-12 | System | 59576 KB | NVIDIA's open GPU driver, for GeForce RTX 30 and 40 cards (first stage: it starts the GPU) |
| NVIDIA Vulkan | `nvidia-vulkan` | 26.2.6-26 | System | 27177 KB | Vulkan and OpenGL for NVIDIA cards (Mesa's NVK and Zink, Google's ANGLE): vktest, gltest and zinktest check the card, vkcube and glcube spin cubes |
| Wine | `wine` | 11.0-9 | System | 147312 KB | Wine: run Windows programs (early: a command, no app yet) |
