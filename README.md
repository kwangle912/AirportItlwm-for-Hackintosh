# AirportItwm-Itlwm


## Intel WiFi Driver for Hackintosh
Only Catalina - Big Sur:
* [Clover](https://github.com/CloverHackyColor/CloverBootloader/releases): Kext to /EFI/Clover/Kext/Other (unsupported Catalina)
* Disable SIP & install AirportItlwm into /Library/Extensions "With Hackintool" & rebuild kext cache then reboot (use AirportItlwm Catalina and install [Hackintool.app](https://github.com/headkaze/Hackintool/releases))

Note :
The kexts can be installed to /Library/Extensions with System Integrity Protection disabled (Terminal type: csrutil disable)
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
* [kext Big Sur v1.2.0-Debug-Alpha](https://drive.google.com/file/d/1DpR2DpiEN1TVN_JBgOiu82G_5XAE5td3/view?usp=sharing) Update Jan-11-2021
* [kext Catalina v1.2.0-Debug-Alpha](https://drive.google.com/file/d/1C2Yng6EUYoDtOAtDkgjtPTboopt03YZt/view?usp=sharing) Update Jan-11-2021
* [HeliPort.app](https://github.com/OpenIntelWireless/HeliPort) copy to `Application` and check `Launch At Login`

<h2 align="left" >Credits</h2>
<br/>

* [OpenIntelWireless](https://github.com/OpenIntelWireless)
