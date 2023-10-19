## Guide

<strong>Delete all current keyboard patch before starting following this guide, for example `SSDT-KBRD.aml` or any `.aml` in `ACPI` folder and the current updated `VoodooPS2Controller.kext` in `Kexts` folder.<br>

**1. Download the latest patched  `VoodooPS2Controller.kext` in [Custom patch](https://github.com/KenDxD/Lenovo-Thinkpad-E560-Hackintosh/tree/main/Custom%20patch).**<br>
**2. Paste it on your `EFI>OC>Kexts` folder.**<br>
**3. [Use Propertree](https://github.com/corpnewt/ProperTree) to OC snapshot your `config.plist`.**<br>
**4. Restart your machine.**<br>

Current patched version of VoodooPS2Controller.kext is based on [Acindathera VoodooPS2 v2.3.5 Release](https://github.com/acidanthera/VoodooPS2/releases/tag/2.3.5).<br>

## What's working on this patched?
**- Swap Command and Option is `enabled` by default.**<br>
**- Fn Key that currently works.**<br>
`Fn + F1` for `Mute`<br>
`Fn + F2` for `Volume Down`<br>
`Fn + F3` for `Volume Up`<br>
`Fn + F5` for `Decrease Brightness`<br>
`Fn + F6` for `Increase Brightness`<br>
