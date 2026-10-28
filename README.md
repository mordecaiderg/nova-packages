# Nova packages

Software for [Nova](https://github.com/mordecaiderg/nova), the hobby operating system: Nova's
default package source. Install from Nova's Terminal with `pkg install NAME`, or from the Store.

`index.json` lists the packages (the format is in Nova's `docs/PACKAGES.md`); the package files
themselves are in the [`testing` release](../../releases/tag/testing). This repository is
written by Nova's `make publish`: don't edit it by hand.

| Package | Name | Version | Category | Download | About |
|---|---|---|---|---|---|
| NVIDIA Graphics | `nvidia` | 570.144-7 | System | 59575 KB | NVIDIA's open GPU driver, for GeForce RTX 30 and 40 cards (first stage: it starts the GPU) |
