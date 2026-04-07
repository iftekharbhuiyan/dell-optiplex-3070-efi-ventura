# Dell Optiplex 3070 MFF EFI - macOS Ventura

[![Static Badge](https://img.shields.io/badge/macOS-Ventura-orange)](https://developer.apple.com/documentation/macos-release-notes/macos-13-release-notes)
[![Static Badge](https://img.shields.io/badge/OpenCore-1.0.7-blue)](https://github.com/acidanthera/OpenCorePkg/releases/tag/1.0.7)
[![Static Badge](https://img.shields.io/badge/License-MIT-purple)](/LICENSE)


<p>Dell Optiplex 3070 MFF OpenCore EFI build for macOS Ventura v13.7.8.</p>

## Screenshot

<p>
<figure>
<img src="./screenshots/desktop.png" alt="macOS Ventura Desktop" />
<figcaption>Screenshot of the macOS Ventura Desktop.</figcaption>
</figure>
</p>

## Specification

| Device       | Model                               | Status |
| ------------ | ----------------------------------- | ------ |
| CPU          | Intel Core i7-9700T                 | Works  |
| GPU          | Intel UHD Graphics 630              | Works  |
| Memory       | Crucial 16GB DDR4 2666 MHz          | Works  |
| Drive        | SK hynix BC511 NVMe SSD 256GB       | Works  |
| Audio        | Realtek ALC3234                     | Works  |
| WiFi & BT    | Broadcom BCM94360 Wireless-AC       | Works  |
| Ethernet     | Realtek RTL8111 GbE Controller      | Works  |
| Speaker      | Internal                            | Works  |

## BIOS

<p>The BIOS has been upgraded from v1.24.0 to v1.35.0.</p>

<details>
<summary><strong>BIOS Options</strong></summary><br/>
<ul>
<li>Integrated NIC - Enabled</li>
<li>SATA Operation - AHCI</li>
<li>Primary Display - Intel HD Graphics</li>
<li>TPM 2.0 Security - Unchecked</li>
<li>SMM Security Mitigation - Unchecked</li>
<li>Secure Boot Enable - Unchecked</li>
<li>Secure Boot Mode - Audit Mode</li>
<li>Intel SGX Enable - Disabled</li>
<li>C-States Control - Checked</li>
<li>Deep Sleep Control - Disabled</li>
<li>Wakes on LAN/WLAN - LAN Only</li>
<li>Block Sleep - Checked</li>
<li>Fastboot - Minimal</li>
<li>ASPM - Disabled</li>
<li>Virtualization - Enable Intel Virtualization Technology</li>
<li>VT for Direct I/O - Enable VT for Direct I/O</li>
<li>UEFI Boot Path Security - Always, Except Internal HDD</li>
</ul>
</details>

## Notes

<p>Everything works without any issue. The CFG lock has been removed and DVMT has been updated to 64 MB.</p>

## Credits

- [Acidanthera](https://github.com/acidanthera) - OpenCorePkg
- [lzhoang2801](https://github.com/lzhoang2801) - OpenCore Simplify
- [Mieze](https://github.com/Mieze) - Realtek RTL8111
- [ic005k](https://github.com/ic005k) - OC Auxiliary Tools
- [corpnewt](https://github.com/corpnewt/) - ProperTree & SSDTTime
- [datasone](https://github.com/datasone) - setup_var.efi
- [USBToolBox](https://github.com/USBToolBox) - USB Mapping Tool
- [badges](https://github.com/badges) - Shields.io