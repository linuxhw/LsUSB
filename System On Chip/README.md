Most popular USB devices in System On Chips
===========================================

See more info in the [README](https://github.com/linuxhw/LsUSB).

Contents
--------

1. [ USB Devices in System On Chips ](#usb-devices)
   * [ Audio ](#audio-usb)
   * [ Bluetooth ](#bluetooth-usb)
   * [ Camera ](#camera-usb)
   * [ Cdrom ](#cdrom-usb)
   * [ Chipcard ](#chipcard-usb)
   * [ Disk ](#disk-usb)
   * [ Dvb card ](#dvb-card-usb)
   * [ Fingerprint reader ](#fingerprint-reader-usb)
   * [ Gamepad ](#gamepad-usb)
   * [ Hub ](#hub-usb)
   * [ Human interface ](#human-interface-usb)
   * [ Input/keyboard ](#inputkeyboard-usb)
   * [ Input/mouse ](#inputmouse-usb)
   * [ Joystick ](#joystick-usb)
   * [ Mfp ](#mfp-usb)
   * [ Miscellaneous ](#miscellaneous-usb)
   * [ Modem ](#modem-usb)
   * [ Net/ethernet ](#netethernet-usb)
   * [ Net/wireless ](#netwireless-usb)
   * [ Network ](#network-usb)
   * [ Printer ](#printer-usb)
   * [ Scanner ](#scanner-usb)
   * [ Serial controller ](#serial-controller-usb)
   * [ Sound ](#sound-usb)
   * [ Touchpad ](#touchpad-usb)
   * [ Touchscreen ](#touchscreen-usb)
   * [ Tv card ](#tv-card-usb)
   * [ Ups ](#ups-usb)
   * [ Wireless ](#wireless-usb)
   * [ Others ](#others-usb)

USB Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Audio (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:49ab | Realtek Semic... | USB Audio                            | 1     | snd_usb... | [BD05C84564](<System On Chip/HUAWEI/W510/W510 PGU-WBY0/5583E74879DC/UBUNTU-21.04/5.8.0-36-GENERIC/AARCH64/BD05C84564>) |
| 1235:8202 | Focusrite-Nov... | Focusrite Scarlett 2i2 2nd Gen       | 1     | snd_usb... | [46D79DE66E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3E699A4BBDB1/UBUNTU-21.10/5.13.0-1009-RASPI/AARCH64/46D79DE66E>) |

### Bluetooth (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0a12:0001 | Cambridge Sil... | Bluetooth Dongle (HCI mode)          | 12    | btusb      | [6A686B1A1D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B49D2AC00A0D/DEBIAN-11/5.10.92-V8+/AARCH64/6A686B1A1D>) |
| 8087:0a2b | Intel            | Bluetooth wireless interface         | 11    | btusb      | [54592EC1A2](<System On Chip/Nvidia/Tegra/Tegra/54129FFCE65C/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/54592EC1A2>) |
| 13d3:3549 | IMC Networks     | Bluetooth Radio                      | 6     | rtk_btu... | [077899579F](<System On Chip/Nvidia/Tegra/Tegra/EBC4CC1806ED/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/077899579F>) |
| 04ca:3015 | Lite-On Techn... | Qualcomm Atheros QCA9377 Bluetooth   | 1     | btusb      | [5E682A0733](<System On Chip/Nvidia/Tegra/Tegra/A1DD672248E9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/5E682A0733>) |
| 07d1:f101 | D-Link System    | DBT-122 Bluetooth                    | 1     | btusb      | [7CDE4A4D40](<System On Chip/Nvidia/Tegra/Tegra/57BEF78164BC/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/7CDE4A4D40>) |
| 0a5c:2121 | Broadcom         | BCM2210 Bluetooth                    | 1     | btusb      | [4BAC63946A](<System On Chip/Hardkernel/Odroid/Odroid XU4/1EFF612359AC/DEBIAN-10/5.4.72-ODROIDXU4/ARMV7L/4BAC63946A>) |
| 0a5c:21e8 | Broadcom         | BCM20702A0 Bluetooth 4.0             | 1     | btusb      | [A63AF8E149](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/40D0D2E0539C/XUBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/A63AF8E149>) |
| 0a5c:21ec | Broadcom         | BCM20702A0 Bluetooth 4.0             | 1     | btusb      | [9B157B83A5](<System On Chip/Nvidia/Tegra/Tegra/B0A5FE7D6DB8/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/9B157B83A5>) |
| 0b05:17cb | ASUSTek Computer | Broadcom BCM20702A0 Bluetooth        | 1     | btusb      | [226E0DBC7F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/C59DA5B2FE63/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/226E0DBC7F>) |
| 0bda:8771 | Realtek Semic... | Bluetooth Radio                      | 1     | btusb      | [776ED378CB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/00C8F9395248/POP!_OS-21.10/5.13.0-1008-RASPI/AARCH64/776ED378CB>) |
| 0cf3:e500 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 1     | btusb      | [B2621747DB](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-21.04/4.9.253-TEGRA/AARCH64/B2621747DB>) |
| 0e5e:6622 | Conwise Techn... | CW6622                               | 1     | btusb      | [55067D6AFE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/22FA5E73FA5C/UBUNTU-MATE-20.04/4.9.277-119/AARCH64/55067D6AFE>) |
| 13d3:3548 | IMC Networks     | Bluetooth Radio                      | 1     | rtk_btu... | [DB3EB249A1](<System On Chip/Nvidia/Tegra/Tegra/A2D34F7D05EB/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DB3EB249A1>) |
| 21ee:1100 | Broadcom         | Bluetooth V3.0 USB Device            | 1     | btusb      | [5E07806B7E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi ? Rev 1.0/D8FBFD41D06C/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/5E07806B7E>) |
| 7392:a611 | Edimax Techno... | EW-7611ULB 802.11b/g/n and Blueto... | 1     | btusb      | [52F0B7D3FA](<System On Chip/Sony UK/Raspberry/Raspberry Pi 3 Model B/412890FF8DE8/DEBIAN-10/4.19.0-8-ARM64/AARCH64/52F0B7D3FA>) |
| 8087:0032 | Intel            | AX210 Bluetooth                      | 1     | btusb      | [1CCD6EEE0E](<System On Chip/Nvidia/Jetson/Jetson Nano Developer Kit/6563B51893AF/UBUNTU-21.04/5.12.6-JETSON-NANO/AARCH64/1CCD6EEE0E>) |
| 8087:0a2a | Intel            | Bluetooth wireless interface         | 1     | btusb      | [C72F8C76F7](<System On Chip/Nvidia/Tegra/Tegra/B2307FE84F73/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/C72F8C76F7>) |

### Camera (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:075d | Microsoft        | LifeCam Cinema                       | 6     | snd_usb... | [B468496893](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6966851E18EE/UBUNTU-21.04/5.11.0-1003-RASPI/AARCH64/B468496893>) |
| 046d:082d | Logitech         | HD Pro Webcam C920                   | 5     | snd_usb... | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 046d:0825 | Logitech         | Webcam C270                          | 4     | snd_usb... | [342CCD2ECF](<System On Chip/Rockchip/Others/Others/46F00341A611/DEBIAN-11/4.4.190-1233-ROCKCHIP-AYUFAN-GD3F1BE0ED310/AARCH64/342CCD2ECF>) |
| 04e8:6860 | Samsung Elect... | Galaxy A5 (MTP)                      | 4     | usbfs      | [A8BD03AC5B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6DB17957B8F8/RASPBIAN-10/5.10.63-V8+/AARCH64/A8BD03AC5B>) |
| 1908:2311 | GEMBIRD          | USB2.0 PC CAMERA                     | 3     | uvcvideo   | [FF4D3F33C9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/38A846689288/ENDLESS-4.0.2/5.11.0-35-GENERIC/AARCH64/FF4D3F33C9>) |
| 05a3:9331 | ARC Internati... | Camera                               | 2     | snd_usb... | [53A8BE279F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/1BDCF5CF7214/UBUNTU-BUDGIE-21.04/5.11.0-1015-RASPI/AARCH64/53A8BE279F>) |
| 0ac8:3420 | Z-Star Microe... | Venus USB2.0 Camera                  | 2     | snd_usb... | [FF6CAF6571](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/12D25371B9C9/RASPBIAN-10/4.19.75-V7L+/ARMV7L/FF6CAF6571>) |
| 1004:633e | LG Electronics   | LM-X420xxx/G2/G3 Android Phone (M... | 2     | usbfs      | [4298DA2E03](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E726DE6BBF8A/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/4298DA2E03>) |
| 1224:2a25 | Jieli Technology | USB PHY 2.0                          | 2     | snd_usb... | [1CB7F5BA83](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/FAA57A34044F/RASPBIAN-11/5.10.63-V7+/ARMV7L/1CB7F5BA83>) |
| 1b3f:2247 | Generalplus T... | GENERAL WEBCAM                       | 2     | snd_usb... | [D62808AD60](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B06C6E42A5A0/UBUNTU-21.04/5.11.0-1021-RASPI/AARCH64/D62808AD60>) |
| 1e4e:0109 | Cubeternet       | EtronTech CMOS based eSP570 WebCa... | 2     | snd_usb... | [54592EC1A2](<System On Chip/Nvidia/Tegra/Tegra/54129FFCE65C/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/54592EC1A2>) |
| 2a70:9012 | OnePlus Techn... | SM8150-MTP _SN:A05FE1A2              | 2     | usbfs      | [1E21B25BBA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/786472A5BF4A/MANJARO-ARM-22.01/5.10.88-1-MANJARO-ARM-RPI/AARCH64/1E21B25BBA>) |
| 041e:4095 | Creative Tech... | Live! Cam Sync HD [VF0770]           | 1     | snd_usb... | [F5CA9E190E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/866573591706/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/F5CA9E190E>) |
| 043e:3012 | LG Electronics   | AN-VC500 Camera                      | 1     | snd_usb... | [5A08EE43A7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F140D978D199/RASPBIAN-10/5.10.60-V7+/ARMV7L/5A08EE43A7>) |
| 0458:7060 | KYE Systems (... | iSlim 1320                           | 1     | uvcvideo   | [537289447F](<System On Chip/Hardkernel/ODROID-C/ODROID-C2/4172A3F60C92/UBUNTU-MATE-20.04/3.16.85-62/AARCH64/537289447F>) |
| 045e:076d | Microsoft        | LifeCam HD-5000                      | 1     | uvcvideo   | [FC5AEB0B10](<System On Chip/Others/Unknown/Unknown Product/E710D01431EC/OPENMANDRIVA-4.50/5.11.11-SERVER-1OMV4050/AARCH64/FC5AEB0B10>) |
| 046d:081b | Logitech         | Webcam C310                          | 1     | snd_usb... | [63055A9C60](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/986E2A73F333/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/63055A9C60>) |
| 046d:0821 | Logitech         | HD Webcam C910                       | 1     | uvcvideo   | [E8C67DC172](<System On Chip/Nvidia/Tegra/Tegra/49846891E392/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/E8C67DC172>) |
| 046d:0823 | Logitech         | HD Webcam B910                       | 1     | uvcvideo   | [6C59E641C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/A98FE60A0893/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/6C59E641C3>) |
| 046d:0826 | Logitech         | HD Webcam C525                       | 1     | uvcvideo   | [980B14C09A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/FECC17F56857/RASPBIAN-11/5.10.92-V7L+/ARMV7L/980B14C09A>) |
| 046d:082c | Logitech         | HD Webcam C615                       | 1     | uvcvideo   | [BE96BBE4F4](<System On Chip/Nvidia/Tegra/Tegra/1F5B34B20D8B/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/BE96BBE4F4>) |
| 046d:0894 | Logitech         | CrystalCam                           | 1     | snd_usb... | [E65C4D13BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/E65C4D13BF>) |
| 046d:0991 | Logitech         | QuickCam Pro for Notebooks           | 1     | snd_usb... | [1B7191941B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/92C928CEBED8/UBUNTU-20.04/5.4.0-1008-RASPI/AARCH64/1B7191941B>) |
| 046d:09a4 | Logitech         | QuickCam E 3500                      | 1     | snd_usb... | [DC1D4B5FF5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D75482517216/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/DC1D4B5FF5>) |
| 0471:0311 | Philips (or NXP) | PCVC740K ToUcam Pro [pwc]            | 1     | pwc        | [742BE0320C](<System On Chip/Nvidia/Tegra/Tegra/216EBFEFA071/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/742BE0320C>) |
| 057e:030a | Nintendo         | USB Camera                           | 1     | uvcvideo   | [8075B94007](<System On Chip/sunxi/Others/Others/108D12CE0E97/UBUNTU-20.04/5.10.60-SUNXI64/AARCH64/8075B94007>) |
| 058f:3861 | Alcor Micro      | USB 2.0 PC Camera                    | 1     | snd_usb... | [A7E12A6A67](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2BB6856D88E4/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/A7E12A6A67>) |
| 05a3:9230 | ARC Internati... | Camera                               | 1     | uvcvideo   | [2511C4E555](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5D8866DB4632/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/2511C4E555>) |
| 05ac:8508 | Apple            | iSight in LED Cinema Display         | 1     | uvcvideo   | [6ADCA880A0](<System On Chip/Nvidia/Tegra/Tegra/E316CF040727/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/6ADCA880A0>) |
| 05e3:0510 | Genesys Logic    | Camera                               | 1     | uvcvideo   | [690F707A87](<System On Chip/Nvidia/Tegra/Tegra/E0E6BD12DF48/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/690F707A87>) |
| 0ac8:3450 | Z-Star Microe... | Vimicro USB Camera (Altair)          | 1     | uvcvideo   | [70271C9802](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/70271C9802>) |
| 0ac8:c40a | Z-Star Microe... | A4 TECH USB2.0 PC Camera J           | 1     | snd_usb... | [5FC70F3F84](<System On Chip/Nvidia/Tegra/Tegra/A5CD0129FDE8/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/5FC70F3F84>) |
| 0bda:5760 | Realtek Semic... | Integrated_Webcam_FHD                | 1     | uvcvideo   | [E688396A21](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3EB3867D6F0/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/E688396A21>) |
| 0c45:6321 | Microdia         | HP Integrated Webcam                 | 1     | uvcvideo   | [BF8ABDFB09](<System On Chip/Others/Unknown/Unknown Product/4BE11779C833/FEDORA-35/5.14.9-300.FC35.AARCH64/AARCH64/BF8ABDFB09>) |
| 0c45:632e | Microdia         | USB 2.0 Camera                       | 1     | uvcvideo   | [1E9CA3C359](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/63627667A60B/RASPBIAN-10/5.10.17-V7+/ARMV7L/1E9CA3C359>) |
| 0c45:6366 | Microdia         | Webcam Vitade AF                     | 1     | snd_usb... | [DF9A0F37EB](<System On Chip/Nvidia/Tegra/Tegra/1F5B34B20D8B/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DF9A0F37EB>) |
| 0c46:64ab | WaveRider Com... | USB 2.0 Camera                       | 1     | snd_usb... | [C4324B9288](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/7B4BA0B15A17/UBUNTU-20.10/5.8.0-1007-RASPI/AARCH64/C4324B9288>) |
| 13d3:784b | IMC Networks     | XHC Camera                           | 1     | uvcvideo   | [B246EBE37C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/5532B9D494DE/RASPBIAN-10/5.10.17-V7+/ARMV7L/B246EBE37C>) |
| 1903:8328 |                  | HD camera                            | 1     | snd_usb... | [A0E1815666](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5879101AD455/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/A0E1815666>) |
| 1908:2310 | GEMBIRD          | USB2.0 PC CAMERA                     | 1     | snd_usb... | [B2621747DB](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-21.04/4.9.253-TEGRA/AARCH64/B2621747DB>) |
| 1b3f:1167 | Generalplus T... | GENERAL WEBCAM                       | 1     | snd_usb... | [81FB7C8D99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3574C7CD7F7C/RASPBIAN-11/5.10.63-V7L+/ARMV7L/81FB7C8D99>) |
| 1bcf:2281 | Sunplus Innov... | SPCA2281 Web Camera                  | 1     | snd_usb... | [7AEB73D109](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/378385C3965D/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/7AEB73D109>) |
| 1e4e:0102 | Cubeternet       | GL-UPC822 UVC WebCam                 | 1     | uvcvideo   | [FD8D00A7FA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4C21E716C190/DEBIAN-10/5.6.19-RT12-V8+/AARCH64/FD8D00A7FA>) |
| 2b03:f780 | Technologies     | ZED 2                                | 1     | uvcvideo   | [7616B8F6B7](<System On Chip/Nvidia/Tegra/Tegra/0A0982FDE24A/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/7616B8F6B7>) |
| 328f:003f | EMEET            | HD Webcam C960                       | 1     | snd_usb... | [C7B32FF620](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4EC359174BBB/KUBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/C7B32FF620>) |
| 534d:2109 | MacroSilicon     | USB Video                            | 1     | usbhid     | [295E0059AF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E8540BA672CD/UBUNTU-20.04/5.4.0-1019-RASPI/AARCH64/295E0059AF>) |
| fefe:4321 | Ruision          | UVC Camera                           | 1     | uvcvideo   | [D17AFC3CF8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/92E21CFB7C8C/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/D17AFC3CF8>) |

### Cdrom (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 152d:2329 | JMicron Techn... | JM20329 SATA Bridge                  | 6     | usb_sto... | [D1FC84613E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/1369F49F8A13/RASPBIAN-11/5.10.63-V7+/ARMV7L/D1FC84613E>) |
| 152e:2571 | LG (HLDS)        | GP08NU6W DVD-RW                      | 6     | uas, us... | [9048879465](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BB83E3AF30AE/UBUNTU-21.04/5.11.0-1021-RASPI/AARCH64/9048879465>) |
| 0bda:1a2b | Realtek Semic... | RTL8188GU 802.11n WLAN Adapter (D... | 1     | usb_sto... | [D5C172D8B6](<System On Chip/TI/AM335x/AM335x BeagleBone Black/C686C868F203/UBUNTU-18.04/5.4.47-BONE30/ARMV7L/D5C172D8B6>) |
| 0e8d:1806 | MediaTek         | Samsung SE-208 Slim Portable DVD ... | 1     | usb_sto... | [7FD7E42E53](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/77C6901CC1FB/UBUNTU-20.10/5.8.0-1008-RASPI/AARCH64/7FD7E42E53>) |
| 0e8d:1836 | MediaTek         | Samsung SE-S084 Super WriteMaster... | 1     | usb_sto... | [57BDF81032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F65C49EF596B/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/57BDF81032>) |
| 0e8d:1956 | MediaTek         | Samsung SE-506 Portable BluRay Di... | 1     | usb_sto... | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 13fd:1040 | Initio           | INIC-1511L PATA Bridge               | 1     | usb_sto... | [53A8BE279F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/1BDCF5CF7214/UBUNTU-BUDGIE-21.04/5.11.0-1015-RASPI/AARCH64/53A8BE279F>) |
| 152e:1640 | LG (HLDS)        | INIC-1605 SATA Bridge                | 1     | usb_sto... | [454D02D902](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/02429B9557C8/MANJARO-ARM/4.19.127-1-MANJARO-ARM/AARCH64/454D02D902>) |
| 8564:8000 | Transcend        | TRANSCEND                            | 1     | usb_sto... | [FDC6B746FE](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2FA63A79DB67/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/FDC6B746FE>) |

### Chipcard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 058f:9540 | Alcor Micro      | AU9540 Smartcard Reader              | 1     |            | [E50D894B93](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/1C59F83A8416/UBUNTU-MATE-20.04/5.4.0-1025-RASPI/AARCH64/E50D894B93>) |

### Disk (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 174c:55aa | ASMedia Techn... | ASM1051E SATA 6Gb/s bridge, ASM10... | 59    | usb_sto... | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 152d:0578 | JMicron Techn... | JMS578 SATA 6Gb/s                    | 32    | usb_sto... | [AFF575B483](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/662506DEB22E/DEBIAN-11/5.10.92-V8+/AARCH64/AFF575B483>) |
| 14cd:1212 | Super Top        | microSD card reader (SY-T18)         | 16    | uas, us... | [53A2BB987D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B7CAE3493BED/RASPBIAN-10/5.10.63-V7+/ARMV7L/53A2BB987D>) |
| 0781:5583 | SanDisk          | Ultra Fit                            | 11    | uas, us... | [591BEDF88F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/41DD4743631C/UBUNTU-21.04/5.11.0-1027-RASPI/AARCH64/591BEDF88F>) |
| 152d:0562 | JMicron Techn... | JMS567 SATA 6Gb/s bridge             | 11    | uas        | [64AA8D06F4](<System On Chip/theobroma-systems/puma_rk/puma_rk3399/216F71D2BB0E/FEDORA-34/5.13.16-200.FC34.AARCH64/AARCH64/64AA8D06F4>) |
| 090c:1000 | Silicon Motion   | USB                                  | 10    | usb_sto... | [511563DFC4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B380287AFB60/POP!_OS-21.10/5.13.0-1017-RASPI/AARCH64/511563DFC4>) |
| 0951:1666 | Kingston Tech... | DataTraveler 100 G3/G4/SE9 G2        | 10    | usb_sto... | [FF4D3F33C9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/38A846689288/ENDLESS-4.0.2/5.11.0-35-GENERIC/AARCH64/FF4D3F33C9>) |
| 05e3:0749 | Genesys Logic    | USB3.0 Card Reader                   | 9     | uas, us... | [39FDB94E1C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/28AFDBAFD1CF/RASPBIAN-10/5.10.17-V7L+/ARMV7L/39FDB94E1C>) |
| 2109:0711 | VIA Labs         | VL711 SATA 6Gb/s bridge              | 9     | uas        | [16D3C3D359](<System On Chip/theobroma-systems/puma_rk/puma_rk3399/C7048E225E39/FEDORA-34/5.14.9-200.FC34.AARCH64/AARCH64/16D3C3D359>) |
| 0781:5581 | SanDisk          | Ultra                                | 8     | uas, us... | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 174c:0825 | ASMedia Techn... | X825                                 | 8     | uas        | [6268790A76](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/27B41BF22A1E/UBUNTU-21.04/5.11.0-1019-RASPI/AARCH64/6268790A76>) |
| 0080:a001 | Assmann Elect... | Digitus DA-71114 SATA                | 6     | uas        | [C31954F957](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E9A51311359B/UBUNTU-20.04/5.4.0-1053-RASPI/AARCH64/C31954F957>) |
| 04e8:61f5 | Samsung Elect... | Portable SSD T5                      | 6     | uas        | [D2B091C26B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BCB91EF70389/MANJARO-ARM-22.01/5.15.24-1-MANJARO-ARM-RPI/AARCH64/D2B091C26B>) |
| 1058:2624 | Western Digit... | easystore 2624                       | 6     | uas, us... | [123113DDFD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A954C80F17DD/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/123113DDFD>) |
| 152d:2338 | JMicron Techn... | JM20337 Hi-Speed USB to SATA & PA... | 6     | uas, us... | [9EDD5667E5](<System On Chip/Nvidia/Tegra/Tegra/6981659F8C33/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/9EDD5667E5>) |
| 174c:1153 | ASMedia Techn... | ASM1153 SATA 3Gb/s bridge            | 6     | uas        | [D0D26EC246](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/44F1AE604EF6/UBUNTU-MATE-20.10/5.8.0-1032-RASPI/AARCH64/D0D26EC246>) |
| 1058:25e1 | Western Digit... | My Passport 25E1                     | 5     | uas, us... | [557A4ACED6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/AA9ED3B46CF4/UBUNTU-20.10/5.8.0-1020-RASPI/AARCH64/557A4ACED6>) |
| 152d:1561 | JMicron Techn... | JMS561U two ports SATA 6Gb/s bridge  | 5     | uas        | [FAEF08AF10](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E686329F359A/UBUNTU-MATE-20.04/5.10.27-V7+/ARMV7L/FAEF08AF10>) |
| 152d:2590 | JMicron Techn... | JMS567 SATA 6Gb/s bridge             | 5     | uas        | [0B96F93C52](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6966851E18EE/UBUNTU-20.04/5.15.24-BCM2711/AARCH64/0B96F93C52>) |
| 1908:0226 | GEMBIRD          | Mass-Storage                         | 5     | uas, us... | [7B3700265A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E4FE3E3CD572/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/7B3700265A>) |
| 7825:a2a4 | Other World C... | BD-RE WH16NS40                       | 5     | uas        | [6C9A78F854](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/20CA46FB02F1/DEBIAN-11/5.10.63-V8+/AARCH64/6C9A78F854>) |
| 048d:1234 | Integrated Te... | Mass storage                         | 4     | uas, us... | [AFF575B483](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/662506DEB22E/DEBIAN-11/5.10.92-V8+/AARCH64/AFF575B483>) |
| 0781:5575 | SanDisk          | Cruzer Glide                         | 4     | uas, us... | [3D8D1682DD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/B2A0C4665DE3/UBUNTU-21.04/5.4.0-1028-RASPI/AARCH64/3D8D1682DD>) |
| 0781:5591 | SanDisk          | Ultra Flair                          | 4     | uas, us... | [DA8C18883D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6966851E18EE/POP!_OS-21.10/5.13.0-1011-RASPI/AARCH64/DA8C18883D>) |
| 0bc2:ab24 | Seagate          | Backup Plus Portable Drive           | 4     | uas        | [053E9AC0E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BA4A62CA68F9/RASPBIAN-10/5.10.63-V7+/ARMV7L/053E9AC0E2>) |
| 152d:0561 | JMicron Techn... | JMS551 - Sharkoon SATA QuickPort Duo | 4     | uas        | [0892AC4796](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1015-RASPI/AARCH64/0892AC4796>) |
| 174c:1156 | ASMedia Techn... | Forty                                | 4     | uas        | [FAE9412031](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/79256D3F1194/DEBIAN-11/5.10.92-V8+/AARCH64/FAE9412031>) |
| 18a5:0302 | Verbatim         | STORE N GO                           | 4     | usb_sto... | [095D666164](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3BD4A7F3FCFE/UBUNTU-21.04/5.11.0-1023-RASPI/AARCH64/095D666164>) |
| 8564:1000 | Transcend        | JetFlash                             | 4     | usb_sto... | [077445F205](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6966851E18EE/DEBIAN-10/5.10.17-V8+/AARCH64/077445F205>) |
| 05e3:0751 | Genesys Logic    | microSD Card Reader                  | 3     | uas, us... | [E5ED3CE077](<System On Chip/Others/Others/Others/098BC2088E60/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/E5ED3CE077>) |
| 0781:5567 | SanDisk          | Cruzer Blade                         | 3     | uas, us... | [6E1FBE4DDE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B7BD09B3EC83/UBUNTU-MATE-20.04/4.9.277-117/AARCH64/6E1FBE4DDE>) |
| 0781:5588 | SanDisk          | Extreme Pro                          | 3     | usb_sto... | [FBD81069CC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/03B2FCD92C32/GENTOO-2.7/5.11.0-V7L+/ARMV7L/FBD81069CC>) |
| 0781:558c | SanDisk          | Extreme SSD                          | 3     | uas        | [FFC6A87703](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/74B1203C3BAC/RASPBIAN-11/5.10.92-V7L+/ARMV7L/FFC6A87703>) |
| 0bda:0306 | Realtek Semic... | USB3.0-CRW                           | 3     | usb_sto... | [F37642F9C9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/1D7457665804/RASPBIAN-11/5.10.63-V7+/ARMV7L/F37642F9C9>) |
| 0bda:9210 | Realtek Semic... | RTL9210                              | 3     | uas        | [1742E1C6A9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/16F02FCDBB88/UBUNTU-21.04/5.11.0-1015-RASPI/AARCH64/1742E1C6A9>) |
| 13fe:6400 | Kingston Tech... | USB DISK 3.0                         | 3     | usb_sto... | [FEF12EE80A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/ABCE585EFD30/DEBIAN-10/5.10.17-V8+/AARCH64/FEF12EE80A>) |
| 152d:0567 | JMicron Techn... | JMS567 SATA 6Gb/s bridge             | 3     | uas        | [308808FB7A](<System On Chip/Others/Others/Others/6B4EAAD93D3C/DEBIAN-10/5.10.11-V8+/AARCH64/308808FB7A>) |
| 152d:0580 | JMicron Techn... | USB 3.1 Storage Device               | 3     | uas        | [B6BC1B40B7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B257A3ECD634/UBUNTU-21.10/5.13.0-1009-RASPI/AARCH64/B6BC1B40B7>) |
| 152d:0583 | JMicron Techn... | USB 3.0                              | 3     | uas        | [267F559E91](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B/D4818413E3EF/GENTOO-2.7/5.10.11-V8/AARCH64/267F559E91>) |
| 1f75:0611 | Innostor Tech... | IS611 SATA/PATA Bridge Controller    | 3     | uas, us... | [A63AF8E149](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/40D0D2E0539C/XUBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/A63AF8E149>) |
| 2109:0715 | VIA Labs         | VL817 SATA Adaptor                   | 3     | uas        | [75490E3FD0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E8540BA672CD/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/75490E3FD0>) |
| 0480:a202 | Toshiba America  | Canvio Basics HDD                    | 2     | uas, us... | [56FD2119F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DCA856441D51/RASPBIAN-11/5.10.92-V8+/AARCH64/56FD2119F8>) |
| 0480:b207 | Toshiba America  | Canvio Ready                         | 2     | uas        | [D8A93CCE54](<System On Chip/sunxi/Others/Others/5EDD4F5F3927/DEBIAN-9/4.19.62-SUNXI/ARMV7L/D8A93CCE54>) |
| 04e8:4001 | Samsung Elect... | PSSD T7                              | 2     | uas        | [FE662B5B36](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3D5DBFC613F5/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/FE662B5B36>) |
| 0578:0578 | Intrinsix        | JMS580                               | 2     | uas        | [7CDE4A4D40](<System On Chip/Nvidia/Tegra/Tegra/57BEF78164BC/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/7CDE4A4D40>) |
| 0781:5571 | SanDisk          | Cruzer Fit                           | 2     | uas, us... | [990E5C71B2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EBA7FC9211A8/XUBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/990E5C71B2>) |
| 0781:5572 | SanDisk          | Cruzer Switch                        | 2     | usb_sto... | [DD8F825A76](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/EDFEB1D21F33/DEBIAN-10/4.19.122-2-OSMC/ARMV7L/DD8F825A76>) |
| 0781:558a | SanDisk          | Ultra                                | 2     | uas, us... | [FAFFA9BA50](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/108D422AD61E/UBUNTU-21.04/5.11.0-1024-RASPI/AARCH64/FAFFA9BA50>) |
| 0781:5597 | SanDisk          | Cruzer Glide 3.0                     | 2     | uas, us... | [06612D9E40](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/56BD017D9BD5/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/06612D9E40>) |
| 090c:2000 | Silicon Motion   | USB DISK                             | 2     | uas, us... | [77691E80A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8F3A96026FD0/RASPBIAN-10/5.10.63-V7L+/ARMV7L/77691E80A4>) |

### Dvb card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:2838 | Realtek Semic... | RTL2838 DVB-T                        | 10    | dvb_usb... | [CF8776E11F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/DE55C8A593CC/KALI-2021.4/5.4.83-RE4SON-V8+/AARCH64/CF8776E11F>) |
| 0bda:2832 | Realtek Semic... | RTL2832U DVB-T                       | 2     | dvb_usb... | [6A8CCD44AA](<System On Chip/Pine Microsystems/PineTab/PineTab/7455DD389474/ARCHARM/5.10.19-4-DANCTNIX/AARCH64/6A8CCD44AA>) |
| 07ca:1835 | AVerMedia Tec... | A835B                                | 1     | dvb_usb... | [44857FE932](<System On Chip/Others/Others/Others/7F1F3D0DAB2B/RASPBIAN-10/5.4.51-V7+/ARMV7L/44857FE932>) |
| 15f4:0131 | HanfTek          | Astrometa DVB-T/T2/C FM & DAB rec... | 1     | dvb_usb... | [78A0A02DF1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/EA281E0179D9/UBUNTU-20.10/5.8.0-1007-RASPI/AARCH64/78A0A02DF1>) |

### Fingerprint reader (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 27c6:5117 | Shenzhen Good... | Fingerprint Reader                   | 1     |            | [BD05C84564](<System On Chip/HUAWEI/W510/W510 PGU-WBY0/5583E74879DC/UBUNTU-21.04/5.8.0-36-GENERIC/AARCH64/BD05C84564>) |

### Gamepad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:028e | Microsoft        | Xbox360 Controller                   | 3     | xpad       | [46D79DE66E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3E699A4BBDB1/UBUNTU-21.10/5.13.0-1009-RASPI/AARCH64/46D79DE66E>) |
| 046d:c21d | Logitech         | F310 Gamepad [XInput Mode]           | 1     | xpad       | [4DF0FC88BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CCAD18E99D36/UBUNTU-20.10/5.8.0-1011-RASPI/AARCH64/4DF0FC88BF>) |
| 07b5:0213 | Mega World In... | Thrustmaster Firestorm Digital 3 ... | 1     | usbhid     | [70271C9802](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/70271C9802>) |
| 0e6f:0213 | Logic3           | Afterglow Gamepad for Xbox 360       | 1     | xpad       | [FEF12EE80A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/ABCE585EFD30/DEBIAN-10/5.10.17-V8+/AARCH64/FEF12EE80A>) |
| 0e6f:0413 | Logic3           | Afterglow AX.1 Gamepad for Xbox 360  | 1     | xpad       | [04DA44A3D2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/A72EE6CE5710/UBUNTU-18.04/4.19.97-V8-27/AARCH64/04DA44A3D2>) |
| 2563:0575 | ShenZhen Shan... | ZD-V+ Wired Gaming Controller        | 1     | usbhid     | [6FB5AE90DB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/EF9198620015/UBUNTU-19.10/5.3.0-1019-RASPI2/AARCH64/6FB5AE90DB>) |

### Hub (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1d6b:0002 | Linux Foundation | 2.0 root hub                         | 932   | hub        | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 1d6b:0003 | Linux Foundation | 3.0 root hub                         | 775   | hub        | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 2109:3431 | VIA Labs         | Hub                                  | 637   | hub        | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 05e3:0610 | Genesys Logic    | Hub                                  | 93    | hub        | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 1d6b:0001 | Linux Foundation | 1.1 root hub                         | 67    | hub        | [8E3573295D](<System On Chip/Hardkernel/Odroid/Odroid XU4/A7DC4E2AD6C4/UBUNTU-MATE-20.04/5.4.167-240/ARMV7L/8E3573295D>) |
| 0424:9514 | Microchip Tec... | SMC9514 Hub                          | 61    | hub        | [0C406A0FB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/657E70087A27/RASPBIAN-9/5.15.21-V7+/ARMV7L/0C406A0FB6>) |
| 0bda:5411 | Realtek Semic... | 4-Port USB 2.0 Hub                   | 54    | hub        | [D2B091C26B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BCB91EF70389/MANJARO-ARM-22.01/5.15.24-1-MANJARO-ARM-RPI/AARCH64/D2B091C26B>) |
| 0bda:0411 | Realtek Semic... | 2-Port USB 3.0 Hub                   | 51    | hub        | [D2B091C26B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BCB91EF70389/MANJARO-ARM-22.01/5.15.24-1-MANJARO-ARM-RPI/AARCH64/D2B091C26B>) |
| 1a40:0101 | Terminus Tech... | Hub                                  | 46    | hub        | [C7B32FF620](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4EC359174BBB/KUBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/C7B32FF620>) |
| 0424:2514 | Microchip Tec... | USB 2.0 Hub                          | 45    | hub        | [053E9AC0E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BA4A62CA68F9/RASPBIAN-10/5.10.63-V7+/ARMV7L/053E9AC0E2>) |
| 05e3:0608 | Genesys Logic    | Hub                                  | 29    | hub        | [06BE200111](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8173C1117C20/RASPBIAN-11/5.10.92+/ARMV6L/06BE200111>) |
| 2109:2817 | VIA Labs         | USB2.0 Hub                           | 15    | hub        | [0892AC4796](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1015-RASPI/AARCH64/0892AC4796>) |
| 214b:7250 | Huasheng Elec... | USB2.0 HUB                           | 14    | hub        | [C3E2B43E74](<System On Chip/Khadas/VIM/VIM2/61FE2BBAE08B/XUBUNTU-18.04/5.0.0-AML-S912-GF2F3A8C1A-DIRTY/AARCH64/C3E2B43E74>) |
| 05e3:0616 | Genesys Logic    | hub                                  | 13    | hub        | [8E3573295D](<System On Chip/Hardkernel/Odroid/Odroid XU4/A7DC4E2AD6C4/UBUNTU-MATE-20.04/5.4.167-240/ARMV7L/8E3573295D>) |
| 05e3:0626 | Genesys Logic    | USB3.1 Hub                           | 11    | hub        | [9EF99E18E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BB768FB03CCD/MANJARO-ARM/5.10.52-2-MANJARO-ARM/AARCH64/9EF99E18E2>) |
| 2109:0817 | VIA Labs         | USB3.0 Hub                           | 11    | hub        | [0892AC4796](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1015-RASPI/AARCH64/0892AC4796>) |
| 2109:2813 | VIA Labs         | VL813 Hub                            | 10    | hub        | [77691E80A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8F3A96026FD0/RASPBIAN-10/5.10.63-V7L+/ARMV7L/77691E80A4>) |
| 2109:0813 | VIA Labs         | VL813 Hub                            | 9     | hub        | [77691E80A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8F3A96026FD0/RASPBIAN-10/5.10.63-V7L+/ARMV7L/77691E80A4>) |
| 0424:9512 | Microchip Tec... | SMC9512/9514 USB Hub                 | 8     | hub        | [973297C20F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A99C7AB3E4AF/RASPBIAN-11/5.4.150+/ARMV6L/973297C20F>) |
| 05e3:0612 | Genesys Logic    | Hub                                  | 8     | hub        | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 05e3:0620 | Genesys Logic    | USB3.1 Hub                           | 8     | hub        | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 0bda:0401 | Realtek Semic... | USB3.0 Hub                           | 8     | hub        | [6C9A78F854](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/20CA46FB02F1/DEBIAN-11/5.10.63-V8+/AARCH64/6C9A78F854>) |
| 0bda:5401 | Realtek Semic... | RTL 8153 USB 3.0 hub with gigabit... | 8     | hub        | [6C9A78F854](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/20CA46FB02F1/DEBIAN-11/5.10.63-V8+/AARCH64/6C9A78F854>) |
| 1a40:0201 | Terminus Tech... | FE 2.1 7-port Hub                    | 8     | hub        | [1E21B25BBA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/786472A5BF4A/MANJARO-ARM-22.01/5.10.88-1-MANJARO-ARM-RPI/AARCH64/1E21B25BBA>) |
| 1a40:0801 | Terminus Tech... | USB 2.0 Hub                          | 8     | hub        | [904F2D4F21](<System On Chip/Nvidia/Tegra/Tegra/C04445AE216D/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/904F2D4F21>) |
| 0b95:6802 | ASIX Electronics | AX68002 KVM Switch SoC               | 7     | hub        | [F8FA8FDC4D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3C2F4FDA790A/RASPBIAN-11/5.10.63-V7L+/ARMV7L/F8FA8FDC4D>) |
| 05ac:1006 | Apple            | Hub in Aluminum Keyboard             | 6     | apple_m... | [55067D6AFE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/22FA5E73FA5C/UBUNTU-MATE-20.04/4.9.277-119/AARCH64/55067D6AFE>) |
| 0bda:0489 | Realtek Semic... | 4-Port USB 3.0 Hub                   | 6     | hub        | [077899579F](<System On Chip/Nvidia/Tegra/Tegra/EBC4CC1806ED/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/077899579F>) |
| 0bda:5489 | Realtek Semic... | 4-Port USB 2.0 Hub                   | 6     | hub        | [077899579F](<System On Chip/Nvidia/Tegra/Tegra/EBC4CC1806ED/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/077899579F>) |
| 045b:0209 | Hitachi          | Hub                                  | 4     | hub        | [4298DA2E03](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E726DE6BBF8A/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/4298DA2E03>) |
| 045b:0210 | Hitachi          | Hub                                  | 4     | hub        | [4298DA2E03](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E726DE6BBF8A/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/4298DA2E03>) |
| 058f:9254 | Alcor Micro      | Hub                                  | 4     | hub        | [77691E80A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8F3A96026FD0/RASPBIAN-10/5.10.63-V7L+/ARMV7L/77691E80A4>) |
| 05ac:1003 | Apple            | Hub in Pro Keyboard [Mitsumi, A1048] | 4     | hub        | [E79D569EAC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8144B4823136/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/E79D569EAC>) |
| 2109:2811 | VIA Labs         | Hub                                  | 4     | hub        | [F8FA8FDC4D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3C2F4FDA790A/RASPBIAN-11/5.10.63-V7L+/ARMV7L/F8FA8FDC4D>) |
| 413c:1003 | Dell             | Keyboard Hub                         | 4     | hub        | [33593B35B3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06F5C52ACD4E/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/33593B35B3>) |
| 0424:2512 | Microchip Tec... | USB 2.0 Hub                          | 3     | hub        | [7616B8F6B7](<System On Chip/Nvidia/Tegra/Tegra/0A0982FDE24A/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/7616B8F6B7>) |
| 04b4:6502 | Cypress Semic... | CY4609                               | 3     | hub        | [16D3C3D359](<System On Chip/theobroma-systems/puma_rk/puma_rk3399/C7048E225E39/FEDORA-34/5.14.9-200.FC34.AARCH64/AARCH64/16D3C3D359>) |
| 05ac:1002 | Apple            | Extended Keyboard Hub [Mitsumi]      | 3     | hub        | [10D6088BF3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6C7B34346A0D/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/10D6088BF3>) |
| 05e3:0617 | Genesys Logic    | USB3.1 Hub                           | 3     | hub        | [E65C4D13BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/E65C4D13BF>) |
| 0b95:6804 | ASIX Electronics | AX68004                              | 3     | hub        | [DE0E6691CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06196A934E36/DEBIAN-11/5.10.63-V8+/AARCH64/DE0E6691CD>) |
| 14cd:8601 | Super Top        | 4-Port hub                           | 3     | hub        | [3BD9548BAB](<System On Chip/Hardkernel/ODROID-C/ODROID-C4/CB901DF2A096/UBUNTU-MATE-20.04/4.9.277-76/AARCH64/3BD9548BAB>) |
| 2109:0815 | VIA Labs         | USB3.0 Hub                           | 3     | hub        | [87CF7F053C](<System On Chip/Nvidia/Tegra/Tegra/E271192D27D5/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/87CF7F053C>) |
| 2109:2812 | VIA Labs         | VL812 Hub                            | 3     | hub        | [7AEB73D109](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/378385C3965D/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/7AEB73D109>) |
| 2109:2815 | VIA Labs         | USB2.0 Hub                           | 3     | hub        | [87CF7F053C](<System On Chip/Nvidia/Tegra/Tegra/E271192D27D5/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/87CF7F053C>) |
| 2109:8110 | VIA Labs         | Hub                                  | 3     | hub        | [0A7252BA46](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/E2CC6674DB28/RASPBIAN-10/5.4.83-V7L+/ARMV7L/0A7252BA46>) |
| 03eb:0902 | Atmel            | 4-Port Hub                           | 2     | hub        | [8AD4DEE3B1](<System On Chip/Samsung Electronics/UNIVERSAL8890/UNIVERSAL8890 board based on EXYNOS8890/7892F79EB76E/KALI-2020.4/3.18.91.NETHUNTER-WIRUSMOD-V1.2+/AARCH64/8AD4DEE3B1>) |
| 0424:2412 | Microchip Tec... | Hub                                  | 2     | hub        | [53A2BB987D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B7CAE3493BED/RASPBIAN-10/5.10.63-V7+/ARMV7L/53A2BB987D>) |
| 04b4:6500 | Cypress Semic... | Cypress Hub                          | 2     | hub        | [16D3C3D359](<System On Chip/theobroma-systems/puma_rk/puma_rk3399/C7048E225E39/FEDORA-34/5.14.9-200.FC34.AARCH64/AARCH64/16D3C3D359>) |
| 05e3:0605 | Genesys Logic    | USB 2.0 Hub                          | 2     | hub        | [7127187A55](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DA8A3D24D2D7/RASPBIAN-10/5.4.51-V7+/ARMV7L/7127187A55>) |
| 0bda:5412 | Realtek Semic... | 4-Port USB 2.0 Hub                   | 2     | hub        | [A617383C6F](<System On Chip/Others/Others/Others/488EC17BC74D/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/A617383C6F>) |

### Human interface (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0079:0006 | DragonRise       | PC TWIN SHOCK Gamepad                | 1     | usbhid     | [904F2D4F21](<System On Chip/Nvidia/Tegra/Tegra/C04445AE216D/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/904F2D4F21>) |
| 0451:82ff | Texas Instrum... |                                      | 1     | usbhid     | [D48FD712A5](<System On Chip/Nvidia/Tegra/Tegra/A6096A1A9829/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/D48FD712A5>) |
| 046d:c216 | Logitech         | F310 Gamepad [DirectInput Mode]      | 1     | usbhid     | [A8BD03AC5B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6DB17957B8F8/RASPBIAN-10/5.10.63-V8+/AARCH64/A8BD03AC5B>) |
| 046d:c222 | Logitech         | G15 Keyboard / LCD                   | 1     | usbhid     | [796691962C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/677EC6DF9624/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/796691962C>) |
| 047f:0113 | Plantronics      | Voyager Legend                       | 1     | usbhid     | [802945D7D4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/2A516F87783F/UBUNTU-19.10/5.3.0-1018-RASPI2/AARCH64/802945D7D4>) |
| 04b4:fd13 | Cypress Semic... | Programmable power socket            | 1     |            | [E7E5ACB3BB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/54C6E331D35E/RASPBIAN-10/5.4.51-V7L+/ARMV7L/E7E5ACB3BB>) |
| 054c:0268 | Sony             | Batoh Device / PlayStation 3 Cont... | 1     | usbhid     | [06612D9E40](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/56BD017D9BD5/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/06612D9E40>) |
| 054c:05c4 | Sony             | DualShock 4 [CUH-ZCT1x]              | 1     | usbhid     | [66F0F8092B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/014B8BE86E99/UBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/66F0F8092B>) |
| 05ac:055b | Apple            | Gamesir-G3w                          | 1     | usbhid     | [C9D96D72E1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/5EB4769E77ED/UBUNTU-18.04/4.19.75V64/AARCH64/C9D96D72E1>) |
| 05ac:9226 | Apple            | LED Cinema Display                   | 1     | usbhid     | [6ADCA880A0](<System On Chip/Nvidia/Tegra/Tegra/E316CF040727/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/6ADCA880A0>) |
| 0665:5161 | Cypress Semic... | USB to Serial                        | 1     | usbhid     | [FDC6B746FE](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2FA63A79DB67/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/FDC6B746FE>) |
| 06c4:c411 | Bizlink Inter... | D6000 Controller                     | 1     | usbhid     | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 06c4:c412 | Bizlink Inter... | DELL DA300                           | 1     |            | [28143BF30E](<System On Chip/Qualcomm Technologies/SDM845/SDM845 v2.1 MTP PVT/8B8A857D4C70/KALI-2022.1/4.9.254-NETHUNTER/AARCH64/28143BF30E>) |
| 0bda:48f0 | Realtek Semic... | USB Audio                            | 1     | usbhid     | [FB1D446B99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/FE2789F8F214/RASPBIAN-10/5.10.17+/ARMV6L/FB1D446B99>) |
| 2563:0526 | ShenZhen Shan... | Android Gamepad                      | 1     | usbhid     | [DAE41A9529](<System On Chip/Nvidia/Tegra/Tegra/863D34773943/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DAE41A9529>) |
| 27c0:0858 | WingCoolTouch    |                                      | 1     | usbhid     | [0A8ADA10B5](<System On Chip/Nvidia/Tegra/Tegra/2B8AFCD2D256/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/0A8ADA10B5>) |
| 2b03:f781 | STEREOLABS       | ZED-2 HID INTERFACE                  | 1     | usbhid     | [7616B8F6B7](<System On Chip/Nvidia/Tegra/Tegra/0A0982FDE24A/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/7616B8F6B7>) |

### Input/keyboard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:c52b | Logitech         | Unifying Receiver                    | 134   | usbhid     | [AFF575B483](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/662506DEB22E/DEBIAN-11/5.10.92-V8+/AARCH64/AFF575B483>) |
| 046d:c534 | Logitech         | Unifying Receiver                    | 64    | usbhid     | [C7B32FF620](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4EC359174BBB/KUBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/C7B32FF620>) |
| 04d9:0007 | Holtek Semico... | Raspberry Pi Internal Keyboard       | 54    | usbhid     | [0B96F93C52](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6966851E18EE/UBUNTU-20.04/5.15.24-BCM2711/AARCH64/0B96F93C52>) |
| 04d9:0006 | Holtek Semico... | Wired Keyboard (78/79 key) [RPI W... | 37    | usbhid     | [C36FE6C067](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DA8EA20CB922/KALI-2021.4/5.4.83-RE4SON-V8L+/AARCH64/C36FE6C067>) |
| 046d:c31c | Logitech         | Keyboard K120                        | 21    | usbhid     | [80A1A1A3F2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/66EB44DCDD67/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/80A1A1A3F2>) |
| 413c:2113 | Dell             | KB216 Wired Keyboard                 | 19    | usbhid     | [2511C4E555](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5D8866DB4632/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/2511C4E555>) |
| 1997:2433 | Shenzhen Riit... | wireless mini keyboard with touchpad | 17    | usbhid     | [3303E6EB5E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/65EBB61BF49E/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/3303E6EB5E>) |
| 062a:4101 | MosArt Semico... | Wireless Keyboard/Mouse              | 16    | usbhid     | [4F92DEA8F4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4A1C5FAD507F/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/4F92DEA8F4>) |
| 1c4f:0002 | SiGma Micro      | Keyboard TRACER Gamma Ivory          | 12    | usbhid     | [34D80AF75A](<System On Chip/Nvidia/Tegra/Tegra/0E4BE18C9DF5/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/34D80AF75A>) |
| 045e:0745 | Microsoft        | Nano Transceiver v1.0 for Bluetooth  | 10    | usbhid     | [143A4E3C60](<System On Chip/Nvidia/Tegra/Tegra/7A6746DEFE47/LUBUNTU-18.04/4.9.201-TEGRA/AARCH64/143A4E3C60>) |
| 0513:0318 | digital-X        | USB Mouse                            | 8     | usbhid     | [ABD011C6B2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DBF5DAC73542/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/ABD011C6B2>) |
| 046a:0011 | Cherry           | G83 (RS 6000) Keyboard               | 7     | usbhid     | [2B4CD63D88](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/ATZ-11.2/5.10.0-12-ARM64/AARCH64/2B4CD63D88>) |
| 04d9:1702 | Holtek Semico... | Keyboard LKS02                       | 7     | usbhid     | [92829C951D](<System On Chip/Edelweiss/TF307/TF307-MB-S-D/B1DFE0530581/ALT-9.1.990/5.10.46-UN-DEF-ALT1/AARCH64/92829C951D>) |
| 413c:2107 | Dell             | KB212-B Quiet Key Keyboard           | 7     | usbhid     | [D4E45CB534](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E6D711ED9B50/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/D4E45CB534>) |
| 046a:0023 | Cherry           | Keyboard                             | 6     | usbhid     | [8C13511A03](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/32685E135116/DEBIAN-11/5.10.92-V8+/AARCH64/8C13511A03>) |
| 1a2c:2d23 | China Resourc... | Keyboard                             | 6     | usbhid     | [4020E881A1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/60B300074A8A/MANJARO-ARM/5.10.39-1-MANJARO-ARM/AARCH64/4020E881A1>) |
| 4037:2804 |                  | 2.4G Composite Devic                 | 6     | usbhid     | [A7E12A6A67](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2BB6856D88E4/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/A7E12A6A67>) |
| 03f0:0024 | Hewlett-Packard  | KU-0316 Keyboard                     | 5     | usbhid     | [66DF3754B3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/870E0570B155/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/66DF3754B3>) |
| 045e:0800 | Microsoft        | MicrosoftÂ Nano Transceiver v2.0     | 5     | usbhid     | [64AA8D06F4](<System On Chip/theobroma-systems/puma_rk/puma_rk3399/216F71D2BB0E/FEDORA-34/5.13.16-200.FC34.AARCH64/AARCH64/64AA8D06F4>) |
| 04f3:0103 | Elan Microele... | ActiveJet K-2024 Multimedia Keyboard | 5     | usbhid     | [2151A0B75D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/986E2A73F333/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/2151A0B75D>) |
| 1a2c:0e24 | China Resourc... | USB Keyboard                         | 5     | usbhid     | [E6EE79F80E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06F5C52ACD4E/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/E6EE79F80E>) |
| 1a2c:2124 | China Resourc... | Keyboard                             | 5     | usbhid     | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 258a:0001 | SINO WEALTH      | USB KEYBOARD                         | 5     | usbhid     | [53A2BB987D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B7CAE3493BED/RASPBIAN-10/5.10.63-V7+/ARMV7L/53A2BB987D>) |
| 045e:07f8 | Microsoft        | Wired Keyboard 600 (model 1576)      | 4     | usbhid     | [E87A8C6A13](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2FB104CFBB52/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/E87A8C6A13>) |
| 046d:c52e | Logitech         | MK260 Wireless Combo Receiver        | 4     | usbhid     | [001A68D211](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2F754B9634CA/UBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/001A68D211>) |
| 0c45:7603 | Microdia         | USB Keyboard                         | 4     | usbhid     | [F6FC8D9281](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1015-RASPI/AARCH64/F6FC8D9281>) |
| 24ae:2010 | Shenzhen Rapo... | 2.4G Wireless Device                 | 4     | usbhid     | [8426EF6261](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D1613665100E/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/8426EF6261>) |
| 25a7:fa61 | Areson Techno... | Elecom Co., Ltd MR-K013 Multicard... | 4     | usbhid     | [3BD9548BAB](<System On Chip/Hardkernel/ODROID-C/ODROID-C4/CB901DF2A096/UBUNTU-MATE-20.04/4.9.277-76/AARCH64/3BD9548BAB>) |
| 413c:2003 | Dell             | Keyboard SK-8115                     | 4     | usbhid     | [8222CC9CC3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/66F8067091F7/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/8222CC9CC3>) |
| 413c:2010 | Dell             | Keyboard                             | 4     | usbhid     | [33593B35B3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06F5C52ACD4E/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/33593B35B3>) |
| 045e:0752 | Microsoft        | Wired Keyboard 400                   | 3     | usbhid     | [965F364F1D](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/0B7E187F6FBF/MANJARO-ARM-21.10/5.16.0-RC3-1-MANJARO-ARM/AARCH64/965F364F1D>) |
| 045e:078c | Microsoft        | USB Keyboard                         | 3     | usbhid     | [1F1FC02023](<System On Chip/Others/Others/Others/F4E06447D552/UBUNTU-20.04/5.4.0-1003-MTK/AARCH64/1F1FC02023>) |
| 045e:07b2 | Microsoft        | 2.4GHz Transceiver v8.0 used by m... | 3     | usbhid     | [4C76845A26](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EFB50B591BD7/UBUNTU-20.04/5.4.0-1050-RASPI/AARCH64/4C76845A26>) |
| 045e:07fd | Microsoft        | Nano Transceiver 1.1                 | 3     | usbhid     | [8105B661FC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CFFB0B939BBF/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/8105B661FC>) |
| 0461:0010 | Primax Electr... | HP PR1101U / Primax PMX-KPR1101U ... | 3     | usbhid     | [0C406A0FB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/657E70087A27/RASPBIAN-9/5.15.21-V7+/ARMV7L/0C406A0FB6>) |
| 046d:c517 | Logitech         | LX710 Cordless Desktop Laser         | 3     | usbhid     | [71F0E328A1](<System On Chip/Others/Amlogic/Amlogic Meson GXL P212 Development/27F50E63E5F7/DEBIAN-11/5.9.0-ARM-64/AARCH64/71F0E328A1>) |
| 04d9:1603 | Holtek Semico... | Keyboard                             | 3     | usbhid     | [784EB9D04F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F4E9E4B582A0/DEBIAN-11/5.10.92-V8+/AARCH64/784EB9D04F>) |
| 05ac:0250 | Apple            | Aluminium Keyboard (ISO)             | 3     | usbhid     | [7B86B0DEE4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9EA4BB12B2DE/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/7B86B0DEE4>) |
| 0603:0002 | Novatek Micro... | Sino Wealth keyboard/mouse 2.4 GH... | 3     | usbhid     | [2C9C9A7C22](<System On Chip/Others/Others/Others/3CBCEA187C38/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/2C9C9A7C22>) |
| 0e6a:02c0 | Megawin Techn... | Defender Gaming Keyboard             | 3     | usbhid     | [3E9C3B2719](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/46E8145A373B/UBUNTU-20.10/5.8.0-1017-RASPI/AARCH64/3E9C3B2719>) |
| 0e8f:0022 | GreenAsia        | multimedia keyboard controller       | 3     | usbhid     | [2DC3E976E3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/92054DC43525/GENTOO-2.8/5.10.63-V8/AARCH64/2DC3E976E3>) |
| 0e8f:00a7 | GreenAsia        | 2.4G RX                              | 3     | usbhid     | [935CCFFCD5](<System On Chip/sunxi/Banana/Banana Pi BPI-M2-Ultra/ADAD3F8DDC8A/DEBIAN-11/5.10.12-SUNXI/ARMV7L/935CCFFCD5>) |
| 0e8f:00a8 | GreenAsia        | 2.4G RX                              | 3     | usbhid     | [721AFC488A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6FCBB96EC015/UBUNTU-20.10/5.8.0-1029-RASPI/AARCH64/721AFC488A>) |
| 1997:1221 | Shenzhen Riit... | Wireless Air mouse Keyboard          | 3     | usbhid     | [96144F8D28](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7F91DAFAA1AA/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/96144F8D28>) |
| 1a2c:2d43 | China Resourc... | USB Keyboard                         | 3     | usbhid     | [91E6F21231](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E73782C01D6D/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/91E6F21231>) |
| 248a:00da | Maxxter          | Wireless Receiver                    | 3     | usbhid     | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 24ae:1813 | Shenzhen Rapo... | E9260 Wireless Multi-mode Keyboard   | 3     | usbhid     | [6CAB644CFC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DB88EBCE19C1/UBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/6CAB644CFC>) |
| 24ae:2000 | RAPOO            | 2.4G Wireless Device                 | 3     | usbhid     | [FAE9412031](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/79256D3F1194/DEBIAN-11/5.10.92-V8+/AARCH64/FAE9412031>) |
| 25a7:fa67 | Areson Techno... | 2.4G Receiver                        | 3     | usbhid     | [7E8A8B37A7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/26D92CC1169A/UBUNTU-20.04/5.4.0-1051-RASPI/AARCH64/7E8A8B37A7>) |
| 276d:3257 |                  | 2.4G RF Keyboard & Mouse             | 3     | usbhid     | [D8FFAC9451](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2DFBE4D659AE/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/D8FFAC9451>) |

### Input/mouse (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 093a:2510 | Pixart Imaging   | Optical Mouse                        | 87    | usbhid     | [C36FE6C067](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DA8EA20CB922/KALI-2021.4/5.4.83-RE4SON-V8L+/AARCH64/C36FE6C067>) |
| 046d:c077 | Logitech         | M105 Optical Mouse                   | 20    | usbhid     | [2511C4E555](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5D8866DB4632/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/2511C4E555>) |
| 046d:c52f | Logitech         | Unifying Receiver                    | 19    | usbhid     | [2D70C02261](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6333AE03AB3B/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/2D70C02261>) |
| 248a:8367 | Maxxter          | Telink Wireless Receiver             | 11    | usbhid     | [73CFB1D650](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/11FC552C428F/RASPBIAN-11/5.10.63-V7L+/ARMV7L/73CFB1D650>) |
| 046d:c05a | Logitech         | M90/M100 Optical Mouse               | 9     | usbhid     | [7CDE4A4D40](<System On Chip/Nvidia/Tegra/Tegra/57BEF78164BC/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/7CDE4A4D40>) |
| 1ea7:0064 | SHARKOON Tech... | 2.4GHz Wireless rechargeable vert... | 9     | usbhid     | [9AF646FD14](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A785A002E43E/UBUNTU-21.10/5.13.0-1009-RASPI/AARCH64/9AF646FD14>) |
| 093a:2521 | Pixart Imaging   | Optical Mouse                        | 8     | usbhid     | [7AEB73D109](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/378385C3965D/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/7AEB73D109>) |
| 0416:c168 | Winbond Elect... | MTouch                               | 7     | usbhid     | [A75C5A2C02](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/11B8A9AE9008/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/A75C5A2C02>) |
| 413c:301a | Dell             | Dell MS116 Optical Mouse             | 7     | usbhid     | [41A38C1E60](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/437B04347154/DEBIAN-11/5.10.92-V8+/AARCH64/41A38C1E60>) |
| 0000:3825 |                  | USB OPTICAL MOUSE                    | 6     | usbhid     | [C3E2B43E74](<System On Chip/Khadas/VIM/VIM2/61FE2BBAE08B/XUBUNTU-18.04/5.0.0-AML-S912-GF2F3A8C1A-DIRTY/AARCH64/C3E2B43E74>) |
| 04f2:0939 | Chicony Elect... | Amazon Basics mouse                  | 6     | usbhid     | [53A2BB987D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B7CAE3493BED/RASPBIAN-10/5.10.63-V7+/ARMV7L/53A2BB987D>) |
| 1bcf:0005 | Sunplus Innov... | Optical Mouse                        | 6     | usbhid     | [B6BC1B40B7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B257A3ECD634/UBUNTU-21.10/5.13.0-1009-RASPI/AARCH64/B6BC1B40B7>) |
| 1c4f:0034 | SiGma Micro      | XM102K Optical Wheel Mouse           | 6     | usbhid     | [8E3573295D](<System On Chip/Hardkernel/Odroid/Odroid XU4/A7DC4E2AD6C4/UBUNTU-MATE-20.04/5.4.167-240/ARMV7L/8E3573295D>) |
| 222a:0001 | ILI Technology   | Multi-Touch Screen                   | 6     | usbhid     | [784EB9D04F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F4E9E4B582A0/DEBIAN-11/5.10.92-V8+/AARCH64/784EB9D04F>) |
| 046d:c040 | Logitech         | Corded Tilt-Wheel Mouse              | 5     | usbhid     | [8E6770F9BD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/946C8531B9B0/DEBIAN-11/5.10.0-8-ARM64/AARCH64/8E6770F9BD>) |
| 046d:c050 | Logitech         | RX 250 Optical Mouse                 | 5     | usbhid     | [D516CBBC97](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/D74AEC9E1203/DEBIAN-11/5.10.0-8-ARM64/AARCH64/D516CBBC97>) |
| 17ef:6019 | Lenovo           | M-U0025-O Mouse                      | 5     | usbhid     | [1E21B25BBA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/786472A5BF4A/MANJARO-ARM-22.01/5.10.88-1-MANJARO-ARM-RPI/AARCH64/1E21B25BBA>) |
| 248a:8514 | Maxxter          | Wireless Receiver                    | 5     | usbhid     | [24CECFE4C4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2B525F0CEEB5/POP!_OS-21.10/5.13.0-1011-RASPI/AARCH64/24CECFE4C4>) |
| 25a7:fa23 | Compx            | 2.4G Receiver                        | 5     | usbhid     | [2860BCE826](<System On Chip/Others/Others/Others/4FAC1337C966/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/2860BCE826>) |
| 045e:00cb | Microsoft        | Basic Optical Mouse v2.0             | 4     | usbhid     | [AB15FA7759](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4BB33BF10B64/UBUNTU-21.04/5.11.0-1015-RASPI/AARCH64/AB15FA7759>) |
| 046d:c016 | Logitech         | Optical Wheel Mouse                  | 4     | usbhid     | [4DECE01140](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F5A28CCF7A12/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/4DECE01140>) |
| 05ac:0304 | Apple            | Mighty Mouse [Mitsumi, M1152]        | 4     | usbhid     | [973297C20F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A99C7AB3E4AF/RASPBIAN-11/5.4.150+/ARMV6L/973297C20F>) |
| 0c45:8101 | Microdia         | USB Device                           | 4     | usbhid     | [0892AC4796](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1015-RASPI/AARCH64/0892AC4796>) |
| 0000:0538 |                  | USB OPTICAL MOUSE                    | 3     | usbhid     | [E6EE79F80E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/06F5C52ACD4E/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/E6EE79F80E>) |
| 03f0:0941 | Hewlett-Packard  | X500 Optical Mouse                   | 3     | usbhid     | [543099B0FA](<System On Chip/Radxa/ROCK/ROCK Pi 4/733E621E45CC/MANJARO-ARM-20.03/5.6.0-0.42-MANJARO-ARM/AARCH64/543099B0FA>) |
| 03f0:094a | Hewlett-Packard  | Optical Mouse [672662-001]           | 3     | usbhid     | [AFDBC607C5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2E8ADBA8214D/RASPBIAN-11/5.10.92-V7L+/ARMV7L/AFDBC607C5>) |
| 04ca:0061 | Lite-On Techn... | USB Optical Mouse                    | 3     | usbhid     | [B246EBE37C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/5532B9D494DE/RASPBIAN-10/5.10.17-V7+/ARMV7L/B246EBE37C>) |
| 04d9:0499 | Holtek Semico... | Optical Mouse                        | 3     | usbhid     | [F1562F69C5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/88B5CA9988A1/UBUNTU-21.10/5.13.0-1008-RASPI/AARCH64/F1562F69C5>) |
| 093a:2533 | Pixart Imaging   | Gaming Mouse                         | 3     | usbhid     | [7133090590](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9C8F81C157CC/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/7133090590>) |
| 18f8:0f97 | [Maxxter]        | Optical Gaming Mouse [Xtrem]         | 3     | usbhid     | [4B04BE2436](<System On Chip/Rockchip/Others/Others/F590D4D52D83/UBUNTU-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/4B04BE2436>) |
| 1bcf:0007 | Sunplus Innov... | Optical Mouse                        | 3     | usbhid     | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 1bcf:08a0 | Sunplus Innov... | Gaming mouse [Philips SPK9304]       | 3     | usbhid     | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 275d:0ba6 |                  | USB OPTICAL MOUSE                    | 3     | usbhid     | [E27B1CF91C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/2E52CCF8CADC/RASPBIAN-10/5.4.79-V7+/ARMV7L/E27B1CF91C>) |
| 0458:0007 | KYE Systems (... | Trackbar Emotion                     | 2     | usbhid     | [D243B289C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/C701E4440D09/UBUNTU-21.04/5.11.0-1009-RASPI/AARCH64/D243B289C3>) |
| 0461:4d64 | Primax Electr... | USB Optical Mouse                    | 2     | usbhid     | [CF8601E4F0](<System On Chip/Nvidia/Tegra/Tegra/2B3775F7B28D/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/CF8601E4F0>) |
| 0461:4d65 | Primax Electr... | USB Optical Mouse                    | 2     | usbhid     | [017BF22AB7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6DF4981BCCB2/POP!_OS-21.10/5.13.0-1009-RASPI/AARCH64/017BF22AB7>) |
| 0461:4e22 | Primax Electr... | Dell Mouse, 2 Buttons, Modell: MS... | 2     | usbhid     | [70FC801295](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B28BFA03EDD3/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/70FC801295>) |
| 0461:4e90 | Primax Electr... | HP Wireless Keyboard Mouse Kit       | 2     | usbhid     | [FF4D3F33C9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/38A846689288/ENDLESS-4.0.2/5.11.0-35-GENERIC/AARCH64/FF4D3F33C9>) |
| 046d:c00e | Logitech         | M-BJ58/M-BJ69 Optical Wheel Mouse    | 2     | usbhid     | [825770FD12](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/6A87DC7253AD/DEBIAN-11/5.10.0-8-ARM64/AARCH64/825770FD12>) |
| 046d:c018 | Logitech         | Optical Wheel Mouse                  | 2     | usbhid     | [7616B8F6B7](<System On Chip/Nvidia/Tegra/Tegra/0A0982FDE24A/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/7616B8F6B7>) |
| 046d:c045 | Logitech         | Optical Mouse                        | 2     | usbhid     | [6E1FBE4DDE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B7BD09B3EC83/UBUNTU-MATE-20.04/4.9.277-117/AARCH64/6E1FBE4DDE>) |
| 046d:c332 | Logitech         | G502 Proteus Spectrum Optical Mouse  | 2     | usbhid     | [80A1A1A3F2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/66EB44DCDD67/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/80A1A1A3F2>) |
| 046d:c408 | Logitech         | Marble Mouse (4-button)              | 2     | usbhid     | [0B96F93C52](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6966851E18EE/UBUNTU-20.04/5.15.24-BCM2711/AARCH64/0B96F93C52>) |
| 04d9:fc38 | Holtek Semico... | Gaming Mouse [Redragon M602-RGB]     | 2     | usbhid     | [543A85726B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/39F8F94A4B87/MANJARO-ARM/5.10.23-1-MANJARO-ARM/AARCH64/543A85726B>) |
| 0c45:7403 | Microdia         | Foot Switch                          | 2     | usbhid     | [F3483EB2D5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D5EC5BE2DA49/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/F3483EB2D5>) |
| 10c4:8108 | Silicon Labs     | USB OPTICAL MOUSE                    | 2     | usbhid     | [B4E6606B42](<System On Chip/Others/Baikal/Baikal Electronics Baikal-M mitx/D3C87EED480F/ALT-9.2/5.10.35-UN-DEF-ALT1/AARCH64/B4E6606B42>) |
| 1532:0003 | Razer USA        | Krait Mouse                          | 2     | usbhid     | [AB4793DC5E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2623DFFA12CE/GENTOO-2.7/5.10.63-RPI3/AARCH64/AB4793DC5E>) |
| 15ca:00c3 | Textech Inter... | Mini Optical Mouse                   | 2     | usbhid     | [F2F6BCC691](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B/48C5874C9150/ENDLESS-3.9.0/5.8.0-14-GENERIC/AARCH64/F2F6BCC691>) |
| 192f:0416 | Avago Technol... | ADNS-5700 Optical Mouse Controlle... | 2     | usbhid     | [FAFFA9BA50](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/108D422AD61E/UBUNTU-21.04/5.11.0-1024-RASPI/AARCH64/FAFFA9BA50>) |
| 1c4f:0003 | SiGma Micro      | HID controller                       | 2     | usbhid     | [6E8B50E148](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/33133DB1A2B1/UBUNTU-21.10/5.13.0-1008-RASPI/AARCH64/6E8B50E148>) |

### Joystick (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 24c6:581a | ThrustMaster     | XB1 Classic Controller               | 1     | xpad       | [7A240C3393](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F234CD61A4EA/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/7A240C3393>) |

### Mfp (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 03f0:012a | Hewlett-Packard  | LaserJet M1536dnf MFP                | 1     |            | [4DECE01140](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F5A28CCF7A12/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/4DECE01140>) |

### Miscellaneous (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 2676:ba05 | Basler           | a2A1920-160ucBAS                     | 1     |            | [273BC677CD](<System On Chip/Nvidia/Tegra/Tegra/C5692083B3F9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/273BC677CD>) |

### Modem (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0483:5740 | STMicroelectr... | Virtual COM Port                     | 3     | cdc_acm    | [32B0B1581C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/94EAD393C973/RASPBIAN-10/5.10.52-V7L+/ARMV7L/32B0B1581C>) |
| 2341:0043 | Arduino SA       | Uno R3 (CDC ACM)                     | 3     | cdc_acm    | [321B9F409A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/05F9E3E0E156/MANJARO-ARM/5.10.31-1-MANJARO-ARM/AARCH64/321B9F409A>) |
| 0451:16a8 | Texas Instrum... | CC2531 ZigBee                        | 1     | cdc_acm    | [7D51E2E653](<System On Chip/Others/Others/Others/CC98E2BA2A1B/RASPBIAN-10/4.19.118-V7L+/ARMV7L/7D51E2E653>) |
| 12d1:1001 | Huawei Techno... | E161/E169/E620/E800 HSDPA Modem      | 1     | usb_sto... | [A8C122E87D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/919DFC420DE1/RASPBIAN-10/5.4.70-V7L+/ARMV7L/A8C122E87D>) |
| 1546:01a7 | U-Blox           | [u-blox 7]                           | 1     | cdc_acm    | [A617383C6F](<System On Chip/Others/Others/Others/488EC17BC74D/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/A617383C6F>) |
| 18d1:d001 | Google           | Nexus 4 (fastboot)                   | 1     | rndis_host | [F2C4A2F8E9](<System On Chip/sunxi/Others/Others/F2F5CE95D58C/DEBIAN-10/5.10.34-SUNXI64/AARCH64/F2C4A2F8E9>) |
| 1eaf:0024 | Leaflabs         | DevTerm                              | 1     | cdc_acm    | [6C1B0DF48A](<System On Chip/sunxi/Others/Others/6A9E1BD0578E/UBUNTU-21.04/5.10.75-SUNXI64/AARCH64/6C1B0DF48A>) |

### Net/ethernet (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:8156 | Realtek Semic... | USB 10/100/1G/2.5G LAN               | 2     | r8152      | [5A1557AE1E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B113F42F0F82/UBUNTU-20.04/5.4.0-1038-RASPI/AARCH64/5A1557AE1E>) |
| 0fe6:9900 | ICS Advent       | 10/100M LAN                          | 1     | cdc_ether  | [2A66F4B578](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F6690455088F/RASPBIAN-11/5.10.63-V7+/ARMV7L/2A66F4B578>) |

### Net/wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:b812 | Realtek Semic... | RTL88x2bu [AC1200 Techkey]           | 7     | 88x2bu     | [216BCE9E93](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/216BCE9E93>) |
| 0bda:8179 | Realtek Semic... | RTL8188EUS 802.11n Wireless Netwo... | 6     | r8188eu    | [3C7D66229B](<System On Chip/Nvidia/Tegra/Tegra/F947C33E209B/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/3C7D66229B>) |
| 2357:011e | TP-Link          | 802.11ac WLAN Adapter                | 6     | 8812au     | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 148f:5370 | Ralink Techno... | RT5370 Wireless Adapter              | 5     | rt2800usb  | [3731E90788](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/131F65A756D8/LUBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/3731E90788>) |
| 148f:5572 | Ralink Techno... | RT5572 Wireless Adapter              | 5     | rt2800usb  | [017BF22AB7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6DF4981BCCB2/POP!_OS-21.10/5.13.0-1009-RASPI/AARCH64/017BF22AB7>) |
| 0bda:c811 | Realtek Semic... | 802.11ac NIC                         | 4     | rtl8821cu  | [904F2D4F21](<System On Chip/Nvidia/Tegra/Tegra/C04445AE216D/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/904F2D4F21>) |
| 0b05:17d2 | ASUSTek Computer | USB-AC56 802.11a/b/g/n/ac Wireles... | 3     | 88XXau     | [6DB0AEC69B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B308F978ACC3/UBUNTU-20.10/5.8.0-1032-RASPI/AARCH64/6DB0AEC69B>) |
| 0bda:a811 | Realtek Semic... | RTL8811AU 802.11a/b/g/n/ac WLAN A... | 3     | 88XXau     | [3BD9548BAB](<System On Chip/Hardkernel/ODROID-C/ODROID-C4/CB901DF2A096/UBUNTU-MATE-20.04/4.9.277-76/AARCH64/3BD9548BAB>) |
| 148f:5372 | Ralink Techno... | RT5372 Wireless Adapter              | 3     | rt2800usb  | [1D2F662FB7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9B3ADB652799/DEBIAN-TESTING/UNSTABLE/5.10.17-V7L+/ARMV7L/1D2F662FB7>) |
| 148f:7601 | Ralink Techno... | MT7601U Wireless Adapter             | 3     | mt7601u    | [C3E2B43E74](<System On Chip/Khadas/VIM/VIM2/61FE2BBAE08B/XUBUNTU-18.04/5.0.0-AML-S912-GF2F3A8C1A-DIRTY/AARCH64/C3E2B43E74>) |
| 2357:010c | TP-Link          | TL-WN722N v2/v3 [Realtek RTL8188EUS] | 3     | r8188eu    | [87CF7F053C](<System On Chip/Nvidia/Tegra/Tegra/E271192D27D5/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/87CF7F053C>) |
| 7392:7811 | Edimax Techno... | EW-7811Un 802.11n Wireless Adapte... | 3     | rtl8192cu  | [71F0E328A1](<System On Chip/Others/Amlogic/Amlogic Meson GXL P212 Development/27F50E63E5F7/DEBIAN-11/5.9.0-ARM-64/AARCH64/71F0E328A1>) |
| 0a5c:bd1e | Broadcom         | BCM43143 802.11bgn (1x1) Wireless... | 2     | brcmfmac   | [5E07806B7E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi ? Rev 1.0/D8FBFD41D06C/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/5E07806B7E>) |
| 0bda:8176 | Realtek Semic... | RTL8188CUS 802.11n WLAN Adapter      | 2     | rtl8192... | [DB93B6B390](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/93958385BC5D/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/DB93B6B390>) |
| 0bda:818b | Realtek Semic... | RTL8192EU 802.11b/g/n WLAN Adapter   | 2     |            | [F31E42B06C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/978F743209E0/RASPBIAN-10/5.10.52-V7L+/ARMV7L/F31E42B06C>) |
| 0bda:8812 | Realtek Semic... | RTL8812AU 802.11a/b/g/n/ac 2T2R D... | 2     | rtl8812au  | [AFDBC607C5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2E8ADBA8214D/RASPBIAN-11/5.10.92-V7L+/ARMV7L/AFDBC607C5>) |
| 0bda:8813 | Realtek Semic... | RTL8814AU 802.11a/b/g/n/ac Wirele... | 2     | rtl88XXau  | [9DBCC5EB42](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B771D1B91D90/KALI-2021.3/5.4.83-RE4SON-V7L+/ARMV7L/9DBCC5EB42>) |
| 0cf3:7015 | Qualcomm Athe... | TP-Link TL-WN821N v3 / TL-WN822N ... | 2     | ath9k_htc  | [4020E881A1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/60B300074A8A/MANJARO-ARM/5.10.39-1-MANJARO-ARM/AARCH64/4020E881A1>) |
| 0e8d:7612 | MediaTek         | MT7612U 802.11a/b/g/n/ac Wireless... | 2     | mt76x2u    | [4E1C736EBD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/AE06D5BC3399/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/4E1C736EBD>) |
| 148f:3070 | Ralink Techno... | RT2870/RT3070 Wireless Adapter       | 2     | rt2800usb  | [FEF5E29664](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CC27A622D6E5/RASPBIAN-10/5.10.17-V7+/ARMV7L/FEF5E29664>) |
| 2357:0109 | TP-Link          | TL-WN823N v2/v3 [Realtek RTL8192EU]  | 2     | rtl8xxxu   | [30C09E0585](<System On Chip/Nvidia/Tegra/Tegra/083D6ABF3079/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/30C09E0585>) |
| 04dd:941f | Sharp            | Remote Download Wireless Adapter     | 1     |            | [A054B3B41B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8EA077DD3644/RASPBIAN-10/5.10.60-V7+/ARMV7L/A054B3B41B>) |
| 0846:4210 | NetGear          | WG121(v2) 54 Mbps Wireless [Inter... | 1     | p54usb     | [433D54A30D](<System On Chip/Pine Microsystems/Pine64/Pine64+/CB0CC1CB9398/DEBIAN-11/5.10.0-8-ARM64/AARCH64/433D54A30D>) |
| 0846:9012 | NetGear          | WNDA4100 802.11abgn 3x3:3 [Ralink... | 1     | rt2800usb  | [41FB50247C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3866EA1B4A8D/UBUNTU-19.10/4.19.105-V8-28/AARCH64/41FB50247C>) |
| 0846:9020 | NetGear          | WNA3100(v1) Wireless-N 300 [Broad... | 1     |            | [5D3CE591BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/EF9198620015/UBUNTU-19.10/5.3.0-1019-RASPI2/AARCH64/5D3CE591BF>) |
| 0846:9052 | NetGear          | A6100 AC600 DB Wireless Adapter [... | 1     | 88XXau     | [8075B94007](<System On Chip/sunxi/Others/Others/108D12CE0E97/UBUNTU-20.04/5.10.60-SUNXI64/AARCH64/8075B94007>) |
| 0b05:17ba | ASUSTek Computer | N10 Nano 802.11n Network Adapter ... | 1     | rtl8192cu  | [02F65D4D20](<System On Chip/Others/Others/Others/548DF22116EC/PUREOS-10/4.19.72-IMX8-SR/AARCH64/02F65D4D20>) |
| 0bda:8172 | Realtek Semic... | RTL8191SU 802.11n WLAN Adapter       | 1     | r8712u     | [9B157B83A5](<System On Chip/Nvidia/Tegra/Tegra/B0A5FE7D6DB8/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/9B157B83A5>) |
| 0bda:8187 | Realtek Semic... | RTL8187 Wireless Adapter             | 1     | rtl8187    | [1A1189F529](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/14F096237BC9/UBUNTU-MATE-21.04/5.11.0-1016-RASPI/AARCH64/1A1189F529>) |
| 0cf3:1006 | Qualcomm Athe... | TP-Link TL-WN322G v3 / TL-WN422G ... | 1     | ath9k_htc  | [B79CD8C2B0](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/REDFLAG-11.0/4.19.0-15-PHYTIUM/AARCH64/B79CD8C2B0>) |
| 0cf3:9271 | Qualcomm Athe... | AR9271 802.11n                       | 1     | ath9k_htc  | [9BA35E9B27](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A954C80F17DD/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/9BA35E9B27>) |
| 0e66:0026 | Hawking Techn... | 802.11ac NIC                         | 1     |            | [5ECCD016B4](<System On Chip/Qualcomm Technologies/SDM845/SDM845 v2.1 MTP PVT/8B8A857D4C70/KALI-2022.1/4.9.254-NETHUNTER/AARCH64/5ECCD016B4>) |
| 0e8d:761b | MediaTek         | 802.11ac WLAN                        | 1     |            | [F60622CCA7](<System On Chip/Others/Others/Others/52150C65B995/UBUNTU-22.04/3.16.85-65/AARCH64/F60622CCA7>) |
| 13b1:0039 | Linksys          | AE1200 802.11bgn Wireless Adapter... | 1     | brcmfmac   | [930CB7D8B3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/CE2212347C1C/KALI-2021.1/4.19.127-RE4SON-V8L+/AARCH64/930CB7D8B3>) |
| 13b1:003e | Linksys          | AE6000 802.11a/b/g/n/ac Wireless ... | 1     |            | [70271C9802](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/70271C9802>) |
| 148f:3072 | Ralink Techno... | RT3072 Wireless Adapter              | 1     | rt2800usb  | [08EF6E888C](<System On Chip/Hardkernel/ODROID-C/ODROID-C2/5D912EC5D6C9/XUBUNTU-20.04/5.8.13-MESON64/AARCH64/08EF6E888C>) |
| 148f:3572 | Ralink Techno... | RT3572 Wireless Adapter              | 1     |            | [FFE8633188](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/AA64B87F32E9/UBUNTU-21.10/5.13.0-1012-RASPI/AARCH64/FFE8633188>) |
| 148f:760b | Ralink Techno... | MT7601U Wireless Adapter             | 1     | mt7601u    | [CBD268B858](<System On Chip/Others/Others/Others/799870895E60/UBUNTU-20.10/5.8.0-31-GENERIC/AARCH64/CBD268B858>) |
| 2001:331e | D-Link           | 802.11ac NIC                         | 1     |            | [C2CD717E53](<System On Chip/Qualcomm Technologies/SDM845/SDM845 v2.1 MTP PVT/8B8A857D4C70/KALI-2022.1/4.9.254-NETHUNTER/AARCH64/C2CD717E53>) |
| 2357:0108 | TP-Link          | TL-WN822N Version 4 RTL8192EU        | 1     | rtl8xxxu   | [4239296E76](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/0B7E187F6FBF/MANJARO-ARM-21.10/5.16.0-RC3-1-MANJARO-ARM/AARCH64/4239296E76>) |
| 2357:0115 | TP-Link          | Archer T4U ver.3                     | 1     |            | [E506B52862](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E8540BA672CD/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/E506B52862>) |
| 2357:0120 | TP-Link          | Archer T2U PLUS [RTL8821AU]          | 1     | 88XXau     | [D40EBEFD39](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BCB91EF70389/MANJARO-ARM-22.01/5.10.94-1-MANJARO-ARM-RPI/AARCH64/D40EBEFD39>) |
| 2357:0126 | TP-Link          | 802.11n NIC                          | 1     |            | [C36FE6C067](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DA8EA20CB922/KALI-2021.4/5.4.83-RE4SON-V8L+/AARCH64/C36FE6C067>) |
| 2357:0138 | TP-Link          | 802.11ac NIC                         | 1     | 88x2bu     | [3EB6755842](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/932E009E33E9/RASPBIAN-10/5.10.60-V7L+/ARMV7L/3EB6755842>) |
| 7392:a812 | Edimax Techno... | AC600 USB                            | 1     | 88XXau     | [EB00E0198C](<System On Chip/Xunlong/Orange/Orange Pi Zero/603147C387C1/UBUNTU-20.04/5.8.13-SUNXI/ARMV7L/EB00E0198C>) |

### Network (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0424:ec00 | Microchip Tec... | SMSC9512/9514 Fast Ethernet Adapter  | 69    | smsc95xx   | [0C406A0FB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/657E70087A27/RASPBIAN-9/5.15.21-V7+/ARMV7L/0C406A0FB6>) |
| 0424:7800 | Standard Micr... | Ethernet controller                  | 34    | lan78xx    | [053E9AC0E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BA4A62CA68F9/RASPBIAN-10/5.10.63-V7+/ARMV7L/053E9AC0E2>) |
| 0bda:8153 | Realtek Semic... | RTL8153 Gigabit Ethernet Adapter     | 31    | r8152      | [8E3573295D](<System On Chip/Hardkernel/Odroid/Odroid XU4/A7DC4E2AD6C4/UBUNTU-MATE-20.04/5.4.167-240/ARMV7L/8E3573295D>) |
| 04e8:6863 | Samsung Elect... | Galaxy series, misc. (tethering m... | 4     | rndis_host | [1630E680BC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/061F43A0A781/RASPBIAN-11/5.10.63-V7L+/ARMV7L/1630E680BC>) |
| 0bda:8152 | Realtek Semic... | RTL8152 Fast Ethernet Adapter        | 4     | r8152      | [FF4D3F33C9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/38A846689288/ENDLESS-4.0.2/5.11.0-35-GENERIC/AARCH64/FF4D3F33C9>) |
| 081f:e401 | Manta            | MM812                                | 2     | usbhid     | [2310ED4D7C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/22346AC8F0D2/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/2310ED4D7C>) |
| 0fe6:9700 | ICS Advent       | DM9601 Fast Ethernet Adapter         | 2     | dm9601,... | [43BB230E40](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5CD14C1C8F25/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/43BB230E40>) |
| 2717:ff80 | Xiaomi           | Mi/Redmi series (RNDIS)              | 2     | rndis_host | [19A54AC7D6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/76DC6B8C8DB4/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/19A54AC7D6>) |
| 04e8:6864 | Samsung Elect... | GT-I9070 (network tethering, USB ... | 1     | rndis_host | [C489F2F2A0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3E8575D9121/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/C489F2F2A0>) |
| 0525:a4a2 | Netchip Techn... | Linux-USB Ethernet/RNDIS Gadget      | 1     | cdc_subset | [7BAB2D2C6C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/974290CBD141/UBUNTU-MATE-20.04/5.4.0-1019-RASPI/AARCH64/7BAB2D2C6C>) |
| 0b95:1790 | ASIX Electronics | AX88179 Gigabit Ethernet             | 1     | ax88179... | [94F3848F94](<System On Chip/Shenzhen Amediatech Technology/X96/X96 Max/64FC3F78BF49/MANJARO-ARM-21.10/5.15.7-1-MANJARO-ARM/AARCH64/94F3848F94>) |
| 0b95:7720 | ASIX Electronics | AX88772                              | 1     | asix       | [AC382F40E8](<System On Chip/Qualcomm Technologies/Open-Q/Open-Q 820 microsom/F6FEB21E1005/DEBIAN-UNSTABLE/4.14.0-QCOMLT-ARM64/AARCH64/AC382F40E8>) |
| 0bb4:0003 | HTC (High Tec... | WEXLER.ZEN 4.7                       | 1     | rndis_host | [C72F8C76F7](<System On Chip/Nvidia/Tegra/Tegra/B2307FE84F73/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/C72F8C76F7>) |
| 0bda:c82c | Realtek Semic... | 802.11ac NIC                         | 1     | rtk_btu... | [B62C884AEC](<System On Chip/Nvidia/Tegra/Tegra/EA52D6551D30/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/B62C884AEC>) |
| 0e8d:2005 | MediaTek         | moto g(8) power lite                 | 1     | rndis_host | [5E682A0733](<System On Chip/Nvidia/Tegra/Tegra/A1DD672248E9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/5E682A0733>) |
| 12d1:108a | Huawei Techno... | ELS-NX9                              | 1     | rndis_host | [CE0D8F233C](<System On Chip/Shenzhen Amediatech Technology/X96/X96 Max/42FDDAF80558/XUBUNTU-20.04/5.9.0-ARM-64/AARCH64/CE0D8F233C>) |
| 1410:b00b | Novatel Wireless | MiFi 5510                            | 1     | rndis_host | [6873B9B896](<System On Chip/Hardkernel/Odroid/Odroid XU4/3C686A8058C1/UBUNTU-18.10/4.14.94-155/ARMV7L/6873B9B896>) |
| 17e9:6000 | DisplayLink      | Universal Dual 4K Video Dock         | 1     | cdc_ncm    | [D79A51C5A2](<System On Chip/Others/Others/Others/07AC06C2CBF0/UBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/D79A51C5A2>) |
| 17e9:6006 | DisplayLink      | Dell Universal Dock D6000            | 1     | cdc_ncm... | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 19d2:1015 | ZTE WCDMA Tec... | K3806-Z                              | 1     | cdc_ether  | [0C406A0FB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/657E70087A27/RASPBIAN-9/5.15.21-V7+/ARMV7L/0C406A0FB6>) |
| 2a70:f00e | OnePlus          | OnePlus                              | 1     | rndis_host | [1E008A514E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/17EA778A8698/UBUNTU-BUDGIE-19.10/5.3.0-1018-RASPI2/ARMV7L/1E008A514E>) |

### Printer (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0483:5750 | STMicroelectr... | LED badge -- mini LED display -- ... | 1     | usbhid     | [E32526B458](<System On Chip/Others/Others/Others/B0A3FCFAC123/XUBUNTU-20.04/5.4.0-1012-RASPI/AARCH64/E32526B458>) |
| 04a9:1825 | Canon            | TS5100 series                        | 1     | usblp      | [369B72F0FD](<System On Chip/Nvidia/Tegra/Tegra/B7396B276574/LUBUNTU-18.04/4.9.201-TEGRA/AARCH64/369B72F0FD>) |
| 04b8:008f | Seiko Epson      | AL-M310DN                            | 1     | usblp      | [0333751471](<System On Chip/sunxi/Orange/Orange Pi/347D564F5F58/DEBIAN-10/5.8.6-SUNXI/ARMV7L/0333751471>) |
| 04e8:3301 | Samsung Elect... | ML-1660 Series                       | 1     | usblp      | [21604049F3](<System On Chip/Others/Others/Others/4F4346C7FD17/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/21604049F3>) |
| 04e8:331a | Samsung Elect... | CLP-360 Series                       | 1     |            | [C7B32FF620](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4EC359174BBB/KUBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/C7B32FF620>) |
| 04e8:3433 | Samsung Elect... | SCX-4600 Series                      | 1     | usblp      | [9EF99E18E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BB768FB03CCD/MANJARO-ARM/5.10.52-2-MANJARO-ARM/AARCH64/9EF99E18E2>) |
| 04e8:344f | Samsung Elect... | SCX-3400 Series                      | 1     | usblp      | [2154AE968A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/964AD18F5EB7/UBUNTU-20.10/5.8.0-1011-RASPI/AARCH64/2154AE968A>) |
| 04f9:0273 | Brother Indus... | DCP-7057 scanner/printer             | 1     | usblp      | [79E8256BFB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/E3847B9370EE/RASPBIAN-9.8/4.14.98-V7+/ARMV7L/79E8256BFB>) |
| 06bc:034d | Oki Data         | USB Device                           | 1     | usbfs      | [E688396A21](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3EB3867D6F0/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/E688396A21>) |

### Scanner (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 04a9:1901 | Canon            | CanoScan 8800F                       | 1     |            | [94A6B9B7F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7F34CF394EF5/UBUNTU-20.10/5.8.0-1011-RASPI/AARCH64/94A6B9B7F8>) |
| 04a9:1909 | Canon            | CanoScan LiDE 110                    | 1     |            | [06BE200111](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8173C1117C20/RASPBIAN-11/5.10.92+/ARMV6L/06BE200111>) |
| 04b8:011b | Seiko Epson      | GT-9300UF [Perfection 2400 PHOTO]    | 1     |            | [57BDF81032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F65C49EF596B/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/57BDF81032>) |
| 04b8:011f | Seiko Epson      | GT-8400UF [Perfection 1670/1670 P... | 1     |            | [94A6B9B7F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7F34CF394EF5/UBUNTU-20.10/5.8.0-1011-RASPI/AARCH64/94A6B9B7F8>) |
| 04b8:012d | Seiko Epson      | GT-F650 [GT-S600/Perfection V10/V... | 1     |            | [55067D6AFE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/22FA5E73FA5C/UBUNTU-MATE-20.04/4.9.277-119/AARCH64/55067D6AFE>) |

### Serial controller (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 067b:2303 | Prolific Tech... | PL2303 Serial Port / Mobile Actio... | 11    | pl2303     | [1F12724CCE](<System On Chip/sunxi/Banana/Banana Pi BPI-M2-Plus H3/7AEBD225F3B0/DEBIAN-11/5.10.60-SUNXI/ARMV7L/1F12724CCE>) |
| 1a86:7523 | QinHeng Elect... | CH340 serial converter               | 8     | ch341      | [1E9CA3C359](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/63627667A60B/RASPBIAN-10/5.10.17-V7+/ARMV7L/1E9CA3C359>) |
| 0403:6001 | Future Techno... | FT232 Serial (UART) IC               | 7     | ftdi_sio   | [81FB7C8D99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3574C7CD7F7C/RASPBIAN-11/5.10.63-V7L+/ARMV7L/81FB7C8D99>) |
| 10c4:ea60 | Silicon Labs     | CP210x UART Bridge                   | 7     | cp210x     | [286449F8C4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/286449F8C4>) |
| 0403:6015 | Future Techno... | Bridge(I2C/SPI/UART/FIFO)            | 4     | ftdi_sio   | [6C9A78F854](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/20CA46FB02F1/DEBIAN-11/5.10.63-V8+/AARCH64/6C9A78F854>) |
| 0403:6010 | Future Techno... | FT2232C/D/H Dual UART/FIFO IC        | 3     | ftdi_sio   | [CB0D8D901A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B46C7D9294F4/UBUNTU-21.10/5.13.0-1008-RASPI/AARCH64/CB0D8D901A>) |
| 2c7c:0306 | Quectel Wirel... | EG06/EP06/EM06 LTE-A modem           | 3     | option     | [A1512911DF](<System On Chip/Khadas/VIM/VIM3/8E76D129C324/UBUNTU-20.04/4.9.241/AARCH64/A1512911DF>) |
| 0403:6011 | Future Techno... | FT4232H Quad HS USB-UART/FIFO IC     | 1     | ftdi_sio   | [67AF488496](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6B14664990A4/RASPBIAN-11/5.10.63-V7+/ARMV7L/67AF488496>) |
| 0403:6014 | Future Techno... | FT232H Single HS USB-UART/FIFO IC    | 1     |            | [3534D3E5F1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/1AD393D84921/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/3534D3E5F1>) |
| 12d1:15c1 | Huawei Techno... | ME906s LTE M.2 Module                | 1     | cdc_mbim   | [B341CB28A3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/FC0EEDB5C199/UBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/B341CB28A3>) |
| 1934:1202 | Feature Integ... | Fintek U4U F81534 AA66               | 1     | f81534     | [1F1FC02023](<System On Chip/Others/Others/Others/F4E06447D552/UBUNTU-20.04/5.4.0-1003-MTK/AARCH64/1F1FC02023>) |
| 1e0e:9001 | Qualcomm / Op... | SimTech, Incorporated                | 1     | option     | [3EEF74187F](<System On Chip/Nvidia/Tegra/Tegra/43CE974B3462/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/3EEF74187F>) |
| 2c7c:0800 | Quectel          | RM500Q-GL                            | 1     | option     | [B62C884AEC](<System On Chip/Nvidia/Tegra/Tegra/EA52D6551D30/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/B62C884AEC>) |

### Sound (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0d8c:0014 | C-Media Elect... | Audio Adapter (Unitek Y-247A)        | 11    | snd_usb... | [C636B137CF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B7CD2AE6FE1F/POP!_OS-21.10/5.13.0-1011-RASPI/AARCH64/C636B137CF>) |
| 1b3f:2008 | Generalplus T... | USB Audio Device                     | 6     | snd_usb... | [FF42CA8248](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3D5DBFC613F5/UBUNTU-21.04/5.11.0-1025-RASPI/AARCH64/FF42CA8248>) |
| 8086:0808 | Intel            | USB PnP Sound Device                 | 5     | snd_usb... | [342CCD2ECF](<System On Chip/Rockchip/Others/Others/46F00341A611/DEBIAN-11/4.4.190-1233-ROCKCHIP-AYUFAN-GD3F1BE0ED310/AARCH64/342CCD2ECF>) |
| 08bb:2704 | Texas Instrum... | PCM2704 16-bit stereo audio DAC      | 2     | snd_usb... | [D62808AD60](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B06C6E42A5A0/UBUNTU-21.04/5.11.0-1021-RASPI/AARCH64/D62808AD60>) |
| 08bb:2902 | Texas Instrum... | PCM2902 Audio Codec                  | 2     | snd_usb... | [6808E089AF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/274AA425FE22/RASPBIAN-10/5.10.63-V7L+/ARMV7L/6808E089AF>) |
| 08bb:29b3 | Texas Instrum... | PCM2903B Audio CODEC                 | 2     | snd_usb... | [8C5AE3D1CC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/7F4C3C256014/UBUNTU-20.10/5.8.0-1007-RASPI/AARCH64/8C5AE3D1CC>) |
| 0bda:4987 | Realtek Semic... | USB Audio                            | 2     | snd_usb... | [2A8B1A08BC](<System On Chip/Others/Others/Others/CA52484FDDC1/REDFLAG-11.0/4.19.0-16-ARM64/AARCH64/2A8B1A08BC>) |
| 045e:070f | Microsoft        | LifeChat LX-3000 Headset             | 1     | snd_usb... | [3EE1EB4EE7](<System On Chip/Nvidia/Tegra/Tegra/E77706A741F9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/3EE1EB4EE7>) |
| 046d:0a19 | Logitech         | Z205                                 | 1     | snd_usb... | [7133090590](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9C8F81C157CC/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/7133090590>) |
| 046d:0a23 | Logitech         | Z305                                 | 1     | snd_usb... | [980B14C09A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/FECC17F56857/RASPBIAN-11/5.10.92-V7L+/ARMV7L/980B14C09A>) |
| 046d:0a66 | Logitech         | [G533 Wireless Headset Dongle]       | 1     | snd_usb... | [D9070DA088](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/DFEA52D75DD5/MANJARO-ARM-20.12/5.10.1-1-MANJARO-ARM/AARCH64/D9070DA088>) |
| 046d:0a9c | Logitech         | G432 Gaming Headset                  | 1     | snd_usb... | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 047f:02ee | Plantronics      | BT600                                | 1     | snd_usb... | [07B65B98D0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/5BA420594234/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/07B65B98D0>) |
| 047f:c02f | Plantronics      | P610                                 | 1     | snd_usb... | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 054c:09cc | Sony             | DualShock 4 [CUH-ZCT2x]              | 1     | snd_usb... | [A7E12A6A67](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2BB6856D88E4/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/A7E12A6A67>) |
| 0582:0137 | Roland           | DUO-CAPTURE                          | 1     | snd_usb... | [56BBBD14D5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2530055FA946/XUBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/56BBBD14D5>) |
| 05ac:1105 | Apple            | Audio in LED Cinema Display          | 1     | snd_usb... | [6ADCA880A0](<System On Chip/Nvidia/Tegra/Tegra/E316CF040727/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/6ADCA880A0>) |
| 08bb:29c0 | Texas Instrum... | PCM2900C Audio CODEC                 | 1     | snd_usb... | [F8FA8FDC4D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3C2F4FDA790A/RASPBIAN-11/5.10.63-V7L+/ARMV7L/F8FA8FDC4D>) |
| 0b0e:0305 | GN Netcom        | Jabra EVOLVE LINK MS                 | 1     | snd_usb... | [E75BF2D175](<System On Chip/Others/Others/Others/B349704E2CFF/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/E75BF2D175>) |
| 0b0e:1022 | GN Netcom        | Jabra PRO 9450, Type 9400BS (DECT... | 1     | snd_usb... | [F8FA8FDC4D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3C2F4FDA790A/RASPBIAN-11/5.10.63-V7L+/ARMV7L/F8FA8FDC4D>) |
| 0bda:481a | Realtek Semic... | USB Audio                            | 1     | snd_usb... | [39533BD754](<System On Chip/Rockchip/RK3288/RK3288 Asus Tinker/0ABE66931753/XUBUNTU-18.04/5.4.24-ROCKCHIP/ARMV7L/39533BD754>) |
| 0c76:161f | JMTek            | USB PnP Audio Device                 | 1     | snd_usb... | [3E9C3B2719](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/46E8145A373B/UBUNTU-20.10/5.8.0-1017-RASPI/AARCH64/3E9C3B2719>) |
| 0d8c:000c | C-Media Elect... | Audio Adapter                        | 1     | snd_usb... | [7FD7E42E53](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/77C6901CC1FB/UBUNTU-20.10/5.8.0-1008-RASPI/AARCH64/7FD7E42E53>) |
| 0d8c:000e | C-Media Elect... | Audio Adapter (Planet UP-100, Gen... | 1     | snd_usb... | [77691E80A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8F3A96026FD0/RASPBIAN-10/5.10.63-V7L+/ARMV7L/77691E80A4>) |
| 0d8c:013c | C-Media Elect... | CM108 Audio Controller               | 1     | snd_usb... | [FA181224FF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9D48FFC3D337/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/FA181224FF>) |
| 1043:8773 | iCreate Techn... | ASUS BE/C6 webcam series             | 1     | usbhid     | [E688396A21](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3EB3867D6F0/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/E688396A21>) |
| 12ba:0035 | Licensed by S... | Wireless Stereo Headset              | 1     | snd_usb... | [9BA35E9B27](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A954C80F17DD/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/9BA35E9B27>) |
| 1395:0033 | Sennheiser Co... | SC60 for Lync                        | 1     | snd_usb... | [4D0329526A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/129C61A93C89/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/4D0329526A>) |
| 1395:005d | Sennheiser Co... | Sennheiser Main Audio                | 1     | snd_usb... | [1E21B25BBA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/786472A5BF4A/MANJARO-ARM-22.01/5.10.88-1-MANJARO-ARM-RPI/AARCH64/1E21B25BBA>) |
| 1915:1012 | Nordic Semico... | Smart Control                        | 1     | snd_usb... | [D96D0BEBA4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EBA7FC9211A8/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/D96D0BEBA4>) |
| 1915:7856 | Nordic Semico... | Uniplay U6                           | 1     | snd_usb... | [2F1CA6D742](<System On Chip/Nvidia/Tegra/Tegra/9845C4314AEE/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/2F1CA6D742>) |
| 1997:7b03 | Shenzhen Riit... | Multimedia Air Mouse Keyboard        | 1     | snd_usb... | [79DB7CDBA8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/2FCF9738EDCB/UBUNTU-20.10/5.8.0-1008-RASPI/AARCH64/79DB7CDBA8>) |
| 2000:dd00 | CMX Systems      | USB PnP Audio Device                 | 1     | snd_usb... | [BF8ABDFB09](<System On Chip/Others/Unknown/Unknown Product/4BE11779C833/FEDORA-35/5.14.9-300.FC35.AARCH64/AARCH64/BF8ABDFB09>) |
| 2034:0105 | Best Buy         | INSIGNIA NS-CBM19                    | 1     | snd_usb... | [E65C4D13BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/E65C4D13BF>) |
| 413c:a503 | Dell             | AC511 USB SoundBar                   | 1     | snd_usb... | [0006A974C9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/E7E9E3BD9361/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/0006A974C9>) |
| b58e:9e84 | Blue Microphones | Yeti Stereo Microphone               | 1     | snd_usb... | [D89F4CF907](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3CCD380912E8/RASPBIAN-10/5.10.11-V7L+/ARMV7L/D89F4CF907>) |

### Touchpad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 06cb:0009 | Synaptics        | Composite TouchPad and TrackPoint    | 1     | synapti... | [591BEDF88F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/41DD4743631C/UBUNTU-21.04/5.11.0-1027-RASPI/AARCH64/591BEDF88F>) |

### Touchscreen (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0eef:0001 | D-WAV Scientific | Titan6001 Surface Acoustic Wave T... | 2     | usbhid     | [8C13511A03](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/32685E135116/DEBIAN-11/5.10.92-V8+/AARCH64/8C13511A03>) |

### Tv card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0ac8:301b | Z-Star Microe... | ZC0301 Webcam                        | 2     | gspca_z... | [76DC55B00E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EB72DE30F09D/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/76DC55B00E>) |
| 041e:4068 | Creative Tech... | Live! Cam Notebook [VF0470]          | 1     | gspca_o... | [3FDF6B4559](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B308F978ACC3/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/3FDF6B4559>) |
| 045e:00f5 | Microsoft        | LifeCam VX-3000                      | 1     | gspca_s... | [40ADEBBAD2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4194DDE215B4/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/40ADEBBAD2>) |
| 046d:0892 | Logitech         | C920 HD Pro Webcam                   | 1     | gspca_v... | [8A69B09CAB](<System On Chip/Nvidia/Tegra/Tegra/B0435DC20AF7/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/8A69B09CAB>) |
| 046d:0920 | Logitech         | QuickCam Express                     | 1     | gspca_t... | [40748C60B0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/92054DC43525/GENTOO-2.8/5.10.11-V8/AARCH64/40748C60B0>) |
| 0553:0002 | STMicroelectr... | CPiA Webcam                          | 1     | gspca_c... | [D5FFD1FF38](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/367DAA77496B/RASPBIAN-10/4.19.75-V7+/ARMV7L/D5FFD1FF38>) |
| 0ac8:307b | Z-Star Microe... | USB 1.1 Webcam                       | 1     | gspca_z... | [93004B8E8F](<System On Chip/Nvidia/Tegra/Tegra/4BE71AD4E685/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/93004B8E8F>) |
| 1415:2000 | Nam Tai E&E P... | Sony Playstation Eye                 | 1     | snd_usb... | [14BC5C234D](<System On Chip/Khadas/VIM/VIM3/AD2E7941E7E9/XUBUNTU-20.04/4.9.241/AARCH64/14BC5C234D>) |

### Ups (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0764:0501 | Cyber Power S... | CP1500 AVR UPS                       | 1     | usbhid     | [B417AFA8D1](<System On Chip/Others/Others/Others/57A822BF053D/DEBIAN-10/5.4.79-V8+/AARCH64/B417AFA8D1>) |
| 0d9f:0004 | Powercom         | HID UPS Battery                      | 1     | usbfs      | [77BB019FE0](<System On Chip/Bananapi/BPI-M/BPI-M5/91E0E094EEA8/DEBIAN-10/4.9.236-BPI-M5-KERNEL/AARCH64/77BB019FE0>) |

### Wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 17ef:7a1c | Lenovo           | Lenovo Composite ADB Interface       | 1     | rndis_host | [30C09E0585](<System On Chip/Nvidia/Tegra/Tegra/083D6ABF3079/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/30C09E0585>) |
| 2d95:600b | vivo             | S9                                   | 1     | rndis_host | [B62C884AEC](<System On Chip/Nvidia/Tegra/Tegra/EA52D6551D30/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/B62C884AEC>) |

### Others (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1d5c:7102 | Fresco Logic     | Generic Billboard Device             | 2     |            | [BF8ABDFB09](<System On Chip/Others/Unknown/Unknown Product/4BE11779C833/FEDORA-35/5.14.9-300.FC35.AARCH64/AARCH64/BF8ABDFB09>) |
| 2109:0102 | VIA Labs         | USB 2.0 BILLBOARD                    | 2     |            | [D8411DFAB2](<System On Chip/Qualcomm Technologies/SM8150/SM8150 V2 PM8150 CEPHEUS/93F44C6259DA/KALI-2021.2/4.14.212-QUANTIC_MIUI//94C9FEE9AE/AARCH64/D8411DFAB2>) |
| 2294:425a | Theobroma Sys... | Mule USB/CAN Adapter                 | 2     |            | [16D3C3D359](<System On Chip/theobroma-systems/puma_rk/puma_rk3399/C7048E225E39/FEDORA-34/5.14.9-200.FC34.AARCH64/AARCH64/16D3C3D359>) |
| 03f0:0a6b | Hewlett-Packard  | USB-C/A Universal Dock G2            | 1     | usbhid     | [E75BF2D175](<System On Chip/Others/Others/Others/B349704E2CFF/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/E75BF2D175>) |
| 0451:16ae | Texas Instrum... | CC2531 Dongle                        | 1     |            | [1971415007](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/870E0570B155/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/1971415007>) |
| 04e8:6001 | Samsung Elect... | sd-wire                              | 1     |            | [04EDD2ED9A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/F65B7C80FDEE/DEBIAN-TESTING/5.8.0-2-ARM64/AARCH64/04EDD2ED9A>) |
| 0955:cf07 | Nvidia           | SHIELD Tablet                        | 1     | usbfs      | [E56E9C8A57](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/8D2589DBE95B/UBUNTU-19.10/5.3.0-1023-RASPI2/AARCH64/E56E9C8A57>) |
| 0bda:5418 | Realtek Semic... | BillBoard Device                     | 1     |            | [A617383C6F](<System On Chip/Others/Others/Others/488EC17BC74D/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/A617383C6F>) |
| 0e41:4750 | Line6            | GuitarPort                           | 1     | snd_usb... | [46CF1EB748](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CF04D8227DE3/DEBIAN-11/5.10.92-V8+/AARCH64/46CF1EB748>) |
| 17e9:601e | DisplayLink      | HP USB-C Universal Docking Station   | 1     | snd_usb... | [E75BF2D175](<System On Chip/Others/Others/Others/B349704E2CFF/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/E75BF2D175>) |
| 1d50:6089 | OpenMoko         | Great Scott Gadgets HackRF One SDR   | 1     | hackrf     | [604DD9D393](<System On Chip/sunxi/Others/Others/AF0F9587AEF6/DEBIAN-11/5.4.18-SUNXI64/AARCH64/604DD9D393>) |
| 1df7:3000 | SDRplay          | RSP1a                                | 1     |            | [C38D256CAB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E4FE3E3CD572/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/C38D256CAB>) |
| 2188:0011 | No brand         | TS3 Plus                             | 1     |            | [123113DDFD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A954C80F17DD/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/123113DDFD>) |

