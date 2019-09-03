Most popular USB devices
========================

This is a project to identify most popular USB devices in modern computers and
share detailed lsusb reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo hw-probe -all -upload

Total reports: 52005.

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
| 1043:857c | iCreate... | Xonar U7                     | 11    | snd_usb... | D969A32092 |
| 0955:7002 | Nvidia     | stereo controller            | 8     |            | A1B30D6B32 |
| 041e:322c | Creativ... | SB Omni Surround 5.1         | 7     | snd_usb... | 2933DDC278 |
| 1235:8205 | Focusri... | Scarlett Solo USB            | 7     | snd_usb... | AB69AA73CD |
| 1235:8202 | Focusri... | Scarlett 2i2 USB             | 6     | snd_usb... | 623E24CBA5 |
| 041e:3f19 | Creativ... | E-MU 0204 / USB              | 5     | snd_usb... | 12E892C5EB |
| 041e:3f02 | Creativ... | E-Mu 0202                    | 4     | snd_usb... | D3E963E3FC |
| 0b05:17a8 | ASUSTek... | ASUS Xonar Essence One       | 4     | usbhid     | 14FD5844A7 |
| 0b05:180d | ASUSTek... | STRIX SOUND CARD             | 4     | snd_usb... | 394C81B911 |
| 041e:3f04 | Creativ... | E-Mu 0404                    | 3     | snd_usb... | F380930D83 |
| 0582:012f | Roland     | QUAD-CAPTURE                 | 3     | snd_usb... | 8ADE04AF96 |
| 0b05:180f | ASUSTek... | XONAR SOUND CARD             | 3     | snd_usb... | D082929A57 |
| 0d8c:0004 | C-Media... | USB2.0 High-Speed True HD... | 3     | snd_usb... | 586F0C90D9 |
| 1397:0509 | BEHRING... | UMC404HD 192k                | 3     | snd_usb... | 5A8BAD0B76 |
| 046d:0a0b | Logitech   | ClearChat Pro USB            | 2     | snd_usb... | 4B9D75483A |
| 0499:1506 | Yamaha     | THR5                         | 2     | snd_usb... | CEBC9E7C7E |
| 0499:1704 | Yamaha     | Steinberg UR44               | 2     | snd_usb... | D61154EABE |
| 0499:170b | Yamaha     | Steinberg UR242              | 2     | snd_usb... | 7EFEC12422 |
| 0582:00e6 | Roland     | EDIROL UA-25EX (Advanced ... | 2     | snd_usb... | FE2E4341C3 |
| 0644:8030 | TEAC       | US-1800                      | 2     |            | 75C7FE6B69 |
| 1235:8016 | Focusri... | Focusrite Scarlett 2i2       | 2     | snd_usb... | CE863BAC18 |
| 1235:8200 | Focusri... | Scarlett 2i4 USB             | 2     | snd_usb... | 4E80D3D440 |
| 152a:8750 | Thesyco... | D10                          | 2     | snd_usb... | 6E8096D588 |
| 20b1:3023 | XMOS       | X1S USB DAC                  | 2     | snd_usb... | 0A36000504 |
| b58e:0005 | Blue Mi... |                              | 2     | snd_usb... | CDC565D73D |
| 041e:3f0a | Creativ... | E-MU Tracker Pre / USB       | 1     | snd_usb... | 6996B0918E |
| 0499:170f | Yamaha     | Steinberg UR22mkII           | 1     | snd_usb... | 996F55BB36 |
| 0644:8043 | TEAC       | UD-501                       | 1     | usbhid     | 71D8772E62 |
| 0763:201a | M-Audio    | M-Audio Micro                | 1     |            | 4AFB8F7991 |
| 0763:4009 | M-Audio    | M-Track Plus                 | 1     | snd_usb... | B5DD161856 |
| 0763:400b | Midiman    | M-Track 2X2                  | 1     | snd_usb... | BE604B2A9C |
| 07fd:0005 | Mark of... | 24Ao                         | 1     | snd_usb... | 67D9C7BB6F |
| 08e4:0165 | Pioneer    | USB Audio Device             | 1     | snd_usb... | 2F1A3868EA |
| 095d:9205 | Polycom    | CX600                        | 1     | snd_usb... | 7B334F9FB4 |
| 0b05:17a3 | ASUSTek... | ROG ThunderBolt Audio        | 1     | snd_usb... | C784644541 |
| 0b05:17f3 | ASUSTek... | ASUS EONE MKII USB DAC       | 1     | usbhid     | F599EB6750 |
| 0b05:17f5 | ASUSTek... | ASUS XONAR U5                | 1     | snd_usb... | E8E7E33BB2 |
| 0bda:485a | Realtek... | USB Audio                    | 1     | snd_usb... | CEA175B6F3 |
| 0db0:7926 | Micro S... | USB2.0 High-Speed True HD... | 1     | snd_usb... | 065A4C6977 |
| 1235:8006 | Focusri... | Focusrite Scarlett 2i2       | 1     | snd_usb... | 5DC57BDE0C |
| 1235:8008 | Focusri... | Saffire 6                    | 1     | snd_usb... | 2E214EDAA5 |
| 1235:800a | Focusri... | Scarlett 2i4                 | 1     | snd_usb... | 9BC8084A3E |
| 1235:800e | Focusri... | iTrack Solo                  | 1     | snd_usb... | D1B3D0E283 |
| 1235:801c | Focusri... | Scarlett Solo USB            | 1     | snd_usb... | 13A468E1E4 |
| 1235:8204 | Focusri... | Scarlett 18i8 2nd Gen        | 1     | snd_usb... | F192890A26 |
| 1397:0507 | BEHRING... | UMC202HD 192k                | 1     | snd_usb... | 31261D00B1 |
| 152a:85d3 | Thesyco... | Audinst HUD-DX1              | 1     | snd_usb... | 1B1C811590 |
| 152a:85dd | Thesyco... | SMSL Sanskrit 10th           | 1     | snd_usb... | E3F88D9448 |
| 154e:3005 | D&M Hol... | PM7005                       | 1     | snd_usb... | 1E889CCEFD |
| 17cc:1001 | Native ... | Komplete Audio 6             | 1     | snd_usb... | 7D2057C89D |
| 17cc:1021 | Native ... | Traktor Audio 10             | 1     | snd_usb... | 7D2057C89D |
| 17cc:1330 | Native ... | Traktor Audio 2 MK2          | 1     | usbhid     | DDC37B050D |
| 194f:0103 | PreSonu... | AudioBox 1818 VSL            | 1     | snd_usb... | 5BE101218C |
| 20b1:0002 | XMOS       | USB Audio 2.0                | 1     | snd_usb... | 2EEB0DCBEF |
| 20b1:0008 | XMOS       | Audio                        | 1     | snd_usb... | CBFF9F25B0 |
| 20b1:000a | XMOS       | xCORE USB Audio 2.0          | 1     | snd_usb... | D8358F3D32 |
| 20b1:3008 | XMOS       | iFi (by AMR) HD USB Audio    | 1     | snd_usb... | 9C11BAA82B |
| 22e8:dac2 | Cambrid... | USB Audio 2.0                | 1     | snd_usb... | 7984717E58 |
| 22e8:dac6 | Unknown... | DacMagicXS 2.0               | 1     | snd_usb... | 0C93611C78 |
| 233e:3002 | Aastra     | 6725ip                       | 1     | snd_usb... | B2D3CC175F |
| 249c:930b | M2Tech     | hiFaceTWO UAC2               | 1     | snd_usb... | 53D87B0DB3 |
| 2972:0001 | SmartAc... | FiiO USB Audio Class 2.0 DAC | 1     | snd_usb... | FBC2F0A547 |
| 2a39:3fb0 | RME        | Babyface Pro (71984822)      | 1     | snd_usb... | 9E0B67B32E |

### Bluetooth (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a12:0001 | Cambrid... | Bluetooth Dongle (HCI mode)  | 742   | btusb      | 699B1F26E0 |
| 8087:0a2a | Intel      | Bluetooth Device             | 567   | btusb      | 4C9A2AA59C |
| 0cf3:3005 | Qualcom... | AR3011 Bluetooth             | 496   | btusb      | 3ACD13490F |
| 8087:0a2b | Intel      | Bluetooth Device             | 445   | btusb      | F68CFBE3F5 |
| 8087:07dc | Intel      | Bluetooth Device             | 441   | btusb      | 7637F3DE5F |
| 0cf3:3004 | Qualcom... | AR3012 Bluetooth 4.0         | 387   | ath3k, ... | 53302E45B6 |
| 8087:07da | Intel      | Bluetooth Device             | 283   | btusb      | 7C0CD24986 |
| 8086:0189 | Intel      | Bluetooth Device             | 210   | btusb      | D2006E7A87 |
| 04ca:300b | Lite-On... | Lite-On Bluetooth Device     | 178   | ath3k, ... | 50FFA5DCEC |
| 8087:0aaa | Intel      | Bluetooth Device 9460/9560   | 168   | btusb      | 3A4D90A1C3 |
| 105b:e065 | Foxconn... | BCM43142A0 Bluetooth Module  | 161   | btusb      | 06603D3DCE |
| 8087:0aa7 | Intel      | Bluetooth Device             | 158   | btusb      | C7F97B95C4 |
| 13d3:3362 | IMC Net... | Atheros AR3012 Bluetooth ... | 156   | ath3k, ... | 92AE8C0F3B |
| 0bda:b009 | Realtek... | 802.11n WLAN Adapter         | 137   | btusb      | D7977A3B0E |
| 0bda:b728 | Realtek... | Bluetooth Radio              | 137   | btusb      | 00C22F3924 |
| 0a5c:2101 | Broadcom   | BCM2045 Bluetooth            | 136   | btusb      | 74624FF493 |
| 03f0:171d | Hewlett... | Bluetooth 2.0 Interface [... | 134   | btusb      | 4A6A073320 |
| 04ca:3015 | Lite-On... | Lite-On Bluetooth Device     | 134   | btusb      | 6E04F26B23 |
| 0a5c:219c | Broadcom   | BCM2070 Bluetooth Device     | 134   | btusb      | 3A0FEA4700 |
| 0489:e04e | Foxconn... | Bluetooth Device             | 126   | ath3k, ... | DE168F8DCC |
| 0a5c:217f | Broadcom   | BCM2045B (BDC-2.1)           | 122   | btusb      | FBF8462F41 |
| 03f0:231d | Hewlett... | Broadcom 2070 Bluetooth C... | 111   | btusb      | AB17752168 |
| 0a5c:21b4 | Broadcom   | BCM2070 Bluetooth 2.1 + EDR  | 109   | btusb      | 23E7475693 |
| 0cf3:0036 | Qualcom... | Qualcomm Atheros Bluetoot... | 107   | ath3k, ... | 65A9CF6ADE |
| 0cf3:e005 | Qualcom... | Qualcomm Atheros Bluetoot... | 92    | ath3k, ... | 3548830389 |
| 0cf3:311d | Qualcom... | Bluetooth USB Host Contro... | 88    | ath3k, ... | AB69AA73CD |
| 0cf3:e500 | Qualcom... | Qualcomm Atheros Bluetoot... | 83    | btusb      | DE5FB421D9 |
| 0930:0508 | Toshiba    | Integrated Bluetooth HCI     | 81    | btusb      | 97D9353E2A |
| 0a5c:21e3 | Broadcom   | HP Portable Valentine        | 80    | btusb      | 42DF53B120 |
| 0b05:1712 | ASUSTek... | BT-183 Bluetooth 2.0+EDR ... | 80    | btusb      | 4137AC8F54 |
| 0bda:b002 | Realtek... | Bluetooth Radio              | 80    | btusb      | D607079392 |
| 0b05:1788 | ASUSTek... | BT-270 Bluetooth Adapter     | 78    | btusb      | 49783F833C |
| 0489:e00d | Foxconn... | Broadcom Bluetooth 2.1 De... | 74    | btusb      | 62697BF35B |
| 04ca:3006 | Lite-On... | Lite-On Bluetooth Device     | 74    | ath3k, ... | 7750967159 |
| 0a5c:21e6 | Broadcom   | BCM20702 Bluetooth 4.0 [T... | 74    | btusb      | 6D5F1234C2 |
| 0bda:b721 | Realtek... | Bluetooth Radio              | 71    | btusb      | 8BBDB85BE4 |
| 0489:e00f | Foxconn... | Foxconn T77H114 BCM2070 [... | 68    | btusb      | 801A0452F8 |
| 413c:8187 | Dell       | DW375 Bluetooth Module       | 68    | btusb      | 8C536BE4D8 |
| 0b05:1751 | ASUSTek... | BT-253 Bluetooth Adapter     | 63    | btusb      | 96E310C22E |
| 0bda:8723 | Realtek... | RT Bluetooth Radio           | 62    | btusb      | 891DE458D7 |
| 0bda:b001 | Realtek... | Bluetooth Radio              | 62    | btusb      | 4B70A9D252 |
| 0b05:17cb | ASUSTek... | Broadcom BCM20702A0 Bluet... | 61    | btusb      | 3FB755ED84 |
| 0bda:b00a | Realtek... | Bluetooth Radio              | 60    | btusb      | 4F9294F4B5 |
| 13d3:3423 | IMC Net... | Bluetooth Device             | 57    | ath3k, ... | F8FDA4EFC3 |
| 8087:0025 | Intel      | Bluetooth Device             | 55    | btusb      | 94C3F1BC72 |
| 0cf3:e360 | Qualcom... | Qualcomm Atheros Bluetoot... | 54    | btusb      | 7957C03703 |
| 04ca:2006 | Lite-On... | BCM43142A0 Bluetooth Module  | 53    | btusb      | 2A224752BA |
| 0bda:b008 | Realtek... | Bluetooth Radio              | 51    | btusb      | 1CC2218397 |
| 0cf3:e004 | Qualcom... | Bluetooth USB Host Contro... | 51    | ath3k, ... | F72534E2D2 |
| 0cf3:e300 | Qualcom... | Qualcomm Atheros Bluetoot... | 50    | btusb      | 3A71C37AE2 |
| 0a5c:21e8 | Broadcom   | BCM20702A0 Bluetooth 4.0     | 49    | btusb      | A9406FFA03 |
| 13d3:3315 | IMC Net... | Bluetooth module             | 48    | btusb      | 4ADFAB3C4E |
| 0a5c:21d7 | Broadcom   | BCM43142 Bluetooth 4.0       | 47    | btusb      | 67CD98E6C7 |
| 13d3:3402 | IMC Net... | Bluetooth USB Host Contro... | 47    | ath3k, ... | 2D1845C282 |
| 0489:e036 | Foxconn... | Bluetooth USB Host Contro... | 46    | ath3k, ... | B56B7F6394 |
| 0cf3:e009 | Qualcom... | Qualcomm Atheros Bluetoot... | 46    | btusb      | 9402076861 |
| 0a5c:216d | Broadcom   | BCM43142A0 Bluetooth 4.0     | 44    | btusb      | 2EC22FA87A |
| 13d3:3394 | IMC Net... | Bluetooth                    | 44    | btusb      | 3B5C8ADA46 |
| 0a5c:2145 | Broadcom   | BCM2045B (BDC-2.1) [Bluet... | 42    | btusb      | A23E000798 |
| 0930:021d | Toshiba    | RT Bluetooth Radio           | 41    | btusb      | 806B890CCF |
| 148f:1000 | Ralink ... | Motorola BC4 Bluetooth 3.... | 41    | btusb      | 36FF276D26 |
| 413c:8140 | Dell       | Wireless 360 Bluetooth       | 41    | btusb      | F205356420 |
| 0bda:0821 | Realtek... | Bluetooth Radio              | 40    | btusb      | 3E47232411 |
| 13d3:3496 | IMC Net... | Bluetooth Device             | 40    | btusb      | 7D2B995B44 |
| 413c:8126 | Dell       | Wireless 355 Bluetooth       | 39    | btusb      | D400943350 |
| 0b05:179c | ASUSTek... | Bluetooth Device             | 38    | btusb      | BCF1D99475 |
| 0cf3:e007 | Qualcom... | Qualcomm Atheros Bluetoot... | 38    | btusb      | EB49973873 |
| 04ca:3010 | Lite-On... | Lite-On Bluetooth Device     | 37    | ath3k, ... | FDD61F096B |
| 0a5c:2110 | Broadcom   | BCM2045B (BDC-2) [Bluetoo... | 37    | btusb      | 8457BB5791 |
| 0a5c:21e1 | Broadcom   | HP Portable SoftSailing      | 37    | btusb      | 68A86E6E3F |
| 0489:e078 | Foxconn... | Bluetooth Device             | 36    | ath3k, ... | 1C77D7A584 |
| 04ca:3005 | Lite-On... | Bluetooth USB Host Contro... | 36    | ath3k, ... | A1A1F1965A |
| 0930:0214 | Toshiba    | Askey Bluetooth Module       | 36    | btusb      | BD758B3E12 |
| 0bda:c024 | Realtek... | Bluetooth Radio              | 36    | btusb      | C61C9E33F6 |
| 1131:1004 | Integra... | Bluetooth Device             | 36    | btusb      | 6A3D0BEA9D |
| 044e:3017 | Alps El... | BCM2046 Bluetooth Device     | 34    | btusb      | A3C4D07088 |
| 04ca:3016 | Lite-On... | Lite-On Bluetooth Device     | 33    | btusb      | C80CAABFC9 |
| 13d3:3408 | IMC Net... | Bluetooth Device             | 33    | ath3k, ... | 412366312B |
| 05ac:8215 | Apple      | Built-in Bluetooth 2.0+ED... | 32    | btusb      | 561B991E16 |
| 0bda:b006 | Realtek... | Bluetooth Radio              | 32    | btusb      | 3F7F72D7A2 |
| 0a5c:21f4 | Broadcom   | BCM20702A0                   | 31    | btusb      | FA98476936 |
| 0489:e032 | Foxconn... | Broadcom BCM20702 Bluetooth  | 30    | btusb      | F3D7E4E13D |
| 0cf3:3008 | Qualcom... | Bluetooth (AR3011)           | 30    | ath3k, ... | 3CCACD3312 |
| 0a5c:21bc | Broadcom   | BCM2070 Bluetooth 2.1 + EDR  | 29    | btusb      | 11784493FE |
| 0bda:b00b | Realtek... | Bluetooth Radio              | 29    | btusb      | 0BEFDCEA98 |
| 13d3:3526 | IMC Net... | Bluetooth Radio              | 29    | btusb      | B6B40DE397 |
| 413c:8197 | Dell       | Dell Wireless 380 Bluetoo... | 29    | btusb      | 8C26DF88EE |
| 0cf3:3121 | Qualcom... | Qualcomm Atheros Bluetoot... | 28    | ath3k, ... | EA670C7B0D |
| 0489:e062 | Foxconn... | BCM43142A0                   | 26    | btusb      | 66E469F722 |
| 0a5c:2150 | Broadcom   | BCM2046 Bluetooth Device     | 26    | btusb      | 601D53F9EB |
| 13d3:3304 | IMC Net... | Asus Integrated Bluetooth... | 26    | ath3k, ... | DB1BD4EC31 |
| 04ca:3014 | Lite-On... | Qualcomm Atheros Bluetooth   | 25    | ath3k, ... | D91699583D |
| 0489:e0a2 | Foxconn... | Bluetooth Device             | 24    | btusb      | 5D2CB1E1B0 |
| 0a5c:216c | Broadcom   | BCM43142A0 Bluetooth Device  | 24    | btusb      | DC6C804E81 |
| 148f:2000 | Ralink ... | CSR BS8510                   | 24    | btusb      | ED98A45D81 |
| 0a5c:21f1 | Broadcom   | HP Portable Bumble Bee       | 23    | btusb      | E7C8A22676 |
| 0489:e069 | Foxconn... | BT                           | 22    | mt76xx     | 91D9C778CB |
| 0cf3:3002 | Qualcom... | AR3011 Bluetooth             | 22    | ath3k, ... | E03A8C0C89 |
| 13d3:3490 | IMC Net... | Bluetooth Device             | 22    | ath3k, ... | 949FD12104 |
| 0489:e046 | Foxconn... | BCM20702A0                   | 21    | btusb      | 2DABFA1484 |

### Camera (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:0825 | Logitech   | Webcam C270                  | 322   | uvcvideo   | 8C4047657D |
| 0ac8:3420 | Z-Star ... | Venus USB2.0 Camera          | 245   | uvcvideo   | B0B570F44B |
| 0ac8:c40a | Z-Star ... | A4 TECH USB2.0 PC Camera J   | 149   | uvcvideo   | 78E822AD79 |
| 5986:0295 | Acer       | Lenovo EasyCamera            | 141   | uvcvideo   | AE0E410A7F |
| 1bcf:2c18 | Sunplus... | HD WebCam                    | 136   | uvcvideo   | 11B9C937C9 |
| 0c45:6340 | Microdia   | Camera                       | 125   | uvcvideo   | C0B50F9AE1 |
| 04e8:6860 | Samsung... | GT-I9100 Phone [Galaxy S ... | 120   | usbfs      | D7977A3B0E |
| 13d3:5a01 | IMC Net... | USB2.0 VGA UVC WebCam        | 115   | uvcvideo   | 0FAD7AC4EB |
| 064e:a103 | Suyin      | Acer/HP Integrated Webcam... | 112   | uvcvideo   | 77E3B20E26 |
| 13d3:5710 | IMC Net... | UVC VGA Webcam               | 111   | uvcvideo   | 826F5492EB |
| 0402:9665 | ALi        | Gateway Webcam               | 101   | uvcvideo   | D023F50697 |
| 058f:a014 | Alcor M... | Asus Integrated Webcam       | 101   | uvcvideo   | 6B25B8982D |
| 0ac8:3450 | Z-Star ... | Vimicro USB Camera (Altair)  | 101   | uvcvideo   | F0CE444FB7 |
| 0c45:62c0 | Microdia   | Sonix USB 2.0 Camera         | 101   | uvcvideo   | 4A6A073320 |
| 13d3:5130 | IMC Net... | Integrated Webcam            | 98    | uvcvideo   | 527313B5FF |
| 1bcf:2883 | Sunplus... | ASUS USB2.0 Webcam           | 91    | uvcvideo   | 92AE8C0F3B |
| 2232:1020 | Silicon... | WebCam SC-0311139N           | 91    | uvcvideo   | EE56C112BB |
| 04f2:b071 | Chicony... | 2.0M UVC Webcam / CNF7129    | 87    | uvcvideo   | 2D4D5EFCB2 |
| 1210:25f4 | DigiTech   | USB 2.0 PC Camera            | 84    | uvcvideo   | BC68546696 |
| 04f2:b272 | Chicony... | Lenovo EasyCamera            | 82    | uvcvideo   | BD698398A7 |
| 046d:0819 | Logitech   | Webcam C210                  | 80    | uvcvideo   | B0D2314507 |
| 046d:081b | Logitech   | Webcam C310                  | 79    | uvcvideo   | 39C0FBE126 |
| 04f2:b1d6 | Chicony... | CNF9055 Toshiba Webcam       | 78    | uvcvideo   | FE2AB22987 |
| 13d3:5702 | IMC Net... | UVC VGA Webcam               | 78    | uvcvideo   | B658C90327 |
| 046d:0826 | Logitech   | HD Webcam C525               | 76    | snd_usb... | 699B1F26E0 |
| 046d:082b | Logitech   | Webcam C170                  | 76    | uvcvideo   | 48FEA246F9 |
| 0bda:57b5 | Realtek... | USB Camera                   | 76    | uvcvideo   | FDD61F096B |
| 18ec:3399 | Arkmicr... | USB2.0 PC CAMERA             | 75    | uvcvideo   | 969A371A99 |
| 2232:1008 | Silicon... | WebCam SCB-1100N             | 73    | uvcvideo   | 82EA1BF753 |
| 04f2:b47f | Chicony... | VGA Webcam                   | 72    | uvcvideo   | A1D2E02773 |
| 05ac:12a8 | Apple      | iPhone5/5C/5S/6              | 72    | ipheth     | 4C9A2AA59C |
| 093a:2700 | Pixart ... | A4 TECH PC Camera            | 70    | uvcvideo   | C7934C20A0 |
| 04f2:b008 | Chicony... | USB 2.0 Camera               | 69    | uvcvideo   | 2664F9638B |
| 04f2:b1d8 | Chicony... | 1.3M WebCam                  | 69    | uvcvideo   | E01CCE8165 |
| 13d3:5188 | IMC Net... | USB2.0 UVC HD Webcam         | 68    | uvcvideo   | 2D1845C282 |
| 0bda:5728 | Realtek... | Lenovo EasyCamera            | 67    | uvcvideo   | 4FC85D1C31 |
| 13d3:5711 | IMC Net... | USB 2.0 UVC VGA WebCam       | 67    | uvcvideo   | A84D413088 |
| 04f2:b40a | Chicony... | USB2.0 HD UVC WebCam         | 66    | uvcvideo   | F71E42FC3C |
| 064e:a101 | Suyin      | Acer CrystalEye Webcam       | 66    | uvcvideo   | 5A52F8FD85 |
| 046d:082d | Logitech   | HD Pro Webcam C920           | 64    | snd_usb... | BDA3B81C14 |
| 064e:a219 | Suyin      | 1.3M WebCam (notebook ema... | 64    | uvcvideo   | 690FFF1815 |
| 058f:5608 | Alcor M... | USB 2.0 Web Camera           | 63    | uvcvideo   | 4414412FCB |
| 04f2:b374 | Chicony... | HD WebCam                    | 62    | uvcvideo   | DE3BBCF659 |
| 04f2:b337 | Chicony... | HD WebCam                    | 61    | uvcvideo   | E67DFC255A |
| 2232:1006 | Image P... | WebCam SCB-0355N             | 61    | uvcvideo   | 137FB608D0 |
| 05c8:021e | Cheng U... | HP Webcam-101                | 60    | uvcvideo   | 7306A03690 |
| 2232:1028 | Silicon... | WebCam SC-03FFL11939N        | 59    | uvcvideo   | 359A01778D |
| 5986:0652 | Acer       | Lenovo EasyCamera            | 59    | uvcvideo   | 8FF0A9A350 |
| 04f2:b52b | Chicony... | USB2.0 VGA UVC WebCam        | 56    | uvcvideo   | 5AEE6B7CA7 |
| 0ac8:c33f | Z-Star ... | Webcam                       | 56    | uvcvideo   | 3A0FEA4700 |
| 1e4e:0102 | Cubeternet | GL-UPC822 UVC WebCam         | 54    | uvcvideo   | E1D8ADF3C9 |
| 058f:b002 | Alcor M... | Acer Integrated Webcam       | 52    | uvcvideo   | 4C990A61B6 |
| 0bda:57b3 | Realtek... | Acer 640 x 480 laptop camera | 51    | uvcvideo   | 2619209EC5 |
| 0bda:57de | Realtek... | USB2.0 VGA UVC WebCam        | 50    | uvcvideo   | F8FDA4EFC3 |
| 04f2:b044 | Chicony... | Acer CrystalEye Webcam       | 49    | uvcvideo   | 6029A4A18A |
| 5986:0292 | Acer       | Lenovo EasyCamera            | 49    | uvcvideo   | F9F3745636 |
| 046d:0829 | Logitech   | Webcam C110                  | 48    | uvcvideo   | D6764F0C12 |
| 04f2:b230 | Chicony... | Integrated HP HD Webcam      | 48    | uvcvideo   | 15E5D2BB9D |
| 2232:1029 | Silicon... | WebCam SC-13HDL11939N        | 48    | uvcvideo   | 0F042024B4 |
| 04f2:b1e5 | Chicony... | USB2.0 0.3M UVC WebCam       | 47    | uvcvideo   | F47F34752E |
| 04f2:b469 | Chicony... | HD WebCam                    | 46    | uvcvideo   | 8B3744250A |
| 0408:a060 | Quanta ... | HD WebCam                    | 44    | uvcvideo   | C80CAABFC9 |
| 04f2:b43b | Chicony... | USB 2.0 Camera               | 44    | uvcvideo   | D607079392 |
| 04f2:b52d | Chicony... | HP Webcam                    | 44    | uvcvideo   | 1CC2218397 |
| 045e:0779 | Microsoft  | LifeCam HD-3000              | 42    | uvcvideo   | 7FDD5F778A |
| 04f2:b3f6 | Chicony... | HD WebCam (Acer)             | 42    | uvcvideo   | 07CD36611F |
| 04f2:b40e | Chicony... | HP Truevision HD camera      | 42    | uvcvideo   | 4B70A9D252 |
| 13d3:5122 | IMC Net... | 2M Integrated Webcam         | 42    | uvcvideo   | 49783F833C |
| 13d3:5165 | IMC Net... | USB Camera                   | 42    | uvcvideo   | F695A76E03 |
| 0402:7675 | ALi        | WebCam                       | 41    | uvcvideo   | 62BB2E7B3C |
| 04f2:b2e1 | Chicony... | Lenovo EasyCamera            | 41    | uvcvideo   | F3D7E4E13D |
| 1908:2311 | GEMBIRD    | USB2.0 PC CAMERA             | 40    | uvcvideo   | 1579402536 |
| 2232:1005 | Silicon... | WebCam SCB-0385N             | 40    | uvcvideo   | 4B260556B7 |
| 04f2:b23b | Chicony... | CNFA078                      | 39    | uvcvideo   | 9A249DA8EE |
| 04f2:b209 | Chicony... | WebCam                       | 38    | uvcvideo   | 2CD19D38C6 |
| 05a9:2640 | OmniVis... | OV2640 Webcam                | 38    | uvcvideo   | 2967AF01D8 |
| 0bda:579a | Realtek... | Lenovo EasyCamera            | 38    | uvcvideo   | 09141B681A |
| 04f2:b249 | Chicony... | HP Webcam-101                | 37    | uvcvideo   | A7E86DE30D |
| 0bda:5801 | Realtek... | USB2.0-Camera                | 37    | uvcvideo   | DDF30C670A |
| 0c45:6513 | Microdia   | Lenovo EasyCamera            | 37    | uvcvideo   | 7A87F02269 |
| 04f2:b221 | Chicony... | integrated camera            | 36    | uvcvideo   | FBF8462F41 |
| 04f2:b307 | Chicony... | TOSHIBA Web Camera - HD      | 36    | uvcvideo   | 7C82C563B9 |
| 058f:a016 | Alcor M... | ASUS USB2.0 WebCam           | 36    | uvcvideo   | 6A47875DF8 |
| 064e:c21c | Suyin      | 1.3M HD WebCam               | 36    | uvcvideo   | F0F215F1E4 |
| 064e:e263 | Suyin      | HP TrueVision HD Integrat... | 36    | uvcvideo   | 0C02DFD17B |
| 1bcf:2880 | Sunplus... | Laptop_Integrated_Webcam_HD  | 36    | uvcvideo   | 2C903F36D0 |
| 04f2:b483 | Chicony... | USB2.0 VGA UVC WebCam        | 35    | uvcvideo   | F8E8617476 |
| 05ac:8507 | Apple      | Built-in iSight              | 35    | uvcvideo   | 9F753AC669 |
| 064e:e330 | Suyin      | HD WebCam                    | 35    | uvcvideo   | D3813AFBF5 |
| 04f2:b012 | Chicony... | 1.3 MPixel UVC Webcam        | 34    | uvcvideo   | 926753D3C7 |
| 04f2:b404 | Chicony... | USB2.0 HD UVC WebCam         | 34    | uvcvideo   | EF445A792B |
| 05ac:8509 | Apple      | FaceTime HD Camera           | 34    | uvcvideo   | 16BDB52C40 |
| 064e:d214 | Suyin      | WebCam                       | 34    | uvcvideo   | 8CE41DB531 |
| 046d:081d | Logitech   | HD Webcam C510               | 33    | snd_usb... | 23ACB95370 |
| 046d:082c | Logitech   | HD Webcam C615               | 33    | uvcvideo   | EA54CD12AB |
| 04f2:b217 | Chicony... | Lenovo Integrated Camera ... | 33    | uvcvideo   | 23DAC0F1B6 |
| 04f2:b2e2 | Chicony... | Lenovo EasyCamera            | 33    | uvcvideo   | 891002E8F2 |
| 04f2:b2fa | Chicony... | Integrated Camera            | 33    | uvcvideo   | B9CC4FFB0F |
| 05c8:0403 | Cheng U... | Webcam                       | 33    | uvcvideo   | 23E7475693 |
| 04f2:b26f | Chicony... | USB2.0 0.3M UVC WebCam       | 32    | uvcvideo   | 6FB4432F5A |

### Card reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:0129 | Realtek... | RTS5129 Card Reader Contr... | 1697  | rtsx_usb   | 7957C03703 |
| 0bda:0139 | Realtek... | RTS5139 Card Reader Contr... | 374   | rtsx_usb   | F6A627C008 |
| 0aec:3260 | Neodio ... | 7-in-1 Card Reader           | 7     | uas, us... | A3B6AB3380 |
| 0cf2:6250 | ENE Tec... | SD card reader (UB6250)      | 6     | ums_ene... | A6F434EBC3 |
| 0c4b:0500 | Reiner ... | cyberJack RFID standard d... | 5     | usbfs      | 2F2703FBEB |
| 072f:9000 | Advance... | ACR38 AC1038-based Smart ... | 4     | usbfs      | 590B559F72 |
| 0d8c:5200 | C-Media... | Mass Storage Controller(0... | 4     |            | 38C8446DA8 |
| 0c4b:0501 | Reiner ... | cyberJack RFID comfort du... | 2     |            | 37BE65DDB4 |
| 047b:020b | Silitek    | SK-3105 SmartCard Reader     | 1     | usbhid     | 986AC800BA |
| 0b0c:003f | Todos AB   | Todos C400 smartcard cont... | 1     |            | 251D958CA9 |
| 0bda:0150 | Realtek... | USB 2.0 Card Reader          | 1     |            | 3C44204AA0 |
| 0ca6:0010 | Castles... | EZUSB PC/SC Smart Card Re... | 1     |            | 21FB8F59A4 |
| 174f:1105 | Syntek     | SM-MS/Pro-MMC-XD Card Reader | 1     | uvcvideo   | E718456945 |

### Cdrom (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 8564:1000 | Transcend  | TS32GJF370 JetFlash 32GB     | 790   | uas, us... | E9BD04F647 |
| 174c:55aa | ASMedia... | Name: ASM1051E SATA 6Gb/s... | 128   | usb_sto... | D7977A3B0E |
| 152d:2329 | JMicron... | JM20329 SATA Bridge          | 125   | usb_sto... | D569843A2D |
| 04c5:2028 | Fujitsu    | External HDD 128GB           | 93    | uas, us... | 240876777B |
| 152d:2338 | JMicron... | JM20337 Hi-Speed USB to S... | 68    | uas, us... | 36981C6FBC |
| 1bcf:0c31 | Sunplus... | SPIF30x Serial-ATA bridge    | 60    | uas, us... | 92D3DF20F4 |
| 0e8d:1806 | MediaTek   | Samsung SE-208AB Slim Por... | 47    | usb_sto... | 046006226D |
| 0e8d:1887 | MediaTek   | DVDRAM GP60NS50              | 42    | usb_sto... | 11B9C937C9 |
| 152d:0578 | JMicron... | JMS567 SATA 6Gb/s bridge     | 34    | uas, us... | AFD92BF265 |
| 13fd:0840 | Initio     | INIC-1618L SATA 100GB        | 31    | uas, us... | 1D7422A66F |
| 0928:0010 | PLX Tec... | Ext Hard Disk 500GB          | 30    | uas, us... | FE2AB22987 |
| 19d2:1403 | ZTE WCD... | USB SCSI CD-ROM              | 28    | uas, us... | 7B7903FC02 |
| 0e8d:1836 | MediaTek   | Samsung SE-S084 Super Wri... | 24    | usb_sto... | 6A3D0BEA9D |
| 046b:ff20 | America... | Virtual CDROM0               | 19    | uas, us... | 4391DFF8D2 |
| 152d:2339 | JMicron... | JM20339 SATA Bridge          | 18    | uas, us... | 46324F79EA |
| 13fd:1040 | Initio     | INIC-1511L PATA Bridge       | 16    | usb_sto... | 9687F320FD |
| 04fc:0c25 | Sunplus... | SATALink SPIF225A 320GB      | 15    | uas, us... | DA55F26B0D |
| 12d1:107e | Huawei ... | File-CD Gadget               | 15    | uas, us... | 341917FD42 |
| 0781:5406 | SanDisk    | Cruzer Micro U3 2GB          | 14    | uas, us... | 6E8256A0D7 |
| 174c:1351 | ASMedia... | DVDRW DA8AESH                | 14    | uas        | E8755C7EF8 |
| 14cd:6600 | Super Top  | M110E PATA bridge            | 13    | usb_sto... | 782AFB3ED5 |
| 19d2:1410 | ZTE WCD... | LTE Technologies MSM         | 13    | uas, us... | 0E5869D47C |
| 152e:1640 | LG (HLDS)  | DVDRAM GE20NU11              | 12    | usb_sto... | 81BAC67CEE |
| 13fd:0940 | Initio     | ASUS SBW-06D2X-U 500GB       | 11    | uas, us... | 48DACF6BD2 |
| 1c6b:a223 | Philips... | SDRW-08D2S-U                 | 11    | usb_sto... | CDC565D73D |
| 13fd:3940 | Initio     | external DVD burner ECD81... | 10    | uas, us... | 277055C3E7 |
| 13fd:3e40 | Initio     | ZALMAN ZM-VE350 256GB        | 10    | uas, us... | CA27A3BAF8 |
| 048d:1176 | Integra... | USB Flash Disk 16GB          | 9     | uas, us... | 34905CB301 |
| 1f75:0611 | Innosto... | EZEX-75WN4A0 1TB             | 9     | uas, us... | ACDBCD6A13 |
| 054c:02d5 | Sony       | DVD-RAM UJ862PS              | 8     | uas, us... | 3284C77676 |
| 13fd:1640 | Initio     | INIC-1610L SATA Bridge       | 8     | usb_sto... | BDEC0242AA |
| 152e:2507 | LG (HLDS)  | PL-2507 IDE Controller       | 8     | uas, us... | E8794A0676 |
| 1c6b:a222 | Philips... | DVD Writer Slimtype eTAU108  | 8     | uas, us... | 9600A62F92 |
| 2e04:c025 | Linux      | File-CD Gadget               | 8     | uas, us... | 561770352F |
| 12d1:1082 | Huawei ... | File-CD Gadget               | 7     | uas, us... | 7872901FE9 |
| 152e:2571 | LG (HLDS)  | DVDRAM GP08NU6B              | 7     | uas, us... | 123447177A |
| 0b05:7774 | ASUSTek... | Zenfone GO (ZB500KL) (RND... | 6     | rndis_host | 92550C4EB8 |
| 0e8d:1956 | MediaTek   | Samsung SE-506 Portable B... | 6     | usb_sto... | 32AFE6A3D4 |
| 152d:2519 | JMicron... | Transcend                    | 6     | uas, us... | 14FEBB13AA |
| 04b7:0100 | Compal ... | DVDRW DA8AESH                | 5     | uas, us... | DEFB86D43A |
| 04e8:685b | Samsung... | GT-I9100 Phone [Galaxy S ... | 5     | uas, us... | DC58FEE893 |
| 067b:2571 | Prolifi... | DVDRAM GE24NU30              | 5     | usb_sto... | A5DD292F0E |
| 13fd:2040 | Initio     | Samsung Writemaster exter... | 5     | usb_sto... | 4E2CEB128E |
| 413c:9016 | Dell       | DVD+/-RW DW316               | 5     | usb_sto... | 42A2D2DC72 |
| 0476:059b | AESP       | DVD RW AD-7580S              | 4     | usb_sto... | B297051783 |
| 04cf:8818 | Myson C... | USB2.0 to ATAPI Bridge Co... | 4     | usb_sto... | F45F113932 |
| 054c:0377 | Sony       | BD-CMB UJ-120                | 4     | uas, us... | 25C759104C |
| 0bb4:0f25 | HTC (Hi... | One M8                       | 4     | uas, us... | 447E6C6392 |
| 0bda:1a2b | Realtek... | USB Disk autorun             | 4     | uas, us... | B4020C7021 |
| 13fd:0842 | Initio     | CDDVDW SE-T084P              | 4     | usb_sto... | 02B9759D77 |
| 152d:0562 | JMicron... | MK2035GSS                    | 4     | uas        | 42A2D2DC72 |
| 054c:03dc | Sony       | DVD RW DRX-S70U              | 3     | usb_sto... | 7A353432A6 |
| 05c6:92fe | Qualcomm   | Disk                         | 3     | uas, us... | D06E1D8C5B |
| 05e3:0701 | Genesys... | USB 2.0 IDE Adapter          | 3     | usb_sto... | 15252DCF05 |
| 05e3:0719 | Genesys... | SATA adapter                 | 3     | uas, us... | 463CF097DA |
| 0ecd:a100 | Lite-On IT | LDW-411SX DVD/CD Rewritab... | 3     | usb_sto... | 48DACF6BD2 |
| 13fd:0841 | Initio     | Samsung SE-T084M DVD-RW      | 3     | usb_sto... | 84E58AC976 |
| 1782:5d03 | Spreadt... | umopenphone 34GB             | 3     | uas, us... | 1556198BA1 |
| 2e04:c026 | Linux      | File-CD Gadget               | 3     | uas, us... | 5E0DC6DFA3 |
| 03f0:2027 | Hewlett... | Virtual DVD-ROM              | 2     | usb_sto... | D9B1EC3C37 |
| 0402:5621 | ALi        | M5621 High-Speed IDE Cont... | 2     | uas, us... | 2458B122E5 |
| 0409:0056 | NEC Com... | DW-224E-C                    | 2     | usb_sto... | 53ABDA4642 |
| 059b:0155 | Iomega     | DVDRAM GSA-4081B             | 2     | uas, us... | 3EE5BD924C |
| 05ac:1500 | Apple      | SuperDrive [A1379]           | 2     | uas, us... | 3419AE2627 |
| 0789:0197 | Logitec    | DVDRAM GP67N                 | 2     | usb_sto... | 266D78E723 |
| 0930:0c06 | Toshiba    | SuperMultiPA3761             | 2     | usb_sto... | D49249D475 |
| 0b05:1797 | ASUSTek... | DVDRAM GU60N                 | 2     | usb_sto... | E2A6782664 |
| 0b05:5600 | ASUSTek... | File-CD Gadget               | 2     | uas, us... | 635226B290 |
| 0e8d:1807 | MediaTek   | SDRW-08D2S-U                 | 2     | usb_sto... | 0784C6115A |
| 1058:070a | Western... | My Passport Essential (WD... | 2     | usb_sto... | B42452302F |
| 12d1:1052 | Huawei ... | MT7-L09                      | 2     | uas, us... | 8B0A240FA2 |
| 12d1:107f | Huawei ... | File-CD Gadget               | 2     | uas, us... | BD698398A7 |
| 152d:2337 | JMicron... | ATA/ATAPI Bridge             | 2     | uas, us... | 26399C140A |
| 19d2:0501 | ZTE WCD... | File-Stor Gadget             | 2     | uas, us... | 88BD859F3F |
| 03f0:4907 | Hewlett... | DVD Writer 556s              | 1     | uas, us... | 0504CC20A9 |
| 03f0:5907 | Hewlett... | DVD Writer 557s              | 1     | usb_sto... | B91A0B2CB2 |
| 0408:ea42 | Quanta ... | modem CD-ROM                 | 1     | option,... | 8EC72CB3E0 |
| 0409:0840 | NEC Com... | CD/DVDW SE-T084L             | 1     | usb_sto... | A67AF78289 |
| 0411:0094 | BUFFALO    | DVD-RAM GH22NP20             | 1     | usb_sto... | FAD3CD1AA5 |
| 0411:01b8 | BUFFALO    | BD-RW BDR-209M               | 1     | usb_sto... | 692C95368A |
| 046e:3005 | Behavio... | Mass Storage Device          | 1     | uas, us... | 6960E1BAAE |
| 0471:0823 | Philips... | DVD RW AD-7200A              | 1     | uas, us... | F3D9E45F07 |
| 0471:082c | Philips... | SPD3200L1                    | 1     | uas, us... | FE5F95F298 |
| 04b3:4487 | IBM        | RW/DVD GCC-4247N             | 1     | uas, us... | 1501370AB2 |
| 04da:250a | Panason... | DVD-RAM UJ-833S              | 1     | usb_sto... | 497FA7F67C |
| 057c:62ff | AVM        | AVM Fritz!WLAN USB (in CD... | 1     | usb_sto... | D772023A07 |
| 058f:6395 | Alcor M... | DV-W28SS-R                   | 1     | uas, us... | 26CFAAC001 |
| 059b:0252 | Iomega     | Optical                      | 1     | usb_sto... | 08A4E0713E |
| 05c6:6000 | Qualcomm   | Siemens SG75                 | 1     | option,... | 90322CEA13 |
| 060f:1007 | Joinsoo... | DVD A DS8A4S                 | 1     | usb_sto... | 853CE95D3B |
| 06e6:c200 | Tiger J... | Internet Phone               | 1     | uas, us... | 004DE30AFC |
| 0718:4006 | Imation    | 8x Slim DVD Multi-Format ... | 1     | usb_sto... | 9CBBBDBFD2 |
| 0789:00cc | Logitec    | VIRTUAL CD-ROM               | 1     | uas, us... | 8F38D85DBF |
| 0840:009d | Argosy ... | CD/DVDW SN-W082B             | 1     | usb_sto... | 38EF812F4E |
| 08e4:0150 | Pioneer    | DVD-RW DVR-XD09              | 1     | usb_sto... | E8C3307D08 |
| 08e4:017a | Pioneer    | BD-RW BDR-XD05               | 1     | usb_sto... | 528F9F1A24 |
| 08e4:0193 | Pioneer    | DVD-RW DVR-XT11              | 1     | uas, us... | 75DE067DF6 |
| 093b:004a | Plextor    | DVDR PX-L611U                | 1     | uas, us... | 14B329796C |
| 093b:004e | Plextor    | DVDR PX-650US                | 1     | usb_sto... | 8991709C89 |
| 0b05:5601 | ASUSTek... | Device CD-ROM                | 1     | uas, us... | 286A4000F8 |

### Chipcard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a5c:5800 | Broadcom   | BCM5880 Secure Applicatio... | 156   | usbfs      | CA6EFEBBD7 |
| 058f:9540 | Alcor M... | AU9540 Smartcard Reader      | 76    | usbfs      | 0F9287651D |
| 0b97:7772 | O2 Micro   | OZ776 CCID Smartcard Reader  | 69    | usbfs      | F40C3D18FB |
| 147e:2020 | Upek       | TouchChip Fingerprint Cop... | 58    |            | DF1FD87B87 |
| 17ef:1003 | Lenovo     | Integrated Smart Card Reader | 52    | usbfs      | 037CAC7A3D |
| 0a5c:5801 | Broadcom   | BCM5880 Secure Applicatio... | 41    | usbfs      | FFEF7E12D0 |
| 0a5c:5832 | Broadcom   | 5880                         | 23    | usbfs      | B9281326D7 |
| 0b97:7762 | O2 Micro   | Oz776 SmartCard Reader       | 18    |            | BF8ACC676E |
| 0529:0620 | Aladdin... | Token JC                     | 13    | usbfs      | 0CFA900AB7 |
| 0a5c:5834 | Broadcom   | 5880                         | 13    | usbfs      | 90E9F8DFAD |
| 058f:9520 | Alcor M... | EMV Certified Smart Card ... | 10    | usbfs      | 1EFF42042A |
| 072f:90cc | Advance... | ACR38 SmartCard Reader       | 8     | usbfs      | 33F663A020 |
| 08e6:34ec | Gemalto... | Compact Smart Card Reader... | 8     | usbfs      | 85B9549CFF |
| 076b:1021 | OmniKey    | CardMan 1021                 | 6     | usbfs      | 3D9E77AE8A |
| 0a5c:5804 | Broadcom   | BCM5880 Secure Applicatio... | 6     |            | 4926835893 |
| 0bda:0165 | Realtek... | Smart Card Reader Interface  | 6     |            | 7B99FD4C95 |
| 04e6:5116 | SCM Mic... | SCR331-LC1 / SCR3310 Smar... | 3     |            | B511052CC4 |
| 072f:2200 | Advance... | ACR122U                      | 3     | pn533_usb  | C13D443BF5 |
| 0a5c:5805 | Broadcom   | 5880                         | 3     |            | 5E0DC6DFA3 |
| 1a44:0001 | VASCO D... | Digipass 905 SmartCard Re... | 3     |            | AE29C83D96 |
| 072f:90de | Advance... | Token USB 64K                | 2     | usbfs      | 7F6DBA9244 |
| 072f:b000 | Advance... | ACR3901U                     | 2     |            | A44B651190 |
| 076b:3021 | OmniKey    | CardMan 3121                 | 2     | usbfs      | B45F44A0F7 |
| 08e6:3437 | Gemalto... | GemPC Twin SmartCard Reader  | 2     |            | BB385761F8 |
| 0a89:0025 | Aktiv      | Rutoken lite                 | 2     | usbfs      | 7F6DBA9244 |
| 0c4b:9102 | Reiner ... | cyberJack RFID basis cont... | 2     |            | 66EEFE25AF |
| 0ca6:00a0 | Castles... | EZCCID Smart Card Reader     | 2     |            | 3DC7A36CB3 |
| 0dc3:1004 | Athena ... | ASEDrive CCID                | 2     |            | FB13C4ACE3 |
| 24dc:0101 | ARDS       | JaCarta                      | 2     |            | DA308A78C4 |
| 0403:e3b4 | Future ... | Parsec Desktop Reader PR-... | 1     |            | 775160993D |
| 048d:1365 | Integra... | SmartCard Reader             | 1     |            | DB4B891E15 |
| 04e6:5119 | SCM Mic... | SCR3340 - ExpressCard54 S... | 1     | usbfs      | 96AAA39135 |
| 04e6:e001 | SCM Mic... | SCR331 SmartCard Reader      | 1     |            | D3D8B39015 |
| 076b:4321 | OmniKey    | CardMan 4321                 | 1     |            | 3191678465 |
| 076b:5421 | OmniKey    | Smart Card Reader USB        | 1     |            | EE4E49C4A1 |
| 08e6:3438 | Gemalto... | GemPC Key SmartCard Reader   | 1     |            | 6BDD8BE020 |
| 096e:0505 | Feitian... | FT SCR310                    | 1     | usbfs      | 4039D51671 |
| 0a5c:5802 | Broadcom   | BCM5880 Secure Applicatio... | 1     |            | 4D67416D5E |
| 0a5c:5842 | Broadcom   | 58200                        | 1     |            | 8FB4429DD6 |
| 0bf8:1006 | Fujitsu... | SmartCard Reader 2A          | 1     |            | D7D5245A1A |
| 1050:0111 | Yubico.com | Yubikey NEO(-N) OTP+CCID     | 1     | usbfs      | 92C423B62E |
| 1050:0406 | Yubico.com | Yubikey 4 U2F+CCID           | 1     | usbfs      | 424D23C5FE |
| 1a44:0870 | VASCO D... | DIGIPASS 870                 | 1     |            | 1ED6532125 |
| 20a0:4108 | Clay Logic | Nitrokey Pro                 | 1     | usbhid     | E7580A2343 |
| 23a0:0004 | BIFIT      | iBank2Key                    | 1     |            | A8A89AC09A |

### Disk (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 058f:6362 | Alcor M... | Flash Card Reader/Writer     | 839   | uas, us... | 70E729A005 |
| 058f:6366 | Alcor M... | Multi Flash Reader           | 712   | uas, us... | B39AC90CA0 |
| 090c:1000 | Silicon... | Flash Voyager                | 688   | uas, us... | D1EC1DAC8F |
| 058f:6387 | Alcor M... | Transcend JetFlash Flash ... | 608   | uas, us... | D084D64BDF |
| 058f:6364 | Alcor M... | AU6477 Card Reader Contro... | 302   | uas, us... | 78E822AD79 |
| 13fe:4200 | Kingsto... | Silicon-Power32G 32GB        | 295   | uas, us... | DE168F8DCC |
| 0951:1666 | Kingsto... | DataTraveler 100 G3/G4/SE... | 250   | uas, us... | DE5FB421D9 |
| 0781:5567 | SanDisk    | Cruzer Blade 16GB            | 237   | uas, us... | 69A8A11098 |
| 0930:6545 | Toshiba    | Kingston DataTraveler 102... | 221   | uas, us... | D569843A2D |
| 1005:b113 | Apacer ... | Handy Steno/AH123 / Handy... | 205   | uas, us... | CA77267E34 |
| 0bda:0151 | Realtek... | Mass Storage Device (Mult... | 203   | uas, us... | 518A8709C7 |
| 13fe:4100 | Kingsto... | Silicon-Power16G 16GB        | 191   | uas, us... | 1C77D7A584 |
| 0bda:0158 | Realtek... | USB 2.0 multicard reader     | 186   | ums_rea... | BD55864B86 |
| 048d:1336 | Integra... | SD/MMC Cardreader            | 163   | uas, us... | E969E52D33 |
| 0951:1665 | Kingsto... | Digital DataTraveler SE9 ... | 128   | uas, us... | 6426CF04BD |
| 0781:5581 | SanDisk    | Ultra 128GB                  | 118   | uas, us... | 4A2455EAE6 |
| 0930:6544 | Toshiba    | TransMemory-Mini / Kingst... | 115   | uas, us... | CC12571867 |
| 0bda:0111 | Realtek... | RTS5111 Card Reader Contr... | 101   | uas, us... | A95491B363 |
| 14cd:168a | Super Top  | Storage Device 16GB          | 94    | uas, us... | 99614383EB |
| 0781:5571 | SanDisk    | Cruzer Fit 16GB              | 93    | uas, us... | AB17752168 |
| 0bda:0138 | Realtek... | RTS5138 Card Reader Contr... | 93    | ums_rea... | F7B38B6B8B |
| 058f:6377 | Alcor M... | AU6375 4-LUN card reader     | 86    | uas, us... | D084D64BDF |
| 13fe:3e00 | Kingsto... | Silicon-Power16G 16GB        | 81    | uas, us... | C800ABA635 |
| 13fe:5500 | Kingsto... | Silicon-Power32G 31GB        | 79    | uas, us... | 94C3F1BC72 |
| 058f:9360 | Alcor M... | 8-in-1 Media Card Reader     | 75    | uas, us... | 9137FB3859 |
| 12d1:14dc | Huawei ... | E33372 LTE/UMTS/GSM HiLin... | 74    | uas, us... | 54C92BF69C |
| 0951:1643 | Kingsto... | DataTraveler G3 15GB         | 71    | uas, us... | 56D8AE9D24 |
| 18a5:0302 | Verbatim   | STORE N GO 16GB              | 71    | uas, us... | 54C92BF69C |
| 05e3:0745 | Genesys... | Logilink CR0012 32GB         | 70    | uas, us... | 8E95D2B553 |
| 174c:5106 | ASMedia... | Transcend StoreJet 25M3 3... | 69    | uas, us... | 5D65FDCE91 |
| 05e3:0723 | Genesys... | GL827L SD/MMC/MS Flash Ca... | 65    | usb_sto... | 8EB32C768B |
| 0bda:0181 | Realtek... | SD/MMC/MS/MSPRO              | 65    | uas, us... | 6B8676DFEF |
| 0781:5575 | SanDisk    | Cruzer Glide 32GB            | 64    | uas, us... | FE7535550F |
| 05e3:070e | Genesys... | USB 2.0 Card Reader          | 63    | uas, us... | FF78BFBB07 |
| 0781:5583 | SanDisk    | Ultra Fit 123GB              | 63    | uas, us... | B481805845 |
| 0951:1642 | Kingsto... | DT101 G2 16GB                | 62    | uas, us... | F699A76638 |
| 0bda:0153 | Realtek... | 3-in-1 (SD/SDHC/SDXC) Car... | 61    | uas, us... | 4C9A2AA59C |
| 05e3:0716 | Genesys... | USB 2.0 Multislot Card Re... | 59    | uas, us... | 699B1F26E0 |
| 0781:556b | SanDisk    | Cruzer Edge 16GB             | 58    | uas, us... | D5DC53D7FA |
| 13fe:3600 | Kingsto... | flash drive (4GB, EMTEC) ... | 57    | usb_sto... | 7C0CD24986 |
| 1307:0330 | Transcend  | 63-in-1 Multi-Card Reader... | 56    | uas, us... | B39AC90CA0 |
| abcd:1234 | Chipsbnk   | Alu Line 16GB                | 56    | uas, us... | CF41AB5F1A |
| 0bda:0116 | Realtek... | RTS5116 Card Reader Contr... | 53    | uas, us... | 54C92BF69C |
| 14cd:8168 | Super Top  | Storage Device               | 51    | uas, us... | BCD563149D |
| 14cd:6116 | Super Top  | M6116 SATA Bridge            | 49    | uas, us... | 891002E8F2 |
| 1908:0226 | GEMBIRD    | Mass-Storage 134GB           | 48    | uas, us... | 7F1BE20709 |
| 0cf2:6230 | ENE Tec... | SD Card Reader (UB623X)      | 42    | uas, us... | FEAA959521 |
| 05ac:8403 | Apple      | Internal Memory Card Reader  | 41    | uas, us... | 9F753AC669 |
| 0bda:0159 | Realtek... | RTS5159 Card Reader Contr... | 41    | ums_rea... | C2A4730E33 |
| 0781:5591 | SanDisk    | Ultra Flair USB 3.0 124GB    | 40    | uas, us... | AB97B7B7FD |
| 0781:5572 | SanDisk    | Cruzer Switch 16GB           | 36    | uas, us... | 3D5D3F552C |
| 0424:2228 | Standar... | 9-in-2 Card Reader           | 35    | uas, us... | FF0A7B1FC8 |
| 0951:1607 | Kingsto... | DataTraveler 100 32GB        | 35    | uas, us... | F95BBD54DA |
| 0bda:0316 | Realtek... | SD/MMC 128GB                 | 35    | uas, us... | 3A4D90A1C3 |
| 8644:8003 | Intenso... | Micro Line 16GB              | 35    | uas, us... | 4FAA6112C3 |
| 0bda:0177 | Realtek... | SD/MMC/MS PRO 31GB           | 34    | uas, us... | 0AB5BF5B1A |
| 14cd:125d | Super Top  | Storage Device 32GB          | 34    | uas, us... | 048F01BE63 |
| 0951:1653 | Kingsto... | Data Traveler 100 G2 8 Gi... | 33    | uas, us... | 9C885EB562 |
| 1058:1042 | Western... | Elements SE Portable (WDB... | 33    | uas, us... | 2FB80FF93D |
| 125f:c08a | A-DATA ... | C008 Flash Drive 32GB        | 33    | uas, us... | C67AE8B7E3 |
| 13fe:4300 | Kingsto... | USB DISK 2.0 16GB            | 33    | uas, us... | 01EB97A943 |
| 0bc2:231a | Seagate    | Expansion Portable           | 32    | uas        | AD98351C8D |
| 090c:6300 | Silicon... | Reader SD/MS                 | 30    | uas, us... | 54231260FF |
| 1307:0165 | Transcend  | 2GB/4GB/8GB Flash Drive 16GB | 30    | uas, us... | 0BE7A39100 |
| 0480:a202 | Toshiba... | Canvio Basics HDD 500GB      | 29    | uas, us... | 1395F6EFED |
| 0bc2:ab24 | Seagate    | Backup Plus Portable Drive   | 29    | uas        | DD4DA32934 |
| 1058:1021 | Western... | Elements Desktop (WDBAAU)    | 29    | uas, us... | 8D8BE94484 |
| 05e3:0751 | Genesys... | microSD Card Reader          | 27    | uas, us... | 37E5DABF3C |
| 0781:5530 | SanDisk    | Cruzer                       | 27    | uas, us... | 4C192F8B47 |
| 1058:25a2 | Western... | Elements 25A2 500GB          | 27    | uas, us... | AE1CE65D11 |
| 125f:c96a | A-DATA ... | C906 Flash Drive 16GB        | 27    | uas, us... | 4529486397 |
| 3538:0901 | pqi        | IntelligentStick 8GB         | 27    | uas, us... | 6D5F1234C2 |
| 0781:5590 | SanDisk    | Ultra Dual 15GB              | 26    | uas, us... | 73F23254C0 |
| 1058:10b8 | Western... | Elements Portable (WDBU6Y... | 26    | uas, us... | 3A39EF0147 |
| 13fe:1d00 | Kingsto... | DataTraveler 2.0 1GB/4GB ... | 26    | uas, us... | 941367D018 |
| 0bda:0184 | Realtek... | RTS5182 Card Reader          | 25    | uas, us... | D7D5245A1A |
| 174c:1153 | ASMedia... | ASM2115 SATA 6Gb/s bridge    | 25    | uas, us... | 5DA90F3771 |
| 05e3:0722 | Genesys... | SD/MMC card reader           | 24    | uas, us... | C0EABA1044 |
| 1058:074a | Western... | My Passport 074A 500GB       | 24    | uas, us... | 330C957752 |
| ffff:5678 | VendorCo   | ProductCode 16GB             | 24    | uas, us... | 6260EAF2EB |
| 048d:1345 | Integra... | Multi Cardreader             | 23    | uas, us... | 1E64A21630 |
| 0951:1625 | Kingsto... | DataTraveler 101 II 4GB      | 23    | uas, us... | 2ACA3CEF22 |
| 0bb4:0001 | HTC (Hi... | Android Phone via mass st... | 23    | uas, us... | 303F6AA456 |
| 0bc2:2312 | Seagate    | Expansion 500GB              | 23    | uas, us... | 4AFB8F7991 |
| 0bda:0161 | Realtek... | Mass Storage Device          | 23    | mceusb,... | 087F924E20 |
| 13fd:1840 | Initio     | INIC-1608 SATA bridge        | 23    | uas, us... | 456CDA8C49 |
| 13fe:3d00 | Kingsto... | Silicon-Power8G 8GB          | 23    | uas, us... | CC9A8D1703 |
| 14cd:1212 | Super Top  | microSD card reader (SY-T18) | 23    | uas, us... | E9D240DB49 |
| 04e8:61b6 | Samsung... | M3 Portable Hard Drive       | 22    | uas, us... | A5BBF4389F |
| 05e3:0732 | Genesys... | All-in-One Cardreader        | 22    | uas, us... | 30502C41DE |
| 0781:5580 | SanDisk    | SDCZ80 Flash Drive 16GB      | 22    | uas, us... | 33F663A020 |
| 13fe:3623 | Kingsto... | silicon-power 16GB           | 22    | uas, us... | 41C18F108F |
| 1687:3257 | Kingmax... | USB2.0 FlashDisk 33GB        | 22    | uas, us... | E42FD626B2 |
| 1f75:0917 | Innosto... | Ultra Line 16GB              | 22    | uas, us... | 37A334E523 |
| 058f:6361 | Alcor M... | Multimedia Card Reader       | 21    | uas, us... | B2D5544528 |
| 05dc:a838 | Lexar M... | USB JumpDrive Tough 128GB    | 21    | uas, us... | 2D991778CF |
| 05e3:0727 | Genesys... | microSD Reader/Writer        | 21    | uas, us... | 873CD3A203 |
| 0644:0200 | TEAC       | All-In-One Multi-Card Rea... | 21    | uas, us... | C80A50B2B4 |
| 0bc2:a013 | Seagate    | Backup+ SL 500GB             | 21    | uas, us... | B86DF74030 |
| 152d:2509 | JMicron... | JMS539 SuperSpeed SATA II... | 21    | uas, us... | B7DDB54F07 |

### Dvb card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:2838 | Realtek... | RTL2838 DVB-T                | 27    | dvb_usb... | 100291AB94 |
| 07ca:a309 | AVerMed... | AVerTV DVB-T (A309)          | 8     | dvb_usb... | 500C2BCFBC |
| 07ca:0831 | AVerMed... | H831 USB Hybrid DVB-T/T2     | 5     |            | D5A4F195AE |
| 07ca:1336 | AVerMed... | A336 MiniCard Hybrid DVB-T   | 5     |            | A2FF4426C9 |
| 1164:1f08 | YUAN Hi... | STK7700D                     | 5     | dvb_usb... | 7D19EDDC5C |
| 15a4:9016 | Afatech    | AF9015 DVB-T USB2.0 stick    | 5     | dvb_usb... | B5CD6895D0 |
| 07ca:0830 | AVerMed... | H830 USB Hybrid DVB-T        | 4     |            | 79A097BF6F |
| 0bda:2832 | Realtek... | RTL2832U DVB-T               | 4     | dvb_usb... | 9994FB8ABA |
| 2040:7070 | Hauppauge  | Nova-T Stick 3               | 3     | dvb_usb... | F68CFBE3F5 |
| 048d:9005 | Integra... | DVB-T TV Stick               | 2     | dvb_usb... | AE491DB991 |
| 048d:9135 | Integra... | Zolid Mini DVB-T Stick       | 2     | dvb_usb... | 973EEE4869 |
| 04b4:2102 | Cypress... | Cypress DVB Card             | 2     | dvb_usb... | 3F4C49A9AA |
| 0572:c688 | Conexan... | Geniatech T230 DVB-T2 TV ... | 2     | dvb_usb... | 48397FDB3D |
| 07ca:0810 | AVerMed... | H810 USB Hybrid DVB-T        | 2     |            | B46F2FEE35 |
| 07ca:a310 | AVerMed... | A310                         | 2     | dvb_usb... | 4F1C235318 |
| 1164:0871 | YUAN Hi... | STK7700D                     | 2     | dvb_usb... | 97D9353E2A |
| 13d3:3282 | IMC Net... | DVB-T + GPS Minicard [RTL... | 2     |            | 7F0F347502 |
| 14f7:0500 | TechniS... | DVB-PC TV Star HD            | 2     | dvb_usb... | C7D09ABC04 |
| 15f4:0131 | HanfTek    | dvbt2                        | 2     | dvb_usb... | CCB302179F |
| 187f:0202 | Siano M... | Nice                         | 2     | smsusb     | 7F239B5732 |
| 2304:0237 | Pinnacl... | PCTV 73e [DiBcom DiB7000PC]  | 2     | dvb_usb... | B9F2AE0CCF |
| 0413:6a04 | Leadtek... | DVB-T 2                      | 1     | dvb_usb... | C5B8862A26 |
| 04b4:861f | Cypress... | Anysee E30 USB 2.0 DVB-T ... | 1     | dvb_usb... | 1C1B87DEA4 |
| 07ca:1334 | AVerMed... | H334 MiniCard Hybrid DVB-T   | 1     |            | 3EBFFF7DAD |
| 07ca:4336 | AVerMed... | A336 MiniCard Hybrid DVB-T   | 1     |            | 0C3E26BCE7 |
| 07ca:8150 | AVerMed... | A815O                        | 1     | dvb_usb... | 69CC9D8136 |
| 07ca:a815 | AVerMed... | AVerTV DVB-T Volar X (A815)  | 1     | dvb_usb... | 35CFA6018F |
| 0b48:3006 | TechnoT... | TT-connect S-2400 DVB-S r... | 1     | dvb_usb... | 003EB89135 |
| 0bda:2831 | Realtek... | RTL2831U DVB-T               | 1     | dvb_usb... | 2A72B05F9D |
| 14aa:0221 | WideVie... | WT-220U DVB-T dongle         | 1     | dvb_usb... | 7FA8E3A5E5 |
| 15a4:1001 | Afatech    | AF9015/AF9035 DVB-T stick    | 1     | dvb_usb... | 006CC8353F |
| 1b80:d393 | Afatech    | DVB-T receiver [RTL2832U]    | 1     | dvb_usb... | AB722FD0B6 |
| 1d19:1101 | Dexatek... | DK DVB-T Dongle              | 1     | dvb_usb... | BAEBBFC37F |
| 1d19:1102 | Dexatek... | DK mini DVB-T Dongle         | 1     | dvb_usb... | 66EEFE25AF |
| 1f4d:3000 | G-Tek E... | HD Star DVB-S2 USB2.0        | 1     | dvb_usb... | 4D00BA8216 |
| 2040:5200 | Hauppauge  | NovaT 500Stick               | 1     | dvb_usb... | A5A0DA657B |
| 2040:9580 | Hauppauge  | NovaT 500Stick               | 1     | dvb_usb... | 2457E81077 |
| 2304:022b | Pinnacl... | PCTV 71e [Afatech AF9015]    | 1     | dvb_usb... | B778A6096A |
| 2304:022c | Pinnacl... | PCTV 2000e                   | 1     | dvb_usb... | B2BA637E05 |
| 2304:022e | Pinnacl... | PCTV 320cx                   | 1     | dvb_usb... | 9DA08CE4A5 |
| 2304:023a | Pinnacl... | PCTV 801e                    | 1     | dvb_usb... | DC0159ECF4 |
| eb1a:5013 | eMPIA T... | USB 2883 Device              | 1     |            | 5DD14F9164 |

### Fingerprint reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 138a:0011 | Validit... | VFS5011 Fingerprint Reader   | 130   |            | 10FB53EFCA |
| 138a:0018 | Validit... | Fingerprint scanner          | 120   |            | D2006E7A87 |
| 138a:003f | Validit... | VFS495 Fingerprint Reader    | 111   | usbfs      | AC96DD45F9 |
| 147e:2016 | Upek       | Biometric Touchchip/Touch... | 96    |            | C28241E4F0 |
| 0483:2016 | STMicro... | Fingerprint Reader           | 88    |            | 7F41843359 |
| 08ff:2580 | AuthenTec  | AES2501 Fingerprint Sensor   | 87    |            | 084F7E13DA |
| 08ff:2810 | AuthenTec  | AES2810                      | 78    |            | A23E000798 |
| 147e:1002 | Upek       | Biometric Touchchip/Touch... | 69    |            | 7C0CD24986 |
| 08ff:1600 | AuthenTec  | AES1600                      | 68    |            | 4A6A073320 |
| 138a:0007 | Validit... | VFS451 Fingerprint Reader    | 53    | usbfs      | E2C04796A0 |
| 138a:003c | Validit... | VFS471 Fingerprint Reader    | 53    |            | A31B1E8E5E |
| 138a:003d | Validit... | VFS491                       | 50    |            | 68A86E6E3F |
| 138a:0017 | Validit... | VFS 5011 fingerprint sensor  | 48    | usbfs      | 7637F3DE5F |
| 138a:0005 | Validit... | VFS301 Fingerprint Reader    | 43    |            | DDF30C670A |
| 1c7a:0801 | LighTun... | Fingerprint Reader           | 40    |            | E1D809E15F |
| 138a:0001 | Validit... | VFS101 Fingerprint Reader    | 37    |            | 500C2BCFBC |
| 1c7a:0603 | LighTun... | EgisTec ES603                | 37    |            | 47C94E2F61 |
| 138a:0050 | Validit... | Swipe Fingerprint Sensor     | 33    |            | 734FCAFBD7 |
| 1c7a:0570 | LighTun... | EgisTec Touch Fingerprint... | 26    |            | 376C2CCA98 |
| 04f3:0903 | Elan Mi... | ELAN:Fingerprint             | 22    |            | 632AA405C1 |
| 147e:1000 | Upek       | Biometric Touchchip/Touch... | 21    |            | C15AB53D21 |
| 08ff:168f | AuthenTec  | AES1660 Fingerprint Sensor   | 19    |            | 801A0452F8 |
| 04f3:0c1a | Elan Mi... | ELAN:Fingerprint             | 13    |            | A159026F22 |
| 08ff:2550 | AuthenTec  | AES2550 Fingerprint Sensor   | 13    |            | EEFC712947 |
| 06cb:0078 | Synaptics  | WBDI Device                  | 12    |            | 4CED599618 |
| 147e:1001 | Upek       | TCS5B Fingerprint sensor     | 12    |            | 2AFD83B0D3 |
| 04f3:0c03 | Elan Mi... | ELAN:Fingerprint             | 11    |            | E6C392B427 |
| 138a:0090 | Validit... | VFS7500 Touch Fingerprint... | 10    |            | 7E4A6B2354 |
| 138a:0010 | Validit... | VFS Fingerprint sensor       | 9     |            | 467F389FCE |
| 138a:0091 | Validit... | VFS7552 Touch Fingerprint... | 9     |            | 200F73880C |
| 138a:0008 | Validit... | VFS300 Fingerprint Reader    | 8     |            | 6722706FA2 |
| 08ff:168b | AuthenTec  | Fingerprint Sensor           | 6     |            | 4398E73607 |
| 08ff:2665 | AuthenTec  | Fingerprint Sensor           | 5     |            | 42DF53B120 |
| 06cb:0082 | Synaptics  | My Lockey                    | 4     |            | 3E9DFA313B |
| 08ff:2683 | AuthenTec  | Fingerprint Sensor           | 3     |            | 0A5A3C6337 |
| 045e:00bb | Microsoft  | Fingerprint Reader           | 2     | usbhid     | 636774FB05 |
| 08ff:1686 | AuthenTec  | Fingerprint Sensor           | 2     |            | 73CAFC58A2 |
| 08ff:168c | AuthenTec  | Fingerprint Sensor           | 2     |            | 7C26C8530E |
| 05ba:0002 | Digital... | Fingerprint Scanner, U.ar... | 1     |            | AE361E5F23 |
| 06cb:00b7 | Synaptics  | Synaptics VFS7552 Touch F... | 1     |            | 0D375562BD |
| 08ff:1660 | AuthenTec  | AES1660 Fingerprint Sensor   | 1     |            | 89EC4F0398 |
| 08ff:168a | AuthenTec  | Fingerprint Sensor           | 1     |            | 9A145A3041 |
| 08ff:2500 | AuthenTec  | AES2501                      | 1     |            | 4DCFB332DF |
| 08ff:2691 | AuthenTec  | Fingerprint Sensor           | 1     |            | 79E75DF44E |

### Gamepad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:028e | Microsoft  | Xbox360 Controller           | 87    | xpad       | A8F2B39356 |
| 046d:c21f | Logitech   | F710 Wireless Gamepad [XI... | 25    | xpad       | 8C8AF8B557 |
| 045e:0291 | Microsoft  | Xbox 360 Wireless Receive... | 17    | xpad       | 6144FC259F |
| 0079:0011 | DragonRise | Gamepad                      | 16    | usbhid     | 419900511F |
| 046d:c21d | Logitech   | F310 Gamepad [XInput Mode]   | 11    | xpad       | 6B4EBF9EE7 |
| 0810:e501 | Persona... | SNES Gamepad                 | 5     | usbhid     | 6DE273D636 |
| 0e8f:0003 | GreenAsia  | MaxFire Blaze2               | 5     | usbhid     | E075ADEAD4 |
| 046d:c21e | Logitech   | F510 Gamepad [XInput Mode]   | 4     | xpad       | 852999BF0D |
| 0e8f:0008 | GreenAsia  | Game Controller for PC       | 4     | usbhid     | B1600EF31C |
| 0e8f:0012 | GreenAsia  | Joystick/Gamepad             | 3     | usbhid     | 265B796EFD |
| 1345:6006 | Sino Li... | Defender Wireless Controller | 3     |            | E3D0C37620 |
| 2563:0575 | ShanWan    | USB WirelessGamepad          | 3     | usbhid     | 9FFD70ADD1 |
| 0583:a000 | Padix (... | MaxFire G-08XU Gamepad       | 2     | usbhid     | 33EE68D3F5 |
| 0e8f:310d | GreenAsia  | GAMEPAD 3 TURBO              | 2     | usbhid     | 71A5A103B0 |
| 0079:181c | DragonRise | Gamepad                      | 1     | usbhid     | 2D24119519 |
| 044f:b326 | ThrustM... | Gamepad GP XID               | 1     | xpad       | 3C19F51786 |
| 046d:c242 | Logitech   | XUSB Gamepad                 | 1     | xpad       | A07F95C027 |
| 050d:0805 | Belkin ... | Nostromo N50 GamePad         | 1     | usbhid     | CE6735B3BF |
| 07b5:0213 | Mega Wo... | Thrustmaster Firestorm Di... | 1     | usbhid     | 70CA2BBB71 |
| 0810:0005 | Persona... | USB Gamepad                  | 1     | usbhid     | 3BDBF957FA |
| 0e6f:011e | Logic3     | Rock Candy Gamepad for PS3   | 1     | usbhid     | 8E73A7CEDB |
| 0e6f:011f | Logic3     | Rock Candy Gamepad for Xb... | 1     | xpad       | 80B359DC57 |
| 0e6f:0201 | Logic3     | Gamepad                      | 1     | usbfs      | E20DBED4CE |
| 0e6f:0213 | Logic3     | Afterglow Gamepad for Xbo... | 1     | xpad       | 9DE5FB33B8 |
| 12ab:f701 | Honey B... | Xbox Controller              | 1     | xpad       | B621A131B1 |
| 145f:0231 | Trust      | USB Gamepad                  | 1     | usbhid     | 2DC764FFB7 |
| 1689:fd00 | Razer USA  | Onza Tournament Edition c... | 1     | xpad       | EC671CD080 |

### Hardware key (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a89:0003 | Aktiv      | Guardant Stealth/Net II      | 8     |            | 5149320E81 |
| 0a89:0020 | Aktiv      | Rutoken S                    | 8     | usbfs      | 07802CEC21 |
| 0471:485d | Philips... | Senselock SenseIV v2.x       | 4     |            | E4A6E39276 |
| 14a8:0001 | Soft pr... | Soft protection device: U... | 1     |            | 568CDC2D31 |

### Hasp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0529:0001 | Aladdin... | HASP copy protection dongle  | 38    |            | 920F49F96C |

### Hub (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1d6b:0002 | Linux F... | 2.0 root hub                 | 28617 | hub        | C61C9E33F6 |
| 1d6b:0003 | Linux F... | 3.0 root hub                 | 14191 | hub        | C61C9E33F6 |
| 1d6b:0001 | Linux F... | 1.1 root hub                 | 13465 | hub        | E9BD04F647 |
| 8087:0024 | Intel      | Integrated Rate Matching Hub | 6109  | hub        | B9A4817612 |
| 8087:8000 | Intel      | Hub                          | 2001  | hub        | 7637F3DE5F |
| 8087:0020 | Intel      | Integrated Rate Matching Hub | 1406  | hub        | 86987CF1ED |
| 8087:8008 | Intel      | Hub                          | 1347  | hub        | DD4DA32934 |
| 05e3:0608 | Genesys... | USB-2.0 4-Port HUB           | 1145  | hub        | D1EC1DAC8F |
| 1a40:0101 | incompl... | 4-Port HUB                   | 981   | hub        | C7F97B95C4 |
| 8087:8001 | Intel      | Hub                          | 463   | hub        | EFA3992D9A |
| 0438:7900 | AMD        | Hub                          | 455   | hub        | C61C9E33F6 |
| 05e3:0610 | Genesys... | 4-port hub                   | 387   | hub        | 94C3F1BC72 |
| 0a5c:4500 | Broadcom   | BCM2046B1 USB 2.0 Hub (pa... | 307   | hub        | 68BABB69CB |
| 2109:3431 | VIA Labs   | USB2.0 Hub                   | 244   | hub        | 394C81B911 |
| 0424:2514 | Standar... | USB 2.0 Hub                  | 239   | hub        | 8EAEF3C906 |
| 8087:8009 | Intel      | Hub                          | 198   | hub        | EFA3992D9A |
| 2109:2812 | VIA Labs   | USB2.0 VL812 Hub             | 158   | hub        | C92DC5D0CF |
| 0409:005a | NEC Com... | HighSpeed Hub                | 151   | hub        | BF6F02A425 |
| 058f:6254 | Alcor M... | USB Hub                      | 144   | hub        | 7D2B995B44 |
| 05e3:0606 | Genesys... | USB 2.0 Hub / D-Link DUB-... | 140   | hub        | 0FCCED0386 |
| 1a40:0201 | Terminu... | FE 2.1 7-port Hub            | 114   | hub        | E969E52D33 |
| 2109:0812 | VLI Labs   | USB 3.0 VL812 HUB            | 110   | hub        | C92DC5D0CF |
| 8087:8002 | Intel      | Hub                          | 107   | hub        | A8F2B39356 |
| 8087:800a | Intel      | Hub                          | 107   | hub        | A8F2B39356 |
| 174c:2074 | ASMedia... | ASM1074 High-Speed hub       | 98    | hub        | A8F2B39356 |
| 174c:3074 | ASMedia... | ASM1074 SuperSpeed hub       | 98    | hub        | A8F2B39356 |
| 058f:9254 | Alcor M... | Hub                          | 97    | hub        | FE9E0ACDE5 |
| 05e3:0612 | Genesys... | USB3.0 Hub 123               | 89    | hub        | 94C3F1BC72 |
| 14cd:8601 | Super Top  | USB 2.0 Hub                  | 89    | hub        | 8B3744250A |
| 8087:07e6 | Intel      | Hub                          | 88    | hub        | CC7193A7B9 |
| 0b97:7761 | O2 Micro   | Oz776 1.1 Hub                | 87    | hub        | F40C3D18FB |
| 0bda:5411 | Realtek... | 4-Port USB 2.0 Hub           | 83    | hub        | 4CED599618 |
| 2109:2813 | VIA Labs   | USB2.0 Hub                   | 81    | hub        | 537D11B224 |
| 05ac:1006 | Apple      | Hub in Aluminum Keyboard     | 76    | hub        | B6D6A0F54D |
| 2109:0811 | VIA Labs   | 4-Port USB 3.0 Hub           | 66    | hub        | FB18F180A5 |
| 0bda:0411 | Realtek... | 4-Port USB 3.0 Hub           | 65    | hub        | 331420F489 |
| 2109:0813 | VIA Labs   | USB3.0 Hub                   | 62    | hub        | 537D11B224 |
| 214b:7000 |            | USB2.0 HUB                   | 61    | hub        | 95611F735C |
| 2109:2811 | VIA Labs   | USB2.0 Hub                   | 56    | hub        | A8F2B39356 |
| 0424:2504 | Standar... | USB 2.0 Hub                  | 54    | hub        | C9E6C4517D |
| 05e3:0616 | Genesys... | hub                          | 49    | hub        | 7F1F084A4F |
| 0424:2134 | Standar... | USB2134B                     | 45    | hub        | AC96DD45F9 |
| 0424:2513 | Standar... | 2.0 Hub                      | 45    | hub        | 16BDB52C40 |
| 0557:7000 | ATEN In... | Hub                          | 44    | hub        | EBB5316694 |
| 2109:8110 | VIA Labs   | USB 3.0 Hub                  | 43    | hub        | A8F2B39356 |
| 0a05:7211 | Unknown... | hub                          | 41    | hub        | 7CE46A749E |
| 0424:5534 | Standar... | USB5534B                     | 38    | hub        | AC96DD45F9 |
| 04b4:6560 | Cypress... | CY7C65640 USB-2.0 "TetraHub" | 37    | hub        | 4A6A073320 |
| 0451:8142 | Texas I... | TUSB8041 4-Port Hub          | 35    | hub        | 3B3DC1A093 |
| 045b:0209 | Hitachi    | Hub                          | 35    | hub        | D3AFE1DB4A |
| 045b:0210 | Hitachi    | Hub                          | 33    | hub        | 7875ECD5A5 |
| 0424:2512 | Standar... | USB 2.0 Hub                  | 30    | hub        | DDDDDCBF45 |
| 413c:2513 | Dell       | internal USB Hub of E-Por... | 29    | hub        | 8B920A3699 |
| 046b:ff01 | America... | Virtual Hub                  | 28    | hub        | 4391DFF8D2 |
| 0557:8021 | ATEN In... | CS1764A [CubiQ DVI KVMP S... | 28    | hub        | E4277FA218 |
| 413c:a005 | Dell       | Internal 2.0 Hub             | 27    | hub        | BF8ACC676E |
| 05ac:1003 | Apple      | Hub in Pro Keyboard [Mits... | 26    | hub        | 44204F310C |
| 8564:4000 | Transcend  | RDF8 16GB                    | 26    | uas, us... | 725B24FE69 |
| 0424:2660 | Standar... | Hub                          | 25    | hub        | 140DAF886E |
| 05e3:0607 | Genesys... | Logitech G110 Hub            | 25    | hub        | 842E440F34 |
| 2109:0810 | VIA Labs   | 4-Port USB 3.0 VL81x Hub     | 25    | hub        | 07DD5B8424 |
| 413c:1003 | Dell       | Keyboard Hub                 | 25    | hub        | C5B86FB4CB |
| 0409:0058 | NEC Com... | HighSpeed Hub                | 24    | hub        | 4391DFF8D2 |
| 05e3:0605 | Genesys... | USB 2.0 Hub                  | 23    | hub        | 21FB8F59A4 |
| 214b:7250 |            | USB2.0 HUB                   | 23    | hub        | 37E5DABF3C |
| 0451:8140 | Texas I... | TUSB8041 4-Port Hub          | 22    | hub        | 3B3DC1A093 |
| 17ef:100a | Lenovo     | ThinkPad Mini Dock Plus S... | 22    | hub        | C28241E4F0 |
| 2001:f103 | D-Link     | DUB-H7 7-port USB 2.0 hub    | 21    | hub        | 5B8AE7E31F |
| 046d:c223 | Logitech   | G11/G15 Keyboard / USB Hub   | 19    | hub        | B77180A9F5 |
| 0bda:5401 | Realtek... | RTL 8153 USB 3.0 hub with... | 19    | hub        | FEAA959521 |
| 0424:2744 | Standar... | USB2744                      | 18    | hub        | 3FF206C6B8 |
| 04b4:2050 | Cypress... | hub                          | 18    | hub        | 544F0D2A23 |
| 05e3:0617 | Genesys... | USB3.0 Hub                   | 18    | hub        | 85F1B83B30 |
| 2109:2817 | VIA Labs   | USB2.0 Hub                   | 18    | hub        | 74DD313167 |
| 03eb:0902 | Atmel      | 4-Port Hub                   | 17    | hub        | 47293CF17D |
| 2109:0817 | VIA Labs   | USB3.0 Hub                   | 17    | hub        | 74DD313167 |
| 0409:0059 | NEC Com... | HighSpeed Hub                | 16    | hub        | 3F04C2C04F |
| 0bda:0401 | Realtek... | USB3.0 Hub                   | 16    | hub        | FEAA959521 |
| 0424:2640 | Standar... | USB 2.0 Hub                  | 15    | hub        | 22AA6FF795 |
| 03eb:3301 | Atmel      | at43301 4-Port Hub           | 14    | hub        | 31EC690BE3 |
| 0424:5744 | Standar... | USB5744                      | 14    | hub        | A9B1FD6467 |
| 0424:2807 | Standar... | USB2807 Hub                  | 13    | hub        | 5D2CB1E1B0 |
| 0424:5807 | Standar... | USB5807 Hub                  | 13    | hub        | 5D2CB1E1B0 |
| 0451:8044 | Texas I... | Hub                          | 13    | hub        | 02B9759D77 |
| 0835:8500 | Action ... | USB2.0 Hub                   | 13    | hub        | F2981C1775 |
| 413c:5534 | Dell       | USB5534                      | 13    | hub        | 3C07832726 |
| 044e:3011 | Alps El... | BCM2045B2                    | 12    | hub        | C257EC2DD4 |
| 0424:2137 | Standar... | USB2137B                     | 11    | hub        | 68ECFC5409 |
| 05e3:0620 | Genesys... | USB3.0 Hub                   | 11    | hub        | 23DC7C0455 |
| 413c:1002 | Dell       | Keyboard Hub                 | 11    | hub        | BD8118E7B8 |
| 0424:9514 | Standar... | SMC9514 Hub                  | 10    | hub        | A2AB91716A |
| 0451:8043 | Texas I... | Hub                          | 10    | hub        | 734FCAFBD7 |
| 0451:8046 | Texas I... | Hub                          | 10    | hub        | 02B9759D77 |
| 0458:0736 | KYE Sys... | Multimedia Keyboard HUB      | 10    | hub        | 292785F9EC |
| 413c:1005 | Dell       | Multimedia Pro Keyboard Hub  | 10    | hub        | 0BEB4B51BA |
| 413c:1010 | Dell       | USB 2.0 Hub [MTT]            | 10    | hub        | DA78DC8E90 |
| 413c:a001 | Dell       | Hub                          | 10    | hub        | AF9F6ACE3F |
| 0424:2412 | Standar... | Hub                          | 9     | hub        | 92BF714334 |
| 0424:2602 | Standar... | USB 2.0 Hub                  | 9     | hub        | 4E3DF2DAE2 |
| 05ac:1002 | Apple      | Extended Keyboard Hub [Mi... | 9     | hub        | 452CCA7785 |

### Human interface (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 05ac:8242 | Apple      | Built-in IR Receiver         | 134   | usbhid     | B6D6A0F54D |
| 1770:ff00 | MSI EPF... | MSI EPF USB / LED controller | 72    | usbhid     | 3DF62034D2 |
| 0483:91d1 | STMicro... | SGS Thomson Microelectronics | 56    | usbhid     | 734FCAFBD7 |
| 0079:0006 | DragonRise | PC TWIN SHOCK Gamepad        | 54    | usbhid     | 9CEDE9D704 |
| 0665:5161 | Cypress... | USB to Serial                | 37    | usbhid     | D7D3D4F56B |
| 10d5:55a2 | Uni Cla... | 2Port KVMSwitcher            | 24    | usbhid     | A27D10FE73 |
| 1b1c:0c04 | Corsair    | Integrated USB Bridge        | 23    | usbhid     | 725B24FE69 |
| 0b05:1872 | ASUSTek... | AURA LED Controller          | 20    | usbhid     | E57993E26A |
| 054c:0268 | Sony       | Batoh Device / PlayStatio... | 16    | usbhid     | B9E21A89DA |
| 05ac:8240 | Apple      | Built-in IR Receiver         | 16    | usbhid     | FDEA938323 |
| 0408:3001 | Quanta ... | Optical Touch Screen         | 15    | usbhid     | E969E52D33 |
| 2047:0855 | Texas I... | Invensense Embedded Motio... | 15    | usbhid     | B19B3500F2 |
| 2101:1407 | ActionStar | USB KVM                      | 15    | usbhid     | 144815A4E9 |
| 046d:c216 | Logitech   | F310 Gamepad [DirectInput... | 14    | usbhid     | 6D9668A464 |
| 0b05:1867 | ASUSTek... | AURA Custom Human interface  | 14    | usbhid     | 5F582A0578 |
| 046d:c215 | Logitech   | Extreme 3D Pro               | 13    | usbhid     | 29A14836FD |
| 048d:8350 | Integra... | ITE Device(8350)             | 11    | usbhid     | CC12571867 |
| 0810:0003 | Persona... | PlayStation Gamepad          | 10    | usbhid     | D7CC0778FC |
| 147a:e00d | Formosa... | IR Receiver                  | 9     | usbhid     | 331F603CE2 |
| 03eb:8417 | Atmel      | maXTouch Digitizer           | 8     | usbhid     | BB40D4536A |
| 0810:0001 | Persona... | Dual PSX Adaptor             | 8     | usbhid     | 0BEB4B51BA |
| 1e71:170e | NZXT       | USB Device                   | 8     | usbhid     | C9E6C4517D |
| 0424:274c | Standar... | Hub Controller               | 7     | usbhid     | 8B270D4228 |
| 046d:c225 | Logitech   | G11/G15 Keyboard / G keys    | 7     | usbhid     | 5A16BDDE76 |
| 046d:c227 | Logitech   | G15 Refresh Keyboard         | 7     | usbhid     | B77180A9F5 |
| 054c:05c4 | Sony       | DualShock 4 [CUH-ZCT1E]      | 7     | usbhid     | FAAD08E39A |
| 0765:5010 | X-Rite     | X-Rite Pantone Color Sensor  | 7     | usbhid     | C087621D89 |
| 1038:1122 | SteelSe... | SteelSeries KLC              | 7     | usbhid     | DD39CC35AF |
| 10d5:000d | Uni Cla... | SP04-A1                      | 7     | usbhid     | 92C423B62E |
| 1770:ef35 | ASUS OSD   | ASUS OSD                     | 7     | usbhid     | 7F1BE20709 |
| 0001:0000 | Fry's E... | STD UPS MON V1.0             | 6     | usbhid     | 6564000AC6 |
| 0419:8002 | Samsung... | SyncMaster HID Monitor Co... | 6     | usbhid     | 399FE679CE |
| 0451:ca01 | Texas I... | USBtoI2C Solution            | 6     | usbhid     | 4926835893 |
| 0457:102b | Silicon... | SiS HID Touch Controller     | 6     | usbhid     | 1C95C123C9 |
| 048d:8386 | Integra... | ITE Device(8386)             | 6     | usbhid     | E1CD9FD6C1 |
| 11ff:3331 |            | PC Game Controller           | 6     | usbhid     | 4787FF9CAC |
| 17ef:3066 | Lenovo     | ThinkPad Thunderbolt 3 Do... | 6     | usbhid     | C15E0482CA |
| 187c:0524 | Alienware  | M17x                         | 6     | usbhid     | A1B30D6B32 |
| 187c:0550 | Alienware  | AW-ELC                       | 6     | usbhid     | 8B270D4228 |
| 2563:0523 | ShanWan    | PS3/PC Wired GamePad         | 6     | usbhid     | 32AFE6A3D4 |
| 044f:b108 | ThrustM... | T-Flight Hotas X Flight S... | 5     | usbhid     | 744236B602 |
| 0457:10c1 | Silicon... | SiS HID Touch Controller     | 5     | usbhid     | 7C8F86D1BD |
| 046d:c218 | Logitech   | Logitech RumblePad 2 USB     | 5     | usbhid     | EEBB334395 |
| 046d:c219 | Logitech   | F710 Gamepad [DirectInput... | 5     | usbhid     | 92459D790C |
| 046d:c21c | Logitech   | G13 Advanced Gameboard       | 5     | usbhid     | 1C3B65242D |
| 046d:c222 | Logitech   | G15 Keyboard / LCD           | 5     | usbhid     | 4118086F4C |
| 0483:5715 | STMicro... | RemoteSolution               | 5     | usbhid     | 857C8BE5D0 |
| 054c:058d | Sony       | USB Input Device             | 5     | usbhid     | 59BB8EC907 |
| 056a:00e6 | Wacom      | TPCE6                        | 5     | usbhid     | 659C24D76A |
| 187c:0530 | Alienware  | AW1517                       | 5     | usbhid     | 3C817B6AB2 |
| 2687:fb01 | Fitbit     | Base Station                 | 5     | usbhid     | B2D5544528 |
| 03eb:8209 | Atmel      | maXTouch Digitizer           | 4     | usbhid     | 80C0EC4495 |
| 0416:5020 | Winbond... | HID Transfer                 | 4     | usbhid     | 8F87769D12 |
| 046d:c214 | Logitech   | ATK3 (Attack III Joystick)   | 4     | usbhid     | 33687A527A |
| 046d:c626 | Logitech   | 3Dconnexion Space Navigat... | 4     | usbhid     | 07E431CDAB |
| 04d8:0b29 | Microch... | U2417H_0B29_15083001         | 4     | usbhid     | C87E189FA6 |
| 056a:5193 | Wacom      | Pen and multitouch sensor    | 4     | usbhid     | AAB68A3B33 |
| 06a3:0460 | Saitek     | ST290 Pro Flight Stick       | 4     | usbhid     | 95BA8F99A0 |
| 10d5:55a4 | Uni Cla... | 4 Port KVMSwicther           | 4     | usbhid     | 68158424AF |
| 11ff:3341 |            | USB Joystick                 | 4     | usbhid     | C183D48CD3 |
| 16c0:05df | Van Ooi... | HID device except mice, k... | 4     | radio_m... | A71AC3A709 |
| 222a:0011 | ILITEK     | Multi-Touch                  | 4     | usbhid     | 16D6FCA3F1 |
| 03eb:8807 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 19AB1B4351 |
| 03eb:8810 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 94000B6660 |
| 03eb:8814 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | B19B3500F2 |
| 03eb:8819 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | FE571546DB |
| 03eb:8a06 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 46408ABBB6 |
| 03eb:8a0b | Atmel      | maXTouch Digitizer           | 3     | usbhid     | 15AF322AD8 |
| 03eb:8a19 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | DE79BB68E4 |
| 03eb:8a96 | Atmel      | maXTouch Digitizer           | 3     | usbhid     | A3E8CC3C5F |
| 03eb:8b0d | Atmel      |                              | 3     | usbhid     | 30A8F9D279 |
| 0409:02b8 | NEC Com... | PA241W                       | 3     | usbhid     | A9E77A23FE |
| 044f:b106 | ThrustM... | T.Flight Stick X             | 3     | usbhid     | 218F087B6C |
| 044f:b10a | ThrustM... | T.16000M Joystick            | 3     | usbhid     | 14A8808D2B |
| 0457:10c0 | Silicon... | SiS HID Touch Controller     | 3     | usbhid     | 4018847A8C |
| 045e:0904 | Microsoft  | Surface Dock Extender        | 3     | usbhid     | DBF25F43EB |
| 046d:0a5d | Logitech   | Gaming Headset Battery Ch... | 3     | usbhid     | E361B0B9F1 |
| 046d:c21a | Logitech   | Precision Gamepad            | 3     | usbhid     | B0D2314507 |
| 046d:c29b | Logitech   | G27 Racing Wheel             | 3     | usbhid     | 2C043EBD94 |
| 0486:0186 | ASUS Co... | MultiTouch(TTI)              | 3     | usbhid     | 742C2CD59E |
| 04eb:e030 | Northst... | Media Center Interface       | 3     | usbhid     | 3736215480 |
| 05c6:f006 | Qualcomm   | ZTE HSUSB Device             | 3     | usbhid     | 6299339038 |
| 0765:5001 | X-Rite     | Huey PRO Colorimeter         | 3     | usbhid     | F3B59C4994 |
| 0955:000a | Nvidia     | ESA FW Update                | 3     | usbhid     | 92BF714334 |
| 0b05:1726 | ASUSTek... | Laptop OLED Display          | 3     | usbhid     | 4AC478DF18 |
| 1044:7a02 | Chu Yue... |                              | 3     | usbhid     | 5F6E1A3B61 |
| 1050:0120 | Yubico.com | Yubikey Touch U2F Securit... | 3     | usbhid     | C2D1F5C35A |
| 1345:3008 | Sino Li... | USB Controller               | 3     | usbhid     | BE67B91F72 |
| 187c:0526 | Alienware  | A-51                         | 3     | usbhid     | E1BABF19AD |
| 20b3:0a18 | Hanvon     | 10.1 Touch screen overlay    | 3     | usbhid     | 33A13ED635 |
| 2386:310e | Raydium    | Touch System                 | 3     | usbhid     | C731CA9F7F |
| 264a:2329 | Thermal... | Thermaltake DPS PSU          | 3     | usbhid     | 87B482DE1D |
| 2833:0031 | Oculus VR  | Rift                         | 3     | usbhid     | B3E32D1026 |
| 8087:0a04 | Intel      | Sensor Solution              | 3     | usbhid     | 686053FC6E |
| ffff:0000 |            | 068A                         | 3     | usbhid     | 68ECBC0D7A |
| 03eb:211c | Atmel      | maXTouch Digitizer           | 2     | usbhid     | DCF693F16F |
| 03eb:843d | Atmel      | maXTouch Digitizer           | 2     | usbhid     | A7F7276E3D |
| 03eb:8a03 | Atmel      | maXTouch Digitizer           | 2     | usbhid     | C21BC28613 |
| 03eb:8a41 | Atmel      |                              | 2     | usbhid     | 109A5A43A0 |
| 03eb:8b03 | Atmel      |                              | 2     | usbhid     | 57144F6E19 |

### Infrared (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0609:031d | SMK Man... | eHome Infrared Receiver      | 4     | mceusb     | B5CD6895D0 |
| 066f:4200 | SigmaTel   | STIr4200 IrDA Bridge         | 4     | stir4200   | 6682A76496 |
| 147a:e017 | Formosa... | eHome Infrared Receiver      | 2     | mceusb     | A1471119F3 |
| 1509:9242 | First I... | eHome Infrared Transceiver   | 2     | mceusb     | 3ADB7D01A9 |

### Input/keyboard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:c52b | Logitech   | Unifying Receiver            | 1510  | usbhid     | 62E3C9247C |
| 062a:4101 | MosArt ... | Wireless Keyboard/Mouse      | 779   | usbhid     | F68CFBE3F5 |
| 046d:c534 | Logitech   | Unifying Receiver            | 729   | usbhid     | 7637F3DE5F |
| 1c4f:0002 | SiGma M... | Keyboard TRACER Gamma Ivory  | 632   | usbhid     | 8B3744250A |
| 09da:054f | A4Tech     | USB Device                   | 624   | usbhid     | BD3CFBCE71 |
| 09da:9090 | A4Tech     | XL-730K / XL-750BK / XL-7... | 585   | usbhid     | 666B4349AD |
| 046d:c31c | Logitech   | Keyboard K120 for Business   | 515   | usbhid     | 808448B5B6 |
| 04d9:1702 | Holtek ... | Keyboard LKS02               | 390   | usbhid     | 02CBA6FDA0 |
| 045e:0745 | Microsoft  | Nano Transceiver v1.0 for... | 372   | usbhid     | 26243D93F4 |
| 1c4f:0026 | SiGma M... | Keyboard                     | 272   | usbhid     | 56D8AE9D24 |
| 04f3:0103 | Elan Mi... | ActiveJet K-2024 Multimed... | 266   | usbhid     | 8B7204FCBA |
| 1a2c:2124 | China R... | USB Keyboard                 | 213   | usbhid     | B2869F2D2D |
| 046d:c52e | Logitech   | MK260 Wireless Combo Rece... | 198   | usbhid     | 891002E8F2 |
| 0518:0001 | EzKEY      | USB to PS2 Adaptor v1.09     | 192   | usbhid     | 8226B90793 |
| 04d9:1603 | Holtek ... | Keyboard                     | 169   | usbhid     | 240876777B |
| 1a2c:2d23 | China R... | USB Keyboard                 | 167   | usbhid     | 8C4047657D |
| 09da:0260 | A4Tech     | KV-300H Isolation Keyboard   | 158   | usbhid     | 8EAEF3C906 |
| 1a2c:0e24 | China R... | USB Keyboard                 | 147   | usbhid     | DD4DA32934 |
| 24ae:2000 | RAPOO      | 2.4G Wireless Device         | 134   | usbhid     | 415CFBF22F |
| 04d9:1503 | Holtek ... | Shortboard Lefty             | 127   | usbhid     | 7F1F084A4F |
| 1a2c:0c23 | China R... | USB Keyboard                 | 114   | usbhid     | A1DD312C27 |
| 1a2c:0c21 | China R... | USB Keyboard                 | 108   | usbhid     | 699B1F26E0 |
| 0461:0010 | Primax ... | HP PR1101U / Primax PMX-K... | 107   | usbhid     | 0B02A9E571 |
| 413c:2107 | Dell       | USB Entry Keyboard           | 104   | usbhid     | 65A9CF6ADE |
| 046d:c517 | Logitech   | LX710 Cordless Desktop Laser | 103   | usbhid     | F3E244219B |
| 062a:3286 | MosArt ... | Nano Receiver [Sandstrom ... | 102   | usbhid     | F47F34752E |
| 1a2c:2c27 | China R... | USB Keyboard                 | 99    | usbhid     | A0518E949A |
| 03f0:0024 | Hewlett... | KU-0316 Keyboard             | 94    | usbhid     | AF9F6ACE3F |
| 1d57:fa20 | Xenta      | 2.4G Receiver                | 87    | usbhid     | F043044546 |
| 413c:2003 | Dell       | Keyboard                     | 85    | usbhid     | C92DC5D0CF |
| 045e:07b2 | Microsoft  | 2.4GHz Transceiver v8.0 u... | 83    | usbhid     | F03FCA81E0 |
| 046d:c31d | Logitech   | Media Keyboard K200          | 83    | usbhid     | C9CCBD7C3F |
| 09da:9066 | A4Tech     | F3 V-Track Gaming Mouse      | 83    | usbhid     | B724162662 |
| 258a:0001 | SINO WE... | USB KEYBOARD                 | 82    | usbhid     | 70E729A005 |
| 062a:0201 | MosArt ... | Defender Office Keyboard ... | 81    | usbhid     | B26ED41AB8 |
| 0e8f:00a7 | GreenAsia  | 2.4G RX                      | 78    | usbhid     | 82E5D349D1 |
| 1a81:1004 | Holtek ... | Wireless Dongle              | 78    | usbhid     | 6567AEB3C4 |
| 0a5c:4502 | Broadcom   | Keyboard (Boot Interface ... | 71    | usbhid     | 68BABB69CB |
| 0e8f:0022 | GreenAsia  | multimedia keyboard contr... | 71    | usbhid     | 3602A90378 |
| 248a:8566 | Maxxter    | SVEN RX 360 Art Wireless ... | 71    | usbhid     | 8AB719EA6C |
| 045e:00db | Microsoft  | Natural Ergonomic Keyboar... | 70    | usbhid     | FEAA959521 |
| 24ae:2001 | RAPOO      | 5G Wireless Device           | 69    | usbhid     | B8392B7335 |
| 046d:c312 | Logitech   | DeLuxe 250 Keyboard          | 64    | usbhid     | 4E440FBE69 |
| 040b:2000 | Weltren... | USB Keyboard                 | 63    | usbhid     | 54231260FF |
| 04b3:3025 | IBM        | NetVista Full Width Keyboard | 63    | usbhid     | F664FB0C42 |
| 045e:07f8 | Microsoft  | Wired Keyboard 600 (model... | 62    | usbhid     | 42C519E784 |
| 045e:07fd | Microsoft  | Nano Transceiver 1.1         | 62    | usbhid     | 71C7CF2056 |
| 413c:2113 | Dell       | KB216 Wired Keyboard         | 62    | usbhid     | 21F5EEF1AB |
| 046b:ff10 | America... | Virtual Keyboard and Mouse   | 61    | usbhid     | CEC82EF5D0 |
| 0566:3002 | Montere... | Keyboard                     | 60    | usbhid     | D77F80F180 |
| 04f2:0833 | Chicony... | KU-0833 Keyboard             | 58    | usbhid     | 89E5AA85A6 |
| 045e:0750 | Microsoft  | Wired Keyboard 600           | 57    | usbhid     | A1E970227D |
| 1d57:fa60 | Xenta      | 2.4G Receiver                | 56    | usbhid     | 1A1634FC24 |
| 0458:0708 | KYE Sys... | Multimedia Keyboard          | 53    | usbhid     | 5C380FEC25 |
| 1c4f:0016 | SiGma M... | USB Keyboard                 | 53    | usbhid     | DD25592A09 |
| 045e:00dd | Microsoft  | Comfort Curve Keyboard 20... | 50    | usbhid     | 5AFC22B5E1 |
| 0566:3107 | Montere... | Keyboard                     | 50    | usbhid     | E2E650868B |
| 046d:c328 | Logitech   | Corded Keyboard K280e        | 49    | usbhid     | 1E9BB53944 |
| 0a81:0101 | Chesen ... | Keyboard                     | 48    | usbhid     | F0B3D3251C |
| 0c45:7603 | Microdia   | USB Keyboard                 | 48    | usbhid     | AAD0551E27 |
| 03f0:a407 | Hewlett... | Wireless Optical Comfort ... | 47    | usbhid     | AB33DE8D3B |
| 09da:f613 | A4Tech     | USB Device                   | 47    | usbhid     | 873CD3A203 |
| 17ef:602d | Lenovo     | Black Silk USB Keyboard      | 46    | usbhid     | C80A50B2B4 |
| 09da:90a0 | A4Tech     | USB Device                   | 45    | usbhid     | F801DA09F7 |
| 046d:c318 | Logitech   | Illuminated Keyboard         | 44    | usbhid     | D1EC1DAC8F |
| 09da:9033 | A4Tech     | X-718BK Optical Mouse        | 44    | usbhid     | E4A1AC8DFE |
| 046d:c315 | Logitech   | Classic Keyboard 200         | 43    | usbhid     | 140DAF886E |
| 04f2:0402 | Chicony... | Genius LuxeMate i200 Keyb... | 43    | usbhid     | ABCF5C7050 |
| 0b38:0010 | Gear Head  | 107-Key Keyboard             | 43    | usbhid     | 42CC2F59E6 |
| 2a7a:9a18 | CASUE      | USB Keyboard                 | 42    | usbhid     | 01EB97A943 |
| 04f2:0116 | Chicony... | KU-2971/KU-0325 Keyboard     | 41    | usbhid     | 0F3DCCFE4E |
| 413c:2106 | Dell       | Dell QuietKey Keyboard       | 40    | usbhid     | 0BE7A39100 |
| 1ea7:0066 | SHARKOO... | [Mediatrack Edge Mini Key... | 39    | usbhid     | C76B2FB327 |
| 045e:0800 | Microsoft  | Microsoft Nano Transceive... | 38    | usbhid     | 9A41C725F3 |
| 0557:2419 | ATEN In... | Generic USB Mouse            | 37    | usbhid     | 8E73F804F5 |
| 040b:2013 | Weltren... | 2.4G Wireless Keyboard&Mouse | 36    | usbhid     | F8FD891B32 |
| 046a:0023 | Cherry     | CyMotion Master Linux Key... | 35    | usbhid     | D084D64BDF |
| 04fc:05d8 | Sunplus... | Wireless keyboard/mouse      | 35    | usbhid     | 99B2ABEC05 |
| 1ea7:0002 | SHARKOO... | Trust Wireless Keyboard &... | 35    | usbhid     | 0994A3EEB3 |
| 03f0:034a | Hewlett... | Elite Keyboard               | 33    | usbhid     | 341917FD42 |
| 046d:c316 | Logitech   | HID-Compliant Keyboard       | 33    | usbhid     | 8D8BE94484 |
| 0603:00f2 | Novatek... | Keyboard (Labtec Ultra Fl... | 33    | usbhid     | AC96DD45F9 |
| 0e8f:00a5 | GreenAsia  | 2.4G RX                      | 33    | usbhid     | 95D420F37F |
| 09da:90c0 | A4Tech     | USB Device                   | 32    | usbhid     | 6A60A724F9 |
| 413c:8161 | Dell       | Integrated Keyboard          | 32    | usbhid     | 6722706FA2 |
| 04d9:1605 | Holtek ... | USB Keyboard                 | 31    | usbhid     | 5D6E2E4B43 |
| 04f2:0408 | Chicony... | USB-PS/2 Combo Keyboard      | 31    | usbhid     | 9D629FBC20 |
| 413c:8505 | Dell       | Universal Receiver           | 31    | usbhid     | 1675040CCD |
| 0603:0002 | Novatek... | USB Composite Device         | 30    | usbhid     | CEAC334581 |
| 062a:5918 | MosArt ... | 2.4G Keyboard Mouse          | 30    | usbhid     | 8F2E060D39 |
| 1a2c:0021 | China R... | Keyboard                     | 30    | usbhid     | 664ABD17F4 |
| 045e:07b9 | Microsoft  | Wired Keyboard 200           | 29    | usbhid     | FFB658BAF4 |
| 05ac:0221 | Apple      | Aluminum Keyboard (ISO)      | 29    | usbhid     | 2EC70E7CEC |
| 062a:4182 | MosArt ... | 2.4G Keyboard Mouse          | 29    | usbhid     | D607079392 |
| 1241:1503 | Belkin     | Keyboard                     | 29    | usbhid     | AA051D69D4 |
| 1a2c:0002 | China R... | USB Keykoard                 | 29    | usbhid     | BE6DED977D |
| 03ee:8801 | Mitsumi    | Keyboard                     | 28    | usbhid     | 0D2A7EFA14 |
| 045e:0780 | Microsoft  | Comfort Curve Keyboard 3000  | 28    | usbhid     | ED68722348 |
| 0c45:760b | Microdia   | USB Keyboard                 | 28    | usbhid     | BE6D815002 |
| 13ba:0018 | PCPlay     | Barcode PCP-BCG4209          | 28    | usbhid     | CBA535C695 |

### Input/mouse (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 093a:2510 | Pixart ... | Optical Mouse                | 1206  | usbhid     | 8C4047657D |
| 0458:003a | KYE Sys... | NetScroll+ Mini Traveler ... | 1024  | usbhid     | EDC325267B |
| 046d:c52f | Logitech   | Unifying Receiver            | 986   | usbhid     | 6F94FCD1C0 |
| 046d:c077 | Logitech   | M105 Optical Mouse           | 602   | usbhid     | 7C7D8F8CB6 |
| 046d:c05a | Logitech   | M90/M100 Optical Mouse       | 577   | usbhid     | D2006E7A87 |
| 09da:000a | A4Tech     | Optical Mouse Opto 510D /... | 562   | usbhid     | F8AE92B32F |
| 0000:0538 |            | USB OPTICAL MOUSE            | 406   | usbhid     | 4D00578B8B |
| 275d:0ba6 |            | USB OPTICAL MOUSE            | 380   | usbhid     | 86987CF1ED |
| 093a:2521 | Pixart ... | Optical Mouse                | 321   | usbhid     | A1D2E02773 |
| 1bcf:0005 | Sunplus... | USB Optical Mouse            | 301   | usbhid     | BF4A9DEE07 |
| 1c4f:0034 | SiGma M... | Usb Mouse                    | 295   | usbhid     | 8226B90793 |
| 09da:c10a | A4Tech     | USB Mouse                    | 240   | usbhid     | EE184BFE51 |
| 1ea7:0064 | SHARKOO... | 2.4G Wireless Mouse          | 228   | usbhid     | 6722706FA2 |
| 062a:4102 | MosArt ... | 2.4G Wireless Mouse          | 205   | usbhid     | 0FCCED0386 |
| 046d:c05b | Logitech   | M-U0004 810-001317 [B110 ... | 203   | usbhid     | 20EE58CBC8 |
| 248a:8367 | Maxxter    | SVEN Comfort 3400 Wireless   | 194   | usbhid     | C5ADBBB2B3 |
| 10c4:8105 | Cygnal ... | USB OPTICAL MOUSE            | 170   | usbhid     | 51388B8407 |
| 248a:8366 | Maxxter    | Wireless Optical Mouse AC... | 156   | usbhid     | 9CD2D7F72B |
| 046d:c050 | Logitech   | RX 250 Optical Mouse         | 148   | usbhid     | 15E5D2BB9D |
| 15d9:0a4f | Trust I... | Optical Mouse                | 145   | usbhid     | B2A7C69D92 |
| 18f8:0f97 | [Maxxter]  | USB OPTICAL MOUSE            | 142   | usbhid     | 763D365B92 |
| 1a2c:0042 | China R... | Usb Mouse                    | 140   | usbhid     | 153247F60A |
| 1bcf:0007 | Sunplus... | Optical Mouse                | 136   | usbhid     | 7414D62366 |
| 0101:0007 |            | USB OPTICAL MOUSE            | 125   | usbhid     | E3D9D5BAE8 |
| 13ee:0001 | MosArt     | Optical Mouse                | 114   | usbhid     | 2E7D16AEC3 |
| 045e:00cb | Microsoft  | Basic Optical Mouse v2.0     | 113   | usbhid     | B39AC90CA0 |
| 046d:c016 | Logitech   | Optical Wheel Mouse          | 113   | usbhid     | D7977A3B0E |
| 2188:0ae1 | CalDigit   | USB OPTICAL MOUSE            | 112   | usbhid     | 42DF53B120 |
| 046d:c018 | Logitech   | Optical Wheel Mouse          | 111   | usbhid     | 74624FF493 |
| 0e8f:00fb | GreenAsia  | USB Mouse                    | 99    | usbhid     | 763D365B92 |
| 046d:c03e | Logitech   | Premium Optical Wheel Mou... | 95    | usbhid     | CCE7F9292D |
| 046d:c062 | Logitech   | M-UAS144 [LS1 Laser Mouse]   | 95    | usbhid     | A31B1E8E5E |
| 04f3:0235 | Elan Mi... | Optical Mouse                | 91    | usbhid     | 61625F7FA6 |
| 04b4:0060 | Cypress... | Wireless optical mouse       | 89    | usbhid     | 88B7D96AEE |
| 045e:0040 | Microsoft  | Wheel Mouse Optical          | 86    | usbhid     | 46324F79EA |
| 15d9:0a4d | Trust I... | Optical Mouse                | 86    | usbhid     | FF78BFBB07 |
| 192f:0916 | Avago T... | USB Optical Mouse            | 85    | usbhid     | DD20758A89 |
| 25a7:fa23 | Compx      | 2.4G Receiver                | 84    | usbhid     | 3D9E77AE8A |
| 046d:c00e | Logitech   | M-BJ58/M-BJ69 Optical Whe... | 79    | usbhid     | 72549E030D |
| 09da:8090 | A4Tech     | X-718BK Oscar Optical Gam... | 78    | usbhid     | 18FC3D2E64 |
| 276d:1160 | YSTEK      | G Mouse                      | 73    | usbhid     | 4038A574AC |
| 0a5c:4503 | Broadcom   | Mouse (Boot Interface Sub... | 71    | usbhid     | 68BABB69CB |
| 0461:4d0f | Primax ... | HP Optical Mouse             | 70    | usbhid     | EFA3992D9A |
| 046d:c069 | Logitech   | M-U0007 [Corded Mouse M500]  | 67    | usbhid     | 4CED599618 |
| 093a:2516 | Pixart ... | USB OPTICAL MOUSE            | 67    | usbhid     | 99614383EB |
| 18f8:0f99 | [Maxxter]  | Optical gaming mouse         | 66    | usbhid     | 02CBA6FDA0 |
| 1c4f:0003 | SiGma M... | HID controller               | 66    | usbhid     | 65A9CF6ADE |
| 17ef:6019 | Lenovo     | Lenovo USB Optical Mouse     | 64    | usbhid     | F664FB0C42 |
| 413c:301a | Dell       | MS116 USB Optical Mouse      | 64    | usbhid     | EB49973873 |
| 3938:1031 | MOSART ... | 2.4G Wireless Mouse          | 63    | usbhid     | FE652A02C9 |
| 0458:0186 | KYE Sys... | Wired Mouse                  | 58    | usbhid     | 7637F3DE5F |
| 279e:024e | 2.4G wi... | 2.4G wireless USB Device     | 58    | usbhid     | 8AB719EA6C |
| 04b4:0033 | Cypress... | Mouse                        | 57    | usbhid     | F5F1021D04 |
| 046d:c06c | Logitech   | Optical Mouse                | 56    | usbhid     | 9A249DA8EE |
| 09da:000e | A4Tech     | X-F710F Optical Mouse 3xF... | 56    | usbhid     | 643DD308BF |
| 0000:3825 |            | USB OPTICAL MOUSE            | 54    | usbhid     | 54C92BF69C |
| 15d9:0a4c | Trust I... | USB+PS/2 Optical Mouse       | 53    | usbhid     | 42CC2F59E6 |
| 045e:0083 | Microsoft  | Basic Optical Mouse          | 48    | usbhid     | 4EA0694850 |
| 04d9:0499 | Holtek ... | Optical Mouse                | 48    | usbhid     | 77F3E43AB2 |
| 046d:c408 | Logitech   | Marble Mouse (4-button)      | 47    | usbhid     | 70E729A005 |
| 1d57:0008 | Xenta      | 2.4G Wireless Optical Mouse  | 47    | usbhid     | 268D53A8B4 |
| 09da:0006 | A4Tech     | Optical Mouse WOP-35 / Tr... | 44    | usbhid     | 0533339E4E |
| 09da:0080 | A4Tech     | USB Mouse                    | 44    | usbhid     | 4611843133 |
| 1d57:0001 | Xenta      | wireless device              | 44    | usbhid     | E3B1F6D810 |
| 248a:8514 | Maxxter    | Wireless Receiver            | 44    | usbhid     | 9137FB3859 |
| 045e:0084 | Microsoft  | Basic Optical Mouse          | 42    | usbhid     | DDF30C670A |
| 192f:0416 | Avago T... | ADNS-5700 Optical Mouse C... | 42    | usbhid     | 5D6E2E4B43 |
| 046d:c019 | Logitech   | Optical Tilt Wheel Mouse     | 41    | usbhid     | E1D809E15F |
| 04d9:a09f | Holtek ... | E-Signal LUOM G10 Mechani... | 41    | usbhid     | F6CCF2BBA6 |
| 1c4f:0032 | SiGma M... | Usb Mouse                    | 41    | usbhid     | F72534E2D2 |
| 046d:c045 | Logitech   | Optical Mouse                | 40    | usbhid     | 88DB43EE6F |
| 1bcf:0002 | Sunplus... | USB Optical Wheel Mouse      | 40    | usbhid     | 64BD62C7EA |
| 0458:002e | KYE Sys... | NetScroll + Traveler / Ne... | 39    | usbhid     | EB29C895FA |
| 045e:0797 | Microsoft  | Optical Mouse 200            | 39    | usbhid     | F1E5880584 |
| 04f3:0234 | Elan Mi... | Optical Mouse                | 39    | usbhid     | 936B9A47EC |
| 17ef:602e | Lenovo     | USB Optical Mouse            | 39    | usbhid     | F9F3745636 |
| 046d:c51b | Logitech   | V220 Cordless Optical Mou... | 38    | usbhid     | FE7535550F |
| 04fc:05da | Sunplus... | SPEEDLINK SNAPPY Wireless... | 38    | usbhid     | C77FA19C2B |
| 046d:c246 | Logitech   | Gaming Mouse G300            | 37    | usbhid     | B14A3FFEFB |
| 275d:0a29 |            | USB OPTICAL MOUSE            | 37    | usbhid     | 9CEDE9D704 |
| 045e:0039 | Microsoft  | IntelliMouse Optical         | 36    | usbhid     | 1395F6EFED |
| 046d:c526 | Logitech   | Nano Receiver                | 36    | usbhid     | 4C990A61B6 |
| 03f0:134a | Hewlett... | Optical Mouse                | 35    | usbhid     | 046006226D |
| 046d:c040 | Logitech   | Corded Tilt-Wheel Mouse      | 35    | usbhid     | B019AFD4C1 |
| 04fc:0538 | Sunplus... | Wireless Optical Mouse 2.... | 34    | usbhid     | 2ACD24AD30 |
| 04b3:310c | IBM        | Wheel Mouse                  | 33    | usbhid     | E2D3942D30 |
| 1a2c:0044 | China R... | Usb Mouse                    | 33    | usbhid     | 5B60FEFCEC |
| 413c:8162 | Dell       | Integrated Touchpad [Syna... | 32    | usbhid     | 6722706FA2 |
| 89e5:101b |            | USB OPTICAL MOUSE            | 32    | usbhid     | E3825A8890 |
| 03f0:094a | Hewlett... | Optical Mouse [672662-001]   | 30    | usbhid     | C9FA6E4826 |
| 248a:8564 | Maxxter    | SVEN RX 305 Wireless Mouse   | 30    | usbhid     | 6F74CC29B9 |
| 0461:4d64 | Primax ... | USB Optical Mouse            | 29    | usbhid     | 09CC6BAB56 |
| 10c4:8103 | Cygnal ... | USB OPTICAL MOUSE            | 28    | usbhid     | 573813F74B |
| 1d57:ad03 | Xenta      | Feeling-tech-USB product     | 28    | usbhid     | 517CAD6069 |
| 24ae:1100 | RAPOO      | 2.4G Wireless Device         | 28    | usbhid     | F4928B0ED4 |
| 2635:0601 |            | 2.4G RF MOUSE                | 28    | usbhid     | 2BC400D84F |
| 046d:c07e | Logitech   | Gaming Mouse G402            | 27    | usbhid     | 3FB755ED84 |
| 046d:c084 | Logitech   | G102 Prodigy Gaming Mouse    | 27    | usbhid     | 16C4C7C1C0 |
| 046d:c521 | Logitech   | Cordless Mouse Receiver      | 27    | usbhid     | AC0C824624 |
| 1bcf:053a | Sunplus... | Targa Silvercrest OMC807-... | 27    | usbhid     | D7AB000EA5 |

### Isdn adapter (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| ffff:ffff | RAPOO      | AVM FRITZ!Card PCMCIA        | 5     | usbhid     | B8314E6CBC |

### Joystick (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 068e:00f2 | CH Prod... | Flight Sim Pedals            | 3     | usbhid     | 803350A260 |
| 24c6:581a | Unknown... | XB1 Classic controller       | 3     | xpad       | 87B482DE1D |
| 046d:c262 | Logitech   | G920 Driving Force Racing... | 2     | usbhid     | 13D4BA319E |
| 07b5:0317 | Mega Wo... | USB Game Controllers         | 2     | usbhid     | E03A8C0C89 |
| 20bc:5500 | SHANWAN    | Android Gamepad              | 2     | usbhid     | 491DB7C6BD |
| 231d:1105 | www.vkb... | GTX Throttle                 | 2     | usbhid     | CB2AAA3EDB |
| 0079:189c | DragonRise | PXN-V3II                     | 1     | xpad       | D90F3585DA |
| 045e:000e | Microsoft  | SideWinder Freestyle Pro     | 1     | usbhid     | 631092B6D1 |
| 068e:00f3 | CH Prod... | Fighterstick                 | 1     | usbhid     | CB2AAA3EDB |
| 0e6f:0119 | Logic3     | MW3 Wireless Controller f... | 1     | usbhid     | 2933DDC278 |
| 11ff:001b |            | PXN-9613                     | 1     | usbhid     | C23CA49E1E |
| 11ff:001c |            | PXN-V3II                     | 1     | usbhid     | D1DED92F20 |
| 145f:01bb | Trust      | Gamepad                      | 1     | usbhid     | 708CD13E0A |
| 20d6:ca6d | Unknown... | Pro Ex                       | 1     | usbhid     | 0E26792709 |

### Mfp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:042a | Hewlett... | LaserJet M1132 MFP           | 26    | usblp      | BAA91679D8 |
| 03f0:3b17 | Hewlett... | LaserJet M1005 MFP           | 22    | usblp      | 1C1D0D6198 |
| 03f0:222a | Hewlett... | LaserJet Pro MFP M125rnw     | 17    | usblp      | EE184BFE51 |
| 03f0:5617 | Hewlett... | LaserJet M1120 MFP           | 11    | usblp      | 097B4FFD71 |
| 0924:3cef | Xerox      | Phaser 3100MFP               | 11    | usblp      | 3B024E0CB3 |
| 0924:42af | Xerox      | WorkCentre 3045B             | 9     | usblp      | 4E86FFF7EA |
| 04b8:083f | Seiko E... | Stylus CX4300/CX4400/CX55... | 8     | usblp      | EDDD834850 |
| 03f0:052a | Hewlett... | LaserJet Professional M12... | 7     | usblp      | 5CE0BBFFF6 |
| 03f0:5717 | Hewlett... | LaserJet M1120n MFP          | 6     | usblp      | 6697D98216 |
| 03f0:622a | Hewlett... | LaserJet MFP M129-M134       | 5     | usblp      | 1B55239D68 |
| 04b8:084d | Seiko E... | PX-402A [Stylus SX115/Sty... | 5     | usblp      | 105F0DC109 |
| 03f0:3b2a | Hewlett... | Color LaserJet MFP M277dw    | 4     | usblp      | 240876777B |
| 0482:0495 | Kyocera    | FS-1020MFP                   | 4     | usblp      | DCFF794CD3 |
| 04b8:082f | Seiko E... | PX-A620 [Stylus CX3900/DX... | 4     | usblp      | 8B7624FF98 |
| 03f0:062a | Hewlett... | LaserJet 100 colorMFP M175a  | 3     | usblp      | A3BBB7F8A9 |
| 04b8:080e | Seiko E... | PX-A550 [CX-3500/3600/365... | 3     | usblp      | 1AB6F30041 |
| 0924:3d6f | Xerox      | WorkCentre 6605DN            | 3     | usblp      | 79A097BF6F |
| 03f0:142a | Hewlett... | LaserJet 400 MFP M425dn      | 2     | usblp      | C496949B2E |
| 0482:0497 | Kyocera    | FS-1025MFP                   | 2     | usblp      | FD225327D7 |
| 04b8:0841 | Seiko E... | PX-401A [ME 300/Stylus NX... | 2     | usblp      | 75F89195A5 |
| 0924:42c4 | Xerox      | WorkCentre 3615              | 2     | usblp      | 0BF7A6E91D |
| 0924:42da | Xerox      | WorkCentre 3025              | 2     | usblp      | 70F28E74B9 |
| 0924:42db | Xerox      | WorkCentre 3215              | 2     | usblp      | 9D7BDB2727 |
| 03f0:1d2a | Hewlett... | Color LaserJet flow MFP M880 | 1     | usblp      | 9F2622FF85 |
| 03f0:242a | Hewlett... | Color LaserJet Pro MFP M176n | 1     | usblp      | 45CE8F3BAB |
| 03f0:252a | Hewlett... | LaserJet 500 colorMFP M570dw | 1     | usblp      | 8EA70251FB |
| 03f0:2d2a | Hewlett... | LaserJet Pro MFP M225dw      | 1     | usblp      | 589D629D00 |
| 03f0:2e2a | Hewlett... | LaserJet Pro MFP M435nw      | 1     | usblp      | A457D54FAD |
| 03f0:322a | Hewlett... | LaserJet Pro MFP M127fn      | 1     | usblp      | 35F08E0E86 |
| 03f0:362a | Hewlett... | Officejet Color FlowMFP X585 | 1     | usblp      | 4966DF06F4 |
| 03f0:442a | Hewlett... | Color LaserJet Flow MFP M680 | 1     | usblp      | BF4C79032E |
| 03f0:5a2a | Hewlett... | LaserJet MFP M426fdw         | 1     | usblp      | 2FB769F3C1 |
| 03f0:932a | Hewlett... | LaserJet Pro MFP M26nw       | 1     | usblp      | 30B096BF35 |
| 03f0:9e17 | Hewlett... | LaserJet 500 MFP M525        | 1     | usblp      | 80E0F6373A |
| 03f0:9f17 | Hewlett... | LaserJet 500 color MFP M575  | 1     | usblp      | A043EA04EA |
| 03f0:bf2a | Hewlett... | LaserJet MFP M28-M31         | 1     | usblp      | 7C26C8530E |
| 04b8:0818 | Seiko E... | Stylus CX3700/CX3800/DX3800  | 1     | usblp      | 25B3B9DEBA |
| 0924:3d6b | Xerox      | WorkCentre 6505DN            | 1     | usblp      | 66BC368A83 |
| 0924:42d4 | Xerox      | WorkCentre 6027              | 1     | usblp      | E363684B4B |
| 0924:42dc | Xerox      | WorkCentre 3225              | 1     | usblp      | 8ABC3D5F35 |
| 413c:590b | Dell       | MFP                          | 1     | usblp      | 0F4BBAE4FA |

### Modem (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 12d1:1506 | Huawei ... | E398 LTE/UMTS/GSM Modem/N... | 323   | uas, us... | 7B7C9D230C |
| 12d1:1436 | Huawei ... | E173 3G Modem (modem-mode)   | 36    | usb_sto... | 766B0474A3 |
| 0bdb:1911 | Ericsso... | F5521gw                      | 27    | cdc_acm    | FBF8462F41 |
| 12d1:1001 | Huawei ... | E161/E169/E620/E800 HSDPA... | 27    | usb_sto... | 4C163D8A71 |
| 12d1:140c | Huawei ... | E180v                        | 23    | usb_sto... | 9A0C8FB6A2 |
| 12d1:1003 | Huawei ... | E220 HSDPA Modem / E230/E... | 22    | usb_sto... | D0B36608B4 |
| 0bdb:1926 | Ericsso... | H5321 gw Mobile Broadband... | 19    | cdc_acm    | E70E5228B2 |
| 0bdb:1900 | Ericsso... | F3507g Mobile Broadband M... | 16    | cdc_acm    | A23E000798 |
| 03f0:3d1d | Hewlett... | hs2350 HSPA+ MobileBroadband | 13    | cdc_acm    | 79EFD09885 |
| 27c6:5301 | HTMicro... | Goodix Fingerprint Device    | 13    | cdc_acm    | 4E3F5803B1 |
| 27c6:5395 | HTMicro... | Goodix Fingerprint Device    | 13    | cdc_acm    | 7A9639F003 |
| 2341:0043 | Arduino SA | Uno R3 (CDC ACM)             | 12    | cdc_acm    | E267629A35 |
| 03f0:3a1d | Hewlett... | hs2340 HSPA+ mobile broad... | 11    | cdc_acm    | 13780FAE80 |
| 0bdb:193e | Ericsso... | N5321 gw                     | 10    | cdc_acm    | B34F861676 |
| 27c6:5385 | HTMicro... | Goodix Fingerprint Device    | 10    | cdc_acm    | E80894BD2A |
| 413c:8147 | Dell       | F3507g Mobile Broadband M... | 8     | cdc_acm    | F474D6B56B |
| 413c:818e | Dell       | Dell Wireless 5560 Single... | 8     | cdc_acm    | 2E0081C6C9 |
| 0658:0200 | Sigma D... | Aeotec Z-Stick Gen5 (ZW09... | 7     | cdc_acm    | 3D0DACB49E |
| 12d1:1404 | Huawei ... | EM770W miniPCI WCDMA Modem   | 7     | usb_sto... | 1D4EF489F6 |
| 413c:818d | Dell       | DW5550                       | 7     | cdc_acm    | 8C26DF88EE |
| 12d1:14ac | Huawei ... | HUAWEI Mobile                | 6     | option     | 167B3FD913 |
| 1546:01a7 | U-Blox     | u-blox 7 - GPS/GNSS Receiver | 6     | cdc_acm    | 8C6609B568 |
| 19d2:1515 | ZTE WCD... | MF192                        | 5     | cdc_acm    | 3C75190E68 |
| 413c:8184 | Dell       | F3607gw v2 Mobile Broadba... | 5     | cdc_acm    | 7ED1F06568 |
| 04d8:00df | Microch... | MCP2200 USB Serial Port E... | 4     | cdc_acm    | C09E006619 |
| 1546:01a5 | U-Blox     | [u-blox 5]                   | 4     | cdc_acm    | B46F2FEE35 |
| 1edf:6004 | Select ... | MCD-640S-1EDF-6004           | 4     | cdc_acm    | F9D3A09989 |
| 04e8:6872 | Samsung... | Kiera                        | 3     | cdc_acm    | 9A145A3041 |
| 12d1:1570 | Huawei ... | Mobile Broadband Module      | 3     | option     | 63B03B7E15 |
| 12d1:1c1e | Huawei ... | Mass Storage                 | 3     | uas, us... | DDD57927D5 |
| 1519:0020 | Comneon    | HSIC Device                  | 3     | cdc_acm    | E277646CEF |
| 8087:0ab6 | Intel      | UDOO X86                     | 3     | cdc_acm    | AF7921E479 |
| 0421:0302 | Nokia M... | N8-00                        | 2     | cdc_acm    | 495FCF02B1 |
| 0483:5740 | STMicro... | STM32F407                    | 2     | cdc_acm    | 229BA614EC |
| 04e2:1410 | Exar       | XR21V1410 USB-UART IC        | 2     | cdc_acm... | 44204F310C |
| 0baf:00ec | U.S. Ro... | 56K Faxmodem                 | 2     |            | EF974030B3 |
| 0bdb:190a | Ericsso... | F3307 Mobile Broadband Mo... | 2     | cdc_acm    | 4C648779A3 |
| 0e8d:0003 | MediaTek   | MT6227 phone                 | 2     | cdc_acm    | 380509822C |
| 106c:3714 | Curitel... | PANTECH USB MODEM [UM175]    | 2     | cdc_acm    | 93E38006D9 |
| 106c:3716 | Curitel... | UMW190 Modem                 | 2     | cdc_acm    | 06FBB87A4E |
| 27c6:5381 | HTMicro... | Goodix Fingerprint Device    | 2     | cdc_acm    | 7872901FE9 |
| 03f0:2f1d | Hewlett... | lc2010 Mobile Broadband M... | 1     | cdc_acm    | 34C71843B7 |
| 0421:01d0 | Nokia M... | E52                          | 1     | cdc_acm    | D649B2DEB3 |
| 0421:0223 | Nokia M... | E72-1                        | 1     | cdc_acm    | A913DFEFEE |
| 0421:026c | Nokia M... | N97 (PC Suite)               | 1     | cdc_acm    | 11D0F0433C |
| 0421:0348 | Nokia M... | Nokia 5228                   | 1     | cdc_acm    | 4F7EEE94F1 |
| 0421:0355 | Nokia M... | Nokia X2-00                  | 1     | cdc_acm    | 1F5E6B026B |
| 0421:0360 | Nokia M... | C1-01 Ovi Suite Mode         | 1     | cdc_acm    | 9C2894BEA0 |
| 0421:0524 | Nokia M... | Nokia 300                    | 1     | cdc_acm    | B96E92098E |
| 0421:05fd | Nokia M... | 202                          | 1     | cdc_acm    | 1A8A955A5B |
| 0421:0638 | Nokia M... | Nokia USB Modem              | 1     | cdc_acm    | 2D146B746C |
| 0421:0664 | Nokia M... | Nokia 301 Dual SIM           | 1     | cdc_acm    | 17752ECF0C |
| 0451:16a8 | Texas I... | TI CC2531 USB CDC            | 1     | cdc_acm    | D4224E0573 |
| 0461:0033 | Primax ... | USB_Focus                    | 1     | cdc_acm    | 5278A91530 |
| 04d8:fd5e | Microch... | VeRSis                       | 1     | cdc_acm    | AF6FC8545B |
| 04e8:6601 | Samsung... | Mobile Phone                 | 1     | visor, ... | 25239307A1 |
| 04e8:6773 | Samsung... | HSPA Modem                   | 1     | cdc_acm    | 06B0B62AAC |
| 04e8:6843 | Samsung... | E2530 Phone (Samsung Kies... | 1     | cdc_acm    | 55075885CA |
| 04e8:6845 | Samsung... | Mobile USB Modem             | 1     | cdc_acm    | 01619C75A2 |
| 0572:1329 | Conexan... | USB Modem                    | 1     | cdc_acm    | 7A44DA1E2F |
| 0572:cb16 | Conexan... | USB-ADSL Modem               | 1     |            | 07217A2477 |
| 067b:2323 | Prolifi... | 123_AaP                      | 1     | cdc_acm    | D9A29354A7 |
| 0930:1314 | Toshiba    | F5521gw                      | 1     | cdc_acm    | 6F44CBE917 |
| 0930:1319 | Toshiba    | H5321gw                      | 1     | cdc_acm    | 68749635C1 |
| 0ace:1608 | ZyDAS      | ZyXEL Omni FaxModem 56K UNO  | 1     | cdc_acm    | 3489DBD51A |
| 0bdb:1902 | Ericsso... | F3507g v2 Mobile Broadban... | 1     | cdc_acm    | 211BE91D80 |
| 0bdb:1905 | Ericsso... | F3607gw v2 Mobile Broadba... | 1     | cdc_acm    | 26A4676050 |
| 0bf1:0002 | Intracom   | netMod Driver Ver 2.4 (CAPI) | 1     | cdc_acm    | 9DDAB18C28 |
| 0e8d:2011 | MediaTek   | PassPlus                     | 1     | cdc_acm    | 83BFA1527C |
| 1004:61f2 | LG Elec... | LGE Android phone            | 1     | cdc_acm    | 4273247882 |
| 1209:1776 | InterBi... | Io                           | 1     | system7... | ECC26A9233 |
| 12d1:1465 | Huawei ... | K3765 HSPA                   | 1     | option     | 346F4EA91D |
| 12d1:151d | Huawei ... | Mass Storage                 | 1     | uas, us... | 304AA59840 |
| 12d1:1566 | Huawei ... | HUAWEI_MOBILE                | 1     | option     | B07034F89E |
| 12d1:1573 | Huawei ... | Mobile                       | 1     | option     | 740C1D3CBF |
| 16c0:05e1 | Van Ooi... | Free shared USB VID/PID p... | 1     | cdc_acm    | C7A9B4C273 |
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
| 2341:0001 | Arduino SA | Uno (CDC ACM)                | 1     | cdc_acm    | 515907EC21 |
| 2341:0042 | Arduino SA | Mega 2560 R3 (CDC ACM)       | 1     | cdc_acm    | 5D7483C11A |
| 2548:1002 | Pulse-E... | USB-CEC Adapter              | 1     | cdc_acm    | B4173B7EB7 |
| 27b1:0001 | UltiMac... | RAMBo                        | 1     | cdc_acm    | FFDEE4764D |
| 2912:0005 | ATOL Group | ATOL USB device              | 1     | cdc_acm    | 3956F73F02 |
| 2a03:0043 | dog hunter | Arduino Uno Rev3             | 1     | cdc_acm    | 5278A91530 |
| c001:c0de | Team Xe... | SX Pro Dongle                | 1     | cdc_acm    | 5DF12FB380 |

### Net/wimax (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0180 | Intel      | WiMAX Connection 2400m       | 42    | i2400m_usb | 130D733F55 |
| 8086:1406 | Intel      | WiMAX Connection 2400m       | 37    | i2400m_usb | A6DADFE6AF |
| 8086:0186 | Intel      | WiMAX Connection 2400m       | 21    | i2400m_usb | 195F0109A8 |
| 8087:07d6 | Intel      | Centrino WiMAX 6150          | 11    | i2400m_usb | 1FC56D39F8 |
| 8086:0188 | Intel      | WiMAX Connection 2400m       | 3     | i2400m_usb | C81404F4CA |

### Net/wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 148f:7601 | Ralink ... | MT7601U Wireless Adapter     | 235   | mt7601u    | DD4DA32934 |
| 0bda:8179 | Realtek... | RTL8188EUS 802.11n Wirele... | 223   | r8188eu    | FE7535550F |
| 0cf3:9271 | Qualcom... | AR9271 802.11n               | 216   | ath9k_htc  | 82E5D349D1 |
| 148f:5370 | Ralink ... | RT5370 Wireless Adapter      | 148   | rt2800usb  | C6FDAC0AEE |
| 0bda:8178 | Realtek... | RTL8192CU 802.11n WLAN Ad... | 134   | rtl8192cu  | 5F6E1A3B61 |
| 148f:3070 | Ralink ... | RT2870/RT3070 Wireless Ad... | 102   | rt2800usb  | 37B056E670 |
| 0bda:8176 | Realtek... | RTL8188CUS 802.11n WLAN A... | 85    | rtl8192cu  | E814DA247A |
| 0bda:8172 | Realtek... | RTL8191SU 802.11n WLAN Ad... | 39    | r8712u     | 65A9CF6ADE |
| 2357:0109 | Realtek    | RTL8192EU TL-WN823N 802.1... | 37    | rtl8xxxu   | ED8AF41B6E |
| 0bda:8189 | Realtek... | RTL8187B Wireless 802.11g... | 36    | rtl8187    | B26ED41AB8 |
| 2001:3c20 | D-Link     | 802.11 n WLAN                | 36    | rt2800usb  | 3F04B83DFD |
| 0bda:b812 | Realtek... | RTL8812BU USB3.0 802.11ac... | 31    | 8822bu     | 2703EE0766 |
| 0bda:818b | Realtek... | RTL8192EU ACT-WNP-UA-005 ... | 30    | rtl8xxxu   | 9CD2D7F72B |
| 2357:010c | Realtek    | RTL8188EUS TL-WN722N v2      | 30    | r8188eu    | 5B8AE7E31F |
| 0b05:17ba | ASUSTek... | N10 Nano 802.11n Network ... | 29    | rtl8192cu  | FC0B23D4DC |
| 148f:5572 | Ralink ... | RT5572 Wireless Adapter      | 29    | rt2800usb  | 0C9D9C254F |
| 0b05:1786 | ASUSTek... | USB-N10 802.11n Network A... | 27    | r8712u     | B2D5544528 |
| 0b05:17ab | ASUSTek... | USB-N13 802.11n Network A... | 26    | rtl8192cu  | A20DD4DABA |
| 148f:761a | Ralink ... | MT7610U ("Archer T2U" 2.4... | 26    | mt76x0u    | F940B41C82 |
| 045e:0719 | Microsoft  | Xbox 360 Wireless Adapter    | 25    | xpad       | ED7B2348A1 |
| 07d1:3c16 | D-Link ... | DWA-125 Wireless N 150 Ad... | 25    | rt2800usb  | 22D8D62C57 |
| 0bda:8171 | Realtek... | RTL8188SU 802.11n WLAN Ad... | 25    | r8712u     | 1579402536 |
| 148f:2573 | Ralink ... | RT2501/RT2573 Wireless Ad... | 23    | rt73usb    | 08FB21590A |
| 0846:9030 | NetGear    | WNA1100 Wireless-N 150 [A... | 22    | ath9k_htc  | B86DF74030 |
| 0cf3:1006 | Qualcom... | TP-Link TL-WN322G v3 / TL... | 22    | ath9k_htc  | C19D82302D |
| 0cf3:7015 | Qualcom... | TP-Link TL-WN821N v3 / TL... | 22    | ath9k_htc  | DBCE9BE550 |
| 148f:5372 | Ralink ... | RT5372 Wireless Adapter      | 22    | rt2800usb  | FF78BFBB07 |
| 2001:3319 | D-Link     | RTL8192EU DWA-131 Wireles... | 22    | rtl8xxxu   | A95491B363 |
| 7392:7811 | Edimax ... | EW-7811Un 802.11n Wireles... | 22    | rtl8192... | BC9F90FD94 |
| 0bda:8812 | Realtek... | RTL8812AU 802.11a/b/g/n/a... | 21    | 8812au     | 8C6609B568 |
| 0bda:8197 | Realtek... | RTL8187B Wireless Adapter    | 19    | rtl8187    | 6D00C70EFA |
| 2001:3c19 | D-Link     | DWA-125 Wireless N 150 Ad... | 19    | rt2800usb  | 4C91A0DF19 |
| 0bda:a811 | Realtek... | RTL8811AU 802.11a/b/g/n/a... | 17    | rtl8812au  | 96B4E832EE |
| 07d1:3303 | D-Link ... | DWA-131 802.11n Wireless ... | 16    | r8712u     | C5EE060717 |
| 07d1:3c03 | D-Link ... | AirPlus G DWL-G122 Wirele... | 14    | rt73usb    | 8AE6B6F651 |
| 0b05:179d | ASUSTek... | USB-N53 802.11abgn Networ... | 14    | rt2800usb  | 0C9CE69911 |
| 13d3:3323 | IMC Net... | RTL8191S WLAN Adapter        | 14    | r8712u     | 191844565C |
| 07d1:3a10 | D-Link ... | DWA-126 802.11n Wireless ... | 13    | ath9k_htc  | 7B96F419AD |
| 0b05:1791 | ASUSTek... | WL-167G v3 802.11n Adapte... | 13    | r8712u     | BA1AF12DA4 |
| 0bda:0811 | Realtek... | RTL8811AU 802.11ac WLAN A... | 13    | rtl8812au  | 5D65FDCE91 |
| 148f:3072 | Ralink ... | RT3072 Wireless Adapter      | 13    | rt2800usb  | E8755C7EF8 |
| 07d1:3c07 | D-Link ... | DWA-110 Wireless G Adapte... | 12    | rt73usb    | 62697BF35B |
| 0bda:f179 | Realtek... | 802.11n                      | 12    | rtl8188fu  | CCE7F9292D |
| 050d:845a | Belkin ... | F7D2101 802.11n Surf & Sh... | 11    | r8712u     | 1CCC5C7074 |
| 07d1:3c0d | D-Link ... | DWA-125 Wireless N 150 Ad... | 11    | rt2800usb  | 569B9B8B32 |
| 0b05:184c | ASUSTek... | RTL8812BU USB-AC53 Nano 8... | 11    | 88x2bu     | 3E165AC0A4 |
| 0bda:c811 | Realtek... | RTL8811CU 802.11ac NIC       | 11    | 8821cu     | 37460463A1 |
| 13d3:3306 | IMC Net... | Mediao 802.11n WLAN [Real... | 11    | r8712u     | 0BE5F7A9E8 |
| 148f:2070 | Ralink ... | RT2070 Wireless Adapter      | 10    | rt2800usb  | 9AD73F77F9 |
| 148f:2870 | Ralink ... | RT2870 Wireless Adapter      | 10    | rt2800usb  | 6F259EC9AA |
| 148f:3572 | Ralink ... | RT3572 Wireless Adapter      | 10    | rt2800usb  | 49697408DC |
| 0bda:0179 | Realtek... | RTL8188ETV Wireless LAN 8... | 9     | r8188eu    | CDCFCEEBFD |
| 0e8d:7610 | MediaTek   | MT7610U WiFi                 | 9     | mt7650u... | F16EC522A6 |
| 2357:0107 | Realtek    | RTL8192EU TL-WN821N Versi... | 9     | 8192eu     | 3A8D19C8FC |
| 050d:2103 | Belkin ... | F7D2102 802.11n N300 Micr... | 8     | rtl8192... | C9CCBD7C3F |
| 2001:3314 | D-Link     | RTL8821AU DWA-171 802.11n... | 8     | rtl8812au  | 10BA468B45 |
| 2001:3c1b | D-Link     | DWA-127 Wireless N 150 Hi... | 8     | rt2800usb  | 22FADF1971 |
| 2357:0101 | Realtek    | RTL8812AU Archer T4U 802.... | 8     | rtl8812au  | BF63570D7D |
| 0ace:1215 | ZyDAS      | ZD1211B 802.11g              | 7     | zd1211rw   | 9CB261390B |
| 0bda:8198 | Realtek... | RTL8187B Wireless Adapter    | 7     | rtl8187    | 46C7EAAD0A |
| 0db0:6877 | Micro S... | RT2573                       | 7     | rt73usb    | DE010A6F04 |
| 15a9:0004 | Gemtek     | WUBR-177G [Ralink RT2571W]   | 7     | rt73usb    | 3A9AB88271 |
| 2001:3317 | D-Link     | 802.11 n WLAN                | 7     | rt2800usb  | BE6D815002 |
| 413c:81a3 | Dell       | Wireless 5570 HSPA+ (42Mb... | 7     | qcserial   | C0C75EF0DF |
| 0586:341e | ZyXEL C... | NWD2105 802.11bgn Wireles... | 6     | rt2800usb  | B8931B91E5 |
| 0586:341f | ZyXEL C... | NWD2205 802.11n Wireless ... | 6     | rtl8192cu  | B79EE752B4 |
| 0846:9052 | NetGear    | RTL8811AU A6100 AC600 DB ... | 6     | rtl8812au  | AA73E69EE4 |
| 0b05:1723 | ASUSTek... | WL-167G v2 802.11g Adapte... | 6     | rt73usb    | 24F00A45BF |
| 2001:3315 | D-Link     | RTL8812AU DWA-182 Wireles... | 6     | rtl8812au  | CA162546EE |
| 2717:4106 | MediaTek   | MI WLAN Adapter              | 6     | mt7601u    | F9B65F1415 |
| 7392:7711 | Edimax ... | EW-7711UTn nLite Wireless... | 6     | rt2800usb  | CB4983BAF6 |
| 0586:3410 | ZyXEL C... | ZyAIR G-202 802.11bg         | 5     | zd1211rw   | BBCFFE1ECE |
| 079b:0062 | Sagem      | XG-76NA 802.11bg             | 5     | zd1211rw   | CD0F6202CB |
| 07d1:3c09 | D-Link ... | DWA-140 RangeBooster N Ad... | 5     | rt2800usb  | 3C2E5705F9 |
| 0846:4260 | NetGear    | WG111v3 54 Mbps Wireless ... | 5     | rtl8187    | 6BDDC45E74 |
| 0846:9020 | NetGear    | BCM43231 WNA3100(v1) Wire... | 5     |            | 68CF43B792 |
| 0b05:17e8 | ASUSTek... | USB-N14 802.11b/g/n (2x2)... | 5     | rt2800usb  | 53302E45B6 |
| 0cf3:1002 | Qualcom... | TP-Link TL-WN821N v2 / TL... | 5     | carl9170   | A8D0FA2257 |
| 0db0:3871 | Micro S... | MS-3871 802.11bgn Wireles... | 5     | rt2800usb  | 0F152D6AD7 |
| 13b1:003f | Linksys    | RTL8812AU WUSB6300 802.11... | 5     | 8812au     | FDC986FDE7 |
| 148f:760b | Ralink ... | MT7601U Wireless Adapter     | 5     | mt7601u    | 10121DE278 |
| 2357:0105 | MediaTek   | MT7610U Archer T1U 802.11... | 5     | mt76x0u    | F4F1C1053C |
| 2357:0108 | TP-Link    | RTL8192EU TL-WN822N Versi... | 5     | rtl8xxxu   | 6AD994E2BF |
| 2357:0115 | TP-Link    | 802.11ac NIC                 | 5     | 8822bu     | 54A49FCBF7 |
| 050d:705a | Belkin ... | F5D7050 Wireless G Adapte... | 4     | rt73usb    | 2BF7B65239 |
| 0846:9011 | NetGear    | BCM4323 WNDA3100v2 802.11... | 4     |            | E1F01EA189 |
| 0b05:1784 | ASUSTek... | USB-N13 802.11n Network A... | 4     | rt2800usb  | 6B863A586E |
| 0b05:17d1 | ASUSTek... | MT7610U AC51 802.11a/b/g/... | 4     |            | 48E75D806A |
| 0bf8:100f | Fujitsu... | miniCard D2301 802.11bg W... | 4     |            | FEDA3B155D |
| 13d3:3247 | IMC Net... | AW-NU222 802.11bgn Wirele... | 4     | rt2800usb  | 31559386B2 |
| 1737:0078 | Linksys    | WUSB100 v2 RangePlus Wire... | 4     | rt2800usb  | 4B7960D4AB |
| 2357:0100 | Realtek    | RTL8192CU TL-WN8200ND        | 4     | rtl8192cu  | 6FB7A2E4D4 |
| 2357:010d | Realtek    | RTL8812AU TP-Link Archer ... | 4     | 8812au     | 80EEC2D2C0 |
| 2604:0012 | Realtek    | RTL8812AU Tenda U12 802.1... | 4     | 8812au     | 1B1C811590 |
| 2c4e:0100 | Realtek    | RTL8192EU WLAN controller    | 4     | 8192eu     | AFECB4A1DB |
| 050d:815c | Belkin ... | F5D8053 N Wireless USB Ad... | 3     | rt2800usb  | B7DB1F6D08 |
| 050d:935b | Belkin ... | F6D4050 N150 Enhanced Wir... | 3     | rt2800usb  | A2DBF52E17 |
| 07d1:3a09 | D-Link ... | DWA-160 802.11abgn Xtreme... | 3     | carl9170   | 4E72D045DC |
| 0846:9021 | NetGear    | WNA3100M(v1) Wireless-N 3... | 3     | rtl8192... | 33687A527A |
| 0bda:8174 | Realtek... | RTL8192SU 802.11n WLAN Ad... | 3     | r8712u     | 633AB37A3F |

### Network (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 19d2:1405 | ZTE WCD... | ZTE Mobile Broadband Station | 87    | cdc_ether  | C0EABA1044 |
| 0bda:8153 | Realtek... | RTL8153 Gigabit Ethernet ... | 79    | r8152      | 74DD313167 |
| 12d1:14db | Huawei ... | E353/E3131 34GB              | 75    | cdc_ether  | 4C56265E1C |
| 04e8:6863 | Samsung... | GT-I9500 [Galaxy S4] / GT... | 65    | rndis_host | B6D6A0F54D |
| 0bda:8187 | Realtek... | RTL8187 Wireless LAN Adapter | 52    | rtl8187    | 29B7777E42 |
| 0bb4:0003 | HTC (Hi... | Android Incorporated GSM ... | 33    | rndis_host | 00484769BC |
| 2717:ff80 | Android    | SDM636-MTP _SN:5F93851E      | 33    | rndis_host | 4A6A073320 |
| 0bda:8152 | Realtek... | RTL8152 Fast Ethernet Ada... | 32    | r8152      | 1579402536 |
| 04e8:6864 | Samsung... | GT-I9070 (network tetheri... | 28    | rndis_host | B7561ADE6F |
| 12d1:108a | Huawei ... | DLI-TL20                     | 28    | rndis_host | 0AB5BF5B1A |
| 15a9:002d | Gemtek     | WLTUBA-107 [Yota 4G LTE]     | 27    | cdc_ether  | 3630B640F0 |
| 2001:3c15 | D-Link     | DWA-140 RangeBooster N Ad... | 27    | rt2800usb  | CA130B13F3 |
| 0e8d:2004 | MediaTek   | Power Ice Evo                | 24    | rndis_host | 86D04818BE |
| 07d1:3c0a | D-Link ... | DWA-140 RangeBooster N Ad... | 23    | rt2800usb  | 3549E0C30D |
| 0bda:b720 | Realtek... | RTL8723BU 802.11n WLAN Ad... | 22    | rtl8xxxu   | 1579402536 |
| 2001:330f | D-Link     | RTL8188ETV DWA-125 11n Ad... | 22    | r8188eu    | 969A371A99 |
| 0b95:1790 | ASIX El... | AX88179 Gigabit Ethernet     | 19    | ax88179... | F41BD5BF5B |
| 046b:ffb0 | America... | Virtual Ethernet             | 16    | cdc_ether  | 4391DFF8D2 |
| 1076:8002 | GCT Sem... | LU150 LTE Modem [Yota LU150] | 16    | rndis_host | 6999B8686F |
| 216f:0043 | Altair ... | Modem YOTA 4G LTE            | 15    | cdc_ether  | 03602DBEA6 |
| 0b95:772b | ASIX El... | AX88772B                     | 14    | asix       | 2D4AA64C10 |
| 8087:0911 | Intel      | PRODUCT_MODEM                | 14    | cdc_mbim   | 8F9E198F6E |
| 0bb4:0004 | HTC (Hi... | MT65xx Android Phone         | 13    | rndis_host | 39B777FE86 |
| 05c6:f00e | Qualcomm   | DEXP Ixion X LTE 4.5"        | 11    | rndis_host | 42BA5CAA2F |
| 0bda:1724 | Realtek... | RTL8723AU 802.11n WLAN Ad... | 11    | rtl8723au  | B19B3500F2 |
| 0424:ec00 | Standar... | SMSC9512/9514 Fast Ethern... | 10    | smsc95xx   | A2AB91716A |
| 0fe6:9700 | Kontron... | DM9601 Fast Ethernet Adapter | 10    | dm9601,... | BF2A311AD2 |
| 1bbb:0174 | T & A M... | ALCATEL ONETOUCH PIXI 3 (... | 10    | rndis_host | 69ED9F1FFC |
| 2001:3c1e | D-Link     | 11n Adapter                  | 10    | rt2800usb  | F1FF7D2409 |
| 22b8:2e24 | Motorol... | Moto G (4)                   | 10    | rndis_host | 4CA32F1015 |
| 03f0:581d | Hewlett... | lt4112 Gobi 4G Module Net... | 9     | qcserial   | AC96DD45F9 |
| 0e8d:2005 | MediaTek   | X5max_PRO                    | 9     | rndis_host | 5E682A0733 |
| 12d1:15bb | Huawei ... | ME936 LTE/HSDPA+ 4G modem    | 9     | cdc_ncm... | AE9CAC19CA |
| 1782:5d20 | Spreadt... | Fly Era Nano 3               | 9     | rndis_host | 753ED60051 |
| 17ef:7436 | Lenovo     | MT65xx Android Phone         | 9     | rndis_host | 586A6A9F8A |
| 0846:9053 | NetGear    | A6210                        | 8     | mt76x2u    | F87D092FC1 |
| 1199:a001 | Sierra ... | EM7345 4G LTE                | 8     | cdc_mbim   | DF76656467 |
| 413c:81b6 | Dell       | DW5811e Snapdragon X7 LTE    | 8     | qcserial   | B9281326D7 |
| 03f0:9d1d | Hewlett... | lt4120 Snapdragon X5 LTE     | 7     | qmi_wwan   | B8392B7335 |
| 1199:9011 | Sierra ... | MC8305                       | 7     | qcserial   | 8F2E060D39 |
| 1199:9041 | Sierra ... | EM7305                       | 7     | cdc_mbim   | 734FCAFBD7 |
| 15a9:003e | Gemtek     | Yota Many                    | 7     | rndis_host | F48E23AB6A |
| 2357:0601 | TP-Link    | RTL8153 TP-Link UE300 USB... | 7     | r8152      | C5279AB6E4 |
| 04b3:4010 | IBM        | RNDIS/Ethernet Gadget        | 6     | cdc_ether  | B55F7AE6F3 |
| 04b4:3610 | Cypress... | USB-C PD Docking             | 6     | ax88179... | BF4A9DEE07 |
| 0b05:5f04 | ASUSTek... | Android                      | 6     | rndis_host | 43E4578544 |
| 0b95:7e2b | ASIX El... | AX88772B Fast Ethernet Co... | 6     | asix       | 377E8B594A |
| 17ef:3069 | Lenovo     | ThinkPad TBT3 LAN            | 6     | r8152      | C15E0482CA |
| 2e04:c022 | MediaTek   | Android                      | 6     | rndis_host | 5CE732DF30 |
| 7392:a812 | Edimax ... | RTL8811AU AC600 USB          | 6     | rtl8812au  | 690FFF1815 |
| 0846:6a00 | NetGear    | WG111v2 54 Mbps Wireless ... | 5     | rtl8187    | 709C282E30 |
| 0b95:772a | ASIX El... | AX88772A Fast Ethernet       | 5     | asix       | 8C487BE380 |
| 0bda:0823 | Realtek... | 802.11ac WLAN Adapter        | 5     | btusb      | 7F43E2651E |
| 1004:6344 | LG Elec... | G2 Android Phone [tetheri... | 5     | rndis_host | 60ADC60B28 |
| 1199:9079 | Sierra ... | EM7455 Qualcomm Snapdrago... | 5     | qcseria... | 3AC5B5C4AD |
| 12d1:14f1 | Huawei ... | Gobi 3000 HSPA+ Modem        | 5     | qcseria... | 01A4BD5E7F |
| 1376:4e61 | Vimtron... | Mobile Composite Device Bus  | 5     | rndis_host | 61A1DE10C0 |
| 19d2:1365 | ZTE WCD... | MT65xx Android Phone         | 5     | rndis_host | AC739516CE |
| 2001:4a00 | D-Link     | DUB-1312                     | 5     | ax88179... | 0818F19E7A |
| 03f0:371d | Hewlett... | un2430 Mobile Broadband M... | 4     | qcserial   | D16CE79DB7 |
| 0424:7800 | Standar... | Ethernet controller          | 4     | lan78xx    | 66A253B82B |
| 056a:0084 | Wacom      | Wireless adapter for Bamb... | 4     | usbhid     | D6D7F9CC30 |
| 0bb4:0ffe | HTC (Hi... | Desire HD (modem mode)       | 4     | rndis_w... | C5A4767CED |
| 1271:052a | Android    | Android                      | 4     | rndis_host | 407C4DAF14 |
| 12d1:1050 | Huawei ... | Android Adapter              | 4     | rndis_host | B2185404AA |
| 17e9:4307 | Display... | USB3.0 Dual Video Dock       | 4     | cdc_ncm... | 8B7A2D2A08 |
| 1bbb:2026 | T & A M... | ALCATEL ONETOUCH PIXI 3 (... | 4     | cdc_eem    | C4D6A7BC54 |
| 2001:3c21 | D-Link     | DWA-160 Xtreme N Dual Ban... | 4     | rt2800usb  | 8418BEF88A |
| 2717:1280 | JSR Tech   | HM1 Android Phone            | 4     | rndis_host | 266E42DEC5 |
| 0489:c022 | Foxconn... | Nokia 8                      | 3     | rndis_host | 8C18BA014C |
| 0586:3309 | ZyXEL C... | ADSL Modem Prestige 600 s... | 3     | rndis_w... | 316CFC71D0 |
| 05ac:1402 | Apple      | Ethernet Adapter [A1277]     | 3     | asix       | 27D23CBDAA |
| 05c6:9205 | Qualcomm   | Gobi 2000                    | 3     | qmi_wwa... | 6F637899C4 |
| 0b05:5602 | ASUSTek... | Android                      | 3     | rndis_host | 4DD77DD778 |
| 0b95:7720 | ASIX El... | AX88772                      | 3     | asix       | CEA175B6F3 |
| 0fca:8017 | Researc... | BlackBerry                   | 3     | cdc_ncm... | C33C8BA4E4 |
| 0fce:7161 | Sony Er... | ST18i                        | 3     | rndis_host | 9DF4057415 |
| 1199:68a2 | Sierra ... | MC7710                       | 3     | qcseria... | 36D07088D1 |
| 12d1:260d | Huawei ... | TIT-L01                      | 3     | rndis_host | 1DEA266689 |
| 15a9:002b | Gemtek     | Yota Many                    | 3     | rndis_host | 94A0B982A5 |
| 17e9:436e | Display... | Dell USB3.0 Dock             | 3     | usbfs      | 0FCCED0386 |
| 18d1:4ee3 | Google     | Nexus 4/5/7/10 (tether)      | 3     | rndis_host | B80BDB1F75 |
| 19d2:1373 | ZTE WCD... | Android                      | 3     | rndis_host | 1276D33239 |
| 2001:1a02 | D-Link     | DUB-E100 Fast Ethernet Ad... | 3     | asix       | 24743A2A16 |
| 2001:3310 | D-Link     | DWA-123 11n Adapter          | 3     | r8188eu    | 180D33B399 |
| 2001:3318 | D-Link     | 11ac adapter                 | 3     | rtl8812au  | ADF45BCCC3 |
| 2970:2004 | MediaTek   | FS504                        | 3     | rndis_host | 88EC731DFB |
| 0424:7500 | Standar... | LAN7500 Ethernet 10/100/1... | 2     | smsc75xx   | 63B03B7E15 |
| 045e:07c6 | Microsoft  | RTL8153 GigE [Surface Doc... | 2     | r8152      | DBF25F43EB |
| 04e8:6881 | Samsung... | Android USB Device           | 2     | rndis_host | 6B2E5020C2 |
| 05ac:12ab | Apple      | iPad 4/Mini1                 | 2     | ipheth     | 0D7F7B5382 |
| 0a46:1269 | Davicom... | DM9621 USB To Fast Ether     | 2     | dm9601,... | 019B115510 |
| 0b05:7783 | ASUSTek... | Android                      | 2     | rndis_host | 72886E4425 |
| 0b95:1780 | ASIX El... | AX88178                      | 2     | asix       | E19770A9ED |
| 0bb4:0ee7 | HTC (Hi... | Desire 620G dual sim         | 2     | rndis_host | BA6F321C12 |
| 0bda:8150 | Realtek... | RTL8150 Fast Ethernet Ada... | 2     | rtl8150    | 9A4C5DE0DD |
| 0fca:8035 | Researc... | BlackBerry                   | 2     | cdc_ncm... | C7ECD4A0AE |
| 0fce:719b | Sony Er... | Android                      | 2     | rndis_host | 2153C318F3 |
| 0fce:71bc | Sony Er... | D2203                        | 2     | rndis_host | 7EF8DB4E5A |
| 1004:61da | LG Elec... | G2 Android Phone [tetheri... | 2     | rndis_host | 7077729E39 |

### Phone (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 18d1:4ee1 | Google     | Nexus Device (MTP)           | 10    | usbfs      | BF6F02A425 |
| 1004:631c | LG Elec... | G2/Optimus Android Phone ... | 9     | usbfs      | AC6AA4CE59 |
| 1bbb:0168 | T & A M... | ALCATEL ONETOUCH PIXI 3 (... | 9     | usbfs      | 3A50E0F27D |
| 2717:ff48 | MediaTek   | MT65xx Android Phone         | 8     | usbfs      | D6DD84E864 |
| 2a45:2008 | Meizu      | MX Phone (MTP)               | 8     | usbfs      | BCF1D99475 |
| 0bb4:0c02 | HTC (Hi... | Dream / ADP1 / G1 / Magic... | 6     | uas, us... | 1C66419356 |
| 1004:6300 | LG Elec... | G2/Optimus Android Phone ... | 5     | usbhid     | 3A3714805B |
| 0bb4:2008 | HTC (Hi... | Android Phone via MTP [Wi... | 4     |            | 98FF7EAA07 |
| 17ef:7497 | Lenovo     | A789 (MTP mode)              | 4     |            | B60CD6FFC3 |
| 05c6:f003 | Qualcomm   | vivo Android Phone           | 3     | usbfs      | 0D7F7B5382 |
| 0fce:01c4 | Sony Er... | Xperia M4                    | 3     | usbfs      | 06472F3D2C |
| 19d2:0306 | ZTE WCD... | MT65xx Android Phone         | 3     |            | 6AD005D6B7 |
| 19d2:0307 | ZTE WCD... | Android Phone                | 3     | usbfs      | 090D61FAD7 |
| 2717:1240 | Xiaomi     | HM1 Android Phone            | 3     |            | 01AA74496F |
| 2916:f003 | Yota De... | YotaPhone C9660              | 3     | usbfs      | 5595625922 |
| 045e:04ec | Microsoft  | Windows Phone (Zune)         | 2     |            | D4F8B5C1D6 |
| 0471:2008 | Philips... | Android Phone                | 2     |            | D315AFD57C |
| 04e8:685d | Samsung... | GT-I9100 Phone [Galaxy S ... | 2     | cdc_acm    | 3F7F72D7A2 |
| 05c6:9092 | Qualcomm   | DEXP Ixion X LTE 4.5"        | 2     |            | 041AA23640 |
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
| 04e8:685c | Samsung... | GT-I9250 Phone [Galaxy Ne... | 1     |            | 769DC89006 |
| 0b05:5490 | ASUSTek... | ZenFone                      | 1     |            | 196E542A2B |
| 0b05:551f | ASUSTek... | Android Phone                | 1     | usbfs      | E1C6C1D0DB |
| 0bb4:0c81 | HTC (Hi... | Android Phone                | 1     |            | DD80C13918 |
| 0bb4:0df8 | HTC (Hi... | Android Phone                | 1     |            | F4F1952C9C |
| 0bb4:0fa2 | HTC (Hi... | Android Phone                | 1     | usbfs      | 5A59F3A3B4 |
| 0fce:0197 | Sony Er... | Xperia ZR C5502              | 1     |            | 9C65E049FE |
| 0fce:5195 | Sony Er... | Xperia SP C5303              | 1     |            | 481DCFBCF9 |
| 1004:61fe | LG Elec... | Optimus Android Phone [US... | 1     | cdc_acm    | 4A83E029A5 |
| 1527:0200 | Silicon... | YAP Phone (no firmware)      | 1     |            | D857FD97FD |
| 17ef:0c02 | Lenovo     | MT65xx Android Phone         | 1     | usbfs      | B776DA24C5 |
| 17ef:79a1 | Lenovo     | MT65xx Android Phone         | 1     |            | 9271AE1167 |
| 19d2:0343 | ZTE WCD... | V985 Android Phone           | 1     |            | 4215162CA5 |
| 2922:0003 | MediaTek   | MT65xx Android Phone         | 1     | rndis_host | 897D97A18D |

### Printer (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:2b17 | Hewlett... | LaserJet 1020                | 57    | usblp      | C4C3165448 |
| 03f0:002a | Hewlett... | LaserJet P1102               | 40    | usblp      | 00FC2B5C89 |
| 03f0:4117 | Hewlett... | LaserJet 1018                | 40    | usblp      | 3E3879E6A5 |
| 04e8:341b | Samsung... | SCX-4200 series              | 33    | usblp      | 56D8AE9D24 |
| 04a9:2676 | Canon      | CAPT Device                  | 29    | usblp      | A9ED28807E |
| 03f0:0c17 | Hewlett... | LaserJet 1010                | 24    | usblp      | 645B5E5FF4 |
| 04b8:002a | Seiko E... | USB2.0 Printer (Hi-speed)    | 24    | usblp      | FE2AB22987 |
| 04e8:344f | Samsung... | SCX-3400 Series              | 24    | usblp      | 3D5822E22A |
| 04da:0f0b | Panason... | KX-MB1520RU                  | 21    | usblp      | A606FF5D08 |
| 04a9:2737 | Canon      | MF4410                       | 20    | usblp      | DC34CF7D36 |
| 067b:2305 | Prolifi... | PL2305 Parallel Port         | 20    | usblp      | E969E52D33 |
| 04a9:2759 | Canon      | MF3010                       | 19    | usblp      | 2DE6892C13 |
| 04b8:08a1 | Seiko E... | L210 Series                  | 18    | usblp      | EED3020AA4 |
| 04e8:3441 | Samsung... | SCX-3200 Series              | 18    | usblp      | 07F6824787 |
| 04f9:0027 | Brother... | HL-2030 Laser Printer        | 18    | usblp      | 98A829DCFD |
| 03f0:3d17 | Hewlett... | LaserJet P1005               | 17    | usblp      | 0ADA104D17 |
| 04e8:3469 | Samsung... | M2070 Series                 | 17    | usblp      | 23DAC0F1B6 |
| 04b8:0005 | Seiko E... | Printer                      | 16    | usblp      | B174073C45 |
| 04b8:0007 | Seiko E... | Printer                      | 16    | usblp      | DB1A79AC69 |
| 04e8:3292 | Samsung... | ML-1640 Series Laser Printer | 16    | usblp      | 3759770E23 |
| 04e8:3321 | Samsung... | M2020 Series                 | 15    | usblp      | 3751892E56 |
| 03f0:0317 | Hewlett... | LaserJet 1200                | 14    | usblp      | B3E8FFCC97 |
| 03f0:8711 | Hewlett... | Deskjet 2050 J510            | 13    | usblp      | F3C86A9592 |
| 04a9:10dc | Canon      | iP7200 series                | 13    | usblp      | AD610739B6 |
| 04a9:262b | Canon      | LaserShot LBP-1120 Printer   | 12    | usblp      | D425CA175B |
| 04a9:173a | Canon      | PIXMA MP250 series printer   | 11    | usblp      | 915FD7548F |
| 04a9:176c | Canon      | MG2400 series                | 11    | usblp      | 9DD0EDCEF8 |
| 04a9:26da | Canon      | LBP3010B printer             | 11    | usblp      | 456F676592 |
| 04a9:2771 | Canon      | CAPT USB Device              | 11    | usblp      | F12E05AEE4 |
| 04a9:260a | Canon      | CAPT Printer                 | 10    | usblp      | 98686D396A |
| 04a9:271a | Canon      | CAPT USB Device              | 10    | usblp      | 7DEA09C3AC |
| 04e8:300c | Samsung... | ML-1210 Printer              | 10    | usblp      | 9E9C06CB6F |
| 04e8:3413 | Samsung... | SCX-4100 Scanner             | 10    | usblp      | 9A87AA9B0D |
| 03f0:0517 | Hewlett... | LaserJet 1000                | 9     | usblp      | 3AF8833313 |
| 03f0:1d17 | Hewlett... | LaserJet 1320                | 9     | usblp      | 308392F74D |
| 03f0:2504 | Hewlett... | DeskJet F4200 series         | 9     | usblp      | 28DFB478B7 |
| 04a9:176d | Canon      | PIXMA MG2500 Series          | 9     | usblp      | 1EA43A3881 |
| 04a9:2684 | Canon      | MF3200 series                | 9     | usblp      | 5149320E81 |
| 04a9:26b4 | Canon      | MF4010 series                | 9     | usblp      | B98B8362E0 |
| 04f9:003f | Brother... | HL-2130 series               | 9     | usblp      | 5C2A8BB899 |
| 04f9:0054 | Brother... | HL-1110 series               | 9     | usblp      | A83B92D6B0 |
| 0924:3cf4 | Xerox      | Phaser 3140 and 3155         | 9     | usblp      | A15E1952DA |
| 1a86:7584 | QinHeng... | CH340S                       | 9     | usblp      | A4F1D5BD20 |
| 03f0:032a | Hewlett... | LaserJet Professional P1102w | 8     | usblp      | 9BF556CA2F |
| 03f0:1017 | Hewlett... | LaserJet 1300                | 8     | usblp      | FD6FD654DB |
| 03f0:2c17 | Hewlett... | LaserJet 1022                | 8     | usblp      | 9E845B6F0F |
| 03f0:3e17 | Hewlett... | LaserJet P1006               | 8     | usblp      | BEBC187DBD |
| 03f0:7611 | Hewlett... | DeskJet F2492 All-in-One     | 8     | usblp      | 7F0F347502 |
| 03f0:7e04 | Hewlett... | DeskJet F4100 Printer series | 8     | usblp      | 413AE4FF4F |
| 03f0:e111 | Hewlett... | DeskJet 2130 series          | 8     | usblp      | 5AEB4ABFE6 |
| 04e8:326c | Samsung... | ML-2010P Mono Laser Printer  | 8     | usblp      | B63EF41E02 |
| 04f9:0273 | Brother... | DCP-7057 scanner/printer     | 8     | usblp      | 79E8256BFB |
| 0924:3cf7 | Xerox      | WorkCentre 3315              | 8     | usblp      | 839442574A |
| 03f0:d711 | Hewlett... | ENVY 4520 series             | 7     | usblp      | 8FFAA505B6 |
| 04a9:10d3 | Canon      | iP2700 series                | 7     | usblp      | 835B504D5C |
| 04a9:271c | Canon      | CAPT USB Device              | 7     | usblp      | 3602A90378 |
| 04b8:004c | Seiko E... | L110 Series                  | 7     | usblp      | DE463D111A |
| 04b8:0883 | Seiko E... | ME 340 Series/Stylus NX13... | 7     | usblp      | 7C707CF755 |
| 04b8:08a8 | Seiko E... | L355 Series                  | 7     | usblp      | 86314575F7 |
| 04e8:342e | Samsung... | SCX-4300 Series              | 7     | usblp      | 3719375A02 |
| 03f0:3817 | Hewlett... | LaserJet P2015 series        | 6     | usblp      | 93F413D666 |
| 03f0:8911 | Hewlett... | Deskjet 1050 J410 series     | 6     | usblp      | 542C9CBC52 |
| 03f0:c111 | Hewlett... | Deskjet 1510                 | 6     | usblp      | B3C05679A9 |
| 04a9:175f | Canon      | PIXMA MP230 series           | 6     | usblp      | EEEE376F38 |
| 04b8:08d1 | Seiko E... | L222 Series                  | 6     | usblp      | 964D7E69EB |
| 04e8:3301 | Samsung... | ML-1660 Series               | 6     | usblp      | 66E92FA977 |
| 04e8:330c | Samsung... | ML-1865                      | 6     | usblp      | D4EC4EAE87 |
| 04e8:330f | Samsung... | ML-216x Series Laser Printer | 6     | usblp      | 5D1E770980 |
| 05ca:042c | Ricoh      | Aficio SP 100SU              | 6     | usblp      | 1D3FD80F42 |
| 03f0:0b2a | Hewlett... | LaserJet CP1025nw            | 5     | usblp      | 4DA2F6A4AC |
| 03f0:1204 | Hewlett... | DeskJet 930c                 | 5     | usblp      | 435E64F300 |
| 03f0:2d12 | Hewlett... | Officejet 4500 G510g-m       | 5     | usblp      | 9DCEE0A57A |
| 03f0:5c17 | Hewlett... | LaserJet P2055 series        | 5     | usblp      | 79918271CA |
| 03f0:7d04 | Hewlett... | DeskJet F2100 Printer series | 5     | usblp      | 72FFD05528 |
| 04a9:10d8 | Canon      | iP4900 series                | 5     | usblp      | 39B777FE86 |
| 04a9:1746 | Canon      | PIXMA MP280 series           | 5     | usblp      | F1235A8C4C |
| 04b8:001b | Seiko E... | L100 Series                  | 5     | usblp      | 47C52F3C00 |
| 04b8:08d2 | Seiko E... | L366 Series                  | 5     | usblp      | 1A6999BBB2 |
| 04e8:325b | Samsung... | Xerox Phaser 3117 Laser P... | 5     | usblp      | 4068C43059 |
| 04e8:3268 | Samsung... | ML-1610 Mono Laser Printer   | 5     | usblp      | 9D3DBD169B |
| 04f9:02d0 | Brother... | DCP-1510                     | 5     | usblp      | 7BB0831B07 |
| 05ca:042b | Ricoh      | Aficio SP 100                | 5     | usblp      | 268D53A8B4 |
| 0924:4265 | Xerox      | WorkCentre 3119 Series       | 5     | usblp      | 8A288D2FFC |
| 03f0:092a | Hewlett... | LaserJet Professional P1566  | 4     | usblp      | 396BE2A324 |
| 03f0:0d17 | Hewlett... | LaserJet 1012                | 4     | usblp      | 3A1C2004B1 |
| 03f0:3217 | Hewlett... | LaserJet 3050                | 4     | usblp      | 0DCBF3F2DE |
| 03f0:5511 | Hewlett... | DeskJet F300 series          | 4     | usblp      | 0BB045504D |
| 03f0:6004 | Hewlett... | DeskJet 5550                 | 4     | usblp      | 21317BB405 |
| 03f0:6204 | Hewlett... | DeskJet 5150c                | 4     | usblp      | BA27520038 |
| 03f0:7804 | Hewlett... | DeskJet D1360                | 4     | usblp      | 9BB2C9E5C9 |
| 03f0:b011 | Hewlett... | Deskjet 3520 series          | 4     | usblp      | 112BAE6923 |
| 03f0:b911 | Hewlett... | Deskjet 2020 series          | 4     | usblp      | E839F7C3F6 |
| 0482:0496 | Kyocera    | FS-1120MFP                   | 4     | usblp      | 29D7B8D97C |
| 04a9:10c2 | Canon      | PIXMA iP1800 Printer         | 4     | usblp      | AEB1774345 |
| 04a9:10cd | Canon      | iP1900 series                | 4     | usblp      | 441F34B6A5 |
| 04a9:1714 | Canon      | MP160                        | 4     | usblp      | 82C0242C80 |
| 04a9:176b | Canon      | PIXMA MX920 Series           | 4     | usblp      | 22CB9D3AF2 |
| 04a9:176e | Canon      | PIXMA MG3500 Series          | 4     | usblp      | E75F4538BC |
| 04a9:1780 | Canon      | PIXMA MG2900 Series          | 4     | usblp      | 949EC692A8 |
| 04a9:1796 | Canon      | G1000 series                 | 4     | usblp      | 2DE6892C13 |

### Scanner (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04a9:2220 | Canon      | CanoScan LIDE 25             | 32    | usbfs      | A83B92D6B0 |
| 04a9:1909 | Canon      | CanoScan LiDE 110            | 27    |            | 47C94E2F61 |
| 04a9:220d | Canon      | CanoScan N670U/N676U/LiDE 20 | 25    |            | 39F18E2183 |
| 03f0:0a01 | Hewlett... | ScanJet 2400c                | 21    | usbfs      | 24EA81BF4C |
| 04a9:190a | Canon      | CanoScan LiDE 210            | 16    |            | AD610739B6 |
| 04b8:0142 | Seiko E... | GT-F730 [GT-S630/Perfecti... | 16    |            | 1CC81789AC |
| 05d8:4002 | Ultima ... | Artec Ultima 2000 (GT6801... | 16    |            | 9B11B923A2 |
| 04b8:0121 | Seiko E... | GT-F500/GT-F550 [Perfecti... | 15    |            | FF3AABBF0B |
| 04a9:190e | Canon      | CanoScan LiDE 120            | 12    | usbfs      | 3A1BF1D002 |
| 04b8:0120 | Seiko E... | GT-7400U [Perfection 1270]   | 11    |            | 645B5E5FF4 |
| 04a9:190f | Canon      | CanoScan LiDE 220            | 10    | usbfs      | 649FF143AD |
| 04a9:221c | Canon      | CanoScan LiDE 60             | 10    |            | CA59692108 |
| 04b8:012d | Seiko E... | GT-F650 [GT-S600/Perfecti... | 10    |            | B0B570F44B |
| 04a9:1904 | Canon      | CanoScan LiDE 100            | 8     |            | 44001EFF10 |
| 04b8:0122 | Seiko E... | GT-F520/GT-F570 [Perfecti... | 8     |            | 8712B6DE43 |
| 04b8:011f | Seiko E... | GT-8400UF [Perfection 167... | 7     |            | 3E4401FECF |
| 04b8:012e | Seiko E... | GT-F670 [Perfection V200 ... | 7     |            | CA5588BC3D |
| 055f:021b | Mustek ... | BearPaw 1200 CU Plus         | 7     |            | AEEF8EB693 |
| 055f:021d | Mustek ... | BearPaw 2400 CU Plus         | 7     |            | EE0CF0EF40 |
| 04a9:2213 | Canon      | CanoScan LiDE 50/LiDE 35/... | 5     |            | 0D8839C5FC |
| 04b8:010f | Seiko E... | GT-7200U [Perfection 1250... | 5     |            | 936BEEBE68 |
| 04b8:013a | Seiko E... | GT-X820 [Perfection V600 ... | 5     |            | 461345008C |
| 055f:021c | Mustek ... | BearPaw 1200 CU Plus         | 5     | usbfs      | A3F8EC2423 |
| 055f:021f | Mustek ... | SNAPSCAN e22                 | 5     |            | 07BA810409 |
| 03f0:1c05 | Hewlett... | Scanjet 200                  | 4     |            | AE0972B81D |
| 04a5:2311 | Acer Pe... | Benq 5560                    | 4     |            | 25B7198C11 |
| 04a9:1907 | Canon      | CanoScan LiDE 700F           | 4     | usbfs      | 9BF556CA2F |
| 04a9:220e | Canon      | CanoScan N1240U/LiDE 30      | 4     |            | 91544C4D3A |
| 04a9:2225 | Canon      | CanoScan LiDE 70             | 4     |            | 1EA13B6B1B |
| 04b8:0114 | Seiko E... | Perfection 660               | 4     |            | A26B3126F3 |
| 04b8:012a | Seiko E... | GT-X800 [Perfection 4990 ... | 4     |            | 707B18AA4C |
| 055f:021a | Mustek ... | BearPaw 2448 TA Plus         | 4     |            | 6BB9573F31 |
| 03f0:1705 | Hewlett... | ScanJet 5590                 | 3     |            | 297E534CF0 |
| 03f0:1d05 | Hewlett... | Scanjet 300                  | 3     |            | DEAB0E9DCE |
| 03f0:2205 | Hewlett... | ScanJet 3500c                | 3     |            | 126B5ADE99 |
| 03f0:2305 | Hewlett... | ScanJet 3970c                | 3     |            | E3ADCE0E5E |
| 03f0:2605 | Hewlett... | ScanJet 3800c                | 3     |            | 8B640C33D5 |
| 03f0:4205 | Hewlett... | ScanJet G3010                | 3     |            | A9E90B12DC |
| 04a5:20b0 | Acer Pe... | S2W 3300U/4300U              | 3     |            | FDA7FBDBEF |
| 04a5:2137 | Acer Pe... | Benq 5150/5250               | 3     |            | 2D25B17958 |
| 04a9:1900 | Canon      | CanoScan LiDE 90             | 3     |            | 82126F997F |
| 04a9:1908 | Canon      | CanoScan                     | 3     | usbfs      | 75193022D0 |
| 04a9:2224 | Canon      | CanoScan LiDE 600F           | 3     |            | D326506C35 |
| 04a9:2228 | Canon      | CanoScan 4400F               | 3     |            | FE2AB22987 |
| 04b8:0119 | Seiko E... | GT-X750 [Perfection 4490 ... | 3     |            | 5324E8F5B3 |
| 04b8:013b | Seiko E... | Scanner                      | 3     |            | DD8AABC952 |
| 055f:0219 | Mustek ... | BearPaw 2400 TA Plus         | 3     |            | 49BA2B0298 |
| 055f:0408 | Mustek ... | BearPaw 2448 CU Pro          | 3     |            | DD43D2EAFE |
| 03f0:0205 | Hewlett... | ScanJet 3300c                | 2     |            | 435E64F300 |
| 03f0:0405 | Hewlett... | ScanJet 3400cse              | 2     | usbfs      | 856D5A57FF |
| 03f0:0601 | Hewlett... | ScanJet 6300c                | 2     |            | 2047255023 |
| 03f0:0605 | Hewlett... | ScanJet 2200c                | 2     |            | 0E4B7C3629 |
| 03f0:0805 | Hewlett... | HP4470C                      | 2     |            | A014C216F3 |
| 03f0:1405 | Hewlett... | ScanJet 3670                 | 2     |            | 783D86F34C |
| 03f0:2005 | Hewlett... | ScanJet 3570c                | 2     |            | 9C696B9A08 |
| 03f0:2505 | Hewlett... | ScanJet 3770                 | 2     |            | 33F8716B48 |
| 03f0:2f11 | Hewlett... | PSC 1200                     | 2     | usblp      | FEE0937E4F |
| 03f0:4305 | Hewlett... | ScanJet G3110                | 2     |            | 3F1B997D89 |
| 03f0:4605 | Hewlett... | ScanJet G4050                | 2     |            | 665166F420 |
| 0458:2014 | KYE Sys... | ColorPage-Vivid4             | 2     |            | DD360E1D5E |
| 0458:201f | KYE Sys... | ColorPage-Vivid 1200 XE      | 2     |            | C676410AA7 |
| 04a5:20f8 | Acer Pe... | Benq 5000                    | 2     |            | 7952379ACC |
| 04a5:2211 | Acer Pe... | Color FlatbedScanner39       | 2     |            | E507592DE8 |
| 04a5:2331 | Acer Pe... | FlatbedScanner 50            | 2     |            | 0B356FFA8A |
| 04a9:221b | Canon      | CanoScan 4200F               | 2     |            | AFE7557041 |
| 04b8:011b | Seiko E... | GT-9300UF [Perfection 240... | 2     |            | A3F682ED16 |
| 04b8:011c | Seiko E... | GT-9800F [Perfection 3200]   | 2     |            | 86869022FA |
| 04b8:012f | Seiko E... | GT-F700 [Perfection V350]    | 2     |            | F6CDB72510 |
| 04b8:0131 | Seiko E... | GT-F720 [GT-S620/Perfecti... | 2     |            | 99582A958F |
| 01ef:0004 | Hewlett... | Scanjet                      | 1     |            | 3EB97E6189 |
| 03f0:0305 | Hewlett... | ScanJet 4300c                | 1     | usbfs      | 6BAA62B5E0 |
| 03f0:0705 | Hewlett... | ScanJet 4400c                | 1     |            | 1789404C97 |
| 03f0:0b01 | Hewlett... | ScanJet 82x0C                | 1     |            | 2265248DBB |
| 03f0:1205 | Hewlett... | ScanJet 4500C/5550C          | 1     |            | B7C0950BF9 |
| 03f0:1b05 | Hewlett... | ScanJet 4850C/4890C          | 1     | usbfs      | E4F578F490 |
| 03f0:2805 | Hewlett... | ScanJet G2710                | 1     |            | 4B3FF97AD5 |
| 03f0:2811 | Hewlett... | PSC-2100                     | 1     | usbfs      | 390C380926 |
| 03f0:2a05 | Hewlett... | Scanjet N6010                | 1     |            | F855FA062D |
| 03f0:4505 | Hewlett... | ScanJet G4010                | 1     |            | 92D4F82EF9 |
| 0458:2013 | KYE Sys... | ColorPage-HR7 Scanner        | 1     |            | 6A6DA1FE6F |
| 0458:201a | KYE Sys... | ColorPage-Vivid4xe           | 1     |            | 7731F20599 |
| 04a5:211b | Acer Pe... | FlatbedScanner 22            | 1     |            | 0A23FD59F0 |
| 04a7:0477 | Visioneer  | DocuMate 152                 | 1     |            | DE18CDDB21 |
| 04a9:1905 | Canon      | CanoScan LiDE 200            | 1     |            | 3D5D3F552C |
| 04a9:1906 | Canon      | CanoScan 5600F               | 1     |            | D14CE30BB6 |
| 04a9:190d | Canon      | CanoScan 9000F Mark II       | 1     |            | C268560077 |
| 04a9:2204 | Canon      | CanoScan FB630U              | 1     |            | 700FBE7F0A |
| 04a9:221f | Canon      | CanoScan LiDE 500F           | 1     |            | 68FA7AD805 |
| 04b8:0109 | Seiko E... | ES-8500 [Expression 1640 XL] | 1     |            | 52B7E8AF1A |
| 04b8:010b | Seiko E... | GT-7700U [Perfection 1240U]  | 1     |            | F83C6E1394 |
| 04b8:0118 | Seiko E... | GT-F600 [Perfection 4180]    | 1     | usbfs      | 5E6A0B8AE4 |
| 04b8:011d | Seiko E... | GT-7300U [Perfection 1260... | 1     |            | F7C50F2E53 |
| 04b8:011e | Seiko E... | GT-8300UF [Perfection 166... | 1     |            | F702714A09 |
| 04b8:0126 | Seiko E... | ES-7000H [GT-15000]          | 1     |            | F6CC7FBA3A |
| 04b8:0802 | Seiko E... | CC-570L [Stylus CX3100/CX... | 1     | usblp      | 44AA7D667E |
| 04b8:0807 | Seiko E... | Stylus Photo RX500/510       | 1     | usblp      | E8737C8AC8 |
| 04c5:1041 | Fujitsu    | fi-4120c Scanner             | 1     |            | 7593BA7D90 |
| 04c5:128e | Fujitsu    | ScanSnap SV600               | 1     | usbfs      | 4D480C550E |
| 055f:0001 | Mustek ... | ScanExpress 1200 CU          | 1     |            | D40E62887C |
| 055f:0006 | Mustek ... | ScanExpress 1200 UB          | 1     |            | 0FA01E4D66 |

### Serial controller (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 067b:2303 | Prolifi... | PL2303 Serial Port           | 50    | pl2303     | 87DAB1466B |
| 1a86:7523 | QinHeng... | HL-340 USB-Serial adapter    | 46    | ch341      | 517CAD6069 |
| 0403:6001 | Future ... | FT232 USB-Serial (UART) IC   | 44    | ftdi_sio   | 68ECFC5409 |
| 10c4:ea60 | Cygnal ... | CP2102/CP2109 UART Bridge... | 23    | cp210x     | 3D0DACB49E |
| 19d2:0016 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 22    | option     | A44CE70FF7 |
| 05c6:9204 | Qualcomm   | Qualcomm Gobi 2000           | 19    | qcserial   | 14BF9C4413 |
| 03f0:241d | Hewlett... | Gobi 2000 Wireless Modem ... | 16    | qcserial   | AB17752168 |
| 19d2:2003 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 11    | option     | 1476158702 |
| 1199:9013 | Sierra ... | Sierra Wireless Gobi 3000... | 10    | qcserial   | 6D5F1234C2 |
| 0d9f:0002 | Powercom   | Black Knight PRO / WOW Un... | 9     | cypress... | D4B6A04B2C |
| 03f0:521d | Hewlett... | hs3110 HSPA+ Mobile Broad... | 6     | cdc_mbim   | BD22949D99 |
| 0403:6010 | Future ... | FT2232C/D/H Dual USB-UART... | 5     | ftdi_sio   | 31EC690BE3 |
| 05c6:9224 | Qualcomm   | Sony Gobi 2000 Wireless M... | 5     | qcserial   | 94C60C4371 |
| 0fcf:1009 | Dynastr... | ANTUSB-m Stick               | 5     | usb_ser... | E45C3CB530 |
| 1199:9000 | Sierra ... | Gobi 2000 Wireless Modem ... | 5     | qcserial   | A6CA528D43 |
| 413c:8185 | Dell       | Gobi 2000 Wireless Modem ... | 5     | qcserial   | C81404F4CA |
| 04b4:5500 | Cypress... | HID->COM RS232 Adapter       | 4     | cypress... | E0F7798547 |
| 05c6:9008 | Qualcomm   | Gobi Wireless Modem (QDL ... | 4     | qcserial   | 985F45DA27 |
| 0af0:6901 | Option     | Globetrotter HSDPA Modem     | 4     | option     | 46B096153A |
| 1bbb:022c | T & A M... | HSPA+ USB Modem              | 4     | usbseri... | A348E53594 |
| 0403:1234 | Future ... | IronLogic RFID Adapter [Z... | 3     | ftdi_sio   | 876DB8C948 |
| 0451:3410 | Texas I... | TUSB3410 Microcontroller     | 3     | ti_usb_... | 02795B4E4A |
| 1199:683c | Sierra ... | Mobile Broadband 3G/UMTS ... | 3     | sierra     | BA912D76A5 |
| 1b1c:1c00 | Corsair    | Controller for Corsair Link  | 3     | cp210x     | 24D4B49329 |
| 03f0:1e1d | Hewlett... | hs2300 HSDPA Broadband Wi... | 2     | sierra     | 31732E50F6 |
| 03f0:201d | Hewlett... | un2400 Gobi Wireless Mode... | 2     | qcserial   | 0DB5880016 |
| 04da:250c | Panason... | Gobi Wireless Modem (QDL ... | 2     | qcserial   | FDCC1DFB81 |
| 0557:2008 | ATEN In... | UC-232A Serial Port [pl2303] | 2     | pl2303     | 0F9AA13B55 |
| 091e:0003 | Garmin ... | GPS (various models)         | 2     | garmin_gps | 037CAC7A3D |
| 114f:68a2 | Wavecom    | MC7750                       | 2     | qcserial   | 3479D8614B |
| 12d1:15c1 | Huawei ... | ME906s LTE M.2 Module        | 2     | option     | 8F87769D12 |
| 19d2:0117 | ZTE WCD... | WCDMA Technologies MSM       | 2     | option     | 3BEF273525 |
| 1bbb:00b7 | T & A M... | HSPA Data Card               | 2     | option     | E6C9D1B45A |
| 6547:0232 | Arkmicr... | ARK3116 Serial               | 2     | ark3116    | 0FA01E4D66 |
| 03f0:1016 | Hewlett... | Jornada 548 / iPAQ HW6515... | 1     | ipaq       | 4FA0B1AA66 |
| 03f0:a31d | Hewlett... | lt4132 LTE/HSPA+ 4G Module   | 1     | cdc_mbim   | 7F01433E42 |
| 0403:6014 | Future ... | FT232H Single HS USB-UART... | 1     | ftdi_sio   | F1331B62E6 |
| 045e:00ce | Microsoft  | SiRF GPS HH                  | 1     | ipaq       | A587AAD1F9 |
| 057c:6201 | AVM        | AVM Fritz!WLAN v1.1 [Texa... | 1     | option     | 96A1EAB120 |
| 05c6:9221 | Qualcomm   | Gobi Wireless Modem (QDL ... | 1     | qcserial   | F46BDC061A |
| 06cd:0121 | Keyspan    | USA-19hs serial adapter      | 1     | keyspan    | FB2C692CC5 |
| 0711:0230 | Magic C... | MCT-232 Serial Port          | 1     | mct_u232   | D4B46091B4 |
| 0856:ac19 | B&B Ele... | Model USOPTL4DR              | 1     | ftdi_sio   | 077842DAC4 |
| 0bf8:1001 | Fujitsu... | Fujitsu Pocket Loox 600 PDA  | 1     | ipaq       | 224FD9231B |
| 0f3d:68aa | Airprim... | AirCard 313U                 | 1     | sierra     | DB976F7ED5 |
| 0fcf:1008 | Dynastr... | ANTUSB2 Stick                | 1     | usb_ser... | 8D11089A12 |
| 1199:0020 | Sierra ... | MC5725 Modem                 | 1     | sierra     | D2C42C6C14 |
| 1199:0218 | Sierra ... | MC5720 Wireless Modem        | 1     | sierra     | F7A90892DC |
| 1199:6812 | Sierra ... | MC8775 Device                | 1     | sierra     | 527DEFC159 |
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
| 2341:4660 | Arduino SA | USB-RS485                    | 1     | usbseri... | 58340DB405 |
| 413c:8116 | Dell       | Wireless 5505 Mobile Broa... | 1     | option     | 6296C79EF5 |
| 413c:8138 | Dell       | Wireless 5520 Voda I Mobi... | 1     | option     | F88C2A43B9 |
| 9710:7840 | MosChip... | MCS7820/MCS7840 2/4 port ... | 1     | mos7840    | A4BB27D2B7 |

### Sound (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0d8c:013c | C-Media... | CM108 Audio Controller       | 81    | snd_usb... | 87DAB1466B |
| 0d8c:000c | C-Media... | Audio Adapter                | 34    | snd_usb... | 1B78CC518F |
| 1b3f:2008 | General... | USB Audio Device             | 28    | snd_usb... | 21C6ED28C9 |
| 0d8c:0014 | C-Media... | Audio Adapter (Unitek Y-2... | 26    | snd_usb... | EDE121860B |
| 0d8c:0201 | C-Media... | CM6501                       | 26    | snd_usb... | C92DC5D0CF |
| 1130:1620 | Tenx Te... | USB AUDIO                    | 23    | snd_usb... | D6D2A25AA4 |
| 08bb:2902 | Texas I... | PCM2902 Audio Codec          | 20    | snd_usb... | EB0CDD472F |
| 041e:30df | Creativ... | SB X-Fi Surround 5.1 Pro     | 18    | snd_usb... | AE7C45607A |
| 0d8c:0012 | C-Media... | USB Audio Device             | 18    | snd_usb... | 89119460C8 |
| 0d8c:0102 | C-Media... | CM106 Like Sound Device      | 18    | snd_usb... | B86DF74030 |
| 046d:0a44 | Logitech   | Wired headset H390           | 17    | snd_usb... | 6BDDC45E74 |
| 0bda:4014 | Realtek... | USB Audio                    | 16    | snd_usb... | 5D2CB1E1B0 |
| 0d8c:0103 | C-Media... | CM102-A+/102S+ Audio Cont... | 16    | snd_usb... | CC9A8D1703 |
| 8086:0808 | Intel      | USB PnP Sound Device         | 16    | snd_usb... | EDC325267B |
| 045e:070f | Microsoft  | LifeChat LX-3000 Headset     | 14    | snd_usb... | B3B453B4DC |
| 046d:0a29 | Logitech   | H600 [Wireless Headset]      | 14    | snd_usb... | E1610DFA98 |
| 093a:2625 | Pixart ... | Multimedia audio controller  | 12    | gspca_p... | 32D6CC8A86 |
| 046d:0a1f | Logitech   | G930                         | 11    | snd_usb... | 518A8709C7 |
| 0d8c:0126 | C-Media... | USB Audio Device             | 11    | snd_usb... | 87AFEF045F |
| 046d:0a4d | Logitech   | G430 Surround Sound Gamin... | 10    | snd_usb... | BF6F02A425 |
| 08bb:2704 | Texas I... | PCM2704 16-bit stereo aud... | 10    | snd_usb... | 50919B2DDB |
| 041e:30d3 | Creativ... | Sound Blaster Play!          | 9     | snd_usb... | E6D790C032 |
| 046d:0a37 | Logitech   | USB Headset H540             | 9     | snd_usb... | D6FE9DA999 |
| 0556:0001 | Asahi K... | AK5370 I/F A/D Converter     | 9     | snd_usb... | B45F44A0F7 |
| 09da:2701 | A4Tech     | Bloody Gaming Audio Device   | 9     | snd_usb... | C572988845 |
| 24ae:6000 | Rapoo      | Wireless Audio               | 9     | snd_usb... | 5AEB4ABFE6 |
| 08bb:2904 | Texas I... | PCM2904 Audio Codec          | 8     | snd_usb... | 046006226D |
| 08bb:2912 | Texas I... | PCM2912A Audio Codec         | 8     | snd_usb... | BF4A9DEE07 |
| 0c76:160c | JMTek      | USB Speaker                  | 8     | snd_usb... | 0BD7D9FCEA |
| 0c76:161f | JMTek      | USB PnP Audio Device         | 8     | snd_usb... | 57C89FEBD9 |
| 046d:0a38 | Logitech   | Headset H340                 | 7     | snd_usb... | 6966FF65AA |
| 047f:c010 | Plantro... | GameCom 780                  | 7     | snd_usb... | CD59CC78C0 |
| 413c:a503 | Dell       | AC511 USB SoundBar           | 7     | snd_usb... | 02B9759D77 |
| b58e:9e84 | Blue Mi... | Yeti Stereo Microphone       | 7     | snd_usb... | 8B7204FCBA |
| 041e:3040 | Creativ... | SoundBlaster Live! 24-bit... | 6     | snd_usb... | CBC1CB5648 |
| 046d:0a0c | Logitech   | Clear Chat Comfort USB He... | 6     | snd_usb... | 2FAE8819F7 |
| 046d:0a45 | Logitech   | USB Headset                  | 6     | snd_usb... | 0438613602 |
| 046d:0a5b | Logitech   | G933 Wireless Headset Dongle | 6     | snd_usb... | CC9738C393 |
| 047f:c012 | Plantro... | .Audio 628 USB               | 6     | snd_usb... | 48CAEFF57F |
| 0d8c:0001 | C-Media... | Audio Device                 | 6     | snd_usb... | 97BEC56798 |
| 0d8c:0008 | C-Media... | USB Audio Device             | 6     | snd_usb... | A4FB239111 |
| 1210:000a | DigiTech   | Lexicon Alpha                | 6     | snd_usb... | BD2B6260C9 |
| 1532:0504 | Razer USA  | Razer Kraken 7.1 Chroma      | 6     | snd_usb... | F5EAFE71C9 |
| 17ef:306a | Lenovo     | ThinkPad Thunderbolt 3 Do... | 6     | snd_usb... | C15E0482CA |
| 1852:7022 | GYROCOM... | Grant Fidelity dac-11        | 6     | snd_usb... | 23DC7C0455 |
| 18c3:6255 | Elite S... | USB Audio Device             | 6     | snd_usb... | 18D97C7049 |
| 041e:30dd | Creativ... | Sound Blaster X-Fi Go! Pro   | 5     | snd_usb... | D51FB90D46 |
| 0c76:1617 | JMTek      | USB PnP Audio Device         | 5     | snd_usb... | 66C270EC8B |
| 0d8c:0005 | C-Media... | Blue Snowball                | 5     | snd_usb... | 09CC6BAB56 |
| 1532:000e | Razer USA  | Razer Megalodon              | 5     | snd_usb... | E55D921BE1 |
| 6993:b700 | Yealink... | VOIP USB Phone               | 5     | snd_usb... | 60738639D1 |
| 041e:30d7 | Creativ... | USB Sound Blaster HD         | 4     | snd_usb... | 3108FE53D3 |
| 041e:3232 | Creativ... | Sound Blaster Premium HD ... | 4     | snd_usb... | 72FFD05528 |
| 041e:3237 | Creativ... | SB X-Fi Surround 5.1 Pro     | 4     | snd_usb... | BB7DA81BB1 |
| 041e:324d | Creativ... | Sound Blaster Play! 3        | 4     | snd_usb... | 331420F489 |
| 046d:0a01 | Logitech   | USB Headset                  | 4     | snd_usb... | C1C5F4E6DB |
| 046d:0a10 | Logitech   | Speaker                      | 4     | snd_usb... | 195649904F |
| 046d:0a15 | Logitech   | G35 Headset                  | 4     | snd_usb... | A85443A8BB |
| 054c:09cc | Sony       | DualShock 4 [CUH-ZCT2x]      | 4     | snd_usb... | ADA2BD30FA |
| 05fc:0231 | Harman     | JBL Pebbles                  | 4     | snd_usb... | 21C033AABC |
| 0c76:1607 | JMTek      | audio controller             | 4     | snd_usb... | 1DD80D33E5 |
| 0d8c:0139 | C-Media... | Multimedia Headset [Gigaw... | 4     | snd_usb... | D1E49BE03D |
| 12ba:0034 | License... | Wireless Stereo Headset      | 4     | snd_usb... | E9220838E0 |
| 1395:0025 | Sennhei... | Headset [PC 8]               | 4     | snd_usb... | 86E09EF939 |
| 046d:08c1 | Logitech   | QuickCam Fusion              | 3     | snd_usb... | 004C278780 |
| 046d:0a14 | Logitech   | USB Headset                  | 3     | snd_usb... | 0BB045504D |
| 046d:0a66 | Logitech   | [G533 Wireless Headset Do... | 3     | snd_usb... | F733910E90 |
| 0471:2118 | Philips... | SHG7980                      | 3     | snd_usb... | BC5D100BBF |
| 047f:c008 | Plantro... | Audio 655 DSP                | 3     | snd_usb... | 8838C40E2F |
| 047f:d955 | Plantro... | Wireless Audio               | 3     | snd_usb... | A58865F4C4 |
| 0572:1804 | Conexan... | HP Dock Audio                | 3     | snd_usb... | 3240076AA6 |
| 06f8:3009 | Guillemot  | Multimedia audio controller  | 3     | gspca_p... | 9E9C06CB6F |
| 08bb:29c0 | Texas I... | PCM2900C Audio CODEC         | 3     | snd_usb... | 25810F9DC3 |
| 093a:2629 | Pixart ... | Multimedia audio controller  | 3     | gspca_p... | 72FDE83F4C |
| 0951:16a4 | Kingsto... | HyperX 7.1 Audio             | 3     | snd_usb... | 1F7F86ED9E |
| 0a12:1243 | Cambrid... | CSRA64110 USB Audio          | 3     |            | 2A3F7B30CC |
| 0b0e:0306 | GN Netcom  | Jabra EVOLVE LINK            | 3     | snd_usb... | A0518E949A |
| 0d8c:000e | C-Media... | Audio Adapter (Planet UP-... | 3     | snd_usb... | 7CE46A749E |
| 0d8c:0105 | C-Media... | CM108 Audio Controller       | 3     | snd_usb... | D21BC7358D |
| 0d8c:013a | C-Media... | USB PnP Sound Device         | 3     | snd_usb... | 32F9C98FE6 |
| 1532:0a02 | Razer USA  | Razer ManO'War               | 3     | snd_usb... | 1625938FF3 |
| 1a1d:8301 | Veho       | 2.4G Wireless Headset        | 3     | snd_usb... | 76B92234CA |
| 1a86:752d | QinHeng... | CH345 MIDI adapter           | 3     | snd_usb... | 9968239DA3 |
| 1b3f:2007 | General... | USB Audio Device             | 3     | snd_usb... | 94058A82CA |
| 0416:1021 | Winbond... | USB AUDIO Mouse              | 2     | snd_usb... | A860F07046 |
| 041e:3010 | Creativ... | SoundBlaster MP3+            | 2     | snd_usb... | C59EB70BAF |
| 041e:3042 | Creativ... | SB X-Fi Surround 5.1         | 2     | snd_usb... | F32755062C |
| 046d:0a07 | Logitech   | Z-10 Speakers                | 2     | snd_usb... | CCB7142AC0 |
| 046d:0a12 | Logitech   | Wireless Headset             | 2     | snd_usb... | B45F44A0F7 |
| 046d:0a13 | Logitech   | Z-5 Speakers                 | 2     | snd_usb... | A450827948 |
| 046d:0a17 | Logitech   | G330 Headset                 | 2     | snd_usb... | 5FEAFD37C9 |
| 0471:0151 | Philips... | USB Audio System             | 2     | snd_usb... | C2D1F5C35A |
| 0471:2119 | Philips... | SHG8200                      | 2     | snd_usb... | 87086AEB40 |
| 047f:02f7 | Plantro... | BT600                        | 2     | snd_usb... | 4D5087B262 |
| 047f:aa09 | Plantro... | DA40                         | 2     | snd_usb... | F5F54893BC |
| 047f:ad01 | Plantro... | GameCom 777 5.1 Headset      | 2     | snd_usb... | 15BF44F112 |
| 047f:c011 | Plantro... | .Audio 478 USB               | 2     | snd_usb... | 455DDB0E74 |
| 047f:c014 | Plantro... | .Audio 622 USB               | 2     | snd_usb... | A78D2DC653 |
| 047f:c01e | Plantro... | C310-M                       | 2     | snd_usb... | 481A2508BF |
| 047f:c021 | Plantro... | RIG                          | 2     | snd_usb... | E96981E395 |

### Touchpad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 06cb:2970 | Synaptics  | touchpad                     | 25    | usbhid     | 8D6D195DA2 |
| 044e:1218 | Alps El... | Touchpad                     | 3     | usbhid     | 73B87C222F |
| 06cb:0009 | Synaptics  | Composite TouchPad and Tr... | 2     | synapti... | A9E837C9EB |
| 06cb:5710 | Synaptics  | Touch Pad V 103S             | 2     | usbhid     | A3FFD5C89F |
| 044e:1210 | Alps El... | Touchpad                     | 1     | usbhid     | C97022A8FC |
| 062a:19b5 | MosArt ... | TouchPad                     | 1     | usbhid     | 61BB547684 |
| 06cb:5711 | Synaptics  | Touch Pad V 103u9            | 1     | usbhid     | 2D9527DBD4 |

### Touchscreen (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04f3:20d0 | Elan Mi... | Touchscreen                  | 8     | usbhid     | ECFA149223 |
| 04f3:000a | Elan Mi... | Touchscreen                  | 7     | usbhid     | 10D1795169 |
| 04f3:250e | Elan Mi... | Touchscreen                  | 7     | usbhid     | 8B699D7E6C |
| 0eef:0001 | D-WAV S... | eGalax TouchScreen           | 7     | usbhid     | 4A6A073320 |
| 0408:3008 | Quanta ... | OpticalTouchScreen           | 6     | usbhid     | 2E89DCF36E |
| 04f3:0254 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 83F2FF723D |
| 04f3:2494 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 112EB80A9E |
| 04f3:012d | Elan Mi... | Touchscreen                  | 5     | usbhid     | 197C08E66F |
| 04f3:2013 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 13E9034651 |
| 04f3:2234 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 200F73880C |
| 1926:0bce | NextWindow | Touchscreen                  | 5     | usbhid     | 59BB8EC907 |
| 04f3:016f | Elan Mi... | Touchscreen                  | 4     | usbhid     | 41A0E2A118 |
| 04f3:24a1 | Elan Mi... | Touchscreen                  | 4     | usbhid     | 65F14CA77F |
| 04e7:0020 | Elo Tou... | Touchscreen Interface (2700) | 3     | usbhid     | 612620FA7A |
| 04f3:005a | Elan Mi... | Touchscreen                  | 3     | usbhid     | F95BBD54DA |
| 04f3:0074 | Elan Mi... | Touchscreen                  | 3     | usbhid     | 10FB53EFCA |
| 04f3:0085 | Elan Mi... | Touchscreen                  | 3     | usbhid     | 46820DB730 |
| 04f3:009d | Elan Mi... | Touchscreen                  | 3     | usbhid     | 26C2CAF634 |
| 04f3:010c | Elan Mi... | Touchscreen                  | 3     | usbhid     | AD06395996 |
| 04f3:036e | Elan Mi... | Touchscreen                  | 3     | usbhid     | C72380C4E8 |
| 04f3:20d6 | Elan Mi... | Touchscreen                  | 3     | usbhid     | CC12571867 |
| 1926:0344 | NextWindow | Touchscreen                  | 3     | usbhid     | 45679FA2F6 |
| 0408:3003 | Quanta ... | OpticalTouchScreen           | 2     | usbhid     | D44BEF08F5 |
| 04f3:0018 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 72500924FF |
| 04f3:002a | Elan Mi... | Touchscreen                  | 2     | usbhid     | D8DB450D73 |
| 04f3:0034 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 6C7804AC48 |
| 04f3:0117 | Elan Mi... | Touchscreen                  | 2     | usbhid     | A3FFD5C89F |
| 04f3:015d | Elan Mi... | Touchscreen                  | 2     | usbhid     | 44DC7D96C7 |
| 04f3:016c | Elan Mi... | Touchscreen                  | 2     | usbhid     | 35F9DBEE89 |
| 04f3:024b | Elan Mi... | Touchscreen                  | 2     | usbhid     | 18BB588ACC |
| 04f3:0348 | Elan Mi... | Touchscreen                  | 2     | usbhid     | C0DCEE7A80 |
| 04f3:0396 | Elan Mi... | Touchscreen                  | 2     | usbhid     | D5CD1F682E |
| 04f3:0406 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 5CAD0D6150 |
| 04f3:0418 | Elan Mi... | Touchscreen                  | 2     | usbhid     | F2DB78FEFC |
| 04f3:0422 | Elan Mi... | Touchscreen                  | 2     | usbhid     | FDCF5773E1 |
| 04f3:2021 | Elan Mi... | Touchscreen                  | 2     | usbhid     | C6BC466B79 |
| 04f3:2070 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 910D564E8E |
| 04f3:2083 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 759D048AD1 |
| 04f3:2085 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 39115F2454 |
| 04f3:21f9 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 720FCA0EF9 |
| 04f3:228a | Elan Mi... | Touchscreen                  | 2     | usbhid     | 6CB660F70F |
| 04f3:228c | Elan Mi... | Touchscreen                  | 2     | usbhid     | 7611B00DAF |
| 04f3:22c3 | Elan Mi... | Touchscreen                  | 2     | usbhid     | AE39DC6976 |
| 04f3:2313 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 82C02D11DB |
| 04f3:2356 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 44219C33C7 |
| 04f3:24a0 | Elan Mi... | Touchscreen                  | 2     | usbhid     | 329485275D |
| 04f3:24d4 | Elan Mi... | Touchscreen                  | 2     | usbhid     | D302412809 |
| 04f3:2544 | Elan Mi... | Touchscreen                  | 2     | usbhid     | B4ED65654C |
| 1926:0003 | NextWindow | 1900 HID Touchscreen         | 2     | usbhid     | EF835695B4 |
| 1926:0006 | NextWindow | 1950 HID Touchscreen         | 2     | usbhid     | 62E3C9247C |
| 1926:0065 | NextWindow | 1950 HID Touchscreen         | 2     | usbhid     | 26B75090A9 |
| 1926:0083 | NextWindow | 1950 HID Touchscreen         | 2     | usbhid     | A7CE72E3F1 |
| 1926:0330 | NextWindow | Touchscreen                  | 2     | usbhid     | BAA91679D8 |
| 1926:0dbe | NextWindow | Touchscreen                  | 2     | usbhid     | BE8250E028 |
| 1926:0dc6 | NextWindow | Touchscreen                  | 2     | usbhid     | 022809A636 |
| 1926:0e17 | NextWindow | Touchscreen                  | 2     | usbhid     | DE93F78B0C |
| 0408:3033 | Quanta ... | OpticalTouchScreen           | 1     | usbhid     | 0B7EB6DDFC |
| 04f3:000c | Elan Mi... | Touchscreen                  | 1     | usbhid     | 8BF9F9DFC3 |
| 04f3:0017 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 7C82C563B9 |
| 04f3:0021 | Elan Mi... | Touchscreen                  | 1     | usbhid     | B0F9ABFE8D |
| 04f3:0022 | Elan Mi... | Touchscreen                  | 1     | usbhid     | FA5BBECCF2 |
| 04f3:0023 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 4DED2DA172 |
| 04f3:002f | Elan Mi... | Touchscreen                  | 1     | usbhid     | CA13E88F55 |
| 04f3:003d | Elan Mi... | Touchscreen                  | 1     | usbhid     | 9D8F98B831 |
| 04f3:007f | Elan Mi... | Touchscreen                  | 1     | usbhid     | 3E12B22705 |
| 04f3:0086 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 96108AA65D |
| 04f3:009b | Elan Mi... | Touchscreen                  | 1     | usbhid     | C6F56A5676 |
| 04f3:0125 | Elan Mi... | Touchscreen                  | 1     | usbhid     | E4421675DE |
| 04f3:012c | Elan Mi... | Touchscreen                  | 1     | usbhid     | EFCBC58CE9 |
| 04f3:012e | Elan Mi... | Touchscreen                  | 1     | usbhid     | D6A2D267C5 |
| 04f3:013b | Elan Mi... | Touchscreen                  | 1     | usbhid     | 0F518ACFC3 |
| 04f3:0143 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 5834730131 |
| 04f3:0154 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 859AAD148A |
| 04f3:0155 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 106E86F531 |
| 04f3:0194 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 2D9527DBD4 |
| 04f3:0201 | Elan Mi... | Touchscreen                  | 1     | usbhid     | D703E6C3B3 |
| 04f3:0206 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 4202327E1A |
| 04f3:020b | Elan Mi... | Touchscreen                  | 1     | usbhid     | 37B056E670 |
| 04f3:020d | Elan Mi... | Touchscreen                  | 1     | usbhid     | F380930D83 |
| 04f3:021f | Elan Mi... | Touchscreen                  | 1     | usbhid     | E8CAF6C2A9 |
| 04f3:0220 | Elan Mi... | Touchscreen                  | 1     | usbhid     | C1DD7C5ECB |
| 04f3:0224 | Elan Mi... | Touchscreen                  | 1     | usbhid     | C4A77532B2 |
| 04f3:0248 | Elan Mi... | Touchscreen                  | 1     | usbhid     | D96AD40896 |
| 04f3:024d | Elan Mi... | Touchscreen                  | 1     | usbhid     | 56CBE06615 |
| 04f3:0256 | Elan Mi... | Touchscreen                  | 1     | usbhid     | CC3C253FCD |
| 04f3:0261 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 26E0937896 |
| 04f3:0263 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 802A559148 |
| 04f3:0266 | Elan Mi... | Touchscreen                  | 1     | usbhid     | FB0189FEEC |
| 04f3:0280 | Elan Mi... | Touchscreen                  | 1     | usbhid     | CCCDC8BB55 |
| 04f3:0303 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 72EBF685C2 |
| 04f3:034e | Elan Mi... | Touchscreen                  | 1     | usbhid     | 645368FC41 |
| 04f3:034f | Elan Mi... | Touchscreen                  | 1     | usbhid     | 88D364869F |
| 04f3:0363 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 66663BA5E9 |
| 04f3:036d | Elan Mi... | Touchscreen                  | 1     | usbhid     | 6F94FCD1C0 |
| 04f3:0389 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 50FFA5DCEC |
| 04f3:042f | Elan Mi... | Touchscreen                  | 1     | usbhid     | E15FF03F59 |
| 04f3:0436 | Elan Mi... | Touchscreen                  | 1     | usbhid     | A2974D854D |
| 04f3:0441 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 6B7CB439E3 |
| 04f3:2020 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 06EADCEDD8 |
| 04f3:2033 | Elan Mi... | Touchscreen                  | 1     | usbhid     | 6A35A77419 |

### Tv card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 093a:2620 | Pixart ... | TV Card                      | 31    | gspca_p... | F9823E634A |
| 0ac8:303b | Z-Star ... | ZC0303 Webcam                | 26    | gspca_z... | C542826775 |
| 0402:5602 | ALi        | M5602 Video Camera Contro... | 25    | gspca_m... | A28F7B2623 |
| 045e:00f7 | Microsoft  | LifeCam VX-1000              | 20    | gspca_s... | EE184BFE51 |
| 0ac8:305b | Z-Star ... | ZC0305 Webcam                | 20    | gspca_z... | 276FD0BC49 |
| 046d:0896 | Logitech   | OrbiCam                      | 19    | gspca_v... | 1CE26C391A |
| 05e1:0501 | Syntek     | DC-1125 Webcam               | 19    | stkwebcam  | B304C61746 |
| 093a:2622 | Pixart ... | Webcam Genius                | 15    | gspca_p... | BF689A3BCB |
| 046d:08d7 | Logitech   | QuickCam Communicate STX     | 14    | gspca_z... | 426AE68B93 |
| 093a:2624 | Pixart ... | Webcam                       | 12    | gspca_p... | BDB727808F |
| 045e:00f5 | Microsoft  | LifeCam VX-3000              | 11    | gspca_s... | E2791951A5 |
| 046d:08da | Logitech   | QuickCam Messanger           | 11    | gspca_z... | 03A250A2E9 |
| 046d:089d | Logitech   | QuickCam E2500 series        | 10    | gspca_z... | 6B8676DFEF |
| 174f:a311 | Syntek     | 1.3MPixel Web Cam - Asus ... | 9     | stkwebcam  | C1DA7EE91F |
| 046d:08d9 | Logitech   | QuickCam IM/Connect          | 8     | gspca_z... | 8CDD8FFE23 |
| 093a:262c | Pixart ... | TV Card                      | 8     | gspca_p... | D70072A75B |
| 046d:092f | Logitech   | QuickCam Express Plus        | 7     | gspca_s... | B9F2AE0CCF |
| 093a:2476 | Pixart ... | CIF Single Chip              | 7     | gspca_p... | D73E7CDAF7 |
| 093a:2626 | Pixart ... | TV Card                      | 7     | gspca_p... | D3A3F71EF7 |
| 1415:2000 | Nam Tai... | Sony Playstation Eye         | 7     | gspca_o... | D082929A57 |
| 046d:08af | Logitech   | QuickCam Easy/Cool           | 6     | gspca_z... | BB5E8345C0 |
| 093a:2468 | Pixart ... | SoC PC-Camera                | 6     | gspca_p... | B61D174C21 |
| 0c45:624f | Microdia   | PC Camera (SN9C201 + OV9650) | 6     | gspca_s... | 5B4BAFA432 |
| 0ac8:301b | Z-Star ... | ZC0301 Webcam                | 5     | gspca_z... | EF1765E325 |
| 041e:4052 | Creativ... | Live! Cam Vista IM           | 4     | gspca_o... | EBED6181EA |
| 041e:4064 | Creativ... | VF0420 Live! Cam Vista IM    | 4     | gspca_o... | C9CCBD7C3F |
| 046d:08a2 | Logitech   | Labtec Webcam Pro            | 4     | gspca_z... | 51837DE98F |
| 046d:08ad | Logitech   | QuickCam Communicate STX     | 4     | gspca_z... | 98746816D9 |
| 0ac8:0328 | Z-Star ... | A4Tech PK-130MG              | 4     | gspca_v... | 56944B383F |
| 0ac8:307b | Z-Star ... | USB 1.1 Webcam               | 4     | gspca_z... | 15968F5811 |
| 0ac8:c002 | Z-Star ... | Visual Communication Came... | 4     | gspca_v... | 8D7F285234 |
| 0c45:608f | Microdia   | PC Camera (SN9C103 + OV7630) | 4     | gspca_s... | FEFB26C581 |
| 045e:00f4 | Microsoft  | LifeCam VX-6000 (SN9C20x ... | 3     | gspca_s... | EDFDFB06D3 |
| 093a:2472 | Pixart ... | CIF Single Chip              | 3     | gspca_p... | C1255CDB72 |
| 093a:2621 | Pixart ... | PAC731x Trust Webcam         | 3     | gspca_p... | C07EF20B6E |
| 0c45:6128 | Microdia   | PC Camera (SN9C325 + OM6802) | 3     | gspca_s... | 3AAC9757B6 |
| 2040:7200 | Hauppauge  | WinTV HVR-950                | 3     | au0828     | AE5B68C4AD |
| 041e:405f | Creativ... | WebCam Vista (VF0330)        | 2     | gspca_o... | B3C7478840 |
| 041e:4061 | Creativ... | Live! Cam Notebook Pro [V... | 2     | gspca_o... | 4E187292DA |
| 046d:08a9 | Logitech   | Notebook Deluxe              | 2     | gspca_z... | 568DE70E4A |
| 0471:0329 | Philips... | SPC 900NC PC Camera / ORI... | 2     | pwc, sn... | 50792DF026 |
| 093a:2460 | Pixart ... | Q-TEC WEBCAM 100             | 2     | gspca_p... | FC4EBA57CC |
| 093a:2470 | Pixart ... | SoC PC-Camera                | 2     | gspca_p... | A28F7B2623 |
| 093a:2608 | Pixart ... | PAC7311 Trust WB-3300p       | 2     | gspca_p... | 2D16479F4B |
| 093a:260e | Pixart ... | PAC7311 Gigaware VGA PC C... | 2     | gspca_p... | 699063D316 |
| 0ac8:0302 | Z-Star ... | ZC0302 Webcam                | 2     | gspca_z... | ABFAB43B36 |
| 0c45:600d | Microdia   | TwinkleCam USB camera        | 2     | gspca_s... | 6A798F999C |
| 0c45:6028 | Microdia   | Typhoon Easycam USB 330K ... | 2     | gspca_s... | AEAB86C587 |
| 0c45:60b0 | Microdia   | Genius VideoCam Look         | 2     | gspca_s... | 8C929530B7 |
| 0c45:613a | Microdia   | PC Camera (SN9C120)          | 2     | gspca_s... | CFCEDC1F4F |
| 0c45:6270 | Microdia   | PC Camera (SN9C201 + MI03... | 2     | gspca_s... | E969E52D33 |
| 041e:401c | Creativ... | Webcam NX [PD1110]           | 1     | gspca_z... | 5305CEA18B |
| 041e:4028 | Creativ... | Vista Plus cam [VF0090]      | 1     | gspca_p... | EFA320E41A |
| 0458:7029 | KYE Sys... | Genius Look 320s (SN9C201... | 1     | gspca_s... | CE3CF2888A |
| 046d:0892 | Logitech   | OrbiCam                      | 1     | gspca_v... | 7CE7D6F7C3 |
| 046d:08ae | Logitech   | QuickCam for Notebooks       | 1     | snd_usb... | E747D8C526 |
| 046d:08f0 | Logitech   | QuickCam Messenger           | 1     | gspca_s... | AB7B26B325 |
| 046d:08f6 | Logitech   | QuickCam Messenger Plus      | 1     | gspca_s... | 7B106B9427 |
| 046d:0928 | Logitech   | QuickCam Express             | 1     | gspca_s... | D78C1D6096 |
| 046d:0929 | Logitech   | Labtec Webcam Pro            | 1     | gspca_s... | 19C101AB87 |
| 046d:092e | Logitech   | QuickCam Chat                | 1     | gspca_s... | 2C10191944 |
| 0471:032d | Philips... | SPC 210NC PC Camera          | 1     | gspca_z... | 2441D6D1D8 |
| 0545:8333 | Xirlink    | Veo Stingray/Connect Web ... | 1     | gspca_t... | B9F90CB8E0 |
| 054c:0154 | Sony       | Eyetoy Audio Device          | 1     | gspca_o... | 4BA24556E4 |
| 06f8:3008 | Guillemot  | USB camera                   | 1     | gspca_s... | 6E4D6B9ECA |
| 0733:0401 | ViewQue... | CS330 Webcam                 | 1     | gspca_s... | C6F1D561A0 |
| 07ca:0889 | AVerMed... | AVerTV Satellite 2           | 1     |            | 174EC665C6 |
| 093a:2463 | Pixart ... | CIF Single Chip              | 1     | gspca_p... | 1DE59A68CD |
| 093a:2600 | Pixart ... | Typhoon Easycam USB 330K ... | 1     | gspca_p... | 89B7926B1C |
| 0ac8:0321 | Z-Star ... | Vimicro generic vc0321 Ca... | 1     | gspca_v... | 1CF43D844D |
| 0c45:6007 | Microdia   | VideoCAM Eye                 | 1     | gspca_s... | 90EA766D86 |
| 0c45:6009 | Microdia   | VideoCAM ExpressII           | 1     | gspca_s... | 120E7702AF |
| 0c45:6029 | Microdia   | Triplex i-mini PC Camera     | 1     | gspca_s... | 4B8FD34544 |
| 0c45:602b | Microdia   | VideoCAM NB 300              | 1     | sn9c102    | DF2321CD21 |
| 0c45:602c | Microdia   | Clas Ohlson TWC-30XOP Webcam | 1     | gspca_s... | C542826775 |
| 0c45:602e | Microdia   | VideoCAM Messenger           | 1     | gspca_s... | 2022755796 |
| 0c45:6100 | Microdia   | USB camera                   | 1     | gspca_s... | 0AB0ACEA30 |
| 0c45:613c | Microdia   | PC Camera (SN9C120)          | 1     | gspca_s... | 619D8CC7E3 |
| 0c45:613e | Microdia   | PC Camera (SN9C120)          | 1     | gspca_s... | 64E722CEC4 |
| 0c45:6242 | Microdia   | PC Camera (SN9C201 + MI1310) | 1     | gspca_s... | 2CAE195313 |
| 0c45:624e | Microdia   | PC Camera (SN9C201 + SOI968) | 1     | gspca_s... | B60039A681 |
| 0ccd:0096 | TerraTe... | Grabby                       | 1     | em28xx     | F298AE57F6 |
| 1164:0622 | YUAN Hi... | USB GOTVIEW DVD2             | 1     | pvrusb2    | C0CF078B6C |
| 2040:4902 | Hauppauge  | HD PVR                       | 1     | hdpvr      | 01928383AA |
| 2040:7501 | Hauppauge  | WinTV                        | 1     | pvrusb2    | AE5B68C4AD |
| 6000:dec1 | Beholde... | TV Voyage                    | 1     | tm6000     | 39E3030E0A |
| eb1a:2860 | eMPIA T... | USB 2860 Device              | 1     | em28xx     | 5764250D85 |
| eb1a:2861 | eMPIA T... | TV Card                      | 1     | em28xx     | F6F1F3D526 |
| eb1a:2881 | eMPIA T... | EM2881 Video Controller      | 1     | em28xx     | E22CC7C6C8 |

### Ups (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 051d:0002 | America... | Back-UPS Pro 500/1000/1500   | 128   | usbhid     | 19A4B45331 |
| 0764:0501 | Cyber P... | CP1500 AVR UPS               | 40    | usbhid     | 239A2E1678 |
| 0d9f:0004 | Powercom   | HID UPS Battery              | 10    | usbhid     | EF09CB18CC |
| 06da:0003 | Phoenix... | 1300VA UPS                   | 6     | usbhid     | 9B671B15DD |
| 0463:ffff | MGE UPS... | UPS                          | 5     | usbfs      | 8F56CB529C |
| 0d9f:00a2 | Powercom   | Imperial Uninterruptible ... | 5     | usbhid     | AEEDCA54FC |
| 0925:1234 | Lakevie... | UPS USB MON V1.4             | 4     | usbhid     | A12C16610A |
| 0d9f:00a3 | Powercom   | Smart King PRO Uninterrup... | 3     | usbhid     | F4AF5BD9C9 |
| 051d:0003 | America... | UPS                          | 2     | usbhid     | 4213886CA6 |
| 0d9f:00a4 | Powercom   | WOW Uninterruptible Power... | 2     | usbhid     | D06D669535 |
| 050d:0751 | Belkin ... | Belkin UPS                   | 1     | usbhid     | 71F7F3AD8A |
| 0592:0002 | Powerware  | UPS (X-Slot)                 | 1     |            | 049C18DB44 |
| 05dd:a011 | Delta E... | MINUTEMAN UPS                | 1     | usbhid     | E091D03447 |
| 06da:0002 | Phoenix... | UPS                          | 1     |            | 4F5E89A87E |
| 06da:ffff | Phoenix... | Offline UPS                  | 1     | usbhid     | BF9A749A5B |
| 0764:0601 | Cyber P... | PR1500LCDRT2U UPS            | 1     | usbhid     | 91C657B5A8 |
| 09ae:2010 | Tripp Lite | UPS                          | 1     | usbhid     | 5D1A48EE4E |
| 09ae:2012 | Tripp Lite | UPS                          | 1     | usbhid     | 8C61A8435F |
| 09ae:4004 | Tripp Lite | UPS                          | 1     | usbfs      | 52D5275C7F |
| 0d9f:00a6 | Powercom   | Black Knight PRO Uninterr... | 1     | usbhid     | B9B505B7F4 |

### Video (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 048d:9006 | Integra... | IT9135 BDA Afatech DVB-T ... | 3     | dvb_usb... | EDB984C4E6 |
| 2304:0224 | Pinnacl... | MovieBox Plus (710-USB)      | 2     |            | E9365BC8D0 |
| 0fd9:0051 | Elgato ... | GameCapture HD               | 1     |            | 05F988930D |
| 1164:1ee9 | YUAN Hi... | Polaris AV Capture           | 1     |            | 741E3E3C76 |
| 1b80:a41c | Afatech    | Polaris AV Capture           | 1     |            | F20674C0B8 |
| 5555:3382 | Epiphan... | VGA2USB Frame Grabber        | 1     |            | 37A831391B |

### Wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2717:ff88 | Android    | Android                      | 10    | rndis_host | 6C00967A8C |
| 22b8:2e25 | Motorol... | Moto E (4)                   | 5     | rndis_host | 11B9D955A8 |
| 0b05:7782 | ASUSTek... | Device CD-ROM                | 4     | rndis_host | 1F62DD8462 |
| 1286:4e31 | Marvell... | Mobile Composite Device Bus  | 3     | rndis_host | F497726038 |
| 12d1:1039 | Huawei ... | Ideos (tethering mode)       | 3     | rndis_host | CA1FB717A1 |
| 0fce:71e8 | Sony Er... | F5321                        | 2     | rndis_host | 70D66C5819 |
| 17ef:782f | Lenovo     | Lenovo                       | 2     | rndis_host | 7BA3F44B0A |
| 216f:0044 | Altair ... | Modem YOTA 4G LTE            | 2     | rndis_host | 92A7F0EA0B |
| 0421:0704 | Nokia M... | Nokia_X2 (RM-1013)           | 1     | rndis_host | 2762E434EB |
| 0fce:7193 | Sony Er... | C6603                        | 1     | rndis_host | F748A62EBE |
| 0fce:71aa | Sony Er... | Android                      | 1     | rndis_host | 0C9E0F4767 |
| 0fce:71ba | Sony Er... | D6603                        | 1     | rndis_host | 5974A74BFD |
| 0fce:71f6 | Sony Er... | H4311                        | 1     | rndis_host | C9FFEA0EA6 |
| 0fce:81bb | Sony Er... | D5803                        | 1     | rndis_host | 7D93192AAE |
| 12d1:107c | Huawei ... | Che2-L11                     | 1     | rndis_host | 6D94D26ECD |
| 15a9:003a | Gemtek     | Modem YOTA 4G LTE            | 1     |            | 02E0DBC8D3 |
| 271d:90b5 | Android    |                              | 1     | rndis_host | 65345FD237 |
| 2916:f00e | Android    | Android                      | 1     | rndis_host | 79937B3042 |
| 2970:0004 | Fly        | Evo Chic 3                   | 1     | rndis_host | A83B92D6B0 |
| 2970:2005 | Wileyfox   | Spark                        | 1     | rndis_host | 2E016FB88C |

### Others (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2717:ff40 | MediaTek   | SDM636-MTP _SN:02BF3EA3      | 31    | usbfs      | 13D633A029 |
| 06cb:009a | Synaptics  | Synaptics WBDI               | 30    |            | 497E22D203 |
| 0e8d:2008 | MediaTek   | Impress_Luck                 | 28    | usbfs      | FE9E0ACDE5 |
| 138a:0097 | Validit... | Synaptics WBDI               | 20    |            | 3AC5B5C4AD |
| 06cb:0081 | Synaptics  | Synaptics WBDI               | 19    |            | 83192A2228 |
| 05ac:8300 | Apple      | Built-in iSight (no firmw... | 18    | isight_... | FDEA938323 |
| 06cb:00a2 | Synaptics  | Synaptics WBDI               | 12    |            | CE2A6FB934 |
| 138a:00ab | Validit... | Synaptics VFS7552 Touch F... | 11    |            | 0C96DDC649 |
| 22b8:2e82 | Motorol... | Moto Z (2)                   | 11    | usbfs      | 3831423C95 |
| 04b8:014a | Seiko E... | Perfection V37/V370          | 9     |            | CB151DFE45 |
| 0e8d:201d | MediaTek   | Tele2_Maxi_LTE               | 8     | usbfs      | 3FB0BFFFCA |
| 04b4:5217 | Cypress... | Billboard Device             | 6     | usbhid     | BF4A9DEE07 |
| 0955:0007 | Nvidia     | stereo controller            | 6     |            | F6D05FF577 |
| 045e:02ea | Microsoft  | Xbox One S Controller        | 5     | xpad       | 85B34D0336 |
| 0483:3748 | STMicro... | ST-LINK/V2                   | 5     |            | A8EF2FFC63 |
| 0af0:7601 | Option     | Globetrotter MO40x 3G Mod... | 5     | hso        | 03DEB29A41 |
| 1164:7f07 | YUAN Hi... | STK7700D                     | 5     |            | 857C8BE5D0 |
| 1934:5168 | Feature... | F71610A or F71612A Consum... | 5     | mceusb     | B7561ADE6F |
| 2109:0102 | VIA Labs   | USB 2.0 BILLBOARD            | 5     |            | 74DD313167 |
| 045e:028f | Microsoft  | Xbox360 Wireless Controller  | 4     |            | 09CCAF8CCF |
| 045e:02d1 | Microsoft  | Xbox One Controller          | 4     | xpad       | 4B4782AC1D |
| 045e:02e6 | Microsoft  | Wireless XBox Controller ... | 4     |            | 7AF20CDF5A |
| 04eb:e033 | Northst... | eHome Infrared Transceiver   | 4     |            | A8D0FA2257 |
| 085c:0400 | ColorVi... | Spyder 4                     | 4     |            | D8D0364599 |
| 0b05:7772 | ASUSTek... | ASUS Zenfone GO (ZB500KL)... | 4     | usbfs      | 2BC400D84F |
| 0ccd:0080 | TerraTe... | DMX 6Fire USB                | 4     | snd_usb... | 74C3A10E25 |
| 1782:4001 | Spreadt... | IQ4505 Quad                  | 4     |            | 35B986C185 |
| 17e9:6000 | Display... | USB 3.0 5K Graphic Docking   | 4     | cdc_ncm    | 4CED599618 |
| 187f:0600 | Siano M... | MDTV Receiver                | 4     | smsusb     | 4422093EAE |
| 18d1:4ee2 | Google     | Nexus Device (debug)         | 4     |            | 566F024B92 |
| 18d1:4ee7 | Google     | ZTE A2017U                   | 4     |            | A2BCE1F421 |
| 1b1c:0c09 | Corsair    | H100i v2                     | 4     |            | 63314DCB31 |
| 2040:0265 | Hauppauge  | dualHD                       | 4     | em28xx     | 8269929E09 |
| 2109:0100 | VIA Labs   | USB 2.0 BILLBOARD            | 4     |            | C2D1F5C35A |
| 22b8:2e76 | Motorol... | moto e5 play                 | 4     | usbfs      | 55CD396670 |
| 2433:b200 | ASETEK     | 690LC                        | 4     |            | 7F1BE20709 |
| 2833:0211 | Oculus VR  | Rift Sensor                  | 4     | uvcvideo   | B3E32D1026 |
| 0489:e031 | Foxconn... | BCM20702A0                   | 3     | btusb      | 8F5D5F5C26 |
| 0489:e080 | Foxconn... | BT                           | 3     |            | 0E146447BF |
| 04b8:013c | Seiko E... | Perfection V19               | 3     |            | 4DDFFD5967 |
| 054c:01bb | Sony       | FeliCa S320 [PaSoRi]         | 3     |            | F3208D8466 |
| 06cb:00c7 | Synaptics  |                              | 3     |            | 94C3F1BC72 |
| 0bda:5400 | Realtek... | BillBoard Device             | 3     |            | DBA78E9C22 |
| 0e8d:201c | MediaTek   | M5                           | 3     |            | 3D80EACDFC |
| 131d:0156 | Natural... | TrackIR 4 Pro Head Tracker   | 3     |            | CC9738C393 |
| 138a:0094 | Validit... | Synaptics WBDI               | 3     |            | 941DF897AA |
| 16c0:05dc | Van Ooi... | shared ID for use with li... | 3     |            | 78F624C19E |
| 1b71:3002 | Fushicai   | USBTV007 Video Grabber [E... | 3     | usbtv      | C80D56CB77 |
| 1d5c:5100 | Fresco ... | Generic Billboard Device     | 3     |            | 23DC7C0455 |
| 22b8:2e81 | Motorol... | moto z3                      | 3     | usbfs      | 3E998F19FB |
| 0458:2019 | KYE Sys... | ColorPage-HR6X Slim          | 2     |            | 0D2C002967 |
| 045e:02ad | Microsoft  | Xbox NUI Audio               | 2     |            | 2A34F25D17 |
| 045e:02fe | Microsoft  | XBOX ACC                     | 2     |            | 4D739ABCDF |
| 045e:091e | Microsoft  | XBOX ACC                     | 2     |            | A9A066D4B7 |
| 0471:060c | Philips... | Consumer Infrared Transce... | 2     | mceusb     | 28DFB478B7 |
| 0471:060d | Philips... | Consumer Infrared Transce... | 2     | mceusb     | E7259783D1 |
| 0471:0815 | Philips... | eHome Infrared Receiver      | 2     | mceusb     | 0E8628D300 |
| 04b4:1002 | Cypress... | CY7C63001 R100 FM Radio      | 2     | dsbr100    | 4A6A073320 |
| 04b8:0130 | Seiko E... | GT-X770 [Perfection V500]    | 2     |            | B86DF74030 |
| 04b9:0300 | Rainbow... | SafeNet USB SuperPro/Ultr... | 2     |            | F58375E009 |
| 04d8:e11c | Microch... | TL866CS EEPROM Programmer... | 2     |            | 0432DDBB6C |
| 04f2:a216 | Chicony... | Digital Video Device         | 2     |            | 4F0A8E2C5B |
| 04f3:0c07 | Elan Mi... | ELAN:Fingerprint             | 2     |            | A0CF277545 |
| 0502:3643 | Acer       | E39                          | 2     |            | B90C237653 |
| 0572:c68a | Conexan... | EyeTV Stick                  | 2     | dvb_usb... | 4863E51684 |
| 0582:012a | Roland     | UM-ONE                       | 2     | snd_usb... | 1E67C4F731 |
| 05c6:9039 | Qualcomm   | Android                      | 2     | usbfs      | 444FDD1AF8 |
| 0644:8021 | TEAC       | TASCAM US-122mkII            | 2     | snd_usb... | 7F74A650DB |
| 06cb:00a8 | Synaptics  |                              | 2     |            | 0CAC406018 |
| 06cb:00bb | Synaptics  |                              | 2     |            | 74DD313167 |
| 07ca:3835 | AVerMed... | AVerTV Volar Green HD (A8... | 2     | dvb_usb... | 945C737A32 |
| 07ca:8591 | AVerMed... |                              | 2     |            | BE8250E028 |
| 07ca:a110 | AVerMed... | TD110                        | 2     | dvb_usb... | 4039D51671 |
| 07ca:c039 | AVerMed... | C039 USB Pure Capture        | 2     |            | CF1F13340E |
| 0819:0101 | eLicenser  | License Management and Co... | 2     |            | FDC986FDE7 |
| 0971:2000 | Gretag-... | i1 Pro                       | 2     |            | 6B863A586E |
| 0e6f:02b8 | Logic3     | Afterglow Wired Controlle... | 2     | xpad       | 53ABDA4642 |
| 1164:3edc | YUAN Hi... | STK7700D                     | 2     |            | 9FEC6C5DE7 |
| 12d1:1051 | Huawei ... | Android                      | 2     |            | 4E5F4BC633 |
| 12d1:257c | Huawei ... | Y541-U02                     | 2     |            | 4030941DEB |
| 1366:0101 | SEGGER     | J-Link PLUS                  | 2     |            | D54F9EADC8 |
| 138a:0092 | Validit... | Synaptics VFS7552 Touch F... | 2     |            | AE7D79F749 |
| 17e9:019e | Display... | USB-DVI                      | 2     | udl        | B972AC5E0E |
| 17e9:4300 | Display... | USB Display Adapter          | 2     | snd_usb... | 68ECFC5409 |
| 17e9:4305 | Display... | dynadock U3.0                | 2     | cdc_ncm    | 3F35BDC85A |
| 18d1:d00d | Google     | Android                      | 2     |            | C8033B809F |
| 1934:0702 | Feature... | Integrated Consumer Infra... | 2     | mceusb     | 62E3C9247C |
| 19d2:0244 | ZTE WCD... | Android                      | 2     |            | 0D9A8C2133 |
| 1b1c:0c03 | Corsair    | H100iGTX Cooler              | 2     |            | 1E0208BF20 |
| 1b1c:0c08 | Corsair    | H80i v2                      | 2     |            | CE19512CBB |
| 1b1c:0c12 | Corsair    | H150i Platinum               | 2     |            | 10A2FF392A |
| 1b1c:0c13 | Corsair    | H115i Platinum               | 2     |            | DE305E87C5 |
| 1c88:0007 | Somagic    | SMI Grabber (EasyCAP DC60... | 2     |            | 63C667B4E6 |
| 1fc9:5002 | NXP Sem... | PTN5002                      | 2     |            | 24A04CA275 |
| 2001:331b | D-Link     | D-Link DWA-121 Wireless N... | 2     |            | F28399B983 |
| 2013:0245 | PCTV Sy... | PCTV 73ESE                   | 2     | dvb_usb... | B9F2AE0CCF |
| 2040:0264 | Hauppauge  | soloHD                       | 2     | em28xx     | 81D31AAB82 |
| 24c6:543a | Unknown... | Xbox ONE Pro Ex controller   | 2     | xpad       | C09E006619 |
| 27c6:538c | Goodix     | FingerPrint                  | 2     |            | 1E82DEB58E |
| 27c6:5584 | Generic    | Goodix FingerPrint Device    | 2     |            | 2DE7F8E811 |

