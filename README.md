# Pager_CompiledTools

Precompiled static binaries for the **Hak5 WiFi Pineapple Pager** (and other `mipsel_24kc` OpenWrt devices). 

These tools are cross-compiled using the OpenWrt SDK 24.10 to ensure compatibility with modern firmware while being statically linked to avoid missing dependency errors.

## Included Tools
* **MDK4 v4.2**: Wifi Tools (Standalone).
* **Reaver v1.6.6**: WPS brute-force tool.
* **Wash**: WPS scan tool (included in Reaver package).
* **PixieWps v1.4.2**: Offline WPS brute-force tool (Pixie Dust).
* **Aircrack-ng Suite**: Includes `airodump-ng`, `aircrack-ng`, etc.
---

## Installation

1) Transfer the the precompiled binary to the Pager
2) On the pager run `sudo opkg install binary.ipk` e.g: `sudo opkg install reaver_1.6.6-r1_mipsel_24kc.ipk`
3) ???
4) Profit

