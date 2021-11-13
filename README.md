Most popular USB devices
========================

This is a project to identify most popular USB devices in modern computers and
share detailed lsusb reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 211516.

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

Top 100 most popular devices in each category.

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Audio (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1235:8205 | Focusri... | Scarlett Solo USB            | 39    | snd_usb... | 357EA9AB5D |
| 1235:8202 | Focusri... | Focusrite Scarlett 2i2 2n... | 38    | snd_usb... | 066A7CE533 |
| 046d:0a87 | Logitech   | G935 Gaming Headset          | 32    | snd_usb... | C1A8B65233 |
| 0955:7002 | Nvidia     | stereo controller            | 32    |            | C97B201719 |
| 041e:322c | Creativ... | SB Omni Surround 5.1         | 28    | snd_usb... | 9499EBDDD8 |
| 1235:8211 | Focusri... | Scarlett Solo (3rd Gen.)     | 28    | snd_usb... | F7CE357637 |
| 1235:8016 | Focusri... | Focusrite Scarlett 2i2       | 27    | snd_usb... | BC70F25DD1 |
| 152a:8750 | Thesyco... | DX7 Pro                      | 27    | snd_usb... | 58E3F9C07F |
| 1397:0507 | BEHRING... | UMC202HD 192k                | 26    | snd_usb... | 044227E4BA |
| 1397:0509 | BEHRING... | UMC404HD 192k                | 26    | snd_usb... | 3678E02E46 |
| 1043:857c | iCreate... | Xonar U7                     | 20    | usbhid     | A19FF7FB6A |
| 1397:0508 | BEHRING... | UMC204HD 192k                | 20    | snd_usb... | 637DBBACBA |
| 1235:8200 | Focusri... | Scarlett 2i4 USB             | 19    | snd_usb... | 3302374263 |
| 1235:8210 | Focusri... | Scarlett 2i2 Camera          | 19    | snd_usb... | C7A0FE2F88 |
| 26ce:0a01 |            | USB Audio                    | 19    | snd_usb... | 8789F3F1E1 |
| 2972:0047 | FiiO El... | FiiO K5 Pro                  | 19    | snd_usb... | E7742AA472 |
| 0499:170f | Yamaha     | Steinberg UR22mkII           | 18    | snd_usb... | AAC1293B60 |
| 0414:a000 | Giga-By... | USB Audio                    | 17    | snd_usb... | AFB539FF26 |
| 0414:a001 | Giga-By... | USB Audio                    | 17    | snd_usb... | AFB539FF26 |
| 0d8c:0066 | C-Media... | Schiit Modi 3                | 17    | snd_usb... | 2C5F510AB0 |
| 19f7:0015 | RODE Mi... | RODE NT-USB Mini             | 17    | snd_usb... | 2A1930C4E4 |
| 0414:a002 | Giga-By... | USB Audio                    | 16    | snd_usb... | CA8C02F319 |
| 0b05:180d | ASUSTek... | STRIX SOUND CARD             | 15    | snd_usb... | A7A8C2CEAD |
| 0b05:189d | ASUSTek... | Xonar SoundCard              | 15    | snd_usb... | 3A14292469 |
| b58e:0005 | Blue Mi... | Yeti Nano                    | 15    | snd_usb... | 37523E831D |
| 046d:0a0b | Logitech   | ClearChat Pro USB            | 14    | snd_usb... | 1339721AC0 |
| 0d8c:0004 | C-Media... | CM6631A Audio Processor      | 14    | usbhid     | 120780E701 |
| 17cc:1001 | Native ... | Komplete Audio 6             | 14    | snd_usb... | 1360830BAB |
| 0bda:4c07 | Realtek... | TX-384Khz Hifi Type-C Audio  | 12    | snd_usb... | 5630D736DD |
| 0499:170a | Yamaha     | Steinberg UR12               | 11    | snd_usb... | FFB66DAFD4 |
| 0b05:1915 | ASUSTek... | USB Audio                    | 11    | usbhid     | A31BD40281 |
| 0b05:1916 | ASUSTek... | USB Audio                    | 11    | snd_usb... | A31BD40281 |
| 1235:800a | Focusri... | Scarlett 2i4                 | 11    | snd_usb... | A1DD9DDD31 |
| 20b1:0008 | XMOS       | Mayfield Audio               | 11    | snd_usb... | 3F6DFEBDF6 |
| 20b1:3008 | XMOS       | iFi (by AMR) HD USB Audio    | 11    | snd_usb... | FA3F31F773 |
| 0499:1703 | Yamaha     | MG-XU                        | 10    | snd_usb... | D3A4772E4E |
| 0b05:1918 | ASUSTek... | USB Audio                    | 10    | snd_usb... | 6E020F3AD1 |
| 20b1:000a | XMOS       | Khadas Tone Control          | 10    | snd_usb... | 2E4383BD79 |
| 20b1:3023 | XMOS       | X1S USB DAC                  | 10    | snd_usb... | 0CB83B4B82 |
| 0499:170d | Yamaha     | AG06/AG03                    | 9     | snd_usb... | 6EB4797B58 |
| 0b05:180f | ASUSTek... | XONAR SOUND CARD             | 9     | snd_usb... | 1EE663A97D |
| 1395:009a | Sennhei... | GSP 370                      | 9     | cdc_acm    | 197CA976E0 |
| 041e:3f19 | Creativ... | E-MU 0204 / USB              | 8     | snd_usb... | F570A4D64A |
| 0582:012f | Roland     | QUAD-CAPTURE                 | 8     | snd_usb... | 93A093110A |
| 1235:801c | Focusri... | Scarlett Solo USB            | 8     | snd_usb... | B92F4485E6 |
| 2972:0035 | FiiO El... | FiiO Q1                      | 8     | snd_usb... | 3808823182 |
| 041e:3f02 | Creativ... | E-Mu 0202                    | 7     | snd_usb... | 3F6EBB3247 |
| 0b05:183c | ASUSTek... | Xonar U7 MKII                | 7     | snd_usb... | 167DDB49CE |
| 1235:8006 | Focusri... | Focusrite Scarlett 2i2       | 7     | snd_usb... | 660E47DA08 |
| 22e8:dac4 | Cambrid... | Azur DacMagic 100            | 7     | snd_usb... | AC73F29C0F |
| 0499:1704 | Yamaha     | Steinberg UR44               | 6     | snd_usb... | 3792E516CD |
| 074d:0002 | Micronas   | BLUE USB Audio 2.0           | 6     | snd_usb... | 3862CF57E0 |
| 07fd:0008 | Mark of... | M2                           | 6     | snd_usb... | BC2879C7E5 |
| 0b05:17a8 | ASUSTek... | ASUS Xonar Essence One       | 6     | usbhid     | D59E8583C7 |
| 17aa:1046 |            | Realtek USB Audio Rear       | 6     | snd_usb... | 136C409F1A |
| 17aa:104d |            | Realtek USB Audio Front      | 6     | snd_usb... | 136C409F1A |
| 041e:3f04 | Creativ... | E-Mu 0404                    | 5     | snd_usb... | F6317B60DD |
| 0499:170b | Yamaha     | Steinberg UR242              | 5     | snd_usb... | B4B00787C2 |
| 0582:00e6 | Roland     | EDIROL UA-25EX (Advanced ... | 5     | snd_usb... | 8859E15CB5 |
| 05a7:40fa | Bose       | Revolve SoundLink            | 5     | usbhid     | C8375FB45E |
| 0b05:1996 | ASUSTek... | USB Audio                    | 5     | snd_usb... | B9C2FEC8AA |
| 0b05:19ac | ASUSTek... | USB Audio                    | 5     | snd_usb... | FF0BC6375E |
| 0db0:543d | Micro S... | USB Audio                    | 5     | snd_usb... | A06646B4DA |
| 152a:85dd | Thesyco... | SMSL USB AUDIO               | 5     | snd_usb... | C7A0FE2F88 |
| 30be:1014 | Schiit ... | Schiit Modi 3+               | 5     | snd_usb... | 9B7DBA0A9C |
| 041e:3243 | Creativ... | Sound BlasterX G5            | 4     | snd_usb... | 7C519C91CA |
| 041e:3257 | Creativ... | Sound Blaster K3+            | 4     | snd_usb... | F2AB7926E3 |
| 04e8:7084 | Samsung... | USB Audio                    | 4     | snd_usb... | 97D8B548F4 |
| 0b05:1984 | ASUSTek... | USB Audio                    | 4     | snd_usb... | 8F7011B085 |
| 0bda:485a | Realtek... | USB Audio                    | 4     | snd_usb... | 368BC3C902 |
| 0ccd:00c8 | TerraTe... | AUREON XFIRE8.0 HD           | 4     | snd_usb... | 6988796CAF |
| 0d8c:0319 | C-Media... | Schiit Modi Uber             | 4     | usbhid     | 1221B30469 |
| 0db0:0d64 | Micro S... | USB Audio                    | 4     | snd_usb... | 8ADB484D2C |
| 1397:00d4 | BEHRING... | X18/XR18                     | 4     | snd_usb... | FF3BA69D3E |
| 17cc:1330 | Native ... | Traktor Audio 2 MK2          | 4     | snd_usb... | 91BED95D04 |
| 19f7:000a | RODE Mi... | RODE AI-1                    | 4     | usbhid     | 274CBA3955 |
| 20b1:3066 | XMOS       | D30                          | 4     | snd_usb... | 54F1BB3FAF |
| 22e8:dac2 | Cambrid... | USB Audio 2.0                | 4     | snd_usb... | 5F07D88F75 |
| 30be:0101 | Schiit ... | Schiit Hel                   | 4     | snd_usb... | FCA4787959 |
| 041e:323a | Creativ... | Sound Blaster X7             | 3     | usbhid     | B95C1B013E |
| 041e:3f0a | Creativ... | E-MU Tracker Pre / USB       | 3     | snd_usb... | 548AFBB702 |
| 0499:172f | Yamaha     | Steinberg UR22C              | 3     | snd_usb... | 850A748733 |
| 04d2:ff05 | Altec L... | ADA-305 Speakers             | 3     |            | 9DA28A4AEC |
| 0644:8047 | TEAC       | US-16x08                     | 3     | snd_usb... | 197D61DE28 |
| 0763:4009 | M-Audio    | M-Track Plus                 | 3     | snd_usb... | 534EDD42C9 |
| 0b05:17cd | ASUSTek... | Xonar Essence STU            | 3     | snd_usb... | 6C9F9A3C6F |
| 0b05:1917 | ASUSTek... | USB Audio                    | 3     | usbhid     | AFD5F8B9B1 |
| 0bda:492f | Realtek... | TX 384kb Hifi Type_C Audio   | 3     | usbhid     | 32A3812CA0 |
| 0db0:7926 | Micro S... | USB2.0 High-Speed True HD... | 3     | snd_usb... | 17CE8C5436 |
| 1019:0013 | Elitegr... | FOSTEX USB AUDIO HP-A4       | 3     | snd_usb... | 612DDA8FBA |
| 1235:8012 | Focusri... | Scarlett 6i6                 | 3     | snd_usb... | 349F8DBE53 |
| 1235:8014 | Focusri... | Scarlett 18i8                | 3     | snd_usb... | 84A4C5E5E0 |
| 1235:8204 | Focusri... | Scarlett 18i8 2nd Gen        | 3     | snd_usb... | 433AA65798 |
| 1462:1171 | Micro S... | Xtreme Audio DAC             | 3     | usbhid     | A938950688 |
| 152a:85df | Thesyco... | SABAJ D4 v1.2                | 3     | snd_usb... | F0591914C5 |
| 154e:3005 | D&M Hol... | HD-DAC1                      | 3     | snd_usb... | 9DB6C930C1 |
| 17cc:1021 | Native ... | Traktor Audio 10             | 3     | snd_usb... | 0DA8004587 |
| 194f:0101 | PreSonu... | AudioBox 22 VSL              | 3     | snd_usb... | 8BDC39E3AB |
| 194f:0103 | PreSonu... | AudioBox 1818 VSL            | 3     | snd_usb... | 830633EFF6 |
| 20b1:0002 | XMOS       | USB Audio 2.0                | 3     | snd_usb... | E1E70C62DA |

### Bluetooth (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a12:0001 | Cambrid... | Bluetooth Dongle (HCI mode)  | 4111  | btusb      | 5C44D1E88B |
| 8087:0a2a | Intel      | Bluetooth wireless interface | 4060  | btusb      | 9834990221 |
| 8087:0a2b | Intel      | Bluetooth wireless interface | 3840  | btusb      | F45B082C14 |
| 8087:0aaa | Intel      | Bluetooth 9460/9560 Jeffe... | 3741  | btusb      | 2FC377709D |
| 8087:0029 | Intel      | AX200 Bluetooth              | 3428  | btusb      | F581CF8319 |
| 8087:07dc | Intel      | Bluetooth wireless interface | 2805  | btusb      | 36ACEDB60B |
| 8087:0026 | Intel      | AX201 Bluetooth              | 2491  | btusb      | EFDB9E6636 |
| 0cf3:3005 | Qualcom... | AR3011 Bluetooth             | 1217  | btusb      | EAF4F27F7A |
| 8087:0aa7 | Intel      | Wireless-AC 3168 Bluetooth   | 1212  | btusb      | C537345CE8 |
| 8087:07da | Intel      | Centrino Bluetooth Wirele... | 1127  | btusb      | 95C381CCD9 |
| 0cf3:3004 | Qualcom... | AR3012 Bluetooth 4.0         | 1070  | ath3k, ... | AC22E27954 |
| 04ca:3015 | Lite-On... | Qualcomm Atheros QCA9377 ... | 1004  | btusb      | CFA7B4AF8F |
| 8087:0025 | Intel      | Wireless-AC 9260 Bluetoot... | 922   | btusb      | 27E29303BC |
| 0cf3:e500 | Qualcom... | Qualcomm Atheros Bluetoot... | 890   | btusb      | 5154E96ABE |
| 0bda:b00a | Realtek... | Realtek Bluetooth 4.2 Ada... | 741   | btusb      | 3A06ECCCAA |
| 0cf3:e009 | Qualcom... | Qualcomm Atheros Bluetoot... | 652   | btusb      | 60F4AC8CC5 |
| 8086:0189 | Intel      | Centrino Advanced-N 6230 ... | 618   | btusb      | 41323F324C |
| 0bda:b009 | Realtek... | Realtek Bluetooth 4.2 Ada... | 600   | btusb      | F4D2F1104E |
| 0a5c:217f | Broadcom   | BCM2045B (BDC-2.1)           | 561   | btusb      | 570863FD8C |
| 0cf3:e300 | Qualcom... | QCA61x4 Bluetooth 4.0        | 549   | btusb      | 4E8A3E6A15 |
| 04ca:300b | Lite-On... | Atheros AR3012 Bluetooth     | 519   | ath3k, ... | 269771FE3E |
| 03f0:231d | Hewlett... | Broadcom 2070 Bluetooth C... | 458   | btusb      | 99FB47DC2B |
| 0cf3:0036 | Qualcom... | AR9462 Bluetooth             | 443   | ath3k, ... | 0F2394B49D |
| 0a5c:21e8 | Broadcom   | BCM20702A0 Bluetooth 4.0     | 437   | btusb      | 136C0BB900 |
| 03f0:171d | Hewlett... | Bluetooth 2.0 Interface [... | 436   | btusb      | AF8E63842A |
| 0cf3:e005 | Qualcom... | Qualcomm Atheros Bluetoot... | 422   | ath3k, ... | 5900E800AA |
| 0bda:b00b | Realtek... | Realtek Bluetooth 4.2 Ada... | 406   | btusb      | 6B8CF94EA2 |
| 0bda:c024 | Realtek... | Bluetooth Radio              | 382   | btusb      | 8DB63E7A74 |
| 0bda:b728 | Realtek... | RTL8723B Bluetooth           | 367   | btusb      | B76F24F640 |
| 0a5c:21e6 | Broadcom   | BCM20702 Bluetooth 4.0 [T... | 365   | btusb      | C9D8EFC9B9 |
| 413c:8187 | Dell       | DW375 Bluetooth Module       | 364   | btusb      | F442DF91A1 |
| 0b05:17cb | ASUSTek... | Broadcom BCM20702A0 Bluet... | 358   | btusb      | 35B5FCB787 |
| 13d3:3362 | IMC Net... | Atheros AR3012 Bluetooth ... | 339   | ath3k, ... | 58CC91ABA3 |
| 105b:e065 | Foxconn... | BCM43142A0 Bluetooth module  | 337   | btusb      | 0B6699ECD2 |
| 04ca:3016 | Lite-On... | Bluetooth Device             | 327   | btusb      | 66255CA7B5 |
| 0a5c:2101 | Broadcom   | BCM2045 Bluetooth            | 316   | btusb      | 7E2DA6D3E9 |
| 0cf3:e007 | Qualcom... | Qualcomm Atheros Bluetoot... | 307   | btusb      | DA5E2F59CC |
| 0a5c:219c | Broadcom   | BCM2070 Bluetooth Device     | 279   | btusb      | BBABC93B07 |
| 0489:e04e | Foxconn... | Bluetooth Device             | 278   | ath3k, ... | 7302DC6BE1 |
| 0a5c:21b4 | Broadcom   | BCM2070 Bluetooth 2.1 + EDR  | 275   | btusb      | F696958F46 |
| 0bda:b00c | Realtek... | Bluetooth Radio              | 274   | btusb      | 2BA5AE42BB |
| 13d3:3529 | IMC Net... | Bluetooth Radio              | 271   | btusb      | 67F0B45A7A |
| 0bda:0821 | Realtek... | RTL8821A Bluetooth           | 265   | btusb      | 2BF6813AD9 |
| 05ac:828f | Apple      | Bluetooth USB Host Contro... | 257   | apple_m... | 5BE083EDAB |
| 0bda:b721 | Realtek... | Bluetooth Radio              | 251   | btusb      | 4C2453C6A2 |
| 0cf3:e004 | Qualcom... | Bluetooth USB Host Contro... | 248   | ath3k, ... | D70E2B74D0 |
| 0bda:8771 | Realtek... | Bluetooth Radio              | 246   | btusb      | 22807CB857 |
| 0bda:b008 | Realtek... | Bluetooth Radio              | 246   | btusb      | 69C8804209 |
| 05ac:8215 | Apple      | Built-in Bluetooth 2.0+ED... | 239   | btusb      | BD1CB6F826 |
| 0bda:c123 | Realtek... | Bluetooth Radio              | 230   | btusb      | 497BF56CC6 |
| 0bda:b023 | Realtek... | RTL8822BE Bluetooth 4.2 A... | 226   | btusb      | 8272A05168 |
| 0a5c:216d | Broadcom   | BCM43142A0 Bluetooth 4.0     | 225   | btusb      | 65C122FE69 |
| 0a5c:21e1 | Broadcom   | HP Portable SoftSailing      | 218   | btusb      | C4C890F06A |
| 413c:8197 | Dell       | BCM20702A0 Bluetooth Module  | 218   | btusb      | FD1375D5F1 |
| 1358:c123 | Realtek    | Bluetooth Radio              | 208   | btusb      | 1310B8ABF4 |
| 0489:e00f | Foxconn... | Foxconn T77H114 BCM2070 [... | 201   | btusb      | 2D1739DC58 |
| 0489:e0a2 | Foxconn... | Bluetooth Device             | 198   | btusb      | 5A56854746 |
| 13d3:3496 | IMC Net... | Bluetooth Device             | 196   | btusb      | 680FCC27C4 |
| 0bda:b001 | Realtek... | Bluetooth Radio              | 192   | btusb      | 8D5A256374 |
| 04ca:3006 | Lite-On... | Bluetooth Device             | 182   | ath3k, ... | B953B67D06 |
| 0a5c:2145 | Broadcom   | BCM2045B (BDC-2.1) [Bluet... | 179   | btusb      | 9A7BE426F5 |
| 0cf3:311d | Qualcom... | Bluetooth                    | 174   | ath3k, ... | 595D5385BC |
| 0cf3:e360 | Qualcom... | Qualcomm Atheros Bluetoot... | 174   | btusb      | 68F1525BEF |
| 13d3:3526 | IMC Net... | Bluetooth Radio              | 173   | btusb      | 985D10D314 |
| 05ac:821a | Apple      | Bluetooth Host Controller    | 165   | btusb      | 6E17FB6EA4 |
| 13d3:3423 | IMC Net... | Bluetooth Device             | 164   | ath3k, ... | B96D5D5FDC |
| 0930:0508 | Toshiba    | Integrated Bluetooth HCI     | 163   | btusb      | 6A42C7BF7A |
| 0bda:b006 | Realtek... | Bluetooth Radio              | 162   | btusb      | 27D7E6D461 |
| 0489:e00d | Foxconn... | Broadcom Bluetooth 2.1 De... | 155   | btusb      | B2F7AB7E8A |
| 0a5c:21d7 | Broadcom   | BCM43142 Bluetooth 4.0       | 153   | btusb      | 13D221E327 |
| 05ac:8213 | Apple      | Bluetooth Host Controller    | 151   | btusb      | 80E0B6AF9E |
| 0a5c:21e3 | Broadcom   | HP Portable Valentine        | 148   | btusb      | 9CE9B3750D |
| 0b05:1712 | ASUSTek... | BT-183 Bluetooth 2.0+EDR ... | 143   | btusb      | 7A2E7C66E9 |
| 05ac:8205 | Apple      | Bluetooth HCI                | 142   | btusb      | 0346BC764A |
| 1286:204c | Marvell... | Bluetooth and Wireless LA... | 140   | btusb      | 6039985C3F |
| 0489:e036 | Foxconn... | Bluetooth USB Host Contro... | 139   | ath3k, ... | 7E20D79B1D |
| 0b05:1788 | ASUSTek... | BT-270 Bluetooth Adapter     | 139   | btusb      | EDEC5D042A |
| 413c:8160 | Dell       | Wireless 365 Bluetooth       | 139   | btusb      | 557421F62E |
| 0b05:1751 | ASUSTek... | BT-253 Bluetooth Adapter     | 133   | btusb      | 84F6267AD8 |
| 148f:1000 | Ralink ... | Motorola BC4 Bluetooth 3.... | 132   | btusb      | BA21DD1DD0 |
| 05ac:821d | Apple      | Bluetooth USB Host Contro... | 130   | btusb      | 783D081B5A |
| 0a5c:2110 | Broadcom   | BCM2045B (BDC-2) [Bluetoo... | 130   | btusb      | 87AAD99434 |
| 0cf3:e301 | Qualcom... | Qualcomm Atheros Bluetoot... | 128   | btusb      | 9CCE6740BE |
| 0a5c:21f1 | Broadcom   | HP Portable Bumble Bee       | 126   | btusb      | F8A7076D83 |
| 13d3:3491 | IMC Net... | Bluetooth Device             | 125   | btusb      | 02BA908575 |
| 8087:0032 | Intel      | AX210 Bluetooth              | 121   | btusb      | B9C2FEC8AA |
| 0bda:b002 | Realtek... | Bluetooth Radio              | 120   | btusb      | DB30D4A4D6 |
| 0a5c:216c | Broadcom   | BCM43142A0 Bluetooth Device  | 118   | btusb      | D932AC65A5 |
| 05ac:8289 | Apple      | Bluetooth Host Controller    | 117   | btusb      | 0C24CAF245 |
| 413c:8126 | Dell       | Wireless 355 Bluetooth       | 117   | btusb      | A9BA9DF656 |
| 0489:e078 | Foxconn... | Bluetooth Device             | 114   | ath3k, ... | 470C0932AE |
| 13d3:3394 | IMC Net... | Bluetooth                    | 110   | btusb      | 532FD196D0 |
| 0930:021d | Toshiba    | RT Bluetooth Radio           | 109   | btusb      | BB9C65380C |
| 04ca:2006 | Lite-On... | Broadcom BCM43142A0 Bluet... | 107   | btusb      | A0E3E93F48 |
| 05ac:828d | Apple      | Bluetooth USB Host Contro... | 107   | btusb      | B8A7B6080F |
| 044e:3017 | Alps El... | BCM2046 Bluetooth Device     | 106   | btusb      | 87BD2C1CBF |
| 0b05:185c | ASUSTek... | Bluetooth Radio              | 104   | btusb      | DE600DC6CC |
| 413c:8140 | Dell       | Wireless 360 Bluetooth       | 103   | btusb      | 55832DD912 |
| 0cf3:3121 | Qualcom... | Qualcomm Atheros Bluetoot... | 101   | ath3k, ... | E2B0881704 |
| 05ac:8290 | Apple      | Bluetooth Host Controller    | 100   | btusb      | F69B01435F |

### Camera (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:0825 | Logitech   | Webcam C270                  | 1003  | snd_usb... | CF2BC09886 |
| 04e8:6860 | Samsung... | Galaxy A5 (MTP)              | 664   | usbfs      | 71F0D8F5BB |
| 046d:082d | Logitech   | HD Pro Webcam C920           | 555   | snd_usb... | C537345CE8 |
| 05ac:12a8 | Apple      | iPhone 5/5C/5S/6/SE          | 541   | ipheth     | 02E94E7CD4 |
| 13d3:5a11 | IMC Net... | USB2.0 VGA UVC WebCam        | 525   | uvcvideo   | 67F0B45A7A |
| 13d3:56a2 | IMC Net... | USB2.0 HD UVC WebCam         | 388   | uvcvideo   | 3802A77D98 |
| 13d3:5a01 | IMC Net... | USB2.0 VGA UVC WebCam        | 373   | uvcvideo   | 4A93747ED1 |
| 0ac8:3420 | Z-Star ... | Venus USB2.0 Camera          | 367   | uvcvideo   | 3ABF73FB8A |
| 064e:a103 | Suyin      | Acer/HP Integrated Webcam... | 349   | uvcvideo   | 9B324D7185 |
| 0408:a031 | Quanta     | VGA WebCam                   | 346   | uvcvideo   | 06114B7EB7 |
| 04f2:b604 | Chicony... | Integrated Camera (1280x7... | 338   | uvcvideo   | EEB181F50B |
| 0c45:6723 | Microdia   | Integrated_Webcam_HD         | 332   | uvcvideo   | 58E43F0514 |
| 5986:2113 | Acer       | SunplusIT Integrated Camera  | 317   | uvcvideo   | 7555BBD3C1 |
| 0408:a061 | Quanta     | HD User Facing               | 314   | uvcvideo   | F581CF8319 |
| 058f:5608 | Alcor M... | USB 2.0 Web Camera           | 298   | uvcvideo   | 2FBF6F153B |
| 04f2:b64f | Chicony... | HD User Facing               | 297   | uvcvideo   | 7463FACB20 |
| 05ac:8509 | Apple      | FaceTime HD Camera           | 289   | uvcvideo   | 6E17FB6EA4 |
| 1bcf:2c18 | Sunplus... | HD WebCam                    | 281   | uvcvideo   | D2A5CA4ACA |
| 0408:a060 | Quanta     | HD Webcam                    | 267   | uvcvideo   | 4150C71628 |
| 5986:0295 | Acer       | Lenovo Integrated Webcam     | 266   | uvcvideo   | 779684E41D |
| 046d:081b | Logitech   | Webcam C310                  | 257   | snd_usb... | AD0E1A0525 |
| 0c45:62c0 | Microdia   | Sonix USB 2.0 Camera         | 253   | uvcvideo   | 24833C6A59 |
| 1bcf:2883 | Sunplus... | Asus Webcam                  | 250   | uvcvideo   | 7332DA68EC |
| 05ac:8507 | Apple      | Built-in iSight              | 247   | uvcvideo   | 80E0B6AF9E |
| 0c45:6340 | Microdia   | Camera                       | 247   | snd_usb... | D3A9F1CE6E |
| 0402:9665 | ALi        | Gateway Webcam               | 243   | uvcvideo   | 55BA94A26E |
| 13d3:56b2 | IMC Net... | Integrated Camera            | 243   | uvcvideo   | EF7D0F49E1 |
| 046d:0826 | Logitech   | HD Webcam C525               | 234   | uvcvideo   | 36BF6DAB37 |
| 058f:a014 | Alcor M... | Asus Integrated Webcam       | 230   | uvcvideo   | E838F0C769 |
| 04f2:b230 | Chicony... | Integrated HP HD Webcam      | 227   | uvcvideo   | B6AC4539D1 |
| 0408:5365 | Quanta     | HP TrueVision HD Camera      | 223   | uvcvideo   | C227DAEA26 |
| 04f2:b47f | Chicony... | VGA Webcam                   | 222   | uvcvideo   | B943E3347D |
| 04f2:b52b | Chicony... | USB2.0 VGA UVC WebCam        | 219   | uvcvideo   | 9B382500C5 |
| 13d3:5710 | IMC Net... | UVC VGA Webcam               | 218   | uvcvideo   | 011079F499 |
| 046d:082b | Logitech   | Webcam C170                  | 216   | snd_usb... | 58DFAE44E0 |
| 04f2:b217 | Chicony... | Lenovo Integrated Camera ... | 214   | uvcvideo   | 90895AAB86 |
| 04f2:b1d6 | Chicony... | CNF9055 Toshiba Webcam       | 211   | uvcvideo   | 5576D0D6C5 |
| 05ac:8502 | Apple      | Built-in iSight              | 210   | uvcvideo   | BD1CB6F826 |
| 0bda:57b5 | Realtek... | USB Camera                   | 206   | uvcvideo   | 4C2453C6A2 |
| 13d3:5130 | IMC Net... | Integrated Webcam            | 204   | uvcvideo   | 0EEDFC8A67 |
| 0c45:6366 | Microdia   | Webcam Vitade AF             | 203   | snd_usb... | 95616813E6 |
| 04ca:7070 | Lite-On... | Integrated Camera            | 201   | uvcvideo   | F7309EF31A |
| 2232:1020 | Silicon... | WebCam SC-0311139N           | 200   | uvcvideo   | A83E302ABA |
| 0c45:671e | Microdia   | Integrated_Webcam_HD         | 197   | uvcvideo   | 60F4AC8CC5 |
| 045e:0779 | Microsoft  | LifeCam HD-3000              | 193   | snd_usb... | C0FB875CA5 |
| 13d3:56dd | IMC Net... | USB2.0 HD UVC WebCam         | 193   | uvcvideo   | 823C6074D8 |
| 04f2:b071 | Chicony... | 2.0M UVC Webcam / CNF7129    | 191   | uvcvideo   | FFB279A366 |
| 5986:0652 | Acer       | Lenovo EasyCamera            | 185   | uvcvideo   | 37A983C1E7 |
| 04f2:b008 | Chicony... | USB 2.0 Camera               | 181   | uvcvideo   | 01EB2C3459 |
| 04f2:b61e | Chicony... | Integrated Camera            | 180   | uvcvideo   | 72617E5DD9 |
| 0ac8:c40a | Z-Star ... | A4 TECH USB2.0 PC Camera J   | 173   | uvcvideo   | B9DEC327EE |
| 13d3:5188 | IMC Net... | USB2.0 UVC HD Webcam         | 172   | uvcvideo   | 5369ACA258 |
| 5986:2115 | Acer       | Integrated Camera            | 171   | uvcvideo   | 00AC329183 |
| 04f2:b5c5 | Chicony... | HD WebCam                    | 170   | uvcvideo   | 8C3B4736CD |
| 0bda:57de | Realtek... | USB2.0 VGA UVC WebCam        | 169   | uvcvideo   | 02BA908575 |
| 0bda:57b3 | Realtek... | Acer 640 x 480 laptop camera | 168   | uvcvideo   | AA7DD43B73 |
| 13d3:56a6 | IMC Net... | Integrated Camera            | 168   | uvcvideo   | 3FC424B8C6 |
| 2232:1008 | Silicon... | WebCam SCB-1100N             | 167   | uvcvideo   | D8167A915B |
| 04f2:b221 | Chicony... | integrated camera            | 165   | uvcvideo   | A75FFD5203 |
| 064e:a219 | Suyin      | 1.3M WebCam (notebook ema... | 165   | uvcvideo   | 1427EBFFB0 |
| 046d:085c | Logitech   | C922 Pro Stream Webcam       | 162   | snd_usb... | CA3C48F689 |
| 04f2:b469 | Chicony... | HD WebCam                    | 161   | uvcvideo   | 98323BE6F8 |
| 04f2:b52d | Chicony... | HP Webcam                    | 160   | uvcvideo   | 5614E34F51 |
| 04f2:b40a | Chicony... | USB2.0 HD UVC WebCam         | 158   | uvcvideo   | 3498166FA2 |
| 04f2:b39a | Chicony... | Integrated Camera            | 157   | uvcvideo   | 5026826DBE |
| 04f2:b5e0 | Chicony... | VGA WebCam                   | 157   | uvcvideo   | E348A818BD |
| 064e:a101 | Suyin      | Acer CrystalEye Webcam       | 156   | uvcvideo   | 8592F1650F |
| 1210:25f4 | DigiTech   | USB 2.0 PC Camera            | 156   | uvcvideo   | CF2BC09886 |
| 2232:1029 | Silicon... | WebCam SC-13HDL11939N        | 156   | uvcvideo   | 95C381CCD9 |
| 0bda:565a | Realtek... | Integrated_Webcam_HD         | 155   | uvcvideo   | DA5E2F59CC |
| 1bcf:28c1 | Sunplus... | Integrated_Webcam_HD         | 155   | uvcvideo   | C01FA4B013 |
| 05ac:8511 | Apple      | FaceTime HD Camera (Built... | 153   | uvcvideo   | CA3C48F689 |
| 04f2:b40e | Chicony... | HP Truevision HD camera      | 150   | uvcvideo   | AB5E53C9ED |
| 0ac8:3450 | Z-Star ... | Vimicro USB Camera (Altair)  | 150   | uvcvideo   | 42CFC0C15A |
| 0bda:568a | Realtek... | Integrated Webcam            | 149   | uvcvideo   | 19F7BA4A63 |
| 046d:082c | Logitech   | HD Webcam C615               | 148   | uvcvideo   | D3A4772E4E |
| 13d3:5a07 | IMC Net... | VGA UVC WebCam               | 148   | uvcvideo   | EED2A8B965 |
| 13d3:5a02 | IMC Net... | EasyCamera                   | 146   | uvcvideo   | 4EB6B00CAC |
| 04f2:b1d8 | Chicony... | 1.3M Webcam                  | 144   | uvcvideo   | BCEF8C44A6 |
| 05c8:036e | Cheng U... | Webcam                       | 142   | uvcvideo   | 22807CB857 |
| 2232:1080 | Silicon... | Web Camera                   | 142   | uvcvideo   | F3400508FB |
| 0c45:64ad | Microdia   | Dell Laptop Integrated We... | 140   | uvcvideo   | 0F2394B49D |
| 04f2:b5f7 | Chicony... | HD WebCam                    | 138   | uvcvideo   | E4762B54F7 |
| 04f2:b685 | Chicony... | USB2.0 Camera                | 138   | uvcvideo   | 435743B201 |
| 05a9:2640 | OmniVis... | OV2640 Webcam                | 138   | uvcvideo   | A9BA9DF656 |
| 0bda:5689 | Realtek... | Integrated Webcam            | 138   | uvcvideo   | 141148EC26 |
| 0c45:671d | Microdia   | Integrated_Webcam_HD         | 138   | uvcvideo   | 0FA8C3ED0C |
| 13d3:5702 | IMC Net... | UVC VGA Webcam               | 138   | uvcvideo   | E74DC83F0A |
| 5986:9102 | Acer       | BisonCam,NB Pro              | 138   | uvcvideo   | A16445083C |
| 04f2:b044 | Chicony... | Acer CrystalEye Webcam       | 136   | uvcvideo   | 7095848F26 |
| 13d3:5666 | IMC Net... | USB2.0 HD UVC WebCam         | 136   | uvcvideo   | 8A5F05E4C1 |
| 13d3:56ff | IMC Net... | Integrated Camera            | 136   | uvcvideo   | 8D45D9544E |
| 04f2:b374 | Chicony... | HD WebCam                    | 135   | uvcvideo   | 167DA11BB6 |
| 04f2:b446 | Chicony... | TOSHIBA Web Camera - HD      | 135   | uvcvideo   | 8D16328DFD |
| 04f2:b67c | Chicony... | Integrated Camera            | 134   | uvcvideo   | 3517455DF5 |
| 17ef:480f | Lenovo     | Integrated Webcam [R5U877]   | 134   | uvcvideo   | 8B21B7CFFE |
| 05c8:021e | Cheng U... | HP Webcam-101                | 133   | uvcvideo   | 9CE9B3750D |
| 0bda:58c2 | Realtek... | Integrated Webcam HD         | 133   | uvcvideo   | B0F6309320 |
| 04f2:b272 | Chicony... | Lenovo EasyCamera            | 131   | uvcvideo   | D1D57448C4 |
| 04f2:b6d9 | Chicony... | Integrated Camera            | 131   | uvcvideo   | A35AAAEB6D |

### Card reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:0129 | Realtek... | RTS5129 Card Reader Contr... | 7818  | rtsx_usb   | 4A93747ED1 |
| 0bda:0139 | Realtek... | RTS5139 Card Reader Contr... | 830   | rtsx_usb   | 16EBDC4388 |
| 17ef:a38f | Lenovo     | Billboard Device             | 38    | usbhid     | 3FC424B8C6 |
| 0aec:3260 | Neodio ... | 7-in-1 Card Reader           | 30    | uas, us... | 7223BFA184 |
| 17ef:3075 | Lenovo     | USB Billboard Device         | 28    |            | E9A8FB1275 |
| 04b4:521a | Cypress... | USB-I2C Bridge               | 27    |            | 2D80988DDC |
| 0c4b:0500 | Reiner ... | cyberJack RFID standard d... | 19    | usbfs      | 66A1F3F644 |
| 0c4b:0501 | Reiner ... | cyberJack RFID comfort du... | 19    | usbfs      | C408319996 |
| 04b4:5218 | Cypress... | USB-Serial Bridge            | 18    |            | E16A18BC8B |
| 072f:9000 | Advance... | ACR38 AC1038-based Smart ... | 16    | usbfs      | ECD7EC8F36 |
| 0d8c:5200 | C-Media... | Mass Storage Controller(0... | 13    |            | 8496A00774 |
| 0cf2:6250 | ENE Tec... | SD card reader (UB6250)      | 11    | ums_ene... | 2B59C324E6 |
| 0b97:7732 | O2 Micro   | Smart Card Reader            | 8     |            | 369B39D1BE |
| 0ca6:0010 | Castles... | EZUSB PC/SC Smart Card Re... | 8     | usbfs      | 839B20476A |
| 04e6:e003 | SCM Mic... | SPR532 PinPad SmartCard R... | 4     | usbfs      | 842C53B8E2 |
| 0b0c:003f | Todos AB   | Todos C400 smartcard cont... | 4     |            | 7A6F9E9890 |
| 17ef:3078 | Lenovo     | USB Billboard                | 4     |            | 13078A648E |
| 04e6:512b | SCM Mic... | SDI011 Contactless Reader    | 3     |            | 7CF3758630 |
| 04e6:5810 | SCM Mic... | uTrust 2700 R Smart Card ... | 3     | usbfs      | 0AAB60DBC8 |
| 0bda:0150 | Realtek... | Realtek USB 2.0 Card Reader  | 3     | usb_sto... | 30591F341D |
| 11c5:0521 | Inmax      | IMT-0521 Smartcard Reader    | 3     |            | 9B2FCCD56C |
| 174f:1105 | Syntek     | SM-MS/Pro-MMC-XD Card Reader | 3     | uvcvideo   | B0B1659E5A |
| 2ce3:9563 |            | EMV Smartcard Reader         | 3     |            | 60D38664EE |
| 04e6:511a | SCM Mic... | SCR3310-NTTCom USB SmartC... | 2     | usbfs      | A5B2555CC2 |
| 062d:0001 | Taiwan ... | Smart Card Reader            | 2     | usbfs      | DD8F32A8D6 |
| 076b:0596 | OmniKey    | CardMan 2020                 | 2     |            | 517A612C58 |
| 047b:020b | Silitek    | SK-3105 SmartCard Reader     | 1     | usbhid     | 986AC800BA |
| 04e6:5151 | SCM Mic... | SCR338 Keyboard Smart Car... | 1     | usbhid     | BD73A86E1F |
| 0c45:1018 | Microdia   | Compact Flash storage mem... | 1     |            | 696C2127B6 |
| 1667:001a | GIGA-TMS   | MagStripe Card Reader        | 1     | usbhid     | F40A4B7BAC |

### Cdrom (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0e8d:1887 | MediaTek   | Slim Portable DVD Writer     | 250   | usb_sto... | 86F08832C0 |
| 174c:1153 | ASMedia... | ASM1153 SATA 3Gb/s bridge    | 178   | uas, us... | E58D33DF6B |
| 0e8d:1806 | MediaTek   | Samsung SE-208 Slim Porta... | 147   | usb_sto... | 6988796CAF |
| 1c6b:a223 | Philips... | DVD Writer Slimtype eUAU108  | 111   | usb_sto... | 99B9973F19 |
| 0e8d:1836 | MediaTek   | Samsung SE-S084 Super Wri... | 59    | usb_sto... | D19235C3D0 |
| 13fd:3940 | Initio     | external DVD burner ECD81... | 54    | uas, us... | AB5CCB23B0 |
| 174c:1351 | ASMedia... | DVDRW DA8AESH                | 47    | uas, us... | 2E3861AEF3 |
| 152e:1640 | LG (HLDS)  | INIC-1605 SATA Bridge        | 42    | usb_sto... | 91B89EEBF6 |
| 0928:0010 | PLX Tec... | Virtual CDRom                | 38    | uas, us... | 7132BCC66D |
| 152e:2507 | LG (HLDS)  | PL-2507 IDE Controller       | 37    | uas, us... | 7FFBFD1E5A |
| 19d2:1403 | ZTE WCD... | USB SCSI CD-ROM              | 37    | uas, us... | 3B43D9B42F |
| 0b05:7774 | ASUSTek... | Zenfone GO (ZB500KL) (RND... | 32    | rndis_host | 0B6699ECD2 |
| 08e4:017a | Pioneer    | BD-RW BDR-XD05               | 28    | usb_sto... | 0981774043 |
| 14cd:6600 | Super Top  | M110E PATA bridge            | 26    | usb_sto... | CE0DCC0424 |
| 13fd:0940 | Initio     | ASUS SBW-06D2X-U             | 24    | uas, us... | 18591F972C |
| 13fd:2040 | Initio     | Samsung Writemaster exter... | 24    | usb_sto... | B0391F5E3B |
| 2a70:f003 | OnePlus... | Device Driver                | 24    | uas, us... | 514642D183 |
| 2e04:c025 | HMD Global | Nokia 8 (MTP mode)           | 21    | uas, us... | CCC49B1CD4 |
| 0e8d:1956 | MediaTek   | Samsung SE-506 Portable B... | 20    | usb_sto... | A0B7D0CF25 |
| 13fd:0842 | Initio     | CDDVDW SE-S084C              | 19    | usb_sto... | EF16468238 |
| 12d1:107f | Huawei ... | File-CD Gadget               | 18    | uas, us... | 6914386D3D |
| 12d1:1082 | Huawei ... | File-CD Gadget               | 17    | usb_sto... | 1345E7109D |
| 054c:02d5 | Sony       | DVD-RAM UJ-852S              | 16    | uas, us... | 972677CEAB |
| 19d2:1410 | ZTE WCD... | USB SCSI CD-ROM              | 16    | uas, us... | 27CC77A565 |
| 413c:9016 | Dell       | DVD+/-RW DW316               | 16    | usb_sto... | 3A45F51266 |
| 534d:6021 | MacroSi... | VGA Display Adapter          | 15    | snd_usb... | 394501AB2E |
| 05e3:0719 | Genesys... | SATA adapter                 | 13    | uas, us... | DFA0ED56AB |
| 067b:2571 | Prolifi... | LG Electronics GE24LU21      | 12    | uas, us... | 94313FAA27 |
| 12d1:107d | Huawei ... | File-CD Gadget               | 12    | rndis_host | 71C19B42FC |
| 067b:2506 | Prolifi... | Kaser 8gB micro hard drive   | 11    | uas, us... | A392DD59EB |
| 0930:0c05 | Toshiba    | DVD-RAM UJ-844S              | 11    | usb_sto... | B7B8ADEDEE |
| 04e8:685b | Samsung... | GT-I9100 Phone [Galaxy S ... | 10    | uas, us... | C8821B395F |
| 054c:0377 | Sony       | BD-MLT UJ-220S               | 10    | uas, us... | 76C6658153 |
| 0e8d:1807 | MediaTek   | DVDRAM GP40NB40              | 10    | usb_sto... | 9343A7AAC0 |
| 14dd:0002 | Raritan... | Multidevice                  | 10    | usbhid     | B38D253458 |
| 05c6:9039 | Qualcomm   | Android                      | 9     | usbfs      | 954005CA3D |
| 067b:2771 | Prolifi... | BD-RE BE14NU40               | 9     | uas, us... | 314859D762 |
| 13fd:0841 | Initio     | Samsung SE-T084M DVD-RW      | 9     | usb_sto... | 18164956AF |
| 0409:0056 | NEC Com... | CD/DVDW SH-S162L             | 8     | usb_sto... | C6C9F72F10 |
| 0411:01dc | BUFFALO    | Ultra-Slim Portable DVD W... | 8     | usb_sto... | F6A1AECE80 |
| 05c6:f000 | Qualcomm   | Device Driver                | 8     | uas, us... | 4404093CCF |
| 05e3:0701 | Genesys... | USB 2.0 IDE Adapter          | 8     | usb_sto... | 0CFD20F720 |
| 0718:4006 | Imation    | 8x Slim DVD Multi-Format ... | 7     | usb_sto... | E94BEE6137 |
| 0ecd:a100 | Lite-On IT | LDW-411SX DVD/CD Rewritab... | 7     | uas, us... | D7A1EAA74F |
| 1c6b:d002 | Philips... | ES1                          | 7     | usb_sto... | 7FA4A7BF63 |
| 0bb4:0f25 | HTC (Hi... | One M8                       | 6     | uas, us... | AC8EEC8267 |
| 12d1:1052 | Huawei ... | MT7-L09 / P7-L10 / Y330-U01  | 6     | uas, us... | 2ABA1A12DD |
| 17ef:730a | Lenovo     | Ultraslim DVD                | 6     | usb_sto... | 6E2B20FD64 |
| 2e04:c026 | HMD Global | Nokia Smartphone             | 6     | uas, us... | C3FC416C61 |
| 0476:059b | AESP       | CDDVDW SN-S083C              | 5     | uas, us... | D8383576CC |
| 054c:03dc | Sony       | DVD RW DRX-S70U              | 5     | uas, us... | 8E54A49F9F |
| 0ea0:1111 | Ours Te... | Virtual CDROM                | 5     | uas, us... | 8D4CBF243D |
| 0411:02af | BUFFALO    | BD-RW BDR-209M               | 4     | usb_sto... | F5A10112C1 |
| 060f:1007 | Joinsoo... | DVDRAM GT80N                 | 4     | usb_sto... | 504F3BB1BF |
| 0fe6:9702 | ICS Advent | Supereal VR DISK             | 4     | uas, us... | 34D2F87751 |
| 1782:5d03 | Spreadt... | File-CD Gadget               | 4     | uas, us... | 0D165C08F9 |
| 18a5:0414 | Verbatim   | BD-RW BDR-UD03               | 4     | usb_sto... | 4FD0C6F1DC |
| 19d2:0504 | ZTE WCD... | File-CD Gadget               | 4     | uas, us... | 9F6FBAF237 |
| 1c6b:d005 | Philips... | EB1                          | 4     | usb_sto... | 49272ED382 |
| 1e91:de2c | Other W... | DRW-22B1LT                   | 4     | usb_sto... | A0D316EB3E |
| 03f0:2027 | Hewlett... | Virtual DVD-ROM              | 3     | usb_sto... | 55A7B7EC76 |
| 0489:c001 | Foxconn... | File-CD Gadget               | 3     | uas, us... | 2DCD0E4E69 |
| 04b3:4012 | IBM        | Virtual Media                | 3     | uas, us... | 8538814CD6 |
| 059f:0663 | LaCie      | CD/DVDW SH-S182M             | 3     | uas, us... | 0BC409E14C |
| 05c6:92fe | Qualcomm   | Disk                         | 3     | uas, us... | D06E1D8C5B |
| 08f2:6811 | Gotop I... | SZ)                          | 3     | usb_sto... | 11EBF2008B |
| 097f:097f | Barun E... | DVDRW DU8AESH                | 3     | uas, us... | 0D914665C3 |
| 0b05:7780 | ASUSTek... | Device CD-ROM                | 3     | usb_sto... | FCC9DABB3D |
| 103c:8431 | hp PLDS    | DVDRW DU8AESH                | 3     | uas, us... | 9FDCC0F2AF |
| 12d1:2608 | Huawei ... | File-CD Gadget               | 3     | uas, us... | 96188348AE |
| 13fd:1140 | Initio     | DVD-RAM UJ-852S              | 3     | usb_sto... | EA812BCD70 |
| 17ef:b005 | Lenovo     | /mnt/VM0/smolens             | 3     | uas, us... | 543E694E42 |
| 19d2:1557 | ZTE WCD... | MTS Mobile Boardband         | 3     | cdc_ether  | 06AF94BA2D |
| 1ebf:707d | Linux      | File-CD Gadget               | 3     | usb_sto... | 1C59D4F975 |
| 0411:01ec | BUFFALO    | BD-RW BDR-TD04               | 2     | usb_sto... | 2F7D7BBB1D |
| 0451:9261 | Texas I... | DVD+-RW GU90N                | 2     | uas, us... | 362307C0B1 |
| 059b:0155 | Iomega     | CDW/DVD TS-H492A             | 2     | uas, us... | 3EE5BD924C |
| 059b:0252 | Iomega     | Optical                      | 2     | uas, us... | 2ED92032E0 |
| 059f:0363 | LaCie      | DVD_RW ND-3500AG             | 2     | usb_sto... | 8ECBD29ABD |
| 05e3:0627 | Genesys... | CD-ROM DEVICE                | 2     | usb_sto... | 319CE0E306 |
| 0789:0197 | Logitec    | DVDRAM GP67N                 | 2     | usb_sto... | 266D78E723 |
| 07ab:fcdf | Freecom... | DVD+/-RW20J5                 | 2     | usb_sto... | 6D0120C876 |
| 08e4:013e | Pioneer    | DVD-RW DVR-112               | 2     | uas, us... | C17C4C65D5 |
| 08e4:0193 | Pioneer    | DVD-RW DVR-XT11              | 2     | uas, us... | 46250D420A |
| 0930:0c06 | Toshiba    | SuperMultiPA3761             | 2     | usb_sto... | D49249D475 |
| 093b:004a | PLEXTOR    | DVDR PX-L611U                | 2     | uas, us... | E6F737276C |
| 0b05:1797 | ASUSTek... | DVDRAM GU60N                 | 2     | usb_sto... | E2A6782664 |
| 0ecd:40c0 | Lite-On IT | DVDRW SSM-85H5S              | 2     | uas, us... | 3751D2399E |
| 12d1:1078 | Huawei ... | File-CD Gadget               | 2     | uas, us... | 69E46089D9 |
| 1410:6000 | Novatel... | Mass Storage                 | 2     | option,... | 45AEF7A11F |
| 174c:7720 | ASMedia... | BD-RW BDR-212M               | 2     | uas, us... | E46DB68DA5 |
| 17ef:7302 | Lenovo     | USB_DVD_Burner5              | 2     | usb_sto... | A6DCDFAB33 |
| 17ef:7306 | Lenovo     | Slim_USB_Burner              | 2     | usb_sto... | 0974C365AB |
| 1c6b:a120 | Philips... | DVD+-RW DX-20A6Q             | 2     | usb_sto... | B157FE7CA5 |
| 2009:7638 | iStorage   | Fingerprint                  | 2     | uas, us... | 910CE6A9D9 |
| 413c:9001 | Dell       | ATA Bridge                   | 2     | uas, us... | 8CEA54AABF |
| a2a6:7825 | HL-DT-ST   | BD-RE WH16NS40               | 2     | usb_sto... | 24515EE809 |
| 03f0:0656 | Hewlett... | DVDRW GUD1N                  | 1     | uas, us... | 354CEB04D4 |
| 03f0:1207 | Hewlett... | DVD Writer 840d              | 1     | uas, us... | DF9CBAA879 |
| 03f0:1807 | Hewlett... | DVD Writer 1040d             | 1     | uas, us... | 02D0E7EF6E |

### Chipcard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 058f:9540 | Alcor M... | AU9540 Smartcard Reader      | 1097  | usbfs      | 11CD74E647 |
| 0a5c:5800 | Broadcom   | BCM5880 Secure Applicatio... | 889   | usbfs      | F442DF91A1 |
| 0a5c:5801 | Broadcom   | BCM5880 Secure Applicatio... | 358   | usbfs      | BA51FC9216 |
| 0b97:7772 | O2 Micro   | OZ776 CCID Smartcard Reader  | 332   | usbfs      | 4639F065C8 |
| 17ef:1003 | Lenovo     | Integrated Smart Card Reader | 294   | usbfs      | C9D8EFC9B9 |
| 147e:2020 | Upek       | TouchChip Fingerprint Cop... | 293   | usbfs      | 69A252CCD6 |
| 0a5c:5832 | Broadcom   | 5880                         | 216   | usbfs      | 3D0FD285B6 |
| 0a5c:5843 | Broadcom   | 58200                        | 210   | usbfs      | 20266B5994 |
| 0a5c:5834 | Broadcom   | 5880                         | 200   | usbfs      | D926705B17 |
| 0a5c:5804 | Broadcom   | BCM5880 Secure Applicatio... | 71    | usbfs      | 9834990221 |
| 0a5c:5842 | Broadcom   | 58200                        | 69    | usbfs      | F4B1EFA60F |
| 0b97:7762 | O2 Micro   | Oz776 SmartCard Reader       | 64    |            | ED344B9346 |
| 08e6:3437 | Gemalto... | GemPC Twin SmartCard Reader  | 36    | usbfs      | E1358C7C92 |
| 072f:90cc | Advance... | ACR38 SmartCard Reader       | 29    | usbfs      | 9D1EF122F7 |
| 0529:0620 | Aladdin... | Token JC                     | 28    | usbfs      | 754CD1A0C0 |
| 058f:9520 | Alcor M... | Watchdata W 1981             | 27    | usbfs      | 1F91E82C9F |
| 08e6:34ec | Gemalto... | Compact Smart Card Reader... | 26    | usbfs      | 04F114FB0F |
| 0bda:0165 | Realtek... | Smart Card Reader Interface  | 25    | usbfs      | ECF2D90F81 |
| 0a5c:5802 | Broadcom   | BCM5880 Secure Applicatio... | 21    | usbfs      | 18591F972C |
| 04e6:5116 | SCM Mic... | SCR331-LC1 / SCR3310 Smar... | 19    | usbfs      | 0B28226CB5 |
| 076b:3021 | OmniKey    | CardMan 3021 / 3121          | 18    | usbfs      | F17090E5D2 |
| 1050:0406 | Yubico.com | Yubikey 4/5 U2F+CCID         | 15    | usbfs      | 711F2B9E6D |
| 04e6:5119 | SCM Mic... | SCR3340 - ExpressCard54 S... | 13    | usbfs      | ABCF2EEE75 |
| 04f2:1469 | Chicony... | HP Skylab USB Smartcard K... | 12    | usbhid     | 5517C4780D |
| 076b:1021 | OmniKey    | CardMan 1021                 | 12    | usbfs      | 326B3F5892 |
| 03f0:164a | Hewlett... | SC Keyboard - Apollo (Lit... | 11    | usbhid     | 427C8B8D8F |
| 1a44:0001 | VASCO D... | Digipass 905 SmartCard Re... | 11    | usbfs      | 6E6AC0F1B7 |
| 25dd:3111 | BIT4ID     | miniLector EVO               | 11    | usbfs      | BD51F8A0AE |
| 072f:2200 | Advance... | ACR122U                      | 10    | pn533_usb  | 3B93E825DE |
| 20a0:4108 | Clay Logic | Nitrokey Pro                 | 10    | usbhid     | 60B4C707AD |
| 046a:00a1 | Cherry     | SmartCard Reader Keyboard... | 9     | usbhid     | 49272ED382 |
| 076b:4321 | OmniKey    | CardMan 4321                 | 9     | usbfs      | 6C14033E55 |
| 0a89:0025 | Aktiv      | Rutoken lite                 | 8     | usbfs      | B2AA6B2D66 |
| 0dc3:1004 | Athena ... | ASEDrive CCID                | 8     | usbfs      | 83C276AE69 |
| 1050:0111 | Yubico.com | Yubikey NEO(-N) OTP+CCID     | 8     | usbhid     | 2E706CD74A |
| 24dc:0101 | ARDS       | JaCarta                      | 7     | usbfs      | 4D5E452411 |
| 04e6:5410 | SCM Mic... | SCR35xx Smart Card Reader    | 6     | usbfs      | 09CFE58582 |
| 04e6:e001 | SCM Mic... | SCR331 SmartCard Reader      | 6     | usbfs      | B5A0F60525 |
| 08e6:3438 | Gemalto... | GemPC Key SmartCard Reader   | 6     | usbfs      | 10434415D8 |
| 0a5c:5805 | Broadcom   | 5880                         | 6     |            | E306044D0C |
| 0bf8:1006 | Fujitsu... | SmartCard Reader 2A          | 6     | usbfs      | 0C5E4A2345 |
| 0c4b:9102 | Reiner ... | cyberJack RFID basis cont... | 6     | usbfs      | 948DD41AC2 |
| 1a44:0870 | VASCO D... | DIGIPASS 870                 | 6     | usbfs      | 4C88B83358 |
| 0a5c:5833 | Broadcom   | 5880                         | 5     |            | 0CBB50CF63 |
| 1059:0017 | Gieseck... | StarSign CUT                 | 5     | usbfs      | D4931747CA |
| 1059:0019 | Gieseck... | StarSign CUT S               | 5     | usbfs      | 25C060DD59 |
| 04e6:5115 | SCM Mic... | SCR335 SmartCard Reader      | 4     | usbfs      | CF54F0B6EC |
| 072f:b100 | Advance... | ACR39U                       | 4     | usbfs      | 4BC5EB3BBC |
| 0c4b:0580 | Reiner ... | cyberJack one                | 4     |            | 641E5EEB2A |
| 163c:0407 | Watchdata  | USB Key                      | 4     | usbfs      | 7E1580D21A |
| 20a0:4211 | Clay Logic | Nitrokey Start               | 4     | usbfs      | D180569750 |
| 046a:0070 | Cherry     | SmartTerminal XX1X           | 3     | usbfs      | D6668FF825 |
| 058c:9590 | In Focu... | EMV Smartcard Reader         | 3     |            | DB6E8FE547 |
| 072f:90de | Advance... | Token USB 64K                | 3     | usbfs      | 02F1FBC843 |
| 076b:3031 | OmniKey    | 3x21 Smart Card Reader       | 3     | usbfs      | 8F063FE8F1 |
| 0c4b:0551 | Reiner ... | tanJack USB                  | 3     |            | CEE7D17AFF |
| 316d:4c4b | Purism,... | Librem Key                   | 3     | usbfs      | F3E5EBA0C2 |
| 046a:002d | Cherry     | SmartTerminal XX44           | 2     |            | FEC09C0BAC |
| 072f:2224 | Advance... | ACR1281 1S Dual Reader       | 2     | usbfs      | 7EC33920D1 |
| 072f:b000 | Advance... | ACR3901U                     | 2     |            | A44B651190 |
| 076b:3022 | OmniKey    | CardMan 3121 (HID Technol... | 2     | usbfs      | 21C0D0DB9C |
| 076b:5421 | OmniKey    | Smart Card Reader USB        | 2     |            | A72E3CC74F |
| 0783:0006 | C3PO       | LTC31v2                      | 2     |            | A219714B0E |
| 08e6:5504 | Gemalto... | Prox SU USB PC Link Reader   | 2     | usbhid     | 5DBA4D3BCE |
| 0ca6:00a0 | Castles... | EZCCID Smart Card Reader     | 2     |            | 3DC7A36CB3 |
| 0d46:3010 | Kobil S... | KOBIL Class 3 Reader         | 2     |            | A27BDDD9AB |
| 0d46:3014 | Kobil S... | Smart Token                  | 2     |            | 5F126B3966 |
| 15cf:0019 | Avtor      | SecureToken                  | 2     |            | 196CDBC09E |
| 1fc9:010b | NXP Sem... | PR533                        | 2     |            | 08514D3FB0 |
| 0403:e3b4 | Future ... | Parsec Desktop Reader PR-... | 1     |            | 775160993D |
| 046a:01a2 | Cherry     | Cherry GmbH CHERRY SECURE... | 1     | usbhid     | 663D09FE93 |
| 048d:1365 | Integra... | SmartCard Reader             | 1     |            | DB4B891E15 |
| 04cc:5072 | ST-Eric... | Chipcard Reader              | 1     |            | 65FD9B5315 |
| 04e6:511d | SCM Mic... | SCR3311 Smart Card Reader    | 1     |            | 8A42AD40CC |
| 04e6:5811 | SCM Mic... | CLOUD 2900 R Smart Card R... | 1     | usbfs      | 31A6F21CCD |
| 04e6:581d | SCM Mic... | SCR3500 C Contact Reader     | 1     | usbfs      | AF129BFCD6 |
| 058f:9522 | Alcor M... | EMV Smartcard Reader         | 1     |            | 713028C9F2 |
| 05af:605a | Jing-Mo... | HP USB Business Slim Smar... | 1     | usbhid     | 64D562D6EF |
| 076b:a022 | OmniKey    | CardMan Smart@Link           | 1     |            | 0138C33179 |
| 0783:0036 | C3PO       | USB SMART CARD READER        | 1     | usbfs      | 86286FAD9C |
| 0802:0005 | Mako Te... | SZZCS-ZCS80                  | 1     | usbhid     | 6C0FAEA524 |
| 096e:0505 | Feitian... | FT SCR310                    | 1     | usbfs      | 4039D51671 |
| 096e:0853 | Feitian... | U2F CCID KB                  | 1     | usbfs      | 39F6BEF929 |
| 09c3:0013 | HID Global | USB Reader V3                | 1     | usbfs      | D53C2A8B0E |
| 0a89:0035 | Aktiv      | KAZTOKEN                     | 1     |            | AD17A21F6E |
| 0bf8:1017 | Fujitsu... | Keyboard KB SCR              | 1     | usbhid     | C6E7AFB3B9 |
| 0bf8:1023 | Fujitsu... | Keyboard KB100 SCR eSIG      | 1     | usbhid     | 7E432EC517 |
| 0bf8:1024 | Fujitsu... | Smartcard Reader D323        | 1     |            | 3BD076E0FA |
| 0c4b:0100 | Reiner ... | cyberJack e-com/pinpad       | 1     | cyberjack  | 841F3BBD4C |
| 1050:0404 | Yubico.com | Yubikey 4 CCID               | 1     | usbfs      | 30511D93C4 |
| 17ef:6007 | Lenovo     | Smartcard Keyboard           | 1     | usbhid     | 4D4128C3A2 |
| 1c34:91b1 | SpringCard | Two                          | 1     |            | F93D4537CB |
| 20a0:4230 | Clay Logic | Nitrokey HSM                 | 1     |            | DEDECE32F6 |
| 20a0:42d4 | Clay Logic | CanoKey                      | 1     | usbhid     | 5F02658195 |
| 23a0:0004 | BIFIT      | iBank2Key                    | 1     |            | A8A89AC09A |
| 25dd:1101 | BIT4ID     | miniLector-S                 | 1     |            | D40236931F |

### Converter (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0403:7a58 | Future ... | USB <-> Serial Cable         | 15    | usbfs      | A13B05F65F |
| 0403:1237 | Future ... | Z397 GUARD Converter         | 3     |            | 9B4EDD921B |
| 03eb:21fe | Atmel      | AVR309:USB to UART protoc... | 2     | igorplu... | 032A1A34DF |
| 110a:1110 | Moxa Te... | UPort 1110                   | 2     | ti_usb_... | F815AEE35E |
| 051d:c812 | America... | APC USB SERIAL CONVERTER.    | 1     | cdc_acm    | BDB4EBA3E4 |
| 0a12:0042 | Cambrid... | SPI Converter                | 1     |            | E1C0C74CA6 |
| 0c12:0005 | Zeroplus   | PSX Vibration Feedback Co... | 1     | usbhid     | A39C4402B9 |
| 1f6a:15aa | AJA Vid... | AJA Mini-converter           | 1     | cdc_acm    | 31D8634492 |
| 277c:0024 | SIGNALCORE | SC5308A RF DownConverter     | 1     |            | 1343B5BB5D |

### Disk (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 058f:6387 | Alcor M... | Transcend                    | 2013  | uas, us... | A525C8911B |
| 090c:1000 | Silicon... | Silicon-Power8G              | 2010  | uas, us... | 0F2394B49D |
| 058f:6362 | Alcor M... | Flash Card Reader/Writer     | 1929  | uas, us... | 6C7ECC284B |
| 058f:6366 | Alcor M... | Multi Flash Reader           | 1927  | uas, us... | F3E5EBA0C2 |
| 0951:1666 | Kingsto... | DataTraveler 100 G3/G4/SE... | 1669  | uas, us... | D4EE4BA59F |
| 8564:1000 | Transcend  | JetFlash                     | 1409  | uas, us... | 4EB6B00CAC |
| 0bda:0138 | Realtek... | RTS5138 Card Reader Contr... | 1382  | ums_rea... | E9FAA1A00B |
| 0781:5567 | SanDisk    | Cruzer Blade                 | 1344  | uas, us... | EABB3946AD |
| 0bda:0158 | Realtek... | USB 2.0 multicard reader     | 1315  | ums_rea... | C0FAA178A2 |
| 174c:55aa | ASMedia... | ASM1051E SATA 6Gb/s bridg... | 996   | usb_sto... | 3AB561BBE8 |
| 0781:5581 | SanDisk    | Ultra                        | 825   | uas, us... | 65C122FE69 |
| 0930:6545 | Toshiba    | Kingston DataTraveler 102... | 771   | uas, us... | 69DA26C946 |
| 058f:6364 | Alcor M... | AU6477 Card Reader Contro... | 740   | uas, us... | 93DE1508CB |
| 0781:5583 | SanDisk    | Ultra Fit                    | 603   | uas, us... | 24974BE67E |
| 152d:0578 | JMicron... | JMS578 SATA 6Gb/s            | 567   | uas, us... | 93825976F1 |
| 13fe:4200 | Kingsto... | USB DISK 2.0                 | 550   | uas, us... | 3405536413 |
| 0bda:0151 | Realtek... | Mass Storage Device (Mult... | 549   | uas, us... | 788DD45DC8 |
| 0930:6544 | Toshiba    | TransMemory-Mini / Kingst... | 483   | uas, us... | C0FB875CA5 |
| 0bda:0316 | Realtek... | SD/MMC                       | 475   | uas, us... | EEB181F50B |
| 0781:5575 | SanDisk    | Cruzer Glide                 | 463   | uas, us... | 01DBF1B5EC |
| 05e3:0749 | Genesys... | MassStorageClass             | 441   | uas, us... | 32F01CCAAB |
| 0781:5591 | SanDisk    | Ultra Flair                  | 431   | uas, us... | 0C14FFD402 |
| 0951:1665 | Kingsto... | Digital DataTraveler SE9     | 415   | uas, us... | 8264430178 |
| 05e3:0745 | Genesys... | Logilink CR0012              | 394   | uas, us... | 90659E6A34 |
| 0bda:0153 | Realtek... | 3-in-1 (SD/SDHC/SDXC) Car... | 379   | ums_rea... | 269771FE3E |
| 152d:2329 | JMicron... | JM20329 SATA Bridge          | 369   | usb_sto... | D1FC84613E |
| 1005:b113 | Apacer ... | Handy Steno 2.0/HT203        | 350   | uas, us... | 80ADFF7646 |
| 13fe:4100 | Kingsto... | Silicon-Power16G             | 348   | uas, us... | B820B810C9 |
| 0781:5571 | SanDisk    | Cruzer Fit                   | 327   | uas, us... | 35BCBD121B |
| ffff:5678 | VendorCo   | Disk 2.0                     | 317   | uas, us... | 497BF56CC6 |
| 13fe:4300 | Kingsto... | USB DISK                     | 315   | uas, us... | 6A333A499D |
| 18a5:0302 | Verbatim   | STORE N GO                   | 312   | uas, us... | DF99169555 |
| 152d:2338 | JMicron... | JM20337 Hi-Speed USB to S... | 307   | uas, us... | 45661425FF |
| abcd:1234 | General    | UDisk                        | 304   | uas, us... | A9BA9DF656 |
| 05ac:8403 | Apple      | Internal Memory Card Reader  | 302   | uas, us... | BD1CB6F826 |
| 048d:1336 | Integra... | SD/MMC Cardreader            | 300   | uas, us... | 5AC667365B |
| 13fe:6300 | Kingsto... | SP Mobile C31                | 300   | uas, us... | F442DF91A1 |
| 05ac:8406 | Apple      | SD Card Reader               | 297   | apple_m... | 0C24CAF245 |
| 0bda:0111 | Realtek... | RTS5111 Card Reader Contr... | 283   | uas, us... | 543E15E027 |
| 0bc2:231a | Seagate    | Expansion                    | 269   | uas        | 82B124D8C4 |
| 05e3:0723 | Genesys... | GL827L SD/MMC/MS Flash Ca... | 266   | usb_sto... | 735015DCE2 |
| 05e3:0751 | Genesys... | microSD Card Reader          | 264   | uas, us... | 707F27E3E8 |
| 0bda:0181 | Realtek... | MS/MS-Pro/HG                 | 262   | uas, us... | F1AA7841AD |
| 058f:9360 | Alcor M... | 8-in-1 Media Card Reader     | 261   | uas, us... | 34353C5C01 |
| 13fe:5500 | Kingsto... | Patriot Memory               | 249   | uas, us... | 27E29303BC |
| 0bda:0177 | Realtek... | USB2.0-CRW                   | 239   | ums_rea... | 4EB6B00CAC |
| 058f:6377 | Alcor M... | AU6375 4-LUN card reader     | 232   | uas, us... | 24D7BB4DF6 |
| 0bda:0328 | Realtek... | SD/MMC CRW                   | 225   | uas, us... | 2B4A1A20D9 |
| 1058:25a2 | Western... | Elements 25A2                | 224   | uas, us... | D3AA74A821 |
| 14cd:1212 | Super Top  | microSD card reader (SY-T18) | 223   | uas, us... | 4E4E73BA37 |
| 14cd:6116 | Super Top  | M6116 SATA Bridge            | 219   | uas, us... | 7046D52A8D |
| 1908:0226 | GEMBIRD    | Mass-Storage                 | 214   | uas, us... | 3233E1293C |
| 14cd:168a | Super Top  | Elecom Co., Ltd MR-K013 M... | 213   | uas, us... | B0CC9343A8 |
| 05e3:0716 | Genesys... | Multislot Card Reader/Writer | 206   | uas, us... | ECAAA3B66A |
| 13fd:0840 | Initio     | INIC-1618L SATA              | 184   | usb_sto... | 41E623BD85 |
| 174c:5106 | ASMedia... | Transcend StoreJet 25M3      | 184   | uas, us... | 5A86DAC3C6 |
| 0781:5530 | SanDisk    | Cruzer                       | 174   | uas, us... | F5112DBF47 |
| 152d:1561 | JMicron... | JMS561U two ports SATA 6G... | 171   | uas        | 6AF9EA19B5 |
| 0781:556b | SanDisk    | Cruzer Edge                  | 169   | uas, us... | 36ACEDB60B |
| 0951:1643 | Kingsto... | DataTraveler G3              | 165   | uas, us... | 4AA0BD8B9F |
| 12d1:14dc | Huawei ... | E3372 LTE/UMTS/GSM HiLink... | 164   | uas, us... | 8CDB34DBC8 |
| 0bc2:ab24 | Seagate    | Backup Plus Portable Drive   | 162   | uas        | 9834990221 |
| 0951:1642 | Kingsto... | DT101 G2                     | 158   | uas, us... | 61E272A119 |
| 048d:1234 | Integra... | Mass storage                 | 155   | uas, us... | 5282A1C293 |
| 0480:a202 | Toshiba... | Canvio Basics HDD            | 154   | uas, us... | CE1FD9A03E |
| 1bcf:0c31 | Sunplus... | SPIF30x Serial-ATA bridge    | 152   | uas, us... | 02BA908575 |
| 12d1:107e | Huawei ... | P10 smartphone               | 151   | uas, us... | 1DB80A4DB5 |
| 13fe:3e00 | Kingsto... | USB DISK 2.0                 | 146   | uas, us... | 621AA75BF6 |
| 0bc2:ab38 | Seagate    | Backup Plus Hub              | 145   | uas        | B8A7B6080F |
| 14cd:125d | Super Top  | Storage Device               | 145   | uas, us... | E52E9002D0 |
| 0781:5597 | SanDisk    | Cruzer Glide 3.0             | 138   | uas, us... | 1069B24865 |
| 0bda:0184 | Realtek... | RTS5182 Card Reader          | 138   | ums_rea... | 511C376041 |
| 0bc2:2322 | Seagate    | SRD0NF1 Expansion Portabl... | 137   | uas        | 42CD4D28BD |
| 1307:0330 | Transcend  | 63-in-1 Multi-Card Reader... | 136   | uas, us... | 6FE6C2D416 |
| 04c5:2028 | Fujitsu    | Virtual CD-Rom               | 135   | uas, us... | 8E1FA1F2AF |
| 05dc:a81d | Lexar M... | LJDTT16G [JumpDrive 16GB]    | 131   | uas, us... | 1BB97BC7DF |
| 0080:a001 | Assmann... | Digitus DA-71114 SATA        | 128   | uas        | 6B4C3F811B |
| 0781:558a | SanDisk    | Ultra                        | 127   | uas, us... | 767EB7C6D3 |
| 090c:2000 | Silicon... | USB DISK                     | 127   | uas, us... | 8A52B831D7 |
| 152d:0567 | JMicron... | JMS567 SATA 6Gb/s bridge     | 124   | uas, us... | 066A7CE533 |
| 1058:25a3 | Western... | Elements Desktop (WDBWLG)    | 122   | uas, us... | EFA327D791 |
| 1058:10b8 | Western... | Elements Portable (WDBU6Y... | 120   | uas, us... | 7A7DD8EED3 |
| 04e8:61f5 | Samsung... | Portable SSD T5              | 119   | uas        | 278873FF66 |
| 05e3:070e | Genesys... | USB 2.0 Card Reader          | 119   | uas, us... | F98CCE15A3 |
| 2109:0711 | VIA Labs   | VL711 SATA 6Gb/s bridge      | 118   | uas, us... | 1161AF8368 |
| 1058:25e1 | Western... | My Passport 25E1             | 116   | uas, us... | BA8F31C45F |
| 0781:5590 | SanDisk    | Ultra                        | 115   | uas, us... | 326B3F5892 |
| 13fe:3600 | Kingsto... | flash drive (4GB, EMTEC)     | 115   | usb_sto... | 2D1739DC58 |
| 1f75:0917 | Innosto... | NAND Flash                   | 115   | uas, us... | B62359FCB1 |
| 0424:2228 | Microch... | 9-in-2 Card Reader           | 114   | uas, us... | 2F3056DC52 |
| 0bc2:331a | Seagate    | Expansion Desk               | 114   | uas, us... | B8A7B6080F |
| 1058:25ee | Western... | My Book 25EE                 | 114   | uas, us... | 5026826DBE |
| 1f75:0621 | Innosto... | IS621 SATA Storage Contro... | 114   | uas, us... | 2EEB7379DF |
| 04e8:61b6 | Samsung... | M3 Portable Hard Drive       | 113   | uas, us... | 1DF662506B |
| 0644:0200 | TEAC       | All-In-One Multi-Card Rea... | 112   | uas, us... | E77852D5C2 |
| 0781:557d | SanDisk    | Cruzer Force                 | 112   | uas, us... | 41323F324C |
| 1058:1021 | Western... | Elements Desktop (WDBAAU)    | 112   | uas, us... | A031BFBDBF |
| 0781:5406 | SanDisk    | Cruzer Micro U3              | 110   | uas, us... | 5909BE5C82 |
| 0951:1607 | Kingsto... | DataTraveler 100             | 110   | uas, us... | 8465636993 |
| 1307:0165 | Transcend  | 2GB/4GB/8GB Flash Drive      | 110   | uas, us... | B37E349828 |

### Dvb card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:2838 | Realtek... | RTL2838 DVB-T                | 209   | dvb_usb... | 0071FAABAC |
| 07ca:a309 | AVerMed... | AVerTV DVB-T (A309)          | 33    | dvb_usb... | 6C14033E55 |
| 0bda:2832 | Realtek... | RTL2832U DVB-T               | 22    | dvb_usb... | 2A1EDA1972 |
| 15f4:0131 | HanfTek    | Astrometa DVB-T/T2/C FM &... | 15    | dvb_usb... | 17D37C5316 |
| 048d:9135 | Integra... | Zolid Mini DVB-T Stick       | 14    | dvb_usb... | 18FE596FBA |
| 07ca:1336 | AVerMed... | A336 MiniCard Hybrid DVB-T   | 13    |            | CD01C1DDBD |
| 1164:1f08 | YUAN Hi... | STK7700D                     | 12    | dvb_usb... | 7904B934A4 |
| 15a4:9016 | Afatech    | AF9015 DVB-T USB2.0 stick    | 11    | dvb_usb... | 6416E75D0F |
| 0572:c688 | Conexan... | Geniatech T230 DVB-T2 TV ... | 10    | dvb_usb... | 855BFF097C |
| 07ca:a310 | AVerMed... | A310                         | 10    | dvb_usb... | 85137E0EB5 |
| 1d19:1101 | Dexatek... | DK DVB-T Dongle              | 10    | dvb_usb... | 9AA2FF4CA2 |
| 2304:0237 | Pinnacl... | PCTV 73e [DiBcom DiB7000PC]  | 10    | dvb_usb... | A85B460D7A |
| 07ca:1871 | AVerMed... | TD310 DVB-T/T2/C dongle      | 9     | dvb_usb... | 38422D16B5 |
| 048d:9005 | Integra... | DVB-T TV Stick               | 8     | dvb_usb... | 214C59A169 |
| 1f4d:c803 | G-Tek E... | NotOnlyTV (Lifeview) LV5T... | 8     | dvb_usb... | B7DF25BA5D |
| 2040:7070 | Hauppauge  | Nova-T Stick 3               | 8     | dvb_usb... | 0D964B5339 |
| 0572:0320 | Conexan... | DVBSky T330 DVB-T2/C tuner   | 5     | dvb_usb... | 757746E097 |
| 07ca:0831 | AVerMed... | H831 USB Hybrid DVB-T/T2     | 5     |            | D5A4F195AE |
| 07ca:1334 | AVerMed... | H334 MiniCard Hybrid DVB-T   | 5     |            | 5E45DDC465 |
| 07ca:a835 | AVerMed... | A835                         | 5     | dvb_usb... | B7DF25BA5D |
| 0ccd:0038 | TerraTe... | Cinergy TÂ² DVB-T Receiver | 5     | dvb_usb... | A29FC046A6 |
| 187f:0202 | Siano M... | Nice                         | 5     | smsusb     | F032F846BE |
| 2040:9580 | Hauppauge  | NovaT 500Stick               | 5     | dvb_usb... | E1FFF3ADE4 |
| 07ca:0830 | AVerMed... | H830 USB Hybrid DVB-T        | 4     |            | 79A097BF6F |
| 07ca:1835 | AVerMed... | A835B                        | 4     | dvb_usb... | 44857FE932 |
| 07ca:850a | AVerMed... | AverTV Volar Black HD (A850) | 4     | dvb_usb... | 8AB143EC6B |
| 07ca:a373 | AVerMed... | A373                         | 4     |            | BEB207E679 |
| 1164:0871 | YUAN Hi... | STK7700D                     | 4     | dvb_usb... | EE2674AD2E |
| 1164:3edc | YUAN Hi... | STK7700D                     | 4     |            | DF82BB0E17 |
| 15a4:1001 | Afatech    | AF9015/AF9035 DVB-T stick    | 4     | dvb_usb... | 5F974C11F5 |
| 2040:5200 | Hauppauge  | NovaT 500Stick               | 4     | dvb_usb... | 614AC09D36 |
| 04b4:2102 | Cypress... | EZ-USB FX2                   | 3     | dvb_usb... | 40EE943C1C |
| 07ca:a815 | AVerMed... | AVerTV DVB-T Volar X (A815)  | 3     | dvb_usb... | E92157B364 |
| 07ca:a867 | AVerMed... | AVerTV DVB-T (A867)          | 3     | dvb_usb... | AF740EA4C9 |
| 13d3:3282 | IMC Net... | DVB-T + GPS Minicard [RTL... | 3     |            | A3EDD93ADA |
| 1b80:d393 | Afatech    | DVB-T receiver [RTL2832U]    | 3     | dvb_usb... | 832C44928A |
| 1f4d:3000 | G-Tek E... | USB Stick                    | 3     | dvb_usb... | 8EB4D9E6CE |
| 2040:7050 | Hauppauge  | Nova-T Stick                 | 3     | dvb_usb... | EC5B3905FB |
| 0413:6029 | Leadtek... | WinFast DTV Dongle Gold      | 2     | dvb_usb... | 614DBAA6D1 |
| 04ca:f000 | Lite-On... | DVB Card                     | 2     | dvb_usb... | 7225AECEFF |
| 04ca:f01c | Lite-On... | TT1280DA DVB-T TV Tuner      | 2     |            | 24FF3CF596 |
| 0572:c689 | Conexan... | EyeTV Stick                  | 2     | dvb_usb... | D47493ECAE |
| 07ca:0335 | AVerMed... | H335                         | 2     | dvb_usb... | 0362E43257 |
| 07ca:0810 | AVerMed... | H810 USB Hybrid DVB-T        | 2     |            | B46F2FEE35 |
| 07ca:1335 | AVerMed... | H335C                        | 2     |            | 81D55608B8 |
| 0ccd:0064 | TerraTe... | DVB Card                     | 2     | dvb_usb... | BA214D2A0B |
| 1415:0003 | Nam Tai... | SCEH-0036                    | 2     | dvb_usb... | F2536AC0FF |
| 14f7:0500 | TechniS... | DVB-PC TV Star HD            | 2     | dvb_usb... | C7D09ABC04 |
| 1b80:e39a | Afatech    | DVB-T395U [af9015]           | 2     | dvb_usb... | CF4C0A5A4D |
| 1d19:1102 | Dexatek... | DK mini DVB-T Dongle         | 2     | dvb_usb... | 25564EE13D |
| 2040:1801 | Hauppauge  | Okemo B                      | 2     | smsusb     | FE0ED9DA05 |
| 2040:8400 | Hauppauge  | WinTV Nova-T-500             | 2     | dvb_usb... | EE8DC7DA28 |
| 2040:9950 | Hauppauge  | WinTV Nova-T-500             | 2     | dvb_usb... | 03F4361376 |
| 2304:023a | Pinnacl... | PCTV 801e                    | 2     | dvb_usb... | 3B00238998 |
| 0413:6a04 | Leadtek... | DVB-T 2                      | 1     | dvb_usb... | C5B8862A26 |
| 04b4:861f | Cypress... | Anysee E30 USB 2.0 DVB-T ... | 1     | dvb_usb... | 04469024CA |
| 07ca:1830 | AVerMed... | AVerTV Volar Video Captur... | 1     |            | A295A7FAC6 |
| 07ca:1831 | AVerMed... | H831 USB Hybrid DVB-T/T2     | 1     |            | 7DAAC9434C |
| 07ca:3830 | AVerMed... | H830 USB Hybrid DVB-T        | 1     |            | BB4AEE1CE5 |
| 07ca:3867 | AVerMed... | A867                         | 1     |            | 159AB17857 |
| 07ca:4336 | AVerMed... | A336 MiniCard Hybrid DVB-T   | 1     |            | 0C3E26BCE7 |
| 07ca:8150 | AVerMed... | A815O                        | 1     | dvb_usb... | 69CC9D8136 |
| 07ca:a801 | AVerMed... | AVerTV DVB-T (A800)          | 1     | dvb_usb... | 4F4FA6D3F6 |
| 07ca:a868 | AVerMed... | A868                         | 1     | dvb_usb... | 141E382738 |
| 0b05:173f | ASUSTek... | My Cinema U3100 Mini         | 1     | dvb_usb... | 34891AD0E7 |
| 0b48:3006 | TechnoT... | TT-connect S-2400 DVB-S r... | 1     | dvb_usb... | 003EB89135 |
| 0bda:2831 | Realtek... | RTL2831U DVB-T               | 1     | dvb_usb... | 2A72B05F9D |
| 0ccd:0078 | TerraTe... | Cinergy T XXS                | 1     | dvb_usb... | 7D2833C2F9 |
| 0ccd:00a9 | TerraTe... | RTL2838 DVB-T COFDM Demod... | 1     | dvb_usb... | B33866B71B |
| 0fd9:0021 | Elgato ... | EyeTV DTT                    | 1     | dvb_usb... | 88DD86FBBC |
| 1044:7001 | Chu Yue... | Gigabyte U7000 DVB-T tuner   | 1     | dvb_usb... | BB260FBCCF |
| 1044:7002 | Chu Yue... | Gigabyte U8000 DVB-T tuner   | 1     | dvb_usb... | E1F266F412 |
| 1164:2edc | YUAN Hi... | STK7700D                     | 1     | dvb_usb... | 3273D1D45A |
| 14aa:0221 | WideVie... | WT-220U DVB-T dongle         | 1     | dvb_usb... | 7FA8E3A5E5 |
| 14aa:0226 | WideVie... | Digital TV Receiver          | 1     | dvb_usb... | 7B994D2EC2 |
| 14aa:0301 | WideVie... | AVermedia/Yakumo/Hama/Typ... | 1     | dvb_usb... | 65E73516B5 |
| 1b80:c161 | Afatech    | DVB-T 2                      | 1     |            | 2A8FB37B8C |
| 1b80:e402 | Afatech    | DVB-T 2                      | 1     | dvb_usb... | 1EC9575FA4 |
| 2040:7080 | Hauppauge  | myTV.t                       | 1     | dvb_usb... | A1CC53584D |
| 2040:9301 | Hauppauge  | WinTV NOVA-T USB2 (warm)     | 1     | dvb_usb... | 6630C7EF27 |
| 2040:b210 | Hauppauge  | Dell Digital tv              | 1     | dvb_usb... | EE05EBEF50 |
| 2304:022b | Pinnacl... | PCTV 71e [Afatech AF9015]    | 1     | dvb_usb... | B778A6096A |
| 2304:022c | Pinnacl... | PCTV 2000e                   | 1     | dvb_usb... | B2BA637E05 |
| 2304:022e | Pinnacl... | PCTV 320cx                   | 1     | dvb_usb... | 9DA08CE4A5 |
| 2304:0236 | Pinnacl... | PCTV 72e [DiBcom DiB7000PC]  | 1     | dvb_usb... | 5728BD3F53 |
| eb1a:5013 | eMPIA T... | USB 2883 Device              | 1     |            | 5DD14F9164 |

### Fingerprint reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 138a:003f | Validit... | VFS495 Fingerprint Reader    | 867   | usbfs      | 1069B24865 |
| 06cb:00bd | Synaptics  | Prometheus MIS Touch Fing... | 805   | usbfs      | 11CD74E647 |
| 138a:0011 | Validit... | VFS5011 Fingerprint Reader   | 492   | usbfs      | 5D323AF087 |
| 138a:0017 | Validit... | VFS 5011 fingerprint sensor  | 456   | usbfs      | EB89BBEBFE |
| 147e:2016 | Upek       | Biometric Touchchip/Touch... | 449   | usbfs      | 8B21B7CFFE |
| 06cb:009a | Synaptics  | Metallica MIS Touch Finge... | 393   | usbfs      | EEB181F50B |
| 138a:0018 | Validit... | Fingerprint scanner          | 342   |            | 2E9D378E76 |
| 08ff:2810 | AuthenTec  | AES2810                      | 309   | usbfs      | 8C2D9E608C |
| 138a:003c | Validit... | VFS471 Fingerprint Reader    | 303   | usbfs      | 99FB47DC2B |
| 138a:003d | Validit... | VFS491                       | 298   | usbfs      | E12D7E47E6 |
| 06cb:0081 | Synaptics  | Synaptics WBDI               | 287   |            | 08D287D2E2 |
| 08ff:2580 | AuthenTec  | AES2501 Fingerprint Sensor   | 277   |            | 51AB06C26F |
| 1c7a:0570 | LighTun... | EgisTec Touch Fingerprint... | 271   |            | 05087F89C1 |
| 0483:2016 | STMicro... | Fingerprint Reader           | 261   | usbfs      | 1B17B5C927 |
| 04f3:0903 | Elan Mi... | ELAN:Fingerprint             | 249   | usbfs      | C4FFE3D08B |
| 27c6:533c | Shenzhe... | FingerPrint                  | 238   | usbfs      | 5E25D50915 |
| 138a:0007 | Validit... | VFS451 Fingerprint Reader    | 226   | usbfs      | F31AC36B11 |
| 27c6:55b4 | Shenzhe... | Fingerprint Reader           | 220   | usbfs      | F07B9B77F5 |
| 138a:0097 | Validit... | Synaptics WBDI               | 203   | usbfs      | F45B082C14 |
| 06cb:00b7 | Synaptics  | Synaptics VFS7552 Touch F... | 201   |            | D0307FD66E |
| 27c6:55a4 | Shenzhe... | Goodix FingerPrint Device    | 194   |            | A35AAAEB6D |
| 06cb:00be | Synaptics  |                              | 192   |            | 6F6E5DAF18 |
| 147e:1002 | Upek       | Biometric Touchchip/Touch... | 189   |            | 779684E41D |
| 06cb:00a2 | Synaptics  | Metallica MOH Touch Finge... | 181   |            | 3FC424B8C6 |
| 138a:0090 | Validit... | VFS7500 Touch Fingerprint... | 181   | usbfs      | 623506F87F |
| 08ff:1600 | AuthenTec  | AES1600                      | 177   |            | A1F9398A77 |
| 138a:0050 | Validit... | Swipe Fingerprint Sensor     | 176   |            | 4B949C1A1B |
| 138a:00ab | Validit... | Synaptics VFS7552 Touch F... | 168   |            | 005D186DC0 |
| 1c7a:0603 | LighTun... | ES603 Swipe Fingerprint S... | 156   | usbfs      | 34A5253469 |
| 27c6:5110 | Shenzhe... | Goodix Fingerprint Device    | 154   |            | 1310B8ABF4 |
| 06cb:00df | Synaptics  | Synaptics FS7604 Touch Fi... | 147   | usbfs      | 1719B2DC9D |
| 06cb:00c9 | Synaptics  |                              | 126   | usbfs      | 3ADCB9ECF9 |
| 138a:0005 | Validit... | VFS301 Fingerprint Reader    | 125   |            | DBFA388218 |
| 138a:0001 | Validit... | VFS101 Fingerprint Reader    | 115   |            | 93E47A1AB3 |
| 147e:1000 | Upek       | Biometric Touchchip/Touch... | 97    |            | 00EEDD879B |
| 06cb:009b | Synaptics  |                              | 95    |            | 4BF23FF82D |
| 1c7a:0801 | LighTun... | Fingerprint Reader           | 95    |            | F91E822A29 |
| 04f3:0c03 | Elan Mi... | ELAN:Fingerprint             | 80    |            | 3D54291DE2 |
| 138a:0091 | Validit... | VFS7552 Touch Fingerprint... | 79    |            | 69938C221E |
| 27c6:55a2 | Shenzhe... | Goodix FingerPrint Device    | 79    |            | 0C865DDF24 |
| 04f3:0c1a | Elan Mi... | ELAN:Fingerprint             | 73    | usbfs      | 6EE47924BD |
| 138a:0010 | Validit... | VFS Fingerprint sensor       | 70    |            | F108C8522F |
| 27c6:530c | Shenzhe... | Fingerprint Reader           | 65    |            | 1FDA01A947 |
| 06cb:0078 | Synaptics  | WBDI Device                  | 63    |            | 5C62EC0CE3 |
| 27c6:538c | Shenzhe... | Fingerprint Reader           | 62    |            | 5A60912D9F |
| 06cb:00c7 | Synaptics  |                              | 58    |            | 3CD05D02A8 |
| 27c6:5117 | Shenzhe... | Fingerprint Reader           | 57    |            | C62BB4ADC9 |
| 08ff:168f | AuthenTec  | AES1660 Fingerprint Sensor   | 55    | usbfs      | 2D0B219A36 |
| 147e:1001 | Upek       | TCS5B Fingerprint sensor     | 55    |            | 55C2FA54AE |
| 08ff:2550 | AuthenTec  | AES2550 Fingerprint Sensor   | 53    | usbfs      | 78B2FAB1E0 |
| 06cb:00a8 | Synaptics  |                              | 49    | usbfs      | 2054D0DEE6 |
| 06cb:00e7 | Synaptics  |                              | 48    | usbfs      | 28B152BB19 |
| 06cb:00bb | Synaptics  |                              | 43    |            | 2A2CFDB7D4 |
| 08ff:2683 | AuthenTec  | Fingerprint Sensor           | 43    |            | 7FAB4F85E2 |
| 08ff:168b | AuthenTec  | Fingerprint Sensor           | 40    |            | 6378D53C40 |
| 27c6:5584 | Shenzhe... | Fingerprint Reader           | 37    |            | E68DFE0824 |
| 138a:0094 | Validit... | Synaptics WBDI               | 33    |            | 5154E96ABE |
| 138a:0092 | Validit... | Synaptics VFS7552 Touch F... | 32    |            | 95D389BFE5 |
| 04f3:0c28 | Elan Mi... | fingerprint sensor [FeinT... | 28    | usbfs      | 1FCC4E6895 |
| 138a:0008 | Validit... | VFS300 Fingerprint Reader    | 28    |            | CFA7A66840 |
| 138a:00a6 | Validit... | Synaptics VFS7552 Touch F... | 24    |            | F2CA8E8D38 |
| 06cb:0082 | Synaptics  | Synaptics WBDI Fingerprin... | 21    |            | 32F01CCAAB |
| 2808:9338 | Focal-s... | FT9201Fingerprint.           | 19    |            | 06300B96A7 |
| 04e8:730a | Samsung... | Fingerprint Device           | 14    |            | 641AA732DA |
| 27c6:5201 | Shenzhe... | Fingerprint Reader           | 14    | cdc_acm    | 4A5F986165 |
| 08ff:2665 | AuthenTec  | Fingerprint Sensor           | 13    |            | 4E6E58BBBA |
| 27c6:5335 | Shenzhe... | Goodix Fingerprint Device    | 13    | cdc_acm    | D13426531E |
| 04e8:730b | Samsung... | Fingerprint Sensor Device... | 11    |            | BA8F31C45F |
| 138a:009d | Validit... | Synaptics WBDI               | 11    |            | 99C878CD5E |
| 04f3:0c01 | Elan Mi... | ELAN:Fingerprint             | 7     |            | B702F17A07 |
| 08ff:1660 | AuthenTec  | AES1660 Fingerprint Sensor   | 7     |            | FFFFAF4799 |
| 27c6:5042 | Shenzhe... | Goodix Fingerprint Device    | 7     | cdc_acm    | 4D249AE75F |
| 05ba:000a | Digital... | Fingerprint Reader           | 6     | mod_usb... | 21110235EB |
| 08ff:168a | AuthenTec  | Fingerprint Sensor           | 6     |            | AF785987C5 |
| 27c6:5503 | Shenzhe... | Goodix FingerPrint Device    | 6     |            | 8D45D9544E |
| 045e:00bb | Microsoft  | Fingerprint Reader           | 5     | usbhid     | 4B34114E72 |
| 04e8:7301 | Samsung... | Fingerprint Device           | 5     |            | 4F39E11826 |
| 06cb:00e9 | Synaptics  | Synaptics FS7604 Touch Fi... | 5     |            | A3F6FA0AC9 |
| 08ff:1686 | AuthenTec  | Fingerprint Sensor           | 5     |            | 393852D904 |
| 08ff:168c | AuthenTec  | Fingerprint Sensor           | 5     |            | ED52345849 |
| 08ff:2691 | AuthenTec  | Fingerprint Sensor           | 5     |            | 8395F7AEF5 |
| 1c7a:0577 | LighTun... | EgisTec EH577                | 4     |            | 18B5757039 |
| 413c:3021 | Dell       | MS819 Wired Mouse With Fi... | 3     | usbhid     | 653462EBFC |
| 04f3:0c10 | Elan Mi... | ELAN:Fingerprint             | 2     |            | 74C0BDD4EB |
| 138a:0093 | Validit... | Synaptics VFS7552 Touch F... | 2     |            | 579E1F3D79 |
| 1491:0020 | Futroni... | FS81 Fingerprint Scanner ... | 2     | usbfs      | F8BF9AFBE7 |
| 16d1:0401 | Suprema    | SUP-SFR400(A) BioMini Fin... | 2     |            | 783EEAAA01 |
| 1c7a:0571 | LighTun... | EgisTec Touch Fingerprint... | 2     |            | A7E79F067E |
| 2808:6652 | HOLTEK     | FocalTech Fingerprint Device | 2     |            | A93FE624C9 |
| 045e:00bd | Microsoft  | Fingerprint Reader           | 1     |            | 4F0031F39F |
| 04e8:7309 | Samsung... | Fingerprint Device           | 1     |            | 739EE63E1D |
| 04f3:0c3a | Elan Mi... | Elan Security-WBF Fingerp... | 1     |            | F3F60A5C06 |
| 05ba:0002 | Digital... | Fingerprint Scanner, U.ar... | 1     |            | AE361E5F23 |
| 08ff:1680 | AuthenTec  | AES1660 Fingerprint Sensor   | 1     |            | 6C4DA274F4 |
| 08ff:2500 | AuthenTec  | AES2501                      | 1     |            | 4DCFB332DF |
| 08ff:2660 | AuthenTec  | AES2660 Fingerprint Sensor   | 1     |            | 0985E32752 |
| 08ff:5731 | AuthenTec  | AES3500 TruePrint Sensor     | 1     | usbfs      | CF0E73081E |
| 138a:0015 | Validit... | VFS 5011 fingerprint sensor  | 1     |            | 84DC871F65 |
| 147e:3001 | Upek       | TCS1C EIM/STM32 Fingerpri... | 1     |            | 6D671DF349 |
| 147e:5002 | Upek       | TouchStrip Fingerprint Se... | 1     |            | 335EF1CCCD |

### Floppy (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 059b:0030 | Iomega     | Zip 250 (Ver 1)              | 3     | uas, us... | 032097D2F5 |
| 059b:0001 | Iomega     | Zip 100 (Type 1)             | 2     | usb_sto... | C59A1FFF0D |
| 059b:0033 | Iomega     | ZIP 100                      | 2     | uas, us... | F0912110EB |
| 059b:0031 | Iomega     | Zip 100 (Type 3)             | 1     | uas, us... | 1ED8284AB4 |
| 059b:0034 | Iomega     | Zip 100 Driver               | 1     | usb_sto... | 506F4A7C1D |
| 059b:0035 | Iomega     | ZIP 750                      | 1     | usb_sto... | 87C89614B1 |
| 13fe:1e20 | Kingsto... | USB DISK Pro                 | 1     | uas, us... | 8902B96F21 |

### Gamepad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:028e | Microsoft  | Xbox360 Controller           | 487   | xpad       | E1B966B80D |
| 046d:c21d | Logitech   | F310 Gamepad [XInput Mode]   | 94    | xpad       | 592DBF20B3 |
| 046d:c21f | Logitech   | F710 Wireless Gamepad [XI... | 92    | xpad       | EACC1E3F66 |
| 045e:0291 | Microsoft  | Xbox 360 Wireless Receive... | 70    | xpad       | 90659E6A34 |
| 2563:0575 | ShenZhe... | ZD-V+ Wired Gaming Contro... | 39    | usbhid     | 90FE8A952C |
| 0079:0011 | DragonRise | Gamepad                      | 35    | usbhid     | B7A9A59C77 |
| 0e8f:0003 | GreenAsia  | MaxFire Blaze2               | 25    | usbhid     | 775AEB5400 |
| 0810:e501 | Persona... | SNES Gamepad                 | 14    | usbhid     | B7A9A59C77 |
| 0079:181c | DragonRise | TGZ Controller               | 11    | usbhid     | 10B8DBC9A7 |
| 0e6f:0213 | Logic3     | Afterglow Gamepad for Xbo... | 10    | xpad       | C89FA50ED0 |
| 046d:c21e | Logitech   | F510 Gamepad [XInput Mode]   | 7     | xpad       | 3FD70C5B87 |
| 0583:a000 | Padix (... | MaxFire G-08XU Gamepad       | 7     | usbhid     | DA1F0D65EC |
| 0e6f:011f | Logic3     | Rock Candy Wired Controll... | 7     | xpad       | E41DA0FB5E |
| 0e6f:0413 | Logic3     | Afterglow AX.1 Gamepad fo... | 6     | xpad       | E404A8F853 |
| 0e8f:0008 | GreenAsia  | PS Gamepad                   | 5     | usbhid     | 6D7EAF124E |
| 0e8f:0012 | GreenAsia  | Joystick/Gamepad             | 5     | usbhid     | 56A1BC8E09 |
| 145f:01c5 | Trust      | Gamepad                      | 5     | usbhid     | 93A093110A |
| 046d:c242 | Logitech   | XUSB Gamepad                 | 4     | usbfs      | 333F34E356 |
| 1345:6006 | Sino Li... | Defender Wireless Controller | 4     |            | 1A9077AB60 |
| 7545:1122 | SZ-MYPOWER | PC Gamepad                   | 4     | usbhid     | 77513A0FE5 |
| 0e8f:310d | GreenAsia  | USB Joystick                 | 3     | usbhid     | 4D127F6426 |
| 145f:0231 | Trust      | USB Gamepad                  | 3     | usbhid     | A72E3CC74F |
| 1bad:fa01 | Harmoni... | Gamepad                      | 3     | xpad       | 4AA6A34C0C |
| 24c6:5b02 | ThrustM... | GPX Controller               | 3     | xpad       | 653E8EDAB3 |
| 050d:0805 | Belkin ... | Nostromo N50 GamePad         | 2     | usbhid     | 285B5B2D08 |
| 07b5:0213 | Mega Wo... | Thrustmaster Firestorm Di... | 2     | usbhid     | A26C94316C |
| 0e6f:011e | Logic3     | Rock Candy Gamepad for PS3   | 2     | usbhid     | 82ABA65015 |
| 0e6f:0201 | Logic3     | Pelican PL-3601              | 2     | usbfs      | 8F0C5A3C20 |
| 11c9:55f0 | HJC Game   | GAMEPAD                      | 2     | usbhid     | FE1D48F6CC |
| 146b:5500 | BigBen ... | Usb Gamepad                  | 2     | usbhid     | C9E270C528 |
| 1bad:f016 | Harmoni... | MadCatz GamePad              | 2     | xpad       | 1A37FA7FA6 |
| 24c6:fafc | Perform... | Afterglow Gamepad for Xbo... | 2     | xpad       | F34C588CFE |
| 7545:0104 | SZ-MYPOWER | DS4 Wired Controller         | 2     | usbhid     | 11EB2546C1 |
| 0079:1855 | DragonRise | PS3/PC WirelessGamePad       | 1     | usbhid     | A76227F148 |
| 040b:6530 | Weltren... | USB 2A8K GamePad             | 1     | usbhid     | 0539EEEEB8 |
| 044f:b326 | ThrustM... | GPX Gamepad                  | 1     | xpad       | 3C19F51786 |
| 045e:0026 | Microsoft  | SideWinder GamePad Pro       | 1     | usbhid     | F8BFAA2C3D |
| 046d:c208 | Logitech   | WingMan Gamepad Extreme      | 1     | usbhid     | 00B0998670 |
| 06d6:0026 | Aashima... | Predator TH 400 Gamepad      | 1     | usbhid     | 3AFB2CB222 |
| 0738:4716 | Mad Catz   | MadCatz GamePad              | 1     | xpad       | DF679E04AA |
| 07b5:0312 | Mega Wo... | Gamepad                      | 1     | usbhid     | ADD750665B |
| 0810:0005 | Persona... | USB Gamepad                  | 1     | usbhid     | 3BDBF957FA |
| 0c12:0ef1 | Zeroplus   | P4 Wired GamepadV1.8         | 1     | usbhid     | 7A316C9F35 |
| 0e6f:0133 | Logic3     | Wired Controller             | 1     | xpad       | F402C60DD9 |
| 0e6f:021f | Logic3     | Rock Candy Gamepad for Xb... | 1     | xpad       | 806404C773 |
| 0e6f:0401 | Logic3     | Gamepad for Xbox 360         | 1     | xpad       | 8772B2BD66 |
| 0e6f:f501 | Logic3     | Inno GamePad..               | 1     | xpad       | 2248D1A3C8 |
| 0e8f:3010 | GreenAsia  | USB GamePad                  | 1     | usbhid     | 98775B699C |
| 0e8f:3013 | GreenAsia  | USB GamePad                  | 1     | usbhid     | 2669865BF9 |
| 0f30:0107 | Jess Te... | USB 4-Axis 12-Button Gamepad | 1     | usbhid     | 42D3155F59 |
| 12ab:f701 | Honey B... | Controller                   | 1     | xpad       | B621A131B1 |
| 1345:6005 | Sino Li... | SPEEDLINK USB GAMEPAD        | 1     |            | 44A5D6634F |
| 1689:fd00 | Razer USA  | Onza Tournament Edition c... | 1     | xpad       | EC671CD080 |
| 1a34:0802 | ACRUX      | Gamepad                      | 1     | usbhid     | 79099F1375 |
| 1c10:1c17 | Lanterr... | uRage Gamepad                | 1     | usbhid     | BEB08D2968 |
| 24c6:fafd | ThrustM... | Afterglow Gamepad for Xbo... | 1     | xpad       | 57B9F12C78 |
| 2563:058d | ShenZhe... | Cloud Gamepad                | 1     |            | BC2C7BA0CA |
| 2dc8:6001 | 8BitDo     | SN30/SF30 Pro gamepad        | 1     | usbhid     | 0D567A35C2 |

### Hardware key (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a89:0003 | Aktiv      | Guardant Stealth 2           | 10    | usbfs      | 50F1E050A8 |
| 0a89:0020 | Aktiv      | Rutoken S                    | 10    | usbfs      | B2FA33FC7E |
| 0471:485d | Philips... | Senselock SenseIV v2.x       | 5     |            | 658F8F2FD1 |
| 14a8:0001 | Soft pr... | Soft protection device: U... | 4     |            | C933CA0D6F |

### Hasp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0529:0001 | Aladdin... | HASP copy protection dongle  | 74    | usbfs      | D644D366B2 |

### Hub (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1d6b:0002 | Linux F... | 2.0 root hub                 | 11... | hub        | 27E29303BC |
| 1d6b:0003 | Linux F... | 3.0 root hub                 | 79711 | hub        | 27E29303BC |
| 1d6b:0001 | Linux F... | 1.1 root hub                 | 35457 | hub        | 42CD4D28BD |
| 8087:0024 | Intel      | Integrated Rate Matching Hub | 20234 | hub        | 01A3346D88 |
| 8087:8000 | Intel      | Integrated Rate Matching Hub | 8343  | hub        | 36ACEDB60B |
| 05e3:0608 | Genesys... | Hub                          | 6941  | hub        | 44ACFE85A5 |
| 8087:8008 | Intel      | Integrated Rate Matching Hub | 5562  | hub        | 36ACEDB60B |
| 05e3:0610 | Genesys... | Hub                          | 5090  | hub        | 36ACEDB60B |
| 8087:0020 | Intel      | Integrated Rate Matching Hub | 4767  | hub        | C319EC4A5F |
| 1a40:0101 | Terminu... | Hub                          | 4329  | hub        | ECC4515014 |
| 8087:8001 | Intel      | Integrated Hub               | 2491  | hub        | 9834990221 |
| 0438:7900 | AMD        | Root Hub                     | 2299  | hub        | 3A06ECCCAA |
| 0a5c:4500 | Broadcom   | BCM2046B1 USB 2.0 Hub (pa... | 2232  | hub        | ECC4515014 |
| 2109:3431 | VIA Labs   | Hub                          | 1803  | hub        | D4EE4BA59F |
| 0bda:5411 | Realtek... | RTS5411 Hub                  | 1511  | hub        | 138EC046F1 |
| 0bda:0411 | Realtek... | Hub                          | 1185  | hub        | 138EC046F1 |
| 0424:2514 | Microch... | USB 2.0 Hub                  | 1126  | hub        | AE3E01FEF8 |
| 05e3:0612 | Genesys... | Hub                          | 952   | hub        | 93DE1508CB |
| 2109:2813 | VIA Labs   | VL813 Hub                    | 891   | hub        | 93DE1508CB |
| 2109:2812 | VIA Labs   | VL812 Hub                    | 886   | hub        | 9EFBA142DD |
| 8087:8009 | Intel      | Hub                          | 885   | hub        | 5EAD0CA3AD |
| 05e3:0626 | Genesys... | USB3.1 Hub                   | 722   | hub        | 0F6D7BCF66 |
| 2109:0813 | VIA Labs   | VL813 Hub                    | 709   | hub        | 93DE1508CB |
| 174c:2074 | ASMedia... | ASM1074 High-Speed hub       | 704   | hub        | 6E020F3AD1 |
| 2109:0812 | VIA Labs   | VL812 Hub                    | 695   | hub        | 9EFBA142DD |
| 174c:3074 | ASMedia... | ASM1074 SuperSpeed hub       | 694   | hub        | 6E020F3AD1 |
| 2109:2817 | VIA Labs   | USB2.0 Hub                   | 650   | hub        | 497BF56CC6 |
| 8087:8002 | Intel      | 8 channel internal hub       | 592   | hub        | 9EFBA142DD |
| 8087:800a | Intel      | Hub                          | 591   | hub        | 9EFBA142DD |
| 0409:005a | NEC Com... | HighSpeed Hub                | 585   | hub        | 6C7ECC284B |
| 05e3:0606 | Genesys... | USB 2.0 Hub / D-Link DUB-... | 563   | hub        | D4F86565B3 |
| 2109:0817 | VIA Labs   | USB3.0 Hub                   | 561   | hub        | 497BF56CC6 |
| 058f:6254 | Alcor M... | USB Hub                      | 545   | hub        | 588CEFB67B |
| 214b:7250 | Huashen... | USB2.0 HUB                   | 531   | hub        | 707F27E3E8 |
| 05e3:0616 | Genesys... | hub                          | 495   | hub        | 93825976F1 |
| 05e3:0620 | Genesys... | USB3.2 Hub                   | 488   | hub        | 97B2732F29 |
| 05ac:1006 | Apple      | Hub in Aluminum Keyboard     | 449   | hub        | D998D59215 |
| 1a40:0201 | Terminu... | FE 2.1 7-port Hub            | 443   | hub        | CFDD30C7C7 |
| 0424:2134 | Microch... | Hub                          | 433   | hub        | FFB40F821B |
| 2109:2811 | VIA Labs   | Hub                          | 410   | hub        | EACC1E3F66 |
| 0451:8142 | Texas I... | TUSB8041 4-Port Hub          | 407   | hub        | 6B8CF94EA2 |
| 0424:5534 | Microch... | Hub                          | 406   | hub        | FFB40F821B |
| 0b97:7761 | O2 Micro   | Oz776 1.1 Hub                | 396   | hub        | 4639F065C8 |
| 0424:2513 | Microch... | 2.0 Hub                      | 374   | hub        | ECC4515014 |
| 058f:9254 | Alcor M... | Hub                          | 374   | hub        | 5B55E39C35 |
| 14cd:8601 | Super Top  | 4-Port hub                   | 351   | hub        | D926705B17 |
| 045b:0209 | Hitachi    | Hub                          | 310   | hub        | 0071FAABAC |
| 2109:8110 | VIA Labs   | Hub                          | 308   | hub        | EACC1E3F66 |
| 0451:8140 | Texas I... | TUSB8041 4-Port Hub          | 294   | hub        | 6B8CF94EA2 |
| 0a05:7211 | Unknown... | hub                          | 288   | hub        | 0AC8E061F1 |
| 045b:0210 | Hitachi    | Hub                          | 271   | hub        | 2E8639BADA |
| 8087:07e6 | Intel      | Hub                          | 240   | hub        | 1387FAB9FE |
| 214b:7000 | Huashen... | 4-port hub [Maxxter ACT-H... | 223   | hub        | A7DAB352D6 |
| 413c:2513 | Dell       | internal USB Hub of E-Por... | 218   | hub        | 9834990221 |
| 2109:0811 | VIA Labs   | Hub                          | 212   | hub        | 47A0DE503D |
| 1a40:0801 | Terminu... | USB 2.0 Hub                  | 206   | hub        | 32F01CCAAB |
| 0557:8021 | ATEN In... | Hub                          | 202   | hub        | BE8B71D264 |
| 0557:7000 | ATEN In... | Hub                          | 198   | hub        | 9EFBA142DD |
| 0424:2512 | Microch... | USB 2.0 Hub                  | 192   | hub        | 314ABB1FF1 |
| 0424:2744 | Microch... | Hub                          | 186   | hub        | 3FBBE71D21 |
| 2109:2815 | VIA Labs   | USB2.0 Hub                   | 181   | hub        | 32F01CCAAB |
| 0424:2504 | Microch... | Hub                          | 178   | hub        | 6AF9EA19B5 |
| 413c:1003 | Dell       | Keyboard Hub                 | 169   | hub        | D926705B17 |
| 0424:2734 | Microch... | USB2734                      | 160   | hub        | 0C063B9772 |
| 05e3:0617 | Genesys... | USB3.0 Hub                   | 157   | hub        | 95616813E6 |
| 0bc2:ab44 | Seagate    | Backup Plus Hub              | 149   | hub        | B8A7B6080F |
| 2109:0815 | VIA Labs   | USB3.0 Hub                   | 148   | hub        | 32F01CCAAB |
| 0424:5744 | Microch... | Hub                          | 147   | hub        | EFA327D791 |
| 05ac:1003 | Apple      | Hub in Pro Keyboard [Mits... | 144   | hub        | FF8EC660B8 |
| 0424:2807 | Microch... | Hub                          | 139   | hub        | C61BB65266 |
| 0bda:5401 | Realtek... | RTL 8153 USB 3.0 hub with... | 138   | hub        | 15A954CCE4 |
| 0424:5807 | Microch... | Hub                          | 137   | hub        | C61BB65266 |
| 04b4:6560 | Cypress... | CY7C65640 USB-2.0 "TetraHub" | 135   | hub        | 579D962F08 |
| 0424:5734 | Microch... | USB5734                      | 134   | hub        | 0C063B9772 |
| 0451:8442 | Texas I... | Hub                          | 134   | hub        | A814284F0B |
| 05e3:0605 | Genesys... | Hub                          | 126   | hub        | B14C0E8DD2 |
| 046d:c223 | Logitech   | G11/G15 Keyboard / USB Hub   | 122   | hub        | F1CA31B777 |
| 17ef:100a | Lenovo     | ThinkPad Mini Dock Plus S... | 121   | hub        | 8B21B7CFFE |
| 0bc2:ab45 | Seagate    | Backup+ Hub                  | 119   | hub        | B8A7B6080F |
| 0bda:5413 | Realtek... | Dell dock                    | 119   | hub        | 8A880E6565 |
| 0bda:5487 | Realtek... | Dell dock                    | 119   | hub        | 8A880E6565 |
| 8564:4000 | Transcend  | microSD/SD/CF UHS-II Card... | 118   | uas, us... | 03AF7DF5B2 |
| 0bda:0413 | Realtek... | Dell dock                    | 117   | hub        | 8A880E6565 |
| 0bda:0487 | Realtek... | Dell dock                    | 117   | hub        | 8A880E6565 |
| 0bda:0401 | Realtek... | USB3.0 Hub                   | 107   | hub        | 15A954CCE4 |
| 05e3:0607 | Genesys... | Logitech G110 Hub            | 104   | hub        | F60A34FE5C |
| 413c:5534 | Dell       | Hub of E-Port Replicator     | 104   | hub        | 9834990221 |
| 2109:0810 | VIA Labs   | VL81x Hub                    | 99    | hub        | 40C84C9637 |
| 413c:a005 | Dell       | Internal 2.0 Hub             | 96    | hub        | ED344B9346 |
| 0424:2660 | Microch... | Hub                          | 92    | hub        | 7AB4F05613 |
| 0424:2137 | Microch... | USB2137                      | 91    | hub        | 8A52B831D7 |
| 0451:8440 | Texas I... | Hub                          | 87    | hub        | A814284F0B |
| 413c:1010 | Dell       | USB 2.0 Hub [MTT]            | 86    | hub        | 59BF0B789C |
| 0424:2412 | Microch... | Hub                          | 84    | hub        | 5154B1932F |
| 0451:2036 | Texas I... | TUSB2036 Hub                 | 83    | hub        | 830D4C9D9D |
| 413c:2134 | Dell       | Hub of E-Port Replicator     | 83    | hub        | 9834990221 |
| 17ef:100f | Lenovo     | ThinkPad Ultra Dock Hub      | 82    | hub        | FE4AA7E54D |
| 17ef:1010 | Lenovo     | ThinkPad Ultra Dock Hub      | 82    | hub        | FE4AA7E54D |
| 0bda:5412 | Realtek... | 4-Port USB 2.0 Hub           | 81    | hub        | F17090E5D2 |
| 2109:8817 | VIA Labs   | USB Billboard Device         | 80    | hub        | 32F01CCAAB |

### Human interface (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 05ac:8242 | Apple      | Built-in IR Receiver         | 1043  | usbhid     | 6E17FB6EA4 |
| 1770:ff00 | MSI        | steel series rgb keyboard    | 337   | usbhid     | 4E8A3E6A15 |
| 0483:91d1 | STMicro... | Sensor Hub                   | 295   | usbhid     | 5900E800AA |
| 048d:5702 | Integra... | ITE Device                   | 251   | usbhid     | 7983497985 |
| 0b05:1872 | ASUSTek... | AURA LED Controller          | 210   | usbhid     | 05766074D7 |
| 0079:0006 | DragonRise | PC TWIN SHOCK Gamepad        | 192   | usbhid     | 27B0A66CEB |
| 1462:7c37 | Micro S... | MYSTIC LIGHT                 | 176   | usbhid     | 6B0A992D9F |
| 0451:82ff | Texas I... |                              | 170   | usbhid     | A814284F0B |
| 26ce:01a2 | ASRock     | LED Controller               | 170   | usbhid     | DF8AB9EFFB |
| 1038:1122 | SteelSe... | SteelSeries KLC              | 154   | usbhid     | EDD545A455 |
| 0424:274c | Microch... | Hub Controller               | 131   | usbhid     | 244D9D9DFE |
| 413c:b06e | Dell       | dock                         | 119   | usbhid     | 8A880E6565 |
| 413c:b06f | Dell       | dock                         | 119   | usbhid     | 8A880E6565 |
| 1e71:170e | NZXT       | Kraken X                     | 106   | usbhid     | D0CB96F5B2 |
| 1b1c:0c04 | Corsair    | Link Cooling Node            | 103   | usbhid     | EAF56AD62B |
| 0b05:18a3 | ASUSTek... | AURA MOTHERBOARD             | 102   | usbhid     | 6FDC84E266 |
| 187c:0550 | Alienware  | LED controller               | 102   | usbhid     | 5C569C3982 |
| 054c:0268 | Sony       | Batoh Device / PlayStatio... | 90    | usbhid     | EFDE12BE05 |
| 0665:5161 | Cypress... | USB to Serial                | 82    | usbhid     | 6B2B63756D |
| 05ac:8240 | Apple      | Built-in IR Receiver         | 81    | usbhid     | 0346BC764A |
| 0765:5010 | X-Rite     | X-Rite Pantone Color Sensor  | 77    | usbhid     | 69A252CCD6 |
| 0451:ca01 | Texas I... | USBtoI2C Solution            | 69    | usbhid     | B25CD577AD |
| 06c4:c411 | Bizlink... | D6000 Controller             | 64    | usbhid     | BC0BFCD534 |
| 10d5:55a2 | Uni Cla... | 2Port KVMSwitcher            | 64    | usbhid     | E59D042DA2 |
| 046d:c216 | Logitech   | F310 Gamepad [DirectInput... | 63    | usbhid     | F7A082BF52 |
| 048d:8350 | Integra... | ITE Device(8350)             | 63    | usbhid     | 8D16328DFD |
| 1b1c:0c0b | Corsair    | Lighting Node Pro            | 61    | usbhid     | 0ADC8FC04D |
| 046d:c215 | Logitech   | Extreme 3D Pro               | 60    | usbhid     | 8FEE3106F7 |
| 043e:9a39 | LG Elec... | USB Controls                 | 59    | usbhid     | 8EA75A2EC0 |
| 1462:7c91 | Micro S... | MYSTIC LIGHT                 | 58    | usbhid     | 27B0A66CEB |
| 0b05:1867 | ASUSTek... | AURA Custom Human interface  | 57    | usbhid     | 646446DE66 |
| 046d:c227 | Logitech   | G15 Refresh Keyboard         | 56    | usbhid     | F1CA31B777 |
| 056a:00e6 | Wacom      | TPCE6                        | 56    | usbhid     | 93090177CD |
| 1e71:2007 | NZXT       | USB Device                   | 56    | usbhid     | 7983497985 |
| 1b1c:0c10 | Corsair    | Commander PRO                | 52    | usbhid     | 86F08832C0 |
| 0810:0001 | Persona... | Dual PSX Adaptor             | 49    | usbhid     | E10152ABC8 |
| 10d5:55a4 | Uni Cla... | 4 Port KVMSwicther           | 48    | usbhid     | D7FBB47C8B |
| 2047:0855 | Texas I... | Invensense Embedded Motio... | 48    | usbhid     | F5565DFB2A |
| 1462:7c35 | Micro S... | MYSTIC LIGHT                 | 47    | usbhid     | 8EA75A2EC0 |
| 054c:05c4 | Sony       | DualShock 4 [CUH-ZCT1x]      | 45    | usbhid     | D730AC701F |
| 1e71:2006 | NZXT       | Smart Device V2              | 45    | usbhid     | E35A343F46 |
| 05ac:1392 | Apple      | Apple Watch charger          | 44    | usbhid     | 8961245ABB |
| 1462:7c84 | Micro S... | MYSTIC LIGHT                 | 44    | usbhid     | 688A36C9DF |
| 0408:3001 | Quanta     | Optical Touch Screen         | 42    | usbhid     | 937655E17D |
| 1462:7b85 | Micro S... | PRO CARBON                   | 40    | usbhid     | DB9BFA58F9 |
| 044f:b10a | ThrustM... | T.16000M Joystick            | 38    | usbhid     | 3147AE8C58 |
| 046d:c225 | Logitech   | G11/G15 Keyboard / G keys    | 38    | usbhid     | 8693B86435 |
| 1462:7c56 | Micro S... | MYSTIC LIGHT                 | 36    | usbhid     | 91C5853577 |
| 048d:8386 | Integra... | ITE Device(8386)             | 35    | usbhid     | A87E581C64 |
| 1038:1290 | SteelSe... | Arctis Pro Wireless          | 35    | usbhid     | F2CE1A8260 |
| 05a7:40fe | Bose       | SoundLink Color II speaker   | 32    | usbhid     | 886C6B0848 |
| 10d5:000d | Uni Cla... | HA2-A3                       | 32    | usbhid     | 2BB85EA1FA |
| 1b1c:0c1a | Corsair    | Lighting Node CORE           | 32    | usbhid     | 294D1F6A89 |
| 1050:0120 | Yubico.com | Yubikey Touch U2F Securit... | 31    | usbhid     | 0DA96530A0 |
| 1e71:1714 | NZXT       | Smart Device                 | 31    | usbhid     | 2CAE5A1F25 |
| 1462:3fa4 | Micro S... | MSI Gaming Controller        | 30    | usbhid     | 9B357EE9BB |
| 1462:7c94 | Micro S... | MYSTIC LIGHT                 | 29    | usbhid     | 08819513F2 |
| 17ef:3066 | Lenovo     | ThinkPad Thunderbolt 3 Do... | 29    | usbhid     | AA67AEB304 |
| 1b1c:0c17 | Corsair    | H115i Platinum               | 29    | usbhid     | 867E533368 |
| 046d:c222 | Logitech   | G15 Keyboard / LCD           | 28    | usbhid     | A817ED896E |
| 2687:fb01 | Fitbit     | Base Station                 | 28    | usbhid     | B961168B44 |
| 1462:7c95 | Micro S... | MYSTIC LIGHT                 | 27    | usbhid     | F1A1A21C56 |
| 045e:0904 | Microsoft  | Surface Dock Extender        | 26    | usbhid     | C864CCE720 |
| 1b1c:1b65 | Corsair    | Harpoon Wireless Dongle      | 26    | usbhid     | 67B629D7F9 |
| 28de:2101 | Valve S... | Watchman Dongle              | 26    | usbhid     | C198141A8E |
| 046d:c21c | Logitech   | G13 Advanced Gameboard       | 25    | usbhid     | E496AA32C8 |
| 1462:7b93 | Micro S... | MYSTIC LIGHT                 | 25    | usbhid     | 93DE1508CB |
| 147a:e00d | Formosa... | IR Receiver                  | 25    | usbhid     | 6522D9DC18 |
| 1b1c:0c18 | Corsair    | H100i Platinum               | 25    | usbhid     | 294D1F6A89 |
| 28de:2300 | Valve S... | Index HMD                    | 25    | usbhid     | F5C02601D0 |
| 0bda:1100 | Realtek... | Hub Controller               | 24    | usbhid     | 138EC046F1 |
| 1462:7c75 | Micro S... | MYSTIC LIGHT                 | 24    | usbhid     | B8A7B6080F |
| 0001:0000 | Fry's E... | MEC0003                      | 23    | usbhid     | B39ED56CC9 |
| 056a:5193 | Wacom      | Pen and multitouch sensor    | 23    | usbhid     | BC3DF872B2 |
| 187c:0520 | Alienware  | M17x                         | 22    | usbhid     | 98464FE67B |
| 2101:1407 | ActionStar | USB KVM                      | 22    | usbhid     | 9B5832381A |
| 03eb:8209 | Atmel      | maXTouch Digitizer           | 21    | usbhid     | 2CCAE0040C |
| 187c:0530 | Alienware  | AW1517                       | 21    | usbhid     | 564DD05308 |
| 046d:c214 | Logitech   | ATK3 (Attack III Joystick)   | 20    | usbhid     | 91501CC801 |
| 046d:c218 | Logitech   | F510 Gamepad [DirectInput... | 20    | usbhid     | 179854811E |
| 0bb4:2c87 | HTC (Hi... | Vive                         | 20    | snd_usb... | C198141A8E |
| 2833:0031 | Oculus VR  | Rift CV1                     | 20    | usbhid     | 7E563A9D44 |
| 28de:2000 | Valve S... | Lighthouse FPGA RX           | 20    | usbhid     | C198141A8E |
| 8087:0a04 | Intel      | Sensor Solution              | 20    | usbhid     | 5D8E12212A |
| 03eb:8417 | Atmel      | maXTouch Digitizer           | 19    | usbhid     | CEB0DF45DC |
| 044f:b108 | ThrustM... | T-Flight Hotas X Flight S... | 19    | usbhid     | 454C9E999E |
| 046d:c626 | Logitech   | 3Dconnexion Space Navigat... | 19    | usbhid     | 87C89614B1 |
| 06c4:c412 | Bizlink... | DELL DA300                   | 19    | usbhid     | E68FF3079C |
| 1b1c:1c0a | Corsair    | Corsair RM650i C-Link Ada... | 19    | usbhid     | 1129266F95 |
| 046d:c219 | Logitech   | F710 Gamepad [DirectInput... | 18    | usbhid     | CDF90072FD |
| 0483:a2ca | STMicro... | Solo 4.0.0                   | 18    | usbhid     | C5A7069C64 |
| 056a:0357 | Wacom      | PTH-660 [Intuos Pro (M)]     | 18    | usbhid     | 7B2B9D46DF |
| 057e:0337 | Nintendo   | Wii U GameCube Controller... | 18    | usbhid     | 7772A0A5AF |
| 1b1c:1c06 | Corsair    | Corsair HX-Series C-Link ... | 18    | usbhid     | 944CD264E8 |
| 1b1c:1c0b | Corsair    | RM750i Power Supply          | 18    | usbhid     | 10CA0BF6BD |
| 056d:0002 | EIZO       | HID Monitor Controls         | 17    | usbhid     | 947CDFD30B |
| 0810:0003 | Persona... | PlayStation Gamepad          | 17    | usbhid     | 2BC0B62213 |
| 187c:0524 | Alienware  | M17x                         | 17    | usbhid     | 595987AFA9 |
| 1b96:0006 | N-Trig     | DuoSense                     | 17    | usbhid     | 4AD73429AF |
| 04b5:0680 | ROHM LS... | Kionix Sensor Hub F:0004 ... | 16    | usbhid     | 8A52B831D7 |

### Infrared (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 066f:4200 | SigmaTel   | STIr4200 IrDA Bridge         | 7     | stir4200   | A519C7C3B0 |
| 0609:031d | SMK Man... | eHome Infrared Receiver      | 6     | mceusb     | 264E35C172 |
| 1509:9242 | FIC        | eHome Infrared Transceiver   | 5     | mceusb     | 00863FCEA8 |
| 147a:e017 | Formosa... | eHome Infrared Receiver      | 3     | mceusb     | D78CA9AB47 |

### Input/keyboard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:c52b | Logitech   | Unifying Receiver            | 9868  | usbhid     | 27E29303BC |
| 046d:c534 | Logitech   | Unifying Receiver            | 5379  | usbhid     | 93825976F1 |
| 046d:c31c | Logitech   | Keyboard K120                | 2433  | usbhid     | 1BB97BC7DF |
| 1c4f:0002 | SiGma M... | Keyboard TRACER Gamma Ivory  | 2147  | usbhid     | 51862605EF |
| 062a:4101 | MosArt ... | Wireless Keyboard/Mouse      | 1949  | usbhid     | 93DE1508CB |
| 045e:0745 | Microsoft  | Nano Transceiver v1.0 for... | 1383  | usbhid     | FA750DAFE2 |
| 04d9:1702 | Holtek ... | Keyboard LKS02               | 899   | usbhid     | C0FB875CA5 |
| 09da:9090 | A4Tech     | XL-730K / XL-750BK / XL-7... | 858   | usbhid     | DE9D0646DA |
| 1a2c:2124 | China R... | Keyboard                     | 857   | usbhid     | 4E4E73BA37 |
| 09da:054f | A4Tech     | USB Device                   | 840   | usbhid     | AA4E0FDCD6 |
| 1a2c:2d23 | China R... | Keyboard                     | 786   | usbhid     | 88286C36E9 |
| 413c:2113 | Dell       | KB216 Wired Keyboard         | 747   | usbhid     | 6978CD209F |
| 04f3:0103 | Elan Mi... | ActiveJet K-2024 Multimed... | 720   | usbhid     | 0D99C162A3 |
| 413c:2003 | Dell       | Keyboard SK-8115             | 681   | usbhid     | 6B2B63756D |
| 413c:2107 | Dell       | KB212-B Quiet Key Keyboard   | 668   | usbhid     | 497C824FD5 |
| 046d:c52e | Logitech   | MK260 Wireless Combo Rece... | 620   | usbhid     | 74CFC314C6 |
| 1c4f:0026 | SiGma M... | Keyboard                     | 556   | usbhid     | CF804488DD |
| 0461:0010 | Primax ... | HP PR1101U / Primax PMX-K... | 551   | usbhid     | 56EDF0B800 |
| 045e:07b2 | Microsoft  | 2.4GHz Transceiver v8.0 u... | 487   | usbhid     | 0C14FFD402 |
| 048d:8297 | Integra... | IT8297 RGB LED Controller    | 478   | usbhid     | 6B471BC42D |
| 04d9:1603 | Holtek ... | Keyboard                     | 468   | usbhid     | 75B3FF1C27 |
| 1a2c:0e24 | China R... | USB Keyboard                 | 459   | usbhid     | 01A3346D88 |
| 1a2c:2c27 | China R... | USB Keyboard                 | 426   | usbhid     | CF2BC09886 |
| 0c45:7603 | Microdia   | USB Keyboard                 | 422   | usbhid     | 32F01CCAAB |
| 03f0:0024 | Hewlett... | KU-0316 Keyboard             | 420   | usbhid     | B2D3620851 |
| 046d:c539 | Logitech   | USB Receiver                 | 396   | usbhid     | ECC4515014 |
| 258a:0001 | SINO WE... | USB KEYBOARD                 | 389   | usbhid     | 7A70FC2989 |
| 046d:c517 | Logitech   | LX710 Cordless Desktop Laser | 381   | usbhid     | 50B1B1A6C5 |
| 04d9:1503 | Holtek ... | Keyboard                     | 380   | usbhid     | DE9D0646DA |
| 1a2c:4c5e | China R... | USB Keyboard                 | 362   | usbhid     | 93DE1508CB |
| 045e:07f8 | Microsoft  | Wired Keyboard 600 (model... | 357   | usbhid     | FBCB5D8594 |
| 062a:4c01 | MosArt ... | 2,4Ghz Wireless Transceiv... | 344   | usbhid     | AADCA45789 |
| 045e:07fd | Microsoft  | Nano Transceiver 1.1         | 338   | usbhid     | EC8AF5F350 |
| 04b3:3025 | IBM        | NetVista Full Width Keyboard | 316   | usbhid     | D6237E9949 |
| 062a:5918 | MosArt ... | 2.4G Keyboard Mouse          | 316   | usbhid     | 497BF56CC6 |
| 1050:0407 | Yubico.com | Yubikey 4/5 OTP+U2F+CCID     | 311   | usbhid     | BEE34D8394 |
| 045e:00db | Microsoft  | Natural Ergonomic Keyboar... | 305   | usbhid     | ECAEB257A3 |
| 0518:0001 | EzKEY      | USB to PS2 Adaptor v1.09     | 290   | usbhid     | 10C1E2B304 |
| 258a:1006 | SINO WE... | USB KEYBOARD                 | 285   | usbhid     | 3ABF73FB8A |
| 24ae:2000 | Shenzhe... | 2.4G Wireless Device Serial  | 281   | usbhid     | A7DAB352D6 |
| 045e:0750 | Microsoft  | Wired Keyboard 600           | 280   | usbhid     | 6E1FBE4DDE |
| 0a5c:4502 | Broadcom   | Keyboard (Boot Interface ... | 272   | usbhid     | C319EC4A5F |
| 1ea7:0066 | SHARKOO... | [Mediatrack Edge Mini Key... | 272   | usbhid     | E04A41FC30 |
| 046d:c31d | Logitech   | Media Keyboard K200          | 268   | usbhid     | 6C7ECC284B |
| 1a2c:0c21 | China R... | USB Keyboard                 | 265   | usbhid     | 4F5C7DDE74 |
| 046a:0023 | Cherry     | Keyboard                     | 260   | usbhid     | E757687F86 |
| 28de:1142 | Valve S... | Wireless Steam Controller    | 256   | usbhid     | 2D4144D0B9 |
| 0458:6001 | KYE Sys... | GF3000F Ethernet Adapter     | 248   | usbhid     | 2DB4EBB6EF |
| 046d:c328 | Logitech   | Corded Keyboard K280e        | 247   | usbhid     | 8A6B85A2D2 |
| 046d:c312 | Logitech   | DeLuxe 250 Keyboard          | 241   | usbhid     | E49216D0BB |
| 05ac:024f | Apple      | Aluminium Keyboard (ANSI)    | 241   | usbhid     | 82E27C0415 |
| 046d:c318 | Logitech   | Illuminated Keyboard         | 240   | usbhid     | EAF4F27F7A |
| 25a7:fa61 | Areson ... | Elecom Co., Ltd MR-K013 M... | 237   | usbhid     | 0071FAABAC |
| 413c:8161 | Dell       | Integrated Keyboard          | 234   | usbhid     | 5A8280A663 |
| 0b05:1866 | ASUSTek... | N-KEY Device                 | 230   | usbhid     | 32F01CCAAB |
| 0e6a:02c0 | Megawin... | Defender Gaming Keyboard     | 227   | usbhid     | 0E8D69E9B8 |
| 2516:0051 | Cooler ... | AMD SR4 lamplight Control    | 223   | usbhid     | 86F08832C0 |
| 413c:2106 | Dell       | QuietKey Keyboard            | 217   | usbhid     | 80FB4514C5 |
| 09da:0260 | A4Tech     | KV-300H Isolation Keyboard   | 210   | usbhid     | 6D4DC3E8AF |
| 1a2c:0c23 | China R... | USB Keyboard                 | 210   | usbhid     | F493A9D83B |
| 04f2:0833 | Chicony... | KU-0833 Keyboard             | 204   | usbhid     | 9B5832381A |
| 045e:07a5 | Microsoft  | Wireless Receiver 1461C      | 203   | usbhid     | 514267F2D8 |
| 413c:2105 | Dell       | Model L100 Keyboard          | 199   | usbhid     | 4B09579E42 |
| 1d57:fa20 | Xenta      | 2.4GHz Wireless Reciever ... | 196   | usbhid     | 314ABB1FF1 |
| 03f0:034a | Hewlett... | Elite Keyboard               | 191   | usbhid     | BE8B71D264 |
| 048d:c100 | Integra... | ITE Device(8910)             | 188   | usbhid     | 3CDC08297E |
| 046b:ff10 | America... | Virtual Keyboard and Mouse   | 182   | usbhid     | 451F363726 |
| 2a7a:9a18 | CASUE      | USB Keyboard                 | 181   | usbhid     | 84968F77F9 |
| 046d:c33a | Logitech   | G413 Gaming Keyboard         | 176   | usbhid     | 8DD5924480 |
| 258a:002a | SINO WE... | Gaming KB                    | 175   | usbhid     | 17B2218DAB |
| 3938:1032 | MOSART ... | 2.4G RF Keyboard & Mouse     | 175   | usbhid     | 1A267B14D3 |
| 1a2c:4094 | China R... | USB Keyboard                 | 171   | usbhid     | 17892FBF03 |
| 2717:ff40 | Xiaomi     | Mi/Redmi series (MTP)        | 170   | usbfs      | A9908463D8 |
| 413c:2010 | Dell       | Keyboard                     | 170   | usbhid     | D926705B17 |
| 0e8f:0022 | GreenAsia  | multimedia keyboard contr... | 169   | usbhid     | 0A4D7FB95D |
| 062a:3286 | MosArt ... | Nano Receiver [Sandstrom ... | 166   | usbhid     | 4299904C4D |
| 17ef:602d | Lenovo     | Black Silk Keyboard          | 166   | usbhid     | FB267CA5AE |
| 413c:2005 | Dell       | RT7D50 Keyboard              | 166   | usbhid     | A1D5EA2503 |
| 046d:c315 | Logitech   | Classic Keyboard 200         | 163   | usbhid     | DFA80F4B9F |
| 0557:2419 | ATEN In... | Virtual mouse/keyboard de... | 163   | usbhid     | 9EFBA142DD |
| 062a:0201 | MosArt ... | Defender Office Keyboard ... | 160   | usbhid     | 7A2EC5ECFF |
| 0c45:5004 | Microdia   | Redragon Mitra RGB Keyboard  | 160   | usbhid     | C483A48272 |
| 1d57:fa60 | Xenta      | 2.4G Wireless Mouse          | 160   | usbhid     | 9A707E937A |
| 045e:0800 | Microsoft  | Wireless keyboard (All-in... | 159   | usbhid     | 111E98DDEF |
| 0603:00f2 | Novatek... | Keyboard (Labtec Ultra Fl... | 158   | usbhid     | 82B124D8C4 |
| 045e:00dd | Microsoft  | Comfort Curve Keyboard 20... | 157   | usbhid     | 11CD74E647 |
| 1b1c:1b3d | Corsair    | Corsair Corsair Gaming K5... | 157   | usbhid     | 8F5AD2889E |
| 258a:0016 | BY Tech    | Usb Gaming Keyboard          | 156   | usbhid     | 0DFE108C69 |
| 1997:2433 | Shenzhe... | wireless mini keyboard wi... | 155   | usbhid     | DD513D338C |
| 0e8f:00a7 | GreenAsia  | 2.4G RX                      | 153   | usbhid     | A84CB3EE36 |
| 24ae:2010 | Shenzhe... | Rapoo 2.4G Wireless Device   | 152   | usbhid     | 9E0858267B |
| 03f0:a407 | Hewlett... | Wireless Optical Comfort ... | 151   | usbhid     | E37216CFA8 |
| 13ba:0018 | PCPlay     | Barcode PCP-BCG4209          | 150   | usbhid     | EC41EEB7C0 |
| 413c:8505 | Dell       | Universal Receiver           | 150   | usbhid     | 04C5F1689D |
| 1a81:1004 | Holtek ... | Wireless Dongle 2.4 GHZ H... | 148   | usbhid     | 60D72BDCE7 |
| 045e:0752 | Microsoft  | Wired Keyboard 400           | 145   | usbhid     | F3B1068713 |
| 046a:0011 | Cherry     | G83 (RS 6000) Keyboard       | 145   | usbhid     | FBD2076EEE |
| 05ac:0291 | Apple      | Internal Keyboard / Trackpad | 145   | usbhid     | 5BE083EDAB |
| 17ef:608c | Lenovo     | Calliope USB Keyboard        | 145   | usbhid     | 243713E97A |
| 046a:b090 | Cherry     | Keyboard                     | 143   | usbhid     | 36BF6DAB37 |

### Input/mouse (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 093a:2510 | Pixart ... | Optical Mouse                | 4028  | usbhid     | 068BEE7912 |
| 046d:c077 | Logitech   | M105 Optical Mouse           | 3319  | usbhid     | 427C8B8D8F |
| 046d:c52f | Logitech   | Unifying Receiver            | 3117  | usbhid     | 588CEFB67B |
| 1ea7:0064 | SHARKOO... | 2.4GHz Wireless rechargea... | 1743  | usbhid     | 707F27E3E8 |
| 0458:003a | KYE Sys... | NetScroll+ Mini Traveler ... | 1676  | usbhid     | 7A2E7C66E9 |
| 275d:0ba6 |            | USB OPTICAL MOUSE            | 1517  | usbhid     | 7095848F26 |
| 046d:c05a | Logitech   | M90/M100 Optical Mouse       | 1391  | usbhid     | 342CCD2ECF |
| 1bcf:0005 | Sunplus... | Optical Mouse                | 1344  | usbhid     | 24974BE67E |
| 1c4f:0034 | SiGma M... | XM102K Optical Wheel Mouse   | 1168  | usbhid     | C319EC4A5F |
| 0000:0538 |            | USB OPTICAL MOUSE            | 1094  | usbhid     | 51862605EF |
| 248a:8367 | Maxxter    | Telink Wireless Receiver     | 847   | usbhid     | B5BD43E606 |
| 09da:000a | A4Tech     | Optical Mouse Opto 510D /... | 833   | usbhid     | 863C87266B |
| 18f8:0f97 | [Maxxter]  | Optical Gaming Mouse [Xtrem] | 819   | usbhid     | 7463FACB20 |
| 0000:3825 |            | USB OPTICAL MOUSE            | 770   | usbhid     | 8948989999 |
| 093a:2521 | Pixart ... | Optical Mouse                | 740   | usbhid     | 93FBAD33CF |
| 413c:301a | Dell       | Dell MS116 Optical Mouse     | 706   | usbhid     | 6978CD209F |
| 25a7:fa23 | Areson ... | 2.4G Receiver                | 704   | usbhid     | C96A2AA7A8 |
| 248a:8514 | Maxxter    | Wireless Receiver            | 679   | usbhid     | AC22E27954 |
| 045e:00cb | Microsoft  | Basic Optical Mouse v2.0     | 650   | usbhid     | 370DDA1922 |
| 062a:4102 | MosArt ... | Wireless Mouse               | 579   | usbhid     | 3377403E20 |
| 3938:1031 | MOSART ... | 2.4G Wireless Mouse          | 546   | usbhid     | D954A6BA33 |
| 046d:c016 | Logitech   | Optical Wheel Mouse          | 540   | usbhid     | 967427D98C |
| 18f8:0f99 | [Maxxter]  | Optical gaming mouse         | 462   | usbhid     | 6CEE757CF0 |
| 10c4:8108 | Silicon... | USB OPTICAL MOUSE            | 457   | usbhid     | 01A3346D88 |
| 10c4:8105 | Silicon... | USB OPTICAL MOUSE            | 454   | usbhid     | 5CA23CF3F6 |
| 09da:c10a | A4Tech     | USB Mouse                    | 447   | usbhid     | 9347A8D008 |
| 045e:0040 | Microsoft  | Wheel Mouse Optical          | 441   | usbhid     | EF87C7EE7B |
| 046d:c050 | Logitech   | RX 250 Optical Mouse         | 439   | usbhid     | 99FB47DC2B |
| 046d:c018 | Logitech   | Optical Wheel Mouse          | 426   | usbhid     | F493A9D83B |
| 0458:0186 | KYE Sys... | Genius DX-120 Mouse          | 414   | usbhid     | B92CD04EE7 |
| 248a:8366 | Maxxter    | Wireless Optical Mouse AC... | 414   | usbhid     | 1310B8ABF4 |
| 046d:c05b | Logitech   | M-U0004 810-001317 [B110 ... | 407   | usbhid     | F3E5EBA0C2 |
| 1bcf:0007 | Sunplus... | Optical Mouse                | 389   | usbhid     | 0D99C162A3 |
| 046d:c069 | Logitech   | M-U0007 [Corded Mouse M500]  | 385   | usbhid     | FBAA649304 |
| 1a2c:0042 | China R... | Usb Mouse                    | 385   | usbhid     | F1D3A975C0 |
| 046d:c332 | Logitech   | G502 Proteus Spectrum Opt... | 345   | usbhid     | 8F364E1E1D |
| 0461:4d0f | Primax ... | HP Optical Mouse             | 333   | usbhid     | 69C8804209 |
| 046d:c084 | Logitech   | G203 Gaming Mouse            | 331   | usbhid     | AA747D41F1 |
| 046d:c08b | Logitech   | G502 SE HERO Gaming Mouse    | 327   | usbhid     | 77006702F8 |
| 17ef:6019 | Lenovo     | M-U0025-O Mouse              | 323   | usbhid     | D6237E9949 |
| 046d:c03e | Logitech   | Premium Optical Wheel Mou... | 305   | usbhid     | 8216F8BFAE |
| 0a5c:4503 | Broadcom   | Mouse (Boot Interface Sub... | 274   | usbhid     | C319EC4A5F |
| 15d9:0a4f | Trust I... | Optical Mouse                | 273   | usbhid     | 783D081B5A |
| 258a:1007 | SINOWEALTH | Wired Gaming Mouse           | 270   | usbhid     | 7070F2EAF3 |
| 17ef:608d | Lenovo     | Optical Mouse                | 263   | usbhid     | 243713E97A |
| 2188:0ae1 | No brand   | USB OPTICAL MOUSE            | 258   | usbhid     | 0AC8E061F1 |
| 0101:0007 |            | USB OPTICAL MOUSE            | 256   | usbhid     | 5C44D1E88B |
| 046d:c00e | Logitech   | M-BJ58/M-BJ69 Optical Whe... | 251   | usbhid     | DFA80F4B9F |
| 046d:c53f | Logitech   | USB Receiver                 | 250   | usbhid     | 1069B24865 |
| 046d:c062 | Logitech   | M-UAS144 [LS1 Laser Mouse]   | 249   | usbhid     | 5750588053 |
| 03f0:094a | Hewlett... | Optical Mouse [672662-001]   | 248   | usbhid     | BB6DE8B3E0 |
| 04f3:0235 | Elan Mi... | Optical Mouse                | 248   | usbhid     | 997A879973 |
| 046d:c542 | Logitech   | Wireless Receiver            | 238   | usbhid     | 8CDB34DBC8 |
| 413c:8162 | Dell       | Integrated Touchpad [Syna... | 234   | usbhid     | 5A8280A663 |
| 046d:c408 | Logitech   | Marble Mouse (4-button)      | 230   | usbhid     | 287D0004F3 |
| 046d:c07e | Logitech   | G402 Gaming Mouse            | 223   | usbhid     | 3729813684 |
| 03f0:134a | Hewlett... | Optical Mouse                | 221   | usbhid     | B396E1C4F4 |
| 046d:c246 | Logitech   | Gaming Mouse G300            | 217   | usbhid     | 6014D2DA08 |
| 04d9:a09f | Holtek ... | E-Signal LUOM G10 Mechani... | 204   | usbhid     | D4F86565B3 |
| 192f:0916 | Avago T... | ADNS-2710 Optical Mouse C... | 203   | usbhid     | DC24D5D19F |
| 04b3:310c | IBM        | Wheel Mouse                  | 201   | usbhid     | 2590EC6A56 |
| 1bcf:08a0 | Sunplus... | Gaming mouse [Philips SPK... | 195   | usbhid     | 0F6D7BCF66 |
| 1c4f:0003 | SiGma M... | HID controller               | 192   | usbhid     | FF796824D2 |
| 046d:c537 | Logitech   | Cordless Mouse Receiver      | 190   | usbhid     | FBE1D68B82 |
| 15d9:0a4d | Trust I... | Optical Mouse                | 190   | usbhid     | 3A35B86AAA |
| 1532:005c | Razer USA  | DeathAdder Elite             | 188   | usbhid     | F1AA7841AD |
| 062a:4106 | MosArt ... | Wireless Mouse 2.4G          | 184   | usbhid     | 9B324D7185 |
| 045e:0084 | Microsoft  | Basic Optical Mouse          | 180   | usbhid     | CFDD30C7C7 |
| 13ee:0001 | MosArt     | Optical Mouse                | 176   | usbhid     | 4768B805FF |
| 276d:1160 | YSTEK      | G Mouse                      | 175   | usbhid     | 045B2CD511 |
| 0e8f:00fb | GreenAsia  | USB Mouse                    | 171   | usbhid     | 4A4F239E4D |
| 192f:0416 | Avago T... | ADNS-5700 Optical Mouse C... | 170   | usbhid     | 83DF635945 |
| 15d9:0a4c | Trust I... | USB+PS/2 Optical Mouse       | 166   | usbhid     | B6ADDF8D7B |
| 04f2:0939 | Chicony... | Amazon Basics mouse          | 165   | usbhid     | 8DE72FD346 |
| 413c:3012 | Dell       | Optical Wheel Mouse          | 165   | usbhid     | F7EE091AE1 |
| 046d:c07d | Logitech   | G502 Mouse                   | 164   | usbhid     | B9C2FEC8AA |
| 04b4:0060 | Cypress... | Wireless optical mouse       | 155   | usbhid     | 522367965D |
| 045e:0039 | Microsoft  | IntelliMouse Optical         | 151   | usbhid     | 9BBF3BEFAB |
| 0461:4d22 | Primax ... | USB Optical Mouse            | 145   | usbhid     | 7CA61CA6E1 |
| 413c:301d | Dell       | Universal Receiver           | 144   | usbhid     | D4EE4BA59F |
| 24ae:1100 | Shenzhe... | 2.4G Wireless Device         | 143   | usbhid     | EB594B6EB5 |
| 17ef:602e | Lenovo     | USB Optical Mouse            | 142   | usbhid     | 4EA9AE9F30 |
| 045e:0083 | Microsoft  | Basic Optical Mouse          | 139   | usbhid     | 099B6F5EBB |
| 093a:2533 | Pixart ... | Gaming Mouse                 | 139   | usbhid     | 36ACEDB60B |
| 1a2c:0044 | China R... | Usb Mouse                    | 139   | usbhid     | 8C0EB7F583 |
| 413c:3016 | Dell       | Optical 5-Button Wheel Mouse | 139   | usbhid     | A1D5EA2503 |
| 3938:1080 | YK         | 2.4G Wireless Device         | 137   | usbhid     | FF8EC660B8 |
| 046d:c526 | Logitech   | Nano Receiver                | 134   | usbhid     | BC0BFCD534 |
| 046d:c03d | Logitech   | M-BT96a Pilot Optical Mouse  | 133   | usbhid     | CE787D81EF |
| 05ac:0304 | Apple      | Mighty Mouse [Mitsumi, M1... | 131   | usbhid     | 0F2394B49D |
| 0461:4e22 | Primax ... | Dell Mouse, 2 Buttons, Mo... | 128   | usbhid     | BD1CB6F826 |
| 1b1c:1b3c | Corsair    | Gaming HARPOON RGB Mouse     | 126   | usbhid     | BD2E23A97B |
| 1d57:0008 | Xenta      | 2.4G Wireless Optical Mouse  | 126   | usbhid     | 9F298535A5 |
| 045e:076c | Microsoft  | Comfort Mouse 4500           | 124   | usbhid     | 6EEF53AC22 |
| 1c4f:0048 | SiGma M... | Usb Mouse                    | 124   | usbhid     | 3BFB2E5E7B |
| 045e:0797 | Microsoft  | Optical Mouse 200            | 123   | usbhid     | 6E3084CF7F |
| 046d:c083 | Logitech   | G403 Prodigy Gaming Mouse    | 123   | usbhid     | 5A5D3A54C3 |
| 09da:2403 | A4Tech     | 2.4G Device                  | 123   | usbhid     | A35AAAEB6D |
| 413c:8158 | Dell       | Integrated Touchpad / Tra... | 122   | usbhid     | 69DC8FEFA7 |
| 1d57:ad17 | Xenta      | ZELOTES GAME MOUSE           | 121   | usbhid     | 6163DE66F1 |

### Isdn adapter (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| ffff:ffff | RAPOO      | AVM A1 PCMCIA                | 11    | usbhid     | 3C03CE796F |
| 0681:0002 | Siemens... | Gigaset 3075 Passive ISDN    | 1     | bas_gig... | B11EDA70A9 |

### Joystick (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:02ea | Microsoft  | Xbox One S Controller        | 107   | xpad       | E348A818BD |
| 045e:02d1 | Microsoft  | Xbox One Controller          | 34    | xpad       | 477512BA5C |
| 24c6:581a | ThrustM... | XB1 Classic controller       | 27    | xpad       | 6B0A992D9F |
| 044f:b687 | ThrustM... | TWCS Throttle                | 12    | usbhid     | A635A3ACB3 |
| 068e:00f2 | CH Prod... | Flight Sim Pedals            | 9     | usbhid     | 5E6A1D1926 |
| 0e6f:02b8 | Logic3     | Afterglow Wired Controlle... | 9     | xpad       | 2E9BB335EE |
| 24c6:530a | ThrustM... | ProEX Controller for Xbox... | 8     | xpad       | 983C46DBBE |
| 2341:8037 | Arduino SA | Arduino Micro                | 7     | usbhid     | 3DFFE46C47 |
| 07b5:0317 | Mega Wo... | USB Game Controllers         | 6     | usbhid     | 78FC18FCF4 |
| 28de:1102 | Valve S... | Wired Controller             | 6     | usbhid     | D482D475F7 |
| 046d:c213 | Logitech   | J-UH16 (Freedom 2.4 Cordl... | 5     | usbhid     | 6F0E81A6D9 |
| 046d:c262 | Logitech   | G920 Driving Force Racing... | 5     | usbhid     | F32B55643E |
| 0e6f:02a4 | Logic3     | PDP Wired Controller for ... | 5     | xpad       | 7CCAB1854D |
| 145f:01bb | Trust      | Gamepad                      | 5     | usbhid     | 4A611B712A |
| 1532:0a14 | Razer USA  | Razer Wolverine Ultimate     | 5     | xpad       | E9139E2C55 |
| 06a3:0109 | Saitek     | P880 Pad                     | 4     | usbhid     | 40210AAF34 |
| 06a3:0c2d | Saitek     | Pro Flight Quadrant          | 4     | usbhid     | 4D4959DF32 |
| 0e6f:02a2 | Logic3     | PDP Wired Controller for ... | 4     | xpad       | BB2FD997AB |
| 0458:1004 | KYE Sys... | Flight2000 F-23 Joystick     | 3     | usbhid     | 0C5BDA9187 |
| 045e:000e | Microsoft  | SideWinder?� Freestyle Pro   | 3     | usbhid     | 29CD216C62 |
| 04d8:fd0a | Microch... | Lexip Gaming                 | 3     | usbhid     | F36828F316 |
| 0738:1302 | Mad Catz   | F.L.Y.5 Stick                | 3     | usbhid     | FBAF774D0B |
| 0e6f:0119 | Logic3     | wireless controller for PS3  | 3     | usbhid     | 300431594A |
| 0e6f:02c6 | Logic3     | PDP Deluxe Wired Controll... | 3     | xpad       | 7F349B8B8D |
| 12bd:a02f | Gembird    | 5-Axis,12-Button with POV    | 3     | usbhid     | B723B19A29 |
| 20bc:5500 | ShenZhe... | Frostbite controller         | 3     | usbhid     | 71733FBF6F |
| 231d:1105 | www.vkb... | GTX Throttle                 | 3     | usbhid     | 417453E269 |
| 0428:4001 | Advance... | GamePad Pro                  | 2     | usbhid     | B33486C990 |
| 044f:0407 | ThrustM... | TCA Q-Eng 1&2                | 2     | usbhid     | 15FA98AA93 |
| 044f:b323 | ThrustM... | Dual Trigger 3-in-1 (PC M... | 2     | usbhid     | D36AA4ED19 |
| 044f:d007 | ThrustM... | T Mini Wireless              | 2     | usbhid     | E06775BBD6 |
| 046d:c211 | Logitech   | iTouch Cordless Receiver     | 2     | usbhid     | DD082AFE88 |
| 054c:03d5 | Sony       | PlayStation Move motion c... | 2     | usbhid     | 32805E80B1 |
| 05ac:056b | Apple      | GameSir-T2a                  | 2     | usbhid     | 912852805F |
| 068e:00f1 | CH Prod... | Pro Throttle                 | 2     | usbhid     | E496AA32C8 |
| 068e:00f3 | CH Prod... | Fighterstick                 | 2     | usbhid     | B87BD193E6 |
| 099a:7010 | Zippy T... | Gaming Keyboard              | 2     | usbhid     | 8D3183F3B8 |
| 0e6f:0139 | Logic3     | Afterglow Wired Controlle... | 2     | xpad       | 17ACFC90D4 |
| 0e6f:0162 | Logic3     | PDP Wired Controller for ... | 2     | xpad       | 09520E9204 |
| 0eb7:183b | Endor      | ClubSportPedal               | 2     | usbhid     | B2DE3AF507 |
| 11ff:001b |            | LS PC Controller             | 2     | usbhid     | B52E5BED36 |
| 20d6:ca6d | Unknown... | Pro Ex                       | 2     | usbhid     | 858605237B |
| 231d:0121 | www.vkb... | VKBsim Gladiator             | 2     | usbhid     | 7BCE3059DC |
| 24c6:542a | ThrustM... | Spectra for Xbox One         | 2     | xpad       | 34A482168B |
| 256f:c62e | 3Dconne... | SpaceMouse Wireless (cabled) | 2     | usbhid     | 7DB180DFDD |
| 2f24:0053 |            | Canyon controller GPW3       | 2     | xpad       | D720268B28 |
| 0079:0122 | DragonRise | Game Controller for PC       | 1     | usbhid     | D4C7126B92 |
| 0079:1803 | DragonRise | Mayflash Wiimote PC Adapter  | 1     | usbhid     | 593BA86C4F |
| 0079:189c | DragonRise | PXN-V3II                     | 1     | xpad       | D90F3585DA |
| 044f:d00e | ThrustM... | eSwap PRO Controller         | 1     | usbhid     | F816144F1B |
| 046d:c20a | Logitech   | WingMan RumblePad            | 1     | usbhid     | B23B139081 |
| 046d:c293 | Logitech   | WingMan Formula Force GP     | 1     | usbhid     | 38E0EE4482 |
| 0583:805e | Padix (... | USB, 4-axis, 4-button joy... | 1     | usbhid     | 838D58EB90 |
| 05b8:0a20 | Agiler     | Steering Wheel               | 1     | usbhid     | 3BD37E342E |
| 061c:0010 | Act Labs   | InterLink                    | 1     | usbhid     | AB314D65BE |
| 062a:2410 | MosArt ... | Wireless PS3 gamepad         | 1     | usbhid     | 14781D6ECE |
| 06a3:0006 | Saitek     | Cyborg Gold Joystick         | 1     | usbhid     | 392A044989 |
| 06a3:0255 | Saitek     | X52 Flight Controller        | 1     | usbhid     | 79777938CC |
| 06a3:053c | Saitek     | X45 Flight Controller        | 1     | usbhid     | 629A45E23D |
| 079d:0a07 | Alfadat... | XBOX Game Device             | 1     | usbhid     | 00579CA792 |
| 0866:0100 | WWW.TUA... | VENOM-X_MOUSE                | 1     | usbhid     | 7A2466E991 |
| 0b43:0003 | Play.com   | PS2 Controller Converter     | 1     | usbhid     | A26AF9A455 |
| 0c12:0e10 | Zeroplus   | P4 Wired Gamepad             | 1     | usbhid     | BBD6DA0DD4 |
| 0e6f:013a | Logic3     | PDP Xbox One Controller      | 1     | xpad       | 41D1A4F015 |
| 0e6f:0229 | Logic3     | Disney Infinity Base         | 1     | xpad       | 7D749B3ECC |
| 0e8f:0013 | GreenAsia  | USB Joystick                 | 1     | usbhid     | 1EAADEB8F4 |
| 0eb7:1a92 | Endor      | ClubSport USB Shifter        | 1     | usbhid     | 3DFFE46C47 |
| 0f0d:005e | Hori       | Fighting Commander 4         | 1     | usbhid     | F232C678DA |
| 11ff:001c |            | PXN-V3II                     | 1     | usbhid     | D1DED92F20 |
| 1209:f00d | InterBi... | Shifter/Pedals Adapter       | 1     | usbhid     | 5AAA478577 |
| 12bd:e001 | Gembird    | PS To USB Converter One P... | 1     | usbhid     | 96C970127E |
| 1532:0705 | Razer USA  | Raiju Mobile Wired           | 1     | usbhid     | 21184F9BA8 |
| 1bad:f025 | Harmoni... | Call of Duty Controller f... | 1     | xpad       | 4625D62A82 |
| 20bc:5501 | Umido      | NeoGeo G1 Pro D-Input        | 1     | usbhid     | 64DB7E90FE |
| 20bc:5656 | ShenZhe... | GC101 Controller 1.03        | 1     | usbhid     | E40A4C5A0C |
| 20bc:aa00 | ShenZhe... | BETOP CONTROLLER             | 1     | usbhid     | 220E504029 |
| 20d6:a713 | Bensuss... | NSW Wired controller         | 1     | usbhid     | C1576F7B77 |
| 214e:0014 | Swiftpoint | Swiftpoint Tracer            | 1     | usbhid     | 0B85AF69C2 |
| 231d:0201 | Alex Oz... | VKBsim Gladiator NXT L       | 1     | usbhid     | 4C87B2FF27 |
| 294b:1900 | Honeyco... | Alpha Flight Controls        | 1     | usbhid     | B2E8193BF3 |
| 2f24:008f |            | GAME FOR WINDOWS             | 1     | xpad       | 29C80ABE49 |

### Mfp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:042a | Hewlett... | LaserJet M1132 MFP           | 43    | usblp      | 522367965D |
| 03f0:222a | Hewlett... | LaserJet Pro MFP M125nw      | 31    | usblp      | DC4A709A3B |
| 03f0:3b17 | Hewlett... | LaserJet M1005 MFP           | 29    | usblp      | B79DCDB648 |
| 03f0:5617 | Hewlett... | LaserJet M1120 MFP           | 22    | usblp      | D0C64B1828 |
| 03f0:622a | Hewlett... | LaserJet MFP M129-M134       | 13    | usblp      | 214D892F21 |
| 03f0:bf2a | Hewlett... | LaserJet MFP M28-M31         | 13    | usblp      | C6B159CA95 |
| 03f0:052a | Hewlett... | LaserJet M1212nf MFP         | 12    | usblp      | 5B4619D24C |
| 0924:3cef | Xerox      | Phaser 3100MFP               | 12    | usblp      | 7AB9D987EB |
| 03f0:ad2a | Hewlett... | ColorLaserJet MFP M278-M281  | 11    | usblp      | 8EA8E6AFE8 |
| 04b8:083f | Seiko E... | Stylus CX4300/CX4400/CX55... | 10    | usblp      | 9473725930 |
| 04b8:084d | Seiko E... | PX-402A [Stylus SX115/Sty... | 10    | usblp      | ACC18F350E |
| 0924:42af | Xerox      | WorkCentre 3045B             | 10    | usblp      | 989A2EAABB |
| 04b8:082f | Seiko E... | PX-A620 [Stylus CX3900/DX... | 9     | usblp      | BC0BFCD534 |
| 03f0:5717 | Hewlett... | LaserJet M1120n MFP          | 7     | usblp      | 44103309B6 |
| 03f0:3b2a | Hewlett... | Color LaserJet MFP M277dw    | 6     | usblp      | A781661029 |
| 0482:0495 | Kyocera    | FS-1020MFP                   | 6     | usblp      | 71AEB24115 |
| 04b8:0841 | Seiko E... | PX-401A [ME 300/Stylus NX... | 5     | usblp      | 31DC2A086D |
| 03f0:062a | Hewlett... | LaserJet 100 colorMFP M175a  | 4     | usblp      | 5B83E2F312 |
| 03f0:2d2a | Hewlett... | LaserJet Pro MFP M225dn      | 4     | usblp      | 1B4BF985A0 |
| 03f0:932a | Hewlett... | LaserJet Pro MFP M26a        | 4     | usblp      | 71A5232043 |
| 03f0:f22a | Hewlett... | Laser MFP 135w               | 4     | usbfs      | B26C826616 |
| 0482:0497 | Kyocera    | FS-1025MFP                   | 4     | usblp      | 6C8DDCD99B |
| 04b8:080e | Seiko E... | PX-A550 [CX-3500/3600/365... | 4     | usblp      | D34B022996 |
| 0924:42da | Xerox      | WorkCentre 3025              | 4     | usblp      | D23574ECF1 |
| 03f0:012a | Hewlett... | LaserJet M1536dnf MFP        | 3     | usblp      | 9849E9DD35 |
| 03f0:0e2a | Hewlett... | Smart Install                | 3     | uas, us... | B027C83F03 |
| 03f0:142a | Hewlett... | LaserJet 400 MFP M425dn      | 3     | usblp      | BB50D755A2 |
| 03f0:242a | Hewlett... | Color LaserJet Pro MFP M176n | 3     | usblp      | 769CB653F7 |
| 03f0:322a | Hewlett... | LaserJet Pro MFP M127fn      | 3     | usblp      | 9FD78FBC60 |
| 0924:3d6f | Xerox      | Phaser 6020                  | 3     | usblp      | 79A097BF6F |
| 0924:42db | Xerox      | WorkCentre 3215              | 3     | usblp      | 0F22425E10 |
| 0924:42dc | Xerox      | WorkCentre 3225              | 3     | usblp      | 585BFD5E2A |
| 03f0:5817 | Hewlett... | LaserJet M1319f MFP          | 2     | usblp      | DD0A730661 |
| 03f0:5a2a | Hewlett... | LaserJet MFP M426fdw         | 2     | usblp      | D00254CBC5 |
| 03f0:642a | Hewlett... | LaserJet MFP M227-M231       | 2     | usblp      | B7CB0C276C |
| 04b8:0818 | Seiko E... | Stylus CX3700/CX3800/DX3800  | 2     | usblp      | D4567C6F8A |
| 0924:42c4 | Xerox      | WorkCentre 3615              | 2     | usblp      | 0BF7A6E91D |
| 413c:523b | Dell       | B1265dfw Mono MFP            | 2     | usblp      | 26B6148847 |
| 03f0:0970 | Hewlett... | ColorLaserJet MFP M282-M285  | 1     | usblp      | 0AD4AA43AA |
| 03f0:1d2a | Hewlett... | Color LaserJet flow MFP M880 | 1     | usblp      | 9F2622FF85 |
| 03f0:252a | Hewlett... | LaserJet 500 colorMFP M570dw | 1     | usblp      | 8EA70251FB |
| 03f0:2e2a | Hewlett... | LaserJet Pro MFP M435nw      | 1     | usblp      | A457D54FAD |
| 03f0:342a | Hewlett... | Color LaserJet MFP M476dn    | 1     | usblp      | F9F42752CA |
| 03f0:362a | Hewlett... | Officejet Color FlowMFP X585 | 1     | usblp      | 4966DF06F4 |
| 03f0:442a | Hewlett... | Color LaserJet Flow MFP M680 | 1     | usblp      | BF4C79032E |
| 03f0:4e17 | Hewlett... | Color LaserJet CM1312 MFP    | 1     | usblp      | 426F11F2D2 |
| 03f0:532a | Hewlett... | LaserJet MFP M426dw          | 1     | usblp      | 93A67E4976 |
| 03f0:5a17 | Hewlett... | Color LaserJet CM2320nf MFP  | 1     | usblp      | 946BA8AA98 |
| 03f0:862a | Hewlett... | Color LaserJet MFP M377dw    | 1     | usblp      | 136E5D26E2 |
| 03f0:9e17 | Hewlett... | LaserJet 500 MFP M525        | 1     | usblp      | 80E0F6373A |
| 03f0:9f17 | Hewlett... | LaserJet 500 color MFP M575  | 1     | usblp      | A043EA04EA |
| 03f0:af2a | Hewlett... | ColorLaserJet MFP M178-M181  | 1     | usblp      | F9F288372E |
| 03f0:d511 | Hewlett... | PageWide Pro 477dw MFP       | 1     | usbfs      | BD95D49C15 |
| 03f0:eb2a | Hewlett... | Color Laser MFP 178nw        | 1     | usblp      | 2FE3E165EB |
| 0924:3d6b | Xerox      | WorkCentre 6505DN            | 1     | usblp      | 66BC368A83 |
| 0924:42d4 | Xerox      | WorkCentre 6027              | 1     | usblp      | E363684B4B |
| 413c:5406 | Dell       | 1355cnw Color MFP            | 1     | usbfs      | EF4245C8A3 |
| 413c:564a | Dell       | C1765nfw Color MFP           | 1     | usblp      | FD8ACE53F7 |
| 413c:564e | Dell       | C2665dnf Color MFP           | 1     | usblp      | 70493B615B |
| 413c:590b | Dell       | MFP                          | 1     | usblp      | 0F4BBAE4FA |

### Miscellaneous (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2d95:600a | vivo       | V2027                        | 9     | rndis_host | ACC6C11A97 |
| 2e04:c008 | HMD Global | Tethering Network Interface  | 4     | rndis_host | C8A59F2F74 |
| 1390:5a01 | TOMTOM     | GO Professional 6250         | 2     | rndis_host | BE27200090 |
| 1e10:4000 | Point G... | U3V camera                   | 2     |            | 2BC5FA3C88 |
| 0bb4:0b0c | HTC (Hi... | Elf / Touch / P3450 / T-M... | 1     | rndis_w... | 5E75A35A7D |
| 1004:6343 | LG Elec... | LM-V600                      | 1     | rndis_h... | B5C18575BF |
| 1410:b022 | Novatel... | MiFi 7000                    | 1     | rndis_h... | 9F5C7C160A |
| 2676:ba05 | Basler     | a2A1920-160ucBAS             | 1     |            | 273BC677CD |
| 2bdf:0001 | Hikrobot   | MV-CB013-20UC-C              | 1     |            | 2690174808 |

### Modem (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 12d1:1506 | Huawei ... | Modem/Networkcard            | 407   | uas, us... | FAF35CB112 |
| 27c6:5395 | Shenzhe... | Fingerprint Reader           | 310   | cdc_acm    | 58E43F0514 |
| 27c6:5301 | Shenzhe... | Fingerprint Reader           | 229   | cdc_acm    | 8F25043C64 |
| 27c6:5385 | Shenzhe... | Fingerprint Reader           | 163   | cdc_acm    | 8956FEE2F3 |
| 0bdb:1911 | Ericsso... | F5521gw                      | 126   | cdc_acm    | 90895AAB86 |
| 0bdb:1926 | Ericsso... | H5321 gw Mobile Broadband... | 115   | cdc_acm    | B868085BFC |
| 0bdb:193e | Ericsso... | N5321 gw                     | 74    | cdc_acm    | 7D6AB19F8D |
| 413c:818d | Dell       | DW5550                       | 60    | cdc_acm    | A1027F938F |
| 2341:0043 | Arduino SA | Uno R3 (CDC ACM)             | 59    | cdc_acm    | A0197C30DB |
| 12d1:1436 | Huawei ... | Broadband stick              | 56    | usb_sto... | BA9A8E1D7A |
| 0bdb:1900 | Ericsso... | F3507g Mobile Broadband M... | 54    | cdc_acm... | C3769F3B77 |
| 03f0:3d1d | Hewlett... | hs2350 HSPA+ MobileBroadband | 51    | cdc_acm    | F66BA65DC8 |
| 03f0:3a1d | Hewlett... | hs2340 HSPA+ mobile broad... | 46    | cdc_acm    | 0B1F6A34CE |
| 413c:818e | Dell       | DW5560 miniPCIe HSPA+ Mob... | 40    | cdc_acm    | A377D34C0D |
| 12d1:1001 | Huawei ... | E161/E169/E620/E800 HSDPA... | 39    | usb_sto... | D507F88A47 |
| 27c6:5381 | Shenzhe... | Fingerprint Reader           | 35    | cdc_acm    | AF1479F2FE |
| 413c:8147 | Dell       | F3507g Mobile Broadband M... | 33    | cdc_ether  | 843B7BD830 |
| 413c:8184 | Dell       | F3607gw v2 Mobile Broadba... | 33    | cdc_acm    | 56AEC59FBB |
| 12d1:1003 | Huawei ... | E220 HSDPA Modem / E230/E... | 27    | usb_sto... | 10ACFF551D |
| 12d1:140c | Huawei ... | E180v                        | 27    | usb_sto... | 37EFD6FC5E |
| 1209:1776 | InterBi... | Io                           | 23    | system7... | F6580E7358 |
| 1546:01a7 | U-Blox     | [u-blox 7]                   | 21    | cdc_acm    | 1BF2275BE4 |
| 0658:0200 | Sigma D... | Aeotec Z-Stick Gen5 (ZW09... | 19    | cdc_acm    | BC7F078524 |
| 12d1:1570 | Huawei ... | MOBILE                       | 17    | option     | 379E9A74C2 |
| 0424:274d | Microch... | HTC Hub Controller           | 16    | cdc_acm    | C198141A8E |
| 0483:5740 | STMicro... | Virtual COM Port             | 16    | cdc_acm    | B961168B44 |
| 1546:01a8 | U-Blox     | [u-blox 8]                   | 15    | cdc_acm    | 07C752AA8C |
| 04e8:6872 | Samsung... | Kiera                        | 14    | cdc_acm    | 200275BBD6 |
| 04d8:00df | Microch... | MCP2200 USB Serial Port E... | 13    | cdc_acm    | 532A08B7C5 |
| 12d1:1404 | Huawei ... | EM770W miniPCI WCDMA Modem   | 13    | usb_sto... | 89B02002A5 |
| 1cf1:0030 | Dresden... | ZigBee gateway [ConBee II]   | 12    | cdc_acm    | C7798BA8D3 |
| 0451:16a8 | Texas I... | CC2531 ZigBee                | 11    | cdc_acm    | 271E56E195 |
| 1366:0105 | SEGGER     | J-Link                       | 10    | cdc_acm    | 2AD271E81F |
| 2341:0042 | Arduino SA | Mega 2560 R3 (CDC ACM)       | 10    | cdc_acm    | 419E0C7EB2 |
| 2833:0051 | Oculus VR  | Rift S                       | 10    | usbhid     | 6014D2DA08 |
| 04e2:1410 | Exar       | XR21V1410 USB-UART IC        | 9     | cdc_acm... | B5BD43E606 |
| 2548:1002 | Pulse-E... | CEC Adapter                  | 9     | cdc_acm    | C7798BA8D3 |
| 0e8d:0003 | MediaTek   | MT6227 phone                 | 8     | cdc_acm... | 78890894DA |
| 19d2:1515 | ZTE WCD... | MF195                        | 8     | cdc_acm    | 3954E61E9A |
| 12d1:14ac | Huawei ... | E815                         | 7     | option     | 8B53FFA4DF |
| 1c11:b04d | Input Club | Keyboard - WhiteFox:truef... | 7     | usbhid     | 0F23806951 |
| 2341:0001 | Arduino SA | Uno (CDC ACM)                | 7     | cdc_acm    | C3E5771D2F |
| 0930:1319 | Toshiba    | H5321gw                      | 6     | cdc_acm    | 9816B952D7 |
| 0bdb:190a | Ericsso... | F3307 Mobile Broadband Mo... | 6     | cdc_acm    | 8D386EA5A9 |
| 1209:2201 | InterBi... | Dygma Shortcut Keyboard      | 6     | usbhid     | CEF9098008 |
| 0603:4001 | Novatek... | NVT-FPR                      | 5     | usbhid     | BB04E3D7E3 |
| 0930:1314 | Toshiba    | F5521gw                      | 5     | cdc_acm    | 6378D53C40 |
| 1546:01a5 | U-Blox     | [u-blox 5]                   | 5     | cdc_acm    | C2D9EFD034 |
| 2886:8027 | Seeed T... | Seeeduino_Cortex_M0+         | 5     | cdc_acm    | 855A10F536 |
| 0483:a26d | STMicro... | USB Watchdog                 | 4     | cdc_acm    | 83857E3215 |
| 04d8:f5fe | Microch... | TrueRNG                      | 4     | cdc_acm    | 07A5B3C465 |
| 04e2:1411 | Exar       | XR21B1411                    | 4     | cdc_acm... | FFC2D5A399 |
| 04e8:6773 | Samsung... | HSPA Modem                   | 4     | cdc_acm    | 2CFD6DD7EE |
| 0bdb:190d | Ericsso... | F5521gw                      | 4     | cdc_acm    | 09CFE58582 |
| 0bdb:1936 | Ericsso... | C5621 gw                     | 4     | cdc_acm    | 06EE7D4C06 |
| 18d1:d001 | Google     | Nexus 4 (fastboot)           | 4     | rndis_host | 2B14368AED |
| 1edf:6004 | Select ... | MCD-640S-1EDF-6004           | 4     | cdc_acm    | F9D3A09989 |
| 2687:fd11 | Fitbit     | Versa 3                      | 4     | cdc_acm    | 0ABD7690C0 |
| 2a03:0043 | dog hunter | Arduino Uno Rev3             | 4     | cdc_acm    | EFCE67D492 |
| 8087:0ab6 | Intel      | UDOO X86                     | 4     | cdc_acm    | 62AE920D77 |
| 03f0:2f1d | Hewlett... | lc2010 Mobile Broadband M... | 3     | cdc_acm    | ADF2557C53 |
| 04e8:6843 | Samsung... | E2530 Phone (Samsung Kies... | 3     | cdc_acm... | 459627EDA2 |
| 0baf:0303 | U.S. Ro... | USR5637 56K Faxmodem         | 3     | cdc_acm    | EEA1F6E691 |
| 0bdb:1902 | Ericsso... | F3507g v2 Mobile Broadban... | 3     | cdc_acm    | 349C20610A |
| 1004:6000 | LG Elec... | Various Mobile Phones        | 3     | cdc_acm    | 0519B9A79C |
| 1004:6169 | LG Elec... | LGE Modem                    | 3     | cdc_ether  | 626D49A6A9 |
| 106c:3714 | Curitel... | PANTECH USB MODEM [UM175]    | 3     | cdc_acm    | F4807D695F |
| 12d1:1573 | Huawei ... | Mobile                       | 3     | option     | 4120FA5430 |
| 12d1:1c1e | Huawei ... | Mass Storage                 | 3     | uas, us... | DDD57927D5 |
| 1519:0020 | Comneon    | HSIC Device                  | 3     | cdc_acm    | E277646CEF |
| 16c0:0483 | Van Ooi... | Teensyduino Serial           | 3     | cdc_acm    | A50C792692 |
| 1eaf:0004 | Leaflabs   | Maple serial interface       | 3     | cdc_acm    | 825C9359F9 |
| 2e8a:0005 | MicroPy... | Board in FS mode             | 3     | cdc_acm    | F1A1A21C56 |
| 03eb:204b | Atmel      | LUFA USB to Serial Adapte... | 2     | cdc_acm    | DAE3697FF8 |
| 0421:0302 | Nokia M... | N8-00                        | 2     | cdc_acm    | 495FCF02B1 |
| 0421:0524 | Nokia M... | Nokia 300                    | 2     | cdc_acm    | 9C1238B041 |
| 0461:0033 | Primax ... | USB_Focus                    | 2     | cdc_acm    | 09C3D95876 |
| 04e2:1412 | Exar       | XR21V1412 USB UART Ch A      | 2     | cdc_acm    | 593A489E8D |
| 0525:a4a7 | Netchip... | Linux-USB Serial Gadget (... | 2     | cdc_acm    | 2541D35BD4 |
| 0525:a4aa | Netchip... | Linux-USB CDC Composite G... | 2     | cdc_acm    | 50BADFB190 |
| 0572:1340 | Conexan... | USB Modem                    | 2     | cdc_acm    | B8A7B6080F |
| 079b:0028 | Sagem      | Modem                        | 2     | cdc_acm    | 9005441938 |
| 0baf:00ec | U.S. Ro... | 56K Faxmodem                 | 2     |            | EF974030B3 |
| 106c:3716 | Curitel... | UMW190 Modem                 | 2     | cdc_acm    | 06FBB87A4E |
| 12d1:1465 | Huawei ... | K3765 HSPA                   | 2     | uas, us... | D99338778F |
| 1366:1015 | SEGGER     | J-Link                       | 2     | cdc_acm    | 6BE76778AE |
| 1546:01a6 | U-Blox     | [u-blox 6]                   | 2     | cdc_acm    | A4AD398189 |
| 1b4f:9206 | SparkFun   | Pro Micro                    | 2     | cdc_acm    | C6B33CF692 |
| 1bbb:2011 | T & A M... | Alcatel_5002R                | 2     | cdc_acm    | B8552BD421 |
| 1cbe:00fd | Luminar... | In-Circuit Debug Interface   | 2     | cdc_acm    | 363320D61E |
| 1d50:6086 | OpenMoko   | OneRNG entropy device        | 2     | cdc_acm    | DAE3697FF8 |
| 1fc9:8125 | NXP Sem... | openSPOT2                    | 2     | cdc_acm    | CAE2DE05FF |
| 2341:003d | Arduino SA | Due Programming Port         | 2     | cdc_acm    | 4A25280BA6 |
| 27b1:0001 | UltiMac... | RAMBo                        | 2     | cdc_acm    | 751345EB91 |
| 2886:802f | Seeed      | XIAO M0                      | 2     | cdc_acm    | 06A3CD7D2F |
| 2ec2:0002 | Loupedeck  | Loupedeck+                   | 2     | snd_usb... | C9F5D6FDD0 |
| 8087:095a | Intel      | MODEM + 2 CDC-ACM + 3 CDC... | 2     | cdc_ncm    | 7154F86BD2 |
| 03eb:2404 | Atmel      | The Micro                    | 1     | cdc_acm    | FF465CB33F |
| 03eb:6124 | Atmel      | at91sam SAMBA bootloader     | 1     | cdc_acm    | 2BF3A4DEF3 |
| 0416:5011 | Winbond... | Virtual Com Port             | 1     | cdc_acm    | 913D5AFF80 |

### Net/ethernet (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0fe6:9900 | ICS Advent | 10/100M LAN                  | 13    | cdc_ether  | 0C261084DB |
| 0bda:8156 | Realtek... | USB 10/100/1G/2.5G LAN       | 12    | r8152      | B8DB87E047 |
| 03f0:911d | Hewlett... | lt4211 Gobi 4G Module        | 7     | cdc_ether  | 0AD916110D |
| 17e9:430a | Display... | HP Port Replicator (Compo... | 3     | cdc_ncm    | F02A4A5E93 |
| 17e9:436c | Display... | Dell D1000 USB3.0 Dock       | 3     | cdc_ncm    | 1E6CBEB181 |
| 17ef:721e | Lenovo     | Powered Hub                  | 3     | r8152      | F4F26A9357 |
| 2eca:c101 | Aquantia   | 5G USB Ethernet Adapter      | 3     | aqc111     | 5909EA8D8D |
| 0424:9500 | Microch... | LAN9500/LAN9500i             | 2     | smsc95xx   | 2F9F2D0497 |
| 0424:9e00 | Microch... | LAN9500A/LAN9500Ai           | 2     | smsc95xx   | 9F69E439BC |
| 17e9:431f | Display... | ThinkPad Basic USB 3.0 Dock  | 2     | cdc_ncm... | C9837EF0C1 |
| 17e9:4340 | Display... | ThinkPad USB 3.0 Ultra Dock  | 2     | snd_usb... | 04852A18CB |
| 1c04:0015 | QNAP Sy... | QNAP QNA-UC5G1T USB to 5G... | 2     | aqc111     | D391C49614 |
| 03f0:0547 | Hewlett... | L2311c LAN7500 Ethernet      | 1     |            | EBB304F58E |
| 03f0:0857 | Hewlett... | lt4220 Snapdragon X12 LTE    | 1     | cdc_ether  | 54BAAAD690 |
| 045e:09a0 | Microsoft  | USB 10/100/1000 LAN          | 1     | cdc_ether  | C8FB985280 |
| 056e:4007 | Elecom     | WDC-433DU2HBK                | 1     | rtl8812au  | 4F8794ED64 |
| 0df6:0072 | Sitecom... | AX88179 Gigabit Ethernet ... | 1     | ax88179... | 85C6FB8933 |
| 17e9:433e | Display... | dynadock 4K                  | 1     | cdc_ncm    | FDC926F819 |
| 17e9:6008 | Display... | Targus USB3 DV4K DOCK w P... | 1     | cdc_ncm... | C503EFCF6C |
| 17ef:3052 | Lenovo     | ThinkPad TabletDock          | 1     | cdc_ether  | 1D6F4C02A1 |
| 17ef:3098 | Lenovo     | Mini Dock                    | 1     | cdc_ether  | 534A4C683F |
| 2001:b301 | D-Link     | DUBE250 2.5GbE Adapter       | 1     | cdc_ncm    | 4DC4A0EFE0 |

### Net/wimax (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0186 | Intel      | WiMAX Connection 2400m       | 57    | i2400m_usb | 2D0B219A36 |
| 8086:0180 | Intel      | WiMAX Connection 2400m       | 55    | i2400m_usb | FFB279A366 |
| 8086:1406 | Intel      | WiMAX Connection 2400m       | 44    | i2400m_usb | 787FE33124 |
| 8087:07d6 | Intel      | Centrino Wireless-N + WiM... | 44    | i2400m_usb | A610876405 |
| 8086:0188 | Intel      | WiMAX Connection 2400m       | 19    | i2400m_usb | 2495309045 |
| 8086:0187 | Intel      | Centrino Advanced-N + WiM... | 14    | i2400m_usb | 33137C7C23 |
| 8086:0182 | Intel      | WiMAX Connection 2400m       | 2     | i2400m_usb | 01517BE2D7 |

### Net/wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 148f:7601 | Ralink ... | MT7601U Wireless Adapter     | 1075  | mt7601u    | E52E9002D0 |
| 0bda:8179 | Realtek... | RTL8188EUS 802.11n Wirele... | 981   | r8188eu    | 1161AF8368 |
| 0cf3:9271 | Qualcom... | AR9271 802.11n               | 716   | ath9k_htc  | 40C84C9637 |
| 0bda:b812 | Realtek... | RTL88x2bu [AC1200 Techkey]   | 503   | 88x2bu     | 543E15E027 |
| 148f:5370 | Ralink ... | RT5370 Wireless Adapter      | 501   | rt2800usb  | CFA7B4AF8F |
| 148f:3070 | Ralink ... | RT2870/RT3070 Wireless Ad... | 461   | rt2800usb  | 2A39EF919C |
| 0bda:8178 | Realtek... | RTL8192CU 802.11n WLAN Ad... | 398   | rtl8192... | C96A2AA7A8 |
| 2357:0109 | TP-Link    | TL-WN823N v2/v3 [Realtek ... | 317   | rtl8xxxu   | FF796824D2 |
| 0bda:c811 | Realtek... | 802.11ac NIC                 | 308   | 8821cu     | 2CCAE0040C |
| 0bda:8176 | Realtek... | RTL8188CUS 802.11n WLAN A... | 306   | rtl8192... | B7DF25BA5D |
| 2357:010c | TP-Link    | TL-WN722N v2/v3 [Realtek ... | 225   | r8188eu    | 5EAD0CA3AD |
| 0bda:f179 | Realtek... | RTL8188FTV 802.11b/g/n 1T... | 211   | rtl8188fu  | 84968F77F9 |
| 0bda:8189 | Realtek... | RTL8187B Wireless 802.11g... | 207   | rtl8187    | C0FAA178A2 |
| 0bda:818b | Realtek... | RTL8192EU 802.11b/g/n WLA... | 199   | rtl8xxxu   | E766BCBB62 |
| 045e:0719 | Microsoft  | Xbox 360 Wireless Adapter    | 170   | xpad       | 7070F2EAF3 |
| 0bda:8812 | Realtek... | RTL8812AU 802.11a/b/g/n/a... | 165   | 8812au     | 21C683ED97 |
| 2357:011e | TP-Link    | AC600 wireless Realtek RT... | 165   | 88XXau     | 8C2B6CF453 |
| 0bda:8187 | Realtek... | RTL8187 Wireless Adapter     | 153   | rtl8187    | 966B07A428 |
| 0bda:8172 | Realtek... | RTL8191SU 802.11n WLAN Ad... | 140   | r8712u     | 07E2A98918 |
| 148f:5572 | Ralink ... | RT5572 Wireless Adapter      | 134   | rt2800usb  | ECC4515014 |
| 7392:7811 | Edimax ... | EW-7811Un 802.11n Wireles... | 132   | rtl8192... | 31AC5CDF6E |
| 0bda:a811 | Realtek... | RTL8811AU 802.11a/b/g/n/a... | 121   | 88XXau     | FE1E002CB0 |
| 148f:761a | Ralink ... | MT7610U ("Archer T2U" 2.4... | 118   | mt76x0u    | ADFE19C61C |
| 148f:5372 | Ralink ... | RT5372 Wireless Adapter      | 111   | rt2800usb  | 00FE3AD0A4 |
| 2357:0107 | TP-Link    | TL-WN821N v5/v6 [RTL8192EU]  | 108   | rtl8xxxu   | 798A613FA7 |
| 148f:2573 | Ralink ... | RT2501/RT2573 Wireless Ad... | 99    | rt73usb    | 534A66A78E |
| 413c:81b6 | Dell       | DW5811e Snapdragonâ¢ ... | 96    | qcseria... | E7A049A026 |
| 0bda:0811 | Realtek... | Realtek 8812AU/8821AU 802... | 92    | rtl8812au  | 406FCB6975 |
| 1199:9079 | Sierra ... | EM7455                       | 88    | qcseria... | 8A52B831D7 |
| 0846:9053 | NetGear    | A6210                        | 86    | mt76x2u    | 93FBAD33CF |
| 2357:012d | TP-Link    | Archer T3U [Realtek RTL88... | 80    | 88x2bu     | 0F2394B49D |
| 0bda:8171 | Realtek... | RTL8188SU 802.11n WLAN Ad... | 77    | r8712u     | 3FF4BE2B55 |
| 0b05:17ba | ASUSTek... | N10 Nano 802.11n Network ... | 76    | rtl8192cu  | 7A0EA791BE |
| 07d1:3c0a | D-Link ... | DWA-140 RangeBooster N Ad... | 75    | rt2800usb  | 1161032A20 |
| 2001:3319 | D-Link     | DWA-131 Wireless N Nano A... | 75    | rtl8xxxu   | 9FC60B0BA8 |
| 0846:9052 | NetGear    | A6100 AC600 DB Wireless A... | 74    | 8812au     | 68BF7D6DF3 |
| 2357:0115 | TP-Link    | Archer T4U ver.3             | 73    | 88x2bu     | 219A3A234F |
| 045e:02fe | Microsoft  | XBOX ACC                     | 72    | mt76x2u    | A13F872E3B |
| 0cf3:7015 | Qualcom... | TP-Link TL-WN821N v3 / TL... | 70    | ath9k_htc  | 854B629E99 |
| 2357:0120 | TP-Link    | Archer T2U PLUS [RTL8821AU]  | 69    | 88XXau     | 4DBC03E904 |
| 0b05:17ab | ASUSTek... | USB-N13 802.11n Network A... | 68    | rtl8192cu  | 6CA4F46D1B |
| 0bda:8197 | Realtek... | RTL8187B Wireless Adapter    | 68    | rtl8187    | 9881895B74 |
| 2357:011f | TP-Link    | 802.11ac WLAN Adapter        | 66    | 88XXau     | DD22D96D07 |
| 0846:9030 | NetGear    | WNA1100 Wireless-N 150 [A... | 64    | ath9k_htc  | 191B8606BA |
| 13d3:3306 | IMC Net... | Mediao 802.11n WLAN [Real... | 63    | r8712u     | 2656CF8992 |
| 2357:0108 | TP-Link    | TL-WN822N Version 4 RTL81... | 63    | rtl8xxxu   | 0B2123C367 |
| 045e:02e6 | Microsoft  | Wireless XBox Controller ... | 61    | mt76x2u    | AAC1293B60 |
| 2001:3c15 | D-Link     | DWA-140 RangeBooster N Ad... | 58    | rt2800usb  | B61E9946E0 |
| 07d1:3c16 | D-Link ... | DWA-125 Wireless N 150 Ad... | 55    | rt2800usb  | 1B80FF1B5A |
| 0b05:184c | ASUSTek... | 802.11ac NIC                 | 53    | 88x2bu     | 6027A620DD |
| 03f0:9d1d | Hewlett... | lt4120 Snapdragon X5 LTE     | 50    | cdc_ether  | 71F0D8F5BB |
| 413c:81a3 | Dell       | Hub of E-Port Replicator     | 49    | qcserial   | CFE53904BC |
| 03f0:581d | Hewlett... | lt4112 Gobi 4G Module Net... | 48    | qcserial   | FFB40F821B |
| 2001:3c20 | D-Link     | 802.11 n WLAN                | 48    | rt2800usb  | A3D97103BF |
| 1199:9041 | Sierra ... | EM7305 Modem                 | 47    | qcseria... | 6F921AA428 |
| 07d1:3c03 | D-Link ... | AirPlus G DWL-G122 Wirele... | 46    | rt73usb    | 9E231F71ED |
| 0b05:1786 | ASUSTek... | USB-N10 802.11n Network A... | 46    | r8712u     | DC91801E45 |
| 1199:9011 | Sierra ... | MC8305 Modem                 | 46    | qcseria... | 7FAB4F85E2 |
| 0cf3:1006 | Qualcom... | TP-Link TL-WN322G v3 / TL... | 45    | ath9k_htc  | 269B4AD58E |
| 15a9:0004 | Gemtek     | WUBR-177G [Ralink RT2571W]   | 45    | rt73usb    | D5D1B22B75 |
| 148f:3072 | Ralink ... | RT3072 Wireless Adapter      | 44    | rt2800usb  | 278873FF66 |
| 0e8d:7610 | MediaTek   | WiFi                         | 43    | mt76x0u    | 71506FF3BD |
| 0bda:8813 | Realtek... | RTL8814AU 802.11a/b/g/n/a... | 42    | 8814au     | 6449E0E3F0 |
| 050d:845a | Belkin ... | F7D2101 802.11n Surf & Sh... | 41    | r8712u     | 09E0E6DEA3 |
| 0846:4260 | NetGear    | WG111v3 54 Mbps Wireless ... | 40    | rtl8187    | 200E91CA92 |
| 0ace:1215 | ZyDAS      | ZD1211B 802.11g              | 40    | zd1211rw   | 2359C14813 |
| 148f:2070 | Ralink ... | RT2070 Wireless Adapter      | 39    | rt2800usb  | 5153E99CCE |
| 0b05:17d1 | ASUSTek... | AC51 802.11a/b/g/n/ac Wir... | 38    | mt76x0u    | A67BC74BFD |
| 0bda:0179 | Realtek... | RTL8188ETV Wireless LAN 8... | 36    | r8188eu    | 88647490E2 |
| 07d1:3303 | D-Link ... | DWA-131 802.11n Wireless ... | 35    | r8712u     | 4340E989F9 |
| 0846:9020 | NetGear    | WNA3100(v1) Wireless-N 30... | 34    |            | 231505C0B0 |
| 2001:3c19 | D-Link     | DWA-125 Wireless N 150 Ad... | 34    | rt2800usb  | 88DE86B5FF |
| 2357:010d | TP-Link    | 802.11n NIC                  | 34    | 88XXau     | 810E386D8B |
| 2357:0138 | TP-Link    | 802.11ac NIC                 | 34    | 88x2bu     | EC15C793BF |
| 7392:a812 | Edimax ... | AC600 USB                    | 34    | 88XXau     | 48187ACCDE |
| 2001:3314 | D-Link     | DWA-171 AC600 DB Wireless... | 33    | rtl8812au  | 265977F345 |
| 413c:81b1 | Dell       | Wireless 5809e Gobiâ¢... | 33    | qcserial   | 793091AC6A |
| 148f:3572 | Ralink ... | RT3572 Wireless Adapter      | 31    | rt2800usb  | 8E5C6EB374 |
| 07d1:3c07 | D-Link ... | DWA-110 Wireless G Adapte... | 30    | rt73usb    | 84B1C46F3C |
| 0b05:179d | ASUSTek... | USB-N53 802.11abgn Networ... | 30    | rt2800usb  | E10152ABC8 |
| 0b05:17e8 | ASUSTek... | USB-N14 802.11b/g/n (2x2)... | 30    | rt2800usb  | F31E6E3DD0 |
| 7392:7711 | Edimax ... | EW-7711UTn nLite Wireless... | 29    | rt2800usb  | 352946E177 |
| 07d1:3c0d | D-Link ... | DWA-125 Wireless N 150 Ad... | 27    | rt2800usb  | DC7A02C862 |
| 13b1:0020 | Linksys    | WUSB54GC v1 802.11g Adapt... | 27    | rt73usb    | 393213DEE8 |
| 13b1:0042 | Linksys    | WUSB6100M 802.11a/b/g/n/a... | 27    | ath10k_usb | C7BE2FF77E |
| 2001:3310 | D-Link     | DWA-123 Wireless N 150 Ad... | 27    | r8188eu    | 277AF949B6 |
| 2001:330f | D-Link     | DWA-125 11n Adapter          | 26    | r8188eu    | 2DDCBE8E2C |
| 2357:0105 | TP-Link    | Archer T1U 802.11a/n/ac W... | 26    | mt76x0u    | C42D20565C |
| 057c:8503 | AVM        | FRITZ!WLAN AC 860            | 25    | mt76x2u    | 9A2D988ABA |
| 13b1:003f | Linksys    | WUSB6300 802.11a/b/g/n/ac... | 25    | 8812au     | 349F8DBE53 |
| 2357:0101 | TP-Link    | RTL8812AU Archer T4U 802.... | 25    | 8812au     | EB9C99A6DB |
| 0e8d:7612 | MediaTek   | MT7612U 802.11a/b/g/n/ac ... | 24    | mt76x2u    | D3D69E7587 |
| 0b05:17d2 | ASUSTek... | USB-AC56 802.11a/b/g/n/ac... | 23    | 8812au     | 1473B3D2CA |
| 0bda:b711 | Realtek... | RTL8188GU 802.11n WLAN Ad... | 23    | option     | 4FA9117126 |
| 13d3:3247 | IMC Net... | AW-NU222 802.11bgn Wirele... | 23    | rt2800usb  | C38A6A2227 |
| 148f:2870 | Ralink ... | RT2870 Wireless Adapter      | 23    | rt2800usb  | EC8E63E96E |
| 2001:3315 | D-Link     | DWA-182 Wireless AC Dualb... | 23    | 8812au     | FC440EEE50 |
| 2357:0106 | TP-Link    | Archer T9UH v1 [Realtek R... | 23    | 8814au     | FEF715F491 |
| 050d:945a | Belkin ... | F7D1101 v1 Basic Wireless... | 22    | r8712u     | 67A9610B67 |
| 057c:8501 | AVM        | FRITZ WLAN N v2 [RT5572/r... | 22    | rt2800usb  | ECAAA3B66A |

### Network (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:8153 | Realtek... | RTL8153 Gigabit Ethernet ... | 1700  | r8152      | 138EC046F1 |
| 04e8:6863 | Samsung... | Galaxy series, misc. (tet... | 501   | rndis_host | 02BA908575 |
| 2717:ff80 | Xiaomi     | Mi/Redmi series (RNDIS)      | 322   | rndis_host | B2D3620851 |
| 0b95:1790 | ASIX El... | AX88179 Gigabit Ethernet     | 297   | ax88179... | E04A41FC30 |
| 12d1:108a | Huawei ... | ANE-LX1                      | 234   | rndis_host | 37AE9A9258 |
| 0bda:8152 | Realtek... | RTL8152 Fast Ethernet Ada... | 216   | r8152      | D4EE4BA59F |
| 04e8:6864 | Samsung... | GT-I9070 (network tetheri... | 206   | rndis_host | DD22D96D07 |
| 0bda:b720 | Realtek... | RTL8723BU 802.11b/g/n WLA... | 185   | rtl8xxxu   | FD406382B2 |
| 12d1:14db | Huawei ... | E353/E3131                   | 163   | cdc_ether  | 90BE7D16BE |
| 0e8d:2004 | MediaTek   | CUBOT J3 PRO                 | 141   | rndis_host | 0BA26CCC72 |
| 19d2:1405 | ZTE WCD... | ZTE Mobile Broadband Station | 127   | cdc_ether  | C9D1B330A2 |
| 22b8:2e24 | Motorol... | moto g stylus                | 110   | rndis_host | 93116D84F3 |
| 2357:0601 | TP-Link    | UE300 10/100/1000 LAN (et... | 103   | r8152      | 4F39E11826 |
| 1199:a001 | Sierra ... | EM7345 4G LTE                | 91    | cdc_mbim   | DF466B506D |
| 0b95:772b | ASIX El... | AX88772B                     | 77    | asix       | BDBFF8ABC8 |
| 2cb7:0210 | Fibocom    | L830-EB-00 LTE WWAN Modem    | 77    | cdc_acm    | 91FC910CF6 |
| 05c6:f00e | Qualcomm   | SDM632-MTP _SN:756EE0DB      | 66    | rndis_host | BB7E656AE8 |
| 17e9:6006 | Display... | Dell Universal Dock D6000    | 64    | cdc_ncm    | BC0BFCD534 |
| 18d1:4ee3 | Google     | Nexus/Pixel Device (tether)  | 62    | rndis_host | E49216D0BB |
| 17ef:a387 | Lenovo     | USB-C Dock Ethernet          | 61    | r8152      | 3FC424B8C6 |
| 0bda:c820 | Realtek... | 802.11ac NIC                 | 59    | btusb      | B5BD43E606 |
| 22d9:276a | OPPO El... | SDM450-MTP _SN:C4014000      | 59    | rndis_host | 4FA9117126 |
| 0fe6:9700 | ICS Advent | DM9601 Fast Ethernet Adapter | 57    | dm9601,... | 97B4291E10 |
| 17ef:3082 | Lenovo     | ThinkPad TBT 3 Dock          | 57    | r8152      | C625F457A9 |
| 0424:ec00 | Standar... | SMSC9512/9514 Fast Ethern... | 56    | smsc95xx   | ED876591F1 |
| 17e9:4307 | Display... | LAPDOCK                      | 55    | cdc_ncm    | 3F5D6AAAB8 |
| 04b3:4010 | IBM        | RNDIS/Ethernet Gadget        | 42    | cdc_ether  | 033203AADE |
| 2e04:c022 | HMD Global | Nokia 3.1                    | 42    | rndis_host | 84968F77F9 |
| 0b95:7720 | ASIX El... | AX88772                      | 41    | asix       | B8DBB2F250 |
| 0bb4:0003 | HTC (Hi... | MT65xx Android Phone         | 40    | rndis_host | 8E9DDFBA30 |
| 03f0:371d | Hewlett... | un2430 Mobile Broadband M... | 39    | qcserial   | 18F27D1F5C |
| 2a70:f00e | OnePlus... | AC2003                       | 39    | rndis_host | 44537C7FBA |
| 05ac:12ab | Apple      | iPad 4/Mini1                 | 38    | ipheth     | 13D7AD71C7 |
| 15a9:002d | Gemtek     | WLTUBA-107 [Yota 4G LTE]     | 35    | cdc_ether  | 10CA362CF0 |
| 045e:07c6 | Microsoft  | RTL8153 GigE [Surface Eth... | 34    | r8152      | C864CCE720 |
| 0e8d:2005 | MediaTek   | WP5                          | 34    | rndis_host | 3BBEC8B8FD |
| 17e9:436e | Display... | Dell D3100 Docking Station   | 34    | cdc_ncm    | 946790A20E |
| 19d2:1365 | ZTE WCD... | Z6201V                       | 34    | rndis_host | 2A068AFC0C |
| 17e9:6000 | Display... | USB 3.0 Dual 4K Dock         | 33    | snd_usb... | 50385DDE8B |
| 17ef:a359 | Lenovo     | ThinkPad Lan                 | 33    | cdc_ether  | E16A18BC8B |
| 1004:6344 | LG Elec... | LM-X420xxx/G2 Android Pho... | 32    | rndis_h... | 6C15236BA3 |
| 0b95:772a | ASIX El... | AX88772A Fast Ethernet       | 30    | asix       | E7E870C6CC |
| 1bbb:0174 | T & A M... | Alcatel 1S                   | 30    | rndis_host | 4A92FAD651 |
| 17ef:3069 | Lenovo     | ThinkPad TBT3 LAN            | 29    | r8152      | AA67AEB304 |
| 046b:ffb0 | America... | Virtual Ethernet             | 27    | cdc_ether  | 2D609FDBDF |
| 17ef:3062 | Lenovo     | ThinkPad Dock Ethernet [R... | 27    | r8152      | FEEC038877 |
| 05c6:9024 | Qualcomm   | SM8250-APOLLO _SN:B760817D   | 25    | rndis_host | 7729A22E1F |
| 0bda:1724 | Realtek... | RTL8723AU 802.11n WLAN Ad... | 24    | rtl8xxxu   | F5565DFB2A |
| 8087:0911 | Intel      | PRODUCT_MODEM                | 24    | cdc_mbim   | B95391E679 |
| 0424:7800 | Standar... | Ethernet controller          | 23    | lan78xx    | D1FC84613E |
| 05ac:1402 | Apple      | Ethernet Adapter [A1277]     | 23    | asix       | 619A3816EB |
| 0b95:7e2b | ASIX El... | AX88772B Fast Ethernet Co... | 22    | asix       | 18263076EA |
| 1782:5d20 | Spreadt... | Unisoc Phone                 | 21    | rndis_host | 4FAEB04124 |
| 0846:6a00 | NetGear    | WG111v2 54 Mbps Wireless ... | 20    | rtl8187    | 96DA43B986 |
| 0bda:b82c | Realtek... | 802.11ac NIC                 | 19    | btusb      | 2CE7E668C7 |
| 216f:0043 | NTmore     | JMR814                       | 19    | cdc_ether  | 32F81DC962 |
| 1076:8002 | GCT Sem... | LU150 LTE Modem [Yota LU150] | 18    | rndis_host | 53874D702A |
| 2001:4a00 | D-Link     | DUB-1312 Gigabit Ethernet... | 18    | ax88179... | 50A93243D2 |
| 056a:0084 | Wacom      | ACK-40401 [Wireless Acces... | 17    | usbhid     | 90D1808D1F |
| 17e9:4323 | Display... | Plugable UD-3900             | 17    | cdc_ncm    | B4171E377E |
| 04b4:3610 | Cypress... | K38231_03                    | 16    | ax88179... | 711E2E3960 |
| 0bb4:0004 | HTC (Hi... | 779                          | 16    | rndis_host | 44FE9BDC7D |
| 1376:4e61 | Vimtron... | Mobile Composite Device Bus  | 16    | rndis_host | B978BE9281 |
| 2357:0602 | TP-Link    | USB 10/100 LAN               | 16    | cdc_ether  | D6E67470FF |
| 05ac:8233 | Apple      | T2 Controller                | 15    | cdc_ncm    | 7B3CDDA6E2 |
| 17e9:4302 | Display... | ThinkPad USB 3.0 Dock        | 15    | snd_usb... | 10C9991F0B |
| 0bb4:0ffe | HTC (Hi... | Desire HD (modem mode)       | 14    | rndis_host | E5BEDFF47D |
| 17e9:4306 | Display... | Targus USB3.0 DV2K Dock w... | 14    | cdc_ncm    | 5E8AE97908 |
| 413c:a102 | Dell       | iDRAC Virtual NIC USB Device | 14    | cdc_ether  | 29F49B3A79 |
| 0489:c022 | Foxconn... | Nokia 7 plus                 | 13    | rndis_host | BEC2435C15 |
| 0846:68e1 | NetGear    | LB1120-100NAS                | 13    | rndis_host | 2EB74A58D2 |
| 0a46:1269 | Davicom... | DM9621A USB To FastEther     | 13    | dm9601     | 8774B51F01 |
| 0bda:0823 | Realtek... | 802.11ac WLAN Adapter        | 13    | btusb      | 3D23100553 |
| 13b1:0041 | Linksys    | Gigabit Ethernet Adapter     | 13    | r8152      | 0F6D7BCF66 |
| 2001:1a02 | D-Link     | DUB-E100 Fast Ethernet Ad... | 13    | asix       | BC4F8ACAF2 |
| 045e:091e | Microsoft  | XBOX ACC                     | 12    |            | C864CCE720 |
| 17ef:7205 | Lenovo     | Thinkpad USB LAN             | 12    | r8152      | D491843ECC |
| 1004:61da | LG Elec... | G2 Android Phone [tetheri... | 11    | rndis_host | F91A752D4D |
| 17ef:7436 | Lenovo     | Android Phone                | 11    | rndis_host | 3412BF6285 |
| 2cb7:0002 | Fibocom    | L831-EAU                     | 11    | cdc_mbim   | 401D1460E9 |
| 17ef:304f | Lenovo     | RTL8153 Gigabit Ethernet ... | 10    | r8152      | 1E1E40CE8B |
| 17ef:720c | Lenovo     | USB-C to LAN                 | 10    | r8152      | 3047B3EC7C |
| 03f0:026a | Hewlett... | L830-EB                      | 9     | cdc_acm    | A2F9CA954A |
| 17e9:4305 | Display... | dynadock U3.0                | 9     | cdc_ncm    | F91B1F41FC |
| 05c6:9057 | Qualcomm   | Android                      | 8     | rndis_host | 21B492B0BF |
| 0bda:8150 | Realtek... | RTL8150 Fast Ethernet Ada... | 8     | rtl8150    | 74B79EAF21 |
| 0bda:d723 | Realtek... | 802.11n WLAN Adapter         | 8     | btusb      | E5E22DF913 |
| 9710:7830 | MosChip... | MCS7830 10/100 Mbps Ether... | 8     | mcs7830    | 2B043D7A15 |
| 04d9:a119 | Holtek ... | SKILLER SGM1                 | 7     | usbhid     | 338292D813 |
| 0525:a4a2 | Netchip... | Linux-USB Ethernet/RNDIS ... | 7     | cdc_subset | EBDEA9D0F5 |
| 081f:e401 | Manta      | MM812                        | 7     | usbhid     | 64AA8D06F4 |
| 12d1:1050 | Huawei ... | Android Phone                | 7     | rndis_host | 1DA678C883 |
| 12d1:260d | Huawei ... | TIT-L01                      | 7     | rndis_host | 85F0F44820 |
| 15a9:003e | Gemtek     | Yota Many                    | 7     | rndis_host | F48E23AB6A |
| 0b05:5f04 | ASUSTek... | Android                      | 6     | rndis_host | 43E4578544 |
| 0fca:8017 | Researc... | BlackBerry                   | 6     | cdc_ncm    | BC53AD8072 |
| 12d1:1c50 | Huawei ... | MOBILE                       | 6     | cdc_ether  | 1511A3D0D3 |
| 17e9:436f | Display... | Dell 4-in-1 Adapter          | 6     | cdc_ncm... | 928665D302 |
| 19d2:1373 | ZTE WCD... | SM8150-MTP _SN:2C95DDEB      | 6     | rndis_host | 3BA95FA890 |
| 1bbb:2026 | T & A M... | ALCATEL ONE TOUCH POP C1     | 6     | cdc_eem    | 8CF1F80E50 |

### Phone (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0e8d:2008 | MediaTek   | Cyrus Technology CS 24       | 97    | usbfs      | 22DCA8A98C |
| 18d1:4ee1 | Google     | Nexus/Pixel Device (MTP)     | 67    | usbfs      | B6966EBC42 |
| 2717:ff48 | Xiaomi     | Mi/Redmi series (MTP + ADB)  | 42    | usbfs      | 4FE54B07A9 |
| 1004:631c | LG Elec... | LM-X420xxx/G2/Optimus And... | 41    | usbfs      | EC8AF5F350 |
| 0e8d:201d | MediaTek   | CUBOT CHEETAH 2              | 24    | usbfs      | E6E8DA123E |
| 1bbb:0168 | T & A M... | Alcatel 1X                   | 24    | usbfs      | A6732AB721 |
| 04e8:685d | Samsung... | GT-I9100 Phone [Galaxy S ... | 16    | cdc_acm    | D2D1C6E65E |
| 1004:6300 | LG Elec... | G2/Optimus Android Phone ... | 11    | usbhid     | CEFBA84AE8 |
| 05c6:f003 | Qualcomm   | Nokia 8110 4G                | 10    | usbfs      | 117223995C |
| 0bb4:0c02 | HTC (Hi... | Dream / ADP1 / G1 / Magic... | 9     | usbfs      | 93825976F1 |
| 19d2:0306 | ZTE WCD... | ZTE USB Device               | 8     | usbfs      | D95EE27C85 |
| 19d2:0307 | ZTE WCD... | Platy                        | 8     | usbfs      | FA18FC0356 |
| 2a45:2008 | Meizu      | MX Phone (MTP)               | 8     | usbfs      | BCF1D99475 |
| 0bb4:2008 | HTC (Hi... | Android Phone via MTP [Wi... | 6     |            | 52ECA6CE50 |
| 1782:4001 | Spreadt... | Android                      | 6     | usbfs      | F13E4BF411 |
| 1bbb:0167 | T & A M... | Alcatel 5X                   | 5     | usbfs      | 27828E1DFB |
| 04e8:685c | Samsung... | GT-I9250 Phone [Galaxy Ne... | 4     | usbfs      | D9976E30E3 |
| 05c6:9092 | Qualcomm   | Android                      | 4     |            | 0A09D00B74 |
| 0bb4:0c01 | HTC (Hi... | Dream / ADP1 / G1 / Magic... | 4     |            | CB71A2D937 |
| 0bb4:0f0b | HTC (Hi... | U12+                         | 4     | usbhid     | 7CBE8BB003 |
| 0fce:01c4 | Sony Er... | Android                      | 4     | usbfs      | 6C0BF83741 |
| 1004:633a | LG Elec... | Ultimate 2 Android Phone ... | 4     | cdc_acm    | 16AEB4166B |
| 17ef:7497 | Lenovo     | A789 (MTP mode)              | 4     |            | B60CD6FFC3 |
| 045e:04ec | Microsoft  | Windows Phone (Zune)         | 3     | usbfs      | 587BECD063 |
| 0bb4:0f87 | HTC (Hi... | Android Phone                | 3     | usbfs      | 541E753F9D |
| 0bb4:f006 | HTC (Hi... | Android Phone                | 3     | usbhid     | 5902EF81CA |
| 1004:61fe | LG Elec... | Optimus Android Phone [US... | 3     | cdc_ether  | 0728097100 |
| 18d1:4ee8 | Google     | Nexus/Pixel Device (MIDI)    | 3     | snd_usb... | E9F2B0CEDA |
| 2717:1240 | Xiaomi     | HM1 Android Phone            | 3     |            | 01AA74496F |
| 2916:f003 | Android    | Android                      | 3     | usbfs      | 5595625922 |
| 2a45:0c02 | Meizu      | MX Phone (MTP & ADB)         | 3     | usbfs      | 5B337FDB0A |
| 0471:0003 | Philips... | Hub                          | 2     | hub        | 20FA770830 |
| 0471:2008 | Philips... | W732                         | 2     |            | D315AFD57C |
| 0bb4:0402 | HTC (Hi... | Android Phone                | 2     | rndis_host | EBBD83B0CA |
| 0bb4:0c81 | HTC (Hi... | Android Phone                | 2     |            | 404A8B3A68 |
| 0fce:0189 | Sony Er... | C6503                        | 2     |            | 97D00825B7 |
| 0fce:019b | Sony Er... | Android                      | 2     |            | 49389100FC |
| 0fce:01b5 | Sony Er... | D2105                        | 2     |            | 165BEE2B5C |
| 0fce:51ad | Sony Er... | Android                      | 2     |            | 41B2D085B5 |
| 1004:61fc | LG Elec... | Optimus 3                    | 2     | cdc_acm... | 1EBB6C2E61 |
| 1532:9052 | Razer USA  | Razer Phone 2                | 2     | usbfs      | F0B799EFBB |
| 1782:4012 | Spreadt... | RIO_ZAM                      | 2     |            | 83DBEAD899 |
| 17ef:74f8 | Lenovo     | MT65xx Android Phone         | 2     |            | B89D04A41B |
| 17ef:79a1 | Lenovo     | MT65xx Android Phone         | 2     | usbfs      | E661874CB2 |
| 1bbb:2008 | T & A M... | MT65xx Android Phone         | 2     | usbfs      | E48E425669 |
| 0414:0c02 | Giga-By... | MT65xx Android Phone         | 1     | usbfs      | 755B9B413C |
| 0421:002f | Nokia M... | 6120 Phone (PC-Suite mode)   | 1     | cdc_acm... | 408A3116F5 |
| 0b05:5490 | ASUSTek... | Android                      | 1     |            | 196E542A2B |
| 0b05:551f | ASUSTek... | Android                      | 1     | usbfs      | E1C6C1D0DB |
| 0bb4:0df8 | HTC (Hi... | Android Phone                | 1     |            | F4F1952C9C |
| 0bb4:0e32 | HTC (Hi... | Android Phone                | 1     | usbfs      | A131EB3789 |
| 0bb4:0fa2 | HTC (Hi... | Android Phone                | 1     | usbfs      | 5A59F3A3B4 |
| 0fce:0197 | Sony Er... | C5502                        | 1     |            | 9C65E049FE |
| 0fce:5195 | Sony Er... | C5303                        | 1     |            | 481DCFBCF9 |
| 1527:0200 | Silicon... | YAP Phone (no firmware)      | 1     |            | D857FD97FD |
| 1532:9051 | Razer USA  | Razer Phone 2                | 1     |            | 46CD15B9A7 |
| 17ef:0c02 | Lenovo     | MT65xx Android Phone         | 1     | usbfs      | B776DA24C5 |
| 19d2:0260 | ZTE WCD... | File-CD Gadget               | 1     | uas, us... | 522AEE0B0B |
| 19d2:0343 | ZTE WCD... | V985                         | 1     |            | 4215162CA5 |
| 22b8:2e71 | Motorol... | Motorola Phone               | 1     | usbhid     | B8DA2787DA |
| 2922:0003 | MediaTek   | MT65xx Android Phone         | 1     | rndis_host | 7B88CC04C1 |

### Printer (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:2b17 | Hewlett... | LaserJet 1020                | 104   | usblp      | A955D2E293 |
| 03f0:4117 | Hewlett... | LaserJet 1018                | 68    | usblp      | 1A39F562B3 |
| 067b:2305 | Prolifi... | PL2305 Parallel Port         | 66    | usblp      | B40EA88DA1 |
| 04e8:341b | Samsung... | SCX-4200 series              | 57    | usblp      | 2992DD1DF0 |
| 03f0:002a | Hewlett... | LaserJet P1102               | 56    | usblp      | F900105A8A |
| 03f0:0053 | Hewlett... | DeskJet 2620 All-in-One P... | 54    | usblp      | 639EF19CE2 |
| 04e8:3321 | Samsung... | M2020 Series                 | 49    | usblp      | DFE0D9FBAF |
| 03f0:e111 | Hewlett... | DeskJet 2130 series          | 46    | usblp      | 0F15DCBAA1 |
| 04a9:176d | Canon      | PIXMA MG2500 Series          | 46    | usblp      | 633FC31D82 |
| 04a9:2676 | Canon      | LBP2900                      | 43    | usblp      | 17EC413352 |
| 04e8:344f | Samsung... | SCX-3400 Series              | 43    | usblp      | 9DE4382874 |
| 04e8:3469 | Samsung... | M2070 Series                 | 43    | usblp      | E39CE9ADE6 |
| 03f0:d711 | Hewlett... | ENVY 4520 series             | 41    | usblp      | 69C8804209 |
| 03f0:3d17 | Hewlett... | LaserJet P1005               | 39    | usblp      | 866150F656 |
| 04f9:0027 | Brother... | HL-2030 Laser Printer        | 35    | usblp      | C7798BA8D3 |
| 03f0:0c17 | Hewlett... | LaserJet 1010                | 34    | usblp      | DA176384C5 |
| 1a86:7584 | QinHeng... | CH340S                       | 33    | usblp      | B7DF25BA5D |
| 04e8:3441 | Samsung... | SCX-3200 Series              | 32    | usblp      | 24974BE67E |
| 04e8:3292 | Samsung... | ML-1640 Series Laser Printer | 31    | usblp      | 843C7A8519 |
| 03f0:8711 | Hewlett... | Deskjet 2050 J510            | 29    | usblp      | D79188A009 |
| 03f0:c211 | Hewlett... | Deskjet 2540 series          | 29    | usblp      | 54507E44FD |
| 03f0:e311 | Hewlett... | DeskJet 3630 series          | 29    | usblp      | 48617BE8F2 |
| 04a9:10dc | Canon      | iP7200 series                | 27    | usblp      | B9CDAB0CBC |
| 04b8:002a | Seiko E... | USB2.0 Printer (Hi-speed)    | 27    | usblp      | D5BDA28E79 |
| 04da:0f0b | Panason... | KX-MB1500CX                  | 27    | usblp      | 82DD7F530A |
| 03f0:102a | Hewlett... | LaserJet Professional P 1... | 26    | usblp      | 46A74B74FC |
| 04a9:2759 | Canon      | MF3010                       | 26    | usblp      | FCBB29A9CF |
| 04b8:0005 | Seiko E... | Printer                      | 26    | usblp      | 5422D3BF1D |
| 04b8:0007 | Seiko E... | Printer                      | 26    | usblp      | AA62962D75 |
| 04f9:0054 | Brother... | HL-1110 series               | 26    | usblp      | E3263A11A6 |
| 04a9:2737 | Canon      | MF4410                       | 25    | usblp      | E0E9A2E532 |
| 03f0:8911 | Hewlett... | Deskjet 1050 J410            | 24    | usblp      | C9D77F5B77 |
| 04a9:176b | Canon      | PIXMA MX920 Series           | 24    | usblp      | 5026826DBE |
| 04b8:08a1 | Seiko E... | L210 Series                  | 23    | usblp      | 7AEE651D14 |
| 03f0:2504 | Hewlett... | DeskJet F4200 series         | 22    | usblp      | 28B6DC130A |
| 04e8:330f | Samsung... | ML-216x Series Laser Printer | 22    | usblp      | 109188CC8F |
| 03f0:0317 | Hewlett... | LaserJet 1200                | 21    | usblp      | D74C10F41F |
| 03f0:032a | Hewlett... | LaserJet Professional P1102w | 21    | usblp      | 3EE51E8A56 |
| 03f0:2c17 | Hewlett... | LaserJet 1022                | 21    | usblp      | 9C52EC1EB2 |
| 04a9:178a | Canon      | PIXMA MG3600 Series          | 21    | usbfs      | 200BFFF8BA |
| 03f0:1d17 | Hewlett... | LaserJet 1320                | 20    | usblp      | DD50FE59B2 |
| 03f0:3e17 | Hewlett... | LaserJet P1006               | 20    | usblp      | 7122E4BD16 |
| 03f0:2d12 | Hewlett... | Officejet 4500 G510g-m       | 19    | usblp      | EDB5BC2CAC |
| 03f0:3217 | Hewlett... | LaserJet 3050                | 19    | usblp      | 3C335B37FA |
| 03f0:9311 | Hewlett... | Deskjet 3050 J610 series     | 19    | usblp      | A180A91A9F |
| 04a9:26b4 | Canon      | MF4010 series                | 19    | usblp      | E7304A0193 |
| 04a9:271a | Canon      | LBP6000                      | 19    | usblp      | AE3EABE5FA |
| 04e8:3301 | Samsung... | ML-1660 Series               | 19    | usblp      | AB74A35021 |
| 03f0:0853 | Hewlett... | ENVY 5000 series             | 18    | usblp      | EEA45758B7 |
| 04a9:1913 | Canon      | LiDE 300                     | 18    | usbfs      | 896C7C1C82 |
| 04b8:005e | Seiko E... | L120 Series                  | 18    | usblp      | E94404D654 |
| 04b8:08d1 | Seiko E... | L222 Series                  | 18    | usblp      | 8DB9070723 |
| 04f9:003f | Brother... | HL-2130 series               | 18    | usblp      | A81005EF0B |
| 04a9:26da | Canon      | LBP3010B printer             | 17    | usblp      | BF7B9902DA |
| 04e8:326c | Samsung... | ML-2010P Mono Laser Printer  | 17    | usblp      | 75A9AA20F2 |
| 03f0:7e04 | Hewlett... | DeskJet F4100 Printer series | 16    | usblp      | 35B768567F |
| 04a9:1746 | Canon      | PIXMA MP280                  | 16    | usblp      | A549C95CBD |
| 04a9:260a | Canon      | LBP810                       | 16    | usblp      | 7DDF671031 |
| 04b8:08a8 | Seiko E... | L355 Series                  | 16    | usblp      | 5E97B4ABA2 |
| 04b8:1122 | Seiko E... | L395 Series                  | 16    | usblp      | A367EC462A |
| 04b8:1143 | Seiko E... | L3150 Series                 | 16    | usblp      | 3F67C7622C |
| 04e8:3413 | Samsung... | SCX-4100 Scanner             | 16    | usblp      | DA8850DC6A |
| 03f0:1017 | Hewlett... | LaserJet 1300                | 15    | usblp      | 66228CE4DF |
| 03f0:7611 | Hewlett... | DeskJet F2492 All-in-One     | 15    | usblp      | 3F9B2942E1 |
| 03f0:7d04 | Hewlett... | DeskJet F2100 Printer series | 15    | usblp      | 30B02CF768 |
| 03f0:b011 | Hewlett... | Deskjet 3520 series          | 15    | usblp      | 1112AC9EC4 |
| 03f0:e511 | Hewlett... | OfficeJet 3830 series        | 15    | usblp      | FF7E2B9FFD |
| 04a9:173a | Canon      | PIXMA MP250                  | 15    | usblp      | C3A23AE9FB |
| 04a9:176c | Canon      | MG2400 series                | 15    | usblp      | 74AABB5491 |
| 04a9:262b | Canon      | LaserShot LBP-1120 Printer   | 15    | usblp      | 0705CFCBA0 |
| 04e8:300c | Samsung... | ML-1210 Printer              | 15    | usblp      | A8699BE8C7 |
| 03f0:0517 | Hewlett... | LaserJet 1000                | 14    | usblp      | 85B282F128 |
| 03f0:0653 | Hewlett... | DeskJet 3700 series          | 14    | usbfs      | 36BF6DAB37 |
| 03f0:0953 | Hewlett... | OfficeJet 5200 series        | 14    | usblp      | D065E6065E |
| 03f0:3817 | Hewlett... | LaserJet P2015 series        | 14    | usblp      | 633FC31D82 |
| 03f0:8c11 | Hewlett... | Deskjet F4500 series         | 14    | usblp      | 801C1D8AF3 |
| 03f0:c111 | Hewlett... | Deskjet 1510                 | 14    | usblp      | 35167A79E9 |
| 04a9:1912 | Canon      | LiDE 400                     | 14    | usbfs      | C9B1B88BA8 |
| 04a9:2771 | Canon      | LBP6020                      | 14    | usblp      | A31437072C |
| 04e8:342e | Samsung... | SCX-4300 Series              | 14    | usblp      | 73330F71A8 |
| 03f0:1853 | Hewlett... | DeskJet 2700 series          | 13    | usbfs      | CF720E50DB |
| 03f0:612a | Hewlett... | LaserJet M101-M106           | 13    | usblp      | 5ADC857043 |
| 03f0:a011 | Hewlett... | Deskjet 3050A                | 13    | usblp      | 704043DEAB |
| 03f0:c511 | Hewlett... | ENVY 4500 series             | 13    | usblp      | A13B05F65F |
| 04a9:10d3 | Canon      | iP2700 series                | 13    | usblp      | 5856720999 |
| 04b8:08d2 | Seiko E... | L365 Series                  | 13    | usblp      | 89C4E2A423 |
| 04b8:1116 | Seiko E... | XP-240 Series                | 13    | usblp      | 80572AE324 |
| 04f9:02d0 | Brother... | DCP-1510                     | 13    | usblp      | 0071FAABAC |
| 03f0:5511 | Hewlett... | DeskJet F300 series          | 12    | usblp      | E81CD8C462 |
| 0483:5750 | STMicro... | LED badge -- mini LED dis... | 12    | usbhid     | 91D12A5041 |
| 04a9:1827 | Canon      | TS3100 series                | 12    | usblp      | 7926C787F0 |
| 04a9:2684 | Canon      | MF3200 series                | 12    | usblp      | C901CB9ABB |
| 04b8:0883 | Seiko E... | ME 340 Series/Stylus NX13... | 12    | usblp      | 8532A53B66 |
| 04e8:325b | Samsung... | Xerox Phaser 3117 Laser P... | 12    | usblp      | EB1FE5A371 |
| 04e8:347e | Samsung... | C48x Series Color Laser M... | 12    | usblp      | 2590EC6A56 |
| 04f9:0042 | Brother... | HL-2270DW Laser Printer      | 12    | usblp      | 1DD1E8824B |
| 04f9:0061 | Brother... | HL-L2300D series             | 12    | usblp      | 1D9F5A408E |
| 04f9:0063 | Brother... | HL-L2340D series             | 12    | usblp      | 7AB201B716 |
| 04f9:035b | Brother... | DCP-1610W                    | 12    | usblp      | 938B16305C |
| 03f0:0d17 | Hewlett... | LaserJet 1012                | 11    | usblp      | 02394DEF9F |

### Scanner (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04a9:1909 | Canon      | CanoScan LiDE 110            | 86    | usbfs      | 031CDD1297 |
| 04a9:2220 | Canon      | CanoScan LIDE 25             | 66    | usbfs      | 3A06ECCCAA |
| 04a9:190a | Canon      | CanoScan LiDE 210            | 59    |            | F66B710A8A |
| 04a9:220d | Canon      | CanoScan N670U/N676U/LiDE 20 | 56    |            | 9E2D96B5B6 |
| 04a9:190f | Canon      | CanoScan LiDE 220            | 38    | usbfs      | F943D839A8 |
| 04a9:190e | Canon      | CanoScan LiDE 120            | 35    | usbfs      | 55CCE80C82 |
| 03f0:0a01 | Hewlett... | ScanJet 2400c                | 33    | usbfs      | 42CD4D28BD |
| 04a9:220e | Canon      | CanoScan N1240U/LiDE 30      | 27    | usbfs      | D3AA74A821 |
| 04b8:0142 | Seiko E... | GT-F730 [GT-S630/Perfecti... | 24    |            | D0FD1CE0E8 |
| 05d8:4002 | Ultima ... | Artec Ultima 2000 (GT6801... | 23    | usbfs      | 0C5E09B00C |
| 04a9:1904 | Canon      | CanoScan LiDE 100            | 22    |            | 8FA77435F7 |
| 04b8:0121 | Seiko E... | GT-F500/GT-F550 [Perfecti... | 22    |            | E1DAAA37F5 |
| 04a9:221c | Canon      | CanoScan LiDE 60             | 16    |            | 1EA8028ECB |
| 04b8:012d | Seiko E... | GT-F650 [GT-S600/Perfecti... | 16    |            | 6BD5CC2D9B |
| 04b8:0130 | Seiko E... | GT-X770 [Perfection V500]    | 16    |            | 4EA9AE9F30 |
| 04a9:2213 | Canon      | CanoScan LiDE 50/LiDE 35/... | 15    |            | 1229314F25 |
| 04b8:0122 | Seiko E... | GT-F520/GT-F570 [Perfecti... | 15    | usbfs      | 4ED3CD9A74 |
| 055f:021b | Mustek ... | BearPaw 1200 CU Plus         | 14    | usbfs      | 9FAA6E8AF8 |
| 04a9:1907 | Canon      | CanoScan LiDE 700F           | 13    | usbfs      | AF24409637 |
| 04b8:011f | Seiko E... | GT-8400UF [Perfection 167... | 13    |            | A792022089 |
| 04b8:0120 | Seiko E... | GT-7400U [Perfection 1270]   | 13    |            | 2FCE3F9ABF |
| 04b8:013a | Seiko E... | GT-X820 [Perfection V600 ... | 13    |            | D35C6EA078 |
| 055f:021f | Mustek ... | SNAPSCAN e22                 | 11    |            | 23B6389BB5 |
| 04a9:1905 | Canon      | CanoScan LiDE 200            | 10    |            | 630FEC5A83 |
| 04a9:2228 | Canon      | CanoScan 4400F               | 9     |            | 109188CC8F |
| 04b8:011b | Seiko E... | GT-9300UF [Perfection 240... | 9     |            | 842C53B8E2 |
| 04b8:012e | Seiko E... | GT-F670 [Perfection V200 ... | 9     |            | EDD8B3C5B2 |
| 04b8:013b | Seiko E... | Scanner                      | 9     |            | B6C7C92FAF |
| 03f0:1c05 | Hewlett... | Scanjet 200                  | 8     |            | FEBB5AEE31 |
| 03f0:2605 | Hewlett... | ScanJet 3800c                | 8     |            | 4005AC4804 |
| 04b8:0119 | Seiko E... | GT-X750 [Perfection 4490 ... | 8     |            | 0CEDF0F08E |
| 055f:021d | Mustek ... | BearPaw 2400 CU Plus         | 8     |            | A5CA2582B6 |
| 03f0:1705 | Hewlett... | ScanJet 5590                 | 7     |            | D1ECE8006F |
| 04a9:1900 | Canon      | CanoScan LiDE 90             | 7     |            | E1B742D511 |
| 04a9:2206 | Canon      | CanoScan N650U/N656U         | 7     |            | CF8D063DEB |
| 04a9:2225 | Canon      | CanoScan LiDE 70             | 7     |            | DCE96AE07E |
| 04b8:0131 | Seiko E... | GT-F720 [GT-S620/Perfecti... | 7     |            | 6F0E81A6D9 |
| 055f:0006 | Mustek ... | ScanExpress 1200 UB          | 7     |            | ADF9EBB679 |
| 055f:021c | Mustek ... | BearPaw 1200 CU Plus         | 7     | usbfs      | 74E1239BF6 |
| 03f0:2305 | Hewlett... | ScanJet 3970c                | 6     |            | DCA9B0F592 |
| 04a9:1908 | Canon      | CanoScan                     | 6     | usbfs      | CBFFDF2C56 |
| 04a9:2224 | Canon      | CanoScan LiDE 600F           | 6     |            | 2ED92032E0 |
| 04b8:010f | Seiko E... | GT-7200U [Perfection 1250... | 6     |            | 799AD15D8B |
| 04b8:011d | Seiko E... | GT-7300U [Perfection 1260... | 6     |            | FDAD3D0ED9 |
| 055f:0408 | Mustek ... | BearPaw 2448 CU Pro          | 6     |            | D342F4E0A4 |
| 03f0:0405 | Hewlett... | ScanJet 3400cse              | 5     | usbfs      | 18837F1515 |
| 03f0:0805 | Hewlett... | HP4470C                      | 5     |            | 5600070A23 |
| 03f0:0b01 | Hewlett... | ScanJet 82x0C                | 5     | usbfs      | 85121B8AEC |
| 03f0:1d05 | Hewlett... | Scanjet 300                  | 5     |            | 953BA0670D |
| 03f0:2005 | Hewlett... | ScanJet 3570c                | 5     |            | 587B440CE4 |
| 03f0:2f11 | Hewlett... | PSC 1200                     | 5     | usblp      | 9BD4224188 |
| 03f0:4605 | Hewlett... | ScanJet G4050                | 5     |            | BB31E60922 |
| 04a9:221b | Canon      | CanoScan 4200F               | 5     |            | C6097BDDA4 |
| 04a9:221f | Canon      | CanoScan LiDE 500F           | 5     |            | 03216262DD |
| 04b8:0114 | Seiko E... | Perfection 660               | 5     |            | 72B40A39D4 |
| 04b8:012a | Seiko E... | GT-X800 [Perfection 4990 ... | 5     | usbfs      | 76FFF4BB1C |
| 055f:021a | Mustek ... | BearPaw 2448 TA Plus         | 5     |            | EF1C9E227C |
| 03f0:0605 | Hewlett... | ScanJet 2200c                | 4     |            | C5719C54C2 |
| 03f0:0701 | Hewlett... | ScanJet 5300c/5370c          | 4     |            | F9375B6948 |
| 03f0:1405 | Hewlett... | ScanJet 3670                 | 4     |            | 7E4D284284 |
| 03f0:4505 | Hewlett... | ScanJet G4010                | 4     |            | 7C3D5F062E |
| 04a5:20b0 | Acer Pe... | S2W 3300U/4300U              | 4     |            | 2A42DEB5A5 |
| 04a5:2311 | Acer Pe... | Benq 5560                    | 4     |            | 25B7198C11 |
| 04a9:190d | Canon      | CanoScan 9000F Mark II       | 4     |            | DBBA1BCF47 |
| 04b8:010b | Seiko E... | GT-7700U [Perfection 1240U]  | 4     |            | E6D0744E85 |
| 04b8:0112 | Seiko E... | GT-9700F [Perfection 2450... | 4     |            | 425D116724 |
| 04b8:011e | Seiko E... | GT-8300UF [Perfection 166... | 4     |            | 99773CF00E |
| 04b8:012f | Seiko E... | GT-F700 [Perfection V350]    | 4     |            | 9506DFA1DB |
| 03f0:0305 | Hewlett... | ScanJet 4300c                | 3     | usbfs      | F519F06748 |
| 03f0:2205 | Hewlett... | ScanJet 3500c                | 3     |            | 126B5ADE99 |
| 03f0:2505 | Hewlett... | ScanJet 3770                 | 3     |            | 87E50471AE |
| 03f0:4205 | Hewlett... | ScanJet G3010                | 3     |            | A9E90B12DC |
| 0458:2014 | KYE Sys... | ColorPage-Vivid4             | 3     |            | 6F51B530BD |
| 04a5:20f8 | Acer Pe... | Benq 5000                    | 3     |            | 78F2C3136C |
| 04a5:2137 | Acer Pe... | Benq 5150/5250               | 3     |            | 2D25B17958 |
| 04a9:1901 | Canon      | CanoScan 8800F               | 3     |            | EE15B6DAB0 |
| 04b8:010a | Seiko E... | GT-8700/GT-8700F [Perfect... | 3     |            | D819B1CC24 |
| 04b8:0110 | Seiko E... | GT-8200U/GT-8200UF [Perfe... | 3     |            | 3796A94A31 |
| 04b8:011c | Seiko E... | GT-9800F [Perfection 3200]   | 3     |            | 1F57F19AFF |
| 04b8:012c | Seiko E... | GT-X900 [Perfection V700/... | 3     |            | 674668F4DD |
| 04b8:0807 | Seiko E... | Stylus Photo RX500/510       | 3     | uas, us... | 26F16E4312 |
| 055f:0219 | Mustek ... | BearPaw 2400 TA Plus         | 3     |            | 49BA2B0298 |
| 06bd:2091 | AGFA-Ge... | SnapScan e20                 | 3     |            | AF794C7302 |
| 03f0:0205 | Hewlett... | ScanJet 3300c                | 2     |            | CD5BCE9449 |
| 03f0:0401 | Hewlett... | ScanJet 5200c                | 2     |            | 8DE53A9490 |
| 03f0:0601 | Hewlett... | ScanJet 6300c                | 2     |            | 2047255023 |
| 03f0:0901 | Hewlett... | ScanJet 2300c                | 2     |            | 09D469F1FC |
| 03f0:1205 | Hewlett... | ScanJet 4500C/5550C          | 2     |            | 093D03CAF5 |
| 03f0:1305 | Hewlett... | ScanJet 4570c                | 2     |            | 87DB1E85E8 |
| 03f0:1805 | Hewlett... | ScanJet 7650                 | 2     |            | 97B2CD2B45 |
| 03f0:1b05 | Hewlett... | ScanJet 4850C/4890C          | 2     | usbfs      | 4DFA675040 |
| 03f0:2805 | Hewlett... | Scanjet G2710                | 2     |            | D6B3AEBB34 |
| 03f0:4105 | Hewlett... | ScanJet 4370                 | 2     |            | 9126D5D2E7 |
| 03f0:4305 | Hewlett... | ScanJet G3110                | 2     |            | 3F1B997D89 |
| 0458:201f | KYE Sys... | ColorPage-Vivid 1200 XE      | 2     |            | C676410AA7 |
| 04a5:2211 | Acer Pe... | Color FlatbedScanner39       | 2     |            | E507592DE8 |
| 04a5:2331 | Acer Pe... | FlatbedScanner 50            | 2     |            | 0B356FFA8A |
| 04a9:1906 | Canon      | CanoScan 5600F               | 2     |            | 5889B752F5 |
| 04a9:2204 | Canon      | CanoScan FB630U              | 2     |            | 74202436B2 |
| 04b8:0116 | Seiko E... | GT-9400UF [Perfection 3170]  | 2     |            | B961168B44 |

### Serial controller (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1a86:7523 | QinHeng... | CH340 serial converter       | 265   | ch341      | 0F4AE74D8E |
| 0403:6001 | Future ... | FT232 Serial (UART) IC       | 260   | ftdi_sio   | 8A52B831D7 |
| 067b:2303 | Prolifi... | PL2303 Serial Port / Mobi... | 205   | pl2303     | B14C0E8DD2 |
| 10c4:ea60 | Silicon... | CP210x UART Bridge           | 164   | cp210x     | 2AD271E81F |
| 05c6:9204 | Qualcomm   | Gobi 2000                    | 90    | qcserial   | 5DA95784CA |
| 03f0:521d | Hewlett... | hs3110 HSPA+ Mobile Broad... | 63    | option     | 1069B24865 |
| 03f0:241d | Hewlett... | Gobi 2000 Wireless Modem ... | 45    | qcserial   | 1408D15ECE |
| 0451:3410 | Texas I... | TUSB3410 Microcontroller     | 39    | ti_usb_... | 4698844EC0 |
| 1199:9013 | Sierra ... | Sierra Wireless Gobi 3000... | 39    | qcserial   | 525CE59581 |
| 12d1:15c1 | Huawei ... | ME906s LTE M.2 Module        | 37    | option     | 72EF63C911 |
| 2c7c:0125 | Quectel... | EC25 LTE modem               | 31    | qmi_wwan   | 4A5E673FE5 |
| 03f0:a31d | Hewlett... | lt4132 LTE/HSPA+ 4G Module   | 30    | option     | A5331A4D5E |
| 0403:6010 | Future ... | FT2232C/D/H Dual UART/FIF... | 28    | ftdi_sio   | CB0D8D901A |
| 0403:6015 | Future ... | Bridge(I2C/SPI/UART/FIFO)    | 28    | ftdi_sio   | 7C73C4E6F0 |
| 1b1c:1c00 | Corsair    | Controller for Corsair Link  | 25    | cp210x     | F1CA31B777 |
| 19d2:0016 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 24    | option     | EB04CF12AA |
| 1199:9000 | Sierra ... | Gobi 2000 Wireless Modem ... | 20    | qcserial   | 4D6A940F2A |
| 03f0:201d | Hewlett... | un2400 Gobi Wireless Mode... | 17    | qcserial   | 9028097D4D |
| 0403:6014 | Future ... | FT232H Single HS USB-UART... | 16    | ftdi_sio   | 1FCE457AC6 |
| 413c:8185 | Dell       | Gobi 2000 Wireless Modem ... | 15    | qcserial   | 4370197A2D |
| 0fcf:1008 | Dynastr... | ANTUSB2 Stick                | 14    | usb_ser... | F3E5EBA0C2 |
| 0d9f:0002 | Powercom   | Black Knight PRO / WOW Un... | 13    | cypress... | 3F52A340FB |
| 0fcf:1009 | Dynastr... | ANTUSB-m Stick               | 13    | usb_ser... | 0B28226CB5 |
| 19d2:2003 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 13    | option     | F125F4CD03 |
| 10c4:ea70 | Silicon... | CP2105 Dual UART Bridge      | 12    | cp210x     | D998D59215 |
| 05c6:9224 | Qualcomm   | Sony Gobi 2000 Wireless M... | 11    | qcserial   | 2D1739DC58 |
| 0403:6011 | Future ... | FT4232H Quad HS USB-UART/... | 10    | ftdi_sio   | FD8290E92F |
| 0557:2008 | ATEN In... | UC-232A Serial Port [pl2303] | 10    | pl2303     | E8E6AF7531 |
| 0af0:6901 | Option     | Globetrotter HSDPA Modem     | 10    | option     | EE6FDF4608 |
| 04b4:5500 | Cypress... | HID->COM RS232 Adapter       | 9     | cypress... | 294D1F6A89 |
| 1199:683c | Sierra ... | Mobile Broadband 3G/UMTS ... | 9     | sierra     | B26E82328A |
| 03f0:1e1d | Hewlett... | hs2300 HSDPA Broadband Wi... | 8     | sierra     | 1F3C069A21 |
| 05c6:9008 | Qualcomm   | Gobi Wireless Modem (QDL ... | 8     | qcserial   | 77972D0737 |
| 057c:6201 | AVM        | AVM Fritz!WLAN v1.1 [Texa... | 7     | option     | 3C0A297EDE |
| 1199:6832 | Sierra ... | MC8780 Device                | 7     | sierra     | 3B7266D323 |
| 413c:8133 | Dell       | Wireless 5720 VZW Mobile ... | 6     | option     | 5F6EC9333E |
| 0711:0230 | Magic C... | MCT-232 Serial Port          | 5     | mct_u232   | E7DE7DF1C7 |
| 10c4:8a2a | Silicon... | HubZ Smart Home Controller   | 5     | cp210x     | 4F2775E12D |
| 10c4:ea71 | Silicon... | CP2108 Quad UART Bridge      | 5     | cp210x     | CE3945EA8E |
| 1199:6813 | Sierra ... | Mini Card                    | 5     | sierra     | 56D9CF2086 |
| 1410:2420 | Novatel... | Expedite EU850D/EU860D/EU... | 5     | option     | 99920AD031 |
| 413c:81d7 | Dell       | DW5821e Snapdragon X20 LTE   | 5     | option     | C5856B1EA0 |
| 04da:250c | Panason... | Gobi Wireless Modem (QDL ... | 4     | qcserial   | 29EEE33555 |
| 05c6:9221 | Qualcomm   | Gobi Wireless Modem (QDL ... | 4     | qcserial   | 950506FE40 |
| 0f3d:68aa | Airprim... | AirCard 320U                 | 4     | uas, us... | 1473909011 |
| 19d2:0117 | ZTE WCD... | USB SCSI CD-ROM              | 4     | uas, us... | 01068C79DF |
| 1bbb:022c | T & A M... | HSPA+ USB Modem              | 4     | usbseri... | A348E53594 |
| 1e0e:9001 | Qualcom... | SimTech, Incorporated        | 4     | option     | 3EEF74187F |
| 413c:819b | Dell       | Novatel Wireless HSPA        | 4     | cdc_eth... | FD1375D5F1 |
| 0403:1234 | Future ... | IronLogic RFID Adapter [Z... | 3     | ftdi_sio   | 876DB8C948 |
| 067b:aaa0 | Prolifi... | Prolific Pharos              | 3     | pl2303     | 25A1DC80F1 |
| 091e:0003 | Garmin ... | GPS (various models)         | 3     | garmin_gps | A877A0F4BC |
| 1199:68c0 | Sierra ... | MC7304                       | 3     | qcserial   | 11C9D92E85 |
| 2100:9e58 | RT Systems | USB63C Radio Cable [Yaesu... | 3     | ftdi_sio   | 0263CC00DA |
| 6547:0232 | Arkmicr... | ARK3116 Serial               | 3     | ark3116    | BFE6259C0C |
| 03f0:1f1d | Hewlett... | un2400 Gobi Wireless Modem   | 2     | qcserial   | 1BEB03698D |
| 0403:fc60 | Future ... | IRTrans USB                  | 2     | ftdi_sio   | 88DB2A30AA |
| 045e:00ce | Microsoft  | Generic PPC Flash device     | 2     | ipaq       | D61BE7331F |
| 0af0:6501 | Option     | GlobeTrotter 3G+ Module      | 2     | option     | 7024487BCD |
| 0df7:0620 | Mobile ... | MA-620 Infrared Adapter      | 2     | pl2303     | 467812DB7D |
| 114f:68a2 | Wavecom    | MC7750                       | 2     | qcserial   | 33AF47893A |
| 1199:0218 | Sierra ... | MC5720 Wireless Modem        | 2     | sierra     | E5C5CE1445 |
| 1199:68a3 | Sierra ... | MC8700 Modem                 | 2     | sierra     | B11B688D14 |
| 15ba:002b | Olimex     | ARM-USB-OCD-H JTAG+RS232     | 2     | ftdi_sio   | FFD6111CE0 |
| 1bbb:00b7 | T & A M... | 3G Wireless Router           | 2     | option     | E6C9D1B45A |
| 2020:2060 | Qualcom... | CDMA Technologies MSM        | 2     | option     | C24817EE80 |
| 2c7c:0306 | Quectel... | EG06/EP06/EM06 LTE-A modem   | 2     | option     | D48FD712A5 |
| 413c:8171 | Dell       | Gobi Wireless Modem (QDL ... | 2     | qcserial   | CB6D9E241E |
| 413c:81e0 | Dell       | DW5821e-eSIM Snapdragon X... | 2     | cdc_mbim   | 4B2C0DDDEB |
| 4348:5523 | WinChip... | USB->RS 232 adapter with ... | 2     | ch341      | D1BC30B527 |
| 9710:7720 | MosChip... | MCS7720 Dual serial port ... | 2     | mos7720    | B9B07BDC0A |
| 9710:7840 | MosChip... | MCS7820/MCS7840 2/4 port ... | 2     | mos7840    | BC36FB9437 |
| 03f0:1016 | Hewlett... | Jornada 548 / iPAQ HW6515... | 1     | ipaq       | 4FA0B1AA66 |
| 0403:0011 | Future ... | Z3X BOX                      | 1     | ftdi_sio   | BB2FD997AB |
| 0403:f06e | Future ... | ELV ALC8500 Expert           | 1     | ftdi_sio   | 25B569ADA4 |
| 0403:fc0d | Future ... | Crystalfontz CFA-635 USB LCD | 1     | ftdi_sio   | DAE3697FF8 |
| 0408:ea06 | Quanta     | CDMA Technologies MSM        | 1     | option     | 97C6728357 |
| 0451:505f | Texas I... | TUSB5052 Serial              | 1     | ti_usb_... | 64A9C1D635 |
| 0483:3747 | STMicro... | ST Micro Connect Lite        | 1     | ftdi_sio   | A56D8D1C28 |
| 050d:0257 | Belkin ... | F5U257 Serial                | 1     | pl2303     | FFEED70C90 |
| 05c6:9225 | Qualcomm   | Sony Gobi 2000 Wireless M... | 1     | qcserial   | 3631A4D89D |
| 067b:e1f1 | Prolifi... | Z-TEK USB to Serial Comm ... | 1     | pl2303     | 34CED022E3 |
| 06cd:0121 | Keyspan    | USA-19hs serial adapter      | 1     | keyspan    | FB2C692CC5 |
| 0856:ac19 | B&B Ele... | Model USOPTL4DR              | 1     | ftdi_sio   | 077842DAC4 |
| 0930:1302 | Toshiba    | Wireless Broadband (3G HS... | 1     | option     | 6F67780462 |
| 0bf8:1001 | Fujitsu... | Fujitsu Pocket Loox 600 PDA  | 1     | ipaq       | 224FD9231B |
| 0df8:0001 | HOYA Co... | HOYA IrWave 520UK Usb-IrDA   | 1     | ir_usb     | 19BC1494C6 |
| 0ea0:6858 | Ours Te... | OTi-6858 serial adapter      | 1     | oti6858    | 7D394B641E |
| 106c:3715 | Curitel... | PANTECH USB MODEM            | 1     | qcaux      | B25CD577AD |
| 10c4:8056 | Silicon... | USB Sensor Interface Device  | 1     | cp210x     | 6B03F1DB66 |
| 10c4:814a | Silicon... | West Mountain Radio RIGbl... | 1     | cp210x     | A85DC8D30D |
| 10c4:8470 | Cygnal ... | Juniper Networks BX Serie... | 1     | cp210x     | 06DECE3B2A |
| 10c4:ea61 | Silicon... | CP210x UART Bridge           | 1     | cp210x     | 7A4D566F94 |
| 110a:1450 | Moxa Te... | UPort 1450 4-Port RS-232/... | 1     | mxuport    | F86906F641 |
| 1199:0020 | Sierra ... | MC5725 Modem                 | 1     | sierra     | D2C42C6C14 |
| 1199:6802 | Sierra ... | MC8755 Device                | 1     | sierra     | 69A21019E7 |
| 1199:6804 | Sierra ... | MC8755 Device                | 1     | sierra     | DB650F6297 |
| 1199:6812 | Sierra ... | MC8775 Device                | 1     | sierra     | 7D9E4527B1 |
| 1199:6856 | Sierra ... | ATT "USB Connect 881"        | 1     | sierra     | 5A1CA7D377 |
| 1199:6890 | Sierra ... | AC504                        | 1     | sierra     | 83B675C99C |

### Sound (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0d8c:0014 | C-Media... | Audio Adapter (Unitek Y-2... | 341   | snd_usb... | 3D0FD285B6 |
| 1b3f:2008 | General... | USB Audio Device             | 270   | snd_usb... | F2D60E0B6A |
| 0d8c:013c | C-Media... | CM108 Audio Controller       | 264   | snd_usb... | 6C7ECC284B |
| 08bb:2902 | Texas I... | PCM2902 Audio Codec          | 226   | snd_usb... | 56EDF0B800 |
| 0d8c:0012 | C-Media... | 7.1ch Surround Audio Device  | 214   | snd_usb... | A525C8911B |
| 0951:16a4 | Kingsto... | HyperX 7.1 Audio             | 166   | snd_usb... | F60A34FE5C |
| 0d8c:0005 | C-Media... | Blue Snowball                | 162   | snd_usb... | 9D4EDC7252 |
| 0bda:4014 | Realtek... | USB Audio                    | 148   | snd_usb... | 83DF635945 |
| 0c76:161f | JMTek      | USB PnP Audio Device         | 148   | snd_usb... | 4E5DA9E4D3 |
| 8086:0808 | Intel      | USB PnP Sound Device         | 134   | snd_usb... | 342CCD2ECF |
| 0d8c:000c | C-Media... | Audio Adapter                | 126   | snd_usb... | 4EC5CDCBD1 |
| b58e:9e84 | Blue Mi... | Yeti Stereo Microphone       | 123   | snd_usb... | 7E563A9D44 |
| 1130:1620 | Tenx Te... | USB AUDIO                    | 117   | snd_usb... | B4CD0BDE35 |
| 0bda:402e | Realtek... | USB Audio                    | 109   | snd_usb... | 8A880E6565 |
| 0d8c:0102 | C-Media... | CM106 Like Sound Device      | 100   | snd_usb... | 136C409F1A |
| 046d:0a44 | Logitech   | Headset H390                 | 96    | snd_usb... | B806A146D2 |
| 413c:a503 | Dell       | AC511 Sound Bar              | 94    | snd_usb... | F20F2BFC32 |
| 0c76:161e | JMTek      | USB PnP Audio Device         | 84    | snd_usb... | 22A32FC3F2 |
| 1852:7022 | GYROCOM... | Fiio E10                     | 83    | snd_usb... | FBCB5D8594 |
| 046d:0a29 | Logitech   | H600 [Wireless Headset]      | 73    | snd_usb... | 56FE4AB8A1 |
| 046d:0a4d | Logitech   | G430 Surround Sound Gamin... | 69    | snd_usb... | 3B31EBD53C |
| 046d:0a8f | Logitech   | H390 headset with microphone | 67    | snd_usb... | 4946A6A02C |
| 0d8c:0134 | C-Media... | TONOR TC-777 Audio Device    | 67    | snd_usb... | 6AE3033841 |
| 045e:070f | Microsoft  | LifeChat LX-3000 Headset     | 66    | snd_usb... | 990FACB027 |
| 0d8c:0103 | C-Media... | CM102-A+/102S+ Audio Cont... | 66    | snd_usb... | 0A76AC3FB8 |
| 17ef:a396 | Lenovo     | ThinkPad USB-C Dock Gen2 ... | 64    | snd_usb... | 3FC424B8C6 |
| 17ef:3083 | Lenovo     | ThinkPad Thunderbolt 3 Do... | 59    | snd_usb... | C625F457A9 |
| 1038:12ad | SteelSe... | SteelSeries Arctis 7         | 58    | snd_usb... | 6DB5E9BE6B |
| 054c:09cc | Sony       | DualShock 4 [CUH-ZCT2x]      | 55    | snd_usb... | 1BE6C8DC87 |
| 1395:0025 | Sennhei... | Headset [PC 8]               | 54    | snd_usb... | DF0C058313 |
| 046d:0a5b | Logitech   | G933 Wireless Headset Dongle | 52    | snd_usb... | FF6B763448 |
| 046d:0a66 | Logitech   | [G533 Wireless Headset Do... | 48    | snd_usb... | 193E15B733 |
| 046d:0a38 | Logitech   | Headset H340                 | 45    | snd_usb... | C0FB875CA5 |
| 08bb:2704 | Texas I... | PCM2704 16-bit stereo aud... | 42    | snd_usb... | 30AA6C2F49 |
| 0d8c:0201 | C-Media... | CM6501                       | 42    | snd_usb... | F9BFF20C4D |
| 17ef:306f | Lenovo     | ThinkPad Dock USB Audio      | 41    | snd_usb... | E9A8FB1275 |
| 046d:0a45 | Logitech   | 960 Headset                  | 39    | snd_usb... | B72E4A7240 |
| 1b1c:0a14 | Corsair    | VOID PRO Wireless Gaming ... | 39    | snd_usb... | 6B45028E3E |
| 041e:324d | Creativ... | Sound Blaster Play! 3        | 38    | snd_usb... | 280B8AF5CC |
| 03f0:056b | Hewlett... | USB Audio                    | 37    | snd_usb... | F8024B89D4 |
| 0b0e:245e | GN Netcom  | Jabra Link 370               | 37    | snd_usb... | 49C747EFAD |
| 0556:0001 | Asahi K... | AK5370 I/F A/D Converter     | 36    | snd_usb... | DE3B970F84 |
| 08bb:2912 | Texas I... | PCM2912A Audio Codec         | 35    | snd_usb... | 2A2CFDB7D4 |
| 046d:0a1f | Logitech   | G930                         | 33    | snd_usb... | 9D2A807F08 |
| 1532:0520 | Razer USA  | Kraken Tournament Edition    | 33    | snd_usb... | EE6A141211 |
| 0d8c:000e | C-Media... | Audio Adapter (Planet UP-... | 32    | snd_usb... | E30173ADF4 |
| 1038:1294 | SteelSe... | Arctis Pro Wireless          | 32    | snd_usb... | F2CE1A8260 |
| 0b0e:0305 | GN Netcom  | Jabra EVOLVE Link MS         | 31    | snd_usb... | 1BF61C0698 |
| 19f7:0003 | RODE Mi... | RODE NT-USB                  | 31    | snd_usb... | 0EABE998D2 |
| 046d:0a37 | Logitech   | USB Headset H540             | 30    | snd_usb... | F27A29129F |
| 08bb:2900 | Texas I... | PCM2900 Audio Codec          | 29    | snd_usb... | 746401B748 |
| 17ef:306a | Lenovo     | ThinkPad Thunderbolt 3 Do... | 29    | snd_usb... | AA67AEB304 |
| 0b0e:245d | GN Netcom  | Jabra Link 370               | 28    | snd_usb... | 8E04250418 |
| 17a0:0310 | Samson ... | Meteor condenser microphone  | 28    | snd_usb... | 1E7666D492 |
| 17ef:3063 | Lenovo     | ThinkPad Dock Audio          | 27    | snd_usb... | FEEC038877 |
| 041e:30df | Creativ... | SB X-Fi Surround 5.1 Pro     | 26    | snd_usb... | 43894B89A7 |
| 041e:3232 | Creativ... | Sound Blaster Premium HD ... | 26    | snd_usb... | 357EA9AB5D |
| 047f:c056 | Plantro... | Blackwire 3220 Series        | 26    | snd_usb... | 396CA17477 |
| 0a12:1243 | Cambrid... | Audioengine HD3              | 26    | snd_usb... | BB94FAA2B1 |
| 041e:3237 | Creativ... | SB X-Fi Surround 5.1 Pro     | 25    | snd_usb... | 2713972F14 |
| 046d:0aaa | Logitech   | PRO X                        | 25    | snd_usb... | FC6F79950A |
| 0d8c:0008 | C-Media... | USB Audio Device             | 25    | snd_usb... | 0898C11493 |
| 0d8c:016c | C-Media... | USB Advanced Audio Device    | 25    | snd_usb... | A7EA75F7C5 |
| 047f:02ee | Plantro... | BT600                        | 24    | snd_usb... | FB94B38F6D |
| 18c3:6255 | Elite S... | USB Audio Device             | 24    | snd_usb... | 38F7084DAC |
| 28de:2102 | Valve S... | Valve VR Radio & HMD Mic     | 24    | snd_usb... | F5C02601D0 |
| 05a7:1020 | Bose       | USB Audio                    | 23    | snd_usb... | 22A32FC3F2 |
| 0d8c:0001 | C-Media... | Audio Device                 | 23    | snd_usb... | 68D9423AFE |
| 041e:3040 | Creativ... | SoundBlaster Live! 24-bit... | 22    | snd_usb... | 235E8C9537 |
| 046d:0a15 | Logitech   | G35 Headset                  | 22    | snd_usb... | 0A88FF958D |
| 0d8c:0126 | C-Media... | USB Audio Device             | 22    | snd_usb... | 78B2FAB1E0 |
| 262a:9023 | SAVITECH   | Bravo-X USB Audio            | 22    | snd_usb... | 0F4AE74D8E |
| 041e:3256 | Creativ... | Sound BlasterX G6            | 21    | snd_usb... | BB422D7EFE |
| 047f:02f7 | Plantro... | BT600                        | 21    | snd_usb... | 1BB97BC7DF |
| 0c76:160c | JMTek      | USB Speaker                  | 21    | snd_usb... | 27E2083302 |
| 17a0:0305 | Samson ... | GoMic compact condenser mic  | 21    | snd_usb... | BEE34D8394 |
| 046d:0a0c | Logitech   | Clear Chat Comfort USB He... | 20    | snd_usb... | 5E8A523A20 |
| 047f:c025 | Plantro... | C320-M                       | 20    | snd_usb... | 7F0754075C |
| 08bb:2904 | Texas I... | PCM2904 Audio Codec          | 20    | snd_usb... | ED77D40EEB |
| 0b0e:0420 | GN Netcom  | Jabra SPEAK 510              | 20    | snd_usb... | E16A18BC8B |
| 0c76:1607 | JMTek      | audio controller             | 20    | snd_usb... | BA51FC9216 |
| 0d8c:0139 | C-Media... | Multimedia Headset [Gigaw... | 20    | snd_usb... | 99FC59557A |
| 1038:1260 | SteelSe... | Arctis 7 wireless adapter    | 20    | snd_usb... | 36B667DA98 |
| 046d:0a01 | Logitech   | USB Headset                  | 19    | snd_usb... | B2115B09E3 |
| 046d:0a5c | Logitech   | G633 Gaming Headset          | 19    | snd_usb... | 2FF008A28D |
| 0951:16c4 | Kingsto... | HyperX Cloud Flight Wirel... | 19    | snd_usb... | 12DB76B549 |
| 1b1c:0a4f | Corsair    | HS70 Pro Wireless Gaming ... | 19    | snd_usb... | 10F8E5F5CF |
| 2188:6533 | No brand   | Thunderbolt 3 Audio          | 19    | snd_usb... | 20EED1CD12 |
| 03f0:0269 | Hewlett... | USB Audio                    | 18    | snd_usb... | 532CB2DFC8 |
| 046d:0a03 | Logitech   | Logitech USB Microphone      | 18    | snd_usb... | 85B942A5C3 |
| 08bb:29c0 | Texas I... | PCM2900C Audio CODEC         | 18    | snd_usb... | CB6CAEFA10 |
| 1038:12aa | SteelSe... | SteelSeries Arctis 5         | 18    | snd_usb... | E1DDC26C5E |
| 1532:0504 | Razer USA  | Kraken 7.1 Chroma            | 18    | snd_usb... | 3E95020892 |
| 1532:0510 | Razer USA  | Kraken 7.1 V2                | 18    | snd_usb... | CFBE862160 |
| 041e:30d3 | Creativ... | Sound Blaster Play!          | 17    | snd_usb... | B92A5DC353 |
| 047f:c012 | Plantro... | Audio 628 USB                | 17    | snd_usb... | F8BB575441 |
| 08bb:29b3 | Texas I... | PCM2903B Audio CODEC         | 17    | snd_usb... | D998D59215 |
| 1b1c:0a38 | Corsair    | HS70 Wireless Gaming Headset | 17    | snd_usb... | 3C2298BA3B |
| 047f:c053 | Plantro... | Blackwire 5220 Series        | 16    | snd_usb... | 603CCDFB84 |
| 05e1:0408 | Syntek     | STK1160 Video Capture Device | 16    | stk1160    | 143436EBD4 |

### Touchpad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 06cb:2970 | Synaptics  | touchpad                     | 74    | usbhid     | 0B2EC748F2 |
| 044e:1218 | Alps El... | Touchpad                     | 20    | usbhid     | 5097E0F8C8 |
| 044e:120d | Alps El... | Touchpad                     | 12    | usbhid     | 89E5AB8846 |
| 06cb:0009 | Synaptics  | Composite TouchPad and Tr... | 10    | synapti... | B8973B3B0A |
| 044e:1216 | Alps El... | Touchpad                     | 7     | usbhid     | D6AB5352B8 |
| 044e:120f | Alps El... | Touchpad                     | 6     | usbhid     | BF9CC483F0 |
| 044e:1217 | Alps El... | Touchpad                     | 6     | usbhid     | 5A85AB6B0F |
| 17ef:6046 | Lenovo     | Wireless Touchpad K5923      | 6     | usbhid     | F600127AB1 |
| 06cb:5710 | Synaptics  | SynapticsTouch Pad V 1.03U3  | 4     | usbhid     | 5834B6321D |
| 0488:0280 | Cirque     | 9925 AG Touchpad             | 3     | usbhid     | 66C97ED64B |
| 04b4:fef3 | Cypress... | OSA Express Network card     | 3     | usbhid     | A1FFAD5B6D |
| 06cb:7af9 | Synaptics  | HIDUSB TouchPad V07          | 3     | usbhid     | D20C059F3D |
| 044e:1210 | Alps El... | Touchpad                     | 2     | usbhid     | 4FA01CCEE6 |
| 044e:1221 | Alps El... | Touchpad                     | 2     | usbhid     | 6EE77ED959 |
| 0488:8010 | Cirque     | 9925 AG Touchpad             | 1     | usbhid     | 1498A5A5A4 |
| 062a:19b5 | MosArt ... | TouchPad                     | 1     | usbhid     | 61BB547684 |
| 06cb:0001 | Synaptics  | TouchPad                     | 1     | synapti... | 7023DC94DA |
| 06cb:0096 | Synaptics  | HIDUSB TouchPad V01          | 1     | usbhid     | 1E10940254 |
| 06cb:5711 | Synaptics  | Touch Pad V 103u9            | 1     | usbhid     | 2D9527DBD4 |
| 06cb:7d29 | Synaptics  | HIDUSB TouchPad V03          | 1     | usbhid     | 49A6D8DEC1 |
| 413c:2507 | Dell       | TP713 Wireless Touchpad      | 1     | usbhid     | 8A10AE7D58 |

### Touchscreen (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04f3:20d0 | Elan Mi... | Touchscreen                  | 54    | usbhid     | DDE814D7CA |
| 0eef:0001 | D-WAV S... | Titan6001 Surface Acousti... | 53    | usbhid     | F98CCE15A3 |
| 04f3:2494 | Elan Mi... | Touchscreen                  | 39    | usbhid     | 5575068859 |
| 04f3:250e | Elan Mi... | Touchscreen                  | 38    | usbhid     | C7BE2FF77E |
| 0408:3008 | Quanta     | Optical Touch Screen         | 31    | usbhid     | 81048AABF5 |
| 04f3:012d | Elan Mi... | Touchscreen                  | 22    | usbhid     | 5CD5DD7086 |
| 04f3:24a0 | Elan Mi... | Touchscreen                  | 22    | usbhid     | 69938C221E |
| 04f3:0254 | Elan Mi... | Touchscreen                  | 21    | usbhid     | 9FACBD3D72 |
| 04f3:2234 | Elan Mi... | Touchscreen                  | 21    | usbhid     | 8BB0307157 |
| 04f3:24a1 | Elan Mi... | Touchscreen                  | 21    | usbhid     | B33AF6D329 |
| 04f3:2acc | Elan Mi... | Touchscreen                  | 20    | usbhid     | 10C9991F0B |
| 04f3:016f | Elan Mi... | Touchscreen                  | 19    | usbhid     | D07052119D |
| 04f3:21d5 | Elan Mi... | Touchscreen                  | 19    | usbhid     | 32EC7FD885 |
| 04f3:2013 | Elan Mi... | Touchscreen                  | 17    | usbhid     | 11BEA838AA |
| 04f3:010c | Elan Mi... | Touchscreen                  | 16    | usbhid     | F56A2BD3FA |
| 1926:0006 | NextWindow | 1950 HID Touchscreen         | 15    | usbhid     | 622D9B0AE4 |
| 04f3:000a | Elan Mi... | Touchscreen                  | 14    | usbhid     | F5565DFB2A |
| 04f3:0224 | Elan Mi... | Touchscreen                  | 14    | usbhid     | B64657DAFD |
| 04f3:0042 | Elan Mi... | Touchscreen                  | 13    | usbhid     | 5EBA5CDCBF |
| 04f3:034e | Elan Mi... | Touchscreen                  | 13    | usbhid     | 102ED51ABD |
| 04f3:2337 | Elan Mi... | Touchscreen                  | 13    | usbhid     | 67552D79AC |
| 04f3:0085 | Elan Mi... | Touchscreen                  | 12    | usbhid     | 8AEC766EA6 |
| 04f3:2398 | Elan Mi... | Touchscreen                  | 12    | usbhid     | 5C87BCB1DC |
| 04f3:289b | Elan Mi... | Touchscreen                  | 12    | usbhid     | 2D3F367FA7 |
| 1926:0003 | NextWindow | 1900 HID Touchscreen         | 12    | usbhid     | C5AB105EAD |
| 04f3:036e | Elan Mi... | Touchscreen                  | 11    | usbhid     | 5900E800AA |
| 04f3:2012 | Elan Mi... | Touchscreen                  | 11    | usbhid     | 8FA08D58EF |
| 04f3:22c3 | Elan Mi... | Touchscreen                  | 11    | usbhid     | 86719BBD60 |
| 04f3:2753 | Elan Mi... | Touchscreen                  | 11    | usbhid     | 728E0FACD6 |
| 04f3:0023 | Elan Mi... | Touchscreen                  | 10    | usbhid     | 7302DC6BE1 |
| 04f3:002a | Elan Mi... | Touchscreen                  | 10    | usbhid     | B977195EB4 |
| 04f3:0034 | Elan Mi... | Touchscreen                  | 10    | usbhid     | CAC5BCFFE9 |
| 04f3:24e1 | Elan Mi... | Touchscreen                  | 10    | usbhid     | 6C65C257C6 |
| 04e7:0020 | Elo Tou... | Touchscreen Interface (2700) | 9     | usbhid     | 7A38C478BB |
| 04f3:0206 | Elan Mi... | Touchscreen                  | 9     | usbhid     | 1493A2EAE1 |
| 04f3:0389 | Elan Mi... | Touchscreen                  | 9     | usbhid     | 3EECFD13AD |
| 04f3:2083 | Elan Mi... | Touchscreen                  | 9     | usbhid     | 70496150EB |
| 04f3:2672 | Elan Mi... | Touchscreen                  | 9     | usbhid     | 06E7A51D6A |
| 04f3:2793 | Elan Mi... | Touchscreen                  | 9     | usbhid     | E2A4A5E396 |
| 1926:0bce | NextWindow | Touchscreen                  | 9     | usbhid     | 626BFE0484 |
| 04f3:0135 | Elan Mi... | Touchscreen                  | 8     | usbhid     | 0AD6768049 |
| 04f3:0301 | Elan Mi... | Touchscreen                  | 8     | usbhid     | 2F6B8A2BD6 |
| 04f3:0303 | Elan Mi... | Touchscreen                  | 8     | usbhid     | 7FBD3218A8 |
| 04f3:2033 | Elan Mi... | Touchscreen                  | 8     | usbhid     | D0D5054FE1 |
| 04f3:2070 | Elan Mi... | Touchscreen                  | 8     | usbhid     | 0B68C3F5C3 |
| 04f3:24dd | Elan Mi... | Touchscreen                  | 8     | usbhid     | 03B08007CD |
| 04f3:2884 | Elan Mi... | Touchscreen                  | 8     | usbhid     | F7309EF31A |
| 04f3:034f | Elan Mi... | Touchscreen                  | 7     | usbhid     | DCA302A80B |
| 04f3:0436 | Elan Mi... | Touchscreen                  | 7     | usbhid     | 15E92E7427 |
| 04f3:0439 | Elan Mi... | Touchscreen                  | 7     | usbhid     | 7A0695E6BB |
| 04f3:2071 | Elan Mi... | Touchscreen                  | 7     | usbhid     | E1DFE46F2F |
| 04f3:2089 | Elan Mi... | Touchscreen                  | 7     | usbhid     | E2DB581D0B |
| 04f3:20d6 | Elan Mi... | Touchscreen                  | 7     | usbhid     | 8D16328DFD |
| 04f3:228a | Elan Mi... | Touchscreen                  | 7     | usbhid     | 0D1A190DED |
| 04f3:245a | Elan Mi... | Touchscreen                  | 7     | usbhid     | ED461C00CA |
| 04f3:2497 | Elan Mi... | Touchscreen                  | 7     | usbhid     | 2713F21DD7 |
| 1926:0dbe | NextWindow | Touchscreen                  | 7     | usbhid     | BF3A74D7D0 |
| 04f3:003d | Elan Mi... | Touchscreen                  | 6     | usbhid     | D70E2B74D0 |
| 04f3:009d | Elan Mi... | Touchscreen                  | 6     | usbhid     | 14086A6760 |
| 04f3:0111 | Elan Mi... | Touchscreen                  | 6     | usbhid     | E4D6F94CCB |
| 04f3:024b | Elan Mi... | Touchscreen                  | 6     | usbhid     | D96AEA9F90 |
| 04f3:0363 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 6F1CA4C9FD |
| 04f3:0428 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 2A367A6EE4 |
| 04f3:2044 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 3871A3C4FC |
| 04f3:206f | Elan Mi... | Touchscreen                  | 6     | usbhid     | CBBC9C0451 |
| 04f3:228b | Elan Mi... | Touchscreen                  | 6     | usbhid     | 243BB6524D |
| 04f3:22ea | Elan Mi... | Touchscreen                  | 6     | usbhid     | 566FA6B1D5 |
| 04f3:2313 | Elan Mi... | Touchscreen                  | 6     | usbhid     | CF08166AE9 |
| 1926:1846 | NextWindow | Touchscreen                  | 6     | usbhid     | CA3F4AA75A |
| 0408:3003 | Quanta     | OpticalTouchScreen           | 5     | usbhid     | 1CBEE8A7EF |
| 04f3:0089 | Elan Mi... | Touchscreen                  | 5     | usbhid     | D63ABB12EE |
| 04f3:009c | Elan Mi... | Touchscreen                  | 5     | usbhid     | 229728B316 |
| 04f3:0201 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 02548CA78D |
| 04f3:0261 | Elan Mi... | Touchscreen                  | 5     | usbhid     | B6B916AFD7 |
| 04f3:0268 | Elan Mi... | Touchscreen                  | 5     | usbhid     | D5EDE165EC |
| 04f3:0307 | Elan Mi... | Touchscreen                  | 5     | usbhid     | D3F828A286 |
| 04f3:031a | Elan Mi... | Touchscreen                  | 5     | usbhid     | F67C2F8D32 |
| 04f3:034a | Elan Mi... | Touchscreen                  | 5     | usbhid     | 6690081521 |
| 04f3:038a | Elan Mi... | Touchscreen                  | 5     | usbhid     | AAF45F99A4 |
| 04f3:0396 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 366DCDAD53 |
| 04f3:0418 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 3C7ED2F9B7 |
| 04f3:2020 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 0A7B01F59F |
| 04f3:2039 | Elan Mi... | Touchscreen                  | 5     | usbhid     | E3ACA6B408 |
| 04f3:2073 | Elan Mi... | Touchscreen                  | 5     | usbhid     | E5C02D2922 |
| 04f3:2085 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 871B9656F1 |
| 04f3:21b4 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 4C55449378 |
| 04f3:21c3 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 801535D049 |
| 04f3:21d4 | Elan Mi... | Touchscreen                  | 5     | usbhid     | D403FA5702 |
| 04f3:2252 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 00123E7E27 |
| 04f3:2266 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 15B5A3DEAE |
| 04f3:228e | Elan Mi... | Touchscreen                  | 5     | usbhid     | 89CCCAF8CF |
| 04f3:2379 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 82E8AEFE39 |
| 04f3:254f | Elan Mi... | Touchscreen                  | 5     | usbhid     | 92DCB677F7 |
| 04f3:2754 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 74D1170C9D |
| 04f3:2837 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 52E5D3E16D |
| 1926:0082 | NextWindow | 1950 HID Touchscreen         | 5     | usbhid     | FD68D44A6A |
| 1926:0093 | NextWindow | Touchscreen                  | 5     | usbhid     | 29ECAF9382 |
| 1926:0344 | NextWindow | Touchscreen                  | 5     | usbhid     | 73FE3F4EE7 |
| 1926:0e17 | NextWindow | Touchscreen                  | 5     | usbhid     | EEB433BF77 |
| 04f3:000c | Elan Mi... | Touchscreen                  | 4     | usbhid     | B00AE19B84 |

### Tv card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:0892 | Logitech   | C920 HD Pro Webcam           | 174   | gspca_v... | 15A954CCE4 |
| 1415:2000 | Nam Tai... | Sony Playstation Eye         | 89    | gspca_o... | 14BC5C234D |
| 0402:5602 | ALi        | M5602 Video Camera Contro... | 88    | gspca_m... | B09A0D7779 |
| 045e:00f7 | Microsoft  | LifeCam VX-1000              | 57    | gspca_s... | 06D254591F |
| 046d:08d7 | Logitech   | QuickCam Communicate STX     | 51    | gspca_z... | 4AD36B7601 |
| 0ac8:303b | Z-Star ... | ZC0303 Webcam                | 49    | gspca_z... | 3C302B5285 |
| 093a:2620 | Pixart ... | TV Card                      | 48    | gspca_p... | 79A5EF3DAD |
| 046d:0896 | Logitech   | OrbiCam                      | 37    | gspca_v... | 7E2DA6D3E9 |
| 045e:00f5 | Microsoft  | LifeCam VX-3000              | 35    | gspca_s... | 23F7EA44CE |
| 05e1:0501 | Syntek     | DC-1125 Webcam               | 30    | stkwebcam  | AE3220A328 |
| 046d:08da | Logitech   | QuickCam Messanger           | 28    | gspca_z... | 24329438D1 |
| 0ac8:305b | Z-Star ... | ZC0305 Webcam                | 28    | gspca_z... | BA5FE21088 |
| 046d:089d | Logitech   | QuickCam E2500 series        | 24    | gspca_z... | 57601D98F3 |
| 093a:2622 | Pixart ... | Webcam Genius                | 24    | gspca_p... | 30D745E8D3 |
| 174f:a311 | Syntek     | 1.3MPixel Web Cam - Asus ... | 24    | stkwebcam  | 4192E41344 |
| 046d:08d9 | Logitech   | QuickCam IM/Connect          | 23    | gspca_z... | 30E50BF019 |
| 093a:2468 | Pixart ... | SoC PC-Camera                | 23    | gspca_p... | 410672559F |
| 093a:262c | Pixart ... | TV Card                      | 21    | gspca_p... | DF8210558E |
| 046d:08ad | Logitech   | QuickCam Communicate STX     | 18    | gspca_z... | 566B587DD9 |
| 0c45:624f | Microdia   | PC Camera (SN9C201 + OV9650) | 18    | gspca_s... | 5E8CB420EA |
| 0ac8:307b | Z-Star ... | USB 1.1 Webcam               | 14    | gspca_z... | 93004B8E8F |
| 093a:2624 | Pixart ... | Webcam                       | 13    | gspca_p... | 673D4FAA98 |
| 046d:08af | Logitech   | QuickCam Easy/Cool           | 12    | gspca_z... | 163B47753D |
| 0ac8:301b | Z-Star ... | ZC0301 Webcam                | 12    | gspca_z... | 2E8639BADA |
| 2040:7200 | Hauppauge  | WinTV HVR-950                | 12    | au0828     | FE850F1CA6 |
| 093a:2460 | Pixart ... | Q-TEC WEBCAM 100             | 11    | gspca_p... | C7C1D06954 |
| 093a:2621 | Pixart ... | PAC731x Trust Webcam         | 11    | gspca_p... | 3E710C5B09 |
| 041e:4052 | Creativ... | Live! Cam Vista IM           | 10    | gspca_o... | DF4338099C |
| 045e:00f4 | Microsoft  | LifeCam VX-6000 (SN9C20x ... | 10    | gspca_s... | 535D0016E2 |
| 046d:08f0 | Logitech   | QuickCam Messenger           | 9     | gspca_s... | 1005EC2531 |
| 046d:092f | Logitech   | QuickCam Express Plus        | 9     | gspca_s... | 83DFC4B9D8 |
| 093a:2476 | Pixart ... | CIF Single Chip              | 9     | gspca_p... | 324E08922C |
| 093a:2626 | Pixart ... | TV Card                      | 9     | gspca_p... | F4AE9B990F |
| 0ac8:c002 | Z-Star ... | Visual Communication Came... | 9     | gspca_v... | 7C1F897BC6 |
| 0c45:608f | Microdia   | PC Camera (SN9C103 + OV7630) | 9     | gspca_s... | 8EE329F5CF |
| 0471:0329 | Philips... | SPC 900NC PC Camera / ORI... | 8     | pwc        | 88DCB8813A |
| 041e:405f | Creativ... | WebCam Vista (VF0330)        | 7     | gspca_o... | 11FED8F8AE |
| 041e:4064 | Creativ... | VF0420 Live! Cam Vista IM    | 7     | gspca_o... | EF8DFE0673 |
| 093a:2472 | Pixart ... | CIF Single Chip              | 7     | gspca_p... | 0DC7C8F9DC |
| 0c45:6007 | Microdia   | VideoCAM Eye                 | 7     | gspca_s... | 39C5751F26 |
| 0c45:600d | Microdia   | TwinkleCam USB camera        | 7     | gspca_s... | 584063E568 |
| 0c45:6242 | Microdia   | PC Camera (SN9C201 + MI1310) | 7     | gspca_s... | 18019F6606 |
| 2304:021a | Pinnacl... | Dazzle DVC100 Audio Device   | 7     | em28xx     | 0778440642 |
| 046d:08a2 | Logitech   | Labtec Webcam Pro            | 6     | gspca_z... | 72DD85EA81 |
| 046d:08dd | Logitech   | QuickCam for Notebooks       | 6     | gspca_z... | 769A6A4900 |
| 0733:0401 | ViewQue... | CS330 Webcam                 | 6     | gspca_s... | 16640D2961 |
| 093a:2608 | Pixart ... | PAC7311 Trust WB-3300p       | 6     | gspca_p... | A43D67CD48 |
| 0ac8:0328 | Z-Star ... | A4Tech PK-130MG              | 6     | gspca_v... | A3D54DEE1B |
| 0c45:6028 | Microdia   | Typhoon Easycam USB 330K ... | 6     | gspca_s... | CC9D06DBBB |
| 0c45:613c | Microdia   | PC Camera (SN9C120)          | 6     | gspca_s... | 88FF9DCD47 |
| 0c45:6270 | Microdia   | PC Camera (SN9C201 + MI03... | 6     | gspca_s... | AD7EBCC3C5 |
| eb1a:2861 | eMPIA T... | EasyCAP DC60+ [EM2861]       | 6     | em28xx     | 25822EE96D |
| 046d:092e | Logitech   | QuickCam Chat                | 5     | gspca_s... | 3A04E52D73 |
| 093a:2600 | Pixart ... | Typhoon Easycam USB 330K ... | 5     | gspca_p... | F32DFBFE2A |
| 0c45:6260 | Microdia   | PC Camera (SN9C201 + OV76... | 5     | gspca_s... | 43B40CA9ED |
| 041e:4034 | Creativ... | Webcam Instant               | 4     | gspca_z... | 4929B0E708 |
| 041e:4036 | Creativ... | Webcam Live!/Live! Pro       | 4     | gspca_z... | BA80D79115 |
| 046d:0870 | Logitech   | QuickCam Express             | 4     | gspca_s... | D3F38DBF63 |
| 046d:08ae | Logitech   | QuickCam for Notebooks       | 4     | snd_usb... | 4152D7A631 |
| 046d:0928 | Logitech   | QuickCam Express             | 4     | gspca_s... | 1604193C0F |
| 0471:032d | Philips... | SPC 210NC PC Camera          | 4     | gspca_z... | FB4D52B3B2 |
| 04fc:0561 | Sunplus... | Flexcam 100                  | 4     | gspca_s... | 6EB800A8C2 |
| 054c:0155 | Sony       | Eyetoy Video Device          | 4     | gspca_o... | 222C467B30 |
| 093a:2470 | Pixart ... | SoC PC-Camera                | 4     | gspca_p... | 8BEEE2F359 |
| 093a:260e | Pixart ... | PAC7311 Gigaware VGA PC C... | 4     | gspca_p... | 2462C80A14 |
| 0ac8:0302 | Z-Star ... | ZC0302 Webcam                | 4     | gspca_z... | 56DD661396 |
| 0ac8:0321 | Z-Star ... | Vimicro generic vc0321 Ca... | 4     | gspca_v... | 2466DF7773 |
| 0c45:6128 | Microdia   | PC Camera (SN9C325 + OM6802) | 4     | gspca_s... | F75214C8D9 |
| 041e:401f | Creativ... | Webcam Notebook [PD1171]     | 3     | gspca_z... | 200E91CA92 |
| 041e:4061 | Creativ... | Live! Cam Notebook Pro [V... | 3     | gspca_o... | AAB6789435 |
| 041e:4068 | Creativ... | Live! Cam Notebook [VF0470]  | 3     | gspca_o... | 3FDF6B4559 |
| 046d:08f5 | Logitech   | QuickCam Messenger Commun... | 3     | gspca_s... | 139478F373 |
| 046d:0929 | Logitech   | Labtec Webcam Pro            | 3     | gspca_s... | 9A2D988ABA |
| 046d:092b | Logitech   | Labtec Webcam Plus           | 3     | gspca_s... | 966D2650E0 |
| 046d:092c | Logitech   | QuickCam Chat                | 3     | gspca_s... | 40CF3439DB |
| 05a9:8519 | OmniVis... | OV519 Webcam                 | 3     | gspca_o... | DC19FC7FD2 |
| 0c45:602c | Microdia   | Clas Ohlson TWC-30XOP Webcam | 3     | gspca_s... | 84AB3C0A57 |
| 0c45:602e | Microdia   | VideoCAM Messenger           | 3     | gspca_s... | 11B0CECD6B |
| 0c45:60b0 | Microdia   | Genius VideoCam Look         | 3     | gspca_s... | A053325EFE |
| 0c45:613a | Microdia   | PC Camera (SN9C120)          | 3     | gspca_s... | 93490E7142 |
| 0c45:613b | Microdia   | Win2 PC Camera               | 3     | gspca_s... | AB98B73D62 |
| 0c45:627b | Microdia   | PC Camera (SN9C201 + OV7660) | 3     | gspca_s... | E89B83FDD4 |
| 0ccd:0096 | TerraTe... | Grabby                       | 3     | em28xx     | 560552DEB4 |
| 041e:401d | Creativ... | Webcam NX Ultra              | 2     | gspca_s... | 969BF56907 |
| 041e:401e | Creativ... | Webcam NX Pro                | 2     | gspca_z... | 8EBC1639B1 |
| 0458:7004 | KYE Sys... | VideoCAM Express V2          | 2     | gspca_s... | 7B80116745 |
| 046d:08a9 | Logitech   | Notebook Deluxe              | 2     | gspca_z... | F81A55F416 |
| 046d:08d8 | Logitech   | QuickCam for Notebook Deluxe | 2     | gspca_z... | 1280EBBEDF |
| 046d:08f6 | Logitech   | QuickCam Messenger Plus      | 2     | gspca_s... | F55F5434E6 |
| 046d:0920 | Logitech   | QuickCam Express             | 2     | gspca_t... | 1A6EEA194F |
| 0471:032e | Philips... | SPC 315NC PC Camera          | 2     | gspca_z... | 4048E5035D |
| 0553:0002 | STMicro... | CPiA Webcam                  | 2     | gspca_c... | D5FFD1FF38 |
| 05a9:4519 | OmniVis... | Webcam Classic               | 2     | gspca_o... | 5BF965D2F1 |
| 06f8:3004 | Guillemot  | Hercules Classic Silver      | 2     | gspca_s... | ECF2D90F81 |
| 06f8:3008 | Guillemot  | USB camera                   | 2     | gspca_s... | 7966B612A9 |
| 0923:010f | IC Media   | SIIG MobileCam               | 2     | gspca_t... | C00289E6ED |
| 093a:2471 | Pixart ... | SoC PC-Camera                | 2     | gspca_p... | 79B90A017A |
| 0c45:6001 | Microdia   | Genius VideoCAM NB           | 2     | gspca_s... | D165244F3B |
| 0c45:60c0 | Microdia   | PC Camera with Mic (SN9C105) | 2     | gspca_s... | 7DC713CD9F |
| 0c45:624e | Microdia   | PC Camera (SN9C201 + SOI968) | 2     | gspca_s... | 7CD8FE006C |

### Ups (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 051d:0002 | America... | Uninterruptible Power Supply | 491   | usbhid     | 6E020F3AD1 |
| 0764:0501 | Cyber P... | CP1500 AVR UPS               | 199   | usbhid     | 588CEFB67B |
| 0463:ffff | MGE UPS... | UPS                          | 45    | usbhid     | 8789F3F1E1 |
| 0d9f:0004 | Powercom   | HID UPS Battery              | 27    | usbhid     | 77BB019FE0 |
| 051d:0003 | America... | UPS                          | 24    | usbhid     | 658F8F2FD1 |
| 0764:0601 | Cyber P... | PR1500LCDRT2U UPS            | 24    | usbhid     | 8620323354 |
| 06da:ffff | Phoenix... | Offline UPS                  | 12    | usbhid     | 990FACB027 |
| 0925:1234 | Lakevie... | UPS USB MON V1.4             | 10    | usbhid     | 1BC488324F |
| 06da:0003 | Phoenix... | 1300VA UPS                   | 8     | usbhid     | 6A1741B4B2 |
| 0d9f:00a2 | Powercom   | Imperial Uninterruptible ... | 6     | usbhid     | 2846E3D112 |
| 0d9f:00a6 | Powercom   | Black Knight PRO Uninterr... | 5     | usbhid     | 282ECB40CA |
| 0592:0002 | Powerware  | UPS (X-Slot)                 | 4     | usbfs      | E18761A6B2 |
| 09ae:3016 | Tripp Lite | UPS                          | 4     | usbhid     | 7AEE1156D8 |
| 0d9f:00a3 | Powercom   | Smart King PRO Uninterrup... | 4     | usbhid     | 89CC93BB0F |
| 0d9f:00a4 | Powercom   | WOW Uninterruptible Power... | 3     | usbhid     | 0C982DF6CC |
| 05dd:a011 | Delta E... | MINUTEMAN UPS                | 2     | usbhid     | 1BAE5B1DC6 |
| 09ae:2012 | Tripp Lite | UPS                          | 2     | usbhid     | 8D6C4235C3 |
| 03f0:1fe2 | Hewlett... | T1000 G3 UPS                 | 1     | usbhid     | 19AE174CC7 |
| 050d:0751 | Belkin ... | Belkin UPS                   | 1     | usbhid     | E4FDAFF878 |
| 06da:0002 | Phoenix... | UPS                          | 1     |            | 4F5E89A87E |
| 09ae:2010 | Tripp Lite | UPS                          | 1     | usbhid     | 5D1A48EE4E |
| 09ae:4004 | Tripp Lite | UPS                          | 1     | usbfs      | 52D5275C7F |
| 10af:0001 | Liebert    | PowerSure PSA UPS            | 1     | usbhid     | C7B9018598 |

### Video (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0fd9:0066 | Elgato ... | Cam Link 4K                  | 9     | snd_usb... | 174875A3D4 |
| 048d:9006 | Integra... | IT9135 BDA Afatech DVB-T ... | 8     | dvb_usb... | A40F61B08A |
| 1164:1ee9 | YUAN Hi... | Polaris AV Capture           | 5     |            | 7600B0715D |
| 2304:0224 | Pinnacl... | Pinnacle High Speed USB D... | 5     |            | 9B0B45B6FB |
| 0fd9:0051 | Elgato ... | GameCapture HD               | 2     |            | 3A3874784C |
| 0fd9:0067 | Elgato ... | Cam Link 4K                  | 2     | snd_usb... | EDD8B3C5B2 |
| 0fd9:006a | Elgato ... | Game Capture HD60 S+         | 2     | snd_usb... | 610B9319E9 |
| 1b80:a41c | Afatech    | Polaris AV Capture           | 2     |            | 6DE34F58AF |
| 04b4:00f9 | Cypress... | Ninja Dock                   | 1     | usbhid     | 79FA3F7509 |
| 0fd9:0061 | Elgato ... | Cam Link                     | 1     | uvcvideo   | 5114B3BC7A |
| 0fd9:0062 | Elgato ... | Cam Link                     | 1     | snd_usb... | D0234C90FB |
| 5555:3382 | Epiphan... | VGA2USB Frame Grabber        | 1     |            | 37A831391B |

### Webcam (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 145f:013c | Trust      | Multimedia audio controller  | 3     | gspca_p... | B85703D1E4 |

### Wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2717:ff88 | Xiaomi     | Mi/Redmi series (RNDIS + ... | 85    | rndis_host | 75B53E8D45 |
| 22b8:2e25 | Motorol... | REVVLRY                      | 52    | rndis_host | 7A993D28FD |
| 2a70:9024 | OnePlus... | OnePlus                      | 16    | rndis_host | 2FDC29F9CB |
| 0489:e0a6 | Foxconn... | Android                      | 11    | rndis_host | CA8DCD489C |
| 12d1:1039 | Huawei ... | Ideos (tethering mode)       | 11    | rndis_host | DE1BE07E5A |
| 18d1:4ee4 | Google     | Nexus/Pixel Device (tethe... | 11    | rndis_host | 42DF25414B |
| 22d9:2766 | OPPO El... | SDM720G-IDP _SN:14DFE8AD     | 9     | rndis_host | 5CA8BBD80D |
| 1286:4e31 | Marvell... | Mobile Composite Device Bus  | 8     | rndis_host | 387EE22BC4 |
| 0b05:7782 | ASUSTek... | Android                      | 6     | rndis_host | A56935A751 |
| 12d1:107c | Huawei ... | Android                      | 6     | rndis_host | C1273267FF |
| 2d95:6ffa | vivo       | 1819                         | 6     | rndis_host | B068BAD0BE |
| 05c6:f626 | Qualcomm   | MDM9607-MTP _SN:E51AF6C2     | 4     | rndis_host | 7D94C98AA7 |
| 0b05:7775 | ASUSTek... | Zenfone GO (ZB500KL) (Deb... | 4     | rndis_host | 5DC8528948 |
| 2d95:6ffb | vivo       | 1819                         | 4     | rndis_host | A8D131CD6A |
| 12d1:2607 | Huawei ... | HUAWEI                       | 3     | rndis_host | DCC1CCB590 |
| 15a9:003a | Gemtek     | Modem YOTA 4G LTE            | 3     | rndis_host | 99F2FBC2FE |
| 17ef:782f | Lenovo     | Lenovo                       | 3     | rndis_host | 0504CFE362 |
| 04b7:88d4 | Compal ... | Android                      | 2     | rndis_host | 63AC92DFF4 |
| 0bb4:0ffc | HTC (Hi... | Android Phone                | 2     | rndis_host | ACC6C85624 |
| 0fce:71aa | Sony Er... | D2303                        | 2     | rndis_host | 0014DBBEAD |
| 0fce:71e8 | Sony Er... | F5321                        | 2     | rndis_host | 70D66C5819 |
| 0fce:71fa | Sony Er... | H8216                        | 2     | rndis_host | 6BF9D537A8 |
| 1271:0541 | Android    | Android                      | 2     | rndis_host | 0C8768F146 |
| 17ef:7c4b | Lenovo     | TB-X606V                     | 2     | rndis_host | B9A115E6A4 |
| 216f:0044 | Altair ... | Alt38XX devboard             | 2     | rndis_host | 92A7F0EA0B |
| 271d:3004 | SPA Con... | Allure M1                    | 2     | rndis_host | B4EF87DE2D |
| 2d95:600b | Android    | Android                      | 2     | rndis_host | B6FA661FDD |
| 0421:06eb | Nokia M... | Nokia_X (RM-980)             | 1     | rndis_host | E8E340D720 |
| 0421:0704 | Nokia M... | Nokia_X2 (RM-1013)           | 1     | rndis_host | 2762E434EB |
| 0471:2005 | Philips... | X586                         | 1     | rndis_host | 84A631B3D1 |
| 04dd:97f2 | Sharp      | SH05F                        | 1     | rndis_host | B10FE6845E |
| 05c6:0a02 | Qualcomm   | Jolla C                      | 1     | rndis_host | A08DCFFB5A |
| 05c6:902d | Qualcomm   | Android                      | 1     | rndis_host | E6C85F7E85 |
| 05c6:90b6 | Qualcomm   | Android                      | 1     | rndis_host | DBCA41493B |
| 0b05:5603 | ASUSTek... | ASUS_Z01RD                   | 1     | rndis_host | 82B2D38326 |
| 0e79:52b7 | Archos     | Archos                       | 1     | rndis_host | 4E4EF907A0 |
| 0fce:7193 | Sony Er... | C6603                        | 1     | rndis_host | F748A62EBE |
| 0fce:71ba | Sony Er... | D6603                        | 1     | rndis_host | 5974A74BFD |
| 0fce:71de | Sony Er... | F3111                        | 1     | rndis_host | D1BA1C9EFA |
| 0fce:71e7 | Sony Er... | F8331                        | 1     | rndis_host | 8AE1EA1D6B |
| 0fce:71f3 | Sony Er... | G8341                        | 1     | rndis_host | 3AF551E450 |
| 0fce:71f6 | Sony Er... | H4311                        | 1     | rndis_host | C9FFEA0EA6 |
| 0fce:7201 | Sony Er... | I4113                        | 1     | rndis_host | A8B162F110 |
| 0fce:720d | Sony Er... | XQ-AS52                      | 1     | rndis_host | 560598D6FB |
| 0fce:81a9 | Sony Er... | D5322                        | 1     | rndis_host | 502EF11B75 |
| 0fce:81bb | Sony Er... | D5803                        | 1     | rndis_host | 7D93192AAE |
| 0fce:81e8 | Sony Er... | F5321                        | 1     | rndis_host | D1E41EC5C0 |
| 0fce:81f1 | Sony Er... | Android                      | 1     | rndis_host | 535EA77E4F |
| 0fce:81f9 | Sony Er... | H8324                        | 1     |            | 75C607555E |
| 0fce:8207 | Sony Er... | I3312                        | 1     | rndis_host | 1DBF9CCED7 |
| 0fce:820e | Sony Er... | XQ-AD51                      | 1     | rndis_host | F2418E15EC |
| 109b:5d20 | Hisense    | U972                         | 1     | rndis_host | B95A7FC433 |
| 15a9:0046 | Gemtek     | 4G Modem                     | 1     | rndis_host | FBF317133B |
| 17ef:79bb | Lenovo     | Android                      | 1     | rndis_host | 0B5B82FFE2 |
| 17ef:7a2f | Lenovo     | Karate                       | 1     | rndis_host | 59C3CB6EA6 |
| 17ef:7be6 | Lenovo     | Android                      | 1     | rndis_host | 750413CC61 |
| 19d2:1611 | ZTE WCD... | Yota Router                  | 1     | rndis_host | 452CA6FFA5 |
| 1bbb:9024 | T & A M... | Alcatel 5059S                | 1     | rndis_host | 050A5F077E |
| 1ecb:02e2 | AMTelecom  | JMR1140                      | 1     | rndis_host | 6F786FC511 |
| 201e:2498 | Android    | Android                      | 1     | rndis_host | 4DE0326F3B |
| 2357:039e | MediaTek   | Neffos C5a                   | 1     | rndis_host | BDE1812AE9 |
| 271d:90b5 | Android    |                              | 1     | rndis_host | 65345FD237 |
| 2916:f00e | Android    | Android                      | 1     | rndis_host | 79937B3042 |
| 2970:0004 | Fly        | Evo Chic 3                   | 1     | rndis_host | A83B92D6B0 |
| 2970:2005 | Wileyfox   | Spark                        | 1     | rndis_host | 2E016FB88C |
| 2a45:0004 | Meizu      | m3                           | 1     | rndis_host | 0D99884DCD |
| 2a96:2005 | MediaTek   | Plume L2 Pro                 | 1     | rndis_host | 0EB94C0487 |
| 2ae5:9024 | Fairphone  | FP2                          | 1     | rndis_host | 8200C0DCD0 |
| 2e17:c008 | Essenti... | PH-1                         | 1     | rndis_host | 224C36CF4D |

### Xbox (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:0289 | Microsoft  | Xbox Controller S            | 3     | xpad       | 0FCCD48745 |
| 045e:0285 | Microsoft  | Xbox Controller S            | 1     | usbfs      | 3B240B1EF9 |
| 0c12:880a | Zeroplus   | Pelican Eclipse PL-2023      | 1     |            | C5BABDFD30 |

### Others (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0b05:18f3 | ASUSTek... | AURA LED Controller          | 544   | usbhid     | A525C8911B |
| 27c6:538d | Shenzhe... | FingerPrint                  | 276   | usbfs      | DA5E2F59CC |
| 0b05:1939 | ASUSTek... | AURA LED Controller          | 267   | usbhid     | 82E27C0415 |
| 05ac:8300 | Apple      | Built-in iSight (no firmw... | 146   | isight_... | 58205197AC |
| 06cb:00da | Synaptics  |                              | 131   |            | 8A34D739FD |
| 2109:0100 | VIA Labs   | USB 2.0 BILLBOARD            | 131   |            | C7A0FE2F88 |
| 2109:0102 | VIA Labs   | USB 2.0 BILLBOARD            | 115   |            | 2AD271E81F |
| 04f3:0c00 | Elan Mi... | ELAN:ARM-M4                  | 100   |            | D49638CC86 |
| 27c6:521d | Shenzhe... | FingerPrint                  | 90    |            | 3F7A2585FE |
| 04f3:0c4b | Elan Mi... | ELAN:Fingerprint             | 84    |            | 04852A18CB |
| 04f3:0c4c | Elan Mi... | ELAN:ARM-M4                  | 78    |            | 5F67B298AB |
| 1c7a:0575 | LighTun... | EgisTec EH575                | 78    |            | 84B1C46F3C |
| 22b8:2e82 | Motorol... | XT1541 [Moto G 3rd Gen]      | 78    | usbfs      | 1F83ADD647 |
| 04f3:0c4d | Elan Mi... | ELAN:Fingerprint             | 62    | usbfs      | 4826046B43 |
| 04f3:0c4f | Elan Mi... | ELAN:Fingerprint             | 61    |            | EFDB9E6636 |
| 1b1c:0c09 | Corsair    | H100i v2                     | 59    |            | F60A34FE5C |
| 1d5c:7102 | Fresco ... | Generic Billboard Device     | 59    |            | F4B1EFA60F |
| 06cb:00d8 | Synaptics  | Synaptics FS7604 Touch Fi... | 48    |            | 4B05A606A3 |
| 2109:0103 | VIA Labs   | USB 2.0 BILLBOARD            | 48    |            | F5385D6B10 |
| 2109:8818 | VIA Labs   | USB Billboard Device         | 47    |            | C625F457A9 |
| 2433:b200 | ASETEK     | [NZXT Kraken X60]            | 42    | usbfs      | 0981774043 |
| 1b1c:0c08 | Corsair    | H80i v2                      | 36    |            | 1FCE457AC6 |
| 03f0:046b | Hewlett... | USB-C Dock G5                | 35    | usbhid     | F8024B89D4 |
| 413c:b080 | Dell       | DA20 Adapter                 | 35    |            | 27F4B2412F |
| 0424:2740 | Microch... | Hub Controller               | 34    |            | F5C02601D0 |
| 27c6:532d | Shenzhe... | Fingerprint                  | 34    |            | 138EC046F1 |
| 2833:0211 | Oculus VR  | Rift CV1 Sensor              | 34    | uvcvideo   | 6E020F3AD1 |
| 17e9:6015 | Display... | ThinkPad Hybrid USB-C wit... | 33    | snd_usb... | E16A18BC8B |
| 17e9:4301 | Display... | USB3.0 UHD HDMI Adapter      | 32    | snd_usb... | 9F69E439BC |
| 27c6:639c | Shenzhe... | Goodix USB2.0 MISC           | 32    |            | 6A3D844D87 |
| 0b05:19af | ASUSTek... | AURA LED Controller          | 30    | usbhid     | 97BD114229 |
| 0483:3748 | STMicro... | ST-LINK/V2                   | 28    |            | 42CD4D28BD |
| 1b1c:0c13 | Corsair    | H115i Platinum               | 28    |            | A7C1A61E9F |
| 17ef:3060 | Lenovo     | ThinkPad Dock                | 27    | usbhid     | FEEC038877 |
| 1b1c:0c15 | Corsair    | H100i Platinum               | 27    | usbfs      | 1B20F40F47 |
| 0bda:5400 | Realtek... | BillBoard Device             | 26    |            | BF7F394D00 |
| 2109:0101 | VIA Labs   | USB 2.0 BILLBOARD            | 26    |            | 90E49546C2 |
| 0b05:7772 | ASUSTek... | Zenfone GO (ZB500KL) (MTP... | 25    | usbfs      | E184C22F47 |
| 06cb:00f0 | Synaptics  |                              | 24    |            | E0D6EAFD15 |
| 1b1c:0c12 | Corsair    | H150i Platinum               | 24    |            | F6EED137F3 |
| 0bda:2171 | Realtek... | BillBoard Device             | 23    |            | E40947106A |
| 17ef:3074 | Lenovo     | USB Billboard                | 23    | usbhid     | E9A8FB1275 |
| 1b1c:0c0a | Corsair    | Hydro Series H115i Liquid... | 23    |            | 6D73A59A01 |
| 27c6:63ac | Shenzhe... | Goodix USB2.0 MISC           | 23    |            | 27F4B2412F |
| 04f3:0c5e | Elan Mi... | ELAN:ARM-M4                  | 22    |            | A92566EE89 |
| 06cb:00cb | Synaptics  |                              | 22    |            | 63EBD660D8 |
| 1d50:6089 | OpenMoko   | Great Scott Gadgets HackR... | 21    | hackrf     | ABDA3BD166 |
| 22b8:2e76 | Motorol... | moto g power (2021)          | 21    | usbfs      | BB9C65380C |
| 0451:82ee | Texas I... |                              | 20    |            | 603CCDFB84 |
| 04eb:e033 | Northst... | eHome Infrared Transceiver   | 20    |            | 248C508EB0 |
| 0bda:5442 | Realtek... | Cable Matters USB-C Video... | 20    |            | C4FB03E194 |
| 2109:8887 | VIA Labs   | 40AN                         | 20    |            | 8E49254C26 |
| 04f3:0c63 | Elan Mi... | ELAN:Fingerprint             | 19    |            | A3AB1B4A11 |
| 06cb:0088 | Synaptics  | Kensington Fingerprint Ke... | 19    |            | 8EA75A2EC0 |
| 03f0:0667 | Hewlett... | WinUSB                       | 18    | usbhid     | 532CB2DFC8 |
| 04b4:5217 | Cypress... | Billboard Device             | 18    | usbhid     | 711E2E3960 |
| 04b8:014a | Seiko E... | Perfection V37/V370          | 18    |            | E9D4B3C500 |
| 06cb:00fc | Synaptics  |                              | 18    |            | 67AB68B5F3 |
| 0819:0101 | eLicenser  | License Management and Co... | 18    |            | 5ACD7C3CBF |
| 1366:0101 | SEGGER     | J-Link PLUS                  | 18    | usbfs      | 6E020F3AD1 |
| 22b8:2e81 | Motorol... | Moto G (5) Plus              | 18    | usbfs      | DBBB8B3026 |
| 04f3:0c3d | Elan Mi... | ELAN:Fingerprint             | 17    |            | 2B4A1A20D9 |
| 0711:5601 | Magic C... | USB Station                  | 17    |            | 80FB4514C5 |
| 1b71:3002 | Fushicai   | USBTV007 Video Grabber [E... | 17    | usbtv      | C3C2BDED72 |
| 2a70:4ee7 | OnePlus... | ONEPLUS A3010 [OnePlus 3T... | 17    | usbfs      | F5EDE0A97C |
| 0451:ace1 | Texas I... | TPS65983B                    | 16    |            | 50385DDE8B |
| 0471:0815 | Philips... | eHome Infrared Receiver      | 16    | mceusb     | F98CCE15A3 |
| 04f3:0c58 | Elan Mi... | ELAN:Fingerprint             | 16    |            | 0540C800C7 |
| 05ac:1460 | Apple      | USB-C Digital AV Multipor... | 16    |            | BB1AA448FD |
| 17e9:4300 | Display... | FM122 CRD                    | 16    | snd_usb... | 8A52B831D7 |
| 1934:5168 | Feature... | F71610A or F71612A Consum... | 16    | mceusb     | 622D9B0AE4 |
| 1e71:3008 | NZXT       | KrakenZ Device               | 16    | usbhid     | 1FCE0AB0E8 |
| 0e8d:201c | MediaTek   | TECNO SPARK 3 Pro            | 15    | usbfs      | 6C9393A9D6 |
| 10a5:9200 | FPC        | Sensor Controller            | 15    |            | F5385D6B10 |
| 1934:0702 | Feature... | Integrated Consumer Infra... | 15    | mceusb     | 6B1CF875FD |
| 1d5c:5100 | Fresco ... | PD3.0 USB-C Device           | 15    |            | 2DBA12AE97 |
| 2109:8883 | VIA Labs   | USB Billboard Device         | 15    |            | 58E3F9C07F |
| 0424:2530 | Microch... | Bridge device                | 14    |            | 3F6DFEBDF6 |
| 045e:02dd | Microsoft  | Xbox One Controller (Firm... | 14    | xpad       | E45FCC146D |
| 04f3:0c11 | Elan Mi... | ELAN:Fingerprint             | 14    | usbfs      | 6F4B47BF70 |
| 187f:0600 | Siano M... | MDTV Receiver                | 14    | smsusb     | 28BAC734C5 |
| 054c:01bb | Sony       | FeliCa S320 [PaSoRi]         | 13    |            | D32BF9DCED |
| 0bda:5450 | Realtek... | BillBoard Device             | 13    |            | 138EC046F1 |
| 0bda:5812 | Realtek... | Realtek USB2.0 Finger Pri... | 13    |            | 00AC329183 |
| 16c0:05dc | Van Ooi... | shared ID for use with li... | 13    |            | E5C076C975 |
| 2717:ff08 | Xiaomi     | Redmi Note 3 (ADB Interface) | 13    | usbfs      | C847E8ACF2 |
| 03f0:484a | Hewlett... | Elite USB-C Dock G4          | 12    | usbhid     | 444E13B5ED |
| 0499:1509 | Yamaha     | Steinberg UR22               | 12    | snd_usb... | 059A88A1CB |
| 0835:2a01 | Action ... | BILLBOARD DEVICE             | 12    |            | A5F10AE10B |
| 0955:0007 | Nvidia     | stereo controller            | 12    |            | 8366A7EDD1 |
| 27c6:609c | Shenzhe... | Goodix USB2.0 MISC           | 12    |            | 04DB6C2222 |
| 298d:2033 | Next Bi... | NB-2033-U                    | 12    |            | 54FB1101F1 |
| 0483:374b | STMicro... | ST-LINK/V2.1                 | 11    | cdc_acm    | 97A8F28916 |
| 04b8:0202 | Seiko E... | Interface Card UB-U05 for... | 11    | usblp      | 7FE3C46D72 |
| 0572:c68a | Conexan... | EyeTV Stick                  | 11    | dvb_usb... | E30173ADF4 |
| 0bda:2172 | Realtek... | BillBoard Device             | 11    |            | 2C2443341F |
| 1fc9:5002 | NXP Sem... | PTN5002 [Startech VGA/DVI... | 11    |            | E30173ADF4 |
| 2040:0265 | Hauppauge  | WinTV-dualHD DVB             | 11    | em28xx     | 4EF6B3F267 |
| 2040:8268 | Hauppauge  | soloHD                       | 11    | em28xx     | 7EC475CDD0 |
| 24c6:543a | ThrustM... | PowerA Wired Controller f... | 11    | xpad       | C424D5C53D |

