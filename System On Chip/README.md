Most popular USB devices in System On Chips
-------------------------------------------

See more info in the [README](https://github.com/linuxhw/LsUSB).

Contents
--------

1. [ USB Devices in System On Chips ](#usb-devices)
   * [ Audio ](#audio-usb)
   * [ Bluetooth ](#bluetooth-usb)
   * [ Camera ](#camera-usb)
   * [ Card reader ](#card-reader-usb)
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
| 0bda:49ab | Realtek Semic... | USB Audio                            | 2     | snd_usb... | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |
| 0bda:4be2 | Realtek Semic... | Realtek USB2.0 Audio                 | 1     | snd_usb... | [5236B9452C](<System On Chip/Rockchip/Others/Others/46F00341A611/DEBIAN-11/4.4.202-1237-ROCKCHIP-AYUFAN-GFD4492386213/AARCH64/5236B9452C>) |
| 1235:8202 | Focusrite-Nov... | Focusrite Scarlett 2i2 2nd Gen       | 1     | snd_usb... | [46D79DE66E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3E699A4BBDB1/UBUNTU-21.10/5.13.0-1009-RASPI/AARCH64/46D79DE66E>) |

### Bluetooth (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0a12:0001 | Cambridge Sil... | Bluetooth Dongle (HCI mode)          | 20    | btusb      | [B120C1B209](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/94C534C252BB/RASPBIAN-11/5.15.84-V7+/ARMV7L/B120C1B209>) |
| 8087:0a2b | Intel            | Bluetooth wireless interface         | 12    | btusb      | [4D32910C65](<System On Chip/Nvidia/Tegra/Tegra/CC41B2AA6D5B/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/4D32910C65>) |
| 13d3:3549 | IMC Networks     | Bluetooth Radio                      | 8     | rtk_btu... | [08B3F5414E](<System On Chip/Nvidia/Tegra/Tegra/3D43A83DC6B6/UBUNTU-20.04/5.10.65-TEGRA/AARCH64/08B3F5414E>) |
| 0bda:8771 | Realtek Semic... | Bluetooth Radio                      | 6     | btusb      | [5715CFF1D5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/14B11EFFEDEC/RASPBIAN-11/5.15.84-V7+/ARMV7L/5715CFF1D5>) |
| 7392:a611 | Edimax Techno... | EW-7611ULB 802.11b/g/n and Blueto... | 4     | btusb      | [44ADEC89D8](<System On Chip/Bananapi/BPI-M/BPI-M5/487C39187D98/UBUNTU-20.04/4.9.241-BPI-M5/AARCH64/44ADEC89D8>) |
| 0a5c:21e8 | Broadcom         | BCM20702A0 Bluetooth 4.0             | 3     | btusb      | [BA7A43587C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/D19D7D7ACF07/DEBIAN-11/6.1.19-V8+/AARCH64/BA7A43587C>) |
| 2357:0604 | TP-Link          | UB500 Adapter                        | 3     | btusb      | [1378D303E3](<System On Chip/Nvidia/Tegra/Tegra/E1CEE4DBB7F5/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/1378D303E3>) |
| 0b05:17cb | ASUSTek Computer | Broadcom BCM20702A0 Bluetooth        | 2     | btusb      | [B6661B1166](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/5C0749770C50/RASPBIAN-10/5.10.103-V7L+/ARMV7L/B6661B1166>) |
| 8087:0032 | Intel            | AX210 Bluetooth                      | 2     | btusb      | [B05FAAC149](<System On Chip/Others/NVIDIA/NVIDIA Jetson Xavier NX Developer Kit/FF85D7E95ADF/UBUNTU-20.04/5.10.104-TEGRA/AARCH64/B05FAAC149>) |
| 04ca:3015 | Lite-On Techn... | Qualcomm Atheros QCA9377 Bluetooth   | 1     | btusb      | [5E682A0733](<System On Chip/Nvidia/Tegra/Tegra/A1DD672248E9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/5E682A0733>) |
| 07d1:f101 | D-Link System    | DBT-122 Bluetooth                    | 1     | btusb      | [7CDE4A4D40](<System On Chip/Nvidia/Tegra/Tegra/57BEF78164BC/UBUNTU-UNITY-18.04/4.9.253-TEGRA/AARCH64/7CDE4A4D40>) |
| 0a5c:2121 | Broadcom         | BCM2210 Bluetooth                    | 1     | btusb      | [4BAC63946A](<System On Chip/Hardkernel/Odroid/Odroid XU4/1EFF612359AC/DEBIAN-10/5.4.72-ODROIDXU4/ARMV7L/4BAC63946A>) |
| 0a5c:21ec | Broadcom         | BCM20702A0 Bluetooth 4.0             | 1     | btusb      | [9B157B83A5](<System On Chip/Nvidia/Tegra/Tegra/B0A5FE7D6DB8/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/9B157B83A5>) |
| 0b05:190e | ASUSTek Computer | AalteUSB-BT500                       | 1     | btusb      | [4361E01E42](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/324FCA6EC2EE/RASPBIAN-11/5.10.92-V7+/ARMV7L/4361E01E42>) |
| 0bda:b85b | Realtek Semic... | Bluetooth Radio                      | 1     | rtk_btu... | [7037D37121](<System On Chip/Radxa/ROCK/ROCK 5B/E01230749C71/REBORNOS-ARM-ROLLING/5.10.110-ROCKCHIP-RK3588/AARCH64/7037D37121>) |
| 0cf3:e500 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 1     | btusb      | [CFEB6FB78F](<System On Chip/Nvidia/Tegra/Tegra/52416602189B/UBUNTU-UNITY-18.04/4.9.253-TEGRA/AARCH64/CFEB6FB78F>) |
| 0e5e:6622 | Conwise Techn... | CW6622                               | 1     | btusb      | [55067D6AFE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/22FA5E73FA5C/UBUNTU-MATE-20.04/4.9.277-119/AARCH64/55067D6AFE>) |
| 13d3:3548 | IMC Networks     | Bluetooth Radio                      | 1     | rtk_btu... | [DB3EB249A1](<System On Chip/Nvidia/Tegra/Tegra/A2D34F7D05EB/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DB3EB249A1>) |
| 21ee:1100 | Broadcom         | Bluetooth V3.0 USB Device            | 1     | btusb      | [5E07806B7E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi ? Rev 1.0/D8FBFD41D06C/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/5E07806B7E>) |
| 8087:0029 | Intel            | AX200 Bluetooth                      | 1     | btusb      | [769A23D6D3](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/UBUNTU-20.04/5.10.110-30-ROCKCHIP-G12EE46F17A0C/AARCH64/769A23D6D3>) |
| 8087:07dc | Intel            | Bluetooth wireless interface         | 1     | btusb      | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 8087:0a2a | Intel            | Bluetooth wireless interface         | 1     | btusb      | [C72F8C76F7](<System On Chip/Nvidia/Tegra/Tegra/B2307FE84F73/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/C72F8C76F7>) |
| 8087:0aaa | Intel            | Bluetooth 9460/9560 Jefferson Pea... | 1     | btusb      | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |

### Camera (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:075d | Microsoft        | LifeCam Cinema                       | 6     | snd_usb... | [B468496893](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/6966851E18EE/UBUNTU-21.04/5.11.0-1003-RASPI/AARCH64/B468496893>) |
| 046d:082d | Logitech         | HD Pro Webcam C920                   | 6     | snd_usb... | [A58EF799E8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/BB83E3AF30AE/UBUNTU-22.04/5.15.0-1012-RASPI/AARCH64/A58EF799E8>) |
| 05a3:9331 | ARC Internati... | Camera                               | 6     | snd_usb... | [BB26B3803B](<System On Chip/sunxi/Others/Others/332ED02F0A69/DEBIAN-11/5.15.79-SUNXI64/AARCH64/BB26B3803B>) |
| 1908:2311 | GEMBIRD          | USB2.0 PC CAMERA                     | 6     | uvcvideo   | [40FAEC573D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/01C8A884DD7C/RASPBIAN-11/5.15.84-V7L+/ARMV7L/40FAEC573D>) |
| 046d:0825 | Logitech         | Webcam C270                          | 5     | snd_usb... | [A8C118C380](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DF13040690E6/RASPBIAN-11/5.10.103-V7+/ARMV7L/A8C118C380>) |
| 04e8:6860 | Samsung Elect... | Galaxy A5 (MTP)                      | 5     | usbfs      | [EAB6A0EE2A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/84379B68A573/UBUNTU-22.04/5.15.0-1006-RASPI/AARCH64/EAB6A0EE2A>) |
| 0c45:6366 | Microdia         | Webcam Vitade AF                     | 5     | snd_usb... | [99D2997B98](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/14F1BEF2204E/RASPBIAN-11/5.15.84+/ARMV6L/99D2997B98>) |
| 0ac8:3420 | Z-Star Microe... | Venus USB2.0 Camera                  | 4     | snd_usb... | [AC565D5D7D](<System On Chip/Xunlong/Orange/Orange Pi PC Plus/96B482F42282/XUBUNTU-22.04/5.15.93-SUNXI/ARMV7L/AC565D5D7D>) |
| 0c45:6321 | Microdia         | HP Integrated Webcam                 | 4     | uvcvideo   | [D8CD86DB45](<System On Chip/PINE64/Pinebook/Pinebook Pro/9912F73F6133/FEDORA-37/6.0.7-301.FC37.AARCH64/AARCH64/D8CD86DB45>) |
| 1224:2a25 | Jieli Technology | USB PHY 2.0                          | 3     | snd_usb... | [3584E25B54](<System On Chip/Xunlong/Orange/Orange Pi Lite/89B0620C4302/DEBIAN-11/5.15.43-SUNXI/ARMV7L/3584E25B54>) |
| 1b3f:2247 | Generalplus T... | GENERAL WEBCAM                       | 3     | snd_usb... | [18EB9A1E52](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/2C50102B3F1A/RASPBIAN-11/5.15.32-V7L+/ARMV7L/18EB9A1E52>) |
| 046d:081b | Logitech         | Webcam C310                          | 2     | snd_usb... | [E19D9EAD40](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.1/18B5E2EB9324/RASPBIAN-10/5.10.103-V8+/AARCH64/E19D9EAD40>) |
| 046d:0826 | Logitech         | HD Webcam C525                       | 2     | uvcvideo   | [2D06B54D63](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/80421287995C/UBUNTU-22.04/5.15.0-1005-RASPI/AARCH64/2D06B54D63>) |
| 05ac:12a8 | Apple            | iPhone 5/5C/5S/6/SE/7/8/X            | 2     | apple_m... | [0C5A37EFD2](<System On Chip/Others/Others/Others/83028C31DEB3/XUBUNTU-20.04/5.15.25-ROCKCHIP64/AARCH64/0C5A37EFD2>) |
| 0c45:636b | Microdia         | USB 2.0 Camera                       | 2     | snd_usb... | [E513434675](<System On Chip/Radxa/ROCK/ROCK Pi 4C+/423812C7428B/XUBUNTU-22.04/5.15.89-ROCKCHIP64/AARCH64/E513434675>) |
| 1004:633e | LG Electronics   | LM-X420xxx/G2/G3 Android Phone (M... | 2     | usbfs      | [4298DA2E03](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E726DE6BBF8A/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/4298DA2E03>) |
| 1b3f:1167 | Generalplus T... | WEB CAM                              | 2     | snd_usb... | [4776ECDC2A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B/DC7253D0EC7D/RHEL-9/5.14.0-70.17.1.EL9_0.AARCH64/AARCH64/4776ECDC2A>) |
| 1b3f:2202 | Generalplus T... | GENERAL - UVC                        | 2     | snd_usb... | [9CCDF29023](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/55E956921EA3/RASPBIAN-11/6.1.21-V8+/AARCH64/9CCDF29023>) |
| 1bcf:2286 | Sunplus Innov... | FHD Camera                           | 2     | snd_usb... | [24EE06B435](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero Rev 1.3/DAC76A68429F/RASPBIAN-11/5.15.84+/ARMV6L/24EE06B435>) |
| 1e4e:0109 | Cubeternet       | EtronTech CMOS based eSP570 WebCa... | 2     | snd_usb... | [54592EC1A2](<System On Chip/Nvidia/Tegra/Tegra/54129FFCE65C/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/54592EC1A2>) |
| 2a70:9012 | OnePlus Techn... | SM8150-MTP _SN:A05FE1A2              | 2     | usbfs      | [1E21B25BBA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/786472A5BF4A/MANJARO-ARM-22.01/5.10.88-1-MANJARO-ARM-RPI/AARCH64/1E21B25BBA>) |
| 534d:2109 | MacroSilicon     | USB Video                            | 2     | usbhid     | [F3C11793EE](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/0B7E187F6FBF/MANJARO-ARM-22.03/5.17.0-RC8-2-MANJARO-ARM-RC/AARCH64/F3C11793EE>) |
| 0408:1030 | Quanta           | FV TouchCam N1 (Video)               | 1     | uvcvideo   | [024050E40A](<System On Chip/Xunlong/Orange/Orange Pi Zero/02164B58FD0B/DEBIAN-11/5.15.74-SUNXI/ARMV7L/024050E40A>) |
| 041e:4095 | Creative Tech... | Live! Cam Sync HD [VF0770]           | 1     | snd_usb... | [F5CA9E190E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/866573591706/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/F5CA9E190E>) |
| 043e:3012 | LG Electronics   | AN-VC500 Camera                      | 1     | snd_usb... | [5A08EE43A7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/F140D978D199/RASPBIAN-10/5.10.60-V7+/ARMV7L/5A08EE43A7>) |
| 0458:7060 | KYE Systems (... | iSlim 1320                           | 1     | uvcvideo   | [537289447F](<System On Chip/Others/Others/Others/BDF0B02C0CAD/UBUNTU-MATE-20.04/3.16.85-62/AARCH64/537289447F>) |
| 045e:076d | Microsoft        | LifeCam HD-5000                      | 1     | uvcvideo   | [FC5AEB0B10](<System On Chip/pine64,rockpro64-v2.1/RockPro64/RockPro64 v2.1/E710D01431EC/OPENMANDRIVA-4.50/5.11.11-SERVER-1OMV4050/AARCH64/FC5AEB0B10>) |
| 045e:0779 | Microsoft        | LifeCam HD-3000                      | 1     | uvcvideo   | [C2F69BB6EF](<System On Chip/Others/Others/Others/D70379D8CACE/UBUNTU-20.04/3.16.85-65/AARCH64/C2F69BB6EF>) |
| 046d:080f | Logitech         | Webcam C120                          | 1     | uvcvideo   | [7E56CCE9C8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7EC4C0AFB59D/ALMA-8.6/5.15.45-V8.1.EL8/AARCH64/7E56CCE9C8>) |
| 046d:0821 | Logitech         | HD Webcam C910                       | 1     | uvcvideo   | [E8C67DC172](<System On Chip/Nvidia/Tegra/Tegra/49846891E392/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/E8C67DC172>) |
| 046d:0823 | Logitech         | HD Webcam B910                       | 1     | uvcvideo   | [6C59E641C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/A98FE60A0893/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/6C59E641C3>) |
| 046d:082c | Logitech         | HD Webcam C615                       | 1     | uvcvideo   | [BE96BBE4F4](<System On Chip/Nvidia/Tegra/Tegra/1F5B34B20D8B/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/BE96BBE4F4>) |
| 046d:085c | Logitech         | C922 Pro Stream Webcam               | 1     | snd_usb... | [A5CFF855E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/F4D7831C00DB/RASPBIAN-10/5.10.103-V7L+/ARMV7L/A5CFF855E2>) |
| 046d:0894 | Logitech         | CrystalCam                           | 1     | snd_usb... | [E65C4D13BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/E65C4D13BF>) |
| 046d:08e3 | Logitech         | C505 HD Webcam                       | 1     | snd_usb... | [E0A7F48AE2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/74F788DE0027/RASPBIAN-11/5.15.84-V7+/ARMV7L/E0A7F48AE2>) |
| 046d:0990 | Logitech         | QuickCam Pro 9000                    | 1     | snd_usb... | [7C33656745](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D563CAC58049/UBUNTU-22.04/5.15.0-1012-RASPI/AARCH64/7C33656745>) |
| 046d:0991 | Logitech         | QuickCam Pro for Notebooks           | 1     | snd_usb... | [1B7191941B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/92C928CEBED8/UBUNTU-20.04/5.4.0-1008-RASPI/AARCH64/1B7191941B>) |
| 046d:09a4 | Logitech         | QuickCam E 3500                      | 1     | snd_usb... | [DC1D4B5FF5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D75482517216/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/DC1D4B5FF5>) |
| 046d:09a6 | Logitech         | QuickCam Vision Pro                  | 1     | snd_usb... | [4571B799F0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7EC4C0AFB59D/ALMA-8.7/5.15.45-V8.1.EL8/AARCH64/4571B799F0>) |
| 0471:0311 | Philips (or NXP) | PCVC740K ToUcam Pro [pwc]            | 1     | pwc        | [742BE0320C](<System On Chip/Nvidia/Tegra/Tegra/CC41B2AA6D5B/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/742BE0320C>) |
| 057e:030a | Nintendo         | USB Camera                           | 1     | uvcvideo   | [8075B94007](<System On Chip/sunxi/Others/Others/108D12CE0E97/UBUNTU-20.04/5.10.60-SUNXI64/AARCH64/8075B94007>) |
| 058f:3861 | Alcor Micro      | USB 2.0 PC Camera                    | 1     | snd_usb... | [A7E12A6A67](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2BB6856D88E4/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/A7E12A6A67>) |
| 05a3:9230 | ARC Internati... | Camera                               | 1     | uvcvideo   | [2511C4E555](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5D8866DB4632/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/2511C4E555>) |
| 05ac:8508 | Apple            | iSight in LED Cinema Display         | 1     | uvcvideo   | [6ADCA880A0](<System On Chip/Nvidia/Tegra/Tegra/E316CF040727/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/6ADCA880A0>) |
| 05e3:0510 | Genesys Logic    | Camera                               | 1     | uvcvideo   | [690F707A87](<System On Chip/Nvidia/Tegra/Tegra/E0E6BD12DF48/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/690F707A87>) |
| 05e3:0515 | Genesys Logic    | USB2.0 UVC PC Camera                 | 1     |            | [EFEAE454C8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/A436D468F504/DEBIAN-11/5.15.84-V8+/AARCH64/EFEAE454C8>) |
| 0711:3108 | Magic Control... | j5 WebCam JVCU100                    | 1     | uvcvideo   | [A5CFF855E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/F4D7831C00DB/RASPBIAN-10/5.10.103-V7L+/ARMV7L/A5CFF855E2>) |
| 0ac8:0346 | Z-Star Microe... | HBV HD CAMERA                        | 1     | uvcvideo   | [42F1A36ACE](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/3D0BF9B58B59/RASPBIAN-11/5.15.84-V7+/ARMV7L/42F1A36ACE>) |
| 0ac8:3450 | Z-Star Microe... | A4 TECH USB2.0 PC Camera E           | 1     | uvcvideo   | [70271C9802](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/70271C9802>) |
| 0ac8:c40a | Z-Star Microe... | A4 TECH USB2.0 PC Camera J           | 1     | snd_usb... | [5FC70F3F84](<System On Chip/Nvidia/Tegra/Tegra/A5CD0129FDE8/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/5FC70F3F84>) |

### Card reader (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 2ce3:9563 | Alcorlink        | EMV Smartcard Reader                 | 1     | usbfs      | [018EB0B0BB](<System On Chip/NCI/PC/PC BLICK101/3CFE875BAE08/RED-OS-7.3/5.4.197-1.EL7.AARCH64/AARCH64/018EB0B0BB>) |

### Cdrom (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 152e:2571 | LG (HLDS)        | GP08NU6W DVD-RW                      | 6     | uas, us... | [9048879465](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/BB83E3AF30AE/UBUNTU-21.04/5.11.0-1021-RASPI/AARCH64/9048879465>) |
| 0fe6:9702 | ICS Advent       | Supereal VR DISK                     | 5     | usb_sto... | [F1537BEEDF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8ED828060896/RASPBIAN-12/6.1.21-V7+/ARMV7L/F1537BEEDF>) |
| 152e:1640 | LG (HLDS)        | INIC-1605 SATA Bridge                | 2     | usb_sto... | [1A369AD73A](<System On Chip/Nvidia/Tegra/Tegra/ADBC4F66375D/LUBUNTU-18.04/4.9.253-TEGRA/AARCH64/1A369AD73A>) |
| 067b:3507 | Prolific Tech... | PL3507 ATAPI6 Bridge                 | 1     | usb_sto... | [8D04531B2A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/75D7217E3FA2/UBUNTU-20.10/5.8.0-1007-RASPI/AARCH64/8D04531B2A>) |
| 0b05:7774 | ASUSTek Computer | Zenfone GO (ZB500KL) (RNDIS mode)    | 1     | rndis_host | [DBD6AC01D6](<System On Chip/Pine Microsystems/Pine64/Pine64 Rock64/15D9FF44F966/XUBUNTU-22.04/5.15.68-ROCKCHIP64/AARCH64/DBD6AC01D6>) |
| 0bda:8151 | Realtek Semic... | RTL8151 Adapteon Business Mobile ... | 1     | usb_sto... | [DE369A751A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/29BF1DBCCFC4/DEBIAN-11/6.1.19-V8+/AARCH64/DE369A751A>) |
| 0e8d:1806 | MediaTek         | Samsung SE-208 Slim Portable DVD ... | 1     | usb_sto... | [7FD7E42E53](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/77C6901CC1FB/UBUNTU-20.10/5.8.0-1008-RASPI/AARCH64/7FD7E42E53>) |
| 0e8d:1836 | MediaTek         | Samsung SE-S084 Super WriteMaster... | 1     | usb_sto... | [57BDF81032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F65C49EF596B/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/57BDF81032>) |
| 0e8d:1887 | MediaTek         | Slim Portable DVD Writer             | 1     | usb_sto... | [27C1DAE829](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4CA5A946C266/UBUNTU-22.04/5.15.0-1011-RASPI/AARCH64/27C1DAE829>) |
| 0e8d:1956 | MediaTek         | Samsung SE-506 Portable BluRay Di... | 1     | usb_sto... | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 13fd:3609 | Initio           | BD-RE BU40N                          | 1     | usb_sto... | [0A683CEF46](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/139149DFB9A7/RASPBIAN-10/5.10.11-V7L+/ARMV7L/0A683CEF46>) |
| 8564:8000 | Transcend        | TRANSCEND                            | 1     | usb_sto... | [FDC6B746FE](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2FA63A79DB67/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/FDC6B746FE>) |

### Chipcard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 058f:9540 | Alcor Micro      | AU9540 Smartcard Reader              | 1     |            | [E50D894B93](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/1C59F83A8416/UBUNTU-MATE-20.04/5.4.0-1025-RASPI/AARCH64/E50D894B93>) |

### Disk (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 174c:55aa | ASMedia Techn... | ASM1051E SATA 6Gb/s bridge, ASM10... | 85    | usb_sto... | [A7283D568F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/7FFDAD8BC5DF/DEBIAN-11/6.1.19-V8+/AARCH64/A7283D568F>) |
| 152d:0578 | JMicron Techn... | JMS578 SATA 6Gb/s                    | 39    | uas, us... | [5236B9452C](<System On Chip/Rockchip/Others/Others/46F00341A611/DEBIAN-11/4.4.202-1237-ROCKCHIP-AYUFAN-GFD4492386213/AARCH64/5236B9452C>) |
| 090c:1000 | Silicon Motion   | USB                                  | 26    | usb_sto... | [93826EA84A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/0AEC31239676/RASPBIAN-11/5.15.84-V7+/ARMV7L/93826EA84A>) |
| 14cd:1212 | Super Top        | microSD card reader (SY-T18)         | 22    | uas, us... | [23A61DFA8F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/7EC5A75B56F2/RASPBIAN-11/6.1.23-V8+/AARCH64/23A61DFA8F>) |
| 0781:5583 | SanDisk          | Ultra Fit                            | 19    | usb_sto... | [D0C2C987FC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model A Plus Rev 1.0/3E5943BD89A6/DEBIAN-11/5.15.84-V8+/AARCH64/D0C2C987FC>) |
| 0781:5581 | SanDisk          | Ultra                                | 16    | uas, us... | [5874F73855](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/F7DD6274B850/RASPBIAN-11/5.15.76-V7L+/ARMV7L/5874F73855>) |
| 0951:1666 | Kingston Tech... | DataTraveler 100 G3/G4/SE9 G2        | 16    | usb_sto... | [D57318F254](<System On Chip/Nvidia/Tegra/Tegra/08DCF44A15CD/XUBUNTU-20.04/4.9.140-TEGRA/AARCH64/D57318F254>) |
| 174c:1153 | ASMedia Techn... | ASM1153 SATA 3Gb/s bridge            | 15    | uas        | [37A6B115CB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/73EC8FD2B322/DEBIAN-11/5.15.84-V8+/AARCH64/37A6B115CB>) |
| 152d:0562 | JMicron Techn... | JMS567 SATA 6Gb/s bridge             | 14    | uas        | [407CA5845D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/99AA913EF833/RASPBIAN-11/6.1.21-V7+/ARMV7L/407CA5845D>) |
| 2109:0711 | VIA Labs         | VL711 SATA 6Gb/s bridge              | 14    | uas, us... | [DD05575BB4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/94832BF0E91C/DEBIAN-11/5.15.61-V8+/AARCH64/DD05575BB4>) |
| 05e3:0749 | Genesys Logic    | USB3.0 Card Reader                   | 12    | usb_sto... | [592FEA8754](<System On Chip/Radxa/ROCK/ROCK 5B/139991BFFDC7/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/592FEA8754>) |
| 152d:0561 | JMicron Techn... | JMS551 - Sharkoon SATA QuickPort Duo | 10    | uas        | [2188A4A04E](<System On Chip/Hardkernel/Odroid/Odroid XU4/BDA5AE2539D0/DEBIAN-11/5.4.225-ODROIDXU4/ARMV7L/2188A4A04E>) |
| 152d:2338 | JMicron Techn... | JM20337 Hi-Speed USB to SATA & PA... | 10    | uas, us... | [BF3FEE013B](<System On Chip/Nvidia/Tegra/Tegra/6981659F8C33/XUBUNTU-18.04/4.9.253-TEGRA/AARCH64/BF3FEE013B>) |
| 174c:0825 | ASMedia Techn... | X825                                 | 10    | uas        | [AF50FDF3B9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6D40827EBDE4/UBUNTU-22.04/5.15.0-1011-RASPI/AARCH64/AF50FDF3B9>) |
| 0bda:9210 | Realtek Semic... | RTL9210                              | 9     | uas        | [592FEA8754](<System On Chip/Radxa/ROCK/ROCK 5B/139991BFFDC7/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/592FEA8754>) |
| 174c:1156 | ASMedia Techn... | Forty                                | 9     | uas        | [AE13C0BB6B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F25A9886F352/ALT-10.1/5.15.74-UN-DEF-ALT1/AARCH64/AE13C0BB6B>) |
| 0080:a001 | Assmann Elect... | Digitus DA-71114 SATA                | 8     | uas        | [C65FD15277](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/778E7E6702DC/DEBIAN-11/6.2.7-V8+/AARCH64/C65FD15277>) |
| 152d:1561 | JMicron Techn... | JMS561U two ports SATA 6Gb/s bridge  | 8     | uas        | [420373DCA1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/6BE5E3ABA36B/DEBIAN-11/5.10.43V64/AARCH64/420373DCA1>) |
| 2109:0715 | VIA Labs         | VL817 SATA Adaptor                   | 8     | uas        | [A7283D568F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/7FFDAD8BC5DF/DEBIAN-11/6.1.19-V8+/AARCH64/A7283D568F>) |
| 8564:1000 | Transcend        | JetFlash                             | 8     | usb_sto... | [D27D307085](<System On Chip/sunxi/LeMaker/LeMaker Banana Pi/A46088CADC70/DEBIAN-11/6.1.11-SUNXI/ARMV7L/D27D307085>) |
| 0930:6544 | Toshiba          | TransMemory-Mini / Kingston DataT... | 7     | uas, us... | [F1537BEEDF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8ED828060896/RASPBIAN-12/6.1.21-V7+/ARMV7L/F1537BEEDF>) |
| 152d:2329 | JMicron Techn... | JM20329 SATA Bridge                  | 7     | usb_sto... | [36BBD53EC1](<System On Chip/Nvidia/Tegra/Tegra/3DDE0D84E562/XUBUNTU-20.04/4.9.253-TEGRA/AARCH64/36BBD53EC1>) |
| 1908:0226 | GEMBIRD          | MicroSD Card Reader/Writer           | 7     | uas, us... | [C03BBC1DFB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E7AA79E146FB/RASPBIAN-TESTING/5.10.103-V7L+/ARMV7L/C03BBC1DFB>) |
| 048d:1234 | Integrated Te... | Mass storage                         | 6     | uas, us... | [D59DA741C5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/BFC645C66AAC/UBUNTU-21.10/5.10.43V64/AARCH64/D59DA741C5>) |
| 04e8:4001 | Samsung Elect... | PSSD T7                              | 6     | uas        | [4A8EC9290E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/BCB91EF70389/MANJARO-ARM/5.15.92-1-MANJARO-ARM-RPI/AARCH64/4A8EC9290E>) |
| 04e8:61f5 | Samsung Elect... | Portable SSD T5                      | 6     | uas        | [AC0705FEAE](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/BCB91EF70389/MANJARO-ARM-22.09/5.15.70-1-MANJARO-ARM-RPI/AARCH64/AC0705FEAE>) |
| 058f:6387 | Alcor Micro      | Transcend                            | 6     | uas, us... | [61A2726A1D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/217191B3CA97/RASPBIAN-11/6.1.21-V8+/AARCH64/61A2726A1D>) |
| 0781:5588 | SanDisk          | Extreme Pro                          | 6     | usb_sto... | [95C95C980D](<System On Chip/Others/Others/Others/A877A66C5D0B/DEBIAN-11/5.19.1-STB-CBQ+/AARCH64/95C95C980D>) |
| 090c:2000 | Silicon Motion   | USB DISK                             | 6     | usb_sto... | [61A2726A1D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/217191B3CA97/RASPBIAN-11/6.1.21-V8+/AARCH64/61A2726A1D>) |
| 1058:25e1 | Western Digit... | My Passport (WD20NMVW)               | 6     | uas, us... | [08EF3B4EB5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/659022AFEF90/UBUNTU-21.10/5.13.0-1024-RASPI/AARCH64/08EF3B4EB5>) |
| 1058:2624 | Western Digit... | easystore 2624                       | 6     | uas, us... | [123113DDFD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A954C80F17DD/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/123113DDFD>) |
| 152d:0583 | JMicron Techn... | JMS583Gen 2 to PCIe Gen3x2 Bridge    | 6     | uas        | [9184B7F306](<System On Chip/Google/Homestar/Homestar/3747919F00E7/DEBIAN-12/6.1.11-STB-CBQ/AARCH64/9184B7F306>) |
| 0781:5591 | SanDisk          | Ultra Flair                          | 5     | uas, us... | [F4F2A0D4E6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/FB2A61B6A26B/RASPBIAN-11/5.15.76-V7L+/ARMV7L/F4F2A0D4E6>) |
| 13fe:6400 | Phison Electr... | USB DISK 3.0                         | 5     | uas, us... | [9D5CC656DA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3C47FA8BC2E/UBUNTU-22.04/5.15.0-1011-RASPI/AARCH64/9D5CC656DA>) |
| 152d:0567 | JMicron Techn... | JMS567 SATA 6Gb/s bridge             | 5     | uas        | [2FEDFF1D10](<System On Chip/Others/Others/Others/DEB6485066DE/UBUNTU-22.04/5.15.93-ROCKCHIP64/AARCH64/2FEDFF1D10>) |
| 152d:2590 | JMicron Techn... | JMS567 SATA 6Gb/s bridge             | 5     | uas        | [A3F2F1DCC7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/6966851E18EE/FEDORA-38/6.1.0-0.RC0.20221007GIT4C86114194E6.5.FC38.AARCH64/AARCH64/A3F2F1DCC7>) |
| 18a5:0302 | Verbatim         | STORE N GO                           | 5     | uas, us... | [C42643096A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3B5266D85CF7/UBUNTU-22.04/5.15.0-1013-RASPI/AARCH64/C42643096A>) |
| 7825:a2a4 | Other World C... | External SATA Hard Drive Adapter ... | 5     | uas        | [C01B933066](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/BB83E3AF30AE/UBUNTU-22.04/5.15.0-1016-RASPI/AARCH64/C01B933066>) |
| 0781:5571 | SanDisk          | Cruzer Fit                           | 4     | uas, us... | [645C8515A1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F67FB4C216FD/DEBIAN-11/6.1.19-V8+/AARCH64/645C8515A1>) |
| 0781:5575 | SanDisk          | Cruzer Glide                         | 4     | uas, us... | [3D8D1682DD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/B2A0C4665DE3/UBUNTU-21.04/5.4.0-1028-RASPI/AARCH64/3D8D1682DD>) |
| 0781:558c | SanDisk          | Extreme SSD                          | 4     | uas        | [B478B39BDB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/E54E575FC48E/RASPBIAN-11/5.15.82-V7L+/ARMV7L/B478B39BDB>) |
| 0bc2:ab24 | Seagate          | Backup Plus Portable Drive           | 4     | uas        | [053E9AC0E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/BA4A62CA68F9/RASPBIAN-10/5.10.63-V7+/ARMV7L/053E9AC0E2>) |
| 0bda:0306 | Realtek Semic... | USB3.0-CRW                           | 4     | usb_sto... | [0C5A37EFD2](<System On Chip/Others/Others/Others/83028C31DEB3/XUBUNTU-20.04/5.15.25-ROCKCHIP64/AARCH64/0C5A37EFD2>) |
| 152d:0580 | JMicron Techn... | USB 3.1 Storage Device               | 4     | uas        | [81375E1AFC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/9FC1F1D11002/RASPBIAN-11/5.15.84-V7L+/ARMV7L/81375E1AFC>) |
| 1bcf:0c31 | Sunplus Innov... | SPIF30x Serial-ATA bridge            | 4     | uas        | [5C530C94B3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/AC4EC76ED48F/GENTOO-2.7/5.10.11-V8/AARCH64/5C530C94B3>) |
| 1f75:0621 | Innostor Tech... | IS621 SATA Storage Controller        | 4     | usb_sto... | [8E854926E0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/2C3A61B8D814/UBUNTU-22.04/5.15.0-1006-RASPI/AARCH64/8E854926E0>) |
| 0480:b207 | Toshiba America  | Canvio Ready                         | 3     | uas        | [4B5EBC25D2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/6BE5E3ABA36B/DEBIAN-11/5.10.43V64/AARCH64/4B5EBC25D2>) |
| 05e3:0751 | Genesys Logic    | microSD Card Reader                  | 3     | uas, us... | [E5ED3CE077](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/098BC2088E60/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/E5ED3CE077>) |
| 0781:5567 | SanDisk          | Cruzer Blade                         | 3     | uas, us... | [6E1FBE4DDE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B7BD09B3EC83/UBUNTU-MATE-20.04/4.9.277-117/AARCH64/6E1FBE4DDE>) |
| 0781:5572 | SanDisk          | Cruzer Switch                        | 3     | uas, us... | [ACFE0DFFFA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/59C53CF2DA4B/UBUNTU-22.04/5.15.0-1013-RASPI/AARCH64/ACFE0DFFFA>) |

### Dvb card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:2838 | Realtek Semic... | RTL2838 DVB-T                        | 15    | dvb_usb... | [DE089A077E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/46DA6DB9C2D8/RASPBIAN-11/5.15.84-V7+/ARMV7L/DE089A077E>) |
| 0bda:2832 | Realtek Semic... | RTL2832U DVB-T                       | 3     | dvb_usb... | [D400A91BE1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/5713B3BB8EE3/RASPBIAN-11/5.10.52-V7+/ARMV7L/D400A91BE1>) |
| 07ca:1835 | AVerMedia Tec... | A835B                                | 1     | dvb_usb... | [44857FE932](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7F1F3D0DAB2B/RASPBIAN-10/5.4.51-V7+/ARMV7L/44857FE932>) |
| 07ca:1871 | AVerMedia Tec... | TD310 DVB-T/T2/C dongle              | 1     | dvb_usb... | [B063A72D21](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/4AE8222E9092/DEBIAN-11/5.15.61-V8+/AARCH64/B063A72D21>) |
| 15f4:0131 | HanfTek          | dvbt2                                | 1     | dvb_usb... | [78A0A02DF1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/EA281E0179D9/UBUNTU-20.10/5.8.0-1007-RASPI/AARCH64/78A0A02DF1>) |

### Fingerprint reader (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 138a:0011 | Validity Sensors | VFS5011 Fingerprint Reader           | 1     |            | [82192DCB1D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/82192DCB1D>) |
| 27c6:5117 | Shenzhen Good... | Fingerprint Reader                   | 1     |            | [B4F452D2D8](<System On Chip/HUAWEI/HUAWEIPGU-WBY/HUAWEIPGU-WBY0/ABDCBB39B3E3/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.0.8-1-DEFAULT/AARCH64/B4F452D2D8>) |

### Gamepad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:028e | Microsoft        | Xbox360 Controller                   | 3     | xpad       | [46D79DE66E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3E699A4BBDB1/UBUNTU-21.10/5.13.0-1009-RASPI/AARCH64/46D79DE66E>) |
| 046d:c21d | Logitech         | F310 Gamepad [XInput Mode]           | 2     | xpad       | [EAB2C9895A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/51F4036C55DE/UBUNTU-22.04/5.15.0-1005-RASPI/AARCH64/EAB2C9895A>) |
| 07b5:0213 | Mega World In... | Thrustmaster Firestorm Digital 3 ... | 1     | usbhid     | [70271C9802](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/70271C9802>) |
| 0e6f:0213 | Logic3           | Afterglow Gamepad for Xbox 360       | 1     | xpad       | [FEF12EE80A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/ABCE585EFD30/DEBIAN-10/5.10.17-V8+/AARCH64/FEF12EE80A>) |
| 0e6f:0413 | Logic3           | Afterglow AX.1 Gamepad for Xbox 360  | 1     | xpad       | [04DA44A3D2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/A72EE6CE5710/UBUNTU-18.04/4.19.97-V8-27/AARCH64/04DA44A3D2>) |
| 2563:0575 | ShenZhen Shan... | ZD-V+ Wired Gaming Controller        | 1     | usbhid     | [6FB5AE90DB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/EF9198620015/UBUNTU-19.10/5.3.0-1019-RASPI2/AARCH64/6FB5AE90DB>) |

### Hub (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1d6b:0002 | Linux Foundation | 2.0 root hub                         | 1460  | hub        | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 1d6b:0003 | Linux Foundation | 3.0 root hub                         | 1155  | hub        | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 2109:3431 | VIA Labs         | Hub                                  | 888   | hub        | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 1d6b:0001 | Linux Foundation | 1.1 root hub                         | 164   | hub        | [55F6CAEC2D](<System On Chip/Others/Others/Others/3584471355A1/DEBIAN-11/4.9.318-SUN50IW9/AARCH64/55F6CAEC2D>) |
| 05e3:0610 | Genesys Logic    | Hub                                  | 159   | hub        | [D0C2C987FC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model A Plus Rev 1.0/3E5943BD89A6/DEBIAN-11/5.15.84-V8+/AARCH64/D0C2C987FC>) |
| 0424:9514 | Standard Micr... | SMC9514 Hub                          | 123   | hub        | [50A67AB03C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/3A28E3EB24BC/RASPBIAN-10/5.10.103-V7+/ARMV7L/50A67AB03C>) |
| 1a40:0101 | Terminus Tech... | Hub                                  | 88    | hub        | [61A2726A1D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/217191B3CA97/RASPBIAN-11/6.1.21-V8+/AARCH64/61A2726A1D>) |
| 0bda:5411 | Realtek Semic... | RTS5411 Hub                          | 62    | hub        | [5236B9452C](<System On Chip/Rockchip/Others/Others/46F00341A611/DEBIAN-11/4.4.202-1237-ROCKCHIP-AYUFAN-GFD4492386213/AARCH64/5236B9452C>) |
| 0424:2514 | Microchip Tec... | USB 2.0 Hub                          | 61    | hub        | [407CA5845D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/99AA913EF833/RASPBIAN-11/6.1.21-V7+/ARMV7L/407CA5845D>) |
| 0bda:0411 | Realtek Semic... | Hub                                  | 57    | hub        | [1378D303E3](<System On Chip/Nvidia/Tegra/Tegra/E1CEE4DBB7F5/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/1378D303E3>) |
| 05e3:0608 | Genesys Logic    | Hub                                  | 51    | hub        | [C564829AE4](<System On Chip/Amlogic/Meson8/Meson8B/F0FC5B0515B8/XUBUNTU-18.04/3.10.108/ARMV7L/C564829AE4>) |
| 2109:2817 | VIA Labs         | USB2.0 Hub                           | 29    | hub        | [D0C2C987FC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model A Plus Rev 1.0/3E5943BD89A6/DEBIAN-11/5.15.84-V8+/AARCH64/D0C2C987FC>) |
| 05e3:0626 | Genesys Logic    | Hub                                  | 26    | hub        | [592FEA8754](<System On Chip/Radxa/ROCK/ROCK 5B/139991BFFDC7/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/592FEA8754>) |
| 2109:0817 | VIA Labs         | USB3.0 Hub                           | 23    | hub        | [7DEB9825C2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/355FDFB6283F/POP!_OS-22.04/5.15.0-1024-RASPI/AARCH64/7DEB9825C2>) |
| 05e3:0620 | Genesys Logic    | GL3523 Hub                           | 22    | hub        | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 214b:7250 | Huasheng Elec... | USB2.0 HUB                           | 22    | hub        | [CAF7D9B39A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6F7C76C14862/RASPBIAN-10/5.10.103-V7L+/ARMV7L/CAF7D9B39A>) |
| 05e3:0616 | Genesys Logic    | hub                                  | 19    | hub        | [2188A4A04E](<System On Chip/Hardkernel/Odroid/Odroid XU4/BDA5AE2539D0/DEBIAN-11/5.4.225-ODROIDXU4/ARMV7L/2188A4A04E>) |
| 1a40:0801 | Terminus Tech... | USB 2.0 Hub                          | 16    | hub        | [DDF24FD076](<System On Chip/khadas/VIM/VIM3/B1FC44241EF3/ROSA-12/5.10.74-GENERIC-2ROSA2021.1-ARM64/AARCH64/DDF24FD076>) |
| 0424:9512 | Microchip Tec... | SMC9512/9514 USB Hub                 | 14    | hub        | [3516608F3C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Model B Rev 2/E17DCD62E2FD/RASPBIAN-11/5.4.150+/ARMV6L/3516608F3C>) |
| 2109:2813 | VIA Labs         | VL813 Hub                            | 13    | hub        | [17AC97DC37](<System On Chip/Rockchip/Orange/Orange Pi 5/A6798147E384/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/17AC97DC37>) |
| 05ac:1006 | Apple            | Hub in Aluminum Keyboard             | 11    | apple_m... | [4382F0CCE7](<System On Chip/Radxa/ROCK/ROCK Pi 4B/57E79905A598/XUBUNTU-22.04/5.15.93-ROCKCHIP64/AARCH64/4382F0CCE7>) |
| 2109:0813 | VIA Labs         | VL813 Hub                            | 11    | hub        | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 05e3:0612 | Genesys Logic    | Hub                                  | 9     | hub        | [29F6C3C897](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/015935A967F6/DEBIAN-11/5.15.84-V8+/AARCH64/29F6C3C897>) |
| 0bda:0401 | Realtek Semic... | USB3.0 Hub                           | 9     | hub        | [F644B30D69](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D245CEC4938D/UBUNTU-22.04/5.15.0-1006-RASPI/AARCH64/F644B30D69>) |
| 0bda:5401 | Realtek Semic... | RTL 8153 USB 3.0 hub with gigabit... | 9     | hub        | [F644B30D69](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D245CEC4938D/UBUNTU-22.04/5.15.0-1006-RASPI/AARCH64/F644B30D69>) |
| 1a40:0201 | Terminus Tech... | FE 2.1 7-port Hub                    | 9     | hub        | [F9378D9804](<System On Chip/Rockchip/RK3288/RK3288 Asus Tinker Board S/EE8878FF231B/UBUNTU-22.04/5.15.80-ROCKCHIP/ARMV7L/F9378D9804>) |
| 0b95:6802 | ASIX Electronics | AX68002 KVM Switch SoC               | 8     | hub        | [C01B933066](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/BB83E3AF30AE/UBUNTU-22.04/5.15.0-1016-RASPI/AARCH64/C01B933066>) |
| 0b95:6804 | ASIX Electronics | AX68004                              | 8     | hub        | [19BB445EE4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/34613528FE2B/RASPBIAN-11/5.15.84+/ARMV6L/19BB445EE4>) |
| 0bda:0489 | Realtek Semic... | 4-Port USB 3.0 Hub                   | 7     | hub        | [A786D1F74E](<System On Chip/Nvidia/Jetson/Jetson Xavier NX Developer Kit/2CF7872C1C62/FEDORA-36/5.17.3-300.FC36.AARCH64/AARCH64/A786D1F74E>) |
| 0bda:5489 | Realtek Semic... | 4-Port USB 2.0 Hub                   | 7     | hub        | [A786D1F74E](<System On Chip/Nvidia/Jetson/Jetson Xavier NX Developer Kit/2CF7872C1C62/FEDORA-36/5.17.3-300.FC36.AARCH64/AARCH64/A786D1F74E>) |
| 045b:0209 | Hitachi          | Hub                                  | 6     | hub        | [E9BFE6DE60](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/9181F4238E83/DEBIAN-11/5.15.32-V8+/AARCH64/E9BFE6DE60>) |
| 058f:9254 | Alcor Micro      | Hub                                  | 6     | hub        | [CAF7D9B39A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6F7C76C14862/RASPBIAN-10/5.10.103-V7L+/ARMV7L/CAF7D9B39A>) |
| 05ac:1003 | Apple            | Hub in Pro Keyboard [Mitsumi, A1048] | 6     | hub        | [E574477CB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/24E449AF1324/RASPBIAN-11/5.15.32-V7L+/ARMV7L/E574477CB6>) |
| 14cd:8601 | Super Top        | 4-Port hub                           | 6     | hub        | [59A76AA42B](<System On Chip/Others/Shenzhen/Shenzhen CYX Industrial Co., Ltd A95XF3-AIR/9D8006F1DA1B/UBUNTU-22.04/5.15.45-FLIPPY-73+O/AARCH64/59A76AA42B>) |
| 2109:2812 | VIA Labs         | VL812 Hub                            | 6     | hub        | [3F823868FD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/B721BB87B27D/NIXOS-22.05/5.15.32/AARCH64/3F823868FD>) |
| 045b:0210 | Hitachi          | Hub                                  | 5     | hub        | [E9BFE6DE60](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/9181F4238E83/DEBIAN-11/5.15.32-V8+/AARCH64/E9BFE6DE60>) |
| 2109:0812 | VIA Labs         | VL812 Hub                            | 5     | hub        | [3F823868FD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/B721BB87B27D/NIXOS-22.05/5.15.32/AARCH64/3F823868FD>) |
| 2109:2815 | VIA Labs         | USB2.0 Hub                           | 5     | hub        | [EA0218B031](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/9877C059E9D7/RASPBIAN-11/5.15.56-V7+/ARMV7L/EA0218B031>) |
| 413c:1003 | Dell             | Keyboard Hub                         | 5     | hub        | [29E02A10BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/B04A08455F7D/RASPBIAN-11/5.15.76-V7L+/ARMV7L/29E02A10BF>) |
| 04b4:6502 | Cypress Semic... | CY4609                               | 4     | hub        | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 2109:2811 | VIA Labs         | Hub                                  | 4     | hub        | [F8FA8FDC4D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/3C2F4FDA790A/RASPBIAN-11/5.10.63-V7L+/ARMV7L/F8FA8FDC4D>) |
| 0424:2512 | Microchip Tec... | USB 2.0 Hub                          | 3     | hub        | [7616B8F6B7](<System On Chip/Nvidia/Tegra/Tegra/0A0982FDE24A/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/7616B8F6B7>) |
| 0424:2640 | Microchip Tec... | USB 2.0 Hub                          | 3     | hub        | [5D9CED37D2](<System On Chip/Others/Others/Others/03008CADF655/PUREOS-10.0/6.1.0-1-LIBREM5/AARCH64/5D9CED37D2>) |
| 0424:2744 | Microchip Tec... | Hub                                  | 3     | hub        | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 0424:5744 | Microchip Tec... | Hub                                  | 3     | hub        | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 04b4:6500 | Cypress Semic... | Cypress Hub                          | 3     | hub        | [63A5E327FB](<System On Chip/SolidRun/LX2160A/LX2160A Clearfog CX/446971F0A5EC/UBUNTU-20.04/5.10.35-00021-G3CC6354C3606/AARCH64/63A5E327FB>) |
| 05ac:1002 | Apple            | Extended Keyboard Hub [Mitsumi]      | 3     | hub        | [10D6088BF3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6C7B34346A0D/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/10D6088BF3>) |
| 05e3:0617 | Genesys Logic    | USB3.0 Hub                           | 3     | hub        | [E65C4D13BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/E65C4D13BF>) |
| 0a05:7211 |                  | hub                                  | 3     | hub        | [24EE06B435](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero Rev 1.3/DAC76A68429F/RASPBIAN-11/5.15.84+/ARMV6L/24EE06B435>) |
| 0bc2:ab44 | Seagate          | Backup Plus Hub                      | 3     | hub        | [ED5D3570EF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/D8CE448B5A10/DEBIAN-11/5.15.76-V8+/AARCH64/ED5D3570EF>) |

### Human interface (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0079:0006 | DragonRise       | PC TWIN SHOCK Gamepad                | 2     | usbhid     | [44FC490D82](<System On Chip/Others/Others/Others/EF9ED3C6C442/DEBIAN-11/5.10.68-STATION/AARCH64/44FC490D82>) |
| 0665:5161 | Cypress Semic... | USB to Serial                        | 2     | usbhid     | [23A61DFA8F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/7EC5A75B56F2/RASPBIAN-11/6.1.23-V8+/AARCH64/23A61DFA8F>) |
| 0079:1846 | DragonRise       | Controller Adapter                   | 1     | usbhid     | [15A1A38207](<System On Chip/Others/Others/Others/5E64C7087FBA/DEBIAN-11/5.10.110-1-ROCKCHIP/AARCH64/15A1A38207>) |
| 0451:82ff | Texas Instrum... | Monitor Control                      | 1     | usbhid     | [D48FD712A5](<System On Chip/Nvidia/Tegra/Tegra/A6096A1A9829/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/D48FD712A5>) |
| 046d:c216 | Logitech         | F310 Gamepad [DirectInput Mode]      | 1     | usbhid     | [A8BD03AC5B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/6DB17957B8F8/RASPBIAN-10/5.10.63-V8+/AARCH64/A8BD03AC5B>) |
| 046d:c222 | Logitech         | G15 Keyboard / LCD                   | 1     | usbhid     | [796691962C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/677EC6DF9624/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/796691962C>) |
| 047f:0113 | Plantronics      | Voyager Legend                       | 1     | usbhid     | [802945D7D4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/2A516F87783F/UBUNTU-19.10/5.3.0-1018-RASPI2/AARCH64/802945D7D4>) |
| 04b4:fd13 | Cypress Semic... | Energenie EG-PMS                     | 1     |            | [E7E5ACB3BB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/54C6E331D35E/RASPBIAN-10/5.4.51-V7L+/ARMV7L/E7E5ACB3BB>) |
| 054c:0268 | Sony             | Batoh Device / PlayStation 3 Cont... | 1     | usbhid     | [06612D9E40](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/56BD017D9BD5/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/06612D9E40>) |
| 054c:05c4 | Sony             | DualShock 4 [CUH-ZCT1x]              | 1     | usbhid     | [66F0F8092B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/014B8BE86E99/UBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/66F0F8092B>) |
| 05ac:055b | Apple            | Gamesir-G3w                          | 1     | usbhid     | [C9D96D72E1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/5EB4769E77ED/UBUNTU-18.04/4.19.75V64/AARCH64/C9D96D72E1>) |
| 05ac:9226 | Apple            | LED Cinema Display                   | 1     | usbhid     | [6ADCA880A0](<System On Chip/Nvidia/Tegra/Tegra/E316CF040727/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/6ADCA880A0>) |
| 06c4:c411 | Bizlink Inter... | D6000 Controller                     | 1     | usbhid     | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 06c4:c412 | Bizlink Inter... | DELL DA300                           | 1     |            | [28143BF30E](<System On Chip/Qualcomm Technologies/SDM845/SDM845 v2.1 MTP PVT/8B8A857D4C70/KALI-2022.1/4.9.254-NETHUNTER/AARCH64/28143BF30E>) |
| 08f7:0003 | Vernier          | Go!Link                              | 1     | usbhid     | [E6C6F42DD7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/B4B6F6A6BD4D/RASPBIAN-10/5.10.63-V7L+/ARMV7L/E6C6F42DD7>) |
| 0bda:48f0 | Realtek Semic... | USB Audio                            | 1     | usbhid     | [FB1D446B99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/FE2789F8F214/RASPBIAN-10/5.10.17+/ARMV6L/FB1D446B99>) |
| 1038:1122 | SteelSeries ApS  | SteelSeries KLC                      | 1     | usbhid     | [C57BCAA35D](<System On Chip/Radxa/ROCK/ROCK 5B/EE56FD79C0B0/PARROT-4.11/5.10.0-6PARROT1-AMD64/X86_64/C57BCAA35D>) |
| 1462:3fa4 | Micro Star In... | MSI Gaming Controller                | 1     | usb_sto... | [DE369A751A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/29BF1DBCCFC4/DEBIAN-11/6.1.19-V8+/AARCH64/DE369A751A>) |
| 22e1:f008 | TempoTec         | HD USB AUDIO                         | 1     | snd_usb... | [B8EA59E9F8](<System On Chip/Inspur/CE520/CE520F/3A556DC2B09D/DEBIAN-11/5.10.0-18-ARM64/AARCH64/B8EA59E9F8>) |
| 2563:0526 | ShenZhen Shan... | Trust MUTA Wireless                  | 1     | usbhid     | [DAE41A9529](<System On Chip/Nvidia/Tegra/Tegra/863D34773943/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/DAE41A9529>) |
| 2563:0555 | ShenZhen Shan... | Twin USB Joystick                    | 1     | usbhid     | [EC9EB5536D](<System On Chip/Others/Others/Others/086635414683/MANJARO-ARM/5.18.5-1-MANJARO-ARM-KHADAS/AARCH64/EC9EB5536D>) |
| 27c0:0858 | WingCoolTouch    |                                      | 1     | usbhid     | [0A8ADA10B5](<System On Chip/Nvidia/Tegra/Tegra/2B8AFCD2D256/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/0A8ADA10B5>) |
| 2b03:f781 | STEREOLABS       | ZED-2 HID INTERFACE                  | 1     | usbhid     | [7616B8F6B7](<System On Chip/Nvidia/Tegra/Tegra/0A0982FDE24A/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/7616B8F6B7>) |
| 6666:5555 | Prototype pro... | Weather Direct Light Wireless Device | 1     | usbhid     | [D99707EF15](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/AB56BC5C369A/DEBIAN-11/5.18.0-3-ARM64/AARCH64/D99707EF15>) |

### Input/keyboard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:c52b | Logitech         | Unifying Receiver                    | 199   | usbhid     | [50A67AB03C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/3A28E3EB24BC/RASPBIAN-10/5.10.103-V7+/ARMV7L/50A67AB03C>) |
| 04d9:0007 | Holtek Semico... | Raspberry Pi Internal Keyboard       | 91    | usbhid     | [71FF8CCA4E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/2ABF1A0B9A2D/UBUNTU-22.10/5.19.0-1017-RASPI/AARCH64/71FF8CCA4E>) |
| 046d:c534 | Logitech         | Unifying Receiver                    | 85    | usbhid     | [BE369FE18A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/50224502A0D4/DEBIAN-11/5.15.84-V8+/AARCH64/BE369FE18A>) |
| 04d9:0006 | Holtek Semico... | Wired Keyboard (78/79 key) [RPI W... | 46    | usbhid     | [17AC97DC37](<System On Chip/Rockchip/Orange/Orange Pi 5/A6798147E384/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/17AC97DC37>) |
| 046d:c31c | Logitech         | Keyboard K120                        | 33    | usbhid     | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 062a:4101 | MosArt Semico... | Wireless Keyboard/Mouse              | 27    | usbhid     | [CAF7D9B39A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6F7C76C14862/RASPBIAN-10/5.10.103-V7L+/ARMV7L/CAF7D9B39A>) |
| 1997:2433 | Shenzhen Riit... | wireless mini keyboard with touchpad | 23    | usbhid     | [FBA90ACF4D](<System On Chip/libre-computer/aml-s905/aml-s905x-cc/21BB4942570F/DEBIAN-11/6.0.19-02543-G73F2949C2DD9/AARCH64/FBA90ACF4D>) |
| 413c:2113 | Dell             | KB216 Wired Keyboard                 | 23    | usbhid     | [EF312297D4](<System On Chip/Rockchip/Others/Others/0AE7935BE0EA/UBUNTU-20.04/4.4.194-11-RK3399-ROCKCHIP-G1BB08D49CC40/AARCH64/EF312297D4>) |
| 045e:0745 | Microsoft        | Nano Transceiver v1.0 for Bluetooth  | 20    | usbhid     | [764115860E](<System On Chip/Others/Others/Others/3BC233EB6C65/DEBIAN-11/5.15.74-ROCKCHIP/ARMV7L/764115860E>) |
| 1c4f:0002 | SiGma Micro      | Keyboard TRACER Gamma Ivory          | 19    | usbhid     | [42F1A36ACE](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/3D0BF9B58B59/RASPBIAN-11/5.15.84-V7+/ARMV7L/42F1A36ACE>) |
| 413c:2107 | Dell             | KB212-B Quiet Key Keyboard           | 11    | usbhid     | [2D767E0513](<System On Chip/Rockchip/Orange/Orange Pi 5/B6466CB0DFF0/DEBIAN-11/5.10.110-ROCKCHIP-RK3588/AARCH64/2D767E0513>) |
| 046a:0023 | Cherry           | Keyboard                             | 10    | usbhid     | [78A631609D](<System On Chip/Radxa/ROCK/ROCK 5B/9FE9E6CD2459/GENTOO-2.9/5.10.110-274242-GC7EF840FB61B-DIRTY/AARCH64/78A631609D>) |
| 0513:0318 | digital-X        | USB Mouse                            | 10    | usbhid     | [DEA44E447F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D076D229E435/UBUNTU-22.04/5.15.0-1014-RASPI/AARCH64/DEA44E447F>) |
| 046a:0011 | Cherry           | G83 (RS 6000) Keyboard               | 8     | usbhid     | [052379F89E](<System On Chip/Others/Xiaobao/Xiaobao Nas I/7B0A3C55476F/ATZ-11.4/5.15.52-ROCKCHIP64/AARCH64/052379F89E>) |
| 04d9:1702 | Holtek Semico... | Keyboard LKS02                       | 8     | usbhid     | [1FF18A82B8](<System On Chip/Edelweiss/TF307/TF307-MB-S-D/B1DFE0530581/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-ARM64/AARCH64/1FF18A82B8>) |
| 0c45:7603 | Microdia         | USB Keyboard                         | 8     | usbhid     | [592FEA8754](<System On Chip/Radxa/ROCK/ROCK 5B/139991BFFDC7/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/592FEA8754>) |
| 4037:2804 |                  | 2.4G Composite Devic                 | 8     | usbhid     | [5FA6CEED90](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/AE6DCB247DE7/DEBIAN-11/5.15.76-V8+/AARCH64/5FA6CEED90>) |
| 413c:2003 | Dell             | Keyboard SK-8115                     | 8     | usbhid     | [998427CDCF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/05F8D3262304/POP!_OS-22.04/5.15.0-1027-RASPI/AARCH64/998427CDCF>) |
| 1a2c:0e24 | China Resourc... | USB Keyboard                         | 7     | usbhid     | [AA0A31A88D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/4E60FA81B497/ATZ-11.5/5.15.61-V8+/AARCH64/AA0A31A88D>) |
| 1a2c:2124 | China Resourc... | Keyboard                             | 7     | usbhid     | [C2F69BB6EF](<System On Chip/Others/Others/Others/D70379D8CACE/UBUNTU-20.04/3.16.85-65/AARCH64/C2F69BB6EF>) |
| 03f0:0024 | Hewlett-Packard  | KU-0316 Keyboard                     | 6     | usbhid     | [F9382ECE8E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/0DFA695573B0/RASPBIAN-11/6.1.21-V7+/ARMV7L/F9382ECE8E>) |
| 045e:0800 | Microsoft        | Wireless keyboard (All-in-One-Media) | 6     | usbhid     | [BF1ABA4EBE](<System On Chip/Rockchip/RK3318/RK3318 BOX/51BD593B42AC/XUBUNTU-22.04/5.15.59-ROCKCHIP64/AARCH64/BF1ABA4EBE>) |
| 0461:0010 | Primax Electr... | HP PR1101U / Primax PMX-KPR1101U ... | 6     | usbhid     | [E2B4056812](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/752C931C0AAF/XUBUNTU-22.04/5.15.61-BCM2711/AARCH64/E2B4056812>) |
| 046d:c52e | Logitech         | MK260 Wireless Combo Receiver        | 6     | usbhid     | [901194D1E1](<System On Chip/FriendlyElec/NanoPC-T/NanoPC-T4/A458CAB83B53/DEBIAN-11/5.10.0-21-ARM64/AARCH64/901194D1E1>) |
| 04f3:0103 | Elan Microele... | ActiveJet K-2024 Multimedia Keyboard | 6     | usbhid     | [018EB0B0BB](<System On Chip/NCI/PC/PC BLICK101/3CFE875BAE08/RED-OS-7.3/5.4.197-1.EL7.AARCH64/AARCH64/018EB0B0BB>) |
| 1a2c:2d23 | China Resourc... | Keyboard                             | 6     | usbhid     | [4020E881A1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/60B300074A8A/MANJARO-ARM/5.10.39-1-MANJARO-ARM/AARCH64/4020E881A1>) |
| 24ae:2010 | Shenzhen Rapo... | 2.4G Wireless Device                 | 6     | usbhid     | [E2BEED8EE0](<System On Chip/Xunlong/Orange/Orange Pi Plus 2E/687EE73FF56F/DEBIAN-11/5.15.43-SUNXI/ARMV7L/E2BEED8EE0>) |
| 25a7:fa61 | Areson Techno... | Elecom Co., Ltd MR-K013 Multicard... | 6     | usbhid     | [7952EC28EF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/753FC4525BFA/RASPBIAN-11/5.15.56-V7L+/ARMV7L/7952EC28EF>) |
| 045e:07b2 | Microsoft        | 2.4GHz Transceiver v8.0 used by m... | 5     | usbhid     | [C66FAF607D](<System On Chip/Others/Others/Others/646B2BF92C9A/UBUNTU-20.04/4.9.277-82/AARCH64/C66FAF607D>) |
| 045e:07f8 | Microsoft        | Wired Keyboard 600 (model 1576)      | 5     | usbhid     | [781AE865B0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/A718511717F4/DEBIAN-11/5.15.32-V8+/AARCH64/781AE865B0>) |
| 046d:c31d | Logitech         | Media Keyboard K200                  | 5     | usbhid     | [DA62C7238D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/04E93A648E41/XUBUNTU-18.04/5.4.0-1056-RASPI/AARCH64/DA62C7238D>) |
| 05ac:0250 | Apple            | Aluminium Keyboard (ISO)             | 5     | usbhid     | [5542DE4F04](<System On Chip/Xunlong/Orange/Orange Pi One/859CDF64A438/UBUNTU-22.04/5.15.93-SUNXI/ARMV7L/5542DE4F04>) |
| 1ea7:0066 | SHARKOON Tech... | [Mediatrack Edge Mini Keyboard]      | 5     | usbhid     | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 258a:0001 | SINO WEALTH      | USB KEYBOARD                         | 5     | usbhid     | [53A2BB987D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/B7CAE3493BED/RASPBIAN-10/5.10.63-V7+/ARMV7L/53A2BB987D>) |
| 258a:001e | SIGMACHIP        | USB Keyboard                         | 5     | usbhid     | [D8CD86DB45](<System On Chip/PINE64/Pinebook/Pinebook Pro/9912F73F6133/FEDORA-37/6.0.7-301.FC37.AARCH64/AARCH64/D8CD86DB45>) |
| 413c:2010 | Dell             | Keyboard                             | 5     | usbhid     | [29E02A10BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/B04A08455F7D/RASPBIAN-11/5.15.76-V7L+/ARMV7L/29E02A10BF>) |
| 04d9:1603 | Holtek Semico... | Keyboard                             | 4     | usbhid     | [1A369AD73A](<System On Chip/Nvidia/Tegra/Tegra/ADBC4F66375D/LUBUNTU-18.04/4.9.253-TEGRA/AARCH64/1A369AD73A>) |
| 05ac:020c | Apple            | Extended Keyboard [Mitsumi]          | 4     | usbhid     | [E574477CB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/24E449AF1324/RASPBIAN-11/5.15.32-V7L+/ARMV7L/E574477CB6>) |
| 05ac:0221 | Apple            | Aluminum Keyboard (ISO)              | 4     | usbhid     | [4382F0CCE7](<System On Chip/Radxa/ROCK/ROCK Pi 4B/57E79905A598/XUBUNTU-22.04/5.15.93-ROCKCHIP64/AARCH64/4382F0CCE7>) |
| 0b95:6801 | ASIX Electronics | AX68004                              | 4     | usbhid     | [19BB445EE4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/34613528FE2B/RASPBIAN-11/5.15.84+/ARMV6L/19BB445EE4>) |
| 0e6a:02c0 | Megawin Techn... | Defender Gaming Keyboard             | 4     | usbhid     | [16C06E9416](<System On Chip/Hardkernel/ODROID-M/ODROID-M1/38A39AD81389/UBUNTU-20.04/4.19.219-ODROID-ARM64/AARCH64/16C06E9416>) |
| 0e8f:0022 | GreenAsia        | multimedia keyboard controller       | 4     | usbhid     | [56F65F30B3](<System On Chip/sunxi/LeMaker/LeMaker Banana Pi/2DFB2CBA3E83/XUBUNTU-22.04/5.15.74-SUNXI/ARMV7L/56F65F30B3>) |
| 24ae:2013 | Shenzhen Rapo... | Rapoo 2.4G Wireless Device           | 4     | usbhid     | [FF9B46FD29](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/4E60FA81B497/ATZ-11.3/5.15.32-V8+/AARCH64/FF9B46FD29>) |
| 25a7:fa67 | Areson Techno... | 2.4G Receiver                        | 4     | usbhid     | [08EF3B4EB5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/659022AFEF90/UBUNTU-21.10/5.13.0-1024-RASPI/AARCH64/08EF3B4EB5>) |
| 276d:3257 | YSTEK Technology | 2.4G RF Keyboard & Mouse             | 4     | usbhid     | [D59DA741C5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/BFC645C66AAC/UBUNTU-21.10/5.10.43V64/AARCH64/D59DA741C5>) |
| 413c:2005 | Dell             | RT7D50 Keyboard                      | 4     | usbhid     | [DD05575BB4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/94832BF0E91C/DEBIAN-11/5.15.61-V8+/AARCH64/DD05575BB4>) |
| 03f0:0324 | Hewlett-Packard  | SK-2885 keyboard                     | 3     | usbhid     | [311E49C553](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/B4208B608F83/KALI-2023.1/5.4.83-RE4SON-V8L+/AARCH64/311E49C553>) |
| 045e:00db | Microsoft        | Natural Ergonomic Keyboard 4000 V1.0 | 3     | usbhid     | [632A8A0AD8](<System On Chip/sunxi/Allwinner/Allwinner sun7i Family/0AF4EB9982A2/XUBUNTU-22.04/5.15.48-SUNXI/ARMV7L/632A8A0AD8>) |
| 045e:0752 | Microsoft        | Wired Keyboard 400                   | 3     | usbhid     | [965F364F1D](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/0B7E187F6FBF/MANJARO-ARM-21.10/5.16.0-RC3-1-MANJARO-ARM/AARCH64/965F364F1D>) |
| 045e:078c | Microsoft        | USB Keyboard                         | 3     | usbhid     | [1F1FC02023](<System On Chip/Others/Others/Others/F4E06447D552/UBUNTU-20.04/5.4.0-1003-MTK/AARCH64/1F1FC02023>) |

### Input/mouse (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 093a:2510 | Pixart Imaging   | Optical Mouse                        | 118   | usbhid     | [2F16B0A530](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.1/07B3CFEBDD4B/KALI-2023.1/5.15.44-RE4SON-V8L+/AARCH64/2F16B0A530>) |
| 046d:c077 | Logitech         | Mouse                                | 30    | usbhid     | [5A3CB266DB](<System On Chip/GreatWall/DF/DF/5813E68F06D1/DEBIAN-11/5.10.0-22-ARM64/AARCH64/5A3CB266DB>) |
| 046d:c52f | Logitech         | Unifying Receiver                    | 25    | usbhid     | [78A631609D](<System On Chip/Radxa/ROCK/ROCK 5B/9FE9E6CD2459/GENTOO-2.9/5.10.110-274242-GC7EF840FB61B-DIRTY/AARCH64/78A631609D>) |
| 248a:8367 | Maxxter          | Telink Wireless Receiver             | 16    | usbhid     | [48AB84D4F4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/50224502A0D4/DEBIAN-11/5.15.84-V8+/AARCH64/48AB84D4F4>) |
| 046d:c05a | Logitech         | M90/M100 Optical Mouse               | 15    | usbhid     | [5236B9452C](<System On Chip/Rockchip/Others/Others/46F00341A611/DEBIAN-11/4.4.202-1237-ROCKCHIP-AYUFAN-GFD4492386213/AARCH64/5236B9452C>) |
| 1ea7:0064 | SHARKOON Tech... | 2.4GHz Wireless rechargeable vert... | 13    | usbhid     | [AA0A31A88D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/4E60FA81B497/ATZ-11.5/5.15.61-V8+/AARCH64/AA0A31A88D>) |
| 1c4f:0034 | SiGma Micro      | XM102K Optical Wheel Mouse           | 12    | usbhid     | [592FEA8754](<System On Chip/Radxa/ROCK/ROCK 5B/139991BFFDC7/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/592FEA8754>) |
| 1bcf:0005 | Sunplus Innov... | Optical Mouse                        | 10    | usbhid     | [F7AF4B1164](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/21904A6C1DF6/DEBIAN-11/5.15.76-V8+/AARCH64/F7AF4B1164>) |
| 413c:301a | Dell             | Dell MS116 Optical Mouse             | 10    | usbhid     | [AC565D5D7D](<System On Chip/Xunlong/Orange/Orange Pi PC Plus/96B482F42282/XUBUNTU-22.04/5.15.93-SUNXI/ARMV7L/AC565D5D7D>) |
| 0416:c168 | Winbond Elect... | MTouch                               | 9     | usbhid     | [EA3430977C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/34DC0FA7FB6C/RASPBIAN-11/6.1.19-V8+/AARCH64/EA3430977C>) |
| 222a:0001 | ILI Technology   | Multi-Touch Screen                   | 9     | usbhid     | [6F492F55C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F41C4EB93F2B/UBUNTU-22.04/5.15.0-1015-RASPI/AARCH64/6F492F55C3>) |
| 275d:0ba6 |                  | USB OPTICAL MOUSE                    | 9     | usbhid     | [C008FC6206](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/A801B8CEEC01/DEBIAN-11/5.15.61-V8+/AARCH64/C008FC6206>) |
| 0000:3825 |                  | USB OPTICAL MOUSE                    | 8     | usbhid     | [D57318F254](<System On Chip/Nvidia/Tegra/Tegra/08DCF44A15CD/XUBUNTU-20.04/4.9.140-TEGRA/AARCH64/D57318F254>) |
| 093a:2521 | Pixart Imaging   | Optical Mouse                        | 8     | usbhid     | [7AEB73D109](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/378385C3965D/UBUNTU-21.04/5.11.0-1007-RASPI/AARCH64/7AEB73D109>) |
| 046d:c016 | Logitech         | Optical Wheel Mouse                  | 7     | usbhid     | [C564829AE4](<System On Chip/Amlogic/Meson8/Meson8B/F0FC5B0515B8/XUBUNTU-18.04/3.10.108/ARMV7L/C564829AE4>) |
| 046d:c050 | Logitech         | RX 250 Optical Mouse                 | 7     | usbhid     | [62974AF203](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D774D23D7181/UBUNTU-22.04/5.15.0-1006-RASPI/AARCH64/62974AF203>) |
| 04f2:0939 | Chicony Elect... | Amazon Basics mouse                  | 7     | usbhid     | [D355D76B47](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/7C8C2633D6CC/UBUNTU-22.04/5.15.0-1014-RASPI/AARCH64/D355D76B47>) |
| 05ac:0304 | Apple            | Mighty Mouse [Mitsumi, M1152]        | 7     | usbhid     | [41DA6A7BFB](<System On Chip/libre-computer/aml-s905/aml-s905x-cc/8DF32D522A87/UBUNTU-22.04/6.0.12-00858-GB98721EA4575/AARCH64/41DA6A7BFB>) |
| 17ef:6019 | Lenovo           | M-U0025-O Mouse                      | 6     | usbhid     | [C209FC2B22](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/1C544B0D5DB6/DEBIAN-11/5.15.76-V8+/AARCH64/C209FC2B22>) |
| 1bcf:08a0 | Sunplus Innov... | Gaming mouse [Philips SPK9304]       | 6     | usbhid     | [A922F68180](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6C627570BFAB/LUBUNTU-22.04/5.15.0-1017-RASPI/AARCH64/A922F68180>) |
| 248a:8514 | Maxxter          | Wireless Receiver                    | 6     | usbhid     | [CAF7D9B39A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/6F7C76C14862/RASPBIAN-10/5.10.103-V7L+/ARMV7L/CAF7D9B39A>) |
| 0000:0538 |                  | USB OPTICAL MOUSE                    | 5     | usbhid     | [27C1DAE829](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4CA5A946C266/UBUNTU-22.04/5.15.0-1011-RASPI/AARCH64/27C1DAE829>) |
| 03f0:0941 | Hewlett-Packard  | X500 Optical Mouse                   | 5     | usbhid     | [543099B0FA](<System On Chip/Radxa/ROCK/ROCK Pi 4/733E621E45CC/MANJARO-ARM-20.03/5.6.0-0.42-MANJARO-ARM/AARCH64/543099B0FA>) |
| 045e:00cb | Microsoft        | Basic Optical Mouse v2.0             | 5     | usbhid     | [1FF18A82B8](<System On Chip/Edelweiss/TF307/TF307-MB-S-D/B1DFE0530581/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-ARM64/AARCH64/1FF18A82B8>) |
| 046d:c040 | Logitech         | Corded Tilt-Wheel Mouse              | 5     | usbhid     | [8E6770F9BD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/946C8531B9B0/DEBIAN-11/5.10.0-8-ARM64/AARCH64/8E6770F9BD>) |
| 25a7:fa23 | Areson Techno... | 2.4G Receiver                        | 5     | usbhid     | [2860BCE826](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4FAC1337C966/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/2860BCE826>) |
| 03f0:094a | Hewlett-Packard  | Optical Mouse [672662-001]           | 4     | usbhid     | [4C292CFF97](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2E8ADBA8214D/RASPBIAN-11/5.15.74-V7L+/ARMV7L/4C292CFF97>) |
| 0461:4d0f | Primax Electr... | HP Optical Mouse                     | 4     | usbhid     | [17AC97DC37](<System On Chip/Rockchip/Orange/Orange Pi 5/A6798147E384/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/17AC97DC37>) |
| 04d9:0499 | Holtek Semico... | Optical Mouse                        | 4     | usbhid     | [989B41F386](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EBA7FC9211A8/UBUNTU-22.04/5.15.0-1008-RASPI/AARCH64/989B41F386>) |
| 093a:2533 | Pixart Imaging   | Gaming Mouse                         | 4     | usbhid     | [011C3940F9](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/D8CD1CEE9DA6/DEBIAN-11/5.15.84-V8+/AARCH64/011C3940F9>) |
| 0c45:8101 | Microdia         | USB Device                           | 4     | usbhid     | [0892AC4796](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A34A798254/UBUNTU-21.10/5.13.0-1015-RASPI/AARCH64/0892AC4796>) |
| 3151:3000 | YICHIP           | Wireless Device                      | 4     | usbhid     | [DA1BDD1D3D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5CF2FF51D8A9/UBUNTU-22.04/5.15.0-1024-RASPI/AARCH64/DA1BDD1D3D>) |
| 3938:1080 | YK               | 2.4G Wireless Device                 | 4     | usbhid     | [A02943108D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/A73CFAED1C43/UBUNTU-18.04/4.15.0-1077-RASPI2/ARMV7L/A02943108D>) |
| 0461:4de2 | Primax Electr... | USB Optical Mouse                    | 3     | usbhid     | [3FD62A1D06](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3769F7792AE7/UBUNTU-21.10/5.13.0-1029-RASPI/AARCH64/3FD62A1D06>) |
| 046d:c07e | Logitech         | G402 Gaming Mouse                    | 3     | usbhid     | [62347DFD8D](<System On Chip/Others/Others/Others/728DA564B431/SLACKWARE-14.2/4.4.206+/AARCH64/62347DFD8D>) |
| 04ca:0061 | Lite-On Techn... | USB Optical Mouse                    | 3     | usbhid     | [B246EBE37C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/5532B9D494DE/RASPBIAN-10/5.10.17-V7+/ARMV7L/B246EBE37C>) |
| 10c4:8108 | Silicon Labs     | USB OPTICAL MOUSE                    | 3     | usbhid     | [2EAD7FB94B](<System On Chip/Khadas/VIM/VIM2/5790791A9DC3/XUBUNTU-18.04/5.0.0-AML-S912-GF2F3A8C1A-DIRTY/AARCH64/2EAD7FB94B>) |
| 1532:0003 | Razer USA        | Krait Mouse                          | 3     | usbhid     | [AB4793DC5E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/2623DFFA12CE/GENTOO-2.7/5.10.63-RPI3/AARCH64/AB4793DC5E>) |
| 18f8:0f97 | [Maxxter]        | Optical Gaming Mouse [Xtrem]         | 3     | usbhid     | [4B04BE2436](<System On Chip/Rockchip/Others/Others/F590D4D52D83/UBUNTU-20.04/4.4.154-113-ROCKCHIP-GDB9DFC2CDD25/AARCH64/4B04BE2436>) |
| 1bcf:0007 | Sunplus Innov... | Optical Mouse                        | 3     | usbhid     | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 248a:8368 | Maxxter          | Wireless Receiver                    | 3     | usbhid     | [168B774A5B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/C3613DF75B87/UBUNTU-22.04/5.15.0-1012-RASPI/AARCH64/168B774A5B>) |
| 24ae:1100 | Shenzhen Rapo... | Rapoo 2.4G Wireless Device           | 3     | usbhid     | [E88EEB7239](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/656E6812F7EB/RASPBIAN-10/5.10.103-V7L+/ARMV7L/E88EEB7239>) |
| 258a:1007 | SINOWEALTH       | Game Mouse                           | 3     | usbhid     | [46AE253039](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/6BE5E3ABA36B/DEBIAN-11/5.10.43V64/AARCH64/46AE253039>) |
| 276d:1119 | YSTEK            | G Mouse                              | 3     | usbhid     | [DB72A98D92](<System On Chip/Rockchip/RK3288/RK3288 Asus Tinker Board S/3CE8E05BA615/UBUNTU-20.04/5.15.25-ROCKCHIP/ARMV7L/DB72A98D92>) |
| 03f0:134a | Hewlett-Packard  | Optical Mouse                        | 2     | usbhid     | [E574477CB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/24E449AF1324/RASPBIAN-11/5.15.32-V7L+/ARMV7L/E574477CB6>) |
| 0458:0007 | KYE Systems (... | Trackbar Emotion                     | 2     | usbhid     | [D243B289C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/C701E4440D09/UBUNTU-21.04/5.11.0-1009-RASPI/AARCH64/D243B289C3>) |
| 0458:0186 | KYE Systems (... | Genius DX-120 Mouse                  | 2     | usbhid     | [8B8B6527F5](<System On Chip/Radxa/Zero/Zero/0D63B88E9410/UBUNTU-20.04/5.10.110-MESON64/AARCH64/8B8B6527F5>) |
| 045e:0797 | Microsoft        | Optical Mouse 200                    | 2     | usbhid     | [E3CE4C2D95](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/0CEE906562A8/RASPBIAN-10/5.10.103-V7+/ARMV7L/E3CE4C2D95>) |
| 0461:4d17 | Primax Electr... | Optical Mouse                        | 2     | usbhid     | [4D1339EF49](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/CD7CD841DF03/UBUNTU-22.04/5.15.0-1013-RASPI/AARCH64/4D1339EF49>) |
| 0461:4d64 | Primax Electr... | Asus wired optical mouse - Model ... | 2     | usbhid     | [CF8601E4F0](<System On Chip/Nvidia/Tegra/Tegra/2B3775F7B28D/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/CF8601E4F0>) |

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
| 2341:0043 | Arduino SA       | Uno R3 (CDC ACM)                     | 4     | cdc_acm    | [18294DD367](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/00827297B847/DEBIAN-11/5.10.103-V8+/AARCH64/18294DD367>) |
| 0483:5740 | STMicroelectr... | Virtual COM Port                     | 3     | cdc_acm    | [32B0B1581C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/94EAD393C973/RASPBIAN-10/5.10.52-V7L+/ARMV7L/32B0B1581C>) |
| 0658:0200 | Sigma Designs    | Aeotec Z-Stick Gen5 (ZW090) - UZB    | 2     | cdc_acm    | [8E925E1C6D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/77B81E0E5D85/RASPBIAN-11/4.19.66-V7+/ARMV7L/8E925E1C6D>) |
| 12d1:1001 | Huawei Techno... | E161/E169/E620/E800 HSDPA Modem      | 2     | option     | [CD7F5ACA29](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/FE6FE1EF7D0C/RASPBIAN-10/5.10.103-V7L+/ARMV7L/CD7F5ACA29>) |
| 1cf1:0030 | Dresden Elekt... | ZigBee gateway [ConBee II]           | 2     | cdc_acm    | [BE0BA34F37](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/A7182D901236/RASPBIAN-11/5.15.76-V7L+/ARMV7L/BE0BA34F37>) |
| 03eb:204b | Atmel            | LUFA USB to Serial Adapter Project   | 1     | cdc_acm    | [BE0BA34F37](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/A7182D901236/RASPBIAN-11/5.15.76-V7L+/ARMV7L/BE0BA34F37>) |
| 0451:16a8 | Texas Instrum... | CC2531 ZigBee                        | 1     | cdc_acm    | [7D51E2E653](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CC98E2BA2A1B/RASPBIAN-10/4.19.118-V7L+/ARMV7L/7D51E2E653>) |
| 0572:1321 | Conexant Systems | USB Modem                            | 1     | cdc_acm    | [71717109C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/E6673FFC2012/RASPBIAN-11/5.15.32-V7+/ARMV7L/71717109C3>) |
| 0572:1340 | Conexant Systems | USB Modem                            | 1     | cdc_acm    | [705FA3E0A1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/7D8C9D56FA28/UBUNTU-20.04/5.4.0-1069-RASPI/ARMV7L/705FA3E0A1>) |
| 0e8d:7127 | MediaTek         | FM350-GL                             | 1     | rndis_host | [34CD286C5F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.1/F4CECE04E250/UBUNTU-22.04/5.15.0-1021-RASPI/AARCH64/34CD286C5F>) |
| 12d1:1506 | Huawei Techno... | Modem/Networkcard                    | 1     | usb_sto... | [A69564B477](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/573F7C7803A6/RASPBIAN-10/5.15.45-V8+/AARCH64/A69564B477>) |
| 1546:01a7 | U-Blox           | [u-blox 7]                           | 1     | cdc_acm    | [A617383C6F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/488EC17BC74D/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/A617383C6F>) |
| 18d1:d001 | Google           | Nexus 4 (fastboot)                   | 1     | rndis_host | [F2C4A2F8E9](<System On Chip/sunxi/Others/Others/F2F5CE95D58C/DEBIAN-10/5.10.34-SUNXI64/AARCH64/F2C4A2F8E9>) |
| 1965:001a | Uniden           | BCD436HP Scanner                     | 1     |            | [51A5C15FA6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/B88D7E0EB8C2/RASPBIAN-11/5.15.32+/ARMV6L/51A5C15FA6>) |
| 1a86:55d4 | QinHeng Elect... | USB Single Serial                    | 1     |            | [094563419E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/52BB409DF306/DEBIAN-11/5.15.84-V8+/AARCH64/094563419E>) |
| 1cbc:0007 | EPC MSU          | EyePoint Signature Analyzer (IVM)    | 1     | cdc_acm    | [6AD73C849B](<System On Chip/Khadas/VIM/VIM3/9239F4567E3E/UBUNTU-20.04/4.9.241/AARCH64/6AD73C849B>) |
| 1eaf:0024 | Leaflabs         | DevTerm                              | 1     | cdc_acm    | [6C1B0DF48A](<System On Chip/sunxi/Others/Others/6A9E1BD0578E/UBUNTU-21.04/5.10.75-SUNXI64/AARCH64/6C1B0DF48A>) |
| 2341:0042 | Arduino SA       | Mega 2560 R3 (CDC ACM)               | 1     | cdc_acm    | [E513434675](<System On Chip/Radxa/ROCK/ROCK Pi 4C+/423812C7428B/XUBUNTU-22.04/5.15.89-ROCKCHIP64/AARCH64/E513434675>) |
| 2e8a:0004 | Raspberry Pi     | Picoprobe                            | 1     | cdc_acm    | [B6A4466BD7](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/D30FDAF93B1A/RASPBIAN-11/5.15.32-V7L+/ARMV7L/B6A4466BD7>) |
| 2e8a:0005 | MicroPython      | Board in FS mode                     | 1     | cdc_acm    | [D6B65A07A2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/D30FDAF93B1A/RASPBIAN-11/5.15.32-V7L+/ARMV7L/D6B65A07A2>) |

### Net/ethernet (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:8156 | Realtek Semic... | USB 10/100/1G/2.5G LAN               | 3     | r8152      | [CCC97B1211](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E8540BA672CD/UBUNTU-22.10/5.19.0-1004-RASPI/AARCH64/CCC97B1211>) |
| 0fe6:9900 | ICS Advent       | 10/100M LAN                          | 2     | cdc_ether  | [015AA87271](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/FEEDE16402FB/DEBIAN-11/5.15.32-V8+/AARCH64/015AA87271>) |

### Net/wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:8179 | Realtek Semic... | RTL8188EUS 802.11n Wireless Netwo... | 17    | r8188eu    | [F1537BEEDF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8ED828060896/RASPBIAN-12/6.1.21-V7+/ARMV7L/F1537BEEDF>) |
| 148f:5370 | Ralink Techno... | RT5370 Wireless Adapter              | 15    | rt2800usb  | [3E411BDADE](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/43D66AB65374/RASPBIAN-11/6.1.24-V8+/AARCH64/3E411BDADE>) |
| 0bda:b812 | Realtek Semic... | RTL88x2bu [AC1200 Techkey]           | 13    | 88x2bu     | [D5ECBDF7E4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/1B6D3E4A31DC/RASPBIAN-11/6.1.21-V8+/AARCH64/D5ECBDF7E4>) |
| 0bda:c811 | Realtek Semic... | 802.11ac NIC                         | 13    | rtl8821cu  | [A1C0A82172](<System On Chip/OrangePi/4/4/6C91BA6EBD27/XUBUNTU-21.04/4.4.213-RK3399/AARCH64/A1C0A82172>) |
| 148f:7601 | Ralink Techno... | MT7601U Wireless Adapter             | 11    | mt7601u    | [2C41D3C020](<System On Chip/libre-computer/aml-s905/aml-s905x-cc/3AF9FDDC0567/DEBIAN-11/6.1.22-04691-G10D99E724BD0/AARCH64/2C41D3C020>) |
| 2357:011e | TP-Link          | AC600 wireless Realtek RTL8811AU ... | 9     | 8812au     | [E3CE4C2D95](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/0CEE906562A8/RASPBIAN-10/5.10.103-V7+/ARMV7L/E3CE4C2D95>) |
| 148f:5572 | Ralink Techno... | RT5572 Wireless Adapter              | 7     | rt2800usb  | [24EE06B435](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero Rev 1.3/DAC76A68429F/RASPBIAN-11/5.15.84+/ARMV6L/24EE06B435>) |
| 2357:010c | TP-Link          | TL-WN722N v2/v3 [Realtek RTL8188EUS] | 6     | 8188eu     | [2F16B0A530](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.1/07B3CFEBDD4B/KALI-2023.1/5.15.44-RE4SON-V8L+/AARCH64/2F16B0A530>) |
| 0bda:8176 | Realtek Semic... | RTL8188CUS 802.11n WLAN Adapter      | 5     | rtl8192cu  | [58B8028451](<System On Chip/Others/Others/Others/E304453730D2/KALI-2022.1/4.14.272-GULCHR/AARCH64/58B8028451>) |
| 0bda:a811 | Realtek Semic... | RTL8811AU 802.11a/b/g/n/ac WLAN A... | 5     | 88XXau     | [6F492F55C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F41C4EB93F2B/UBUNTU-22.04/5.15.0-1015-RASPI/AARCH64/6F492F55C3>) |
| 0e8d:7612 | MediaTek         | MT7612U 802.11a/b/g/n/ac Wireless... | 5     | mt76x2u    | [2D767E0513](<System On Chip/Rockchip/Orange/Orange Pi 5/B6466CB0DFF0/DEBIAN-11/5.10.110-ROCKCHIP-RK3588/AARCH64/2D767E0513>) |
| 2357:0120 | TP-Link          | Archer T2U PLUS [RTL8821AU]          | 5     | 88XXau     | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 0b05:17d2 | ASUSTek Computer | USB-AC56 802.11a/b/g/n/ac Wireles... | 4     | 8812au     | [6DB0AEC69B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B308F978ACC3/UBUNTU-20.10/5.8.0-1032-RASPI/AARCH64/6DB0AEC69B>) |
| 0bda:818b | Realtek Semic... | RTL8192EU 802.11b/g/n WLAN Adapter   | 4     | rtl8xxxu   | [418B5DD7FF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/90053BBD0C39/PARROT-5.2/5.10.92-V8+/AARCH64/418B5DD7FF>) |
| 0bda:8812 | Realtek Semic... | RTL8812AU 802.11a/b/g/n/ac 2T2R D... | 4     | 8812au     | [4C292CFF97](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2E8ADBA8214D/RASPBIAN-11/5.15.74-V7L+/ARMV7L/4C292CFF97>) |
| 148f:5372 | Ralink Techno... | RT5372 Wireless Adapter              | 4     | rt2800usb  | [F62074389E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Model B Plus Rev 1.2/3C6951195636/RASPBIAN-11/5.15.56+/ARMV6L/F62074389E>) |
| 2357:0109 | TP-Link          | TL-WN823N v2/v3 [Realtek RTL8192EU]  | 4     | rtl8xxxu   | [61D82AF735](<System On Chip/Others/Others/Others/6555EFD46738/KALI-2023.1/5.10.107-ANDROID13-4-00004-G6522BF85D262-AB8935228/AARCH64/61D82AF735>) |
| 7392:7811 | Edimax Techno... | EW-7811Un 802.11n Wireless Adapte... | 4     | rtl8192... | [705FA3E0A1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/7D8C9D56FA28/UBUNTU-20.04/5.4.0-1069-RASPI/ARMV7L/705FA3E0A1>) |
| 0bda:8813 | Realtek Semic... | RTL8814AU 802.11a/b/g/n/ac Wirele... | 3     | rtl8814... | [8538B8DCE2](<System On Chip/Nvidia/Tegra/Tegra/9B87837D36FF/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/8538B8DCE2>) |
| 2357:011f | TP-Link          | 802.11ac WLAN Adapter                | 3     |            | [4995C8C687](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Model B Rev 2/2E706A982136/RASPBIAN-11/5.15.84+/ARMV6L/4995C8C687>) |
| 2357:0138 | TP-Link          | 802.11ac NIC                         | 3     | 88x2bu     | [C65FD15277](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/778E7E6702DC/DEBIAN-11/6.2.7-V8+/AARCH64/C65FD15277>) |
| 0a5c:bd1e | Broadcom         | BCM43143 802.11bgn (1x1) Wireless... | 2     | brcmfmac   | [5E07806B7E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi ? Rev 1.0/D8FBFD41D06C/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/5E07806B7E>) |
| 0bda:8172 | Realtek Semic... | RTL8191SU 802.11n WLAN Adapter       | 2     | r8712u     | [953F1D5B3D](<System On Chip/Others/Others/Others/2A42E6ADE2C2/UBUNTU-18.04/4.4.114/AARCH64/953F1D5B3D>) |
| 0bda:8187 | Realtek Semic... | RTL8187 Wireless Adapter             | 2     | rtl8187    | [6F492F55C3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F41C4EB93F2B/UBUNTU-22.04/5.15.0-1015-RASPI/AARCH64/6F492F55C3>) |
| 0cf3:7015 | Qualcomm Athe... | TP-Link TL-WN821N v3 / TL-WN822N ... | 2     | ath9k_htc  | [4020E881A1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/60B300074A8A/MANJARO-ARM/5.10.39-1-MANJARO-ARM/AARCH64/4020E881A1>) |
| 0cf3:9271 | Qualcomm Athe... | AR9271 802.11n                       | 2     | ath9k_htc  | [C2F69BB6EF](<System On Chip/Others/Others/Others/D70379D8CACE/UBUNTU-20.04/3.16.85-65/AARCH64/C2F69BB6EF>) |
| 148f:3070 | Ralink Techno... | RT2870/RT3070 Wireless Adapter       | 2     | rt2800usb  | [FEF5E29664](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/CC27A622D6E5/RASPBIAN-10/5.10.17-V7+/ARMV7L/FEF5E29664>) |
| 148f:761a | Ralink Techno... | MT7610U ("Archer T2U" 2.4G+5G WLA... | 2     | mt76x0u    | [D076BCD8A5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/132B1CAE5360/KALI-2023.1/5.15.44-RE4SON-V7L+/ARMV7L/D076BCD8A5>) |
| 2001:330d | D-Link           | DWA-131 802.11n Wireless N Nano A... | 2     | rtl8192cu  | [0D06F313D8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/03C0497F5B0D/RASPBIAN-10/4.19.118-V7+/ARMV7L/0D06F313D8>) |
| 2001:331e | D-Link           | 802.11ac NIC                         | 2     |            | [8226EFCB30](<System On Chip/Pine Microsystems/Pine64/Pine64 RK3566 Quartz64-A/0B7E187F6FBF/MANJARO-ARM-22.06/5.18.0-RC7-7-MANJARO-ARM-RC/AARCH64/8226EFCB30>) |
| 2357:0115 | TP-Link          | Archer T4U ver.3                     | 2     |            | [E506B52862](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E8540BA672CD/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/E506B52862>) |
| 043e:3001 | LG Electronics   | AN-WF100 802.11abgn Wireless Adap... | 1     |            | [FCEF507E8E](<System On Chip/Rockchip/Others/Others/ECA94755F334/UBUNTU-18.04/4.4.190-1233-ROCKCHIP-AYUFAN-GD3F1BE0ED310/AARCH64/FCEF507E8E>) |
| 04b4:0bdc | Cypress Semic... | Cypress USB 802.11 Wireless Adapter  | 1     | brcmfmac   | [E6398A18AC](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/E6398A18AC>) |
| 04dd:941f | Sharp            | Remote Download Wireless Adapter     | 1     |            | [A054B3B41B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/8EA077DD3644/RASPBIAN-10/5.10.60-V7+/ARMV7L/A054B3B41B>) |
| 050d:825b | Belkin Compon... | F5D8055 N+ Wireless Adapter v2000... | 1     |            | [E187058616](<System On Chip/Radxa/ROCK/ROCK 5B/AFFD9ADD41B4/DEBIAN-11/5.10.110-34-ROCKCHIP-GCA15BBE36E6C/AARCH64/E187058616>) |
| 0846:4210 | NetGear          | WG121(v2) 54 Mbps Wireless [Inter... | 1     | p54usb     | [433D54A30D](<System On Chip/Pine Microsystems/Pine64/Pine64+/CB0CC1CB9398/DEBIAN-11/5.10.0-8-ARM64/AARCH64/433D54A30D>) |
| 0846:9012 | NetGear          | WNDA4100 802.11abgn 3x3:3 [Ralink... | 1     | rt2800usb  | [41FB50247C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/3866EA1B4A8D/UBUNTU-19.10/4.19.105-V8-28/AARCH64/41FB50247C>) |
| 0846:9020 | NetGear          | WNA3100(v1) Wireless-N 300 [Broad... | 1     |            | [5D3CE591BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/EF9198620015/UBUNTU-19.10/5.3.0-1019-RASPI2/AARCH64/5D3CE591BF>) |
| 0846:9052 | NetGear          | A6100 AC600 DB Wireless Adapter [... | 1     | 88XXau     | [8075B94007](<System On Chip/sunxi/Others/Others/108D12CE0E97/UBUNTU-20.04/5.10.60-SUNXI64/AARCH64/8075B94007>) |
| 0846:9053 | NetGear          | A6210                                | 1     | mt76x2u    | [0C5A37EFD2](<System On Chip/Others/Others/Others/83028C31DEB3/XUBUNTU-20.04/5.15.25-ROCKCHIP64/AARCH64/0C5A37EFD2>) |
| 0846:9055 | NetGear          | A6150                                | 1     |            | [50A67AB03C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/3A28E3EB24BC/RASPBIAN-10/5.10.103-V7+/ARMV7L/50A67AB03C>) |
| 0b05:17ba | ASUSTek Computer | N10 Nano 802.11n Network Adapter ... | 1     | rtl8192cu  | [02F65D4D20](<System On Chip/Others/Others/Others/548DF22116EC/PUREOS-10/4.19.72-IMX8-SR/AARCH64/02F65D4D20>) |
| 0bda:0179 | Realtek Semic... | RTL8188ETV Wireless LAN 802.11n N... | 1     |            | [AB1DD22124](<System On Chip/Xunlong/Orange/Orange Pi PC/DA4071C6C1FE/DEBIAN-11/5.15.80-SUNXI/ARMV7L/AB1DD22124>) |
| 0bda:8178 | Realtek Semic... | RTL8192CU 802.11n WLAN Adapter       | 1     |            | [A13D9AFEAD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3A48F5833E5/UBUNTU-22.04/5.15.0-1012-RASPI/AARCH64/A13D9AFEAD>) |
| 0bda:f179 | Realtek Semic... | RTL8188FTV 802.11b/g/n 1T1R 2.4G ... | 1     |            | [682ACA59D0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Model B Rev 2/A286DA5FE74B/RASPBIAN-11/5.15.84+/ARMV6L/682ACA59D0>) |
| 0cf3:1006 | Qualcomm Athe... | TP-Link TL-WN322G v3 / TL-WN422G ... | 1     | ath9k_htc  | [B79CD8C2B0](<System On Chip/HANWEI/FT-208/FT-208-COME-B/7D2A7DE07A62/REDFLAG-11.0/4.19.0-15-PHYTIUM/AARCH64/B79CD8C2B0>) |
| 0e66:0026 | Hawking Techn... | 802.11ac NIC                         | 1     |            | [5ECCD016B4](<System On Chip/Qualcomm Technologies/SDM845/SDM845 v2.1 MTP PVT/8B8A857D4C70/KALI-2022.1/4.9.254-NETHUNTER/AARCH64/5ECCD016B4>) |
| 0e8d:761b | MediaTek         | 802.11ac WLAN                        | 1     |            | [F60622CCA7](<System On Chip/Others/Others/Others/52150C65B995/UBUNTU-22.04/3.16.85-65/AARCH64/F60622CCA7>) |
| 1199:9091 | Sierra Wireless  | EM7421 QualcommÂ Snapdragonâ�... | 1     | qmi_wwa... | [B565B4082E](<System On Chip/Nvidia/Tegra/Tegra/70C6735F4190/UBUNTU-20.04/4.9.253-TEGRA/AARCH64/B565B4082E>) |
| 13b1:0039 | Linksys          | AE1200 802.11bgn Wireless Adapter... | 1     | brcmfmac   | [930CB7D8B3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/CE2212347C1C/KALI-2021.1/4.19.127-RE4SON-V8L+/AARCH64/930CB7D8B3>) |

### Network (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0424:ec00 | Standard Micr... | SMSC9512/9514 Fast Ethernet Adapter  | 137   | smsc95xx   | [50A67AB03C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/3A28E3EB24BC/RASPBIAN-10/5.10.103-V7+/ARMV7L/50A67AB03C>) |
| 0bda:8153 | Realtek Semic... | RTL8153 Gigabit Ethernet Adapter     | 48    | r8152      | [311E49C553](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/B4208B608F83/KALI-2023.1/5.4.83-RE4SON-V8L+/AARCH64/311E49C553>) |
| 0424:7800 | Standard Micr... | Ethernet controller                  | 46    | lan78xx    | [407CA5845D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/99AA913EF833/RASPBIAN-11/6.1.21-V7+/ARMV7L/407CA5845D>) |
| 0bda:8152 | Realtek Semic... | RTL8152 Fast Ethernet Adapter        | 10    | r8152      | [15C9BD2A8A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/A143C05A69D9/RASPBIAN-11/5.15.61+/ARMV6L/15C9BD2A8A>) |
| 0bda:c820 | Realtek Semic... | 802.11ac NIC                         | 9     | btusb      | [EB2E4B24CC](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/4BDA294CC4CF/UBUNTU-MATE-22.04/4.9.337-31/AARCH64/EB2E4B24CC>) |
| 04e8:6863 | Samsung Elect... | Galaxy series, misc. (tethering m... | 7     | rndis_host | [F1537BEEDF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8ED828060896/RASPBIAN-12/6.1.21-V7+/ARMV7L/F1537BEEDF>) |
| 0b95:1790 | ASIX Electronics | AX88179 Gigabit Ethernet             | 6     | ax88179... | [D0C2C987FC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model A Plus Rev 1.0/3E5943BD89A6/DEBIAN-11/5.15.84-V8+/AARCH64/D0C2C987FC>) |
| 0b95:7720 | ASIX Electronics | AX88772                              | 4     | asix       | [931D20E8AE](<System On Chip/pine64,pinebook-pro/Pinebook/Pinebook Pro/AAAD9C14D968/FEDORA-37/6.0.15-300.FC37.AARCH64/AARCH64/931D20E8AE>) |
| 0fe6:9700 | ICS Advent       | DM9601 Fast Ethernet Adapter         | 3     | dm9601,... | [14DDB3F22E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/ECDED66FC70A/UBUNTU-22.04/5.15.0-1011-RASPI/AARCH64/14DDB3F22E>) |
| 2717:ff80 | Xiaomi           | Mi/Redmi series (RNDIS)              | 3     | rndis_host | [8A4AACB421](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E662BC4BE8CA/DEBIAN-11/6.1.21-V8+/AARCH64/8A4AACB421>) |
| 081f:e401 | Manta            | MM812                                | 2     | usbhid     | [2310ED4D7C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/22346AC8F0D2/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/2310ED4D7C>) |
| 0bda:c82c | Realtek Semic... | 802.11ac NIC                         | 2     | btusb      | [475F3981CD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/998CF4046985/RASPBIAN-11/5.10.63-V7L+/ARMV7L/475F3981CD>) |
| 1004:6344 | LG Electronics   | LM-X420xxx/G2 Android Phone (USB ... | 2     | rndis_host | [3516608F3C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Model B Rev 2/E17DCD62E2FD/RASPBIAN-11/5.4.150+/ARMV6L/3516608F3C>) |
| 12d1:108a | Huawei Techno... | STK-LX3                              | 2     | rndis_host | [CE0D8F233C](<System On Chip/Shenzhen Amediatech Technology/X96/X96 Max/42FDDAF80558/XUBUNTU-20.04/5.9.0-ARM-64/AARCH64/CE0D8F233C>) |
| 04e8:6864 | Samsung Elect... | GT-I9070 (network tethering, USB ... | 1     | rndis_host | [C489F2F2A0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3E8575D9121/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/C489F2F2A0>) |
| 0525:a4a2 | Netchip Techn... | Linux-USB Ethernet/RNDIS Gadget      | 1     | cdc_subset | [7BAB2D2C6C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/974290CBD141/UBUNTU-MATE-20.04/5.4.0-1019-RASPI/AARCH64/7BAB2D2C6C>) |
| 056a:0084 | Wacom            | ACK-40401 [Wireless Accessory Kit]   | 1     | usbhid     | [DA1BDD1D3D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5CF2FF51D8A9/UBUNTU-22.04/5.15.0-1024-RASPI/AARCH64/DA1BDD1D3D>) |
| 05ac:1402 | Apple            | Ethernet Adapter [A1277]             | 1     | asix       | [6CB2B7B0C2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/C91123F236C7/RASPBIAN-11/5.15.61+/ARMV6L/6CB2B7B0C2>) |
| 0bb4:0003 | HTC (High Tec... | L-EMENT 350                          | 1     | rndis_host | [C72F8C76F7](<System On Chip/Nvidia/Tegra/Tegra/B2307FE84F73/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/C72F8C76F7>) |
| 0e8d:2005 | MediaTek         | BL8800Pro                            | 1     | rndis_host | [5E682A0733](<System On Chip/Nvidia/Tegra/Tegra/A1DD672248E9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/5E682A0733>) |
| 1410:b00b | Novatel Wireless | MiFi 5510                            | 1     | rndis_host | [6873B9B896](<System On Chip/Hardkernel/Odroid/Odroid XU4/3C686A8058C1/UBUNTU-18.10/4.14.94-155/ARMV7L/6873B9B896>) |
| 17e9:6000 | DisplayLink      | USB-C Hybrid UHD Video Dock          | 1     | cdc_ncm    | [D79A51C5A2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/07AC06C2CBF0/UBUNTU-20.10/5.8.0-1013-RASPI/AARCH64/D79A51C5A2>) |
| 17e9:6006 | DisplayLink      | Dell Universal Dock D6000            | 1     | cdc_ncm... | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 18d1:4eeb | Google           | Pixel 6a                             | 1     | cdc_mbim   | [8DD5FE636D](<System On Chip/Rockchip/Orange/Orange Pi 5/E73465E3004D/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/8DD5FE636D>) |
| 19d2:1015 | ZTE WCDMA Tec... | K3806-Z                              | 1     | cdc_ether  | [0C406A0FB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/657E70087A27/RASPBIAN-9/5.15.21-V7+/ARMV7L/0C406A0FB6>) |
| 2357:0601 | TP-Link          | UE300 10/100/1000 LAN (ethernet m... | 1     | r8152      | [CB2148EE5D](<System On Chip/Xunlong/Orange/Orange Pi PC Plus/0C5AC74F46F0/UBUNTU-22.04/5.15.80-SUNXI/ARMV7L/CB2148EE5D>) |
| 2357:0602 | TP-Link          | USB 10/100 LAN                       | 1     | cdc_ether  | [380EFD9F08](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero Rev 1.3/D191D2F84259/RASPBIAN-11/5.10.103+/ARMV6L/380EFD9F08>) |
| 2a70:f00e | OnePlus Techn... | OnePlus                              | 1     | rndis_host | [1E008A514E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/17EA778A8698/UBUNTU-BUDGIE-19.10/5.3.0-1018-RASPI2/ARMV7L/1E008A514E>) |

### Printer (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0483:5750 | STMicroelectr... | LED badge -- mini LED display -- ... | 1     | usbhid     | [E32526B458](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B0A3FCFAC123/XUBUNTU-20.04/5.4.0-1012-RASPI/AARCH64/E32526B458>) |
| 04a9:176d | Canon            | PIXMA MG2500 Series                  | 1     | usblp      | [DEA44E447F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D076D229E435/UBUNTU-22.04/5.15.0-1014-RASPI/AARCH64/DEA44E447F>) |
| 04a9:1825 | Canon            | TS5100 series                        | 1     | usblp      | [369B72F0FD](<System On Chip/Nvidia/Tegra/Tegra/B7396B276574/LUBUNTU-18.04/4.9.201-TEGRA/AARCH64/369B72F0FD>) |
| 04a9:1912 | Canon            | LiDE 400                             | 1     |            | [5CCBF39183](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/92054DC43525/GENTOO-2.6/5.15.32-V8/AARCH64/5CCBF39183>) |
| 04b8:008f | Seiko Epson      | AL-M310DN                            | 1     | usblp      | [0333751471](<System On Chip/sunxi/Orange/Orange Pi/347D564F5F58/DEBIAN-10/5.8.6-SUNXI/ARMV7L/0333751471>) |
| 04da:0f0b | Panasonic (Ma... | KX-MB1500RU                          | 1     | usblp      | [2504AD4FA5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/57EEA8137619/DEBIAN-11/5.15.61-V8+/AARCH64/2504AD4FA5>) |
| 04e8:3301 | Samsung Elect... | ML-1660 Series                       | 1     | usblp      | [21604049F3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4F4346C7FD17/UBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/21604049F3>) |
| 04e8:331a | Samsung Elect... | CLP-360 Series                       | 1     |            | [C7B32FF620](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4EC359174BBB/KUBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/C7B32FF620>) |
| 04e8:3433 | Samsung Elect... | SCX-4600 Series                      | 1     | usblp      | [9EF99E18E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/BB768FB03CCD/MANJARO-ARM/5.10.52-2-MANJARO-ARM/AARCH64/9EF99E18E2>) |
| 04e8:344f | Samsung Elect... | SCX-3400 Series                      | 1     | usblp      | [2154AE968A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/964AD18F5EB7/UBUNTU-20.10/5.8.0-1011-RASPI/AARCH64/2154AE968A>) |
| 04f9:0273 | Brother Indus... | DCP-7057 scanner/printer             | 1     | usblp      | [79E8256BFB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/E3847B9370EE/RASPBIAN-9.8/4.14.98-V7+/ARMV7L/79E8256BFB>) |
| 0550:00f0 | Fuji Xerox       | DocuPrint P205 b                     | 1     | usblp      | [F9382ECE8E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/0DFA695573B0/RASPBIAN-11/6.1.21-V7+/ARMV7L/F9382ECE8E>) |
| 06bc:034d | Oki Data         | USB Device                           | 1     | usbfs      | [E688396A21](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3EB3867D6F0/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/E688396A21>) |
| 0924:3cec | Xerox            | Phaser 3250                          | 1     | usblp      | [DC7E6F17D4](<System On Chip/Pine Microsystems/Pine64/Pine64+/CB0CC1CB9398/DEBIAN-11/5.10.0-17-ARM64/AARCH64/DC7E6F17D4>) |
| 0a5f:0062 | Zebra            | ZTC ZP 500 (ZPL)                     | 1     | usblp      | [94A5A8790E](<System On Chip/Xunlong/Orange/Orange Pi Zero/464F8A2E0BBA/UBUNTU-18.04/5.4.27-SUNXI/ARMV7L/94A5A8790E>) |
| 3044:50e0 | MIIIW            | MW Keyboard Air Mini                 | 1     | usbhid     | [9973BAF711](<System On Chip/pine64,rockpro64-v2.1/RockPro64/RockPro64 v2.1/E710D01431EC/OPENMANDRIVA-22.90/6.0.10-SERVER-2OMV22090/AARCH64/9973BAF711>) |

### Scanner (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 04a9:1901 | Canon            | CanoScan 8800F                       | 1     |            | [94A6B9B7F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7F34CF394EF5/UBUNTU-20.10/5.8.0-1011-RASPI/AARCH64/94A6B9B7F8>) |
| 04a9:1909 | Canon            | CanoScan LiDE 110                    | 1     |            | [A1E7385FFA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Zero W Rev 1.1/8173C1117C20/RASPBIAN-11/6.1.21+/ARMV6L/A1E7385FFA>) |
| 04a9:2207 | Canon            | CanoScan 1220U                       | 1     |            | [9F9D73DDFB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/0F5A47C5D67C/RASPBIAN-11/5.15.32-V7+/ARMV7L/9F9D73DDFB>) |
| 04b8:011b | Seiko Epson      | GT-9300UF [Perfection 2400 PHOTO]    | 1     |            | [57BDF81032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/F65C49EF596B/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/57BDF81032>) |
| 04b8:011f | Seiko Epson      | GT-8400UF [Perfection 1670/1670 P... | 1     |            | [94A6B9B7F8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/7F34CF394EF5/UBUNTU-20.10/5.8.0-1011-RASPI/AARCH64/94A6B9B7F8>) |
| 04b8:012d | Seiko Epson      | GT-F650 [GT-S600/Perfection V10/V... | 1     |            | [55067D6AFE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/22FA5E73FA5C/UBUNTU-MATE-20.04/4.9.277-119/AARCH64/55067D6AFE>) |

### Serial controller (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a86:7523 | QinHeng Elect... | CH340 serial converter               | 17    | ch341      | [952B46C211](<System On Chip/sunxi/Others/Others/332ED02F0A69/DEBIAN-11/5.15.79-SUNXI64/AARCH64/952B46C211>) |
| 0403:6001 | Future Techno... | FT232 Serial (UART) IC               | 14    | ftdi_sio   | [2891F201F0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/D2FE0F192815/DEBIAN-11/5.15.89-V8+/AARCH64/2891F201F0>) |
| 067b:2303 | Prolific Tech... | PL2303 Serial Port / Mobile Actio... | 13    | pl2303     | [5246120C58](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/E97C46B310B5/UBUNTU-22.10/5.19.0-1009-RASPI/AARCH64/5246120C58>) |
| 10c4:ea60 | Silicon Labs     | CP210x UART Bridge                   | 9     | cp210x     | [F6EAC95147](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2C9DFC4AD7C9/RASPBIAN-11/5.15.84-V7L+/ARMV7L/F6EAC95147>) |
| 0403:6015 | Future Techno... | Bridge(I2C/SPI/UART/FIFO)            | 5     | ftdi_sio   | [C01B933066](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/BB83E3AF30AE/UBUNTU-22.04/5.15.0-1016-RASPI/AARCH64/C01B933066>) |
| 0403:6010 | Future Techno... | FT2232C/D/H Dual UART/FIFO IC        | 4     | ftdi_sio   | [F12132C99F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/22B613E3C0EA/RASPBIAN-10/5.10.103-V7L+/ARMV7L/F12132C99F>) |
| 2c7c:0125 | Quectel Wirel... | EC25 LTE modem                       | 3     | option     | [7B3BD1C86A](<System On Chip/Others/Others/Others/66F1009C1BE4/ARCHARM/6.1.9-1-DANCTNIX/AARCH64/7B3BD1C86A>) |
| 2c7c:0306 | Quectel          | EM06-E                               | 3     | option     | [A1512911DF](<System On Chip/Khadas/VIM/VIM3/8E76D129C324/UBUNTU-20.04/4.9.241/AARCH64/A1512911DF>) |
| 12d1:15c1 | Huawei Techno... | ME906s LTE M.2 Module                | 2     | cdc_ether  | [C17309EC68](<System On Chip/Khadas/VIM/VIM3/6CB0C4BD1229/UBUNTU-20.04/5.17.0/AARCH64/C17309EC68>) |
| 1e0e:9001 | Qualcomm / Op... | SimTech SIM7000                      | 2     | option     | [5A2507857C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/2116D7F4EAF5/DEBIAN-11/5.19.0-RC4-V8/AARCH64/5A2507857C>) |
| 2020:2060 | Qualcomm, Inc... | CDMA Technologies MSM                | 2     | option     | [5D9CED37D2](<System On Chip/Others/Others/Others/03008CADF655/PUREOS-10.0/6.1.0-1-LIBREM5/AARCH64/5D9CED37D2>) |
| 0403:6011 | Future Techno... | FT4232H Quad HS USB-UART/FIFO IC     | 1     | ftdi_sio   | [67AF488496](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 3 Plus Rev 1.0/6B14664990A4/RASPBIAN-11/5.10.63-V7+/ARMV7L/67AF488496>) |
| 0403:6014 | Future Techno... | FT232H Single HS USB-UART/FIFO IC    | 1     |            | [3534D3E5F1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/1AD393D84921/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/3534D3E5F1>) |
| 06cd:0121 | Keyspan          | USA-19hs serial adapter              | 1     | keyspan    | [EE177D0E61](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/F7174F6BBACB/DEBIAN-11/5.15.84-V8+/AARCH64/EE177D0E61>) |
| 10c4:8a2a | Silicon Labs     | HubZ Smart Home Controller           | 1     | cp210x     | [2D767E0513](<System On Chip/Rockchip/Orange/Orange Pi 5/B6466CB0DFF0/DEBIAN-11/5.10.110-ROCKCHIP-RK3588/AARCH64/2D767E0513>) |
| 1934:1202 | Feature Integ... | Fintek U4U F81534 AA66               | 1     | f81534     | [1F1FC02023](<System On Chip/Others/Others/Others/F4E06447D552/UBUNTU-20.04/5.4.0-1003-MTK/AARCH64/1F1FC02023>) |
| 2c7c:0121 | Quectel          | EG21-G                               | 1     | option     | [770C4E4092](<System On Chip/Nvidia/Tegra/Tegra/023A61968717/UBUNTU-UNITY-18.04/4.9.253-TEGRA/AARCH64/770C4E4092>) |
| 2c7c:0800 | Quectel          | RM500Q-GL                            | 1     | option     | [B62C884AEC](<System On Chip/Nvidia/Tegra/Tegra/EA52D6551D30/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/B62C884AEC>) |

### Sound (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0d8c:0014 | C-Media Elect... | Audio Adapter (Unitek Y-247A)        | 13    | snd_usb... | [BCB9E7B9E7](<System On Chip/Olimex/A20/A20-OLinuXino-LIME/C7CC56D1AC8A/DEBIAN-11/5.10.105-OLIMEX/ARMV7L/BCB9E7B9E7>) |
| 1b3f:2008 | Generalplus T... | YC1006                               | 9     | snd_usb... | [420373DCA1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/6BE5E3ABA36B/DEBIAN-11/5.10.43V64/AARCH64/420373DCA1>) |
| 08bb:2902 | Texas Instrum... | PCM2902 Audio Codec                  | 6     | snd_usb... | [C5C7909B2D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/1D45B7BE8EAC/RASPBIAN-11/5.15.61-V7L+/ARMV7L/C5C7909B2D>) |
| 8086:0808 | Intel            | USB PnP Sound Device                 | 5     | snd_usb... | [342CCD2ECF](<System On Chip/Rockchip/Others/Others/46F00341A611/DEBIAN-11/4.4.190-1233-ROCKCHIP-AYUFAN-GD3F1BE0ED310/AARCH64/342CCD2ECF>) |
| 08bb:2704 | Texas Instrum... | PCM2704 16-bit stereo audio DAC      | 4     | snd_usb... | [D62808AD60](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/CA34B1FC13CC/UBUNTU-21.04/5.11.0-1021-RASPI/AARCH64/D62808AD60>) |
| 0bda:481a | Realtek Semic... | USB Audio                            | 4     | snd_usb... | [F9378D9804](<System On Chip/Rockchip/RK3288/RK3288 Asus Tinker Board S/EE8878FF231B/UBUNTU-22.04/5.15.80-ROCKCHIP/ARMV7L/F9378D9804>) |
| 4c4a:4155 | BR25             | USB Composite Device                 | 4     | snd_usb... | [5A0D032110](<System On Chip/Nvidia/Tegra/Tegra/9694CE049FA8/UBUNTU-UNITY-18.04/4.9.253-TEGRA/AARCH64/5A0D032110>) |
| 0c76:161f | JMTek            | USB PnP Audio Device                 | 3     | snd_usb... | [55F6CAEC2D](<System On Chip/Others/Others/Others/3584471355A1/DEBIAN-11/4.9.318-SUN50IW9/AARCH64/55F6CAEC2D>) |
| 046d:0a37 | Logitech         | USB Headset H540                     | 2     | snd_usb... | [EAB2C9895A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/51F4036C55DE/UBUNTU-22.04/5.15.0-1005-RASPI/AARCH64/EAB2C9895A>) |
| 08bb:29b3 | Texas Instrum... | PCM2903B Audio CODEC                 | 2     | snd_usb... | [8C5AE3D1CC](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/7F4C3C256014/UBUNTU-20.10/5.8.0-1007-RASPI/AARCH64/8C5AE3D1CC>) |
| 0d8c:013c | C-Media Elect... | CM108 Audio Controller               | 2     | snd_usb... | [F7AF4B1164](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/21904A6C1DF6/DEBIAN-11/5.15.76-V8+/AARCH64/F7AF4B1164>) |
| 0408:0103 | Quanta           | FV TouchCam N1 (Audio)               | 1     | snd_usb... | [024050E40A](<System On Chip/Xunlong/Orange/Orange Pi Zero/02164B58FD0B/DEBIAN-11/5.15.74-SUNXI/ARMV7L/024050E40A>) |
| 041e:3232 | Creative Tech... | Sound Blaster Premium HD [SBX]       | 1     | snd_usb... | [A5030D74D4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4E719BCF26CE/GENTOO-2.8/5.15.32-V8+/AARCH64/A5030D74D4>) |
| 045e:070f | Microsoft        | LifeChat LX-3000 Headset             | 1     | snd_usb... | [3EE1EB4EE7](<System On Chip/Nvidia/Tegra/Tegra/E77706A741F9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/3EE1EB4EE7>) |
| 046d:0a19 | Logitech         | Z205                                 | 1     | snd_usb... | [7133090590](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9C8F81C157CC/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/7133090590>) |
| 046d:0a23 | Logitech         | Z305                                 | 1     | snd_usb... | [980B14C09A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/FECC17F56857/RASPBIAN-11/5.10.92-V7L+/ARMV7L/980B14C09A>) |
| 046d:0a66 | Logitech         | [G533 Wireless Headset Dongle]       | 1     | snd_usb... | [D9070DA088](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/DFEA52D75DD5/MANJARO-ARM-20.12/5.10.1-1-MANJARO-ARM/AARCH64/D9070DA088>) |
| 046d:0a9c | Logitech         | G432 Gaming Headset                  | 1     | snd_usb... | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 047f:02ee | Plantronics      | BT600                                | 1     | snd_usb... | [07B65B98D0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/5BA420594234/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/07B65B98D0>) |
| 047f:ac01 | Plantronics      | Savi 7xx                             | 1     | snd_usb... | [F9382ECE8E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/0DFA695573B0/RASPBIAN-11/6.1.21-V7+/ARMV7L/F9382ECE8E>) |
| 047f:ac2b | Plantronics      | Savi 8200 Office Series              | 1     | snd_usb... | [6DD2D460AA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/0DFA695573B0/RASPBIAN-11/6.1.21-V7+/ARMV7L/6DD2D460AA>) |
| 047f:c02f | Plantronics      | P610                                 | 1     | snd_usb... | [DAA5086032](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/CD33FD1AB204/RASPBIAN-11/5.10.90-V7+/ARMV7L/DAA5086032>) |
| 054c:09cc | Sony             | DualShock 4 [CUH-ZCT2x]              | 1     | snd_usb... | [A7E12A6A67](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/2BB6856D88E4/UBUNTU-21.10/5.13.0-1013-RASPI/AARCH64/A7E12A6A67>) |
| 0582:0137 | Roland           | DUO-CAPTURE                          | 1     | snd_usb... | [56BBBD14D5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2530055FA946/XUBUNTU-20.04/5.4.0-1015-RASPI/AARCH64/56BBBD14D5>) |
| 05ac:1105 | Apple            | Audio in LED Cinema Display          | 1     | snd_usb... | [6ADCA880A0](<System On Chip/Nvidia/Tegra/Tegra/E316CF040727/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/6ADCA880A0>) |
| 08bb:2912 | Texas Instrum... | PCM2912A Audio Codec                 | 1     | snd_usb... | [AB9D235376](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/1DF34BBBEEB1/RASPBIAN-11/5.15.32-V7L+/ARMV7L/AB9D235376>) |
| 08bb:29c0 | Texas Instrum... | PCM2900C Audio CODEC                 | 1     | snd_usb... | [F8FA8FDC4D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/3C2F4FDA790A/RASPBIAN-11/5.10.63-V7L+/ARMV7L/F8FA8FDC4D>) |
| 08bb:29c2 | Texas Instrum... | PCM2902C Audio CODEC                 | 1     | snd_usb... | [7714BA77EB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/E07159AF60BD/MANJARO-ARM/6.1.0-RC8-1-MANJARO-ARM-RPI/AARCH64/7714BA77EB>) |
| 0b0e:0305 | GN Netcom        | Jabra EVOLVE Link MS                 | 1     | snd_usb... | [E75BF2D175](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B349704E2CFF/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/E75BF2D175>) |
| 0b0e:1022 | GN Netcom        | Jabra PRO 9450, Type 9400BS (DECT... | 1     | snd_usb... | [F8FA8FDC4D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/3C2F4FDA790A/RASPBIAN-11/5.10.63-V7L+/ARMV7L/F8FA8FDC4D>) |
| 0bda:4e28 | Realtek Semic... | USB Audio                            | 1     | snd_usb... | [1A369AD73A](<System On Chip/Nvidia/Tegra/Tegra/ADBC4F66375D/LUBUNTU-18.04/4.9.253-TEGRA/AARCH64/1A369AD73A>) |
| 0d8c:0008 | C-Media Elect... | USB Audio Device                     | 1     | snd_usb... | [764115860E](<System On Chip/Others/Others/Others/3BC233EB6C65/DEBIAN-11/5.15.74-ROCKCHIP/ARMV7L/764115860E>) |
| 0d8c:000c | C-Media Elect... | Audio Adapter                        | 1     | snd_usb... | [7FD7E42E53](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/77C6901CC1FB/UBUNTU-20.10/5.8.0-1008-RASPI/AARCH64/7FD7E42E53>) |
| 0d8c:000e | C-Media Elect... | Audio Adapter (Planet UP-100, Gen... | 1     | snd_usb... | [77691E80A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/8F3A96026FD0/RASPBIAN-10/5.10.63-V7L+/ARMV7L/77691E80A4>) |
| 0d8c:0012 | C-Media Elect... | USB Audio Device                     | 1     | snd_usb... | [4DB8DABA6A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/57BE4BC3605A/UBUNTU-21.10/5.13.0-1022-RASPI/AARCH64/4DB8DABA6A>) |
| 0d8c:0024 | C-Media Elect... | YOWU-SELKIRK-3G                      | 1     | snd_usb... | [77EFB9691B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/015935A967F6/UBUNTU-22.04/5.15.0-1014-RASPI/AARCH64/77EFB9691B>) |
| 0d8c:0102 | C-Media Elect... | CM106 Like Sound Device              | 1     | snd_usb... | [DEA44E447F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D076D229E435/UBUNTU-22.04/5.15.0-1014-RASPI/AARCH64/DEA44E447F>) |
| 0d8c:0171 | C-Media Elect... | JLAB TALK PRO MICROPHONE             | 1     | snd_usb... | [F61F103CF9](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/12C06F858984/UBUNTU-22.04/4.9.312-23/AARCH64/F61F103CF9>) |
| 1043:8773 | iCreate Techn... | ASUS BE/C6 webcam series             | 1     | usbhid     | [E688396A21](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A3EB3867D6F0/UBUNTU-20.10/5.8.0-1015-RASPI/AARCH64/E688396A21>) |
| 1130:1620 | Tenx Technology  | USB AUDIO                            | 1     | snd_usb... | [F4F2A0D4E6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/FB2A61B6A26B/RASPBIAN-11/5.15.76-V7L+/ARMV7L/F4F2A0D4E6>) |
| 12ba:0035 | Licensed by S... | Wireless Stereo Headset              | 1     | snd_usb... | [9BA35E9B27](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A954C80F17DD/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/9BA35E9B27>) |
| 1395:0033 | DSEA A/S         | SC60 for Lync                        | 1     | snd_usb... | [4D0329526A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/129C61A93C89/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/4D0329526A>) |
| 1395:005d | DSEA A/S         | Sennheiser Main Audio                | 1     | snd_usb... | [1E21B25BBA](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/786472A5BF4A/MANJARO-ARM-22.01/5.10.88-1-MANJARO-ARM-RPI/AARCH64/1E21B25BBA>) |
| 1532:0529 | Razer USA        | Razer USB Sound Card                 | 1     | snd_usb... | [9D1652F80E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/22A4F8332474/UBUNTU-22.04/5.15.0-1013-RASPI/AARCH64/9D1652F80E>) |
| 1852:db96 | GYROCOM C&C      | NuForce ÂµDAC 2                    | 1     | snd_usb... | [A69564B477](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/573F7C7803A6/RASPBIAN-10/5.15.45-V8+/AARCH64/A69564B477>) |
| 1908:332a | GEMBIRD          | Multimedia audio controller          | 1     | snd_usb... | [3AF57A322F](<System On Chip/Xunlong/Orange/Orange Pi Zero/2787DBD3957A/DEBIAN-11/5.15.80-SUNXI/ARMV7L/3AF57A322F>) |
| 1915:1012 | Nordic Semico... | Smart Control                        | 1     | snd_usb... | [D96D0BEBA4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EBA7FC9211A8/UBUNTU-20.10/5.8.0-1016-RASPI/AARCH64/D96D0BEBA4>) |
| 1915:7856 | Nordic Semico... | Uniplay U6                           | 1     | snd_usb... | [2F1CA6D742](<System On Chip/Nvidia/Tegra/Tegra/9845C4314AEE/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/2F1CA6D742>) |
| 194f:0303 | PreSonus Audi... | AudioBox USB 96                      | 1     | snd_usb... | [EAB2C9895A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/51F4036C55DE/UBUNTU-22.04/5.15.0-1005-RASPI/AARCH64/EAB2C9895A>) |
| 1997:7b03 | Shenzhen Riit... | Multimedia Air Mouse Keyboard        | 1     | snd_usb... | [79DB7CDBA8](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/2FCF9738EDCB/UBUNTU-20.10/5.8.0-1008-RASPI/AARCH64/79DB7CDBA8>) |

### Touchpad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 06cb:0009 | Synaptics        | Composite TouchPad and TrackPoint    | 1     | synapti... | [591BEDF88F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/41DD4743631C/UBUNTU-21.04/5.11.0-1027-RASPI/AARCH64/591BEDF88F>) |

### Touchscreen (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0eef:0001 | D-WAV Scientific | Titan6001 Surface Acoustic Wave T... | 4     | usbhid     | [C008FC6206](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Rev 1.2/A801B8CEEC01/DEBIAN-11/5.15.61-V8+/AARCH64/C008FC6206>) |

### Tv card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0ac8:301b | Z-Star Microe... | ZC0301 Webcam                        | 2     | gspca_z... | [76DC55B00E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EB72DE30F09D/UBUNTU-21.04/5.11.0-1012-RASPI/AARCH64/76DC55B00E>) |
| 041e:4068 | Creative Tech... | Live! Cam Notebook [VF0470]          | 1     | gspca_o... | [3FDF6B4559](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B308F978ACC3/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/3FDF6B4559>) |
| 045e:00f4 | Microsoft        | LifeCam VX-6000 (SN9C20x + OV9650)   | 1     | gspca_s... | [94ABE2C8AF](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/C601D229FFDD/UBUNTU-MATE-20.04/4.9.277-122/AARCH64/94ABE2C8AF>) |
| 045e:00f5 | Microsoft        | LifeCam VX-3000                      | 1     | gspca_s... | [40ADEBBAD2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/4194DDE215B4/UBUNTU-20.10/5.8.0-1021-RASPI/AARCH64/40ADEBBAD2>) |
| 046d:0892 | Logitech         | C920 HD Pro Webcam                   | 1     | gspca_v... | [8A69B09CAB](<System On Chip/Nvidia/Tegra/Tegra/B0435DC20AF7/UBUNTU-UNITY-18.04/4.9.140-TEGRA/AARCH64/8A69B09CAB>) |
| 046d:08ad | Logitech         | QuickCam Communicate STX             | 1     | snd_usb... | [9B39BC4979](<System On Chip/Rockchip/Orange/Orange Pi 5/5E1E10BA1F21/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/9B39BC4979>) |
| 046d:0920 | Logitech         | QuickCam Express                     | 1     | gspca_t... | [40748C60B0](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/92054DC43525/GENTOO-2.8/5.10.11-V8/AARCH64/40748C60B0>) |
| 0553:0002 | STMicroelectr... | CPiA Webcam                          | 1     | gspca_c... | [D5FFD1FF38](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/367DAA77496B/RASPBIAN-10/4.19.75-V7+/ARMV7L/D5FFD1FF38>) |
| 093a:2600 | Pixart Imaging   | Typhoon Easycam USB 330K (newer)/... | 1     | gspca_p... | [F6EAC95147](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/2C9DFC4AD7C9/RASPBIAN-11/5.15.84-V7L+/ARMV7L/F6EAC95147>) |
| 0ac8:307b | Z-Star Microe... | USB 1.1 Webcam                       | 1     | gspca_z... | [93004B8E8F](<System On Chip/Nvidia/Tegra/Tegra/4BE71AD4E685/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/93004B8E8F>) |
| 1415:2000 | Nam Tai E&E P... | Sony Playstation Eye                 | 1     | snd_usb... | [14BC5C234D](<System On Chip/Khadas/VIM/VIM3/AD2E7941E7E9/XUBUNTU-20.04/4.9.241/AARCH64/14BC5C234D>) |
| eb1a:2870 | eMPIA Technology | Pinnacle PCTV Stick                  | 1     | em28xx     | [BAC5E4B9C2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B0A3FCFAC123/UBUNTU-21.10/5.13.0-1022-RASPI/AARCH64/BAC5E4B9C2>) |

### Ups (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 051d:0002 | American Powe... | Uninterruptible Power Supply         | 1     | usbfs      | [925C92EA4B](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/12F79386C154/RASPBIAN-11/5.15.84-V7L+/ARMV7L/925C92EA4B>) |
| 0764:0501 | Cyber Power S... | CP1500 AVR UPS                       | 1     | usbhid     | [B417AFA8D1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/57A822BF053D/DEBIAN-10/5.4.79-V8+/AARCH64/B417AFA8D1>) |
| 0d9f:0004 | Powercom         | HID UPS Battery                      | 1     | usbfs      | [77BB019FE0](<System On Chip/Bananapi/BPI-M/BPI-M5/91E0E094EEA8/DEBIAN-10/4.9.236-BPI-M5-KERNEL/AARCH64/77BB019FE0>) |

### Wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 05c6:90b6 | Qualcomm         | Android                              | 1     | rndis_host | [015AA87271](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Compute Module 4 Rev 1.0/FEEDE16402FB/DEBIAN-11/5.15.32-V8+/AARCH64/015AA87271>) |
| 0e79:2005 | Archos           | Archos                               | 1     | rndis_host | [C081CBEF0C](<System On Chip/TI/OMAP3/OMAP3 BeagleBoard xM/1EDBF8C9261F/DEBIAN-8/4.8.7-ARMV7-X4/ARMV7L/C081CBEF0C>) |
| 17ef:7a1c | Lenovo           | Lenovo Composite ADB Interface       | 1     | rndis_host | [30C09E0585](<System On Chip/Nvidia/Tegra/Tegra/083D6ABF3079/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/30C09E0585>) |
| 2717:ff88 | Xiaomi           | Mi/Redmi series (RNDIS + ADB)        | 1     | rndis_host | [59A015C31D](<System On Chip/Rockchip/Orange/Orange Pi 5/B0174FC988EC/XUBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/59A015C31D>) |
| 2d95:600b | Android          | Android                              | 1     | rndis_host | [B62C884AEC](<System On Chip/Nvidia/Tegra/Tegra/EA52D6551D30/UBUNTU-UNITY-18.04/4.9.201-TEGRA/AARCH64/B62C884AEC>) |

### Others (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1d5c:7102 | Fresco Logic     | Generic Billboard Device             | 3     |            | [DE369A751A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/29BF1DBCCFC4/DEBIAN-11/6.1.19-V8+/AARCH64/DE369A751A>) |
| 3452:6600 | ESWIN            | 6600U                                | 3     | wlan_ec... | [018DAF402B](<System On Chip/Others/Others/Others/678CF1D282D3/DEBIAN-12/5.15.0-STARFIVE/RISCV64/018DAF402B>) |
| 0424:2740 | Microchip Tec... | Hub Controller                       | 2     |            | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 2109:0102 | VIA Labs         | USB 2.0 BILLBOARD                    | 2     |            | [D8411DFAB2](<System On Chip/Qualcomm Technologies/SM8150/SM8150 V2 PM8150 CEPHEUS/93F44C6259DA/KALI-2021.2/4.14.212-QUANTIC_MIUI//94C9FEE9AE/AARCH64/D8411DFAB2>) |
| 2294:425a | Theobroma Sys... | Mule USB/CAN Adapter                 | 2     |            | [16D3C3D359](<System On Chip/theobroma-systems/puma_rk/puma_rk3399/C7048E225E39/FEDORA-34/5.14.9-200.FC34.AARCH64/AARCH64/16D3C3D359>) |
| 03f0:0a6b | Hewlett-Packard  | USB-C/A Universal Dock G2            | 1     | usbhid     | [E75BF2D175](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B349704E2CFF/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/E75BF2D175>) |
| 0403:8050 | Future Techno... | Belimo ZTH                           | 1     |            | [2911B2782C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B+/BD2292AE8867/NIXOS-22.05/5.15.47/AARCH64/2911B2782C>) |
| 0424:9730 | Microchip Tec... | LAN9730 USB 2.0 to Ethernet 10/10... | 1     | smsc95xx   | [04B62E9EB2](<System On Chip/Hardkernel/ODROID-U3/ODROID-U3 board based on Exynos4412/EF69CCC814EB/DEBIAN-11/5.19.1-STB-EXY+/ARMV7L/04B62E9EB2>) |
| 0438:b003 | AMD              | ATI Unified AVStream                 | 1     |            | [DEA44E447F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D076D229E435/UBUNTU-22.04/5.15.0-1014-RASPI/AARCH64/DEA44E447F>) |
| 0451:16ae | Texas Instrum... | CC2531 Dongle                        | 1     |            | [1971415007](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/870E0570B155/UBUNTU-21.04/5.11.0-1016-RASPI/AARCH64/1971415007>) |
| 04b4:640c | Cypress Semic... | BCM2045A0                            | 1     |            | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 04e8:6001 | Samsung Elect... | sd-wire                              | 1     |            | [04EDD2ED9A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/F65B7C80FDEE/DEBIAN-TESTING/5.8.0-2-ARM64/AARCH64/04EDD2ED9A>) |
| 057e:200a | Nintendo         |                                      | 1     |            | [6A3439A8E1](<System On Chip/Others/Others/Others/FDF2652907A7/UBUNTU-18.04/4.9.140-L4T/AARCH64/6A3439A8E1>) |
| 06b8:1042 | Pixela           | XIT-STK100                           | 1     |            | [9DE5875AF1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.2/D5E4B73E24AB/RASPBIAN-10/5.10.103-V7L+/ARMV7L/9DE5875AF1>) |
| 07ca:c039 | AVerMedia Tec... | C039 USB Pure Capture                | 1     | cx231xx    | [901194D1E1](<System On Chip/FriendlyElec/NanoPC-T/NanoPC-T4/A458CAB83B53/DEBIAN-11/5.10.0-21-ARM64/AARCH64/901194D1E1>) |
| 0955:cf07 | Nvidia           | SHIELD Tablet                        | 1     | usbfs      | [E56E9C8A57](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/8D2589DBE95B/UBUNTU-19.10/5.3.0-1023-RASPI2/AARCH64/E56E9C8A57>) |
| 0bda:5418 | Realtek Semic... | BillBoard Device                     | 1     |            | [A617383C6F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/488EC17BC74D/UBUNTU-20.10/5.8.0-1006-RASPI/AARCH64/A617383C6F>) |
| 0c72:000c | PEAK System      | PCAN-USB                             | 1     | peak_usb   | [BE369FE18A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/50224502A0D4/DEBIAN-11/5.15.84-V8+/AARCH64/BE369FE18A>) |
| 0cd5:0007 | LabJack          | T7                                   | 1     | usbfs      | [68AC87675A](<System On Chip/Nvidia/Tegra/Tegra/DBB28DEA9F16/UBUNTU-18.04/4.9.253-TEGRA/AARCH64/68AC87675A>) |
| 0e41:4750 | Line6            | GuitarPort                           | 1     | snd_usb... | [46CF1EB748](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/CF04D8227DE3/DEBIAN-11/5.10.92-V8+/AARCH64/46CF1EB748>) |
| 0e8d:201c | MediaTek         | Infinix X682B                        | 1     | usbfs      | [81F59BA6F5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/E07159AF60BD/MANJARO-ARM/6.1.0-RC1-2-MANJARO-ARM-RPI/AARCH64/81F59BA6F5>) |
| 17e9:601e | DisplayLink      | HP USB-C Universal Docking Station   | 1     | snd_usb... | [E75BF2D175](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/B349704E2CFF/UBUNTU-20.10/5.8.0-1010-RASPI/AARCH64/E75BF2D175>) |
| 1b71:3002 | Fushicai         | USBTV007 Video Grabber [EasyCAP]     | 1     | usbtv      | [632A8A0AD8](<System On Chip/sunxi/Allwinner/Allwinner sun7i Family/0AF4EB9982A2/XUBUNTU-22.04/5.15.48-SUNXI/ARMV7L/632A8A0AD8>) |
| 1d50:6089 | OpenMoko         | Great Scott Gadgets HackRF One SDR   | 1     | hackrf     | [604DD9D393](<System On Chip/sunxi/Others/Others/AF0F9587AEF6/DEBIAN-11/5.4.18-SUNXI64/AARCH64/604DD9D393>) |
| 1df7:2500 | SDRplay          | RSP1                                 | 1     |            | [29E02A10BF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.5/B04A08455F7D/RASPBIAN-11/5.15.76-V7L+/ARMV7L/29E02A10BF>) |
| 1df7:3000 | SDRplay          | RSP1a                                | 1     |            | [C38D256CAB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E4FE3E3CD572/UBUNTU-21.10/5.13.0-1011-RASPI/AARCH64/C38D256CAB>) |
| 1f29:0000 | Analogix         | USB Type-C Digital AV Adapter        | 1     |            | [59A015C31D](<System On Chip/Rockchip/Orange/Orange Pi 5/B0174FC988EC/XUBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/59A015C31D>) |
| 1f4d:a681 | G-Tek Electro... | ATSC USB Stick                       | 1     |            | [A4FC4AD9E3](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D076D229E435/UBUNTU-22.04/5.15.0-1014-RASPI/AARCH64/A4FC4AD9E3>) |
| 2040:0264 | Hauppauge        | soloHD                               | 1     | em28xx     | [989B41F386](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/EBA7FC9211A8/UBUNTU-22.04/5.15.0-1008-RASPI/AARCH64/989B41F386>) |
| 2040:8265 | Hauppauge        | dualHD                               | 1     |            | [C19DB93D49](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.1/39A749B3E489/RASPBIAN-11/5.10.92-V7L+/ARMV7L/C19DB93D49>) |
| 2188:0011 | No brand         | TS3 Plus                             | 1     |            | [123113DDFD](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/A954C80F17DD/UBUNTU-21.04/5.11.0-1017-RASPI/AARCH64/123113DDFD>) |
| 291a:8346 | AnkerInnovati... | Anker USB-C Hub Device               | 1     |            | [95C95C980D](<System On Chip/Others/Others/Others/A877A66C5D0B/DEBIAN-11/5.19.1-STB-CBQ+/AARCH64/95C95C980D>) |

