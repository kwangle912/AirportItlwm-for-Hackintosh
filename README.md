# AirportItwm-Itlwm

## AirportItlwm `Beta`

1. Supports all itlwm-supported devices.
2. Supports native Wi-Fi selection and switching with WPA/WPA2/Unencrypted Wi-Fi Networks.
3. Supports Location Services.
4. Handoff and Universal Clipboard perfectly supported.

## Itlwm
1. Merged itlwmx to itlwm, itlwmx is now deprecated.
2. Compressed firmware files, reduced itlwm size to <b>9.9 MB</b>.
3. Resolved an issue that causes the system to become unresponsive when uploading with P2P software.

A single <i>itlwm.kext</i> supports all the previously supported devices.

itlwm still needs to be used with [Heliport](https://github.com/OpenIntelWireless/HeliPort) and provides support for `macOS 10.12` and above systems.


## Intel WiFi Driver for Hackintosh
<b>Only Catalina - Big Sur:</b>
* [Clover](https://github.com/CloverHackyColor/CloverBootloader/releases): Kext to /EFI/Clover/Kext/Other (unsupported Catalina)
* Disable SIP and install AirportItlwm into `/Library/Extensions` "With Hackintool" & rebuild kext cache then reboot. (use AirportItlwm Catalina and install [Hackintool.app](https://github.com/headkaze/Hackintool/releases))

<b>Note:</b>
The kexts can be installed to `/Library/Extensions` with System Integrity Protection disabled (Terminal type: `csrutil disable`on Recovery OS)

<b>Bootloader Compatibility</b>

<b>Note:</b><br/>
* [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases) requires 0.6.1 or higher. Please read OpenCore's Official Document for more details.

Set `SecureBootModel` to `Default` to make sure IO80211Family loads properly.
* [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases): Kext to /EFI/OC/Kexts (both AirportItlwm Big Sur/Catalina)

<b>WARNING</b>
You should NEVER use both `itlwm.kext` and `Airportitlwm.kext` at the same time.

<h2 align="left" >Supported Intel WiFi Cards by itlwm</h2>
<br/>

- Intel Centrino Wireless-N network devices
- `100/105/135/1000/2000/2030/4965/5000/5150/6000/6005/6030/6050`
- 1000-Series: `N 1000 BGN`, `N 1000 BG`, `N 100 BGN/BG`
- 2000-Series: `Supported`
- 3000-Series: `AC 3160`, `AC 3165`, `AC 3168`
- 4000-Series: `AC 4165`
- 5000-Series: `5300 AGN`, `5100 BGN/AGN/ABG`, `5350 AGN`, `5150 AGN/ABG`
- 6xxx-Series: `Supported`
- 7000-Series: `AC 7260`, `AC 7265`
- 8000-Series: `AC 8260`
- 9000-Series：`AC 9260`,`AC 9461`, `AC 9462`, `AC 9560`
- 22000-Series：`NVM Gen 2 (IWX) Supported`
- 22000--Series: Unsupported NVM Gen 3 `AC 9560 160MHz`, `Wi-Fi 6 AX210 160MHz`
- AX: `1650S`
- AX: `200`, `201`
- [Supported Devices](https://openintelwireless.github.io/itlwm/Compat.html)
- Supported macOS: High Sierra 10.13.x, Mojave 10.14.x, Catalina 10.15.x, Big Sur 11.x

<h2 align="left" >Download kext</h2>
<br/>

<b>You can download latest kext.</b>

Debug Version 1.2.0
* Update Jan-14-2021 - [Big Sur](https://drive.google.com/file/d/1fh2zFdO-3H0mU_mpnucn0lk3Yu-1pSi4/view?usp=sharing)
* Update Jan-11-2021 - [Catalina](https://drive.google.com/file/d/1C2Yng6EUYoDtOAtDkgjtPTboopt03YZt/view?usp=sharing)

Stable Version 1.2.0
* Update Jan-15-2021 - [Big Sur](https://drive.google.com/file/d/1MCHizCV-2uc_ck5wsu7f5VpFZA-yXgaW/view?usp=sharing)
* Update Jan-15-2021 - [Catalina](https://drive.google.com/file/d/1wFHnwUiy7Nyr1mM_PxtOjm0gB3w5TQ2q/view?usp=sharing)

Debug Version 1.3.0
* Update Mar-15-2021 - [Big Sur](https://github.com/kwangle912/AirportItlwm-for-Hackintosh/releases/download/v20210315/AirportItlwm-BigSur-v130-debug-Mar-15.zip)
* Update Mar-14-2021 - [Catalina](https://github.com/kwangle912/AirportItlwm-for-Hackintosh/releases/download/v20210315/AirportItlwm-Catalina-v130-debug-Mar-14.zip)

Stable Version 1.3.0
* Update Apr-20-2021 - [Big Sur](https://github.com/kwangle912/AirportItlwm-for-Hackintosh/releases/download/v20210420/AirportItlwm-v130-stable-BigSur.kext.zip)
* Update Apr-20-2021 - [Catalina](https://github.com/kwangle912/AirportItlwm-for-Hackintosh/releases/download/v20210420/AirportItlwm-v130-stable-Catalina.kext.zip)

Debug Version 2.0.0
* Update Apr-20-2021 - [Big Sur](https://github.com/kwangle912/AirportItlwm-for-Hackintosh/releases/download/v20210424/AirportItlwm-BigSur-v200-debug-Apr-24.zip)
* Update Apr-20-2021 - [Catalina](https://github.com/kwangle912/AirportItlwm-for-Hackintosh/releases/download/v20210424/AirportItlwm-Catalina-v200-debug-Apr-24.zip)


Install Heliport.dmg:
* [HeliPort.app](https://github.com/OpenIntelWireless/HeliPort) copy to `Application` and check `Launch At Login`

<h2 align="left" >Credits</h2>
<br/>

* [OpenIntelWireless](https://github.com/OpenIntelWireless)
