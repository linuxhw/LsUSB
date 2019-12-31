Most popular USB devices
========================

This is a project to identify most popular USB devices in modern computers and
share detailed lsusb reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo hw-probe -all -upload

Total reports: 65956.

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
   * [ Disk ](#disk-usb)
   * [ Dvb card ](#dvb-card-usb)
   * [ Fingerprint reader ](#fingerprint-reader-usb)
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
   * [ Modem ](#modem-usb)
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
   * [ Wireless ](#wireless-usb)
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

Top 100 most popular devices in each category.

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Audio (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1043:857c | iCreate... | Xonar U7                     | 14    | usbhid     | 103CA8741C |
| 0955:7002 | Nvidia     | stereo controller            | 9     |            | BA096189BC |
| 1235:8205 | Focusri... | Scarlett Solo USB            | 9     | snd_usb... | 62F60902C0 |
| 041e:322c | Creativ... | SB Omni Surround 5.1         | 8     | snd_usb... | B3D3A2E95B |
| 1235:8016 | Focusri... | Focusrite Scarlett 2i2       | 7     | snd_usb... | 851FF60610 |
| 1235:8202 | Focusri... | Scarlett 2i2 USB             | 6     | snd_usb... | 623E24CBA5 |
| 041e:3f19 | Creativ... | E-MU 0204 / USB              | 5     | snd_usb... | 12E892C5EB |
| 0b05:180d | ASUSTek... | STRIX SOUND CARD             | 5     | snd_usb... | 8121182288 |
| 1397:0509 | BEHRING... | UMC404HD 192k                | 5     | snd_usb... | 25A4C08FB7 |
| 041e:3f02 | Creativ... | E-Mu 0202                    | 4     | snd_usb... | D3E963E3FC |
| 046d:0a0b | Logitech   | ClearChat Pro USB            | 4     | snd_usb... | 5EF345D877 |
| 0b05:17a8 | ASUSTek... | ASUS Xonar Essence One       | 4     | usbhid     | 14FD5844A7 |
| 0b05:180f | ASUSTek... | XONAR SOUND CARD             | 4     | snd_usb... | 25A4C08FB7 |
| 17cc:1001 | Native ... | Komplete Audio 6             | 4     | snd_usb... | 55D80C1ED6 |
| 041e:3f04 | Creativ... | E-Mu 0404                    | 3     | snd_usb... | F380930D83 |
| 0582:012f | Roland     | QUAD-CAPTURE                 | 3     | snd_usb... | 8ADE04AF96 |
| 0d8c:0004 | C-Media... | USB2.0 High-Speed True HD... | 3     | snd_usb... | 586F0C90D9 |
| 152a:8750 | Thesyco... | D10                          | 3     | snd_usb... | 7B5DD98B3D |
| 0499:1506 | Yamaha     | THR5                         | 2     | snd_usb... | CEBC9E7C7E |
| 0499:1704 | Yamaha     | Steinberg UR44               | 2     | snd_usb... | D61154EABE |
| 0499:170a | Yamaha     | Steinberg UR12               | 2     | snd_usb... | 7E353F1BDA |
| 0499:170b | Yamaha     | Steinberg UR242              | 2     | snd_usb... | 7EFEC12422 |
| 0582:00e6 | Roland     | EDIROL UA-25EX (Advanced ... | 2     | snd_usb... | FE2E4341C3 |
| 0644:8030 | TEAC       | US-1800                      | 2     |            | 75C7FE6B69 |
| 0763:4009 | M-Audio    | M-Track Plus                 | 2     | snd_usb... | 596D2F7A72 |
| 0b05:189d | ASUSTek... | Xonar SoundCard              | 2     | snd_usb... | 234B2E07BA |
| 1235:800a | Focusri... | Scarlett 2i4                 | 2     | snd_usb... | 2030142A09 |
| 1235:8200 | Focusri... | Scarlett 2i4 USB             | 2     | snd_usb... | 4E80D3D440 |
| 1397:0507 | BEHRING... | UMC202HD 192k                | 2     | snd_usb... | 805E960AA9 |
| 20b1:0008 | XMOS       | Audio                        | 2     | snd_usb... | 08480474F8 |
| 20b1:000a | XMOS       | xCORE USB Audio 2.0          | 2     | snd_usb... | E563EFC670 |
| 20b1:3023 | XMOS       | X1S USB DAC                  | 2     | snd_usb... | 0A36000504 |
| 2a39:3fb0 | RME        | Babyface Pro (71984822)      | 2     | snd_usb... | 6FE912B704 |
| b58e:0005 | Blue Mi... |                              | 2     | snd_usb... | CDC565D73D |
| 041e:3243 | Creativ... | Sound BlasterX G5            | 1     | snd_usb... | CBEE931F44 |
| 041e:3f0a | Creativ... | E-MU Tracker Pre / USB       | 1     | snd_usb... | 6996B0918E |
| 046d:0a87 | Logitech   | G935 Gaming Headset          | 1     |            | 58C9748044 |
| 0499:1703 | Yamaha     | MG-XU                        | 1     | snd_usb... | 786069DE60 |
| 0499:170f | Yamaha     | Steinberg UR22mkII           | 1     | snd_usb... | 996F55BB36 |
| 04e8:7084 | Samsung... | USB Audio                    | 1     | snd_usb... | BF727C8928 |
| 0582:01df | Roland     | Rubix22                      | 1     | snd_usb... | 5A8A673266 |
| 0644:8043 | TEAC       | UD-501                       | 1     | usbhid     | 71D8772E62 |
| 0763:201a | M-Audio    | M-Audio Micro                | 1     |            | 4AFB8F7991 |
| 0763:400b | Midiman    | M-Track 2X2                  | 1     | snd_usb... | BE604B2A9C |
| 07fd:0005 | Mark of... | 24Ao                         | 1     | snd_usb... | 67D9C7BB6F |
| 08e4:0165 | Pioneer    | USB Audio Device             | 1     | snd_usb... | 2F1A3868EA |
| 08e4:01bd | Pioneer    | A-70DA A-50DA USB AUDIO      | 1     | usbhid     | 5B20134B9A |
| 095d:9205 | Polycom    | CX600                        | 1     | snd_usb... | 7B334F9FB4 |
| 0b05:17a3 | ASUSTek... | ROG ThunderBolt Audio        | 1     | snd_usb... | C784644541 |
| 0b05:17b1 | ASUSTek... | ThunderFX                    | 1     | snd_usb... | B1F64D81B5 |
| 0b05:17f3 | ASUSTek... | ASUS EONE MKII USB DAC       | 1     | usbhid     | F599EB6750 |
| 0b05:17f5 | ASUSTek... | ASUS XONAR U5                | 1     | snd_usb... | E8E7E33BB2 |
| 0b05:180c | ASUSTek... | STRIX RAID DLX               | 1     | snd_usb... | A51882A612 |
| 0b05:183c | ASUSTek... | Xonar U7 MKII                | 1     | usbhid     | 9A70878DE0 |
| 0bda:485a | Realtek... | USB Audio                    | 1     | snd_usb... | CEA175B6F3 |
| 0db0:7926 | Micro S... | USB2.0 High-Speed True HD... | 1     | snd_usb... | 065A4C6977 |
| 1235:8006 | Focusri... | Focusrite Scarlett 2i2       | 1     | snd_usb... | 5DC57BDE0C |
| 1235:8008 | Focusri... | Saffire 6                    | 1     | snd_usb... | 2E214EDAA5 |
| 1235:800c | Focusri... | Scarlett 18i20               | 1     | snd_usb... | 83413EEEDF |
| 1235:800e | Focusri... | iTrack Solo                  | 1     | snd_usb... | D1B3D0E283 |
| 1235:8012 | Focusri... | Scarlett 6i6                 | 1     | snd_usb... | 87E89E7B91 |
| 1235:801c | Focusri... | Scarlett Solo USB            | 1     | snd_usb... | 13A468E1E4 |
| 1235:8204 | Focusri... | Scarlett 18i8 2nd Gen        | 1     | snd_usb... | F192890A26 |
| 152a:85d3 | Thesyco... | Audinst HUD-DX1              | 1     | snd_usb... | 1B1C811590 |
| 152a:85dd | Thesyco... | SMSL Sanskrit 10th           | 1     | snd_usb... | E3F88D9448 |
| 154e:1003 | D&M Hol... | DA-300USB                    | 1     | usbhid     | DE9A3F49DB |
| 154e:3005 | D&M Hol... | PM7005                       | 1     | snd_usb... | 1E889CCEFD |
| 17cc:1021 | Native ... | Traktor Audio 10             | 1     | snd_usb... | 7D2057C89D |
| 17cc:1330 | Native ... | Traktor Audio 2 MK2          | 1     | usbhid     | DDC37B050D |
| 194f:0103 | PreSonu... | AudioBox 1818 VSL            | 1     | snd_usb... | 5BE101218C |
| 1fc9:6315 | NXP Sem... | Monitor 10                   | 1     | snd_usb... | 5652E9E755 |
| 20b1:0002 | XMOS       | USB Audio 2.0                | 1     | snd_usb... | 2EEB0DCBEF |
| 20b1:3008 | XMOS       | iFi (by AMR) HD USB Audio    | 1     | snd_usb... | 9C11BAA82B |
| 22e8:dac2 | Cambrid... | USB Audio 2.0                | 1     | snd_usb... | 7984717E58 |
| 22e8:dac4 | Cambrid... | DAC100 USB 2                 | 1     | snd_usb... | D82B325EA5 |
| 22e8:dac6 | Unknown... | DacMagicXS 2.0               | 1     | snd_usb... | 0C93611C78 |
| 233e:3002 | Aastra     | 6725ip                       | 1     | snd_usb... | B2D3CC175F |
| 249c:930b | M2Tech     | hiFaceTWO UAC2               | 1     | snd_usb... | 53D87B0DB3 |
| 2573:8101 | JAVS       | USB Audio 2.0                | 1     | snd_usb... | 103CA8741C |
| 278b:3001 | ROTEL      | PC-USB                       | 1     | snd_usb... | E9EFD83068 |
| 2972:0001 | SmartAc... | FiiO USB Audio Class 2.0 DAC | 1     | snd_usb... | FBC2F0A547 |
| 2972:0047 | FiiO       | K3                           | 1     | snd_usb... | F0F19467E3 |
| 2a39:3fd3 | RME        | ADI-2 DAC (57750227)         | 1     | snd_usb... | B41206F2FD |

### Bluetooth (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a12:0001 | Cambrid... | Bluetooth Dongle (HCI mode)  | 986   | btusb      | F0615F7666 |
| 8087:0a2a | Intel      | Bluetooth Device             | 862   | btusb      | D75C0B2DA5 |
| 8087:0a2b | Intel      | Bluetooth Device             | 716   | btusb      | 65B1EB0CA1 |
| 8087:07dc | Intel      | Bluetooth Device             | 619   | btusb      | 988B0D9458 |
| 0cf3:3005 | Qualcom... | AR3011 Bluetooth             | 576   | btusb      | A9E0A905BD |
| 0cf3:3004 | Qualcom... | AR3012 Bluetooth 4.0         | 455   | ath3k, ... | 5F1837A6B4 |
| 8087:0aaa | Intel      | Bluetooth Device 9460/9560   | 430   | btusb      | A47D005445 |
| 8087:07da | Intel      | Bluetooth Device             | 369   | btusb      | 19B3FE3FF8 |
| 8086:0189 | Intel      | Bluetooth Device             | 242   | btusb      | A2BC6AC4B5 |
| 0bda:b009 | Realtek... | 802.11n WLAN Adapter         | 234   | btusb      | 16EA8E9AC4 |
| 8087:0aa7 | Intel      | Bluetooth Device             | 228   | btusb      | D5082D8C3F |
| 04ca:3015 | Lite-On... | Lite-On Bluetooth Device     | 212   | btusb      | CE1098A7F5 |
| 04ca:300b | Lite-On... | Lite-On Bluetooth Device     | 211   | ath3k, ... | 216DFBDCC6 |
| 105b:e065 | Foxconn... | BCM43142A0 Bluetooth Module  | 185   | btusb      | 8CE0C08E9A |
| 13d3:3362 | IMC Net... | Atheros AR3012 Bluetooth ... | 175   | ath3k, ... | CE99670CEB |
| 0bda:b728 | Realtek... | Bluetooth Radio              | 163   | btusb      | 7605FC1D79 |
| 03f0:171d | Hewlett... | Bluetooth 2.0 Interface [... | 161   | btusb      | 65DCADAC42 |
| 0a5c:217f | Broadcom   | BCM2045B (BDC-2.1)           | 156   | btusb      | F3FBF8BC70 |
| 0a5c:2101 | Broadcom   | BCM2045 Bluetooth            | 152   | btusb      | 63A6B62E6F |
| 0a5c:219c | Broadcom   | BCM2070 Bluetooth Device     | 147   | btusb      | 5D58BEEA77 |
| 03f0:231d | Hewlett... | Broadcom 2070 Bluetooth C... | 146   | btusb      | 4663DEB0DD |
| 0489:e04e | Foxconn... | Bluetooth Device             | 143   | ath3k, ... | 9084C70732 |
| 0cf3:e500 | Qualcom... | Qualcomm Atheros Bluetoot... | 141   | btusb      | E0F719AEB9 |
| 0cf3:0036 | Qualcom... | Qualcomm Atheros Bluetoot... | 129   | ath3k, ... | A0554A7E66 |
| 0a5c:21b4 | Broadcom   | BCM2070 Bluetooth 2.1 + EDR  | 128   | btusb      | 0C390ADEEF |
| 0cf3:e005 | Qualcom... | Qualcomm Atheros Bluetoot... | 117   | ath3k, ... | 0F87997CD1 |
| 8087:0025 | Intel      | Bluetooth Device             | 114   | btusb      | D1CA80EDFF |
| 0cf3:311d | Qualcom... | Bluetooth USB Host Contro... | 101   | ath3k, ... | 9C722B6763 |
| 0cf3:e009 | Qualcom... | Qualcomm Atheros Bluetoot... | 101   | btusb      | 2B2912B5B0 |
| 0bda:b00a | Realtek... | Bluetooth Radio              | 100   | btusb      | 6EEF4CAED6 |
| 0bda:b721 | Realtek... | Bluetooth Radio              | 98    | btusb      | A14B78EF65 |
| 0a5c:21e6 | Broadcom   | BCM20702 Bluetooth 4.0 [T... | 96    | btusb      | 1949413DC7 |
| 413c:8187 | Dell       | DW375 Bluetooth Module       | 91    | btusb      | 3E3F341EF4 |
| 0930:0508 | Toshiba    | Integrated Bluetooth HCI     | 89    | btusb      | 6108B0C47E |
| 0a5c:21e3 | Broadcom   | HP Portable Valentine        | 88    | btusb      | CD1743483A |
| 0bda:b002 | Realtek... | Bluetooth Radio              | 87    | btusb      | AA2E59FD60 |
| 0489:e00f | Foxconn... | Foxconn T77H114 BCM2070 [... | 86    | btusb      | FC53E6761D |
| 0b05:1712 | ASUSTek... | BT-183 Bluetooth 2.0+EDR ... | 85    | btusb      | F31D0D4E9A |
| 04ca:3006 | Lite-On... | Lite-On Bluetooth Device     | 83    | ath3k, ... | 7BE60A0A2C |
| 0b05:17cb | ASUSTek... | Broadcom BCM20702A0 Bluet... | 83    | btusb      | 0B771C098E |
| 0cf3:e300 | Qualcom... | Qualcomm Atheros Bluetoot... | 83    | btusb      | 18DC19F3EC |
| 0b05:1788 | ASUSTek... | BT-270 Bluetooth Adapter     | 81    | btusb      | 0793BD9823 |
| 0bda:c024 | Realtek... | Bluetooth Radio              | 81    | btusb      | C65ABD0640 |
| 0489:e00d | Foxconn... | Broadcom Bluetooth 2.1 De... | 80    | btusb      | 15789D122D |
| 0bda:b001 | Realtek... | Bluetooth Radio              | 77    | btusb      | 0A66464BD9 |
| 0a5c:21e8 | Broadcom   | BCM20702A0 Bluetooth 4.0     | 73    | btusb      | C24A536495 |
| 0bda:b008 | Realtek... | Bluetooth Radio              | 73    | btusb      | A0C06307BA |
| 0b05:1751 | ASUSTek... | BT-253 Bluetooth Adapter     | 72    | btusb      | 088FFC2823 |
| 13d3:3496 | IMC Net... | Bluetooth Device             | 70    | btusb      | 219AE079DC |
| 8087:0029 | Intel      | Bluetooth Device             | 68    | btusb      | B944521EC0 |
| 0bda:8723 | Realtek... | RT Bluetooth Radio           | 67    | btusb      | 0830776CD0 |
| 0cf3:e004 | Qualcom... | Bluetooth USB Host Contro... | 67    | ath3k, ... | 2187C4D783 |
| 0a5c:216d | Broadcom   | BCM43142A0 Bluetooth 4.0     | 64    | btusb      | 7C960F54DF |
| 0bda:0821 | Realtek... | Bluetooth Radio              | 64    | btusb      | 2B46AD4F9B |
| 13d3:3423 | IMC Net... | Bluetooth Device             | 64    | ath3k, ... | 81F8804034 |
| 0cf3:e360 | Qualcom... | Qualcomm Atheros Bluetoot... | 62    | btusb      | 10AB399874 |
| 0a5c:21d7 | Broadcom   | BCM43142 Bluetooth 4.0       | 61    | btusb      | 17ED1F4194 |
| 0bda:b00b | Realtek... | Bluetooth Radio              | 60    | btusb      | 992E2074FF |
| 04ca:2006 | Lite-On... | BCM43142A0 Bluetooth Module  | 58    | btusb      | CC9B263062 |
| 0cf3:e007 | Qualcom... | Qualcomm Atheros Bluetoot... | 55    | btusb      | D782AD033A |
| 0489:e036 | Foxconn... | Bluetooth USB Host Contro... | 54    | ath3k, ... | 0E850DC9C3 |
| 0a5c:21e1 | Broadcom   | HP Portable SoftSailing      | 52    | btusb      | 57308077EE |
| 13d3:3315 | IMC Net... | Bluetooth module             | 52    | btusb      | A6B1293F94 |
| 13d3:3394 | IMC Net... | Bluetooth                    | 52    | btusb      | 6E20292C6B |
| 148f:1000 | Ralink ... | Motorola BC4 Bluetooth 3.... | 51    | btusb      | 780F3AE697 |
| 0a5c:2145 | Broadcom   | BCM2045B (BDC-2.1) [Bluet... | 50    | btusb      | 1A90AC4588 |
| 13d3:3402 | IMC Net... | Bluetooth USB Host Contro... | 49    | ath3k, ... | A8BE285B93 |
| 413c:8126 | Dell       | Wireless 355 Bluetooth       | 48    | btusb      | 09BC8D2536 |
| 0930:021d | Toshiba    | RT Bluetooth Radio           | 45    | btusb      | AF0C1D5F3C |
| 413c:8140 | Dell       | Wireless 360 Bluetooth       | 45    | btusb      | 2EAA232D45 |
| 0489:e078 | Foxconn... | Bluetooth Device             | 44    | ath3k, ... | F61E2D2B7B |
| 04ca:3016 | Lite-On... | Lite-On Bluetooth Device     | 44    | btusb      | B9A37AB909 |
| 0a5c:2110 | Broadcom   | BCM2045B (BDC-2) [Bluetoo... | 44    | btusb      | 3DAAC5C0C6 |
| 13d3:3526 | IMC Net... | Bluetooth Radio              | 44    | btusb      | 24F8864FB8 |
| 04ca:3010 | Lite-On... | Lite-On Bluetooth Device     | 42    | ath3k, ... | E69A522EFC |
| 05ac:8215 | Apple      | Built-in Bluetooth 2.0+ED... | 42    | btusb      | FA300CEB06 |
| 044e:3017 | Alps El... | BCM2046 Bluetooth Device     | 41    | btusb      | A7F8695392 |
| 413c:8197 | Dell       | Dell Wireless 380 Bluetoo... | 41    | btusb      | 813731AB25 |
| 0489:e0a2 | Foxconn... | Bluetooth Device             | 40    | btusb      | ED8598DB62 |
| 0bda:b006 | Realtek... | Bluetooth Radio              | 40    | btusb      | 225743793E |
| 0b05:179c | ASUSTek... | Bluetooth Device             | 39    | btusb      | BD3C6A762C |
| 13d3:3408 | IMC Net... | Bluetooth Device             | 39    | ath3k, ... | A0D9281AE2 |
| 04ca:3005 | Lite-On... | Bluetooth USB Host Contro... | 37    | ath3k, ... | FC6E592FB1 |
| 0930:0214 | Toshiba    | Askey Bluetooth Module       | 37    | btusb      | A36FC6A447 |
| 1131:1004 | Integra... | Bluetooth Device             | 37    | btusb      | 2373345C64 |
| 0489:e062 | Foxconn... | BCM43142A0                   | 35    | btusb      | B9133671A8 |
| 0489:e032 | Foxconn... | Broadcom BCM20702 Bluetooth  | 34    | btusb      | CE8329CC49 |
| 05ac:8205 | Apple      | Bluetooth HCI                | 32    | btusb      | 3A660A2575 |
| 0a5c:216c | Broadcom   | BCM43142A0 Bluetooth Device  | 32    | btusb      | 86639B5A92 |
| 0a5c:21f4 | Broadcom   | BCM20702A0                   | 32    | btusb      | 0755ABE833 |
| 0cf3:3121 | Qualcom... | Qualcomm Atheros Bluetoot... | 32    | ath3k, ... | 1F86F4415B |
| 13d3:3490 | IMC Net... | Bluetooth Device             | 32    | btusb      | 6391F5ED0E |
| 04ca:3014 | Lite-On... | Qualcomm Atheros Bluetooth   | 31    | ath3k, ... | 576A71CE48 |
| 0a5c:2150 | Broadcom   | BCM2046 Bluetooth Device     | 31    | btusb      | 5986AA0AAC |
| 0a5c:21bc | Broadcom   | BCM2070 Bluetooth 2.1 + EDR  | 31    | btusb      | 7873FB02D1 |
| 0cf3:3008 | Qualcom... | Bluetooth (AR3011)           | 31    | ath3k, ... | AEEE40220B |
| 1286:204c | Marvell... | Bluetooth and Wireless LA... | 31    | btusb      | 85085D7FF6 |
| 0a5c:21f1 | Broadcom   | HP Portable Bumble Bee       | 29    | btusb      | A1C9FF7880 |
| 0bda:b023 | Realtek... | Bluetooth Radio              | 29    | btusb      | 061B2C7F34 |
| 13d3:3529 | IMC Net... | Bluetooth Radio              | 29    | btusb      | 59974C206C |

### Camera (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:0825 | Logitech   | Webcam C270                  | 362   | uvcvideo   | D6F5A65583 |
| 0ac8:3420 | Z-Star ... | Venus USB2.0 Camera          | 264   | uvcvideo   | 50C613C8D6 |
| 04e8:6860 | Samsung... | GT-I9100 Phone [Galaxy S ... | 168   | usbfs      | 55ABCF11C5 |
| 5986:0295 | Acer       | Lenovo EasyCamera            | 160   | uvcvideo   | 62C717C459 |
| 0ac8:c40a | Z-Star ... | A4 TECH USB2.0 PC Camera J   | 155   | uvcvideo   | C87B5D73CA |
| 13d3:5a01 | IMC Net... | USB2.0 VGA UVC WebCam        | 155   | uvcvideo   | 6391F5ED0E |
| 1bcf:2c18 | Sunplus... | HD WebCam                    | 155   | uvcvideo   | 19E141A0F7 |
| 0c45:6340 | Microdia   | Camera                       | 136   | uvcvideo   | 550E44C270 |
| 064e:a103 | Suyin      | Acer/HP Integrated Webcam... | 134   | uvcvideo   | CCC2EA91E1 |
| 058f:a014 | Alcor M... | Asus Integrated Webcam       | 122   | uvcvideo   | AF47B62F54 |
| 13d3:5710 | IMC Net... | UVC VGA Webcam               | 122   | uvcvideo   | 4DB132BB33 |
| 05ac:12a8 | Apple      | iPhone5/5C/5S/6              | 115   | ipheth     | CCD20E9767 |
| 0402:9665 | ALi        | Gateway Webcam               | 114   | uvcvideo   | CEF0B9CE71 |
| 0c45:62c0 | Microdia   | Sonix USB 2.0 Camera         | 111   | uvcvideo   | 5D02B6C874 |
| 1bcf:2883 | Sunplus... | ASUS USB2.0 Webcam           | 111   | uvcvideo   | 1A825B75E9 |
| 0ac8:3450 | Z-Star ... | Vimicro USB Camera (Altair)  | 106   | uvcvideo   | B64547F948 |
| 13d3:5130 | IMC Net... | Integrated Webcam            | 104   | uvcvideo   | 088FFC2823 |
| 058f:5608 | Alcor M... | USB 2.0 Web Camera           | 103   | uvcvideo   | AE477CA654 |
| 2232:1020 | Silicon... | WebCam SC-0311139N           | 102   | uvcvideo   | ECD2F0D753 |
| 046d:082d | Logitech   | HD Pro Webcam C920           | 96    | snd_usb... | 2F0B3935B3 |
| 04f2:b071 | Chicony... | 2.0M UVC Webcam / CNF7129    | 96    | uvcvideo   | 33E615851D |
| 1210:25f4 | DigiTech   | USB 2.0 PC Camera            | 93    | uvcvideo   | A3F9F98355 |
| 04f2:b272 | Chicony... | Lenovo EasyCamera            | 90    | uvcvideo   | 7C676D0AAC |
| 04f2:b47f | Chicony... | VGA Webcam                   | 90    | uvcvideo   | D5082D8C3F |
| 046d:082b | Logitech   | Webcam C170                  | 88    | uvcvideo   | E097415087 |
| 04f2:b1d6 | Chicony... | CNF9055 Toshiba Webcam       | 88    | uvcvideo   | A36FC6A447 |
| 046d:0826 | Logitech   | HD Webcam C525               | 87    | snd_usb... | CC521D8042 |
| 046d:081b | Logitech   | Webcam C310                  | 85    | uvcvideo   | BBAA313D83 |
| 0bda:57b5 | Realtek... | USB Camera                   | 85    | uvcvideo   | CC9B263062 |
| 046d:0819 | Logitech   | Webcam C210                  | 84    | uvcvideo   | 107280E5A9 |
| 13d3:5702 | IMC Net... | UVC VGA Webcam               | 84    | uvcvideo   | A6B1293F94 |
| 2232:1008 | Silicon... | WebCam SCB-1100N             | 81    | uvcvideo   | 5118CD27DD |
| 064e:a219 | Suyin      | 1.3M WebCam (notebook ema... | 79    | uvcvideo   | B99A6015C7 |
| 18ec:3399 | Arkmicr... | USB2.0 PC CAMERA             | 79    | uvcvideo   | A410481B3F |
| 04f2:b1d8 | Chicony... | 1.3M WebCam                  | 78    | uvcvideo   | D16FFC45F1 |
| 04f2:b008 | Chicony... | USB 2.0 Camera               | 77    | uvcvideo   | 6108B0C47E |
| 04f2:b40a | Chicony... | USB2.0 HD UVC WebCam         | 77    | uvcvideo   | A0D9281AE2 |
| 04f2:b52b | Chicony... | USB2.0 VGA UVC WebCam        | 77    | uvcvideo   | A14B78EF65 |
| 093a:2700 | Pixart ... | A4 TECH PC Camera            | 77    | uvcvideo   | 984B3421C1 |
| 13d3:5188 | IMC Net... | USB2.0 UVC HD Webcam         | 76    | uvcvideo   | 179397B4EA |
| 13d3:5a11 | IMC Net... | USB2.0 VGA UVC WebCam        | 76    | uvcvideo   | 59974C206C |
| 5986:0652 | Acer       | Lenovo EasyCamera            | 74    | uvcvideo   | 9BF86AA35D |
| 13d3:5711 | IMC Net... | USB 2.0 UVC VGA WebCam       | 73    | uvcvideo   | ECB853F69D |
| 064e:a101 | Suyin      | Acer CrystalEye Webcam       | 72    | uvcvideo   | BA9EFF4F3B |
| 0408:a060 | Quanta ... | HD WebCam                    | 69    | uvcvideo   | E1D731F58D |
| 0bda:5728 | Realtek... | Lenovo EasyCamera            | 69    | uvcvideo   | 8CE0C08E9A |
| 2232:1006 | Image P... | WebCam SCB-0355N             | 68    | uvcvideo   | F82F83E9FF |
| 04f2:b374 | Chicony... | HD WebCam                    | 67    | uvcvideo   | ECACED6F64 |
| 04f2:b337 | Chicony... | HD WebCam                    | 65    | uvcvideo   | 7857E6A77B |
| 05c8:021e | Cheng U... | HP Webcam-101                | 65    | uvcvideo   | 4C52CE8BDE |
| 0bda:57b3 | Realtek... | Acer 640 x 480 laptop camera | 64    | uvcvideo   | F61E2D2B7B |
| 0ac8:c33f | Z-Star ... | Webcam                       | 62    | uvcvideo   | 60127AB94A |
| 2232:1028 | Silicon... | WebCam SC-03FFL11939N        | 61    | uvcvideo   | 869503FA54 |
| 04f2:b230 | Chicony... | Integrated HP HD Webcam      | 59    | uvcvideo   | D217DB81AF |
| 04f2:b469 | Chicony... | HD WebCam                    | 59    | uvcvideo   | A807D18119 |
| 04f2:b52d | Chicony... | HP Webcam                    | 59    | uvcvideo   | 9FAC88C07A |
| 2232:1029 | Silicon... | WebCam SC-13HDL11939N        | 59    | uvcvideo   | C5694CCAC0 |
| 5986:0292 | Acer       | Lenovo EasyCamera            | 58    | uvcvideo   | 47BBFE4D38 |
| 058f:b002 | Alcor M... | Acer Integrated Webcam       | 57    | uvcvideo   | D500F84DEB |
| 04f2:b044 | Chicony... | Acer CrystalEye Webcam       | 56    | uvcvideo   | E7D08D8DDE |
| 0bda:57de | Realtek... | USB2.0 VGA UVC WebCam        | 55    | uvcvideo   | A54E52EFE8 |
| 1e4e:0102 | Cubeternet | GL-UPC822 UVC WebCam         | 55    | uvcvideo   | 987894BE57 |
| 04f2:b40e | Chicony... | HP Truevision HD camera      | 54    | uvcvideo   | C62B42752B |
| 045e:0779 | Microsoft  | LifeCam HD-3000              | 53    | uvcvideo   | D32464D841 |
| 04f2:b217 | Chicony... | Lenovo Integrated Camera ... | 52    | uvcvideo   | B6BD03FB53 |
| 046d:0829 | Logitech   | Webcam C110                  | 50    | uvcvideo   | FE4505E1D3 |
| 13d3:56a2 | IMC Net... | USB2.0 HD UVC WebCam         | 50    | uvcvideo   | A47D005445 |
| 1908:2311 | GEMBIRD    | USB2.0 PC CAMERA             | 50    | uvcvideo   | 4908CB8960 |
| 04f2:b221 | Chicony... | integrated camera            | 49    | uvcvideo   | F3FBF8BC70 |
| 04f2:b43b | Chicony... | USB 2.0 Camera               | 49    | uvcvideo   | 0E8F6B44E6 |
| 05ac:8507 | Apple      | Built-in iSight              | 49    | uvcvideo   | 303C043B8B |
| 0bda:5801 | Realtek... | USB2.0-Camera                | 48    | uvcvideo   | 566E1793D3 |
| 04f2:b1e5 | Chicony... | USB2.0 0.3M UVC WebCam       | 47    | uvcvideo   | F9B4DC3790 |
| 04f2:b2e1 | Chicony... | Lenovo EasyCamera            | 47    | uvcvideo   | CE8329CC49 |
| 04f2:b3f6 | Chicony... | HD WebCam (Acer)             | 47    | uvcvideo   | 94CD691A35 |
| 05ac:8509 | Apple      | FaceTime HD Camera           | 47    | uvcvideo   | 2B202B204B |
| 0bda:579a | Realtek... | Lenovo EasyCamera            | 47    | uvcvideo   | 9BBE2A2129 |
| 13d3:5122 | IMC Net... | 2M Integrated Webcam         | 47    | uvcvideo   | B7B1C7DF29 |
| 0402:7675 | ALi        | WebCam                       | 46    | uvcvideo   | A54B8C9315 |
| 0408:a031 | Quanta ... | VGA WebCam                   | 46    | uvcvideo   | CE1098A7F5 |
| 04f2:b483 | Chicony... | USB2.0 VGA UVC WebCam        | 46    | uvcvideo   | 7BE60A0A2C |
| 13d3:5165 | IMC Net... | USB Camera                   | 46    | uvcvideo   | A14ECCA066 |
| 5986:2113 | Acer       | Integrated Camera            | 46    | uvcvideo   | 98395B298B |
| 04f2:b23b | Chicony... | CNFA078                      | 45    | uvcvideo   | 2512ED1F69 |
| 04f2:b604 | Chicony... | Integrated Camera            | 45    | uvcvideo   | C65ABD0640 |
| 05a9:2640 | OmniVis... | OV2640 Webcam                | 45    | uvcvideo   | 09BC8D2536 |
| 2232:1005 | Silicon... | WebCam SCB-0385N             | 44    | uvcvideo   | A99FE6DE20 |
| 04f2:b249 | Chicony... | HP Webcam-101                | 43    | uvcvideo   | 758C395C78 |
| 064e:d20c | Suyin      | 1.3M HD WebCam               | 43    | uvcvideo   | 53ECD14649 |
| 04f2:b209 | Chicony... | WebCam                       | 42    | uvcvideo   | 06E96D08B8 |
| 064e:e263 | Suyin      | HP TrueVision HD Integrat... | 42    | uvcvideo   | CEA7815308 |
| 064e:e330 | Suyin      | HD WebCam                    | 42    | uvcvideo   | 7537E7CB35 |
| 064e:d214 | Suyin      | WebCam                       | 41    | uvcvideo   | 5BD4609615 |
| 0c45:6513 | Microdia   | Lenovo EasyCamera            | 41    | uvcvideo   | D59788C082 |
| 046d:081d | Logitech   | HD Webcam C510               | 40    | snd_usb... | 6EE10A7999 |
| 046d:082c | Logitech   | HD Webcam C615               | 40    | uvcvideo   | 5D617B8DE0 |
| 04f2:b307 | Chicony... | TOSHIBA Web Camera - HD      | 40    | uvcvideo   | A0FFB29C6C |
| 0bda:58c2 | Realtek... | Laptop_Integrated_Webcam_HD  | 40    | uvcvideo   | 271C309BFA |
| 17ef:480f | Lenovo     | Integrated Webcam [R5U877]   | 40    | uvcvideo   | 0DCA6ECB6C |
| 1bcf:2880 | Sunplus... | Laptop_Integrated_Webcam_HD  | 40    | uvcvideo   | DF459BC2B0 |

### Card reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:0129 | Realtek... | RTS5129 Card Reader Contr... | 2261  | rtsx_usb   | 19B3FE3FF8 |
| 0bda:0139 | Realtek... | RTS5139 Card Reader Contr... | 422   | rtsx_usb   | 64EDCECFF8 |
| 0aec:3260 | Neodio ... | 7-in-1 Card Reader           | 9     | uas, us... | 101A310C00 |
| 072f:9000 | Advance... | ACR38 AC1038-based Smart ... | 7     | usbfs      | 415CE07875 |
| 0cf2:6250 | ENE Tec... | SD card reader (UB6250)      | 6     | ums_ene... | A6F434EBC3 |
| 0c4b:0500 | Reiner ... | cyberJack RFID standard d... | 5     | usbfs      | 2F2703FBEB |
| 0d8c:5200 | C-Media... | Mass Storage Controller(0... | 5     |            | 24A0914BA3 |
| 17ef:3075 | Lenovo     | USB Billboard Device         | 5     |            | 5F8373C716 |
| 0c4b:0501 | Reiner ... | cyberJack RFID comfort du... | 4     | usbfs      | A70C18309D |
| 0ca6:0010 | Castles... | EZUSB PC/SC Smart Card Re... | 2     |            | EF816B48E7 |
| 047b:020b | Silitek    | SK-3105 SmartCard Reader     | 1     | usbhid     | 986AC800BA |
| 0b0c:003f | Todos AB   | Todos C400 smartcard cont... | 1     |            | 251D958CA9 |
| 0bda:0150 | Realtek... | USB 2.0 Card Reader          | 1     |            | 3C44204AA0 |
| 0c45:1018 | Microdia   | Compact Flash storage mem... | 1     |            | 696C2127B6 |
| 174f:1105 | Syntek     | SM-MS/Pro-MMC-XD Card Reader | 1     | uvcvideo   | E718456945 |

### Cdrom (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 8564:1000 | Transcend  | TS32GJF370 JetFlash 32GB     | 859   | uas, us... | A5A20E3A8D |
| 174c:55aa | ASMedia... | Name: ASM1051E SATA 6Gb/s... | 164   | usb_sto... | D87E2ED1BC |
| 152d:2329 | JMicron... | JM20329 SATA Bridge          | 147   | usb_sto... | 988B0D9458 |
| 04c5:2028 | Fujitsu    | External HDD 128GB           | 100   | uas, us... | E357EFF4D1 |
| 152d:2338 | JMicron... | JM20337 Hi-Speed USB to S... | 90    | uas, us... | 98E4EFCCB2 |
| 152d:0578 | JMicron... | JMS567 SATA 6Gb/s bridge     | 64    | uas, us... | 18D138561D |
| 1bcf:0c31 | Sunplus... | SPIF30x Serial-ATA bridge    | 64    | uas, us... | C2F20FEC02 |
| 0e8d:1887 | MediaTek   | DVDRAM GP60NS50              | 61    | usb_sto... | 2E33715189 |
| 0e8d:1806 | MediaTek   | Samsung SE-208AB Slim Por... | 54    | usb_sto... | 59974C206C |
| 13fd:0840 | Initio     | INIC-1618L SATA 100GB        | 37    | uas, us... | FB4073D000 |
| 0928:0010 | PLX Tec... | Ext Hard Disk 500GB          | 35    | uas, us... | 3251848CE3 |
| 0e8d:1836 | MediaTek   | Samsung SE-S084 Super Wri... | 33    | usb_sto... | A8A0EB4EEE |
| 19d2:1403 | ZTE WCD... | USB SCSI CD-ROM              | 30    | uas, us... | 7873FB02D1 |
| 12d1:107e | Huawei ... | File-CD Gadget               | 28    | uas, us... | BE02E71CFB |
| 0781:5406 | SanDisk    | Cruzer Micro U3 2GB          | 25    | uas, us... | B6F032A1EE |
| 152d:2339 | JMicron... | JM20339 SATA Bridge          | 24    | uas, us... | 6D298DA4A5 |
| 046b:ff20 | America... | Virtual CDROM0               | 22    | uas, us... | A14B2C7156 |
| 1c6b:a223 | Philips... | SDRW-08D2S-U                 | 22    | usb_sto... | D043FCBC96 |
| 174c:1351 | ASMedia... | DVDRW DA8AESH                | 20    | uas        | D73B2AC7D1 |
| 13fd:1040 | Initio     | INIC-1511L PATA Bridge       | 19    | usb_sto... | E0E18094AD |
| 04fc:0c25 | Sunplus... | SATALink SPIF225A 320GB      | 17    | uas, us... | FFF25A9A01 |
| 13fd:3940 | Initio     | external DVD burner ECD81... | 16    | uas, us... | 363851A935 |
| 152e:1640 | LG (HLDS)  | DVDRAM GE20NU11              | 16    | usb_sto... | 9647A2B303 |
| 14cd:6600 | Super Top  | M110E PATA bridge            | 15    | usb_sto... | ADEC400398 |
| 048d:1176 | Integra... | USB Flash Disk 16GB          | 14    | uas, us... | 4F100584BC |
| 1f75:0611 | Innosto... | EZEX-75WN4A0 1TB             | 14    | uas, us... | 42B0E234AF |
| 19d2:1410 | ZTE WCD... | LTE Technologies MSM         | 13    | uas, us... | 0E5869D47C |
| 0b05:7774 | ASUSTek... | Zenfone GO (ZB500KL) (RND... | 12    | rndis_host | 0793BD9823 |
| 13fd:0940 | Initio     | ASUS SBW-06D2X-U 500GB       | 12    | uas, us... | FF2075223C |
| 13fd:3e40 | Initio     | ZALMAN ZM-VE350 256GB        | 12    | uas, us... | CD20A07535 |
| 2109:0711 | VIA Labs   | External USB 3.0             | 12    | uas, us... | 2BFF73F199 |
| 152e:2507 | LG (HLDS)  | PL-2507 IDE Controller       | 11    | uas, us... | 40428812FD |
| 0bda:1a2b | Realtek... | USB Disk autorun             | 10    | uas, us... | 567E5E5444 |
| 12d1:1082 | Huawei ... | File-CD Gadget               | 10    | uas, us... | 0701994A3F |
| 152e:2571 | LG (HLDS)  | DVDRAM GP08NU6B              | 10    | uas, us... | 7C2A18E726 |
| 054c:02d5 | Sony       | DVD-RAM UJ862PS              | 9     | uas, us... | 7B4B0311EA |
| 13fd:2040 | Initio     | Samsung Writemaster exter... | 9     | usb_sto... | E818A123C5 |
| 1c6b:a222 | Philips... | DVD Writer Slimtype eTAU108  | 9     | uas, us... | FF4F65BE26 |
| 0e8d:1956 | MediaTek   | Samsung SE-506 Portable B... | 8     | usb_sto... | 74A6661DF4 |
| 13fd:1640 | Initio     | INIC-1610L SATA Bridge       | 8     | usb_sto... | BDEC0242AA |
| 2e04:c025 | Linux      | File-CD Gadget               | 8     | uas, us... | 561770352F |
| 0781:5408 | SanDisk    | Cruzer Titanium U3 4GB       | 6     | uas, us... | DFE8A137BA |
| 152d:2519 | JMicron... | Transcend                    | 6     | uas, us... | 14FEBB13AA |
| 04b7:0100 | Compal ... | DVDRW DA8AESH                | 5     | uas, us... | DFC4334B0C |
| 04cf:8818 | Myson C... | USB2.0 to ATAPI Bridge Co... | 5     | usb_sto... | 549A0D8258 |
| 04e8:685b | Samsung... | GT-I9100 Phone [Galaxy S ... | 5     | uas, us... | DC58FEE893 |
| 054c:0377 | Sony       | BD-CMB UJ-120                | 5     | uas, us... | 0C80B6E23F |
| 05e3:0719 | Genesys... | SATA adapter                 | 5     | uas, us... | A2C07ECC65 |
| 067b:2571 | Prolifi... | DVDRAM GE24NU30              | 5     | usb_sto... | A5DD292F0E |
| 0bb4:0f25 | HTC (Hi... | One M8                       | 5     | uas, us... | 2AB556FD2E |
| 152d:0562 | JMicron... | MK2035GSS                    | 5     | uas        | 9035828E24 |
| 413c:9016 | Dell       | DVD+/-RW DW316               | 5     | usb_sto... | 42A2D2DC72 |
| 0476:059b | AESP       | DVD RW AD-7580S              | 4     | usb_sto... | B297051783 |
| 13fd:0842 | Initio     | CDDVDW SE-T084P              | 4     | usb_sto... | 02B9759D77 |
| 1782:5d03 | Spreadt... | umopenphone 34GB             | 4     | uas, us... | 0D165C08F9 |
| 2a70:f003 | Linux      | File-CD Gadget               | 4     | uas, us... | 53631F5F96 |
| 2e04:c026 | Linux      | File-CD Gadget               | 4     | uas, us... | C8BAF0AEDF |
| 0402:5621 | ALi        | M5621 High-Speed IDE Cont... | 3     | uas, us... | A3C0EB2B8C |
| 054c:03dc | Sony       | DVD RW DRX-S70U              | 3     | usb_sto... | 7A353432A6 |
| 05ac:1500 | Apple      | SuperDrive [A1379]           | 3     | uas, us... | 2F817B8D77 |
| 05c6:92fe | Qualcomm   | Disk                         | 3     | uas, us... | D06E1D8C5B |
| 05e3:0701 | Genesys... | USB 2.0 IDE Adapter          | 3     | usb_sto... | 15252DCF05 |
| 08e4:017a | Pioneer    | BD-RW BDR-XD05               | 3     | usb_sto... | 28738FC201 |
| 0b05:5600 | ASUSTek... | File-CD Gadget               | 3     | uas, us... | FDE33600E4 |
| 0ecd:a100 | Lite-On IT | LDW-411SX DVD/CD Rewritab... | 3     | usb_sto... | 48DACF6BD2 |
| 1058:070a | Western... | My Passport Essential (WD... | 3     | usb_sto... | 8E365DF17F |
| 13fd:0841 | Initio     | Samsung SE-T084M DVD-RW      | 3     | usb_sto... | 84E58AC976 |
| 19d2:0501 | ZTE WCD... | File-Stor Gadget             | 3     | uas, us... | 865EB363F8 |
| 03f0:2027 | Hewlett... | Virtual DVD-ROM              | 2     | usb_sto... | D9B1EC3C37 |
| 0409:0056 | NEC Com... | DW-224E-C                    | 2     | usb_sto... | 53ABDA4642 |
| 059b:0155 | Iomega     | DVDRAM GSA-4081B             | 2     | uas, us... | 3EE5BD924C |
| 0789:0197 | Logitec    | DVDRAM GP67N                 | 2     | usb_sto... | 266D78E723 |
| 0930:0c06 | Toshiba    | SuperMultiPA3761             | 2     | usb_sto... | D49249D475 |
| 0b05:1797 | ASUSTek... | DVDRAM GU60N                 | 2     | usb_sto... | E2A6782664 |
| 0e8d:1807 | MediaTek   | SDRW-08D2S-U                 | 2     | usb_sto... | 0784C6115A |
| 0e8d:2870 | MediaTek   | Flash autorun                | 2     | uas, us... | DB5A6D60DD |
| 1058:083a | Western... | Virtual CD 083A 1TB          | 2     | uas, us... | 6BEE5D9A22 |
| 12d1:1052 | Huawei ... | MT7-L09                      | 2     | uas, us... | 8B0A240FA2 |
| 12d1:107d | Huawei ... | File-CD Gadget               | 2     | uas, us... | 32E71A014C |
| 12d1:107f | Huawei ... | File-CD Gadget               | 2     | uas, us... | BD698398A7 |
| 13fd:1140 | Initio     | DVD/CDRW UJDA770             | 2     | usb_sto... | B6CCAA4CB3 |
| 152d:2337 | JMicron... | ATA/ATAPI Bridge             | 2     | uas, us... | 26399C140A |
| 17ef:74a6 | Lenovo     | File-Stor Gadget             | 2     | uas, us... | 5C664D23D8 |
| 8564:8000 | Transcend  | TRANSCEND                    | 2     | usb_sto... | EC4B0C74D2 |
| 03f0:1207 | Hewlett... | DVD Writer 840d              | 1     | uas, us... | B3BD7C901C |
| 03f0:4907 | Hewlett... | DVD Writer 556s              | 1     | uas, us... | 0504CC20A9 |
| 03f0:5907 | Hewlett... | DVD Writer 557s              | 1     | usb_sto... | B91A0B2CB2 |
| 03f0:f907 | Hewlett... | DVD Writer 600y              | 1     | usb_sto... | ED7FB8CBB9 |
| 0408:ea42 | Quanta ... | modem CD-ROM                 | 1     | option,... | 8EC72CB3E0 |
| 0409:0840 | NEC Com... | CD/DVDW SE-T084L             | 1     | usb_sto... | A67AF78289 |
| 0411:0094 | BUFFALO    | DVD-RAM GH22NP20             | 1     | usb_sto... | FAD3CD1AA5 |
| 0411:01b8 | BUFFALO    | BD-RW BDR-209M               | 1     | usb_sto... | 692C95368A |
| 0411:01dc | BUFFALO    | Ultra-Slim Portable DVD W... | 1     | usb_sto... | 8F99628F42 |
| 0424:4050 | Standar... | Ultra HS-SD/MMC              | 1     | uas, us... | EBB304F58E |
| 046e:3005 | Behavio... | Mass Storage Device          | 1     | uas, us... | 58754B3F38 |
| 0471:0823 | Philips... | DVD RW AD-7200A              | 1     | uas, us... | F3D9E45F07 |
| 0471:082c | Philips... | SPD3200L1                    | 1     | uas, us... | FE5F95F298 |
| 04b3:4487 | IBM        | RW/DVD GCC-4247N             | 1     | uas, us... | 1501370AB2 |
| 04da:250a | Panason... | DVD-RAM UJ-833S              | 1     | usb_sto... | 497FA7F67C |
| 054c:043a | Sony       | DVD RW AD-7700S              | 1     | uas, us... | 86A741EB31 |

### Chipcard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a5c:5800 | Broadcom   | BCM5880 Secure Applicatio... | 216   | usbfs      | 32D2083BB0 |
| 058f:9540 | Alcor M... | AU9540 Smartcard Reader      | 149   | usbfs      | 345BBA3C1F |
| 0b97:7772 | O2 Micro   | OZ776 CCID Smartcard Reader  | 91    | usbfs      | FF0970D119 |
| 147e:2020 | Upek       | TouchChip Fingerprint Cop... | 73    |            | 1949413DC7 |
| 17ef:1003 | Lenovo     | Integrated Smart Card Reader | 73    | usbfs      | F3FBF8BC70 |
| 0a5c:5801 | Broadcom   | BCM5880 Secure Applicatio... | 65    | usbfs      | C7F7A6189C |
| 0a5c:5832 | Broadcom   | 5880                         | 36    | usbfs      | 4EF902306F |
| 0a5c:5834 | Broadcom   | 5880                         | 26    | usbfs      | E89AA0C891 |
| 0b97:7762 | O2 Micro   | Oz776 SmartCard Reader       | 23    |            | 48CAE00098 |
| 0529:0620 | Aladdin... | Token JC                     | 15    | usbfs      | ACFF74E0DB |
| 072f:90cc | Advance... | ACR38 SmartCard Reader       | 12    | usbfs      | 898F2B7197 |
| 0a5c:5804 | Broadcom   | BCM5880 Secure Applicatio... | 11    |            | BA50FFBC59 |
| 058f:9520 | Alcor M... | EMV Certified Smart Card ... | 10    | usbfs      | 885EC5C180 |
| 08e6:34ec | Gemalto... | Compact Smart Card Reader... | 8     | usbfs      | 38A59CAFAC |
| 0bda:0165 | Realtek... | Smart Card Reader Interface  | 8     | usbfs      | C298C38FA6 |
| 076b:1021 | OmniKey    | CardMan 1021                 | 6     | usbfs      | 8BEB57338D |
| 0a5c:5843 | Broadcom   | 58200                        | 6     |            | F576DDF5DC |
| 08e6:3437 | Gemalto... | GemPC Twin SmartCard Reader  | 5     |            | D2B107774B |
| 04e6:5116 | SCM Mic... | SCR331-LC1 / SCR3310 Smar... | 4     |            | 58A23E8EFE |
| 0a5c:5805 | Broadcom   | 5880                         | 4     |            | 83771C3BEE |
| 0dc3:1004 | Athena ... | ASEDrive CCID                | 4     |            | AFCF4B3764 |
| 1a44:0001 | VASCO D... | Digipass 905 SmartCard Re... | 4     | usbfs      | 6B93E5D1F1 |
| 072f:2200 | Advance... | ACR122U                      | 3     | pn533_usb  | C13D443BF5 |
| 072f:90de | Advance... | Token USB 64K                | 3     | usbfs      | 02F1FBC843 |
| 076b:3021 | OmniKey    | CardMan 3121                 | 3     | usbfs      | 898F2B7197 |
| 0a5c:5842 | Broadcom   | 58200                        | 3     |            | 1FA52D766E |
| 1050:0111 | Yubico.com | Yubikey NEO(-N) OTP+CCID     | 3     | usbhid     | 944525D6AB |
| 072f:b000 | Advance... | ACR3901U                     | 2     |            | A44B651190 |
| 08e6:3438 | Gemalto... | GemPC Key SmartCard Reader   | 2     |            | 4CCFEAF9AE |
| 0a89:0025 | Aktiv      | Rutoken lite                 | 2     | usbfs      | 7F6DBA9244 |
| 0bf8:1006 | Fujitsu... | SmartCard Reader 2A          | 2     |            | 4CDB503B48 |
| 0c4b:9102 | Reiner ... | cyberJack RFID basis cont... | 2     |            | 66EEFE25AF |
| 0ca6:00a0 | Castles... | EZCCID Smart Card Reader     | 2     |            | 3DC7A36CB3 |
| 1050:0406 | Yubico.com | Yubikey 4 U2F+CCID           | 2     | usbhid     | 2902DCE4BA |
| 20a0:4108 | Clay Logic | Nitrokey Pro                 | 2     | usbhid     | 2902DCE4BA |
| 24dc:0101 | ARDS       | JaCarta                      | 2     |            | DA308A78C4 |
| 03f0:164a | Hewlett... | SC Keyboard - Apollo (Lit... | 1     | usbhid     | D0629B653D |
| 0403:e3b4 | Future ... | Parsec Desktop Reader PR-... | 1     |            | 775160993D |
| 048d:1365 | Integra... | SmartCard Reader             | 1     |            | DB4B891E15 |
| 04cc:5072 | ST-Eric... | Chipcard Reader              | 1     |            | 65FD9B5315 |
| 04e6:5119 | SCM Mic... | SCR3340 - ExpressCard54 S... | 1     | usbfs      | 96AAA39135 |
| 04e6:5410 | SCM Mic... | SCR35xx Smart Card Reader    | 1     |            | 219BC0E959 |
| 04e6:e001 | SCM Mic... | SCR331 SmartCard Reader      | 1     |            | D3D8B39015 |
| 072f:b100 | Advance... | ACR39U                       | 1     | usbfs      | A9A218F5DD |
| 076b:3022 | OmniKey    | CardMan 3021                 | 1     | usbfs      | 136B27BA17 |
| 076b:4321 | OmniKey    | CardMan 4321                 | 1     |            | 3191678465 |
| 076b:5421 | OmniKey    | Smart Card Reader USB        | 1     |            | EE4E49C4A1 |
| 0802:0005 | Mako Te... | SZZCS-ZCS80                  | 1     | usbhid     | 6C0FAEA524 |
| 096e:0505 | Feitian... | FT SCR310                    | 1     | usbfs      | 4039D51671 |
| 096e:0853 | Feitian... | U2F CCID KB                  | 1     | usbfs      | 39F6BEF929 |
| 0a5c:5802 | Broadcom   | BCM5880 Secure Applicatio... | 1     |            | 3FCBB46E3F |
| 0c4b:0580 | Reiner ... | cyberJack one                | 1     |            | 5AB1A45C53 |
| 0d46:3010 | Kobil S... | KOBIL Class 3 Reader         | 1     |            | CE2E3AD9AE |
| 1a44:0870 | VASCO D... | DIGIPASS 870                 | 1     |            | 1ED6532125 |
| 20a0:4211 | Clay Logic | Nitrokey Start               | 1     | usbfs      | D4186F5067 |
| 23a0:0004 | BIFIT      | iBank2Key                    | 1     |            | A8A89AC09A |

### Disk (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 058f:6362 | Alcor M... | Flash Card Reader/Writer     | 969   | uas, us... | 2D378E81BE |
| 058f:6366 | Alcor M... | Multi Flash Reader           | 828   | uas, us... | 345BBA3C1F |
| 090c:1000 | Silicon... | Flash Voyager                | 808   | uas, us... | 345BBA3C1F |
| 058f:6387 | Alcor M... | Transcend JetFlash Flash ... | 708   | uas, us... | E40B76E473 |
| 0951:1666 | Kingsto... | DataTraveler 100 G3/G4/SE... | 365   | uas, us... | AF9D5F2B32 |
| 058f:6364 | Alcor M... | AU6477 Card Reader Contro... | 349   | uas, us... | 522AE798B9 |
| 0781:5567 | SanDisk    | Cruzer Blade 16GB            | 330   | uas, us... | 779B6B3344 |
| 13fe:4200 | Kingsto... | Silicon-Power32G 32GB        | 321   | uas, us... | FD20ECEEC0 |
| 0930:6545 | Toshiba    | Kingston DataTraveler 102... | 256   | uas, us... | A3F9F98355 |
| 0bda:0158 | Realtek... | USB 2.0 multicard reader     | 250   | ums_rea... | 3C957A3758 |
| 0bda:0151 | Realtek... | Mass Storage Device (Mult... | 240   | uas, us... | 249DBA1826 |
| 1005:b113 | Apacer ... | Handy Steno/AH123 / Handy... | 216   | uas, us... | 32D296FEE0 |
| 13fe:4100 | Kingsto... | Silicon-Power16G 16GB        | 206   | uas, us... | B223E3C2E0 |
| 048d:1336 | Integra... | SD/MMC Cardreader            | 174   | uas, us... | E40B76E473 |
| 0bda:0138 | Realtek... | RTS5138 Card Reader Contr... | 166   | ums_rea... | A8B0F879A4 |
| 0781:5581 | SanDisk    | Ultra 128GB                  | 163   | uas, us... | D043FCBC96 |
| 0930:6544 | Toshiba    | TransMemory-Mini / Kingst... | 151   | uas, us... | BAF893B7F3 |
| 0951:1665 | Kingsto... | Digital DataTraveler SE9 ... | 146   | uas, us... | 3A712F9C97 |
| 0bda:0111 | Realtek... | RTS5111 Card Reader Contr... | 119   | uas, us... | 13ACEC4985 |
| 0781:5571 | SanDisk    | Cruzer Fit 16GB              | 115   | uas, us... | BB239C7852 |
| 14cd:168a | Super Top  | Storage Device 16GB          | 106   | uas, us... | E357EFF4D1 |
| 058f:9360 | Alcor M... | 8-in-1 Media Card Reader     | 103   | uas, us... | F60B0BE33D |
| 058f:6377 | Alcor M... | AU6375 4-LUN card reader     | 102   | uas, us... | 6D882902AD |
| 0781:5575 | SanDisk    | Cruzer Glide 32GB            | 97    | uas, us... | 704C328C67 |
| 13fe:5500 | Kingsto... | Silicon-Power32G 31GB        | 96    | uas, us... | 502C5D4B04 |
| 0781:5583 | SanDisk    | Ultra Fit 123GB              | 94    | uas, us... | 55D80C1ED6 |
| 05e3:0745 | Genesys... | Logilink CR0012 32GB         | 92    | uas, us... | 11FC0E438A |
| 13fe:3e00 | Kingsto... | Silicon-Power16G 16GB        | 90    | uas, us... | ADE7B4EB87 |
| 18a5:0302 | Verbatim   | STORE N GO 16GB              | 89    | uas, us... | FF0970D119 |
| 12d1:14dc | Huawei ... | E33372 LTE/UMTS/GSM HiLin... | 85    | uas, us... | 53D2EF8D02 |
| 174c:5106 | ASMedia... | Transcend StoreJet 25M3 3... | 85    | uas, us... | 15E3126F2C |
| 1908:0226 | GEMBIRD    | Mass-Storage 134GB           | 82    | uas, us... | 3F59B414C8 |
| 05e3:0723 | Genesys... | GL827L SD/MMC/MS Flash Ca... | 81    | usb_sto... | 502C5D4B04 |
| 0951:1643 | Kingsto... | DataTraveler G3 15GB         | 81    | uas, us... | 487090E1B2 |
| 0bda:0153 | Realtek... | 3-in-1 (SD/SDHC/SDXC) Car... | 79    | uas, us... | 19CA06726A |
| abcd:1234 | Chipsbnk   | Alu Line 16GB                | 79    | uas, us... | 0C84774BED |
| 0bda:0181 | Realtek... | SD/MMC/MS/MSPRO              | 78    | uas, us... | 7C1A93E022 |
| 0951:1642 | Kingsto... | DT101 G2 16GB                | 74    | uas, us... | FF0970D119 |
| 05e3:0716 | Genesys... | USB 2.0 Multislot Card Re... | 73    | uas, us... | 15E3126F2C |
| 0781:556b | SanDisk    | Cruzer Edge 16GB             | 71    | uas, us... | 9DA6060143 |
| 05e3:070e | Genesys... | USB 2.0 Card Reader          | 68    | uas, us... | 8E4185612B |
| 14cd:6116 | Super Top  | M6116 SATA Bridge            | 63    | uas, us... | 92DD9B01DE |
| 0781:5591 | SanDisk    | Ultra Flair USB 3.0 124GB    | 61    | uas, us... | 7DF7D9C296 |
| 0bda:0316 | Realtek... | SD/MMC 128GB                 | 60    | uas, us... | 37BFEEE080 |
| 1307:0330 | Transcend  | 63-in-1 Multi-Card Reader... | 60    | uas, us... | E1DDFFDB07 |
| 13fe:3600 | Kingsto... | flash drive (4GB, EMTEC) ... | 60    | usb_sto... | E6D736339F |
| 0bda:0116 | Realtek... | RTS5116 Card Reader Contr... | 58    | uas, us... | 14EEC92B5D |
| 13fe:4300 | Kingsto... | USB DISK 2.0 16GB            | 58    | uas, us... | 283C5FD2D1 |
| 14cd:8168 | Super Top  | Storage Device               | 53    | uas, us... | E64F670E53 |
| 05ac:8403 | Apple      | Internal Memory Card Reader  | 50    | uas, us... | 303C043B8B |
| 0cf2:6230 | ENE Tec... | SD Card Reader (UB623X)      | 50    | uas, us... | 9650DD9DCE |
| 0bc2:231a | Seagate    | Expansion Portable           | 49    | uas        | 84669A36B5 |
| 0bda:0159 | Realtek... | RTS5159 Card Reader Contr... | 48    | ums_rea... | A6CC982E96 |
| 1058:25a2 | Western... | Elements 25A2 500GB          | 47    | uas, us... | 0C951A796F |
| 0bda:0177 | Realtek... | SD/MMC/MS PRO 31GB           | 45    | uas, us... | 5F7DD9FA0C |
| 0781:5572 | SanDisk    | Cruzer Switch 16GB           | 43    | uas, us... | CC352F0876 |
| 14cd:125d | Super Top  | Storage Device 32GB          | 43    | uas, us... | 5097027E46 |
| 0424:2228 | Standar... | 9-in-2 Card Reader           | 41    | uas, us... | 345BBA3C1F |
| 0480:a202 | Toshiba... | Canvio Basics HDD 500GB      | 40    | uas, us... | 8DF8DAD46F |
| 05e3:0751 | Genesys... | microSD Card Reader          | 39    | uas, us... | 42B284E62D |
| 090c:6300 | Silicon... | Reader SD/MS                 | 39    | uas, us... | BB64800479 |
| 1058:1021 | Western... | Elements Desktop (WDBAAU)    | 39    | uas, us... | 84669A36B5 |
| 1058:1042 | Western... | Elements SE Portable (WDB... | 39    | uas, us... | 615BA4CE00 |
| 8644:8003 | Intenso... | Micro Line 16GB              | 39    | uas, us... | 8F3B236A02 |
| ffff:5678 | VendorCo   | ProductCode 16GB             | 39    | uas, us... | 1949413DC7 |
| 0781:5530 | SanDisk    | Cruzer                       | 38    | uas, us... | BEBF95FDC9 |
| 0951:1607 | Kingsto... | DataTraveler 100 32GB        | 38    | uas, us... | 565150F795 |
| 0bc2:ab24 | Seagate    | Backup Plus Portable Drive   | 38    | uas        | FC7EA0E29B |
| 0bda:0184 | Realtek... | RTS5182 Card Reader          | 38    | uas, us... | A86EF1E6D5 |
| 125f:c08a | A-DATA ... | C008 Flash Drive 32GB        | 38    | uas, us... | D1FAA99D53 |
| 174c:1153 | ASMedia... | ASM2115 SATA 6Gb/s bridge    | 36    | uas, us... | C96E6BC37C |
| 125f:c96a | A-DATA ... | C906 Flash Drive 16GB        | 35    | uas, us... | 832F6EF100 |
| 3538:0901 | pqi        | IntelligentStick 8GB         | 35    | uas, us... | C51735EE45 |
| 0951:1653 | Kingsto... | Data Traveler 100 G2 8 Gi... | 34    | uas, us... | 2933FE3369 |
| 05ac:8406 | Apple      | SD Card Reader               | 33    | uas, us... | 1A26D7B485 |
| 0644:0200 | TEAC       | All-In-One Multi-Card Rea... | 33    | uas, us... | A309FDA4F4 |
| 05dc:a81d | Lexar M... | LJDTT16G [JumpDrive 16GB]... | 32    | uas, us... | 961F173B92 |
| 0bc2:2322 | Seagate    | SRD0NF1 Expansion Portabl... | 32    | uas        | 988B0D9458 |
| 1058:10b8 | Western... | Elements Portable (WDBU6Y... | 32    | uas, us... | 326E45E1EF |
| 14cd:1212 | Super Top  | microSD card reader (SY-T18) | 32    | uas, us... | DF4413AF58 |
| 0781:5590 | SanDisk    | Ultra Dual 15GB              | 31    | uas, us... | 4F4314B0B4 |
| 0951:1625 | Kingsto... | DataTraveler 101 II 4GB      | 31    | uas, us... | 4EA8D503AE |
| 1307:0165 | Transcend  | 2GB/4GB/8GB Flash Drive 16GB | 31    | uas, us... | 6126EB96B3 |
| 14cd:125c | Super Top  | SD card reader               | 31    | uas, us... | C0D7396586 |
| 05e3:0749 | Genesys... | STORAGE DEVICE 8GB           | 30    | uas, us... | 8F2ECB882C |
| 0781:5597 | SanDisk    | Cruzer Glide 3.0 124GB       | 30    | uas, us... | 03956CBFAF |
| 05e3:0732 | Genesys... | All-in-One Cardreader        | 29    | uas, us... | 86E30487B4 |
| 13fe:1d00 | Kingsto... | DataTraveler 2.0 1GB/4GB ... | 29    | uas, us... | AC96BE451C |
| 1f75:0621 | Innosto... | JPVX-22JC3T0                 | 29    | uas, us... | 90BEE29CFB |
| 048d:1234 | Integra... | PenDrive 8GB                 | 28    | uas, us... | FF0970D119 |
| 048d:1345 | Integra... | Multi Cardreader             | 28    | uas, us... | D4D638D4B0 |
| 058f:6361 | Alcor M... | Multimedia Card Reader       | 28    | uas, us... | 68EBBE767E |
| 05e3:0722 | Genesys... | SD/MMC card reader           | 28    | uas, us... | F7CE0A6B8B |
| 0bc2:2312 | Seagate    | Expansion 500GB              | 28    | uas, us... | FF0970D119 |
| 0bda:0328 | Realtek... | SD/MMC CRW                   | 28    | uas, us... | A4567A345B |
| 05e3:0727 | Genesys... | microSD Reader/Writer        | 27    | uas, us... | FFF25A9A01 |
| 0bda:0186 | Realtek... | Card Reader                  | 27    | uas, us... | FC53E6761D |
| 13fd:1840 | Initio     | INIC-1608 SATA bridge        | 27    | uas, us... | 61F3387AAA |
| 1f75:0917 | Innosto... | Ultra Line 16GB              | 27    | uas, us... | 009DCD4A93 |
| 04e8:61b6 | Samsung... | M3 Portable Hard Drive       | 26    | uas, us... | DBAC8BD679 |

### Dvb card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:2838 | Realtek... | RTL2838 DVB-T                | 38    | dvb_usb... | 032EB66625 |
| 07ca:a309 | AVerMed... | AVerTV DVB-T (A309)          | 10    | dvb_usb... | 01F5E9CD57 |
| 0bda:2832 | Realtek... | RTL2832U DVB-T               | 8     | dvb_usb... | 3EB7EB388C |
| 15a4:9016 | Afatech    | AF9015 DVB-T USB2.0 stick    | 7     | dvb_usb... | 850853FE91 |
| 07ca:0831 | AVerMed... | H831 USB Hybrid DVB-T/T2     | 5     |            | D5A4F195AE |
| 07ca:1336 | AVerMed... | A336 MiniCard Hybrid DVB-T   | 5     |            | A2FF4426C9 |
| 1164:1f08 | YUAN Hi... | STK7700D                     | 5     | dvb_usb... | 7D19EDDC5C |
| 15f4:0131 | HanfTek    | dvbt2                        | 5     | dvb_usb... | B4A53FAFC1 |
| 07ca:0830 | AVerMed... | H830 USB Hybrid DVB-T        | 4     |            | 79A097BF6F |
| 2040:7070 | Hauppauge  | Nova-T Stick 3               | 4     | dvb_usb... | FAC36A561A |
| 048d:9135 | Integra... | Zolid Mini DVB-T Stick       | 3     | dvb_usb... | B521C64D4C |
| 0572:c688 | Conexan... | Geniatech T230 DVB-T2 TV ... | 3     | dvb_usb... | 931BED40DE |
| 07ca:a310 | AVerMed... | A310                         | 3     | dvb_usb... | 8C172C772A |
| 2040:9580 | Hauppauge  | NovaT 500Stick               | 3     | dvb_usb... | B4AFED8FAD |
| 2304:0237 | Pinnacl... | PCTV 73e [DiBcom DiB7000PC]  | 3     | dvb_usb... | 6B7FA4FF60 |
| 048d:9005 | Integra... | DVB-T TV Stick               | 2     | dvb_usb... | AE491DB991 |
| 04b4:2102 | Cypress... | Cypress DVB Card             | 2     | dvb_usb... | 3F4C49A9AA |
| 0572:0320 | Conexan... | DVBSky T330 DVB-T2/C tuner   | 2     | dvb_usb... | CF5363083C |
| 07ca:0810 | AVerMed... | H810 USB Hybrid DVB-T        | 2     |            | B46F2FEE35 |
| 07ca:1334 | AVerMed... | H334 MiniCard Hybrid DVB-T   | 2     |            | 647613F22B |
| 1164:0871 | YUAN Hi... | STK7700D                     | 2     | dvb_usb... | 97D9353E2A |
| 13d3:3282 | IMC Net... | DVB-T + GPS Minicard [RTL... | 2     |            | 7F0F347502 |
| 14f7:0500 | TechniS... | DVB-PC TV Star HD            | 2     | dvb_usb... | C7D09ABC04 |
| 187f:0202 | Siano M... | Nice                         | 2     | smsusb     | 7F239B5732 |
| 1d19:1101 | Dexatek... | DK DVB-T Dongle              | 2     | dvb_usb... | E19045809A |
| 2040:7050 | Hauppauge  | Nova-T Stick                 | 2     | dvb_usb... | E6D57EFB25 |
| 0413:6a04 | Leadtek... | DVB-T 2                      | 1     | dvb_usb... | C5B8862A26 |
| 04b4:861f | Cypress... | Anysee E30 USB 2.0 DVB-T ... | 1     | dvb_usb... | 1C1B87DEA4 |
| 07ca:4336 | AVerMed... | A336 MiniCard Hybrid DVB-T   | 1     |            | 0C3E26BCE7 |
| 07ca:8150 | AVerMed... | A815O                        | 1     | dvb_usb... | 69CC9D8136 |
| 07ca:850a | AVerMed... | AverTV Volar Black HD (A850) | 1     | dvb_usb... | 7537E7CB35 |
| 07ca:a815 | AVerMed... | AVerTV DVB-T Volar X (A815)  | 1     | dvb_usb... | 35CFA6018F |
| 07ca:a867 | AVerMed... | AVerTV DVB-T (A867)          | 1     | dvb_usb... | 0ABB4F0E21 |
| 0b48:3006 | TechnoT... | TT-connect S-2400 DVB-S r... | 1     | dvb_usb... | 003EB89135 |
| 0bda:2831 | Realtek... | RTL2831U DVB-T               | 1     | dvb_usb... | 2A72B05F9D |
| 0ccd:0064 | TerraTe... | DVB Card                     | 1     | dvb_usb... | ACFF74E0DB |
| 14aa:0221 | WideVie... | WT-220U DVB-T dongle         | 1     | dvb_usb... | 7FA8E3A5E5 |
| 14aa:0226 | WideVie... | Digital TV Receiver          | 1     | dvb_usb... | 7B994D2EC2 |
| 14aa:0301 | WideVie... | AVermedia/Yakumo/Hama/Typ... | 1     | dvb_usb... | 65E73516B5 |
| 15a4:1001 | Afatech    | AF9015/AF9035 DVB-T stick    | 1     | dvb_usb... | 006CC8353F |
| 1b80:c161 | Afatech    | DVB-T 2                      | 1     |            | 2A8FB37B8C |
| 1b80:d393 | Afatech    | DVB-T receiver [RTL2832U]    | 1     | dvb_usb... | AB722FD0B6 |
| 1b80:e39a | Afatech    | DVB-T395U [af9015]           | 1     |            | 2A8FB37B8C |
| 1d19:1102 | Dexatek... | DK mini DVB-T Dongle         | 1     | dvb_usb... | 66EEFE25AF |
| 1f4d:3000 | G-Tek E... | HD Star DVB-S2 USB2.0        | 1     | dvb_usb... | 4D00BA8216 |
| 2040:5200 | Hauppauge  | NovaT 500Stick               | 1     | dvb_usb... | A5A0DA657B |
| 2304:022b | Pinnacl... | PCTV 71e [Afatech AF9015]    | 1     | dvb_usb... | B778A6096A |
| 2304:022c | Pinnacl... | PCTV 2000e                   | 1     | dvb_usb... | B2BA637E05 |
| 2304:022e | Pinnacl... | PCTV 320cx                   | 1     | dvb_usb... | 9DA08CE4A5 |
| 2304:023a | Pinnacl... | PCTV 801e                    | 1     | dvb_usb... | DC0159ECF4 |
| eb1a:5013 | eMPIA T... | USB 2883 Device              | 1     |            | 5DD14F9164 |

### Fingerprint reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 138a:0011 | Validit... | VFS5011 Fingerprint Reader   | 174   |            | AFC9FC3D29 |
| 138a:003f | Validit... | VFS495 Fingerprint Reader    | 160   | usbfs      | D85B25CD22 |
| 138a:0018 | Validit... | Fingerprint scanner          | 138   |            | 56BA5D2A72 |
| 147e:2016 | Upek       | Biometric Touchchip/Touch... | 125   |            | 6EFC416CE0 |
| 08ff:2580 | AuthenTec  | AES2501 Fingerprint Sensor   | 107   |            | 65DCADAC42 |
| 0483:2016 | STMicro... | Fingerprint Reader           | 106   |            | 5823C076FA |
| 08ff:2810 | AuthenTec  | AES2810                      | 100   |            | 1A90AC4588 |
| 147e:1002 | Upek       | Biometric Touchchip/Touch... | 80    |            | 91C9287871 |
| 138a:0017 | Validit... | VFS 5011 fingerprint sensor  | 78    | usbfs      | 14015A6CDE |
| 138a:0007 | Validit... | VFS451 Fingerprint Reader    | 77    | usbfs      | 82CB2D5E90 |
| 08ff:1600 | AuthenTec  | AES1600                      | 76    |            | B720D65E19 |
| 138a:003c | Validit... | VFS471 Fingerprint Reader    | 75    | usbfs      | 3EAB448396 |
| 138a:003d | Validit... | VFS491                       | 69    |            | 57308077EE |
| 138a:0005 | Validit... | VFS301 Fingerprint Reader    | 57    |            | 566E1793D3 |
| 06cb:009a | Synaptics  | Synaptics WBDI               | 55    |            | 98395B298B |
| 1c7a:0801 | LighTun... | Fingerprint Reader           | 53    |            | DF25B03899 |
| 1c7a:0570 | LighTun... | EgisTec Touch Fingerprint... | 49    |            | 82680EE78B |
| 1c7a:0603 | LighTun... | EgisTec ES603                | 49    |            | D75C0B2DA5 |
| 06cb:00bd | Synaptics  |                              | 45    |            | 1820A998EC |
| 138a:0050 | Validit... | Swipe Fingerprint Sensor     | 45    |            | 18D138561D |
| 138a:0001 | Validit... | VFS101 Fingerprint Reader    | 43    |            | F31F2EC406 |
| 04f3:0903 | Elan Mi... | ELAN:Fingerprint             | 39    |            | 9809687258 |
| 06cb:0081 | Synaptics  | Synaptics WBDI               | 36    |            | B0FCF85E0D |
| 147e:1000 | Upek       | Biometric Touchchip/Touch... | 33    |            | B7F262168C |
| 138a:0097 | Validit... | Synaptics WBDI               | 32    |            | 46BFB60272 |
| 138a:0090 | Validit... | VFS7500 Touch Fingerprint... | 26    | usbfs      | 3504F119EA |
| 138a:00ab | Validit... | Synaptics VFS7552 Touch F... | 24    |            | 65B1EB0CA1 |
| 06cb:00a2 | Synaptics  | Synaptics WBDI               | 23    |            | F4826C3A2A |
| 08ff:168f | AuthenTec  | AES1660 Fingerprint Sensor   | 20    |            | 07B13B0CD0 |
| 04f3:0c1a | Elan Mi... | ELAN:Fingerprint             | 19    |            | 4DCFEFF869 |
| 06cb:0078 | Synaptics  | WBDI Device                  | 19    |            | 4A5BA1C902 |
| 147e:1001 | Upek       | TCS5B Fingerprint sensor     | 19    |            | AAB454995E |
| 04f3:0c03 | Elan Mi... | ELAN:Fingerprint             | 17    |            | BAE5A5C3DD |
| 08ff:2550 | AuthenTec  | AES2550 Fingerprint Sensor   | 16    |            | 09C1DFABF4 |
| 27c6:55b4 | Generic    | Goodix FingerPrint Device    | 15    | usbfs      | B49AAC1247 |
| 06cb:00b7 | Synaptics  | Synaptics VFS7552 Touch F... | 14    |            | 0B8C8AB6F3 |
| 138a:0010 | Validit... | VFS Fingerprint sensor       | 14    |            | 11B6D41A9A |
| 138a:0091 | Validit... | VFS7552 Touch Fingerprint... | 11    |            | 14C2B3FA53 |
| 138a:0008 | Validit... | VFS300 Fingerprint Reader    | 10    |            | 1BB8E0A4D4 |
| 27c6:538c | Goodix     | FingerPrint                  | 9     |            | 85BB9ECF3B |
| 08ff:168b | AuthenTec  | Fingerprint Sensor           | 8     |            | 9BE4F247B6 |
| 08ff:2665 | AuthenTec  | Fingerprint Sensor           | 6     |            | 6A0E9D372C |
| 08ff:2683 | AuthenTec  | Fingerprint Sensor           | 6     |            | 52882927F1 |
| 27c6:5584 | Generic    | Goodix FingerPrint Device    | 6     |            | D1CA80EDFF |
| 06cb:0082 | Synaptics  | My Lockey                    | 5     |            | F2B50C0999 |
| 138a:0094 | Validit... | Synaptics WBDI               | 5     |            | A549A39A12 |
| 045e:00bb | Microsoft  | Fingerprint Reader           | 3     | usbhid     | 9D2304C49F |
| 08ff:1686 | AuthenTec  | Fingerprint Sensor           | 3     |            | 32C7E07A9A |
| 08ff:168a | AuthenTec  | Fingerprint Sensor           | 3     |            | EBCFDCE11A |
| 08ff:168c | AuthenTec  | Fingerprint Sensor           | 3     |            | DA5EB48DBB |
| 27c6:5117 | Shenzhe... | Fingerprint Reader           | 3     |            | 53631F5F96 |
| 27c6:55a4 | Generic    | Goodix FingerPrint Device    | 3     |            | E4301E56F9 |
| 04e8:730a | Samsung... | Fingerprint Device           | 2     |            | 3701BEE474 |
| 138a:0092 | Validit... | Synaptics VFS7552 Touch F... | 2     |            | E9DECBC4FD |
| 27c6:530c | Shenzhe... | Fingerprint Reader           | 2     |            | DAE953BAB0 |
| 04f3:0c3a | Elan Mi... | Elan Security-WBF Fingerp... | 1     |            | F3F60A5C06 |
| 05ba:0002 | Digital... | Fingerprint Scanner, U.ar... | 1     |            | AE361E5F23 |
| 08ff:1660 | AuthenTec  | AES1660 Fingerprint Sensor   | 1     |            | 89EC4F0398 |
| 08ff:2500 | AuthenTec  | AES2501                      | 1     |            | 4DCFB332DF |
| 08ff:2691 | AuthenTec  | Fingerprint Sensor           | 1     |            | 79E75DF44E |
| 138a:009d | Validit... | Synaptics WBDI               | 1     |            | 0818236221 |
| 138a:00a6 | Validit... | Synaptics VFS7552 Touch F... | 1     |            | 2687FA68FB |

### Gamepad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:028e | Microsoft  | Xbox360 Controller           | 118   | xpad       | D399F689F0 |
| 046d:c21f | Logitech   | F710 Wireless Gamepad [XI... | 32    | xpad       | B039AEFD9E |
| 045e:0291 | Microsoft  | Xbox 360 Wireless Receive... | 20    | xpad       | 5B4AFF6FE8 |
| 0079:0011 | DragonRise | Gamepad                      | 18    | usbhid     | F887DD7A43 |
| 046d:c21d | Logitech   | F310 Gamepad [XInput Mode]   | 16    | xpad       | B8C562A7E5 |
| 0810:e501 | Persona... | SNES Gamepad                 | 6     | usbhid     | DB521911E3 |
| 0e8f:0003 | GreenAsia  | MaxFire Blaze2               | 6     | usbhid     | 90B3457F58 |
| 046d:c21e | Logitech   | F510 Gamepad [XInput Mode]   | 5     | xpad       | 107280E5A9 |
| 0e8f:0008 | GreenAsia  | Game Controller for PC       | 4     | usbhid     | B1600EF31C |
| 2563:0575 | ShanWan    | USB WirelessGamepad          | 4     | usbhid     | BEF4BD526B |
| 0583:a000 | Padix (... | MaxFire G-08XU Gamepad       | 3     | usbhid     | 2371D130D0 |
| 0e8f:0012 | GreenAsia  | Joystick/Gamepad             | 3     | usbhid     | 608F40C8AC |
| 1345:6006 | Sino Li... | Defender Wireless Controller | 3     |            | E3D0C37620 |
| 0079:181c | DragonRise | Gamepad                      | 2     | usbhid     | 27564C20BE |
| 046d:c242 | Logitech   | XUSB Gamepad                 | 2     | usbfs      | 38D61517B0 |
| 0e6f:0213 | Logic3     | Afterglow Gamepad for Xbo... | 2     | xpad       | DB5B3DC5C8 |
| 0e8f:310d | GreenAsia  | GAMEPAD 3 TURBO              | 2     | usbhid     | 71A5A103B0 |
| 145f:0231 | Trust      | USB Gamepad                  | 2     | usbhid     | AB75F057B1 |
| 044f:b326 | ThrustM... | Gamepad GP XID               | 1     | xpad       | 3C19F51786 |
| 045e:0026 | Microsoft  | SideWinder GamePad Pro       | 1     | usbhid     | F8BFAA2C3D |
| 050d:0805 | Belkin ... | Nostromo N50 GamePad         | 1     | usbhid     | CE6735B3BF |
| 07b5:0213 | Mega Wo... | Thrustmaster Firestorm Di... | 1     | usbhid     | 70CA2BBB71 |
| 07b5:0312 | Mega Wo... | Gamepad                      | 1     | usbhid     | ADD750665B |
| 0810:0005 | Persona... | USB Gamepad                  | 1     | usbhid     | 3BDBF957FA |
| 0e6f:011e | Logic3     | Rock Candy Gamepad for PS3   | 1     | usbhid     | 8E73A7CEDB |
| 0e6f:011f | Logic3     | Rock Candy Gamepad for Xb... | 1     | xpad       | 80B359DC57 |
| 0e6f:0201 | Logic3     | Gamepad                      | 1     | usbfs      | E20DBED4CE |
| 0e6f:0401 | Logic3     | Gamepad for Xbox 360         | 1     | xpad       | 8772B2BD66 |
| 12ab:f701 | Honey B... | Xbox Controller              | 1     | xpad       | B621A131B1 |
| 145f:01c5 | Trust      | Gamepad                      | 1     | usbhid     | 394EF589B0 |
| 1689:fd00 | Razer USA  | Onza Tournament Edition c... | 1     | xpad       | EC671CD080 |
| 24c6:5b02 | Thrustm... | GPX Gamepad                  | 1     | xpad       | 20CBDD5A24 |
| 7545:1122 | SZMY-POWER | PC Gamepad                   | 1     | usbhid     | 5B3BBC4A24 |

### Hardware key (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a89:0020 | Aktiv      | Rutoken S                    | 9     | usbfs      | 35FB98B552 |
| 0a89:0003 | Aktiv      | Guardant Stealth/Net II      | 8     |            | 5149320E81 |
| 0471:485d | Philips... | Senselock SenseIV v2.x       | 4     |            | E4A6E39276 |
| 14a8:0001 | Soft pr... | Soft protection device: U... | 2     |            | 4015843475 |

### Hasp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0529:0001 | Aladdin... | HASP copy protection dongle  | 42    |            | 4015843475 |

### Hub (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1d6b:0002 | Linux F... | 2.0 root hub                 | 36219 | hub        | 4E93B3E62B |
| 1d6b:0003 | Linux F... | 3.0 root hub                 | 19172 | hub        | A86EF1E6D5 |
| 1d6b:0001 | Linux F... | 1.1 root hub                 | 15749 | hub        | 4E93B3E62B |
| 8087:0024 | Intel      | Integrated Rate Matching Hub | 7459  | hub        | A86EF1E6D5 |
| 8087:8000 | Intel      | Hub                          | 2561  | hub        | 988B0D9458 |
| 8087:0020 | Intel      | Integrated Rate Matching Hub | 1741  | hub        | 82CB2D5E90 |
| 8087:8008 | Intel      | Hub                          | 1699  | hub        | 32D2083BB0 |
| 05e3:0608 | Genesys... | USB-2.0 4-Port HUB           | 1517  | hub        | F0615F7666 |
| 1a40:0101 | incompl... | 4-Port HUB                   | 1289  | hub        | D87E2ED1BC |
| 0438:7900 | AMD        | Hub                          | 669   | hub        | 6EEF4CAED6 |
| 8087:8001 | Intel      | Hub                          | 639   | hub        | 8279148D8F |
| 05e3:0610 | Genesys... | 4-port hub                   | 593   | hub        | 988B0D9458 |
| 0a5c:4500 | Broadcom   | BCM2046B1 USB 2.0 Hub (pa... | 410   | hub        | FA300CEB06 |
| 2109:3431 | VIA Labs   | USB2.0 Hub                   | 349   | hub        | BB239C7852 |
| 0424:2514 | Standar... | USB 2.0 Hub                  | 305   | hub        | 8F2ECB882C |
| 8087:8009 | Intel      | Hub                          | 262   | hub        | 984B3421C1 |
| 2109:2812 | VIA Labs   | USB2.0 VL812 Hub             | 215   | hub        | 615BA4CE00 |
| 058f:6254 | Alcor M... | USB Hub                      | 197   | hub        | 345BBA3C1F |
| 0409:005a | NEC Com... | HighSpeed Hub                | 194   | hub        | 6E20292C6B |
| 05e3:0606 | Genesys... | USB 2.0 Hub / D-Link DUB-... | 181   | hub        | 0CABEB6C95 |
| 2109:0812 | VLI Labs   | USB 3.0 VL812 HUB            | 159   | hub        | 615BA4CE00 |
| 0bda:5411 | Realtek... | 4-Port USB 2.0 Hub           | 145   | hub        | D043FCBC96 |
| 8087:8002 | Intel      | Hub                          | 140   | hub        | E5DA683598 |
| 8087:800a | Intel      | Hub                          | 140   | hub        | E5DA683598 |
| 1a40:0201 | Terminu... | FE 2.1 7-port Hub            | 138   | hub        | 485C2FB9C0 |
| 05e3:0612 | Genesys... | USB3.0 Hub 123               | 137   | hub        | 8F2ECB882C |
| 174c:2074 | ASMedia... | ASM1074 High-Speed hub       | 131   | hub        | B0161E1E77 |
| 174c:3074 | ASMedia... | ASM1074 SuperSpeed hub       | 131   | hub        | B0161E1E77 |
| 2109:2813 | VIA Labs   | USB2.0 Hub                   | 122   | hub        | B039AEFD9E |
| 058f:9254 | Alcor M... | Hub                          | 119   | hub        | F60B0BE33D |
| 0b97:7761 | O2 Micro   | Oz776 1.1 Hub                | 114   | hub        | FF0970D119 |
| 14cd:8601 | Super Top  | USB 2.0 Hub                  | 112   | hub        | E643B8ED58 |
| 0bda:0411 | Realtek... | 4-Port USB 3.0 Hub           | 111   | hub        | D043FCBC96 |
| 8087:07e6 | Intel      | Hub                          | 101   | hub        | 74719C2872 |
| 05ac:1006 | Apple      | Hub in Aluminum Keyboard     | 99    | hub        | FA300CEB06 |
| 2109:0813 | VIA Labs   | USB3.0 Hub                   | 95    | hub        | B039AEFD9E |
| 214b:7000 |            | USB2.0 HUB                   | 85    | hub        | E40B76E473 |
| 2109:2811 | VIA Labs   | USB2.0 Hub                   | 84    | hub        | A47D005445 |
| 2109:0811 | VIA Labs   | 4-Port USB 3.0 Hub           | 82    | hub        | F140183571 |
| 0424:2134 | Standar... | USB2134B                     | 79    | hub        | 8279148D8F |
| 05e3:0616 | Genesys... | hub                          | 77    | hub        | 988B0D9458 |
| 0424:5534 | Standar... | USB5534B                     | 70    | hub        | 8279148D8F |
| 0424:2504 | Standar... | USB 2.0 Hub                  | 68    | hub        | 37BC71433C |
| 2109:8110 | VIA Labs   | USB 3.0 Hub                  | 65    | hub        | A47D005445 |
| 0424:2513 | Standar... | 2.0 Hub                      | 61    | hub        | D28ACFF1E6 |
| 045b:0209 | Hitachi    | Hub                          | 60    | hub        | 2F0B3935B3 |
| 0557:7000 | ATEN In... | Hub                          | 59    | hub        | 988B0D9458 |
| 0a05:7211 | Unknown... | hub                          | 55    | hub        | D87E2ED1BC |
| 045b:0210 | Hitachi    | Hub                          | 52    | hub        | 02A7674592 |
| 0451:8142 | Texas I... | TUSB8041 4-Port Hub          | 49    | hub        | 476F99FF1B |
| 214b:7250 |            | USB2.0 HUB                   | 48    | hub        | 42B284E62D |
| 04b4:6560 | Cypress... | CY7C65640 USB-2.0 "TetraHub" | 47    | hub        | 564EB1FFE4 |
| 0557:8021 | ATEN In... | CS1764A [CubiQ DVI KVMP S... | 46    | hub        | A309FDA4F4 |
| 0424:2512 | Standar... | USB 2.0 Hub                  | 44    | hub        | 75E8A3936D |
| 413c:2513 | Dell       | internal USB Hub of E-Por... | 43    | hub        | 813731AB25 |
| 413c:1003 | Dell       | Keyboard Hub                 | 40    | hub        | 655547B351 |
| 05e3:0607 | Genesys... | Logitech G110 Hub            | 37    | hub        | B3D3A2E95B |
| 2109:2817 | VIA Labs   | USB2.0 Hub                   | 36    | hub        | BF1166DD4B |
| 0424:2744 | Standar... | USB2744                      | 35    | hub        | D2B107774B |
| 8564:4000 | Transcend  | RDF8 16GB                    | 35    | uas, us... | 3C957A3758 |
| 046b:ff01 | America... | Virtual Hub                  | 34    | hub        | A14B2C7156 |
| 2109:0817 | VIA Labs   | USB3.0 Hub                   | 33    | hub        | BF1166DD4B |
| 413c:a005 | Dell       | Internal 2.0 Hub             | 33    | hub        | 48CAE00098 |
| 05e3:0605 | Genesys... | USB 2.0 Hub                  | 32    | hub        | 2AD366F4C0 |
| 17ef:100a | Lenovo     | ThinkPad Mini Dock Plus S... | 32    | hub        | B162D0FD81 |
| 0424:2660 | Standar... | Hub                          | 29    | hub        | 80E0B0265B |
| 0451:8140 | Texas I... | TUSB8041 4-Port Hub          | 29    | hub        | 053F507950 |
| 05ac:1003 | Apple      | Hub in Pro Keyboard [Mits... | 29    | hub        | 485C2FB9C0 |
| 0409:0058 | NEC Com... | HighSpeed Hub                | 28    | hub        | 59E341B3D5 |
| 05e3:0617 | Genesys... | USB3.0 Hub                   | 28    | hub        | 988B0D9458 |
| 2109:0810 | VIA Labs   | 4-Port USB 3.0 VL81x Hub     | 28    | hub        | B0D238EB2E |
| 0424:5744 | Standar... | USB5744                      | 27    | hub        | D2B107774B |
| 2001:f103 | D-Link     | DUB-H7 7-port USB 2.0 hub    | 26    | hub        | B8AA5EF26C |
| 046d:c223 | Logitech   | G11/G15 Keyboard / USB Hub   | 25    | hub        | 6AA8E0B9B0 |
| 05e3:0620 | Genesys... | USB3.0 Hub                   | 24    | hub        | 060179220F |
| 03eb:0902 | Atmel      | 4-Port Hub                   | 23    | hub        | 68248270EE |
| 0bda:5401 | Realtek... | RTL 8153 USB 3.0 hub with... | 23    | hub        | 9650DD9DCE |
| 0424:2640 | Standar... | USB 2.0 Hub                  | 22    | hub        | 009DCD4A93 |
| 413c:5534 | Dell       | USB5534                      | 22    | hub        | 813731AB25 |
| 0409:0059 | NEC Com... | HighSpeed Hub                | 20    | hub        | 3A8B42421B |
| 0424:2807 | Standar... | USB2807 Hub                  | 20    | hub        | DDDCE22B3D |
| 0424:5807 | Standar... | USB5807 Hub                  | 20    | hub        | DDDCE22B3D |
| 0bc2:ab44 | Seagate    | Backup+ Hub                  | 20    | hub        | 0579B2ED3A |
| 0424:2137 | Standar... | USB2137B                     | 19    | hub        | 75E8A3936D |
| 04b4:2050 | Cypress... | hub                          | 19    | hub        | 988203EE61 |
| 0bda:0401 | Realtek... | USB3.0 Hub                   | 19    | hub        | 9650DD9DCE |
| 0424:2412 | Standar... | Hub                          | 18    | hub        | 926A3919E3 |
| 413c:1002 | Dell       | Keyboard Hub                 | 18    | hub        | 7887992116 |
| 03eb:3301 | Atmel      | at43301 4-Port Hub           | 17    | hub        | A6C486FDB5 |
| 0424:2734 | Standar... | USB2734                      | 17    | hub        | 5BE7CC1609 |
| 0451:2036 | Texas I... | TUSB2036 Hub                 | 17    | hub        | 5D617B8DE0 |
| 0451:8044 | Texas I... | Hub                          | 17    | hub        | 831FF4B7FC |
| 413c:1010 | Dell       | USB 2.0 Hub [MTT]            | 16    | hub        | A17808DA56 |
| 413c:2134 | Dell       | USB2134                      | 16    | hub        | 813731AB25 |
| 044e:3011 | Alps El... | BCM2045B2                    | 15    | hub        | B6F0BD6CA4 |
| 0bc2:ab45 | Seagate    | Backup+ Hub                  | 15    | hub        | 0579B2ED3A |
| 0424:5734 | Standar... | USB5734                      | 14    | hub        | 5BE7CC1609 |
| 0451:2046 | Texas I... | TUSB2046 Hub                 | 14    | hub        | 988B0D9458 |
| 0451:8043 | Texas I... | Hub                          | 14    | hub        | AC370F7595 |
| 05e3:0626 | Genesys... | USB3.1 Hub                   | 14    | hub        | A2C937F34C |

### Human interface (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 05ac:8242 | Apple      | Built-in IR Receiver         | 179   | usbhid     | 75E8A3936D |
| 1770:ff00 | MSI EPF... | MSI EPF USB / LED controller | 96    | usbhid     | 6E20292C6B |
| 0483:91d1 | STMicro... | SGS Thomson Microelectronics | 71    | usbhid     | 2DC8B3F35D |
| 0079:0006 | DragonRise | PC TWIN SHOCK Gamepad        | 63    | usbhid     | 8ED3B0B386 |
| 0b05:1872 | ASUSTek... | AURA LED Controller          | 45    | usbhid     | BBAA313D83 |
| 0665:5161 | Cypress... | USB to Serial                | 42    | usbhid     | 2FB35125E3 |
| 10d5:55a2 | Uni Cla... | 2Port KVMSwitcher            | 30    | usbhid     | F60B0BE33D |
| 05ac:8240 | Apple      | Built-in IR Receiver         | 28    | usbhid     | 3A660A2575 |
| 1b1c:0c04 | Corsair    | Integrated USB Bridge        | 26    | usbhid     | 172F18A294 |
| 054c:0268 | Sony       | Batoh Device / PlayStatio... | 21    | usbhid     | 851FF60610 |
| 0b05:1867 | ASUSTek... | AURA Custom Human interface  | 21    | usbhid     | 785E45F5BF |
| 046d:c216 | Logitech   | F310 Gamepad [DirectInput... | 20    | usbhid     | F887DD7A43 |
| 0408:3001 | Quanta ... | Optical Touch Screen         | 19    | usbhid     | F15D263E67 |
| 048d:8350 | Integra... | ITE Device(8350)             | 17    | usbhid     | 6F8FD31C2C |
| 2047:0855 | Texas I... | Invensense Embedded Motio... | 17    | usbhid     | B1BEB13466 |
| 0424:274c | Standar... | Hub Controller               | 16    | usbhid     | 5BE7CC1609 |
| 056a:00e6 | Wacom      | TPCE6                        | 16    | usbhid     | B6BD03FB53 |
| 2101:1407 | ActionStar | USB KVM                      | 16    | usbhid     | 69A2CEC1D7 |
| 1e71:170e | NZXT       | USB Device                   | 15    | usbhid     | 94934B2DA3 |
| 046d:c215 | Logitech   | Extreme 3D Pro               | 14    | usbhid     | C4FE6001DE |
| 1038:1122 | SteelSe... | SteelSeries KLC              | 14    | usbhid     | A9A218F5DD |
| 0765:5010 | X-Rite     | X-Rite Pantone Color Sensor  | 12    | usbhid     | 40EBBC5FE0 |
| 147a:e00d | Formosa... | IR Receiver                  | 12    | usbhid     | 41B216CF99 |
| 0810:0001 | Persona... | Dual PSX Adaptor             | 11    | usbhid     | FCA74860DF |
| 046d:c227 | Logitech   | G15 Refresh Keyboard         | 10    | usbhid     | 6AA8E0B9B0 |
| 054c:05c4 | Sony       | DualShock 4 [CUH-ZCT1E]      | 10    | usbhid     | B3D3A2E95B |
| 0810:0003 | Persona... | PlayStation Gamepad          | 10    | usbhid     | D7CC0778FC |
| 046d:c225 | Logitech   | G11/G15 Keyboard / G keys    | 9     | usbhid     | 100C1162BF |
| 10d5:55a4 | Uni Cla... | 4 Port KVMSwicther           | 9     | usbhid     | 885EC5C180 |
| 03eb:8417 | Atmel      | maXTouch Digitizer           | 8     | usbhid     | BB40D4536A |
| 0451:82ff | Texas I... |                              | 8     | usbhid     | 2E60313B01 |
| 0451:ca01 | Texas I... | USBtoI2C Solution            | 8     | usbhid     | 476F99FF1B |
| 046d:c218 | Logitech   | Logitech RumblePad 2 USB     | 8     | usbhid     | 55D80C1ED6 |
| 10d5:000d | Uni Cla... | SP04-A1                      | 8     | usbhid     | 1C5A3B85A1 |
| 17ef:3066 | Lenovo     | ThinkPad Thunderbolt 3 Do... | 8     | usbhid     | CABDFDF87F |
| 187c:0530 | Alienware  | AW1517                       | 8     | usbhid     | 57B11CE1BC |
| 187c:0550 | Alienware  | AW-ELC                       | 8     | usbhid     | D20FB61951 |
| 0001:0000 | Fry's E... | STD UPS MON V1.0             | 7     | usbhid     | 3833787EFA |
| 044f:b108 | ThrustM... | T-Flight Hotas X Flight S... | 7     | usbhid     | 3FEC3F3DC6 |
| 0457:102b | Silicon... | SiS HID Touch Controller     | 7     | usbhid     | 8365A8B9D6 |
| 048d:8386 | Integra... | ITE Device(8386)             | 7     | usbhid     | 7D2C7C038A |
| 056a:5193 | Wacom      | Pen and multitouch sensor    | 7     | usbhid     | 539C9F807E |
| 1462:7c37 | Micro S... | MYSTIC LIGHT                 | 7     | usbhid     | 38CC600543 |
| 1770:ef35 | ASUS OSD   | ASUS OSD                     | 7     | usbhid     | 55A6E54ACA |
| 187c:0524 | Alienware  | M17x                         | 7     | usbhid     | 1D4C1380A3 |
| 2563:0523 | ShanWan    | PS3/PC Wired GamePad         | 7     | usbhid     | BFEA104C20 |
| 2687:fb01 | Fitbit     | Base Station                 | 7     | usbhid     | 3877A5D3BB |
| 0419:8002 | Samsung... | SyncMaster HID Monitor Co... | 6     | usbhid     | 399FE679CE |
| 044f:b10a | ThrustM... | T.16000M Joystick            | 6     | usbhid     | 417453E269 |
| 0457:10c1 | Silicon... | SiS HID Touch Controller     | 6     | usbhid     | 5E1D50070F |
| 045e:0904 | Microsoft  | Surface Dock Extender        | 6     | usbhid     | 8132DC0ECA |
| 046d:c214 | Logitech   | ATK3 (Attack III Joystick)   | 6     | usbhid     | 107280E5A9 |
| 046d:c21c | Logitech   | G13 Advanced Gameboard       | 6     | usbhid     | 7AACC5A9AA |
| 046d:c222 | Logitech   | G15 Keyboard / LCD           | 6     | usbhid     | 5839919EA2 |
| 054c:058d | Sony       | USB Input Device             | 6     | usbhid     | 4A2DA5DD1B |
| 11ff:3331 |            | PC Game Controller           | 6     | usbhid     | 4787FF9CAC |
| 16c0:05df | Van Ooi... | HID device except mice, k... | 6     | usbhid     | 0DD69D07BD |
| 187c:0521 | Alienware  | M14x                         | 6     | usbhid     | 8BE5B82B62 |
| 03eb:8209 | Atmel      | maXTouch Digitizer           | 5     | usbhid     | 2C6B301BC3 |
| 0416:5020 | Winbond... | HID Transfer                 | 5     | usbhid     | A569D1638B |
| 044f:b315 | ThrustM... | Firestorm Dual Analog 3      | 5     | usbhid     | B6CACD96B5 |
| 0457:10c0 | Silicon... | SiS HID Touch Controller     | 5     | usbhid     | 5523479738 |
| 046d:c219 | Logitech   | F710 Gamepad [DirectInput... | 5     | usbhid     | 92459D790C |
| 046d:c626 | Logitech   | 3Dconnexion Space Navigat... | 5     | usbhid     | C6E5717425 |
| 0483:5715 | STMicro... | RemoteSolution               | 5     | usbhid     | 857C8BE5D0 |
| 1b1c:0c0b | Corsair    | Lighting Node PRO            | 5     | usbhid     | 3973A7CEF2 |
| 03eb:8807 | Atmel      | maXTouch Digitizer           | 4     | usbhid     | 0CFC2759A8 |
| 03eb:8814 | Atmel      | maXTouch Digitizer           | 4     | usbhid     | B1BEB13466 |
| 03eb:8a06 | Atmel      | maXTouch Digitizer           | 4     | usbhid     | 2DC8B3F35D |
| 046d:0a5d | Logitech   | Gaming Headset Battery Ch... | 4     | usbhid     | 215C5E6F2A |
| 046d:c21a | Logitech   | Precision Gamepad            | 4     | usbhid     | F887DD7A43 |
| 04d8:0b29 | Microch... | U2417H_0B29_15083001         | 4     | usbhid     | E8CCB234ED |
| 04d8:0b2a | Microch... | U2717D_0B2A_15091601         | 4     | usbhid     | 6614475F9A |
| 050d:3201 | Belkin ... | F1DF102U/F1DG102U Flip KVM   | 4     | usbhid     | 44D8BC1D36 |
| 05a7:40fe | Bose       | QC35 II                      | 4     | usbhid     | 199FAD181E |
| 05c6:f006 | Qualcomm   | ZTE HSUSB Device             | 4     | usbhid     | 7236E159E0 |
| 064f:2af9 | WIBU-Sy... | CmStick (HID, article no.... | 4     | usbhid     | CB363A3342 |
| 06a3:0460 | Saitek     | ST290 Pro Flight Stick       | 4     | usbhid     | 95BA8F99A0 |
| 0955:000a | Nvidia     | ESA FW Update                | 4     | usbhid     | 713C36EFA0 |
| 0b05:1726 | ASUSTek... | Laptop OLED Display          | 4     | usbhid     | 0860A0C8E0 |
| 11ff:3341 |            | USB Joystick                 | 4     | usbhid     | C183D48CD3 |
| 1b1c:1c05 | Corsair    | Corsair HX-Series C-Link ... | 4     | usbhid     | 6F4D65445A |
| 1b1c:1c06 | Corsair    | Corsair HX-Series C-Link ... | 4     | usbhid     | 4C53FECA58 |
| 1b1c:1c0a | Corsair    | Corsair RM650i C-Link Ada... | 4     | usbhid     | 6DF8CD9DDD |
| 1fd2:6103 | Melfas     | LGD AIT Touch Controller     | 4     | usbhid     | 5BE7CC1609 |
| 222a:0011 | ILITEK     | Multi-Touch                  | 4     | usbhid     | 16D6FCA3F1 |
| 2386:310e | Raydium    | Touch System                 | 4     | usbhid     | 9F5951C997 |
| 8087:0a04 | Intel      | Sensor Solution              | 4     | usbhid     | D87DADFCD6 |
| ffff:0000 |            | 068A                         | 4     | usbhid     | 5BA4EDF60F |
| 03eb:843d | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 1412692359 |
| 03eb:880f | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 3A7CEBA9A2 |
| 03eb:8810 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 94000B6660 |
| 03eb:8819 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | FE571546DB |
| 03eb:8a0b | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 15AF322AD8 |
| 03eb:8a19 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | DE79BB68E4 |
| 03eb:8a1d | Atmel      | maXTouch Digitizer           | 3     | usbhid     | E7B1ADE0EC |
| 03eb:8a41 | Atmel      |                              | 3     | usbhid     | 89B768B90D |
| 03eb:8a96 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | A3E8CC3C5F |
| 03eb:8b0d | Atmel      |                              | 3     | usbhid     | 30A8F9D279 |
| 0409:02b8 | NEC Com... | PA241W                       | 3     | usbhid     | A9E77A23FE |

### Infrared (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 066f:4200 | SigmaTel   | STIr4200 IrDA Bridge         | 5     | stir4200   | 5D5773E96F |
| 0609:031d | SMK Man... | eHome Infrared Receiver      | 4     | mceusb     | B5CD6895D0 |
| 1509:9242 | First I... | eHome Infrared Transceiver   | 3     | mceusb     | 40B94D516E |
| 147a:e017 | Formosa... | eHome Infrared Receiver      | 2     | mceusb     | A1471119F3 |

### Input/keyboard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:c52b | Logitech   | Unifying Receiver            | 2073  | usbhid     | A47D005445 |
| 046d:c534 | Logitech   | Unifying Receiver            | 1093  | usbhid     | F0615F7666 |
| 062a:4101 | MosArt ... | Wireless Keyboard/Mouse      | 895   | usbhid     | 0CABEB6C95 |
| 1c4f:0002 | SiGma M... | Keyboard TRACER Gamma Ivory  | 762   | usbhid     | 9084C70732 |
| 046d:c31c | Logitech   | Keyboard K120 for Business   | 675   | usbhid     | 7E1E79D0B1 |
| 09da:054f | A4Tech     | USB Device                   | 657   | usbhid     | 16EA8E9AC4 |
| 09da:9090 | A4Tech     | XL-730K / XL-750BK / XL-7... | 620   | usbhid     | 1F6E09C44C |
| 045e:0745 | Microsoft  | Nano Transceiver v1.0 for... | 470   | usbhid     | 6FDB8DFE61 |
| 04d9:1702 | Holtek ... | Keyboard LKS02               | 437   | usbhid     | 94CD691A35 |
| 04f3:0103 | Elan Mi... | ActiveJet K-2024 Multimed... | 322   | usbhid     | A86EF1E6D5 |
| 1c4f:0026 | SiGma M... | Keyboard                     | 309   | usbhid     | 2C202D97E7 |
| 1a2c:2124 | China R... | USB Keyboard                 | 276   | usbhid     | 779B6B3344 |
| 046d:c52e | Logitech   | MK260 Wireless Combo Rece... | 240   | usbhid     | F140183571 |
| 1a2c:2d23 | China R... | USB Keyboard                 | 226   | usbhid     | A3871B3E32 |
| 0518:0001 | EzKEY      | USB to PS2 Adaptor v1.09     | 210   | usbhid     | 366E5CAC3F |
| 04d9:1603 | Holtek ... | Keyboard                     | 198   | usbhid     | 057A5601FF |
| 1a2c:0e24 | China R... | USB Keyboard                 | 177   | usbhid     | B8C562A7E5 |
| 09da:0260 | A4Tech     | KV-300H Isolation Keyboard   | 169   | usbhid     | D6F5A65583 |
| 24ae:2000 | RAPOO      | 2.4G Wireless Device         | 155   | usbhid     | 763C21681A |
| 413c:2107 | Dell       | USB Entry Keyboard           | 153   | usbhid     | 5151CB704B |
| 0461:0010 | Primax ... | HP PR1101U / Primax PMX-K... | 148   | usbhid     | 53B4651D22 |
| 04d9:1503 | Holtek ... | Shortboard Lefty             | 148   | usbhid     | 9D4E540AFF |
| 413c:2003 | Dell       | Keyboard                     | 145   | usbhid     | E40B76E473 |
| 1a2c:2c27 | China R... | USB Keyboard                 | 135   | usbhid     | 71F9B6C386 |
| 046d:c517 | Logitech   | LX710 Cordless Desktop Laser | 130   | usbhid     | 7857E6A77B |
| 03f0:0024 | Hewlett... | KU-0316 Keyboard             | 128   | usbhid     | E6D57EFB25 |
| 1a2c:0c23 | China R... | USB Keyboard                 | 128   | usbhid     | 5942A2957D |
| 045e:07b2 | Microsoft  | 2.4GHz Transceiver v8.0 u... | 124   | usbhid     | B039AEFD9E |
| 1a2c:0c21 | China R... | USB Keyboard                 | 124   | usbhid     | 7052A98F3B |
| 258a:0001 | SINO WE... | USB KEYBOARD                 | 109   | usbhid     | 13AF031E5E |
| 062a:3286 | MosArt ... | Nano Receiver [Sandstrom ... | 107   | usbhid     | 2D378E81BE |
| 045e:00db | Microsoft  | Natural Ergonomic Keyboar... | 100   | usbhid     | 9650DD9DCE |
| 046d:c31d | Logitech   | Media Keyboard K200          | 100   | usbhid     | 43EE2001E1 |
| 413c:2113 | Dell       | KB216 Wired Keyboard         | 98    | usbhid     | 90FEDE556D |
| 1d57:fa20 | Xenta      | 2.4G Receiver                | 93    | usbhid     | F61E2D2B7B |
| 0a5c:4502 | Broadcom   | Keyboard (Boot Interface ... | 92    | usbhid     | A8A928ED59 |
| 0e8f:00a7 | GreenAsia  | 2.4G RX                      | 91    | usbhid     | 7605FC1D79 |
| 045e:0750 | Microsoft  | Wired Keyboard 600           | 89    | usbhid     | 9D0BA3BCD7 |
| 062a:0201 | MosArt ... | Defender Office Keyboard ... | 89    | usbhid     | 522AE798B9 |
| 09da:9066 | A4Tech     | F3 V-Track Gaming Mouse      | 88    | usbhid     | 68B91906DC |
| 04b3:3025 | IBM        | NetVista Full Width Keyboard | 85    | usbhid     | 4E93B3E62B |
| 1a81:1004 | Holtek ... | Wireless Dongle              | 85    | usbhid     | A4D3F8A8AC |
| 045e:07f8 | Microsoft  | Wired Keyboard 600 (model... | 84    | usbhid     | DA6FADCAD7 |
| 046d:c312 | Logitech   | DeLuxe 250 Keyboard          | 84    | usbhid     | EC1F6C8A0B |
| 248a:8566 | Maxxter    | SVEN RX 360 Art Wireless ... | 84    | usbhid     | A2BC6AC4B5 |
| 045e:07fd | Microsoft  | Nano Transceiver 1.1         | 83    | usbhid     | 4EB3AF1B51 |
| 046b:ff10 | America... | Virtual Keyboard and Mouse   | 83    | usbhid     | A14B2C7156 |
| 0e8f:0022 | GreenAsia  | multimedia keyboard contr... | 82    | usbhid     | C3FAB2A420 |
| 04f2:0833 | Chicony... | KU-0833 Keyboard             | 75    | usbhid     | 1F6E09C44C |
| 24ae:2001 | RAPOO      | 5G Wireless Device           | 75    | usbhid     | 363B08984A |
| 040b:2000 | Weltren... | USB Keyboard                 | 71    | usbhid     | 2B573D439E |
| 0c45:7603 | Microdia   | USB Keyboard                 | 71    | usbhid     | 26E9910108 |
| 046d:c328 | Logitech   | Corded Keyboard K280e        | 70    | usbhid     | B944521EC0 |
| 0566:3002 | Montere... | Keyboard                     | 69    | usbhid     | 984F33EE01 |
| 046d:c318 | Logitech   | Illuminated Keyboard         | 66    | usbhid     | BF1166DD4B |
| 046d:c315 | Logitech   | Classic Keyboard 200         | 65    | usbhid     | 15EA243CBA |
| 045e:00dd | Microsoft  | Comfort Curve Keyboard 20... | 62    | usbhid     | F82FCD2051 |
| 1d57:fa60 | Xenta      | 2.4G Receiver                | 62    | usbhid     | E60C730AE2 |
| 1c4f:0016 | SiGma M... | USB Keyboard                 | 61    | usbhid     | 6EC2CBBEF3 |
| 09da:f613 | A4Tech     | USB Device                   | 58    | usbhid     | C06920EDAE |
| 17ef:602d | Lenovo     | Black Silk USB Keyboard      | 58    | usbhid     | 3D2FB01EE4 |
| 2a7a:9a18 | CASUE      | USB Keyboard                 | 58    | usbhid     | 3E65C0157C |
| 03f0:034a | Hewlett... | Elite Keyboard               | 57    | usbhid     | 45D2F79356 |
| 0566:3107 | Montere... | Keyboard                     | 57    | usbhid     | 1F2CC192F8 |
| 0458:0708 | KYE Sys... | Multimedia Keyboard          | 56    | usbhid     | 64266B67A2 |
| 0a81:0101 | Chesen ... | Keyboard                     | 56    | usbhid     | 1D2014DD53 |
| 062a:5918 | MosArt ... | 2.4G Keyboard Mouse          | 55    | usbhid     | 7C2A18E726 |
| 03f0:a407 | Hewlett... | Wireless Optical Comfort ... | 54    | usbhid     | 18F9503086 |
| 413c:2106 | Dell       | Dell QuietKey Keyboard       | 54    | usbhid     | 4D1157B020 |
| 046a:0023 | Cherry     | CyMotion Master Linux Key... | 52    | usbhid     | 98395B298B |
| 0b38:0010 | Gear Head  | 107-Key Keyboard             | 52    | usbhid     | 46CBFD5EE9 |
| 04f2:0402 | Chicony... | Genius LuxeMate i200 Keyb... | 50    | usbhid     | 56BA5D2A72 |
| 0557:2419 | ATEN In... | Generic USB Mouse            | 49    | usbhid     | E5DA683598 |
| 0603:00f2 | Novatek... | Keyboard (Labtec Ultra Fl... | 49    | usbhid     | A28B80D89C |
| 04f2:0116 | Chicony... | KU-2971/KU-0325 Keyboard     | 48    | usbhid     | 1081E64E2C |
| 09da:9033 | A4Tech     | X-718BK Optical Mouse        | 48    | usbhid     | 5BA4EDF60F |
| 1ea7:0066 | SHARKOO... | [Mediatrack Edge Mini Key... | 47    | usbhid     | 34DC7B3038 |
| 09da:90a0 | A4Tech     | USB Device                   | 46    | usbhid     | 5759D12C82 |
| 3938:1032 | MOSART ... | 2.4G RF Keyboard & Mouse     | 45    | usbhid     | B3BE7A7A95 |
| 413c:8505 | Dell       | Universal Receiver           | 45    | usbhid     | 593246FB00 |
| 046d:c316 | Logitech   | HID-Compliant Keyboard       | 44    | usbhid     | DC3EC7E210 |
| 04fc:05d8 | Sunplus... | Wireless keyboard/mouse      | 44    | usbhid     | EBF0A97D73 |
| 1a2c:4c5e | China R... | USB Keyboard                 | 44    | usbhid     | B301762DE6 |
| 045e:0800 | Microsoft  | Microsoft Nano Transceive... | 43    | usbhid     | FFBFB70794 |
| 045e:07b9 | Microsoft  | Wired Keyboard 200           | 42    | usbhid     | A056C6C7D5 |
| 062a:4182 | MosArt ... | 2.4G Keyboard Mouse          | 40    | usbhid     | B0FCF85E0D |
| 413c:2010 | Dell       | Keyboard                     | 40    | usbhid     | 655547B351 |
| 062a:4c01 | MosArt ... | 2.4G Keyboard Mouse          | 39    | usbhid     | 9CF4B12D12 |
| 1241:1503 | Belkin     | Keyboard                     | 39    | usbhid     | E13730F188 |
| 413c:2105 | Dell       | Model L100 Keyboard          | 39    | usbhid     | 0BC668FE41 |
| 040b:2013 | Weltren... | 2.4G Wireless Keyboard&Mouse | 38    | usbhid     | 62D8472DD6 |
| 13ba:0018 | PCPlay     | Barcode PCP-BCG4209          | 38    | usbhid     | 18B3D6D2B3 |
| 413c:8161 | Dell       | Integrated Keyboard          | 38    | usbhid     | D5FEC65DF9 |
| 045e:07a5 | Microsoft  | 2.4GHz Transceiver v9.0      | 37    | usbhid     | F30B5E8075 |
| 05ac:0221 | Apple      | Aluminum Keyboard (ISO)      | 37    | usbhid     | FA300CEB06 |
| 0603:0002 | Novatek... | USB Composite Device         | 37    | usbhid     | E13730F188 |
| 1ea7:0002 | SHARKOO... | Trust Wireless Keyboard &... | 37    | usbhid     | 3ACB153D5D |
| 25a7:fa61 | Compx      | 2.4G Receiver                | 37    | usbhid     | AEA4DE6DD1 |
| 0e8f:00a5 | GreenAsia  | 2.4G RX                      | 36    | usbhid     | 9928EAEA06 |
| 28de:1142 | Valve S... | Wireless Steam Controller    | 36    | usbhid     | 215C5E6F2A |

### Input/mouse (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 093a:2510 | Pixart ... | Optical Mouse                | 1467  | usbhid     | 13AF031E5E |
| 046d:c52f | Logitech   | Unifying Receiver            | 1194  | usbhid     | DF25B03899 |
| 0458:003a | KYE Sys... | NetScroll+ Mini Traveler ... | 1107  | usbhid     | 53D2EF8D02 |
| 046d:c077 | Logitech   | M105 Optical Mouse           | 838   | usbhid     | 3C504F06A2 |
| 046d:c05a | Logitech   | M90/M100 Optical Mouse       | 673   | usbhid     | A36FC6A447 |
| 09da:000a | A4Tech     | Optical Mouse Opto 510D /... | 598   | usbhid     | 4015843475 |
| 275d:0ba6 |            | USB OPTICAL MOUSE            | 495   | usbhid     | 073EE0D8BC |
| 0000:0538 |            | USB OPTICAL MOUSE            | 487   | usbhid     | 5986AA0AAC |
| 1bcf:0005 | Sunplus... | USB Optical Mouse            | 387   | usbhid     | 8F2ECB882C |
| 1c4f:0034 | SiGma M... | Usb Mouse                    | 383   | usbhid     | D5082D8C3F |
| 093a:2521 | Pixart ... | Optical Mouse                | 365   | usbhid     | B470E45C2C |
| 1ea7:0064 | SHARKOO... | 2.4G Wireless Mouse          | 341   | usbhid     | A56D8D1C28 |
| 09da:c10a | A4Tech     | USB Mouse                    | 273   | usbhid     | 442F0D1A5A |
| 248a:8367 | Maxxter    | SVEN Comfort 3400 Wireless   | 251   | usbhid     | E26638D750 |
| 062a:4102 | MosArt ... | 2.4G Wireless Mouse          | 241   | usbhid     | 32D2083BB0 |
| 046d:c05b | Logitech   | M-U0004 810-001317 [B110 ... | 231   | usbhid     | E6D57EFB25 |
| 10c4:8105 | Cygnal ... | USB OPTICAL MOUSE            | 210   | usbhid     | 007691F448 |
| 18f8:0f97 | [Maxxter]  | USB OPTICAL MOUSE            | 194   | usbhid     | 988B0D9458 |
| 046d:c050 | Logitech   | RX 250 Optical Mouse         | 193   | usbhid     | 4EF902306F |
| 248a:8366 | Maxxter    | Wireless Optical Mouse AC... | 184   | usbhid     | A14B78EF65 |
| 046d:c016 | Logitech   | Optical Wheel Mouse          | 166   | usbhid     | C0D7396586 |
| 1a2c:0042 | China R... | Usb Mouse                    | 162   | usbhid     | DE19DEDDB6 |
| 045e:00cb | Microsoft  | Basic Optical Mouse v2.0     | 159   | usbhid     | 4AA0EF1314 |
| 15d9:0a4f | Trust I... | Optical Mouse                | 158   | usbhid     | C7F7A6189C |
| 1bcf:0007 | Sunplus... | Optical Mouse                | 151   | usbhid     | 60EC6F52F9 |
| 046d:c018 | Logitech   | Optical Wheel Mouse          | 146   | usbhid     | 704C328C67 |
| 0101:0007 |            | USB OPTICAL MOUSE            | 139   | usbhid     | 366E5CAC3F |
| 2188:0ae1 | CalDigit   | USB OPTICAL MOUSE            | 124   | usbhid     | 9214D5AED4 |
| 25a7:fa23 | Compx      | 2.4G Receiver                | 123   | usbhid     | CCC2EA91E1 |
| 13ee:0001 | MosArt     | Optical Mouse                | 121   | usbhid     | E1DE6C6DC3 |
| 045e:0040 | Microsoft  | Wheel Mouse Optical          | 117   | usbhid     | D6813FBC7C |
| 046d:c03e | Logitech   | Premium Optical Wheel Mou... | 117   | usbhid     | A95D4AC608 |
| 046d:c062 | Logitech   | M-UAS144 [LS1 Laser Mouse]   | 114   | usbhid     | DC3EC7E210 |
| 0e8f:00fb | GreenAsia  | USB Mouse                    | 110   | usbhid     | 8DF8DAD46F |
| 04f3:0235 | Elan Mi... | Optical Mouse                | 105   | usbhid     | 984F33EE01 |
| 046d:c00e | Logitech   | M-BJ58/M-BJ69 Optical Whe... | 104   | usbhid     | E8194FE27B |
| 3938:1031 | MOSART ... | 2.4G Wireless Mouse          | 104   | usbhid     | 26E9910108 |
| 192f:0916 | Avago T... | USB Optical Mouse            | 102   | usbhid     | 65B1EB0CA1 |
| 413c:301a | Dell       | MS116 USB Optical Mouse      | 101   | usbhid     | A17808DA56 |
| 18f8:0f99 | [Maxxter]  | Optical gaming mouse         | 97    | usbhid     | D043FCBC96 |
| 04b4:0060 | Cypress... | Wireless optical mouse       | 95    | usbhid     | AF47B62F54 |
| 0000:3825 |            | USB OPTICAL MOUSE            | 94    | usbhid     | 64EDCECFF8 |
| 046d:c069 | Logitech   | M-U0007 [Corded Mouse M500]  | 94    | usbhid     | B944521EC0 |
| 0461:4d0f | Primax ... | HP Optical Mouse             | 93    | usbhid     | 1D2014DD53 |
| 15d9:0a4d | Trust I... | Optical Mouse                | 93    | usbhid     | B51C7D1EE8 |
| 0a5c:4503 | Broadcom   | Mouse (Boot Interface Sub... | 92    | usbhid     | A8A928ED59 |
| 276d:1160 | YSTEK      | G Mouse                      | 90    | usbhid     | 47B10CD4F1 |
| 0458:0186 | KYE Sys... | Wired Mouse                  | 89    | usbhid     | 9CBD6C2E0E |
| 17ef:6019 | Lenovo     | Lenovo USB Optical Mouse     | 87    | usbhid     | CE47638461 |
| 248a:8514 | Maxxter    | Wireless Receiver            | 85    | usbhid     | A3F9F98355 |
| 09da:8090 | A4Tech     | X-718BK Oscar Optical Gam... | 79    | usbhid     | E40B76E473 |
| 1c4f:0003 | SiGma M... | HID controller               | 78    | usbhid     | 1F99995749 |
| 093a:2516 | Pixart ... | USB OPTICAL MOUSE            | 70    | usbhid     | 9084C70732 |
| 045e:0083 | Microsoft  | Basic Optical Mouse          | 69    | usbhid     | 320DDE739D |
| 15d9:0a4c | Trust I... | USB+PS/2 Optical Mouse       | 65    | usbhid     | 7052A98F3B |
| 04b4:0033 | Cypress... | Mouse                        | 64    | usbhid     | 13ACEC4985 |
| 279e:024e | 2.4G wi... | 2.4G wireless USB Device     | 63    | usbhid     | ECACED6F64 |
| 1d57:0008 | Xenta      | 2.4G Wireless Optical Mouse  | 61    | usbhid     | C569ED25EF |
| 046d:c06c | Logitech   | Optical Mouse                | 60    | usbhid     | 92DDA5BB91 |
| 046d:c408 | Logitech   | Marble Mouse (4-button)      | 59    | usbhid     | 98E4EFCCB2 |
| 09da:000e | A4Tech     | X-F710F Optical Mouse 3xF... | 59    | usbhid     | F6827302F3 |
| 04d9:a09f | Holtek ... | E-Signal LUOM G10 Mechani... | 57    | usbhid     | D32464D841 |
| 192f:0416 | Avago T... | ADNS-5700 Optical Mouse C... | 57    | usbhid     | 901A69EDCC |
| 045e:0084 | Microsoft  | Basic Optical Mouse          | 55    | usbhid     | 38CC600543 |
| 04d9:0499 | Holtek ... | Optical Mouse                | 55    | usbhid     | 47A635ACC1 |
| 046d:c084 | Logitech   | G102 Prodigy Gaming Mouse    | 54    | usbhid     | B99A6015C7 |
| 03f0:094a | Hewlett... | Optical Mouse [672662-001]   | 50    | usbhid     | 7EA80B167D |
| 03f0:134a | Hewlett... | Optical Mouse                | 50    | usbhid     | D54DC05BEB |
| 046d:c246 | Logitech   | Gaming Mouse G300            | 50    | usbhid     | AB555162C8 |
| 04b3:310c | IBM        | Wheel Mouse                  | 50    | usbhid     | 1081E64E2C |
| 10c4:8108 | Cygnal ... | USB OPTICAL MOUSE            | 50    | usbhid     | 65DCADAC42 |
| 1c4f:0032 | SiGma M... | Usb Mouse                    | 50    | usbhid     | 8230399CC0 |
| 09da:0006 | A4Tech     | Optical Mouse WOP-35 / Tr... | 49    | usbhid     | 36384227BA |
| 045e:0797 | Microsoft  | Optical Mouse 200            | 48    | usbhid     | A056C6C7D5 |
| 045e:0039 | Microsoft  | IntelliMouse Optical         | 47    | usbhid     | A86EF1E6D5 |
| 046d:c045 | Logitech   | Optical Mouse                | 47    | usbhid     | A3871B3E32 |
| 275d:0a29 |            | USB OPTICAL MOUSE            | 47    | usbhid     | 678C4A37DA |
| 046d:c019 | Logitech   | Optical Tilt Wheel Mouse     | 46    | usbhid     | 1F32728DC2 |
| 046d:c51b | Logitech   | V220 Cordless Optical Mou... | 46    | usbhid     | 0F6F76F8A1 |
| 046d:c526 | Logitech   | Nano Receiver                | 45    | usbhid     | 6C6668A1A5 |
| 09da:0080 | A4Tech     | USB Mouse                    | 45    | usbhid     | BA096189BC |
| 17ef:602e | Lenovo     | USB Optical Mouse            | 45    | usbhid     | D85B25CD22 |
| 1d57:0001 | Xenta      | wireless device              | 45    | usbhid     | AAEBB44C17 |
| 24ae:1100 | RAPOO      | 2.4G Wireless Device         | 45    | usbhid     | 01F5E9CD57 |
| 1bcf:0002 | Sunplus... | USB Optical Wheel Mouse      | 44    | usbhid     | CED3C3C6BB |
| 04f3:0234 | Elan Mi... | Optical Mouse                | 43    | usbhid     | 4E93B3E62B |
| 0458:002e | KYE Sys... | NetScroll + Traveler / Ne... | 42    | usbhid     | 984156A325 |
| 046d:c332 | Logitech   | G502 Proteus Spectrum Opt... | 42    | usbhid     | 926A3919E3 |
| 0461:4d64 | Primax ... | USB Optical Mouse            | 41    | usbhid     | E795735D5B |
| 046d:c040 | Logitech   | Corded Tilt-Wheel Mouse      | 41    | usbhid     | BCF0EBFEDD |
| 1a2c:0044 | China R... | Usb Mouse                    | 41    | usbhid     | A410481B3F |
| 046d:c537 | Logitech   | USB Receiver                 | 39    | usbhid     | 345BBA3C1F |
| 04fc:05da | Sunplus... | SPEEDLINK SNAPPY Wireless... | 39    | usbhid     | 3EDA8059EE |
| 17ef:608d | Lenovo     | lenovo USB Optical Mouse     | 39    | usbhid     | 4DB132BB33 |
| 413c:3012 | Dell       | Optical Wheel Mouse          | 39    | usbhid     | 1F04FD556B |
| 413c:8162 | Dell       | Integrated Touchpad [Syna... | 38    | usbhid     | D5FEC65DF9 |
| 0461:4e22 | Primax ... | USB Optical Mouse            | 37    | usbhid     | 779B6B3344 |
| 046d:c521 | Logitech   | Cordless Mouse Receiver      | 37    | usbhid     | 40061999CC |
| 04f2:0939 | Chicony... | USB Optical Mouse            | 37    | usbhid     | 19ABB6C0FB |
| 3938:1080 | YK         | 2.4G Wireless Device         | 37    | usbhid     | 75D510C6D7 |

### Isdn adapter (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| ffff:ffff | RAPOO      | AVM FRITZ!Card PCMCIA        | 6     | usbhid     | 44539B5FA6 |

### Joystick (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 068e:00f2 | CH Prod... | Flight Sim Pedals            | 3     | usbhid     | 803350A260 |
| 231d:1105 | www.vkb... | GTX Throttle                 | 3     | usbhid     | 417453E269 |
| 24c6:581a | Unknown... | XB1 Classic controller       | 3     | xpad       | 87B482DE1D |
| 046d:c262 | Logitech   | G920 Driving Force Racing... | 2     | usbhid     | 13D4BA319E |
| 07b5:0317 | Mega Wo... | USB Game Controllers         | 2     | usbhid     | E03A8C0C89 |
| 20bc:5500 | SHANWAN    | Android Gamepad              | 2     | usbhid     | 491DB7C6BD |
| 0079:189c | DragonRise | PXN-V3II                     | 1     | xpad       | D90F3585DA |
| 045e:000e | Microsoft  | SideWinder Freestyle Pro     | 1     | usbhid     | 9531621804 |
| 068e:00f3 | CH Prod... | Fighterstick                 | 1     | usbhid     | CB2AAA3EDB |
| 06a3:0109 | Saitek     | P880 Pad                     | 1     | usbhid     | B9165D8EE1 |
| 0e6f:0119 | Logic3     | MW3 Wireless Controller f... | 1     | usbhid     | 2933DDC278 |
| 0e6f:02c6 | Logic3     | PDP Deluxe Wired Controll... | 1     | xpad       | 0FAF3BCE11 |
| 11ff:001b |            | PXN-9613                     | 1     | usbhid     | C23CA49E1E |
| 11ff:001c |            | PXN-V3II                     | 1     | usbhid     | D1DED92F20 |
| 145f:01bb | Trust      | Gamepad                      | 1     | usbhid     | 708CD13E0A |
| 20d6:ca6d | Unknown... | Pro Ex                       | 1     | usbhid     | 0E26792709 |
| 28de:1102 | Valve S... | Wired Controller             | 1     | usbhid     | 6DE2802483 |

### Mfp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:042a | Hewlett... | LaserJet M1132 MFP           | 28    | usblp      | 079C504F7C |
| 03f0:3b17 | Hewlett... | LaserJet M1005 MFP           | 24    | usblp      | 136395C194 |
| 03f0:222a | Hewlett... | LaserJet Pro MFP M125rnw     | 19    | usblp      | C897C33BBA |
| 03f0:5617 | Hewlett... | LaserJet M1120 MFP           | 12    | usblp      | 44917A35A9 |
| 0924:3cef | Xerox      | Phaser 3100MFP               | 11    | usblp      | 3B024E0CB3 |
| 04b8:083f | Seiko E... | Stylus CX4300/CX4400/CX55... | 10    | usblp      | 3418011C79 |
| 0924:42af | Xerox      | WorkCentre 3045B             | 9     | usblp      | 4E86FFF7EA |
| 03f0:052a | Hewlett... | LaserJet Professional M12... | 8     | usblp      | 4D53809886 |
| 03f0:622a | Hewlett... | LaserJet MFP M129-M134       | 7     | usblp      | 54DD716B9D |
| 03f0:5717 | Hewlett... | LaserJet M1120n MFP          | 6     | usblp      | 6697D98216 |
| 04b8:082f | Seiko E... | PX-A620 [Stylus CX3900/DX... | 5     | usblp      | B43982A156 |
| 04b8:084d | Seiko E... | PX-402A [Stylus SX115/Sty... | 5     | usblp      | 105F0DC109 |
| 03f0:3b2a | Hewlett... | Color LaserJet MFP M277dw    | 4     | usblp      | 240876777B |
| 0482:0495 | Kyocera    | FS-1020MFP                   | 4     | usblp      | DCFF794CD3 |
| 03f0:062a | Hewlett... | LaserJet 100 colorMFP M175a  | 3     | usblp      | A3BBB7F8A9 |
| 0482:0497 | Kyocera    | FS-1025MFP                   | 3     | usblp      | 442642A23C |
| 04b8:080e | Seiko E... | PX-A550 [CX-3500/3600/365... | 3     | usblp      | 1AB6F30041 |
| 04b8:0841 | Seiko E... | PX-401A [ME 300/Stylus NX... | 3     | usblp      | 20788C640E |
| 0924:3d6f | Xerox      | WorkCentre 6605DN            | 3     | usblp      | 79A097BF6F |
| 03f0:142a | Hewlett... | LaserJet 400 MFP M425dn      | 2     | usblp      | C496949B2E |
| 03f0:242a | Hewlett... | Color LaserJet Pro MFP M176n | 2     | usblp      | 84E202DB45 |
| 03f0:2d2a | Hewlett... | LaserJet Pro MFP M225dw      | 2     | usblp      | CAC97D7EB8 |
| 0924:42c4 | Xerox      | WorkCentre 3615              | 2     | usblp      | 0BF7A6E91D |
| 0924:42da | Xerox      | WorkCentre 3025              | 2     | usblp      | 70F28E74B9 |
| 0924:42db | Xerox      | WorkCentre 3215              | 2     | usblp      | 9D7BDB2727 |
| 03f0:012a | Hewlett... | LaserJet M1536dnf MFP        | 1     | usblp      | 7671A123ED |
| 03f0:1d2a | Hewlett... | Color LaserJet flow MFP M880 | 1     | usblp      | 9F2622FF85 |
| 03f0:252a | Hewlett... | LaserJet 500 colorMFP M570dw | 1     | usblp      | 8EA70251FB |
| 03f0:2e2a | Hewlett... | LaserJet Pro MFP M435nw      | 1     | usblp      | A457D54FAD |
| 03f0:322a | Hewlett... | LaserJet Pro MFP M127fn      | 1     | usblp      | 35F08E0E86 |
| 03f0:362a | Hewlett... | Officejet Color FlowMFP X585 | 1     | usblp      | 4966DF06F4 |
| 03f0:442a | Hewlett... | Color LaserJet Flow MFP M680 | 1     | usblp      | BF4C79032E |
| 03f0:532a | Hewlett... | LaserJet MFP M426dw          | 1     | usblp      | 93A67E4976 |
| 03f0:5a2a | Hewlett... | LaserJet MFP M426fdw         | 1     | usblp      | 2FB769F3C1 |
| 03f0:932a | Hewlett... | LaserJet Pro MFP M26nw       | 1     | usblp      | 30B096BF35 |
| 03f0:9e17 | Hewlett... | LaserJet 500 MFP M525        | 1     | usblp      | 80E0F6373A |
| 03f0:9f17 | Hewlett... | LaserJet 500 color MFP M575  | 1     | usblp      | A043EA04EA |
| 03f0:bf2a | Hewlett... | LaserJet MFP M28-M31         | 1     | usblp      | 7C26C8530E |
| 04b8:0818 | Seiko E... | Stylus CX3700/CX3800/DX3800  | 1     | usblp      | 25B3B9DEBA |
| 0924:3d6b | Xerox      | WorkCentre 6505DN            | 1     | usblp      | 66BC368A83 |
| 0924:42d4 | Xerox      | WorkCentre 6027              | 1     | usblp      | E363684B4B |
| 0924:42dc | Xerox      | WorkCentre 3225              | 1     | usblp      | 8ABC3D5F35 |
| 413c:564e | Dell       | C2665dnf Color MFP           | 1     | usblp      | 70493B615B |
| 413c:590b | Dell       | MFP                          | 1     | usblp      | 0F4BBAE4FA |

### Modem (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 12d1:1506 | Huawei ... | E398 LTE/UMTS/GSM Modem/N... | 337   | uas, us... | E407354B88 |
| 12d1:1436 | Huawei ... | E173 3G Modem (modem-mode)   | 42    | usb_sto... | 44726EA287 |
| 0bdb:1911 | Ericsso... | F5521gw                      | 37    | cdc_acm    | B6BD03FB53 |
| 27c6:5395 | HTMicro... | Goodix Fingerprint Device    | 31    | cdc_acm    | 18DC19F3EC |
| 0bdb:1926 | Ericsso... | H5321 gw Mobile Broadband... | 28    | cdc_acm    | 4433C4AB4E |
| 12d1:1001 | Huawei ... | E161/E169/E620/E800 HSDPA... | 28    | usb_sto... | 6F8237E870 |
| 27c6:5301 | HTMicro... | Goodix Fingerprint Device    | 27    | cdc_acm    | 5CD9AAC635 |
| 12d1:140c | Huawei ... | E180v                        | 23    | usb_sto... | 9A0C8FB6A2 |
| 12d1:1003 | Huawei ... | E220 HSDPA Modem / E230/E... | 22    | usb_sto... | D0B36608B4 |
| 0bdb:1900 | Ericsso... | F3507g Mobile Broadband M... | 19    | cdc_acm    | 7AD5A75B0A |
| 03f0:3a1d | Hewlett... | hs2340 HSPA+ mobile broad... | 18    | cdc_acm    | 6D298DA4A5 |
| 0bdb:193e | Ericsso... | N5321 gw                     | 18    | cdc_acm    | 2E36EF3205 |
| 03f0:3d1d | Hewlett... | hs2350 HSPA+ MobileBroadband | 17    | cdc_acm    | 57308077EE |
| 2341:0043 | Arduino SA | Uno R3 (CDC ACM)             | 15    | cdc_acm    | BFCE40AEA0 |
| 27c6:5385 | HTMicro... | Goodix Fingerprint Device    | 15    | cdc_acm    | 02009E3788 |
| 413c:8147 | Dell       | F3507g Mobile Broadband M... | 12    | cdc_acm    | EBB7E1B084 |
| 413c:818d | Dell       | DW5550                       | 12    | cdc_acm    | 5051F637C0 |
| 413c:818e | Dell       | Dell Wireless 5560 Single... | 11    | cdc_acm    | C87C3F181E |
| 0658:0200 | Sigma D... | Aeotec Z-Stick Gen5 (ZW09... | 8     | cdc_acm    | BA6884F66B |
| 12d1:1404 | Huawei ... | EM770W miniPCI WCDMA Modem   | 8     | usb_sto... | 2BE5D91B09 |
| 413c:8184 | Dell       | F3607gw v2 Mobile Broadba... | 7     | cdc_acm    | 1C9F512B78 |
| 12d1:14ac | Huawei ... | HUAWEI Mobile                | 6     | option     | 167B3FD913 |
| 1546:01a7 | U-Blox     | u-blox 7 - GPS/GNSS Receiver | 6     | cdc_acm    | 8C6609B568 |
| 27c6:5381 | HTMicro... | Goodix Fingerprint Device    | 6     | cdc_acm    | 1742540BC9 |
| 04d8:00df | Microch... | MCP2200 USB Serial Port E... | 5     | cdc_acm    | 11473758BD |
| 04e8:6872 | Samsung... | Kiera                        | 5     | cdc_acm    | EBCFDCE11A |
| 1546:01a5 | U-Blox     | [u-blox 5]                   | 5     | cdc_acm    | C2D9EFD034 |
| 19d2:1515 | ZTE WCD... | MF192                        | 5     | cdc_acm    | 3C75190E68 |
| 0bdb:190a | Ericsso... | F3307 Mobile Broadband Mo... | 4     | cdc_acm    | DA5EB48DBB |
| 12d1:1570 | Huawei ... | Mobile Broadband Module      | 4     | option     | 764B8DF89D |
| 1edf:6004 | Select ... | MCD-640S-1EDF-6004           | 4     | cdc_acm    | F9D3A09989 |
| 0e8d:0003 | MediaTek   | MT6227 phone                 | 3     | cdc_acm... | 1AE1144336 |
| 12d1:1c1e | Huawei ... | Mass Storage                 | 3     | uas, us... | DDD57927D5 |
| 1519:0020 | Comneon    | HSIC Device                  | 3     | cdc_acm    | E277646CEF |
| 8087:0ab6 | Intel      | UDOO X86                     | 3     | cdc_acm    | AF7921E479 |
| 0421:0302 | Nokia M... | N8-00                        | 2     | cdc_acm    | 495FCF02B1 |
| 0483:5740 | STMicro... | STM32F407                    | 2     | cdc_acm    | 229BA614EC |
| 04e2:1410 | Exar       | XR21V1410 USB-UART IC        | 2     | cdc_acm... | 44204F310C |
| 0baf:00ec | U.S. Ro... | 56K Faxmodem                 | 2     |            | EF974030B3 |
| 0bdb:190d | Ericsso... | F5521gw                      | 2     | cdc_acm    | 460DA2DCE7 |
| 1004:6169 | LG Elec... | LGE Modem                    | 2     | cdc_ether  | D2599D1470 |
| 106c:3714 | Curitel... | PANTECH USB MODEM [UM175]    | 2     | cdc_acm    | 93E38006D9 |
| 106c:3716 | Curitel... | UMW190 Modem                 | 2     | cdc_acm    | 06FBB87A4E |
| 12d1:1573 | Huawei ... | Mobile                       | 2     | option     | 3522F1F23C |
| 2341:0001 | Arduino SA | Uno (CDC ACM)                | 2     | cdc_acm    | 071F922873 |
| 2341:0042 | Arduino SA | Mega 2560 R3 (CDC ACM)       | 2     | cdc_acm    | E3CFB6B7E6 |
| 2548:1002 | Pulse-E... | USB-CEC Adapter              | 2     | cdc_acm    | B307AE54D9 |
| 03f0:2f1d | Hewlett... | lc2010 Mobile Broadband M... | 1     | cdc_acm    | 34C71843B7 |
| 0421:01d0 | Nokia M... | E52                          | 1     | cdc_acm    | D649B2DEB3 |
| 0421:0223 | Nokia M... | E72-1                        | 1     | cdc_acm    | A913DFEFEE |
| 0421:026c | Nokia M... | N97 (PC Suite)               | 1     | cdc_acm    | 11D0F0433C |
| 0421:0348 | Nokia M... | Nokia 5228                   | 1     | cdc_acm    | 4F7EEE94F1 |
| 0421:0355 | Nokia M... | Nokia X2-00                  | 1     | cdc_acm    | 1F5E6B026B |
| 0421:0360 | Nokia M... | C1-01 Ovi Suite Mode         | 1     | cdc_acm    | 9C2894BEA0 |
| 0421:0524 | Nokia M... | Nokia 300                    | 1     | cdc_acm    | B96E92098E |
| 0421:05fd | Nokia M... | 202                          | 1     | cdc_acm    | 1A8A955A5B |
| 0421:0623 | Nokia M... | Nokia Datacard               | 1     | cdc_acm    | F35C4CAA2B |
| 0421:0638 | Nokia M... | Nokia USB Modem              | 1     | cdc_acm    | 2D146B746C |
| 0421:0664 | Nokia M... | Nokia 301 Dual SIM           | 1     | cdc_acm    | 17752ECF0C |
| 0451:16a8 | Texas I... | TI CC2531 USB CDC            | 1     | cdc_acm    | D4224E0573 |
| 0461:0033 | Primax ... | USB_Focus                    | 1     | cdc_acm    | 5278A91530 |
| 04d8:000a | Microch... | CDC RS-232 Emulation Demo    | 1     | cdc_acm    | 2A902BCD5E |
| 04d8:fd5e | Microch... | VeRSis                       | 1     | cdc_acm    | AF6FC8545B |
| 04e8:6601 | Samsung... | Mobile Phone                 | 1     | visor, ... | 25239307A1 |
| 04e8:6773 | Samsung... | HSPA Modem                   | 1     | cdc_acm    | 06B0B62AAC |
| 04e8:6843 | Samsung... | E2530 Phone (Samsung Kies... | 1     | cdc_acm    | 55075885CA |
| 04e8:6845 | Samsung... | Mobile USB Modem             | 1     | cdc_acm    | 01619C75A2 |
| 04e8:6862 | Samsung... | Android                      | 1     | cdc_acm    | 0E1F45AE13 |
| 0572:1328 | Conexan... | TrendNet TFM-561 modem       | 1     | cdc_acm    | 678C383DB7 |
| 0572:1329 | Conexan... | USB Modem                    | 1     | cdc_acm    | 7A44DA1E2F |
| 0572:cb16 | Conexan... | USB-ADSL Modem               | 1     |            | 07217A2477 |
| 067b:2323 | Prolifi... | 123_AaP                      | 1     | cdc_acm    | D9A29354A7 |
| 079b:0028 | Sagem      | Modem                        | 1     | cdc_acm    | 48A3B0ECA9 |
| 0930:1314 | Toshiba    | F5521gw                      | 1     | cdc_acm    | 6F44CBE917 |
| 0930:1319 | Toshiba    | H5321gw                      | 1     | cdc_acm    | 68749635C1 |
| 0ace:1608 | ZyDAS      | ZyXEL Omni FaxModem 56K UNO  | 1     | cdc_acm    | 3489DBD51A |
| 0b1b:0109 | Linux 3... | Gadget Serial v2.4           | 1     | cdc_acm    | B7E5888FFE |
| 0bdb:1902 | Ericsso... | F3507g v2 Mobile Broadban... | 1     | cdc_acm    | 211BE91D80 |
| 0bdb:1905 | Ericsso... | F3607gw v2 Mobile Broadba... | 1     | cdc_acm    | 26A4676050 |
| 0bf1:0002 | Intracom   | netMod Driver Ver 2.4 (CAPI) | 1     | cdc_acm    | 9DDAB18C28 |
| 0e8d:2011 | MediaTek   | PassPlus                     | 1     | cdc_acm    | 83BFA1527C |
| 1004:61f2 | LG Elec... | LGE Android phone            | 1     | cdc_acm    | 4273247882 |
| 1209:1776 | InterBi... | Io                           | 1     | system7... | ECC26A9233 |
| 12d1:1465 | Huawei ... | K3765 HSPA                   | 1     | option     | 346F4EA91D |
| 12d1:151d | Huawei ... | Mass Storage                 | 1     | uas, us... | 304AA59840 |
| 12d1:1566 | Huawei ... | HUAWEI_MOBILE                | 1     | option     | B07034F89E |
| 16c0:05e1 | Van Ooi... | Free shared USB VID/PID p... | 1     | cdc_acm    | C7A9B4C273 |
| 17ef:7499 | Lenovo     | K3                           | 1     | cdc_acm    | 2030142A09 |
| 18d1:d012 | Google     | Android                      | 1     | rndis_host | 14C479036B |
| 19d2:0579 | ZTE WCD... | ZXIC Mobile Boardband        | 1     | rndis_host | F00E135A18 |
| 1bbb:2011 | T & A M... | ALCATEL ONETOUCH POP 3 (5.5) | 1     | cdc_acm    | 03EBD4DBF1 |
| 1c11:b04d | Input Club | Keyboard - WhiteFox Parti... | 1     | cdc_acm    | 7A92C75597 |
| 1d50:6086 | OpenMoko   | OneRNG entropy device        | 1     | cdc_acm    | D42C7918FD |
| 1eaf:0004 | LeafLabs   | Maple                        | 1     | cdc_acm    | B322F04446 |
| 1fc9:0083 | NXP Sem... | VCOM Port                    | 1     | cdc_acm    | AAA8608D22 |
| 1fc9:00a3 | NXP Sem... |                              | 1     | cdc_acm    | CD4CAE5343 |
| 1fc9:2002 | NXP Sem... | NXP LPC17xx VCOM             | 1     | cdc_acm    | E5901957AD |
| 20d3:0007 | Linux 2... | Gadget Serial v2.4           | 1     | cdc_acm    | 16ECB5A13F |
| 216f:0051 | Das U-Boot | U-Boot 2010.12               | 1     | cdc_acm    | BB85981F98 |
| 2184:0021 | GW Instek  | GDS-71062A                   | 1     | cdc_acm    | 26D6AB71AA |

### Net/wimax (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0180 | Intel      | WiMAX Connection 2400m       | 44    | i2400m_usb | 604780766A |
| 8086:1406 | Intel      | WiMAX Connection 2400m       | 40    | i2400m_usb | 15789D122D |
| 8086:0186 | Intel      | WiMAX Connection 2400m       | 26    | i2400m_usb | 1DE544887B |
| 8087:07d6 | Intel      | Centrino WiMAX 6150          | 14    | i2400m_usb | 2FAE738892 |
| 8086:0188 | Intel      | WiMAX Connection 2400m       | 4     | i2400m_usb | 4384225066 |
| 8086:0187 | Intel      | Centrino Advanced-N + WiM... | 1     | i2400m_usb | 922C33C259 |

### Net/wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 148f:7601 | Ralink ... | MT7601U Wireless Adapter     | 318   | mt7601u    | 5E8A739106 |
| 0bda:8179 | Realtek... | RTL8188EUS 802.11n Wirele... | 298   | r8188eu    | 9650DD9DCE |
| 0cf3:9271 | Qualcom... | AR9271 802.11n               | 267   | ath9k_htc  | ABA2A5E5E6 |
| 148f:5370 | Ralink ... | RT5370 Wireless Adapter      | 174   | rt2800usb  | 0709E8111B |
| 0bda:8178 | Realtek... | RTL8192CU 802.11n WLAN Ad... | 161   | rtl8192cu  | 522AE798B9 |
| 148f:3070 | Ralink ... | RT2870/RT3070 Wireless Ad... | 145   | rt2800usb  | F140183571 |
| 0bda:8176 | Realtek... | RTL8188CUS 802.11n WLAN A... | 101   | rtl8192cu  | 87578A05DA |
| 2357:0109 | Realtek    | RTL8192EU TL-WN823N 802.1... | 67    | rtl8xxxu   | DDF39244D2 |
| 0bda:b812 | Realtek... | RTL8812BU USB3.0 802.11ac... | 58    | 88x2bu     | B5C538F345 |
| 0bda:8189 | Realtek... | RTL8187B Wireless 802.11g... | 52    | rtl8187    | 4AB980D7C1 |
| 0bda:8172 | Realtek... | RTL8191SU 802.11n WLAN Ad... | 50    | r8712u     | 7FD884E502 |
| 2357:010c | Realtek    | RTL8188EUS TL-WN722N v2      | 43    | r8188eu    | DEDCC243D5 |
| 148f:761a | Ralink ... | MT7610U ("Archer T2U" 2.4... | 39    | mt76x0u    | 35862ADAD1 |
| 0bda:818b | Realtek... | RTL8192EU ACT-WNP-UA-005 ... | 38    | rtl8xxxu   | 7EA80B167D |
| 2001:3c20 | D-Link     | 802.11 n WLAN                | 37    | rt2800usb  | 3F3529C000 |
| 045e:0719 | Microsoft  | Xbox 360 Wireless Adapter    | 35    | xpad       | E203D0B513 |
| 0b05:17ab | ASUSTek... | USB-N13 802.11n Network A... | 35    | rtl8192cu  | 3A7D6AD8A5 |
| 148f:5572 | Ralink ... | RT5572 Wireless Adapter      | 35    | rt2800usb  | BBAA313D83 |
| 0b05:17ba | ASUSTek... | N10 Nano 802.11n Network ... | 33    | rtl8192cu  | 88BB28214D |
| 0bda:8171 | Realtek... | RTL8188SU 802.11n WLAN Ad... | 33    | r8712u     | F0971CD52C |
| 7392:7811 | Edimax ... | EW-7811Un 802.11n Wireles... | 33    | rtl8192... | 60CEE7D0B8 |
| 0bda:8812 | Realtek... | RTL8812AU 802.11a/b/g/n/a... | 32    | 8812au     | BB239C7852 |
| 0b05:1786 | ASUSTek... | USB-N10 802.11n Network A... | 30    | r8712u     | 4F7A61943D |
| 07d1:3c16 | D-Link ... | DWA-125 Wireless N 150 Ad... | 29    | rt2800usb  | 90F55C011B |
| 0846:9030 | NetGear    | WNA1100 Wireless-N 150 [A... | 28    | ath9k_htc  | B1D7110D4D |
| 148f:2573 | Ralink ... | RT2501/RT2573 Wireless Ad... | 28    | rt73usb    | BCFB5FEC5D |
| 0cf3:7015 | Qualcom... | TP-Link TL-WN821N v3 / TL... | 27    | ath9k_htc  | 3EB7EB388C |
| 148f:5372 | Ralink ... | RT5372 Wireless Adapter      | 27    | rt2800usb  | BD250445FE |
| 0bda:c811 | Realtek... | RTL8811CU 802.11ac NIC       | 26    | 8821cu     | 1F9408B984 |
| 2001:3319 | D-Link     | RTL8192EU DWA-131 Wireles... | 26    | rtl8xxxu   | B9B80DB558 |
| 0bda:a811 | Realtek... | RTL8811AU 802.11a/b/g/n/a... | 24    | rtl8812au  | E50B6BA10C |
| 0cf3:1006 | Qualcom... | TP-Link TL-WN322G v3 / TL... | 24    | ath9k_htc  | 1092EBC2BC |
| 0bda:0811 | Realtek... | RTL8811AU 802.11ac WLAN A... | 23    | rtl8812au  | D75C0B2DA5 |
| 2001:3c19 | D-Link     | DWA-125 Wireless N 150 Ad... | 22    | rt2800usb  | 0755ABE833 |
| 0bda:8197 | Realtek... | RTL8187B Wireless Adapter    | 21    | rtl8187    | FD6FC05D97 |
| 0bda:f179 | Realtek... | 802.11n                      | 20    | rtl8188fu  | 7605FC1D79 |
| 07d1:3c03 | D-Link ... | AirPlus G DWL-G122 Wirele... | 17    | rt73usb    | 0029366B0D |
| 13d3:3323 | IMC Net... | RTL8191S WLAN Adapter        | 17    | r8712u     | 97064D9748 |
| 148f:3072 | Ralink ... | RT3072 Wireless Adapter      | 17    | rt2800usb  | FDF42F20BB |
| 050d:845a | Belkin ... | F7D2101 802.11n Surf & Sh... | 16    | r8712u     | 54000CEF8B |
| 07d1:3303 | D-Link ... | DWA-131 802.11n Wireless ... | 16    | r8712u     | C5EE060717 |
| 07d1:3c07 | D-Link ... | DWA-110 Wireless G Adapte... | 15    | rt73usb    | 91AED62FEE |
| 0ace:1215 | ZyDAS      | ZD1211B 802.11g              | 15    | zd1211rw   | F265177B92 |
| 0b05:179d | ASUSTek... | USB-N53 802.11abgn Networ... | 15    | rt2800usb  | A056C6C7D5 |
| 07d1:3a10 | D-Link ... | DWA-126 802.11n Wireless ... | 14    | ath9k_htc  | 5BDF9E88E0 |
| 0b05:1791 | ASUSTek... | WL-167G v3 802.11n Adapte... | 14    | r8712u     | 24AE34F871 |
| 0b05:184c | ASUSTek... | RTL8812BU USB-AC53 Nano 8... | 14    | 88x2bu     | BA1D0F6920 |
| 148f:2870 | Ralink ... | RT2870 Wireless Adapter      | 14    | rt2800usb  | 2553EF6468 |
| 2001:3314 | D-Link     | RTL8821AU DWA-171 802.11n... | 14    | rtl8812au  | D85422E2C1 |
| 2357:0107 | Realtek    | RTL8192EU TL-WN821N Versi... | 14    | rtl8xxxu   | A3871B3E32 |
| 13d3:3306 | IMC Net... | Mediao 802.11n WLAN [Real... | 13    | r8712u     | A86EF1E6D5 |
| 148f:2070 | Ralink ... | RT2070 Wireless Adapter      | 13    | rt2800usb  | 31BD26BC3B |
| 07d1:3c0d | D-Link ... | DWA-125 Wireless N 150 Ad... | 12    | rt2800usb  | 8491772FE8 |
| 0bda:0179 | Realtek... | RTL8188ETV Wireless LAN 8... | 12    | r8188eu    | 82A50E872A |
| 15a9:0004 | Gemtek     | WUBR-177G [Ralink RT2571W]   | 12    | rt73usb    | C4A328C606 |
| 148f:3572 | Ralink ... | RT3572 Wireless Adapter      | 11    | rt2800usb  | 5EA1F0F406 |
| 050d:2103 | Belkin ... | F7D2102 802.11n N300 Micr... | 10    | rtl8192... | 889987DE67 |
| 0846:4260 | NetGear    | WG111v3 54 Mbps Wireless ... | 10    | rtl8187    | 32D5B1A614 |
| 0b05:17d1 | ASUSTek... | MT7610U AC51 802.11a/b/g/... | 10    | mt76x0u    | B612D89D47 |
| 0e8d:7610 | MediaTek   | MT7610U WiFi                 | 10    | mt7650u... | 0C42DFC62C |
| 2001:3317 | D-Link     | 802.11 n WLAN                | 10    | rt2800usb  | B815184D9D |
| 2357:010d | Realtek    | RTL8812AU TP-Link Archer ... | 10    | rtl8812au  | C0B10ED08F |
| 413c:81a3 | Dell       | Wireless 5570 HSPA+ (42Mb... | 10    | qcserial   | F06D9184CB |
| 0846:9052 | NetGear    | RTL8811AU A6100 AC600 DB ... | 9     | 8812au     | 7DB8E54DDE |
| 0db0:6877 | Micro S... | RT2573                       | 9     | rt73usb    | 9088E52FE4 |
| 2001:3c1b | D-Link     | DWA-127 Wireless N 150 Hi... | 9     | rt2800usb  | 8C45D223F8 |
| 2357:0115 | TP-Link    | 802.11ac NIC                 | 9     | 8822bu     | 1BB0C8F064 |
| 2717:4106 | MediaTek   | MI WLAN Adapter              | 9     | mt7601u    | 25987883B0 |
| 0b05:1723 | ASUSTek... | WL-167G v2 802.11g Adapte... | 8     | rt73usb    | 8996CEBF5B |
| 0bda:8198 | Realtek... | RTL8187B Wireless Adapter    | 8     | rtl8187    | C21C72FEED |
| 2357:0101 | Realtek    | RTL8812AU Archer T4U 802.... | 8     | rtl8812au  | 7F22F1C8CA |
| 050d:705a | Belkin ... | F5D7050 Wireless G Adapte... | 7     | rt73usb    | 607CDE1E46 |
| 0cf3:1002 | Qualcom... | TP-Link TL-WN821N v2 / TL... | 7     | carl9170   | 4ED3A4A663 |
| 0db0:3871 | Micro S... | MS-3871 802.11bgn Wireles... | 7     | rt2800usb  | 8868E8087F |
| 13b1:003f | Linksys    | RTL8812AU WUSB6300 802.11... | 7     | 8812au     | 92100B9B64 |
| 2001:3315 | D-Link     | RTL8812AU DWA-182 Wireles... | 7     | rtl8812au  | 1111158623 |
| 2357:0108 | TP-Link    | RTL8192EU TL-WN822N Versi... | 7     | rtl8xxxu   | 06FA41FE93 |
| 0586:341e | ZyXEL C... | NWD2105 802.11bgn Wireles... | 6     | rt2800usb  | B8931B91E5 |
| 0586:341f | ZyXEL C... | NWD2205 802.11n Wireless ... | 6     | rtl8192cu  | B79EE752B4 |
| 0846:9001 | NetGear    | WN111(v2) RangeMax Next W... | 6     | carl9170   | 5D617B8DE0 |
| 0b05:17e8 | ASUSTek... | USB-N14 802.11b/g/n (2x2)... | 6     | rt2800usb  | FDC304F1CB |
| 13b1:0020 | Linksys    | WUSB54GC v1 802.11g Adapt... | 6     | rt73usb    | A5A20E3A8D |
| 1737:0071 | Linksys    | WUSB600N v1 Dual-Band Wir... | 6     | rt2800usb  | 5B9BB1AEDB |
| 2357:0105 | MediaTek   | MT7610U Archer T1U 802.11... | 6     | mt76x0u    | E68759AA8E |
| 7392:7711 | Edimax ... | EW-7711UTn nLite Wireless... | 6     | rt2800usb  | CB4983BAF6 |
| 0586:3410 | ZyXEL C... | ZyAIR G-202 802.11bg         | 5     | zd1211rw   | BBCFFE1ECE |
| 079b:0062 | Sagem      | XG-76NA 802.11bg             | 5     | zd1211rw   | CD0F6202CB |
| 07d1:3c09 | D-Link ... | DWA-140 RangeBooster N Ad... | 5     | rt2800usb  | 3C2E5705F9 |
| 0846:9011 | NetGear    | BCM4323 WNDA3100v2 802.11... | 5     |            | 9DA498DED3 |
| 0846:9020 | NetGear    | BCM43231 WNA3100(v1) Wire... | 5     |            | 68CF43B792 |
| 0846:9021 | NetGear    | WNA3100M(v1) Wireless-N 3... | 5     | rtl8192... | 2030142A09 |
| 0b05:1784 | ASUSTek... | USB-N13 802.11n Network A... | 5     | rt2800usb  | A26BD26890 |
| 0bda:8813 | Realtek... | RTL8814AU 802.11a/b/g/n/a... | 5     |            | D32464D841 |
| 0bf8:100f | Fujitsu... | miniCard D2301 802.11bg W... | 5     |            | 40B94D516E |
| 13b1:003a | Linksys    | BCM43236 AE2500 802.11abg... | 5     |            | 913FC75AA0 |
| 148f:760b | Ralink ... | MT7601U Wireless Adapter     | 5     | mt7601u    | 10121DE278 |
| 2001:3c1a | D-Link     | DWA-160 802.11abgn Xtreme... | 5     | rt2800usb  | BFA99152B0 |
| 2357:011e | TP-Link    | 802.11ac WLAN Adapter        | 5     | 88XXau     | BBD4C79799 |
| 413c:81b1 | Dell       | Wireless 5809e Gobi 4G LT... | 5     | qcserial   | 6EDCE17255 |
| 8087:07d7 | Intel      | Centrino Wireless-N + WiM... | 5     | i2400m_usb | 89EF922929 |

### Network (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:8153 | Realtek... | RTL8153 Gigabit Ethernet ... | 144   | r8152      | D2B107774B |
| 04e8:6863 | Samsung... | GT-I9500 [Galaxy S4] / GT... | 94    | rndis_host | 17ED1F4194 |
| 19d2:1405 | ZTE WCD... | ZTE Mobile Broadband Station | 94    | cdc_ether  | C77563A5FB |
| 12d1:14db | Huawei ... | E353/E3131 34GB              | 85    | cdc_ether  | C8749F61B6 |
| 0bda:8187 | Realtek... | RTL8187 Wireless LAN Adapter | 65    | rtl8187    | 064DD1CCBF |
| 0bda:8152 | Realtek... | RTL8152 Fast Ethernet Ada... | 52    | r8152      | 79D7D4F6C4 |
| 0bda:b720 | Realtek... | RTL8723BU 802.11n WLAN Ad... | 52    | rtl8xxxu   | 97BCBB884E |
| 2717:ff80 | Android    | SDM636-MTP _SN:5F93851E      | 51    | rndis_host | 7E1E79D0B1 |
| 04e8:6864 | Samsung... | GT-I9070 (network tetheri... | 47    | rndis_host | C9C2EFF56C |
| 12d1:108a | Huawei ... | DLI-TL20                     | 42    | rndis_host | 97BCBB884E |
| 0bb4:0003 | HTC (Hi... | Android Incorporated GSM ... | 36    | rndis_host | 0E99848A09 |
| 0e8d:2004 | MediaTek   | Power Ice Evo                | 34    | rndis_host | AF9D5F2B32 |
| 0b95:1790 | ASIX El... | AX88179 Gigabit Ethernet     | 33    | ax88179... | A413F419EF |
| 2001:3c15 | D-Link     | DWA-140 RangeBooster N Ad... | 31    | rt2800usb  | 41F3167FB7 |
| 07d1:3c0a | D-Link ... | DWA-140 RangeBooster N Ad... | 30    | rt2800usb  | 5A95AD178B |
| 15a9:002d | Gemtek     | WLTUBA-107 [Yota 4G LTE]     | 28    | cdc_ether  | FA6B260BE6 |
| 0b95:772b | ASIX El... | AX88772B                     | 22    | asix       | AFE3135216 |
| 2001:330f | D-Link     | RTL8188ETV DWA-125 11n Ad... | 22    | r8188eu    | 969A371A99 |
| 22b8:2e24 | Motorol... | Moto G (4)                   | 18    | rndis_host | 71764E2EB9 |
| 046b:ffb0 | America... | Virtual Ethernet             | 17    | cdc_ether  | A14B2C7156 |
| 216f:0043 | Altair ... | Modem YOTA 4G LTE            | 17    | cdc_ether  | 2DC1AE73B8 |
| 05c6:f00e | Qualcomm   | DEXP Ixion X LTE 4.5"        | 16    | rndis_host | 74837A3467 |
| 1076:8002 | GCT Sem... | LU150 LTE Modem [Yota LU150] | 16    | rndis_host | 6999B8686F |
| 8087:0911 | Intel      | PRODUCT_MODEM                | 16    | cdc_mbim   | 0A96B79D5F |
| 0bb4:0004 | HTC (Hi... | MT65xx Android Phone         | 15    | rndis_host | EEDAAEA2D7 |
| 0846:9053 | NetGear    | A6210                        | 13    | mt76x2u    | D28ACFF1E6 |
| 0fe6:9700 | Kontron... | DM9601 Fast Ethernet Adapter | 13    | dm9601,... | 781E93AD34 |
| 1199:a001 | Sierra ... | EM7345 4G LTE                | 13    | cdc_mbim   | 14015A6CDE |
| 1bbb:0174 | T & A M... | ALCATEL ONETOUCH PIXI 3 (... | 13    | rndis_host | 22FEE5E38F |
| 2e04:c022 | MediaTek   | Android                      | 13    | rndis_host | 8111E750C1 |
| 03f0:581d | Hewlett... | lt4112 Gobi 4G Module Net... | 12    | qcserial   | F9CD4D265E |
| 0bda:1724 | Realtek... | RTL8723AU 802.11n WLAN Ad... | 12    | rtl8723au  | B1BEB13466 |
| 0e8d:2005 | MediaTek   | X5max_PRO                    | 12    | rndis_host | 6F8FD31C2C |
| 1199:9011 | Sierra ... | MC8305                       | 12    | qcserial   | 153AFABCB5 |
| 413c:81b6 | Dell       | DW5811e Snapdragon X7 LTE    | 12    | qcseria... | EC07F9B3A7 |
| 0424:ec00 | Standar... | SMSC9512/9514 Fast Ethern... | 11    | smsc95xx   | 213D7241FD |
| 03f0:9d1d | Hewlett... | lt4120 Snapdragon X5 LTE     | 10    | qmi_wwan   | BCF0EBFEDD |
| 1782:5d20 | Spreadt... | Fly Era Nano 3               | 10    | rndis_host | 3846E1FF93 |
| 19d2:1365 | ZTE WCD... | MT65xx Android Phone         | 10    | rndis_host | 20F8191625 |
| 2001:3c1e | D-Link     | 11n Adapter                  | 10    | rt2800usb  | F1FF7D2409 |
| 04b4:3610 | Cypress... | USB-C PD Docking             | 9     | ax88179... | 2D71938FC4 |
| 0b95:772a | ASIX El... | AX88772A Fast Ethernet       | 9     | asix       | CD3C0C4583 |
| 12d1:15bb | Huawei ... | ME936 LTE/HSDPA+ 4G modem    | 9     | cdc_ncm... | AE9CAC19CA |
| 17ef:7436 | Lenovo     | MT65xx Android Phone         | 9     | rndis_host | 586A6A9F8A |
| 1199:9041 | Sierra ... | EM7305                       | 8     | cdc_mbim   | CF73AE98A0 |
| 1199:9079 | Sierra ... | EM7455 Qualcomm Snapdrago... | 8     | qcseria... | 66ACB89125 |
| 17ef:3069 | Lenovo     | ThinkPad TBT3 LAN            | 8     | r8152      | CABDFDF87F |
| 2357:0601 | TP-Link    | RTL8153 TP-Link UE300 USB... | 8     | r8152      | 0DFD787765 |
| 03f0:371d | Hewlett... | un2430 Mobile Broadband M... | 7     | qcserial   | 89CC1EC47E |
| 0b95:7e2b | ASIX El... | AX88772B Fast Ethernet Co... | 7     | asix       | EA3B68E3CD |
| 1376:4e61 | Vimtron... | Mobile Composite Device Bus  | 7     | rndis_host | 9E282C1163 |
| 15a9:003e | Gemtek     | Yota Many                    | 7     | rndis_host | F48E23AB6A |
| 2001:4a00 | D-Link     | DUB-1312                     | 7     | ax88179... | 70309E8B8E |
| 2cb7:0210 | FIBOCOM    | L830-EB-00                   | 7     | cdc_acm    | 5F8373C716 |
| 04b3:4010 | IBM        | RNDIS/Ethernet Gadget        | 6     | cdc_ether  | B55F7AE6F3 |
| 0b05:5f04 | ASUSTek... | Android                      | 6     | rndis_host | 43E4578544 |
| 0bb4:0ffe | HTC (Hi... | Desire HD (modem mode)       | 6     | rndis_w... | 0886AD75BB |
| 0bda:0823 | Realtek... | 802.11ac WLAN Adapter        | 6     | btusb      | 266C08C437 |
| 1004:6344 | LG Elec... | G2 Android Phone [tetheri... | 6     | rndis_host | 8BDED60C71 |
| 17e9:436e | Display... | Dell USB3.0 Dock             | 6     | cdc_ncm    | 18DC19F3EC |
| 7392:a812 | Edimax ... | RTL8811AU AC600 USB          | 6     | rtl8812au  | 690FFF1815 |
| 045e:07c6 | Microsoft  | RTL8153 GigE [Surface Doc... | 5     | r8152      | 8132DC0ECA |
| 0489:c022 | Foxconn... | Nokia 8                      | 5     | rndis_host | 689CFCEF10 |
| 05c6:9205 | Qualcomm   | Gobi 2000                    | 5     | qmi_wwa... | 9F6EB096F3 |
| 0846:6a00 | NetGear    | WG111v2 54 Mbps Wireless ... | 5     | rtl8187    | 709C282E30 |
| 0b05:5602 | ASUSTek... | Android                      | 5     | rndis_host | 380140EB8D |
| 0b95:7720 | ASIX El... | AX88772                      | 5     | asix       | 3A512A24A7 |
| 1199:68a2 | Sierra ... | MC7710                       | 5     | qcserial   | 55E0CBBC35 |
| 12d1:14f1 | Huawei ... | Gobi 3000 HSPA+ Modem        | 5     | qcseria... | 01A4BD5E7F |
| 17e9:4307 | Display... | USB3.0 Dual Video Dock       | 5     | cdc_ncm... | A6B5F083CA |
| 17e9:6000 | Display... | USB 3.0 5K Graphic Docking   | 5     | cdc_ncm    | F2C990D6BA |
| 17ef:3062 | Lenovo     | USB-C Dock Ethernet          | 5     | r8152      | FD5A5FBD54 |
| 18d1:4ee3 | Google     | Nexus 4/5/7/10 (tether)      | 5     | rndis_host | 24792BF2AB |
| 1bbb:2026 | T & A M... | ALCATEL ONETOUCH PIXI 3 (... | 5     | cdc_eem    | A5F8220E5C |
| 2001:1a02 | D-Link     | DUB-E100 Fast Ethernet Ad... | 5     | asix       | 7537E7CB35 |
| 2001:3310 | D-Link     | DWA-123 11n Adapter          | 5     | r8188eu    | 27F823C12D |
| 2001:3c21 | D-Link     | DWA-160 Xtreme N Dual Ban... | 5     | rt2800usb  | 5BD4609615 |
| 0424:7500 | Standar... | LAN7500 Ethernet 10/100/1... | 4     | smsc75xx   | 5998E86885 |
| 0424:7800 | Standar... | Ethernet controller          | 4     | lan78xx    | 66A253B82B |
| 056a:0084 | Wacom      | Wireless adapter for Bamb... | 4     | usbhid     | D6D7F9CC30 |
| 05c6:9024 | Qualcomm   | Android                      | 4     | rndis_host | AD80176B34 |
| 1271:052a | Android    | Android                      | 4     | rndis_host | 407C4DAF14 |
| 12d1:1050 | Huawei ... | Android Adapter              | 4     | rndis_host | B2185404AA |
| 12d1:260d | Huawei ... | TIT-L01                      | 4     | rndis_host | D0B4620C9C |
| 17e9:6006 | Display... | Dell Universal Dock D6000    | 4     | cdc_ncm... | 100788F6D3 |
| 17ef:a359 | Lenovo     | ThinkPad Lan                 | 4     | cdc_ether  | 5F28B24437 |
| 2717:1280 | JSR Tech   | HM1 Android Phone            | 4     | rndis_host | 266E42DEC5 |
| 04d9:a119 | Holtek ... | OSA Express Network card     | 3     | usbhid     | 3CF95EC244 |
| 04e8:6881 | Samsung... | Android USB Device           | 3     | rndis_host | EE8B6A4998 |
| 0586:3309 | ZyXEL C... | ADSL Modem Prestige 600 s... | 3     | rndis_w... | 316CFC71D0 |
| 05ac:12ab | Apple      | iPad 4/Mini1                 | 3     | ipheth     | AB105D132E |
| 05ac:1402 | Apple      | Ethernet Adapter [A1277]     | 3     | asix       | 27D23CBDAA |
| 0a46:1269 | Davicom... | DM9621 USB To Fast Ether     | 3     | dm9601,... | B2ABBFCF51 |
| 0b95:1780 | ASIX El... | AX88178                      | 3     | asix       | 84495E0FB8 |
| 0bb4:0ee7 | HTC (Hi... | Desire 620G dual sim         | 3     | rndis_host | B03F58CC28 |
| 0fca:8017 | Researc... | BlackBerry                   | 3     | cdc_ncm... | C33C8BA4E4 |
| 0fce:7161 | Sony Er... | ST18i                        | 3     | rndis_host | 9DF4057415 |
| 1004:61da | LG Elec... | G2 Android Phone [tetheri... | 3     | rndis_host | 7FF127B585 |
| 15a9:002b | Gemtek     | Yota Many                    | 3     | rndis_host | 94A0B982A5 |
| 17e9:4306 | Display... | Targus USB3.0 DV Dock wit... | 3     | cdc_ncm    | 6C8F4AD0D7 |

### Phone (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2717:ff48 | MediaTek   | MT65xx Android Phone         | 15    | usbfs      | 8F2ECB882C |
| 18d1:4ee1 | Google     | Nexus Device (MTP)           | 13    | usbfs      | B944521EC0 |
| 1004:631c | LG Elec... | G2/Optimus Android Phone ... | 11    | usbfs      | 00103EC78E |
| 1bbb:0168 | T & A M... | ALCATEL ONETOUCH PIXI 3 (... | 11    | usbfs      | 9A42A921E7 |
| 2a45:2008 | Meizu      | MX Phone (MTP)               | 8     | usbfs      | BCF1D99475 |
| 0bb4:0c02 | HTC (Hi... | Dream / ADP1 / G1 / Magic... | 6     | uas, us... | 1C66419356 |
| 04e8:685d | Samsung... | GT-I9100 Phone [Galaxy S ... | 5     | cdc_acm    | A13B3BB6D9 |
| 0bb4:2008 | HTC (Hi... | Android Phone via MTP [Wi... | 5     |            | F03D97F38F |
| 1004:6300 | LG Elec... | G2/Optimus Android Phone ... | 5     | usbhid     | 3A3714805B |
| 17ef:7497 | Lenovo     | A789 (MTP mode)              | 4     |            | B60CD6FFC3 |
| 19d2:0307 | ZTE WCD... | Android Phone                | 4     | usbfs      | 45021EC259 |
| 04e8:685c | Samsung... | GT-I9250 Phone [Galaxy Ne... | 3     | usbfs      | FB1CD7BF88 |
| 05c6:9092 | Qualcomm   | DEXP Ixion X LTE 4.5"        | 3     |            | 0458C5593D |
| 05c6:f003 | Qualcomm   | vivo Android Phone           | 3     | usbfs      | 0D7F7B5382 |
| 0fce:01c4 | Sony Er... | Xperia M4                    | 3     | usbfs      | 06472F3D2C |
| 19d2:0306 | ZTE WCD... | MT65xx Android Phone         | 3     |            | 6AD005D6B7 |
| 2717:1240 | Xiaomi     | HM1 Android Phone            | 3     |            | 01AA74496F |
| 2916:f003 | Yota De... | YotaPhone C9660              | 3     | usbfs      | 5595625922 |
| 045e:04ec | Microsoft  | Windows Phone (Zune)         | 2     |            | D4F8B5C1D6 |
| 0471:2008 | Philips... | Android Phone                | 2     |            | D315AFD57C |
| 0bb4:0402 | HTC (Hi... | Android Phone                | 2     | rndis_host | EBBD83B0CA |
| 0bb4:0c81 | HTC (Hi... | Android Phone                | 2     |            | 404A8B3A68 |
| 0bb4:0f0b | HTC (Hi... | Android Phone                | 2     | usbhid     | 25B5BF978A |
| 0bb4:f006 | HTC (Hi... | Android Phone                | 2     | usbhid     | 36497E7C3F |
| 0fce:0189 | Sony Er... | Xperia ZL C6503              | 2     |            | 97D00825B7 |
| 0fce:019b | Sony Er... | Android Phone                | 2     |            | 49389100FC |
| 0fce:01b5 | Sony Er... | Xperia E1 D2005              | 2     |            | 165BEE2B5C |
| 0fce:51ad | Sony Er... | Android Phone                | 2     |            | 41B2D085B5 |
| 1004:61fc | LG Elec... | Optimus 3                    | 2     | cdc_acm... | 1EBB6C2E61 |
| 17ef:74f8 | Lenovo     | MT65xx Android Phone         | 2     |            | B89D04A41B |
| 0421:002f | Nokia M... | 6120 Phone (PC-Suite mode)   | 1     | cdc_acm... | 408A3116F5 |
| 0471:0003 | Philips... | Android Phone                | 1     | rndis_host | 5F5A42CFCD |
| 0b05:5490 | ASUSTek... | ZenFone                      | 1     |            | 196E542A2B |
| 0b05:551f | ASUSTek... | Android Phone                | 1     | usbfs      | E1C6C1D0DB |
| 0bb4:0df8 | HTC (Hi... | Android Phone                | 1     |            | F4F1952C9C |
| 0bb4:0fa2 | HTC (Hi... | Android Phone                | 1     | usbfs      | 5A59F3A3B4 |
| 0fce:0197 | Sony Er... | Xperia ZR C5502              | 1     |            | 9C65E049FE |
| 0fce:5195 | Sony Er... | Xperia SP C5303              | 1     |            | 481DCFBCF9 |
| 1004:61fe | LG Elec... | Optimus Android Phone [US... | 1     | cdc_acm    | 4A83E029A5 |
| 1004:633a | LG Elec... | Ultimate 2 Android Phone ... | 1     | cdc_acm    | 3E770677B5 |
| 1527:0200 | Silicon... | YAP Phone (no firmware)      | 1     |            | D857FD97FD |
| 17ef:0c02 | Lenovo     | MT65xx Android Phone         | 1     | usbfs      | B776DA24C5 |
| 17ef:79a1 | Lenovo     | MT65xx Android Phone         | 1     |            | 9271AE1167 |
| 19d2:0343 | ZTE WCD... | V985 Android Phone           | 1     |            | 4215162CA5 |
| 2922:0003 | MediaTek   | MT65xx Android Phone         | 1     | rndis_host | 897D97A18D |

### Printer (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:2b17 | Hewlett... | LaserJet 1020                | 63    | usblp      | 2D378E81BE |
| 03f0:002a | Hewlett... | LaserJet P1102               | 43    | usblp      | 0292847FA4 |
| 03f0:4117 | Hewlett... | LaserJet 1018                | 43    | usblp      | 843A450979 |
| 04e8:341b | Samsung... | SCX-4200 series              | 34    | usblp      | EF2092E08E |
| 04a9:2676 | Canon      | CAPT Device                  | 33    | usblp      | 0680547BE3 |
| 03f0:0c17 | Hewlett... | LaserJet 1010                | 25    | usblp      | 4CC48EC551 |
| 067b:2305 | Prolifi... | PL2305 Parallel Port         | 25    | usblp      | E067B0A694 |
| 04b8:002a | Seiko E... | USB2.0 Printer (Hi-speed)    | 24    | usblp      | FE2AB22987 |
| 04e8:344f | Samsung... | SCX-3400 Series              | 24    | usblp      | 3D5822E22A |
| 04a9:2737 | Canon      | MF4410                       | 22    | usblp      | 13AF031E5E |
| 04a9:2759 | Canon      | MF3010                       | 22    | usblp      | 41F3167FB7 |
| 04da:0f0b | Panason... | KX-MB1520RU                  | 21    | usblp      | 119BB270A4 |
| 04e8:3441 | Samsung... | SCX-3200 Series              | 21    | usblp      | 96FD3589B3 |
| 04b8:08a1 | Seiko E... | L210 Series                  | 20    | usblp      | E7507BCF5F |
| 04e8:3469 | Samsung... | M2070 Series                 | 20    | usblp      | CA561AA481 |
| 04b8:0007 | Seiko E... | Printer                      | 19    | usblp      | 4A6F03A5A8 |
| 04f9:0027 | Brother... | HL-2030 Laser Printer        | 19    | usblp      | E9FDF75898 |
| 03f0:3d17 | Hewlett... | LaserJet P1005               | 17    | usblp      | 0ADA104D17 |
| 04b8:0005 | Seiko E... | Printer                      | 17    | usblp      | 379911F605 |
| 04e8:3292 | Samsung... | ML-1640 Series Laser Printer | 17    | usblp      | 465FC87979 |
| 04e8:3321 | Samsung... | M2020 Series                 | 17    | usblp      | FBBF365BF8 |
| 03f0:0317 | Hewlett... | LaserJet 1200                | 14    | usblp      | 8F04A56986 |
| 03f0:8711 | Hewlett... | Deskjet 2050 J510            | 14    | usblp      | 46D69646E5 |
| 04a9:10dc | Canon      | iP7200 series                | 14    | usblp      | 35D97833A7 |
| 04a9:176d | Canon      | PIXMA MG2500 Series          | 13    | usblp      | D8E903F398 |
| 03f0:2504 | Hewlett... | DeskJet F4200 series         | 12    | usblp      | 639305E27C |
| 04a9:262b | Canon      | LaserShot LBP-1120 Printer   | 12    | usblp      | D425CA175B |
| 04a9:26b4 | Canon      | MF4010 series                | 12    | usblp      | 909B7E7E5C |
| 04a9:26da | Canon      | LBP3010B printer             | 12    | usblp      | A89C098655 |
| 04a9:271a | Canon      | CAPT USB Device              | 12    | usblp      | 73AE3BCE39 |
| 04e8:3413 | Samsung... | SCX-4100 Scanner             | 12    | usblp      | A772887752 |
| 03f0:032a | Hewlett... | LaserJet Professional P1102w | 11    | usblp      | DB05087A98 |
| 03f0:2c17 | Hewlett... | LaserJet 1022                | 11    | usblp      | 06513D31C5 |
| 03f0:7611 | Hewlett... | DeskJet F2492 All-in-One     | 11    | usblp      | 410EB6B767 |
| 03f0:e111 | Hewlett... | DeskJet 2130 series          | 11    | usblp      | 3AF4F950EA |
| 04a9:173a | Canon      | PIXMA MP250 series printer   | 11    | usblp      | 915FD7548F |
| 04a9:176c | Canon      | MG2400 series                | 11    | usblp      | 9DD0EDCEF8 |
| 04a9:2771 | Canon      | CAPT USB Device              | 11    | usblp      | F12E05AEE4 |
| 03f0:1d17 | Hewlett... | LaserJet 1320                | 10    | usblp      | EBDD923895 |
| 03f0:8911 | Hewlett... | Deskjet 1050 J410 series     | 10    | usblp      | DFC4334B0C |
| 03f0:d711 | Hewlett... | ENVY 4520 series             | 10    | usblp      | 22D7E30FD4 |
| 04a9:260a | Canon      | CAPT Printer                 | 10    | usblp      | 98686D396A |
| 04b8:08d1 | Seiko E... | L222 Series                  | 10    | usblp      | F51BFFC1EC |
| 04e8:300c | Samsung... | ML-1210 Printer              | 10    | usblp      | 41B27F2557 |
| 04f9:0054 | Brother... | HL-1110 series               | 10    | usblp      | 9C5C83EF21 |
| 1a86:7584 | QinHeng... | CH340S                       | 10    | usblp      | 603796DE3A |
| 03f0:0517 | Hewlett... | LaserJet 1000                | 9     | usblp      | 3AF8833313 |
| 03f0:3e17 | Hewlett... | LaserJet P1006               | 9     | usblp      | 5D050BABD0 |
| 04a9:2684 | Canon      | MF3200 series                | 9     | usblp      | 5149320E81 |
| 04f9:003f | Brother... | HL-2130 series               | 9     | usblp      | 21C54B23DD |
| 0924:3cf4 | Xerox      | Phaser 3140 and 3155         | 9     | usblp      | A15E1952DA |
| 03f0:1017 | Hewlett... | LaserJet 1300                | 8     | usblp      | FD6FD654DB |
| 03f0:2d12 | Hewlett... | Officejet 4500 G510g-m       | 8     | usblp      | 210776A202 |
| 03f0:7e04 | Hewlett... | DeskJet F4100 Printer series | 8     | usblp      | 413AE4FF4F |
| 04a9:10d3 | Canon      | iP2700 series                | 8     | usblp      | 62C88A6530 |
| 04a9:1746 | Canon      | PIXMA MP280 series           | 8     | usblp      | 9C581DD7B1 |
| 04a9:271c | Canon      | CAPT USB Device              | 8     | usblp      | 25E73FCC4B |
| 04b8:0883 | Seiko E... | ME 340 Series/Stylus NX13... | 8     | usblp      | 60C7492B42 |
| 04b8:08a8 | Seiko E... | L355 Series                  | 8     | usblp      | E160C46127 |
| 04e8:326c | Samsung... | ML-2010P Mono Laser Printer  | 8     | usblp      | 74249DC009 |
| 04e8:330f | Samsung... | ML-216x Series Laser Printer | 8     | usblp      | 8A2411B256 |
| 04f9:0273 | Brother... | DCP-7057 scanner/printer     | 8     | usblp      | 79E8256BFB |
| 0924:3cf7 | Xerox      | WorkCentre 3315              | 8     | usblp      | 839442574A |
| 03f0:102a | Hewlett... | LaserJet Professional P 1... | 7     | usblp      | 36570780B5 |
| 03f0:c111 | Hewlett... | Deskjet 1510                 | 7     | usblp      | 0E51CAA7A2 |
| 04b8:004c | Seiko E... | L110 Series                  | 7     | usblp      | DE463D111A |
| 04e8:330c | Samsung... | ML-1865                      | 7     | usblp      | 485C2FB9C0 |
| 04e8:342e | Samsung... | SCX-4300 Series              | 7     | usblp      | 3719375A02 |
| 03f0:0053 | Hewlett... | DeskJet 2600 series          | 6     | usblp      | 8029CAB2FB |
| 03f0:3817 | Hewlett... | LaserJet P2015 series        | 6     | usblp      | 93F413D666 |
| 03f0:5511 | Hewlett... | DeskJet F300 series          | 6     | usblp      | 936319BED0 |
| 04a9:175f | Canon      | PIXMA MP230 series           | 6     | usblp      | EEEE376F38 |
| 04a9:176b | Canon      | PIXMA MX920 Series           | 6     | usblp      | 15BB8982DC |
| 04b8:08d2 | Seiko E... | L366 Series                  | 6     | usblp      | 06D2E7E6AC |
| 04e8:3268 | Samsung... | ML-1610 Mono Laser Printer   | 6     | usblp      | BF727C8928 |
| 04e8:3301 | Samsung... | ML-1660 Series               | 6     | usblp      | 66E92FA977 |
| 05ca:042c | Ricoh      | Aficio SP 100SU              | 6     | usblp      | 1D3FD80F42 |
| 0924:4265 | Xerox      | WorkCentre 3119 Series       | 6     | usblp      | 97152DC2A4 |
| 03f0:0b2a | Hewlett... | LaserJet CP1025nw            | 5     | usblp      | 4DA2F6A4AC |
| 03f0:1204 | Hewlett... | DeskJet 930c                 | 5     | usblp      | 435E64F300 |
| 03f0:5c17 | Hewlett... | LaserJet P2055 series        | 5     | usblp      | 79918271CA |
| 03f0:5d17 | Hewlett... | LaserJet P2035n              | 5     | usblp      | 44F6DB57C6 |
| 03f0:7d04 | Hewlett... | DeskJet F2100 Printer series | 5     | usblp      | 72FFD05528 |
| 03f0:e311 | Hewlett... | DeskJet 3630 series          | 5     | usblp      | 552827C68A |
| 04a9:10d8 | Canon      | iP4900 series                | 5     | usblp      | 39B777FE86 |
| 04a9:1714 | Canon      | MP160                        | 5     | usblp      | E8CCB234ED |
| 04a9:176e | Canon      | PIXMA MG3500 Series          | 5     | usblp      | 33E8833C53 |
| 04a9:1796 | Canon      | G1000 series                 | 5     | usblp      | 85B9604A5F |
| 04a9:180b | Canon      | PIXMA MG3000 series          | 5     | usblp      | CE9A7A34EE |
| 04a9:2660 | Canon      | MF3110                       | 5     | usblp      | 66ABB75DBC |
| 04b8:001b | Seiko E... | L100 Series                  | 5     | usblp      | 47C52F3C00 |
| 04b8:111f | Seiko E... | L386 Series                  | 5     | usblp      | D42C7A796B |
| 04b8:1122 | Seiko E... | L3060 Series                 | 5     | usblp      | 7CCCF8AE74 |
| 04e8:325b | Samsung... | Xerox Phaser 3117 Laser P... | 5     | usblp      | 4068C43059 |
| 04e8:3434 | Samsung... | SCX-4623 Series              | 5     | usblp      | 3F5304647A |
| 04f9:01ea | Brother... | DCP-7030                     | 5     | usblp      | 34D1BD348B |
| 04f9:02d0 | Brother... | DCP-1510                     | 5     | usblp      | 7BB0831B07 |
| 05ca:042b | Ricoh      | Aficio SP 100                | 5     | usblp      | 268D53A8B4 |
| 0922:0020 | Dymo-Co... | LabelWriter 450              | 5     | usblp      | 05505081A2 |
| 03f0:092a | Hewlett... | LaserJet Professional P1566  | 4     | usblp      | 396BE2A324 |

### Scanner (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04a9:1909 | Canon      | CanoScan LiDE 110            | 33    |            | DF71A0BB83 |
| 04a9:2220 | Canon      | CanoScan LIDE 25             | 33    | usbfs      | 26982F6D52 |
| 04a9:220d | Canon      | CanoScan N670U/N676U/LiDE 20 | 28    |            | CE87F391CE |
| 03f0:0a01 | Hewlett... | ScanJet 2400c                | 23    | usbfs      | E067B0A694 |
| 04a9:190a | Canon      | CanoScan LiDE 210            | 20    |            | 15E3126F2C |
| 04b8:0142 | Seiko E... | GT-F730 [GT-S630/Perfecti... | 17    |            | DC102E1DB6 |
| 05d8:4002 | Ultima ... | Artec Ultima 2000 (GT6801... | 17    |            | 6785C105CC |
| 04b8:0121 | Seiko E... | GT-F500/GT-F550 [Perfecti... | 15    |            | 74CD4C3894 |
| 04a9:190e | Canon      | CanoScan LiDE 120            | 13    | usbfs      | F40B146E07 |
| 04a9:190f | Canon      | CanoScan LiDE 220            | 12    | usbfs      | 6C5C8CCFD4 |
| 04b8:0120 | Seiko E... | GT-7400U [Perfection 1270]   | 12    |            | 4CC48EC551 |
| 04b8:012d | Seiko E... | GT-F650 [GT-S600/Perfecti... | 12    |            | 8DEE041C6B |
| 04a9:1904 | Canon      | CanoScan LiDE 100            | 10    |            | 278994D939 |
| 04a9:221c | Canon      | CanoScan LiDE 60             | 10    |            | 71DAB7CD24 |
| 04b8:0122 | Seiko E... | GT-F520/GT-F570 [Perfecti... | 10    |            | A26BD26890 |
| 055f:021b | Mustek ... | BearPaw 1200 CU Plus         | 10    |            | BF8E7A5595 |
| 055f:021f | Mustek ... | SNAPSCAN e22                 | 9     |            | 6E6B64D799 |
| 04b8:011f | Seiko E... | GT-8400UF [Perfection 167... | 8     |            | 6C85E652D6 |
| 04b8:012e | Seiko E... | GT-F670 [Perfection V200 ... | 8     |            | 9EA64D6592 |
| 055f:021d | Mustek ... | BearPaw 2400 CU Plus         | 7     |            | EE0CF0EF40 |
| 04a9:1907 | Canon      | CanoScan LiDE 700F           | 6     | usbfs      | FA300CEB06 |
| 04a9:2213 | Canon      | CanoScan LiDE 50/LiDE 35/... | 6     |            | 5FB89A8B2F |
| 03f0:1c05 | Hewlett... | Scanjet 200                  | 5     |            | 7C9C7AC9A1 |
| 04b8:010f | Seiko E... | GT-7200U [Perfection 1250... | 5     |            | 885EC5C180 |
| 04b8:013a | Seiko E... | GT-X820 [Perfection V600 ... | 5     |            | 25393EF083 |
| 055f:021c | Mustek ... | BearPaw 1200 CU Plus         | 5     | usbfs      | A3F8EC2423 |
| 03f0:1705 | Hewlett... | ScanJet 5590                 | 4     |            | 70EA4F97BF |
| 04a5:20b0 | Acer Pe... | S2W 3300U/4300U              | 4     |            | 2A42DEB5A5 |
| 04a5:2311 | Acer Pe... | Benq 5560                    | 4     |            | 25B7198C11 |
| 04a9:1905 | Canon      | CanoScan LiDE 200            | 4     |            | 23B0F48535 |
| 04a9:220e | Canon      | CanoScan N1240U/LiDE 30      | 4     |            | 91544C4D3A |
| 04a9:2224 | Canon      | CanoScan LiDE 600F           | 4     |            | 7DD5675204 |
| 04a9:2225 | Canon      | CanoScan LiDE 70             | 4     |            | 1EA13B6B1B |
| 04b8:0114 | Seiko E... | Perfection 660               | 4     |            | A26B3126F3 |
| 04b8:0119 | Seiko E... | GT-X750 [Perfection 4490 ... | 4     |            | 585D8319DA |
| 04b8:012a | Seiko E... | GT-X800 [Perfection 4990 ... | 4     |            | 21C54B23DD |
| 055f:021a | Mustek ... | BearPaw 2448 TA Plus         | 4     |            | 6BB9573F31 |
| 03f0:1405 | Hewlett... | ScanJet 3670                 | 3     |            | 58A8ECB02A |
| 03f0:1d05 | Hewlett... | Scanjet 300                  | 3     |            | DEAB0E9DCE |
| 03f0:2205 | Hewlett... | ScanJet 3500c                | 3     |            | 126B5ADE99 |
| 03f0:2305 | Hewlett... | ScanJet 3970c                | 3     |            | E3ADCE0E5E |
| 03f0:2605 | Hewlett... | ScanJet 3800c                | 3     |            | 8B640C33D5 |
| 03f0:2f11 | Hewlett... | PSC 1200                     | 3     | usblp      | 7A2F7425E7 |
| 03f0:4205 | Hewlett... | ScanJet G3010                | 3     |            | A9E90B12DC |
| 04a5:2137 | Acer Pe... | Benq 5150/5250               | 3     |            | 2D25B17958 |
| 04a9:1900 | Canon      | CanoScan LiDE 90             | 3     |            | 82126F997F |
| 04a9:1908 | Canon      | CanoScan                     | 3     | usbfs      | 75193022D0 |
| 04a9:2228 | Canon      | CanoScan 4400F               | 3     |            | FE2AB22987 |
| 04b8:0130 | Seiko E... | GT-X770 [Perfection V500]    | 3     |            | 7BA4EECA79 |
| 04b8:0131 | Seiko E... | GT-F720 [GT-S620/Perfecti... | 3     |            | A5379B40DD |
| 04b8:013b | Seiko E... | Scanner                      | 3     |            | DD8AABC952 |
| 055f:0219 | Mustek ... | BearPaw 2400 TA Plus         | 3     |            | 49BA2B0298 |
| 055f:0408 | Mustek ... | BearPaw 2448 CU Pro          | 3     |            | DD43D2EAFE |
| 03f0:0205 | Hewlett... | ScanJet 3300c                | 2     |            | 435E64F300 |
| 03f0:0405 | Hewlett... | ScanJet 3400cse              | 2     | usbfs      | 856D5A57FF |
| 03f0:0601 | Hewlett... | ScanJet 6300c                | 2     |            | 2047255023 |
| 03f0:0605 | Hewlett... | ScanJet 2200c                | 2     |            | 0E4B7C3629 |
| 03f0:0805 | Hewlett... | HP4470C                      | 2     |            | A014C216F3 |
| 03f0:1b05 | Hewlett... | ScanJet 4850C/4890C          | 2     | usbfs      | 4DFA675040 |
| 03f0:2005 | Hewlett... | ScanJet 3570c                | 2     |            | 9C696B9A08 |
| 03f0:2505 | Hewlett... | ScanJet 3770                 | 2     |            | 33F8716B48 |
| 03f0:4305 | Hewlett... | ScanJet G3110                | 2     |            | 3F1B997D89 |
| 03f0:4505 | Hewlett... | ScanJet G4010                | 2     |            | 5D369BF902 |
| 03f0:4605 | Hewlett... | ScanJet G4050                | 2     |            | 665166F420 |
| 0458:2014 | KYE Sys... | ColorPage-Vivid4             | 2     |            | DD360E1D5E |
| 0458:201f | KYE Sys... | ColorPage-Vivid 1200 XE      | 2     |            | C676410AA7 |
| 04a5:20f8 | Acer Pe... | Benq 5000                    | 2     |            | 7952379ACC |
| 04a5:2211 | Acer Pe... | Color FlatbedScanner39       | 2     |            | E507592DE8 |
| 04a5:2331 | Acer Pe... | FlatbedScanner 50            | 2     |            | 0B356FFA8A |
| 04a9:221b | Canon      | CanoScan 4200F               | 2     |            | AFE7557041 |
| 04b8:0112 | Seiko E... | GT-9700F [Perfection 2450... | 2     |            | 59E341B3D5 |
| 04b8:011b | Seiko E... | GT-9300UF [Perfection 240... | 2     |            | A3F682ED16 |
| 04b8:011c | Seiko E... | GT-9800F [Perfection 3200]   | 2     |            | 86869022FA |
| 04b8:011d | Seiko E... | GT-7300U [Perfection 1260... | 2     |            | CDFEEC3A5F |
| 04b8:012f | Seiko E... | GT-F700 [Perfection V350]    | 2     |            | F6CDB72510 |
| 04c5:128e | Fujitsu    | ScanSnap SV600               | 2     | usbfs      | 3C409E3FAC |
| 055f:021e | Mustek ... | BearPaw 1200 TA/CS           | 2     |            | 7FC17D0078 |
| 01ef:0004 | Hewlett... | Scanjet                      | 1     |            | 3EB97E6189 |
| 03f0:0305 | Hewlett... | ScanJet 4300c                | 1     | usbfs      | 6BAA62B5E0 |
| 03f0:0705 | Hewlett... | ScanJet 4400c                | 1     |            | 1789404C97 |
| 03f0:0b01 | Hewlett... | ScanJet 82x0C                | 1     |            | 2265248DBB |
| 03f0:1205 | Hewlett... | ScanJet 4500C/5550C          | 1     |            | B7C0950BF9 |
| 03f0:2805 | Hewlett... | ScanJet G2710                | 1     |            | 4B3FF97AD5 |
| 03f0:2811 | Hewlett... | PSC-2100                     | 1     | usbfs      | 390C380926 |
| 03f0:2a05 | Hewlett... | Scanjet N6010                | 1     |            | F855FA062D |
| 0458:2013 | KYE Sys... | ColorPage-HR7 Scanner        | 1     |            | 6A6DA1FE6F |
| 0458:201a | KYE Sys... | ColorPage-Vivid4xe           | 1     |            | 7731F20599 |
| 04a5:211b | Acer Pe... | FlatbedScanner 22            | 1     |            | 0A23FD59F0 |
| 04a7:0477 | Visioneer  | DocuMate 152                 | 1     |            | DE18CDDB21 |
| 04a9:1906 | Canon      | CanoScan 5600F               | 1     |            | D14CE30BB6 |
| 04a9:190d | Canon      | CanoScan 9000F Mark II       | 1     |            | C268560077 |
| 04a9:2204 | Canon      | CanoScan FB630U              | 1     |            | 700FBE7F0A |
| 04a9:2206 | Canon      | CanoScan N650U/N656U         | 1     |            | B3EE98B7CC |
| 04a9:221f | Canon      | CanoScan LiDE 500F           | 1     |            | 68FA7AD805 |
| 04b8:0109 | Seiko E... | ES-8500 [Expression 1640 XL] | 1     |            | 52B7E8AF1A |
| 04b8:010b | Seiko E... | GT-7700U [Perfection 1240U]  | 1     |            | F83C6E1394 |
| 04b8:0118 | Seiko E... | GT-F600 [Perfection 4180]    | 1     | usbfs      | 5E6A0B8AE4 |
| 04b8:011e | Seiko E... | GT-8300UF [Perfection 166... | 1     |            | F702714A09 |
| 04b8:0126 | Seiko E... | ES-7000H [GT-15000]          | 1     |            | F6CC7FBA3A |
| 04b8:0802 | Seiko E... | CC-570L [Stylus CX3100/CX... | 1     | usblp      | 44AA7D667E |

### Serial controller (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0403:6001 | Future ... | FT232 USB-Serial (UART) IC   | 64    | ftdi_sio   | FFF26D5712 |
| 1a86:7523 | QinHeng... | HL-340 USB-Serial adapter    | 64    | ch341      | D17275F479 |
| 067b:2303 | Prolifi... | PL2303 Serial Port           | 60    | pl2303     | 6E20292C6B |
| 10c4:ea60 | Cygnal ... | CP2102/CP2109 UART Bridge... | 38    | cp210x     | 94CD691A35 |
| 05c6:9204 | Qualcomm   | Qualcomm Gobi 2000           | 27    | qcserial   | C9C2EFF56C |
| 19d2:0016 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 23    | option     | 1004AD3220 |
| 03f0:241d | Hewlett... | Gobi 2000 Wireless Modem ... | 21    | qcserial   | 82CB2D5E90 |
| 1199:9013 | Sierra ... | Sierra Wireless Gobi 3000... | 20    | qcserial   | BDDCEDAF68 |
| 19d2:2003 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 12    | option     | C438D3E439 |
| 03f0:521d | Hewlett... | hs3110 HSPA+ Mobile Broad... | 11    | option     | 2DC8B3F35D |
| 0d9f:0002 | Powercom   | Black Knight PRO / WOW Un... | 9     | cypress... | D4B6A04B2C |
| 0403:6010 | Future ... | FT2232C/D/H Dual USB-UART... | 7     | ftdi_sio   | 010C5C0DFC |
| 413c:8185 | Dell       | Gobi 2000 Wireless Modem ... | 7     | qcserial   | 62619F4F6C |
| 0451:3410 | Texas I... | TUSB3410 Microcontroller     | 6     | ti_usb_... | ADF7E21650 |
| 1199:9000 | Sierra ... | Gobi 2000 Wireless Modem ... | 6     | qcserial   | F022D26DCE |
| 0403:6015 | Future ... | Bridge(I2C/SPI/UART/FIFO)    | 5     | ftdi_sio   | 831FF4B7FC |
| 04b4:5500 | Cypress... | HID->COM RS232 Adapter       | 5     | cypress... | 47534CE5C1 |
| 05c6:9224 | Qualcomm   | Sony Gobi 2000 Wireless M... | 5     | qcserial   | 94C60C4371 |
| 0af0:6901 | Option     | Globetrotter HSDPA Modem     | 5     | option     | CB80682975 |
| 0fcf:1009 | Dynastr... | ANTUSB-m Stick               | 5     | usb_ser... | E45C3CB530 |
| 05c6:9008 | Qualcomm   | Gobi Wireless Modem (QDL ... | 4     | qcserial   | 6744470582 |
| 1bbb:022c | T & A M... | HSPA+ USB Modem              | 4     | usbseri... | A348E53594 |
| 03f0:1e1d | Hewlett... | hs2300 HSDPA Broadband Wi... | 3     | sierra     | 2724623348 |
| 03f0:201d | Hewlett... | un2400 Gobi Wireless Mode... | 3     | qcserial   | 90DCC06EEA |
| 0403:1234 | Future ... | IronLogic RFID Adapter [Z... | 3     | ftdi_sio   | 876DB8C948 |
| 057c:6201 | AVM        | AVM Fritz!WLAN v1.1 [Texa... | 3     | ndiswra... | 138F3B5EE7 |
| 05c6:9221 | Qualcomm   | Gobi Wireless Modem (QDL ... | 3     | qcserial   | E76B89013B |
| 1199:683c | Sierra ... | Mobile Broadband 3G/UMTS ... | 3     | sierra     | BA912D76A5 |
| 12d1:15c1 | Huawei ... | ME906s LTE M.2 Module        | 3     | option     | CE47638461 |
| 1b1c:1c00 | Corsair    | Controller for Corsair Link  | 3     | cp210x     | 24D4B49329 |
| 04da:250c | Panason... | Gobi Wireless Modem (QDL ... | 2     | qcserial   | FDCC1DFB81 |
| 0557:2008 | ATEN In... | UC-232A Serial Port [pl2303] | 2     | pl2303     | 0F9AA13B55 |
| 0711:0230 | Magic C... | MCT-232 Serial Port          | 2     | mct_u232   | B60D9FA71A |
| 091e:0003 | Garmin ... | GPS (various models)         | 2     | garmin_gps | 037CAC7A3D |
| 114f:68a2 | Wavecom    | MC7750                       | 2     | qcserial   | DED0A1024C |
| 19d2:0117 | ZTE WCD... | WCDMA Technologies MSM       | 2     | option     | 3BEF273525 |
| 1bbb:00b7 | T & A M... | HSPA Data Card               | 2     | option     | E6C9D1B45A |
| 6547:0232 | Arkmicr... | ARK3116 Serial               | 2     | ark3116    | 0FA01E4D66 |
| 03f0:1016 | Hewlett... | Jornada 548 / iPAQ HW6515... | 1     | ipaq       | 4FA0B1AA66 |
| 03f0:a31d | Hewlett... | lt4132 LTE/HSPA+ 4G Module   | 1     | cdc_mbim   | 7F01433E42 |
| 0403:6014 | Future ... | FT232H Single HS USB-UART... | 1     | ftdi_sio   | F1331B62E6 |
| 0403:fc60 | Future ... | IRTrans USB                  | 1     | ftdi_sio   | 6298B19758 |
| 045e:00ce | Microsoft  | SiRF GPS HH                  | 1     | ipaq       | A587AAD1F9 |
| 0483:3747 | STMicro... | ST Micro Connect Lite        | 1     | ftdi_sio   | A56D8D1C28 |
| 06cd:0121 | Keyspan    | USA-19hs serial adapter      | 1     | keyspan    | FB2C692CC5 |
| 0856:ac19 | B&B Ele... | Model USOPTL4DR              | 1     | ftdi_sio   | 077842DAC4 |
| 0bf8:1001 | Fujitsu... | Fujitsu Pocket Loox 600 PDA  | 1     | ipaq       | 224FD9231B |
| 0f3d:68aa | Airprim... | AirCard 313U                 | 1     | sierra     | DB976F7ED5 |
| 0fcf:1008 | Dynastr... | ANTUSB2 Stick                | 1     | usb_ser... | 8D11089A12 |
| 1199:0020 | Sierra ... | MC5725 Modem                 | 1     | sierra     | D2C42C6C14 |
| 1199:0218 | Sierra ... | MC5720 Wireless Modem        | 1     | sierra     | 09DC8C3829 |
| 1199:6812 | Sierra ... | MC8775 Device                | 1     | sierra     | 7D9E4527B1 |
| 1199:6813 | Sierra ... | Mini Card                    | 1     | sierra     | 57A59F48BB |
| 1199:6832 | Sierra ... | MC8780 Device                | 1     | sierra     | 6639C529C5 |
| 1199:6856 | Sierra ... | ATT "USB Connect 881"        | 1     | sierra     | 5A1CA7D377 |
| 1199:6890 | Sierra ... | AC504                        | 1     | sierra     | 83B675C99C |
| 1199:68a3 | Sierra ... | MC8700 Modem                 | 1     | sierra     | 55167C5D7C |
| 1199:68c0 | Sierra ... | MC7304                       | 1     | qcserial   | 787245DA69 |
| 12d1:1569 | Huawei ... | EM680 w/Gobi Technology      | 1     | option     | F05FDF7D0F |
| 1410:2110 | Novatel... | Ovation U720/MCD3000         | 1     | option     | 441D60EA88 |
| 1410:2410 | Novatel... | Expedite EU740               | 1     | option     | 4938E3EC42 |
| 1410:2420 | Novatel... | Expedite EU850D/EU860D/EU... | 1     | option     | EE82411E6C |
| 1555:0004 | Silicon... | AC4 USB to RS-485 Converter  | 1     | cp210x     | 1ED36B8028 |
| 1e0e:9001 | Qualcom... | SimTech, Incorporated        | 1     | option     | E6AC162ADE |
| 2341:4660 | Arduino SA | USB-RS485                    | 1     | usbseri... | 58340DB405 |
| 413c:8116 | Dell       | Wireless 5505 Mobile Broa... | 1     | option     | 6296C79EF5 |
| 413c:8133 | Dell       | Wireless 5720 VZW Mobile ... | 1     | option     | 8CD472192D |
| 413c:8138 | Dell       | Wireless 5520 Voda I Mobi... | 1     | option     | F88C2A43B9 |
| 413c:8171 | Dell       | Gobi Wireless Modem (QDL ... | 1     | qcserial   | 9A4872A774 |
| 9710:7840 | MosChip... | MCS7820/MCS7840 2/4 port ... | 1     | mos7840    | A4BB27D2B7 |

### Sound (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0d8c:013c | C-Media... | CM108 Audio Controller       | 94    | snd_usb... | 502C5D4B04 |
| 0d8c:000c | C-Media... | Audio Adapter                | 41    | snd_usb... | 52475DA06B |
| 1b3f:2008 | General... | USB Audio Device             | 39    | snd_usb... | 363851A935 |
| 1130:1620 | Tenx Te... | USB AUDIO                    | 36    | snd_usb... | 813731AB25 |
| 0d8c:0014 | C-Media... | Audio Adapter (Unitek Y-2... | 35    | snd_usb... | 704C328C67 |
| 08bb:2902 | Texas I... | PCM2902 Audio Codec          | 28    | snd_usb... | B5BA9A13DC |
| 0d8c:0012 | C-Media... | USB Audio Device             | 28    | snd_usb... | D720B44576 |
| 046d:0a44 | Logitech   | Wired headset H390           | 27    | snd_usb... | 5A73C07158 |
| 0d8c:0201 | C-Media... | CM6501                       | 27    | snd_usb... | 0DB30CC602 |
| 0d8c:0102 | C-Media... | CM106 Like Sound Device      | 25    | snd_usb... | 64266B67A2 |
| 045e:070f | Microsoft  | LifeChat LX-3000 Headset     | 24    | snd_usb... | F21C5B69B8 |
| 0bda:4014 | Realtek... | USB Audio                    | 24    | snd_usb... | D2CA5F0DC2 |
| 8086:0808 | Intel      | USB PnP Sound Device         | 20    | snd_usb... | 9D0BA3BCD7 |
| 0c76:161f | JMTek      | USB PnP Audio Device         | 19    | snd_usb... | F0971CD52C |
| 0d8c:0103 | C-Media... | CM102-A+/102S+ Audio Cont... | 19    | snd_usb... | 06052B8628 |
| 041e:30df | Creativ... | SB X-Fi Surround 5.1 Pro     | 18    | snd_usb... | 3A46AD6FD1 |
| 046d:0a29 | Logitech   | H600 [Wireless Headset]      | 15    | snd_usb... | 2F41136472 |
| 046d:0a1f | Logitech   | G930                         | 14    | snd_usb... | 167048774C |
| b58e:9e84 | Blue Mi... | Yeti Stereo Microphone       | 14    | snd_usb... | 5F28B24437 |
| 046d:0a4d | Logitech   | G430 Surround Sound Gamin... | 13    | snd_usb... | 38D61517B0 |
| 08bb:2912 | Texas I... | PCM2912A Audio Codec         | 13    | snd_usb... | 2D71938FC4 |
| 046d:0a37 | Logitech   | USB Headset H540             | 12    | snd_usb... | 1C1D928B1D |
| 08bb:2704 | Texas I... | PCM2704 16-bit stereo aud... | 12    | snd_usb... | FF7DDB741C |
| 093a:2625 | Pixart ... | Multimedia audio controller  | 12    | gspca_p... | 32D6CC8A86 |
| 413c:a503 | Dell       | AC511 USB SoundBar           | 12    | snd_usb... | 086C06ABD4 |
| 046d:0a38 | Logitech   | Headset H340                 | 11    | snd_usb... | 5AC9AC64F7 |
| 046d:0a5b | Logitech   | G933 Wireless Headset Dongle | 11    | snd_usb... | 215C5E6F2A |
| 0951:16a4 | Kingsto... | HyperX 7.1 Audio             | 11    | snd_usb... | AF58D23265 |
| 09da:2701 | A4Tech     | Bloody Gaming Audio Device   | 11    | snd_usb... | BAFB10A069 |
| 0d8c:0005 | C-Media... | Blue Snowball                | 11    | snd_usb... | 66820D32BA |
| 0d8c:0126 | C-Media... | USB Audio Device             | 11    | snd_usb... | 87AFEF045F |
| 18c3:6255 | Elite S... | USB Audio Device             | 11    | snd_usb... | 75E8A3936D |
| 1395:0025 | Sennhei... | Headset [PC 8]               | 10    | snd_usb... | 6388AF2414 |
| 17ef:306f | Lenovo     | ThinkPad Dock USB Audio      | 10    | snd_usb... | 5F8373C716 |
| 041e:30d3 | Creativ... | Sound Blaster Play!          | 9     | snd_usb... | 6A5344B4CC |
| 0556:0001 | Asahi K... | AK5370 I/F A/D Converter     | 9     | snd_usb... | B45F44A0F7 |
| 0d8c:0008 | C-Media... | USB Audio Device             | 9     | snd_usb... | D6813FBC7C |
| 24ae:6000 | Rapoo      | Wireless Audio               | 9     | snd_usb... | 5AEB4ABFE6 |
| 047f:c010 | Plantro... | GameCom 780                  | 8     | snd_usb... | 8DEE041C6B |
| 047f:c012 | Plantro... | .Audio 628 USB               | 8     | snd_usb... | A6B7FD949D |
| 08bb:2904 | Texas I... | PCM2904 Audio Codec          | 8     | snd_usb... | 518F783AA5 |
| 0c76:160c | JMTek      | USB Speaker                  | 8     | snd_usb... | 0BD7D9FCEA |
| 1532:0504 | Razer USA  | Razer Kraken 7.1 Chroma      | 8     | snd_usb... | BBAA313D83 |
| 17ef:306a | Lenovo     | ThinkPad Thunderbolt 3 Do... | 8     | snd_usb... | CABDFDF87F |
| 041e:3040 | Creativ... | SoundBlaster Live! 24-bit... | 7     | snd_usb... | A47D005445 |
| 041e:3232 | Creativ... | Sound Blaster Premium HD ... | 7     | snd_usb... | EFBD2122B7 |
| 046d:0a0c | Logitech   | Clear Chat Comfort USB He... | 7     | snd_usb... | 23B0F48535 |
| 046d:0a15 | Logitech   | G35 Headset                  | 7     | snd_usb... | 0FADE9A3F7 |
| 046d:0a45 | Logitech   | USB Headset                  | 7     | snd_usb... | 256B6730C4 |
| 0d8c:0001 | C-Media... | Audio Device                 | 7     | snd_usb... | DC19476CF2 |
| 1210:000a | DigiTech   | Lexicon Alpha                | 7     | snd_usb... | 786069DE60 |
| 1852:7022 | GYROCOM... | Grant Fidelity dac-11        | 7     | snd_usb... | 0D6CA866B0 |
| 041e:30dd | Creativ... | Sound Blaster X-Fi Go! Pro   | 6     | snd_usb... | C02E4721B7 |
| 046d:0a10 | Logitech   | Speaker                      | 6     | snd_usb... | BE80A2004E |
| 0c76:1617 | JMTek      | USB PnP Audio Device         | 6     | snd_usb... | 84669A36B5 |
| 0d8c:000e | C-Media... | Audio Adapter (Planet UP-... | 6     | snd_usb... | 4821676FE6 |
| 1b1c:0a14 | Corsair    | VOID PRO Wireless Gaming ... | 6     | snd_usb... | F16600B204 |
| 041e:30d7 | Creativ... | USB Sound Blaster HD         | 5     | snd_usb... | BD84F3FEEB |
| 041e:3237 | Creativ... | SB X-Fi Surround 5.1 Pro     | 5     | snd_usb... | 28B8E9271B |
| 041e:324d | Creativ... | Sound Blaster Play! 3        | 5     | snd_usb... | 61DE3D6439 |
| 054c:09cc | Sony       | DualShock 4 [CUH-ZCT2x]      | 5     | snd_usb... | B6AB673257 |
| 0572:1804 | Conexan... | HP Dock Audio                | 5     | snd_usb... | E9DECBC4FD |
| 05a7:1020 | Bose       | USB Audio                    | 5     | snd_usb... | 7DB8E54DDE |
| 06f8:3009 | Guillemot  | Multimedia audio controller  | 5     | gspca_p... | 8E4185612B |
| 0c76:1607 | JMTek      | audio controller             | 5     | snd_usb... | 51A1AAC539 |
| 0d8c:0105 | C-Media... | CM108 Audio Controller       | 5     | snd_usb... | 18DC19F3EC |
| 0d8c:0139 | C-Media... | Multimedia Headset [Gigaw... | 5     | snd_usb... | 23D31351E2 |
| 12ba:0034 | License... | Wireless Stereo Headset      | 5     | snd_usb... | DD3B201BCE |
| 1532:000e | Razer USA  | Razer Megalodon              | 5     | snd_usb... | E55D921BE1 |
| 17ef:3063 | Lenovo     | ThinkPad USB-C Dock Audio    | 5     | snd_usb... | FD5A5FBD54 |
| 6993:b700 | Yealink... | VOIP USB Phone               | 5     | snd_usb... | 60738639D1 |
| 046d:0a01 | Logitech   | USB Headset                  | 4     | snd_usb... | C1C5F4E6DB |
| 046d:0a06 | Logitech   | EasyCall Speakerphone        | 4     | snd_usb... | 5D617B8DE0 |
| 046d:0a66 | Logitech   | [G533 Wireless Headset Do... | 4     | snd_usb... | 912F4D4453 |
| 05fc:0231 | Harman     | JBL Pebbles                  | 4     | snd_usb... | 21C033AABC |
| 08bb:2900 | Texas I... | PCM2900 Audio Codec          | 4     | snd_usb... | B05E61E4D9 |
| 08bb:29c0 | Texas I... | PCM2900C Audio CODEC         | 4     | snd_usb... | C7998D926E |
| 0a12:1243 | Cambrid... | CSRA64110 USB Audio          | 4     | snd_usb... | BBA7F1B63C |
| 0b05:17a0 | ASUSTek... | Xonar U3 sound card          | 4     | snd_usb... | D87E2ED1BC |
| 0d8c:0006 | C-Media... | Storm HP-USB500 5.1 Headset  | 4     | snd_usb... | 02221C3F6B |
| 0d8c:0024 | C-Media... | USB Advanced Audio Device    | 4     | snd_usb... | 67F3C88566 |
| 0d8c:013a | C-Media... | USB PnP Sound Device         | 4     | snd_usb... | EBB304F58E |
| 1038:1250 | SteelSe... | SteelSeries Arctis 5         | 4     | snd_usb... | 172F18A294 |
| 12d1:3a07 | Huawei ... | USB-C HEADSET                | 4     | snd_usb... | 4DCFEFF869 |
| 1532:0a02 | Razer USA  | Razer ManO'War               | 4     | snd_usb... | F790EC4E2C |
| 1a86:752d | QinHeng... | CH345 MIDI adapter           | 4     | snd_usb... | 675E3C5D99 |
| 1b3f:2007 | General... | USB Audio Device             | 4     | snd_usb... | 7996A706B9 |
| 041e:3042 | Creativ... | SB X-Fi Surround 5.1         | 3     | snd_usb... | A0DE23CA8B |
| 041e:3225 | Creativ... | SB Tactic3D Rage Wireless    | 3     | snd_usb... | A645A0DA1D |
| 046d:08c1 | Logitech   | QuickCam Fusion              | 3     | snd_usb... | 004C278780 |
| 046d:0a0e | Logitech   | AudioHub Speaker             | 3     | snd_usb... | B75E2928BD |
| 046d:0a14 | Logitech   | USB Headset                  | 3     | snd_usb... | 9D8F3824E7 |
| 046d:0a6d | Logitech   | G433 Gaming Headset          | 3     | snd_usb... | 695CF5055E |
| 0471:2118 | Philips... | SHG7980                      | 3     | snd_usb... | D21BD5C706 |
| 047f:c008 | Plantro... | Audio 655 DSP                | 3     | snd_usb... | 8838C40E2F |
| 047f:c011 | Plantro... | .Audio 478 USB               | 3     | snd_usb... | CBC2CE04F0 |
| 047f:c021 | Plantro... | RIG                          | 3     | snd_usb... | 345BBA3C1F |
| 047f:c023 | Plantro... | C310-M                       | 3     | snd_usb... | C00059FE69 |
| 047f:c025 | Plantro... | C320-M                       | 3     | snd_usb... | 5F8373C716 |
| 047f:d955 | Plantro... | Wireless Audio               | 3     | snd_usb... | A58865F4C4 |

### Touchpad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 06cb:2970 | Synaptics  | touchpad                     | 28    | usbhid     | 0C710C33F6 |
| 044e:1218 | Alps El... | Touchpad                     | 4     | usbhid     | 87A44EF029 |
| 06cb:0009 | Synaptics  | Composite TouchPad and Tr... | 3     | synapti... | 59E341B3D5 |
| 06cb:5710 | Synaptics  | Touch Pad V 103S             | 3     | usbhid     | BDBFBC68E1 |
| 17ef:6046 | Lenovo     | Wireless Touchpad K5923      | 2     | usbhid     | A70BC24DCC |
| 044e:1210 | Alps El... | Touchpad                     | 1     | usbhid     | EC07F9B3A7 |
| 04b4:fef3 | Cypress... | PenPower Touchpad            | 1     | usbhid     | AC3E990070 |
| 062a:19b5 | MosArt ... | TouchPad                     | 1     | usbhid     | 61BB547684 |
| 06cb:5711 | Synaptics  | Touch Pad V 103u9            | 1     | usbhid     | 2D9527DBD4 |

### Touchscreen (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04f3:20d0 | Elan Mi... | Touchscreen                  | 15    | usbhid     | B983AFEDFC |
| 04f3:250e | Elan Mi... | Touchscreen                  | 13    | usbhid     | 931D7104FA |
| 04f3:2494 | Elan Mi... | Touchscreen                  | 9     | usbhid     | 271C309BFA |
| 0eef:0001 | D-WAV S... | eGalax TouchScreen           | 9     | usbhid     | 6F28F56C47 |
| 04f3:000a | Elan Mi... | Touchscreen                  | 7     | usbhid     | 8A9D1FE58F |
| 04f3:0254 | Elan Mi... | Touchscreen                  | 7     | usbhid     | 2607C4AD33 |
| 0408:3008 | Quanta ... | OpticalTouchScreen           | 6     | usbhid     | 2E89DCF36E |
| 04f3:012d | Elan Mi... | Touchscreen                  | 6     | usbhid     | 65AD0CE191 |
| 04f3:2013 | Elan Mi... | Touchscreen                  | 6     | usbhid     | EC2AF399B2 |
| 04f3:24a1 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 14C2B3FA53 |
| 1926:0bce | NextWindow | Touchscreen                  | 6     | usbhid     | 4A2DA5DD1B |
| 04f3:0085 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 7537E7CB35 |
| 04f3:016f | Elan Mi... | Touchscreen                  | 5     | usbhid     | AB1C14D729 |
| 04f3:2234 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 200F73880C |
| 04f3:010c | Elan Mi... | Touchscreen                  | 4     | usbhid     | E5CD52885F |
| 04f3:024b | Elan Mi... | Touchscreen                  | 4     | usbhid     | 4488D384BA |
| 04f3:036e | Elan Mi... | Touchscreen                  | 4     | usbhid     | 0E74429D54 |
| 04f3:2083 | Elan Mi... | Touchscreen                  | 4     | usbhid     | A599D32521 |
| 04f3:20d6 | Elan Mi... | Touchscreen                  | 4     | usbhid     | 0251B0C34F |
| 1926:0344 | NextWindow | Touchscreen                  | 4     | usbhid     | 28B99207FE |
| 0408:3003 | Quanta ... | OpticalTouchScreen           | 3     | usbhid     | A010F0A8F5 |
| 04e7:0020 | Elo Tou... | Touchscreen Interface (2700) | 3     | usbhid     | 612620FA7A |
| 04f3:0034 | Elan Mi... | Touchscreen                  | 3     | usbhid     | 3B2693598E |
| 04f3:005a | Elan Mi... | Touchscreen                  | 3     | usbhid     | F95BBD54DA |
| 04f3:0074 | Elan Mi... | Touchscreen                  | 3     | usbhid     | 10FB53EFCA |
| 04f3:009d | Elan Mi... | Touchscreen                  | 3     | usbhid     | 26C2CAF634 |
| 04f3:0117 | Elan Mi... | Touchscreen                  | 3     | usbhid     | BDBFBC68E1 |
| 04f3:034e | Elan Mi... | Touchscreen                  | 3     | usbhid     | 4D1CBAF708 |
| 04f3:0396 | Elan Mi... | Touchscreen                  | 3     | usbhid     | AA5BFF0634 |
| 04f3:2085 | Elan Mi... | Touchscreen                  | 3     | usbhid     | C35AD981F9 |
| 04f3:21f9 | Elan Mi... | Touchscreen                  | 3     | usbhid     | B133F93FAA |
| 04f3:24a0 | Elan Mi... | Touchscreen                  | 3     | usbhid     | 000D8EB1AC |
| 04f3:24e1 | Elan Mi... | Touchscreen                  | 3     | usbhid     | E93E7BA3C5 |
| 1926:0006 | NextWindow | 1950 HID Touchscreen         | 3     | usbhid     | C3AF2AAD45 |
| 1926:0065 | NextWindow | 1950 HID Touchscreen         | 3     | usbhid     | 05CFF66AC2 |
| 1926:0e17 | NextWindow | Touchscreen                  | 3     | usbhid     | B4CF237F88 |
| 04f3:0018 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 72500924FF |
| 04f3:002a | Elan Mi... | Touchscreen                  | 2     | usbhid     | 4A406AE051 |
| 04f3:0135 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 09281F5A50 |
| 04f3:015d | Elan Mi... | Touchscreen                  | 2     | usbhid     | 44DC7D96C7 |
| 04f3:016c | Elan Mi... | Touchscreen                  | 2     | usbhid     | 35F9DBEE89 |
| 04f3:0201 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 19D02B1151 |
| 04f3:0206 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 584DBB41C7 |
| 04f3:0303 | Elan Mi... | Touchscreen                  | 2     | usbhid     | A5C7637FC8 |
| 04f3:0348 | Elan Mi... | Touchscreen                  | 2     | usbhid     | C0DCEE7A80 |
| 04f3:034f | Elan Mi... | Touchscreen                  | 2     | usbhid     | 08B3438DF5 |
| 04f3:0363 | Elan Mi... | Touchscreen                  | 2     | usbhid     | EBA1957459 |
| 04f3:0406 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 5CAD0D6150 |
| 04f3:0418 | Elan Mi... | Touchscreen                  | 2     | usbhid     | F2DB78FEFC |
| 04f3:0422 | Elan Mi... | Touchscreen                  | 2     | usbhid     | FDCF5773E1 |
| 04f3:2012 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 8E8253A973 |
| 04f3:2021 | Elan Mi... | Touchscreen                  | 2     | usbhid     | C6BC466B79 |
| 04f3:2033 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 0F57C777F6 |
| 04f3:2044 | Elan Mi... | Touchscreen                  | 2     | usbhid     | C90B14D1E5 |
| 04f3:2070 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 910D564E8E |
| 04f3:2089 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 7C54A20D12 |
| 04f3:20d8 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 1274A24ED0 |
| 04f3:20f0 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 1FBEE12FFE |
| 04f3:21d4 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 68C56E0AB4 |
| 04f3:21f3 | Elan Mi... | Touchscreen                  | 2     | usbhid     | E89AA0C891 |
| 04f3:228a | Elan Mi... | Touchscreen                  | 2     | usbhid     | 6CB660F70F |
| 04f3:228c | Elan Mi... | Touchscreen                  | 2     | usbhid     | 7611B00DAF |
| 04f3:22c3 | Elan Mi... | Touchscreen                  | 2     | usbhid     | A4264E7371 |
| 04f3:2313 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 82C02D11DB |
| 04f3:2356 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 44219C33C7 |
| 04f3:2398 | Elan Mi... | Touchscreen                  | 2     | usbhid     | B4C9E8DC23 |
| 04f3:24d4 | Elan Mi... | Touchscreen                  | 2     | usbhid     | D302412809 |
| 04f3:2544 | Elan Mi... | Touchscreen                  | 2     | usbhid     | B4ED65654C |
| 04f3:2754 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 1FAE59F532 |
| 04f3:2793 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 3275EB49D9 |
| 1926:0003 | NextWindow | 1900 HID Touchscreen         | 2     | usbhid     | EF835695B4 |
| 1926:0083 | NextWindow | 1950 HID Touchscreen         | 2     | usbhid     | A7CE72E3F1 |
| 1926:0330 | NextWindow | Touchscreen                  | 2     | usbhid     | BAA91679D8 |
| 1926:0dbe | NextWindow | Touchscreen                  | 2     | usbhid     | BE8250E028 |
| 1926:0dc6 | NextWindow | Touchscreen                  | 2     | usbhid     | 022809A636 |
| 2149:211b | Advance... | Touchscreen Controller       | 2     | usbhid     | 48A3B0ECA9 |
| 0408:3033 | Quanta ... | OpticalTouchScreen           | 1     | usbhid     | 227CCDA2A1 |
| 04f3:000c | Elan Mi... | Touchscreen                  | 1     | usbhid     | 8BF9F9DFC3 |
| 04f3:0017 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 7C82C563B9 |
| 04f3:0021 | Elan Mi... | Touchscreen                  | 1     | usbhid     | B0F9ABFE8D |
| 04f3:0022 | Elan Mi... | Touchscreen                  | 1     | usbhid     | FA5BBECCF2 |
| 04f3:0023 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 4DED2DA172 |
| 04f3:002f | Elan Mi... | Touchscreen                  | 1     | usbhid     | CA13E88F55 |
| 04f3:003d | Elan Mi... | Touchscreen                  | 1     | usbhid     | 9D8F98B831 |
| 04f3:0046 | Elan Mi... | Touchscreen                  | 1     | usbhid     | C7B8BCD428 |
| 04f3:006f | Elan Mi... | Touchscreen                  | 1     | usbhid     | F93A729611 |
| 04f3:007f | Elan Mi... | Touchscreen                  | 1     | usbhid     | 3E12B22705 |
| 04f3:0086 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 96108AA65D |
| 04f3:0089 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 73A88E2C94 |
| 04f3:009b | Elan Mi... | Touchscreen                  | 1     | usbhid     | AC370F7595 |
| 04f3:009c | Elan Mi... | Touchscreen                  | 1     | usbhid     | B9FA875E7D |
| 04f3:0125 | Elan Mi... | Touchscreen                  | 1     | usbhid     | E4421675DE |
| 04f3:012c | Elan Mi... | Touchscreen                  | 1     | usbhid     | EFCBC58CE9 |
| 04f3:012e | Elan Mi... | Touchscreen                  | 1     | usbhid     | D6A2D267C5 |
| 04f3:013b | Elan Mi... | Touchscreen                  | 1     | usbhid     | 0F518ACFC3 |
| 04f3:0143 | Elan Mi... | Touchscreen                  | 1     | usbhid     | BF342390E8 |
| 04f3:0154 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 859AAD148A |
| 04f3:0155 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 106E86F531 |
| 04f3:0194 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 2D9527DBD4 |
| 04f3:0208 | Elan Mi... | Touchscreen                  | 1     | usbhid     | CF96C22265 |

### Tv card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 093a:2620 | Pixart ... | TV Card                      | 34    | gspca_p... | DC849CA1DE |
| 0402:5602 | ALi        | M5602 Video Camera Contro... | 31    | gspca_m... | 008D49D6FC |
| 0ac8:303b | Z-Star ... | ZC0303 Webcam                | 27    | gspca_z... | 8FF0EB4E50 |
| 045e:00f7 | Microsoft  | LifeCam VX-1000              | 23    | gspca_s... | BD250445FE |
| 046d:0896 | Logitech   | OrbiCam                      | 22    | gspca_v... | 290DB67DA7 |
| 05e1:0501 | Syntek     | DC-1125 Webcam               | 21    | stkwebcam  | B2D7F1D3EC |
| 0ac8:305b | Z-Star ... | ZC0305 Webcam                | 20    | gspca_z... | 276FD0BC49 |
| 093a:2622 | Pixart ... | Webcam Genius                | 17    | gspca_p... | 9A1F61188E |
| 046d:08d7 | Logitech   | QuickCam Communicate STX     | 16    | gspca_z... | F1886B084F |
| 045e:00f5 | Microsoft  | LifeCam VX-3000              | 12    | gspca_s... | 588C79360B |
| 093a:2624 | Pixart ... | Webcam                       | 12    | gspca_p... | BDB727808F |
| 046d:089d | Logitech   | QuickCam E2500 series        | 11    | gspca_z... | 921FA6BB77 |
| 046d:08da | Logitech   | QuickCam Messanger           | 11    | gspca_z... | 8E3B163179 |
| 046d:08d9 | Logitech   | QuickCam IM/Connect          | 9     | gspca_z... | 2327D3DDB8 |
| 093a:2468 | Pixart ... | SoC PC-Camera                | 9     | gspca_p... | 871C8E598B |
| 1415:2000 | Nam Tai... | Sony Playstation Eye         | 9     | gspca_o... | 3C5BAF94F5 |
| 174f:a311 | Syntek     | 1.3MPixel Web Cam - Asus ... | 9     | stkwebcam  | C1DA7EE91F |
| 093a:262c | Pixart ... | TV Card                      | 8     | gspca_p... | D70072A75B |
| 046d:08af | Logitech   | QuickCam Easy/Cool           | 7     | gspca_z... | B6CACD96B5 |
| 046d:092f | Logitech   | QuickCam Express Plus        | 7     | gspca_s... | B9F2AE0CCF |
| 093a:2476 | Pixart ... | CIF Single Chip              | 7     | gspca_p... | D73E7CDAF7 |
| 093a:2626 | Pixart ... | TV Card                      | 7     | gspca_p... | B656825800 |
| 0ac8:301b | Z-Star ... | ZC0301 Webcam                | 6     | gspca_z... | 9928EAEA06 |
| 0c45:624f | Microdia   | PC Camera (SN9C201 + OV9650) | 6     | gspca_s... | 5B4BAFA432 |
| 041e:4052 | Creativ... | Live! Cam Vista IM           | 5     | gspca_o... | 950859DD95 |
| 046d:08ad | Logitech   | QuickCam Communicate STX     | 5     | gspca_z... | F1D5B6204E |
| 0ac8:307b | Z-Star ... | USB 1.1 Webcam               | 5     | gspca_z... | 1F44759168 |
| 0ac8:c002 | Z-Star ... | Visual Communication Came... | 5     | gspca_v... | 0A49B7984F |
| 041e:4064 | Creativ... | VF0420 Live! Cam Vista IM    | 4     | gspca_o... | 6A04D25891 |
| 045e:00f4 | Microsoft  | LifeCam VX-6000 (SN9C20x ... | 4     | gspca_s... | AE27E5AC51 |
| 046d:08a2 | Logitech   | Labtec Webcam Pro            | 4     | gspca_z... | 51837DE98F |
| 093a:2621 | Pixart ... | PAC731x Trust Webcam         | 4     | gspca_p... | B5BA9A13DC |
| 0ac8:0328 | Z-Star ... | A4Tech PK-130MG              | 4     | gspca_v... | 56944B383F |
| 0c45:608f | Microdia   | PC Camera (SN9C103 + OV7630) | 4     | gspca_s... | FEFB26C581 |
| 041e:405f | Creativ... | WebCam Vista (VF0330)        | 3     | gspca_o... | FBFD1473BD |
| 093a:2472 | Pixart ... | CIF Single Chip              | 3     | gspca_p... | C1255CDB72 |
| 093a:2608 | Pixart ... | PAC7311 Trust WB-3300p       | 3     | gspca_p... | DB521911E3 |
| 093a:260e | Pixart ... | PAC7311 Gigaware VGA PC C... | 3     | gspca_p... | 880C81C0C9 |
| 0c45:6028 | Microdia   | Typhoon Easycam USB 330K ... | 3     | gspca_s... | E0AA274C72 |
| 0c45:6128 | Microdia   | PC Camera (SN9C325 + OM6802) | 3     | gspca_s... | 3AAC9757B6 |
| 2040:7200 | Hauppauge  | WinTV HVR-950                | 3     | au0828     | 19AE174CC7 |
| 041e:4034 | Creativ... | Webcam Instant               | 2     | gspca_z... | 57024648C9 |
| 041e:4061 | Creativ... | Live! Cam Notebook Pro [V... | 2     | gspca_o... | 4E187292DA |
| 046d:0892 | Logitech   | OrbiCam                      | 2     | gspca_v... | A548B448E7 |
| 046d:08a9 | Logitech   | Notebook Deluxe              | 2     | gspca_z... | F81A55F416 |
| 0471:0329 | Philips... | SPC 900NC PC Camera / ORI... | 2     | pwc, sn... | 50792DF026 |
| 06f8:3008 | Guillemot  | USB camera                   | 2     | gspca_s... | 7966B612A9 |
| 093a:2460 | Pixart ... | Q-TEC WEBCAM 100             | 2     | gspca_p... | FC4EBA57CC |
| 093a:2470 | Pixart ... | SoC PC-Camera                | 2     | gspca_p... | A28F7B2623 |
| 0ac8:0302 | Z-Star ... | ZC0302 Webcam                | 2     | gspca_z... | 4F1BC27C5A |
| 0ac8:0321 | Z-Star ... | Vimicro generic vc0321 Ca... | 2     | gspca_v... | A1228CD6CC |
| 0c45:600d | Microdia   | TwinkleCam USB camera        | 2     | gspca_s... | 4ED412D115 |
| 0c45:602c | Microdia   | Clas Ohlson TWC-30XOP Webcam | 2     | gspca_s... | 23B0F48535 |
| 0c45:60b0 | Microdia   | Genius VideoCam Look         | 2     | gspca_s... | 8C929530B7 |
| 0c45:613a | Microdia   | PC Camera (SN9C120)          | 2     | gspca_s... | CFCEDC1F4F |
| 0c45:613c | Microdia   | PC Camera (SN9C120)          | 2     | gspca_s... | C6B09D560F |
| 0c45:6242 | Microdia   | PC Camera (SN9C201 + MI1310) | 2     | gspca_s... | F476459E50 |
| 0c45:6270 | Microdia   | PC Camera (SN9C201 + MI03... | 2     | gspca_s... | E969E52D33 |
| eb1a:2860 | eMPIA T... | USB 2860 Device              | 2     | em28xx     | F6E7472126 |
| eb1a:2861 | eMPIA T... | TV Card                      | 2     | em28xx     | 247D9E9C2F |
| 040a:0300 | Kodak      | EZ-200                       | 1     | gspca_s... | 70949E4CAC |
| 041e:401c | Creativ... | Webcam NX [PD1110]           | 1     | gspca_z... | 5305CEA18B |
| 041e:401e | Creativ... | Webcam NX Pro                | 1     | gspca_z... | BC416CD580 |
| 041e:4028 | Creativ... | Vista Plus cam [VF0090]      | 1     | gspca_p... | EFA320E41A |
| 0458:7004 | KYE Sys... | VideoCAM Express V2          | 1     | gspca_s... | E7C73C81EC |
| 0458:7029 | KYE Sys... | Genius Look 320s (SN9C201... | 1     | gspca_s... | CE3CF2888A |
| 046d:08ae | Logitech   | QuickCam for Notebooks       | 1     | snd_usb... | E747D8C526 |
| 046d:08f0 | Logitech   | QuickCam Messenger           | 1     | gspca_s... | AB7B26B325 |
| 046d:08f6 | Logitech   | QuickCam Messenger Plus      | 1     | gspca_s... | F235798C9E |
| 046d:0928 | Logitech   | QuickCam Express             | 1     | gspca_s... | D78C1D6096 |
| 046d:0929 | Logitech   | Labtec Webcam Pro            | 1     | gspca_s... | 19C101AB87 |
| 046d:092e | Logitech   | QuickCam Chat                | 1     | gspca_s... | 2C10191944 |
| 0471:032d | Philips... | SPC 210NC PC Camera          | 1     | gspca_z... | 2441D6D1D8 |
| 0545:8333 | Xirlink    | Veo Stingray/Connect Web ... | 1     | gspca_t... | B9F90CB8E0 |
| 054c:0154 | Sony       | Eyetoy Audio Device          | 1     | gspca_o... | 4BA24556E4 |
| 05a9:8519 | OmniVis... | OV519 Webcam                 | 1     | gspca_o... | 23D31351E2 |
| 0733:0401 | ViewQue... | CS330 Webcam                 | 1     | gspca_s... | C6F1D561A0 |
| 0733:2211 | ViewQue... | Jenoptik jdc 21 LCD Camera   | 1     | gspca_s... | 8B663BFE23 |
| 07ca:0889 | AVerMed... | AVerTV Satellite 2           | 1     |            | 174EC665C6 |
| 093a:2463 | Pixart ... | CIF Single Chip              | 1     | gspca_p... | 1DE59A68CD |
| 093a:2600 | Pixart ... | Typhoon Easycam USB 330K ... | 1     | gspca_p... | 89B7926B1C |
| 0c45:6007 | Microdia   | VideoCAM Eye                 | 1     | gspca_s... | 90EA766D86 |
| 0c45:6009 | Microdia   | VideoCAM ExpressII           | 1     | gspca_s... | 120E7702AF |
| 0c45:6029 | Microdia   | Triplex i-mini PC Camera     | 1     | gspca_s... | 4B8FD34544 |
| 0c45:602b | Microdia   | VideoCAM NB 300              | 1     | sn9c102    | DF2321CD21 |
| 0c45:602e | Microdia   | VideoCAM Messenger           | 1     | gspca_s... | 2022755796 |
| 0c45:6030 | Microdia   | VideoCAM ExpressII           | 1     |            | 6F28F56C47 |
| 0c45:6100 | Microdia   | USB camera                   | 1     | gspca_s... | 0AB0ACEA30 |
| 0c45:612c | Microdia   | PC Camera (SN9C110)          | 1     | gspca_s... | 411AE44FDE |
| 0c45:613e | Microdia   | PC Camera (SN9C120)          | 1     | gspca_s... | 64E722CEC4 |
| 0c45:624e | Microdia   | PC Camera (SN9C201 + SOI968) | 1     | gspca_s... | B60039A681 |
| 0ccd:0096 | TerraTe... | Grabby                       | 1     | em28xx     | F298AE57F6 |
| 1164:0622 | YUAN Hi... | USB GOTVIEW DVD2             | 1     | pvrusb2    | C0CF078B6C |
| 1943:2255 | Sensoray   | Model 2255 4 Channel Capt... | 1     | s2255drv   | F077B2F98E |
| 2040:2400 | Hauppauge  | WinTV PVR USB2 (Model 24019) | 1     | pvrusb2    | C991B3CFCA |
| 2040:4902 | Hauppauge  | HD PVR                       | 1     | hdpvr      | 01928383AA |
| 2040:6513 | Hauppauge  | WinTV HVR-980                | 1     | em28xx     | FCC16B2804 |
| 2040:7501 | Hauppauge  | WinTV                        | 1     | pvrusb2    | AE5B68C4AD |
| 6000:dec1 | Beholde... | TV Voyage                    | 1     | tm6000     | 39E3030E0A |
| eb1a:2881 | eMPIA T... | EM2881 Video Controller      | 1     | em28xx     | E22CC7C6C8 |

### Ups (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 051d:0002 | America... | Back-UPS Pro 500/1000/1500   | 148   | usbhid     | 801CA1718A |
| 0764:0501 | Cyber P... | CP1500 AVR UPS               | 52    | usbhid     | 5A0F369648 |
| 0d9f:0004 | Powercom   | HID UPS Battery              | 11    | usbhid     | 8D0B9127EF |
| 0463:ffff | MGE UPS... | UPS                          | 8     | usbfs      | A4A2089B96 |
| 06da:0003 | Phoenix... | 1300VA UPS                   | 6     | usbhid     | 9B671B15DD |
| 0d9f:00a2 | Powercom   | Imperial Uninterruptible ... | 5     | usbhid     | AEEDCA54FC |
| 0925:1234 | Lakevie... | UPS USB MON V1.4             | 4     | usbhid     | A12C16610A |
| 051d:0003 | America... | UPS                          | 3     | usbhid     | 1B28CC994F |
| 06da:ffff | Phoenix... | Offline UPS                  | 3     | usbhid     | DE640CB2FF |
| 0d9f:00a3 | Powercom   | Smart King PRO Uninterrup... | 3     | usbhid     | F4AF5BD9C9 |
| 05dd:a011 | Delta E... | MINUTEMAN UPS                | 2     | usbhid     | 1BAE5B1DC6 |
| 0764:0601 | Cyber P... | PR1500LCDRT2U UPS            | 2     | usbhid     | 97CC3C4274 |
| 09ae:2012 | Tripp Lite | UPS                          | 2     | usbhid     | 8D6C4235C3 |
| 0d9f:00a4 | Powercom   | WOW Uninterruptible Power... | 2     | usbhid     | D06D669535 |
| 03f0:1fe2 | Hewlett... | T1000 G3 UPS                 | 1     | usbhid     | 19AE174CC7 |
| 050d:0751 | Belkin ... | Belkin UPS                   | 1     | usbhid     | 71F7F3AD8A |
| 0592:0002 | Powerware  | UPS (X-Slot)                 | 1     |            | 049C18DB44 |
| 06da:0002 | Phoenix... | UPS                          | 1     |            | 4F5E89A87E |
| 09ae:2010 | Tripp Lite | UPS                          | 1     | usbhid     | 5D1A48EE4E |
| 09ae:4004 | Tripp Lite | UPS                          | 1     | usbfs      | 52D5275C7F |
| 0d9f:00a6 | Powercom   | Black Knight PRO Uninterr... | 1     | usbhid     | B9B505B7F4 |

### Video (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 048d:9006 | Integra... | IT9135 BDA Afatech DVB-T ... | 4     | dvb_usb... | 63DC09B54E |
| 1164:1ee9 | YUAN Hi... | Polaris AV Capture           | 3     |            | A2613DB100 |
| 2304:0224 | Pinnacl... | MovieBox Plus (710-USB)      | 2     |            | E9365BC8D0 |
| 0fd9:0051 | Elgato ... | GameCapture HD               | 1     |            | 05F988930D |
| 0fd9:0062 | Elgato ... | Cam Link                     | 1     | snd_usb... | D0234C90FB |
| 1b80:a41c | Afatech    | Polaris AV Capture           | 1     |            | F20674C0B8 |
| 5555:3382 | Epiphan... | VGA2USB Frame Grabber        | 1     |            | 37A831391B |

### Wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2717:ff88 | Android    | Android                      | 16    | rndis_host | CFCEC9BCBB |
| 22b8:2e25 | Motorol... | Moto E (4)                   | 7     | rndis_host | 6206EB1A2F |
| 0b05:7782 | ASUSTek... | Device CD-ROM                | 4     | rndis_host | 1F62DD8462 |
| 1286:4e31 | Marvell... | Mobile Composite Device Bus  | 3     | rndis_host | F497726038 |
| 12d1:1039 | Huawei ... | Ideos (tethering mode)       | 3     | rndis_host | CA1FB717A1 |
| 0fce:71e8 | Sony Er... | F5321                        | 2     | rndis_host | 70D66C5819 |
| 1271:0541 | Android    | Android                      | 2     | rndis_host | 0C8768F146 |
| 12d1:107c | Huawei ... | Che2-L11                     | 2     | rndis_host | 07E2ABDE16 |
| 17ef:782f | Lenovo     | Lenovo                       | 2     | rndis_host | 7BA3F44B0A |
| 216f:0044 | Altair ... | Modem YOTA 4G LTE            | 2     | rndis_host | 92A7F0EA0B |
| 0421:0704 | Nokia M... | Nokia_X2 (RM-1013)           | 1     | rndis_host | 2762E434EB |
| 04dd:97f2 | Sharp      | SH05F                        | 1     | rndis_host | B10FE6845E |
| 05c6:90b6 | Qualcomm   | Android                      | 1     | rndis_host | DBCA41493B |
| 0b05:7775 | ASUSTek... | Zenfone GO (ZB500KL) (Deb... | 1     | rndis_host | 3D52782061 |
| 0fce:7193 | Sony Er... | C6603                        | 1     | rndis_host | F748A62EBE |
| 0fce:71aa | Sony Er... | Android                      | 1     | rndis_host | 0C9E0F4767 |
| 0fce:71ba | Sony Er... | D6603                        | 1     | rndis_host | 5974A74BFD |
| 0fce:71f6 | Sony Er... | H4311                        | 1     | rndis_host | C9FFEA0EA6 |
| 0fce:71fa | Sony Er... | H8216                        | 1     | rndis_host | 2E8293E201 |
| 0fce:81bb | Sony Er... | D5803                        | 1     | rndis_host | 7D93192AAE |
| 12d1:2607 | Huawei ... | HUAWEI                       | 1     | rndis_host | A6385534C5 |
| 15a9:003a | Gemtek     | Modem YOTA 4G LTE            | 1     |            | 02E0DBC8D3 |
| 17ef:79bb | Lenovo     | Android                      | 1     | rndis_host | 0B5B82FFE2 |
| 271d:90b5 | Android    |                              | 1     | rndis_host | 65345FD237 |
| 2916:f00e | Android    | Android                      | 1     | rndis_host | 79937B3042 |
| 2970:0004 | Fly        | Evo Chic 3                   | 1     | rndis_host | A83B92D6B0 |
| 2970:2005 | Wileyfox   | Spark                        | 1     | rndis_host | 2E016FB88C |
| 2a70:9024 | OnePlus    | OnePlus                      | 1     | rndis_host | A56E6DB84E |
| 2ae5:9024 | Fairphone  | FP2                          | 1     | rndis_host | 8200C0DCD0 |
| 2d95:600b | Android    | Android                      | 1     | rndis_host | FE62192F4F |

### Others (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0e8d:2008 | MediaTek   | Impress_Luck                 | 36    | usbfs      | 7AB7A76920 |
| 2717:ff40 | MediaTek   | SDM636-MTP _SN:02BF3EA3      | 36    | usbfs      | ADEC400398 |
| 05ac:8300 | Apple      | Built-in iSight (no firmw... | 32    | isight_... | 3A660A2575 |
| 22b8:2e82 | Motorol... | Moto Z (2)                   | 17    | usbfs      | 4250651580 |
| 2109:0100 | VIA Labs   | USB 2.0 BILLBOARD            | 14    |            | C7B13E4BA2 |
| 2109:0102 | VIA Labs   | USB 2.0 BILLBOARD            | 12    |            | 85085D7FF6 |
| 04b8:014a | Seiko E... | Perfection V37/V370          | 11    |            | BF0DFBF414 |
| 04b4:5217 | Cypress... | Billboard Device             | 10    | usbhid     | 2D71938FC4 |
| 0b05:18f3 | ASUSTek... | AURA LED Controller          | 9     | usbhid     | 172F18A294 |
| 0e8d:201d | MediaTek   | Tele2_Maxi_LTE               | 9     | usbfs      | 21AE6DBDF0 |
| 045e:02ea | Microsoft  | Xbox One S Controller        | 8     | xpad       | 3ED88526C2 |
| 0b05:7772 | ASUSTek... | ASUS Zenfone GO (ZB500KL)... | 8     | usbfs      | D00F8461C6 |
| 27c6:538d | Goodix     | FingerPrint                  | 8     |            | 53A24AAEB0 |
| 045e:028f | Microsoft  | Xbox360 Wireless Controller  | 7     |            | EC2AF399B2 |
| 06cb:00c7 | Synaptics  |                              | 7     |            | 944DBD3519 |
| 1b1c:0c09 | Corsair    | H100i v2                     | 7     |            | 40EA4505B9 |
| 045e:02e6 | Microsoft  | Wireless XBox Controller ... | 6     |            | 3833787EFA |
| 045e:02fe | Microsoft  | XBOX ACC                     | 6     |            | EC48803226 |
| 0483:3748 | STMicro... | ST-LINK/V2                   | 6     |            | E3CFB6B7E6 |
| 0489:e031 | Foxconn... | BCM20702A0                   | 6     | btusb      | 12ED876B92 |
| 06cb:00bb | Synaptics  |                              | 6     |            | 0CF9D0AFB9 |
| 06cb:00be | Synaptics  |                              | 6     |            | C7DFFC3F2A |
| 0955:0007 | Nvidia     | stereo controller            | 6     |            | F6D05FF577 |
| 187f:0600 | Siano M... | MDTV Receiver                | 6     | smsusb     | F668CAA5B9 |
| 1934:5168 | Feature... | F71610A or F71612A Consum... | 6     | mceusb     | C3AF2AAD45 |
| 045e:02d1 | Microsoft  | Xbox One Controller          | 5     | xpad       | 9C07DD1B6D |
| 0489:e080 | Foxconn... | BT                           | 5     |            | DF4413AF58 |
| 04eb:e033 | Northst... | eHome Infrared Transceiver   | 5     |            | 39BC0AD7B5 |
| 06cb:00c9 | Synaptics  |                              | 5     |            | C161243049 |
| 0af0:7601 | Option     | Globetrotter MO40x 3G Mod... | 5     | hso        | 03DEB29A41 |
| 0bda:5400 | Realtek... | BillBoard Device             | 5     |            | 43AC1A35D7 |
| 1164:7f07 | YUAN Hi... | STK7700D                     | 5     |            | 857C8BE5D0 |
| 16c0:05dc | Van Ooi... | shared ID for use with li... | 5     |            | E3CFB6B7E6 |
| 17ef:3060 | Lenovo     | Billboard Device             | 5     | usbhid     | FD5A5FBD54 |
| 1b1c:0c08 | Corsair    | H80i v2                      | 5     |            | 227E62B97E |
| 1b71:3002 | Fushicai   | USBTV007 Video Grabber [E... | 5     | usbtv      | AF0164260D |
| 2109:0101 | VIA Labs   | USB 2.0 BILLBOARD            | 5     |            | EF5E47EE93 |
| 22b8:2e76 | Motorol... | moto e5 play                 | 5     | usbfs      | 4AEA7A651A |
| 2433:b200 | ASETEK     | 690LC                        | 5     |            | B75E2928BD |
| 04b8:013c | Seiko E... | Perfection V19               | 4     |            | E0F00FF32B |
| 06cb:009b | Synaptics  |                              | 4     |            | 6FDC52DBF7 |
| 0819:0101 | eLicenser  | License Management and Co... | 4     |            | 2021C0A4A3 |
| 085c:0400 | ColorVi... | Spyder 4                     | 4     |            | C1253B8603 |
| 0ccd:0080 | TerraTe... | DMX 6Fire USB                | 4     | snd_usb... | 74C3A10E25 |
| 131d:0156 | Natural... | TrackIR 4 Pro Head Tracker   | 4     |            | B1F64D81B5 |
| 1782:4001 | Spreadt... | IQ4505 Quad                  | 4     |            | 35B986C185 |
| 17e9:4300 | Display... | USB Display Adapter          | 4     | snd_usb... | 2059C9D9E9 |
| 17e9:6015 | Display... | ThinkPad Hybrid USB-C wit... | 4     | snd_usb... | 5F28B24437 |
| 1b1c:0c15 | Corsair    | H100i Platinum               | 4     |            | 814D24ED49 |
| 2040:0265 | Hauppauge  | dualHD                       | 4     | em28xx     | 8269929E09 |
| 2109:8817 | VIA Labs   | USB Billboard Device         | 4     |            | 25ED159745 |
| 24c6:543a | Unknown... | Xbox ONE Pro Ex controller   | 4     | xpad       | E2923BE323 |
| 2833:0211 | Oculus VR  | Rift Sensor                  | 4     | uvcvideo   | B3E32D1026 |
| 2a70:4ee7 | OnePlus    |                              | 4     |            | A6E6EC4497 |
| 045e:02f9 | Microsoft  | Xbox Embedded Wireless       | 3     |            | 43AC1A35D7 |
| 04b4:00fa | Cypress... | USBSC MFG                    | 3     |            | 216DFBDCC6 |
| 054c:01bb | Sony       | FeliCa S320 [PaSoRi]         | 3     |            | F3208D8466 |
| 05ac:1460 | Apple      |                              | 3     |            | 8EE92AF301 |
| 05c6:9039 | Qualcomm   | Android                      | 3     | usbfs      | 174AED26D5 |
| 0e8d:201c | MediaTek   | M5                           | 3     |            | 3D80EACDFC |
| 1164:3edc | YUAN Hi... | STK7700D                     | 3     |            | F1E1BF19CC |
| 1366:0101 | SEGGER     | J-Link PLUS                  | 3     |            | C964203822 |
| 17e9:4301 | Display... | USB3.0 UHD HDMI Adapter      | 3     | snd_usb... | 988B0D9458 |
| 17e9:4305 | Display... | dynadock U3.0                | 3     | cdc_ncm    | E6D66177E4 |
| 17ef:306c | Lenovo     | USB Billboard                | 3     | usbhid     | 5F8373C716 |
| 17ef:3076 | Lenovo     | USB Billboard                | 3     | usbhid     | 1BB0047E0E |
| 17ef:a354 | Lenovo     | Billboard Device             | 3     | usbhid     | 5F28B24437 |
| 17ef:a38f | Lenovo     | Billboard Device             | 3     | usbhid     | 19276DA8DC |
| 1934:0702 | Feature... | Integrated Consumer Infra... | 3     | mceusb     | 87AFD7DD02 |
| 1a86:5512 | QinHeng... | CH341 in EPP/MEM/I2C mode... | 3     | i2c_ch3... | C1C91FE558 |
| 1b1c:0c03 | Corsair    | H100iGTX Cooler              | 3     |            | 4F4314B0B4 |
| 1b1c:0c12 | Corsair    | H150i Platinum               | 3     |            | 6A34D47E53 |
| 1b1c:0c13 | Corsair    | H115i Platinum               | 3     |            | C8BBE43470 |
| 1d5c:5100 | Fresco ... | Generic Billboard Device     | 3     |            | 23DC7C0455 |
| 2109:0103 | VIA Labs   | USB 2.0 BILLBOARD            | 3     |            | 25ED159745 |
| 2109:8818 | VIA Labs   | USB Billboard Device         | 3     |            | 539C9F807E |
| 2109:8888 | VIA Labs   | USB Billboard Device         | 3     |            | DDDCE22B3D |
| 22b8:2e81 | Motorol... | moto z3                      | 3     | usbfs      | 3E998F19FB |
| 2970:2008 | Mediatek   | IQ4418                       | 3     | usbfs      | 026DF0BC7D |
| 03f0:0667 | Hewlett... | WinUSB                       | 2     | usbhid     | DDDCE22B3D |
| 0458:2019 | KYE Sys... | ColorPage-HR6X Slim          | 2     |            | 0D2C002967 |
| 045e:02ad | Microsoft  | Xbox NUI Audio               | 2     |            | 2A34F25D17 |
| 045e:091e | Microsoft  | XBOX ACC                     | 2     |            | A9A066D4B7 |
| 0471:060c | Philips... | Consumer Infrared Transce... | 2     | mceusb     | 28DFB478B7 |
| 0471:060d | Philips... | Consumer Infrared Transce... | 2     | mceusb     | E7259783D1 |
| 0471:0815 | Philips... | eHome Infrared Receiver      | 2     | mceusb     | 0E8628D300 |
| 0483:374b | STMicro... | ST-LINK/V2.1                 | 2     | cdc_acm    | 497A461951 |
| 04b4:1002 | Cypress... | CY7C63001 R100 FM Radio      | 2     | dsbr100    | 4A6A073320 |
| 04b9:0300 | Rainbow... | SafeNet USB SuperPro/Ultr... | 2     |            | F58375E009 |
| 04d8:e11c | Microch... | TL866CS EEPROM Programmer... | 2     |            | 0432DDBB6C |
| 04f2:a216 | Chicony... | Digital Video Device         | 2     |            | 4F0A8E2C5B |
| 04f3:0c07 | Elan Mi... | ELAN:Fingerprint             | 2     |            | A0CF277545 |
| 04f3:0c28 | Elan Mi... | ELAN:Fingerprint             | 2     |            | DFC83A3DB4 |
| 0502:3643 | Acer       | E39                          | 2     |            | B90C237653 |
| 0572:c68a | Conexan... | EyeTV Stick                  | 2     | dvb_usb... | 4863E51684 |
| 057c:8502 | AVM        | FRITZ!WLAN AC 430            | 2     | mt76x0u    | 25A7B5D49A |
| 0582:012a | Roland     | UM-ONE                       | 2     | snd_usb... | 1E67C4F731 |
| 05c6:6769 | Qualcomm   | A0001                        | 2     |            | 2E7AF7D495 |
| 0609:0322 | SMK Man... | eHome Infrared Receiver      | 2     | mceusb     | 29555CDBC9 |
| 0644:8021 | TEAC       | TASCAM US-122mkII            | 2     | snd_usb... | 7F74A650DB |

