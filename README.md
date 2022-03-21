Most popular USB devices
========================

This is a project to identify most popular USB devices in modern computers and
share detailed lsusb reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 239679.

Contents
--------

1. [ About ](#about)
2. [ USB Devices ](#usb-devices)
   * [ Audio ](#audio-usb)
   * [ Bluetooth ](#bluetooth-usb)
   * [ Camera ](#camera-usb)
   * [ Card reader ](#card-reader-usb)
   * [ Cdrom ](#cdrom-usb)
   * [ Chipcard ](#chipcard-usb)
   * [ Converter ](#converter-usb)
   * [ Disk ](#disk-usb)
   * [ Dvb card ](#dvb-card-usb)
   * [ Fingerprint reader ](#fingerprint-reader-usb)
   * [ Floppy ](#floppy-usb)
   * [ Gamepad ](#gamepad-usb)
   * [ Hardware key ](#hardware-key-usb)
   * [ Hasp ](#hasp-usb)
   * [ Hub ](#hub-usb)
   * [ Human interface ](#human-interface-usb)
   * [ Infrared ](#infrared-usb)
   * [ Input/keyboard ](#inputkeyboard-usb)
   * [ Input/mouse ](#inputmouse-usb)
   * [ Isdn adapter ](#isdn-adapter-usb)
   * [ Joystick ](#joystick-usb)
   * [ Mfp ](#mfp-usb)
   * [ Miscellaneous ](#miscellaneous-usb)
   * [ Modem ](#modem-usb)
   * [ Net/ethernet ](#netethernet-usb)
   * [ Net/wimax ](#netwimax-usb)
   * [ Net/wireless ](#netwireless-usb)
   * [ Network ](#network-usb)
   * [ Phone ](#phone-usb)
   * [ Printer ](#printer-usb)
   * [ Scanner ](#scanner-usb)
   * [ Serial controller ](#serial-controller-usb)
   * [ Sound ](#sound-usb)
   * [ Touchpad ](#touchpad-usb)
   * [ Touchscreen ](#touchscreen-usb)
   * [ Tv card ](#tv-card-usb)
   * [ Ups ](#ups-usb)
   * [ Video ](#video-usb)
   * [ Webcam ](#webcam-usb)
   * [ Wireless ](#wireless-usb)
   * [ Xbox ](#xbox-usb)
   * [ Others ](#others-usb)

About
-----

The structure of the repository is the following:

    {COMPUTER TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}/{OS}/{KERNEL}/{ARCH}/{PROBE ID}

    ( e.g. Notebook/Dell/XPS/XPS 15 9550/323DFD9291C0/UBUNTU-18.04/4.15.0-24-GENERIC/X86_64/AC68474628 )

You can find appropriate lsusb report in this repository by a probe ID as follows:

    find . -name {PROBE ID}

USB Devices
-----------

Top 50 most popular devices in each category.

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Audio (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1235:8202 | Focusrite-Nov... | Focusrite Scarlett 2i2 2nd Gen       | 47    | snd_usb... | [56C75F9229](<Tablet/Microsoft/Surface/Surface Pro/30C30BAC02B4/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/56C75F9229>) |
| 1235:8205 | Focusrite-Nov... | Scarlett Solo USB                    | 45    | snd_usb... | [311C6DA8E0](<Notebook/Hewlett-Packard/ProBook/ProBook 455 G7/656F39058145/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/311C6DA8E0>) |
| 1235:8211 | Focusrite-Nov... | Scarlett Solo (3rd Gen.)             | 41    | snd_usb... | [39D215E49D](<Mini Pc/AZW/GTR/GTR/0370FAAF0441/FEDORA-35/5.16.10-200.FC35.X86_64/X86_64/39D215E49D>) |
| 046d:0a87 | Logitech         | G935 Gaming Headset                  | 37    | snd_usb... | [97BB5E5628](<Desktop/Gigabyte Technology/X58/X58A-UD3R/3B4E0E4FDB3A/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/97BB5E5628>) |
| 0955:7002 | Nvidia           | stereo controller                    | 37    |            | [E1D4821EC2](<Notebook/Dell/System/System XPS L702X/335C8CE6230A/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E1D4821EC2>) |
| 041e:322c | Creative Tech... | SB Omni Surround 5.1                 | 34    | snd_usb... | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 1397:0507 | BEHRINGER Int... | UMC202HD 192k                        | 34    | snd_usb... | [AAFF820712](<Desktop/MSI/MS-7/MS-7C91/F1C5798A309A/ARCH-ROLLING/5.16.7-ARCH1-1/X86_64/AAFF820712>) |
| 152a:8750 | Thesycon Syst... | E30                                  | 33    | snd_usb... | [6F9489B2E6](<Desktop/EVGA/X299/X299 FTW K/E0352CDBA41D/NIXOS-21.11/5.10.102/X86_64/6F9489B2E6>) |
| 1235:8016 | Focusrite-Nov... | Focusrite Scarlett 2i2               | 31    | snd_usb... | [F6F59E8802](<Desktop/ASUSTek Computer/TUF/TUF Z390-PRO GAMING/6A9975B9246F/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/F6F59E8802>) |
| 1235:8210 | Focusrite-Nov... | Scarlett 2i2 USB                     | 30    | snd_usb... | [73526F92AC](<Notebook/Dell/XPS/XPS 15 7590/77162A4B48CB/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/73526F92AC>) |
| 1397:0509 | BEHRINGER Int... | UMC404HD 192k                        | 30    | snd_usb... | [66F88A032F](<Desktop/Dell/Precision/Precision T5600/5F2EC5F04A2D/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/66F88A032F>) |
| 1397:0508 | BEHRINGER Int... | UMC204HD 192k                        | 24    | snd_usb... | [C419233C03](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DF002BUK/F37DCC884D42/DEBIAN-11/5.10.0-9-AMD64/X86_64/C419233C03>) |
| 2972:0047 | FiiO Electron... | K3                                   | 24    | snd_usb... | [EBF8ED89A1](<Desktop/ASRock/X570M/X570M Pro4/C59C39CF1D6D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EBF8ED89A1>) |
| 0499:170f | Yamaha           | Steinberg UR22mkII                   | 23    | snd_usb... | [E6564282E5](<Desktop/Dell/OptiPlex/OptiPlex 9020/B00EA09617F4/MANJARO-21.2.3/5.15.21-1-MANJARO/X86_64/E6564282E5>) |
| 0d8c:0066 | C-Media Elect... | Schiit Modi 3                        | 23    | snd_usb... | [4B812791AD](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/2F35197461AB/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/4B812791AD>) |
| 26ce:0a01 |                  | USB Audio                            | 22    | snd_usb... | [B24408A4D1](<Desktop/ASRock/TRX40/TRX40 Creator/FBE6BE644825/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/B24408A4D1>) |
| 0b05:189d | ASUSTek Computer | Xonar SoundCard                      | 21    | snd_usb... | [9648D5B905](<Desktop/MSI/MS-7/MS-7B51/6B86FC5E500F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/9648D5B905>) |
| 1043:857c | iCreate Techn... | Xonar U7                             | 21    | usbhid     | [FFACA9CABF](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE/6057B3C73FA1/ZORIN-16/5.13.0-25-GENERIC/X86_64/FFACA9CABF>) |
| 1235:8200 | Focusrite-Nov... | Scarlett 2i4 USB                     | 21    | snd_usb... | [F48FE5A028](<Desktop/Gigabyte Technology/AB350M-Gaming/AB350M-Gaming 3/E7D64C95AD9F/MANJARO/5.15.16-1-MANJARO/X86_64/F48FE5A028>) |
| 19f7:0015 | RODE Microphones | RODE NT-USB Mini                     | 21    | snd_usb... | [ECCFE5B35C](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20YDS00G00/AB2C6D7EBED9/DEBIAN-11/5.16.0-3-AMD64/X86_64/ECCFE5B35C>) |
| 0414:a000 | Giga-Byte Tec... | USB Audio                            | 20    | snd_usb... | [5CA44FE54C](<Desktop/Gigabyte Technology/TRX40/TRX40 AORUS MASTER/065050471491/ENDEAVOUROS-ROLLING/5.15.13-ZEN1-1-ZEN/X86_64/5CA44FE54C>) |
| 0414:a001 | Giga-Byte Tec... | USB Audio                            | 20    | snd_usb... | [5CA44FE54C](<Desktop/Gigabyte Technology/TRX40/TRX40 AORUS MASTER/065050471491/ENDEAVOUROS-ROLLING/5.15.13-ZEN1-1-ZEN/X86_64/5CA44FE54C>) |
| 0b05:180d | ASUSTek Computer | STRIX SOUND CARD                     | 20    | usbhid     | [759958A4B0](<Desktop/Gigabyte Technology/B550/B550 AORUS MASTER/2A7DA6CE54F8/ARCO-ROLLING/5.16.11-XANMOD1-1/X86_64/759958A4B0>) |
| 0414:a002 | Giga-Byte Tec... | USB Audio                            | 18    | snd_usb... | [67406A5FB6](<Desktop/Gigabyte Technology/TRX40/TRX40 AORUS PRO WIFI/58A31B2CA364/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/67406A5FB6>) |
| b58e:0005 | Blue Microphones | Yeti Nano                            | 18    | snd_usb... | [419BEA0E4E](<Desktop/Acer/Aspire/Aspire X3400G/F1CE4E9AFBD2/UBUNTU-18.04/4.15.0-156-GENERIC/I686/419BEA0E4E>) |
| 20b1:3008 | XMOS             | iFi (by AMR) HD USB Audio            | 17    | snd_usb... | [1090FC46ED](<Desktop/ASRock/A320/A320M-HDV/331E2ECEE370/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1090FC46ED>) |
| 046d:0a0b | Logitech         | ClearChat Pro USB                    | 16    | snd_usb... | [BD96B37321](<Desktop/MSI/MS-7/MS-7A75/D5FAFE44E303/CENTOS-8/4.18.0-348.2.1.EL8_5.X86_64/X86_64/BD96B37321>) |
| 0bda:4c07 | Realtek Semic... | USB Condenser Microphone             | 16    | snd_usb... | [7AF526BBB7](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/30FE7B5F0DE7/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/7AF526BBB7>) |
| 0d8c:0004 | C-Media Elect... | CM6631A Audio Processor              | 16    | snd_usb... | [0B0C1ACA1B](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401IV_GA401IV/459D23F4E8DD/SLACKWARE-15.0/5.16.9-JOE1/X86_64/0B0C1ACA1B>) |
| 0b05:1915 | ASUSTek Computer | USB Audio                            | 15    | usbhid     | [3AB95EAABB](<Desktop/ASUSTek Computer/ROG/ROG ZENITH II EXTREME ALPHA/DA6566FB83C7/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/3AB95EAABB>) |
| 0b05:1916 | ASUSTek Computer | USB Audio                            | 15    | snd_usb... | [3AB95EAABB](<Desktop/ASUSTek Computer/ROG/ROG ZENITH II EXTREME ALPHA/DA6566FB83C7/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/3AB95EAABB>) |
| 17cc:1001 | Native Instru... | Komplete Audio 6                     | 15    | snd_usb... | [299A727E8A](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/7BBCC0E7BA7B/ARTIX/5.16.10-ARTIX1-1/X86_64/299A727E8A>) |
| 0499:170d | Yamaha           | AG06/AG03                            | 14    | snd_usb... | [D2A90294B3](<Desktop/ASUSTek Computer/TUF/TUF B450-PLUS GAMING/1E5FA9FB4A36/POP!_OS-21.10/5.16.9-TKG-PDS/X86_64/D2A90294B3>) |
| 0499:1703 | Yamaha           | MG-XU                                | 13    | snd_usb... | [54C4F70C98](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/B24147C07140/XUBUNTU-20.04/5.13.0-30-GENERIC/X86_64/54C4F70C98>) |
| 0499:170a | Yamaha           | Steinberg UR12                       | 13    | snd_usb... | [9AB82BA1E9](<Notebook/Hewlett-Packard/EliteBook/EliteBook Folio 9470m/69FEFD546ADD/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/9AB82BA1E9>) |
| 0b05:1996 | ASUSTek Computer | USB Audio                            | 13    | snd_usb... | [308DF080E6](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/0E83D6815B1B/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/308DF080E6>) |
| 1235:800a | Focusrite-Nov... | Scarlett 2i4                         | 13    | snd_usb... | [61E605E1D8](<Desktop/ASUSTek Computer/P9X79/P9X79 LE/038890B3C3CE/UBUNTU-18.04/5.15.10-GENTOO-DIST/X86_64/61E605E1D8>) |
| 0b05:183c | ASUSTek Computer | Xonar U7 MKII                        | 12    | snd_usb... | [3D54B5DB38](<Desktop/Apple/MacPro2/MacPro2,1/87C3C7A6020B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3D54B5DB38>) |
| 20b1:000a | XMOS             | xCORE USB Audio 2.0                  | 12    | snd_usb... | [8D3CFB2F81](<Desktop/Dell/OptiPlex/OptiPlex 7050/54AABFD59D5C/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/8D3CFB2F81>) |
| 0b05:180f | ASUSTek Computer | XONAR SOUND CARD                     | 11    | snd_usb... | [87A19CA6BD](<Desktop/PC Specialist/Intel/Intel Z370/C9F0E26F12D0/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/87A19CA6BD>) |
| 0b05:1918 | ASUSTek Computer | USB Audio                            | 11    | snd_usb... | [CC04FE990C](<Desktop/ASUSTek Computer/PRIME/PRIME TRX40-PRO S/7E3F7BC6DB03/DEBIAN-11/5.10.0-10-AMD64/X86_64/CC04FE990C>) |
| 20b1:0008 | XMOS             | Mayfield Audio                       | 11    | snd_usb... | [3F6DFEBDF6](<Desktop/AAEON/MF/MF-001/BC79BDE06228/LUBUNTU-20.04/5.3.18-DLI/X86_64/3F6DFEBDF6>) |
| 20b1:3023 | XMOS             | X1S USB DAC                          | 11    | snd_usb... | [3188AA78C9](<Desktop/ASUSTek Computer/Z10PE-D16/Z10PE-D16 WS/CAA4B6326775/ARCH-ROLLING/5.10.80-1-LTS/X86_64/3188AA78C9>) |
| 1395:009a | Sennheiser Co... | GSP 370                              | 10    | cdc_acm    | [D47819516A](<Desktop/ASRock/X99/X99 Extreme4/1E598F64C524/ARCH-ROLLING/5.16.10-ARCH1-1/X86_64/D47819516A>) |
| 041e:3f19 | Creative Tech... | E-MU 0204 / USB                      | 9     | snd_usb... | [DC150F9FBA](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Nano Gen 1 20UN005PRT/C740D7AE4BE9/FEDORA-35/5.14.17-301.FC35.X86_64/X86_64/DC150F9FBA>) |
| 0582:012f | Roland           | QUAD-CAPTURE                         | 8     | snd_usb... | [93A093110A](<Desktop/ASUSTek Computer/All/All Series/180F9B80D6FF/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/93A093110A>) |
| 0b05:19ac | ASUSTek Computer | USB Audio                            | 8     | snd_usb... | [DEF3788FF1](<Desktop/ASUSTek Computer/ROG/ROG Maximus XIII HERO/F54690D6421C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/DEF3788FF1>) |
| 1235:8006 | Focusrite-Nov... | Focusrite Scarlett 2i2               | 8     | snd_usb... | [F7E362D977](<Desktop/Dell/OptiPlex/OptiPlex 390/B82902E9B1A2/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/F7E362D977>) |
| 1235:801c | Focusrite-Nov... | Scarlett Solo USB                    | 8     | snd_usb... | [B92F4485E6](<Desktop/Huanan/X99/X99-TF/4876D7DDFFB2/KUBUNTU-20.04/5.4.0-72-GENERIC/X86_64/B92F4485E6>) |
| 17aa:1046 |                  | Realtek USB Audio Rear               | 8     | snd_usb... | [FC313A8F4A](<Desktop/Lenovo/ThinkStation/ThinkStation P620 30E0CTO1WW/7F255D9F3929/DEBIAN-11/5.15.0-2-AMD64/X86_64/FC313A8F4A>) |

### Bluetooth (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0a12:0001 | Cambridge Sil... | Bluetooth Dongle (HCI mode)          | 4743  | btusb      | [CB8AFCB315](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/10C8FEF878C9/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CB8AFCB315>) |
| 8087:0a2a | Intel            | Bluetooth wireless interface         | 4658  | btusb      | [3ECBD85311](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G2/8D1B4AD5F2F1/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/3ECBD85311>) |
| 8087:0a2b | Intel            | Bluetooth wireless interface         | 4465  | btusb      | [41C5B09AA4](<Convertible/Dell/Latitude/Latitude 7389/65E58898D2C3/WINDOWSFX-11/5.13.0-27-GENERIC/X86_64/41C5B09AA4>) |
| 8087:0aaa | Intel            | Bluetooth 9460/9560 Jefferson Pea... | 4372  | btusb      | [92A248BAC7](<Desktop/ASUSTek Computer/TUF/TUF Z390-PLUS GAMING/A0A3C7594D1A/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/92A248BAC7>) |
| 8087:0029 | Intel            | AX200 Bluetooth                      | 4234  | btusb      | [7ADB5A975B](<Notebook/Dell/Inspiron/Inspiron 5415/A6EF8FB28A53/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7ADB5A975B>) |
| 8087:0026 | Intel            | AX201 Bluetooth                      | 3605  | btusb      | [2372B12D5C](<Notebook/Dell/Latitude/Latitude 5511/2B9275757CE0/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/2372B12D5C>) |
| 8087:07dc | Intel            | Bluetooth wireless interface         | 3181  | btusb      | [4F1CAE64B4](<Notebook/ASUSTek Computer/G73/G73Jh/A82E379AD538/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/4F1CAE64B4>) |
| 8087:0aa7 | Intel            | Bluetooth Device                     | 1392  | btusb      | [390462D20A](<Desktop/Hewlett-Packard/OMEN/OMEN by Desktop PC 870-2XX/23E79BD78168/KUBUNTU-20.04/5.13.0-35-GENERIC/X86_64/390462D20A>) |
| 0cf3:3005 | Qualcomm Athe... | AR3011 Bluetooth                     | 1321  | btusb      | [F6068483CE](<Notebook/Toshiba/Satellite/Satellite C660/B9B75BA01934/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F6068483CE>) |
| 8087:07da | Intel            | Centrino Bluetooth Wireless Trans... | 1266  | btusb      | [47099A8C6C](<Notebook/Medion/E/E6228/11ECFFA666E6/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/47099A8C6C>) |
| 0cf3:3004 | Qualcomm Athe... | AR3012 Bluetooth 4.0                 | 1181  | ath3k, ... | [57531C7393](<Notebook/Samsung Electronics/350V5/350V5C-350V5X-350V4C-350V4X-351V5C-351V5X-351V4C-351V4X-3540VC-3540VX-3440VC-3440VX/73394EEE6C15/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/57531C7393>) |
| 04ca:3015 | Lite-On Techn... | Qualcomm Atheros QCA9377 Bluetooth   | 1137  | btusb      | [DBC222289C](<Notebook/Acer/Aspire/Aspire A315-56/7D0CCEC5B16C/ENDLESS-4.0.3/5.11.0-35-GENERIC/X86_64/DBC222289C>) |
| 8087:0025 | Intel            | Wireless-AC 9260 Bluetooth Adapter   | 1075  | btusb      | [889E5FE7A3](<Desktop/MSI/MS-7/MS-7B85/E913502156FC/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/889E5FE7A3>) |
| 0cf3:e500 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 1028  | btusb      | [B950D195CE](<Notebook/Lenovo/IdeaPad/IdeaPad 330S-15ARR 81FB/E10C1473180B/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/B950D195CE>) |
| 0bda:b00a | Realtek Semic... | Bluetooth Radio                      | 854   | btusb      | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 0cf3:e009 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 736   | btusb      | [8248B17F01](<Notebook/Dell/Vostro/Vostro 5471/BF689F2C5926/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/8248B17F01>) |
| 8086:0189 | Intel            | Centrino Advanced-N 6230 Bluetoot... | 682   | btusb      | [BC9AB1100F](<Notebook/Dell/System/System XPS L702X/31ACC7DF06F6/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/BC9AB1100F>) |
| 0bda:b009 | Realtek Semic... | Realtek Bluetooth 4.2 Adapter        | 657   | btusb      | [BC59A5A32B](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bs0xx/4C5B05E3EE0E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/BC59A5A32B>) |
| 0cf3:e300 | Qualcomm Athe... | QCA61x4 Bluetooth 4.0                | 651   | btusb      | [3F8FE40793](<Notebook/Dell/XPS/XPS 15 9570/FFC4E3644992/UBUNTUSTUDIO-21.10/5.13.0-30-GENERIC/X86_64/3F8FE40793>) |
| 0a5c:217f | Broadcom         | BCM2045B (BDC-2.1)                   | 623   | btusb      | [A83A1FFE1A](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4180MBM/D74FF9CB9D32/ARCO-ROLLING/5.16.13-ARCH1-1/X86_64/A83A1FFE1A>) |
| 04ca:300b | Lite-On Techn... | Atheros AR3012 Bluetooth             | 575   | ath3k, ... | [FCD769423D](<Notebook/Acer/Aspire/Aspire ES1-311/00C1CB7A91AF/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/FCD769423D>) |
| 03f0:231d | Hewlett-Packard  | Broadcom 2070 Bluetooth Combo        | 524   | btusb      | [7C9250A463](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8440p/322E3EEB7C57/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/7C9250A463>) |
| 0a5c:21e8 | Broadcom         | BCM20702A0 Bluetooth 4.0             | 512   | btusb      | [EF2E2E6872](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/F1248BB1749F/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/EF2E2E6872>) |
| 0cf3:e005 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 485   | ath3k, ... | [490DA26167](<Notebook/Dell/Inspiron/Inspiron 15-3567/2C39383F2B1A/UBUNTU-18.04/5.4.0-100-GENERIC/X86_64/490DA26167>) |
| 0cf3:0036 | Qualcomm Athe... | AR9462 Bluetooth                     | 483   | ath3k, ... | [7D57D04480](<Desktop/Dell/Inspiron/Inspiron 3847/ACEAAE9A8A20/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/7D57D04480>) |
| 03f0:171d | Hewlett-Packard  | Bluetooth 2.0 Interface [Broadcom... | 478   | btusb      | [55A6D982B3](<Notebook/Hewlett-Packard/Compaq/Compaq nw8440/341816537142/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/55A6D982B3>) |
| 0bda:b00b | Realtek Semic... | Bluetooth Radio                      | 459   | btusb      | [1064E67665](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/4F19AA0B254D/ELEMENTARY-6.1/5.13.0-35-GENERIC/X86_64/1064E67665>) |
| 0bda:c024 | Realtek Semic... | Bluetooth Radio                      | 434   | btusb      | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 0a5c:21e6 | Broadcom         | BCM20702 Bluetooth 4.0 [ThinkPad]    | 427   | btusb      | [1A0CAB737B](<Notebook/Lenovo/ThinkPad/ThinkPad X230 2325P38/5DD76B98FF69/SLACKWARE-15.0/5.15.19/X86_64/1A0CAB737B>) |
| 413c:8187 | Dell             | DW375 Bluetooth Module               | 423   | btusb      | [E7BEC31798](<Notebook/Dell/Precision/Precision M4500/B8D1C7791579/LINUXMINT-19.3/5.4.0-100-GENERIC/I686/E7BEC31798>) |
| 0b05:17cb | ASUSTek Computer | Broadcom BCM20702A0 Bluetooth        | 407   | btusb      | [C75EB0D27F](<Desktop/ASRock/FM2A88X+/FM2A88X+ Killer/1AEF9FFA4343/DEBIAN-11/5.10.0-11-AMD64/X86_64/C75EB0D27F>) |
| 0bda:b728 | Realtek Semic... | RTL8723B Bluetooth                   | 403   | btusb      | [0B073EA407](<Notebook/Lenovo/G50-70/G50-70 20351/981DCA4EEF11/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/0B073EA407>) |
| 0bda:b00c | Realtek Semic... | Bluetooth Radio                      | 390   | btusb      | [92DB061239](<Notebook/Hewlett-Packard/Laptop/Laptop 14s-dq2xxx/995426A11705/ARTIX-ROLLING/5.16.10-ARTIX1-1/X86_64/92DB061239>) |
| 04ca:3016 | Lite-On Techn... | Bluetooth Device                     | 368   | btusb      | [952FD83515](<Notebook/Acer/Aspire/Aspire VN7-572/4987999D82D2/XUBUNTU-21.10/5.13.0-19-GENERIC/X86_64/952FD83515>) |
| 13d3:3362 | IMC Networks     | Atheros AR3012 Bluetooth 4.0 Adapter | 368   | ath3k, ... | [A1D8D94B5F](<Notebook/ASUSTek Computer/N56/N56VJ/1D425D5F0660/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/A1D8D94B5F>) |
| 105b:e065 | Foxconn Inter... | BCM43142A0 Bluetooth module          | 366   | btusb      | [FB6977C476](<Notebook/Lenovo/G700/G700 20251/2A35DDF1CF5C/KDE-NEON-20.04/5.13.0-28-GENERIC/X86_64/FB6977C476>) |
| 0cf3:e007 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 361   | btusb      | [E99C4341CA](<Notebook/Dell/Inspiron/Inspiron 5409/34EA23E7BE6D/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/E99C4341CA>) |
| 0bda:8771 | Realtek Semic... | Bluetooth Radio                      | 356   | btusb      | [67EAD34E9E](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/13EB708B851F/ZORIN-16/5.13.0-35-GENERIC/X86_64/67EAD34E9E>) |
| 0a5c:2101 | Broadcom         | BCM2045 Bluetooth                    | 340   | btusb      | [3104016080](<Notebook/Acer/Extensa/Extensa 5620/43D119AE7DB3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3104016080>) |
| 13d3:3529 | IMC Networks     | Bluetooth Radio                      | 334   | btusb      | [F735730566](<Notebook/ASUSTek Computer/VivoBook/VivoBook 15_ASUS Laptop X540MA_X543MA/12E0D68E7183/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/F735730566>) |
| 05ac:8215 | Apple            | Built-in Bluetooth 2.0+EDR HCI       | 306   | btusb      | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 0a5c:219c | Broadcom         | BCM2070 Bluetooth Device             | 304   | btusb      | [7E3A87A955](<Notebook/Samsung Electronics/R425/R425D-R525D/BB1EA454007A/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/7E3A87A955>) |
| 8087:0032 | Intel            | AX210 Bluetooth                      | 303   | btusb      | [9BB17A1C87](<Notebook/Lenovo/ThinkPad/ThinkPad T15 Gen 2i 20W4000NRT/A8DFB379DA21/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/9BB17A1C87>) |
| 0bda:0821 | Realtek Semic... | RTL8821A Bluetooth                   | 293   | btusb      | [5AF22F3639](<Notebook/Lenovo/IdeaPad/IdeaPad 320-15ISK 80XH/7063C8B4BE67/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/5AF22F3639>) |
| 0bda:c123 | Realtek Semic... | Bluetooth Radio                      | 293   | btusb      | [3617D41378](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 15ALC05 82HV/BFC66FC359C3/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3617D41378>) |
| 05ac:828f | Apple            | Bluetooth USB Host Controller        | 292   | apple_m... | [92F34786B4](<Notebook/Apple/MacBookAir6/MacBookAir6,2/2BA3C5A30C3E/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/92F34786B4>) |
| 0a5c:21b4 | Broadcom         | BCM2070 Bluetooth 2.1 + EDR          | 292   | btusb      | [3FF8CF8ED0](<Notebook/Hewlett-Packard/Pavilion/Pavilion g4/181B582E2746/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/3FF8CF8ED0>) |
| 0489:e04e | Foxconn / Hon... | Bluetooth Device                     | 291   | ath3k, ... | [40F6802B71](<Notebook/Acer/Aspire/Aspire V3-571G/DD1C23020DFA/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/40F6802B71>) |
| 0bda:b008 | Realtek Semic... | Bluetooth Radio                      | 281   | btusb      | [DE3091D5D4](<Notebook/Hewlett-Packard/Notebook/Notebook/2290168F381B/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/DE3091D5D4>) |
| 0bda:b721 | Realtek Semic... | Bluetooth Radio                      | 273   | btusb      | [629D92121B](<Notebook/ASUSTek Computer/X541/X541UA/2830FC4B7DF8/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/629D92121B>) |

### Camera (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:0825 | Logitech         | Webcam C270                          | 1147  | snd_usb... | [55CE4F1460](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/A185B7D2F341/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/55CE4F1460>) |
| 04e8:6860 | Samsung Elect... | Galaxy A5 (MTP)                      | 761   | usbfs      | [5C45B0B08A](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-fq0xxx/4BB07732F905/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/5C45B0B08A>) |
| 046d:082d | Logitech         | HD Pro Webcam C920                   | 668   | snd_usb... | [3F58A0F2A4](<Notebook/Lenovo/Legion/Legion Y530-15ICH 81FV/A4B769895625/GENTOO-2.6/5.15.23-GENTOO/X86_64/3F58A0F2A4>) |
| 05ac:12a8 | Apple            | iPhone5/5C/5S/6                      | 626   | ipheth     | [B48A6240BF](<Notebook/Lenovo/ThinkPad/ThinkPad E15 20RD0016GE/4F4BEFFC091C/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/B48A6240BF>) |
| 13d3:5a11 | IMC Networks     | USB2.0 VGA UVC WebCam                | 615   | uvcvideo   | [F735730566](<Notebook/ASUSTek Computer/VivoBook/VivoBook 15_ASUS Laptop X540MA_X543MA/12E0D68E7183/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/F735730566>) |
| 13d3:56a2 | IMC Networks     | USB2.0 HD UVC WebCam                 | 459   | uvcvideo   | [ED4DB5233E](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DD_FX505DD/5EA1D9EED139/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/ED4DB5233E>) |
| 0408:a061 | Quanta           | HD User Facing                       | 402   | uvcvideo   | [CCA64BFD46](<Notebook/Acer/Nitro/Nitro AN515-54/7DBAAC635A99/ENDLESS-4.0.3/5.11.0-35-GENERIC/X86_64/CCA64BFD46>) |
| 0408:a031 | Quanta           | VGA WebCam                           | 401   | uvcvideo   | [DBC222289C](<Notebook/Acer/Aspire/Aspire A315-56/7D0CCEC5B16C/ENDLESS-4.0.3/5.11.0-35-GENERIC/X86_64/DBC222289C>) |
| 13d3:5a01 | IMC Networks     | USB2.0 VGA UVC WebCam                | 401   | uvcvideo   | [629D92121B](<Notebook/ASUSTek Computer/X541/X541UA/2830FC4B7DF8/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/629D92121B>) |
| 064e:a103 | Suyin            | Acer/HP Integrated Webcam [CN0314]   | 380   | uvcvideo   | [9F926D363E](<Notebook/Acer/Aspire/Aspire 5732Z/51D431EC5846/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/9F926D363E>) |
| 0ac8:3420 | Z-Star Microe... | Venus USB2.0 Camera                  | 374   | uvcvideo   | [FFFBA31B29](<Desktop/ASRock/G31/G31M-GS/74FF3B185257/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/FFFBA31B29>) |
| 04f2:b604 | Chicony Elect... | Integrated Camera (1280x720@30)      | 372   | uvcvideo   | [755854F7D4](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5A07TAU/0D8B48BD5BBE/ORACLESERVER-8.5/5.4.17-2136.304.4.3.EL8UEK.X86_64/X86_64/755854F7D4>) |
| 0c45:6723 | Microdia         | Integrated_Webcam_HD                 | 368   | uvcvideo   | [69FD2B147F](<Notebook/Dell/XPS/XPS 13 9305/8DFBFD565288/LINUXMINT-20.1/5.4.0-104-GENERIC/X86_64/69FD2B147F>) |
| 5986:2113 | Acer             | Integrated Camera                    | 359   | uvcvideo   | [2F136D5BF5](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN002YPH/61077ED80EDE/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/2F136D5BF5>) |
| 058f:5608 | Alcor Micro      | USB 2.0 Web Camera                   | 350   | uvcvideo   | [FA7F40245B](<Notebook/Positivo/CHT12/CHT12CP/D453CC3A0C14/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/FA7F40245B>) |
| 05ac:8509 | Apple            | FaceTime HD Camera                   | 339   | uvcvideo   | [2AB16BFCEE](<Notebook/Apple/MacBookPro9/MacBookPro9,2/69963227A53F/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/2AB16BFCEE>) |
| 04f2:b64f | Chicony Elect... | HD User Facing                       | 337   | uvcvideo   | [84BC5F3382](<Convertible/Acer/Spin/Spin SP314-54N/1F529A73EE54/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/84BC5F3382>) |
| 1bcf:2c18 | Sunplus Innov... | HD WebCam                            | 310   | uvcvideo   | [809073B4D7](<Notebook/Acer/TravelMate/TravelMate P253/13612FA220ED/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/809073B4D7>) |
| 0408:a060 | Quanta           | HD Webcam                            | 297   | uvcvideo   | [8E7B1DB68F](<Notebook/Acer/Aspire/Aspire A515-51/1B666FCC2D3A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/8E7B1DB68F>) |
| 05ac:8507 | Apple            | Built-in iSight                      | 296   | uvcvideo   | [0F0EF0F4A0](<Notebook/Apple/MacBook5/MacBook5,1/204181EE85F0/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/0F0EF0F4A0>) |
| 5986:0295 | Acer             | Lenovo Integrated Webcam             | 290   | uvcvideo   | [1F84B1E42D](<Notebook/Lenovo/G580/G580 20150/8AADC209F667/CENTOS-9/5.14.0-66.EL9.X86_64/X86_64/1F84B1E42D>) |
| 046d:081b | Logitech         | Webcam C310                          | 287   | snd_usb... | [45BEEC1B7C](<Desktop/ASUSTek Computer/All/All Series/3C968B8AB880/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/45BEEC1B7C>) |
| 13d3:56b2 | IMC Networks     | Integrated Camera                    | 286   | uvcvideo   | [17F7F8858F](<Convertible/Lenovo/IdeaPad/IdeaPad C340-14IWL 81RL/226C9C17E7DC/DEBIAN-10/4.19.0-18-AMD64/X86_64/17F7F8858F>) |
| 0408:5365 | Quanta           | HP TrueVision HD Camera              | 280   | uvcvideo   | [60A1D94845](<Notebook/Hewlett-Packard/Laptop/Laptop 15-dw1xxx/34FFE39D867E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/60A1D94845>) |
| 1bcf:2883 | Sunplus Innov... | Asus Webcam                          | 276   | uvcvideo   | [41F11E9487](<Notebook/ASUSTek Computer/X45/X45U/1C5D5B5B5ED2/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/41F11E9487>) |
| 0c45:62c0 | Microdia         | Sonix USB 2.0 Camera                 | 274   | uvcvideo   | [7404E9534E](<Desktop/Acer/Aspire/Aspire M7720/23A5D7219017/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/7404E9534E>) |
| 05ac:8502 | Apple            | Built-in iSight                      | 271   | uvcvideo   | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 0c45:6366 | Microdia         | Webcam Vitade AF                     | 267   | snd_usb... | [19894BD1A8](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VI EXTREME/F911FC352B7F/KDE-NEON-20.04/5.15.26-XANMOD1/X86_64/19894BD1A8>) |
| 0c45:6340 | Microdia         | Camera                               | 266   | snd_usb... | [1400ED0B8D](<Desktop/ASUSTek Computer/PRIME/PRIME B365M-A/BFAC8BBEE43F/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/1400ED0B8D>) |
| 0402:9665 | ALi              | Gateway Webcam                       | 264   | uvcvideo   | [CD3380A8B4](<Notebook/Acer/Aspire/Aspire 5349/800E1822B08D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/CD3380A8B4>) |
| 046d:0826 | Logitech         | HD Webcam C525                       | 258   | uvcvideo   | [71E8B113B4](<Desktop/Gigabyte Technology/H61/H61M-S2PV/9D2B0DF0631F/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/71E8B113B4>) |
| 0c45:671e | Microdia         | Integrated_Webcam_HD                 | 251   | uvcvideo   | [F094B510C8](<Notebook/Dell/Inspiron/Inspiron 3793/FF8F84C8407D/DEBIAN-11/5.15.6.1-MARCH/X86_64/F094B510C8>) |
| 058f:a014 | Alcor Micro      | Asus Integrated Webcam               | 250   | uvcvideo   | [117876C3AA](<Notebook/ASUSTek Computer/K53/K53SC/87A3FEDFF767/XUBUNTU-20.04/5.4.0-100-LOWLATENCY/X86_64/117876C3AA>) |
| 04f2:b230 | Chicony Elect... | Integrated HP HD Webcam              | 249   | uvcvideo   | [FBC726A0B8](<Notebook/Hewlett-Packard/ProBook/ProBook 6470b/32A30A3A3068/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/FBC726A0B8>) |
| 04f2:b52b | Chicony Elect... | USB2.0 VGA UVC WebCam                | 247   | uvcvideo   | [AEF8901D13](<Notebook/ASUSTek Computer/X541/X541UV/6D894B1F1576/POP!_OS-20.04/5.15.15-76051515-GENERIC/X86_64/AEF8901D13>) |
| 04f2:b47f | Chicony Elect... | VGA Webcam                           | 244   | uvcvideo   | [A885962E63](<Notebook/Acer/Aspire/Aspire ES1-520/62CFB2DBE91A/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/A885962E63>) |
| 04f2:b1d6 | Chicony Elect... | CNF9055 Toshiba Webcam               | 241   | uvcvideo   | [F6068483CE](<Notebook/Toshiba/Satellite/Satellite C660/B9B75BA01934/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F6068483CE>) |
| 046d:082b | Logitech         | Webcam C170                          | 239   | snd_usb... | [C8474E89B8](<Desktop/Gigabyte Technology/H110/H110M-H/A6D65E8E4B13/ENDLESS-4.0.3/5.11.0-35-GENERIC/X86_64/C8474E89B8>) |
| 04f2:b217 | Chicony Elect... | Lenovo Integrated Camera (0.3MP)     | 236   | uvcvideo   | [508A68F09E](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4290EC5/45C5B8282921/KUBUNTU-18.04/4.15.0-169-GENERIC/X86_64/508A68F09E>) |
| 13d3:5710 | IMC Networks     | UVC VGA Webcam                       | 235   | uvcvideo   | [B7944A1493](<Notebook/ASUSTek Computer/U32/U32U/EEB44DF601E7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B7944A1493>) |
| 2232:1020 | Silicon Motion   | WebCam SC-0311139N                   | 227   | uvcvideo   | [0456C09970](<Notebook/Samsung Electronics/300E4/300E4A-300E5A-300E7A/6017E3E6CDEB/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0456C09970>) |
| 04ca:7070 | Lite-On Techn... | Integrated Camera                    | 226   | uvcvideo   | [4F65353F3E](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20T1S8E400/DFC9BE7636A6/XUBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4F65353F3E>) |
| 0bda:57b5 | Realtek Semic... | USB Camera                           | 224   | uvcvideo   | [4F9B339DD5](<Notebook/ASUSTek Computer/X555/X555LAB/F640F8067BC1/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/4F9B339DD5>) |
| 045e:0779 | Microsoft        | LifeCam HD-3000                      | 221   | snd_usb... | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 13d3:5130 | IMC Networks     | Integrated Webcam                    | 220   | uvcvideo   | [D8A321AAE3](<Notebook/ASUSTek Computer/K52/K52JT/18EC50970937/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/D8A321AAE3>) |
| 13d3:56dd | IMC Networks     | USB2.0 HD UVC WebCam                 | 216   | uvcvideo   | [95296F29BB](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X512UB/975FDC0F3724/ENDLESS-4.0.2/5.11.0-35-GENERIC/X86_64/95296F29BB>) |
| 04f2:b071 | Chicony Elect... | 2.0M UVC Webcam / CNF7129            | 213   | uvcvideo   | [4F1CAE64B4](<Notebook/ASUSTek Computer/G73/G73Jh/A82E379AD538/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/4F1CAE64B4>) |
| 5986:0652 | Acer             | Lenovo EasyCamera                    | 205   | uvcvideo   | [0F4E501D1F](<Notebook/Lenovo/G50-70/G50-70 20351/988EAF32234E/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/0F4E501D1F>) |
| 046d:085c | Logitech         | C922 Pro Stream Webcam               | 204   | snd_usb... | [3CBA5D22BC](<Desktop/MSI/MS/MS-7918/9432F9FD1040/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/3CBA5D22BC>) |
| 04f2:b61e | Chicony Elect... | Integrated Camera                    | 204   | uvcvideo   | [E24C41D802](<Notebook/Lenovo/IdeaPad/IdeaPad Flex-14API 81SS/1999F7A23999/ARCO-ROLLING/5.16.10-ARCH1-1/X86_64/E24C41D802>) |

### Card reader (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:0129 | Realtek Semic... | RTS5129 Card Reader Controller       | 8868  | rtsx_usb   | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 0bda:0139 | Realtek Semic... | RTS5139 Card Reader Controller       | 920   | rtsx_usb   | [BF2F9B2C1D](<Notebook/ASUSTek Computer/Q501/Q501LA/E3FF080C61AE/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/BF2F9B2C1D>) |
| 17ef:a38f | Lenovo           | Billboard Device                     | 46    | usbhid     | [F86D99B8A1](<Notebook/Lenovo/ThinkPad/ThinkPad L14 Gen 1 20U5S01S00/2B880CC2B844/KUBUNTU-21.10/5.16.5/X86_64/F86D99B8A1>) |
| 04b4:521a | Cypress Semic... | USB-I2C Bridge                       | 35    |            | [B48A6240BF](<Notebook/Lenovo/ThinkPad/ThinkPad E15 20RD0016GE/4F4BEFFC091C/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/B48A6240BF>) |
| 0aec:3260 | Neodio Techno... | 7-in-1 Card Reader                   | 34    | uas, us... | [42B94E096D](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/74EF604DC6AB/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/42B94E096D>) |
| 17ef:3075 | Lenovo           | USB Billboard Device                 | 34    |            | [ABED4A5863](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 2i 20W0000FRT/03B6D51ED61F/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/ABED4A5863>) |
| 04b4:5218 | Cypress Semic... | USB-Serial Bridge                    | 26    |            | [33CE116B8A](<Notebook/Lenovo/ThinkBook/ThinkBook 16p Gen 2 20YM/4DAF13AEA8CC/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/33CE116B8A>) |
| 0c4b:0501 | Reiner SCT Ka... | cyberJack RFID comfort dual inter... | 25    | usbfs      | [4205CEB454](<Desktop/Hewlett-Packard/870/870-115ng/EA1BDA1000D0/OPENSUSE-TUMBLEWEED-20220131/5.16.2-1-DEFAULT/X86_64/4205CEB454>) |
| 0c4b:0500 | Reiner SCT Ka... | cyberJack RFID standard dual inte... | 23    | usbfs      | [3C4A78636B](<Desktop/Dell/OptiPlex/OptiPlex 790/1819FDD9F3F3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3C4A78636B>) |
| 072f:9000 | Advanced Card... | ACR38 AC1038-based Smart Card Reader | 18    | usbfs      | [CC04FE990C](<Desktop/ASUSTek Computer/PRIME/PRIME TRX40-PRO S/7E3F7BC6DB03/DEBIAN-11/5.10.0-10-AMD64/X86_64/CC04FE990C>) |
| 0d8c:5200 | C-Media Elect... | Mass Storage Controller(0D8C,5200)   | 15    |            | [7F95A3373C](<Notebook/Acer/Aspire/Aspire A515-44G/90521D8710C9/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/7F95A3373C>) |
| 0ca6:0010 | Castles Techn... | EZUSB PC/SC Smart Card Reader        | 11    | usbfs      | [C408F72A53](<Desktop/ASUSTek Computer/B75/B75M-PLUS/FB6FECDDD0A6/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/C408F72A53>) |
| 0cf2:6250 | ENE Technology   | SD card reader (UB6250)              | 11    | ums_ene... | [2B59C324E6](<Notebook/Acer/AOHAPPY/AOHAPPY/60C87E0F9C88/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/2B59C324E6>) |
| 0b97:7732 | O2 Micro         | Smart Card Reader                    | 10    |            | [19DC89049D](<Desktop/Hewlett-Packard/Compaq/Compaq dc7600 Small Form Factor/171FB7F56D52/DEBIAN-11/5.10.0-11-AMD64/X86_64/19DC89049D>) |
| 2ce3:9563 |                  | EMV Smartcard Reader                 | 7     |            | [2C27A1EED4](<Notebook/Dynabook/PORTEGE/PORTEGE X30L-J/34424342D908/UBUNTU-21.10/5.16.9-051609-GENERIC/X86_64/2C27A1EED4>) |
| 0bda:0150 | Realtek Semic... | Realtek USB 2.0 Card Reader          | 5     | usb_sto... | [6FB3466F59](<Notebook/Lenovo/Legion/Legion 5 15ARH05H 82B1/3C58F4D0006A/ARCO-ROLLING/5.15.3-ZEN1-1-ZEN/X86_64/6FB3466F59>) |
| 04e6:e003 | SCM Microsystems | SPR532 PinPad SmartCard Reader       | 4     | usbfs      | [842C53B8E2](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S41E00/14889CC0A2CC/DEBIAN-11/5.10.0-6-RT-AMD64/X86_64/842C53B8E2>) |
| 0b0c:003f | Todos AB         | Todos C400 smartcard controller (... | 4     |            | [7A6F9E9890](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/6FA4F11E106E/FEDORA-34/5.12.9-300.FC34.X86_64/X86_64/7A6F9E9890>) |
| 17ef:3078 | Lenovo           | USB Billboard                        | 4     |            | [13078A648E](<Notebook/Lenovo/ThinkPad/ThinkPad X390 20Q1S04L00/52518B703A6C/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/13078A648E>) |
| 04e6:512b | SCM Microsystems | SDI011 Contactless Reader            | 3     |            | [7CF3758630](<Desktop/MSI/MS-7/MS-7B86/B90AD7D7FF07/UBUNTU-21.04/5.11.0-31-GENERIC/X86_64/7CF3758630>) |
| 04e6:5810 | SCM Microsystems | uTrust 2700 R Smart Card Reader      | 3     | usbfs      | [0AAB60DBC8](<Desktop/Gigabyte Technology/H67/H67A-USB3-B3/138819A05940/ELEMENTARY-5.1.7/5.4.0-86-GENERIC/X86_64/0AAB60DBC8>) |
| 11c5:0521 | Inmax            | IMT-0521 Smartcard Reader            | 3     |            | [9B2FCCD56C](<Desktop/ASUSTek Computer/P7/P7P55D/D4D4068DBF5C/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/9B2FCCD56C>) |
| 174f:1105 | Syntek           | SM-MS/Pro-MMC-XD Card Reader         | 3     | uvcvideo   | [B0B1659E5A](<Notebook/Hewlett-Packard/Mini/Mini 110-1000/D41F7AC4A974/ZORIN-15/5.4.0-45-GENERIC/I686/B0B1659E5A>) |
| 04e6:511a | SCM Microsystems | SCR3310-NTTCom USB SmartCard Reader  | 2     | usbfs      | [A5B2555CC2](<Desktop/ASUSTek Computer/PRO/PRO H410M-C/ABEF71E577AC/UBUNTU-20.10/5.8.0-48-GENERIC/X86_64/A5B2555CC2>) |
| 062d:0001 | Taiwan Tai-Ha... | Smart Card Reader                    | 2     | usbfs      | [DD8F32A8D6](<Desktop/MSI/MS-7/MS-7B86/8BE19FF1B402/ARCH-ROLLING/5.12.3-ARCH1-1/X86_64/DD8F32A8D6>) |
| 076b:0596 | OmniKey          | CardMan 2020                         | 2     |            | [517A612C58](<Desktop/MSI/MS-7/MS-7C34/65D396BD52B2/GENTOO-2.7/5.10.27-GENTOO-X86_64/X86_64/517A612C58>) |
| 047b:020b | Silitek          | SK-3105 SmartCard Reader             | 1     | usbhid     | [986AC800BA](<Desktop/Dell/OptiPlex/OptiPlex 3010/5FA9C2F2A894/UBUNTU-18.04/4.15.0-50-GENERIC/X86_64/986AC800BA>) |
| 04e6:5151 | SCM Microsystems | SCR338 Keyboard Smart Card Reader    | 1     | usbhid     | [BD73A86E1F](<Notebook/Dell/Latitude/Latitude E7440/E5F9C0AE9C43/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/BD73A86E1F>) |
| 0c45:1018 | Microdia         | Compact Flash storage memory card... | 1     |            | [696C2127B6](<Desktop/Lenovo/H520S/H520S 10093/1E6D75332EB5/UBUNTU-19.04/5.0.0-25-GENERIC/X86_64/696C2127B6>) |
| 1667:001a | GIGA-TMS         | MagStripe Card Reader                | 1     | usbhid     | [F40A4B7BAC](<Desktop/Panasonic/JS-970/JS-970WS0018/A1766F006B7A/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/F40A4B7BAC>) |

### Cdrom (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 152d:2329 | JMicron Techn... | JM20329 SATA Bridge                  | 397   | usb_sto... | [472B82D84C](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-A/0AFDD40C40B8/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/472B82D84C>) |
| 0e8d:1887 | MediaTek         | Slim Portable DVD Writer             | 287   | usb_sto... | [93C8BFF33B](<Notebook/Lenovo/IdeaPad/IdeaPad 100-15IBY 80MJ/1C5B87A81853/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/93C8BFF33B>) |
| 13fd:0840 | Initio           | INIC-1618L SATA                      | 216   | usb_sto... | [72775A871A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/72775A871A>) |
| 12d1:107e | Huawei Techno... | P10 smartphone                       | 168   | uas, us... | [44656B1BD4](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/25E6B428C266/GENTOO-2.8/5.16.11-GENTOO-X86_64/X86_64/44656B1BD4>) |
| 0e8d:1806 | MediaTek         | Samsung SE-208 Slim Portable DVD ... | 164   | usb_sto... | [3F34CB2ADA](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G3 Desktop Mini/116367474190/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/3F34CB2ADA>) |
| 04c5:2028 | Fujitsu          | Virtual CD-Rom                       | 140   | uas, us... | [6F14FD298C](<Convertible/Dell/XPS/XPS 13 9310 2-in-1/77A46B94B11C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6F14FD298C>) |
| 1c6b:a223 | Philips & Lit... | eBAU108 6 L                          | 128   | usb_sto... | [DE63F89D08](<Desktop/Gigabyte Technology/H61/H61M-D2H/8ACC07EA8985/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/DE63F89D08>) |
| 152d:2339 | JMicron Techn... | JM20339 SATA Bridge                  | 91    | uas, us... | [7FA47971C2](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92p 3238B37/EA97B63EE3F9/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/7FA47971C2>) |
| 13fd:1040 | Initio           | INIC-1511L PATA Bridge               | 90    | usb_sto... | [61F8410ABD](<Desktop/Gigabyte Technology/AX370-Gaming/AX370-Gaming K5/180A39028A18/ZORIN-16/5.13.0-28-GENERIC/X86_64/61F8410ABD>) |
| 0e8d:1836 | MediaTek         | Samsung SE-S084 Super WriteMaster... | 67    | usb_sto... | [9F4470EA28](<Desktop/MSI/MS/MS-7360/AC7505976B3C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/9F4470EA28>) |
| 13fd:3940 | Initio           | external DVD burner ECD819-SU3       | 65    | uas, us... | [0171FA003C](<Notebook/Hewlett-Packard/255/255 G7 Notebook PC/1045F9222C2A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0171FA003C>) |
| 152e:2571 | LG (HLDS)        | GP08NU6W DVD-RW                      | 62    | uas, us... | [37D07EC6DF](<Desktop/Gigabyte Technology/B550/B550 AORUS PRO/51837CB040D6/OPENSUSE-TUMBLEWEED-20220228/5.16.11-1-DEFAULT/X86_64/37D07EC6DF>) |
| 0bda:1a2b | Realtek Semic... | RTL8188GU 802.11n WLAN Adapter (D... | 58    | uas, us... | [01CAE1BB94](<Desktop/Dell/OptiPlex/OptiPlex 390/327A317D7B9C/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/01CAE1BB94>) |
| 174c:1351 | ASMedia Techn... | DVDRW DA8AESH                        | 55    | uas, us... | [8443B3C441](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/37F739C18F0A/LINUXMINT-20.2/5.4.0-80-GENERIC/X86_64/8443B3C441>) |
| 152e:1640 | LG (HLDS)        | INIC-1605 SATA Bridge                | 47    | usb_sto... | [4CBFB2942D](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/43964D9A93C6/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/4CBFB2942D>) |
| 046b:ff20 | American Mega... | Virtual CDROM0                       | 39    | uas, us... | [C462619A26](<Desktop/ASRockRack/X470/X470D4U2-2T/EBA52B45302C/DEBIAN-11/5.13.19-4-PVE/X86_64/C462619A26>) |
| 152e:2507 | LG (HLDS)        | PL-2507 IDE Controller               | 39    | uas, us... | [781A92F9A4](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10DR000TUK/01F82514F195/UBUNTU-20.04/5.16.0-051600-GENERIC/X86_64/781A92F9A4>) |
| 0928:0010 | PLX Technology   | Virtual CDRom                        | 38    | uas, us... | [7132BCC66D](<Notebook/Samsung Electronics/350V5/350V5C-351V5C-3540VC-3440VC/8AA326D861A9/ELEMENTARY-5.1.7/5.4.0-42-GENERIC/X86_64/7132BCC66D>) |
| 0b05:7774 | ASUSTek Computer | Zenfone GO (ZB500KL) (RNDIS mode)    | 35    | rndis_host | [AA1E6A4C82](<Desktop/Biostar/N68/N68S3B/A98E2FD5FA9F/ELEMENTARY-6.1/5.13.0-35-GENERIC/X86_64/AA1E6A4C82>) |
| 08e4:017a | Pioneer          | BD-RW BDR-XS07U                      | 33    | usb_sto... | [42921AEBFD](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G6/A8B5AAF45EC2/UBUNTU-BUDGIE-21.10/5.13.0-35-GENERIC/X86_64/42921AEBFD>) |
| 13fd:0940 | Initio           | ASUS SBW-06D2X-U                     | 27    | uas, us... | [1EB72BDE90](<Desktop/Gigabyte Technology/B450/B450 AORUS PRO/A2EC40193D14/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1EB72BDE90>) |
| 13fd:2040 | Initio           | Samsung Writemaster external DVD ... | 26    | usb_sto... | [7EAB522138](<Mini Pc/ZOTAC/ZBOXNANO-ID/ZBOXNANO-ID67/C3933CE474DF/LINUXMINT-20.3/5.4.0-26-GENERIC/X86_64/7EAB522138>) |
| 0e8d:1956 | MediaTek         | Samsung SE-506 Portable BluRay Di... | 25    | usb_sto... | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 13fd:3e40 | Initio           | ZALMAN ZM-VE350                      | 25    | uas, us... | [DCD8E45866](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/8DAA8C8E0AB8/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/DCD8E45866>) |
| 2a70:f003 | OnePlus          | IN2017                               | 25    | uas, us... | [D65C6F6AB1](<Notebook/Dell/Precision/Precision M6400/59903F98A6D7/LINUXMINT-19.3/4.15.0-162-GENERIC/X86_64/D65C6F6AB1>) |
| 12d1:107f | Huawei Techno... | File-CD Gadget                       | 24    | uas, us... | [E6F96C5F67](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800 Small Form Factor/1ED8D250F9AD/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/E6F96C5F67>) |
| 2e04:c025 | HMD Global       | Nokia 8 (MTP mode)                   | 23    | uas, us... | [93957DDAC1](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ALC6 82KU/1B9155B752DC/ENDEAVOUROS-ROLLING/5.15.7-ARCH1-1/X86_64/93957DDAC1>) |
| 12d1:1082 | Huawei Techno... | File-CD Gadget                       | 22    | uas, us... | [D5D2EE0AB5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G7 Microtower PC/473ECA75FDF0/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D5D2EE0AB5>) |
| 13fd:0842 | Initio           | CDDVDW SE-S084C                      | 19    | usb_sto... | [B3B777135E](<Desktop/Gigabyte Technology/F2/F2A68HM-H/726E68ABEAAB/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/B3B777135E>) |
| 413c:9016 | Dell             | DVD+/-RW DW316                       | 17    | usb_sto... | [06ACAB97B2](<Desktop/Gigabyte Technology/990/990FXA-UD3/48166B33D432/FEDORA-34/5.14.18-200.FC34.X86_64/X86_64/06ACAB97B2>) |
| 054c:02d5 | Sony             | DVD-RAM UJ-852S                      | 16    | uas, us... | [972677CEAB](<Notebook/Sony/VGN-TZ21/VGN-TZ21WN_B/8007887B1C37/LINUXMINT-20.2/5.4.0-80-GENERIC/X86_64/972677CEAB>) |
| 19d2:1410 | ZTE WCDMA Tec... | USB SCSI CD-ROM                      | 16    | uas, us... | [27CC77A565](<Notebook/Apple/MacBookPro16/MacBookPro16,2/78BB42B0745C/KALI-2020.3/5.7.0-KALI1-AMD64/X86_64/27CC77A565>) |
| 8564:8000 | Transcend        | TRANSCEND                            | 14    | usb_sto... | [34E71F1E27](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/79C0C0B28FC3/ELEMENTARY-6/5.11.0-40-GENERIC/X86_64/34E71F1E27>) |
| 05e3:0719 | Genesys Logic    | SATA adapter                         | 13    | uas, us... | [BD43E4B748](<Desktop/ASUSTek Computer/EB1501/EB1501P/F9379D75B4AB/KUBUNTU-20.04/5.13.0-27-GENERIC/X86_64/BD43E4B748>) |
| 0624:0251 | Avocent          | Virtual Mass Storage                 | 12    | uas, us... | [D5C4EF93C4](<Server/Dell/PowerEdge/PowerEdge R720xd/6A086FD83CA7/ROCKY-8.5/4.18.0-348.7.1.EL8_5.X86_64/X86_64/D5C4EF93C4>) |
| 067b:2571 | Prolific Tech... | LG Electronics GE24LU21              | 12    | uas, us... | [65E7FC8820](<Desktop/Gigabyte Technology/X399/X399 AORUS Gaming 7/6DC84C2CE66B/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/65E7FC8820>) |
| 0930:0c05 | Toshiba          | DVD-RAM UJ-844S                      | 12    | usb_sto... | [B4DBC4297F](<Notebook/Toshiba/PORTEGE/PORTEGE R600/710934C3584F/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/B4DBC4297F>) |
| 12d1:107d | Huawei Techno... | File-CD Gadget                       | 12    | rndis_host | [71C19B42FC](<Desktop/Gigabyte Technology/B450M/B450M S2H/ED3A74F66A5F/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/71C19B42FC>) |
| 04b7:0100 | Compal Electr... | DVDRW DA8AESH                        | 11    | uas, us... | [F3EE6F9DBB](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ca0xxx/B10B91A6708A/POP!_OS-21.04/5.15.11-76051511-GENERIC/X86_64/F3EE6F9DBB>) |
| 054c:0377 | Sony             | BD-CMB UJ-120                        | 11    | uas, us... | [EDEAD40B0D](<Notebook/Sony/VGN-FW170/VGN-FW170J/221E48B294E0/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EDEAD40B0D>) |
| 14dd:0002 | Raritan Computer | Multidevice                          | 11    | usbhid     | [A4B004EA5E](<Desktop/MSI/MS-7/MS-7D18/0877AFCD98DC/ARCH-ROLLING/5.16.2-ARCH1-1/X86_64/A4B004EA5E>) |
| 04e8:685b | Samsung Elect... | GT-I9100 Phone [Galaxy S II] (mas... | 10    | uas, us... | [C8821B395F](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bw0xx/5BB5B5D64356/FEDORA-34/5.12.17-300.FC34.X86_64/X86_64/C8821B395F>) |
| 05c6:9039 | Qualcomm         | Android                              | 10    | usbfs      | [5496B24A51](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 6th 20KHS1L200/4F0EA27BB90B/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/5496B24A51>) |
| 0e8d:1807 | MediaTek         | DVDRAM GP40NB40                      | 10    | usb_sto... | [9343A7AAC0](<Desktop/ASUSTek Computer/All/All Series/BE6F4E222975/LINUXMINT-20.2/5.4.0-58-GENERIC/X86_64/9343A7AAC0>) |
| 1c6b:d002 | Philips & Lit... | ES1 1                                | 10    | usb_sto... | [F86D99B8A1](<Notebook/Lenovo/ThinkPad/ThinkPad L14 Gen 1 20U5S01S00/2B880CC2B844/KUBUNTU-21.10/5.16.5/X86_64/F86D99B8A1>) |
| 05c6:f000 | Qualcomm         | Device Driver                        | 9     | uas, us... | [C62460798A](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509DA_M509DA/FD1964527BD4/GENTOO-2.6/5.15.5-GENTOO/X86_64/C62460798A>) |
| 067b:2771 | Prolific Tech... | BD-RE BE14NU40                       | 9     | uas, us... | [314859D762](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/EF13771DDCCC/ZORIN-16/5.11.0-27-GENERIC/X86_64/314859D762>) |
| 13fd:0841 | Initio           | Samsung SE-T084M DVD-RW              | 9     | usb_sto... | [18164956AF](<Desktop/ASRock/J4205/J4205-ITX/92AF736169F9/KDE-NEON-20.04/5.4.0-70-GENERIC/X86_64/18164956AF>) |
| 152d:2519 | JMicron Techn... | Transcend                            | 9     | uas, us... | [1386180677](<All In One/Apple/iMac8/iMac8,1/8D1870971813/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/1386180677>) |
| 0409:0056 | NEC Computers    | CD/DVDW SH-S162L                     | 8     | usb_sto... | [C6C9F72F10](<Desktop/ASUSTek Computer/P5/P5KC/ABC729FF17D4/LINUXMINT-20/5.4.0-70-GENERIC/X86_64/C6C9F72F10>) |

### Chipcard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 058f:9540 | Alcor Micro      | AU9540 Smartcard Reader              | 1303  | usbfs      | [4766FE6362](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2000KRT/974FF46B3D36/ARCH-ROLLING/5.16.13-ARCH1-1/X86_64/4766FE6362>) |
| 0a5c:5800 | Broadcom         | BCM5880 Secure Applications Proce... | 1016  | usbfs      | [E7BEC31798](<Notebook/Dell/Precision/Precision M4500/B8D1C7791579/LINUXMINT-19.3/5.4.0-100-GENERIC/I686/E7BEC31798>) |
| 0a5c:5801 | Broadcom         | BCM5880 Secure Applications Proce... | 417   | usbfs      | [2AF2BBA8DA](<Notebook/Dell/Latitude/Latitude E6430s/A8788E2EED17/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/2AF2BBA8DA>) |
| 0b97:7772 | O2 Micro         | OZ776 CCID Smartcard Reader          | 390   | usbfs      | [CC5F0F79DD](<Notebook/Toshiba/TECRA/TECRA Z50-A/FF500FE27A3A/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/CC5F0F79DD>) |
| 147e:2020 | Upek             | TouchChip Fingerprint Coprocessor... | 336   | usbfs      | [CEEC77F198](<Notebook/Lenovo/ThinkPad/ThinkPad T530 2359CTO/2A7FFCF59535/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/CEEC77F198>) |
| 17ef:1003 | Lenovo           | Integrated Smart Card Reader         | 334   | usbfs      | [4601C3AA77](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537VGY/60E94FBE6817/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/4601C3AA77>) |
| 0a5c:5843 | Broadcom         | 58200                                | 267   | usbfs      | [B56BB115A0](<Notebook/Dell/Latitude/Latitude 5411/33F2D924CBA3/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B56BB115A0>) |
| 0a5c:5832 | Broadcom         | 5880                                 | 260   | usbfs      | [9E9710E890](<Notebook/Dell/Precision/Precision 7730/2A131BBCEBD8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/9E9710E890>) |
| 0a5c:5834 | Broadcom         | 5880                                 | 238   | usbfs      | [CBFF798F89](<Notebook/Dell/Latitude/Latitude 7480/046B50AF97D4/OPENSUSE-20220309/5.16.11-1-DEFAULT/X86_64/CBFF798F89>) |
| 0a5c:5842 | Broadcom         | 58200                                | 84    | usbfs      | [3D87BC42C6](<Notebook/Dell/Latitude/Latitude 5500/0ABE26200F3D/ROCKY-8.5/4.18.0-348.12.2.EL8_5.X86_64/X86_64/3D87BC42C6>) |
| 0a5c:5804 | Broadcom         | BCM5880 Secure Applications Proce... | 77    | usbfs      | [7EB0675554](<Notebook/Dell/Latitude/Latitude E5550/FE67D8CE4D4C/LINUXMINT-19.3/5.4.0-100-GENERIC/X86_64/7EB0675554>) |
| 0b97:7762 | O2 Micro         | Oz776 SmartCard Reader               | 72    |            | [D4E50F40F3](<Notebook/Dell/Latitude/Latitude D620/BFE0941CFFA9/LMDE-4/4.19.0-8-686/I686/D4E50F40F3>) |
| 08e6:3437 | Gemalto (was ... | GemPC Twin SmartCard Reader          | 47    | usbfs      | [8A97B4F2D3](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-K/F094BA5D12EA/CLEAR-LINUX-OS-35980/5.16.12-1129.NATIVE/X86_64/8A97B4F2D3>) |
| 072f:90cc | Advanced Card... | ACR38 SmartCard Reader               | 36    | usbfs      | [567A2D4073](<Notebook/Samsung Electronics/RF511/RF511-RF411-RF711/C4AB2C2CD176/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/567A2D4073>) |
| 0529:0620 | Aladdin Knowl... | Token JC                             | 35    | usbfs      | [5D73B6F2F7](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G7/77EC59780235/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/5D73B6F2F7>) |
| 0bda:0165 | Realtek Semic... | Smart Card Reader Interface          | 33    | usbfs      | [F7B7D4D2DB](<Notebook/ASUSTek Computer/U32/U32U/79A07A28D70D/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/F7B7D4D2DB>) |
| 058f:9520 | Alcor Micro      | Watchdata W 1981                     | 32    | usbfs      | [1C3E6A4AF1](<Desktop/Gigabyte Technology/F2/F2A88XM-HD3P/565489800D93/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/1C3E6A4AF1>) |
| 08e6:34ec | Gemalto (was ... | Compact Smart Card Reader Writer     | 27    | usbfs      | [02818352E0](<Notebook/Lenovo/ThinkPad/ThinkPad X230 2325ND9/AC1E7BFBB0B0/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/02818352E0>) |
| 0a5c:5802 | Broadcom         | BCM5880 Secure Applications Proce... | 22    | usbfs      | [5569C72650](<Notebook/Dell/Latitude/Latitude E6500/A3037319A9E9/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/5569C72650>) |
| 04e6:5116 | SCM Microsystems | SCR331-LC1 / SCR3310 SmartCard Re... | 21    | usbfs      | [44E1189857](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN003WUS/1857B32A610F/FEDORA-34/5.15.8-100.FC34.X86_64/X86_64/44E1189857>) |
| 076b:3021 | OmniKey          | CardMan 3021 / 3121                  | 20    | usbfs      | [5E7B7A63A9](<Notebook/ASUSTek Computer/GL552/GL552VW/138484BF59CB/ZORIN-16/5.13.0-27-GENERIC/X86_64/5E7B7A63A9>) |
| 04e6:5119 | SCM Microsystems | SCR3340 - ExpressCard54 Smart Car... | 17    | usbfs      | [0BA38C6605](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK E780/E68F3F32BD0E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0BA38C6605>) |
| 1050:0406 | Yubico.com       | Yubikey 4 U2F+CCID                   | 16    | usbfs      | [A0D13572A5](<Notebook/TUXEDO/InfinityBook/InfinityBook Pro 14 Gen6/CF00A18B4833/ZORIN-16/5.11.0-38-GENERIC/X86_64/A0D13572A5>) |
| 03f0:164a | Hewlett-Packard  | SC Keyboard - Apollo (Liteon)        | 15    | usbhid     | [28D2C658A9](<Desktop/ASUSTek Computer/Z170/Z170-PRO/F8DF2941D1CD/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/28D2C658A9>) |
| 04f2:1469 | Chicony Elect... | HP Skylab USB Smartcard Keyboard     | 14    | usbhid     | [EBB68892DC](<Notebook/Acer/Swift/Swift SF314-42/094ABAA189DB/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/EBB68892DC>) |
| 076b:1021 | OmniKey          | CardMan 1021                         | 13    | usbfs      | [A27E7CDBEF](<Desktop/Huanan/X79/X79 V2.47/0D0CD837D848/POP!_OS-21.10/5.15.5-76051505-GENERIC/X86_64/A27E7CDBEF>) |
| 25dd:3111 | BIT4ID           | miniLector EVO                       | 12    | usbfs      | [3EDD9950F9](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEK/FC630F3086E8/UBUNTU-21.04/5.11.0-41-GENERIC/X86_64/3EDD9950F9>) |
| 072f:2200 | Advanced Card... | ACR122U                              | 11    | pn533_usb  | [2FD17C77B0](<Notebook/Acer/Swift/Swift SF514-52T/B03ADD0B3D03/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/2FD17C77B0>) |
| 1a44:0001 | VASCO Data Se... | Digipass 905 SmartCard Reader        | 11    | usbfs      | [6E6AC0F1B7](<Desktop/ASUSTek Computer/M3N78-EMH/M3N78-EMH HDMI/8A4B73FAFE20/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/6E6AC0F1B7>) |
| 20a0:4108 | Clay Logic       | Nitrokey Pro                         | 11    | usbhid     | [7697915441](<Notebook/Schenker/VISION/VISION 15/0307C26A2A5F/MANJARO-21.2.2/5.16.2-1-MANJARO/X86_64/7697915441>) |
| 046a:00a1 | Cherry           | SmartCard Reader Keyboard KC 1000 SC | 10    | usbhid     | [52D37E9A75](<Desktop/Intel/DB75EN/DB75EN AAG39650-302/4403CF70CD97/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/52D37E9A75>) |
| 076b:4321 | OmniKey          | CardMan 4321                         | 9     | usbfs      | [6C14033E55](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/A4347166A656/LINUXMINT-20.2/5.4.0-88-GENERIC/X86_64/6C14033E55>) |
| 0a89:0025 | Aktiv            | Rutoken lite                         | 9     | usbfs      | [4492677869](<Desktop/MSI/MS-7/MS-7C35/CBC46B1328AA/GENTOO-2.7/5.16.0-RC2AEON/X86_64/4492677869>) |
| 1050:0111 | Yubico.com       | Yubikey NEO(-N) OTP+CCID             | 9     | usbhid     | [0F83B2FD97](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/9DECE84F972A/ARCO-ROLLING/5.16.8-ARCH1-1/X86_64/0F83B2FD97>) |
| 0a5c:5833 | Broadcom         | 5880                                 | 8     |            | [817E973E9D](<Notebook/Dell/Latitude/Latitude 5480/B95B01FCFA31/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/817E973E9D>) |
| 0c4b:9102 | Reiner SCT Ka... | cyberJack RFID basis contactless ... | 8     | usbfs      | [A7A2A13E23](<Desktop/Gigabyte Technology/GA-890/GA-890FXA-UD5/A481A294ABD4/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/A7A2A13E23>) |
| 0dc3:1004 | Athena Smartc... | ASEDrive CCID                        | 8     | usbfs      | [83C276AE69](<Desktop/Gigabyte Technology/H310M/H310M S2H 2.0/265BF6A6C8AF/DEBIAN-TESTING/5.14.0-2-AMD64/X86_64/83C276AE69>) |
| 1a44:0870 | VASCO Data Se... | DIGIPASS 870                         | 8     | usbfs      | [5E7B7A63A9](<Notebook/ASUSTek Computer/GL552/GL552VW/138484BF59CB/ZORIN-16/5.13.0-27-GENERIC/X86_64/5E7B7A63A9>) |
| 04e6:5410 | SCM Microsystems | SCR35xx Smart Card Reader            | 7     | usbfs      | [EFAC7F4D90](<Notebook/Panasonic/CF-192/CF-192VYFX1M/2E1AB60D3F3E/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/EFAC7F4D90>) |
| 04e6:e001 | SCM Microsystems | SCR331 SmartCard Reader              | 7     | usbfs      | [F7DCF4AD9C](<Notebook/Apple/MacBookPro16/MacBookPro16,1/AC19FB1992A0/FEDORA-32/5.11.22-100.FC32.X86_64/X86_64/F7DCF4AD9C>) |
| 0a5c:5805 | Broadcom         | 5880                                 | 7     |            | [B462D15A6B](<Notebook/Dell/Latitude/Latitude E7270/B35AEC6069FE/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/B462D15A6B>) |
| 0bf8:1006 | Fujitsu Sieme... | SmartCard Reader 2A                  | 7     | usbfs      | [E96B1F7F6B](<Desktop/Fujitsu/FUTRO/FUTRO S900/E3D0AE36A20E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/E96B1F7F6B>) |
| 24dc:0101 | ARDS             | JaCarta                              | 7     | usbfs      | [4D5E452411](<Desktop/Intel/DX79SI/DX79SI AAG28808-600/6BC4311034CA/KUBUNTU-20.04/5.4.0-73-GENERIC/X86_64/4D5E452411>) |
| 08e6:3438 | Gemalto (was ... | GemPC Key SmartCard Reader           | 6     | usbfs      | [10434415D8](<Notebook/Dell/Latitude/Latitude 5511/50F53384CAF3/UBUNTU-21.04/5.11.0-22-GENERIC/X86_64/10434415D8>) |
| 0c4b:0580 | Reiner SCT Ka... | cyberJack one                        | 6     |            | [2A41E081DA](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/F3E6316969DA/XUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/2A41E081DA>) |
| 1059:0017 | Giesecke & De... | StarSign CUT                         | 6     | usbfs      | [03802BFDA7](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/045DF77207C8/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/03802BFDA7>) |
| 1059:0019 | Giesecke & De... | StarSign CUT S                       | 6     | usbfs      | [F1D9692C18](<Notebook/Dell/XPS/XPS 13 7390/57D551536163/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/F1D9692C18>) |
| 04e6:5115 | SCM Microsystems | SCR335 SmartCard Reader              | 5     | usbfs      | [890E3A285F](<Desktop/Acer/Aspire/Aspire XC-105/7CF14550D2EF/UBUNTU-20.04/5.13.0-25-GENERIC/X86_64/890E3A285F>) |
| 072f:b100 | Advanced Card... | ACR39U                               | 4     | usbfs      | [4BC5EB3BBC](<Desktop/ASUSTek Computer/ROG/ROG Maximus XIII HERO/1F5A3C80E4DB/ZORIN-16/5.11.0-36-GENERIC/X86_64/4BC5EB3BBC>) |
| 076b:3031 | OmniKey          | 3x21 Smart Card Reader               | 4     | usbfs      | [408821B06E](<Notebook/Lenovo/IdeaPad/IdeaPad 530S-14ARR 81H1/4A3DB20005A9/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/408821B06E>) |

### Converter (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0403:7a58 | Future Techno... | USB <-> Serial Cable                 | 16    | usbfs      | [5F93713B6D](<Desktop/MSI/MS-7/MS-7A37/4312934B7550/MANJARO-21.2.1/5.15.12-1-MANJARO/X86_64/5F93713B6D>) |
| 0403:1237 | Future Techno... | Z397 GUARD Converter                 | 4     |            | [CF5DEA43E1](<Mini Pc/Hewlett-Packard/260/260 G3 DM/D334B500C95E/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/CF5DEA43E1>) |
| 03eb:21fe | Atmel            | AVR309:USB to UART protocol conve... | 2     | igorplu... | [032A1A34DF](<Desktop/CompuLab/SBC-FITPC/SBC-FITPC2/74B4C3F47893/ZORIN-15/5.3.0-53-GENERIC/I686/032A1A34DF>) |
| 110a:1110 | Moxa Technolo... | UPort 1110                           | 2     | ti_usb_... | [F815AEE35E](<Notebook/Lenovo/ThinkPad/ThinkPad T60 1951BY8/5D9A1B55704D/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-I586/I686/F815AEE35E>) |
| 051d:c812 | American Powe... | APC USB SERIAL CONVERTER.            | 1     | cdc_acm    | [BDB4EBA3E4](<Desktop/ASRock/Q1900/Q1900M/5B23A80950DA/XUBUNTU-20.04/4.15.0-111-GENERIC/X86_64/BDB4EBA3E4>) |
| 0a12:0042 | Cambridge Sil... | SPI Converter                        | 1     |            | [E1C0C74CA6](<Desktop/ASRock/Z390/Z390 Pro4/1A53A6D86AB6/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/E1C0C74CA6>) |
| 0c12:0005 | Zeroplus         | PSX Vibration Feedback Converter     | 1     | usbhid     | [A39C4402B9](<Desktop/ASRock/B75/B75 Pro3-M/93E8C8FE35E9/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/A39C4402B9>) |
| 1f6a:15aa | AJA Video Sys... | AJA Mini-converter                   | 1     | cdc_acm    | [31D8634492](<Desktop/Dell/Precision/Precision WorkStation T3500/6E3A480272C7/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/31D8634492>) |
| 277c:0024 | SIGNALCORE       | SC5308A RF DownConverter             | 1     |            | [1343B5BB5D](<Desktop/ASUSTek Computer/ROG/ROG Maximus XII HERO/3B3EE14AB971/UBUNTU-18.04/4.15.0-144-GENERIC/X86_64/1343B5BB5D>) |

### Disk (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 058f:6387 | Alcor Micro      | Transcend                            | 2360  | uas, us... | [3C01AC84D3](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/730ACCC800BC/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/3C01AC84D3>) |
| 090c:1000 | Silicon Motion   | USB                                  | 2324  | uas, us... | [520A9BC6A0](<All In One/Acer/Aspire/Aspire ZS600/307894E2C20C/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/520A9BC6A0>) |
| 058f:6366 | Alcor Micro      | Multi Flash Reader                   | 2163  | uas, us... | [4F1CAE64B4](<Notebook/ASUSTek Computer/G73/G73Jh/A82E379AD538/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/4F1CAE64B4>) |
| 058f:6362 | Alcor Micro      | Flash Card Reader/Writer             | 2089  | uas, us... | [37C37094B9](<Desktop/Gigabyte Technology/M61/M61PME-S2P/9DACEC325D22/DEBIAN-11/5.10.0-7-AMD64/X86_64/37C37094B9>) |
| 0951:1666 | Kingston Tech... | DataTraveler 100 G3/G4/SE9 G2        | 2014  | uas, us... | [B5A4E6051E](<Desktop/ASUSTek Computer/P8/P8H77-M/836B72179132/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/B5A4E6051E>) |
| 0bda:0138 | Realtek Semic... | RTS5138 Card Reader Controller       | 1620  | ums_rea... | [F6068483CE](<Notebook/Toshiba/Satellite/Satellite C660/B9B75BA01934/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F6068483CE>) |
| 0781:5567 | SanDisk          | Cruzer Blade                         | 1592  | uas, us... | [7A484A0D61](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 R2/65F56473253E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/7A484A0D61>) |
| 8564:1000 | Transcend        | JetFlash                             | 1541  | uas, us... | [629D92121B](<Notebook/ASUSTek Computer/X541/X541UA/2830FC4B7DF8/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/629D92121B>) |
| 0bda:0158 | Realtek Semic... | USB 2.0 multicard reader             | 1506  | ums_rea... | [8762E9C632](<Notebook/Fujitsu Siemens/AMILO/AMILO Li3910/1045062C78EF/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/8762E9C632>) |
| 174c:55aa | ASMedia Techn... | ASM1051E SATA 6Gb/s bridge, ASM10... | 1160  | usb_sto... | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 0781:5581 | SanDisk          | Ultra                                | 1003  | uas, us... | [4F1CAE64B4](<Notebook/ASUSTek Computer/G73/G73Jh/A82E379AD538/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/4F1CAE64B4>) |
| 0930:6545 | Toshiba          | Kingston DataTraveler 102/2.0 / H... | 888   | uas, us... | [5AF22F3639](<Notebook/Lenovo/IdeaPad/IdeaPad 320-15ISK 80XH/7063C8B4BE67/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/5AF22F3639>) |
| 058f:6364 | Alcor Micro      | AU6477 Card Reader Controller        | 805   | uas, us... | [A90045FFA3](<Desktop/ASRock/P67/P67 Pro3/E2B313BFC54F/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/A90045FFA3>) |
| 0781:5583 | SanDisk          | Ultra Fit                            | 716   | uas, us... | [72775A871A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/72775A871A>) |
| 152d:0578 | JMicron Techn... | JMS578 SATA 6Gb/s                    | 681   | uas, us... | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 13fe:4200 | Kingston Tech... | USB DISK 2.0                         | 601   | uas, us... | [73D930BE97](<Notebook/Toshiba/Satellite/Satellite C650/7BC552597A23/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/73D930BE97>) |
| 0bda:0151 | Realtek Semic... | Mass Storage Device (Multicard Re... | 597   | uas, us... | [8DCDBB2B22](<Desktop/Fujitsu Siemens/AMILO/AMILO Desktop Pi3620A/B546F6B2BCF4/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/8DCDBB2B22>) |
| 05e3:0749 | Genesys Logic    | USB3.0 Card Reader                   | 576   | uas, us... | [7A11CA484C](<Desktop/ASUSTek Computer/PRIME/PRIME Z370-P/65A3A46F7F4A/LINUXMINT-20.2/5.4.0-92-GENERIC/X86_64/7A11CA484C>) |
| 0bda:0316 | Realtek Semic... | SD/MMC                               | 571   | uas, us... | [755854F7D4](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5A07TAU/0D8B48BD5BBE/ORACLESERVER-8.5/5.4.17-2136.304.4.3.EL8UEK.X86_64/X86_64/755854F7D4>) |
| 0930:6544 | Toshiba          | TransMemory-Mini / Kingston DataT... | 562   | uas, us... | [83A319F258](<Notebook/Dell/Inspiron/Inspiron 1525/E3C6D99D7C40/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/83A319F258>) |
| 0781:5591 | SanDisk          | Ultra Flair                          | 544   | uas, us... | [8CB0C8F9C9](<Convertible/Dell/Latitude/Latitude 3120/0AD0304CD721/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/8CB0C8F9C9>) |
| 0781:5575 | SanDisk          | Cruzer Glide                         | 538   | uas, us... | [C303702AC5](<Desktop/Dell/PowerEdge/PowerEdge T30/03724261F468/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/C303702AC5>) |
| 0951:1665 | Kingston Tech... | Digital DataTraveler SE9             | 462   | uas, us... | [4601C3AA77](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537VGY/60E94FBE6817/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/4601C3AA77>) |
| 05e3:0745 | Genesys Logic    | Logilink CR0012                      | 460   | uas, us... | [8952D0F7D8](<All In One/Acer/Aspire/Aspire C22-760/1F1998194D47/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/8952D0F7D8>) |
| 0bda:0153 | Realtek Semic... | 3-in-1 (SD/SDHC/SDXC) Card Reader    | 433   | ums_rea... | [71511D4306](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p0xx/EE170EB23889/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/71511D4306>) |
| 13fe:4300 | Kingston Tech... | USB DISK                             | 409   | uas, us... | [F58BB47A42](<Desktop/ASUSTek Computer/P8H61-MX/P8H61-MX R2.0/142916096E18/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F58BB47A42>) |
| ffff:5678 | VendorCo         | Disk 2.0                             | 393   | uas, us... | [CDDC590270](<Mini Pc/BESSTAR Tech/Z83/Z83-F/833154D27E3C/ZORIN-16/5.13.0-30-GENERIC/X86_64/CDDC590270>) |
| 05ac:8403 | Apple            | Internal Memory Card Reader          | 384   | uas, us... | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 13fe:6300 | Kingston Tech... | SP Mobile C31                        | 379   | uas, us... | [83881D4EB6](<All In One/3Logic Group/Graviton/Graviton/2B12BC91A8E9/ALT-10.0/5.10.82-STD-DEF-ALT1/X86_64/83881D4EB6>) |
| 18a5:0302 | Verbatim         | STORE N GO                           | 379   | uas, us... | [76AFE39F5E](<Notebook/Sony/SVS1311/SVS13118GBB/F65894F76BAC/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/76AFE39F5E>) |
| 13fe:4100 | Kingston Tech... | Silicon-Power16G                     | 377   | uas, us... | [57CE8D33B8](<Notebook/Hewlett-Packard/Notebook/Notebook/D8E63FF4C50D/ROSA-2016.1/5.4.32-GENERIC-2ROSA-X86_64/X86_64/57CE8D33B8>) |
| 1005:b113 | Apacer Techno... | Handy Steno 2.0/HT203                | 375   | uas, us... | [231DA9915B](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-22ICB F0E90010RK/7B7162E100C2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/231DA9915B>) |
| 0781:5571 | SanDisk          | Cruzer Fit                           | 362   | uas, us... | [D52BA5F273](<Notebook/Toshiba/Satellite/Satellite A660/7B4E41608F26/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/D52BA5F273>) |
| abcd:1234 | LogiLink         | UDisk                                | 362   | uas, us... | [E5E17E5138](<Notebook/Dell/Inspiron/Inspiron N4030/9F1F976E8029/UBUNTUDDE-21.10/5.13.0-30-GENERIC/X86_64/E5E17E5138>) |
| 05ac:8406 | Apple            | SD Card Reader                       | 354   | apple_m... | [B27D8C8724](<Notebook/Apple/MacBookPro11/MacBookPro11,4/67C61AAA3F88/PARROT-5.0/5.14.0-9PARROT1-AMD64/X86_64/B27D8C8724>) |
| 152d:2338 | JMicron Techn... | JM20337 Hi-Speed USB to SATA & PA... | 347   | uas, us... | [E5EAEC6553](<Desktop/Hewlett-Packard/Pro/Pro 3000 Microtower PC/5B8622E21C1D/DEBIAN-11/5.10.0-11-AMD64/X86_64/E5EAEC6553>) |
| 05e3:0751 | Genesys Logic    | microSD Card Reader                  | 341   | uas, us... | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 048d:1336 | Integrated Te... | SD/MMC Cardreader                    | 323   | uas, us... | [50BB4C65AB](<Desktop/ASUSTek Computer/All/All Series/3CDA02BE060E/UBUNTU-20.04/5.4.0-53-GENERIC/X86_64/50BB4C65AB>) |
| 0bda:0111 | Realtek Semic... | RTS5111 Card Reader Controller       | 310   | uas, us... | [28E6A0766D](<Desktop/ASRock/N68C-S/N68C-S UCC/238E55628E17/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/28E6A0766D>) |
| 0bc2:231a | Seagate          | Expansion                            | 306   | uas        | [4F1CAE64B4](<Notebook/ASUSTek Computer/G73/G73Jh/A82E379AD538/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/4F1CAE64B4>) |
| 05e3:0723 | Genesys Logic    | GL827L SD/MMC/MS Flash Card Reader   | 298   | usb_sto... | [C447074D2B](<Notebook/Others/Others/Others/11A6F365658A/LINUXMINT-19.3/5.4.0-99-GENERIC/X86_64/C447074D2B>) |
| 058f:9360 | Alcor Micro      | 8-in-1 Media Card Reader             | 289   | uas, us... | [08DA43BE7F](<Desktop/ASRock/P43/P43DE/CF9CAC13052E/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/08DA43BE7F>) |
| 0bda:0181 | Realtek Semic... | MS/MS-Pro/HG                         | 288   | uas, us... | [02B86C4D66](<Desktop/Dell/OptiPlex/OptiPlex 760/7ABFAD006548/OPENSUSE-20220227/5.16.11-1-DEFAULT/X86_64/02B86C4D66>) |
| 14cd:1212 | Super Top        | microSD card reader (SY-T18)         | 287   | uas, us... | [B27D8C8724](<Notebook/Apple/MacBookPro11/MacBookPro11,4/67C61AAA3F88/PARROT-5.0/5.14.0-9PARROT1-AMD64/X86_64/B27D8C8724>) |
| 13fe:5500 | Kingston Tech... | Patriot Memory                       | 283   | uas, us... | [30FF404B05](<Desktop/ASRock/FM2/FM2A68M-HD+/152ABEB9848B/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/30FF404B05>) |
| 0bda:0177 | Realtek Semic... | USB2.0-CRW                           | 276   | ums_rea... | [84BC5F3382](<Convertible/Acer/Spin/Spin SP314-54N/1F529A73EE54/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/84BC5F3382>) |
| 0bda:0328 | Realtek Semic... | SD/MMC CRW                           | 269   | uas, us... | [41C5B09AA4](<Convertible/Dell/Latitude/Latitude 7389/65E58898D2C3/WINDOWSFX-11/5.13.0-27-GENERIC/X86_64/41C5B09AA4>) |
| 058f:6377 | Alcor Micro      | AU6375 4-LUN card reader             | 259   | uas, us... | [5FB853C510](<Desktop/MSI/MS/MS-7823/6F80EE4A14BE/ZORIN-16/5.13.0-30-GENERIC/X86_64/5FB853C510>) |
| 1058:25a2 | Western Digit... | Elements 25A2                        | 255   | uas, us... | [12459FC7EA](<Desktop/ASRock/B450M/B450M Pro4/8ACBABADFDE3/ELEMENTARY-6.1/5.13.0-35-GENERIC/X86_64/12459FC7EA>) |
| 14cd:6116 | Super Top        | M6116 SATA Bridge                    | 247   | uas, us... | [47099A8C6C](<Notebook/Medion/E/E6228/11ECFFA666E6/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/47099A8C6C>) |

### Dvb card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:2838 | Realtek Semic... | RTL2838 DVB-T                        | 248   | dvb_usb... | [0A534CF272](<Desktop/ASRock/H110M-DGS/H110M-DGS R3.0/64B1432E50B0/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0A534CF272>) |
| 07ca:a309 | AVerMedia Tec... | AVerTV DVB-T (A309)                  | 37    | dvb_usb... | [38D3A28768](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv5/A91AD53AE9F4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/38D3A28768>) |
| 0bda:2832 | Realtek Semic... | RTL2832U DVB-T                       | 24    | dvb_usb... | [B14B8A40EC](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/EFF5D66858B6/ARCO-ROLLING/5.10.84-1-LTS/X86_64/B14B8A40EC>) |
| 15f4:0131 | HanfTek          | Astrometa DVB-T/T2/C FM & DAB rec... | 16    | dvb_usb... | [010E56531A](<Desktop/ASRock/H81/H81M-HDS/BC437A41F75F/LINUXMINT-19.3/5.6.17-050617-GENERIC/X86_64/010E56531A>) |
| 048d:9135 | Integrated Te... | Zolid Mini DVB-T Stick               | 15    | dvb_usb... | [872772F278](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-A/6A9CCC297928/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/872772F278>) |
| 07ca:1336 | AVerMedia Tec... | A336 MiniCard Hybrid DVB-T           | 14    |            | [141F5642FC](<All In One/Acer/Aspire/Aspire Z5610/93F4A5EF8D69/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/141F5642FC>) |
| 1164:1f08 | YUAN High-Tec... | STK7700D                             | 12    | dvb_usb... | [7904B934A4](<Notebook/ASUSTek Computer/G71/G71V/E38FEEE17954/FEDORA-35/5.14.0-60.FC35.X86_64/X86_64/7904B934A4>) |
| 15a4:9016 | Afatech          | AF9015 DVB-T USB2.0 stick            | 12    | dvb_usb... | [CA26AE6FF8](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8460p/97924DD3D7BF/LINUXMINT-19.3/4.15.0-159-GENERIC/X86_64/CA26AE6FF8>) |
| 0572:c688 | Conexant Systems | Geniatech T230 DVB-T2 TV Stick       | 11    | dvb_usb... | [7DDECFD5B6](<Desktop/Gigabyte Technology/B360/B360M-D2V/17BA41366A4F/ARCH/5.16.10-ARCH1-1/X86_64/7DDECFD5B6>) |
| 07ca:1871 | AVerMedia Tec... | TD310 DVB-T/T2/C dongle              | 10    | dvb_usb... | [038E9B79EF](<Desktop/ASUSTek Computer/PRIME/PRIME B360M-A/AFA9473151CA/LINUXMINT-20.1/5.4.0-100-GENERIC/X86_64/038E9B79EF>) |
| 07ca:a310 | AVerMedia Tec... | A310                                 | 10    | dvb_usb... | [61E120F622](<Notebook/Acer/Aspire/Aspire 7720G/C94DFFBAE145/DEBIAN-11/5.10.0-6-AMD64/X86_64/61E120F622>) |
| 1d19:1101 | Dexatek Techn... | DK DVB-T Dongle                      | 10    | dvb_usb... | [9AA2FF4CA2](<Desktop/ASUSTek Computer/M2/M2A-MX/A18D5F85321C/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/9AA2FF4CA2>) |
| 1f4d:c803 | G-Tek Electro... | NotOnlyTV (Lifeview) LV5TDLX DVB-... | 10    | dvb_usb... | [89FF5AF60E](<Notebook/HUAWEI/BOHB-WAX/BOHB-WAX9/C90742BFA2D9/UBUNTU-20.04/5.13.0-1008-INTEL/X86_64/89FF5AF60E>) |
| 2304:0237 | Pinnacle Systems | PCTV 73e [DiBcom DiB7000PC]          | 10    | dvb_usb... | [A85B460D7A](<Desktop/Gigabyte Technology/B85/B85M-D3H/05105A9902CF/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/A85B460D7A>) |
| 048d:9005 | Integrated Te... | DVB-T TV Stick                       | 9     | dvb_usb... | [CD0C65171A](<Desktop/Dell/OptiPlex/OptiPlex 990/944CF24FDC91/LINUXMINT-19.1/4.15.0-163-GENERIC/I686/CD0C65171A>) |
| 2040:7070 | Hauppauge        | Nova-T Stick 3                       | 8     | dvb_usb... | [0D964B5339](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/139716A7F3B1/LINUXMINT-20.1/5.4.0-73-GENERIC/X86_64/0D964B5339>) |
| 07ca:0831 | AVerMedia Tec... | H831 USB Hybrid DVB-T/T2             | 6     |            | [9257745E1C](<Notebook/Acer/Aspire/Aspire V5-572G/8F3208F4A590/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/9257745E1C>) |
| 187f:0202 | Siano Mobile ... | Nice                                 | 6     | smsusb     | [110C37E799](<Desktop/Hewlett-Packard/xw8600/xw8600 Workstation/8FD875414A07/ZORIN-16/5.11.0-38-GENERIC/X86_64/110C37E799>) |
| 0572:0320 | Conexant Systems | DVBSky T330 DVB-T2/C tuner           | 5     | dvb_usb... | [757746E097](<Notebook/Dell/Latitude/Latitude E5440/B5B590620A95/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/757746E097>) |
| 07ca:1334 | AVerMedia Tec... | H334 MiniCard Hybrid DVB-T           | 5     |            | [5E45DDC465](<All In One/Lenovo/A740/A740 F0AM/FD905B8098E4/UBUNTU-20.04/5.11.0-25-GENERIC/X86_64/5E45DDC465>) |
| 07ca:a373 | AVerMedia Tec... | A373                                 | 5     |            | [520A9BC6A0](<All In One/Acer/Aspire/Aspire ZS600/307894E2C20C/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/520A9BC6A0>) |
| 07ca:a835 | AVerMedia Tec... | A835                                 | 5     | dvb_usb... | [B7DF25BA5D](<Desktop/MSI/MS-7/MS-7C52/B426A26950C3/SLACKWARE-15.0/5.13.12/X86_64/B7DF25BA5D>) |
| 0ccd:0038 | TerraTec Elec... | Cinergy TÃ‚Â² DVB-T Receiver         | 5     | dvb_usb... | [A29FC046A6](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450-PLUS II/356BEB3DCDB4/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/A29FC046A6>) |
| 2040:9580 | Hauppauge        | NovaT 500Stick                       | 5     | dvb_usb... | [E1FFF3ADE4](<Desktop/Hewlett-Packard/Compaq/Compaq dx2450 Microtower PC/95D9E25A8E92/MANJARO-21.0/5.11.6-1-MANJARO/X86_64/E1FFF3ADE4>) |
| 07ca:0830 | AVerMedia Tec... | H830 USB Hybrid DVB-T                | 4     |            | [79A097BF6F](<Desktop/Gigabyte Technology/X48/X48-DS5/C5305DDA638D/UBUNTU-18.04/4.15.0-47-GENERIC/X86_64/79A097BF6F>) |
| 07ca:1835 | AVerMedia Tec... | A835B                                | 4     | dvb_usb... | [44857FE932](<System On Chip/Others/Others/Others/7F1F3D0DAB2B/RASPBIAN-10/5.4.51-V7+/ARMV7L/44857FE932>) |
| 07ca:850a | AVerMedia Tec... | AverTV Volar Black HD (A850)         | 4     | dvb_usb... | [8AB143EC6B](<Desktop/ASUSTek Computer/P5Q/P5Q DELUXE/211EE5BEF015/LMDE-4/4.19.0-16-AMD64/X86_64/8AB143EC6B>) |
| 1164:0871 | YUAN High-Tec... | STK7700D                             | 4     | dvb_usb... | [EE2674AD2E](<Notebook/Toshiba/Satellite/Satellite P750/66BEBE8FFED1/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/EE2674AD2E>) |
| 1164:3edc | YUAN High-Tec... | STK7700D                             | 4     |            | [DF82BB0E17](<All In One/ASUSTek Computer/ET2011/ET2011A/08966144026E/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/DF82BB0E17>) |
| 15a4:1001 | Afatech          | AF9015/AF9035 DVB-T stick            | 4     | dvb_usb... | [5F974C11F5](<Desktop/ASRock/4/4CoreDual-VSTA/541AEE339B10/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/5F974C11F5>) |
| 1b80:d393 | Afatech          | DVB-T receiver [RTL2832U]            | 4     | dvb_usb... | [DE8EB0C2DE](<Notebook/Dell/Vostro/Vostro 3560/07C198B5C782/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/DE8EB0C2DE>) |
| 2040:5200 | Hauppauge        | NovaT 500Stick                       | 4     | dvb_usb... | [614AC09D36](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/F8ED80F7E192/FEDORA-34/5.13.9-200.FC34.X86_64/X86_64/614AC09D36>) |
| 2040:7050 | Hauppauge        | Nova-T Stick                         | 4     | dvb_usb... | [F56996AAB6](<Desktop/Gigabyte Technology/X58/X58A-UD3R/4D2C07D9CFD0/UBUNTU-21.10/5.13.0-272202022022-GENERIC/X86_64/F56996AAB6>) |
| 04b4:2102 | Cypress Semic... | EZ-USB FX2                           | 3     | dvb_usb... | [40EE943C1C](<Desktop/ASRock/G31/G31M-VS2/E4CB55304B9A/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/40EE943C1C>) |
| 07ca:a815 | AVerMedia Tec... | AVerTV DVB-T Volar X (A815)          | 3     | dvb_usb... | [E92157B364](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LK/64FE8299E12D/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/E92157B364>) |
| 07ca:a867 | AVerMedia Tec... | AVerTV DVB-T (A867)                  | 3     | dvb_usb... | [AF79E42583](<Desktop/Acer/Aspire/Aspire X5950/F8C1EDA60C7C/UBUNTU-21.10/5.13.0-23-GENERIC/X86_64/AF79E42583>) |
| 13d3:3282 | IMC Networks     | DVB-T + GPS Minicard [RTL2832U]      | 3     |            | [A3EDD93ADA](<Desktop/ASUSTek Computer/ET2700/ET2700I/3BCF057A74B1/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/A3EDD93ADA>) |
| 1f4d:3000 | G-Tek Electro... | USB Stick                            | 3     | dvb_usb... | [8EB4D9E6CE](<Desktop/Dell/Precision/Precision T3600/AD13DC5FD6DD/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/8EB4D9E6CE>) |
| 2040:8400 | Hauppauge        | WinTV Nova-T-500                     | 3     | dvb_usb... | [1F4B756D04](<Desktop/ASUSTek Computer/P7/P7H55-USB3/2CEAF10E15E5/LINUXMINT-20.2/5.4.0-94-GENERIC/X86_64/1F4B756D04>) |
| 0413:6029 | Leadtek Research | WinFast DTV Dongle Gold              | 2     | dvb_usb... | [614DBAA6D1](<Desktop/Gigabyte Technology/B85/B85M-D2V/4867F54E230D/KDE-NEON-18.04/5.3.0-28-GENERIC/X86_64/614DBAA6D1>) |
| 04b4:861f | Cypress Semic... | Anysee E30 USB 2.0 DVB-T Receiver    | 2     | dvb_usb... | [040550CDAA](<Desktop/Gigabyte Technology/B250/B250M-DS3H/A8D870914ABD/MANJARO/5.15.19-1-MANJARO/X86_64/040550CDAA>) |
| 04ca:f000 | Lite-On Techn... | DVB Card                             | 2     | dvb_usb... | [7225AECEFF](<Notebook/Toshiba/Satellite/Satellite P850/F79358A2F822/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/7225AECEFF>) |
| 04ca:f01c | Lite-On Techn... | TT1280DA DVB-T TV Tuner              | 2     |            | [24FF3CF596](<Notebook/Acer/Aspire/Aspire 8940G/3EB6F0C4396B/ZORIN-16/5.11.0-25-GENERIC/X86_64/24FF3CF596>) |
| 0572:c689 | Conexant Systems | EyeTV Stick                          | 2     | dvb_usb... | [D47493ECAE](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-A/5751A395EDAB/ELEMENTARY-5.1.7/5.4.0-53-GENERIC/X86_64/D47493ECAE>) |
| 07ca:0335 | AVerMedia Tec... | H335                                 | 2     | dvb_usb... | [0362E43257](<All In One/Packard Bell/ONETWO/ONETWO L5871/D9CDC409CC4E/POP!_OS-20.10/5.11.0-7614-GENERIC/X86_64/0362E43257>) |
| 07ca:0810 | AVerMedia Tec... | H810 USB Hybrid DVB-T                | 2     |            | [B46F2FEE35](<Notebook/ASUSTek Computer/E403/E403NA/E3A7CFB90011/FEDORA-29/4.18.3-300.FC29.X86_64/X86_64/B46F2FEE35>) |
| 07ca:1335 | AVerMedia Tec... | H335C                                | 2     |            | [81D55608B8](<Desktop/Hewlett-Packard/23/23-d101e1/EACC0394BAA7/UBUNTU-20.04/5.8.0-32-GENERIC/X86_64/81D55608B8>) |
| 0ccd:0064 | TerraTec Elec... | DVB Card                             | 2     | dvb_usb... | [BA214D2A0B](<Desktop/ASUSTek Computer/P5B-PLUS/P5B-PLUS Series/E98A7F6B8CC6/LINUXMINT-19.1/4.15.0-126-GENERIC/X86_64/BA214D2A0B>) |
| 1044:7002 | Chu Yuen Ente... | Gigabyte U8000 DVB-T tuner           | 2     | dvb_usb... | [57DE891506](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3CD636B21316/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/57DE891506>) |
| 1415:0003 | Nam Tai E&E P... | SCEH-0036                            | 2     | dvb_usb... | [F2536AC0FF](<Desktop/ASUSTek Computer/P5/P5E/484AFE9B8835/LINUXMINT-20.2/5.4.0-81-LOWLATENCY/X86_64/F2536AC0FF>) |

### Fingerprint reader (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 06cb:00bd | Synaptics        | Prometheus MIS Touch Fingerprint ... | 1021  | usbfs      | [1F4FADBE2E](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Nano Gen 1 20UN002PCK/C35BF89AA0CF/ARCO-ROLLING/5.16.13-ZEN1-1-ZEN/X86_64/1F4FADBE2E>) |
| 138a:003f | Validity Sensors | VFS495 Fingerprint Reader            | 1003  | usbfs      | [3ECBD85311](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G2/8D1B4AD5F2F1/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/3ECBD85311>) |
| 138a:0011 | Validity Sensors | VFS5011 Fingerprint Reader           | 548   | usbfs      | [25951F4351](<Notebook/Dell/Vostro/Vostro 3550/864BFB5EE573/ZORIN-16/5.13.0-30-GENERIC/X86_64/25951F4351>) |
| 138a:0017 | Validity Sensors | VFS 5011 fingerprint sensor          | 523   | usbfs      | [841857DD45](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FN002SUS/5BCAE155A7D7/LINUXMINT-20.2/5.13.0-27-GENERIC/X86_64/841857DD45>) |
| 147e:2016 | Upek             | Biometric Touchchip/Touchstrip Fi... | 494   | usbfs      | [B1A7B4593A](<Notebook/Lenovo/ThinkPad/ThinkPad X201 3680DQ1/C51F9D078D98/UBUNTU-20.04/5.16.12-051612-GENERIC/X86_64/B1A7B4593A>) |
| 06cb:009a | Synaptics        | Metallica MIS Touch Fingerprint R... | 438   | usbfs      | [755854F7D4](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5A07TAU/0D8B48BD5BBE/ORACLESERVER-8.5/5.4.17-2136.304.4.3.EL8UEK.X86_64/X86_64/755854F7D4>) |
| 138a:0018 | Validity Sensors | Fingerprint scanner                  | 367   |            | [708BC5F491](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/DEA8D34C9EEA/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/708BC5F491>) |
| 08ff:2810 | AuthenTec        | AES2810                              | 346   | usbfs      | [AC28CDA346](<Notebook/Lenovo/ThinkPad/ThinkPad X200 7459N40/B1C498DEDE05/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/AC28CDA346>) |
| 138a:003c | Validity Sensors | VFS471 Fingerprint Reader            | 339   | usbfs      | [42020405AB](<Notebook/Hewlett-Packard/ProBook/ProBook 6560b/F155064A9FED/LINUXMINT-20/5.4.0-100-GENERIC/X86_64/42020405AB>) |
| 138a:003d | Validity Sensors | VFS491                               | 331   | usbfs      | [354C365696](<Notebook/Hewlett-Packard/EliteBook/EliteBook Folio 9480m/E002B40E424E/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/354C365696>) |
| 06cb:0081 | Synaptics        | Synaptics WBDI                       | 317   |            | [3BC582AD91](<Notebook/Lenovo/V330-15IKB/V330-15IKB 81AX/FAA914D05210/MANJARO-21.2.3/5.10.98-1-MANJARO/X86_64/3BC582AD91>) |
| 1c7a:0570 | LighTuning Te... | EgisTec Touch Fingerprint Sensor     | 314   |            | [23C2A93047](<Notebook/HONOR/BMH-WCX/BMH-WCX9/19886291EEA7/DEBIAN-11/5.15.0-2-AMD64/X86_64/23C2A93047>) |
| 27c6:533c | Shenzhen Good... | FingerPrint                          | 302   | usbfs      | [7D27557EBE](<Notebook/Dell/XPS/XPS 15 9500/3F35783A65E6/UBUNTU-21.10/5.13.0-27-GENERIC/X86_64/7D27557EBE>) |
| 08ff:2580 | AuthenTec        | AES2501 Fingerprint Sensor           | 299   |            | [55A6D982B3](<Notebook/Hewlett-Packard/Compaq/Compaq nw8440/341816537142/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/55A6D982B3>) |
| 04f3:0903 | Elan Microele... | ELAN:Fingerprint                     | 284   | usbfs      | [86DC3583CA](<Notebook/ASUSTek Computer/UX430/UX430UNR/F0783EEF957D/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/86DC3583CA>) |
| 0483:2016 | STMicroelectr... | Fingerprint Reader                   | 283   | usbfs      | [B00D789D5D](<Notebook/Lenovo/ThinkPad/ThinkPad T61 64659TU/A51B35E96C9E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B00D789D5D>) |
| 27c6:55b4 | Shenzhen Good... | Fingerprint Reader                   | 263   | usbfs      | [3617D41378](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 15ALC05 82HV/BFC66FC359C3/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/3617D41378>) |
| 138a:0007 | Validity Sensors | VFS451 Fingerprint Reader            | 255   | usbfs      | [CAF1F719F4](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8440p/725B6221FBB1/BUNSENLABS-10.5/4.19.0-18-AMD64/X86_64/CAF1F719F4>) |
| 138a:0097 | Validity Sensors | Synaptics WBDI                       | 243   | usbfs      | [C781FC668F](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20HNS0LW00/E03394933E2B/XUBUNTU-18.04/5.4.0-99-GENERIC/X86_64/C781FC668F>) |
| 27c6:55a4 | Shenzhen Good... | Goodix FingerPrint Device            | 236   |            | [B48A6240BF](<Notebook/Lenovo/ThinkPad/ThinkPad E15 20RD0016GE/4F4BEFFC091C/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/B48A6240BF>) |
| 06cb:00be | Synaptics        |                                      | 232   |            | [D6D94816FC](<Convertible/Lenovo/Yoga/Yoga C940-14IIL 81Q9/8BFCF89EE199/GENTOO-2.6/5.15.11-GENTOO-X86_64/X86_64/D6D94816FC>) |
| 06cb:00b7 | Synaptics        | Synaptics VFS7552 Touch Fingerpri... | 226   |            | [42921AEBFD](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G6/A8B5AAF45EC2/UBUNTU-BUDGIE-21.10/5.13.0-35-GENERIC/X86_64/42921AEBFD>) |
| 06cb:00a2 | Synaptics        | Metallica MOH Touch Fingerprint R... | 213   |            | [2F136D5BF5](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN002YPH/61077ED80EDE/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/2F136D5BF5>) |
| 27c6:5110 | Shenzhen Good... | Goodix Fingerprint Device            | 211   |            | [2B1AC5C4F4](<Notebook/HUAWEI/BOHK-WAX9/BOHK-WAX9X/F1FF0FAF7B7F/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/2B1AC5C4F4>) |
| 138a:0090 | Validity Sensors | VFS7500 Touch Fingerprint Sensor     | 210   | usbfs      | [566EEE23F5](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Carbon 4th 20FRS08T00/3A0B7992B26B/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/566EEE23F5>) |
| 147e:1002 | Upek             | Biometric Touchchip/Touchstrip Fi... | 204   |            | [08E970FD6C](<Notebook/Clevo/P15/P15xEMx/EF53301D5ED0/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/08E970FD6C>) |
| 138a:0050 | Validity Sensors | Swipe Fingerprint Sensor             | 202   | usbfs      | [C2305ED449](<Notebook/Hewlett-Packard/ENVY/ENVY TS 15/007DD8904C2D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/C2305ED449>) |
| 08ff:1600 | AuthenTec        | AES1600                              | 196   |            | [CE6005769A](<Notebook/Medion/WIM/WIM2140/EDECB8B33C5A/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/CE6005769A>) |
| 138a:00ab | Validity Sensors | Synaptics VFS7552 Touch Fingerpri... | 194   |            | [AB88A095AC](<Notebook/Hewlett-Packard/EliteBook/EliteBook 850 G5/0EF543DE53BD/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/AB88A095AC>) |
| 06cb:00df | Synaptics        | Synaptics FS7604 Touch Fingerprin... | 172   | usbfs      | [917A6B65A8](<Notebook/Hewlett-Packard/ZBook/ZBook Fury 15 G7 Mobile Workstation/37F95CCCBE32/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/917A6B65A8>) |
| 1c7a:0603 | LighTuning Te... | EgisTec_ES603                        | 170   | usbfs      | [D782BEA38A](<Notebook/Getac/B300/B300G5/D37A392C328B/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/D782BEA38A>) |
| 06cb:00c9 | Synaptics        |                                      | 141   | usbfs      | [C2633CA615](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-dr1xxx/A04C0388CF0E/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/C2633CA615>) |
| 138a:0005 | Validity Sensors | VFS301 Fingerprint Reader            | 136   |            | [D04802B99E](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/E7F94FDB9327/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D04802B99E>) |
| 138a:0001 | Validity Sensors | VFS101 Fingerprint Reader            | 125   |            | [A6788BFE93](<Notebook/Hewlett-Packard/HDX/HDX18/B6E6008E29E1/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/A6788BFE93>) |
| 06cb:009b | Synaptics        |                                      | 114   |            | [20757CC7E0](<Notebook/MSI/Prestige/Prestige 15 A11SCS/C4124BB337A8/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/20757CC7E0>) |
| 147e:1000 | Upek             | Biometric Touchchip/Touchstrip Fi... | 108   |            | [D3465ABE44](<Notebook/Sony/VGN-Z690/VGN-Z690N/C7EACBA309C4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D3465ABE44>) |
| 1c7a:0801 | LighTuning Te... | Fingerprint Reader                   | 106   |            | [B7E82C9025](<Notebook/Acer/Aspire/Aspire 8943G/D311E289CC71/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/B7E82C9025>) |
| 27c6:55a2 | Shenzhen Good... | Goodix FingerPrint Device            | 106   |            | [1EAA06BF11](<Notebook/Lenovo/Yoga/Yoga Slim 7 15IIL05 82AA/F9B567DBF8D7/OPENSUSE-20220304/5.16.8-1-DEFAULT/X86_64/1EAA06BF11>) |
| 04f3:0c03 | Elan Microele... | ELAN:Fingerprint                     | 94    |            | [5765E1B103](<Notebook/Acer/Aspire/Aspire A514-53/3D99719304A6/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5765E1B103>) |
| 138a:0091 | Validity Sensors | VFS7552 Touch Fingerprint Sensor     | 90    |            | [4C72EBCB41](<Notebook/Dell/XPS/XPS 15 9560/F843245F97BA/KUBUNTU-20.04/5.13.0-30-GENERIC/X86_64/4C72EBCB41>) |
| 04f3:0c1a | Elan Microele... | ELAN:Fingerprint                     | 82    | usbfs      | [F9A954EEA3](<Notebook/Timi/TM/TM1703/017E7F3CEDFF/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/F9A954EEA3>) |
| 138a:0010 | Validity Sensors | VFS Fingerprint sensor               | 81    |            | [2DF54EF02E](<Notebook/ASUSTek Computer/BU401/BU401LA/8150F1E3711A/DEBIAN-11/5.10.0-10-AMD64/X86_64/2DF54EF02E>) |
| 27c6:530c | Shenzhen Good... | Fingerprint Reader                   | 74    |            | [9001CCACBC](<Notebook/Dell/G3/G3 3500/FC55ABC42E02/ARCH-ROLLING/5.16.7-ARCH1-1/X86_64/9001CCACBC>) |
| 06cb:0078 | Synaptics        | WBDI Device                          | 69    |            | [7C9F5C83CF](<Notebook/System76/Oryx/Oryx Pro/DE0C4B888206/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/7C9F5C83CF>) |
| 27c6:538c | Shenzhen Good... | Fingerprint Reader                   | 69    |            | [17584AE0E4](<Convertible/Dell/Inspiron/Inspiron 5482/99CE6490B4AE/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/17584AE0E4>) |
| 27c6:5117 | Shenzhen Good... | Fingerprint Reader                   | 68    |            | [C2DE0E3F1C](<Notebook/HONOR/HLYL-WXX/HLYL-WXX9/76B6CD26EF9D/LINUXMINT-20.3/5.16.6-051606-GENERIC/X86_64/C2DE0E3F1C>) |
| 06cb:00c7 | Synaptics        |                                      | 64    |            | [D36E30FA5B](<Notebook/System76/Oryx/Oryx Pro/2E17FD71D927/ARCO-ROLLING/5.16.12-ARCH1-1/X86_64/D36E30FA5B>) |
| 08ff:168f | AuthenTec        | AES1660 Fingerprint Sensor           | 64    | usbfs      | [64DC07D0AF](<Notebook/Sony/SVS1311/SVS13118GBB/F65894F76BAC/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/64DC07D0AF>) |
| 147e:1001 | Upek             | TCS5B Fingerprint sensor             | 63    |            | [1F9694D47D](<Notebook/Lenovo/ThinkPad/ThinkPad Edge 0301FAG/9A32EE6F60AB/LUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/1F9694D47D>) |
| 06cb:00a8 | Synaptics        |                                      | 61    | usbfs      | [00B59D57B7](<Notebook/Notebook/PCx0/PCx0Dx/F6BE0CE248E0/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/00B59D57B7>) |

### Floppy (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 059b:0030 | Iomega           | Zip 250 (Ver 1)                      | 3     | uas, us... | [BFE2966C97](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da0xxx/CF4825367441/UBUNTU-20.04/5.4.0-73-GENERIC/X86_64/BFE2966C97>) |
| 059b:0001 | Iomega           | Zip 100 (Type 1)                     | 2     | usb_sto... | [C59A1FFF0D](<All In One/Apple/iMac13/iMac13,2/D0AC600AD6CB/ZORIN-16/5.11.0-27-GENERIC/X86_64/C59A1FFF0D>) |
| 059b:0033 | Iomega           | ZIP 100                              | 2     | uas, us... | [F0912110EB](<Desktop/Hewlett-Packard/Compaq/Compaq dc5850 Small Form Factor/EED5FB81E710/FEDORA-34/5.11.16-300.FC34.X86_64/X86_64/F0912110EB>) |
| 059b:0031 | Iomega           | Zip 100 (Type 3)                     | 1     | uas, us... | [1ED8284AB4](<Desktop/Gigabyte Technology/970/970A-DS3P/5F4A991B9691/UBUNTU-20.04/5.8.0-41-GENERIC/X86_64/1ED8284AB4>) |
| 059b:0034 | Iomega           | Zip 100 Driver                       | 1     | usb_sto... | [506F4A7C1D](<Desktop/Gigabyte Technology/B75/B75M-D3H/1CD73ECC584C/LINUXMINT-19.1/4.15.0-47-GENERIC/X86_64/506F4A7C1D>) |
| 059b:0035 | Iomega           | ZIP 750                              | 1     | usb_sto... | [87C89614B1](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD04/AF3EA48DA0B8/LINUXMINT-20.2/5.11.0-37-GENERIC/X86_64/87C89614B1>) |
| 13fe:1e20 | Kingston Tech... | USB DISK Pro                         | 1     | uas, us... | [8902B96F21](<Desktop/ASRock/970M/970M Pro3/DC46E5B8C22B/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/8902B96F21>) |

### Gamepad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:028e | Microsoft        | Xbox360 Controller                   | 571   | xpad       | [4A89454909](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/A7B435E0E41E/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/4A89454909>) |
| 046d:c21d | Logitech         | F310 Gamepad [XInput Mode]           | 108   | xpad       | [6F9489B2E6](<Desktop/EVGA/X299/X299 FTW K/E0352CDBA41D/NIXOS-21.11/5.10.102/X86_64/6F9489B2E6>) |
| 046d:c21f | Logitech         | F710 Wireless Gamepad [XInput Mode]  | 102   | xpad       | [5C169A1D32](<Desktop/Gigabyte Technology/H110/H110M-H-CF/ECE185D878D5/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/5C169A1D32>) |
| 045e:0291 | Microsoft        | Xbox 360 Wireless Receiver for Wi... | 74    | xpad       | [A36352A738](<Desktop/MSI/MS-7/MS-7C35/C7349768E120/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/A36352A738>) |
| 0079:0011 | DragonRise       | Gamepad                              | 43    | usbhid     | [5597750B89](<Notebook/Acer/Aspire/Aspire E5-553G/38F72A113349/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/5597750B89>) |
| 2563:0575 | ShenZhen Shan... | ZD-V+ Wired Gaming Controller        | 43    | usbhid     | [01D3E72FE4](<Desktop/ASRock/B75/B75M-DGS/4BDE514875F8/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/01D3E72FE4>) |
| 0e8f:0003 | GreenAsia        | MaxFire Blaze2                       | 28    | usbhid     | [FD04C0293F](<Desktop/ASUSTek Computer/P8/P8B75-V/0F74E3D43E36/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FD04C0293F>) |
| 0079:181c | DragonRise       | TGZ Controller                       | 16    | usbhid     | [42CBFE4EE6](<Notebook/Lenovo/IdeaPad/IdeaPad 5 15IIL05 81YK/EEF79161C8E1/MANJARO-21.2.3/5.15.21-1-MANJARO/X86_64/42CBFE4EE6>) |
| 0810:e501 | Personal Comm... | SNES Gamepad                         | 16    | usbhid     | [B9BEC9D182](<Desktop/ASUSTek Computer/M4A87TD/M4A87TD EVO/E0F3A8DB25AE/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/B9BEC9D182>) |
| 0e6f:0213 | Logic3           | Afterglow Gamepad for Xbox 360       | 10    | xpad       | [7F28B8E845](<Desktop/ASUSTek Computer/M5A97/M5A97 PLUS/53E018DF5222/LINUXMINT-20.3/5.4.0-94-GENERIC/X86_64/7F28B8E845>) |
| 046d:c21e | Logitech         | F510 Gamepad [XInput Mode]           | 8     | xpad       | [4CF62D2B87](<Desktop/Intel/DH67CL/DH67CL AAG10212-210/1226CF32B431/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/4CF62D2B87>) |
| 0583:a000 | Padix (Rockfire) | MaxFire G-08XU Gamepad               | 7     | usbhid     | [DA1F0D65EC](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75e 5065A11/D1F33BDDA84A/UBUNTU-MATE-21.04/5.11.0-24-GENERIC/X86_64/DA1F0D65EC>) |
| 0e6f:011f | Logic3           | Rock Candy Wired Controller for X... | 7     | xpad       | [E41DA0FB5E](<Desktop/ASRock/FM2A88X/FM2A88X Pro3+/873F5EE17BDF/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/E41DA0FB5E>) |
| 0e6f:0413 | Logic3           | Afterglow AX.1 Gamepad for Xbox 360  | 7     | xpad       | [4899DD71F5](<Desktop/MSI/MS-7/MS-7A57/C9436D17A162/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/4899DD71F5>) |
| 0e8f:0008 | GreenAsia        | PS Gamepad                           | 5     | usbhid     | [6D7EAF124E](<Desktop/ASUSTek Computer/M5A97/M5A97 EVO R2.0/97D6FE0803E5/UBUNTU-18.04/5.3.0-26-GENERIC/X86_64/6D7EAF124E>) |
| 0e8f:0012 | GreenAsia        | Joystick/Gamepad                     | 5     | usbhid     | [56A1BC8E09](<Desktop/ASRock/B450/B450 Gaming-ITX-ac/8258D1EAD6E4/UBUNTU-20.10/5.8.0-53-GENERIC/X86_64/56A1BC8E09>) |
| 145f:01c5 | Trust            | Gamepad                              | 5     | usbhid     | [93A093110A](<Desktop/ASUSTek Computer/All/All Series/180F9B80D6FF/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/93A093110A>) |
| 046d:c242 | Logitech         | XUSB Gamepad                         | 4     | usbfs      | [333F34E356](<Desktop/Lenovo/ThinkCentre/ThinkCentre Edge72 3484DBG/A8FE82E68CBF/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/333F34E356>) |
| 0e8f:310d | GreenAsia        | USB Controller                       | 4     | usbhid     | [0962B3B7B4](<Desktop/Megaware/G41/G41T-M7/155FD3A2FF00/ENDLESS-4.0.2/5.11.0-35-GENERIC/X86_64/0962B3B7B4>) |
| 1345:6006 | Sino Lite Tec... | Defender Wireless Controller         | 4     |            | [1A9077AB60](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 R2/ED33D8263F9F/DEBIAN-10/4.19.0-8-AMD64/X86_64/1A9077AB60>) |
| 7545:1122 | SZ-MYPOWER       | PC Gamepad                           | 4     | usbhid     | [77513A0FE5](<Desktop/Fujitsu/CELSIUS/CELSIUS R570-2/2D827C2A5C9A/UBUNTU-21.04/5.11.0-22-GENERIC/X86_64/77513A0FE5>) |
| 07b5:0213 | Mega World In... | Thrustmaster Firestorm Digital 3 ... | 3     | usbhid     | [70271C9802](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D09F0E5D5CED/UBUNTU-21.10/5.13.0-1016-RASPI/AARCH64/70271C9802>) |
| 0e6f:0201 | Logic3           | TSZ360 Pad                           | 3     | xpad       | [048B7BCF6A](<Desktop/ABIT/I-G/I-G31/AFE1ED3BF69C/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/048B7BCF6A>) |
| 145f:0231 | Trust            | USB Gamepad                          | 3     | usbhid     | [A72E3CC74F](<Desktop/ASRock/X399/X399 Taichi/DBB64A12814D/ARCH/5.8.14-ARCH1-1/X86_64/A72E3CC74F>) |
| 146b:5500 | BigBen Intera... | Usb Gamepad                          | 3     | usbhid     | [AB62777CB6](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P720/FFF12BD3239C/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/AB62777CB6>) |
| 1bad:fa01 | Harmonix Music   | Gamepad                              | 3     | xpad       | [4AA6A34C0C](<Notebook/Samsung Electronics/RC530/RC530-RC730/AE11140B6A56/GENTOO-2.6/5.4.80-GENTOO-R1/X86_64/4AA6A34C0C>) |
| 24c6:5b02 | ThrustMaster     | GPX Controller                       | 3     | xpad       | [653E8EDAB3](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/D7C334EEC193/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/653E8EDAB3>) |
| 050d:0805 | Belkin Compon... | Nostromo N50 GamePad                 | 2     | usbhid     | [285B5B2D08](<Desktop/Gigabyte Technology/B450M/B450M S2H/1A51DBD9A55B/KUBUNTU-20.10/5.8.0-44-GENERIC/X86_64/285B5B2D08>) |
| 07b5:0312 | Mega World In... | Gamepad                              | 2     | usbhid     | [A4A0A9E165](<Desktop/Hewlett-Packard/GZ679AA-ABF/GZ679AA-ABF a6295.fr/9E4431E4B2E5/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/A4A0A9E165>) |
| 0e6f:011e | Logic3           | Rock Candy Gamepad for PS3           | 2     | usbhid     | [82ABA65015](<Notebook/Dell/Inspiron/Inspiron 3593/BFE606D4F6F4/MANJARO/5.10.0-1-MANJARO/X86_64/82ABA65015>) |
| 0e6f:f501 | Logic3           | Hi-TEC Essentials Wired Gamepad      | 2     | xpad       | [487957580F](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-E GAMING/5F5CF432ED26/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/487957580F>) |
| 0e8f:3013 | GreenAsia        | USB GamePad                          | 2     | usbhid     | [35801F40DF](<Desktop/Gigabyte Technology/B550/B550 AORUS PRO/654005523A04/FEDORA-35/5.14.18-300.FC35.X86_64/X86_64/35801F40DF>) |
| 11c9:55f0 | HJC Game         | GAMEPAD                              | 2     | usbhid     | [FE1D48F6CC](<Desktop/MSI/MS-7/MS-7B86/CC9A290E388C/POP!_OS-20.04/5.4.0-7642-GENERIC/X86_64/FE1D48F6CC>) |
| 1a34:0802 | ACRUX            | Gamepad                              | 2     | usbhid     | [609FFD75B7](<Notebook/Lenovo/B560/B560 43308VG/B3CA7A2AD047/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/609FFD75B7>) |
| 1bad:f016 | Harmonix Music   | MadCatz GamePad                      | 2     | xpad       | [1A37FA7FA6](<Desktop/MSI/MS-7/MS-7B00/1B0C137459F4/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/1A37FA7FA6>) |
| 24c6:fafc | Performance D... | Afterglow Gamepad for Xbox 360       | 2     | xpad       | [F34C588CFE](<Desktop/ASUSTek Computer/M5A99FX/M5A99FX PRO R2.0/BF3065B532AE/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/F34C588CFE>) |
| 2563:058d | ShenZhen Shan... | Cloud Gamepad                        | 2     | xpad       | [B127C7B5E0](<Notebook/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/CEAAC50AC7AB/BUILDROOT-2021.08.1/5.14.12/X86_64/B127C7B5E0>) |
| 7545:0104 | SZ-MYPOWER       | DS4 Wired Controller                 | 2     | usbhid     | [11EB2546C1](<Desktop/Vorke/V1/V1 Plus/5DD9E2EFF86F/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/11EB2546C1>) |
| 0079:1855 | DragonRise       | PS3/PC WirelessGamePad               | 1     | usbhid     | [A76227F148](<Desktop/Gigabyte Technology/B450/B450 AORUS PRO/330B4A607473/UBUNTU-20.04/5.7.2/X86_64/A76227F148>) |
| 0079:954e | DragonRise       | NGC USB Gamepad                      | 1     | usbhid     | [398B45ED60](<Desktop/Dell/OptiPlex/OptiPlex 790/54C6DC6065E9/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/398B45ED60>) |
| 040b:6530 | Weltrend Semi... | USB 2A8K GamePad                     | 1     | usbhid     | [0539EEEEB8](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/CCFE86F30A4D/XUBUNTU-20.04/5.4.0-59-LOWLATENCY/X86_64/0539EEEEB8>) |
| 044f:b326 | ThrustMaster     | GPX Gamepad                          | 1     | xpad       | [3C19F51786](<Desktop/ASUSTek Computer/P5/P5Q-EM/759343D4D1CF/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/3C19F51786>) |
| 045e:0026 | Microsoft        | SideWinder GamePad Pro               | 1     | usbhid     | [F8BFAA2C3D](<Notebook/Acer/Aspire/Aspire ES1-531/DEA928C93DC0/UBUNTU-19.04/5.0.0-34-GENERIC/X86_64/F8BFAA2C3D>) |
| 046d:c208 | Logitech         | WingMan Gamepad Extreme              | 1     | usbhid     | [00B0998670](<Desktop/ASUSTek Computer/M2/M2N-E/598AE60AAC4F/UBUNTU-20.04/5.8.0-40-GENERIC/X86_64/00B0998670>) |
| 06d6:0026 | Aashima Techn... | Predator TH 400 Gamepad              | 1     | usbhid     | [3AFB2CB222](<Desktop/Dell/OptiPlex/OptiPlex 780/3F4F52CED60A/UBUNTU-20.04/5.4.0-37-GENERIC/X86_64/3AFB2CB222>) |
| 0738:4716 | Mad Catz         | MadCatz GamePad                      | 1     | xpad       | [DF679E04AA](<Desktop/MSI/MS-7/MS-7A40/20866AB73D0C/DEBIAN-UNSTABLE/5.6.0-2-AMD64/X86_64/DF679E04AA>) |
| 0810:0005 | Personal Comm... | USB Gamepad                          | 1     | usbhid     | [3BDBF957FA](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/007F13BDFFF0/ROSA-2014.1/4.1.15-NRJ-DESKTOP-1ROSA-X86_64/X86_64/3BDBF957FA>) |
| 0c12:0ef1 | Zeroplus         | P4 Wired GamepadV1.8                 | 1     | usbhid     | [7A316C9F35](<Desktop/PCWare/IPMH61/IPMH61R2/25034AAA4E7E/DEBIAN-10/4.19.0-13-686-PAE/I686/7A316C9F35>) |
| 0e6f:0133 | Logic3           | Wired Controller                     | 1     | xpad       | [F402C60DD9](<Desktop/Gigabyte Technology/970/970A-D3/AB05AFA95250/LINUXMINT-20/5.4.0-52-GENERIC/X86_64/F402C60DD9>) |
| 0e6f:021f | Logic3           | Rock Candy Gamepad for Xbox 360      | 1     | xpad       | [806404C773](<Desktop/Gigabyte Technology/B85/B85-HD3/076DB53099F5/MANJARO/5.14.0-1-MANJARO/X86_64/806404C773>) |

### Hardware key (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0a89:0003 | Aktiv            | Guardant Stealth 2                   | 11    | usbfs      | [EA6139E86C](<Notebook/Lenovo/IdeaPad/IdeaPad 3 17IIL05 81WF/F3EDA25D3B15/FEDORA-35/5.14.16-301.FC35.X86_64/X86_64/EA6139E86C>) |
| 0a89:0020 | Aktiv            | Rutoken S                            | 10    | usbfs      | [B2FA33FC7E](<Desktop/ASUSTek Computer/P8/P8B75-M/CDA98A9A20A1/ROSA-2016.1/4.15.0-DESKTOP-94.1ROSA-X86_64/X86_64/B2FA33FC7E>) |
| 0471:485d | Philips (or NXP) | Senselock SenseIV v2.x               | 5     |            | [658F8F2FD1](<Desktop/ASUSTek Computer/PRIME/PRIME H570-PLUS/66AF7BF339F9/ASTRALINUXSE-1.6/5.4.0-34-GENERIC/X86_64/658F8F2FD1>) |
| 14a8:0001 | Soft protecti... | Soft protection device: USB Prote... | 4     |            | [C933CA0D6F](<Desktop/ASRock/B450M/B450M Pro4/C5BD0782AA9C/DEBIAN-10/5.0.21-4-PVE/X86_64/C933CA0D6F>) |

### Hasp (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0529:0001 | Aladdin Knowl... | HASP copy protection dongle          | 78    | usbfs      | [4F6FE9951A](<Desktop/ASRock/Q370M/Q370M vPro/222B02CEA7A1/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/4F6FE9951A>) |

### Hub (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1d6b:0002 | Linux Foundation | 2.0 root hub                         | 13... | hub        | [2372B12D5C](<Notebook/Dell/Latitude/Latitude 5511/2B9275757CE0/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/2372B12D5C>) |
| 1d6b:0003 | Linux Foundation | 3.0 root hub                         | 92865 | hub        | [2372B12D5C](<Notebook/Dell/Latitude/Latitude 5511/2B9275757CE0/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/2372B12D5C>) |
| 1d6b:0001 | Linux Foundation | 1.1 root hub                         | 38613 | hub        | [37C37094B9](<Desktop/Gigabyte Technology/M61/M61PME-S2P/9DACEC325D22/DEBIAN-11/5.10.0-7-AMD64/X86_64/37C37094B9>) |
| 8087:0024 | Intel            | Integrated Rate Matching Hub         | 22564 | hub        | [F6068483CE](<Notebook/Toshiba/Satellite/Satellite C660/B9B75BA01934/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F6068483CE>) |
| 8087:8000 | Intel            | Integrated Rate Matching Hub         | 9499  | hub        | [2D3F5F0F14](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P720/0940F1E1173B/DEBIAN-11/5.10.0-7-AMD64/X86_64/2D3F5F0F14>) |
| 05e3:0608 | Genesys Logic    | Hub                                  | 8287  | hub        | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 8087:8008 | Intel            | Integrated Rate Matching Hub         | 6347  | hub        | [2D3F5F0F14](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P720/0940F1E1173B/DEBIAN-11/5.10.0-7-AMD64/X86_64/2D3F5F0F14>) |
| 05e3:0610 | Genesys Logic    | Hub                                  | 6194  | hub        | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 8087:0020 | Intel            | Integrated Rate Matching Hub         | 5311  | hub        | [4F1CAE64B4](<Notebook/ASUSTek Computer/G73/G73Jh/A82E379AD538/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/4F1CAE64B4>) |
| 1a40:0101 | Terminus Tech... | Hub                                  | 5104  | hub        | [83A319F258](<Notebook/Dell/Inspiron/Inspiron 1525/E3C6D99D7C40/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/83A319F258>) |
| 8087:8001 | Intel            | Integrated Hub                       | 2835  | hub        | [3ECBD85311](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G2/8D1B4AD5F2F1/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/3ECBD85311>) |
| 0438:7900 | AMD              | Root Hub                             | 2625  | hub        | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 0a5c:4500 | Broadcom         | BCM2046B1 USB 2.0 Hub (part of BC... | 2613  | hub        | [2A4E580BD6](<Notebook/Apple/MacBookPro10/MacBookPro10,1/60A7DE71C92F/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/2A4E580BD6>) |
| 2109:3431 | VIA Labs         | Hub                                  | 2093  | hub        | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 0bda:5411 | Realtek Semic... | 4-Port USB 2.0 Hub                   | 1880  | hub        | [59405132C9](<Desktop/Gigabyte Technology/B660M/B660M AORUS PRO AX DDR4/2FD0EDB99498/UBUNTU-20.04/5.16.13-051613-GENERIC/X86_64/59405132C9>) |
| 0bda:0411 | Realtek Semic... | 2-Port USB 3.0 Hub                   | 1463  | hub        | [59405132C9](<Desktop/Gigabyte Technology/B660M/B660M AORUS PRO AX DDR4/2FD0EDB99498/UBUNTU-20.04/5.16.13-051613-GENERIC/X86_64/59405132C9>) |
| 0424:2514 | Microchip Tec... | USB 2.0 Hub                          | 1311  | hub        | [17B7D9DD0C](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/17B7D9DD0C>) |
| 05e3:0612 | Genesys Logic    | Hub                                  | 1119  | hub        | [3F58A0F2A4](<Notebook/Lenovo/Legion/Legion Y530-15ICH 81FV/A4B769895625/GENTOO-2.6/5.15.23-GENTOO/X86_64/3F58A0F2A4>) |
| 2109:2813 | VIA Labs         | VL813 Hub                            | 1081  | hub        | [CB8AFCB315](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/10C8FEF878C9/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CB8AFCB315>) |
| 2109:2812 | VIA Labs         | VL812 Hub                            | 1034  | hub        | [E7A3D16CC0](<Notebook/Dell/XPS/XPS 13 9310/ABE3F73FC2AC/KUBUNTU-21.04/5.10.0-1038-OEM/X86_64/E7A3D16CC0>) |
| 8087:8009 | Intel            | Hub                                  | 1019  | hub        | [3CBA5D22BC](<Desktop/MSI/MS/MS-7918/9432F9FD1040/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/3CBA5D22BC>) |
| 05e3:0626 | Genesys Logic    | USB3.1 Hub                           | 931   | hub        | [7D27557EBE](<Notebook/Dell/XPS/XPS 15 9500/3F35783A65E6/UBUNTU-21.10/5.13.0-27-GENERIC/X86_64/7D27557EBE>) |
| 2109:2817 | VIA Labs         | USB2.0 Hub                           | 924   | hub        | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 174c:2074 | ASMedia Techn... | ASM1074 High-Speed hub               | 875   | hub        | [2032FBBA77](<Desktop/MSI/MS-7/MS-7C36/075DC59573FF/KUBUNTU-20.04/5.4.0-100-GENERIC/X86_64/2032FBBA77>) |
| 174c:3074 | ASMedia Techn... | ASM1074 SuperSpeed hub               | 861   | hub        | [2032FBBA77](<Desktop/MSI/MS-7/MS-7C36/075DC59573FF/KUBUNTU-20.04/5.4.0-100-GENERIC/X86_64/2032FBBA77>) |
| 2109:0813 | VIA Labs         | VL813 Hub                            | 857   | hub        | [CB8AFCB315](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/10C8FEF878C9/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/CB8AFCB315>) |
| 2109:0812 | VIA Labs         | VL812 Hub                            | 819   | hub        | [E7A3D16CC0](<Notebook/Dell/XPS/XPS 13 9310/ABE3F73FC2AC/KUBUNTU-21.04/5.10.0-1038-OEM/X86_64/E7A3D16CC0>) |
| 2109:0817 | VIA Labs         | USB3.0 Hub                           | 789   | hub        | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 0409:005a | NEC Computers    | HighSpeed Hub                        | 676   | hub        | [4C71606B0A](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/4C71606B0A>) |
| 8087:8002 | Intel            | 8 channel internal hub               | 654   | hub        | [D47819516A](<Desktop/ASRock/X99/X99 Extreme4/1E598F64C524/ARCH-ROLLING/5.16.10-ARCH1-1/X86_64/D47819516A>) |
| 8087:800a | Intel            | Hub                                  | 653   | hub        | [D47819516A](<Desktop/ASRock/X99/X99 Extreme4/1E598F64C524/ARCH-ROLLING/5.16.10-ARCH1-1/X86_64/D47819516A>) |
| 214b:7250 | Huasheng Elec... | USB2.0 HUB                           | 652   | hub        | [72775A871A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/72775A871A>) |
| 05e3:0620 | Genesys Logic    | USB3.1 Hub                           | 638   | hub        | [016BF7F6AB](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/B20C0FCD0DEE/UBUNTU-21.10/5.16.0-ODROID-ARM64/AARCH64/016BF7F6AB>) |
| 05e3:0606 | Genesys Logic    | USB 2.0 Hub / D-Link DUB-H4 USB 2... | 614   | hub        | [1400ED0B8D](<Desktop/ASUSTek Computer/PRIME/PRIME B365M-A/BFAC8BBEE43F/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/1400ED0B8D>) |
| 058f:6254 | Alcor Micro      | USB Hub                              | 611   | hub        | [5939B86F71](<Notebook/ASUSTek Computer/VivoBook_ASUS/VivoBook_ASUS Laptop X505ZA_A505ZA/94B093502A4D/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/5939B86F71>) |
| 05e3:0616 | Genesys Logic    | hub                                  | 580   | hub        | [7A11CA484C](<Desktop/ASUSTek Computer/PRIME/PRIME Z370-P/65A3A46F7F4A/LINUXMINT-20.2/5.4.0-92-GENERIC/X86_64/7A11CA484C>) |
| 05ac:1006 | Apple            | Hub in Aluminum Keyboard             | 530   | hub        | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 1a40:0201 | Terminus Tech... | FE 2.1 7-port Hub                    | 505   | hub        | [55DA3AB4E0](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK S792/AA9902ADCF71/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/55DA3AB4E0>) |
| 0424:2134 | Microchip Tec... | Hub                                  | 503   | hub        | [3ECBD85311](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G2/8D1B4AD5F2F1/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/3ECBD85311>) |
| 2109:2811 | VIA Labs         | Hub                                  | 478   | hub        | [38C8508BC0](<Desktop/ASRock/X570/X570 Phantom Gaming 4/C2ED70ED019A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/38C8508BC0>) |
| 0424:5534 | Microchip Tec... | Hub                                  | 472   | hub        | [3ECBD85311](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G2/8D1B4AD5F2F1/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/3ECBD85311>) |
| 0451:8142 | Texas Instrum... | TUSB8041 4-Port Hub                  | 470   | hub        | [3CBA5D22BC](<Desktop/MSI/MS/MS-7918/9432F9FD1040/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/3CBA5D22BC>) |
| 0b97:7761 | O2 Micro         | Oz776 1.1 Hub                        | 462   | hub        | [CC5F0F79DD](<Notebook/Toshiba/TECRA/TECRA Z50-A/FF500FE27A3A/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/CC5F0F79DD>) |
| 0424:2513 | Microchip Tec... | 2.0 Hub                              | 431   | hub        | [2AB16BFCEE](<Notebook/Apple/MacBookPro9/MacBookPro9,2/69963227A53F/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/2AB16BFCEE>) |
| 058f:9254 | Alcor Micro      | Hub                                  | 429   | hub        | [8E109E46C5](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/0F30D8DBEDA3/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/8E109E46C5>) |
| 14cd:8601 | Super Top        | 4-Port hub                           | 410   | hub        | [EC3824B685](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S3C100/899563E44536/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/EC3824B685>) |
| 045b:0209 | Hitachi          | Hub                                  | 370   | hub        | [A1A19B3342](<Desktop/ASUSTek Computer/All/All Series/D18B96FE4419/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/A1A19B3342>) |
| 2109:8110 | VIA Labs         | Hub                                  | 355   | hub        | [38C8508BC0](<Desktop/ASRock/X570/X570 Phantom Gaming 4/C2ED70ED019A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/38C8508BC0>) |
| 0a05:7211 | Unknown Manuf... | hub                                  | 350   | hub        | [72775A871A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/72775A871A>) |
| 0451:8140 | Texas Instrum... | TUSB8041 4-Port Hub                  | 334   | hub        | [3CBA5D22BC](<Desktop/MSI/MS/MS-7918/9432F9FD1040/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/3CBA5D22BC>) |

### Human interface (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 05ac:8242 | Apple            | Built-in IR Receiver                 | 1267  | usbhid     | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 048d:5702 | Integrated Te... | ITE Device                           | 396   | usbhid     | [59405132C9](<Desktop/Gigabyte Technology/B660M/B660M AORUS PRO AX DDR4/2FD0EDB99498/UBUNTU-20.04/5.16.13-051613-GENERIC/X86_64/59405132C9>) |
| 1770:ff00 | MSI              | steel series rgb keyboard            | 383   | usbhid     | [3E80EF6096](<Notebook/MSI/GT70/GT70 2OC-2OD/2329E9C32128/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/3E80EF6096>) |
| 0483:91d1 | STMicroelectr... | Sensor Hub                           | 331   | usbhid     | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 0b05:1872 | ASUSTek Computer | AURA LED Controller                  | 230   | usbhid     | [A544689BD5](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VII HERO/A6F209226EA9/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/A544689BD5>) |
| 26ce:01a2 | ASRock           | LED Controller                       | 226   | usbhid     | [2EEB109321](<Desktop/ASRock/B550M/B550M Steel Legend/BBD26BBC6762/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/2EEB109321>) |
| 0079:0006 | DragonRise       | PC TWIN SHOCK Gamepad                | 213   | usbhid     | [EE546897FD](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LE-USB3/FC08B5D7AC3F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE546897FD>) |
| 0451:82ff | Texas Instrum... |                                      | 207   | usbhid     | [E7C5306C00](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc0xxx/1020FE6EFFAE/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/E7C5306C00>) |
| 1462:7c37 | Micro Star In... | MYSTIC LIGHT                         | 207   | usbhid     | [AC671D5E38](<Desktop/MSI/MS-7/MS-7C37/6E636F2A2773/DEBIAN-11/5.16.0-1-AMD64/X86_64/AC671D5E38>) |
| 1038:1122 | SteelSeries ApS  | SteelSeries KLC                      | 189   | usbhid     | [CCBD207EBD](<Notebook/MSI/GP66/GP66 Leopard 11UG/45801156845B/ARCH-ROLLING/5.16.7-ZEN1-1-ZEN/X86_64/CCBD207EBD>) |
| 413c:b06e | Dell             | dock                                 | 174   | usbhid     | [E7C5306C00](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc0xxx/1020FE6EFFAE/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/E7C5306C00>) |
| 413c:b06f | Dell             | dock                                 | 174   | usbhid     | [E7C5306C00](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc0xxx/1020FE6EFFAE/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/E7C5306C00>) |
| 0424:274c | Microchip Tec... | Hub Controller                       | 150   | usbhid     | [755854F7D4](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5A07TAU/0D8B48BD5BBE/ORACLESERVER-8.5/5.4.17-2136.304.4.3.EL8UEK.X86_64/X86_64/755854F7D4>) |
| 187c:0550 | Alienware        | LED controller                       | 137   | usbhid     | [17EDA5DE26](<Desktop/Alienware/Aurora/Aurora Ryzen Edition/56696C1838BA/GENTOO-2.7/5.4.97-GENTOO-X86_64/X86_64/17EDA5DE26>) |
| 0b05:18a3 | ASUSTek Computer | AURA MOTHERBOARD                     | 121   | usbhid     | [E6BB78EFDA](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-I GAMING/0524EA4B88B1/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/E6BB78EFDA>) |
| 1b1c:0c04 | Corsair          | Link Cooling Node                    | 117   | usbhid     | [30FAF7E57A](<Desktop/Gigabyte Technology/F2/F2A88XN-WIFI/0AA0C64308BE/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/30FAF7E57A>) |
| 1e71:170e | NZXT             | USB Device                           | 113   | usbhid     | [6D5688DB26](<Desktop/MSI/MS-7/MS-7B17/8DF51B50D894/GENTOO-2.6/5.15.23-GENTOO/X86_64/6D5688DB26>) |
| 054c:0268 | Sony             | Batoh Device / PlayStation 3 Cont... | 99    | usbhid     | [F2EE067B5F](<Desktop/Hewlett-Packard/h8/h8-1207eo/9913034BA75B/XUBUNTU-20.04/5.13.0-30-GENERIC/X86_64/F2EE067B5F>) |
| 05ac:8240 | Apple            | Built-in IR Receiver                 | 87    | usbhid     | [6563E94C95](<Notebook/Apple/MacBookPro1/MacBookPro1,1/FA34E0181F6E/UBUNTU-16.04/4.4.0-210-GENERIC/I686/6563E94C95>) |
| 0665:5161 | Cypress Semic... | USB to Serial                        | 86    | usbhid     | [072EDD2DCA](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/575CB7BD14E7/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/072EDD2DCA>) |
| 0765:5010 | X-Rite           | X-Rite Pantone Color Sensor          | 83    | usbhid     | [742AF9249B](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HHCTO1WW/0C27487A8E95/MANJARO/5.10.96-1-MANJARO/X86_64/742AF9249B>) |
| 0451:ca01 | Texas Instrum... | USBtoI2C Solution                    | 80    | usbhid     | [E7A3D16CC0](<Notebook/Dell/XPS/XPS 13 9310/ABE3F73FC2AC/KUBUNTU-21.04/5.10.0-1038-OEM/X86_64/E7A3D16CC0>) |
| 06c4:c411 | Bizlink Inter... | D6000 Controller                     | 79    | usbhid     | [9BB17A1C87](<Notebook/Lenovo/ThinkPad/ThinkPad T15 Gen 2i 20W4000NRT/A8DFB379DA21/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/9BB17A1C87>) |
| 1e71:2007 | NZXT             | USB Device                           | 77    | usbhid     | [95B7C99A5A](<Desktop/MSI/MS-7/MS-7C91/1CCD0C7BC7DB/GARUDA-SOARING/5.16.11-ZEN1-1-ZEN/X86_64/95B7C99A5A>) |
| 1462:7c91 | Micro Star In... | MYSTIC LIGHT                         | 76    | usbhid     | [95B7C99A5A](<Desktop/MSI/MS-7/MS-7C91/1CCD0C7BC7DB/GARUDA-SOARING/5.16.11-ZEN1-1-ZEN/X86_64/95B7C99A5A>) |
| 1b1c:0c0b | Corsair          | Lighting Node Pro                    | 76    | usbhid     | [DC38E0D85A](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-A/9834133266EF/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/DC38E0D85A>) |
| 043e:9a39 | LG Electronics   | LG Monitor Controls                  | 75    | usbhid     | [47FF2C9673](<Desktop/Gigabyte Technology/B550/B550 AORUS ELITE AX V2/CF12609E6156/OPENSUSE-TUMBLEWEED-20220213/5.16.8-1-DEFAULT/X86_64/47FF2C9673>) |
| 10d5:55a2 | Uni Class Tec... | 2Port KVMSwitcher                    | 74    | usbhid     | [0403520776](<Desktop/Hewlett-Packard/xw6600/xw6600 Workstation/08B20C49A3C6/CENTOS-7/3.10.0-1160.24.1.EL7.X86_64/X86_64/0403520776>) |
| 048d:8350 | Integrated Te... | ITE Device(8350)                     | 71    | usbhid     | [4425801F5C](<Notebook/Toshiba/Satellite/Satellite L10W-B-101/D8FCAC83307E/MANJARO/5.15.25-1-MANJARO/X86_64/4425801F5C>) |
| 046d:c215 | Logitech         | Extreme 3D Pro                       | 66    | usbhid     | [5F37C84D61](<Desktop/MSI/MS-7/MS-7D09/AC92341239B6/MAGEIA-8/5.15.23-DESKTOP-1.MGA8/X86_64/5F37C84D61>) |
| 046d:c216 | Logitech         | F310 Gamepad [DirectInput Mode]      | 66    | usbhid     | [74FDE42ED9](<Desktop/MSI/MS/MS-7758/B43232868663/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/74FDE42ED9>) |
| 046d:c227 | Logitech         | G15 Refresh Keyboard                 | 66    | usbhid     | [6B32E0C788](<Desktop/Gigabyte Technology/H61/H61M-S2PV/EB2B21B97997/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/6B32E0C788>) |
| 0b05:1867 | ASUSTek Computer | AURA Custom Human interface          | 65    | usbhid     | [19894BD1A8](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VI EXTREME/F911FC352B7F/KDE-NEON-20.04/5.15.26-XANMOD1/X86_64/19894BD1A8>) |
| 056a:00e6 | Wacom            | TPCE6                                | 61    | usbhid     | [E8DD84A845](<Notebook/Lenovo/ThinkPad/ThinkPad X220 Tablet 4298R65/7C15AE583D2A/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E8DD84A845>) |
| 1b1c:0c10 | Corsair          | Commander PRO                        | 60    | usbhid     | [DC38E0D85A](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-A/9834133266EF/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/DC38E0D85A>) |
| 0810:0001 | Personal Comm... | Dual PSX Adaptor                     | 59    | usbhid     | [9F1EDFD714](<Desktop/ASRock/B450/B450 Pro4/6FB8DDE75BA5/KDE-NEON-20.04/5.13.0-28-GENERIC/X86_64/9F1EDFD714>) |
| 1462:7c84 | Micro Star In... | MYSTIC LIGHT                         | 59    | usbhid     | [F38279E396](<Desktop/MSI/MS-7/MS-7C84/82BE05228435/NIXOS-22.05/5.15.7/X86_64/F38279E396>) |
| 1462:7c56 | Micro Star In... | MYSTIC LIGHT                         | 58    | usbhid     | [04E8E7704E](<Desktop/MSI/MS-7/MS-7C56/CF756CAB432A/POP!_OS-21.10/5.16.0-10.1-LIQUORIX-AMD64/X86_64/04E8E7704E>) |
| 2047:0855 | Texas Instrum... | Invensense Embedded MotionApp HID... | 57    | usbhid     | [DDA75E3BA9](<Notebook/Lenovo/Yoga/Yoga 2 Pro 20266/26A04B698FE7/ZORIN-16/5.11.0-38-GENERIC/X86_64/DDA75E3BA9>) |
| 10d5:55a4 | Uni Class Tec... | 4 Port KVMSwicther                   | 54    | usbhid     | [BF085B398D](<Desktop/Gigabyte Technology/B75/B75M-D3V/CBB8EB51C606/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/BF085B398D>) |
| 1462:7c35 | Micro Star In... | MYSTIC LIGHT                         | 54    | usbhid     | [4CB6628353](<Desktop/MSI/MS-7/MS-7C35/1A925FFBC44B/XUBUNTU-20.04/5.13.0-28-LOWLATENCY/X86_64/4CB6628353>) |
| 1e71:2006 | NZXT             | Smart Device V2                      | 53    | usbhid     | [42FBA9424E](<Desktop/MSI/MS/MS-7817/E544C06A9CFE/ZORIN-16/5.13.0-30-GENERIC/X86_64/42FBA9424E>) |
| 054c:05c4 | Sony             | DualShock 4 [CUH-ZCT1x]              | 52    | usbhid     | [24FEDCCA0A](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/83963AF67D76/VOID-ROLLING/5.15.11_1/X86_64/24FEDCCA0A>) |
| 05ac:1392 | Apple            | Apple Watch charger                  | 52    | usbhid     | [B98AE7B6B2](<Desktop/MSI/MS-7/MS-7C02/3B0DD57EBCE9/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/B98AE7B6B2>) |
| 1462:7b85 | Micro Star In... | PRO CARBON                           | 50    | usbhid     | [889E5FE7A3](<Desktop/MSI/MS-7/MS-7B85/E913502156FC/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/889E5FE7A3>) |
| 1b1c:0c1a | Corsair          | Lighting Node CORE                   | 47    | usbhid     | [55D8863B7B](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E0F900F46405/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/55D8863B7B>) |
| 0bda:1100 | Realtek Semic... | HID Device                           | 46    | usbhid     | [385D1914EE](<Desktop/ASUSTek Computer/TUF/TUF B450M-PLUS GAMING/55622562AC3A/ARCH-ROLLING/5.15.26-1-LTS/X86_64/385D1914EE>) |
| 0408:3001 | Quanta           | Optical Touch Screen                 | 45    | usbhid     | [D1D4080F45](<All In One/Sony/VPCJ118/VPCJ118FW/7247E7BFDC34/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D1D4080F45>) |
| 044f:b10a | ThrustMaster     | T.16000M Joystick                    | 45    | usbhid     | [759958A4B0](<Desktop/Gigabyte Technology/B550/B550 AORUS MASTER/2A7DA6CE54F8/ARCO-ROLLING/5.16.11-XANMOD1-1/X86_64/759958A4B0>) |
| 046d:c225 | Logitech         | G11/G15 Keyboard / G keys            | 43    | usbhid     | [AE6CB3BEA9](<Desktop/ASRock/B360/B360 Gaming K4/B53CA139A0EA/KUBUNTU-20.04/5.13.0-35-GENERIC/X86_64/AE6CB3BEA9>) |

### Infrared (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 066f:4200 | SigmaTel         | STIr4200 IrDA Bridge                 | 7     | stir4200   | [A519C7C3B0](<Desktop/MSI/MS/MS-7596/1EF2D7E56EC2/FEDORA-31/5.7.9-100.FC31.X86_64/X86_64/A519C7C3B0>) |
| 0609:031d | SMK Manufactu... | eHome Infrared Receiver              | 6     | mceusb     | [264E35C172](<Desktop/Biostar/Hi-Fi/Hi-Fi Z87X 3D/166F522FB7FE/POP!_OS-20.10/5.8.0-7630-GENERIC/X86_64/264E35C172>) |
| 1509:9242 | FIC              | eHome Infrared Transceiver           | 6     | mceusb     | [9BB3496465](<Desktop/FIC/GE2/GE2 Series/FE1DFC3AB0F4/UBUNTU-20.04/5.13.0-32-GENERIC/X86_64/9BB3496465>) |
| 147a:e017 | Formosa Indus... | eHome Infrared Receiver              | 3     | mceusb     | [D78CA9AB47](<Notebook/MSI/GX/GX710/9EE784107BF4/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/D78CA9AB47>) |

### Input/keyboard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:c52b | Logitech         | Unifying Receiver                    | 11588 | usbhid     | [09D876AB23](<Desktop/ASUSTek Computer/STRIX/STRIX Z270E GAMING/572D30F97D55/KUBUNTU-21.10/5.13.0-35-GENERIC/X86_64/09D876AB23>) |
| 046d:c534 | Logitech         | Unifying Receiver                    | 6252  | usbhid     | [8248B17F01](<Notebook/Dell/Vostro/Vostro 5471/BF689F2C5926/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/8248B17F01>) |
| 046d:c31c | Logitech         | Keyboard K120                        | 2766  | usbhid     | [C8474E89B8](<Desktop/Gigabyte Technology/H110/H110M-H/A6D65E8E4B13/ENDLESS-4.0.3/5.11.0-35-GENERIC/X86_64/C8474E89B8>) |
| 1c4f:0002 | SiGma Micro      | Keyboard TRACER Gamma Ivory          | 2382  | usbhid     | [83881D4EB6](<All In One/3Logic Group/Graviton/Graviton/2B12BC91A8E9/ALT-10.0/5.10.82-STD-DEF-ALT1/X86_64/83881D4EB6>) |
| 062a:4101 | MosArt Semico... | Wireless Keyboard/Mouse              | 2156  | usbhid     | [C68CEC2207](<Notebook/Hewlett-Packard/Victus/Victus by Laptop 16-d1xxx/C277E60CB4EA/UBUNTU-20.04/5.8.0-43-GENERIC/X86_64/C68CEC2207>) |
| 045e:0745 | Microsoft        | Nano Transceiver v1.0 for Bluetooth  | 1527  | usbhid     | [1575F2F0BE](<Notebook/Sony/SVE14/SVE14A2V2ES/F3A92336CE08/PARDUS-19.5/4.19.0-19-AMD64/X86_64/1575F2F0BE>) |
| 04d9:1702 | Holtek Semico... | Keyboard LKS02                       | 983   | usbhid     | [AA1E6A4C82](<Desktop/Biostar/N68/N68S3B/A98E2FD5FA9F/ELEMENTARY-6.1/5.13.0-35-GENERIC/X86_64/AA1E6A4C82>) |
| 1a2c:2124 | China Resourc... | Keyboard                             | 973   | usbhid     | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 413c:2113 | Dell             | KB216 Wired Keyboard                 | 934   | usbhid     | [41088E9FA5](<Desktop/Gigabyte Technology/H410M/H410M H V3/21EE77B60B48/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/41088E9FA5>) |
| 09da:9090 | A4Tech           | XL-730K / XL-750BK / XL-755BK Mice   | 903   | usbhid     | [DAB731FD45](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/A2C546D96445/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/DAB731FD45>) |
| 09da:054f | A4Tech           | USB Device                           | 865   | usbhid     | [8BBF7F5495](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/07187B792FB5/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/8BBF7F5495>) |
| 1a2c:2d23 | China Resourc... | Keyboard                             | 862   | usbhid     | [21926A008C](<Desktop/Gigabyte Technology/GA-970/GA-970A-DS3/EAEF26F74332/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/21926A008C>) |
| 413c:2003 | Dell             | Keyboard SK-8115                     | 788   | usbhid     | [0A6B13D126](<Desktop/ASUSTek Computer/H110/H110M-E-M.2/78F22BF40F06/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/0A6B13D126>) |
| 04f3:0103 | Elan Microele... | ActiveJet K-2024 Multimedia Keyboard | 787   | usbhid     | [30DF05CC2F](<Desktop/Wortmann AG/TERRA_PC/TERRA_PC/A8AB20556C45/MANJARO/5.15.25-1-MANJARO/X86_64/30DF05CC2F>) |
| 413c:2107 | Dell             | KB212-B Quiet Key Keyboard           | 777   | usbhid     | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 046d:c52e | Logitech         | MK260 Wireless Combo Receiver        | 671   | usbhid     | [E947D6AF7F](<Desktop/Others/Intel/Intel X79/05010125287F/UBUNTU-21.10/5.15.0-051500RC7-GENERIC/X86_64/E947D6AF7F>) |
| 0461:0010 | Primax Electr... | HP PR1101U / Primax PMX-KPR1101U ... | 617   | usbhid     | [00BCB5F530](<Desktop/Hewlett-Packard/KN278AA-ABM/KN278AA-ABM a6430la/211B5A8F19E0/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/00BCB5F530>) |
| 1c4f:0026 | SiGma Micro      | Keyboard                             | 604   | usbhid     | [55CE4F1460](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/A185B7D2F341/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/55CE4F1460>) |
| 048d:8297 | Integrated Te... | IT8297 RGB LED Controller            | 562   | usbhid     | [4F7AA0F57C](<Desktop/Gigabyte Technology/X570/X570 GAMING X/723F54EA2F09/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/4F7AA0F57C>) |
| 045e:07b2 | Microsoft        | 2.4GHz Transceiver v8.0 used by m... | 550   | usbhid     | [0DD6576588](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 520-22AST F0D6002EFR/7FE429038D53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0DD6576588>) |
| 04d9:1603 | Holtek Semico... | Keyboard                             | 517   | usbhid     | [6E46455791](<Notebook/Dell/Vostro/Vostro 5471/91A167765016/MANJARO-21.2.4/5.10.102-1-MANJARO/X86_64/6E46455791>) |
| 1a2c:0e24 | China Resourc... | USB Keyboard                         | 508   | usbhid     | [EAAE14DE4F](<Desktop/Gigabyte Technology/970/970A-DS3P/069ADAD23CA7/UBUNTU-BUDGIE-20.04/5.4.0-102-GENERIC/X86_64/EAAE14DE4F>) |
| 046d:c539 | Logitech         | USB Receiver                         | 496   | usbhid     | [B979165379](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/4001EA066FBB/ARCH/5.16.12-ARCH1-1/X86_64/B979165379>) |
| 0c45:7603 | Microdia         | USB Keyboard                         | 493   | usbhid     | [256DC440EC](<Desktop/Others/T3/T3 MRD/40E9767A0365/UBUNTU-22.04/5.15.0-22-GENERIC/X86_64/256DC440EC>) |
| 03f0:0024 | Hewlett-Packard  | KU-0316 Keyboard                     | 478   | usbhid     | [C79A71B9DB](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/C0AF1D599D12/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C79A71B9DB>) |
| 1a2c:2c27 | China Resourc... | USB Keyboard                         | 474   | usbhid     | [DA3962A1DA](<Desktop/Gigabyte Technology/EP45/EP45-DS3L/E3972A4CE3A2/FEDORA-36/5.17.0-0.RC5.102.FC36.X86_64/X86_64/DA3962A1DA>) |
| 258a:0001 | SINO WEALTH      | USB KEYBOARD                         | 441   | usbhid     | [72775A871A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/72775A871A>) |
| 1a2c:4c5e | China Resourc... | USB Keyboard                         | 436   | usbhid     | [9695618053](<Desktop/Primux Tech/Primux_Device_W/Primux_Device_W10/5CE3FF86ACD3/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/9695618053>) |
| 045e:07f8 | Microsoft        | Wired Keyboard 600 (model 1576)      | 427   | usbhid     | [8A97B4F2D3](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-K/F094BA5D12EA/CLEAR-LINUX-OS-35980/5.16.12-1129.NATIVE/X86_64/8A97B4F2D3>) |
| 046d:c517 | Logitech         | LX710 Cordless Desktop Laser         | 416   | usbhid     | [5E75B405EA](<Desktop/Gigabyte Technology/Z590/Z590 UD AC/CD009638363A/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/5E75B405EA>) |
| 04d9:1503 | Holtek Semico... | Keyboard                             | 416   | usbhid     | [503D10D676](<All In One/Dell/Inspiron/Inspiron 5400 AIO/1B0441A55B57/ZORIN-16/5.11.0-38-GENERIC/X86_64/503D10D676>) |
| 062a:4c01 | MosArt Semico... | 2,4Ghz Wireless Transceiver [for ... | 403   | usbhid     | [47099A8C6C](<Notebook/Medion/E/E6228/11ECFFA666E6/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/47099A8C6C>) |
| 1050:0407 | Yubico.com       | Yubikey 4/5 OTP+U2F+CCID             | 395   | usbhid     | [3F58A0F2A4](<Notebook/Lenovo/Legion/Legion Y530-15ICH 81FV/A4B769895625/GENTOO-2.6/5.15.23-GENTOO/X86_64/3F58A0F2A4>) |
| 045e:07fd | Microsoft        | Nano Transceiver 1.1                 | 392   | usbhid     | [2E4BDB96FA](<Notebook/Dell/Inspiron/Inspiron 7520/D9F7258E8353/XUBUNTU-21.10/5.13.0-35-GENERIC/X86_64/2E4BDB96FA>) |
| 062a:5918 | MosArt Semico... | 2.4G Keyboard Mouse                  | 372   | usbhid     | [CEB8D030E2](<Notebook/Toshiba/Satellite/Satellite P755/7E251E73A571/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/CEB8D030E2>) |
| 04b3:3025 | IBM              | NetVista Full Width Keyboard         | 359   | usbhid     | [9BE6D8C4AA](<Desktop/Gigabyte Technology/GA-MA780/GA-MA780G-UD3H/2E783AB9CC77/FEDORA-35/5.16.12-200.FC35.X86_64/X86_64/9BE6D8C4AA>) |
| 1ea7:0066 | SHARKOON Tech... | [Mediatrack Edge Mini Keyboard]      | 348   | usbhid     | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 045e:00db | Microsoft        | Natural Ergonomic Keyboard 4000 V1.0 | 347   | usbhid     | [88876808E9](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/0BCBF54A8A61/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/88876808E9>) |
| 258a:1006 | SINO WEALTH      | USB KEYBOARD                         | 325   | usbhid     | [38C8508BC0](<Desktop/ASRock/X570/X570 Phantom Gaming 4/C2ED70ED019A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/38C8508BC0>) |
| 05ac:024f | Apple            | Keyboard                             | 315   | usbhid     | [A4D2E10715](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/AC63455180C3/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/A4D2E10715>) |
| 045e:0750 | Microsoft        | Wired Keyboard 600                   | 311   | usbhid     | [59ED587F49](<Desktop/Hewlett-Packard/110/110-129/F7C0EC5275B9/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/59ED587F49>) |
| 24ae:2000 | RAPOO            | 2.4G Wireless Device                 | 306   | usbhid     | [378234E501](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/DB636D4B15B5/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/378234E501>) |
| 0518:0001 | EzKEY            | USB to PS2 Adaptor v1.09             | 305   | usbhid     | [37C37094B9](<Desktop/Gigabyte Technology/M61/M61PME-S2P/9DACEC325D22/DEBIAN-11/5.10.0-7-AMD64/X86_64/37C37094B9>) |
| 046d:c31d | Logitech         | Media Keyboard K200                  | 302   | usbhid     | [4DE85D4700](<Desktop/Supermicro/X10/X10DAi/054CD4D16CA3/KUBUNTU-20.04/5.4.0-100-GENERIC/X86_64/4DE85D4700>) |
| 0a5c:4502 | Broadcom         | Keyboard (Boot Interface Subclass)   | 299   | usbhid     | [FAC84EDCF2](<Desktop/ASUSTek Computer/Z170/Z170-P/53020D74CC73/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/FAC84EDCF2>) |
| 046a:0023 | Cherry           | Keyboard                             | 294   | usbhid     | [35E716F504](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-D3/658541A7D930/DEBIAN-11/5.10.0-11-AMD64/X86_64/35E716F504>) |
| 25a7:fa61 | Areson Techno... | Elecom Co., Ltd MR-K013 Multicard... | 289   | usbhid     | [9A92C2571B](<Notebook/ASUSTek Computer/X451/X451CAP/2FDD68A7BB53/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/9A92C2571B>) |
| 0458:6001 | KYE Systems (... | GF3000F Ethernet Adapter             | 286   | usbhid     | [E6D7592AF0](<Notebook/Dell/Inspiron/Inspiron 3543/209FEBF36AAD/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/E6D7592AF0>) |
| 0b05:1866 | ASUSTek Computer | N-KEY Device                         | 286   | usbhid     | [4B2B4E7F5A](<Notebook/ASUSTek Computer/ROG/ROG Strix G713QE_G713QE/41E684CE14EB/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/4B2B4E7F5A>) |
| 1a2c:0c21 | China Resourc... | USB Keyboard                         | 286   | usbhid     | [0A534CF272](<Desktop/ASRock/H110M-DGS/H110M-DGS R3.0/64B1432E50B0/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0A534CF272>) |

### Input/mouse (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 093a:2510 | Pixart Imaging   | Optical Mouse                        | 4514  | usbhid     | [83881D4EB6](<All In One/3Logic Group/Graviton/Graviton/2B12BC91A8E9/ALT-10.0/5.10.82-STD-DEF-ALT1/X86_64/83881D4EB6>) |
| 046d:c077 | Logitech         | M105 Optical Mouse                   | 3818  | usbhid     | [FD6766AABB](<Desktop/Hewlett-Packard/Compaq/Compaq 8000 Elite CMT PC/D6DA53EF4163/MX-21/5.10.0-10-AMD64/X86_64/FD6766AABB>) |
| 046d:c52f | Logitech         | Unifying Receiver                    | 3505  | usbhid     | [FE9AB2819C](<All In One/Apple/iMac10/iMac10,1/33AACCC69432/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/FE9AB2819C>) |
| 1ea7:0064 | SHARKOON Tech... | 2.4GHz Wireless rechargeable vert... | 2049  | usbhid     | [E947D6AF7F](<Desktop/Others/Intel/Intel X79/05010125287F/UBUNTU-21.10/5.15.0-051500RC7-GENERIC/X86_64/E947D6AF7F>) |
| 0458:003a | KYE Systems (... | NetScroll+ Mini Traveler / Genius... | 1763  | usbhid     | [1A2A0418C9](<Desktop/ASUSTek Computer/CROSSBLADE/CROSSBLADE RANGER/E3D889FAA220/ENDLESS-4.0.3/5.11.0-35-GENERIC/X86_64/1A2A0418C9>) |
| 275d:0ba6 |                  | USB OPTICAL MOUSE                    | 1694  | usbhid     | [5B061FA374](<Desktop/ASUSTek Computer/M4N68T/M4N68T V2/153A82DB799D/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/5B061FA374>) |
| 046d:c05a | Logitech         | M90/M100 Optical Mouse               | 1523  | usbhid     | [CE28F1E721](<Desktop/ASRock/Q1900/Q1900M/AB30F2BD2E2D/LUBUNTU-20.04/5.11.0-27-GENERIC/X86_64/CE28F1E721>) |
| 1bcf:0005 | Sunplus Innov... | Optical Mouse                        | 1497  | usbhid     | [CDDC590270](<Mini Pc/BESSTAR Tech/Z83/Z83-F/833154D27E3C/ZORIN-16/5.13.0-30-GENERIC/X86_64/CDDC590270>) |
| 1c4f:0034 | SiGma Micro      | XM102K Optical Wheel Mouse           | 1306  | usbhid     | [FC3707D356](<Desktop/MSI/MS-7/MS-7A15/650F34E662BB/ZORIN-16/5.13.0-30-GENERIC/X86_64/FC3707D356>) |
| 0000:0538 |                  | USB OPTICAL MOUSE                    | 1179  | usbhid     | [0A534CF272](<Desktop/ASRock/H110M-DGS/H110M-DGS R3.0/64B1432E50B0/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/0A534CF272>) |
| 248a:8367 | Maxxter          | Telink Wireless Receiver             | 996   | usbhid     | [9A92C2571B](<Notebook/ASUSTek Computer/X451/X451CAP/2FDD68A7BB53/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/9A92C2571B>) |
| 18f8:0f97 | [Maxxter]        | Optical Gaming Mouse [Xtrem]         | 920   | usbhid     | [45BEEC1B7C](<Desktop/ASUSTek Computer/All/All Series/3C968B8AB880/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/45BEEC1B7C>) |
| 0000:3825 |                  | USB OPTICAL MOUSE                    | 919   | usbhid     | [14747D7263](<Notebook/MSI/GF65/GF65 Thin 9SEXR/BF90DCCF31DE/MANJARO/5.15.25-1-MANJARO/X86_64/14747D7263>) |
| 09da:000a | A4Tech           | Optical Mouse Opto 510D / OP-620D    | 891   | usbhid     | [DB28C629EC](<Desktop/Gigabyte Technology/H81/H81M-S2V/0F282FDFB77B/DEBIAN-11/5.10.0-7-AMD64/X86_64/DB28C629EC>) |
| 413c:301a | Dell             | Dell MS116 Optical Mouse             | 878   | usbhid     | [41088E9FA5](<Desktop/Gigabyte Technology/H410M/H410M H V3/21EE77B60B48/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/41088E9FA5>) |
| 25a7:fa23 | Compx            | 2.4G Receiver                        | 846   | usbhid     | [2F136D5BF5](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN002YPH/61077ED80EDE/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/2F136D5BF5>) |
| 093a:2521 | Pixart Imaging   | Optical Mouse                        | 812   | usbhid     | [09D876AB23](<Desktop/ASUSTek Computer/STRIX/STRIX Z270E GAMING/572D30F97D55/KUBUNTU-21.10/5.13.0-35-GENERIC/X86_64/09D876AB23>) |
| 248a:8514 | Maxxter          | Wireless Receiver                    | 780   | usbhid     | [817E973E9D](<Notebook/Dell/Latitude/Latitude 5480/B95B01FCFA31/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/817E973E9D>) |
| 045e:00cb | Microsoft        | Basic Optical Mouse v2.0             | 748   | usbhid     | [F486888101](<Desktop/Dell/OptiPlex/OptiPlex 9010/4EC36D4A001A/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/F486888101>) |
| 062a:4102 | MosArt Semico... | 2.4G Wireless Mouse                  | 648   | usbhid     | [BB234C5FD0](<Notebook/Dell/Latitude/Latitude 5520/68E7A5BBE393/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/BB234C5FD0>) |
| 3938:1031 | MOSART Semi.     | 2.4G Wireless Mouse                  | 628   | usbhid     | [63D555C391](<Desktop/ASUSTek Computer/PRIME/PRIME A520M-A/7B56B88F045B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/63D555C391>) |
| 046d:c016 | Logitech         | Optical Wheel Mouse                  | 613   | usbhid     | [7D57D04480](<Desktop/Dell/Inspiron/Inspiron 3847/ACEAAE9A8A20/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/7D57D04480>) |
| 10c4:8108 | Silicon Labs     | USB OPTICAL MOUSE                    | 575   | usbhid     | [F3A97CAD04](<Desktop/ASUSTek Computer/H61/H61M-A-BR/5CE3A55BFCBC/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F3A97CAD04>) |
| 18f8:0f99 | [Maxxter]        | Optical gaming mouse                 | 532   | usbhid     | [0BD936F5B1](<Desktop/Apple/MacPro6/MacPro6,1/D18E2872903D/UBUNTU-20.04/5.4.0-104-GENERIC/X86_64/0BD936F5B1>) |
| 045e:0040 | Microsoft        | Wheel Mouse Optical                  | 505   | usbhid     | [CD13B1CD77](<Notebook/Toshiba/Satellite/Satellite Radius L10W-C/A697BB18C3B6/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/CD13B1CD77>) |
| 10c4:8105 | Silicon Labs     | USB OPTICAL MOUSE                    | 496   | usbhid     | [E32F5B40A1](<Notebook/Dell/Latitude/Latitude E6430/CF0301C655CD/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/E32F5B40A1>) |
| 046d:c050 | Logitech         | RX 250 Optical Mouse                 | 486   | usbhid     | [14AC6C1F51](<Notebook/Toshiba/Satellite/Satellite C870-1F3/576838609E8D/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/14AC6C1F51>) |
| 046d:c018 | Logitech         | Optical Wheel Mouse                  | 482   | usbhid     | [3C01AC84D3](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/730ACCC800BC/LINUXMINT-20.3/5.4.0-104-GENERIC/X86_64/3C01AC84D3>) |
| 09da:c10a | A4Tech           | USB Mouse                            | 479   | usbhid     | [8BCA9F27C4](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2570p/00A310807387/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/8BCA9F27C4>) |
| 0458:0186 | KYE Systems (... | Genius DX-120 Mouse                  | 468   | usbhid     | [DD40993D97](<Desktop/Gigabyte Technology/G31/G31M-S2L/B38A5C83A51B/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/DD40993D97>) |
| 248a:8366 | Maxxter          | Wireless Optical Mouse ACT-MUSW-002  | 457   | usbhid     | [E909E31559](<Notebook/Acer/Aspire/Aspire V5-571G/1E1289439524/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E909E31559>) |
| 046d:c069 | Logitech         | M-U0007 [Corded Mouse M500]          | 455   | usbhid     | [8E7B1DB68F](<Notebook/Acer/Aspire/Aspire A515-51/1B666FCC2D3A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/8E7B1DB68F>) |
| 046d:c08b | Logitech         | G502 HERO Gaming Mouse               | 438   | usbhid     | [3B338F456B](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop/7A0412709E2F/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/3B338F456B>) |
| 046d:c05b | Logitech         | M-U0004 810-001317 [B110 Optical ... | 434   | usbhid     | [DE34294599](<Notebook/Hewlett-Packard/Presario/Presario CQ42/0F7402BC6299/UBUNTU-22.04/5.15.0-18-GENERIC/X86_64/DE34294599>) |
| 1bcf:0007 | Sunplus Innov... | Optical Mouse                        | 425   | usbhid     | [BD24A29894](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5AF618BB3024/MANJARO-ARM/5.15.24-1-MANJARO-ARM-RPI/AARCH64/BD24A29894>) |
| 1a2c:0042 | China Resourc... | Usb Mouse                            | 416   | usbhid     | [52526B4A77](<Desktop/Dell/OptiPlex/OptiPlex GX520/7F3E83EA613F/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/52526B4A77>) |
| 046d:c332 | Logitech         | G502 Proteus Spectrum Optical Mouse  | 397   | usbhid     | [BAD433FA2F](<Notebook/Lenovo/IdeaPad/IdeaPad 3 14ITL6 82H7/140C80F609F1/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/BAD433FA2F>) |
| 046d:c084 | Logitech         | G203 Gaming Mouse                    | 387   | usbhid     | [798E5F6C43](<Desktop/ASUSTek Computer/TUF/TUF B450-PRO GAMING/A03E463A72CD/ZORIN-16/5.13.0-35-GENERIC/X86_64/798E5F6C43>) |
| 0461:4d0f | Primax Electr... | HP Optical Mouse                     | 380   | usbhid     | [4C4AFB883E](<Desktop/ASRock/Z68/Z68 Pro3/106121ED38D4/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/4C4AFB883E>) |
| 17ef:6019 | Lenovo           | M-U0025-O Mouse                      | 363   | usbhid     | [146505ADEE](<Desktop/Acer/Aspire/Aspire TC-391/45578AE790D2/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/146505ADEE>) |
| 046d:c53f | Logitech         | USB Receiver                         | 345   | usbhid     | [C7025AC75E](<Notebook/Lenovo/IdeaPad/IdeaPad S145-15IIL 82DJ/78365AF6FE7D/KUBUNTU-11/5.13.0-30-GENERIC/X86_64/C7025AC75E>) |
| 258a:1007 | SINOWEALTH       | Wired Gaming Mouse                   | 343   | usbhid     | [A90045FFA3](<Desktop/ASRock/P67/P67 Pro3/E2B313BFC54F/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/A90045FFA3>) |
| 17ef:608d | Lenovo           | Optical Mouse                        | 337   | usbhid     | [E99C4341CA](<Notebook/Dell/Inspiron/Inspiron 5409/34EA23E7BE6D/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/E99C4341CA>) |
| 046d:c542 | Logitech         | Wireless Receiver                    | 331   | usbhid     | [96B36779E0](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK AH544/016D5650067E/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/96B36779E0>) |
| 046d:c03e | Logitech         | Premium Optical Wheel Mouse (M-BT58) | 327   | usbhid     | [C25FFC39DB](<Desktop/MSI/MS/MS-7751/F7E4EA6432BF/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/C25FFC39DB>) |
| 0a5c:4503 | Broadcom         | Mouse (Boot Interface Subclass)      | 301   | usbhid     | [FAC84EDCF2](<Desktop/ASUSTek Computer/Z170/Z170-P/53020D74CC73/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/FAC84EDCF2>) |
| 03f0:094a | Hewlett-Packard  | Optical Mouse [672662-001]           | 289   | usbhid     | [7DE0381DB8](<All In One/Hewlett-Packard/205/205 G4 22 All-in-One PC/F158F87A803B/SLACKWARE-15.0/5.15.27/X86_64/7DE0381DB8>) |
| 15d9:0a4f | Trust Interna... | Optical Mouse                        | 287   | usbhid     | [59A21D0AA2](<Desktop/ASUSTek Computer/P5/P5Q/54A685670DC2/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/59A21D0AA2>) |
| 2188:0ae1 | No brand         | USB OPTICAL MOUSE                    | 279   | usbhid     | [21E65FB534](<Desktop/Gigabyte Technology/G41/G41M-Combo/06DB9F3AB20E/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/21E65FB534>) |
| 046d:c00e | Logitech         | M-BJ58/M-BJ69 Optical Wheel Mouse    | 274   | usbhid     | [A529D98D69](<Notebook/Hewlett-Packard/Pavilion/Pavilion g6/234917B78CC1/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/A529D98D69>) |

### Isdn adapter (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| ffff:ffff | C-Media Elect... | USB Headset                          | 12    | usbhid     | [AA49529B6C](<Notebook/Lenovo/ThinkPad/ThinkPad E15 Gen 3 20YG006CSC/3AC4CC484403/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/AA49529B6C>) |
| 0681:0002 | Siemens Infor... | Gigaset 3075 Passive ISDN            | 1     | bas_gig... | [B11EDA70A9](<Desktop/Gigabyte Technology/Z77/Z77X-UD5H/6AC23D98FB7B/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/B11EDA70A9>) |

### Joystick (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:02ea | Microsoft        | Xbox One S Controller                | 124   | xpad       | [EED6DC3694](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/1553ADD3C443/ARCH/5.16.13-ARCH1-1/X86_64/EED6DC3694>) |
| 045e:02d1 | Microsoft        | Xbox One Controller                  | 37    | xpad       | [A64818CCEA](<Desktop/Gigabyte Technology/B150N/B150N Phoenix-WIFI/DC157CA1519D/ELEMENTARY-6.1/5.13.0-35-GENERIC/X86_64/A64818CCEA>) |
| 24c6:581a | ThrustMaster     | XB1 Classic Controller               | 29    | xpad       | [F4DED8B967](<Desktop/MSI/MS-7/MS-7A38/12276B123BB7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F4DED8B967>) |
| 044f:b687 | ThrustMaster     | TWCS Throttle                        | 18    | usbhid     | [55B76D666C](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/9252CC15DCB7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/55B76D666C>) |
| 24c6:543a | ThrustMaster     | PowerA Wired Controller for Xbox One | 14    | xpad       | [8F0EB971EC](<Notebook/Dell/Inspiron/Inspiron 5577/DFB5462F6EC9/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/8F0EB971EC>) |
| 068e:00f2 | CH Products      | Flight Sim Pedals                    | 10    | usbhid     | [4A961CB5C6](<Notebook/MSI/GE62/GE62 2QF/226182A653D0/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/4A961CB5C6>) |
| 0e6f:02b8 | Logic3           | Afterglow Wired Controller for Xb... | 9     | xpad       | [6A9245ACD2](<Desktop/Others/Intel/Intel X79/057FED06BE48/ARCO-ROLLING/5.16.11-ARCH1-1/X86_64/6A9245ACD2>) |
| 24c6:530a | ThrustMaster     | ProEX Controller for Xbox 360        | 9     | xpad       | [2C15FDB7F3](<Desktop/MSI/MS/MS-7693/AD4DCEC3F0D1/KDE-NEON-20.04/5.13.0-28-GENERIC/X86_64/2C15FDB7F3>) |
| 2341:8037 | Arduino SA       | Arduino Micro                        | 7     | cdc_acm    | [44DA109AED](<Desktop/ASRock/X370/X370 Gaming X/66E787CE117F/ARCH/5.15.22-XANMOD1-1/X86_64/44DA109AED>) |
| 046d:c262 | Logitech         | G920 Driving Force Racing Wheel      | 6     | usbhid     | [711A930635](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/6E72ACA8B1DF/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/711A930635>) |
| 07b5:0317 | Mega World In... | USB Game Controllers                 | 6     | usbhid     | [78FC18FCF4](<Desktop/Acer/Aspire/Aspire G7713/50BC3E207941/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/78FC18FCF4>) |
| 145f:01bb | Trust            | Gamepad                              | 6     | usbhid     | [9A1C8EC615](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/2A3CCF4DB6EA/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/9A1C8EC615>) |
| 28de:1102 | Valve Software   | Wired Controller                     | 6     | usbhid     | [D482D475F7](<Desktop/Alienware/ASM/ASM100/BF93FEEE0332/KUBUNTU-20.04/5.11.0-34-GENERIC/X86_64/D482D475F7>) |
| 046d:c213 | Logitech         | J-UH16 (Freedom 2.4 Cordless Joys... | 5     | usbhid     | [6F0E81A6D9](<Desktop/Gigabyte Technology/B150/B150M-D3H/F3481A4CB99E/FEDORA-34/5.13.12-200.FC34.X86_64/X86_64/6F0E81A6D9>) |
| 06a3:0c2d | Saitek           | Pro Flight Quadrant                  | 5     | usbhid     | [3164BE18F3](<Desktop/ASUSTek Computer/All/All Series/E435ADA3C440/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/3164BE18F3>) |
| 0e6f:02a4 | Logic3           | PDP Wired Controller for Xbox One... | 5     | xpad       | [7CCAB1854D](<Desktop/MSI/MS-7/MS-7C02/FAE18E253586/FEDORA-33/5.11.10-200.FC33.X86_64/X86_64/7CCAB1854D>) |
| 1532:0a14 | Razer USA        | Razer Wolverine Ultimate             | 5     | xpad       | [E9139E2C55](<Desktop/MSI/MS-7/MS-7B93/BC9FE35A89F8/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/E9139E2C55>) |
| 0428:4001 | Advanced Grav... | GamePad Pro                          | 4     | usbhid     | [B3559AEEC4](<All In One/Dell/Inspiron/Inspiron One 2305/939A63A720E7/MAKULU-2020/5.11.0-43-GENERIC/X86_64/B3559AEEC4>) |
| 06a3:0109 | Saitek           | P880 Pad                             | 4     | usbhid     | [40210AAF34](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AWS0DS0S/EBCD8B846A52/UBUNTU-20.10/5.8.0-44-GENERIC/X86_64/40210AAF34>) |
| 0e6f:02a2 | Logic3           | PDP Wired Controller for Xbox One... | 4     | xpad       | [BB2FD997AB](<Desktop/Alienware/X/X51/3C7841EA14B6/ZORIN-16/5.11.0-38-GENERIC/X86_64/BB2FD997AB>) |
| 12bd:a02f | Gembird          | 5-Axis,12-Button with POV            | 4     | usbhid     | [EF57A01461](<Desktop/Biostar/TB250/TB250-BTC+/88F463FF134F/LINUXMINT-20/5.4.0-91-GENERIC/X86_64/EF57A01461>) |
| 20bc:5500 | ShenZhen Shan... | Frostbite controller                 | 4     | usbhid     | [A611E12778](<Notebook/Dell/Inspiron/Inspiron 3542/105B2B38387D/ENDEAVOUROS-ROLLING/5.15.12-ZEN1-1-ZEN/X86_64/A611E12778>) |
| 0458:1004 | KYE Systems (... | Flight2000 F-23 Joystick             | 3     | usbhid     | [0C5BDA9187](<Desktop/ASRock/H61/H61M-U3S3/B79F3240A57D/UBUNTU-20.10/5.8.0-25-GENERIC/X86_64/0C5BDA9187>) |
| 045e:000e | Microsoft        | SideWinder?‚ Freestyle Pro           | 3     | usbhid     | [29CD216C62](<Notebook/Toshiba/Satellite/Satellite C650/320D9F9D1BCC/ARCH/5.8.10-ARCH1-1/X86_64/29CD216C62>) |
| 04d8:fd0a | Microchip Tec... | Lexip Gaming                         | 3     | usbhid     | [F36828F316](<Desktop/ASRock/H81/H81 Pro BTC R2.0/A9FEE1338840/KDE-NEON-20.04/5.4.0-73-GENERIC/X86_64/F36828F316>) |
| 05ac:056b | Apple            | GameSir-T2a                          | 3     | usbhid     | [7404E9534E](<Desktop/Acer/Aspire/Aspire M7720/23A5D7219017/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/7404E9534E>) |
| 068e:00f3 | CH Products      | Fighterstick                         | 3     | usbhid     | [AEACC62BC1](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX PLUS/F1AF6E990A2C/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/AEACC62BC1>) |
| 06a3:0255 | Saitek           | X52 Flight Controller                | 3     | usbhid     | [732C7AD77E](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/90E5FEC0AC62/ARCO-ROLLING/5.15.22-1-LTS/X86_64/732C7AD77E>) |
| 0738:1302 | Mad Catz         | F.L.Y.5 Stick                        | 3     | usbhid     | [FBAF774D0B](<Desktop/ASUSTek Computer/P8/P8P67/C67C4CD5A3A5/KDE-NEON-20.04/5.4.0-65-GENERIC/X86_64/FBAF774D0B>) |
| 0e6f:0119 | Logic3           | wireless controller for PS3          | 3     | usbhid     | [300431594A](<Desktop/Dell/OptiPlex/OptiPlex 760/2C4E47CE790B/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/300431594A>) |
| 0e6f:02c6 | Logic3           | PDP Deluxe Wired Controller for X... | 3     | xpad       | [7F349B8B8D](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/FFAA38A35502/UBUNTU-20.04/5.9.10-050910-GENERIC/X86_64/7F349B8B8D>) |
| 20d6:a713 | Bensussen Deu... | NSW Wired controller                 | 3     | usbhid     | [52D5157FD9](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/6FE32786146E/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/52D5157FD9>) |
| 231d:1105 | www.vkb-fligh... | GTX Throttle                         | 3     | usbhid     | [417453E269](<Desktop/ECS/P67/P67H2-A3/D28598A0850C/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/417453E269>) |
| 256f:c62e | 3Dconnexion      | SpaceMouse Wireless (cabled)         | 3     | usbhid     | [399CC50503](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/71A8F8E0695E/FEDORA-37/5.17.0-0.RC6.109.FC37.X86_64/X86_64/399CC50503>) |
| 2f24:0050 |                  | GAME FOR WINDOWS                     | 3     | xpad       | [91B2A03D70](<Desktop/ASRock/B450M/B450M Steel Legend/B4499FBFB597/POP!_OS-21.04/5.15.6-TKG-PDS/X86_64/91B2A03D70>) |
| 044f:0407 | ThrustMaster     | TCA Q-Eng 1&2                        | 2     | usbhid     | [82BD12BCF4](<Desktop/MSI/MS-7/MS-7C75/EC93D8F2ABA9/DEBIAN-UNSTABLE/5.15.0-2-AMD64/X86_64/82BD12BCF4>) |
| 044f:b323 | ThrustMaster     | Dual Trigger 3-in-1 (PC Mode)        | 2     | usbhid     | [D36AA4ED19](<Desktop/ASUSTek Computer/M4/M4A87TD-USB3/DB37E805A8E6/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/D36AA4ED19>) |
| 044f:d007 | ThrustMaster     | T Mini Wireless                      | 2     | usbhid     | [E06775BBD6](<Desktop/Gigabyte Technology/Z77/Z77-DS3H/7CFF88802F8D/UBUNTU-21.04/5.11.0-31-GENERIC/X86_64/E06775BBD6>) |
| 046d:c211 | Logitech         | iTouch Cordless Receiver             | 2     | usbhid     | [DD082AFE88](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-A/E84BFF3E9AB1/UBUNTU-21.04/5.11.0-36-GENERIC/X86_64/DD082AFE88>) |
| 054c:03d5 | Sony             | PlayStation Move motion controller   | 2     | usbhid     | [32805E80B1](<Desktop/ASUSTek Computer/Rampage/Rampage IV BLACK EDITION/A3D2718BE858/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/32805E80B1>) |
| 068e:00f1 | CH Products      | Pro Throttle                         | 2     | usbhid     | [8C48770CA6](<Desktop/ASUSTek Computer/Maximus/Maximus IX HERO/334AB95654E3/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/8C48770CA6>) |
| 06a3:0006 | Saitek           | Cyborg Gold Joystick                 | 2     | usbhid     | [55B76D666C](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/9252CC15DCB7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/55B76D666C>) |
| 099a:7010 | Zippy Technology | Gaming Keyboard                      | 2     | usbhid     | [BCACEFE427](<Notebook/Dell/Latitude/Latitude E6400/822A42E7F792/XUBUNTU-16.04/4.15.0-169-GENERIC/X86_64/BCACEFE427>) |
| 0e6f:0139 | Logic3           | Afterglow Wired Controller for Xb... | 2     | xpad       | [17ACFC90D4](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/F459445B4FC0/GNOME-OS-3.38/5.7.14/X86_64/17ACFC90D4>) |
| 0e6f:0162 | Logic3           | PDP Wired Controller for Xbox One    | 2     | xpad       | [09520E9204](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/2AC8C310DDE0/ARCH/5.4.0-RC7-1-AMD-STAGING-DRM-NEXT-GIT-01902-G38419046943F/X86_64/09520E9204>) |
| 0e6f:02da | Logic3           | Afterglow Wired Controller for Xb... | 2     | xpad       | [B60FD7636C](<Desktop/Others/Others/Others/96A3F3A2B406/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/B60FD7636C>) |
| 0eb7:183b | Endor            | ClubSportPedal                       | 2     | usbhid     | [B2DE3AF507](<Desktop/MSI/MEG/MEG Z490 Infinite X/09B7D7DA3998/XUBUNTU-20.04/5.4.0-45-GENERIC/X86_64/B2DE3AF507>) |
| 11ff:001b |                  | LS PC Controller                     | 2     | usbhid     | [B52E5BED36](<Notebook/Dell/Inspiron/Inspiron 13-5378/979FFC27BB65/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/B52E5BED36>) |
| 20bc:5656 | ShenZhen Shan... | Gamesir-T4w 1.39                     | 2     | usbhid     | [936BD6BF44](<Desktop/Acidanthera/MacPro7/MacPro7,1/B475B33ADA9A/MANJARO/5.14.16-214-TKG-PDS/X86_64/936BD6BF44>) |
| 20d6:ca6d | Unknown (BDA)    | Pro Ex                               | 2     | usbhid     | [858605237B](<Desktop/Intel/DP45SG/DP45SG AAE27733-404/28E8883E65EB/KDE-NEON-20.04/5.4.0-54-GENERIC/X86_64/858605237B>) |

### Mfp (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 03f0:042a | Hewlett-Packard  | LaserJet M1132 MFP                   | 45    | usblp      | [29CA9095C4](<Desktop/Gigabyte Technology/B85/B85M-D3V-A/12D3DD49427D/FEDORA-35/5.16.5-200.FC35.X86_64/X86_64/29CA9095C4>) |
| 03f0:222a | Hewlett-Packard  | LaserJet Pro MFP M125nw              | 33    | usblp      | [515BA182FF](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M EVO/4062631E0DA6/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/515BA182FF>) |
| 03f0:3b17 | Hewlett-Packard  | LaserJet M1005 MFP                   | 30    | usblp      | [09B482F622](<Desktop/ASRock/H470/H470M-HDV/E059DC95E295/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/09B482F622>) |
| 03f0:5617 | Hewlett-Packard  | LaserJet M1120 MFP                   | 23    | usblp      | [BFADFAD800](<Desktop/ASUSTek Computer/P5E-VM/P5E-VM SE/DA8F7FC1AED9/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/BFADFAD800>) |
| 03f0:bf2a | Hewlett-Packard  | LaserJet MFP M28-M31                 | 19    | usblp      | [CE783FBB35](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/92FDA53E9838/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/CE783FBB35>) |
| 03f0:622a | Hewlett-Packard  | LaserJet MFP M129-M134               | 17    | usblp      | [FCF69ABC8F](<Desktop/Supermicro/X7/X7DA8/DCC6E9D73FBB/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/FCF69ABC8F>) |
| 03f0:ad2a | Hewlett-Packard  | ColorLaserJet MFP M278-M281          | 14    | usblp      | [AFC31097CD](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/7DD783E57123/MANJARO-21.2.3/5.15.19-1-MANJARO/X86_64/AFC31097CD>) |
| 03f0:052a | Hewlett-Packard  | LaserJet M1212nf MFP                 | 12    | usblp      | [5B4619D24C](<Notebook/Acer/Extensa/Extensa 2540/73DD249CF2CD/ENDLESS-3.9.3/5.8.0-14-GENERIC/X86_64/5B4619D24C>) |
| 04b8:084d | Seiko Epson      | PX-402A [Stylus SX115/Stylus NX11... | 12    | usblp      | [17DD3A82AE](<Desktop/Gigabyte Technology/G31/G31M-S2L/673E549E404E/ROSA-2016.1/5.4.83-GENERIC-2ROSA-I586/I686/17DD3A82AE>) |
| 0924:3cef | Xerox            | Phaser 3100MFP                       | 12    | usblp      | [7AB9D987EB](<Desktop/ASUSTek Computer/M2N68-AM/M2N68-AM Plus/CCBD4EE6AAA6/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-X86_64/X86_64/7AB9D987EB>) |
| 04b8:082f | Seiko Epson      | PX-A620 [Stylus CX3900/DX4000/DX4... | 11    | usblp      | [EC63D82626](<Desktop/Gigabyte Technology/M57/M57SLI-S4/65DEAA0AF9C4/LINUXMINT-20.1/5.4.0-92-GENERIC/X86_64/EC63D82626>) |
| 04b8:083f | Seiko Epson      | Stylus CX4300/CX4400/CX5500/CX560... | 10    | usblp      | [9473725930](<Desktop/Gigabyte Technology/H81/H81M-DS2/59E02CFB88AB/UBUNTU-20.04/5.4.0-65-GENERIC/X86_64/9473725930>) |
| 0924:42af | Xerox            | WorkCentre 3045B                     | 10    | usblp      | [989A2EAABB](<Notebook/eMachines/eME/eME732/0C7DCAFE269A/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/989A2EAABB>) |
| 03f0:3b2a | Hewlett-Packard  | Color LaserJet MFP M277dw            | 8     | usblp      | [F04139C372](<Desktop/Gigabyte Technology/GA-MA790/GA-MA790XT-UD4P/49FE29E72D57/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/F04139C372>) |
| 03f0:5717 | Hewlett-Packard  | LaserJet M1120n MFP                  | 7     | usblp      | [44103309B6](<Desktop/ASUSTek Computer/P7/P7H55/792D1CECDC45/LINUXMINT-20.2/5.4.0-80-GENERIC/X86_64/44103309B6>) |
| 0482:0495 | Kyocera          | FS-1020MFP                           | 6     | usblp      | [71AEB24115](<Desktop/Gigabyte Technology/H170/H170-HD3/63B7D39E045B/DEBIAN-10/4.19.0-17-AMD64/X86_64/71AEB24115>) |
| 04b8:0841 | Seiko Epson      | PX-401A [ME 300/Stylus NX100]        | 6     | usblp      | [FD1407E384](<Desktop/ASRock/ALiveXFire-eSATA/ALiveXFire-eSATA2/EE695EC2526C/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/FD1407E384>) |
| 03f0:062a | Hewlett-Packard  | LaserJet 100 colorMFP M175a          | 5     | usblp      | [B03AAAB88C](<Desktop/Huanan/X99/X99-F8/AB9A5F53D1A0/POP!_OS-21.10/5.15.5-76051505-GENERIC/X86_64/B03AAAB88C>) |
| 03f0:932a | Hewlett-Packard  | LaserJet Pro MFP M26a                | 5     | usblp      | [22B1E02DCD](<Desktop/ASRock/N68C-S/N68C-S UCC/89D5A7956623/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/22B1E02DCD>) |
| 03f0:f22a | Hewlett-Packard  | Laser MFP 135a                       | 5     | usblp      | [00F5CC73FE](<Desktop/Dell/OptiPlex/OptiPlex 7070/D3E0146ABA66/FEDORA-35/5.14.17-301.FC35.X86_64/X86_64/00F5CC73FE>) |
| 0924:42da | Xerox            | WorkCentre 3025                      | 5     | usblp      | [9D9C4FE241](<Desktop/Fujitsu/ESPRIMO/ESPRIMO C910/A231FFA61548/KUBUNTU-20.04/5.4.0-100-GENERIC/X86_64/9D9C4FE241>) |
| 03f0:012a | Hewlett-Packard  | LaserJet M1536dnf MFP                | 4     | usblp      | [4DECE01140](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F5A28CCF7A12/UBUNTU-21.10/5.13.0-1010-RASPI/AARCH64/4DECE01140>) |
| 03f0:2d2a | Hewlett-Packard  | LaserJet Pro MFP M225dn              | 4     | usblp      | [1B4BF985A0](<Desktop/MSI/MS-7/MS-7A78/37EFA54F640E/GENTOO-2.6/5.4.32-DESK/X86_64/1B4BF985A0>) |
| 03f0:322a | Hewlett-Packard  | LaserJet Pro MFP M127fw              | 4     | usblp      | [A2E80395F1](<Mini Pc/Apple/Macmini3/Macmini3,1/89AEF2A6D7AC/DEBIAN-11/5.10.0-9-AMD64/X86_64/A2E80395F1>) |
| 0482:0497 | Kyocera          | FS-1025MFP                           | 4     | usblp      | [6C8DDCD99B](<Desktop/Intel/H55/H55 INTEL/B951CF589723/MANJARO-21.0.7/5.10.42-1-MANJARO/X86_64/6C8DDCD99B>) |
| 04b8:080e | Seiko Epson      | PX-A550 [CX-3500/3600/3650 MFP]      | 4     | usblp      | [D34B022996](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/6F4F5EDCBFEB/CENTOS-7/5.4.96-200.EL7.X86_64/X86_64/D34B022996>) |
| 03f0:0e2a | Hewlett-Packard  | Smart Install                        | 3     | uas, us... | [B027C83F03](<Desktop/MSI/MS-7/MS-7B22/4696DE406054/UBUNTU-20.04/5.8.0-41-GENERIC/X86_64/B027C83F03>) |
| 03f0:142a | Hewlett-Packard  | LaserJet 400 MFP M425dn              | 3     | usblp      | [BB50D755A2](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/5830A4521D35/UBUNTU-20.04/5.4.0-47-GENERIC/X86_64/BB50D755A2>) |
| 03f0:242a | Hewlett-Packard  | Color LaserJet Pro MFP M176n         | 3     | usblp      | [769CB653F7](<Desktop/ECS/G31/G31T-M9/1185D58E3BB7/DEBIAN-11/5.10.0-2-AMD64/X86_64/769CB653F7>) |
| 0924:3d6f | Xerox            | Phaser 6020                          | 3     | usblp      | [79A097BF6F](<Desktop/Gigabyte Technology/X48/X48-DS5/C5305DDA638D/UBUNTU-18.04/4.15.0-47-GENERIC/X86_64/79A097BF6F>) |
| 0924:42db | Xerox            | WorkCentre 3215                      | 3     | usblp      | [0F22425E10](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/44EFF2E7D2F9/UBUNTU-18.04/4.15.0-118-GENERIC/X86_64/0F22425E10>) |
| 0924:42dc | Xerox            | WorkCentre 3225                      | 3     | usblp      | [585BFD5E2A](<Desktop/ASUSTek Computer/P5/P5K/CEA28403C3D8/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/585BFD5E2A>) |
| 03f0:342a | Hewlett-Packard  | Color LaserJet MFP M476dn            | 2     | usblp      | [B0C6FDF764](<Desktop/MSI/MS-7/MS-7B79/CD62FA4BE558/DEBIAN-11/5.15.0-0.BPO.2-AMD64/X86_64/B0C6FDF764>) |
| 03f0:5817 | Hewlett-Packard  | LaserJet M1319f MFP                  | 2     | usblp      | [DD0A730661](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S16X0J/C7CF1EEC17B0/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/DD0A730661>) |
| 03f0:5a2a | Hewlett-Packard  | LaserJet MFP M426fdw                 | 2     | usblp      | [D00254CBC5](<Desktop/Dell/XPS/XPS 8700/6A5D775C6993/FEDORA-31/5.5.5-200.FC31.X86_64/X86_64/D00254CBC5>) |
| 03f0:642a | Hewlett-Packard  | LaserJet MFP M227-M231               | 2     | usblp      | [B7CB0C276C](<Desktop/MSI/MS/MS-7885/A4EBDE2BF531/KDE-NEON-20.04/5.11.0-27-GENERIC/X86_64/B7CB0C276C>) |
| 03f0:af2a | Hewlett-Packard  | ColorLaserJet MFP M178-M181          | 2     | usblp      | [7B9F86430D](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 2i 20WK00AJGE/F5EC0165A139/LINUXMINT-20.2/5.10.0-1051-OEM/X86_64/7B9F86430D>) |
| 04b8:0818 | Seiko Epson      | Stylus CX3700/CX3800/DX3800          | 2     | usblp      | [D4567C6F8A](<Notebook/ASUSTek Computer/K55/K55VD/A104E9D59AE9/UBUNTU-20.10/5.8.0-29-GENERIC/X86_64/D4567C6F8A>) |
| 0924:42c4 | Xerox            | WorkCentre 3615                      | 2     | usblp      | [0BF7A6E91D](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8740w/C619FE23190E/ROSA-2014.1/4.0.4-NRJ-DESKTOP-1ROSA-X86_64/X86_64/0BF7A6E91D>) |
| 413c:523b | Dell             | B1265dfw Mono MFP                    | 2     | usblp      | [26B6148847](<Desktop/Medion/MS/MS-7707/B32C8E3A24E6/LINUXMINT-20.2/5.11.0-34-GENERIC/X86_64/26B6148847>) |
| 413c:590b | Dell             | MFP                                  | 2     | usblp      | [B56038968A](<Desktop/Gigabyte Technology/B75/B75M-D3H/20CE70C40451/POP!_OS-21.04/5.15.11-76051511-GENERIC/X86_64/B56038968A>) |
| 03f0:0970 | Hewlett-Packard  | ColorLaserJet MFP M282-M285          | 1     | usblp      | [0AD4AA43AA](<Desktop/ASUSTek Computer/A68/A68HM-K/938BA8CF2C8C/LINUXMINT-20.1/5.4.0-65-GENERIC/X86_64/0AD4AA43AA>) |
| 03f0:1d2a | Hewlett-Packard  | Color LaserJet flow MFP M880         | 1     | usblp      | [9F2622FF85](<Notebook/Lenovo/G570/G570 20079/92B1F90D7EAE/ROSA-2014.1/3.14.39-NRJ-DESKTOP-4ROSA-X86_64/X86_64/9F2622FF85>) |
| 03f0:252a | Hewlett-Packard  | LaserJet 500 colorMFP M570dw         | 1     | usblp      | [8EA70251FB](<Notebook/Lenovo/G570/G570 20079/92B1F90D7EAE/ROSA-2014.1/3.14.39-NRJ-DESKTOP-4ROSA-X86_64/X86_64/8EA70251FB>) |
| 03f0:2e2a | Hewlett-Packard  | LaserJet Pro MFP M435nw              | 1     | usblp      | [A457D54FAD](<Notebook/Lenovo/G570/G570 20079/92B1F90D7EAE/ROSA-2014.1/3.14.39-NRJ-DESKTOP-4ROSA-X86_64/X86_64/A457D54FAD>) |
| 03f0:362a | Hewlett-Packard  | Officejet Color FlowMFP X585         | 1     | usblp      | [4966DF06F4](<Notebook/Lenovo/G570/G570 20079/92B1F90D7EAE/ROSA-2014.1/3.14.39-NRJ-DESKTOP-4ROSA-X86_64/X86_64/4966DF06F4>) |
| 03f0:442a | Hewlett-Packard  | Color LaserJet Flow MFP M680         | 1     | usblp      | [BF4C79032E](<Notebook/Lenovo/G570/G570 20079/92B1F90D7EAE/ROSA-2014.1/3.14.39-NRJ-DESKTOP-4ROSA-X86_64/X86_64/BF4C79032E>) |
| 03f0:4e17 | Hewlett-Packard  | Color LaserJet CM1312 MFP            | 1     | usblp      | [426F11F2D2](<Desktop/ASUSTek Computer/P7H55-M/P7H55-M PRO/AD2171FDE073/LINUXMINT-19.1/4.15.0-140-GENERIC/X86_64/426F11F2D2>) |
| 03f0:532a | Hewlett-Packard  | LaserJet MFP M426dw                  | 1     | usblp      | [93A67E4976](<Desktop/Lenovo/ThinkCentre/ThinkCentre M900 10FCS0V500/87E1264133C2/LINUXMINT-19.1/4.15.0-58-GENERIC/X86_64/93A67E4976>) |
| 03f0:5a17 | Hewlett-Packard  | Color LaserJet CM2320nf MFP          | 1     | usblp      | [946BA8AA98](<Desktop/Hewlett-Packard/Compaq/Compaq dc7700p Convertible Minitower/DC7D0138AC31/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/946BA8AA98>) |

### Miscellaneous (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 2d95:600a | vivo             | 1907                                 | 11    | rndis_host | [12C90ED760](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec2xxx/54742165F121/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/12C90ED760>) |
| 2e04:c008 | HMD Global       | Tethering Network Interface          | 5     | rndis_host | [38785DD89C](<Desktop/Lenovo/IdeaCentre/IdeaCentre 510S-07ICK 90LX0091IN/ADCE86539D8B/DEBIAN-11/5.10.0-10-AMD64/X86_64/38785DD89C>) |
| 1390:5a01 | TOMTOM           | GO Professional 6250                 | 2     | rndis_host | [BE27200090](<Notebook/Lenovo/V145-15AST/V145-15AST 81MT/83C010F69464/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/BE27200090>) |
| 1ab2:0001 | Allied Vision    | Vision device                        | 2     |            | [2CDAC4454D](<Server/Supermicro/SYS-7049/SYS-7049GP-TRT/B2747FDA575F/UBUNTU-18.04/5.16.8-051608-GENERIC/X86_64/2CDAC4454D>) |
| 1e10:4000 | Point Grey Re... | U3V camera                           | 2     |            | [2BC5FA3C88](<Notebook/ASUSTek Computer/X555/X555LJ/19545E88E836/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/2BC5FA3C88>) |
| 0bb4:0b0c | HTC (High Tec... | Elf / Touch / P3450 / T-Mobile MD... | 1     | rndis_w... | [5E75A35A7D](<Notebook/Hewlett-Packard/Pavilion/Pavilion zx5000/5ED9898B7A22/LUBUNTU-18.04/4.15.0-20-GENERIC/I686/5E75A35A7D>) |
| 1004:6343 | LG Electronics   | LM-V600                              | 1     | rndis_h... | [B5C18575BF](<Desktop/Gigabyte Technology/H61/H61M-S2-B3/9D85AF0476EC/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/B5C18575BF>) |
| 1410:b022 | Novatel Wireless | MiFi 7000                            | 1     | rndis_h... | [9F5C7C160A](<Notebook/Sony/VPCF136/VPCF136FM/C939FAAB434A/OPENSUSE-20200528/5.6.14-1-DEFAULT/X86_64/9F5C7C160A>) |
| 2676:ba02 | Basler           | ace                                  | 1     |            | [F65C6B2C80](<Notebook/Dell/XPS/XPS 15 9570/56E85BDE9BD2/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/F65C6B2C80>) |
| 2676:ba05 | Basler           | a2A1920-160ucBAS                     | 1     |            | [273BC677CD](<System On Chip/Nvidia/Tegra/Tegra/C5692083B3F9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/273BC677CD>) |
| 2bdf:0001 | Hikrobot         | MV-CB013-20UC-C                      | 1     |            | [2690174808](<Desktop/ASUSTek Computer/PRIME/PRIME B460M-A/95F64D371370/LINUXMINT-20/5.4.0-26-GENERIC/X86_64/2690174808>) |

### Modem (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 12d1:1506 | Huawei Techno... | Modem/Networkcard                    | 415   | uas, us... | [E8067701ED](<Desktop/ASRock/H55/H55M-LE/EBF1969A1344/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/E8067701ED>) |
| 27c6:5395 | Shenzhen Good... | Fingerprint Reader                   | 346   | cdc_acm    | [3F8FE40793](<Notebook/Dell/XPS/XPS 15 9570/FFC4E3644992/UBUNTUSTUDIO-21.10/5.13.0-30-GENERIC/X86_64/3F8FE40793>) |
| 27c6:5301 | Shenzhen Good... | Fingerprint Reader                   | 258   | cdc_acm    | [8248B17F01](<Notebook/Dell/Vostro/Vostro 5471/BF689F2C5926/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/8248B17F01>) |
| 27c6:5385 | Shenzhen Good... | Fingerprint Reader                   | 184   | cdc_acm    | [EFC6123D49](<Notebook/Dell/XPS/XPS 13 9380/AD3D35DC38DC/SOLUS-4.3/5.14.21-210.CURRENT/X86_64/EFC6123D49>) |
| 0bdb:1911 | Ericsson Busi... | F5521gw                              | 139   | cdc_acm    | [508A68F09E](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4290EC5/45C5B8282921/KUBUNTU-18.04/4.15.0-169-GENERIC/X86_64/508A68F09E>) |
| 0bdb:1926 | Ericsson Busi... | H5321 gw Mobile Broadband Driver     | 130   | cdc_acm    | [CEEC77F198](<Notebook/Lenovo/ThinkPad/ThinkPad T530 2359CTO/2A7FFCF59535/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/CEEC77F198>) |
| 0bdb:193e | Ericsson Busi... | N5321 gw                             | 89    | cdc_acm    | [6D0CD0F4B9](<Notebook/Lenovo/ThinkPad/ThinkPad T540p 20BE005YMH/B6072358711D/NIXOS-22.05/5.15.26/X86_64/6D0CD0F4B9>) |
| 2341:0043 | Arduino SA       | Uno R3 (CDC ACM)                     | 70    | cdc_acm    | [DDDE911C72](<Desktop/Supermicro/X7/X7SBL/68DDA7FD7ABB/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/DDDE911C72>) |
| 413c:818d | Dell             | DW5550                               | 70    | cdc_acm    | [05D9080C0C](<Notebook/Dell/Latitude/Latitude E6230/03403DA90720/FEDORA-35/5.15.18-200.FC35.X86_64/X86_64/05D9080C0C>) |
| 0bdb:1900 | Ericsson Busi... | F3507g Mobile Broadband Module       | 60    | cdc_acm... | [6A5D0584BD](<Notebook/Lenovo/ThinkPad/ThinkPad T400s 2808D9G/071BA4158C4D/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/6A5D0584BD>) |
| 03f0:3d1d | Hewlett-Packard  | hs2350 HSPA+ MobileBroadband         | 57    | cdc_acm    | [C757E559B0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2570p/6D941852B098/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/C757E559B0>) |
| 12d1:1436 | Huawei Techno... | Broadband stick                      | 57    | usb_sto... | [9F4F77F51D](<Notebook/Apple/MacBook7/MacBook7,1/7DBA8502BAB7/PARROT-5.0/5.14.0-9PARROT1-AMD64/X86_64/9F4F77F51D>) |
| 03f0:3a1d | Hewlett-Packard  | hs2340 HSPA+ mobile broadband        | 51    | cdc_acm    | [6644889929](<Notebook/Hewlett-Packard/ProBook/ProBook 6560b/5843CB495648/UBUNTU-20.04/5.4.0-96-GENERIC/X86_64/6644889929>) |
| 413c:818e | Dell             | DW5560 miniPCIe HSPA+ Mobile Broa... | 44    | cdc_acm    | [E32F5B40A1](<Notebook/Dell/Latitude/Latitude E6430/CF0301C655CD/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/E32F5B40A1>) |
| 413c:8184 | Dell             | F3607gw v2 Mobile Broadband Module   | 43    | cdc_acm    | [D4FA7879A4](<Notebook/Dell/Latitude/Latitude E6410/6BC9157A0724/UBUNTU-18.04/4.15.0-171-GENERIC/I686/D4FA7879A4>) |
| 12d1:1001 | Huawei Techno... | E161/E169/E620/E800 HSDPA Modem      | 41    | usb_sto... | [B673072FBB](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK A3510/F0BA03F18441/XUBUNTU-21.10/5.13.0-23-GENERIC/X86_64/B673072FBB>) |
| 413c:8147 | Dell             | F3507g Mobile Broadband Module       | 41    | cdc_ether  | [3EFD166E47](<Notebook/Dell/Latitude/Latitude E4300/0CBECFA2694E/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/3EFD166E47>) |
| 27c6:5381 | Shenzhen Good... | Fingerprint Reader                   | 36    | cdc_acm    | [33819E0316](<Notebook/Dell/G5/G5 5587/C490686C7FE3/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/33819E0316>) |
| 1209:1776 | InterBiometrics  | Io                                   | 29    | system7... | [2BA8489718](<Desktop/System76/Thelio/Thelio/D6BA7584D74D/POP!_OS-20.04/5.15.11-76051511-GENERIC/X86_64/2BA8489718>) |
| 12d1:1003 | Huawei Techno... | E220 HSDPA Modem / E230/E270/E870... | 27    | usb_sto... | [10ACFF551D](<Notebook/Hewlett-Packard/Presario/Presario CQ56/25C7CF1173E5/LINUXMINT-20.2/5.11.0-38-GENERIC/X86_64/10ACFF551D>) |
| 12d1:140c | Huawei Techno... | E180v                                | 27    | usb_sto... | [37EFD6FC5E](<Notebook/ASUSTek Computer/X205/X205TA/5ED1180BCDB4/DEBIAN-10/5.10.0-8-AMD64/X86_64/37EFD6FC5E>) |
| 1546:01a7 | U-Blox           | [u-blox 7]                           | 27    | cdc_acm    | [6CEC0DB416](<Notebook/Dell/Inspiron/Inspiron N5110/2B4CE78E3ACA/DEBIAN-11/4.19.0-6-AMD64/X86_64/6CEC0DB416>) |
| 0658:0200 | Sigma Designs    | Aeotec Z-Stick Gen5 (ZW090) - UZB    | 21    | cdc_acm    | [53D4957635](<Desktop/ASUSTek Computer/ROG/ROG STRIX B350-F GAMING/A0BCB3D464DC/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/53D4957635>) |
| 0424:274d | Microchip Tec... | HTC Hub Controller                   | 19    | cdc_acm    | [8F7C57B03F](<Desktop/ASUSTek Computer/Maximus/Maximus VIII HERO/734460839920/ARCH-ROLLING/5.16.1-ZEN1-1-ZEN/X86_64/8F7C57B03F>) |
| 12d1:1570 | Huawei Techno... | Mobile Broadband Module              | 19    | option     | [EE9E63AB7C](<Notebook/Sony/SVD1321/SVD13213SGW/5BAC9DD4DC6F/KUBUNTU-11/5.13.0-27-GENERIC/X86_64/EE9E63AB7C>) |
| 1546:01a8 | U-Blox           | [u-blox 8]                           | 19    | cdc_acm    | [64EF1D30C3](<Notebook/Dell/Latitude/Latitude 7424 Rugged Extreme/8E222DD36428/DEBIAN-TESTING/5.15.0-3-AMD64/X86_64/64EF1D30C3>) |
| 0483:5740 | STMicroelectr... | Virtual COM Port                     | 18    | cdc_acm    | [36434C8979](<Server/Supermicro/Super/Super Server/64BD44B140C6/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/36434C8979>) |
| 04e8:6872 | Samsung Elect... | Kiera                                | 16    | cdc_acm    | [A593B663F7](<Notebook/Samsung Electronics/NC210/NC210-NC110/8309E1560AC2/LINUXMINT-19.1/4.15.0-169-GENERIC/X86_64/A593B663F7>) |
| 1cf1:0030 | Dresden Elekt... | ZigBee gateway [ConBee II]           | 16    | cdc_acm    | [DFD0CB667C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/0C45B1FBE800/DEBIAN-11/5.10.0-11-AMD64/X86_64/DFD0CB667C>) |
| 04d8:00df | Microchip Tec... | MCP2200 USB Serial Port Emulator     | 14    | cdc_acm    | [FC03E1E42F](<Desktop/ASUSTek Computer/ROG/ROG Maximus XI FORMULA/C00810BA471C/KALI-2022.1/5.15.0-KALI3-AMD64/X86_64/FC03E1E42F>) |
| 0451:16a8 | Texas Instrum... | CC2531 ZigBee                        | 13    | cdc_acm    | [D5BA9DEED5](<Desktop/Lenovo/ThinkCentre/ThinkCentre M72e 3264AN3/787E5A174123/DEBIAN-11/5.13.19-4-PVE/X86_64/D5BA9DEED5>) |
| 12d1:1404 | Huawei Techno... | EM770W miniPCI WCDMA Modem           | 13    | usb_sto... | [89B02002A5](<Notebook/Lenovo/G460e/G460e 1049/BFAE0055F4C6/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/89B02002A5>) |
| 2833:0051 | Oculus VR        | Rift S                               | 13    | usbhid     | [FF74ABC44D](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-F GAMING/435ABB9A7CC3/KUBUNTU-21.10/5.13.0-28-GENERIC/X86_64/FF74ABC44D>) |
| 2341:0042 | Arduino SA       | Mega 2560 R3 (CDC ACM)               | 12    | cdc_acm    | [C06C350DC3](<Notebook/Dell/Inspiron/Inspiron 3180/84F1EF9AF83E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/C06C350DC3>) |
| 04e2:1410 | Exar             | XR21V1410 USB-UART IC                | 11    | cdc_acm... | [497E370FC3](<Desktop/LattePanda/Alpha/Alpha/2214BBB4C9CB/ENDEAVOUROS/5.10.88-2-LTS/X86_64/497E370FC3>) |
| 1366:0105 | SEGGER           | J-Link                               | 11    | cdc_acm    | [B0CF9AA220](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Notebook/0C8B2E15DFD2/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/B0CF9AA220>) |
| 2548:1002 | Pulse-Eight      | CEC Adapter                          | 10    | cdc_acm    | [6D6980D0BB](<Desktop/Shuttle/XH61/XH61V/2F96D84F579F/LINUXMINT-20.3/5.13.0-25-GENERIC/X86_64/6D6980D0BB>) |
| 0e8d:0003 | MediaTek         | MT6227 phone                         | 9     | cdc_acm... | [03BA9FDF17](<Desktop/Gigabyte Technology/Z490/Z490 AORUS PRO AX/78E075636E6E/DEBIAN-11/5.10.0-9-AMD64/X86_64/03BA9FDF17>) |
| 19d2:1515 | ZTE WCDMA Tec... | MF195                                | 8     | cdc_acm    | [3954E61E9A](<Notebook/Lenovo/G505s/G505s 20255/D4F5F16D51F5/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/3954E61E9A>) |
| 1c11:b04d | Input Club       | ErgoDox Infinity                     | 8     | usbhid     | [856134876D](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE/A59830624A05/MANJARO-21.2RC/5.15.6-2-MANJARO/X86_64/856134876D>) |
| 2886:8027 | Seeed Technology | Seeeduino_Cortex_M0+                 | 8     | cdc_acm    | [FB722F7D84](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/51D031DDD4C7/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/FB722F7D84>) |
| 1209:2201 | InterBiometrics  | Dygma Shortcut Keyboard              | 7     | usbhid     | [424F798E37](<Desktop/MSI/MS-7/MS-7A66/3A67859906B6/MANJARO/5.15.7-1-RT23-MANJARO/X86_64/424F798E37>) |
| 12d1:14ac | Huawei Techno... | E815                                 | 7     | option     | [8B53FFA4DF](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro MT PC/6CBF3B8FF40E/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/8B53FFA4DF>) |
| 2341:0001 | Arduino SA       | Uno (CDC ACM)                        | 7     | cdc_acm    | [C3E5771D2F](<Desktop/Fujitsu/D3417-B2/D3417-B2 S26361-D3417-B2/B2B95914F6B0/UBUNTU-20.04/5.4.0-62-GENERIC/X86_64/C3E5771D2F>) |
| 0930:1314 | Toshiba          | F5521gw                              | 6     | cdc_acm    | [CD13F4B4AB](<Notebook/Toshiba/TECRA/TECRA R850/B8DA5C76BE1A/WINDOWSFX-11/5.11.0-46-GENERIC/X86_64/CD13F4B4AB>) |
| 0930:1319 | Toshiba          | H5321gw                              | 6     | cdc_acm    | [9816B952D7](<Notebook/Toshiba/PORTEGE/PORTEGE Z830/2160F388A770/LINUXMINT-20.1/5.4.0-67-GENERIC/X86_64/9816B952D7>) |
| 0bdb:190a | Ericsson Busi... | F3307 Mobile Broadband Module        | 6     | cdc_acm    | [D706658FF8](<Notebook/Acer/TravelMate/TravelMate 6594/B227FF345066/UBUNTU-20.04/5.4.0-65-GENERIC/X86_64/D706658FF8>) |
| 0483:a26d | STMicroelectr... | USB Watchdog                         | 5     | cdc_acm    | [F59CE2E29B](<Desktop/Gigabyte Technology/B450M/B450M S2H/4E00B881235B/UBUNTU-18.04/4.15.0-162-GENERIC/X86_64/F59CE2E29B>) |
| 04e2:1411 | Exar             | XR21B1411                            | 5     | cdc_acm... | [6D72E2608A](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Small Form Factor/E92C01254E0F/DEBIAN-11/5.10.0-11-AMD64/X86_64/6D72E2608A>) |
| 04e8:6773 | Samsung Elect... | HSPA Modem                           | 5     | cdc_acm    | [1A88380AF6](<Notebook/Samsung Electronics/N/N130/D8A313DD4B42/TRISQUEL-9.0/4.15.0-161-GENERIC/I686/1A88380AF6>) |

### Net/ethernet (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0fe6:9900 | ICS Advent       | 10/100M LAN                          | 24    | cdc_ether  | [ECCFE5B35C](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20YDS00G00/AB2C6D7EBED9/DEBIAN-11/5.16.0-3-AMD64/X86_64/ECCFE5B35C>) |
| 0bda:8156 | Realtek Semic... | USB 10/100/1G/2.5G LAN               | 20    | cdc_ncm    | [6536E752DD](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/D6FDC6C0C087/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/6536E752DD>) |
| 03f0:911d | Hewlett-Packard  | lt4211 Gobi 4G Module                | 7     | cdc_ether  | [0AD916110D](<Notebook/Hewlett-Packard/EliteBook/EliteBook Revolve 810 G3/29EE6BCF3B2A/KDE-NEON-20.04/5.11.0-38-GENERIC/X86_64/0AD916110D>) |
| 17e9:430f | DisplayLink      | Kensington Dock (Composite Device)   | 5     | cdc_ncm    | [F74F7D2A25](<Desktop/Gigabyte Technology/H81/H81M-HD3/4F3EDB333543/KDE-NEON-20.04/5.11.0-41-GENERIC/X86_64/F74F7D2A25>) |
| 17e9:436c | DisplayLink      | Dell D1000 USB3.0 Dock               | 5     | cdc_ncm    | [13C53062B6](<Notebook/Dell/Latitude/Latitude 5320/2BFC68DC749F/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/13C53062B6>) |
| 2eca:c101 | Aquantia         | 5G USB Ethernet Adapter              | 5     | aqc111     | [51293D0B71](<Desktop/MSI/MS-7/MS-7C34/E6E0A11BC9D5/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/51293D0B71>) |
| 17e9:430a | DisplayLink      | HP Port Replicator (Composite Dev... | 3     | cdc_ncm    | [F02A4A5E93](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G2 MINI/215824C09548/CENTOS-8/4.18.0-240.1.1.EL8_3.X86_64/X86_64/F02A4A5E93>) |
| 17e9:4340 | DisplayLink      | ThinkPad USB 3.0 Ultra Dock          | 3     | cdc_ncm... | [4365BDF905](<Notebook/Lenovo/ThinkPad/ThinkPad P15 Gen 1 20SUS26R00/98F6F4311C87/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/4365BDF905>) |
| 17e9:6011 | DisplayLink      | Plugable UD-6950 Docking Station     | 3     | snd_usb... | [F69FADFB4B](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus M16 GU603HM_GU603HM/89BB5FCE2323/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/F69FADFB4B>) |
| 17ef:721e | Lenovo           | Powered Hub                          | 3     | r8152      | [F4F26A9357](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S27C00/4FABB701A0A0/UBUNTU-20.04/5.8.0-63-GENERIC/X86_64/F4F26A9357>) |
| 0424:9500 | Microchip Tec... | LAN9500/LAN9500i                     | 2     | smsc95xx   | [2F9F2D0497](<Notebook/Panasonic/CF-53/CF-53JWX1CFG/02DE21A6B399/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/2F9F2D0497>) |
| 0424:9e00 | Microchip Tec... | LAN9500A/LAN9500Ai                   | 2     | smsc95xx   | [9F69E439BC](<Desktop/ASUSTek Computer/PRIME/PRIME H310T R2.0/62C346E7C248/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/9F69E439BC>) |
| 045e:09a0 | Microsoft        | RTL8153B GigE [Surface Ethernet A... | 2     | cdc_ether  | [25CA2E2C75](<Tablet/Microsoft/Surface/Surface Pro 7/1EAA0CAAC758/DEBIAN-11/5.10.0-9-AMD64/X86_64/25CA2E2C75>) |
| 050d:0128 | Belkin Compon... | Belkin USB 3.0 Hub                   | 2     | ax88179... | [DB38480B2F](<Notebook/Dell/Inspiron/Inspiron 5570/385FEAFE3C7C/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/DB38480B2F>) |
| 17e9:431f | DisplayLink      | ThinkPad Basic USB 3.0 Dock          | 2     | cdc_ncm... | [C9837EF0C1](<Notebook/Lenovo/ThinkPad/ThinkPad P50 20EQA0GSLM/A3D5663CE0B5/UBUNTU-20.04/5.8.0-50-GENERIC/X86_64/C9837EF0C1>) |
| 17e9:4351 | DisplayLink      | HP USB Dock                          | 2     | cdc_ncm    | [C400D6B3F2](<Notebook/Lenovo/IdeaPad/IdeaPad 330S-14IKB 81JM/43E0AB99DD44/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/C400D6B3F2>) |
| 17e9:6004 | DisplayLink      | Targus USB3 DV4K DOCK w PD60W        | 2     | cdc_ncm    | [395718DB33](<Tablet/Microsoft/Surface/Surface Pro 3/E1E08E7F6973/FEDORA-35/5.15.4-200.FC35.X86_64/X86_64/395718DB33>) |
| 17ef:3098 | Lenovo           | Mini Dock                            | 2     | cdc_ether  | [78CB2CA751](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NJ0010BM/8B539696F948/UBUNTU-20.04/5.4.0-59-GENERIC/X86_64/78CB2CA751>) |
| 1c04:0015 | QNAP System      | QNAP QNA-UC5G1T USB to 5GbE Adapter  | 2     | aqc111     | [D391C49614](<Mini Pc/ZOTAC/ZBOX-CI620/ZBOX-CI620-CI640-CI660/325193929FA8/KUBUNTU-20.04/5.4.0-64-GENERIC/X86_64/D391C49614>) |
| 03f0:0547 | Hewlett-Packard  | L2311c LAN7500 Ethernet              | 1     |            | [EBB304F58E](<Notebook/Dell/Precision/Precision 5520/CC4D70FDB6F0/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/EBB304F58E>) |
| 03f0:0857 | Hewlett-Packard  | lt4220 Snapdragon X12 LTE            | 1     | cdc_ether  | [54BAAAD690](<Notebook/Dell/Precision/Precision 7730/42E975357450/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/54BAAAD690>) |
| 056e:4007 | Elecom           | WDC-433DU2HBK                        | 1     | rtl8812au  | [4F8794ED64](<Desktop/ASRock/A300/A300M-STX/FD07F40ED5D5/KUBUNTU-20.04/5.4.0-64-GENERIC/X86_64/4F8794ED64>) |
| 0b05:1976 | ASUSTek Computer | USB 10/100/1G/2.5G LAN               | 1     | cdc_ncm... | [043F80CDED](<Desktop/Azulle/Inspire/Inspire/F8B9EB296470/FEDORA-35/5.15.11-200.FC35.X86_64/X86_64/043F80CDED>) |
| 0df6:0072 | Sitecom Europe   | AX88179 Gigabit Ethernet [Sitecom]   | 1     | ax88179... | [85C6FB8933](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X512DA_F512DA/39BB7F1EFA33/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/85C6FB8933>) |
| 17e9:433e | DisplayLink      | dynadock 4K                          | 1     | cdc_ncm    | [FDC926F819](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2G303/5386512A6B05/LINUXMINT-20.1/5.8.0-48-GENERIC/X86_64/FDC926F819>) |
| 17e9:6008 | DisplayLink      | Targus USB3 DV4K DOCK w PD100W       | 1     | cdc_ncm... | [C503EFCF6C](<Desktop/Dell/XPS/XPS 8700/378EE66F48A9/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/C503EFCF6C>) |
| 17ef:3052 | Lenovo           | ThinkPad TabletDock                  | 1     | cdc_ether  | [1D6F4C02A1](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C10024GE/CE86374CD564/XUBUNTU-20.04/5.4.0-42-GENERIC/X86_64/1D6F4C02A1>) |
| 2001:b301 | D-Link           | DUBE250 2.5GbE Adapter               | 1     | cdc_ncm    | [4DC4A0EFE0](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20UHCTO1WW/F34F31471099/FEDORA-34/5.13.8-200.FC34.X86_64/X86_64/4DC4A0EFE0>) |
| 2b73:0007 | Pioneer DJ       | USB 10/100 LAN                       | 1     | cdc_ether  | [09D7C3567E](<Desktop/Gigabyte Technology/990/990FXA-UD3/E739A1F28B0B/UBUNTU-20.04/5.11.0-42-GENERIC/X86_64/09D7C3567E>) |

### Net/wimax (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0186 | Intel            | WiMAX Connection 2400m               | 62    | i2400m_usb | [D547C2E9D6](<Notebook/ASUSTek Computer/U43/U43F/12B28C98AD17/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/D547C2E9D6>) |
| 8086:0180 | Intel            | WiMAX Connection 2400m               | 56    | i2400m_usb | [A933B77B15](<Notebook/ASUSTek Computer/N61/N61Vn/2976011E8405/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/A933B77B15>) |
| 8087:07d6 | Intel            | Centrino Wireless-N + WiMAX 6150     | 47    | i2400m_usb | [08BF40800A](<Notebook/Sony/VPCF236/VPCF236FM/048DA2EA9551/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/08BF40800A>) |
| 8086:1406 | Intel            | WiMAX Connection 2400m               | 44    | i2400m_usb | [35FFCAED33](<Notebook/Lenovo/IdeaPad/IdeaPad S10-2 20027/E23D1264EBC6/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-I586/I686/35FFCAED33>) |
| 8086:0188 | Intel            | WiMAX Connection 2400m               | 21    | i2400m_usb | [E9737D434F](<Notebook/Dell/Precision/Precision M6600/8FB5BEAE810F/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/E9737D434F>) |
| 8086:0187 | Intel            | Centrino Advanced-N + WiMAX 6250     | 16    | i2400m_usb | [8910DE29BC](<Notebook/Lenovo/ThinkPad/ThinkPad X201 3323LWA/73B8CF069195/ARCO-ROLLING/5.10.79-1-LTS/X86_64/8910DE29BC>) |
| 8086:0182 | Intel            | WiMAX Connection 2400m               | 2     | i2400m_usb | [01517BE2D7](<Notebook/Dell/Inspiron/Inspiron 1110/AAEB47BE7B9E/ZORIN-15/5.4.0-47-GENERIC/X86_64/01517BE2D7>) |

### Net/wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 148f:7601 | Ralink Techno... | MT7601U Wireless Adapter             | 1224  | mt7601u    | [83A319F258](<Notebook/Dell/Inspiron/Inspiron 1525/E3C6D99D7C40/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/83A319F258>) |
| 0bda:8179 | Realtek Semic... | RTL8188EUS 802.11n Wireless Netwo... | 1104  | r8188eu    | [59A21D0AA2](<Desktop/ASUSTek Computer/P5/P5Q/54A685670DC2/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/59A21D0AA2>) |
| 0cf3:9271 | Qualcomm Athe... | AR9271 802.11n                       | 769   | ath9k_htc  | [5C0115E49D](<All In One/Apple/iMac8/iMac8,1/B79007BB214E/LINUXMINT-20.3/5.13.0-27-GENERIC/X86_64/5C0115E49D>) |
| 0bda:b812 | Realtek Semic... | RTL88x2bu [AC1200 Techkey]           | 598   | 88x2bu     | [10C87BED94](<Notebook/Packard Bell/EasyNote/EasyNote TM85/FE9D28710D40/XUBUNTU-21.10/5.13.0-30-GENERIC/X86_64/10C87BED94>) |
| 148f:5370 | Ralink Techno... | RT5370 Wireless Adapter              | 565   | rt2800usb  | [DD1758AAA7](<Desktop/Gigabyte Technology/EP35/EP35-DS3/72A5C842FFCC/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/DD1758AAA7>) |
| 148f:3070 | Ralink Techno... | RT2870/RT3070 Wireless Adapter       | 516   | rt2800usb  | [72775A871A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/72775A871A>) |
| 0bda:8178 | Realtek Semic... | RTL8192CU 802.11n WLAN Adapter       | 434   | rtl8192... | [3BBA8576A0](<Desktop/Gigabyte Technology/Z68/Z68A-D3H-B3/28E04E932B5D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3BBA8576A0>) |
| 0bda:c811 | Realtek Semic... | 802.11ac NIC                         | 403   | 8821cu     | [50BB4C65AB](<Desktop/ASUSTek Computer/All/All Series/3CDA02BE060E/UBUNTU-20.04/5.4.0-53-GENERIC/X86_64/50BB4C65AB>) |
| 2357:0109 | TP-Link          | TL-WN823N v2/v3 [Realtek RTL8192EU]  | 355   | rtl8xxxu   | [DBF296E963](<Desktop/Dell/OptiPlex/OptiPlex 7020/612B24C7DA29/ARCO-ROLLING/5.15.10-ARCH1-1/X86_64/DBF296E963>) |
| 0bda:8176 | Realtek Semic... | RTL8188CUS 802.11n WLAN Adapter      | 348   | rtl8192... | [80DFCFD4BF](<Desktop/Wortmann AG/TERRA_SERVER/TERRA_SERVER/0E3B5A23CB14/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/80DFCFD4BF>) |
| 2357:010c | TP-Link          | TL-WN722N v2/v3 [Realtek RTL8188EUS] | 278   | r8188eu    | [019EEB069D](<Notebook/ASUSTek Computer/UX303/UX303LAB/E19561E45808/LINUXMINT-20.2/5.4.0-94-GENERIC/X86_64/019EEB069D>) |
| 0bda:f179 | Realtek Semic... | RTL8188FTV 802.11b/g/n 1T1R 2.4G ... | 259   | rtl8188fu  | [CB91470EA7](<Desktop/Intel/H/H61/AD423E6040EC/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/CB91470EA7>) |
| 0bda:8189 | Realtek Semic... | RTL8187B Wireless 802.11g 54Mbps ... | 229   | rtl8187    | [463CA7F3A3](<Notebook/Quanta/TW8/TW8-SW8-DW8/073CF94DED83/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/463CA7F3A3>) |
| 0bda:818b | Realtek Semic... | RTL8192EU 802.11b/g/n WLAN Adapter   | 225   | rtl8xxxu   | [146505ADEE](<Desktop/Acer/Aspire/Aspire TC-391/45578AE790D2/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/146505ADEE>) |
| 2357:011e | TP-Link          | 802.11ac WLAN Adapter                | 210   | 88XXau     | [EF2E2E6872](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/F1248BB1749F/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/EF2E2E6872>) |
| 045e:0719 | Microsoft        | Xbox 360 Wireless Adapter            | 199   | xpad       | [589486D805](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401QM_GA401QM/26E6E3C2710A/UBUNTU-21.10/5.15.27-051527-GENERIC/X86_64/589486D805>) |
| 0bda:8812 | Realtek Semic... | RTL8812AU 802.11a/b/g/n/ac 2T2R D... | 191   | 8812au     | [72775A871A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/72775A871A>) |
| 0bda:8187 | Realtek Semic... | RTL8187 Wireless Adapter             | 172   | rtl8187    | [6BEDA6E2DA](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-A/35642A99888E/ELEMENTARY-6.1/5.13.0-27-GENERIC/X86_64/6BEDA6E2DA>) |
| 0bda:8172 | Realtek Semic... | RTL8191SU 802.11n WLAN Adapter       | 154   | r8712u     | [6B32E0C788](<Desktop/Gigabyte Technology/H61/H61M-S2PV/EB2B21B97997/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/6B32E0C788>) |
| 7392:7811 | Edimax Techno... | EW-7811Un 802.11n Wireless Adapte... | 153   | rtl8192... | [FB183BFD9B](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/056649DD334F/MANJARO/5.15.25-1-MANJARO/X86_64/FB183BFD9B>) |
| 148f:5572 | Ralink Techno... | RT5572 Wireless Adapter              | 151   | rt2800usb  | [73526F92AC](<Notebook/Dell/XPS/XPS 15 7590/77162A4B48CB/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/73526F92AC>) |
| 148f:761a | Ralink Techno... | MT7610U ("Archer T2U" 2.4G+5G WLA... | 143   | mt76x0u    | [4F6714E804](<Desktop/ASUSTek Computer/All/All Series/96C0B166BFD2/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/4F6714E804>) |
| 148f:5372 | Ralink Techno... | RT5372 Wireless Adapter              | 140   | rt2800usb  | [EAA5B0F454](<Desktop/ASUSTek Computer/PRIME/PRIME B460M-A/28091A90C0B8/UBUNTU-21.04/5.11.0-49-GENERIC/X86_64/EAA5B0F454>) |
| 0bda:a811 | Realtek Semic... | RTL8811AU 802.11a/b/g/n/ac WLAN A... | 136   | 88XXau     | [38C8508BC0](<Desktop/ASRock/X570/X570 Phantom Gaming 4/C2ED70ED019A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/38C8508BC0>) |
| 2357:0107 | TP-Link          | TL-WN821N v5/v6 [RTL8192EU]          | 123   | rtl8xxxu   | [5A3C3065D0](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D5ED4AD18E99/DEBIAN-11/5.13.19-4-PVE/X86_64/5A3C3065D0>) |
| 413c:81b6 | Dell             | DW5811e Snapdragonâ?¢ X7 LTE         | 120   | qcseria... | [1EF8A55EDE](<Notebook/Dell/Latitude/Latitude E5470/9C8C05DE5674/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/1EF8A55EDE>) |
| 1199:9079 | Sierra Wireless  | EM7455                               | 113   | qcseria... | [D5E5A6FD60](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 4th 20FCS12V06/02C322415C07/UBUNTU-20.04/5.0.0-27-GENERIC/X86_64/D5E5A6FD60>) |
| 148f:2573 | Ralink Techno... | RT2501/RT2573 Wireless Adapter       | 107   | rt73usb    | [A0D52488B2](<Desktop/Gigabyte Technology/Z77/Z77-D3H/C3A95A6B369E/LMDE-4/4.19.0-18-AMD64/X86_64/A0D52488B2>) |
| 0bda:0811 | Realtek Semic... | Realtek 8812AU/8821AU 802.11ac WL... | 103   | 8812au     | [2C17897902](<Desktop/ASUSTek Computer/Z170I/Z170I PRO GAMING/4593A2E4A7D0/XUBUNTU-21.10/5.13.0-32-GENERIC/X86_64/2C17897902>) |
| 0846:9053 | NetGear          | A6210                                | 102   | mt76x2u    | [862A31FA80](<Notebook/Dell/Inspiron/Inspiron 5548/B32A4E77F99D/MANJARO/5.15.21-1-MANJARO/X86_64/862A31FA80>) |
| 2357:012d | TP-Link          | Archer T3U [Realtek RTL8812BU]       | 102   | 88x2bu     | [FE8CE505F4](<Desktop/Dell/OptiPlex/OptiPlex 3010/1EC4C5680CA5/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/FE8CE505F4>) |
| 045e:02fe | Microsoft        | XBOX ACC                             | 92    | mt76x2u    | [3CBA5D22BC](<Desktop/MSI/MS/MS-7918/9432F9FD1040/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/3CBA5D22BC>) |
| 2357:0120 | TP-Link          | Archer T2U PLUS [RTL8821AU]          | 92    | 88XXau     | [4425801F5C](<Notebook/Toshiba/Satellite/Satellite L10W-B-101/D8FCAC83307E/MANJARO/5.15.25-1-MANJARO/X86_64/4425801F5C>) |
| 2001:3319 | D-Link           | DWA-131 Wireless N Nano Adapter (... | 87    | rtl8xxxu   | [994D0F847E](<Desktop/Gigabyte Technology/H310M/H310M H/099DA5E23971/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/994D0F847E>) |
| 2357:011f | TP-Link          | 802.11ac WLAN Adapter                | 87    | 88XXau     | [066FECF595](<Notebook/Acer/Aspire/Aspire 5750G/168C1610F4AF/KUBUNTU-21.10/5.13.0-30-GENERIC/X86_64/066FECF595>) |
| 2357:0115 | TP-Link          | Archer T4U ver.3                     | 86    | 88x2bu     | [39926596B7](<Desktop/MSI/MS/MS-7851/DBD69D2446F7/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/39926596B7>) |
| 0bda:8171 | Realtek Semic... | RTL8188SU 802.11n WLAN Adapter       | 85    | r8712u     | [499346B7AB](<Desktop/ASUSTek Computer/M2N-CM/M2N-CM DVI/4D1F5E205475/LINUXMINT-20.1/5.4.0-72-GENERIC/X86_64/499346B7AB>) |
| 0846:9052 | NetGear          | A6100 AC600 DB Wireless Adapter [... | 83    | 8812au     | [E06660B923](<Desktop/Dell/Precision/Precision WorkStation T5400/27979DD07505/KUBUNTU-11/5.13.0-30-GENERIC/X86_64/E06660B923>) |
| 07d1:3c0a | D-Link System    | DWA-140 RangeBooster N Adapter(re... | 82    | rt2800usb  | [664D13320F](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/7EE8C432873F/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/664D13320F>) |
| 0b05:17ba | ASUSTek Computer | N10 Nano 802.11n Network Adapter ... | 81    | rtl8192cu  | [13989D56EC](<Desktop/Wortmann AG/TERRA_PC/TERRA_PC/4DC78B7D0A0C/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/13989D56EC>) |
| 13d3:3306 | IMC Networks     | Mediao 802.11n WLAN [Realtek RTL8... | 77    | r8712u     | [C1A78E4700](<Desktop/Medion/MS/MS-7728/6DC5B5C32DF2/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/C1A78E4700>) |
| 0cf3:7015 | Qualcomm Athe... | TP-Link TL-WN821N v3 / TL-WN822N ... | 75    | ath9k_htc  | [5715780BFC](<Notebook/Fujitsu Siemens/AMILO/AMILO Pa 1538/467523013938/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/5715780BFC>) |
| 2357:0108 | TP-Link          | TL-WN822N Version 4 RTL8192EU        | 75    | rtl8xxxu   | [CF460C52BB](<Notebook/Lenovo/ThinkPad/ThinkPad W520 42844MG/8BC92228F8B9/XUBUNTU-20.04/5.11.0-44-GENERIC/X86_64/CF460C52BB>) |
| 045e:02e6 | Microsoft        | Wireless XBox Controller Dongle      | 74    | mt76x2u    | [EAA5B0F454](<Desktop/ASUSTek Computer/PRIME/PRIME B460M-A/28091A90C0B8/UBUNTU-21.04/5.11.0-49-GENERIC/X86_64/EAA5B0F454>) |
| 0bda:8197 | Realtek Semic... | RTL8187B Wireless Adapter            | 74    | rtl8187    | [9E9C1B741B](<Notebook/Toshiba/Satellite/Satellite L350D/430E5424D73B/LINUXMINT-20.2/5.4.0-100-GENERIC/X86_64/9E9C1B741B>) |
| 0b05:17ab | ASUSTek Computer | USB-N13 802.11n Network Adapter (... | 72    | rtl8192cu  | [D1EC585515](<Notebook/Hewlett-Packard/ProBook/ProBook 6475b/815C7BF19476/POP!_OS-21.10/5.15.24-XANMOD1/X86_64/D1EC585515>) |
| 0846:9030 | NetGear          | WNA1100 Wireless-N 150 [Atheros A... | 68    | ath9k_htc  | [9E310A9389](<Desktop/Biostar/P4/P4M90-M7/8A9BEEE2EA0C/ROSA-12/5.10.71-GENERIC-1ROSA2021.1-X86_64/X86_64/9E310A9389>) |
| 0b05:184c | ASUSTek Computer | 802.11ac NIC                         | 62    | 88x2bu     | [1575F2F0BE](<Notebook/Sony/SVE14/SVE14A2V2ES/F3A92336CE08/PARDUS-19.5/4.19.0-19-AMD64/X86_64/1575F2F0BE>) |
| 03f0:581d | Hewlett-Packard  | lt4112 Gobi 4G Module Network Device | 60    | qcserial   | [ECB1064B14](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G2/20A1597C4E96/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/ECB1064B14>) |
| 03f0:9d1d | Hewlett-Packard  | lt4120 Snapdragon X5 LTE             | 60    | cdc_ether  | [C6FA3E547D](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G3/05112EB756D8/CLEAR-LINUX-OS-35970/5.10.103-54.LTS2020/X86_64/C6FA3E547D>) |

### Network (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:8153 | Realtek Semic... | RTL8153 Gigabit Ethernet Adapter     | 2192  | r8152      | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 04e8:6863 | Samsung Elect... | Galaxy series, misc. (tethering m... | 595   | rndis_host | [62F3B41D12](<Notebook/ASUSTek Computer/UX31/UX31E/22CCF8FF6593/OPENMANDRIVA-4.50/5.14.7-DESKTOP-1OMV4050/X86_64/62F3B41D12>) |
| 2717:ff80 | Xiaomi           | Mi/Redmi series (RNDIS)              | 389   | rndis_host | [8CE8958B88](<Desktop/Intel/H/H61/2E5077B92ADB/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/8CE8958B88>) |
| 0b95:1790 | ASIX Electronics | AX88179 Gigabit Ethernet             | 382   | ax88179... | [589486D805](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401QM_GA401QM/26E6E3C2710A/UBUNTU-21.10/5.15.27-051527-GENERIC/X86_64/589486D805>) |
| 0bda:8152 | Realtek Semic... | RTL8152 Fast Ethernet Adapter        | 263   | r8152      | [698AF00B9C](<Notebook/MSI/Modern/Modern 14 B4MW/6E9EA3CA6611/ARCH-ROLLING/5.16.13-ARCH1-1/X86_64/698AF00B9C>) |
| 12d1:108a | Huawei Techno... | ELS-NX9                              | 259   | rndis_host | [D5C330BAD8](<Desktop/Biostar/H61/H61MLV2/B70932ED3EE9/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/D5C330BAD8>) |
| 04e8:6864 | Samsung Elect... | GT-I9070 (network tethering, USB ... | 243   | rndis_host | [2693582A54](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da2xxx/548E7C53EBB9/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/2693582A54>) |
| 0bda:b720 | Realtek Semic... | 802.11n WLAN Adapter                 | 229   | rtl8xxxu   | [674A4FBEDE](<Notebook/Chuwi/HeroBook/HeroBook Air/96A0EC35E00A/ZORIN-16/5.11.0-38-GENERIC/X86_64/674A4FBEDE>) |
| 12d1:14db | Huawei Techno... | E353/E3131                           | 189   | cdc_ether  | [5BE286E220](<Desktop/ASRock/H310/H310M-HDV/8286140E1C85/POP!_OS-21.04/5.13.0-7620-GENERIC/X86_64/5BE286E220>) |
| 0e8d:2004 | MediaTek         | TECNO SPARK 7                        | 162   | rndis_host | [CED72EE9F4](<Desktop/ASUSTek Computer/P8/P8B75-V/6CCF94A1E127/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/CED72EE9F4>) |
| 19d2:1405 | ZTE WCDMA Tec... | ZTE Mobile Broadband Station         | 132   | cdc_ether  | [D5D2EE0AB5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G7 Microtower PC/473ECA75FDF0/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D5D2EE0AB5>) |
| 22b8:2e24 | Motorola PCS     | motorola edge                        | 128   | rndis_host | [B7250E82A1](<Notebook/ASUSTek Computer/N551/N551VW/ED4708B95D9A/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B7250E82A1>) |
| 2357:0601 | TP-Link          | UE300 10/100/1000 LAN (ethernet m... | 128   | r8152      | [D3AD998DFA](<Notebook/HONOR/BMH-WCX/BMH-WCX9/19886291EEA7/DEBIAN-11/5.15.0-2-AMD64/X86_64/D3AD998DFA>) |
| 1199:a001 | Sierra Wireless  | EM7345 4G LTE                        | 104   | cdc_mbim   | [3667F5B9E9](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CM001XMC/63B862C115F0/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/3667F5B9E9>) |
| 0b95:772b | ASIX Electronics | AX88772B                             | 89    | asix       | [4A49294D21](<Notebook/Multilaser/DS/DS133/5A1E6E974FF3/ZORIN-16/5.13.0-30-GENERIC/X86_64/4A49294D21>) |
| 2cb7:0210 | Fibocom          | L830-EB-00 LTE WWAN Modem            | 87    | cdc_acm    | [4766FE6362](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2000KRT/974FF46B3D36/ARCH-ROLLING/5.16.13-ARCH1-1/X86_64/4766FE6362>) |
| 0bda:c820 | Realtek Semic... | 802.11ac NIC                         | 84    | btusb      | [256DC440EC](<Desktop/Others/T3/T3 MRD/40E9767A0365/UBUNTU-22.04/5.15.0-22-GENERIC/X86_64/256DC440EC>) |
| 05c6:f00e | Qualcomm         | Mobile Router                        | 81    | rndis_host | [994D0F847E](<Desktop/Gigabyte Technology/H310M/H310M H/099DA5E23971/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/994D0F847E>) |
| 18d1:4ee3 | Google           | Nexus/Pixel Device (tether)          | 81    | rndis_host | [E543F0217A](<Desktop/NZXT/MS-7/MS-7D09/DA40C6D42E6E/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/E543F0217A>) |
| 17e9:6006 | DisplayLink      | Dell Universal Dock D6000            | 78    | cdc_ncm    | [9BB17A1C87](<Notebook/Lenovo/ThinkPad/ThinkPad T15 Gen 2i 20W4000NRT/A8DFB379DA21/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/9BB17A1C87>) |
| 17ef:3082 | Lenovo           | ThinkPad TBT 3 Dock                  | 75    | r8152      | [48C1285EEC](<Notebook/Lenovo/ThinkPad/ThinkPad P53 20QN0011IV/90C24C7500E3/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/48C1285EEC>) |
| 17ef:a387 | Lenovo           | USB-C Dock Ethernet                  | 74    | r8152      | [B48A6240BF](<Notebook/Lenovo/ThinkPad/ThinkPad E15 20RD0016GE/4F4BEFFC091C/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/B48A6240BF>) |
| 0424:ec00 | Microchip Tec... | SMSC9512/9514 Fast Ethernet Adapter  | 72    | smsc95xx   | [0C406A0FB6](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/657E70087A27/RASPBIAN-9/5.15.21-V7+/ARMV7L/0C406A0FB6>) |
| 22d9:276a | oneplus          | Nord 2 5G                            | 71    | rndis_host | [14237B32D9](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop M3500QA_M3500QA/701977B77E24/ZORIN-16/5.13.0-35-GENERIC/X86_64/14237B32D9>) |
| 0fe6:9700 | ICS Advent       | DM9601 Fast Ethernet Adapter         | 68    | dm9601,... | [43BB230E40](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/5CD14C1C8F25/UBUNTU-21.10/5.13.0-1017-RASPI/AARCH64/43BB230E40>) |
| 17e9:4307 | DisplayLink      | usb_device                           | 68    | cdc_ncm    | [EE32355409](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/EE29838C95B5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EE32355409>) |
| 0b95:7720 | ASIX Electronics | AX88772                              | 50    | asix       | [1A8B02FE5E](<Notebook/Others/Others/Others/7503F5C8DFAB/UBUNTU-21.10/5.13.0-32-GENERIC/X86_64/1A8B02FE5E>) |
| 2a70:f00e | OnePlus          | OnePlus                              | 50    | rndis_host | [EA12D27CF9](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506IC_FA566IC/18C77343A370/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/EA12D27CF9>) |
| 04b3:4010 | IBM              | RNDIS/Ethernet Gadget                | 49    | cdc_ether  | [C717BB4AC6](<Server/IBM/System/System X iDataPlex dx360 M4 Server -[7912AC1]-/E15173785994/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/C717BB4AC6>) |
| 2e04:c022 | HMD Global       | SDM439-QRD _SN:13A316C0              | 48    | rndis_host | [849A97D8C3](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/C1EBC5D5D8E2/DEBIAN-11/5.10.0-11-AMD64/X86_64/849A97D8C3>) |
| 03f0:371d | Hewlett-Packard  | un2430 Mobile Broadband Module       | 45    | qcserial   | [C6A3599160](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2560p/CE037D037263/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/C6A3599160>) |
| 17ef:a359 | Lenovo           | ThinkPad Lan                         | 43    | cdc_ether  | [33CE116B8A](<Notebook/Lenovo/ThinkBook/ThinkBook 16p Gen 2 20YM/4DAF13AEA8CC/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/33CE116B8A>) |
| 05ac:12ab | Apple            | iPad 4/Mini1                         | 42    | ipheth     | [989EEC2F5F](<Desktop/MSI/MS-7/MS-7A62/161A2AC8544D/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/989EEC2F5F>) |
| 17e9:436e | DisplayLink      | Dell D3100 Docking Station           | 41    | cdc_ncm    | [54C4F70C98](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/B24147C07140/XUBUNTU-20.04/5.13.0-30-GENERIC/X86_64/54C4F70C98>) |
| 0bb4:0003 | HTC (High Tec... | WEXLER.ZEN 4.7                       | 40    | rndis_host | [A6A5772C7F](<Notebook/ASUSTek Computer/K42/K42Jc/DB7C142319CB/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/A6A5772C7F>) |
| 045e:07c6 | Microsoft        | RTL8153 GigE [Surface Ethernet Ad... | 39    | r8152      | [D8EA22EFF5](<Tablet/Microsoft/Surface/Surface 3/DEBCA8820BEF/DEBIAN-TESTING/5.16.11-SURFACE/X86_64/D8EA22EFF5>) |
| 17e9:6000 | DisplayLink      | Universal Dual 4K Video Dock         | 39    | snd_usb... | [4F65353F3E](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20T1S8E400/DFC9BE7636A6/XUBUNTU-20.04/5.13.0-35-GENERIC/X86_64/4F65353F3E>) |
| 0e8d:2005 | MediaTek         | moto g(8) power lite                 | 37    | rndis_host | [C40A0C5222](<Notebook/Lenovo/ThinkPad/ThinkPad E495 20NES01600/B3AE3A54FFB2/MANJARO/5.15.19-1-MANJARO/X86_64/C40A0C5222>) |
| 0bda:d723 | Realtek Semic... | 802.11n WLAN Adapter                 | 36    | btusb      | [C166EC8175](<Notebook/Noblex/N14/N14WD21/5082BCE4838F/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/C166EC8175>) |
| 15a9:002d | Gemtek           | WLTUBA-107 [Yota 4G LTE]             | 36    | cdc_ether  | [01DF3A24CD](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO P5925/EEBA739012EF/DEBIAN-11/5.10.0-10-AMD64/X86_64/01DF3A24CD>) |
| 19d2:1365 | ZTE WCDMA Tec... | Spreadtrum Phone                     | 36    | rndis_host | [872772F278](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-A/6A9CCC297928/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/872772F278>) |
| 0424:7800 | Standard Micr... | Ethernet controller                  | 34    | lan78xx    | [053E9AC0E2](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/BA4A62CA68F9/RASPBIAN-10/5.10.63-V7+/ARMV7L/053E9AC0E2>) |
| 1004:6344 | LG Electronics   | LM-X420xxx/G2 Android Phone (USB ... | 34    | rndis_h... | [C3A95BEF82](<Notebook/Toshiba/Satellite/Satellite A215/1553956409BD/UBUNTU-20.10/5.8.0-43-GENERIC/X86_64/C3A95BEF82>) |
| 17ef:3069 | Lenovo           | ThinkPad TBT3 LAN                    | 34    | r8152      | [FDA7557AA0](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L60033MX/18E95B12F364/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/FDA7557AA0>) |
| 0b95:772a | ASIX Electronics | AX88772A Fast Ethernet               | 33    | asix       | [3767B10050](<Desktop/MSI/MS-7/MS-7D25/AA64896099DD/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/3767B10050>) |
| 05c6:9024 | Qualcomm         | FP3                                  | 31    | rndis_host | [393E833123](<Notebook/Lenovo/ThinkPad/ThinkPad P1 Gen 3 20TJS2KM00/A298F1ED5E8C/ARCH-ROLLING/5.15.24-2-LTS/X86_64/393E833123>) |
| 1bbb:0174 | T & A Mobile ... | Alcatel 3X                           | 31    | rndis_host | [FFFBA31B29](<Desktop/ASRock/G31/G31M-GS/74FF3B185257/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/FFFBA31B29>) |
| 046b:ffb0 | American Mega... | Virtual Ethernet                     | 30    | cdc_ether  | [C462619A26](<Desktop/ASRockRack/X470/X470D4U2-2T/EBA52B45302C/DEBIAN-11/5.13.19-4-PVE/X86_64/C462619A26>) |
| 0bda:b82c | Realtek Semic... | 802.11ac NIC                         | 30    | btusb      | [961BE2A608](<Desktop/MSI/MS-7/MS-7D06/22FAC0329158/ZORIN-16/5.13.0-28-GENERIC/X86_64/961BE2A608>) |
| 0bda:1724 | Realtek Semic... | RTL8723AU 802.11n WLAN Adapter       | 29    | rtl8xxxu   | [347317645D](<Notebook/Lenovo/IdeaPad/IdeaPad Yoga 13 20175/57CB55619157/XUBUNTU-21.10/5.13.0-25-GENERIC/X86_64/347317645D>) |

### Phone (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0e8d:2008 | MediaTek         | Cyrus Technology CS 24               | 115   | usbfs      | [3327E56999](<Notebook/MSI/GF63/GF63 Thin 9SC/40BAF5C8DEF5/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/3327E56999>) |
| 18d1:4ee1 | Google           | Nexus/Pixel Device (MTP)             | 81    | usbfs      | [E29F709958](<Desktop/Dell/XPS/XPS 8700/C159B982C0A3/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/E29F709958>) |
| 2717:ff48 | Xiaomi           | Mi/Redmi series (MTP + ADB)          | 46    | usbfs      | [134D1CF65B](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 14-ce0xxx/13B56A2CF8AB/FEDORA-35/5.16.12-250.VANILLA.1.FC35.X86_64/X86_64/134D1CF65B>) |
| 1004:631c | LG Electronics   | LM-X420xxx/G2/Optimus Android Pho... | 45    | usbfs      | [1080E5A099](<Desktop/Hewlett-Packard/Pavilion/Pavilion Gaming Desktop TG01-0xxx/1B138A6CB00E/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/1080E5A099>) |
| 0e8d:201d | MediaTek         | M5s                                  | 26    | usbfs      | [ADD118EFCC](<Desktop/Gigabyte Technology/B85/B85M-D3H/2291BAFFB1CB/KALI-2022.1/5.15.0-KALI2-AMD64/X86_64/ADD118EFCC>) |
| 1bbb:0168 | T & A Mobile ... | Alcatel 1X                           | 24    | usbfs      | [A6732AB721](<Notebook/Clevo/W54/W54xEU/EB4306F65FAD/UBUNTU-20.04/5.11.0-37-GENERIC/X86_64/A6732AB721>) |
| 04e8:685d | Samsung Elect... | GT-I9100 Phone [Galaxy S II] (Dow... | 18    | cdc_acm    | [CEC2A1A3E3](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G1/355A9FEC09A4/KALI-2021.4/5.14.0-KALI4-AMD64/X86_64/CEC2A1A3E3>) |
| 1004:6300 | LG Electronics   | G2/Optimus Android Phone [Charge ... | 13    | usbhid     | [B4D3516747](<Desktop/Biostar/B450/B450MHC/E3F2ADE33D69/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/B4D3516747>) |
| 05c6:f003 | Qualcomm         | Nokia 8110 4G                        | 11    | usbfs      | [E1F153A5E6](<Desktop/MSI/MS-7/MS-7A31/7F728D1D894B/ENDEAVOUROS-ROLLING/5.15.13-ZEN1-1-ZEN/X86_64/E1F153A5E6>) |
| 19d2:0307 | ZTE WCDMA Tec... | Spreadtrum Phone                     | 11    | usbfs      | [0E8FBC26F1](<Desktop/Pegatron/IPM41/IPM41-D3/70EAAEB78B53/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/0E8FBC26F1>) |
| 0bb4:0c02 | HTC (High Tec... | Dream / ADP1 / G1 / Magic / Tatto... | 9     | usbfs      | [C1991967BB](<Desktop/ASRock/B450/B450 Steel Legend/EACAC3900360/LINUXMINT-20.2/5.4.0-90-GENERIC/X86_64/C1991967BB>) |
| 19d2:0306 | ZTE WCDMA Tec... | ZTE USB Device                       | 9     | usbfs      | [FDFD650FCC](<Notebook/Sony/SVF1421/SVF14211CLB/4D841A70D8D6/ZORIN-16/5.11.0-40-GENERIC/X86_64/FDFD650FCC>) |
| 2a45:2008 | Meizu            | MX Phone (MTP)                       | 8     | usbfs      | [BCF1D99475](<Desktop/ASUSTek Computer/P8/P8Z68-V/4BC4C841D8A0/MANJARO-18.0.4/5.1.4-1-MANJARO/X86_64/BCF1D99475>) |
| 0bb4:2008 | HTC (High Tec... | Android Phone via MTP [Wiko Cink ... | 6     |            | [52ECA6CE50](<Notebook/Lenovo/G570/G570 20079/FA239870D40A/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-X86_64/X86_64/52ECA6CE50>) |
| 1782:4001 | Spreadtrum Co... | Android                              | 6     | usbfs      | [F13E4BF411](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LE-USB3/A8F3429FE2BB/ENDLESS-3.9.5/5.8.0-14-GENERIC/X86_64/F13E4BF411>) |
| 18d1:4ee8 | Google           | Nexus/Pixel Device (MIDI)            | 5     | snd_usb... | [1E57C317B4](<Notebook/Hewlett-Packard/Notebook/Notebook/D61A76DDA959/MANJARO/5.16.7-1-MANJARO/X86_64/1E57C317B4>) |
| 1bbb:0167 | T & A Mobile ... | Alcatel 5X                           | 5     | usbfs      | [27828E1DFB](<Notebook/Sony/Serie/Serie VJC14/BF8332F0A46F/ELEMENTARY-6/5.11.0-27-GENERIC/X86_64/27828E1DFB>) |
| 04e8:685c | Samsung Elect... | GT-I9250 Phone [Galaxy Nexus] (Ma... | 4     | usbfs      | [D9976E30E3](<Notebook/ASUSTek Computer/K75/K75VM/E4A852A4AEF1/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/D9976E30E3>) |
| 05c6:9092 | Qualcomm         | Android                              | 4     |            | [0A09D00B74](<Convertible/Acer/Spin/Spin SP111-33/FEEB57789B59/UBUNTU-MATE-20.04/5.4.0-62-GENERIC/X86_64/0A09D00B74>) |
| 0bb4:0c01 | HTC (High Tec... | Dream / ADP1 / G1 / Magic / Tatto... | 4     |            | [CB71A2D937](<Notebook/Lenovo/IdeaPad/IdeaPad 3 14IML05 81WA/AFCEC909C039/MANJARO/5.10.42-1-MANJARO/X86_64/CB71A2D937>) |
| 0bb4:0f0b | HTC (High Tec... | U12+                                 | 4     | usbhid     | [7CBE8BB003](<Desktop/MSI/MS-7/MS-7A35/8EF0854E581C/MANJARO-21.1.2/5.14.0-0-MANJARO/X86_64/7CBE8BB003>) |
| 0bb4:0f87 | HTC (High Tec... | m8                                   | 4     | usbfs      | [6F9489B2E6](<Desktop/EVGA/X299/X299 FTW K/E0352CDBA41D/NIXOS-21.11/5.10.102/X86_64/6F9489B2E6>) |
| 0fce:01c4 | Sony Ericsson... | Android                              | 4     | usbfs      | [6C0BF83741](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/DE5965167BBF/MANJARO/4.19.91-1-MANJARO/X86_64/6C0BF83741>) |
| 1004:633a | LG Electronics   | Ultimate 2 Android Phone L41C        | 4     | cdc_acm    | [16AEB4166B](<Desktop/Dell/Precision/Precision T1700/5EAB4E043B3F/UBUNTU-20.04/5.8.0-56-GENERIC/X86_64/16AEB4166B>) |
| 17ef:7497 | Lenovo           | A789 (MTP mode)                      | 4     |            | [B60CD6FFC3](<Notebook/Acer/Aspire/Aspire E1-571G/4D6A7182CE38/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/B60CD6FFC3>) |
| 045e:04ec | Microsoft        | Windows Phone (Zune)                 | 3     | usbfs      | [587BECD063](<Desktop/ASRock/G41/G41M-VS3/E4127A1A8A70/DEBIAN-10/4.19.0-14-AMD64/X86_64/587BECD063>) |
| 0bb4:f006 | HTC (High Tec... | Android Phone                        | 3     | usbhid     | [5902EF81CA](<Desktop/Dell/OptiPlex/OptiPlex 7010/81048E1FE46E/MANJARO-20.2/5.9.8-2-MANJARO/X86_64/5902EF81CA>) |
| 1004:61fe | LG Electronics   | Optimus Android Phone [USB tether... | 3     | cdc_ether  | [065636C444](<Desktop/Dell/OptiPlex/OptiPlex 5040/DA886BEEF2C1/SIDUCTION-UNSTABLE/5.15.2-1-SIDUCTION-AMD64/X86_64/065636C444>) |
| 2717:1240 | Xiaomi           | HM1 Android Phone                    | 3     |            | [01AA74496F](<Notebook/Samsung Electronics/530U3/530U3C-530U4C/6A47299A5F26/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/01AA74496F>) |
| 2916:f003 | Android          | Android                              | 3     | usbfs      | [5595625922](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/E6203EE83F54/LINUXMINT-19/4.15.0-20-GENERIC/X86_64/5595625922>) |
| 2a45:0c02 | Meizu            | MX Phone (MTP & ADB)                 | 3     | usbfs      | [5B337FDB0A](<Notebook/Apple/MacBookPro8/MacBookPro8,1/35BAC947BDBB/UBUNTU-21.10/5.13.0-16-GENERIC/X86_64/5B337FDB0A>) |
| 0471:0003 | Philips (or NXP) | Hub                                  | 2     | hub        | [20FA770830](<Server/Dell/PowerEdge/PowerEdge T640/C3C1AB1B873D/DEBIAN-11/5.4.0-73-GENERIC/X86_64/20FA770830>) |
| 0471:2008 | Philips (or NXP) | W732                                 | 2     |            | [D315AFD57C](<Desktop/ASRock/FM2/FM2A85X-ITX/379C7DB3BEA5/ROSA-2014.1/4.1.25-NRJ-DESKTOP-1ROSA-X86_64/X86_64/D315AFD57C>) |
| 0bb4:0402 | HTC (High Tec... | Android Phone                        | 2     | rndis_host | [EBBD83B0CA](<Desktop/Gigabyte Technology/GA-870/GA-870A-UD3/591AD831287C/DEBIAN-10/4.19.0-5-AMD64/X86_64/EBBD83B0CA>) |
| 0bb4:0c81 | HTC (High Tec... | Android Phone                        | 2     |            | [404A8B3A68](<All In One/Dell/Precision/Precision 5720 AIO/20C5601ED4D8/FEDORA-30/5.2.16-200.FC30.X86_64/X86_64/404A8B3A68>) |
| 0fce:0189 | Sony Ericsson... | C6503                                | 2     |            | [97D00825B7](<Notebook/Hewlett-Packard/Pavilion/Pavilion g7/841C91D45F4A/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-X86_64/X86_64/97D00825B7>) |
| 0fce:019b | Sony Ericsson... | Android                              | 2     |            | [49389100FC](<Notebook/Dell/Inspiron/Inspiron 7560/929244539C9A/ROSA-2014.1/4.1.25-NRJ-DESKTOP-1ROSA-X86_64/X86_64/49389100FC>) |
| 0fce:01b5 | Sony Ericsson... | D2105                                | 2     |            | [165BEE2B5C](<Desktop/ASUSTek Computer/P8/P8H61-USB3/2EFDC79D2759/ROSA-2014.1/4.1.19-NRJ-DESKTOP-2ROSA-X86_64/X86_64/165BEE2B5C>) |
| 0fce:51ad | Sony Ericsson... | Android                              | 2     |            | [41B2D085B5](<Desktop/ASUSTek Computer/M5A99FX/M5A99FX PRO R2.0/1F9169D28464/ROSA-2014.1/4.1.34-NRJ-DESKTOP-2ROSA-X86_64/X86_64/41B2D085B5>) |
| 1004:61fc | LG Electronics   | Optimus 3                            | 2     | cdc_acm... | [1EBB6C2E61](<Notebook/Samsung Electronics/R519/R519-R719/F28CF5443841/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/1EBB6C2E61>) |
| 1532:9051 | Razer USA        | Razer Phone 2                        | 2     |            | [CE5A468AEC](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/14560EB0BD3F/KDE-NEON-20.04/5.11.0-38-GENERIC/X86_64/CE5A468AEC>) |
| 1532:9052 | Razer USA        | Razer Phone 2                        | 2     | usbfs      | [F0B799EFBB](<Notebook/Lenovo/ThinkPad/ThinkPad W520 4270CTO/A54DE4BF9430/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/F0B799EFBB>) |
| 1782:4002 | Spreadtrum Co... | Spreadtrum Phone                     | 2     | usbfs      | [BFE957F66C](<Desktop/Samsung Electronics/DeskTop/DeskTop System/D8CD1CB528C1/MANJARO-21.2RC/5.10.83-1-MANJARO/X86_64/BFE957F66C>) |
| 1782:4012 | Spreadtrum Co... | RIO_ZAM                              | 2     |            | [83DBEAD899](<Notebook/Dell/Inspiron/Inspiron 1545/5C2EB2F16053/UBUNTU-18.04/5.4.0-65-GENERIC/X86_64/83DBEAD899>) |
| 17ef:74f8 | Lenovo           | MT65xx Android Phone                 | 2     |            | [B89D04A41B](<Notebook/Dell/Inspiron/Inspiron 7720/277F63301B21/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/B89D04A41B>) |
| 17ef:79a1 | Lenovo           | MT65xx Android Phone                 | 2     | usbfs      | [E661874CB2](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/F14B420DA0DF/MANJARO-21.0.7/5.12.14-NITROUS-FIRE+/X86_64/E661874CB2>) |
| 1bbb:2008 | T & A Mobile ... | MT65xx Android Phone                 | 2     | usbfs      | [E48E425669](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2540p/B6A3A2A1396F/LINUXMINT-20.1/5.4.0-70-GENERIC/X86_64/E48E425669>) |
| 0414:0c02 | Giga-Byte Tec... | MT65xx Android Phone                 | 1     | usbfs      | [755B9B413C](<Desktop/Dell/Inspiron/Inspiron 560/A812972AF97E/UBUNTU-20.10/5.8.0-31-GENERIC/X86_64/755B9B413C>) |
| 0421:002f | Nokia Mobile ... | 6120 Phone (PC-Suite mode)           | 1     | cdc_acm... | [408A3116F5](<Desktop/ASUSTek Computer/P5K/P5K PRO/F3585B744A5D/ROSA-2014.1/4.9.9-NRJ-DESKTOP-1ROSA-I586/I686/408A3116F5>) |
| 0b05:5490 | ASUSTek Computer | Android                              | 1     |            | [196E542A2B](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LE/9C8A18FA3906/ROSA-2014.1/4.1.13-NRJ-DESKTOP-1ROSA-X86_64/X86_64/196E542A2B>) |

### Printer (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 03f0:2b17 | Hewlett-Packard  | LaserJet 1020                        | 106   | usblp      | [A90BF8DB74](<Desktop/Hewlett-Packard/GU609AA-ACB/GU609AA-ACB a6230.ru/B7CE385BBB1F/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/A90BF8DB74>) |
| 03f0:4117 | Hewlett-Packard  | LaserJet 1018                        | 73    | usblp      | [7514554127](<Desktop/ASUSTek Computer/PRIME/PRIME H310-PLUS R2.0/023A708D110E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7514554127>) |
| 067b:2305 | Prolific Tech... | PL2305 Parallel Port                 | 69    | usblp      | [E479FFD9D5](<Desktop/ASUSTek Computer/B75/B75M-PLUS/DAD3EEF66E2E/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/E479FFD9D5>) |
| 04e8:341b | Samsung Elect... | SCX-4200 series                      | 61    | usblp      | [C98A25E545](<Desktop/Gigabyte Technology/H61/H61M-DS2/85DC310F35D3/ROSA-2016.1/4.9.95-NRJ-DESKTOP-2ROSA-X86_64/X86_64/C98A25E545>) |
| 03f0:0053 | Hewlett-Packard  | DeskJet 2620 All-in-One Printer      | 60    | usblp      | [CB91470EA7](<Desktop/Intel/H/H61/AD423E6040EC/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/CB91470EA7>) |
| 03f0:002a | Hewlett-Packard  | LaserJet P1102                       | 57    | usblp      | [5974840AA7](<Notebook/Toshiba/Satellite/Satellite C855-27U/4FCAA3E696F1/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/5974840AA7>) |
| 04e8:3321 | Samsung Elect... | M2020 Series                         | 56    | usblp      | [83DC415E28](<Notebook/Lenovo/IdeaPad/IdeaPad S340-15API 81NC/7BD961757C59/ELEMENTARY-6.1/5.13.0-30-GENERIC/X86_64/83DC415E28>) |
| 03f0:e111 | Hewlett-Packard  | DeskJet 2130 series                  | 50    | usblp      | [DAABBB468A](<Desktop/Intel/DH55HC/DH55HC AAE70933-502/31932C97B953/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/DAABBB468A>) |
| 04e8:344f | Samsung Elect... | SCX-3400 Series                      | 49    | usblp      | [2C4C04AE22](<Desktop/ONDA/A68/A68V+/BD0F36B63B74/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2C4C04AE22>) |
| 04a9:176d | Canon            | PIXMA MG2500 Series                  | 48    | usblp      | [450EF59CB0](<Desktop/MSI/MS-7/MS-7C96/24075414EE43/UBUNTU-21.10/5.13.0-24-GENERIC/X86_64/450EF59CB0>) |
| 04e8:3469 | Samsung Elect... | M2070 Series                         | 48    | usblp      | [1A54683C7C](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/BDEBEEDB188E/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/1A54683C7C>) |
| 04a9:2676 | Canon            | LBP2900                              | 45    | usblp      | [4A77DF037B](<Desktop/ASUSTek Computer/All/All Series/FC23525A6F48/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/4A77DF037B>) |
| 03f0:d711 | Hewlett-Packard  | ENVY 4520 series                     | 44    | usblp      | [544DBAC379](<Desktop/ASUSTek Computer/PRIME/PRIME Z390M-PLUS/D025DB076914/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/544DBAC379>) |
| 1a86:7584 | QinHeng Elect... | CH340S                               | 42    | usblp      | [4BF3474124](<Desktop/Dell/Inspiron/Inspiron 570/AFC6DE10B2A9/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/4BF3474124>) |
| 03f0:3d17 | Hewlett-Packard  | LaserJet P1005                       | 40    | usblp      | [FADE956732](<Desktop/Gigabyte Technology/GA-990X-Gaming/GA-990X-Gaming SLI-CF/B1D97F3C8C93/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/FADE956732>) |
| 04f9:0027 | Brother Indus... | HL-2030 Laser Printer                | 40    | usblp      | [35E716F504](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-D3/658541A7D930/DEBIAN-11/5.10.0-11-AMD64/X86_64/35E716F504>) |
| 03f0:0c17 | Hewlett-Packard  | LaserJet 1010                        | 35    | usblp      | [FB109E5618](<Desktop/MSI/MS-7/MS-7A36/2A38F13057E3/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/FB109E5618>) |
| 04e8:3292 | Samsung Elect... | ML-1640 Series Laser Printer         | 35    | usblp      | [F72047DC6D](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/CB26D11F0398/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/F72047DC6D>) |
| 04e8:3441 | Samsung Elect... | SCX-3200 Series                      | 35    | usblp      | [92FC99440A](<Desktop/Gigabyte Technology/G41/G41MT-D3/F935A8129A09/ALT-5.0.0/5.4.181-STD-DEF-ALT1/X86_64/92FC99440A>) |
| 03f0:e311 | Hewlett-Packard  | DeskJet 3630 series                  | 33    | usblp      | [0C4EA60FD5](<Desktop/ECS/A75/A75F2-M2/E97D6656E19B/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/0C4EA60FD5>) |
| 03f0:c211 | Hewlett-Packard  | Deskjet 2540 series                  | 32    | usblp      | [B4DB24332B](<Desktop/MSI/MS-7/MS-7C34/F0823A3CADC4/KUBUNTU-20.04/5.13.0-28-GENERIC/X86_64/B4DB24332B>) |
| 03f0:8711 | Hewlett-Packard  | Deskjet 2050 J510                    | 31    | usblp      | [9AE863D68C](<Desktop/MSI/MS-7/MS-7C02/CBD1E4CC3C10/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/9AE863D68C>) |
| 04a9:10dc | Canon            | iP7200 series                        | 31    | usblp      | [BA1C658949](<Desktop/ASUSTek Computer/M4A87TD/M4A87TD EVO/C4B869F1036A/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/BA1C658949>) |
| 04f9:0054 | Brother Indus... | HL-1110 series                       | 31    | usblp      | [3EC0BF0BC0](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/6DE1A1833E64/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/3EC0BF0BC0>) |
| 04b8:0005 | Seiko Epson      | Printer                              | 29    | usblp      | [EA2A58F958](<Desktop/MSI/MS/MS-7891/1B010B26E57A/LINUXMINT-20.3/5.4.0-70-GENERIC/X86_64/EA2A58F958>) |
| 03f0:8911 | Hewlett-Packard  | Deskjet 1050 J410                    | 28    | usblp      | [0171FA003C](<Notebook/Hewlett-Packard/255/255 G7 Notebook PC/1045F9222C2A/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/0171FA003C>) |
| 04a9:176b | Canon            | PIXMA MX920 Series                   | 28    | usblp      | [2F4A501C6A](<Desktop/ASUSTek Computer/P5/P5QC/FEDF7972330A/MAKULU-BUILD: 2021.12.15/5.11.0-41-GENERIC/X86_64/2F4A501C6A>) |
| 04da:0f0b | Panasonic (Ma... | KX-MB1500RU                          | 28    | usblp      | [FC801D2C87](<Desktop/MSI/MS/MS-7430/52FA0FB900EF/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-I586/I686/FC801D2C87>) |
| 03f0:102a | Hewlett-Packard  | LaserJet Professional P 1102w        | 27    | usblp      | [4F7FD0EE2A](<Desktop/Medion/MS/MS-7748/C94B4581FB39/LINUXMINT-20.2/5.13.0-27-GENERIC/X86_64/4F7FD0EE2A>) |
| 04b8:002a | Seiko Epson      | USB2.0 Printer (Hi-speed)            | 27    | usblp      | [D5BDA28E79](<Desktop/Gigabyte Technology/H310M/H310M H/0AF1BD31AC43/KDE-NEON-20.04/5.8.0-59-GENERIC/X86_64/D5BDA28E79>) |
| 04a9:2737 | Canon            | MF4410                               | 26    | usblp      | [55CE4F1460](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/A185B7D2F341/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/55CE4F1460>) |
| 04a9:2759 | Canon            | MF3010                               | 26    | usblp      | [FCBB29A9CF](<Notebook/ASUSTek Computer/X541/X541UJ/022E78203929/ENDLESS-3.3.14/4.13.0-32-GENERIC/X86_64/FCBB29A9CF>) |
| 04b8:0007 | Seiko Epson      | Printer                              | 26    | usblp      | [AA62962D75](<Desktop/ASRock/X570M/X570M Pro4/A16A344DA6A7/DEBIAN-10/5.10.0-5MX-AMD64/X86_64/AA62962D75>) |
| 03f0:0317 | Hewlett-Packard  | LaserJet 1200                        | 25    | usblp      | [5A5F32380C](<Desktop/MSI/MS-7/MS-7C91/BD867F970B95/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/5A5F32380C>) |
| 04a9:178a | Canon            | PIXMA MG3600 Series                  | 25    | usbfs      | [C197C7FD6E](<Mini Pc/AMI/Aptio/Aptio CRB/75857A8874A3/LINUXMINT-19.3/5.4.0-100-GENERIC/X86_64/C197C7FD6E>) |
| 04e8:330f | Samsung Elect... | ML-216x Series Laser Printer         | 25    | usblp      | [E5EAEC6553](<Desktop/Hewlett-Packard/Pro/Pro 3000 Microtower PC/5B8622E21C1D/DEBIAN-11/5.10.0-11-AMD64/X86_64/E5EAEC6553>) |
| 03f0:2c17 | Hewlett-Packard  | LaserJet 1022                        | 23    | usblp      | [BA54A33408](<Desktop/ASUSTek Computer/P8H61-MX/P8H61-MX R2.0/77261C75F854/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/BA54A33408>) |
| 04b8:08a1 | Seiko Epson      | L210 Series                          | 23    | usblp      | [7AEE651D14](<Desktop/ASUSTek Computer/P8/P8H61-MX/55B4E29FCEF1/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/7AEE651D14>) |
| 03f0:032a | Hewlett-Packard  | LaserJet Professional P1102w         | 22    | usblp      | [5E908476AC](<Desktop/MSI/MS-7/MS-7C75/25A25CCA8B4E/LINUXMINT-20.2/5.13.0-35-GENERIC/X86_64/5E908476AC>) |
| 03f0:2504 | Hewlett-Packard  | DeskJet F4200 series                 | 22    | usblp      | [4902F63911](<Desktop/MSI/MS/MS-7850/D6781F3D951B/UBUNTU-20.04/5.4.0-48-GENERIC/X86_64/4902F63911>) |
| 03f0:9311 | Hewlett-Packard  | Deskjet 3050 J610 series             | 22    | usblp      | [B98AE7B6B2](<Desktop/MSI/MS-7/MS-7C02/3B0DD57EBCE9/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/B98AE7B6B2>) |
| 03f0:0853 | Hewlett-Packard  | ENVY 5000 series                     | 21    | usblp      | [6D2BEC51F3](<Desktop/Lenovo/V520S-08IKL/V520S-08IKL 10NM0064UK/D3008C18828D/MANJARO/5.17.0-1-MANJARO/X86_64/6D2BEC51F3>) |
| 03f0:1853 | Hewlett-Packard  | DeskJet 2700 series                  | 20    | usblp      | [3B0D723E31](<Server/Dell/PowerEdge/PowerEdge R720/6808912223D2/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/3B0D723E31>) |
| 03f0:1d17 | Hewlett-Packard  | LaserJet 1320                        | 20    | usblp      | [DD50FE59B2](<Desktop/ASUSTek Computer/P5/P5Q3/B32A1E421931/LINUXMINT-19.3/5.4.0-65-GENERIC/X86_64/DD50FE59B2>) |
| 03f0:3217 | Hewlett-Packard  | LaserJet 3050                        | 20    | usblp      | [54E546F9AE](<Desktop/Dell/OptiPlex/OptiPlex 745/6657406C3AF9/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/54E546F9AE>) |
| 03f0:3e17 | Hewlett-Packard  | LaserJet P1006                       | 20    | usblp      | [7122E4BD16](<Desktop/Intel/DG31PR/DG31PR AAD97573-302/E43AAC1C2957/LMDE-4/4.19.0-17-AMD64/X86_64/7122E4BD16>) |
| 04a9:1913 | Canon            | CanoScan LiDE 300                    | 20    | usbfs      | [6A5D19D886](<Desktop/Dell/OptiPlex/OptiPlex 790/9DFE064A27F3/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/6A5D19D886>) |
| 04a9:26b4 | Canon            | MF4010 series                        | 20    | usblp      | [DD197ECB62](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/04ACB3192408/FEDORA-35/5.15.10-200.FC35.X86_64/X86_64/DD197ECB62>) |
| 04b8:1143 | Seiko Epson      | ET-2710 Series                       | 20    | usblp      | [B36BBA1DAC](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 USDT/2E4DEF4CCC04/LINUXMINT-20.3/5.4.0-92-GENERIC/X86_64/B36BBA1DAC>) |
| 04f9:003f | Brother Indus... | HL-2130 series                       | 20    | usblp      | [E5B45F315C](<Desktop/Hewlett-Packard/500/500-512ng/5BCD4728D36B/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/E5B45F315C>) |

### Scanner (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 04a9:1909 | Canon            | CanoScan LiDE 110                    | 94    | usbfs      | [E5EAEC6553](<Desktop/Hewlett-Packard/Pro/Pro 3000 Microtower PC/5B8622E21C1D/DEBIAN-11/5.10.0-11-AMD64/X86_64/E5EAEC6553>) |
| 04a9:2220 | Canon            | CanoScan LIDE 25                     | 74    | usbfs      | [4D2A0C8D41](<Desktop/ASUSTek Computer/P5K/P5K Deluxe/6F368BD5A85D/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/4D2A0C8D41>) |
| 04a9:220d | Canon            | CanoScan N670U/N676U/LiDE 20         | 63    |            | [4A89454909](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/A7B435E0E41E/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/4A89454909>) |
| 04a9:190a | Canon            | CanoScan LiDE 210                    | 60    |            | [54B2E986DA](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/641A833947C7/DEBIAN-9/4.19.0-6-AMD64/X86_64/54B2E986DA>) |
| 04a9:190f | Canon            | CanoScan LiDE 220                    | 49    | usbfs      | [AD6823C08E](<Notebook/Samsung Electronics/750/750XDA/7EAFD985038F/FEDORA-35/5.16.9-200.FC35.X86_64/X86_64/AD6823C08E>) |
| 04a9:190e | Canon            | CanoScan LiDE 120                    | 39    | usbfs      | [B1E6F7CD7C](<Desktop/Gigabyte Technology/Z370/Z370 HD3/CE538DD137E9/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/B1E6F7CD7C>) |
| 03f0:0a01 | Hewlett-Packard  | ScanJet 2400c                        | 33    | usbfs      | [42CD4D28BD](<Desktop/ASRock/FM2/FM2A55M-HD+/49742D3655A8/ZORIN-16/5.11.0-38-GENERIC/X86_64/42CD4D28BD>) |
| 04a9:220e | Canon            | CanoScan N1240U/LiDE 30              | 29    | usbfs      | [66F88A032F](<Desktop/Dell/Precision/Precision T5600/5F2EC5F04A2D/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/66F88A032F>) |
| 04a9:1904 | Canon            | CanoScan LiDE 100                    | 28    |            | [5B7A77242B](<Desktop/ASRock/970/970 Pro3 R2.0/F7DDA159B064/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/5B7A77242B>) |
| 04b8:0142 | Seiko Epson      | GT-F730 [GT-S630/Perfection V33/V... | 26    | usbfs      | [3AB4EBDBFD](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/CE519D9CC12C/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/3AB4EBDBFD>) |
| 04b8:0121 | Seiko Epson      | GT-F500/GT-F550 [Perfection 2480/... | 24    |            | [736A64DF69](<Notebook/Others/Others/Others/CD6E6E07013C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/736A64DF69>) |
| 05d8:4002 | Ultima Electr... | Artec Ultima 2000 (GT6801 based)/... | 23    | usbfs      | [0C5E09B00C](<Desktop/Gigabyte Technology/G31/G31M-ES2L/92F7C923C047/LINUXMINT-19.3/5.4.0-74-GENERIC/X86_64/0C5E09B00C>) |
| 04b8:0130 | Seiko Epson      | GT-X770 [Perfection V500]            | 19    |            | [DCA1097E4A](<Desktop/Gigabyte Technology/GB-BRR7/GB-BRR7H-4800/CEB0BCD0C10E/FEDORA-35/5.15.18-200.FC35.X86_64/X86_64/DCA1097E4A>) |
| 04a9:221c | Canon            | CanoScan LiDE 60                     | 17    |            | [50AE24D560](<Desktop/Gigabyte Technology/P35/P35-DS3/885A7B20C17D/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/50AE24D560>) |
| 04b8:012d | Seiko Epson      | GT-F650 [GT-S600/Perfection V10/V... | 17    |            | [55067D6AFE](<System On Chip/Hardkernel/ODROID-N2/ODROID-N2Plus/22FA5E73FA5C/UBUNTU-MATE-20.04/4.9.277-119/AARCH64/55067D6AFE>) |
| 04a9:2213 | Canon            | CanoScan LiDE 50/LiDE 35/LiDE 40     | 16    |            | [2E6F278ACA](<Desktop/Hewlett-Packard/Z220/Z220 SFF Workstation/28427FF450FC/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/2E6F278ACA>) |
| 04b8:0122 | Seiko Epson      | GT-F520/GT-F570 [Perfection 3590 ... | 16    | usbfs      | [524718F4AB](<Desktop/Hewlett-Packard/500/500-512ng/5BCD4728D36B/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/524718F4AB>) |
| 055f:021b | Mustek Systems   | BearPaw 1200 CU Plus                 | 16    | usbfs      | [DE63F89D08](<Desktop/Gigabyte Technology/H61/H61M-D2H/8ACC07EA8985/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/DE63F89D08>) |
| 04b8:013a | Seiko Epson      | GT-X820 [Perfection V600 Photo]      | 15    |            | [DBD2218092](<Desktop/Dell/Inspiron/Inspiron 3847/2D8237EE3FDF/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/DBD2218092>) |
| 04a9:1907 | Canon            | CanoScan LiDE 700F                   | 13    | usbfs      | [AF24409637](<Desktop/Gigabyte Technology/GA-MA78/GA-MA78GM-S2H/653306D443E6/UBUNTU-19.10/5.3.0-64-GENERIC/X86_64/AF24409637>) |
| 04b8:011f | Seiko Epson      | GT-8400UF [Perfection 1670/1670 P... | 13    |            | [3781103124](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/BCFF47B91DE6/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/3781103124>) |
| 04b8:0120 | Seiko Epson      | GT-7400U [Perfection 1270]           | 13    |            | [2FCE3F9ABF](<Desktop/Gigabyte Technology/F2/F2A55-DS3/744651733A34/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/2FCE3F9ABF>) |
| 055f:021f | Mustek Systems   | SNAPSCAN e22                         | 13    |            | [F8F7E8AC88](<Desktop/Hewlett-Packard/Pro/Pro 3400 Series MT/D80486EC1E02/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/F8F7E8AC88>) |
| 04a9:1905 | Canon            | CanoScan LiDE 200                    | 12    |            | [B8432BE2DA](<Desktop/Dell/OptiPlex/OptiPlex 790/60670905F03D/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B8432BE2DA>) |
| 04b8:011b | Seiko Epson      | GT-9300UF [Perfection 2400 PHOTO]    | 11    |            | [4225E4762C](<Desktop/ASRock/960GM-U3S3/960GM-U3S3 FX/79A0F56F47C4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/4225E4762C>) |
| 04b8:013b | Seiko Epson      | Scanner                              | 10    |            | [6E5A2E29F4](<Notebook/Packard Bell/EasyNote/EasyNote TE11HC/FFDFCA409720/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/6E5A2E29F4>) |
| 04a9:2228 | Canon            | CanoScan 4400F                       | 9     |            | [41F46AC946](<Desktop/Lenovo/ThinkStation/ThinkStation P340 30DH00LNGE/88BEEBA28E49/UBUNTU-20.04/5.10.0-1051-OEM/X86_64/41F46AC946>) |
| 04b8:0119 | Seiko Epson      | GT-X750 [Perfection 4490 Photo]      | 9     |            | [3B3B0C2855](<Desktop/ASRock/B450/B450 Pro4/F162FDCE2EB3/FEDORA-35/5.15.11-200.FC35.X86_64/X86_64/3B3B0C2855>) |
| 04b8:012e | Seiko Epson      | GT-F670 [Perfection V200 Photo]      | 9     |            | [EDD8B3C5B2](<Desktop/ASUSTek Computer/PRIME/PRIME X399-A/8D222005E7BF/FEDORA-34/5.13.12-200.FC34.X86_64/X86_64/EDD8B3C5B2>) |
| 04b8:0131 | Seiko Epson      | GT-F720 [GT-S620/Perfection V30/V... | 9     |            | [358B325347](<Desktop/Hewlett-Packard/Elite/Elite 7100 Microtower PC/C0BA6ED69CE0/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/358B325347>) |
| 03f0:1c05 | Hewlett-Packard  | Scanjet 200                          | 8     |            | [FEBB5AEE31](<Desktop/Hewlett-Packard/Compaq/Compaq 4000 Pro SFF PC/BDB5B57704B3/LINUXMINT-19.3/5.4.0-47-GENERIC/X86_64/FEBB5AEE31>) |
| 03f0:2605 | Hewlett-Packard  | ScanJet 3800c                        | 8     |            | [4005AC4804](<Desktop/Dell/OptiPlex/OptiPlex 7010/374D4E3403B9/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/4005AC4804>) |
| 04a9:1900 | Canon            | CanoScan LiDE 90                     | 8     |            | [2B7A430FCD](<Notebook/Lenovo/G/G700/40AE6DE53839/ZORIN-16/5.11.0-41-GENERIC/X86_64/2B7A430FCD>) |
| 055f:021d | Mustek Systems   | BearPaw 2400 CU Plus                 | 8     |            | [A5CA2582B6](<Desktop/ASUSTek Computer/M2N-MX/M2N-MX SE Plus/BFA5BBD7D3FC/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/A5CA2582B6>) |
| 03f0:1705 | Hewlett-Packard  | ScanJet 5590                         | 7     |            | [D1ECE8006F](<Notebook/Dell/Vostro/Vostro 3700/CCE06CD81EB7/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D1ECE8006F>) |
| 03f0:2305 | Hewlett-Packard  | ScanJet 3970c                        | 7     |            | [2EA42468C2](<Desktop/ASRock/970/970 Extreme3/1168F2ECBF12/UBUNTU-21.10/5.13.0-29-GENERIC/X86_64/2EA42468C2>) |
| 04a9:1908 | Canon            | CanoScan                             | 7     | usbfs      | [8EE3D68631](<Desktop/MSI/MS-7/MS-7B86/D81D4029A3DB/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/8EE3D68631>) |
| 04a9:2206 | Canon            | CanoScan N650U/N656U                 | 7     |            | [CF8D063DEB](<Desktop/Dell/DXP/DXP051/A206B2198B0D/XUBUNTU-18.04/5.4.0-87-GENERIC/X86_64/CF8D063DEB>) |
| 04a9:2224 | Canon            | CanoScan LiDE 600F                   | 7     |            | [E83C271E2E](<Notebook/Samsung Electronics/750/750XDA/9EA80D93B036/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/E83C271E2E>) |
| 04a9:2225 | Canon            | CanoScan LiDE 70                     | 7     |            | [DCE96AE07E](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/58EDD3F685A7/FEDORA-34/5.13.6-200.FC34.X86_64/X86_64/DCE96AE07E>) |
| 04b8:010f | Seiko Epson      | GT-7200U [Perfection 1250/1250 PH... | 7     |            | [AE15BD941D](<Notebook/MSI/GT/GT70/C29DA523610A/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/AE15BD941D>) |
| 055f:0006 | Mustek Systems   | ScanExpress 1200 UB                  | 7     |            | [ADF9EBB679](<Desktop/Hewlett-Packard/rp/rp5800/951DDEC480BE/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/ADF9EBB679>) |
| 055f:021c | Mustek Systems   | BearPaw 1200 CU Plus                 | 7     | usbfs      | [74E1239BF6](<Desktop/MSI/MS-7/MS-7C51/20A3B43FF05A/ROSA-2014.1/4.9.9-NRJ-DESKTOP-1ROSA-I586/I686/74E1239BF6>) |
| 03f0:0605 | Hewlett-Packard  | ScanJet 2200c                        | 6     |            | [398B45ED60](<Desktop/Dell/OptiPlex/OptiPlex 790/54C6DC6065E9/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/398B45ED60>) |
| 03f0:0b01 | Hewlett-Packard  | ScanJet 82x0C                        | 6     | usbfs      | [D5BD9C64AF](<Desktop/Hewlett-Packard/Z200/Z200 Workstation/EB18FD4B082C/KUBUNTU-21.10/5.13.0-22-GENERIC/X86_64/D5BD9C64AF>) |
| 03f0:1d05 | Hewlett-Packard  | Scanjet 300                          | 6     |            | [56EBB4B643](<Desktop/ASRock/B450/B450 Pro4/B6B9FADE9135/DEBIAN-11/5.10.0-10-AMD64/X86_64/56EBB4B643>) |
| 03f0:2f11 | Hewlett-Packard  | PSC 1200                             | 6     | usblp      | [D6AEDCE9DD](<Desktop/Hewlett-Packard/260/260-a010/73FAC14A1A4D/KDE-NEON-20.04/5.11.0-41-GENERIC/X86_64/D6AEDCE9DD>) |
| 04a5:20b0 | Acer Peripher... | S2W 3300U/4300U                      | 6     |            | [E6F96C5F67](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800 Small Form Factor/1ED8D250F9AD/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/E6F96C5F67>) |
| 04a9:190d | Canon            | CanoScan 9000F Mark II               | 6     |            | [7BC924ADF2](<Desktop/Acer/Aspire/Aspire XC-105/7CF14550D2EF/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/7BC924ADF2>) |
| 04a9:221f | Canon            | CanoScan LiDE 500F                   | 6     |            | [86D1CDAE24](<Notebook/Dell/Studio/Studio 1735/2BC071C85299/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/86D1CDAE24>) |

### Serial controller (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a86:7523 | QinHeng Elect... | CH340 serial converter               | 319   | ch341      | [C39FE1A3E3](<Notebook/Dell/XPS/XPS 15 9550/0E22532FC18F/ARCH/5.16.11-ARCH1-2/X86_64/C39FE1A3E3>) |
| 0403:6001 | Future Techno... | FT232 Serial (UART) IC               | 302   | ftdi_sio   | [8DFA30CEF5](<Desktop/MSI/MS/MS-7695/574085D7676B/ZORIN-16/5.13.0-30-GENERIC/X86_64/8DFA30CEF5>) |
| 067b:2303 | Prolific Tech... | PL2303 Serial Port / Mobile Actio... | 235   | pl2303     | [4946A1C5B0](<Desktop/EVGA/X58/X58 SLI FTW3 Tylersburg/884AEF04753E/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/4946A1C5B0>) |
| 10c4:ea60 | Silicon Labs     | CP210x UART Bridge                   | 195   | cp210x     | [2AB16BFCEE](<Notebook/Apple/MacBookPro9/MacBookPro9,2/69963227A53F/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/2AB16BFCEE>) |
| 05c6:9204 | Qualcomm         | Gobi 2000                            | 100   | qcserial   | [4601C3AA77](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537VGY/60E94FBE6817/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/4601C3AA77>) |
| 03f0:521d | Hewlett-Packard  | HP hs3110 HSPA+ Mobile Broadband ... | 75    | option     | [B2AEEA55E5](<Notebook/Hewlett-Packard/EliteBook/EliteBook 850 G1/54841F6E7861/MANJARO/5.16.11-2-MANJARO/X86_64/B2AEEA55E5>) |
| 03f0:241d | Hewlett-Packard  | Gobi 2000 Wireless Modem (QDL mode)  | 51    | qcserial   | [02D7F3125E](<Notebook/Hewlett-Packard/ProBook/ProBook 6550b/CA13DC5FE278/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/02D7F3125E>) |
| 12d1:15c1 | Huawei Techno... | ME906s LTE M.2 Module                | 47    | option     | [566EEE23F5](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Carbon 4th 20FRS08T00/3A0B7992B26B/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/566EEE23F5>) |
| 0451:3410 | Texas Instrum... | TUSB3410 Microcontroller             | 46    | ti_usb_... | [C447074D2B](<Notebook/Others/Others/Others/11A6F365658A/LINUXMINT-19.3/5.4.0-99-GENERIC/X86_64/C447074D2B>) |
| 1199:9013 | Sierra Wireless  | Sierra Wireless Gobi 3000 Modem d... | 42    | qcserial   | [0E2BB9A59F](<Notebook/Lenovo/ThinkPad/ThinkPad T420 423664U/4B32022D42B9/ARCH-ROLLING/5.16.1-ARCH1-1/X86_64/0E2BB9A59F>) |
| 2c7c:0125 | Quectel Wirel... | EC25 LTE modem                       | 39    | qmi_wwan   | [8898D4987B](<Phone/Pine Microsystems/Pine64/Pine64 PinePhone/C9B315D66825/DEBIAN-TESTING/5.15-SUNXI64/AARCH64/8898D4987B>) |
| 03f0:a31d | Hewlett-Packard  | lt4132 LTE/HSPA+ 4G Module           | 36    | option     | [7D5295D845](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/ADD2F9FD8AC9/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/7D5295D845>) |
| 0403:6015 | Future Techno... | Bridge(I2C/SPI/UART/FIFO)            | 34    | ftdi_sio   | [1D6563ADA3](<Desktop/MSI/MS-7/MS-7B89/40C39ADB36D3/NIXOS-22.05/5.15.26/X86_64/1D6563ADA3>) |
| 0403:6010 | Future Techno... | FT2232C/D/H Dual UART/FIFO IC        | 33    | ftdi_sio   | [8CF015E233](<Notebook/Dell/Precision/Precision 3530/D27865B8B747/ARCH/5.16.10-ARCH1-1/X86_64/8CF015E233>) |
| 1b1c:1c00 | Corsair          | Controller for Corsair Link          | 30    | cp210x     | [2B6FD5817C](<Desktop/ASUSTek Computer/All/All Series/9233691B251D/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/2B6FD5817C>) |
| 19d2:0016 | ZTE WCDMA Tec... | ZTE WCDMA Technologies MSM           | 24    | option     | [EB04CF12AA](<Desktop/Hewlett-Packard/Compaq/Compaq dc5800 Small Form Factor/6A6794F38E8F/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/EB04CF12AA>) |
| 1199:9000 | Sierra Wireless  | Gobi 2000 Wireless Modem (QDL mode)  | 22    | qcserial   | [396C65C24C](<Notebook/Getac/V100/V100-X/3FABEFD5B35A/LINUXMINT-20.3/5.4.0-99-GENERIC/X86_64/396C65C24C>) |
| 0403:6014 | Future Techno... | FT232H Single HS USB-UART/FIFO IC    | 20    | ftdi_sio   | [D4D5AA3B0A](<Desktop/ASRock/X370/X370 Taichi/98874DA76438/POP!_OS-20.04/5.15.15-76051515-GENERIC/X86_64/D4D5AA3B0A>) |
| 03f0:201d | Hewlett-Packard  | un2400 Gobi Wireless Modem (QDL m... | 19    | qcserial   | [82000C3346](<Notebook/Hewlett-Packard/EliteBook/EliteBook 6930p/9043BC01FF36/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/82000C3346>) |
| 0fcf:1008 | Dynastream In... | ANTUSB2 Stick                        | 17    | usb_ser... | [5E7B7A63A9](<Notebook/ASUSTek Computer/GL552/GL552VW/138484BF59CB/ZORIN-16/5.13.0-27-GENERIC/X86_64/5E7B7A63A9>) |
| 10c4:ea70 | Cygnal Integr... | CP210x UART Bridge                   | 17    | cp210x     | [7EF7B85267](<Server/Supermicro/X9/X9SRA-X9SRA-3/6DA328B1EF68/UBUNTU-18.04/4.15.0-166-GENERIC/X86_64/7EF7B85267>) |
| 413c:8185 | Dell             | Gobi 2000 Wireless Modem (QDL mode)  | 17    | qcserial   | [FF6A48346F](<Notebook/Dell/Latitude/Latitude XT2/876C72737DC9/PARROT-5.0/5.15.0-15PARROT1-AMD64/X86_64/FF6A48346F>) |
| 05c6:9224 | Qualcomm         | Sony Gobi 2000 Wireless Modem (QD... | 15    | qcserial   | [41F76E701C](<Notebook/Sony/VPCZ11/VPCZ11X9E/C671B6A03CAD/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/41F76E701C>) |
| 0fcf:1009 | Dynastream In... | ANTUSB-m Stick                       | 15    | usb_ser... | [DC41D8A6AD](<Notebook/Medion/E7419/E7419 MD60025/8D8AA73E9981/LINUXMINT-20.3/5.4.0-99-GENERIC/X86_64/DC41D8A6AD>) |
| 0403:6011 | Future Techno... | FT4232H Quad HS USB-UART/FIFO IC     | 14    | ftdi_sio   | [41AC7EFFBE](<Notebook/Hewlett-Packard/ZBook/ZBook 15 G6/10E50F1DF495/UBUNTU-18.04/5.4.0-104-GENERIC/X86_64/41AC7EFFBE>) |
| 0557:2008 | ATEN Internat... | UC-232A Serial Port [pl2303]         | 13    | pl2303     | [2CE44E02C7](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/C438AD4B7273/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/2CE44E02C7>) |
| 0d9f:0002 | Powercom         | Black Knight PRO / WOW Uninterrup... | 13    | cypress... | [3F52A340FB](<Desktop/ASUSTek Computer/M4/M4A78LT-M-LE/E8A0F296662B/ROSA-2016.1/5.4.32-GENERIC-2ROSA-X86_64/X86_64/3F52A340FB>) |
| 19d2:2003 | ZTE WCDMA Tec... | ZTE WCDMA Technologies MSM           | 13    | option     | [F125F4CD03](<Desktop/ASRock/775/775Dual-880Pro/1F74339C25D8/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/F125F4CD03>) |
| 05c6:9008 | Qualcomm         | Gobi Wireless Modem (QDL mode)       | 11    | qcserial   | [1AA838368F](<Notebook/Hewlett-Packard/EliteBook/EliteBook Folio 9470m/527B27C7CA82/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/1AA838368F>) |
| 04b4:5500 | Cypress Semic... | HID->COM RS232 Adapter               | 10    | cypress... | [8F98E59D90](<Desktop/ASUSTek Computer/All/All Series/DB4EA47B8E1C/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/8F98E59D90>) |
| 0af0:6901 | Option           | Globetrotter HSDPA Modem             | 10    | option     | [EE6FDF4608](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile D9500/DF33913DD5B2/MX-21/5.10.0-8-AMD64/X86_64/EE6FDF4608>) |
| 1199:683c | Sierra Wireless  | Mobile Broadband 3G/UMTS (MC8790 ... | 10    | sierra     | [019B0AEEEA](<Notebook/Dell/Latitude/Latitude E6420/0530629A75F0/ARCH-ROLLING/5.16.5-ARCH1-1/X86_64/019B0AEEEA>) |
| 03f0:1e1d | Hewlett-Packard  | hs2300 HSDPA Broadband Wireless M... | 9     | sierra     | [677180A63E](<Notebook/Hewlett-Packard/Compaq/Compaq 6910p/D384BC4BEB35/BLACKARCH/5.13.10-ARCH1-1/X86_64/677180A63E>) |
| 057c:6201 | AVM              | AVM Fritz!WLAN v1.1 [Texas Instru... | 7     | option     | [3C0A297EDE](<Desktop/ASUSTek Computer/V-P7/V-P7H55E/0AE0678A444E/LMDE-4/4.19.0-16-AMD64/X86_64/3C0A297EDE>) |
| 05c6:9221 | Qualcomm         | Gobi Wireless Modem (QDL mode)       | 7     | qcserial   | [D3465ABE44](<Notebook/Sony/VGN-Z690/VGN-Z690N/C7EACBA309C4/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D3465ABE44>) |
| 10c4:8a2a | Silicon Labs     | HubZ Smart Home Controller           | 7     | cp210x     | [F09C3F33E1](<Desktop/Lenovo/ThinkCentre/ThinkCentre M73 10AXS0HN00/E78423790E14/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/F09C3F33E1>) |
| 1199:6832 | Sierra Wireless  | MC8780 Device                        | 7     | sierra     | [3B7266D323](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK S6410/66E7AC9B5367/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/3B7266D323>) |
| 413c:8133 | Dell             | Wireless 5720 VZW Mobile Broadban... | 7     | option     | [712B22AD9B](<Notebook/Dell/Latitude/Latitude D630/1F554D557F80/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/712B22AD9B>) |
| 413c:81d7 | Dell             | DW5821e Snapdragon X20 LTE           | 7     | option     | [64EF1D30C3](<Notebook/Dell/Latitude/Latitude 7424 Rugged Extreme/8E222DD36428/DEBIAN-TESTING/5.15.0-3-AMD64/X86_64/64EF1D30C3>) |
| 0711:0230 | Magic Control... | MCT-232 Serial Port                  | 6     | mct_u232   | [228A05B70F](<Notebook/Medion/P6687/P6687 MD60815/F113B192EF67/LINUXMINT-20/4.19.163-0419163-GENERIC/X86_64/228A05B70F>) |
| 10c4:ea71 | Silicon Labs     | CP2108 Quad UART Bridge              | 5     | cp210x     | [CE3945EA8E](<Notebook/TQ-Group/TQMxE39/TQMxE39S/5FC90CEA47A4/LINUXMINT-20.1/5.4.0-72-GENERIC/X86_64/CE3945EA8E>) |
| 1199:6813 | Sierra Wireless  | Mini Card                            | 5     | sierra     | [56D9CF2086](<Notebook/Lenovo/ThinkPad/ThinkPad X300 40521TG/3A897A884F5E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/56D9CF2086>) |
| 1410:2420 | Novatel Wireless | Expedite EU850D/EU860D/EU870D        | 5     | option     | [99920AD031](<Notebook/Panasonic/CF-19/CF-19KDR80SH/1EDE63316A37/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/99920AD031>) |
| 1e0e:9001 | Qualcomm / Op... | SimTech, Incorporated                | 5     | option     | [4ED85A0F7A](<Mini Pc/AMI/Aptio/Aptio CRB/0D152C7E6A1B/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/4ED85A0F7A>) |
| 413c:819b | Dell             | Novatel Wireless HSPA                | 5     | option     | [FE6DBDEF48](<Notebook/Dell/Latitude/Latitude E6530/4D2A9830B4C8/ZORIN-16/5.11.0-40-GENERIC/X86_64/FE6DBDEF48>) |
| 04da:250c | Panasonic (Ma... | Gobi Wireless Modem (QDL mode)       | 4     | qcserial   | [29EEE33555](<Notebook/Panasonic/CF-19/CF-19KDR78CE/D497CC204F4F/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/29EEE33555>) |
| 0f3d:68aa | Airprime, Inc... | AirCard 320U                         | 4     | uas, us... | [1473909011](<Notebook/Apple/MacBook3/MacBook3,1/6E18E43E0A90/ZORIN-16/5.11.0-27-GENERIC/X86_64/1473909011>) |
| 1199:68c0 | Sierra Wireless  | MC7304                               | 4     | qcserial   | [BF7C2C6D9B](<Mini Pc/NEXCOM/VTC/VTC1010/6EF054560413/DEBIAN-11/5.10.0-11-AMD64/X86_64/BF7C2C6D9B>) |
| 19d2:0117 | ZTE WCDMA Tec... | USB SCSI CD-ROM                      | 4     | uas, us... | [01068C79DF](<Desktop/Lenovo/ThinkCentre/ThinkCentre A57 98517HG/D1ABDBF6BE80/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/01068C79DF>) |
| 1bbb:022c | T & A Mobile ... | HSPA+ USB Modem                      | 4     | usbseri... | [A348E53594](<Notebook/ASUSTek Computer/X502/X502CA/E9240330976A/ROSA-2014.1/4.1.25-NRJ-DESKTOP-1ROSA-X86_64/X86_64/A348E53594>) |

### Sound (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0d8c:0014 | C-Media Elect... | Audio Adapter (Unitek Y-247A)        | 419   | snd_usb... | [89FF3431E1](<Notebook/Positivo/S14/S14CT01/B717D1200791/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/89FF3431E1>) |
| 1b3f:2008 | Generalplus T... | USB Audio Device                     | 330   | snd_usb... | [FBD59F7138](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D671C8895F06/CLEAR-LINUX-OS-35970/5.16.11-1128.NATIVE/X86_64/FBD59F7138>) |
| 0d8c:013c | C-Media Elect... | CM108 Audio Controller               | 280   | snd_usb... | [1784618CFE](<Desktop/Dell/OptiPlex/OptiPlex 990/88E8A2C02B82/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/1784618CFE>) |
| 08bb:2902 | Texas Instrum... | PCM2902 Audio Codec                  | 277   | snd_usb... | [046572A251](<Notebook/Hewlett-Packard/ProBook/ProBook 650 G1/41CAFF8AA906/KALI-2022.1/5.16.0-KALI3-AMD64/X86_64/046572A251>) |
| 0d8c:0012 | C-Media Elect... | USB Audio Device                     | 253   | snd_usb... | [30DF05CC2F](<Desktop/Wortmann AG/TERRA_PC/TERRA_PC/A8AB20556C45/MANJARO/5.15.25-1-MANJARO/X86_64/30DF05CC2F>) |
| 0951:16a4 | Kingston Tech... | HyperX 7.1 Audio                     | 201   | snd_usb... | [989EEC2F5F](<Desktop/MSI/MS-7/MS-7A62/161A2AC8544D/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/989EEC2F5F>) |
| 0d8c:0005 | C-Media Elect... | Blue Snowball                        | 200   | snd_usb... | [B4D3516747](<Desktop/Biostar/B450/B450MHC/E3F2ADE33D69/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/B4D3516747>) |
| 0c76:161f | JMTek            | USB PnP Audio Device                 | 177   | snd_usb... | [C2D198AB83](<Notebook/ASUSTek Computer/X751/X751LD/915032EF5E9C/ARCH/5.16.11-ZEN1-1-ZEN/X86_64/C2D198AB83>) |
| 0bda:4014 | Realtek Semic... | USB Audio                            | 173   | snd_usb... | [311C6DA8E0](<Notebook/Hewlett-Packard/ProBook/ProBook 455 G7/656F39058145/MANJARO-21.2.4/5.16.11-2-MANJARO/X86_64/311C6DA8E0>) |
| 8086:0808 | Intel            | USB PnP Sound Device                 | 158   | snd_usb... | [38C8508BC0](<Desktop/ASRock/X570/X570 Phantom Gaming 4/C2ED70ED019A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/38C8508BC0>) |
| b58e:9e84 | Blue Microphones | Yeti Stereo Microphone               | 150   | snd_usb... | [3F58A0F2A4](<Notebook/Lenovo/Legion/Legion Y530-15ICH 81FV/A4B769895625/GENTOO-2.6/5.15.23-GENTOO/X86_64/3F58A0F2A4>) |
| 0bda:402e | Realtek Semic... | USB Audio                            | 149   | snd_usb... | [E7C5306C00](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc0xxx/1020FE6EFFAE/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/E7C5306C00>) |
| 0d8c:000c | C-Media Elect... | Audio Adapter                        | 142   | snd_usb... | [6034A2269A](<Desktop/MSI/MS/MS-7798/DA83C67B809F/ARCH/5.15.26-1-LTS/X86_64/6034A2269A>) |
| 1130:1620 | Tenx Technology  | USB AUDIO                            | 137   | snd_usb... | [1910BCDEA5](<Desktop/Hewlett-Packard/p6803/p6803w/751D08E7014B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/1910BCDEA5>) |
| 0d8c:0102 | C-Media Elect... | CM106 Like Sound Device              | 120   | snd_usb... | [EB3D721453](<Desktop/MSI/MS-7/MS-7B86/5624595CFCD3/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/EB3D721453>) |
| 0c76:161e | JMTek            | USB PnP Audio Device                 | 112   | snd_usb... | [F07A9BD206](<Desktop/Gigabyte Technology/B460/B460MDS3H/4E6DCAC3F74A/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/F07A9BD206>) |
| 046d:0a44 | Logitech         | Headset H390                         | 104   | snd_usb... | [747899DB53](<Desktop/MSI/MS-7/MS-7C95/D866DA6D8676/UBUNTU-21.04/5.16.10-VOID24-NOMAC-ZNVER3/X86_64/747899DB53>) |
| 413c:a503 | Dell             | AC511 USB SoundBar                   | 104   | snd_usb... | [3CBA5D22BC](<Desktop/MSI/MS/MS-7918/9432F9FD1040/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/3CBA5D22BC>) |
| 1852:7022 | GYROCOM C&C      | Fiio E10                             | 92    | snd_usb... | [6EA2FBDB95](<Desktop/ASRock/AB350M/AB350M Pro4/D2A97069C9C9/MANJARO/5.15.12-1-MANJARO/X86_64/6EA2FBDB95>) |
| 046d:0a8f | Logitech         | H390 headset with microphone         | 84    | snd_usb... | [7280C9C630](<Notebook/Dell/Inspiron/Inspiron 3583/1A2FDF4BA7DD/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/7280C9C630>) |
| 0d8c:0134 | C-Media Elect... | TONOR TC30 Audio Device              | 83    | snd_usb... | [61F8410ABD](<Desktop/Gigabyte Technology/AX370-Gaming/AX370-Gaming K5/180A39028A18/ZORIN-16/5.13.0-28-GENERIC/X86_64/61F8410ABD>) |
| 046d:0a29 | Logitech         | H600 [Wireless Headset]              | 81    | snd_usb... | [E5EAEC6553](<Desktop/Hewlett-Packard/Pro/Pro 3000 Microtower PC/5B8622E21C1D/DEBIAN-11/5.10.0-11-AMD64/X86_64/E5EAEC6553>) |
| 17ef:3083 | Lenovo           | ThinkPad Thunderbolt 3 Dock USB A... | 77    | snd_usb... | [48C1285EEC](<Notebook/Lenovo/ThinkPad/ThinkPad P53 20QN0011IV/90C24C7500E3/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/48C1285EEC>) |
| 17ef:a396 | Lenovo           | ThinkPad USB-C Dock Gen2 USB Audio   | 77    | snd_usb... | [B48A6240BF](<Notebook/Lenovo/ThinkPad/ThinkPad E15 20RD0016GE/4F4BEFFC091C/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/B48A6240BF>) |
| 046d:0a4d | Logitech         | G430 Surround Sound Gaming Headset   | 76    | snd_usb... | [E72B93AADF](<Notebook/Hewlett-Packard/ProBook/ProBook 440 G8 Notebook PC/F9CE94130923/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/E72B93AADF>) |
| 0d8c:0103 | C-Media Elect... | CM102-A+/102S+ Audio Controller      | 74    | snd_usb... | [4C71606B0A](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/4C71606B0A>) |
| 045e:070f | Microsoft        | LifeChat LX-3000 Headset             | 73    | snd_usb... | [ADA27693C4](<Desktop/ASRock/B550/B550 Phantom Gaming 4-ac/CC4B5F41D3F5/FEDORA-35/5.15.15-200.FC35.X86_64/X86_64/ADA27693C4>) |
| 054c:09cc | Sony             | DualShock 4 [CUH-ZCT2x]              | 68    | snd_usb... | [2B3E0F8609](<Desktop/Gigabyte Technology/B450M/B450M DS3H V2/3F0AA1D17C90/KDE-NEON-20.04/5.13.0-28-GENERIC/X86_64/2B3E0F8609>) |
| 1038:12ad | SteelSeries ApS  | SteelSeries Arctis 7                 | 68    | snd_usb... | [EAA5B0F454](<Desktop/ASUSTek Computer/PRIME/PRIME B460M-A/28091A90C0B8/UBUNTU-21.04/5.11.0-49-GENERIC/X86_64/EAA5B0F454>) |
| 1395:0025 | Sennheiser Co... | Headset [PC 8]                       | 63    | snd_usb... | [1D6563ADA3](<Desktop/MSI/MS-7/MS-7B89/40C39ADB36D3/NIXOS-22.05/5.15.26/X86_64/1D6563ADA3>) |
| 046d:0a66 | Logitech         | [G533 Wireless Headset Dongle]       | 59    | snd_usb... | [BDE9B00DE4](<Desktop/ASUSTek Computer/ROG/ROG Maximus XII FORMULA/4FFAD531BF76/KUBUNTU-21.10/5.10.86-051086-LOWLATENCY/X86_64/BDE9B00DE4>) |
| 046d:0a38 | Logitech         | Headset H340                         | 56    | snd_usb... | [88876808E9](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/0BCBF54A8A61/ELEMENTARY-6.1/5.13.0-28-GENERIC/X86_64/88876808E9>) |
| 046d:0a5b | Logitech         | G933 Wireless Headset Dongle         | 56    | snd_usb... | [3FF867B4E2](<Desktop/Intel/HURONRIVER/HURONRIVER/E289D90F9598/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/3FF867B4E2>) |
| 046d:0a45 | Logitech         | 960 Headset                          | 52    | snd_usb... | [393686A6C4](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/03C82F773173/DEBIAN-11/5.10.0-11-AMD64/X86_64/393686A6C4>) |
| 0b0e:245e | GN Netcom        | Jabra Link 370                       | 51    | snd_usb... | [DDC210F8D1](<Desktop/Gigabyte Technology/B550M/B550M AORUS ELITE/BF7B9111AD98/UBUNTU-21.10/5.13.0-32-GENERIC/X86_64/DDC210F8D1>) |
| 17ef:306f | Lenovo           | ThinkPad Dock USB Audio              | 51    | snd_usb... | [ABED4A5863](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 2i 20W0000FRT/03B6D51ED61F/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/ABED4A5863>) |
| 03f0:056b | Hewlett-Packard  | USB Audio                            | 49    | snd_usb... | [30565CB2F9](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G7 Notebook PC/F50B1CFDFE6F/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/30565CB2F9>) |
| 041e:324d | Creative Tech... | Sound Blaster Play! 3                | 47    | snd_usb... | [AA5E521C49](<Notebook/Hewlett-Packard/Pavilion/Pavilion ZV6100/2756A8EF2E18/GENTOO-2.7/5.15.23-GENTOO/X86_64/AA5E521C49>) |
| 08bb:2704 | Texas Instrum... | PCM2704 16-bit stereo audio DAC      | 47    | snd_usb... | [F0199DA02B](<Desktop/MouseComputer/B75/B75H2-M2/A652389EE3F2/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/F0199DA02B>) |
| 08bb:2912 | Texas Instrum... | PCM2912A Audio Codec                 | 45    | snd_usb... | [450F779085](<Notebook/Lenovo/ThinkPad/ThinkPad L14 Gen 1 20U6S1JD00/E7077B6DA568/OPENSUSE-20220218/5.16.8-1-DEFAULT/X86_64/450F779085>) |
| 0d8c:0201 | C-Media Elect... | CM6501                               | 44    | snd_usb... | [675F15B6DB](<Desktop/ASUSTek Computer/M2/M2N-SLI/A053E5030FE4/LUBUNTU-21.10/5.13.0-19-GENERIC/X86_64/675F15B6DB>) |
| 1b1c:0a14 | Corsair          | VOID PRO Wireless Gaming Headset     | 42    | snd_usb... | [EA7EABCF23](<Desktop/Gigabyte Technology/B450M/B450M DS3H/84ACADF7AB31/ARCH-ROLLING/5.16.11-ARCH1-2/X86_64/EA7EABCF23>) |
| 0556:0001 | Asahi Kasei M... | AK5370 I/F A/D Converter             | 39    | snd_usb... | [7E772F422E](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LE-USB3/31B1F880861F/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/7E772F422E>) |
| 19f7:0003 | RODE Microphones | RODE NT-USB                          | 39    | snd_usb... | [A63D909E46](<Desktop/ASUSTek Computer/ROG/ROG Maximus XII FORMULA/F37566448B50/GARUDA-SOARING/5.16.8-ZEN1-1-ZEN/X86_64/A63D909E46>) |
| 1038:1294 | SteelSeries ApS  | Arctis Pro Wireless                  | 38    | snd_usb... | [EE8D1E4B48](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/839688C6612C/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/EE8D1E4B48>) |
| 1532:0520 | Razer USA        | Razer Kraken Tournament Edition      | 38    | snd_usb... | [6D5688DB26](<Desktop/MSI/MS-7/MS-7B17/8DF51B50D894/GENTOO-2.6/5.15.23-GENTOO/X86_64/6D5688DB26>) |
| 046d:0a1f | Logitech         | G930                                 | 36    | snd_usb... | [4639D833BB](<Desktop/MSI/MS/MS-7817/9EC590331920/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/4639D833BB>) |
| 0b0e:245d | GN Netcom        | Jabra Link 370                       | 36    | snd_usb... | [47BF582948](<Desktop/Alienware/Aurora/Aurora R8/483FFF231BC9/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/47BF582948>) |
| 0d8c:000e | C-Media Elect... | Audio Adapter (Planet UP-100, Gen... | 36    | snd_usb... | [77691E80A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8F3A96026FD0/RASPBIAN-10/5.10.63-V7L+/ARMV7L/77691E80A4>) |
| 047f:02ee | Plantronics      | BT600                                | 35    | snd_usb... | [989EEC2F5F](<Desktop/MSI/MS-7/MS-7A62/161A2AC8544D/KDE-NEON-20.04/5.13.0-35-GENERIC/X86_64/989EEC2F5F>) |

### Touchpad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 06cb:2970 | Synaptics        | touchpad                             | 82    | usbhid     | [18BC15734F](<Notebook/Acer/Aspire/Aspire E5-551G/6BB43312BFD1/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/18BC15734F>) |
| 044e:1218 | Alps Electric    | Touchpad                             | 24    | usbhid     | [78F2672479](<Tablet/Dell/Latitude/Latitude 7285/35CB641DDB78/CLEAR-LINUX-OS-35940/5.16.11-1128.NATIVE/X86_64/78F2672479>) |
| 044e:120d | Alps Electric    | Touchpad                             | 17    | usbhid     | [13B478195A](<Notebook/Hewlett-Packard/Elite/Elite x2 1012 G1/F896D0AE278D/ELEMENTARY-6.1/5.11.0-43-GENERIC/X86_64/13B478195A>) |
| 06cb:0009 | Synaptics        | Composite TouchPad and TrackPoint    | 11    | synapti... | [591BEDF88F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/41DD4743631C/UBUNTU-21.04/5.11.0-1027-RASPI/AARCH64/591BEDF88F>) |
| 044e:1216 | Alps Electric    | Touchpad                             | 8     | usbhid     | [BEEB081772](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/945D2246773B/UBUNTU-MATE-20.04/5.13.0-30-GENERIC/X86_64/BEEB081772>) |
| 044e:120f | Alps Electric    | Touchpad                             | 7     | usbhid     | [BF808D506C](<Notebook/Dell/Latitude/Latitude 7275/0100DBA1C24D/ZORIN-16/5.11.0-40-GENERIC/X86_64/BF808D506C>) |
| 17ef:6046 | Lenovo           | Wireless Touchpad K5923              | 7     | usbhid     | [56EBB4B643](<Desktop/ASRock/B450/B450 Pro4/B6B9FADE9135/DEBIAN-11/5.10.0-10-AMD64/X86_64/56EBB4B643>) |
| 044e:1217 | Alps Electric    | Touchpad                             | 6     | usbhid     | [5A85AB6B0F](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/608A6BF05466/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/5A85AB6B0F>) |
| 044e:1210 | Alps Electric    | Touchpad                             | 4     | usbhid     | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 06cb:5710 | Synaptics        | SynapticsTouch Pad V 1.03U3          | 4     | usbhid     | [5834B6321D](<Notebook/Hewlett-Packard/Split/Split 13 x2 PC/CB63276D4C2A/DEBIAN-11/5.10.0-6-AMD64/X86_64/5834B6321D>) |
| 06cb:7af9 | Synaptics        | HIDUSB TouchPad V07                  | 4     | usbhid     | [5A65F95AC7](<Notebook/Hewlett-Packard/Spectre/Spectre x2 Detachable/4A7FC502BC99/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/5A65F95AC7>) |
| 0488:0280 | Cirque           | 9925 AG Touchpad                     | 3     | usbhid     | [66C97ED64B](<Desktop/Hewlett-Packard/Compaq/Compaq dc7700 Convertible Minitower/3D37C853BE6C/UBUNTU-20.04/5.4.0-81-GENERIC/X86_64/66C97ED64B>) |
| 04b4:fef3 | Cypress Semic... | KingSon TouchPad                     | 3     | usbhid     | [0B79772DFA](<Desktop/Hewlett-Packard/KT541AA-UUB/KT541AA-UUB a6528hk/E860C4C6D9E4/LUBUNTU-18.04/4.15.0-147-GENERIC/X86_64/0B79772DFA>) |
| 06cb:5711 | Synaptics        | Touch Pad V 103u9                    | 3     | usbhid     | [ED95E4C1C7](<Notebook/Hewlett-Packard/Spectre/Spectre 13 x2 PC/A094F6311BEA/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/ED95E4C1C7>) |
| 044e:1221 | Alps Electric    | Touchpad                             | 2     | usbhid     | [6EE77ED959](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/3DD573867AA0/UBUNTU-20.04/5.8.0-36-GENERIC/X86_64/6EE77ED959>) |
| 0488:8010 | Cirque           | 9925 AG Touchpad                     | 1     | usbhid     | [1498A5A5A4](<Desktop/System76/Thelio/Thelio/28033514E7BA/POP!_OS-20.04/5.4.0-7642-GENERIC/X86_64/1498A5A5A4>) |
| 062a:19b5 | MosArt Semico... | TouchPad                             | 1     | usbhid     | [61BB547684](<Desktop/ASUSTek Computer/B150/B150M-A/0034453C1345/UBUNTU-18.04/4.18.0-17-GENERIC/X86_64/61BB547684>) |
| 06cb:0001 | Synaptics        | TouchPad                             | 1     | synapti... | [7023DC94DA](<Notebook/Packard Bell/EasyNote/EasyNote ME69BMP/C61580A9F1CA/UBUNTU-MATE-20.04/5.4.0-31-GENERIC/X86_64/7023DC94DA>) |
| 06cb:0096 | Synaptics        | HIDUSB TouchPad V01                  | 1     | usbhid     | [1E10940254](<Tablet/Acer/Switch/Switch SW512-52/FD2520C6F2A4/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/1E10940254>) |
| 06cb:7d29 | Synaptics        | HIDUSB TouchPad V03                  | 1     | usbhid     | [49A6D8DEC1](<Notebook/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/EFCCF32E3904/MANJARO-21.0.5/5.10.36-2-MANJARO/X86_64/49A6D8DEC1>) |
| 258a:0010 | Hailuck          | PTP TouchPad                         | 1     | usbhid     | [C8932DBFD0](<Desktop/Gigabyte Technology/X570/X570 AORUS ULTRA/A25B28905CE4/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/C8932DBFD0>) |
| 413c:2507 | Dell             | TP713 Wireless Touchpad              | 1     | usbhid     | [8A10AE7D58](<Desktop/ASUSTek Computer/M3N78/M3N78 PRO/CF3804C072FE/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/8A10AE7D58>) |

### Touchscreen (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 04f3:20d0 | Elan Microele... | Touchscreen                          | 60    | usbhid     | [CE5FD5227F](<Notebook/Dell/XPS/XPS 13 9350/7D9567596332/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/CE5FD5227F>) |
| 0eef:0001 | D-WAV Scientific | Titan6001 Surface Acoustic Wave T... | 57    | usbhid     | [8C13511A03](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/32685E135116/DEBIAN-11/5.10.92-V8+/AARCH64/8C13511A03>) |
| 04f3:2494 | Elan Microele... | Touchscreen                          | 42    | usbhid     | [8D019441D1](<Notebook/Dell/Inspiron/Inspiron 13-5378/C3F7123D8735/ZORIN-16/5.11.0-43-GENERIC/X86_64/8D019441D1>) |
| 04f3:250e | Elan Microele... | Touchscreen                          | 42    | usbhid     | [6765F9623B](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/371B96DEA22E/DEBIAN-11/5.10.0-11-AMD64/X86_64/6765F9623B>) |
| 0408:3008 | Quanta           | OpticalTouchScreen                   | 35    | usbhid     | [B20D7593CE](<All In One/ASUSTek Computer/ET2013/ET2013I/837E538FD9B7/ZORIN-16/5.13.0-30-GENERIC/X86_64/B20D7593CE>) |
| 04f3:2234 | Elan Microele... | Touchscreen                          | 25    | usbhid     | [0370593223](<Notebook/Dell/XPS/XPS 13 9360/FA69684711C5/ARCH/5.16.1-ARCH1-1/X86_64/0370593223>) |
| 04f3:24a0 | Elan Microele... | Touchscreen                          | 25    | usbhid     | [2A3B959F49](<Notebook/Dell/XPS/XPS 15 9560/F6FCA5ABEA41/DEBIAN-11/5.15.17-XANMOD2-TT/X86_64/2A3B959F49>) |
| 04f3:21d5 | Elan Microele... | Touchscreen                          | 24    | usbhid     | [F4A068F57C](<Notebook/Dell/XPS/XPS 15 9550/A808E86B953A/OPENSUSE-20220226/5.16.11-1-DEFAULT/X86_64/F4A068F57C>) |
| 04f3:016f | Elan Microele... | Touchscreen                          | 23    | usbhid     | [DDA75E3BA9](<Notebook/Lenovo/Yoga/Yoga 2 Pro 20266/26A04B698FE7/ZORIN-16/5.11.0-38-GENERIC/X86_64/DDA75E3BA9>) |
| 04f3:0254 | Elan Microele... | Touchscreen                          | 23    | usbhid     | [14748BA63B](<Notebook/Lenovo/ThinkPad/ThinkPad S1 Yoga 20CD0035GE/453290E4E122/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/14748BA63B>) |
| 04f3:24a1 | Elan Microele... | Touchscreen                          | 23    | usbhid     | [CD1A178797](<Notebook/Dell/Precision/Precision 5520/39459C2F4995/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/CD1A178797>) |
| 04f3:012d | Elan Microele... | Touchscreen                          | 22    | usbhid     | [5CD5DD7086](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 3rd 20BTS11W00/216D2E46205E/XUBUNTU-21.04/5.11.0-25-GENERIC/X86_64/5CD5DD7086>) |
| 04f3:2acc | Elan Microele... | Touchscreen                          | 20    | usbhid     | [10C9991F0B](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y10004CK/DA3873D84740/DEBIAN-11/5.10.0-8-AMD64/X86_64/10C9991F0B>) |
| 04f3:2013 | Elan Microele... | Touchscreen                          | 19    | usbhid     | [862A31FA80](<Notebook/Dell/Inspiron/Inspiron 5548/B32A4E77F99D/MANJARO/5.15.21-1-MANJARO/X86_64/862A31FA80>) |
| 04f3:000a | Elan Microele... | Touchscreen                          | 18    | usbhid     | [347317645D](<Notebook/Lenovo/IdeaPad/IdeaPad Yoga 13 20175/57CB55619157/XUBUNTU-21.10/5.13.0-25-GENERIC/X86_64/347317645D>) |
| 1926:0003 | NextWindow       | 1900 HID Touchscreen                 | 18    | usbhid     | [FACEC46BD5](<Desktop/Hewlett-Packard/KQ437AA-ABA/KQ437AA-ABA IQ506/5EDC880F51E4/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/FACEC46BD5>) |
| 1926:0006 | NextWindow       | 1950 HID Touchscreen                 | 18    | usbhid     | [EA6A720EBF](<Desktop/Hewlett-Packard/VS257AA-ACB/VS257AA-ACB 600-1040ru/B4A91857B704/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/EA6A720EBF>) |
| 04f3:010c | Elan Microele... | Touchscreen                          | 17    | usbhid     | [BF2F9B2C1D](<Notebook/ASUSTek Computer/Q501/Q501LA/E3FF080C61AE/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/BF2F9B2C1D>) |
| 04f3:289b | Elan Microele... | Touchscreen                          | 17    | usbhid     | [D8002E9EAE](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NJ0004US/8D43652EF1E4/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/D8002E9EAE>) |
| 04f3:0042 | Elan Microele... | Touchscreen                          | 15    | usbhid     | [72D6263861](<Notebook/Dell/Inspiron/Inspiron 5537/1C3EEF77A4AB/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/72D6263861>) |
| 04f3:0085 | Elan Microele... | Touchscreen                          | 15    | usbhid     | [B821AEBA3B](<Notebook/Acer/Aspire/Aspire M5-583P/EBD19CDDB07D/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/B821AEBA3B>) |
| 04f3:0224 | Elan Microele... | Touchscreen                          | 15    | usbhid     | [AB6C683160](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS0LU00/26A02EFA467D/ENDEAVOUROS-ROLLING/5.10.68-1-LTS/X86_64/AB6C683160>) |
| 04f3:034e | Elan Microele... | Touchscreen                          | 14    | usbhid     | [EFD2DC8D13](<Notebook/Dell/Inspiron/Inspiron 3541/EFA5976E2DE2/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/EFD2DC8D13>) |
| 04f3:2398 | Elan Microele... | Touchscreen                          | 14    | usbhid     | [1DF9DBEFA1](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0FH00/63A3D35F3615/ARCH/5.16.2-ARCH1-1/X86_64/1DF9DBEFA1>) |
| 04f3:2012 | Elan Microele... | Touchscreen                          | 13    | usbhid     | [AC9CA4D83B](<Notebook/Dell/Inspiron/Inspiron 3541/AEC22D0C049A/KDE-NEON-20.04/5.13.0-28-GENERIC/X86_64/AC9CA4D83B>) |
| 04f3:2337 | Elan Microele... | Touchscreen                          | 13    | usbhid     | [67552D79AC](<Notebook/Dell/Inspiron/Inspiron 11-3168/1907869CF06E/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/67552D79AC>) |
| 04f3:0034 | Elan Microele... | Touchscreen                          | 12    | usbhid     | [F4878864EC](<Notebook/Dell/Inspiron/Inspiron 5537/E37D8F64A166/POP!_OS-21.10/5.15.8-76051508-GENERIC/X86_64/F4878864EC>) |
| 04f3:036e | Elan Microele... | Touchscreen                          | 12    | usbhid     | [6B1A282C17](<Notebook/Dell/Inspiron/Inspiron 11 - 3147/CACF61202444/UBUNTU-22.04/5.13.0-19-GENERIC/X86_64/6B1A282C17>) |
| 04f3:24e1 | Elan Microele... | Touchscreen                          | 12    | usbhid     | [4F3C001854](<Notebook/Dell/Inspiron/Inspiron 13-7378/B4B1820D73E5/LINUXMINT-20.3/5.13.0-30-GENERIC/X86_64/4F3C001854>) |
| 04f3:002a | Elan Microele... | Touchscreen                          | 11    | usbhid     | [2BF059F608](<Notebook/Dell/Inspiron/Inspiron 5421/E6409E5E959F/LINUXMINT-20.2/5.4.0-74-GENERIC/X86_64/2BF059F608>) |
| 04f3:22c3 | Elan Microele... | Touchscreen                          | 11    | usbhid     | [CAA12C2897](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/6AAE06B7F290/UBUNTU-20.04/5.11.0-44-GENERIC/X86_64/CAA12C2897>) |
| 04f3:2753 | Elan Microele... | Touchscreen                          | 11    | usbhid     | [728E0FACD6](<Notebook/Hewlett-Packard/Laptop/Laptop 15-dy1xxx/0FB817714484/ZORIN-16/5.11.0-34-GENERIC/X86_64/728E0FACD6>) |
| 04f3:0023 | Elan Microele... | Touchscreen                          | 10    | usbhid     | [19C732CD05](<Notebook/Acer/Aspire/Aspire V5-571PG/724E8D6FDBAF/ZORIN-16/5.13.0-27-GENERIC/X86_64/19C732CD05>) |
| 04f3:0303 | Elan Microele... | Touchscreen                          | 10    | usbhid     | [F73F06A58D](<Notebook/Lenovo/Yoga/Yoga 2 13 20344/88F8D4DFD573/LINUXMINT-20.1/5.4.0-96-GENERIC/X86_64/F73F06A58D>) |
| 04f3:0389 | Elan Microele... | Touchscreen                          | 10    | usbhid     | [9E290336C1](<Notebook/Acer/Aspire/Aspire E5-571P/920F7DBDB677/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/9E290336C1>) |
| 04f3:2033 | Elan Microele... | Touchscreen                          | 10    | usbhid     | [0565061605](<Notebook/Dell/Inspiron/Inspiron 7348/32CDF3DE371B/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/0565061605>) |
| 04f3:2070 | Elan Microele... | Touchscreen                          | 10    | usbhid     | [9E9FDBFBA5](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible/C1E81F24FE6E/ZORIN-16/5.13.0-30-GENERIC/X86_64/9E9FDBFBA5>) |
| 04f3:2672 | Elan Microele... | Touchscreen                          | 10    | usbhid     | [A4D5174826](<Convertible/ASUSTek Computer/TP410/TP410UAR/D5DB7D73940D/FEDORA-35/5.14.15-300.FC35.X86_64/X86_64/A4D5174826>) |
| 04f3:2793 | Elan Microele... | Touchscreen                          | 10    | usbhid     | [1605FCCC92](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ca0xxx/68E88BAD4188/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/1605FCCC92>) |
| 1926:0bce | NextWindow       | Touchscreen                          | 10    | usbhid     | [0451CAEB29](<All In One/Sony/VPCL212/VPCL212FX/01EE677E7F92/UBUNTU-21.10/5.13.0-22-GENERIC/X86_64/0451CAEB29>) |
| 04e7:0020 | Elo TouchSystems | Touchscreen Interface (2700)         | 9     | usbhid     | [7A38C478BB](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/48D182201BAD/CENTOS-8/4.18.0-240.15.1.EL8_3.X86_64/X86_64/7A38C478BB>) |
| 04f3:0135 | Elan Microele... | Touchscreen                          | 9     | usbhid     | [5B3EC8682E](<Notebook/Lenovo/ThinkPad/ThinkPad T440 20B7S02A00/D6BFB136E4C6/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/5B3EC8682E>) |
| 04f3:0206 | Elan Microele... | Touchscreen                          | 9     | usbhid     | [1493A2EAE1](<Notebook/Dell/Inspiron/Inspiron 7537/3070FEA40F8A/UBUNTU-20.04/5.11.0-34-GENERIC/X86_64/1493A2EAE1>) |
| 04f3:0301 | Elan Microele... | Touchscreen                          | 9     | usbhid     | [A4DFBB6E38](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AMA34HMN/77E2C92377D2/VOID-ROLLING/5.15.6_1/X86_64/A4DFBB6E38>) |
| 04f3:034f | Elan Microele... | Touchscreen                          | 9     | usbhid     | [45ABB29457](<Notebook/Dell/Inspiron/Inspiron 5547/8B1D61AE8AE5/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/45ABB29457>) |
| 04f3:0439 | Elan Microele... | Touchscreen                          | 9     | usbhid     | [99645415A4](<Notebook/Hewlett-Packard/Pavilion/Pavilion 15/4B8DCF546265/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/99645415A4>) |
| 04f3:2083 | Elan Microele... | Touchscreen                          | 9     | usbhid     | [70496150EB](<Notebook/Lenovo/Yoga/Yoga 500-14IBD 80N4/51B76D3D2D50/UBUNTU-20.04/5.4.0-77-GENERIC/X86_64/70496150EB>) |
| 04f3:2089 | Elan Microele... | Touchscreen                          | 9     | usbhid     | [33A40B952E](<Notebook/Lenovo/Yoga/Yoga 500-15IBD 80N6/6D737B48C800/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/33A40B952E>) |
| 04f3:24dd | Elan Microele... | Touchscreen                          | 9     | usbhid     | [A46A3A7F8D](<Notebook/Dell/Inspiron/Inspiron 15-3567/F10DA511EC6D/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/A46A3A7F8D>) |
| 1926:0dbe | NextWindow       | Touchscreen                          | 9     | usbhid     | [8D0B8E2E12](<Desktop/Hewlett-Packard/520/520-1108el/64D1E7CD288A/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/8D0B8E2E12>) |

### Tv card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:0892 | Logitech         | C920 HD Pro Webcam                   | 228   | gspca_v... | [B179A5048F](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/52B170598D86/ARCH/5.16.13-ARCH1-1/X86_64/B179A5048F>) |
| 1415:2000 | Nam Tai E&E P... | Sony Playstation Eye                 | 100   | gspca_o... | [332A3F936B](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX R2.0/0F893912ED0D/DEBIAN-11/5.10.0-10-AMD64/X86_64/332A3F936B>) |
| 0402:5602 | ALi              | M5602 Video Camera Controller        | 90    | gspca_m... | [930E8F9B6A](<Notebook/Itautec/Infoway/Infoway/F7E9E297B279/LINUXMINT-20.3/5.4.0-97-GENERIC/X86_64/930E8F9B6A>) |
| 045e:00f7 | Microsoft        | LifeCam VX-1000                      | 58    | gspca_s... | [86257153D8](<Desktop/ASUSTek Computer/All/All Series/7A15C2DC2E2A/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/86257153D8>) |
| 046d:08d7 | Logitech         | QuickCam Communicate STX             | 58    | gspca_z... | [7519D0FDED](<Desktop/Acer/Aspire/Aspire M5811/BD71CFB0AF65/UBUNTU-21.10/5.13.0-32-GENERIC/X86_64/7519D0FDED>) |
| 0ac8:303b | Z-Star Microe... | ZC0303 Webcam                        | 52    | gspca_z... | [F6174EBD67](<Desktop/Lenovo/IdeaCentre/IdeaCentre G5 14IMB05 90N900FKTX/A68FF73BCA5E/KALI-2022.1/5.15.0-KALI3-AMD64/X86_64/F6174EBD67>) |
| 093a:2620 | Pixart Imaging   | TV Card                              | 49    | gspca_p... | [B1E0EE94BA](<Notebook/Acer/Extensa/Extensa 2510/10FF52A0E74F/UBUNTU-20.04/5.11.0-40-GENERIC/X86_64/B1E0EE94BA>) |
| 046d:0896 | Logitech         | OrbiCam                              | 41    | gspca_v... | [4B2259F040](<Notebook/Acer/Aspire/Aspire 5600/7C28F487841A/LINUX-LITE-3.8/4.15.0-169-GENERIC/I686/4B2259F040>) |
| 045e:00f5 | Microsoft        | LifeCam VX-3000                      | 35    | gspca_s... | [C01D88CC5F](<Desktop/ASUSTek Computer/All/All Series/ABD13DFCD54D/UBUNTU-20.10/5.8.0-63-GENERIC/X86_64/C01D88CC5F>) |
| 046d:08da | Logitech         | QuickCam Messanger                   | 33    | gspca_z... | [5F95F68DF7](<Desktop/Medion/MS/MS-7204/28B2189543C8/LINUXMINT-20.2/5.4.0-99-GENERIC/X86_64/5F95F68DF7>) |
| 05e1:0501 | Syntek           | DC-1125 Webcam                       | 30    | stkwebcam  | [ACDFE6952B](<Notebook/ASUSTek Computer/F5/F5VL/C5BC99C143A5/LINUXMINT-20.3/5.4.0-99-GENERIC/X86_64/ACDFE6952B>) |
| 0ac8:305b | Z-Star Microe... | ZC0305 Webcam                        | 28    | gspca_z... | [BA5FE21088](<Desktop/Dell/Inspiron/Inspiron 3847/F9D6680BF3CB/UBUNTU-20.04/5.11.0-38-GENERIC/X86_64/BA5FE21088>) |
| 093a:2468 | Pixart Imaging   | SoC PC-Camera                        | 25    | gspca_p... | [601F46E5A4](<Desktop/ASRock/N68-VGS3/N68-VGS3 FX/27A9688D8F34/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/601F46E5A4>) |
| 093a:2622 | Pixart Imaging   | Webcam Genius                        | 25    | gspca_p... | [99514A7DD5](<Desktop/Gigabyte Technology/970/970A-DS3P/42CCC2FE8DC9/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/99514A7DD5>) |
| 174f:a311 | Syntek           | 1.3MPixel Web Cam - Asus A3A, A6J... | 25    | stkwebcam  | [787DFA2208](<Notebook/ASUSTek Computer/A7/A7K/E81F04A95852/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/787DFA2208>) |
| 046d:089d | Logitech         | QuickCam E2500 series                | 24    | gspca_z... | [57601D98F3](<Desktop/Hewlett-Packard/G5320/G5320fr/762064A5FC05/UBUNTU-MATE-18.04/5.4.0-81-GENERIC/X86_64/57601D98F3>) |
| 046d:08d9 | Logitech         | QuickCam IM/Connect                  | 24    | gspca_z... | [001EEC2B02](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX/7B03EE1E2206/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/001EEC2B02>) |
| 093a:262c | Pixart Imaging   | TV Card                              | 23    | gspca_p... | [85A293BC45](<Desktop/ASRock/H55/H55M/9B81BCB756D3/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/85A293BC45>) |
| 0c45:624f | Microdia         | PC Camera (SN9C201 + OV9650)         | 19    | gspca_s... | [A3A3EA2BD9](<Notebook/Lenovo/Others/Others/B6894CAF0867/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/A3A3EA2BD9>) |
| 046d:08ad | Logitech         | QuickCam Communicate STX             | 18    | gspca_z... | [566B587DD9](<Desktop/Gigabyte Technology/GA-MA78/GA-MA78LMT-S2/5672BB6E8A92/UBUNTU-20.04/5.4.0-88-GENERIC/X86_64/566B587DD9>) |
| 046d:08af | Logitech         | QuickCam Easy/Cool                   | 16    | gspca_z... | [9E10AD29C3](<Desktop/Gigabyte Technology/H61/H61M-S2PV/0E57E097034D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/9E10AD29C3>) |
| 0ac8:307b | Z-Star Microe... | USB 1.1 Webcam                       | 15    | gspca_z... | [CA561D8BDA](<Desktop/Medion/MS/MS-7728/E5C276717E32/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/CA561D8BDA>) |
| 093a:2624 | Pixart Imaging   | Webcam                               | 13    | gspca_p... | [673D4FAA98](<Desktop/Biostar/G41/G41D3/C7281F7CFAE8/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/673D4FAA98>) |
| 0ac8:301b | Z-Star Microe... | ZC0301 Webcam                        | 12    | gspca_z... | [220050FFF2](<Notebook/Datto/1000/1000/E6ABCDC5C677/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/220050FFF2>) |
| 2040:7200 | Hauppauge        | WinTV HVR-950                        | 12    | au0828     | [FE850F1CA6](<Desktop/ASRock/X470/X470 Gaming K4/48617AE14438/KDE-NEON-20.04/5.4.0-73-GENERIC/X86_64/FE850F1CA6>) |
| 041e:4052 | Creative Tech... | Live! Cam Vista IM                   | 11    | gspca_o... | [781A92F9A4](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10DR000TUK/01F82514F195/UBUNTU-20.04/5.16.0-051600-GENERIC/X86_64/781A92F9A4>) |
| 046d:08a2 | Logitech         | Labtec Webcam Pro                    | 11    | gspca_z... | [9A2C223F55](<Desktop/ASUSTek Computer/P5N-E/P5N-E SLI/991E37D43F88/UBUNTU-18.04/5.4.0-100-GENERIC/X86_64/9A2C223F55>) |
| 093a:2460 | Pixart Imaging   | Q-TEC WEBCAM 100                     | 11    | gspca_p... | [C7C1D06954](<Notebook/Hewlett-Packard/Compaq/Compaq Presario CQ61/40C22A9786B9/ZORIN-15/5.4.0-81-GENERIC/I686/C7C1D06954>) |
| 093a:2621 | Pixart Imaging   | PAC731x Trust Webcam                 | 11    | gspca_p... | [3E710C5B09](<Notebook/Acer/Aspire/Aspire 5310/C08CA1553E2D/UBUNTU-20.10/5.8.0-50-GENERIC/X86_64/3E710C5B09>) |
| 045e:00f4 | Microsoft        | LifeCam VX-6000 (SN9C20x + OV9650)   | 10    | gspca_s... | [535D0016E2](<Notebook/MSI/CX/CX700/403068992425/DEBIAN-11/5.10.0-IO7-AMD64/X86_64/535D0016E2>) |
| 046d:08f0 | Logitech         | QuickCam Messenger                   | 10    | gspca_s... | [485C5E0968](<Notebook/Dell/XPS/XPS 13 9350/D76A916AD957/FEDORA-35/5.15.14-200.FC35.X86_64/X86_64/485C5E0968>) |
| 093a:2476 | Pixart Imaging   | CIF Single Chip                      | 10    | gspca_p... | [719CE542C2](<Desktop/Gigabyte Technology/EP45/EP45-DS3L/0C2039765929/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/719CE542C2>) |
| 0ac8:c002 | Z-Star Microe... | Visual Communication Camera VGP-VCC1 | 10    | gspca_v... | [A7185CC26A](<Notebook/Sony/VGN-FE31/VGN-FE31H/A2CE0403D433/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/A7185CC26A>) |
| 046d:092f | Logitech         | QuickCam Express Plus                | 9     | gspca_s... | [83DFC4B9D8](<Desktop/Hewlett-Packard/Z840/Z840 Workstation/13EF905FCB11/OPENSUSE-LEAP-15.2/5.3.18-LP152.72-PREEMPT/X86_64/83DFC4B9D8>) |
| 0471:0329 | Philips (or NXP) | SPC 900NC PC Camera / ORITE CCD W... | 9     | pwc        | [20E8F6655F](<Desktop/Gigabyte Technology/GA-990/GA-990FXA-UD3/BA519038235F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/20E8F6655F>) |
| 093a:2626 | Pixart Imaging   | TV Card                              | 9     | gspca_p... | [C77F120F57](<Desktop/ABIT/AN/AN52/D7DD731F9CD7/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/C77F120F57>) |
| 0c45:608f | Microdia         | PC Camera (SN9C103 + OV7630)         | 9     | gspca_s... | [8EE329F5CF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/5A8A27AF2677/LINUXMINT-19.1/4.15.0-147-GENERIC/X86_64/8EE329F5CF>) |
| 0c45:6270 | Microdia         | PC Camera (SN9C201 + MI0360/MT9V0... | 9     | gspca_s... | [69B7C755DC](<Desktop/Gigabyte Technology/A320/A320M-S2H/76B725B9BC0A/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/69B7C755DC>) |
| 046d:092e | Logitech         | QuickCam Chat                        | 8     | gspca_s... | [EBEAF681E3](<Desktop/ASUSTek Computer/H110/H110I-PLUS/E28E044EE501/ELEMENTARY-6.1/5.13.0-27-GENERIC/X86_64/EBEAF681E3>) |
| 093a:2600 | Pixart Imaging   | Typhoon Easycam USB 330K (newer)/... | 8     | gspca_p... | [D12F767E54](<Desktop/ASUSTek Computer/P5/P5KC/9B149D7D8269/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/D12F767E54>) |
| 0c45:6007 | Microdia         | VideoCAM Eye                         | 8     | gspca_s... | [AB5CE36275](<Notebook/Dell/Latitude/Latitude E5400/BDE40F600FE3/ARCO-ROLLING/5.4.181-1-LTS54/X86_64/AB5CE36275>) |
| 0c45:600d | Microdia         | TwinkleCam USB camera                | 8     | gspca_s... | [F1F20CD28D](<Desktop/ASUSTek Computer/All/All Series/A669958941F5/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/F1F20CD28D>) |
| 2304:021a | Pinnacle Systems | Dazzle DVC100 Audio Device           | 8     | em28xx     | [DB19440955](<Desktop/Dell/Precision/Precision Tower 5810/7287A3F24CE1/KUBUNTU-21.10/5.13.0-22-GENERIC/X86_64/DB19440955>) |
| 041e:405f | Creative Tech... | WebCam Vista (VF0330)                | 7     | gspca_o... | [11FED8F8AE](<Desktop/ASUSTek Computer/P5/P5K/47D3885B4031/LUBUNTU-21.04/5.11.0-22-GENERIC/X86_64/11FED8F8AE>) |
| 041e:4064 | Creative Tech... | VF0420 Live! Cam Vista IM            | 7     | gspca_o... | [EF8DFE0673](<Desktop/Gigabyte Technology/H81/H81M-S2V/A7A5C481217E/LINUXMINT-20.2/5.4.0-88-GENERIC/X86_64/EF8DFE0673>) |
| 0733:0401 | ViewQuest Tec... | CS330 Webcam                         | 7     | gspca_s... | [C4345F14AD](<Desktop/Lenovo/ThinkCentre/ThinkCentre M73 10AXS0HN00/4DC849B20856/LUBUNTU-20.04/5.13.0-1008-INTEL/X86_64/C4345F14AD>) |
| 093a:2472 | Pixart Imaging   | CIF Single Chip                      | 7     | gspca_p... | [0DC7C8F9DC](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/ACB2F5C6E1DA/XUBUNTU-18.04/5.4.0-66-GENERIC/X86_64/0DC7C8F9DC>) |
| 0c45:6242 | Microdia         | PC Camera (SN9C201 + MI1310)         | 7     | gspca_s... | [18019F6606](<Desktop/MSI/MS/MS-7721/D3A9AC043F59/UBUNTU-20.04/5.11.0-37-GENERIC/X86_64/18019F6606>) |
| eb1a:2861 | eMPIA Technology | EasyCAP DC60+ [EM2861]               | 7     | em28xx     | [F1FA3D65B1](<Notebook/Hewlett-Packard/ProBook/ProBook 640 G4/5500E687A6B8/KUBUNTU-20.10/5.8.0-63-GENERIC/X86_64/F1FA3D65B1>) |
| 046d:0870 | Logitech         | QuickCam Express                     | 6     | gspca_s... | [6F5AF5DA5C](<Notebook/Dell/Latitude/Latitude E5420m/7A8038E8535B/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/6F5AF5DA5C>) |

### Ups (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 051d:0002 | American Powe... | Uninterruptible Power Supply         | 546   | usbhid     | [1232B6173B](<Desktop/ASUSTek Computer/P5/P5K/9124D33B7BE2/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/1232B6173B>) |
| 0764:0501 | Cyber Power S... | CP1500 AVR UPS                       | 218   | usbhid     | [228E9E9D0C](<Desktop/MSI/MS-7/MS-7D25/F124B8D7CBBC/FEDORA-35/5.16.9-200.FC35.X86_64/X86_64/228E9E9D0C>) |
| 0463:ffff | MGE UPS Systems  | UPS                                  | 54    | usbhid     | [66F88A032F](<Desktop/Dell/Precision/Precision T5600/5F2EC5F04A2D/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/66F88A032F>) |
| 0764:0601 | Cyber Power S... | PR1500LCDRT2U UPS                    | 31    | usbhid     | [F953EC8B63](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/573835E1B1A8/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/F953EC8B63>) |
| 0d9f:0004 | Powercom         | HID UPS Battery                      | 27    | usbhid     | [77BB019FE0](<System On Chip/Bananapi/BPI-M/BPI-M5/91E0E094EEA8/DEBIAN-10/4.9.236-BPI-M5-KERNEL/AARCH64/77BB019FE0>) |
| 051d:0003 | American Powe... | UPS                                  | 26    | usbhid     | [38C79D4929](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/0BB8D8851537/UBUNTU-20.04/5.4.0-100-GENERIC/X86_64/38C79D4929>) |
| 06da:ffff | Phoenixtec Power | Offline UPS                          | 14    | usbhid     | [B80A8FBD1B](<Desktop/MSI/MS-7/MS-7C84/E25B3F144FF9/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B80A8FBD1B>) |
| 0925:1234 | Lakeview Rese... | UPS USB MON V1.4                     | 11    | usbhid     | [D64F06FD5A](<Desktop/Gigabyte Technology/B460/B460MD3H/7746545E9850/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/D64F06FD5A>) |
| 06da:0003 | Phoenixtec Power | 1300VA UPS                           | 9     | usbhid     | [2900821ED3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/EC0057AF3E82/GENTOO-2.8/5.15.2-GENTOO-X86_64/X86_64/2900821ED3>) |
| 09ae:3016 | Tripp Lite       | UPS                                  | 6     | usbhid     | [4B935D705C](<Desktop/MSI/MS/MS-7917/F870CB9B4473/ROCKY-8.5/4.18.0-348.7.1.EL8_5.X86_64/X86_64/4B935D705C>) |
| 0d9f:00a2 | Powercom         | Imperial Uninterruptible Power Su... | 6     | usbhid     | [2846E3D112](<Desktop/MSI/MS/MS-7918/2757DAE7BC70/ANTERGOS-ROLLING/5.12.10-ZEN1-1-ZEN/X86_64/2846E3D112>) |
| 0d9f:00a6 | Powercom         | Black Knight PRO Uninterruptible ... | 5     | usbhid     | [282ECB40CA](<Desktop/MSI/MS/MS-7816/C8523EA1567E/UBUNTU-21.04/5.11.0-25-GENERIC/X86_64/282ECB40CA>) |
| 0592:0002 | Powerware        | UPS (X-Slot)                         | 4     | usbfs      | [CEEFDD4EAC](<Desktop/Gigabyte Technology/H81/H81M-S2H/A21250E92AE8/MAGEIA-8/5.15.6-DESKTOP-2.MGA8/X86_64/CEEFDD4EAC>) |
| 0d9f:00a3 | Powercom         | Smart King PRO Uninterruptible Po... | 4     | usbhid     | [89CC93BB0F](<Server/Supermicro/Super/Super Server/1751A0B4EDAF/DEBIAN-9/4.15.18-15-PVE/X86_64/89CC93BB0F>) |
| 0d9f:00a4 | Powercom         | WOW Uninterruptible Power Supply ... | 3     | usbhid     | [0C982DF6CC](<Desktop/MSI/MS-7/MS-7C37/73B8B020B62C/KDE-NEON-20.04/5.4.0-64-GENERIC/X86_64/0C982DF6CC>) |
| 05dd:a011 | Delta Electro... | MINUTEMAN UPS                        | 2     | usbhid     | [1BAE5B1DC6](<Desktop/ASUSTek Computer/Z170/Z170 PRO GAMING/35E5770AE57B/UBUNTU-19.10/5.3.0-21-GENERIC/X86_64/1BAE5B1DC6>) |
| 09ae:2012 | Tripp Lite       | UPS                                  | 2     | usbhid     | [8D6C4235C3](<Desktop/ASUSTek Computer/P8/P8Z68-V/11E74299D197/UBUNTU-18.04/4.15.0-66-GENERIC/X86_64/8D6C4235C3>) |
| 09ae:4004 | Tripp Lite       | UPS                                  | 2     | usbfs      | [8D400B49F8](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/SLACKWARE-15.0/5.15.19/X86_64/8D400B49F8>) |
| 03f0:1fe2 | Hewlett-Packard  | T1000 G3 UPS                         | 1     | usbhid     | [19AE174CC7](<Desktop/ECS/Z77/Z77H2-A4/4A995FDCC7F9/UBUNTU-18.04/4.18.0-25-GENERIC/X86_64/19AE174CC7>) |
| 0403:e520 | Future Techno... | ECO Pro Series UPS                   | 1     | ftdi_sio   | [E599511F33](<Desktop/MSI/MS-7/MS-7B79/0E28B9FF4F84/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/E599511F33>) |
| 050d:0751 | Belkin Compon... | Belkin UPS                           | 1     | usbhid     | [E4FDAFF878](<Desktop/ASUSTek Computer/M2/M2A-VM/81D7E88C664A/UBUNTU-21.04/5.11.0-18-GENERIC/X86_64/E4FDAFF878>) |
| 06da:0002 | Phoenixtec Power | UPS                                  | 1     |            | [4F5E89A87E](<Desktop/Gigabyte Technology/Z77/Z77X-D3H/B6558AB4A76F/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/4F5E89A87E>) |
| 09ae:2010 | Tripp Lite       | UPS                                  | 1     | usbhid     | [5D1A48EE4E](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/920162AF2BF5/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/5D1A48EE4E>) |
| 10af:0001 | Liebert          | PowerSure PSA UPS                    | 1     | usbhid     | [C7B9018598](<Desktop/Dell/OptiPlex/OptiPlex 790/7428F849CCCB/UBUNTU-18.04/5.4.0-74-GENERIC/X86_64/C7B9018598>) |

### Video (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 048d:9006 | Integrated Te... | IT9135 BDA Afatech DVB-T HDTV Dongle | 13    | dvb_usb... | [23251C9E05](<Notebook/Lenovo/IdeaPad/IdeaPad 100-15IBY 80MJ/308E88555DE0/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/23251C9E05>) |
| 0fd9:0066 | Elgato Systems   | Cam Link 4K                          | 12    | snd_usb... | [9C45F031B3](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/FB7F7DAF2C33/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/9C45F031B3>) |
| 1164:1ee9 | YUAN High-Tec... | Polaris AV Capture                   | 5     |            | [7600B0715D](<Desktop/ASUSTek Computer/ET2311/ET2311I/EC5E10BE0E58/UBUNTU-20.04/5.11.0-37-GENERIC/X86_64/7600B0715D>) |
| 2304:0224 | Pinnacle Systems | Pinnacle High Speed USB Device       | 5     |            | [9B0B45B6FB](<Desktop/Dell/Inspiron/Inspiron 580/EC96A893ADA2/UBUNTU-20.04/5.11.0-27-GENERIC/X86_64/9B0B45B6FB>) |
| 0fd9:006a | Elgato Systems   | Game Capture HD60 S+                 | 3     | snd_usb... | [B097A62C18](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/11167364A71C/DEBIAN-11/5.10.0-9-AMD64/X86_64/B097A62C18>) |
| 0fd9:0051 | Elgato Systems   | GameCapture HD                       | 2     |            | [3A3874784C](<Desktop/ASUSTek Computer/P8P67/P8P67 DELUXE/B002AC461587/UBUNTU-18.04/4.4.0-130-GENERIC/X86_64/3A3874784C>) |
| 0fd9:0061 | Elgato Systems   | Cam Link                             | 2     | snd_usb... | [9CB7EBEA38](<Notebook/ASUSTek Computer/X580/X580VD/F521653612FB/ARCH-ROLLING/5.16.0-ARCH1-1/X86_64/9CB7EBEA38>) |
| 0fd9:0067 | Elgato Systems   | Cam Link 4K                          | 2     | snd_usb... | [EDD8B3C5B2](<Desktop/ASUSTek Computer/PRIME/PRIME X399-A/8D222005E7BF/FEDORA-34/5.13.12-200.FC34.X86_64/X86_64/EDD8B3C5B2>) |
| 1b80:a41c | Afatech          | Polaris AV Capture                   | 2     |            | [6DE34F58AF](<Notebook/Toshiba/PORTEGE/PORTEGE M800/79DF89B29C5F/FEDORA-33/5.9.16-200.FC33.X86_64/X86_64/6DE34F58AF>) |
| 04b4:00f9 | Cypress Semic... | Ninja Dock                           | 1     | usbhid     | [79FA3F7509](<Notebook/Lenovo/ThinkPad/ThinkPad P15v Gen 1 20TQ004JAU/244A0ACE6641/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/79FA3F7509>) |
| 0fd9:0062 | Elgato Systems   | Cam Link                             | 1     | snd_usb... | [D0234C90FB](<Notebook/Lenovo/G50-80/G50-80 80E5/2F41BB9D338F/UBUNTU-18.04/4.18.0-25-GENERIC/X86_64/D0234C90FB>) |
| 5555:3382 | Epiphan Systems  | VGA2USB Frame Grabber                | 1     |            | [37A831391B](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv8/D8B9EB76B074/ROSA-2014.1/3.14.25-NRJ-DESKTOP-1ROSA/X86_64/37A831391B>) |

### Webcam (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 145f:013c | Trust            | Multimedia audio controller          | 3     | gspca_p... | [B85703D1E4](<Desktop/MSI/MS/MS-7387/66739E36F2FF/XUBUNTU-18.04/4.15.0-102-GENERIC/X86_64/B85703D1E4>) |

### Wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 2717:ff88 | Xiaomi           | Mi/Redmi series (RNDIS + ADB)        | 102   | rndis_host | [BC59A5A32B](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bs0xx/4C5B05E3EE0E/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/BC59A5A32B>) |
| 22b8:2e25 | Motorola PCS     | moto g stylus                        | 59    | rndis_host | [01CAE1BB94](<Desktop/Dell/OptiPlex/OptiPlex 390/327A317D7B9C/LINUXMINT-20.3/5.4.0-91-GENERIC/X86_64/01CAE1BB94>) |
| 18d1:4ee4 | Google           | Nexus/Pixel Device (tether+ debug)   | 18    | rndis_host | [74173B18DA](<Notebook/Hewlett-Packard/Laptop/Laptop 14-fq1xxx/63CE0B265668/POP!_OS-21.10/5.15.5-76051505-GENERIC/X86_64/74173B18DA>) |
| 2a70:9024 | OnePlus Techn... | OnePlus                              | 18    | rndis_host | [161EDA858B](<Desktop/Tarox/Basic/Basic 3221BM/9D09085B46DA/PARROT-5.0/5.15.0-15PARROT1-AMD64/X86_64/161EDA858B>) |
| 12d1:1039 | Huawei Techno... | Ideos (tethering mode)               | 12    | rndis_host | [7849D3E43A](<Desktop/Hewlett-Packard/1998/1998/3F41A3A64661/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/7849D3E43A>) |
| 0489:e0a6 | Foxconn / Hon... | Android                              | 11    | rndis_host | [CA8DCD489C](<Desktop/HCL Infosystems Limited/HCL/HCL Desktop/5231B2B389D0/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/CA8DCD489C>) |
| 22d9:2766 | OPPO Electronics | SM6115-QRD _SN:D6BC0450              | 11    | rndis_host | [FEB1D977EA](<Desktop/Gigabyte Technology/H310M/H310M S2 2.0/36872B2C1065/UBUNTU-21.04/5.11.0-16-GENERIC/X86_64/FEB1D977EA>) |
| 1286:4e31 | Marvell Semic... | Mobile Composite Device Bus          | 8     | rndis_host | [387EE22BC4](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2516DCU/FA1E6F775BC2/PARABOLA-ROLLING/5.10.56-GNU-1-LTS/X86_64/387EE22BC4>) |
| 2d95:6ffa | MediaTek         | vivo                                 | 7     | rndis_host | [044A00E086](<Desktop/Dell/OptiPlex/OptiPlex 7010/7B91F523B53D/PARROT-5.0/5.14.0-9PARROT1-AMD64/X86_64/044A00E086>) |
| 0b05:7782 | ASUSTek Computer | Android                              | 6     | rndis_host | [A56935A751](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/04C8222C212F/FEDORA-34/5.13.7-200.FC34.X86_64/X86_64/A56935A751>) |
| 12d1:107c | Huawei Techno... | Android                              | 6     | rndis_host | [C1273267FF](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da1xxx/DE7D849D0D82/UBUNTU-18.04/5.0.0-23-GENERIC/X86_64/C1273267FF>) |
| 05c6:f626 | Qualcomm         | MDM9607-MTP _SN:309A4CFE             | 5     | rndis_host | [CE034FA823](<Desktop/Dell/Precision/Precision T3600/05AC24D0BC52/MANJARO/5.10.84-1-MANJARO/X86_64/CE034FA823>) |
| 0b05:7775 | ASUSTek Computer | Zenfone GO (ZB500KL) (Debug, RNDI... | 5     | rndis_host | [29A20CFBD9](<Notebook/Dell/Inspiron/Inspiron 1428/8AC24116CB36/KDE-NEON-20.04/5.11.0-43-GENERIC/X86_64/29A20CFBD9>) |
| 2d95:6ffb | vivo             | 1819                                 | 4     | rndis_host | [A8D131CD6A](<Notebook/AVITA/NS14/NS14A8/D91E6488D9FA/KALI-2021.2/5.5.0-KALI2-AMD64/X86_64/A8D131CD6A>) |
| 12d1:2607 | Huawei Techno... | HUAWEI                               | 3     | rndis_host | [DCC1CCB590](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-408/59A86BD4C203/LINUXMINT-19.3/5.4.0-80-GENERIC/X86_64/DCC1CCB590>) |
| 15a9:003a | Gemtek           | Modem YOTA 4G LTE                    | 3     | rndis_host | [99F2FBC2FE](<Notebook/Hewlett-Packard/Pavilion/Pavilion 15/1A52BA85F4D8/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/99F2FBC2FE>) |
| 17ef:782f | Lenovo           | Lenovo                               | 3     | rndis_host | [0504CFE362](<Notebook/Toshiba/Satellite/Satellite L30/BA7F43548DE3/LUBUNTU-16.04/4.15.0-122-GENERIC/I686/0504CFE362>) |
| 2d95:600b | vivo             | S9                                   | 3     | rndis_host | [B62C884AEC](<System On Chip/Nvidia/Tegra/Tegra/EA52D6551D30/UBUNTU-18.04/4.9.201-TEGRA/AARCH64/B62C884AEC>) |
| 04b7:88d4 | Compal Electr... | Android                              | 2     | rndis_host | [63AC92DFF4](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349NY1/A211E4318AB0/KUBUNTU-18.04/5.0.0-37-GENERIC/X86_64/63AC92DFF4>) |
| 0bb4:0ffc | HTC (High Tec... | Android Phone                        | 2     | rndis_host | [ACC6C85624](<Notebook/Hewlett-Packard/ZBook/ZBook 15 G3/E1C27D8F48C8/OPENSUSE-20200831/5.8.4-1-DEFAULT/X86_64/ACC6C85624>) |
| 0fce:71aa | Sony Ericsson... | D2303                                | 2     | rndis_host | [0014DBBEAD](<Desktop/Intel/X79/X79 (INTEL Xeon E5-Corei7 DMI2 - C600-C200 Cipset V3.5B/48D01368F3D2/MANJARO-20.1/5.8.3-2-MANJARO/X86_64/0014DBBEAD>) |
| 0fce:71e8 | Sony Ericsson... | F5321                                | 2     | rndis_host | [70D66C5819](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G5/50579B71BFA3/UBUNTU-18.04/4.15.0-29-GENERIC/X86_64/70D66C5819>) |
| 0fce:71fa | Sony Ericsson... | H8216                                | 2     | rndis_host | [6BF9D537A8](<Notebook/Lenovo/ThinkPad/ThinkPad E595 20NFCTO1WW/41CBB9C71701/PARROT-4.8/5.4.0-4PARROT1-AMD64/X86_64/6BF9D537A8>) |
| 109b:5d20 | Hisense          | Spreadtrum Phone                     | 2     | rndis_host | [0B0D4DD23F](<Notebook/Lenovo/ThinkPad/ThinkPad T410 25376B8/485335904AC5/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0B0D4DD23F>) |
| 1271:0541 | Android          | Android                              | 2     | rndis_host | [0C8768F146](<Desktop/Gigabyte Technology/F2/F2A68HM-S1/09717554DC82/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/0C8768F146>) |
| 17ef:7c4b | Lenovo           | TB-X606V                             | 2     | rndis_host | [B9A115E6A4](<All In One/Lenovo/IdeaCentre/IdeaCentre A340-24IWL F0E800Q1IN/7A95353B97C7/POP!_OS-21.04/5.11.0-7620-GENERIC/X86_64/B9A115E6A4>) |
| 1ecb:02e2 | AMTelecom        | JMR1140                              | 2     | rndis_host | [7F0F38DC4D](<Notebook/Hewlett-Packard/15/15/877B5258AEB7/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F0F38DC4D>) |
| 216f:0044 | Altair Semico... | Alt38XX devboard                     | 2     | rndis_host | [92A7F0EA0B](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/C4FC1BD7B711/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/92A7F0EA0B>) |
| 271d:3004 | SPA Condor El... | Allure M1                            | 2     | rndis_host | [B4EF87DE2D](<Desktop/ECS/P4/P4M900T-M2/156C90BAB416/UBUNTU-19.10/5.3.0-55-GENERIC/X86_64/B4EF87DE2D>) |
| 0421:06eb | Nokia Mobile ... | Nokia_X (RM-980)                     | 1     | rndis_host | [E8E340D720](<Notebook/Lenovo/B50-45/B50-45 20388/5432CBE9F415/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/E8E340D720>) |
| 0421:0704 | Nokia Mobile ... | Nokia_X2 (RM-1013)                   | 1     | rndis_host | [2762E434EB](<Desktop/MSI/MS/MS-7309/B75258124D4D/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/2762E434EB>) |
| 0471:2005 | Philips (or NXP) | X586                                 | 1     | rndis_host | [84A631B3D1](<Desktop/MSI/MS/MS-7592/0E8A5F8510C0/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-I586/I686/84A631B3D1>) |
| 04dd:97f2 | Sharp            | SH05F                                | 1     | rndis_host | [B10FE6845E](<Notebook/Acer/Aspire/Aspire 4740/C3BF1BF6536E/UBUNTU-18.04/4.15.0-65-LOWLATENCY/X86_64/B10FE6845E>) |
| 0502:3950 | Acer             | B3-A40                               | 1     | rndis_host | [75EF8688A2](<All In One/Acer/Aspire/Aspire ZC-606/7E3C8CE0B8C9/LINUXMINT-19.3/5.4.0-96-GENERIC/X86_64/75EF8688A2>) |
| 05c6:0a02 | Qualcomm         | Jolla C                              | 1     | rndis_host | [A08DCFFB5A](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-0xxx/A7BE62182FA3/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/A08DCFFB5A>) |
| 05c6:902d | Qualcomm         | Android                              | 1     | rndis_host | [E6C85F7E85](<Notebook/Dell/Latitude/Latitude E6510/88F57FBE8570/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/E6C85F7E85>) |
| 05c6:90b6 | Qualcomm         | Android                              | 1     | rndis_host | [DBCA41493B](<Notebook/Lenovo/Legion/Legion Y9000X 2020 81TH/F2E03BE425DB/DEBIAN-10/5.3.0-3-AMD64/X86_64/DBCA41493B>) |
| 0b05:5603 | ASUSTek Computer | ASUS_Z01RD                           | 1     | rndis_host | [82B2D38326](<Notebook/Itautec/Infoway/Infoway/E2A49DA708B2/LMDE-4/4.19.0-17-686/I686/82B2D38326>) |
| 0e79:52b7 | Archos           | Archos                               | 1     | rndis_host | [4E4EF907A0](<Tablet/Samsung Electronics/Galaxy/Galaxy TabPro S/E688B88A43B4/TRISQUEL-9.0/4.15.0-121-GENERIC/X86_64/4E4EF907A0>) |
| 0fce:7193 | Sony Ericsson... | C6603                                | 1     | rndis_host | [F748A62EBE](<Desktop/ASUSTek Computer/P5/P5Q-E/51C4EC4DA427/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/F748A62EBE>) |
| 0fce:71ba | Sony Ericsson... | D6603                                | 1     | rndis_host | [5974A74BFD](<Notebook/Acer/Aspire/Aspire E5-575/98B127133C3F/ROSA-2014.1/4.9.9-NRJ-DESKTOP-1ROSA-X86_64/X86_64/5974A74BFD>) |
| 0fce:71de | Sony Ericsson... | F3111                                | 1     | rndis_host | [D1BA1C9EFA](<Desktop/Gigabyte Technology/F2/F2A85X-D3H/DD566B4052CE/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/D1BA1C9EFA>) |
| 0fce:71e7 | Sony Ericsson... | F8331                                | 1     | rndis_host | [8AE1EA1D6B](<Notebook/Clevo/W760/W760SUB/281C151741D1/XUBUNTU-20.04/5.11.0-34-GENERIC/X86_64/8AE1EA1D6B>) |
| 0fce:71f3 | Sony Ericsson... | G8341                                | 1     | rndis_host | [3AF551E450](<Desktop/Gigabyte Technology/H310M/H310M H 2.0/15C73346AD35/LINUXMINT-20/5.4.0-60-GENERIC/X86_64/3AF551E450>) |
| 0fce:71f6 | Sony Ericsson... | H4311                                | 1     | rndis_host | [C9FFEA0EA6](<Desktop/ASRock/M3/M3A785GMH-128M/6FCFD6C98E6C/ROSA-2014.1/4.9.9-NRJ-DESKTOP-1ROSA-I586/I686/C9FFEA0EA6>) |
| 0fce:7201 | Sony Ericsson... | I4113                                | 1     | rndis_host | [A8B162F110](<Notebook/Acer/Aspire/Aspire ES1-711/B8EA7665A1C7/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/A8B162F110>) |
| 0fce:720d | Sony Ericsson... | XQ-AS52                              | 1     | rndis_host | [560598D6FB](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX433FN_UX433FN/684DC70D2D8D/POP!_OS-21.04/5.13.0-7614-GENERIC/X86_64/560598D6FB>) |
| 0fce:81a9 | Sony Ericsson... | D5322                                | 1     | rndis_host | [502EF11B75](<Desktop/ASUSTek Computer/P5/P5P41T-LE/2C347F6CE053/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/502EF11B75>) |
| 0fce:81bb | Sony Ericsson... | D5803                                | 1     | rndis_host | [7D93192AAE](<Desktop/Aquarius/Pro/Pro, Std, Elt Series/5B685616037B/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-I586/I686/7D93192AAE>) |
| 0fce:81e8 | Sony Ericsson... | F5321                                | 1     | rndis_host | [D1E41EC5C0](<Notebook/Hewlett-Packard/650/650/4E927F6DFE5C/LUBUNTU-20.10/5.8.0-26-GENERIC/X86_64/D1E41EC5C0>) |

### Xbox (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:0289 | Microsoft        | Xbox Controller S                    | 3     | xpad       | [0FCCD48745](<Desktop/ASRock/H310/H310CM-HDV/D8BDF6C4A74B/UBUNTU-20.04/5.8.0-63-GENERIC/X86_64/0FCCD48745>) |
| 045e:0285 | Microsoft        | Xbox Controller S                    | 1     | usbfs      | [3B240B1EF9](<Desktop/Gigabyte Technology/H61/H61M-S2PV/CA33710088DF/DEBIAN-TESTING/5.7.0-1-AMD64/X86_64/3B240B1EF9>) |
| 0c12:880a | Zeroplus         | Pelican Eclipse PL-2023              | 1     |            | [C5BABDFD30](<Notebook/Lenovo/ThinkPad/ThinkPad T420s 4174EK3/9DE5DCA43A62/LINUXMINT-20/5.4.0-48-GENERIC/X86_64/C5BABDFD30>) |
| 0e4c:3510 | Radica Games     | Gamester for Xbox                    | 1     | xpad       | [933234F294](<Desktop/Dell/Precision/Precision T3600/05AC24D0BC52/MANJARO/5.10.70-1-MANJARO/X86_64/933234F294>) |

### Others (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0b05:18f3 | ASUSTek Computer | AURA LED Controller                  | 694   | usbhid     | [74AA64E60F](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-E GAMING/C9A3879713A4/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/74AA64E60F>) |
| 0b05:1939 | ASUSTek Computer | AURA LED Controller                  | 371   | usbhid     | [EED6DC3694](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/1553ADD3C443/ARCH/5.16.13-ARCH1-1/X86_64/EED6DC3694>) |
| 27c6:538d | Shenzhen Good... | FingerPrint                          | 340   | usbfs      | [E99C4341CA](<Notebook/Dell/Inspiron/Inspiron 5409/34EA23E7BE6D/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/E99C4341CA>) |
| 05ac:8300 | Apple            | Built-in iSight (no firmware loaded) | 166   | isight_... | [6563E94C95](<Notebook/Apple/MacBookPro1/MacBookPro1,1/FA34E0181F6E/UBUNTU-16.04/4.4.0-210-GENERIC/I686/6563E94C95>) |
| 2109:0100 | VIA Labs         | USB 2.0 BILLBOARD                    | 160   |            | [86DC3583CA](<Notebook/ASUSTek Computer/UX430/UX430UNR/F0783EEF957D/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/86DC3583CA>) |
| 2109:0102 | VIA Labs         | USB 2.0 BILLBOARD                    | 158   |            | [7FB04E6C7D](<Notebook/Hewlett-Packard/ENVY/ENVY Laptop 13-ah0xxx/F04CCFFD1E74/ARCH/5.16.11-ARCH1-2/X86_64/7FB04E6C7D>) |
| 04f3:0c00 | Elan Microele... | ELAN:ARM-M4                          | 156   |            | [89EF99BD01](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 14-dy0xxx/4B98458F8617/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/89EF99BD01>) |
| 06cb:00da | Synaptics        |                                      | 153   |            | [E60367127E](<Notebook/Lenovo/ThinkPad/ThinkPad E15 Gen 2 20TD0047TX/57ECBA36E9D1/PARDUS-21.1/5.10.0-11-AMD64/X86_64/E60367127E>) |
| 04f3:0c4b | Elan Microele... | ELAN:Fingerprint                     | 141   |            | [ADF7B6C95E](<Notebook/Lenovo/ThinkBook/ThinkBook 16p Gen 2 20YM/EEB2C11874B5/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/ADF7B6C95E>) |
| 27c6:521d | Shenzhen Good... | FingerPrint                          | 129   |            | [589486D805](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401QM_GA401QM/26E6E3C2710A/UBUNTU-21.10/5.15.27-051527-GENERIC/X86_64/589486D805>) |
| 1c7a:0575 | LighTuning Te... | EgisTec EH575                        | 125   |            | [160A8DD021](<Notebook/Acer/Swift/Swift SF314-42/56AB0D1FBC59/MANJARO-21.2.4/5.15.25-1-MANJARO/X86_64/160A8DD021>) |
| 04f3:0c4c | Elan Microele... | ELAN:ARM-M4                          | 112   |            | [F50ABF2114](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-eu0xxx/01463D33400F/GENTOO-2.6/5.16.12-GENTOO-X86_64/X86_64/F50ABF2114>) |
| 0b05:19af | ASUSTek Computer | AURA LED Controller                  | 107   | usbhid     | [FB860CB8CC](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-P D4/B44E86287B47/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/FB860CB8CC>) |
| 22b8:2e82 | Motorola PCS     | XT1541 [Moto G 3rd Gen]              | 89    | usbfs      | [531E740B37](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/FD79B0CA2E7D/ARCO-ROLLING/5.16.12-ARCH1-1/X86_64/531E740B37>) |
| 04f3:0c4f | Elan Microele... | ELAN:Fingerprint                     | 81    |            | [F2E18241DA](<Notebook/Acer/Aspire/Aspire A515-45/C62E3C765A09/KUBUNTU-21.10/5.13.0-30-GENERIC/X86_64/F2E18241DA>) |
| 27c6:639c | Shenzhen Good... | Goodix USB2.0 MISC                   | 79    |            | [6BB35842EB](<Notebook/Dell/Inspiron/Inspiron 5515/9CE692824631/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/6BB35842EB>) |
| 04f3:0c4d | Elan Microele... | ELAN:Fingerprint                     | 70    | usbfs      | [F9C159A911](<Notebook/Lenovo/IdeaPad/IdeaPad 5 14ITL05 82FE/2FE5B5B1B2A5/PARROT-4.11/5.15.0-15PARROT1-AMD64/X86_64/F9C159A911>) |
| 1d5c:7102 | Fresco Logic     | Generic Billboard Device             | 70    |            | [6430380D5B](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-20.04/5.16.11-76051611-GENERIC/X86_64/6430380D5B>) |
| 2109:0103 | VIA Labs         | USB 2.0 BILLBOARD                    | 65    |            | [755854F7D4](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5A07TAU/0D8B48BD5BBE/ORACLESERVER-8.5/5.4.17-2136.304.4.3.EL8UEK.X86_64/X86_64/755854F7D4>) |
| 1b1c:0c09 | Corsair          | H100i v2                             | 63    |            | [F699397A64](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX R2.0/DE8C5623B62B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F699397A64>) |
| 2109:8818 | VIA Labs         | USB Billboard Device                 | 58    |            | [D6D94816FC](<Convertible/Lenovo/Yoga/Yoga C940-14IIL 81Q9/8BFCF89EE199/GENTOO-2.6/5.15.11-GENTOO-X86_64/X86_64/D6D94816FC>) |
| 27c6:63ac | Shenzhen Good... | Goodix USB2.0 MISC                   | 57    |            | [7147FE2D5C](<Notebook/Dell/XPS/XPS 17 9710/61BA964399B6/MX-21/5.15.25-XANMOD1/X86_64/7147FE2D5C>) |
| 06cb:00d8 | Synaptics        | Synaptics FS7604 Touch Fingerprin... | 55    |            | [BF3D7B3F6C](<Notebook/Hewlett-Packard/ProBook/ProBook 440 G7/A963325455B9/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/BF3D7B3F6C>) |
| 413c:b080 | Dell             | DA20 Adapter                         | 54    |            | [851BADDE2E](<Notebook/Dell/XPS/XPS 17 9710/61BA964399B6/MX-21/5.10.0-11-AMD64/X86_64/851BADDE2E>) |
| 2433:b200 | ASETEK           | [NZXT Kraken X60]                    | 53    | usbfs      | [0CF67F0201](<Desktop/ASRock/X99/X99E-ITX-ac/87E9C5669F54/RHEL-8/4.18.0-348.12.2.EL8_5.X86_64/X86_64/0CF67F0201>) |
| 03f0:046b | Hewlett-Packard  | USB-C Dock G5                        | 47    | usbhid     | [30565CB2F9](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G7 Notebook PC/F50B1CFDFE6F/UBUNTU-20.04/5.14.0-1024-OEM/X86_64/30565CB2F9>) |
| 0424:2740 | Microchip Tec... | Hub Controller                       | 45    |            | [F7AF100D8D](<Desktop/MSI/MS-7/MS-7C37/EA69BAC9F4E3/KDE-NEON-20.04/5.13.0-28-GENERIC/X86_64/F7AF100D8D>) |
| 27c6:532d | Shenzhen Good... | Fingerprint                          | 44    |            | [6F14FD298C](<Convertible/Dell/XPS/XPS 13 9310 2-in-1/77A46B94B11C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6F14FD298C>) |
| 17e9:6015 | DisplayLink      | ThinkPad Hybrid USB-C with USB-A ... | 43    | snd_usb... | [33CE116B8A](<Notebook/Lenovo/ThinkBook/ThinkBook 16p Gen 2 20YM/4DAF13AEA8CC/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/33CE116B8A>) |
| 17e9:4301 | DisplayLink      | USB3 to HDMI                         | 38    | snd_usb... | [2F136D5BF5](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN002YPH/61077ED80EDE/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/2F136D5BF5>) |
| 1b1c:0c13 | Corsair          | H115i Platinum                       | 38    |            | [A1E2D401FE](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/2DAEBECC463C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/A1E2D401FE>) |
| 1b1c:0c08 | Corsair          | H80i v2                              | 37    |            | [17CCBF9C76](<Desktop/MSI/MS-7/MS-7A59/E5AC41CD6F98/ELEMENTARY-6.1/5.13.0-27-GENERIC/X86_64/17CCBF9C76>) |
| 0bda:5400 | Realtek Semic... | BillBoard Device                     | 36    |            | [95E3F94065](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 15-eg0xxx/D3B90A352F78/UBUNTU-20.04/5.13.0-28-GENERIC/X86_64/95E3F94065>) |
| 27c6:609c | Shenzhen Good... | Goodix USB2.0 MISC                   | 35    |            | [8902C057FB](<Notebook/Framework/Laptop/Laptop/AE45C9A110C9/GENTOO-2.8/5.16.9-GENTOO-DIST/X86_64/8902C057FB>) |
| 2833:0211 | Oculus VR        | Rift Sensor                          | 35    | uvcvideo   | [232F2DAD91](<Desktop/ASRock/H97M/H97M Pro4/89C9EDCFDE7E/ARCHCRAFT-ROLLING/5.15.7-ZEN1-1-ZEN/X86_64/232F2DAD91>) |
| 04f3:0c5e | Elan Microele... | ELAN:ARM-M4                          | 34    |            | [C4B3104959](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G8 Notebook PC/3CDAF7AE76CA/LINUXMINT-20.3/5.4.0-100-GENERIC/X86_64/C4B3104959>) |
| 1b1c:0c15 | Corsair          | H100i Platinum                       | 34    | usbfs      | [29764FB241](<Desktop/Gigabyte Technology/Z270X-Gaming/Z270X-Gaming 7/5D9003392880/ARCH-ROLLING/5.16.12-ARCH1-1/X86_64/29764FB241>) |
| 2109:0101 | VIA Labs         | USB 2.0 BILLBOARD                    | 32    |            | [F2D47F2D8B](<Desktop/ASUSTek Computer/ROG/ROG Maximus Z690 FORMULA/61EDC45F2E4E/FEDORA-35/5.16.8-200.FC35.X86_64/X86_64/F2D47F2D8B>) |
| 0483:3748 | STMicroelectr... | ST-LINK/V2                           | 30    |            | [B76EF07C59](<Desktop/Gigabyte Technology/990/990FXA-UD3/1079C3583BF3/FEDORA-35/5.15.6-200.FC35.X86_64/X86_64/B76EF07C59>) |
| 2109:8883 | VIA Labs         | USB Billboard Device                 | 30    |            | [759958A4B0](<Desktop/Gigabyte Technology/B550/B550 AORUS MASTER/2A7DA6CE54F8/ARCO-ROLLING/5.16.11-XANMOD1-1/X86_64/759958A4B0>) |
| 2109:8887 | VIA Labs         | 40AN                                 | 30    |            | [48C1285EEC](<Notebook/Lenovo/ThinkPad/ThinkPad P53 20QN0011IV/90C24C7500E3/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/48C1285EEC>) |
| 04f3:0c3d | Elan Microele... | ELAN:Fingerprint                     | 29    | usbfs      | [6A14728490](<Notebook/MSI/GL75/GL75 Leopard 10SDK/8D63ECA236DA/ARCH/5.16.10-ARCH1-1/X86_64/6A14728490>) |
| 0bda:2171 | Realtek Semic... | BillBoard Device                     | 29    |            | [560DE0B6FD](<Desktop/Gigabyte Technology/Z390/Z390 AORUS PRO WIFI/9CC234642A59/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/560DE0B6FD>) |
| 17ef:3074 | Lenovo           | USB Billboard                        | 29    | usbhid     | [ABED4A5863](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 2i 20W0000FRT/03B6D51ED61F/UBUNTU-21.10/5.13.0-30-GENERIC/X86_64/ABED4A5863>) |
| 17ef:3060 | Lenovo           | Billboard Device                     | 28    | usbhid     | [95FF70277E](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401QM_GA401QM/4E4A8BB16FF0/POP!_OS-21.10/5.15.23-76051523-GENERIC/X86_64/95FF70277E>) |
| 1b1c:0c12 | Corsair          | H150i Platinum                       | 28    |            | [4B812791AD](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/2F35197461AB/POP!_OS-21.10/5.15.15-76051515-GENERIC/X86_64/4B812791AD>) |
| 04f3:0c63 | Elan Microele... | ELAN:Fingerprint                     | 27    |            | [E58EB70913](<Notebook/TUXEDO/InfinityBook/InfinityBook S 15 Gen6/50A21C660953/UBUNTU-BUDGIE-20.04/5.13.0-10027-TUXEDO/X86_64/E58EB70913>) |
| 06cb:00fc | Synaptics        |                                      | 26    |            | [973F8EBF5E](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga Gen 6 20XYCTO1WW/279979108057/UBUNTU-22.04/5.15.0-18-GENERIC/X86_64/973F8EBF5E>) |
| 0b05:7772 | ASUSTek Computer | Zenfone GO (ZB500KL) (MTP mode)      | 26    | usbfs      | [AF747FDDC7](<Desktop/Gigabyte Technology/H310M/H310M S2 2.0/3344F8C5171A/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/AF747FDDC7>) |
| 22b8:2e76 | Motorola PCS     | Moto C                               | 26    | usbfs      | [13A9AA4FB3](<Desktop/Gigabyte Technology/H410M/H410M H/8DA009A99BF5/FEDORA-35/5.16.11-200.FC35.X86_64/X86_64/13A9AA4FB3>) |

