![QMK](https://qmk.fm/qmk_icon_48.png) ![Sonix-QMK](https://avatars.githubusercontent.com/u/79227208?s=48&v=4)
# QMK Binaries #
[QMK Firmware](https://qmk.fm/) that is supported by [SignalRGB](https://www.signalrgb.com) (includes protocol information for direct ARGB mode), compiled for your convenience and ready to install!
If you wish to do this yourself the directions can be found [here](https://docs.signalrgb.com/qmk/building-firmware-from-source).
	
**These binaries may include releases from different "playground(s)" and QMK repositories. stability is not guaranteed..**

# Sinowealth MCUs are NOT supported at all so please do not ask! #

### QMK+Default-Firmware: ###
* **[0.15.12-sonix](https://github.com/SRGBmods/QMK-Binaries/tree/main/QMK%2BDefault-Firmware/0.15.12-sonix)** is for **Sonix based keyboards _only_** and comes from [Sonix_QMKRelease_1.0](https://gitlab.com/signalrgb/qmk_firmware/-/tree/Sonix_QMKRelease_1.0/keyboards).

### QMK+VIA-Firmware: ###
* **[0.7.101-sonix](https://github.com/SRGBmods/QMK-Binaries/tree/main/QMK%2BVIA-Firmware/0.7.101-sonix)** is for **Sonix based keyboards _only_** and comes from [SonixQMK](https://github.com/SonixQMK/qmk_firmware/). - More firmware from this repo is coming **soon**!
* **[0.14.29](https://github.com/SRGBmods/QMK-Binaries/tree/main/QMK%2BVIA-Firmware/0.14.29)** is Keychron's [bluetooth_playground](https://github.com/Keychron/qmk_firmware/tree/bluetooth_playground) so at least when charging a K2 Pro to K8 Pro the ARGB is controllable. (Bluetooth is not supported by SignalRGB currently) - This also includes [q1 version two firmware](https://github.com/Keychron/qmk_firmware/tree/keychron-q1v1-q1v2) now as well.
* **[0.15.12-sonix](https://github.com/SRGBmods/QMK-Binaries/tree/main/QMK%2BVIA-Firmware/0.15.12-sonix)** is for **Sonix based keyboards _only_** and comes from [Sonix_QMKRelease_1.0](https://gitlab.com/signalrgb/qmk_firmware/-/tree/Sonix_QMKRelease_1.0/keyboards).
* **[0.19.12](https://github.com/SRGBmods/QMK-Binaries/tree/main/QMK%2BVIA-Firmware/0.19.12)** is the new [QMK Mainline github](https://github.com/qmk/qmk_firmware), currently being pulled and fixes to boards are applied and uploaded.

### Directions ###
To use these files you may find [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases/) helpful.

Or if a Sonix based firmware [these directions](https://sonixqmk.github.io//SonixDocs/install/#4-flashing-the-firmware) should help.

You will also need to follow the directions from your Keyboard manufacturer to put your device in bootloader mode in order to use QMK Toolbox / Sonix Flasher. (Google is your friend!)
(Check their website for directions, you should honestly check there anyways for firmware in case you to need to factory restore as well.)

### Help with these binaries ###

See the [SignalRGB Plugin Testing Discord Server](https://discord.gg/J5dwtcNhqC) for support.

If you notice something missing (keyboard or variation of a keyboard) or have any issues with these binaries please contact Naitoshedo on the above Discord server.

# PLEASE NOTE On Febuary 25th, 2023: I will be pausing all updates as Breaking Changes for QMK occur the next day, after reviewing new code binary firmware updates will start back up. #

### Older Builds - AKA Archived QMK + SignalRGB builds ###
* **[0.19.11](https://github.com/SRGBmods/QMK-Binaries/tree/main/QMK%2BVIA-Firmware/_Archived)** Archived 0.19.11.zip (Old QMK Mainline VIA+SignalRGB Support).

---

### QMK+Default-Firmware: ###
* **[0.19.12](https://github.com/SRGBmods/QMK-Binaries/tree/main/QMK%2BDefault-Firmware/0.19.12)** is the new [QMK Mainline github](https://github.com/qmk/qmk_firmware), currently being pulled and fixes to boards are applied and uploaded (This is default without VIA support).

---

# Credits #
Thanks to the SonixQMK & QMK communities for providing source code, all original code is completely theirs and thanks to them for providing the code for us and everyone else!

[SonixQMK](https://github.com/SonixQMK/qmk_firmware) & [QMK](https://github.com/qmk/qmk_firmware)

---

## For [GPL Compliance (Source code)](https://github.com/SRGBmods/QMK-Binaries/tree/main/GPL): ##
[QMK Mainline + SignalRGB Merged Source](https://gitlab.com/signalrgb/qmk_firmware/-/tree/QMKRelease_1.0) & [SonixQMK + SignalRGB Merged Source](https://gitlab.com/signalrgb/qmk_firmware/-/tree/Sonix_QMKRelease_1.0).

[Code changes for SignalRGB Protocol 1.0.4 + SonixQMK](https://github.com/SRGBmods/QMK-Binaries/blob/main/GPL/SignalRGB-Changes_QMK-example-code-Sonix.patch)

[Code changes for SignalRGB Protocol 1.0.4 + QMK Master](https://github.com/SRGBmods/QMK-Binaries/blob/main/GPL/SignalRGB-Changes_QMK-example-code.patch)

[common_features.mk](https://github.com/SRGBmods/QMK-Binaries/blob/main/GPL/common_features.mk) & [signalrgb.c](https://github.com/SRGBmods/QMK-Binaries/blob/main/GPL/signalrgb.c) & [signalrgb.h](https://github.com/SRGBmods/QMK-Binaries/blob/main/GPL/signalrgb.h) additional code used by both SonixQMK & QMK Mainline.

The above code changes have been applied to vanilla / playground repos for each fork(s) for the binaries provided.