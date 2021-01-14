# AirportItwm-Itlwm

## AirportItlwm `Beta`

1. Supports all itlwm-supported devices.
2. Supports native Wi-Fi selection and switching with WPA/WPA2/Unencrypted Wi-Fi Networks.
3. Supports Location Services.
4. Handoff and Universal Clipboard perfectly supported.

## ItLwm
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
The kexts can be installed to `/Library/Extensions` with System Integrity Protection disabled (Terminal type: `csrutil disable`)

<b>Bootloader Compatibility</b>

<b>Note:</b><br/>
* [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases) requires 0.6.1 or higher. Please read OpenCore's Official Document for more details.

Set `SecureBootModel` to `Default` to make sure IO80211Family loads properly.
* [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases): Kext to /EFI/OC/Kexts (both AirportItlwm Big Sur/Catalina)

<h2 align="left" >Supported Intel WiFi Cards by itlwm</h2>
<br/>

- 2000: `Supported`
- 3xxx: `AC 3160`, `AC 3165`, `AC 3168`
- 4xxx: `AC 4165`
- 7xxx: `AC 7260`, `AC 7265`
- 8xxx: `AC 8260`
- 9xxx：`AC 9260`,`AC 9461`, `AC 9462`, `AC 9560`
- 22000：`ax200`, `ax201`, `AC 9462`
- [Supported Devices](https://openintelwireless.github.io/itlwm/Compat.html)

<h2 align="left" >Download kext</h2>
<br/>

You can download latest kext.
* [kext Big Sur v1.2.0-Debug-Alpha](https://drive.google.com/file/d/1fh2zFdO-3H0mU_mpnucn0lk3Yu-1pSi4/view?usp=sharing) Update Jan-14-2021
* [kext Catalina v1.2.0-Debug-Alpha](https://drive.google.com/file/d/1C2Yng6EUYoDtOAtDkgjtPTboopt03YZt/view?usp=sharing) Update Jan-11-2021
* [HeliPort.app](https://github.com/OpenIntelWireless/HeliPort) copy to `Application` and check `Launch At Login`

<h2 align="left" >Credits</h2>
<br/>

* [OpenIntelWireless](https://github.com/OpenIntelWireless)
