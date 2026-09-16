# RetroHero

**Browse, download, organize, and add artwork to your retro game library directly on your handheld.**

[![Latest release](https://img.shields.io/github/v/release/monokaijs/RetroHero?display_name=tag&sort=semver)](https://github.com/monokaijs/RetroHero/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/monokaijs/RetroHero/total)](https://github.com/monokaijs/RetroHero/releases)

RetroHero is a controller-first app for Linux retro handhelds. It includes per-system catalogs, search and region filters, background downloads, a ROM manager, Libretro artwork scraping, and automatic app updates.

> [!IMPORTANT]
> Choose the download by both **device** and **firmware**. The same handheld can require a different package after changing its operating system.

## Download for your device

Every button below downloads the appropriate package from the **latest release**, even after a new version is published.

### Miyoo

| Device | Firmware | Latest download | Install |
|---|---|---|---|
| Miyoo Mini Plus | OnionOS | [Download OnionOS](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-onionos-armhf.zip) | Extract to the SD-card root |
| Miyoo Mini | OnionOS | [Download OnionOS](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-onionos-armhf.zip) | Extract to the SD-card root; network access requires Wi-Fi hardware |
| Miyoo Mini Plus | Other compatible Miyoo firmware | [Download Miyoo ARMHF](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-miyoo-armhf.zip) | Extract to the SD-card root |
| Miyoo Mini | Other compatible Miyoo firmware | [Download Miyoo ARMHF](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-miyoo-armhf.zip) | Extract to the SD-card root; network access requires Wi-Fi hardware |

The Miyoo package includes its matching EGL and device runtime libraries. It
also writes startup diagnostics to `App/RetroHero/log.txt` if a launch fails.

### R35S / R36S / R40S Pro and ArkOS RK3326 family

| Device | Firmware | Latest download | Install |
|---|---|---|---|
| R35S | ArkOS / compatible community ArkOS | [Download ArkOS RK3326](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-arkos-rk3326-arm64.zip) | Extract at the root of the active ROM card |
| R36S | ArkOS / ArkOS-R3XS / dArkOS | [Download ArkOS RK3326](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-arkos-rk3326-arm64.zip) | Extract at the root of the active ROM card |
| R40S Pro | ArkOS / compatible community ArkOS | [Download ArkOS RK3326](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-arkos-rk3326-arm64.zip) | Extract at the root of the active ROM card |
| Other RK3326 handhelds | ArkOS family | [Download ArkOS RK3326](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-arkos-rk3326-arm64.zip) | Extract at the root of the active ROM card |

After extraction, refresh the game list if necessary and launch **RetroHero** from the **Ports** collection. The launcher detects `/roms` versus `/roms2`, uses PortMaster's controller mapping when available, and includes a raw R36S/R40S fallback. Devices without built-in Wi-Fi require a compatible USB Wi-Fi adapter.

> [!NOTE]
> R36S and R40S names are used by several hardware revisions and clones. This package targets models with an **RK3326 CPU and 64-bit ArkOS userspace**.

### TrimUI

| Device | Firmware | Latest download | Install |
|---|---|---|---|
| TrimUI Brick | Stock / StockMix / CrossMix | [Download TrimUI package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-trimui-stock-arm64.zip) | Extract to the SD-card root |
| TrimUI Smart Pro | Stock / StockMix / CrossMix | [Download TrimUI package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-trimui-stock-arm64.zip) | Extract to the SD-card root |
| TrimUI Brick | NextUI | [Download NextUI package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-nextui-sd-root-arm64.zip) | Extract to the SD-card root |
| TrimUI Brick Pro | NextUI | [Download NextUI package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-nextui-sd-root-arm64.zip) | Extract to the SD-card root |
| TrimUI Smart Pro | NextUI | [Download NextUI package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-nextui-sd-root-arm64.zip) | Extract to the SD-card root |
| TrimUI Smart Pro S | NextUI | [Download NextUI package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-nextui-sd-root-arm64.zip) | Extract to the SD-card root |

NextUI advanced/manual install: [download the `.pak` archive](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-nextui-arm64.pak.zip), extract `RetroHero.pak`, and copy it to the correct `Tools/<platform>/` folder.

### Anbernic running muOS

Install the downloaded `.muxzip` through **Applications → Archive Manager** in muOS.

| Device | Latest download |
|---|---|
| Anbernic RG28XX H | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG34XX H | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG34XX SP | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG35XX 2024 | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG35XX H | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG35XX Plus | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG35XX Pro | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG35XX SP | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG40XX H | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RG40XX V | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| Anbernic RGCubeXX | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |

The same package also supports the TrimUI Brick and TrimUI Smart Pro when they run muOS:

| Device | Latest download |
|---|---|
| TrimUI Brick | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |
| TrimUI Smart Pro | [Download muOS package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-muos-arm64.muxzip) |

### Anbernic H700 running stock firmware

Extract the package to the SD-card root. RetroHero appears under `Roms/APPS`.

| Device family | Latest download |
|---|---|
| RG28XX / RG34XX / RG35XX / RG40XX / RGCubeXX H700 family | [Download Anbernic stock package](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-anbernic-h700-arm64.zip) |

### Other Linux handhelds

| Architecture | Archive | Latest download |
|---|---|---|
| ARM64 / AArch64 | `.zip` | [Download generic ARM64](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-linux-arm64.zip) |
| ARM64 / AArch64 | `.tar.gz` | [Download generic ARM64 tarball](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-linux-arm64.tar.gz) |
| ARMHF / ARMv7 | `.zip` | [Download generic ARMHF](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-linux-armhf.zip) |
| ARMHF / ARMv7 | `.tar.gz` | [Download generic ARMHF tarball](https://github.com/monokaijs/RetroHero/releases/latest/download/RetroHero-latest-linux-armhf.tar.gz) |

Generic builds require compatible SDL2, SDL2_image, SDL2_ttf, and libcurl libraries. Generic ARMHF also requires `aria2c` on `PATH`.

## Features

- Console-by-console catalogs with grid and list views
- Fast local search and USA, Europe, Japan, and World region filters
- Persistent queue with up to three simultaneous background downloads
- Resume, retry, cancel, extraction, and automatic SD-card folder placement
- ROM manager with single-game and full-system artwork scraping
- Controller-first navigation with D-pad and analog-stick support
- Daily automatic updates using the package for the current OS/device family

## Controls

| Button | Action |
|---|---|
| A | Select, confirm, queue, or retry |
| B | Back or cancel |
| D-pad / left stick | Navigate |
| X | Search/filter; cancel a download; scrape a system; delete a ROM |
| Y | Toggle grid/list; clear completed downloads; scrape selected ROM artwork |
| L1 / R1 | Previous/next page |
| START | Search or open the download queue |
| SELECT | Search/filter or change the region filter |
| MENU | Exit |

## Automatic updates

Packaged builds check this repository's latest release once per day. RetroHero selects the matching package, verifies its SHA-256 checksum, stages it, and keeps the previous installation as a rollback copy.

Disable update checks under **Settings → Auto Update**. HTTPS certificate verification is disabled by default for compatibility with handheld firmware whose CA certificates are missing or outdated; enable it under **Settings → Verify HTTPS** when the device has a working certificate store.

## Requirements and notes

- Catalog browsing and downloads require an internet connection.
- Devices without built-in Wi-Fi need a supported network adapter or another way to provide connectivity.
- Verify manually downloaded versioned files with the `SHA256SUMS` files attached to each release.
- This is the binary distribution repository. Source code is maintained separately.

Need a package that is not listed? [Open an issue](https://github.com/monokaijs/RetroHero/issues/new) with the exact device model, firmware name/version, and a launch log.
