# nxRepo: The Switch Homebrew Repository



## Custom Firmware 
### Kosmos (Free)
**Features:**
* Up-to-date package
* Firmware launching and sleep mode for every firmware
* Starting games after launching the Homebrew Menu works
* Splash Screens and instant launch
* Game Mods
* A background FTP-Server
* Atmosphere
* Signature Patches
* NSP Installation
* Automatic Updating through your console
* Completely customizable button bindings for the Homebrew Loader
* Full Atmosphere
* Completely modular
* Drag and drop
* Background netcheat system
* Auto-boot selection through Horizon
* Module selection through Horizon

[Download Latest Version](https://github.com/AtlasNX/Kosmos/releases)

---

### ReiNX (Free)
**Features:**
* Easy to install and use
* Modularity (doesn't rely on or require any SD files to run; customize SD files to your liking)
* Loads all KIPs from `/ReiNX/sysmodules/` directory
* Optional custom kernel/secmon/warmboot
* FS patches on the fly (NCA verify/cmac and optional nogc)
* Kernel patches on the fly (optional debug mode)
* Exclusive ReiNX sysmodules
* ES patch in RXP patch format (used with custom loader.kip)

[Download Latest Version](https://github.com/Reisyukaku/ReiNX/releases)
[Installation Guide](https://reinx.guide/)
[Official Thread](https://gbatemp.net/threads/official-reinx-thread.512203/)

---
### Atmosphere
**Features:**
*   Fusée: First-stage Loader, responsible for loading and validating stage 2 (custom TrustZone) plus package2 (Kernel/FIRM sysmodules), and patching them as needed. This replaces all functionality normally in Package1loader/NX Bootloader.
*   Exosphère: Customized TrustZone, to run a customized Secure Monitor
*   Thermosphère: EL2 EmuNAND support, i.e. backing up and using virtualized/redirected NAND images
*   Stratosphère: Custom Sysmodule(s), both Rosalina style to extend the kernel/provide new features, and of the loader reimplementation style to hook important system actions
*   Troposphère: Application-level Horizon OS patches, used to implement desirable CFW features

[Download Latest Version](https://github.com/Atmosphere-NX/Atmosphere/releases)

---
### SX OS (Paid)
**Features:**
* With SX OS you can play all your favorite games straight off of the microSD card inserted into your Nintendo Switch (in XCI Format).
* Using SX OS homebrew menu launcher you can enjoy all the quality games and software by independent developers.
* Built in Cheatengine
* Using the SX OS Launcher you can easily boot into the normal Nintendo Switch firmware to enjoy your original games.

[SX OS & SX Pro Website](https://sx.xecuter.com/)

---
##  CFW Loaders
### [TegraRCMGui](https://github.com/eliboa/TegraRcmGUI/releases)
For Booting into CFW using Windows
### [Fusee-Launcher](https://github.com/Cease-and-DeSwitch/fusee-launchr)
For Booting into CFW using Linux/Mac
### [Rekado](https://github.com/MenosGrante/Rekado/releases)
For Booting into CFW using Android 

---
## Payloads
### [RCM Test Payload](https://drive.google.com/file/d/1Bzku9r9GJ4F_3BoCBa-9QsPUav2-_2V4/view)
For Checking if your Switch is hackable
### [Hekate](https://github.com/CTCaer/hekate/releases)
Custom Nintendo Switch bootloader, firmware patcher, and more.

---
## PC Utilities
### [nspbuild](https://github.com/ThatNerdyPikachu/nspbuild/releases)
This tool aims to help anyone who wants to create their own NSP, without having information scattered around forums and such.
### [Switch Backup Manager](https://github.com/gibaBR/Switch-Backup-Manager/releases)
Complete Switch Backups management tool
### [SwitchGameManager](https://github.com/LostSoulfly/SwitchGameManager/releases)
Manage your Switch/XCI game library in style!
### [4NXCI](https://github.com/The-4n/4NXCI/releases)
A tool for converting XCI (NX Card Image) files to NSP
### [switch-lan-play](https://github.com/spacemeowx2/switch-lan-play/releases)
Allows you and your friends play games like in a LAN.
### [Lan Play GUI](https://github.com/takashi1kun/lan-play-GUI/releases)
A Visual Interface based on electron for switch-lan-play
### [XCI-to-Split-NSP](https://github.com/NuVanDibe/XCI-to-Split-NSP/releases)
For those on FAT32 and cannot convert XCI files larger than 4GB directly on the Switch
### [NSC Builder](https://github.com/julesontheroad/NSC_BUILDER/releases)
Nintendo Switch Cleaner and Builder, designed to erase titlerights encryption from nsp files and make multicontent nsp/xci files.
### [XCI Builder (Discontinued)](https://github.com/julesontheroad/XCI_Builder/releases)
A simple batchfile to convert Nintendo Switch nsp files (digital format) to xci files (cartridge format) based in LucaFraga's hacbuild
### [SwitchLayoutEditor](https://github.com/FuryBaguette/SwitchLayoutEditor/releases)
This program can edit and render BFLYT files commonly used for layouts in Switch interfaces and games. It enables you to easily create/edit themes.
### [Nro2Nsp](https://github.com/Root-MtX/Nro2Nsp/releases)
Simple GUI for converting homebrew to NSP (and making Retroarch Forwarders)

---
## Switch Apps
### [nx-hbmenu](https://github.com/switchbrew/nx-hbmenu/releases)
The Nintendo Switch Homebrew Menu
### [hb-appstore](https://github.com/vgmoose/hb-appstore/releases)
GUI for downloading/managing homebrew apps
### [Retroarch](http://www.retroarch.com)
Libretro emulators for Nintendo Switch
### [Goldleaf](https://github.com/XorTroll/Goldleaf/releases)
Nintendo Switch homebrew multitool, for several purposes and with several features!
### [FTPD](https://github.com/WinterMute/ftpd/releases)
FTP Server for Switch
### [pplay](https://github.com/Cpasjuste/pplay/releases)
Video Player for Switch
### [NX-Shell](https://github.com/joel16/NX-Shell/releases)
WIP Multi purpose file manager for the Nintendo Switch.
### [Lockpick](https://github.com/shchmue/Lockpick/releases)
Nintendo Switch encryption key derivation homebrew
### [Checkpoint](https://github.com/FlagBrew/Checkpoint/releases)
Fast and simple homebrew save manager.
### [ChoiDujourNX](https://gbatemp.net/threads/choidujournx-a-system-firmware-installer-homebrew-for-the-nintendo-switch.513416/)
A system firmware installer homebrew for the Nintendo Switch.
### [In-Home-Switching](https://github.com/jakibaki/In-Home-Switching/releases)
Allows you to stream your PC display to your Nintendo Switch!
### [EdiZon](https://github.com/WerWolv98/EdiZon/releases)
A homebrew save management and editing tool for Horizon on the Nintendo Switch

---
## Other Utilities
### [ldn_mitm](https://github.com/spacemeowx2/ldn_mitm/releases)
Kip for playing local wireless games online.

---
##### If there are any other tools you would like to see on here [let me know](mailto:azonix401@gmail.com).
##### Last Updated Jan 18, 2019 -- [Azor1n Github](https://www.github.com/azor1n)
