# Lenovo Thinkpad E560 OpenCore v0.9.5


[![rsdev69](https://img.shields.io/badge/rsdev69-fork-green?logo=github)](https://github.com/rsdev69/ThinkPad-E560-Hackintosh)
[![macOS](https://img.shields.io/badge/Apple-macOS-white)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.5-blue)](https://github.com/acidanthera/OpenCorePkg)


Fork from rsdev69. Adding some major improvements check here on [Release Page](https://github.com/KenDxD/Lenovo-Thinkpad-E560-Hackintosh/releases) for more info 🥹.

## Please Read this!!!!

**I'm not responsible to any data loss, broken hardware or nuclear launch by North Korea. This is for `personal use only` and not for `commercial use`. Don't ever sell this config or hardware with this config, please report it to me because it's a violation to the `Apple EULA` called `Software Piracy`. I know we also broke it but people who use this config to gain money are `ULTRA PRO MAX SCUM`. This config is for the people who wants to experience the Apple ecosystem and ready to buy Apple products or `real` Apple hardware.**

## Instruction

<strong>GENERATE YOUR OWN SERIAL, ROM,MLB and UUID for iService to be working.</strong><br>
SMBIOS: <br>
`MacbookPro13,1(Monterey)` <br>
`MacbookPro14,1(Ventura)` <br>
`MacbookPro15,2(Sonoma)` <br>

<strong>Don't ever update `VoodooPS2Controller.kext` because it contains patch for our Fn Key to be functional even after sleep. Follow this [guides](https://github.com/KenDxD/Lenovo-Thinkpad-E560-Hackintosh/blob/main/Custom%20patch/Guide.md) here for manual apply. <br> Note: This is aready included on [v2023.10.18](https://github.com/KenDxD/Lenovo-Thinkpad-E560-Hackintosh/releases/tag/v2023.10.18) release and onwards.</strong><br>

**What's working currently on this patched version?**<br>
*- Swap Command and Option is `enabled` by default.*<br>
*- Fn Key that currently works.*<br>
`Fn + F1` for `Mute`<br>
`Fn + F2` for `Volume Down`<br>
`Fn + F3` for `Volume Up`<br>
`Fn + F5` for `Decrease Brightness`<br>
`Fn + F6` for `Increase Brightness`<br>

## Running macOS

<img align="center" src="./img/specsmonterey.png" alt="specsmonterey" width="500">
<img align="center" src="./img/specsventura.png" alt="specsventura" width="500">

<br clear="right">

## What's working?

| Type               | Status   |
|:------------------:|:--------:|
| Wifi               |    ✅    |
| Bluetooth          |    ✅    |
| Sleep              |    ✅    |
| Lid                |    ✅    |
| NVRAM              |    ✅    |
| iMessage           |    ✅    |
| Facetime           |    ✅    |
| Keyboard Fn Keys   |    ✅    |
| Audio              |    ✅    |
| Touchpad           |    ✅    |
| USB 3.0 SS x 3     |    ✅    |
| VGA Port           |    ✅    |
| HDMI Port          |    ✅    |


<br clear="right">
 
## Hardware and Settings

| Type             | Spec                                  |
|:----------------:|:-------------------------------------:|
| Computer         | Lenovo ThinkPad E560                  |
| BIOS Version     | LENOVO v1.44                          |
| CPU              | Intel i3 6100U 2300 MHz               |
| Display          | 15.6 inch 16:9, 1360 x 768 pixel      |
| Ethernet         | Intel I219V Gigabit Ethernet          |
| Memory           | 6GB DDR3L-1600 MHz / PC3L-12800       |
| Graphics         | Intel HD Graphics 520                 |
| Audio            | Conexant HD Audio CX20753/4           |
| Touchpad         | Elan Touchpad                         |
| USB Ports        | 3 x USB 3.0                           |
| Storage          | RAMSTA SSD 128GB                      |
| Wifi             | IntelAC 3165                          |
| VGA Port         | Max Full HD 60hz                      |
| Card Reader      | 10/15 MB/s                            |
| HDMI 1.4 Ports   | Max 4k 30hz                           |

BIOS SETTINGS

| Menu       |                     |                                   | Setting       |
|:----------:|:-------------------:|:---------------------------------:|:-------------:|
| Config     | USB                 | UEFI BIOS Support                 | `Enable `     |
|            | Power               | Intel SpeedStep Technology        | `Enable `     |
|            |                     | CPU Power Management              | `Enable `     |
|            | CPU                 | Hyper-Threading Technology        | `Enable `     |
| Security   | Security Chip       |                                   | `Disable `    |
|            | Memory Protection   | Execution Prevention              | `Enable `     |
|            | Virtualization      | Intel Virtualization Technology   | `Enable `     |
|            |                     | Intel VT-d Feature                | `Enable `     |
|            | Anti-Theft          | Computrace                        | `Disable `    |
|            | Secure Boot         |                                   | `Disable `    |
|            | Intel SGX           |                                   | `Disable `    |
|            | Device Guard        |                                   | `Disable `    |
| Startup    | UEFI/Legacy Boot    |                                   | `UEFI Only`   |
|            | CSM Support         |                                   | `No`          |
|            | Boot Mode           |                                   | `Quick`       |
