# Acer-A314-22-Opencore
<img src="./Working.png">

## Why?
I've always wanted to try to get a working AMD Hackintosh, and this machine is very cheap and has a modern enough CPU so I decided to finally try and get an all AMD machine working.


Its currently working enough that I have created and written this entire Repo on the machine itself.

## Overview

This EFI has been tested on Mac OS 13 `Ventura` and Mac OS 14 `Sonoma` currently <strong> NOT WORKING </strong> on Mac OS 15 `Sequoia`.

This machine is VERY difficult to get running even with the supplied EFI, I've been battling with it for many hours, so this isn't for the faint of heart, but it does work eventually.

Only faults so far, is <s>no working wifi</s> no keyboard or touchpad working yet. Also the laptop won't boot the full install with the charger plugged in, try unplug the charger if you experiance a kernel panic during boot.


## Specs

| Part             | Description                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| CPU              | 2.3 GHz AMD Athlon Silver 3050U with Radeon Graphics                                                           |
| iGPU             | AMD Radeon Graphics                                                                                            |
| Memory           | 12Gb (1 x 4Gb 2400MHz soldered and 1x8GB DDR4 Sodimm)                                                          |
| Storage          | 128gb NVMe (SATA currently <strong> NOT WORKING </strong>)                                                     |
| Display          | 13 inch 1920x1080 IPS Matte Panel                                                                              |
| Wifi & Bluetooth | Intel® Dual-Band Wireless-AC 8265                                                                              |
| LAN              | Realtek RTL8168H/8111H                                                                                         |
| Audio            | Realtek                                                                                                        |
| External ports   | 2 x USB 3.0, 1 x Ethernet, 1 x USB 2.0, 1 x HDMI 1.4, 1 x 3.5 headphone/microphone combo,                      |

### Working and Not Working

|                                                   | Status | Note                              |
| ------------------------------------------------- | ------ | ----------------------------------|
| Keyboard                                          | ❌     |In Progress                        |
| Touchpad                                          | ❌     |In Progress                        |
| Ethernet                                          | ✅     |                                   |
| Wifi                                              | ✅     |Working perfectly with Airportitlwm|
| Bluetooth                                         | ✅     |                                   |
| Camera & Mic                                      | ✅     |                                   |
| Speaker & 3.5mm audio port                        | ✅     |                                   |
| iGPU & HDMI                                       | ✅     |Working perfectly with NootedRed   |
| USB                                               | ✅     |                                   |
| Sleep                                             | ❌     |                                   |
| Handoff                                           | ❌     |                                   |
| Airdrop                                           | ❌     |                                   |


## Usage

Download my EFI, Change your Serial with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) 

MORE TO COME SOON.


