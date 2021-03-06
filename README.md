bootra1n: Linux + checkra1n, on USB
===================================
Just enough Linux to boot checkra1n on any PC.

You will need:
- An USB flash drive (at least 512MB or larger)
- 64-bit AMD or Intel PC

You do not need to install additional software or an OS.

### 1. Download bootra1n
- [bootra1n LiveCD (393 MB)](https://drive.google.com/uc?id=1QCEfjJlXcVY5QL7SqeJ1ZiRAnHhUJYU7&export=download)

Unzip bootra1n into any directory, it should contain an ISO file.

### 2. Write bootra1n to USB
- Etcher https://www.balena.io/etcher/

Download Etcher, select the ISO file, flash it to your USB drive.

### 3. Reboot and run checkra1n
Reboot your computer and enter your BIOS's boot menu.

- Select the flash drive, and it should boot into the login prompt
- Log in as `anon`, with password `voidlinux`
- At the `$` prompt, enter `sudo checkra1n`

![Prompt](https://i.imgur.com/MmqUBUJ.png)

Happy jailbreaking!

## Troubleshooting
*Error -77:* Remove your passcode before starting the jailbreak, you can set it back once done.

## Credits
- Base OS - [Void Linux Team](https://voidlinux.org/)
- Build - Foxlet ([@FoxletFox](https://twitter.com/foxletfox))
- Concept - Evan ([@evanhackerman](https://twitter.com/evanhackerman))
