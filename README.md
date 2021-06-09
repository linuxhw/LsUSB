Most popular USB devices
========================

This is a project to identify most popular USB devices in modern computers and
share detailed lsusb reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 180960.

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
| 1235:8205 | Focusri... | Scarlett Solo USB            | 33    | snd_usb... | 4E6F30E029 |
| 0955:7002 | Nvidia     | stereo controller            | 28    |            | 024ABE4666 |
| 1235:8202 | Focusri... | Focusrite Scarlett 2i2 2n... | 28    | snd_usb... | 01196F313E |
| 041e:322c | Creativ... | SB Omni Surround 5.1         | 25    | snd_usb... | 72441939BE |
| 1235:8016 | Focusri... | Focusrite Scarlett 2i2       | 25    | snd_usb... | 12CC462C7E |
| 046d:0a87 | Logitech   | G935 Gaming Headset          | 21    | snd_usb... | EBF234C535 |
| 1397:0509 | BEHRING... | UMC404HD 192k                | 21    | snd_usb... | 5AA5DF277A |
| 1397:0507 | BEHRING... | UMC202HD 192k                | 20    | snd_usb... | 8F3FC4EEDA |
| 1043:857c | iCreate... | Xonar U7                     | 19    | usbhid     | A34826BA77 |
| 1235:8211 | Focusri... | Scarlett Solo (3rd Gen.)     | 19    | snd_usb... | C46C37E02C |
| 152a:8750 | Thesyco... | E30                          | 18    | snd_usb... | 9F527DED3C |
| 1397:0508 | BEHRING... | UMC204HD 192k                | 17    | snd_usb... | 04A4129216 |
| 1235:8200 | Focusri... | Scarlett 2i4 USB             | 16    | snd_usb... | F01A365521 |
| 0414:a000 | Giga-By... | USB Audio                    | 15    | snd_usb... | 25CA293EC4 |
| 0414:a001 | Giga-By... | USB Audio                    | 15    | snd_usb... | 25CA293EC4 |
| 0499:170f | Yamaha     | Steinberg UR22mkII           | 14    | snd_usb... | E0277E3530 |
| 0d8c:0004 | C-Media... | CM6631A Audio Processor      | 14    | usbhid     | 59D6BED252 |
| 1235:8210 | Focusri... | Scarlett 2i2 USB             | 14    | snd_usb... | EDEF8DFD8B |
| 0b05:180d | ASUSTek... | STRIX SOUND CARD             | 13    | snd_usb... | 730C09F9E6 |
| 0d8c:0066 | C-Media... | Schiit Modi 3                | 13    | snd_usb... | FA126D0D5F |
| 26ce:0a01 |            | USB Audio                    | 13    | snd_usb... | A770B03DB4 |
| 2972:0047 | FiiO El... | FiiO K5 Pro                  | 13    | snd_usb... | 153BB12A6A |
| 0414:a002 | Giga-By... | USB Audio                    | 12    | snd_usb... | EBF234C535 |
| 17cc:1001 | Native ... | Komplete Audio 6             | 12    | snd_usb... | D2E4A69C16 |
| 046d:0a0b | Logitech   | ClearChat Pro USB            | 11    | snd_usb... | 006B564B4D |
| b58e:0005 | Blue Mi... | Yeti Nano                    | 11    | snd_usb... | C8F8650F7F |
| 0499:170a | Yamaha     | Steinberg UR12               | 10    | snd_usb... | 72C1AB0B9B |
| 20b1:000a | XMOS       | Khadas Tone Control          | 10    | snd_usb... | 2E4383BD79 |
| 0499:1703 | Yamaha     | MG-XU                        | 9     | snd_usb... | 35589DCE0C |
| 0b05:1915 | ASUSTek... | USB Audio                    | 9     | usbhid     | 1F560968AB |
| 0b05:1916 | ASUSTek... | USB Audio                    | 9     | snd_usb... | 1F560968AB |
| 20b1:3008 | XMOS       | iFi (by AMR) HD USB Audio    | 9     | snd_usb... | 7E0EA56C00 |
| 20b1:3023 | XMOS       | X1S USB DAC                  | 9     | snd_usb... | 4C10147742 |
| 0582:012f | Roland     | QUAD-CAPTURE                 | 8     | snd_usb... | 7B77685578 |
| 0b05:180f | ASUSTek... | XONAR SOUND CARD             | 8     | snd_usb... | 00CD4878A3 |
| 0b05:189d | ASUSTek... | Xonar SoundCard              | 8     | snd_usb... | 3453DEC709 |
| 0b05:1918 | ASUSTek... | USB Audio                    | 8     | snd_usb... | F4DA24790D |
| 1235:801c | Focusri... | Scarlett Solo USB            | 8     | snd_usb... | B92F4485E6 |
| 19f7:0015 | RODE Mi... | RODE NT-USB Mini             | 8     | snd_usb... | 65C1600593 |
| 20b1:0008 | XMOS       | Mayfield Audio               | 8     | snd_usb... | EF051B442A |
| 041e:3f02 | Creativ... | E-Mu 0202                    | 7     | snd_usb... | 3F6EBB3247 |
| 0bda:4c07 | Realtek... | TX-Hifi Type_C Audio         | 7     | snd_usb... | F5F34D1237 |
| 1235:800a | Focusri... | Scarlett 2i4                 | 7     | snd_usb... | 6E7B795B09 |
| 1395:009a | Sennhei... | GSP 370                      | 7     | cdc_acm    | ADFDB43F0B |
| 2972:0035 | FiiO El... | FiiO Q1                      | 7     | snd_usb... | 8CA4919B3C |
| 041e:3f19 | Creativ... | E-MU 0204 / USB              | 6     | snd_usb... | B5E15DE718 |
| 0499:1704 | Yamaha     | Steinberg UR44               | 6     | snd_usb... | 3792E516CD |
| 0499:170d | Yamaha     | AG06/AG03                    | 6     | snd_usb... | 9414F40CF2 |
| 0b05:17a8 | ASUSTek... | ASUS Xonar Essence One       | 6     | usbhid     | D59E8583C7 |
| 0b05:183c | ASUSTek... | Xonar U7 MKII                | 6     | snd_usb... | 891913CEEC |
| 22e8:dac4 | Cambrid... | Cambridge AudioDAC100 USB 2  | 6     | snd_usb... | 81212EADBC |
| 0499:170b | Yamaha     | Steinberg UR242              | 5     | snd_usb... | B4B00787C2 |
| 0582:00e6 | Roland     | EDIROL UA-25EX (Advanced ... | 5     | snd_usb... | 8859E15CB5 |
| 07fd:0008 | Mark of... | M Series                     | 5     | snd_usb... | 43CB3AF3A5 |
| 1235:8006 | Focusri... | Focusrite Scarlett 2i2       | 5     | snd_usb... | 53291D247A |
| 041e:3243 | Creativ... | Sound BlasterX G5            | 4     | snd_usb... | 7C519C91CA |
| 041e:3f04 | Creativ... | E-Mu 0404                    | 4     | snd_usb... | 61F0309C59 |
| 04e8:7084 | Samsung... | USB Audio                    | 4     | snd_usb... | 97D8B548F4 |
| 05a7:40fa | Bose       | Revolve SoundLink            | 4     | usbhid     | 3B614F915C |
| 074d:0002 | Micronas   | BLUE USB Audio 2.0           | 4     | snd_usb... | BF37A519FA |
| 0bda:485a | Realtek... | USB Audio                    | 4     | snd_usb... | 368BC3C902 |
| 0d8c:0319 | C-Media... | Schiit Modi Uber             | 4     | usbhid     | 1221B30469 |
| 0db0:0d64 | Micro S... | USB Audio                    | 4     | snd_usb... | 8ADB484D2C |
| 0db0:543d | Micro S... | USB Audio                    | 4     | snd_usb... | 0279EEDBFB |
| 1397:00d4 | BEHRING... | X18/XR18                     | 4     | snd_usb... | FF3BA69D3E |
| 17cc:1330 | Native ... | Traktor Audio 2 MK2          | 4     | snd_usb... | 91BED95D04 |
| 20b1:3066 | XMOS       | D30                          | 4     | snd_usb... | 54F1BB3FAF |
| 22e8:dac2 | Cambrid... | USB Audio 2.0                | 4     | snd_usb... | 5F07D88F75 |
| 30be:0101 | Schiit ... | Schiit Hel                   | 4     | snd_usb... | D283998378 |
| 041e:3f0a | Creativ... | E-MU Tracker Pre / USB       | 3     | snd_usb... | 548AFBB702 |
| 04d2:ff05 | Altec L... | ADA-305 Speakers             | 3     |            | 9DA28A4AEC |
| 0644:8047 | TEAC       | US-16x08                     | 3     | snd_usb... | 197D61DE28 |
| 0763:4009 | M-Audio    | M-Track Plus                 | 3     | snd_usb... | 534EDD42C9 |
| 0bda:492f | Realtek... | TX 384kb Hifi Type_C Audio   | 3     | usbhid     | 32A3812CA0 |
| 1235:8014 | Focusri... | Scarlett 18i8                | 3     | snd_usb... | 84A4C5E5E0 |
| 1235:8204 | Focusri... | Scarlett 18i8 2nd Gen        | 3     | snd_usb... | 433AA65798 |
| 1462:1171 | Micro S... | Xtreme Audio DAC             | 3     | usbhid     | A938950688 |
| 152a:85df | Thesyco... | SABAJ D4 v1.2                | 3     | snd_usb... | F0591914C5 |
| 154e:3005 | D&M Hol... | HD-DAC1                      | 3     | snd_usb... | 9DB6C930C1 |
| 17aa:1046 |            | Realtek USB Audio Rear       | 3     | snd_usb... | 2C58A29C2A |
| 17aa:104d |            | Realtek USB Audio Front      | 3     | snd_usb... | 2C58A29C2A |
| 17cc:1021 | Native ... | Traktor Audio 10             | 3     | snd_usb... | 0DA8004587 |
| 194f:0103 | PreSonu... | AudioBox 1818 VSL            | 3     | snd_usb... | 830633EFF6 |
| 20b1:0002 | XMOS       | USB Audio 2.0                | 3     | snd_usb... | E1E70C62DA |
| 22e8:dac6 | Cambrid... | DacMagicXS 2.0               | 3     | snd_usb... | 0BD951036D |
| 2708:0002 | Audient    | iD14                         | 3     | snd_usb... | 0CEACBCA21 |
| 2772:0230 | Pro-Ject   | Pre Box S2 Digital           | 3     | usbhid     | 62612ABD09 |
| 041e:323c | Creativ... | Sound Blaster E5             | 2     | usbhid     | 7AA5C86F85 |
| 041e:3257 | Creativ... | Sound Blaster K3+            | 2     | snd_usb... | CEF8AA2B69 |
| 0499:1506 | Yamaha     | THR5                         | 2     | snd_usb... | CEBC9E7C7E |
| 0499:172f | Yamaha     | Steinberg UR22C              | 2     | snd_usb... | 1E395F258F |
| 05fc:0032 | Harman     | Notepad-12FX                 | 2     | snd_usb... | 3A66ABABD9 |
| 0644:8030 | TEAC       | US-1800                      | 2     |            | 75C7FE6B69 |
| 0644:8043 | TEAC       | NT-503                       | 2     | snd_usb... | 3A3835D50F |
| 0763:201a | M-Audio    | M-Audio Micro                | 2     |            | 37F36A2183 |
| 0763:400b | M-Audio    | M-Track 2X2                  | 2     | snd_usb... | 7681E991B1 |
| 0b05:17cd | ASUSTek... | Xonar Essence STU            | 2     | snd_usb... | 47D61A08A0 |
| 0b05:17f5 | ASUSTek... | Xonar U5 sound card          | 2     | snd_usb... | AD1DB00B2C |
| 0b05:180c | ASUSTek... | STRIX RAID DLX               | 2     | snd_usb... | 9BC233D847 |
| 0ccd:00c8 | TerraTe... | AUREON XFIRE8.0 HD           | 2     | snd_usb... | CEEE72E420 |

### Bluetooth (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a12:0001 | Cambrid... | Bluetooth Dongle (HCI mode)  | 3431  | btusb      | 0151392F82 |
| 8087:0a2a | Intel      | Bluetooth wireless interface | 3431  | btusb      | 442C1C8B06 |
| 8087:0a2b | Intel      | Bluetooth wireless interface | 3166  | btusb      | EEB5037642 |
| 8087:0aaa | Intel      | Bluetooth 9460/9560 Jeffe... | 3075  | btusb      | 3E4B181CD8 |
| 8087:0029 | Intel      | AX200 Bluetooth              | 2444  | btusb      | 08B1E4C99F |
| 8087:07dc | Intel      | Bluetooth Device             | 2342  | btusb      | 493278D567 |
| 8087:0026 | Intel      | Bluetooth Device             | 1454  | btusb      | F49F22766B |
| 0cf3:3005 | Qualcom... | AR3011 Bluetooth             | 1096  | btusb      | 6B20CF032F |
| 8087:0aa7 | Intel      | Wireless-AC 3168 Bluetooth   | 1018  | btusb      | 5E3023334C |
| 8087:07da | Intel      | Centrino Bluetooth Wirele... | 984   | btusb      | 4B73953633 |
| 0cf3:3004 | Qualcom... | AR3012 Bluetooth 4.0         | 963   | ath3k, ... | EB4F7A5CF5 |
| 04ca:3015 | Lite-On... | Qualcomm Atheros QCA9377 ... | 866   | btusb      | 8C7DAC1018 |
| 8087:0025 | Intel      | Wireless-AC 9260 Bluetoot... | 767   | btusb      | FA126D0D5F |
| 0cf3:e500 | Qualcom... | Qualcomm Atheros Bluetoot... | 740   | btusb      | 63B5D9A81A |
| 0bda:b00a | Realtek... | Realtek Bluetooth 4.2 Ada... | 619   | btusb      | E4CBF06036 |
| 8086:0189 | Intel      | Centrino Advanced-N 6230 ... | 546   | btusb      | FC5E5FB4F1 |
| 0bda:b009 | Realtek... | Realtek Bluetooth 4.2 Ada... | 540   | btusb      | A3594AB925 |
| 0cf3:e009 | Qualcom... | Qualcomm Atheros Bluetoot... | 532   | btusb      | 20665AC634 |
| 0a5c:217f | Broadcom   | BCM2045B (BDC-2.1)           | 473   | btusb      | FA5ABFCCF8 |
| 04ca:300b | Lite-On... | Atheros AR3012 Bluetooth     | 451   | ath3k, ... | 31A46644A6 |
| 0cf3:e300 | Qualcom... | QCA61x4 Bluetooth 4.0        | 435   | btusb      | DEE5936700 |
| 03f0:231d | Hewlett... | Broadcom 2070 Bluetooth C... | 401   | btusb      | D62314D0C2 |
| 03f0:171d | Hewlett... | Bluetooth 2.0 Interface [... | 399   | btusb      | C3E3F15A63 |
| 0cf3:0036 | Qualcom... | AR9462 Bluetooth             | 389   | ath3k, ... | 184390C71D |
| 0a5c:21e8 | Broadcom   | BCM20702A0 Bluetooth 4.0     | 373   | btusb      | BA3E1C4E32 |
| 0cf3:e005 | Qualcom... | Qualcomm Atheros Bluetoot... | 370   | ath3k, ... | BABA8A29AC |
| 0bda:b00b | Realtek... | Realtek Bluetooth 4.2 Ada... | 341   | btusb      | C97186D2ED |
| 0bda:c024 | Realtek... | Bluetooth Radio              | 337   | btusb      | 94CC1922DE |
| 0bda:b728 | Realtek... | RTL8723B Bluetooth           | 332   | btusb      | B1B8196F26 |
| 413c:8187 | Dell       | DW375 Bluetooth Module       | 322   | btusb      | 417833D46E |
| 0a5c:21e6 | Broadcom   | BCM20702 Bluetooth 4.0 [T... | 312   | btusb      | FA237F560A |
| 13d3:3362 | IMC Net... | Atheros AR3012 Bluetooth ... | 309   | ath3k, ... | 278EF790CF |
| 105b:e065 | Foxconn... | BCM43142A0 Bluetooth module  | 307   | btusb      | 02DC78FEDA |
| 0b05:17cb | ASUSTek... | Broadcom BCM20702A0 Bluet... | 301   | btusb      | 73ECE6C322 |
| 0a5c:2101 | Broadcom   | BCM2045 Bluetooth            | 281   | btusb      | AC4F9CD1E4 |
| 04ca:3016 | Lite-On... | Bluetooth Device             | 269   | btusb      | 4B725CA633 |
| 0489:e04e | Foxconn... | Bluetooth Device             | 262   | ath3k, ... | BA274D73F0 |
| 0a5c:219c | Broadcom   | BCM2070 Bluetooth Device     | 261   | btusb      | 4BDFD22FE6 |
| 0cf3:e007 | Qualcom... | Qualcomm Atheros Bluetoot... | 259   | btusb      | 5B65572D25 |
| 0a5c:21b4 | Broadcom   | BCM2070 Bluetooth 2.1 + EDR  | 251   | btusb      | 0245DA9040 |
| 0bda:0821 | Realtek... | RTL8821A Bluetooth           | 238   | btusb      | 52E4F61567 |
| 0bda:b721 | Realtek... | Bluetooth Radio              | 235   | btusb      | DAAD255C87 |
| 0cf3:e004 | Qualcom... | Bluetooth USB Host Contro... | 221   | ath3k, ... | 25EF3FF7A3 |
| 0bda:b008 | Realtek... | Bluetooth Radio              | 211   | btusb      | 7BA1F684FA |
| 13d3:3529 | IMC Net... | Bluetooth Radio              | 205   | btusb      | 6188310C3B |
| 0bda:b023 | Realtek... | RTL8822BE Bluetooth 4.2 A... | 201   | btusb      | 6D45501F90 |
| 05ac:8215 | Apple      | Built-in Bluetooth 2.0+ED... | 198   | btusb      | 940E48E534 |
| 0a5c:216d | Broadcom   | BCM43142A0 Bluetooth 4.0     | 189   | btusb      | E47851B0ED |
| 0a5c:21e1 | Broadcom   | HP Portable SoftSailing      | 185   | btusb      | 558E287068 |
| 13d3:3496 | IMC Net... | Bluetooth Device             | 181   | btusb      | 1772050781 |
| 413c:8197 | Dell       | BCM20702A0 Bluetooth Module  | 181   | btusb      | 70DD19848D |
| 0489:e00f | Foxconn... | Foxconn T77H114 BCM2070 [... | 174   | btusb      | 4C8ACBFF76 |
| 0489:e0a2 | Foxconn... | Bluetooth Device             | 172   | btusb      | 94F04E5543 |
| 04ca:3006 | Lite-On... | Bluetooth Device             | 171   | ath3k, ... | D0F0DA0187 |
| 0bda:b001 | Realtek... | Bluetooth Radio              | 171   | btusb      | C80A118E90 |
| 0bda:b00c | Realtek... | 802.11ac WLAN Adapter        | 170   | btusb      | DE5F0D967B |
| 0cf3:311d | Qualcom... | Bluetooth                    | 164   | ath3k, ... | 0144616BB9 |
| 13d3:3526 | IMC Net... | Bluetooth Radio              | 162   | btusb      | 7D816DAFE7 |
| 0a5c:2145 | Broadcom   | BCM2045B (BDC-2.1) [Bluet... | 161   | btusb      | 90C0FC3F2F |
| 0cf3:e360 | Qualcom... | Qualcomm Atheros Bluetoot... | 161   | btusb      | D1A55D8429 |
| 1358:c123 | Realtek    | Bluetooth Radio              | 153   | btusb      | 0A3C07E3DE |
| 0930:0508 | Toshiba    | Integrated Bluetooth HCI     | 150   | btusb      | 3984B7401D |
| 0bda:b006 | Realtek... | Bluetooth Radio              | 148   | btusb      | 1C8A62B98B |
| 0489:e00d | Foxconn... | Broadcom Bluetooth 2.1 De... | 145   | btusb      | A51ABD79CE |
| 13d3:3423 | IMC Net... | Bluetooth Device             | 145   | ath3k, ... | 9C148A1665 |
| 0bda:c123 | Realtek... | Bluetooth Radio              | 143   | btusb      | 650E1B9BF5 |
| 0a5c:21d7 | Broadcom   | BCM43142 Bluetooth 4.0       | 135   | btusb      | A9F70AAC88 |
| 0b05:1712 | ASUSTek... | BT-183 Bluetooth 2.0+EDR ... | 134   | btusb      | 05D9306FCC |
| 0a5c:21e3 | Broadcom   | HP Portable Valentine        | 133   | btusb      | 20918CCF10 |
| 0bda:8771 | Realtek... | Bluetooth Radio              | 132   | btusb      | 135BE0831A |
| 0b05:1788 | ASUSTek... | BT-270 Bluetooth Adapter     | 131   | btusb      | 29EA6520A1 |
| 05ac:821a | Apple      | Bluetooth Host Controller    | 130   | btusb      | DFDBAE77CF |
| 05ac:8205 | Apple      | Bluetooth HCI                | 124   | btusb      | C480910C6C |
| 413c:8160 | Dell       | Wireless 365 Bluetooth       | 123   | btusb      | FBA9137C3B |
| 05ac:8213 | Apple      | Bluetooth Host Controller    | 122   | btusb      | 9D97894A29 |
| 0b05:1751 | ASUSTek... | BT-253 Bluetooth Adapter     | 121   | btusb      | 9445BDA61C |
| 0489:e036 | Foxconn... | Bluetooth USB Host Contro... | 120   | ath3k, ... | B7EE22588D |
| 1286:204c | Marvell... | Bluetooth and Wireless LA... | 116   | btusb      | 23C6094548 |
| 0bda:b002 | Realtek... | Bluetooth Radio              | 114   | btusb      | 342074C2E1 |
| 148f:1000 | Ralink ... | Motorola BC4 Bluetooth 3.... | 114   | btusb      | B0A9A196DB |
| 0a5c:21f1 | Broadcom   | HP Portable Bumble Bee       | 109   | btusb      | 6B18579FFA |
| 0cf3:e301 | Qualcom... | Qualcomm Atheros Bluetoot... | 109   | btusb      | 31A6F21CCD |
| 13d3:3491 | IMC Net... | Bluetooth Device             | 108   | btusb      | D78CA41229 |
| 0a5c:2110 | Broadcom   | BCM2045B (BDC-2) [Bluetoo... | 105   | btusb      | 7497F56037 |
| 413c:8126 | Dell       | Wireless 355 Bluetooth       | 105   | btusb      | 62B30F282D |
| 05ac:821d | Apple      | Bluetooth USB Host Contro... | 101   | btusb      | 4FB050F895 |
| 0a5c:216c | Broadcom   | BCM43142A0 Bluetooth Device  | 101   | btusb      | 14128860C2 |
| 04ca:2006 | Lite-On... | Broadcom BCM43142A0 Bluet... | 100   | btusb      | 06198ED17C |
| 13d3:3394 | IMC Net... | Bluetooth                    | 99    | btusb      | BA8D4405BE |
| 0489:e078 | Foxconn... | Bluetooth Device             | 98    | ath3k, ... | FA65EBF8C6 |
| 044e:3017 | Alps El... | BCM2046 Bluetooth Device     | 96    | btusb      | AFA509714D |
| 0930:021d | Toshiba    | RT Bluetooth Radio           | 95    | btusb      | 391D22D993 |
| 0bda:8723 | Realtek... | RTL8723A Bluetooth           | 93    | btusb      | 5C17F36C61 |
| 0b05:185c | ASUSTek... | Bluetooth Radio              | 91    | btusb      | CCDE838A37 |
| 413c:8140 | Dell       | Wireless 360 Bluetooth       | 91    | btusb      | C91523855C |
| 04ca:3010 | Lite-On... | Bluetooth Device             | 90    | ath3k, ... | 07BEEE0321 |
| 13d3:3402 | IMC Net... | Bluetooth USB Host Contro... | 90    | ath3k, ... | 475195DCD9 |
| 05ac:828f | Apple      | Bluetooth USB Host Contro... | 89    | btusb      | 57385AC440 |
| 0cf3:3121 | Qualcom... | Qualcomm Atheros Bluetoot... | 87    | ath3k, ... | 1CAE6F65DC |
| 05ac:828d | Apple      | Bluetooth USB Host Contro... | 86    | btusb      | 88DD86FBBC |

### Camera (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:0825 | Logitech   | Webcam C270                  | 845   | snd_usb... | D68ABF1123 |
| 04e8:6860 | Samsung... | Galaxy series, misc. (MTP... | 552   | usbfs      | A580EF9F5C |
| 046d:082d | Logitech   | HD Pro Webcam C920           | 464   | snd_usb... | BA3E1C4E32 |
| 05ac:12a8 | Apple      | iPhone 5/5C/5S/6/SE          | 448   | ipheth     | 166A3F9BB5 |
| 13d3:5a11 | IMC Net... | USB2.0 VGA UVC WebCam        | 436   | uvcvideo   | DA937332F8 |
| 0ac8:3420 | Z-Star ... | Venus USB2.0 Camera          | 354   | uvcvideo   | D770D5673C |
| 13d3:5a01 | IMC Net... | USB2.0 VGA UVC WebCam        | 344   | uvcvideo   | DAAD255C87 |
| 13d3:56a2 | IMC Net... | USB2.0 HD UVC WebCam         | 307   | uvcvideo   | 5A8E01E79D |
| 064e:a103 | Suyin      | Acer/HP Integrated Webcam... | 300   | uvcvideo   | B6E44B21DB |
| 0408:a031 | Quanta     | VGA WebCam                   | 295   | uvcvideo   | 8C7DAC1018 |
| 04f2:b604 | Chicony... | Integrated Camera (1280x7... | 280   | uvcvideo   | 573BCD314D |
| 0c45:6723 | Microdia   | Integrated_Webcam_HD         | 275   | uvcvideo   | 08B1E4C99F |
| 5986:2113 | Acer       | SunplusIT Integrated Camera  | 266   | uvcvideo   | F8EB7B0F52 |
| 1bcf:2c18 | Sunplus... | HD WebCam                    | 264   | uvcvideo   | 52667487D2 |
| 058f:5608 | Alcor M... | USB 2.0 Camera               | 258   | uvcvideo   | 045469EE83 |
| 04f2:b64f | Chicony... | HD User Facing               | 250   | uvcvideo   | 90E861B8CF |
| 5986:0295 | Acer       | Integrated Camera            | 250   | uvcvideo   | 2BA1AA7C62 |
| 0408:a060 | Quanta     | HD Webcam                    | 233   | uvcvideo   | 28AADACD07 |
| 1bcf:2883 | Sunplus... | Asus Webcam                  | 231   | uvcvideo   | 4A44C680DE |
| 046d:081b | Logitech   | Webcam C310                  | 229   | snd_usb... | BABA8A29AC |
| 05ac:8509 | Apple      | FaceTime HD Camera           | 225   | uvcvideo   | 4FB050F895 |
| 0c45:62c0 | Microdia   | Sonix USB 2.0 Camera         | 224   | uvcvideo   | 19783E7AF3 |
| 0c45:6340 | Microdia   | Camera                       | 221   | snd_usb... | 304CE6F1C4 |
| 0402:9665 | ALi        | Gateway Webcam               | 218   | uvcvideo   | E80569AA52 |
| 058f:a014 | Alcor M... | Asus Integrated Webcam       | 210   | uvcvideo   | 90B6F7F3B9 |
| 046d:0826 | Logitech   | HD Webcam C525               | 206   | uvcvideo   | D94C194BA5 |
| 13d3:56b2 | IMC Net... | Integrated Camera            | 205   | uvcvideo   | 27A8094D68 |
| 05ac:8507 | Apple      | Built-in iSight              | 203   | uvcvideo   | 153B049ADE |
| 0408:a061 | Quanta     | HD User Facing               | 200   | uvcvideo   | EBA4267910 |
| 04f2:b52b | Chicony... | USB2.0 VGA UVC WebCam        | 198   | uvcvideo   | DCD714D5FA |
| 13d3:5710 | IMC Net... | UVC VGA Webcam               | 198   | uvcvideo   | CB0F042995 |
| 046d:082b | Logitech   | Webcam C170                  | 194   | snd_usb... | CAEE1EA093 |
| 04f2:b1d6 | Chicony... | CNF9055 Toshiba Webcam       | 193   | uvcvideo   | 39A33D288A |
| 04f2:b230 | Chicony... | Integrated HP HD Webcam      | 191   | uvcvideo   | F9EE7C5367 |
| 13d3:5130 | IMC Net... | Integrated Webcam            | 189   | uvcvideo   | 40F5C93523 |
| 04f2:b47f | Chicony... | VGA Webcam                   | 188   | uvcvideo   | FA65EBF8C6 |
| 0bda:57b5 | Realtek... | USB Camera                   | 184   | uvcvideo   | 40F4002ECB |
| 04f2:b071 | Chicony... | 2.0M UVC Webcam / CNF7129    | 183   | uvcvideo   | 11F1CDC49A |
| 2232:1020 | Silicon... | WebCam SC-0311139N           | 183   | uvcvideo   | 08D0784B54 |
| 04f2:b217 | Chicony... | Lenovo Integrated Camera ... | 179   | uvcvideo   | 066D046333 |
| 05ac:8502 | Apple      | Built-in iSight              | 179   | uvcvideo   | 7E5E7767C0 |
| 04ca:7070 | Lite-On... | Integrated Camera            | 172   | uvcvideo   | 94CC1922DE |
| 045e:0779 | Microsoft  | LifeCam HD-3000              | 168   | snd_usb... | F55F5434E6 |
| 0ac8:c40a | Z-Star ... | A4 TECH USB2.0 PC Camera J   | 168   | uvcvideo   | 59D0D32D9C |
| 04f2:b008 | Chicony... | USB 2.0 Camera               | 167   | uvcvideo   | 3984B7401D |
| 0408:5365 | Quanta     | HP TrueVision HD Camera      | 164   | uvcvideo   | 4F752689ED |
| 13d3:56dd | IMC Net... | USB2.0 HD UVC WebCam         | 160   | uvcvideo   | C98EE08146 |
| 5986:0652 | Acer       | Lenovo EasyCamera            | 159   | uvcvideo   | 779BFC3B47 |
| 0bda:57de | Realtek... | USB2.0 VGA UVC WebCam        | 158   | uvcvideo   | 1772050781 |
| 13d3:5188 | IMC Net... | USB2.0 UVC HD Webcam         | 158   | uvcvideo   | 5B11088438 |
| 04f2:b61e | Chicony... | Integrated Camera            | 152   | uvcvideo   | 6710E0BF1C |
| 064e:a219 | Suyin      | 1.3M WebCam (notebook ema... | 152   | uvcvideo   | FF209E1D5D |
| 0bda:57b3 | Realtek... | Acer 640 x 480 laptop camera | 150   | uvcvideo   | C16C3F3C20 |
| 064e:a101 | Suyin      | Acer CrystalEye Webcam       | 147   | uvcvideo   | A1BE6EEBA3 |
| 2232:1008 | Silicon... | WebCam SCB-1100N             | 147   | uvcvideo   | FC5E5FB4F1 |
| 04f2:b221 | Chicony... | integrated camera            | 146   | uvcvideo   | FA5ABFCCF8 |
| 0c45:671e | Microdia   | Integrated_Webcam_HD         | 146   | uvcvideo   | B81492DB2B |
| 5986:2115 | Acer       | Integrated Camera            | 146   | uvcvideo   | 7CFB53E5F2 |
| 0ac8:3450 | Z-Star ... | Vimicro USB Camera (Altair)  | 144   | uvcvideo   | 29F633706A |
| 0c45:6366 | Microdia   | Webcam Vitade AF             | 142   | snd_usb... | 0298FA0732 |
| 04f2:b40a | Chicony... | USB2.0 HD UVC WebCam         | 141   | uvcvideo   | 06198ED17C |
| 04f2:b469 | Chicony... | HD WebCam                    | 141   | uvcvideo   | 31A46644A6 |
| 04f2:b52d | Chicony... | HP Webcam                    | 141   | uvcvideo   | 2AF2DE3D81 |
| 04f2:b5e0 | Chicony... | VGA WebCam                   | 141   | uvcvideo   | 15DE6A42CC |
| 1210:25f4 | DigiTech   | USB 2.0 PC Camera            | 140   | uvcvideo   | 4BDFD22FE6 |
| 13d3:56a6 | IMC Net... | Integrated Camera            | 140   | uvcvideo   | 63B5D9A81A |
| 2232:1029 | Silicon... | WebCam SC-13HDL11939N        | 138   | uvcvideo   | EB4F7A5CF5 |
| 0bda:565a | Realtek... | Integrated_Webcam_HD         | 135   | uvcvideo   | EC4C7C0192 |
| 04f2:b39a | Chicony... | Integrated Camera            | 134   | uvcvideo   | 4EC9EAAC2F |
| 04f2:b40e | Chicony... | HP Truevision HD camera      | 134   | uvcvideo   | 178DCD7E86 |
| 1bcf:28c1 | Sunplus... | Integrated_Webcam_HD         | 134   | uvcvideo   | 51235B00DB |
| 04f2:b1d8 | Chicony... | 1.3M Webcam                  | 133   | uvcvideo   | 3AF4BD4AEE |
| 04f2:b5c5 | Chicony... | HD WebCam                    | 133   | uvcvideo   | D59D4B6AAC |
| 13d3:5a07 | IMC Net... | VGA UVC WebCam               | 131   | uvcvideo   | 66DC392CC0 |
| 0bda:568a | Realtek... | Integrated Webcam            | 128   | uvcvideo   | 36324023DD |
| 13d3:5702 | IMC Net... | UVC VGA Webcam               | 128   | uvcvideo   | A4A1D08110 |
| 046d:082c | Logitech   | HD Webcam C615               | 126   | uvcvideo   | D283998378 |
| 13d3:5a02 | IMC Net... | EasyCamera                   | 126   | uvcvideo   | C1492EBA42 |
| 05c8:036e | Cheng U... | Webcam                       | 125   | uvcvideo   | C80A118E90 |
| 04f2:b272 | Chicony... | Lenovo EasyCamera            | 123   | uvcvideo   | F16304CA03 |
| 04f2:b374 | Chicony... | HD WebCam                    | 123   | uvcvideo   | BA274D73F0 |
| 05a9:2640 | OmniVis... | OV2640 Webcam                | 122   | uvcvideo   | 355B1336F2 |
| 04f2:b446 | Chicony... | TOSHIBA Web Camera - HD      | 121   | uvcvideo   | A467CAE210 |
| 04f2:b67c | Chicony... | Integrated Camera            | 121   | uvcvideo   | 00119F7BA5 |
| 05c8:021e | Cheng U... | HP Webcam-101                | 121   | uvcvideo   | 0245DA9040 |
| 2232:1080 | Silicon... | Web Camera                   | 121   | uvcvideo   | 6D896A2155 |
| 0bda:5689 | Realtek... | Integrated Webcam            | 120   | uvcvideo   | 7BDEC3EB56 |
| 04f2:b5f7 | Chicony... | HD WebCam                    | 119   | uvcvideo   | FF512AC729 |
| 0c45:64ad | Microdia   | Dell Laptop Integrated We... | 119   | uvcvideo   | 9FC71241E6 |
| 0c45:671d | Microdia   | Integrated_Webcam_HD         | 119   | uvcvideo   | 31A6F21CCD |
| 13d3:5666 | IMC Net... | USB2.0 HD UVC WebCam         | 119   | uvcvideo   | 1A651B0072 |
| 04f2:b044 | Chicony... | Acer CrystalEye Webcam       | 118   | uvcvideo   | F8CF9B2AA2 |
| 046d:085c | Logitech   | C922 Pro Stream Webcam       | 117   | snd_usb... | E8B8B03EBD |
| 058f:b002 | Alcor M... | Acer Integrated Webcam       | 116   | uvcvideo   | B6FA661FDD |
| 17ef:480f | Lenovo     | Integrated Webcam [R5U877]   | 116   | uvcvideo   | 4FF6DAE64C |
| 04f2:b2ea | Chicony... | Integrated Camera [ThinkPad] | 115   | uvcvideo   | FA237F560A |
| 0bda:5728 | Realtek... | Lenovo EasyCamera            | 115   | uvcvideo   | 43D3414168 |
| 0bda:58c2 | Realtek... | Integrated Webcam HD         | 115   | uvcvideo   | F0F4829A9A |
| 0c45:64d0 | Microdia   | Integrated Webcam            | 115   | uvcvideo   | E1FA24C279 |
| 04f2:b483 | Chicony... | USB2.0 VGA UVC WebCam        | 112   | uvcvideo   | 437C3C84E2 |

### Card reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:0129 | Realtek... | RTS5129 Card Reader Contr... | 6742  | rtsx_usb   | 184390C71D |
| 0bda:0139 | Realtek... | RTS5139 Card Reader Contr... | 728   | rtsx_usb   | 475195DCD9 |
| 17ef:a38f | Lenovo     | Billboard Device             | 27    | usbhid     | 94F04E5543 |
| 0aec:3260 | Neodio ... | 7-in-1 Card Reader           | 26    | uas, us... | 819D6E7AD3 |
| 17ef:3075 | Lenovo     | USB Billboard Device         | 23    |            | 3C1D98DCE9 |
| 0c4b:0500 | Reiner ... | cyberJack RFID standard d... | 17    | usbfs      | 8A1C4909D6 |
| 0c4b:0501 | Reiner ... | cyberJack RFID comfort du... | 16    | usbfs      | 7C30C0C3CA |
| 072f:9000 | Advance... | ACR38 AC1038-based Smart ... | 14    | usbfs      | 46855C6116 |
| 0d8c:5200 | C-Media... | Mass Storage Controller(0... | 12    |            | 87456F207B |
| 04b4:521a | Cypress... | USB-I2C Bridge               | 11    |            | 2FFEFBD96C |
| 0cf2:6250 | ENE Tec... | SD card reader (UB6250)      | 11    | ums_ene... | 2B59C324E6 |
| 04b4:5218 | Cypress... | USB-Serial Bridge            | 8     |            | 12CC462C7E |
| 0ca6:0010 | Castles... | EZUSB PC/SC Smart Card Re... | 8     | usbfs      | 839B20476A |
| 0b97:7732 | O2 Micro   | Smart Card Reader            | 7     |            | 16BEFD9DC3 |
| 17ef:3078 | Lenovo     | USB Billboard                | 4     |            | 13078A648E |
| 04e6:e003 | SCM Mic... | SPR532 PinPad SmartCard R... | 3     |            | E035F59C6A |
| 0b0c:003f | Todos AB   | Todos C400 smartcard cont... | 3     |            | 03201EED9F |
| 174f:1105 | Syntek     | SM-MS/Pro-MMC-XD Card Reader | 3     | uvcvideo   | B0B1659E5A |
| 04e6:511a | SCM Mic... | SCR3310-NTTCom USB SmartC... | 2     | usbfs      | A5B2555CC2 |
| 04e6:5810 | SCM Mic... | uTrust 2700 R Smart Card ... | 2     | usbfs      | 57B3B5AF39 |
| 062d:0001 | Taiwan ... | Smart Card Reader            | 2     | usbfs      | DD8F32A8D6 |
| 0bda:0150 | Realtek... | Realtek USB 2.0 Card Reader  | 2     | usb_sto... | 8D867729F0 |
| 11c5:0521 | Inmax      | IMT-0521 Smartcard Reader    | 2     |            | 6DCD3425DF |
| 047b:020b | Silitek    | SK-3105 SmartCard Reader     | 1     | usbhid     | 986AC800BA |
| 04e6:512b | SCM Mic... | SDI011 Contactless Reader    | 1     |            | 3810E77092 |
| 0c45:1018 | Microdia   | Compact Flash storage mem... | 1     |            | 696C2127B6 |
| 1667:001a | GIGA-TMS   | MagStripe Card Reader        | 1     | usbhid     | F40A4B7BAC |
| 2ce3:9563 |            | EMV Smartcard Reader         | 1     |            | 6B0ED71AF5 |

### Cdrom (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0e8d:1887 | MediaTek   | Slim Portable DVD Writer     | 210   | usb_sto... | 07A86D218E |
| 13fd:0840 | Initio     | INIC-1618L SATA              | 153   | usb_sto... | 2696477C0C |
| 0e8d:1806 | MediaTek   | Samsung SE-208 Slim Porta... | 132   | usb_sto... | 0957C928CC |
| 12d1:107e | Huawei ... | File-CD Gadget               | 132   | uas, us... | 73935C874B |
| 1c6b:a223 | Philips... | DVD Writer Slimtype eUAU108  | 98    | usb_sto... | FAE0D4150F |
| 2109:0711 | VIA Labs   | VL711 SATA 6Gb/s bridge      | 92    | uas, us... | 65A21D4A57 |
| 152d:2339 | JMicron... | JM20339 SATA Bridge          | 70    | uas, us... | 3CA0951964 |
| 13fd:1040 | Initio     | INIC-1511L PATA Bridge       | 64    | usb_sto... | 7943FF718E |
| 0e8d:1836 | MediaTek   | Samsung SE-S084 Super Wri... | 53    | usb_sto... | FF54330A37 |
| 152e:2571 | LG (HLDS)  | GP08NU6W DVD-RW              | 45    | uas, us... | CC93252339 |
| 174c:1351 | ASMedia... | DVDRW DA8AESH                | 45    | uas, us... | 0B1A312F87 |
| 152e:1640 | LG (HLDS)  | INIC-1605 SATA Bridge        | 40    | usb_sto... | 00658A23AB |
| 0928:0010 | PLX Tec... | Virtual CDRom                | 38    | uas, us... | 7132BCC66D |
| 152e:2507 | LG (HLDS)  | PL-2507 IDE Controller       | 33    | uas, us... | CC4245844A |
| 046b:ff20 | America... | Virtual CDROM0               | 29    | uas, us... | 8EFAF14886 |
| 0b05:7774 | ASUSTek... | Zenfone GO (ZB500KL) (RND... | 27    | rndis_host | 342F07FA37 |
| 08e4:017a | Pioneer    | BD-RW BDR-XD05               | 23    | usb_sto... | F7C5833C2A |
| 13fd:0940 | Initio     | ASUS SBW-06D2X-U             | 22    | uas, us... | 7CA350189C |
| 2a70:f003 | OnePlus... | Device Driver                | 22    | uas, us... | 204B2A5D7C |
| 2e04:c025 | HMD Global | Nokia 8 (MTP mode)           | 21    | uas, us... | CCC49B1CD4 |
| 0e8d:1956 | MediaTek   | Samsung SE-506 Portable B... | 19    | usb_sto... | 0CD0F0C51F |
| 13fd:2040 | Initio     | Samsung Writemaster exter... | 19    | usb_sto... | 96B81659FD |
| 12d1:1082 | Huawei ... | File-CD Gadget               | 17    | usb_sto... | 1345E7109D |
| 054c:02d5 | Sony       | DVD-RAM UJ-852S              | 16    | uas, us... | F538E64507 |
| 13fd:0842 | TSSTcorp   | CDDVDW SE-S084C              | 16    | usb_sto... | B7EC4606A3 |
| 19d2:1410 | ZTE WCD... | USB SCSI CD-ROM              | 16    | uas, us... | 27CC77A565 |
| 413c:9016 | Dell       | DVD+/-RW DW316               | 14    | usb_sto... | CE3E0081A5 |
| 05ac:1500 | Apple      | SuperDrive [A1379]           | 13    | uas, us... | 90D9BFBFD4 |
| 12d1:107f | Huawei ... | File-CD Gadget               | 13    | uas, us... | 94BC5D25C2 |
| 8564:8000 | Transcend  | TRANSCEND                    | 11    | usb_sto... | F0DF9A9794 |
| 04b7:0100 | Compal ... | DVDRW GUE1N                  | 10    | uas, us... | C66066FF6B |
| 0e8d:1807 | MediaTek   | DVDRAM GP40NB40              | 10    | usb_sto... | 6EB605AE36 |
| 04e8:685b | Samsung... | GT-I9100 Phone [Galaxy S ... | 9     | uas, us... | 9EB611A9DC |
| 054c:0377 | Sony       | DVDRAM GSA-T20L              | 9     | uas, us... | 07CC586801 |
| 13fd:0841 | Initio     | Samsung SE-T084M DVD-RW      | 9     | usb_sto... | 18164956AF |
| 0409:0056 | NEC Com... | CD/DVDW SH-S182M             | 8     | usb_sto... | 9C38185DF8 |
| 05c6:9039 | Qualcomm   | vivo Android Phone           | 8     | usbfs      | D468019E77 |
| 067b:2771 | Prolifi... | BD-RE BE14NU40               | 8     | uas, us... | 48D53DF339 |
| 0930:0c05 | Toshiba    | DVD-RAM UJ-844S              | 8     | usb_sto... | 0C557895BE |
| 0ea0:2272 | Ours Te... | GO! Suite                    | 8     | uas, us... | AB0DF3EC99 |
| 534d:6021 | MacroSi... | VGA Display Adapter          | 8     | usb_sto... | 349F951788 |
| 0411:01dc | BUFFALO    | Ultra-Slim Portable DVD W... | 7     | usb_sto... | 2B91E357CA |
| 05e3:0701 | Genesys... | USB 2.0 IDE Adapter          | 7     | usb_sto... | BCC6EC617C |
| 12d1:107d | Huawei ... | SDM450-MTP _SN:DD5E2781      | 7     | rndis_host | BBD93F8E6D |
| 14dd:0002 | Raritan... | RMM2 VDrive 1                | 7     | usbhid     | 390F15B7F9 |
| 0bb4:0f25 | HTC (Hi... | One M8                       | 6     | uas, us... | AC8EEC8267 |
| 1c6b:d002 | Philips... | ES1                          | 6     | usb_sto... | 3D8C008CA3 |
| 2e04:c026 | HMD Global | Nokia Smartphone             | 6     | uas, us... | C3FC416C61 |
| 054c:03dc | Sony       | DVD RW DRX-S70U              | 5     | uas, us... | 8E54A49F9F |
| 0718:4006 | Imation    | 8x Slim DVD Multi-Format ... | 5     | usb_sto... | 94CDE50175 |
| 12d1:1052 | Huawei ... | MT7-L09 / P7-L10 / Y330-U01  | 5     | uas, us... | B541319A1A |
| 0411:02af | BUFFALO    | BD-RW BDR-209M               | 4     | usb_sto... | F5A10112C1 |
| 0476:059b | AESP       | CDDVDW SN-S083C              | 4     | usb_sto... | B297051783 |
| 05c6:f000 | Qualcomm   | Device Driver                | 4     | uas, us... | 566CC27D41 |
| 0ecd:a100 | Lite-On IT | LDW-411SX DVD/CD Rewritab... | 4     | uas, us... | 12791D4EE3 |
| 1782:5d03 | Spreadt... | File-CD Gadget               | 4     | uas, us... | 0D165C08F9 |
| 17ef:730a | Lenovo     | Ultraslim DVD                | 4     | usb_sto... | 6ED533AD09 |
| 19d2:0504 | ZTE WCD... | File-CD Gadget               | 4     | uas, us... | 9F6FBAF237 |
| 1e91:de2c | Other W... | DRW-22B1LT                   | 4     | usb_sto... | A0D316EB3E |
| 03f0:2027 | Hewlett... | Virtual DVD-ROM              | 3     | usb_sto... | 55A7B7EC76 |
| 0489:c001 | Foxconn... | File-CD Gadget               | 3     | uas, us... | 2DCD0E4E69 |
| 05c6:92fe | Qualcomm   | Disk                         | 3     | uas, us... | D06E1D8C5B |
| 097f:097f | Barun E... | DVDRW DU8AESH                | 3     | uas, us... | 0D914665C3 |
| 0b05:7780 | ASUSTek... | Device CD-ROM                | 3     | usb_sto... | FCC9DABB3D |
| 0fe6:9702 | ICS Advent | Supereal VR DISK             | 3     | uas, us... | F6C392325D |
| 103c:8431 | hp PLDS    | DVDRW DU8AESH                | 3     | uas, us... | 9FDCC0F2AF |
| 17ef:b005 | Lenovo     | /mnt/VM0/smolens             | 3     | uas, us... | 543E694E42 |
| 18a5:0414 | Verbatim   | BD-RW BDR-UD03               | 3     | usb_sto... | F41C784317 |
| 1c6b:d005 | Philips... | EB1                          | 3     | usb_sto... | 7F46CDB7AB |
| 04b3:4012 | IBM        | Composite Device-0           | 2     | uas, us... | C43FD89A0B |
| 059b:0155 | Iomega     | CDW/DVD TS-H492A             | 2     | uas, us... | 3EE5BD924C |
| 059b:0252 | Iomega     | Optical                      | 2     | uas, us... | B0485D3960 |
| 059f:0663 | LaCie      | CD/DVDW SH-S162L             | 2     | uas, us... | E824FDE3F1 |
| 060f:1007 | Joinsoo... | DVDRAM GT60N                 | 2     | usb_sto... | 741A93150F |
| 0789:0197 | Logitec    | DVDRAM GP67N                 | 2     | usb_sto... | 266D78E723 |
| 07ab:fcdf | Freecom... | DVD+/-RW20J5                 | 2     | usb_sto... | 6D0120C876 |
| 08e4:0193 | Pioneer    | DVD-RW DVR-XT11              | 2     | uas, us... | E92ABA1B95 |
| 0930:0c06 | Toshiba    | SuperMultiPA3761             | 2     | usb_sto... | D49249D475 |
| 093b:004a | PLEXTOR    | DVDR PX-L611U                | 2     | uas, us... | E6F737276C |
| 0b05:1797 | ASUSTek... | DVDRAM GU60N                 | 2     | usb_sto... | E2A6782664 |
| 12d1:1078 | Huawei ... | File-CD Gadget               | 2     | uas, us... | 69E46089D9 |
| 13fd:1140 | Initio     | DVD-RAM UJ-875S              | 2     | usb_sto... | B6CCAA4CB3 |
| 1410:6000 | Novatel... | Mass Storage                 | 2     | option,... | 45AEF7A11F |
| 174c:7720 | ASMedia... | BD-RW BDR-212M               | 2     | uas, us... | E46DB68DA5 |
| 17ef:7302 | Lenovo     | USB_DVD_Burner5              | 2     | usb_sto... | A6DCDFAB33 |
| 17ef:7306 | Lenovo     | Slim_USB_Burner              | 2     | usb_sto... | 0974C365AB |
| 19d2:1557 | ZTE WCD... | MTS Mobile Boardband         | 2     | cdc_ether  | 74246DF900 |
| 1c6b:a120 | Philips... | DVD+-RW DX-20A6Q             | 2     | usb_sto... | B157FE7CA5 |
| 2009:7638 | iStorage   | Fingerprint                  | 2     | uas, us... | 910CE6A9D9 |
| 413c:9001 | Dell       | ATA Bridge                   | 2     | uas, us... | 8CEA54AABF |
| a2a6:7825 | HL-DT-ST   | BD-RE WH16NS40               | 2     | usb_sto... | 24515EE809 |
| 03f0:0656 | Hewlett... | DVDRW GUD1N                  | 1     | uas, us... | 354CEB04D4 |
| 03f0:1207 | Hewlett... | DVD Writer 840d              | 1     | uas, us... | DF9CBAA879 |
| 03f0:1807 | Hewlett... | DVD Writer 1040d             | 1     | uas, us... | 02D0E7EF6E |
| 03f0:4207 | Hewlett... | DVD Writer 1270e             | 1     | uas, us... | D4A4C9423A |
| 03f0:4607 | Hewlett... | Virtual CD 4607              | 1     | uas, us... | 785CEEC8FF |
| 03f0:4907 | Hewlett... | DVD Writer 556s              | 1     | uas, us... | 0504CC20A9 |
| 03f0:5907 | Hewlett... | DVD Writer 557s              | 1     | usb_sto... | B91A0B2CB2 |
| 03f0:d707 | Hewlett... | DVD Writer 550r              | 1     | usb_sto... | 0D8910952F |
| 03f0:f907 | Hewlett... | DVD Writer 600y              | 1     | usb_sto... | ED7FB8CBB9 |

### Chipcard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 058f:9540 | Alcor M... | AU9540 Smartcard Reader      | 865   | usbfs      | BBF006F0DF |
| 0a5c:5800 | Broadcom   | BCM5880 Secure Applicatio... | 771   | usbfs      | 8D4563315E |
| 0a5c:5801 | Broadcom   | BCM5880 Secure Applicatio... | 298   | usbfs      | 70DD19848D |
| 0b97:7772 | O2 Micro   | OZ776 CCID Smartcard Reader  | 292   | usbfs      | B2D4A08D24 |
| 147e:2020 | Upek       | TouchChip Fingerprint Cop... | 257   | usbfs      | 1C45DC94EC |
| 17ef:1003 | Lenovo     | Integrated Smart Card Reader | 250   | usbfs      | 61B78FFC77 |
| 0a5c:5832 | Broadcom   | 5880                         | 175   | usbfs      | 5B65572D25 |
| 0a5c:5834 | Broadcom   | 5880                         | 152   | usbfs      | 6BE76778AE |
| 0a5c:5843 | Broadcom   | 58200                        | 150   | usbfs      | F417016CF6 |
| 0a5c:5804 | Broadcom   | BCM5880 Secure Applicatio... | 62    | usbfs      | F53A693225 |
| 0b97:7762 | O2 Micro   | Oz776 SmartCard Reader       | 56    |            | 5B23528D58 |
| 0a5c:5842 | Broadcom   | 58200                        | 55    | usbfs      | 011A257801 |
| 08e6:3437 | Gemalto... | GemPC Twin SmartCard Reader  | 30    | usbfs      | 43A9D38CA0 |
| 0529:0620 | Aladdin... | Token JC                     | 27    | usbfs      | 57EDA985A5 |
| 072f:90cc | Advance... | ACR38 SmartCard Reader       | 25    | usbfs      | 28DDA9B894 |
| 058f:9520 | Alcor M... | Watchdata W 1981             | 24    | usbfs      | 616E5444CA |
| 08e6:34ec | Gemalto... | Compact Smart Card Reader... | 24    | usbfs      | 68610FE700 |
| 0bda:0165 | Realtek... | Smart Card Reader Interface  | 22    | usbfs      | 656E1A976A |
| 04e6:5116 | SCM Mic... | SCR331-LC1 / SCR3310 Smar... | 15    | usbfs      | A0E1E8DA67 |
| 076b:3021 | OmniKey    | CardMan 3121                 | 15    | usbfs      | C1F3F29ED6 |
| 0a5c:5802 | Broadcom   | BCM5880 Secure Applicatio... | 15    | usbfs      | 522D36A07E |
| 1050:0406 | Yubico.com | Yubikey 4/5 U2F+CCID         | 13    | usbfs      | CFA660D1D6 |
| 04f2:1469 | Chicony... | HP Skylab USB Smartcard K... | 10    | usbhid     | A112F2F435 |
| 072f:2200 | Advance... | ACR122U                      | 10    | pn533_usb  | 3B93E825DE |
| 1a44:0001 | VASCO D... | Digipass 905 SmartCard Re... | 10    | usbfs      | 52E2D527CD |
| 20a0:4108 | Clay Logic | Nitrokey Pro                 | 10    | usbhid     | C7F9230C06 |
| 25dd:3111 | BIT4ID     | miniLector EVO               | 10    | usbfs      | 93ACC58EFB |
| 04e6:5119 | SCM Mic... | SCR3340 - ExpressCard54 S... | 9     | usbfs      | 81A0B5F406 |
| 076b:1021 | OmniKey    | CardMan 1021                 | 9     | usbfs      | E1DC5A8EA7 |
| 1050:0111 | Yubico.com | Yubikey NEO(-N) OTP+CCID     | 8     | usbhid     | EA8B53C3DC |
| 0a89:0025 | Aktiv      | Rutoken lite                 | 7     | usbfs      | 3728A3298E |
| 0dc3:1004 | Athena ... | ASEDrive V2C                 | 7     | usbfs      | C1FCE855C8 |
| 24dc:0101 | ARDS       | JaCarta                      | 7     | usbfs      | 4D5E452411 |
| 046a:00a1 | Cherry     | SmartCard Reader Keyboard... | 6     | usbhid     | 4421316918 |
| 04e6:e001 | SCM Mic... | SCR331 SmartCard Reader      | 6     | usbfs      | B5A0F60525 |
| 03f0:164a | Hewlett... | SC Keyboard - Apollo (Lit... | 5     | usbhid     | BB31FB43B4 |
| 04e6:5410 | SCM Mic... | SCR35xx Smart Card Reader    | 5     |            | 3878A93172 |
| 076b:4321 | OmniKey    | CardMan 4321                 | 5     |            | DFC4564C84 |
| 08e6:3438 | Gemalto... | GemPC Key SmartCard Reader   | 5     | usbfs      | 2ADC81FAD9 |
| 0a5c:5805 | Broadcom   | 5880                         | 5     |            | 4C46B3C18D |
| 0a5c:5833 | Broadcom   | 5880                         | 5     |            | 0CBB50CF63 |
| 0c4b:9102 | Reiner ... | cyberJack RFID basis cont... | 5     |            | DECA40F736 |
| 1a44:0870 | VASCO D... | DIGIPASS 870                 | 5     | usbfs      | A011C9B38F |
| 0bf8:1006 | Fujitsu... | SmartCard Reader 2A          | 4     | usbfs      | B04F10E40A |
| 0c4b:0580 | Reiner ... | cyberJack one                | 4     |            | 641E5EEB2A |
| 1059:0017 | Gieseck... | StarSign CUT                 | 4     | usbfs      | 0148616DC8 |
| 20a0:4211 | Clay Logic | Nitrokey Start               | 4     | usbfs      | D180569750 |
| 04e6:5115 | SCM Mic... | SCR335 SmartCard Reader      | 3     | usbfs      | 89AB993C4A |
| 072f:90de | Advance... | Token USB 64K                | 3     | usbfs      | 02F1FBC843 |
| 072f:b100 | Advance... | ACR39U                       | 3     | usbfs      | 32E899AFFD |
| 076b:3031 | OmniKey    | 3x21 Smart Card Reader       | 3     | usbfs      | 8F063FE8F1 |
| 0c4b:0551 | Reiner ... | tanJack USB                  | 3     |            | 5660749E4E |
| 1059:0019 | Gieseck... | StarSign CUT S               | 3     | usbfs      | BCF59E135B |
| 163c:0407 | Watchdata  | USB Key                      | 3     | uas, us... | 7DD454CDEE |
| 046a:0070 | Cherry     | SmartTerminal XX1X           | 2     | usbfs      | 70C81FB2C1 |
| 072f:2224 | Advance... | ACR1281 1S Dual Reader       | 2     | usbfs      | 7EC33920D1 |
| 072f:b000 | Advance... | ACR3901U                     | 2     |            | A44B651190 |
| 076b:3022 | OmniKey    | CardMan 3121 (HID Technol... | 2     | usbfs      | 21C0D0DB9C |
| 076b:5421 | OmniKey    | Smart Card Reader USB        | 2     |            | A72E3CC74F |
| 0ca6:00a0 | Castles... | EZCCID Smart Card Reader     | 2     |            | 3DC7A36CB3 |
| 0d46:3014 | Kobil S... | Smart Token                  | 2     |            | 5F126B3966 |
| 15cf:0019 | Avtor      | SecureToken                  | 2     |            | 196CDBC09E |
| 1fc9:010b | NXP Sem... | PR533                        | 2     |            | 08514D3FB0 |
| 0403:e3b4 | Future ... | Parsec Desktop Reader PR-... | 1     |            | 775160993D |
| 046a:002d | Cherry     | SmartTerminal XX44           | 1     |            | C5B35954B5 |
| 046a:01a2 | Cherry     | Cherry GmbH CHERRY SECURE... | 1     | usbhid     | 663D09FE93 |
| 048d:1365 | Integra... | SmartCard Reader             | 1     |            | DB4B891E15 |
| 04cc:5072 | ST-Eric... | Chipcard Reader              | 1     |            | 65FD9B5315 |
| 04e6:5811 | SCM Mic... | CLOUD 2900 R Smart Card R... | 1     | usbfs      | 31A6F21CCD |
| 04e6:581d | SCM Mic... | SCR3500 C Contact Reader     | 1     | usbfs      | AF129BFCD6 |
| 058f:9522 | Alcor M... | EMV Smartcard Reader         | 1     |            | 713028C9F2 |
| 076b:a022 | OmniKey    | CardMan Smart@Link           | 1     |            | 0138C33179 |
| 0783:0006 | C3PO       | LTC31v2                      | 1     |            | AC8A218E93 |
| 0783:0036 | C3PO       | USB SMART CARD READER        | 1     | usbfs      | 86286FAD9C |
| 0802:0005 | Mako Te... | SZZCS-ZCS80                  | 1     | usbhid     | 6C0FAEA524 |
| 08e6:5504 | Gemalto... | Prox SU USB PC Link Reader   | 1     | usbhid     | 33EE2BD8DB |
| 096e:0505 | Feitian... | FT SCR310                    | 1     | usbfs      | 4039D51671 |
| 096e:0853 | Feitian... | U2F CCID KB                  | 1     | usbfs      | 39F6BEF929 |
| 09c3:0013 | HID Global | USB Reader V3                | 1     | usbfs      | D53C2A8B0E |
| 0bf8:1017 | Fujitsu... | Keyboard KB SCR              | 1     | usbhid     | C6E7AFB3B9 |
| 0bf8:1024 | Fujitsu... | Smartcard Reader D323        | 1     |            | 3BD076E0FA |
| 0c4b:0100 | Reiner ... | cyberJack e-com/pinpad       | 1     | cyberjack  | 841F3BBD4C |
| 0d46:3010 | Kobil S... | KOBIL Class 3 Reader         | 1     |            | CE2E3AD9AE |
| 17ef:6007 | Lenovo     | Smartcard Keyboard           | 1     | usbhid     | 4D4128C3A2 |
| 1c34:91b1 | SpringCard | Two                          | 1     |            | F93D4537CB |
| 20a0:4230 | Clay Logic | Nitrokey HSM                 | 1     |            | DEDECE32F6 |
| 23a0:0004 | BIFIT      | iBank2Key                    | 1     |            | A8A89AC09A |
| 25dd:1101 | BIT4ID     | miniLector-S                 | 1     |            | D40236931F |
| 316d:4c4b | Purism,... | Librem Key                   | 1     | usbfs      | 0C18B37B73 |

### Converter (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0403:7a58 | Future ... | USB <-> Serial Cable         | 14    | usbfs      | 794531A511 |
| 03eb:21fe | Atmel      | AVR309:USB to UART protoc... | 2     | igorplu... | 032A1A34DF |
| 0403:1237 | Future ... | Z397 GUARD Converter         | 2     |            | 5F015278B6 |
| 110a:1110 | Moxa Te... | UPort 1110                   | 2     | ti_usb_... | F815AEE35E |
| 0a12:0042 | Cambrid... | SPI Converter                | 1     |            | E1C0C74CA6 |
| 0c12:0005 | Zeroplus   | PSX Vibration Feedback Co... | 1     | usbhid     | A39C4402B9 |
| 1f6a:15aa | AJA Vid... | AJA Mini-converter           | 1     | cdc_acm    | 31D8634492 |

### Disk (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 058f:6362 | Alcor M... | Flash Card Reader/Writer     | 1755  | uas, us... | 37BE0C0682 |
| 058f:6387 | Alcor M... | Transcend                    | 1738  | uas, us... | F49F22766B |
| 090c:1000 | Silicon... | Silicon-Power8G              | 1729  | uas, us... | 7CCA14C70D |
| 058f:6366 | Alcor M... | Multi Flash Reader           | 1722  | uas, us... | E5A41083D0 |
| 0951:1666 | Kingsto... | DataTraveler 100 G3/G4/SE... | 1398  | uas, us... | B5AA561890 |
| 8564:1000 | Transcend  | JetFlash                     | 1285  | uas, us... | 8BCCE7C02A |
| 0bda:0138 | Realtek... | RTS5138 Card Reader Contr... | 1136  | ums_rea... | FBA9137C3B |
| 0781:5567 | SanDisk    | Cruzer Blade                 | 1109  | uas, us... | 940E48E534 |
| 0bda:0158 | Realtek... | USB 2.0 multicard reader     | 1108  | ums_rea... | 11B9953715 |
| 174c:55aa | ASMedia... | ASM1051E SATA 6Gb/s bridg... | 837   | usb_sto... | D4B005244B |
| 0930:6545 | Toshiba    | Kingston DataTraveler 102... | 672   | uas, us... | 184390C71D |
| 058f:6364 | Alcor M... | AU6477 Card Reader Contro... | 666   | uas, us... | 0F9BAA3F5F |
| 0781:5581 | SanDisk    | Ultra                        | 655   | uas, us... | B5175E38D8 |
| 13fe:4200 | Kingsto... | USB DISK 2.0                 | 504   | uas, us... | DFDBAE77CF |
| 0bda:0151 | Realtek... | Mass Storage Device (Mult... | 486   | uas, us... | FF231665D3 |
| 0781:5583 | SanDisk    | Ultra Fit                    | 485   | uas, us... | 1362660B80 |
| 152d:0578 | JMicron... | JMS578 SATA 6Gb/s            | 444   | uas, us... | 68978259F3 |
| 0930:6544 | Toshiba    | TransMemory-Mini / Kingst... | 416   | uas, us... | BA274D73F0 |
| 0781:5575 | SanDisk    | Cruzer Glide                 | 379   | uas, us... | 60F6603B92 |
| 0951:1665 | Kingsto... | Digital DataTraveler SE9     | 364   | uas, us... | E11F83223C |
| 0bda:0316 | Realtek... | SD/MMC                       | 364   | uas, us... | 97DAED636D |
| 05e3:0749 | Genesys... | MassStorageClass             | 337   | uas, us... | F01A365521 |
| 0781:5591 | SanDisk    | Ultra Flair                  | 337   | uas, us... | B5175E38D8 |
| 152d:2329 | JMicron... | JM20329 SATA Bridge          | 333   | usb_sto... | 68978259F3 |
| 05e3:0745 | Genesys... | Logilink CR0012              | 330   | uas, us... | 6416E75D0F |
| 1005:b113 | Apacer ... | Handy Steno 2.0/HT203        | 327   | uas, us... | 442724EA6A |
| 13fe:4100 | Kingsto... | Silicon-Power16G             | 327   | uas, us... | 4A51B670AC |
| 0bda:0153 | Realtek... | 3-in-1 (SD/SDHC/SDXC) Car... | 326   | ums_rea... | 7BA1F684FA |
| 0781:5571 | SanDisk    | Cruzer Fit                   | 286   | uas, us... | 0B3B288186 |
| 048d:1336 | Integra... | SD/MMC Cardreader            | 280   | uas, us... | FC3B27ABAC |
| abcd:1234 | LogiLink   | UDisk                        | 268   | uas, us... | 1C8A62B98B |
| 152d:2338 | JMicron... | JM20337 Hi-Speed USB to S... | 262   | uas, us... | A9255B2217 |
| 0bda:0111 | Realtek... | RTS5111 Card Reader Contr... | 254   | uas, us... | EB1A429C65 |
| 18a5:0302 | Verbatim   | STORE N GO                   | 254   | uas, us... | D555F722D4 |
| 13fe:4300 | Kingsto... | USB DISK                     | 253   | uas, us... | 666371D8A8 |
| 05ac:8403 | Apple      | Internal Memory Card Reader  | 247   | uas, us... | 940E48E534 |
| ffff:5678 | VendorCo   | Disk 2.0                     | 245   | uas, us... | 08473A1B95 |
| 05e3:0723 | Genesys... | GL827L SD/MMC/MS Flash Ca... | 236   | usb_sto... | D5B8EFA3CA |
| 058f:9360 | Alcor M... | 8-in-1 Media Card Reader     | 234   | uas, us... | C51FA1E450 |
| 0bda:0181 | Realtek... | MS/MS-Pro/HG                 | 224   | uas, us... | 4F331FEC6F |
| 058f:6377 | Alcor M... | AU6375 4-LUN card reader     | 216   | uas, us... | 33BB3C3B9A |
| 0bc2:231a | Seagate    | Expansion                    | 216   | uas        | 62B30F282D |
| 05e3:0751 | Genesys... | microSD Card Reader          | 215   | uas, us... | F0057C8374 |
| 13fe:6300 | Kingsto... | SP Mobile C31                | 211   | uas, us... | 2927765712 |
| 13fe:5500 | Kingsto... | Patriot Memory               | 209   | uas, us... | CCEEAE278F |
| 14cd:168a | Super Top  | Elecom Co., Ltd MR-K013 M... | 197   | uas, us... | 40CF3439DB |
| 14cd:6116 | Super Top  | M6116 SATA Bridge            | 196   | uas, us... | 2AF2DE3D81 |
| 1908:0226 | GEMBIRD    | Mass-Storage                 | 193   | uas, us... | 26947ED7FD |
| 0bda:0177 | Realtek... | USB2.0-CRW                   | 190   | ums_rea... | 002C445B12 |
| 1058:25a2 | Western... | Elements 25A2                | 187   | uas, us... | 0E94F2AD8F |
| 05e3:0716 | Genesys... | USB 2.0 Multislot Card Re... | 181   | uas, us... | 174CF1C7BD |
| 0bda:0328 | Realtek... | SD/MMC CRW                   | 180   | uas, us... | 66769D579A |
| 05ac:8406 | Apple      | SD Card Reader               | 169   | uas, us... | F6F2CF5F89 |
| 174c:5106 | ASMedia... | Transcend StoreJet 25M3      | 165   | uas, us... | 08CC036466 |
| 14cd:1212 | Super Top  | microSD card reader (SY-T18) | 163   | uas, us... | 216D963387 |
| 0951:1643 | Kingsto... | DataTraveler G3              | 155   | uas, us... | E9FC8EB1F1 |
| 12d1:14dc | Huawei ... | E3372 LTE/UMTS/GSM HiLink... | 149   | uas, us... | E0D0239B89 |
| 0781:556b | SanDisk    | Cruzer Edge                  | 146   | uas, us... | 72858B36E6 |
| 0951:1642 | Kingsto... | DT101 G2                     | 145   | uas, us... | 98C6853A46 |
| 0781:5530 | SanDisk    | Cruzer                       | 144   | uas, us... | 4A0A20FD2B |
| 174c:1153 | ASMedia... | ASM1153 SATA 3Gb/s bridge    | 144   | uas, us... | CF083F4B62 |
| 1bcf:0c31 | Sunplus... | SPIF30x Serial-ATA bridge    | 142   | uas, us... | C0E0DE26CB |
| 0480:a202 | Toshiba... | Canvio Basics HDD            | 138   | uas, us... | 5989C34ED4 |
| 0bc2:ab24 | Seagate    | Backup Plus Portable Drive   | 135   | uas        | BE27200090 |
| 13fe:3e00 | Kingsto... | USB DISK 2.0                 | 134   | uas, us... | 004D2C410C |
| 04c5:2028 | Fujitsu    | Virtual CD-Rom               | 126   | uas, us... | 127928C404 |
| 1307:0330 | Transcend  | 63-in-1 Multi-Card Reader... | 126   | uas, us... | 54FCA2179E |
| 0bda:0184 | Realtek... | RTS5182 Card Reader          | 121   | ums_rea... | AF3EBA9CF0 |
| 152d:1561 | JMicron... | JMS561U two ports SATA 6G... | 120   | uas        | 68978259F3 |
| 048d:1234 | Integra... | Mass storage                 | 115   | uas, us... | 45AA9AED0D |
| 0bc2:ab38 | Seagate    | Backup Plus Hub              | 115   | uas        | D5B8EFA3CA |
| 05e3:070e | Genesys... | USB 2.0 Card Reader          | 114   | uas, us... | 08C33E40F0 |
| 14cd:125d | Super Top  | Storage Device               | 114   | uas, us... | 607D6E5E33 |
| 0bc2:2322 | Seagate    | SRD0NF1 Expansion Portabl... | 113   | uas        | FE8CC5A05E |
| 05dc:a81d | Lexar M... | LJDTT16G [JumpDrive 16GB]    | 111   | uas, us... | 13258A5722 |
| 0781:5597 | SanDisk    | Cruzer Glide 3.0             | 110   | uas, us... | 5BA9AAE44B |
| 0080:a001 | Assmann... | Digitus DA-71114 SATA        | 109   | uas        | A82D785D77 |
| 1058:10b8 | Western... | Elements Portable (WDBU6Y... | 109   | uas, us... | F6F2CF5F89 |
| 0424:2228 | Microch... | 9-in-2 Card Reader           | 105   | uas, us... | F239501901 |
| 1058:25e1 | Western... | My Passport 25E1             | 103   | uas, us... | 9E21D06596 |
| 0644:0200 | TEAC       | All-In-One Multi-Card Rea... | 101   | uas, us... | 1D91FD9112 |
| 13fe:3600 | Kingsto... | flash drive (4GB, EMTEC)     | 101   | usb_sto... | 94CC1922DE |
| 04e8:61b6 | Samsung... | M3 Portable Hard Drive       | 100   | uas, us... | 0957C928CC |
| 1307:0165 | Transcend  | 2GB/4GB/8GB Flash Drive      | 100   | uas, us... | 4F82621017 |
| 152d:0567 | JMicron... | JMS567 SATA 6Gb/s bridge     | 100   | uas, us... | 238FAECF47 |
| 0781:5590 | SanDisk    | Ultra                        | 99    | uas, us... | 132ED957BA |
| 0781:558a | SanDisk    | Ultra                        | 98    | uas, us... | 5235448CAF |
| 0bda:0116 | Realtek... | RTS5116 Card Reader Contr... | 98    | uas, us... | 29DBA33D3C |
| 0bc2:331a | Seagate    | Expansion Desk               | 97    | uas, us... | D5B8EFA3CA |
| 1058:1021 | Western... | Elements Desktop (WDBAAU)    | 97    | uas, us... | F0145B568F |
| 1f75:0621 | Innosto... | HDWK105                      | 97    | uas, us... | 8EE390F293 |
| 1f75:0917 | Innosto... | NAND Flash                   | 97    | uas, us... | 38EE95B416 |
| 1058:25e2 | Western... | My Passport (WD40NMZW)       | 96    | uas, us... | 53F89BE1B8 |
| 090c:2000 | Silicon... | USB DISK                     | 95    | uas, us... | 607D6E5E33 |
| 0951:1607 | Kingsto... | DataTraveler 100             | 93    | uas, us... | 3D11EFA233 |
| 0bda:0159 | Realtek... | RTS5159 Card Reader Contr... | 93    | ums_rea... | 327A8383CF |
| 1058:25ee | Western... | My Book 25EE                 | 93    | uas, us... | 3F2F789273 |
| 1058:25a3 | Western... | Elements Desktop (WDBWLG)    | 92    | uas, us... | 4D4959DF32 |
| 0781:5406 | SanDisk    | Cruzer Micro U3              | 91    | uas, us... | A962A76B58 |
| 0781:5572 | SanDisk    | Cruzer Switch                | 90    | uas, us... | B4BED55B15 |

### Dvb card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:2838 | Realtek... | RTL2838 DVB-T                | 175   | dvb_usb... | BA7CCF28B7 |
| 07ca:a309 | AVerMed... | AVerTV DVB-T (A309)          | 28    | dvb_usb... | 14F176409D |
| 0bda:2832 | Realtek... | RTL2832U DVB-T               | 21    | dvb_usb... | 6A8CCD44AA |
| 048d:9135 | Integra... | Zolid Mini DVB-T Stick       | 13    | dvb_usb... | 91EAE01B3A |
| 07ca:1336 | AVerMed... | A336 MiniCard Hybrid DVB-T   | 12    |            | B24FDB7446 |
| 15f4:0131 | HanfTek    | Astrometa DVB-T/T2/C FM &... | 12    | dvb_usb... | 995EF5ECD6 |
| 15a4:9016 | Afatech    | AF9015 DVB-T USB2.0 stick    | 11    | dvb_usb... | 6416E75D0F |
| 1164:1f08 | YUAN Hi... | STK7700D                     | 10    | dvb_usb... | 5A8C885439 |
| 2304:0237 | Pinnacl... | PCTV 73e [DiBcom DiB7000PC]  | 10    | dvb_usb... | A85B460D7A |
| 0572:c688 | Conexan... | Geniatech T230 DVB-T2 TV ... | 9     | dvb_usb... | 659589F1A8 |
| 07ca:a310 | AVerMed... | A310                         | 9     | dvb_usb... | 89FD9BEA1A |
| 1d19:1101 | Dexatek... | DK DVB-T Dongle              | 9     | dvb_usb... | 01E862BAA7 |
| 048d:9005 | Integra... | DVB-T TV Stick               | 8     | dvb_usb... | 0B347A19E2 |
| 2040:7070 | Hauppauge  | Nova-T Stick 3               | 8     | dvb_usb... | 0D964B5339 |
| 07ca:1871 | AVerMed... | TD310 DVB-T/T2/C dongle      | 7     | dvb_usb... | 8C9DD0E965 |
| 0572:0320 | Conexan... | DVBSky T330 DVB-T2/C tuner   | 5     | dvb_usb... | 757746E097 |
| 07ca:0831 | AVerMed... | H831 USB Hybrid DVB-T/T2     | 5     |            | D5A4F195AE |
| 187f:0202 | Siano M... | Nice                         | 5     | smsusb     | F032F846BE |
| 2040:9580 | Hauppauge  | NovaT 500Stick               | 5     | dvb_usb... | E1FFF3ADE4 |
| 07ca:0830 | AVerMed... | H830 USB Hybrid DVB-T        | 4     |            | 79A097BF6F |
| 07ca:1334 | AVerMed... | H334 MiniCard Hybrid DVB-T   | 4     |            | 54E6A4A4F7 |
| 07ca:1835 | AVerMed... | A835B                        | 4     | dvb_usb... | 44857FE932 |
| 07ca:850a | AVerMed... | AverTV Volar Black HD (A850) | 4     | dvb_usb... | 8AB143EC6B |
| 0ccd:0038 | TerraTe... | Cinergy T² DVB-T Receiver   | 4     | dvb_usb... | 7D462F007B |
| 1164:3edc | YUAN Hi... | STK7700D                     | 4     |            | DF82BB0E17 |
| 15a4:1001 | Afatech    | AF9015/AF9035 DVB-T stick    | 4     | dvb_usb... | 5F974C11F5 |
| 04b4:2102 | Cypress... | EZ-USB FX2                   | 3     | dvb_usb... | 40EE943C1C |
| 07ca:a835 | AVerMed... | A835                         | 3     | dvb_usb... | B75E151CA2 |
| 1164:0871 | YUAN Hi... | STK7700D                     | 3     | dvb_usb... | BA7E627A1A |
| 13d3:3282 | IMC Net... | DVB-T + GPS Minicard [RTL... | 3     |            | A3EDD93ADA |
| 1f4d:3000 | G-Tek E... | USB Stick                    | 3     | dvb_usb... | 8EB4D9E6CE |
| 2040:5200 | Hauppauge  | NovaT 500Stick               | 3     | dvb_usb... | EB1F0354F0 |
| 2040:7050 | Hauppauge  | Nova-T Stick                 | 3     | dvb_usb... | EC5B3905FB |
| 0413:6029 | Leadtek... | WinFast DTV Dongle Gold      | 2     | dvb_usb... | 614DBAA6D1 |
| 04ca:f000 | Lite-On... | DVB Card                     | 2     | dvb_usb... | 7225AECEFF |
| 0572:c689 | Conexan... | EyeTV Stick                  | 2     | dvb_usb... | D47493ECAE |
| 07ca:0335 | AVerMed... | H335                         | 2     | dvb_usb... | 0362E43257 |
| 07ca:0810 | AVerMed... | H810 USB Hybrid DVB-T        | 2     |            | B46F2FEE35 |
| 07ca:1335 | AVerMed... | H335C                        | 2     |            | 81D55608B8 |
| 07ca:a373 | AVerMed... | A373                         | 2     |            | 22317B4B49 |
| 07ca:a815 | AVerMed... | AVerTV DVB-T Volar X (A815)  | 2     | dvb_usb... | 0E734F5867 |
| 07ca:a867 | AVerMed... | AVerTV DVB-T (A867)          | 2     | dvb_usb... | 2065A34613 |
| 0ccd:0064 | TerraTe... | DVB Card                     | 2     | dvb_usb... | BA214D2A0B |
| 14f7:0500 | TechniS... | DVB-PC TV Star HD            | 2     | dvb_usb... | C7D09ABC04 |
| 1b80:d393 | Afatech    | DVB-T receiver [RTL2832U]    | 2     | dvb_usb... | 635C1BEC0C |
| 1d19:1102 | Dexatek... | DK mini DVB-T Dongle         | 2     | dvb_usb... | 25564EE13D |
| 2040:1801 | Hauppauge  | Okemo B                      | 2     | smsusb     | FE0ED9DA05 |
| 2040:8400 | Hauppauge  | WinTV Nova-T-500             | 2     | dvb_usb... | EE8DC7DA28 |
| 2304:023a | Pinnacl... | PCTV 801e                    | 2     | dvb_usb... | 3B00238998 |
| 0413:6a04 | Leadtek... | DVB-T 2                      | 1     | dvb_usb... | C5B8862A26 |
| 04b4:861f | Cypress... | Anysee E30 USB 2.0 DVB-T ... | 1     | dvb_usb... | 04469024CA |
| 04ca:f01c | Lite-On... | TT1280DA DVB-T TV Tuner      | 1     |            | 646D7B3BFD |
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
| 1415:0003 | Nam Tai... | SCEH-0036                    | 1     | dvb_usb... | 3F2F789273 |
| 14aa:0221 | WideVie... | WT-220U DVB-T dongle         | 1     | dvb_usb... | 7FA8E3A5E5 |
| 14aa:0226 | WideVie... | Digital TV Receiver          | 1     | dvb_usb... | 7B994D2EC2 |
| 14aa:0301 | WideVie... | AVermedia/Yakumo/Hama/Typ... | 1     | dvb_usb... | 65E73516B5 |
| 1b80:c161 | Afatech    | DVB-T 2                      | 1     |            | 2A8FB37B8C |
| 1b80:e39a | Afatech    | DVB-T395U [af9015]           | 1     |            | 2A8FB37B8C |
| 1b80:e402 | Afatech    | DVB-T 2                      | 1     | dvb_usb... | 1EC9575FA4 |
| 2040:7080 | Hauppauge  | myTV.t                       | 1     | dvb_usb... | A1CC53584D |
| 2040:9950 | Hauppauge  | WinTV Nova-T-500             | 1     | dvb_usb... | 0D964B5339 |
| 2304:022b | Pinnacl... | PCTV 71e [Afatech AF9015]    | 1     | dvb_usb... | B778A6096A |
| 2304:022c | Pinnacl... | PCTV 2000e                   | 1     | dvb_usb... | B2BA637E05 |
| 2304:022e | Pinnacl... | PCTV 320cx                   | 1     | dvb_usb... | 9DA08CE4A5 |
| 2304:0236 | Pinnacl... | PCTV 72e [DiBcom DiB7000PC]  | 1     | dvb_usb... | 5728BD3F53 |
| eb1a:5013 | eMPIA T... | USB 2883 Device              | 1     |            | 5DD14F9164 |

### Fingerprint reader (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 138a:003f | Validit... | VFS495 Fingerprint Reader    | 737   | usbfs      | C97186D2ED |
| 06cb:00bd | Synaptics  | Prometheus MIS Touch Fing... | 553   | usbfs      | BBF006F0DF |
| 138a:0011 | Validit... | VFS5011 Fingerprint Reader   | 428   | usbfs      | F8E58BE450 |
| 147e:2016 | Upek       | Biometric Touchchip/Touch... | 389   | usbfs      | B41310BEF2 |
| 138a:0017 | Validit... | VFS 5011 fingerprint sensor  | 380   | usbfs      | 6B9264BFE9 |
| 06cb:009a | Synaptics  | Metallica MIS Touch Finge... | 324   | usbfs      | BE5BC5605B |
| 138a:0018 | Validit... | Fingerprint scanner          | 305   |            | 20918CCF10 |
| 08ff:2810 | AuthenTec  | AES2810                      | 280   |            | 5254456BAE |
| 138a:003c | Validit... | VFS471 Fingerprint Reader    | 262   | usbfs      | 46588303B9 |
| 138a:003d | Validit... | VFS491                       | 255   | usbfs      | 558E287068 |
| 08ff:2580 | AuthenTec  | AES2501 Fingerprint Sensor   | 250   |            | C3E3F15A63 |
| 06cb:0081 | Synaptics  | Synaptics WBDI               | 244   |            | DEE5936700 |
| 0483:2016 | STMicro... | Fingerprint Reader           | 228   |            | 7497F56037 |
| 1c7a:0570 | LighTun... | EgisTec Touch Fingerprint... | 222   |            | 9D864598E3 |
| 04f3:0903 | Elan Mi... | ELAN:Fingerprint             | 207   | usbfs      | 1A651B0072 |
| 138a:0007 | Validit... | VFS451 Fingerprint Reader    | 197   | usbfs      | 607EA8845B |
| 147e:1002 | Upek       | Biometric Touchchip/Touch... | 174   |            | F02D15E805 |
| 27c6:55b4 | Shenzhe... | Fingerprint Reader           | 170   | usbfs      | F8EB7B0F52 |
| 27c6:533c | Shenzhe... | FingerPrint                  | 169   |            | D9848A2007 |
| 06cb:00b7 | Synaptics  | Synaptics VFS7552 Touch F... | 168   |            | AF16143AD8 |
| 08ff:1600 | AuthenTec  | AES1600                      | 158   |            | 2494100ECB |
| 138a:0050 | Validit... | Swipe Fingerprint Sensor     | 158   |            | 178DCD7E86 |
| 138a:0097 | Validit... | Synaptics WBDI               | 155   | usbfs      | EEB5037642 |
| 06cb:00a2 | Synaptics  | Metallica MOH Touch Finge... | 153   |            | 62C94909C7 |
| 06cb:00be | Synaptics  |                              | 153   |            | A09E2EB4C6 |
| 27c6:55a4 | Shenzhe... | Goodix FingerPrint Device    | 141   |            | 58A64E9B94 |
| 138a:0090 | Validit... | VFS7500 Touch Fingerprint... | 139   | usbfs      | 117372A8FF |
| 138a:00ab | Validit... | Synaptics VFS7552 Touch F... | 138   |            | C3162A0346 |
| 1c7a:0603 | LighTun... | ES603 Swipe Fingerprint S... | 136   |            | 336CC6F919 |
| 06cb:00df | Synaptics  | Synaptics FS7604 Touch Fi... | 117   | usbfs      | 166A3F9BB5 |
| 138a:0005 | Validit... | VFS301 Fingerprint Reader    | 116   |            | 662A781C83 |
| 27c6:5110 | Shenzhe... | Goodix Fingerprint Device    | 115   |            | 0A3C07E3DE |
| 138a:0001 | Validit... | VFS101 Fingerprint Reader    | 103   |            | 94CFDBC88F |
| 06cb:00c9 | Synaptics  |                              | 100   | usbfs      | D63B4A98C3 |
| 1c7a:0801 | LighTun... | Fingerprint Reader           | 88    |            | 62053AE42B |
| 147e:1000 | Upek       | Biometric Touchchip/Touch... | 82    |            | 07AA0B9E2B |
| 06cb:009b | Synaptics  |                              | 81    |            | 453B4A46DC |
| 04f3:0c1a | Elan Mi... | ELAN:Fingerprint             | 67    |            | A8C47AD7F6 |
| 04f3:0c03 | Elan Mi... | ELAN:Fingerprint             | 65    |            | 09499164B9 |
| 138a:0091 | Validit... | VFS7552 Touch Fingerprint... | 63    |            | F788FD5E9D |
| 138a:0010 | Validit... | VFS Fingerprint sensor       | 58    |            | DE3596A9A3 |
| 27c6:538c | Shenzhe... | Fingerprint Reader           | 56    |            | B07A0CF706 |
| 27c6:530c | Shenzhe... | Fingerprint Reader           | 51    |            | D4DCA72327 |
| 08ff:168f | AuthenTec  | AES1660 Fingerprint Sensor   | 50    | usbfs      | 4C8ACBFF76 |
| 147e:1001 | Upek       | TCS5B Fingerprint sensor     | 50    |            | 3E55C8284E |
| 27c6:55a2 | Shenzhe... | Goodix FingerPrint Device    | 49    |            | EFB0B681F0 |
| 06cb:0078 | Synaptics  | WBDI Device                  | 48    |            | A3D9CAE93E |
| 08ff:2550 | AuthenTec  | AES2550 Fingerprint Sensor   | 46    | usbfs      | 9EB48C4B07 |
| 06cb:00a8 | Synaptics  |                              | 41    | usbfs      | 0ECC547A14 |
| 06cb:00bb | Synaptics  |                              | 40    |            | B47C4EF32E |
| 27c6:5117 | Shenzhe... | Fingerprint Reader           | 39    |            | 0D2CFDC2D8 |
| 06cb:00c7 | Synaptics  |                              | 38    |            | 6F1721C390 |
| 08ff:168b | AuthenTec  | Fingerprint Sensor           | 36    |            | 43A653B86D |
| 08ff:2683 | AuthenTec  | Fingerprint Sensor           | 35    |            | 1CB3267B57 |
| 06cb:00e7 | Synaptics  |                              | 33    |            | DEC52D272F |
| 27c6:5584 | Shenzhe... | Fingerprint Reader           | 32    |            | 27A8094D68 |
| 138a:0008 | Validit... | VFS300 Fingerprint Reader    | 26    |            | 841B375C19 |
| 138a:0094 | Validit... | Synaptics WBDI               | 25    |            | A4D6F3CCE4 |
| 138a:0092 | Validit... | Synaptics VFS7552 Touch F... | 24    |            | 51178C1953 |
| 138a:00a6 | Validit... | Synaptics VFS7552 Touch F... | 22    |            | 20665AC634 |
| 06cb:0082 | Synaptics  | Synaptics WBDI Fingerprin... | 19    |            | A48923935D |
| 2808:9338 | Focal-s... | FT9201Fingerprint.           | 15    |            | E9DC8181D8 |
| 04e8:730a | Samsung... | Fingerprint Device           | 14    |            | 641AA732DA |
| 08ff:2665 | AuthenTec  | Fingerprint Sensor           | 10    |            | 12873CCE8E |
| 27c6:5201 | Shenzhe... | Fingerprint Reader           | 10    | cdc_acm    | 74D654A45F |
| 138a:009d | Validit... | Synaptics WBDI               | 7     |            | 847655CB40 |
| 04f3:0c01 | Elan Mi... | ELAN:Fingerprint             | 6     |            | EE3FF1A75D |
| 08ff:1660 | AuthenTec  | AES1660 Fingerprint Sensor   | 6     |            | A0E3328769 |
| 08ff:168a | AuthenTec  | Fingerprint Sensor           | 6     |            | AF785987C5 |
| 045e:00bb | Microsoft  | Fingerprint Reader           | 5     | usbhid     | 4B34114E72 |
| 04e8:730b | Samsung... | Fingerprint Sensor Device... | 5     |            | 662AF5B7D6 |
| 08ff:168c | AuthenTec  | Fingerprint Sensor           | 5     |            | ED52345849 |
| 08ff:2691 | AuthenTec  | Fingerprint Sensor           | 5     |            | 8395F7AEF5 |
| 04e8:7301 | Samsung... | Fingerprint Device           | 4     |            | C2FAFA6C24 |
| 05ba:000a | Digital... | Fingerprint Reader           | 4     | mod_usb... | 6CBCBA7414 |
| 08ff:1686 | AuthenTec  | Fingerprint Sensor           | 4     |            | 3E43593D78 |
| 27c6:5042 | Shenzhe... | Goodix Fingerprint Device    | 4     | cdc_acm    | CE6A0F1035 |
| 06cb:00e9 | Synaptics  | Synaptics FS7604 Touch Fi... | 3     |            | 502CD63C0F |
| 1c7a:0577 | LighTun... | Fingerprint Sensor           | 3     |            | F2D686D743 |
| 04f3:0c10 | Elan Mi... | ELAN:Fingerprint             | 2     |            | 74C0BDD4EB |
| 138a:0093 | Validit... | Synaptics VFS7552 Touch F... | 2     |            | 579E1F3D79 |
| 1491:0020 | Futroni... | FS81 Fingerprint Scanner ... | 2     | usbfs      | F8BF9AFBE7 |
| 413c:3021 | Dell       | MS819 Wired Mouse With Fi... | 2     | usbhid     | 591A0F29B2 |
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
| 1c7a:0571 | LighTun... | EgisTec Touch Fingerprint... | 1     |            | 3BB19F53E9 |
| 27c6:5335 | Shenzhe... | Goodix Fingerprint Device    | 1     | cdc_acm    | D1699D16D0 |
| 2808:6652 | HOLTEK     | FocalTech Fingerprint Device | 1     |            | 63A21F6D55 |

### Floppy (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 059b:0030 | Iomega     | Zip 250 (Ver 1)              | 2     | uas, us... | B68FE62039 |
| 059b:0033 | Iomega     | ZIP 100                      | 2     | uas, us... | F0912110EB |
| 059b:0001 | Iomega     | Zip 100 (Type 1)             | 1     | usb_sto... | A8C6FD947D |
| 059b:0031 | Iomega     | Zip 100 (Type 3)             | 1     | uas, us... | 1ED8284AB4 |
| 059b:0034 | Iomega     | Zip 100 Driver               | 1     | usb_sto... | 506F4A7C1D |
| 13fe:1e20 | Kingsto... | USB DISK Pro                 | 1     | uas, us... | 8902B96F21 |

### Gamepad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:028e | Microsoft  | Xbox360 Controller           | 398   | xpad       | 63985D7619 |
| 046d:c21f | Logitech   | F710 Wireless Gamepad [XI... | 79    | xpad       | 91BA9591F9 |
| 046d:c21d | Logitech   | F310 Gamepad [XInput Mode]   | 75    | xpad       | 1DB1DCBB2C |
| 045e:0291 | Microsoft  | Xbox 360 Wireless Receive... | 60    | xpad       | 995EF5ECD6 |
| 2563:0575 | ShenZhe... | ZD-V+ Wired Gaming Contro... | 33    | usbhid     | FC96347868 |
| 0079:0011 | DragonRise | Gamepad                      | 32    | usbhid     | 729CBF17A4 |
| 0e8f:0003 | GreenAsia  | MaxFire Blaze2               | 23    | usbhid     | E688898ED8 |
| 0810:e501 | Persona... | SNES Gamepad                 | 12    | usbhid     | 73BFADA83A |
| 0079:181c | DragonRise | Controller                   | 9     | usbhid     | DBC571160D |
| 0e6f:0213 | Logic3     | Afterglow Gamepad for Xbo... | 8     | xpad       | E789EA6881 |
| 046d:c21e | Logitech   | F510 Gamepad [XInput Mode]   | 7     | xpad       | 3FD70C5B87 |
| 0e6f:011f | Logic3     | Rock Candy Wired Controll... | 7     | xpad       | E41DA0FB5E |
| 0e6f:0413 | Logic3     | Afterglow AX.1 Gamepad fo... | 6     | xpad       | E404A8F853 |
| 0583:a000 | Padix (... | MaxFire G-08XU Gamepad       | 5     | usbhid     | 1D15B94110 |
| 0e8f:0008 | GreenAsia  | PS Gamepad                   | 5     | usbhid     | 6D7EAF124E |
| 0e8f:0012 | GreenAsia  | Joystick/Gamepad             | 5     | usbhid     | 56A1BC8E09 |
| 046d:c242 | Logitech   | XUSB Gamepad                 | 4     | usbfs      | 333F34E356 |
| 1345:6006 | Sino Li... | Defender Wireless Controller | 4     |            | 1A9077AB60 |
| 145f:01c5 | Trust      | Gamepad                      | 4     | usbhid     | C44FB426DA |
| 0e8f:310d | GreenAsia  | USB Joystick                 | 3     | usbhid     | 4D127F6426 |
| 145f:0231 | Trust      | USB Gamepad                  | 3     | usbhid     | A72E3CC74F |
| 24c6:5b02 | ThrustM... | GPX Controller               | 3     | xpad       | 653E8EDAB3 |
| 7545:1122 | SZ-MYPOWER | PC Gamepad                   | 3     | usbhid     | 5C844EEF2D |
| 050d:0805 | Belkin ... | Nostromo N50 GamePad         | 2     | usbhid     | 285B5B2D08 |
| 0e6f:011e | Logic3     | Rock Candy Gamepad for PS3   | 2     | usbhid     | 82ABA65015 |
| 0e6f:0201 | Logic3     | Pelican PL-3601              | 2     | usbfs      | 8F0C5A3C20 |
| 11c9:55f0 | HJC Game   | GAMEPAD                      | 2     | usbhid     | FE1D48F6CC |
| 146b:5500 | BigBen ... | Usb Gamepad                  | 2     | usbhid     | C9E270C528 |
| 1bad:f016 | Harmoni... | MadCatz GamePad              | 2     | xpad       | 1A37FA7FA6 |
| 1bad:fa01 | Harmoni... | Gamepad                      | 2     | xpad       | 045958C66F |
| 24c6:fafc | Perform... | Afterglow Gamepad for Xbo... | 2     | xpad       | F34C588CFE |
| 7545:0104 | SZ-MYPOWER | DS4 Wired Controller         | 2     | usbhid     | 11EB2546C1 |
| 0079:1855 | DragonRise | PS3/PC WirelessGamePad       | 1     | usbhid     | A76227F148 |
| 040b:6530 | Weltren... | USB 2A8K GamePad             | 1     | usbhid     | 0539EEEEB8 |
| 044f:b326 | ThrustM... | GPX Gamepad                  | 1     | xpad       | 3C19F51786 |
| 045e:0026 | Microsoft  | SideWinder GamePad Pro       | 1     | usbhid     | F8BFAA2C3D |
| 046d:c208 | Logitech   | WingMan Gamepad Extreme      | 1     | usbhid     | 00B0998670 |
| 06d6:0026 | Aashima... | Predator TH 400 Gamepad      | 1     | usbhid     | 3AFB2CB222 |
| 0738:4716 | Mad Catz   | MadCatz GamePad              | 1     | xpad       | DF679E04AA |
| 07b5:0213 | Mega Wo... | Thrustmaster Firestorm Di... | 1     | usbhid     | 70CA2BBB71 |
| 07b5:0312 | Mega Wo... | Gamepad                      | 1     | usbhid     | ADD750665B |
| 0810:0005 | Persona... | USB Gamepad                  | 1     | usbhid     | 3BDBF957FA |
| 0c12:0ef1 | Zeroplus   | P4 Wired GamepadV1.8         | 1     | usbhid     | 7A316C9F35 |
| 0e6f:0133 | Logic3     | Wired Controller             | 1     | xpad       | F402C60DD9 |
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
| 2dc8:6001 | 8BitDo     | SN30/SF30 Pro gamepad        | 1     | usbhid     | 0D567A35C2 |

### Hardware key (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a89:0020 | Aktiv      | Rutoken S                    | 10    | usbfs      | B2FA33FC7E |
| 0a89:0003 | Aktiv      | Guardant Stealth 2           | 9     | usbfs      | 666371D8A8 |
| 0471:485d | Philips... | Senselock SenseIV v2.x       | 4     |            | E4A6E39276 |
| 14a8:0001 | Soft pr... | Soft protection device: U... | 4     |            | C933CA0D6F |

### Hasp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0529:0001 | Aladdin... | HASP copy protection dongle  | 68    | usbfs      | 011928039E |

### Hub (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1d6b:0002 | Linux F... | 2.0 root hub                 | 10... | hub        | 63B5D9A81A |
| 1d6b:0003 | Linux F... | 3.0 root hub                 | 66289 | hub        | 63B5D9A81A |
| 1d6b:0001 | Linux F... | 1.1 root hub                 | 32090 | hub        | BD89F26D7E |
| 8087:0024 | Intel      | Integrated Rate Matching Hub | 17737 | hub        | 6139F5C652 |
| 8087:8000 | Intel      | Integrated Rate Matching Hub | 7195  | hub        | 6416E75D0F |
| 05e3:0608 | Genesys... | Hub                          | 5682  | hub        | 60F7FA9FE7 |
| 8087:8008 | Intel      | Integrated Rate Matching Hub | 4786  | hub        | 6416E75D0F |
| 8087:0020 | Intel      | Integrated Rate Matching Hub | 4234  | hub        | 4BDFD22FE6 |
| 05e3:0610 | Genesys... | 4-port hub                   | 3950  | hub        | 37BE0C0682 |
| 1a40:0101 | Terminu... | Hub                          | 3634  | hub        | B5AA561890 |
| 8087:8001 | Intel      | Hub                          | 2133  | hub        | 493278D567 |
| 0438:7900 | AMD        | Root Hub                     | 2030  | hub        | A9255B2217 |
| 0a5c:4500 | Broadcom   | BCM2046B1 USB 2.0 Hub (pa... | 1714  | hub        | FBA9137C3B |
| 2109:3431 | VIA Labs   | Hub                          | 1532  | hub        | 7CCA14C70D |
| 0bda:5411 | Realtek... | 4-Port USB 2.1 Hub           | 1118  | hub        | 8004D950B6 |
| 0424:2514 | Microch... | USB 2.0 Hub                  | 973   | hub        | 0FD993C4DD |
| 0bda:0411 | Realtek... | 4-Port USB 3.1 Hub           | 861   | hub        | 8004D950B6 |
| 05e3:0612 | Genesys... | Hub                          | 770   | hub        | 6BE76778AE |
| 8087:8009 | Intel      | Hub                          | 769   | hub        | 4552FD3861 |
| 2109:2812 | VIA Labs   | VL812 Hub                    | 759   | hub        | 4BEFD5F360 |
| 2109:2813 | VIA Labs   | VL813 Hub                    | 731   | hub        | B541319A1A |
| 2109:0812 | VIA Labs   | VL812 Hub                    | 587   | hub        | 4BEFD5F360 |
| 2109:0813 | VIA Labs   | VL813 Hub                    | 580   | hub        | B541319A1A |
| 174c:2074 | ASMedia... | ASM1074 High-Speed hub       | 569   | hub        | FA126D0D5F |
| 174c:3074 | ASMedia... | ASM1074 SuperSpeed hub       | 560   | hub        | FA126D0D5F |
| 0409:005a | NEC Com... | HighSpeed Hub                | 516   | hub        | DCAE361982 |
| 05e3:0626 | Genesys... | USB3.1 Hub                   | 511   | hub        | 9712B91F05 |
| 8087:8002 | Intel      | 8 channel internal hub       | 483   | hub        | 53F89BE1B8 |
| 8087:800a | Intel      | Hub                          | 483   | hub        | 53F89BE1B8 |
| 05e3:0606 | Genesys... | USB 2.0 Hub / D-Link DUB-... | 480   | hub        | E4CBF06036 |
| 058f:6254 | Alcor M... | USB Hub                      | 475   | hub        | DCDFADB154 |
| 2109:2817 | VIA Labs   | USB2.0 Hub                   | 471   | hub        | B21D98595A |
| 05e3:0616 | Genesys... | hub                          | 413   | hub        | 99BC345630 |
| 214b:7250 | Huashen... | USB2.0 HUB                   | 411   | hub        | E4CBF06036 |
| 2109:0817 | VIA Labs   | USB3.0 Hub                   | 403   | hub        | B21D98595A |
| 1a40:0201 | Terminu... | FE 2.1 7-port Hub            | 387   | hub        | F1BF9D35EF |
| 05ac:1006 | Apple      | Hub in Aluminum Keyboard     | 378   | hub        | 9712B91F05 |
| 0424:2134 | Microch... | Hub                          | 368   | hub        | 1362660B80 |
| 2109:2811 | VIA Labs   | Hub                          | 351   | hub        | A10433A3CB |
| 0b97:7761 | O2 Micro   | Oz776 1.1 Hub                | 348   | hub        | B2D4A08D24 |
| 05e3:0620 | Genesys... | USB3.2 Hub                   | 346   | hub        | 90AFA2DF5B |
| 0424:5534 | Microch... | Hub                          | 340   | hub        | 1362660B80 |
| 0451:8142 | Texas I... | TUSB8041 4-Port Hub          | 325   | hub        | 4552FD3861 |
| 058f:9254 | Alcor M... | Hub                          | 315   | hub        | 89AE1206BB |
| 0424:2513 | Microch... | 2.0 Hub                      | 292   | hub        | F0B2632BA4 |
| 14cd:8601 | Super Top  | 4-Port hub                   | 286   | hub        | 558E287068 |
| 2109:8110 | VIA Labs   | Hub                          | 265   | hub        | 839B20476A |
| 045b:0209 | Hitachi    | Hub                          | 249   | hub        | 4D4959DF32 |
| 0451:8140 | Texas I... | TUSB8041 4-Port Hub          | 232   | hub        | 4552FD3861 |
| 0a05:7211 | Unknown... | hub                          | 222   | hub        | 13F6FA20F2 |
| 045b:0210 | Hitachi    | Hub                          | 218   | hub        | 4D4959DF32 |
| 8087:07e6 | Intel      | Hub                          | 209   | hub        | 6FFF0F3407 |
| 214b:7000 | Huashen... | 4-port hub [Maxxter ACT-H... | 205   | hub        | 49FF8D705B |
| 2109:0811 | VIA Labs   | Hub                          | 186   | hub        | 0F9BAA3F5F |
| 413c:2513 | Dell       | internal USB Hub of E-Por... | 185   | hub        | 70DD19848D |
| 0557:8021 | ATEN In... | Hub                          | 182   | hub        | 557557B4EB |
| 0557:7000 | ATEN In... | Hub                          | 168   | hub        | 2A05E48525 |
| 0424:2504 | Standar... | USB 2.0 Hub                  | 166   | hub        | 3BD37E342E |
| 0424:2512 | Microch... | USB 2.0 Hub                  | 156   | hub        | 066B825941 |
| 0424:2744 | Microch... | Hub                          | 149   | hub        | B92F4485E6 |
| 413c:1003 | Dell       | Keyboard Hub                 | 147   | hub        | 69F0D916A3 |
| 1a40:0801 | Terminu... | USB 2.0 Hub                  | 138   | hub        | DEE5936700 |
| 05e3:0617 | Genesys... | USB3.0 Hub                   | 136   | hub        | 53F89BE1B8 |
| 05ac:1003 | Apple      | Hub in Pro Keyboard [Mits... | 130   | hub        | 0151392F82 |
| 0424:2734 | Microch... | USB2734                      | 126   | hub        | 63B320D482 |
| 04b4:6560 | Cypress... | CY7C65640 USB-2.0 "TetraHub" | 122   | hub        | E768951284 |
| 0bda:5401 | Realtek... | RTL 8153 USB 3.0 hub with... | 121   | hub        | C4D78E9E43 |
| 0bc2:ab44 | Seagate    | Backup+ Hub                  | 119   | hub        | D5B8EFA3CA |
| 0424:5744 | Microch... | Hub                          | 118   | hub        | B92F4485E6 |
| 0424:2807 | Microch... | Hub                          | 117   | hub        | F9D1627578 |
| 0424:5807 | Microch... | Hub                          | 117   | hub        | F9D1627578 |
| 046d:c223 | Logitech   | G11/G15 Keyboard / USB Hub   | 106   | hub        | 1C0016DC30 |
| 0424:5734 | Microch... | USB5734                      | 103   | hub        | 63B320D482 |
| 05e3:0605 | Genesys... | Hub                          | 103   | hub        | E4CBF06036 |
| 17ef:100a | Lenovo     | ThinkPad Mini Dock Plus S... | 102   | hub        | 1C45DC94EC |
| 0451:8442 | Texas I... | Hub                          | 100   | hub        | F01A365521 |
| 8564:4000 | Transcend  | RDF8                         | 95    | uas, us... | 92D06972E9 |
| 0bda:0401 | Realtek... | USB3.0 Hub                   | 93    | hub        | C4D78E9E43 |
| 0bc2:ab45 | Seagate    | Backup+ Hub                  | 92    | hub        | D5B8EFA3CA |
| 413c:5534 | Dell       | Hub                          | 91    | hub        | 0AA51CD966 |
| 05e3:0607 | Genesys... | Logitech G110 Hub            | 88    | hub        | A2B72216EF |
| 0bda:0413 | Realtek... | Dell dock                    | 87    | hub        | 08B1E4C99F |
| 0bda:0487 | Realtek... | Dell dock                    | 87    | hub        | 08B1E4C99F |
| 0bda:5413 | Realtek... | Dell dock                    | 87    | hub        | 08B1E4C99F |
| 0bda:5487 | Realtek... | Dell dock                    | 87    | hub        | 08B1E4C99F |
| 2109:2815 | VIA Labs   | USB2.0 Hub                   | 84    | hub        | EFB0B681F0 |
| 413c:a005 | Dell       | Internal 2.0 Hub             | 84    | hub        | 5B23528D58 |
| 2109:0810 | VIA Labs   | VL81x Hub                    | 79    | hub        | 31B25815EC |
| 0424:2137 | Microch... | USB2137B                     | 78    | hub        | 1BA665B0B3 |
| 0424:2660 | Microch... | Hub                          | 78    | hub        | 043730AD50 |
| 413c:2134 | Dell       | USB2134                      | 72    | hub        | 1D14E22FBD |
| 2109:0815 | VIA Labs   | USB3.0 Hub                   | 71    | hub        | EFB0B681F0 |
| 0424:2412 | Microch... | Hub                          | 70    | hub        | 637EA140AE |
| 0451:2036 | Texas I... | TUSB2036 Hub                 | 70    | hub        | C0022674FA |
| 413c:1010 | Dell       | USB 2.0 Hub [MTT]            | 67    | hub        | F00C36D8D7 |
| 0bda:5409 | Realtek... | 4-Port USB 2.0 Hub           | 65    | hub        | E7E821C4A7 |
| 0409:0059 | NEC Com... | HighSpeed Hub                | 64    | hub        | C1BF9C169D |
| 0451:8440 | Texas I... | Hub                          | 64    | hub        | F01A365521 |
| 17ef:100f | Lenovo     | ThinkPad Ultra Dock Hub      | 64    | hub        | C685658547 |
| 17ef:1010 | Lenovo     | ThinkPad Ultra Dock Hub      | 64    | hub        | C685658547 |

### Human interface (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 05ac:8242 | Apple      | Built-in IR Receiver         | 839   | usbhid     | 940E48E534 |
| 1770:ff00 | MSI        | steel series rgb keyboard    | 285   | usbhid     | E9EC3BDF25 |
| 0483:91d1 | STMicro... | Sensor Hub                   | 249   | usbhid     | D3455FCB23 |
| 0b05:1872 | ASUSTek... | AURA LED Controller          | 186   | usbhid     | F55A54325F |
| 0079:0006 | DragonRise | PC TWIN SHOCK Gamepad        | 174   | usbhid     | FC5CE69792 |
| 048d:5702 | Integra... | ITE Device                   | 160   | usbhid     | CCEEAE278F |
| 1462:7c37 | Micro S... | MYSTIC LIGHT                 | 144   | usbhid     | 9269E8D802 |
| 0451:82ff | Texas I... |                              | 123   | usbhid     | F01A365521 |
| 1038:1122 | SteelSe... | SteelSeries KLC              | 115   | usbhid     | A9E5BB7556 |
| 26ce:01a2 | ASRock     | LED Controller               | 108   | usbhid     | 7C519C91CA |
| 0424:274c | Microch... | Hub Controller               | 107   | usbhid     | 63B320D482 |
| 1b1c:0c04 | Corsair    | Link Cooling Node            | 87    | usbhid     | FD6A20FF23 |
| 1e71:170e | NZXT       | Kraken X                     | 87    | usbhid     | 3D0DA576B8 |
| 413c:b06e | Dell       | dock                         | 87    | usbhid     | 08B1E4C99F |
| 413c:b06f | Dell       | dock                         | 87    | usbhid     | 08B1E4C99F |
| 054c:0268 | Sony       | Batoh Device / PlayStatio... | 82    | usbhid     | 882DFAFBDF |
| 0665:5161 | Cypress... | USB to Serial                | 77    | usbhid     | C9E4FCB77C |
| 05ac:8240 | Apple      | Built-in IR Receiver         | 73    | usbhid     | C480910C6C |
| 0b05:18a3 | ASUSTek... | AURA MOTHERBOARD             | 72    | usbhid     | A580EF9F5C |
| 0765:5010 | X-Rite     | X-Rite Pantone Color Sensor  | 65    | usbhid     | A0ED307832 |
| 187c:0550 | Alienware  | LED controller               | 63    | usbhid     | 66769D579A |
| 0451:ca01 | Texas I... | USBtoI2C Solution            | 61    | usbhid     | 56B16C9C71 |
| 048d:8350 | Integra... | ITE Device(8350)             | 55    | usbhid     | B1A956F70E |
| 046d:c216 | Logitech   | F310 Gamepad [DirectInput... | 52    | usbhid     | AB0F931A48 |
| 10d5:55a2 | Uni Cla... | 2Port KVMSwitcher            | 51    | usbhid     | 57D1C4DAFA |
| 046d:c215 | Logitech   | Extreme 3D Pro               | 50    | usbhid     | 0A074F7196 |
| 1b1c:0c0b | Corsair    | Lighting Node Pro            | 50    | usbhid     | 51E1E33185 |
| 0b05:1867 | ASUSTek... | AURA Custom Human interface  | 49    | usbhid     | 9A02CBA527 |
| 06c4:c411 | Bizlink... | D6000 Controller             | 48    | usbhid     | F94CED9A41 |
| 046d:c227 | Logitech   | G15 Refresh Keyboard         | 47    | usbhid     | 3E1F5137FD |
| 10d5:55a4 | Uni Cla... | 4 Port KVMSwicther           | 45    | usbhid     | 4EE697B67C |
| 056a:00e6 | Wacom      | TPCE6                        | 43    | usbhid     | FB1DB30A5F |
| 2047:0855 | Texas I... | Invensense Embedded Motio... | 43    | usbhid     | 43A9DC51D9 |
| 043e:9a39 | LG Elec... | USB Controls                 | 42    | usbhid     | 915909A52F |
| 0408:3001 | Quanta     | Optical Touch Screen         | 41    | usbhid     | 312EDCD189 |
| 0810:0001 | Persona... | Dual PSX Adaptor             | 37    | usbhid     | 92E5728D1A |
| 1462:7b85 | Micro S... | PRO CARBON                   | 36    | usbhid     | B8D0E81636 |
| 1e71:2007 | NZXT       | USB Device                   | 36    | usbhid     | D94C194BA5 |
| 046d:c225 | Logitech   | G11/G15 Keyboard / G keys    | 35    | usbhid     | 1C0016DC30 |
| 054c:05c4 | Sony       | DualShock 4 [CUH-ZCT1x]      | 35    | usbhid     | A80686767D |
| 1462:7c91 | Micro S... | MYSTIC LIGHT                 | 34    | usbhid     | C4A7A4682B |
| 05ac:1392 | Apple      | Apple Watch charger          | 33    | usbhid     | 7E5E7767C0 |
| 1b1c:0c10 | Corsair    | Commander PRO                | 33    | usbhid     | 895D614BA3 |
| 044f:b10a | ThrustM... | T.16000M Joystick            | 32    | usbhid     | EF45C7F25A |
| 1462:7c35 | Micro S... | MYSTIC LIGHT                 | 32    | usbhid     | A4D2088CC9 |
| 10d5:000d | Uni Cla... | SP02-A1                      | 30    | usbhid     | 818BB34EAE |
| 1462:7c84 | Micro S... | MYSTIC LIGHT                 | 30    | usbhid     | A750453BA5 |
| 1e71:2006 | NZXT       | USB Device                   | 29    | usbhid     | 44A240B27D |
| 048d:8386 | Integra... | ITE Device(8386)             | 28    | usbhid     | 649E6FB788 |
| 05a7:40fe | Bose       | SoundLink Mini II            | 27    | usbhid     | 38C505F6BD |
| 1038:1290 | SteelSe... | Arctis Pro Wireless          | 26    | usbhid     | 31E45B375E |
| 1e71:1714 | NZXT       | Smart Device                 | 26    | usbhid     | E18D5BC827 |
| 1b1c:0c1a | Corsair    | Lighting Node CORE           | 25    | usbhid     | EE0630B07C |
| 2687:fb01 | Fitbit     | Base Station                 | 25    | usbhid     | FC3B27ABAC |
| 046d:c222 | Logitech   | G15 Keyboard / LCD           | 24    | usbhid     | 09B0FBCF47 |
| 1050:0120 | Yubico.com | Yubikey Touch U2F Securit... | 23    | usbhid     | 25CA293EC4 |
| 17ef:3066 | Lenovo     | ThinkPad Thunderbolt 3 Do... | 23    | usbhid     | 988050AAA4 |
| 28de:2300 | Valve S... | Index HMD                    | 22    | usbhid     | 1CDF133D3B |
| 056a:5193 | Wacom      | Pen and multitouch sensor    | 21    | usbhid     | 8FA5616036 |
| 2101:1407 | ActionStar | USB KVM                      | 21    | usbhid     | FB1E012F68 |
| 045e:0904 | Microsoft  | Surface Dock Extender        | 20    | usbhid     | 3672EF87DE |
| 147a:e00d | Formosa... | IR Receiver                  | 20    | usbhid     | 58C95200B2 |
| 187c:0530 | Alienware  | AW1517                       | 20    | usbhid     | CC69851E7F |
| 1b1c:0c17 | Corsair    | H115i Platinum               | 20    | usbhid     | 34660A208D |
| 046d:c214 | Logitech   | ATK3 (Attack III Joystick)   | 19    | usbhid     | 421B4C4B06 |
| 1462:7c94 | Micro S... | MYSTIC LIGHT                 | 19    | usbhid     | 9747AB9C9C |
| 1b1c:1b65 | Corsair    | HARPOON RGB WIRELESS Gami... | 19    | usbhid     | D811152E10 |
| 0001:0000 | Fry's E... | MEC0002                      | 18    | usbhid     | 514FF6F90A |
| 03eb:8209 | Atmel      | maXTouch Digitizer           | 18    | usbhid     | BA2B6488C2 |
| 03eb:8417 | Atmel      | maXTouch Digitizer           | 18    | usbhid     | CC089D4DDB |
| 046d:c218 | Logitech   | F510 Gamepad [DirectInput... | 18    | usbhid     | 3F7CBCEA74 |
| 046d:c21c | Logitech   | G13 Advanced Gameboard       | 18    | usbhid     | BE4B7E8CD3 |
| 1462:3fa4 | Micro S... | MSI Gaming Controller        | 18    | usbhid     | C42F475A67 |
| 1462:7b93 | Micro S... | MYSTIC LIGHT                 | 18    | usbhid     | ACD068603B |
| 1462:7c75 | Micro S... | MYSTIC LIGHT                 | 18    | usbhid     | 654C105561 |
| 1462:7c95 | Micro S... | MYSTIC LIGHT                 | 18    | usbhid     | 59F94E4DB6 |
| 187c:0520 | Alienware  | M17x                         | 18    | usbhid     | D3DA4EF72C |
| 1b1c:0c18 | Corsair    | H100i Platinum               | 18    | usbhid     | 7D180179C9 |
| 1b1c:1c0b | Corsair    | RM750i Power Supply          | 18    | usbhid     | 43BC2EF593 |
| 28de:2101 | Valve S... | Watchman Dongle              | 18    | usbhid     | 1DA5ED3876 |
| 044f:b108 | ThrustM... | T-Flight Hotas X Flight S... | 17    | usbhid     | 33BB3C3B9A |
| 046d:c219 | Logitech   | F710 Gamepad [DirectInput... | 17    | usbhid     | 493EDC40C4 |
| 06c4:c412 | Bizlink... | DELL DA300                   | 17    | usbhid     | 9CDE952049 |
| 1462:7c56 | Micro S... | MYSTIC LIGHT                 | 17    | usbhid     | 3067A6E57B |
| 8087:0a04 | Intel      | Sensor Solution              | 17    | usbhid     | AB871DCBE2 |
| 04d8:0b2a | Microch... | U2717D_0B2A_15091601         | 16    | usbhid     | EF3422DD2D |
| 057e:0337 | Nintendo   | Wii U GameCube Controller... | 16    | usbhid     | 01196F313E |
| 1b1c:1c06 | Corsair    | Corsair HX-Series C-Link ... | 16    | usbhid     | 99BC345630 |
| 1b1c:1c0a | Corsair    | Corsair RM650i C-Link Ada... | 16    | usbhid     | D5F17BF23F |
| 2563:0523 | ShenZhe... | BM0523 WirelessGamepad       | 16    | usbhid     | 6C53335E2A |
| 0765:5001 | X-Rite     | Huey PRO Colorimeter         | 15    | usbhid     | 29BCDE9934 |
| 1770:ef35 | MSI        | ASUS OSD                     | 15    | usbhid     | 32805E80B1 |
| 0416:5020 | Winbond... | HID Transfer                 | 14    | usbhid     | 43FDBFBC89 |
| 056a:0357 | Wacom      | PTH-660 [Intuos Pro (M)]     | 14    | usbhid     | 1C040E75DD |
| 056d:0002 | EIZO       | HID Monitor Controls         | 14    | usbhid     | 7D916FB4BD |
| 0810:0003 | Persona... | PlayStation Gamepad          | 14    | usbhid     | E0DC32FB35 |
| 0bb4:2c87 | HTC (Hi... | Vive                         | 14    | uvcvideo   | F60AC6188B |
| 187c:0524 | Alienware  | M17x                         | 14    | usbhid     | 024ABE4666 |
| 1b1c:1c07 | Corsair    | HX1000i Power Supply         | 14    | usbhid     | 6E60025AC5 |
| 1b96:0006 | N-Trig     | DuoSense                     | 14    | usbhid     | 70DD19848D |

### Infrared (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 066f:4200 | SigmaTel   | STIr4200 IrDA Bridge         | 7     | stir4200   | A519C7C3B0 |
| 0609:031d | SMK Man... | eHome Infrared Receiver      | 6     | mceusb     | 264E35C172 |
| 1509:9242 | FIC        | eHome Infrared Transceiver   | 4     | mceusb     | 4A92B26339 |
| 147a:e017 | Formosa... | eHome Infrared Receiver      | 3     | mceusb     | D78CA9AB47 |

### Input/keyboard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:c52b | Logitech   | Unifying Receiver            | 8264  | usbhid     | C97186D2ED |
| 046d:c534 | Logitech   | Unifying Receiver            | 4470  | usbhid     | 4BDFD22FE6 |
| 046d:c31c | Logitech   | Keyboard K120                | 2032  | usbhid     | 6416E75D0F |
| 1c4f:0002 | SiGma M... | Keyboard TRACER Gamma Ivory  | 1871  | usbhid     | 1FE01A8A37 |
| 062a:4101 | MosArt ... | Wireless Keyboard/Mouse      | 1765  | usbhid     | 8004D950B6 |
| 045e:0745 | Microsoft  | Nano Transceiver v1.0 for... | 1236  | usbhid     | 607D6E5E33 |
| 09da:9090 | A4Tech     | XL-730K / XL-750BK / XL-7... | 829   | usbhid     | D145EB6F7C |
| 04d9:1702 | Holtek ... | Keyboard LKS02               | 816   | usbhid     | 066D046333 |
| 09da:054f | A4Tech     | USB Device                   | 812   | usbhid     | 2229C9E9F6 |
| 1a2c:2124 | China R... | USB Keyboard                 | 732   | usbhid     | 75B4FE35CF |
| 1a2c:2d23 | China R... | Keyboard                     | 693   | usbhid     | EC7174828A |
| 04f3:0103 | Elan Mi... | ActiveJet K-2024 Multimed... | 654   | usbhid     | 37BE0C0682 |
| 413c:2113 | Dell       | KB216 Wired Keyboard         | 597   | usbhid     | 2DECA4D871 |
| 413c:2003 | Dell       | Keyboard                     | 573   | usbhid     | 3BD37E342E |
| 046d:c52e | Logitech   | MK260 Wireless Combo Rece... | 566   | usbhid     | F5DD3C3494 |
| 413c:2107 | Dell       | USB Entry Keyboard           | 559   | usbhid     | 0AA51CD966 |
| 1c4f:0026 | SiGma M... | Keyboard                     | 515   | usbhid     | 73ECE6C322 |
| 0461:0010 | Primax ... | HP PR1101U / Primax PMX-K... | 468   | usbhid     | 89AE1206BB |
| 04d9:1603 | Holtek ... | Keyboard                     | 428   | usbhid     | 9C1343DD9B |
| 045e:07b2 | Microsoft  | 2.4GHz Transceiver v8.0 u... | 408   | usbhid     | 90C0FC3F2F |
| 1a2c:0e24 | China R... | USB Keyboard                 | 402   | usbhid     | 204B2A5D7C |
| 048d:8297 | Integra... | IT8297 RGB LED Controller    | 374   | usbhid     | 9E21D06596 |
| 1a2c:2c27 | China R... | USB Keyboard                 | 372   | usbhid     | 29F633706A |
| 03f0:0024 | Hewlett... | KU-0316 Keyboard             | 370   | usbhid     | 6BCBD544EE |
| 046d:c517 | Logitech   | LX710 Cordless Desktop Laser | 345   | usbhid     | 6B68CEB0B3 |
| 04d9:1503 | Holtek ... | Keyboard                     | 341   | usbhid     | 14F43DC84D |
| 0c45:7603 | Microdia   | USB Keyboard                 | 338   | usbhid     | 9747AB9C9C |
| 258a:0001 | SINO WE... | USB KEYBOARD                 | 331   | usbhid     | B38568681E |
| 046d:c539 | Logitech   | USB Receiver                 | 290   | usbhid     | 428CB5BB99 |
| 045e:07f8 | Microsoft  | Wired Keyboard 600 (model... | 288   | usbhid     | B513F2FC77 |
| 045e:07fd | Microsoft  | Nano Transceiver 1.1         | 281   | usbhid     | 391D22D993 |
| 0518:0001 | EzKEY      | USB to PS2 Adaptor v1.09     | 281   | usbhid     | B20E379702 |
| 045e:00db | Microsoft  | Natural Ergonomic Keyboar... | 280   | usbhid     | 557557B4EB |
| 1a2c:4c5e | China R... | USB Keyboard                 | 274   | usbhid     | 995EF5ECD6 |
| 04b3:3025 | IBM        | NetVista Full Width Keyboard | 269   | usbhid     | 4BE451AB41 |
| 062a:5918 | MosArt ... | 2.4G Keyboard Mouse          | 266   | usbhid     | 3EC48C5388 |
| 062a:4c01 | MosArt ... | 2.4G Keyboard Mouse          | 265   | usbhid     | 1CAE6F65DC |
| 24ae:2000 | RAPOO      | 2.4G Wireless Device         | 257   | usbhid     | 0F80210C56 |
| 1050:0407 | Yubico.com | Yubikey 4 OTP+U2F+CCID       | 247   | usbhid     | EE0630B07C |
| 1a2c:0c21 | China R... | USB Keyboard                 | 247   | usbhid     | 11B7EB9F82 |
| 258a:1006 | Gaming KB  | Gaming KB                    | 246   | usbhid     | CE4078A2FB |
| 045e:0750 | Microsoft  | Wired Keyboard 600           | 240   | usbhid     | E4CBF06036 |
| 0a5c:4502 | Broadcom   | Keyboard (Boot Interface ... | 237   | usbhid     | 62B30F282D |
| 046d:c31d | Logitech   | Media Keyboard K200          | 236   | usbhid     | 23FBF90204 |
| 28de:1142 | Valve S... | Wireless Steam Controller    | 224   | usbhid     | 62612ABD09 |
| 046d:c312 | Logitech   | DeLuxe 250 Keyboard          | 221   | usbhid     | C8F0FCF24B |
| 046a:0023 | Cherry     | Keyboard                     | 219   | usbhid     | CCDE838A37 |
| 1ea7:0066 | SHARKOO... | [Mediatrack Edge Mini Key... | 214   | usbhid     | E768951284 |
| 0458:6001 | KYE Sys... | GF3000F Ethernet Adapter     | 213   | usbhid     | A3594AB925 |
| 046d:c328 | Logitech   | Corded Keyboard K280e        | 212   | usbhid     | 81FEE2B563 |
| 09da:0260 | A4Tech     | KV-300H Isolation Keyboard   | 202   | usbhid     | 4D5F23E6BA |
| 046d:c318 | Logitech   | Illuminated Keyboard         | 201   | usbhid     | BA3E1C4E32 |
| 413c:8161 | Dell       | Integrated Keyboard          | 201   | usbhid     | FBA9137C3B |
| 1a2c:0c23 | China R... | USB Keyboard                 | 195   | usbhid     | AAB06F55BD |
| 0e6a:02c0 | Megawin... | Defender Gaming Keyboard     | 193   | usbhid     | 5DBE42CF75 |
| 2516:0051 | Cooler ... | AMD SR4 lamplight Control    | 186   | usbhid     | 587E4453B3 |
| 25a7:fa61 | Areson ... | Elecom Co., Ltd MR-K013 M... | 186   | usbhid     | 5E58B5909B |
| 413c:2106 | Dell       | QuietKey Keyboard            | 186   | usbhid     | 39FD78A563 |
| 04f2:0833 | Chicony... | KU-0833 Keyboard             | 177   | usbhid     | F5747F7378 |
| 1d57:fa20 | Xenta      | 2.4GHz Wireless Reciever ... | 174   | usbhid     | 4D1F768F1A |
| 045e:07a5 | Microsoft  | Wireless Receiver 1461C      | 167   | usbhid     | 53F89BE1B8 |
| 2a7a:9a18 | CASUE      | USB Keyboard                 | 164   | usbhid     | 053480926C |
| 05ac:024f | Apple      | Keychron K8                  | 163   | usbhid     | DE3596A9A3 |
| 0b05:1866 | ASUSTek... | N-KEY Device                 | 161   | usbhid     | 4BEFD5F360 |
| 413c:2105 | Dell       | Model L100 Keyboard          | 161   | usbhid     | 9EC2685F9D |
| 046b:ff10 | America... | Virtual Keyboard and Mouse   | 159   | usbhid     | ACA2A2FFDF |
| 0e8f:0022 | GreenAsia  | multimedia keyboard contr... | 158   | usbhid     | 9494E60693 |
| 062a:3286 | MosArt ... | Nano Receiver [Sandstrom ... | 156   | usbhid     | 6853A4CB43 |
| 03f0:034a | Hewlett... | Elite Keyboard               | 155   | usbhid     | 9CFDD32388 |
| 048d:c100 | Integra... | ITE Device(8910)             | 153   | usbhid     | 9194ADF3ED |
| 062a:0201 | MosArt ... | Defender Office Keyboard ... | 151   | usbhid     | D145EB6F7C |
| 17ef:602d | Lenovo     | Black Silk USB Keyboard      | 150   | usbhid     | 11B9953715 |
| 3938:1032 | MOSART ... | 2.4G RF Keyboard & Mouse     | 150   | usbhid     | B541319A1A |
| 413c:2010 | Dell       | Keyboard                     | 148   | usbhid     | BD81547CF5 |
| 046d:c315 | Logitech   | Classic Keyboard 200         | 147   | usbhid     | 90A9EE81F6 |
| 2717:ff40 | Xiaomi     | Mi/Redmi series (MTP)        | 145   | usbfs      | E2D1740F3A |
| 413c:2005 | Dell       | RT7D50 Keyboard              | 145   | usbhid     | D72C25E601 |
| 1d57:fa60 | Xenta      | 2.4G Receiver                | 143   | usbhid     | E4CBF06036 |
| 0603:00f2 | Novatek... | Keyboard (Labtec Ultra Fl... | 142   | usbhid     | EE57980B90 |
| 0e8f:00a7 | GreenAsia  | 2.4G RX                      | 142   | usbhid     | D0705EF193 |
| 413c:8505 | Dell       | Universal Receiver           | 142   | usbhid     | 7130277153 |
| 045e:00dd | Microsoft  | Comfort Curve Keyboard 20... | 139   | usbhid     | 95642C55FC |
| 045e:0800 | Microsoft  | Wireless keyboard (All-in... | 137   | usbhid     | D68ABF1123 |
| 03f0:a407 | Hewlett... | Wireless Optical Comfort ... | 136   | usbhid     | F692FA205D |
| 1a81:1004 | Holtek ... | Wireless Dongle 2.4 GHZ H... | 135   | usbhid     | 25ABEEE3EF |
| 046d:c33a | Logitech   | G413 Gaming Keyboard         | 134   | usbhid     | 32B9A694B3 |
| 0557:2419 | ATEN In... | Keyboard                     | 134   | usbhid     | 2A05E48525 |
| 09da:9066 | A4Tech     | F3 V-Track Gaming Mouse      | 132   | usbhid     | D721904B6E |
| 1a2c:4094 | China R... | USB Keyboard                 | 130   | usbhid     | F55A54325F |
| 24ae:2010 | Shenzhe... | 2.4G Wireless Device         | 130   | usbhid     | EC7F85C26E |
| 1b1c:1b3d | Corsair    | Corsair Corsair Gaming K5... | 128   | usbhid     | 62A56EC749 |
| 248a:8566 | Maxxter    | Wireless Receiver            | 128   | usbhid     | F12C26F48D |
| 0b38:0010 | Gear Head  | 107-Key Keyboard             | 125   | usbhid     | A42B9E9B4C |
| 046a:0011 | Cherry     | G83 (RS 6000) Keyboard       | 124   | usbhid     | 973E323F3C |
| 1997:2433 | Shenzhe... | wireless mini keyboard wi... | 124   | usbhid     | B5A6752EE2 |
| 17ef:608c | Lenovo     | Calliope USB Keyboard        | 123   | usbhid     | F0691E6EDA |
| 05ac:0221 | Apple      | Aluminum Keyboard (ISO)      | 121   | usbhid     | 55A14704FB |
| 1a2c:2d43 | China R... | USB Keyboard                 | 121   | usbhid     | 92E5728D1A |
| 0c45:5004 | Microdia   | Redragon Mitra RGB Keyboard  | 120   | usbhid     | 7E7381D172 |
| 13ba:0018 | PCPlay     | Barcode PCP-BCG4209          | 119   | usbhid     | EE6C610377 |

### Input/mouse (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 093a:2510 | Pixart ... | Optical Mouse                | 3525  | usbhid     | B5175E38D8 |
| 046d:c077 | Logitech   | M105 Optical Mouse           | 2789  | usbhid     | 13F6FA20F2 |
| 046d:c52f | Logitech   | Unifying Receiver            | 2747  | usbhid     | 63B5D9A81A |
| 0458:003a | KYE Sys... | NetScroll+ Mini Traveler ... | 1574  | usbhid     | AAE694A17B |
| 1ea7:0064 | SHARKOO... | 2.4GHz Wireless rechargea... | 1443  | usbhid     | E4CBF06036 |
| 275d:0ba6 |            | USB OPTICAL MOUSE            | 1327  | usbhid     | 11B9953715 |
| 046d:c05a | Logitech   | M90/M100 Optical Mouse       | 1236  | usbhid     | 00119F7BA5 |
| 1bcf:0005 | Sunplus... | Optical Mouse                | 1157  | usbhid     | CA0EB881C4 |
| 1c4f:0034 | SiGma M... | XM102K Optical Wheel Mouse   | 1003  | usbhid     | 5DF50E86BE |
| 0000:0538 |            | USB OPTICAL MOUSE            | 983   | usbhid     | AAB06F55BD |
| 09da:000a | A4Tech     | Optical Mouse Opto 510D /... | 763   | usbhid     | F543BD7919 |
| 248a:8367 | Maxxter    | Telink Wireless Receiver     | 715   | usbhid     | CA501443B2 |
| 18f8:0f97 | [Maxxter]  | USB OPTICAL MOUSE            | 688   | usbhid     | 2C18C9CA1C |
| 093a:2521 | Pixart ... | Optical Mouse                | 679   | usbhid     | 8CA2AF34B9 |
| 0000:3825 |            | USB OPTICAL MOUSE            | 610   | usbhid     | 29F633706A |
| 25a7:fa23 | Areson ... | 2.4G Receiver                | 563   | usbhid     | 5B11088438 |
| 413c:301a | Dell       | Dell MS116 Optical Mouse     | 549   | usbhid     | 5B65572D25 |
| 248a:8514 | Maxxter    | Wireless Receiver            | 544   | usbhid     | 37BE0C0682 |
| 045e:00cb | Microsoft  | Basic Optical Mouse v2.0     | 540   | usbhid     | 940E48E534 |
| 062a:4102 | MosArt ... | Wireless Mouse               | 517   | usbhid     | AF3EBA9CF0 |
| 3938:1031 | MOSART ... | 2.4G Wireless Mouse          | 479   | usbhid     | 8DBEEC994E |
| 046d:c016 | Logitech   | Optical Wheel Mouse          | 473   | usbhid     | BD89F26D7E |
| 10c4:8105 | Silicon... | USB OPTICAL MOUSE            | 408   | usbhid     | 8082B08CE8 |
| 09da:c10a | A4Tech     | USB Mouse                    | 402   | usbhid     | 19F07435FC |
| 046d:c050 | Logitech   | RX 250 Optical Mouse         | 398   | usbhid     | 90A9EE81F6 |
| 18f8:0f99 | [Maxxter]  | Optical gaming mouse         | 394   | usbhid     | 5A6A3FD400 |
| 045e:0040 | Microsoft  | Wheel Mouse Optical          | 387   | usbhid     | C8F0FCF24B |
| 046d:c05b | Logitech   | M-U0004 810-001317 [B110 ... | 382   | usbhid     | 8CBE8C75F8 |
| 046d:c018 | Logitech   | Optical Wheel Mouse          | 379   | usbhid     | 6DF59FAB0E |
| 248a:8366 | Maxxter    | Wireless Optical Mouse AC... | 373   | usbhid     | 3984B7401D |
| 0458:0186 | KYE Sys... | Wired Mouse                  | 349   | usbhid     | 99EF2A5BBA |
| 10c4:8108 | Silicon... | USB OPTICAL MOUSE            | 349   | usbhid     | 1B0AA26214 |
| 1bcf:0007 | Sunplus... | Optical Mouse                | 344   | usbhid     | B5AA561890 |
| 1a2c:0042 | China R... | Usb Mouse                    | 341   | usbhid     | 587E4453B3 |
| 046d:c069 | Logitech   | M-U0007 [Corded Mouse M500]  | 339   | usbhid     | D0428398F6 |
| 17ef:6019 | Lenovo     | M-U0025-O Mouse              | 284   | usbhid     | EBA4267910 |
| 046d:c332 | Logitech   | G502 Proteus Spectrum Opt... | 283   | usbhid     | 204B2A5D7C |
| 046d:c084 | Logitech   | G203 Gaming Mouse            | 282   | usbhid     | B994C1917A |
| 0461:4d0f | Primax ... | HP Optical Mouse             | 281   | usbhid     | D47172F080 |
| 046d:c03e | Logitech   | Premium Optical Wheel Mou... | 270   | usbhid     | F5537F32F6 |
| 15d9:0a4f | Trust I... | Optical Mouse                | 254   | usbhid     | 1023832C74 |
| 0a5c:4503 | Broadcom   | Mouse (Boot Interface Sub... | 239   | usbhid     | 62B30F282D |
| 046d:c062 | Logitech   | M-UAS144 [LS1 Laser Mouse]   | 237   | usbhid     | 6E2F72E53F |
| 2188:0ae1 | No brand   | USB OPTICAL MOUSE            | 234   | usbhid     | 507B8C8A2B |
| 0101:0007 |            | USB OPTICAL MOUSE            | 233   | usbhid     | C432C046F1 |
| 046d:c00e | Logitech   | M-BJ58/M-BJ69 Optical Whe... | 222   | usbhid     | A787298BDB |
| 04f3:0235 | Elan Mi... | Optical Mouse                | 222   | usbhid     | 6BA7F458DA |
| 046d:c08b | Logitech   | G502 SE HERO Gaming Mouse    | 218   | usbhid     | FA126D0D5F |
| 258a:1007 | SINOWEALTH | Game Mouse                   | 206   | usbhid     | 0151392F82 |
| 17ef:608d | Lenovo     | Optical Mouse                | 205   | usbhid     | 29ECAF9382 |
| 03f0:094a | Hewlett... | Optical Mouse [672662-001]   | 202   | usbhid     | EAC7F9AFEC |
| 413c:8162 | Dell       | Integrated Touchpad [Syna... | 201   | usbhid     | FBA9137C3B |
| 046d:c246 | Logitech   | Gaming Mouse G300            | 191   | usbhid     | 0860242147 |
| 03f0:134a | Hewlett... | Optical Mouse                | 189   | usbhid     | 2EFDB3364C |
| 046d:c408 | Logitech   | Marble Mouse (4-button)      | 188   | usbhid     | F2346267E0 |
| 192f:0916 | Avago T... | ADNS-2710 Optical Mouse C... | 185   | usbhid     | CE5B2BF4AB |
| 046d:c07e | Logitech   | G402 Gaming Mouse            | 182   | usbhid     | CCDE838A37 |
| 15d9:0a4d | Trust I... | Optical Mouse                | 177   | usbhid     | 0C76DDBD03 |
| 04b3:310c | IBM        | Wheel Mouse                  | 176   | usbhid     | BB92AB2244 |
| 13ee:0001 | MosArt     | Optical Mouse                | 170   | usbhid     | D4FB582924 |
| 1c4f:0003 | SiGma M... | HID controller               | 170   | usbhid     | A80A7C748B |
| 04d9:a09f | Holtek ... | E-Signal LUOM G10 Mechani... | 169   | usbhid     | F39BCB5DE8 |
| 046d:c53f | Logitech   | USB Receiver                 | 167   | usbhid     | 3E4B181CD8 |
| 046d:c537 | Logitech   | Cordless Mouse Receiver      | 166   | usbhid     | 5D36F4D5D1 |
| 276d:1160 | YSTEK      | G Mouse                      | 164   | usbhid     | 4A44C680DE |
| 0e8f:00fb | GreenAsia  | USB Mouse                    | 161   | usbhid     | C25F7A35DF |
| 1532:005c | Razer USA  | DeathAdder Elite             | 159   | usbhid     | 57D55A953C |
| 062a:4106 | MosArt ... | 2.4G Wireless Mouse          | 156   | usbhid     | DE3596A9A3 |
| 192f:0416 | Avago T... | ADNS-5700 Optical Mouse C... | 155   | usbhid     | C694A13B5A |
| 045e:0084 | Microsoft  | Basic Optical Mouse          | 154   | usbhid     | 14F43DC84D |
| 15d9:0a4c | Trust I... | USB+PS/2 Optical Mouse       | 153   | usbhid     | 00B830F623 |
| 1bcf:08a0 | Sunplus... | Gaming mouse [Philips SPK... | 149   | usbhid     | 19BF6AC286 |
| 04f2:0939 | Chicony... | Amazon Basics mouse          | 146   | usbhid     | F55A54325F |
| 04b4:0060 | Cypress... | Wireless optical mouse       | 143   | usbhid     | 08232B5B75 |
| 046d:c07d | Logitech   | G502 Mouse                   | 142   | usbhid     | D68ABF1123 |
| 046d:c542 | Logitech   | Wireless Receiver            | 140   | usbhid     | 8C7DAC1018 |
| 045e:0039 | Microsoft  | IntelliMouse Optical         | 135   | usbhid     | 5A01104EC3 |
| 413c:3012 | Dell       | Optical Wheel Mouse          | 135   | usbhid     | 913EA68973 |
| 045e:0083 | Microsoft  | Basic Optical Mouse          | 132   | usbhid     | 65E7CD2D3E |
| 1a2c:0044 | China R... | Usb Mouse                    | 124   | usbhid     | 570905286F |
| 24ae:1100 | Shenzhe... | 2.4G Wireless Device         | 124   | usbhid     | 1B01FF9935 |
| 3938:1080 | YK         | 2.4G Wireless Device         | 121   | usbhid     | 8BF97B9982 |
| 0461:4e22 | Primax ... | Dell Mouse, 2 Buttons, Mo... | 120   | usbhid     | 53AB757A21 |
| 046d:c526 | Logitech   | Nano Receiver                | 120   | usbhid     | 442C1C8B06 |
| 17ef:602e | Lenovo     | USB Optical Mouse            | 120   | usbhid     | 442724EA6A |
| 0461:4d22 | Primax ... | USB Optical Mouse            | 117   | usbhid     | 5742C8E4E5 |
| 413c:301d | Dell       | Universal Receiver           | 115   | usbhid     | 184390C71D |
| 1d57:0008 | Xenta      | 2.4G Wireless Optical Mouse  | 113   | usbhid     | 7955F23581 |
| 046d:c03d | Logitech   | M-BT96a Pilot Optical Mouse  | 111   | usbhid     | 464400432F |
| 05ac:0304 | Apple      | Mighty Mouse [Mitsumi, M1... | 110   | usbhid     | EE570B7B0C |
| 046d:c019 | Logitech   | Optical Tilt Wheel Mouse     | 109   | usbhid     | 342F07FA37 |
| 093a:2533 | Pixart ... | Gaming Mouse                 | 109   | usbhid     | 960762905F |
| 1d57:ad17 | Xenta      | ZELOTES GAME MOUSE           | 109   | usbhid     | BD17F8FBD9 |
| 413c:3016 | Dell       | Optical 5-Button Wheel Mouse | 109   | usbhid     | FF231665D3 |
| 045e:0797 | Microsoft  | Optical Mouse 200            | 108   | usbhid     | 08C9C4C3F9 |
| 1c4f:0048 | SiGma M... | Usb Mouse                    | 108   | usbhid     | DACA0DDD7E |
| 045e:076c | Microsoft  | Comfort Mouse 4500           | 107   | usbhid     | 3F35C907A2 |
| 413c:8158 | Dell       | Integrated Touchpad / Tra... | 107   | usbhid     | 90762831E7 |
| 046d:c051 | Logitech   | G3 (MX518) Optical Mouse     | 106   | usbhid     | 59F96992D1 |
| 046d:c045 | Logitech   | Optical Mouse                | 105   | usbhid     | 5AD35410C9 |

### Isdn adapter (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| ffff:ffff | RAPOO      | AVM A1 PCMCIA                | 10    | usbhid     | FCD5C85A91 |
| 0681:0002 | Siemens... | Gigaset 3075 Passive ISDN    | 1     | bas_gig... | B11EDA70A9 |

### Joystick (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:02ea | Microsoft  | Xbox One S Controller        | 88    | xpad       | 3F2F789273 |
| 24c6:581a | ThrustM... | XB1 Classic Controller       | 21    | xpad       | C424F01FF6 |
| 044f:b687 | ThrustM... | TWCS Throttle                | 12    | usbhid     | A635A3ACB3 |
| 068e:00f2 | CH Prod... | Flight Sim Pedals            | 8     | usbhid     | 2D6A252F42 |
| 0e6f:02b8 | Logic3     | Afterglow Wired Controlle... | 8     | xpad       | 63CB2BFE57 |
| 07b5:0317 | Mega Wo... | USB Game Controllers         | 6     | usbhid     | 78FC18FCF4 |
| 2341:8037 | Arduino SA | Arduino Micro                | 6     | usbhid     | 6D05038359 |
| 046d:c262 | Logitech   | G920 Driving Force Racing... | 5     | usbhid     | F32B55643E |
| 0e6f:02a4 | Logic3     | PDP Wired Controller for ... | 5     | xpad       | 7CCAB1854D |
| 28de:1102 | Valve S... | Wired Controller             | 5     | usbhid     | 1769F91F11 |
| 06a3:0109 | Saitek     | P880 Pad                     | 4     | usbhid     | 40210AAF34 |
| 06a3:0c2d | Saitek     | Pro Flight Quadrant          | 4     | usbhid     | 4D4959DF32 |
| 145f:01bb | Trust      | Gamepad                      | 4     | usbhid     | 51CA5C6660 |
| 0458:1004 | KYE Sys... | Flight2000 F-23 Joystick     | 3     | usbhid     | 0C5BDA9187 |
| 045e:000e | Microsoft  | SideWinder� Freestyle Pro    | 3     | usbhid     | 29CD216C62 |
| 046d:c213 | Logitech   | J-UH16 (Freedom 2.4 Cordl... | 3     | usbhid     | 6E2F61F9D2 |
| 04d8:fd0a | Microch... | Lexip Gaming                 | 3     | usbhid     | F36828F316 |
| 0738:1302 | Mad Catz   | F.L.Y.5 Stick                | 3     | usbhid     | FBAF774D0B |
| 0e6f:0119 | Logic3     | wireless controller for PS3  | 3     | usbhid     | 300431594A |
| 0e6f:02c6 | Logic3     | PDP Deluxe Wired Controll... | 3     | xpad       | 7F349B8B8D |
| 12bd:a02f | Gembird    | 5-Axis,12-Button with POV    | 3     | usbhid     | B723B19A29 |
| 1532:0a14 | Razer USA  | Razer Wolverine Ultimate     | 3     | xpad       | 31E45B375E |
| 20bc:5500 | ShenZhe... | Frostbite controller         | 3     | usbhid     | 71733FBF6F |
| 231d:1105 | www.vkb... | GTX Throttle                 | 3     | usbhid     | 417453E269 |
| 0428:4001 | Advance... | GamePad Pro                  | 2     | usbhid     | B33486C990 |
| 044f:b323 | ThrustM... | Dual Trigger 3-in-1 (PC M... | 2     | usbhid     | D36AA4ED19 |
| 054c:03d5 | Sony       | PlayStation Move motion c... | 2     | usbhid     | 32805E80B1 |
| 05ac:056b | Apple      | GameSir-T2a                  | 2     | usbhid     | 912852805F |
| 068e:00f3 | CH Prod... | Fighterstick                 | 2     | usbhid     | B87BD193E6 |
| 0e6f:0139 | Logic3     | Afterglow Wired Controlle... | 2     | xpad       | 17ACFC90D4 |
| 0e6f:0162 | Logic3     | PDP Wired Controller for ... | 2     | xpad       | 09520E9204 |
| 0eb7:183b | Endor      | ClubSportPedal               | 2     | usbhid     | B2DE3AF507 |
| 11ff:001b |            | LS PC Controller             | 2     | usbhid     | B52E5BED36 |
| 20d6:ca6d | Unknown... | Pro Ex                       | 2     | usbhid     | 858605237B |
| 231d:0121 | www.vkb... | VKBsim Gladiator             | 2     | usbhid     | 7BCE3059DC |
| 24c6:542a | ThrustM... | Spectra for Xbox One         | 2     | xpad       | 34A482168B |
| 0079:189c | DragonRise | PXN-V3II                     | 1     | xpad       | D90F3585DA |
| 044f:d007 | ThrustM... | T Mini Wireless              | 1     | usbhid     | 276BA45744 |
| 044f:d00e | ThrustM... | eSwap PRO Controller         | 1     | usbhid     | F816144F1B |
| 046d:c293 | Logitech   | WingMan Formula Force GP     | 1     | usbhid     | 38E0EE4482 |
| 0583:805e | Padix (... | USB, 4-axis, 4-button joy... | 1     | usbhid     | 838D58EB90 |
| 05b8:0a20 | Agiler     | Steering Wheel               | 1     | usbhid     | 3BD37E342E |
| 062a:2410 | MosArt ... | Wireless PS3 gamepad         | 1     | usbhid     | 14781D6ECE |
| 068e:00f1 | CH Prod... | Pro Throttle                 | 1     | usbhid     | B87BD193E6 |
| 06a3:0006 | Saitek     | Cyborg Gold Joystick         | 1     | usbhid     | 392A044989 |
| 06a3:0255 | Saitek     | X52 Flight Controller        | 1     | usbhid     | 79777938CC |
| 0866:0100 | WWW.TUA... | VENOM-X_MOUSE                | 1     | usbhid     | 7A2466E991 |
| 099a:7010 | Zippy T... | Gaming Keyboard              | 1     | usbhid     | F9B28ED0FD |
| 0b43:0003 | Play.com   | PS2 Controller Converter     | 1     | usbhid     | A26AF9A455 |
| 0c12:0e10 | Zeroplus   | P4 Wired Gamepad             | 1     | usbhid     | BBD6DA0DD4 |
| 0e6f:013a | Logic3     | PDP Xbox One Controller      | 1     | xpad       | A9178F9852 |
| 0e6f:0229 | Logic3     | Disney Infinity Base         | 1     | xpad       | 7D749B3ECC |
| 0e8f:0013 | GreenAsia  | USB Joystick                 | 1     | usbhid     | 1EAADEB8F4 |
| 0f0d:005e | Hori       | Fighting Commander 4         | 1     | usbhid     | F232C678DA |
| 11ff:001c |            | PXN-V3II                     | 1     | usbhid     | D1DED92F20 |
| 1209:f00d | InterBi... | Shifter/Pedals Adapter       | 1     | usbhid     | 5AAA478577 |
| 1532:0705 | Razer USA  | Raiju Mobile Wired           | 1     | usbhid     | 21184F9BA8 |
| 1bad:f025 | Harmoni... | Call of Duty Controller f... | 1     | xpad       | 4625D62A82 |
| 20bc:5501 | Umido      | NeoGeo G1 Pro D-Input        | 1     | usbhid     | 64DB7E90FE |
| 20bc:aa00 | ShenZhe... | BETOP CONTROLLER             | 1     | usbhid     | 220E504029 |
| 20d6:a713 | Bensuss... | NSW Wired controller         | 1     | usbhid     | C1576F7B77 |
| 214e:0014 | Swiftpoint | Swiftpoint Tracer            | 1     | usbhid     | 0B85AF69C2 |
| 256f:c62e | 3Dconne... | SpaceMouse Wireless          | 1     | usbhid     | 49486E2ABF |

### Mfp (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:042a | Hewlett... | LaserJet M1132 MFP           | 40    | usblp      | 00658A23AB |
| 03f0:222a | Hewlett... | LaserJet Pro MFP M125nw      | 30    | usblp      | B661AA21F1 |
| 03f0:3b17 | Hewlett... | LaserJet M1005 MFP           | 29    | usblp      | B79DCDB648 |
| 03f0:5617 | Hewlett... | LaserJet M1120 MFP           | 20    | usblp      | 28B516FFF4 |
| 03f0:bf2a | Hewlett... | LaserJet MFP M28-M31         | 13    | usblp      | 77C3BBC977 |
| 03f0:622a | Hewlett... | LaserJet MFP M129-M134       | 12    | usblp      | 8EE390F293 |
| 0924:3cef | Xerox      | Phaser 3100MFP               | 12    | usblp      | 7AB9D987EB |
| 03f0:052a | Hewlett... | LaserJet M1212nf MFP         | 11    | usblp      | 496B2FCD96 |
| 04b8:083f | Seiko E... | Stylus CX4300/CX4400/CX55... | 10    | usblp      | 9473725930 |
| 0924:42af | Xerox      | WorkCentre 3045B             | 10    | usblp      | 989A2EAABB |
| 04b8:084d | Seiko E... | PX-402A [Stylus SX115/Sty... | 9     | usblp      | 2CFB272CEC |
| 03f0:ad2a | Hewlett... | ColorLaserJet MFP M278-M281  | 8     | usblp      | E73BFE9067 |
| 04b8:082f | Seiko E... | PX-A620 [Stylus CX3900/DX... | 7     | usblp      | 2DAC59A075 |
| 03f0:3b2a | Hewlett... | Color LaserJet MFP M277dw    | 6     | usblp      | A781661029 |
| 03f0:5717 | Hewlett... | LaserJet M1120n MFP          | 6     | usblp      | 6697D98216 |
| 0482:0495 | Kyocera    | FS-1020MFP                   | 5     | usblp      | 9088D156A3 |
| 04b8:0841 | Seiko E... | PX-401A [ME 300/Stylus NX... | 5     | usblp      | 31DC2A086D |
| 03f0:062a | Hewlett... | LaserJet 100 colorMFP M175a  | 4     | usblp      | 5B83E2F312 |
| 03f0:2d2a | Hewlett... | LaserJet Pro MFP M225dn      | 4     | usblp      | 1B4BF985A0 |
| 03f0:012a | Hewlett... | LaserJet M1536dnf MFP        | 3     | usblp      | 9849E9DD35 |
| 03f0:0e2a | Hewlett... | Smart Install                | 3     | uas, us... | B027C83F03 |
| 03f0:142a | Hewlett... | LaserJet 400 MFP M425dn      | 3     | usblp      | BB50D755A2 |
| 03f0:242a | Hewlett... | Color LaserJet Pro MFP M176n | 3     | usblp      | 769CB653F7 |
| 03f0:322a | Hewlett... | LaserJet Pro MFP M127fn      | 3     | usblp      | 9FD78FBC60 |
| 03f0:932a | Hewlett... | LaserJet Pro MFP M26nw       | 3     | usblp      | DF4338099C |
| 0482:0497 | Kyocera    | FS-1025MFP                   | 3     | usblp      | 442642A23C |
| 04b8:080e | Seiko E... | PX-A550 [CX-3500/3600/365... | 3     | usblp      | 1AB6F30041 |
| 0924:3d6f | Xerox      | Phaser 6020                  | 3     | usblp      | 79A097BF6F |
| 0924:42da | Xerox      | WorkCentre 3025              | 3     | usblp      | 085B92ACA9 |
| 0924:42db | Xerox      | WorkCentre 3215              | 3     | usblp      | 0F22425E10 |
| 03f0:5817 | Hewlett... | LaserJet M1319f MFP          | 2     | usblp      | DD0A730661 |
| 03f0:5a2a | Hewlett... | LaserJet MFP M426fdw         | 2     | usblp      | D00254CBC5 |
| 04b8:0818 | Seiko E... | Stylus CX3700/CX3800/DX3800  | 2     | usblp      | D4567C6F8A |
| 0924:42c4 | Xerox      | WorkCentre 3615              | 2     | usblp      | 0BF7A6E91D |
| 0924:42dc | Xerox      | WorkCentre 3225              | 2     | usblp      | C9F5D29162 |
| 03f0:0970 | Hewlett... | ColorLaserJet MFP M282-M285  | 1     | usblp      | 0AD4AA43AA |
| 03f0:1d2a | Hewlett... | Color LaserJet flow MFP M880 | 1     | usblp      | 9F2622FF85 |
| 03f0:252a | Hewlett... | LaserJet 500 colorMFP M570dw | 1     | usblp      | 8EA70251FB |
| 03f0:2e2a | Hewlett... | LaserJet Pro MFP M435nw      | 1     | usblp      | A457D54FAD |
| 03f0:342a | Hewlett... | Color LaserJet MFP M476dn    | 1     | usblp      | F9F42752CA |
| 03f0:362a | Hewlett... | Officejet Color FlowMFP X585 | 1     | usblp      | 4966DF06F4 |
| 03f0:442a | Hewlett... | Color LaserJet Flow MFP M680 | 1     | usblp      | BF4C79032E |
| 03f0:4e17 | Hewlett... | Color LaserJet CM1312 MFP    | 1     | usblp      | 426F11F2D2 |
| 03f0:532a | Hewlett... | LaserJet MFP M426dw          | 1     | usblp      | 93A67E4976 |
| 03f0:642a | Hewlett... | LaserJet MFP M227-M231       | 1     | usblp      | 7621EB165A |
| 03f0:862a | Hewlett... | Color LaserJet MFP M377dw    | 1     | usblp      | 136E5D26E2 |
| 03f0:9e17 | Hewlett... | LaserJet 500 MFP M525        | 1     | usblp      | 80E0F6373A |
| 03f0:9f17 | Hewlett... | LaserJet 500 color MFP M575  | 1     | usblp      | A043EA04EA |
| 03f0:af2a | Hewlett... | ColorLaserJet MFP M178-M181  | 1     | usblp      | F9F288372E |
| 03f0:d511 | Hewlett... | PageWide Pro 477dw MFP       | 1     | usbfs      | BD95D49C15 |
| 03f0:eb2a | Hewlett... | Color Laser MFP 178nw        | 1     | usblp      | 2FE3E165EB |
| 0924:3d6b | Xerox      | WorkCentre 6505DN            | 1     | usblp      | 66BC368A83 |
| 0924:42d4 | Xerox      | WorkCentre 6027              | 1     | usblp      | E363684B4B |
| 413c:523b | Dell       | B1265dfw Mono MFP            | 1     | usblp      | 016DA6343D |
| 413c:5406 | Dell       | 1355cnw Color MFP            | 1     | usbfs      | EF4245C8A3 |
| 413c:564a | Dell       | C1765nfw Color MFP           | 1     | usblp      | FD8ACE53F7 |
| 413c:564e | Dell       | C2665dnf Color MFP           | 1     | usblp      | 70493B615B |
| 413c:590b | Dell       | MFP                          | 1     | usblp      | 0F4BBAE4FA |

### Miscellaneous (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2d95:600a | vivo       | V2027                        | 7     | rndis_host | C28788427E |
| 2e04:c008 | HMD Global | Tethering Network Interface  | 4     | rndis_host | C8A59F2F74 |
| 1390:5a01 | TOMTOM     | GO Professional 6250         | 2     | rndis_host | BE27200090 |
| 1e10:4000 | Point G... | U3V camera                   | 2     |            | 2BC5FA3C88 |
| 0bb4:0b0c | HTC (Hi... | Elf / Touch / P3450 / T-M... | 1     | rndis_w... | 5E75A35A7D |
| 1004:6343 | LG Elec... | LM-V600                      | 1     | rndis_h... | B5C18575BF |
| 1410:b022 | Novatel... | MiFi 7000                    | 1     | rndis_h... | 9F5C7C160A |
| 2676:ba05 | Basler     | a2A1920-160ucBAS             | 1     |            | 273BC677CD |

### Modem (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 12d1:1506 | Huawei ... | Modem/Networkcard            | 395   | uas, us... | 142A31AF57 |
| 27c6:5395 | Shenzhe... | Fingerprint Reader           | 255   | cdc_acm    | 08B1E4C99F |
| 27c6:5301 | Shenzhe... | Fingerprint Reader           | 204   | cdc_acm    | 08DBD93BE1 |
| 27c6:5385 | Shenzhe... | Fingerprint Reader           | 136   | cdc_acm    | 94F04E5543 |
| 0bdb:1911 | Ericsso... | F5521gw                      | 106   | cdc_acm    | FA5ABFCCF8 |
| 0bdb:1926 | Ericsso... | H5321 gw Mobile Broadband... | 98    | cdc_acm    | AEF8C27B50 |
| 0bdb:193e | Ericsso... | N5321 gw                     | 62    | cdc_acm    | 92C8EBC282 |
| 12d1:1436 | Huawei ... | Broadband stick              | 54    | usb_sto... | 3056DB282E |
| 0bdb:1900 | Ericsso... | F3507g Mobile Broadband M... | 52    | cdc_acm... | FFC6990547 |
| 2341:0043 | Arduino SA | Uno R3 (CDC ACM)             | 50    | cdc_acm    | 321B9F409A |
| 413c:818d | Dell       | DW5550                       | 49    | cdc_acm    | 70DD19848D |
| 03f0:3d1d | Hewlett... | hs2350 HSPA+ MobileBroadband | 44    | cdc_acm    | 698D0BAADD |
| 03f0:3a1d | Hewlett... | hs2340 HSPA+ mobile broad... | 41    | cdc_acm    | F9EE7C5367 |
| 12d1:1001 | Huawei ... | E161/E169/E620/E800 HSDPA... | 39    | usb_sto... | D507F88A47 |
| 413c:818e | Dell       | DW5560 miniPCIe HSPA+ Mob... | 35    | cdc_acm    | 7F740D929F |
| 413c:8147 | Dell       | F3507g Mobile Broadband M... | 32    | cdc_ether  | 98D088D90D |
| 413c:8184 | Dell       | F3607gw v2 Mobile Broadba... | 30    | cdc_acm    | A004DC1637 |
| 27c6:5381 | Shenzhe... | Fingerprint Reader           | 29    | cdc_acm    | 65C1600593 |
| 12d1:140c | Huawei ... | E180v                        | 26    | usb_sto... | E66EEF020E |
| 12d1:1003 | Huawei ... | E220 HSDPA Modem / E230/E... | 25    | usb_sto... | FA8BCEF5A9 |
| 1546:01a7 | U-Blox     | [u-blox 7]                   | 19    | cdc_acm    | 5FE3179524 |
| 1209:1776 | InterBi... | Io                           | 18    | system7... | EBF234C535 |
| 0658:0200 | Sigma D... | Aeotec Z-Stick Gen5 (ZW09... | 17    | cdc_acm    | 6158B04856 |
| 12d1:1570 | Huawei ... | MOBILE                       | 16    | option     | C31DC1892D |
| 0424:274d | Microch... | HTC Hub Controller           | 14    | cdc_acm    | 3676C6C723 |
| 04e8:6872 | Samsung... | Kiera                        | 14    | cdc_acm    | D02957CDB5 |
| 04d8:00df | Microch... | MCP2200 USB Serial Port E... | 11    | cdc_acm    | 2F8BA8AF70 |
| 12d1:1404 | Huawei ... | EM770W miniPCI WCDMA Modem   | 11    | usb_sto... | F8501E519F |
| 0451:16a8 | Texas I... | TI CC2531 USB CDC            | 9     | cdc_acm    | BAB965C49D |
| 0483:5740 | STMicro... | Virtual COM Port             | 9     | cdc_acm    | D1CA5138F2 |
| 1546:01a8 | U-Blox     | [u-blox 8]                   | 9     | cdc_acm    | 08514D3FB0 |
| 19d2:1515 | ZTE WCD... | MF195                        | 8     | cdc_acm    | 3954E61E9A |
| 2341:0042 | Arduino SA | Mega 2560 R3 (CDC ACM)       | 8     | cdc_acm    | 24FAB4AA05 |
| 2548:1002 | Pulse-E... | CEC Adapter                  | 8     | cdc_acm    | 1BCFF94731 |
| 04e2:1410 | Exar       | XR21V1410 USB-UART IC        | 7     | cdc_acm... | A16A117B5A |
| 0e8d:0003 | MediaTek   | MT6227 phone                 | 7     | cdc_acm... | 687AED65CF |
| 12d1:14ac | Huawei ... | E815                         | 7     | option     | 8B53FFA4DF |
| 1c11:b04d | Input Club | Keyboard - WhiteFox:truef... | 7     | usbhid     | 0F23806951 |
| 1cf1:0030 | Dresden... | ZigBee gateway [ConBee II]   | 7     | cdc_acm    | 6F289497FC |
| 2341:0001 | Arduino SA | Uno (CDC ACM)                | 7     | cdc_acm    | C3E5771D2F |
| 2833:0051 | Oculus VR  | Rift S                       | 7     | usbhid     | 0FC971F278 |
| 0930:1319 | Toshiba    | H5321gw                      | 6     | cdc_acm    | 9816B952D7 |
| 0bdb:190a | Ericsso... | F3307 Mobile Broadband Mo... | 6     | cdc_acm    | 8D386EA5A9 |
| 1366:0105 | SEGGER     | J-Link                       | 6     | cdc_acm    | D180569750 |
| 1546:01a5 | U-Blox     | [u-blox 5]                   | 5     | cdc_acm    | C2D9EFD034 |
| 0603:4001 | Novatek... | NVT-FPR                      | 4     | usbhid     | 8F873C01CB |
| 0930:1314 | Toshiba    | F5521gw                      | 4     | cdc_acm    | F7C456B329 |
| 1edf:6004 | Select ... | MCD-640S-1EDF-6004           | 4     | cdc_acm    | F9D3A09989 |
| 2886:8027 | Seeed T... | Seeeduino_Cortex_M0+         | 4     | cdc_acm    | 2AD340FE6F |
| 2a03:0043 | dog hunter | Arduino Uno Rev3             | 4     | cdc_acm    | EFCE67D492 |
| 8087:0ab6 | Intel      | UDOO X86                     | 4     | cdc_acm    | 62AE920D77 |
| 03f0:2f1d | Hewlett... | lc2010 Mobile Broadband M... | 3     | cdc_acm    | ADF2557C53 |
| 04d8:f5fe | Microch... | TrueRNG                      | 3     | cdc_acm    | B9270B9C26 |
| 04e8:6773 | Samsung... | HSPA Modem                   | 3     | cdc_acm    | 4A42295588 |
| 04e8:6843 | Samsung... | E2530 Phone (Samsung Kies... | 3     | cdc_acm... | 459627EDA2 |
| 0bdb:1902 | Ericsso... | F3507g v2 Mobile Broadban... | 3     | cdc_acm    | 349C20610A |
| 0bdb:190d | Ericsso... | F5521gw                      | 3     | cdc_acm    | E1FED7F277 |
| 0bdb:1936 | Ericsso... | C5621 gw                     | 3     | cdc_acm    | AB871DCBE2 |
| 1004:6000 | LG Elec... | Various Mobile Phones        | 3     | cdc_acm    | EE59C663F5 |
| 106c:3714 | Curitel... | PANTECH USB MODEM [UM175]    | 3     | cdc_acm    | F4807D695F |
| 12d1:1573 | Huawei ... | Mobile                       | 3     | option     | 4120FA5430 |
| 12d1:1c1e | Huawei ... | Mass Storage                 | 3     | uas, us... | DDD57927D5 |
| 1519:0020 | Comneon    | HSIC Device                  | 3     | cdc_acm    | E277646CEF |
| 16c0:0483 | Van Ooi... | Teensyduino Serial           | 3     | cdc_acm    | A50C792692 |
| 1eaf:0004 | Leaflabs   | Maple serial interface       | 3     | cdc_acm    | 825C9359F9 |
| 03eb:204b | Atmel      | LUFA USB to Serial Adapte... | 2     | cdc_acm    | DAE3697FF8 |
| 0421:0302 | Nokia M... | N8-00                        | 2     | cdc_acm    | 495FCF02B1 |
| 0421:0524 | Nokia M... | Nokia 300                    | 2     | cdc_acm    | 9C1238B041 |
| 0461:0033 | Primax ... | USB_Focus                    | 2     | cdc_acm    | 09C3D95876 |
| 0483:a26d | STMicro... | USB Watchdog                 | 2     | cdc_acm    | 8D943AEA44 |
| 04e2:1411 | Exar       | XR21B1411                    | 2     | cdc_acm... | ED5100771D |
| 04e2:1412 | Exar       | XR21V1412 USB UART Ch A      | 2     | cdc_acm    | 593A489E8D |
| 0525:a4a7 | Netchip... | Linux-USB Serial Gadget (... | 2     | cdc_acm    | 2541D35BD4 |
| 0525:a4aa | Netchip... | Linux-USB CDC Composite G... | 2     | cdc_acm    | 50BADFB190 |
| 079b:0028 | Sagem      | Modem                        | 2     | cdc_acm    | 9005441938 |
| 0baf:00ec | U.S. Ro... | 56K Faxmodem                 | 2     |            | EF974030B3 |
| 0baf:0303 | U.S. Ro... | USR5637 56K Faxmodem         | 2     | cdc_acm    | C5109BAB9C |
| 1004:6169 | LG Elec... | LGE Modem                    | 2     | cdc_ether  | D2599D1470 |
| 106c:3716 | Curitel... | UMW190 Modem                 | 2     | cdc_acm    | 06FBB87A4E |
| 1209:2201 | InterBi... | Dygma Shortcut Keyboard      | 2     | cdc_acm    | 00CD4878A3 |
| 12d1:1465 | Huawei ... | K3765 HSPA                   | 2     | uas, us... | D99338778F |
| 1366:1015 | SEGGER     | J-Link                       | 2     | cdc_acm    | 6BE76778AE |
| 1546:01a6 | U-Blox     | [u-blox 6]                   | 2     | cdc_acm    | A4AD398189 |
| 1cbe:00fd | Luminar... | In-Circuit Debug Interface   | 2     | cdc_acm    | 363320D61E |
| 1d50:6086 | OpenMoko   | OneRNG entropy device        | 2     | cdc_acm    | DAE3697FF8 |
| 1fc9:8125 | NXP Sem... | openSPOT2                    | 2     | cdc_acm    | CAE2DE05FF |
| 2687:fd11 | Fitbit     | Versa 2                      | 2     | cdc_acm    | C153015D2F |
| 27b1:0001 | UltiMac... | RAMBo                        | 2     | cdc_acm    | 751345EB91 |
| 2886:802f | Seeed      | XIAO M0                      | 2     | cdc_acm    | 06A3CD7D2F |
| 2ec2:0002 | Loupedeck  | Loupedeck+                   | 2     | snd_usb... | C9F5D6FDD0 |
| 03eb:2404 | Atmel      | The Micro                    | 1     | cdc_acm    | FF465CB33F |
| 03eb:6124 | Atmel      | at91sam SAMBA bootloader     | 1     | cdc_acm    | 2BF3A4DEF3 |
| 0416:5011 | Winbond... | Virtual Com Port             | 1     | cdc_acm    | 913D5AFF80 |
| 0421:01d0 | Nokia M... | E52                          | 1     | cdc_acm    | D649B2DEB3 |
| 0421:0223 | Nokia M... | E72-1                        | 1     | cdc_acm    | A913DFEFEE |
| 0421:026c | Nokia M... | N97 (PC Suite)               | 1     | cdc_acm    | 11D0F0433C |
| 0421:0348 | Nokia M... | Nokia 5228                   | 1     | cdc_acm    | 4F7EEE94F1 |
| 0421:0355 | Nokia M... | Nokia X2-00                  | 1     | cdc_acm    | 1F5E6B026B |
| 0421:0360 | Nokia M... | C1-01 Ovi Suite Mode         | 1     | cdc_acm    | 9C2894BEA0 |
| 0421:05fd | Nokia M... | 202                          | 1     | cdc_acm    | 1A8A955A5B |

### Net/ethernet (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0fe6:9900 | ICS Advent | USB 10/100 LAN               | 7     | cdc_ether  | 64A9E43743 |
| 03f0:911d | Hewlett... | lt4211 Gobi 4G Module        | 4     | cdc_ether  | CEBBA8A2A8 |
| 0bda:8156 | Realtek... | USB 10/100/1G/2.5G LAN       | 4     | cdc_ncm    | D5B8EFA3CA |
| 17e9:430a | Display... | HP Port Replicator (Compo... | 3     | cdc_ncm    | F02A4A5E93 |
| 17e9:436c | Display... | Dell D1000 USB3.0 Dock       | 3     | cdc_ncm    | 1E6CBEB181 |
| 0424:9500 | Microch... | LAN9500/LAN9500i             | 2     | smsc95xx   | 2F9F2D0497 |
| 17e9:431f | Display... | ThinkPad Basic USB 3.0 Dock  | 2     | cdc_ncm... | C9837EF0C1 |
| 1c04:0015 | QNAP Sy... | QNAP QNA-UC5G1T USB to 5G... | 2     | aqc111     | D391C49614 |
| 2eca:c101 | Aquantia   | Sabrent 2.5G Network Adapter | 2     | aqc111     | EDE21C354C |
| 03f0:0547 | Hewlett... | L2311c LAN7500 Ethernet      | 1     |            | EBB304F58E |
| 03f0:0857 | Hewlett... | lt4220 Snapdragon X12 LTE    | 1     | cdc_ether  | 54BAAAD690 |
| 056e:4007 | Elecom     | WDC-433DU2HBK                | 1     | rtl8812au  | 4F8794ED64 |
| 0df6:0072 | Sitecom... | AX88179 Gigabit Ethernet ... | 1     | ax88179... | 85C6FB8933 |
| 17e9:433e | Display... | dynadock 4K                  | 1     | cdc_ncm    | FDC926F819 |
| 17e9:6008 | Display... | Targus USB3 DV4K DOCK w P... | 1     | cdc_ncm... | 2B158EA18F |
| 17ef:3052 | Lenovo     | ThinkPad TabletDock          | 1     | cdc_ether  | 1D6F4C02A1 |
| 17ef:721e | Lenovo     | Powered Hub                  | 1     | cdc_ether  | F1D7117DC7 |

### Net/wimax (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0180 | Intel      | WiMAX Connection 2400m       | 52    | i2400m_usb | 20A3F68FE3 |
| 8086:0186 | Intel      | WiMAX Connection 2400m       | 52    | i2400m_usb | 4C8ACBFF76 |
| 8086:1406 | Intel      | WiMAX Connection 2400m       | 44    | i2400m_usb | 787FE33124 |
| 8087:07d6 | Intel      | Centrino Wireless-N + WiM... | 39    | i2400m_usb | 5E0B431CB8 |
| 8086:0188 | Intel      | WiMAX Connection 2400m       | 16    | i2400m_usb | B93D1CDCA0 |
| 8086:0187 | Intel      | Centrino Advanced-N + WiM... | 9     | i2400m_usb | 74057C8385 |
| 8086:0182 | Intel      | WiMAX Connection 2400m       | 2     | i2400m_usb | 01517BE2D7 |

### Net/wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 148f:7601 | Ralink ... | MT7601U Wireless Adapter     | 905   | mt7601u    | 8BF97B9982 |
| 0bda:8179 | Realtek... | RTL8188EUS 802.11n Wirele... | 857   | r8188eu    | 1FE01A8A37 |
| 0cf3:9271 | Qualcom... | AR9271 802.11n               | 648   | ath9k_htc  | E200A28D76 |
| 148f:5370 | Ralink ... | RT5370 Wireless Adapter      | 437   | rt2800usb  | EB4F7A5CF5 |
| 0bda:b812 | Realtek... | RTL88x2bu [AC1200 Techkey]   | 403   | 88x2bu     | 64ED40D969 |
| 148f:3070 | Ralink ... | RT2870/RT3070 Wireless Ad... | 401   | rt2800usb  | F98947BE5F |
| 0bda:8178 | Realtek... | RTL8192CU 802.11n WLAN Ad... | 365   | rtl8192... | 34A921FD71 |
| 0bda:8176 | Realtek... | RTL8188CUS 802.11n WLAN A... | 275   | rtl8192... | B5A6752EE2 |
| 2357:0109 | TP-Link    | TL-WN823N v2/v3 [Realtek ... | 263   | rtl8xxxu   | A32062ECA7 |
| 0bda:c811 | Realtek... | 802.11ac NIC                 | 227   | 8821cu     | 2469CA65B1 |
| 2357:010c | TP-Link    | TL-WN722N v2                 | 183   | r8188eu    | C432C046F1 |
| 0bda:8189 | Realtek... | RTL8187B Wireless 802.11g... | 180   | rtl8187    | 53428CC56A |
| 0bda:818b | Realtek... | RTL8192EU 802.11b/g/n WLA... | 168   | rtl8xxxu   | 84B10EACCC |
| 0bda:f179 | Realtek... | 802.11n                      | 165   | rtl8188fu  | CE3E0081A5 |
| 2357:011e | TP-Link    | AC600 wireless Realtek RT... | 148   | 88XXau     | 23A20D91EF |
| 045e:0719 | Microsoft  | Xbox 360 Wireless Adapter    | 141   | xpad       | D5D05D2F78 |
| 0bda:8187 | Realtek... | RTL8187 Wireless Adapter     | 140   | rtl8187    | 1C50D13AC7 |
| 0bda:8172 | Realtek... | RTL8191SU 802.11n WLAN Ad... | 132   | r8712u     | 14EDF3BD00 |
| 0bda:8812 | Realtek... | RTL8812AU 802.11a/b/g/n/a... | 128   | 8812au     | F98947BE5F |
| 7392:7811 | Edimax ... | EW-7811Un 802.11n Wireles... | 116   | rtl8192... | 9C1343DD9B |
| 148f:5572 | Ralink ... | RT5572 Wireless Adapter      | 114   | rt2800usb  | C9F48C1D32 |
| 0bda:a811 | Realtek... | RTL8811AU 802.11a/b/g/n/a... | 107   | 88XXau     | 49FF8D705B |
| 148f:5372 | Ralink ... | RT5372 Wireless Adapter      | 101   | rt2800usb  | 464400432F |
| 148f:761a | Ralink ... | MT7610U ("Archer T2U" 2.4... | 101   | mt76x0u    | 7CCA14C70D |
| 148f:2573 | Ralink ... | RT2501/RT2573 Wireless Ad... | 87    | rt73usb    | D33CCE58A1 |
| 2357:0107 | TP-Link    | TL-WN821N v5/v6 [RTL8192EU]  | 87    | rtl8xxxu   | 21FFA9E4C4 |
| 413c:81b6 | Dell       | DW5811e Snapdragon™ X7 LTE | 83    | qcseria... | 6BE76778AE |
| 0bda:0811 | Realtek... | Realtek 8812AU/8821AU 802... | 78    | rtl8812au  | 87B8429DB3 |
| 0bda:8171 | Realtek... | RTL8188SU 802.11n WLAN Ad... | 72    | r8712u     | D502EE8537 |
| 0b05:17ba | ASUSTek... | N10 Nano 802.11n Network ... | 70    | rtl8192cu  | 3E6D98FE9C |
| 07d1:3c0a | D-Link ... | DWA-140 RangeBooster N Ad... | 68    | rt2800usb  | 26947ED7FD |
| 0846:9053 | NetGear    | A6210                        | 68    | mt76x2u    | 71D4E5711B |
| 1199:9079 | Sierra ... | EM7455                       | 67    | qcseria... | EEB5037642 |
| 0bda:8197 | Realtek... | RTL8187B Wireless Adapter    | 66    | rtl8187    | 1C418BBCEF |
| 2001:3319 | D-Link     | Wireless N Nano USB Adapter  | 66    | rtl8xxxu   | 3056DB282E |
| 0846:9052 | NetGear    | A6100 AC600 DB Wireless A... | 65    | 8812au     | E995A218C9 |
| 0cf3:7015 | Qualcom... | TP-Link TL-WN821N v3 / TL... | 64    | ath9k_htc  | 5EFBEFCAA5 |
| 0b05:17ab | ASUSTek... | USB-N13 802.11n Network A... | 60    | rtl8192cu  | 5E58B5909B |
| 0846:9030 | NetGear    | WNA1100 Wireless-N 150 [A... | 59    | ath9k_htc  | 21833C414E |
| 2357:0115 | TP-Link    | Archer T4U ver.3             | 57    | 88x2bu     | 4C34BAF1DC |
| 13d3:3306 | IMC Net... | Mediao 802.11n WLAN [Real... | 53    | r8712u     | 3BD37E342E |
| 2001:3c15 | D-Link     | DWA-140 RangeBooster N Ad... | 52    | rt2800usb  | F98947BE5F |
| 2357:012d | TP-Link    | Archer T3U [Realtek RTL88... | 52    | 88x2bu     | 2D234EB9FB |
| 045e:02fe | Microsoft  | XBOX ACC                     | 51    | mt76x2u    | F36828F316 |
| 2357:0120 | TP-Link    | 802.11ac WLAN Adapter        | 51    | 88XXau     | 2B158EA18F |
| 045e:02e6 | Microsoft  | Wireless XBox Controller ... | 50    | mt76x2u    | 3F2F789273 |
| 2357:0108 | TP-Link    | TL-WN822N Version 4 RTL81... | 50    | rtl8xxxu   | 0F9BAA3F5F |
| 07d1:3c16 | D-Link ... | DWA-125 Wireless N 150 Ad... | 49    | rt2800usb  | F91A20DD51 |
| 2001:3c20 | D-Link     | 802.11 n WLAN                | 46    | rt2800usb  | D4B5BA9F4C |
| 0b05:1786 | ASUSTek... | USB-N10 802.11n Network A... | 44    | r8712u     | 5D0DF96501 |
| 0b05:184c | ASUSTek... | 802.11ac NIC                 | 44    | 88x2bu     | 8BF97B9982 |
| 1199:9041 | Sierra ... | EM7305 Modem                 | 44    | qcseria... | 08514D3FB0 |
| 2357:011f | TP-Link    | 802.11ac WLAN Adapter        | 44    | 88XXau     | B994C1917A |
| 03f0:581d | Hewlett... | lt4112 Gobi 4G Module Net... | 43    | qcserial   | E0068AE9B7 |
| 413c:81a3 | Dell       | Hub of E-Port Replicator     | 43    | qcserial   | C4842EDA94 |
| 0cf3:1006 | Qualcom... | TP-Link TL-WN322G v3 / TL... | 42    | ath9k_htc  | 03938B1FB9 |
| 148f:3072 | Ralink ... | RT3072 Wireless Adapter      | 41    | rt2800usb  | DFA6B5B067 |
| 1199:9011 | Sierra ... | MC8305 Modem                 | 39    | qcserial   | 8EC052BA75 |
| 15a9:0004 | Gemtek     | WUBR-177G [Ralink RT2571W]   | 39    | rt73usb    | E187B3F207 |
| 050d:845a | Belkin ... | F7D2101 802.11n Surf & Sh... | 38    | r8712u     | 7943FF718E |
| 07d1:3c03 | D-Link ... | AirPlus G DWL-G122 Wirele... | 38    | rt73usb    | 0E6DFE4E9B |
| 0e8d:7610 | MediaTek   | WiFi                         | 37    | mt76x0u    | 20EBDE2857 |
| 03f0:9d1d | Hewlett... | HP lt4120 Snapdragon X5 LTE  | 36    | cdc_ether  | 2502C3D7E7 |
| 0ace:1215 | ZyDAS      | ZD1211B 802.11g              | 35    | zd1211rw   | 10DB975AB9 |
| 0846:4260 | NetGear    | WG111v3 54 Mbps Wireless ... | 34    | rtl8187    | 9300FA16E1 |
| 0b05:17d1 | ASUSTek... | AC51 802.11a/b/g/n/ac Wir... | 34    | mt76x0u    | 4552FD3861 |
| 148f:2070 | Ralink ... | RT2070 Wireless Adapter      | 33    | rt2800usb  | F82BC00D23 |
| 0bda:8813 | Realtek... | RTL8814AU 802.11a/b/g/n/a... | 32    | 8814au     | 5AEDB75AD8 |
| 2357:010d | TP-Link    | Archer T4U v2 [Realtek RT... | 32    | 88XXau     | 483A93D1B5 |
| 07d1:3303 | D-Link ... | DWA-131 802.11n Wireless ... | 31    | r8712u     | 8989DF3C9D |
| 0bda:0179 | Realtek... | RTL8188ETV Wireless LAN 8... | 31    | r8188eu    | 5086217BA3 |
| 2001:3314 | D-Link     | DWA-171 AC600 DB Wireless... | 31    | rtl8812au  | 3991895525 |
| 7392:a812 | Edimax ... | AC600 USB                    | 31    | 88XXau     | 75BCA9816E |
| 2001:3c19 | D-Link     | DWA-125 Wireless N 150 Ad... | 30    | rt2800usb  | A1300B4529 |
| 07d1:3c07 | D-Link ... | DWA-110 Wireless G Adapte... | 29    | rt73usb    | 257090F010 |
| 0b05:179d | ASUSTek... | USB-N53 802.11abgn Networ... | 29    | rt2800usb  | D9A732F015 |
| 0846:9020 | NetGear    | WNA3100(v1) Wireless-N 30... | 28    |            | B5C18575BF |
| 0b05:17e8 | ASUSTek... | USB-N14 802.11b/g/n (2x2)... | 28    | rt2800usb  | 86E186908F |
| 148f:3572 | Ralink ... | RT3572 Wireless Adapter      | 27    | rt2800usb  | D32033DE5B |
| 2001:330f | D-Link     | DWA-125 11n Adapter          | 26    | r8188eu    | 2DDCBE8E2C |
| 413c:81b1 | Dell       | Wireless 5809e Gobi™ 4G... | 25    | qcserial   | 4A4F7AF190 |
| 07d1:3c0d | D-Link ... | DWA-125 Wireless N 150 Ad... | 24    | rt2800usb  | 43B7FFE89B |
| 2357:0101 | TP-Link    | RTL8812AU Archer T4U 802.... | 24    | 8812au     | 385C30D3A6 |
| 13b1:0020 | Linksys    | WUSB54GC v1 802.11g Adapt... | 23    | rt73usb    | CA151A6E5C |
| 13b1:003f | Linksys    | WUSB6300 802.11a/b/g/n/ac... | 23    | 8812au     | 60F6603B92 |
| 148f:2870 | Ralink ... | RT2870 Wireless Adapter      | 23    | rt2800usb  | 900011AD0C |
| 2001:3310 | D-Link     | DWA-123 Wireless N 150 Ad... | 23    | r8188eu    | D721904B6E |
| 2357:0105 | TP-Link    | Archer T1U 802.11a/n/ac W... | 23    | mt76x0u    | 1AE24AE582 |
| 7392:7711 | Edimax ... | EW-7711UTn nLite Wireless... | 23    | rt2800usb  | AB87264048 |
| 057c:8503 | AVM        | FRITZ!WLAN AC 860            | 22    | mt76x2u    | 0D7EFB17BC |
| 12d1:15bb | Huawei ... | ME936 LTE/HSDPA+ 4G modem    | 22    | option     | 241E2FC9BD |
| 050d:945a | Belkin ... | F7D1101 v1 Basic Wireless... | 21    | r8712u     | B68FE62039 |
| 0846:9001 | NetGear    | WN111(v2) RangeMax Next W... | 21    | carl9170   | 728347C38C |
| 13b1:0042 | Linksys    | WUSB6100M 802.11a/b/g/n/a... | 21    | ath10k_usb | 44A240B27D |
| 13d3:3247 | IMC Net... | AW-NU222 802.11bgn Wirele... | 21    | rt2800usb  | C554C3A77F |
| 0b05:17d2 | ASUSTek... | USB-AC56 802.11a/b/g/n/ac... | 20    | 8812au     | 1CF830ACD9 |
| 057c:8501 | AVM        | FRITZ WLAN N v2 [RT5572/r... | 19    | rt2800usb  | 78FC18FCF4 |
| 0846:9021 | NetGear    | WNA3100M(v1) Wireless-N 3... | 19    | rtl8192... | 1300EA6A53 |
| 0e8d:7612 | MediaTek   | MT7612U 802.11a/b/g/n/ac ... | 19    | mt76x2u    | EE3BD00385 |
| 13b1:003e | Linksys    | AE6000 802.11a/b/g/n/ac W... | 19    | mt76x0u    | F3E4767726 |

### Network (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0bda:8153 | Realtek... | RTL8153 Gigabit Ethernet ... | 1279  | r8152      | 08B1E4C99F |
| 04e8:6863 | Samsung... | Galaxy series, misc. (tet... | 382   | rndis_host | 2DECA4D871 |
| 2717:ff80 | Xiaomi     | Mi/Redmi series (RNDIS)      | 245   | rndis_host | FFBF3F551C |
| 0b95:1790 | ASIX El... | AX88179 Gigabit Ethernet     | 230   | ax88179... | 274B678E7A |
| 12d1:108a | Huawei ... | POT-LX1                      | 201   | rndis_host | FD79A580D8 |
| 04e8:6864 | Samsung... | GT-I9070 (network tetheri... | 172   | rndis_host | 820516F627 |
| 0bda:8152 | Realtek... | RTL8152 Fast Ethernet Ada... | 172   | r8152      | 1268E75895 |
| 0bda:b720 | Realtek... | RTL8723BU 802.11b/g/n WLA... | 166   | rtl8xxxu   | 8B10E96F42 |
| 12d1:14db | Huawei ... | E353/E3131                   | 148   | cdc_ether  | DF13F72A9A |
| 19d2:1405 | ZTE WCD... | USB SCSI CD-ROM              | 118   | cdc_ether  | 047EAD1D70 |
| 0e8d:2004 | MediaTek   | A80Pro                       | 113   | rndis_host | 25153D8586 |
| 22b8:2e24 | Motorol... | moto g stylus                | 85    | rndis_host | C694A13B5A |
| 2357:0601 | TP-Link    | UE300 10/100/1000 LAN (et... | 78    | r8152      | 3738CED25D |
| 1199:a001 | Sierra ... | EM7345 4G LTE                | 69    | cdc_mbim   | 8390E1030C |
| 0b95:772b | ASIX El... | AX88772B                     | 66    | asix       | 678542F4FE |
| 2cb7:0210 | Fibocom    | L830-EB-00 LTE WWAN Modem    | 65    | cdc_acm    | B571E885E2 |
| 05c6:f00e | Qualcomm   | Redmi Note 7                 | 54    | rndis_host | AF4E4E0E46 |
| 17e9:6006 | Display... | Dell Universal Dock D6000    | 49    | cdc_ncm    | F94CED9A41 |
| 0fe6:9700 | ICS Advent | DM9601 Fast Ethernet Adapter | 47    | dm9601,... | B7175ABF98 |
| 17ef:3082 | Lenovo     | ThinkPad TBT 3 Dock          | 47    | r8152      | 65666A7BEC |
| 17e9:4307 | Display... | LAPDOCK                      | 42    | cdc_ncm    | 1409E11B30 |
| 0424:ec00 | Standar... | Ethernet controller          | 39    | smsc95xx   | B21EF11378 |
| 0bb4:0003 | HTC (Hi... | MT65xx Android Phone         | 39    | rndis_host | 52E0E4C9A6 |
| 18d1:4ee3 | Google     | Nexus/Pixel Device (tether)  | 39    | rndis_host | C1183D6D2F |
| 22d9:276a | OPPO El... | RMX2193                      | 39    | rndis_host | 3B2CF29E19 |
| 0bda:c820 | Realtek... | 802.11ac NIC                 | 37    | btusb      | 045469EE83 |
| 17ef:a387 | Lenovo     | USB-C Dock Ethernet          | 35    | r8152      | 94F04E5543 |
| 04b3:4010 | IBM        | RNDIS/CDC ETHER              | 34    | cdc_ether  | 882EA8E25E |
| 2e04:c022 | HMD Global | Nokia 5.1                    | 34    | rndis_host | B7DC673E5C |
| 03f0:371d | Hewlett... | un2430 Mobile Broadband M... | 33    | qcserial   | 24758ED5B3 |
| 15a9:002d | Gemtek     | WLTUBA-107 [Yota 4G LTE]     | 33    | cdc_ether  | 359451A20F |
| 2a70:f00e | OnePlus... | OnePlus                      | 32    | rndis_host | 9C8B7BC48A |
| 05ac:12ab | Apple      | iPad 4/Mini1                 | 31    | ipheth     | F146C310D6 |
| 0b95:7720 | ASIX El... | AX88772                      | 31    | asix       | 63985D7619 |
| 17e9:436e | Display... | Dell D3100 Docking Station   | 28    | cdc_ncm    | D2E4A69C16 |
| 19d2:1365 | ZTE WCD... | Z6201V                       | 28    | rndis_host | BD1F26E401 |
| 1bbb:0174 | T & A M... | Alcatel 3X                   | 28    | rndis_host | F146C310D6 |
| 0b95:772a | ASIX El... | AX88772A Fast Ethernet       | 27    | asix       | F819AACC7A |
| 045e:07c6 | Microsoft  | RTL8153 GigE [Surface Eth... | 26    | r8152      | 3672EF87DE |
| 1004:6344 | LG Elec... | LM-X420xxx/G2 Android Pho... | 26    | rndis_h... | 4DA44461B8 |
| 0e8d:2005 | MediaTek   | Phh-Treble vanilla           | 25    | rndis_host | 2380C82B48 |
| 046b:ffb0 | America... | Virtual Ethernet             | 23    | cdc_ether  | 8EFAF14886 |
| 17ef:3069 | Lenovo     | ThinkPad TBT3 LAN            | 23    | r8152      | 988050AAA4 |
| 8087:0911 | Intel      | PRODUCT_MODEM                | 23    | cdc_mbim   | 129D1BDA9E |
| 17ef:3062 | Lenovo     | ThinkPad Dock Ethernet [R... | 22    | r8152      | 356AB18B7D |
| 0bda:1724 | Realtek... | RTL8723AU 802.11n WLAN Ad... | 21    | rtl8xxxu   | 43A9DC51D9 |
| 17e9:6000 | Display... | USB3.0 5K Graphic Docking    | 21    | snd_usb... | 1B59A580EA |
| 0424:7800 | Microch... | Ethernet controller          | 20    | lan78xx    | 21A6F78B88 |
| 1782:5d20 | Spreadt... | Spreadtrum Phone             | 20    | rndis_host | 9593642C34 |
| 17ef:a359 | Lenovo     | ThinkPad Lan                 | 20    | cdc_ether  | 69510C22F1 |
| 05c6:9024 | Qualcomm   | U693CL                       | 19    | rndis_host | F427B393E7 |
| 0b95:7e2b | ASIX El... | AX88772B Fast Ethernet Co... | 18    | asix       | C51E8E3296 |
| 1076:8002 | GCT Sem... | LU150 LTE Modem [Yota LU150] | 18    | rndis_host | 53874D702A |
| 216f:0043 | NTmore     | JMR814                       | 18    | cdc_ether  | AB60CEF23B |
| 05ac:1402 | Apple      | Ethernet Adapter [A1277]     | 17    | asix       | A06F0AF7CD |
| 0846:6a00 | NetGear    | WG111v2 54 Mbps Wireless ... | 17    | rtl8187    | 90714DE680 |
| 2001:4a00 | D-Link     | DUB-1312                     | 17    | ax88179... | 52667487D2 |
| 056a:0084 | Wacom      | ACK-40401 [Wireless Acces... | 16    | usbhid     | FAEA47290A |
| 0bb4:0004 | HTC (Hi... | 779                          | 16    | rndis_host | 44FE9BDC7D |
| 04b4:3610 | Cypress... | K38231_03                    | 14    | ax88179... | 31850CE796 |
| 0bda:b82c | Realtek... | 802.11ac NIC                 | 14    | btusb      | C694A13B5A |
| 1376:4e61 | Vimtron... | Mobile Composite Device Bus  | 14    | rndis_host | A1C356034E |
| 17e9:4302 | Display... | ThinkPad USB 3.0 Dock        | 14    | snd_usb... | E196E2BA5D |
| 2357:0602 | TP-LINK    | USB 10/100 LAN               | 14    | cdc_ether  | 178FF75AE6 |
| 0489:c022 | Foxconn... | Nokia 7 plus                 | 13    | rndis_host | BEC2435C15 |
| 0bb4:0ffe | HTC (Hi... | Desire HD (modem mode)       | 13    | rndis_host | 035B3CDC60 |
| 0bda:0823 | Realtek... | 802.11ac WLAN Adapter        | 12    | btusb      | 09CA813F06 |
| 2001:1a02 | D-Link     | DUB-E100 Fast Ethernet Ad... | 12    | asix       | 51178C1953 |
| 413c:a102 | Dell       | iDRAC Virtual NIC USB Device | 12    | cdc_ether  | B7AC531BF5 |
| 0846:68e1 | NetGear    | AirCard 810S                 | 11    | rndis_host | 49FF8D705B |
| 1004:61da | LG Elec... | G2 Android Phone [tetheri... | 11    | rndis_host | F91A752D4D |
| 17e9:4323 | Display... | Plugable UD-3900             | 11    | cdc_ncm    | F4DBE54638 |
| 17ef:7205 | Lenovo     | Thinkpad LAN                 | 11    | r8152      | F72E765EF0 |
| 17ef:7436 | Lenovo     | Android Phone                | 11    | rndis_host | 3412BF6285 |
| 17e9:4306 | Display... | Targus USB3.0 DV Docking ... | 10    | snd_usb... | B6BC261100 |
| 17ef:304f | Lenovo     | RTL8153 Gigabit Ethernet ... | 10    | r8152      | CBBDD343BD |
| 2cb7:0002 | Fibocom    | L831-EAU                     | 10    | cdc_acm    | BF254BE8F9 |
| 05ac:8233 | Apple      | T2 Controller                | 9     | cdc_ncm    | 2BDDF8B98A |
| 13b1:0041 | Linksys    | Gigabit Ethernet Adapter     | 9     | r8152      | 5002E43F11 |
| 03f0:026a | Hewlett... | L830-EB                      | 8     | cdc_acm    | D862548439 |
| 0a46:1269 | Davicom... | DM9621A USB To FastEther     | 8     | dm9601,... | B3D61C6FBD |
| 17e9:4305 | Display... | dynadock U3.0                | 8     | cdc_ncm    | ABFD9A1E11 |
| 05c6:9057 | Qualcomm   | MDM9207-MTP _SN:587E3F45     | 7     | rndis_host | E99E0681D1 |
| 0bda:8150 | Realtek... | RTL8150 Fast Ethernet Ada... | 7     | rtl8150    | 0FF0A247D9 |
| 12d1:1050 | Huawei ... | Android Phone                | 7     | rndis_host | 1DA678C883 |
| 12d1:260d | Huawei ... | TIT-L01                      | 7     | rndis_host | 85F0F44820 |
| 15a9:003e | Gemtek     | Yota Many                    | 7     | rndis_host | F48E23AB6A |
| 9710:7830 | MosChip... | MCS7830 10/100 Mbps Ether... | 7     | mcs7830    | E26F3C0F44 |
| 045e:091e | Microsoft  | XBOX ACC                     | 6     |            | BAA04FAF58 |
| 04d9:a119 | Holtek ... | OSA Express Network card     | 6     | usbhid     | 7C7D911163 |
| 0b05:5f04 | ASUSTek... | Android                      | 6     | rndis_host | 43E4578544 |
| 0fca:8017 | Researc... | BlackBerry                   | 6     | cdc_ncm    | BC53AD8072 |
| 12d1:1c50 | Huawei ... | MOBILE                       | 6     | cdc_ether  | 1511A3D0D3 |
| 1bbb:2026 | T & A M... | ALCATEL ONE TOUCH POP C1     | 6     | cdc_eem    | 8CF1F80E50 |
| 0424:7500 | Microch... | LAN7500 Ethernet 10/100/1... | 5     | smsc75xx   | 70A4BD00B9 |
| 0525:a4a2 | Netchip... | Linux-USB Ethernet/RNDIS ... | 5     | cdc_subset | 9005441938 |
| 0b05:5602 | ASUSTek... | Android                      | 5     | rndis_host | 380140EB8D |
| 0b95:1780 | ASIX El... | AX88178                      | 5     | asix       | CB5FCEB934 |
| 17ef:720c | Lenovo     | USB-C to LAN                 | 5     | r8152      | 349F951788 |
| 19d2:1373 | ZTE WCD... | ZTE USB Device               | 5     | rndis_host | D9E3975F83 |

### Phone (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0e8d:2008 | MediaTek   | Cyrus Technology CS 24       | 83    | usbfs      | DCDFADB154 |
| 18d1:4ee1 | Google     | Nexus/Pixel Device (MTP)     | 61    | usbfs      | 4A568F856E |
| 1004:631c | LG Elec... | G2/Optimus Android Phone ... | 36    | usbfs      | 8672754924 |
| 2717:ff48 | Xiaomi     | Mi/Redmi series (MTP + ADB)  | 35    | usbfs      | B14B138347 |
| 0e8d:201d | MediaTek   | G9 PRO                       | 22    | usbfs      | B94F89A70A |
| 1bbb:0168 | T & A M... | A502DL                       | 22    | usbfs      | B2217103B4 |
| 04e8:685d | Samsung... | GT-I9100 Phone [Galaxy S ... | 15    | cdc_acm    | 67F3ED34B8 |
| 1004:6300 | LG Elec... | G2/Optimus Android Phone ... | 11    | usbhid     | CEFBA84AE8 |
| 0bb4:0c02 | HTC (Hi... | Dream / ADP1 / G1 / Magic... | 9     | usbfs      | BFBFDE5C37 |
| 05c6:f003 | Qualcomm   | Nokia 8110 4G                | 8     | usbfs      | 4ED02BF7A2 |
| 19d2:0306 | ZTE WCD... | ZTE USB Device               | 8     | usbfs      | D95EE27C85 |
| 19d2:0307 | ZTE WCD... | Platy                        | 8     | usbfs      | FA18FC0356 |
| 2a45:2008 | Meizu      | MX Phone (MTP)               | 8     | usbfs      | BCF1D99475 |
| 0bb4:2008 | HTC (Hi... | Android Phone via MTP [Wi... | 6     |            | 52ECA6CE50 |
| 1782:4001 | Spreadt... | Spreadtrum Phone             | 5     | usbfs      | 1695DC11BA |
| 05c6:9092 | Qualcomm   | Android                      | 4     |            | 0A09D00B74 |
| 0fce:01c4 | Sony Er... | Android                      | 4     | usbfs      | 6C0BF83741 |
| 17ef:7497 | Lenovo     | A789 (MTP mode)              | 4     |            | B60CD6FFC3 |
| 1bbb:0167 | T & A M... | 5049Z                        | 4     | usbfs      | FB5F956CA2 |
| 045e:04ec | Microsoft  | Windows Phone (Zune)         | 3     | usbfs      | 587BECD063 |
| 04e8:685c | Samsung... | GT-I9250 Phone [Galaxy Ne... | 3     | usbfs      | FB1CD7BF88 |
| 0bb4:0c01 | HTC (Hi... | Dream / ADP1 / G1 / Magic... | 3     |            | 1E4ACB4F55 |
| 0bb4:0f0b | HTC (Hi... | U11                          | 3     | usbhid     | ED4126EB39 |
| 0bb4:0f87 | HTC (Hi... | Android Phone                | 3     | usbfs      | 541E753F9D |
| 0bb4:f006 | HTC (Hi... | Android Phone                | 3     | usbhid     | 5902EF81CA |
| 1004:633a | LG Elec... | Ultimate 2 Android Phone ... | 3     | cdc_acm    | 9F3D5A596E |
| 2717:1240 | Xiaomi     | HM1 Android Phone            | 3     |            | 01AA74496F |
| 2916:f003 | Android    | Android                      | 3     | usbfs      | 5595625922 |
| 0471:2008 | Philips... | W732                         | 2     |            | D315AFD57C |
| 0bb4:0402 | HTC (Hi... | Android Phone                | 2     | rndis_host | EBBD83B0CA |
| 0bb4:0c81 | HTC (Hi... | Android Phone                | 2     |            | 404A8B3A68 |
| 0fce:0189 | Sony Er... | C6503                        | 2     |            | 97D00825B7 |
| 0fce:019b | Sony Er... | Android                      | 2     |            | 49389100FC |
| 0fce:01b5 | Sony Er... | D2105                        | 2     |            | 165BEE2B5C |
| 0fce:51ad | Sony Er... | Android                      | 2     |            | 41B2D085B5 |
| 1004:61fc | LG Elec... | Optimus 3                    | 2     | cdc_acm... | 1EBB6C2E61 |
| 1004:61fe | LG Elec... | Optimus Android Phone [US... | 2     | cdc_ether  | C56F89B8EB |
| 1782:4012 | Spreadt... | RIO_ZAM                      | 2     |            | 83DBEAD899 |
| 17ef:74f8 | Lenovo     | MT65xx Android Phone         | 2     |            | B89D04A41B |
| 1bbb:2008 | T & A M... | MT65xx Android Phone         | 2     | usbfs      | E48E425669 |
| 2a45:0c02 | Meizu      | MX Phone (MTP & ADB)         | 2     | usbfs      | 1C28AB7987 |
| 0414:0c02 | Giga-By... | MT65xx Android Phone         | 1     | usbfs      | 755B9B413C |
| 0421:002f | Nokia M... | 6120 Phone (PC-Suite mode)   | 1     | cdc_acm... | 408A3116F5 |
| 0471:0003 | Philips... | Android Phone                | 1     | rndis_host | 5F5A42CFCD |
| 0b05:5490 | ASUSTek... | Android                      | 1     |            | 196E542A2B |
| 0b05:551f | ASUSTek... | Android                      | 1     | usbfs      | E1C6C1D0DB |
| 0bb4:0df8 | HTC (Hi... | Android Phone                | 1     |            | F4F1952C9C |
| 0bb4:0e32 | HTC (Hi... | Android Phone                | 1     | usbfs      | A131EB3789 |
| 0bb4:0fa2 | HTC (Hi... | Android Phone                | 1     | usbfs      | 5A59F3A3B4 |
| 0fce:0197 | Sony Er... | C5502                        | 1     |            | 9C65E049FE |
| 0fce:5195 | Sony Er... | C5303                        | 1     |            | 481DCFBCF9 |
| 1527:0200 | Silicon... | YAP Phone (no firmware)      | 1     |            | D857FD97FD |
| 1532:9051 | Razer USA  | Razer Phone 2                | 1     |            | 46CD15B9A7 |
| 1532:9052 | Razer USA  | Razer Phone                  | 1     | usbfs      | 80767A5816 |
| 17ef:0c02 | Lenovo     | MT65xx Android Phone         | 1     | usbfs      | B776DA24C5 |
| 17ef:79a1 | Lenovo     | MT65xx Android Phone         | 1     |            | 9271AE1167 |
| 19d2:0260 | ZTE WCD... | File-CD Gadget               | 1     | uas, us... | 522AEE0B0B |
| 19d2:0343 | ZTE WCD... | V985                         | 1     |            | 4215162CA5 |
| 22b8:2e71 | Motorol... | Motorola Phone               | 1     | usbhid     | B8DA2787DA |
| 2922:0003 | MediaTek   | MT65xx Android Phone         | 1     | rndis_host | 7B88CC04C1 |

### Printer (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:2b17 | Hewlett... | LaserJet 1020                | 100   | usblp      | C2EEEA4334 |
| 03f0:4117 | Hewlett... | LaserJet 1018                | 64    | usblp      | B4A3EDE65B |
| 067b:2305 | Prolifi... | PL2305 Parallel Port         | 57    | usblp      | 1C45DC94EC |
| 03f0:002a | Hewlett... | LaserJet P1102               | 56    | usblp      | F900105A8A |
| 04e8:341b | Samsung... | SCX-4200 series              | 56    | usblp      | 1096F1F298 |
| 04e8:3321 | Samsung... | M2020 Series                 | 47    | usblp      | A85B460D7A |
| 04a9:2676 | Canon      | LBP2900                      | 43    | usblp      | 17EC413352 |
| 03f0:0053 | Hewlett... | DeskJet 2620 All-in-One P... | 42    | usblp      | 9B6328F4F9 |
| 04a9:176d | Canon      | PIXMA MG2500 Series          | 42    | usblp      | 5225757C73 |
| 04e8:344f | Samsung... | SCX-3400 Series              | 41    | usblp      | F90BD49F70 |
| 03f0:e111 | Hewlett... | DeskJet 2130 series          | 40    | usblp      | 13ED4A7523 |
| 04e8:3469 | Samsung... | M2070 Series                 | 38    | usblp      | BA92E877C3 |
| 03f0:3d17 | Hewlett... | LaserJet P1005               | 34    | usblp      | 84A4C5E5E0 |
| 03f0:d711 | Hewlett... | ENVY 4520 series             | 34    | usblp      | 9A3C939249 |
| 04f9:0027 | Brother... | HL-2030 Laser Printer        | 33    | usblp      | A5CA2582B6 |
| 03f0:0c17 | Hewlett... | LaserJet 1010                | 31    | usblp      | 14EB0D132D |
| 04e8:3292 | Samsung... | ML-1640 Series Laser Printer | 30    | usblp      | 3D5408FB8A |
| 04e8:3441 | Samsung... | SCX-3200 Series              | 29    | usblp      | F8FDB6F4B3 |
| 03f0:c211 | Hewlett... | Deskjet 2540 series          | 27    | usblp      | D629981B18 |
| 04a9:10dc | Canon      | iP7200 series                | 27    | usblp      | E4CBF06036 |
| 04da:0f0b | Panason... | KX-MB1500CX                  | 27    | usblp      | 82DD7F530A |
| 03f0:e311 | Hewlett... | DeskJet 3630 series          | 26    | usblp      | 08B08DC8D9 |
| 04a9:2759 | Canon      | MF3010                       | 26    | usblp      | FCBB29A9CF |
| 04b8:0007 | Seiko E... | Printer                      | 26    | usblp      | A6862C2A01 |
| 04b8:002a | Seiko E... | USB2.0 Printer (Hi-speed)    | 26    | usblp      | 23DDB098D4 |
| 03f0:8711 | Hewlett... | Deskjet 2050 J510            | 24    | usblp      | 279A4A99FD |
| 04a9:2737 | Canon      | MF4410                       | 24    | usblp      | CE4078A2FB |
| 04b8:0005 | Seiko E... | Printer                      | 24    | usblp      | E40DF63078 |
| 1a86:7584 | QinHeng... | CH340S                       | 24    | usblp      | F91F457178 |
| 04f9:0054 | Brother... | HL-1110 series               | 23    | usblp      | D558C3E02D |
| 04b8:08a1 | Seiko E... | L210 Series                  | 22    | usblp      | 5C07C319BD |
| 04a9:176b | Canon      | PIXMA MX920 Series           | 21    | usblp      | 2CCB22546D |
| 03f0:1d17 | Hewlett... | LaserJet 1320                | 20    | usblp      | DD50FE59B2 |
| 03f0:2504 | Hewlett... | DeskJet F4200 series         | 20    | usblp      | 60E5407954 |
| 03f0:2c17 | Hewlett... | LaserJet 1022                | 20    | usblp      | B233D9D079 |
| 03f0:8911 | Hewlett... | Deskjet 1050 J410            | 20    | usblp      | 5EF628DEE8 |
| 04e8:330f | Samsung... | ML-216x Series Laser Printer | 20    | usblp      | 33BB3C3B9A |
| 03f0:032a | Hewlett... | Smart Install                | 19    | usblp      | 44A240B27D |
| 03f0:0317 | Hewlett... | LaserJet 1200                | 18    | usblp      | 365DA127D4 |
| 03f0:102a | Hewlett... | LaserJet Professional P 1... | 18    | usblp      | 08C5AC3A58 |
| 03f0:3217 | Hewlett... | LaserJet 3050                | 18    | usblp      | 58F942E8C3 |
| 04a9:26b4 | Canon      | MF4010 series                | 18    | usblp      | C150B69C69 |
| 04a9:271a | Canon      | LBP6000                      | 18    | usblp      | FB2438D378 |
| 04b8:08d1 | Seiko E... | L360 Series                  | 18    | usblp      | 46B6080608 |
| 03f0:2d12 | Hewlett... | Officejet 4500 G510g-m       | 17    | usblp      | 7CCF096E4A |
| 03f0:3e17 | Hewlett... | LaserJet P1006               | 17    | usblp      | 1112AC9EC4 |
| 04e8:3301 | Samsung... | ML-1660 Series               | 17    | usblp      | 926229BE87 |
| 04f9:003f | Brother... | HL-2130 series               | 17    | usblp      | 08BA06F7F2 |
| 04a9:178a | Canon      | PIXMA MG3600 Series          | 16    | usblp      | 1D31D72736 |
| 04a9:26da | Canon      | LBP3010/LBP3018/LBP3050      | 16    | usblp      | 90068E84DB |
| 03f0:1017 | Hewlett... | LaserJet 1300                | 15    | usblp      | 66228CE4DF |
| 03f0:7611 | Hewlett... | DeskJet F2492 All-in-One     | 15    | usblp      | 3F9B2942E1 |
| 03f0:7d04 | Hewlett... | DeskJet F2100 Printer series | 15    | usblp      | 30B02CF768 |
| 03f0:9311 | Hewlett... | Deskjet 3050 J610 series     | 15    | usblp      | 9656967D59 |
| 03f0:b011 | Hewlett... | Deskjet 3520 series          | 15    | usblp      | 1112AC9EC4 |
| 03f0:e511 | Hewlett... | OfficeJet 3830 series        | 15    | usblp      | FF7E2B9FFD |
| 04a9:176c | Canon      | MG2400 series                | 15    | usblp      | 74AABB5491 |
| 04a9:1913 | Canon      | LiDE 300                     | 15    | usbfs      | 5DB737F928 |
| 04a9:260a | Canon      | LBP810                       | 15    | usblp      | 084ADFB723 |
| 04e8:300c | Samsung... | ML-1210 Printer              | 15    | usblp      | E1CA7E719A |
| 04e8:326c | Samsung... | ML-2010P Mono Laser Printer  | 15    | usblp      | 07E689FBD8 |
| 04e8:3413 | Samsung... | SCX-4100 Scanner             | 15    | usblp      | D5C06DEA29 |
| 03f0:0517 | Hewlett... | LaserJet 1000                | 14    | usblp      | 85B282F128 |
| 03f0:7e04 | Hewlett... | DeskJet F4100 Printer series | 14    | usblp      | AD37DB1DA8 |
| 03f0:c111 | Hewlett... | Deskjet 1510                 | 14    | usblp      | 35167A79E9 |
| 04a9:173a | Canon      | PIXMA MP250                  | 14    | usblp      | 11B9953715 |
| 04a9:1746 | Canon      | PIXMA MP280                  | 14    | usblp      | 369547D653 |
| 04a9:262b | Canon      | LaserShot LBP-1120 Printer   | 14    | usblp      | A6D2710163 |
| 04b8:005e | Seiko E... | L120 Series                  | 14    | usblp      | 52C3D1A9ED |
| 04b8:08a8 | Seiko E... | L355 Series                  | 14    | usblp      | B9B6A8F15A |
| 03f0:3817 | Hewlett... | LaserJet P2015 series        | 13    | usblp      | 8670420E76 |
| 04a9:2771 | Canon      | CAPT USB Device              | 13    | usblp      | A1701CB21F |
| 04b8:1122 | Seiko E... | L395 Series                  | 13    | usblp      | 20D4A3A8F9 |
| 04b8:1143 | Seiko E... | L3150 Series                 | 13    | usblp      | EE9233BE38 |
| 04e8:342e | Samsung... | SCX-4300 Series              | 13    | usblp      | 1CFD75328B |
| 03f0:0853 | Hewlett... | ENVY 5000 series             | 12    | usblp      | 6C6D145AD3 |
| 03f0:0953 | Hewlett... | OfficeJet 5200 series        | 12    | usblp      | F79C155FD8 |
| 03f0:5511 | Hewlett... | DeskJet F300 series          | 12    | usblp      | E81CD8C462 |
| 04a9:1827 | Canon      | TS3100 series                | 12    | usblp      | DCD72D6F14 |
| 04b8:0883 | Seiko E... | ME 340 Series/Stylus NX13... | 12    | usblp      | 8532A53B66 |
| 04b8:08d2 | Seiko E... | L365 Series                  | 12    | usblp      | B0A0929002 |
| 04f9:02d0 | Brother... | DCP-1510                     | 12    | usblp      | A242AAE8F0 |
| 03f0:0653 | Hewlett... | DeskJet 3700 series          | 11    | usbfs      | 070E212C9B |
| 03f0:0f54 | Hewlett... | OfficeJet 6950               | 11    | usblp      | 344858AD94 |
| 03f0:c511 | Hewlett... | ENVY 4500 series             | 11    | usblp      | 50BC7903F2 |
| 04a9:2684 | Canon      | MF3200 series                | 11    | usblp      | 5F5AC3A0C4 |
| 04f9:0062 | Brother... | HL-L2320D series             | 11    | usblp      | 7DD3179FEA |
| 04f9:0063 | Brother... | HL-L2340D series             | 11    | usblp      | 3EA9D90A4B |
| 0924:3cf4 | Xerox      | Phaser 3140 and 3155         | 11    | usblp      | 51511E4FC9 |
| 03f0:0d17 | Hewlett... | LaserJet 1012                | 10    | usblp      | C2DACE7DD3 |
| 03f0:612a | Hewlett... | LaserJet M101-M106           | 10    | usblp      | F568952B1D |
| 03f0:8c11 | Hewlett... | Deskjet F4500 series         | 10    | usblp      | 53F89BE1B8 |
| 04a9:10d3 | Canon      | iP2700 series                | 10    | usblp      | 838A34D93C |
| 04b8:1116 | Seiko E... | XP-243 245 247 Series        | 10    | usblp      | C1932872E1 |
| 04e8:330c | Samsung... | ML-1865                      | 10    | usblp      | 2A4031F16A |
| 04e8:347e | Samsung... | C48x Series Color Laser M... | 10    | usblp      | E7262E0201 |
| 04f9:0042 | Brother... | HL-2270DW Laser Printer      | 10    | usblp      | A9FC556262 |
| 04f9:0273 | Brother... | DCP-7057 scanner/printer     | 10    | usblp      | 9DE8B7DAF5 |
| 03f0:5c17 | Hewlett... | LaserJet P2055 series        | 9     | usblp      | 1832B82582 |
| 03f0:a011 | Hewlett... | Deskjet 3050A                | 9     | usblp      | 3D2C0CAAAF |

### Scanner (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04a9:1909 | Canon      | CanoScan LiDE 110            | 83    | usbfs      | 7FB5F68146 |
| 04a9:2220 | Canon      | CanoScan LIDE 25             | 63    | usbfs      | 92D06972E9 |
| 04a9:190a | Canon      | CanoScan LiDE 210            | 52    |            | 600E1A606B |
| 04a9:220d | Canon      | CanoScan N670U/N676U/LiDE 20 | 50    |            | 7CA350189C |
| 04a9:190f | Canon      | CanoScan LiDE 220            | 34    | usbfs      | 0E6DFE4E9B |
| 03f0:0a01 | Hewlett... | ScanJet 2400c                | 32    | usbfs      | FD882239BD |
| 04a9:190e | Canon      | CanoScan LiDE 120            | 32    | usbfs      | E4CBF06036 |
| 04b8:0142 | Seiko E... | GT-F730 [GT-S630/Perfecti... | 24    |            | D0FD1CE0E8 |
| 05d8:4002 | Ultima ... | Artec Ultima 2000 (GT6801... | 23    | usbfs      | D2E63CFAA6 |
| 04a9:1904 | Canon      | CanoScan LiDE 100            | 22    |            | 324DF6EB69 |
| 04b8:0121 | Seiko E... | GT-F500/GT-F550 [Perfecti... | 20    |            | C81D067D76 |
| 04a9:220e | Canon      | CanoScan N1240U/LiDE 30      | 18    |            | 9072EDAEEF |
| 04a9:221c | Canon      | CanoScan LiDE 60             | 16    |            | 1EA8028ECB |
| 04b8:0122 | Seiko E... | GT-F520/GT-F570 [Perfecti... | 15    | usbfs      | 4ED3CD9A74 |
| 04b8:012d | Seiko E... | GT-F650 [GT-S600/Perfecti... | 15    |            | DECA40F736 |
| 055f:021b | Mustek ... | BearPaw 1200 CU Plus         | 14    | usbfs      | 9FAA6E8AF8 |
| 04a9:1907 | Canon      | CanoScan LiDE 700F           | 13    | usbfs      | AF24409637 |
| 04a9:2213 | Canon      | CanoScan LiDE 50/LiDE 35/... | 13    |            | D03C007DEB |
| 04b8:0120 | Seiko E... | GT-7400U [Perfection 1270]   | 13    |            | 2FCE3F9ABF |
| 04b8:011f | Seiko E... | GT-8400UF [Perfection 167... | 12    |            | 94A6B9B7F8 |
| 04b8:0130 | Seiko E... | GT-X770 [Perfection V500]    | 11    |            | 68732ECD4B |
| 055f:021f | Mustek ... | SNAPSCAN e22                 | 11    |            | 23B6389BB5 |
| 04b8:013a | Seiko E... | GT-X820 [Perfection V600 ... | 10    |            | C4F732FEF3 |
| 04a9:1905 | Canon      | CanoScan LiDE 200            | 9     |            | DA7DC5E5B9 |
| 03f0:1c05 | Hewlett... | Scanjet 200                  | 8     |            | FEBB5AEE31 |
| 03f0:2605 | Hewlett... | ScanJet 3800c                | 8     |            | 4005AC4804 |
| 04b8:0119 | Seiko E... | GT-X750 [Perfection 4490 ... | 8     |            | 0CEDF0F08E |
| 04b8:011b | Seiko E... | GT-9300UF [Perfection 240... | 8     |            | E57BC458E3 |
| 04b8:012e | Seiko E... | GT-F670 [Perfection V200 ... | 8     |            | 9EA64D6592 |
| 04b8:013b | Seiko E... | Scanner                      | 8     |            | 697E2F24F0 |
| 055f:021d | Mustek ... | BearPaw 2400 CU Plus         | 8     |            | A5CA2582B6 |
| 03f0:1705 | Hewlett... | ScanJet 5590                 | 7     |            | D1ECE8006F |
| 04a9:1900 | Canon      | CanoScan LiDE 90             | 7     |            | E1B742D511 |
| 04a9:2206 | Canon      | CanoScan N650U/N656U         | 7     |            | D805D39715 |
| 04a9:2228 | Canon      | CanoScan 4400F               | 7     |            | 0767C99ABB |
| 04b8:0131 | Seiko E... | GT-F720 [GT-S620/Perfecti... | 7     |            | 3AB07FF020 |
| 055f:0006 | Mustek ... | ScanExpress 1200 UB          | 7     |            | ADF9EBB679 |
| 055f:021c | Mustek ... | BearPaw 1200 CU Plus         | 7     | usbfs      | 74E1239BF6 |
| 04a9:2224 | Canon      | CanoScan LiDE 600F           | 6     |            | 76815350FC |
| 04a9:2225 | Canon      | CanoScan LiDE 70             | 6     |            | 65A39DDC43 |
| 04b8:010f | Seiko E... | GT-7200U [Perfection 1250... | 6     |            | 799AD15D8B |
| 03f0:0405 | Hewlett... | ScanJet 3400cse              | 5     | usbfs      | 18837F1515 |
| 03f0:0805 | Hewlett... | HP4470C                      | 5     |            | 5600070A23 |
| 03f0:0b01 | Hewlett... | ScanJet 82x0C                | 5     | usbfs      | 85121B8AEC |
| 03f0:1d05 | Hewlett... | Scanjet 300                  | 5     |            | 953BA0670D |
| 03f0:2305 | Hewlett... | ScanJet 3970c                | 5     |            | 7CE74DB09A |
| 03f0:2f11 | Hewlett... | PSC 1200                     | 5     | usblp      | 9BD4224188 |
| 04a9:1908 | Canon      | CanoScan                     | 5     | usbfs      | E94076C272 |
| 04a9:221b | Canon      | CanoScan 4200F               | 5     |            | C6097BDDA4 |
| 04b8:0114 | Seiko E... | Perfection 660               | 5     |            | 72B40A39D4 |
| 04b8:011d | Seiko E... | GT-7300U [Perfection 1260... | 5     |            | 7725DDAF99 |
| 04b8:012a | Seiko E... | GT-X800 [Perfection 4990 ... | 5     | usbfs      | 76FFF4BB1C |
| 055f:021a | Mustek ... | BearPaw 2448 TA Plus         | 5     |            | EF1C9E227C |
| 03f0:0605 | Hewlett... | ScanJet 2200c                | 4     |            | ED0B1EA0A5 |
| 03f0:0701 | Hewlett... | ScanJet 5300c/5370c          | 4     |            | F9375B6948 |
| 03f0:1405 | Hewlett... | ScanJet 3670                 | 4     |            | 7E4D284284 |
| 03f0:2005 | Hewlett... | ScanJet 3570c                | 4     |            | 820146D4E8 |
| 04a5:20b0 | Acer Pe... | S2W 3300U/4300U              | 4     |            | 2A42DEB5A5 |
| 04a5:2311 | Acer Pe... | Benq 5560                    | 4     |            | 25B7198C11 |
| 04a9:190d | Canon      | CanoScan 9000F Mark II       | 4     |            | DBBA1BCF47 |
| 04a9:221f | Canon      | CanoScan LiDE 500F           | 4     |            | 18E30A3F69 |
| 04b8:012f | Seiko E... | GT-F700 [Perfection V350]    | 4     |            | 9506DFA1DB |
| 055f:0408 | Mustek ... | BearPaw 2448 CU Pro          | 4     |            | D29669E299 |
| 03f0:0305 | Hewlett... | ScanJet 4300c                | 3     | usbfs      | F519F06748 |
| 03f0:2205 | Hewlett... | ScanJet 3500c                | 3     |            | 126B5ADE99 |
| 03f0:2505 | Hewlett... | ScanJet 3770                 | 3     |            | 87E50471AE |
| 03f0:4205 | Hewlett... | ScanJet G3010                | 3     |            | A9E90B12DC |
| 03f0:4505 | Hewlett... | ScanJet G4010                | 3     |            | 8BD33FA616 |
| 03f0:4605 | Hewlett... | ScanJet G4050                | 3     |            | 0AE817BCE9 |
| 0458:2014 | KYE Sys... | ColorPage-Vivid4             | 3     |            | 6F51B530BD |
| 04a5:20f8 | Acer Pe... | Benq 5000                    | 3     |            | 78F2C3136C |
| 04a5:2137 | Acer Pe... | Benq 5150/5250               | 3     |            | 2D25B17958 |
| 04b8:0110 | Seiko E... | GT-8200U/GT-8200UF [Perfe... | 3     |            | 3796A94A31 |
| 04b8:0112 | Seiko E... | GT-9700F [Perfection 2450... | 3     |            | BD34C715B3 |
| 04b8:011c | Seiko E... | GT-9800F [Perfection 3200]   | 3     |            | 1F57F19AFF |
| 04b8:012c | Seiko E... | GT-X900 [Perfection V700/... | 3     |            | 674668F4DD |
| 055f:0219 | Mustek ... | BearPaw 2400 TA Plus         | 3     |            | 49BA2B0298 |
| 06bd:2091 | AGFA-Ge... | SnapScan e20                 | 3     |            | AF794C7302 |
| 03f0:0205 | Hewlett... | ScanJet 3300c                | 2     |            | CD5BCE9449 |
| 03f0:0601 | Hewlett... | ScanJet 6300c                | 2     |            | 2047255023 |
| 03f0:0901 | Hewlett... | ScanJet 2300c                | 2     |            | 09D469F1FC |
| 03f0:1205 | Hewlett... | ScanJet 4500C/5550C          | 2     |            | 093D03CAF5 |
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
| 04b8:010a | Seiko E... | GT-8700/GT-8700F [Perfect... | 2     |            | 688B4A3AE6 |
| 04b8:010b | Seiko E... | GT-7700U [Perfection 1240U]  | 2     |            | F0606E05AC |
| 04b8:0118 | Seiko E... | GT-F600 [Perfection 4180]    | 2     | usbfs      | F55F5434E6 |
| 04b8:0802 | Seiko E... | CC-570L [Stylus CX3100/CX... | 2     | usblp      | 60F50C0B8A |
| 04c5:128e | Fujitsu    | ScanSnap SV600               | 2     | usbfs      | 3C409E3FAC |
| 055f:0001 | Mustek ... | ScanExpress 1200 CU          | 2     |            | 84CB4DED95 |
| 055f:0008 | Mustek ... | ScanExpress 1200 CU Plus     | 2     |            | 03853132A4 |
| 055f:021e | Mustek ... | BearPaw 1200 TA/CS           | 2     |            | 7FC17D0078 |

### Serial controller (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0403:6001 | Future ... | FT232 Serial (UART) IC       | 221   | ftdi_sio   | 73ECE6C322 |
| 1a86:7523 | QinHeng... | CH340 serial converter       | 208   | ch341      | DFAE1B630A |
| 067b:2303 | Prolifi... | PL2303 Serial Port / Mobi... | 175   | pl2303     | DBFEAB0BB4 |
| 10c4:ea60 | Cygnal ... | CP2102/CP2109 UART Bridge... | 133   | cp210x     | 74DE7E2ACF |
| 05c6:9204 | Qualcomm   | Gobi 2000                    | 76    | qcserial   | 5DC4A1E557 |
| 03f0:521d | Hewlett... | hs3110 HSPA+ Mobile Broad... | 51    | option     | D741C065BC |
| 03f0:241d | Hewlett... | Gobi 2000 Wireless Modem ... | 39    | qcserial   | 86286FAD9C |
| 1199:9013 | Sierra ... | Sierra Wireless Gobi 3000... | 36    | qcserial   | F4FD2617FD |
| 12d1:15c1 | Huawei ... | ME906s LTE M.2 Module        | 33    | option     | FF72A34439 |
| 0451:3410 | Texas I... | TUSB3410 Microcontroller     | 32    | ti_usb_... | FC7A590412 |
| 2c7c:0125 | Quectel... | EC25 LTE modem               | 26    | qmi_wwan   | 5FE3179524 |
| 03f0:a31d | Hewlett... | lt4132 LTE/HSPA+ 4G Module   | 25    | option     | 51178C1953 |
| 0403:6015 | Future ... | Bridge(I2C/SPI/UART/FIFO)    | 24    | ftdi_sio   | 5F8BFD5FBF |
| 19d2:0016 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 24    | option     | EB04CF12AA |
| 0403:6010 | Future ... | FT2232C/D/H Dual UART/FIF... | 22    | ftdi_sio   | F0473D3564 |
| 1b1c:1c00 | Corsair    | Controller for Corsair Link  | 21    | cp210x     | 9F52D4AAEF |
| 1199:9000 | Sierra ... | Gobi 2000 Wireless Modem ... | 18    | qcserial   | 8E6CE923E0 |
| 03f0:201d | Hewlett... | un2400 Gobi Wireless Mode... | 17    | qcserial   | 9028097D4D |
| 19d2:2003 | ZTE WCD... | ZTE WCDMA Technologies MSM   | 13    | option     | F125F4CD03 |
| 413c:8185 | Dell       | Gobi 2000 Wireless Modem ... | 13    | qcserial   | E291D505C4 |
| 0403:6014 | Future ... | FT232H Single HS USB-UART... | 12    | ftdi_sio   | 79FA3F7509 |
| 0d9f:0002 | Powercom   | Black Knight PRO / WOW Un... | 12    | cypress... | 507FB1F456 |
| 0fcf:1008 | Dynastr... | ANTUSB2 Stick                | 12    | usb_ser... | E6BC960206 |
| 0fcf:1009 | Dynastr... | ANTUSB-m Stick               | 11    | usb_ser... | A37048B876 |
| 05c6:9224 | Qualcomm   | Sony Gobi 2000 Wireless M... | 10    | qcserial   | 5682D68364 |
| 0557:2008 | ATEN In... | UC-232A Serial Port [pl2303] | 9     | pl2303     | 55CFAAEE1B |
| 0af0:6901 | Option     | Globetrotter HSDPA Modem     | 9     | option     | B91A419A64 |
| 1199:683c | Sierra ... | Mobile Broadband 3G/UMTS ... | 8     | sierra     | 6A8AC552FE |
| 03f0:1e1d | Hewlett... | hs2300 HSDPA Broadband Wi... | 7     | sierra     | 7E17CF2706 |
| 0403:6011 | Future ... | FT4232H Quad HS USB-UART/... | 7     | ftdi_sio   | B364724E53 |
| 04b4:5500 | Cypress... | HID->COM RS232 Adapter       | 7     | cypress... | 35C5A59DB3 |
| 057c:6201 | AVM        | AVM Fritz!WLAN v1.1 [Texa... | 7     | option     | 3C0A297EDE |
| 05c6:9008 | Qualcomm   | Gobi Wireless Modem (QDL ... | 7     | qcserial   | 08388CCB27 |
| 10c4:ea70 | Silicon... | CP2105 Dual UART Bridge      | 7     | cp210x     | A85DC8D30D |
| 1199:6832 | Sierra ... | MC8780 Device                | 7     | sierra     | 3B7266D323 |
| 1199:6813 | Sierra ... | Mini Card                    | 5     | sierra     | 56D9CF2086 |
| 1410:2420 | Novatel... | Expedite EU850D/EU860D/EU... | 5     | option     | 99920AD031 |
| 413c:81d7 | Dell       | DW5821e Snapdragon X20 LTE   | 5     | option     | C5856B1EA0 |
| 05c6:9221 | Qualcomm   | Gobi Wireless Modem (QDL ... | 4     | qcserial   | 950506FE40 |
| 0711:0230 | Magic C... | MCT-232 Serial Port          | 4     | mct_u232   | D854654BAD |
| 19d2:0117 | ZTE WCD... | USB SCSI CD-ROM              | 4     | uas, us... | A2EA29B46D |
| 1bbb:022c | T & A M... | HSPA+ USB Modem              | 4     | usbseri... | A348E53594 |
| 1e0e:9001 | Qualcom... | SimTech, Incorporated        | 4     | option     | 3EEF74187F |
| 413c:8133 | Dell       | Wireless 5720 VZW Mobile ... | 4     | option     | 9F4A51F124 |
| 0403:1234 | Future ... | IronLogic RFID Adapter [Z... | 3     | ftdi_sio   | 876DB8C948 |
| 04da:250c | Panason... | Gobi Wireless Modem (QDL ... | 3     | qcserial   | 4502B92271 |
| 091e:0003 | Garmin ... | GPS (various models)         | 3     | garmin_gps | A877A0F4BC |
| 0f3d:68aa | Airprim... | AirCard 313U                 | 3     | uas, us... | 407432A954 |
| 10c4:8a2a | Cygnal ... | HubZ Smart Home Controller   | 3     | cp210x     | C9DA6A52CB |
| 1199:68c0 | Sierra ... | MC7304                       | 3     | qcserial   | 11C9D92E85 |
| 6547:0232 | Arkmicr... | ARK3116 Serial               | 3     | ark3116    | BFE6259C0C |
| 03f0:1f1d | Hewlett... | un2400 Gobi Wireless Modem   | 2     | qcserial   | 1BEB03698D |
| 0403:fc60 | Future ... | IRTrans USB                  | 2     | ftdi_sio   | 88DB2A30AA |
| 067b:aaa0 | Prolifi... | Prolific Pharos              | 2     | pl2303     | F4DBE54638 |
| 0df7:0620 | Mobile ... | MA-620 Infrared Adapter      | 2     | pl2303     | EEF3509B24 |
| 10c4:ea71 | Cygnal ... | CP2108 Quad USB to UART B... | 2     | cp210x     | F70E13FDBA |
| 114f:68a2 | Wavecom    | MC7750                       | 2     | qcserial   | 33AF47893A |
| 1199:0218 | Sierra ... | MC5720 Wireless Modem        | 2     | sierra     | E5C5CE1445 |
| 1bbb:00b7 | T & A M... | 3G Wireless Router           | 2     | option     | E6C9D1B45A |
| 2020:2060 | Qualcom... | CDMA Technologies MSM        | 2     | option     | C24817EE80 |
| 2100:9e58 | RT Systems | CT63 Radio Cable             | 2     | ftdi_sio   | 5C620BE56C |
| 2c7c:0306 | Quectel... | EG06/EP06/EM06 LTE-A modem   | 2     | option     | D48FD712A5 |
| 413c:8171 | Dell       | Gobi Wireless Modem (QDL ... | 2     | qcserial   | CB6D9E241E |
| 413c:819b | Dell       | Novatel Wireless HSPA        | 2     | option     | CE494B7720 |
| 03f0:1016 | Hewlett... | Jornada 548 / iPAQ HW6515... | 1     | ipaq       | 4FA0B1AA66 |
| 0403:f06e | Future ... | ELV ALC8500 Expert           | 1     | ftdi_sio   | 25B569ADA4 |
| 0403:fc0d | Future ... | Crystalfontz CFA-635 USB LCD | 1     | ftdi_sio   | DAE3697FF8 |
| 0451:505f | Texas I... | TUSB5052 Serial              | 1     | ti_usb_... | 64A9C1D635 |
| 045e:00ce | Microsoft  | SiRF GPS HH                  | 1     | ipaq       | A587AAD1F9 |
| 0483:3747 | STMicro... | ST Micro Connect Lite        | 1     | ftdi_sio   | A56D8D1C28 |
| 050d:0257 | Belkin ... | F5U257 Serial                | 1     | pl2303     | FFEED70C90 |
| 05c6:9225 | Qualcomm   | Sony Gobi 2000 Wireless M... | 1     | qcserial   | 3631A4D89D |
| 067b:e1f1 | Prolifi... | Z-TEK USB to Serial Comm ... | 1     | pl2303     | 34CED022E3 |
| 06cd:0121 | Keyspan    | USA-19hs serial adapter      | 1     | keyspan    | FB2C692CC5 |
| 0856:ac19 | B&B Ele... | Model USOPTL4DR              | 1     | ftdi_sio   | 077842DAC4 |
| 0af0:6501 | Option     | GlobeTrotter 3G+ Module      | 1     | option     | E9FA72450F |
| 0bf8:1001 | Fujitsu... | Fujitsu Pocket Loox 600 PDA  | 1     | ipaq       | 224FD9231B |
| 0df8:0001 | HOYA Co... | HOYA IrWave 520UK Usb-IrDA   | 1     | ir_usb     | 19BC1494C6 |
| 0ea0:6858 | Ours Te... | OTi-6858 serial adapter      | 1     | oti6858    | 7D394B641E |
| 10c4:8056 | Silicon... | USB Sensor Interface Device  | 1     | cp210x     | 6B03F1DB66 |
| 10c4:814a | Silicon... | West Mountain Radio RIGbl... | 1     | cp210x     | A85DC8D30D |
| 10c4:8470 | Cygnal ... | Juniper Networks BX Serie... | 1     | cp210x     | 06DECE3B2A |
| 10c4:ea61 | Silicon... | CP210x UART Bridge           | 1     | cp210x     | 7A4D566F94 |
| 110a:1450 | Moxa Te... | UPort 1450 4-Port RS-232/... | 1     | mxuport    | F86906F641 |
| 1199:0020 | Sierra ... | MC5725 Modem                 | 1     | sierra     | D2C42C6C14 |
| 1199:6802 | Sierra ... | MC8755 Device                | 1     | sierra     | 69A21019E7 |
| 1199:6804 | Sierra ... | MC8755 Device                | 1     | sierra     | 784D057761 |
| 1199:6812 | Sierra ... | MC8775 Device                | 1     | sierra     | 7D9E4527B1 |
| 1199:6856 | Sierra ... | ATT "USB Connect 881"        | 1     | sierra     | 5A1CA7D377 |
| 1199:6890 | Sierra ... | AC504                        | 1     | sierra     | 83B675C99C |
| 1199:68a3 | Sierra ... | MC8700 Modem                 | 1     | sierra     | 55167C5D7C |
| 1199:9070 | Sierra ... | EM7455 Qualcomm              | 1     | qcserial   | 032B587C4F |
| 12d1:1569 | Huawei ... | EM680 w/Gobi Technology      | 1     | option     | F05FDF7D0F |
| 1410:2110 | Novatel... | Ovation U720/MCD3000         | 1     | option     | 441D60EA88 |
| 1410:2410 | Novatel... | Expedite EU740               | 1     | option     | 4938E3EC42 |
| 1410:9010 | Novatel... | Expedite E362                | 1     | option     | B242556157 |
| 1555:0004 | Silicon... | AC4 USB to RS-485 Converter  | 1     | cp210x     | 1ED36B8028 |
| 15ba:002b | Olimex     | ARM-USB-OCD-H JTAG+RS232     | 1     | ftdi_sio   | D180569750 |
| 19d2:0189 | ZTE WCD... | ZTE LTE Technologies MSM     | 1     | option     | EA30F4CBE1 |
| 1a79:6001 | Bayer H... | Bayer Serial Cable           | 1     | ftdi_sio   | 07FED1CAB8 |

### Sound (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0d8c:0014 | C-Media... | Audio Adapter (Unitek Y-2... | 254   | snd_usb... | 44A240B27D |
| 0d8c:013c | C-Media... | CM108 Audio Controller       | 239   | snd_usb... | 4DAF9FDC0D |
| 1b3f:2008 | General... | Usb Audio Device             | 199   | snd_usb... | 0298FA0732 |
| 08bb:2902 | Texas I... | PCM2902 Audio Codec          | 188   | snd_usb... | 8DCE933429 |
| 0d8c:0012 | C-Media... | USB Audio Device             | 174   | snd_usb... | 7D7527B0AB |
| 0d8c:0005 | C-Media... | Blue Snowball                | 136   | snd_usb... | DBFEAB0BB4 |
| 0951:16a4 | Kingsto... | HyperX 7.1 Audio             | 132   | snd_usb... | 9747AB9C9C |
| 0bda:4014 | Realtek... | USB Audio                    | 127   | snd_usb... | F9D1627578 |
| 0c76:161f | JMTek      | USB PnP Audio Device         | 119   | snd_usb... | 6D45501F90 |
| 0d8c:000c | C-Media... | Audio Adapter                | 109   | snd_usb... | E7EBAD7358 |
| b58e:9e84 | Blue Mi... | Yeti Stereo Microphone       | 102   | snd_usb... | 3F2F789273 |
| 1130:1620 | Tenx Te... | USB AUDIO                    | 98    | snd_usb... | C694A13B5A |
| 8086:0808 | Intel      | USB PnP Sound Device         | 98    | snd_usb... | FF3D2367EE |
| 0bda:402e | Realtek... | USB Audio                    | 86    | snd_usb... | 08B1E4C99F |
| 0d8c:0102 | C-Media... | CM106 Like Sound Device      | 86    | snd_usb... | 098B7142EA |
| 046d:0a44 | Logitech   | Headset H390                 | 82    | snd_usb... | 4EB777675A |
| 413c:a503 | Dell       | AC511 Sound Bar              | 79    | snd_usb... | C8D175865C |
| 1852:7022 | GYROCOM... | Fiio E10                     | 73    | snd_usb... | 71BD5E1A20 |
| 046d:0a29 | Logitech   | H600 [Wireless Headset]      | 64    | snd_usb... | 5DBE42CF75 |
| 0c76:161e | JMTek      | USB PnP Audio Device         | 62    | snd_usb... | A10433A3CB |
| 046d:0a4d | Logitech   | G430 Surround Sound Gamin... | 61    | snd_usb... | 41311D3164 |
| 045e:070f | Microsoft  | LifeChat LX-3000 Headset     | 57    | snd_usb... | F367112B19 |
| 0d8c:0103 | C-Media... | CM102-A+/102S+ Audio Cont... | 57    | snd_usb... | BD89F26D7E |
| 046d:0a5b | Logitech   | G933 Wireless Headset Dongle | 49    | snd_usb... | A3A6A201CF |
| 046d:0a8f | Logitech   | USB Headset                  | 49    | snd_usb... | 805BFD400C |
| 17ef:3083 | Lenovo     | ThinkPad Thunderbolt 3 Do... | 49    | snd_usb... | 65666A7BEC |
| 0d8c:0134 | C-Media... | Alctron UM600                | 47    | snd_usb... | B3E5699382 |
| 054c:09cc | Sony       | DualShock 4 [CUH-ZCT2x]      | 40    | snd_usb... | 48C22EC264 |
| 1395:0025 | Sennhei... | Headset [PC 8]               | 40    | snd_usb... | 620CD76F75 |
| 046d:0a66 | Logitech   | [G533 Wireless Headset Do... | 39    | snd_usb... | 7BCE3059DC |
| 08bb:2704 | Texas I... | PCM2704 16-bit stereo aud... | 39    | snd_usb... | ED03DAB5F4 |
| 0d8c:0201 | C-Media... | CM6501                       | 39    | snd_usb... | 203B62C458 |
| 17ef:a396 | Lenovo     | ThinkPad USB-C Dock Gen2 ... | 37    | snd_usb... | 94F04E5543 |
| 1038:12ad | SteelSe... | SteelSeries Arctis 7         | 36    | snd_usb... | 5125306D59 |
| 046d:0a38 | Logitech   | Headset H340                 | 35    | snd_usb... | B6CAC26930 |
| 17ef:306f | Lenovo     | ThinkPad Dock USB Audio      | 35    | snd_usb... | 3C1D98DCE9 |
| 0556:0001 | Asahi K... | AK5370 I/F A/D Converter     | 34    | snd_usb... | 19BF6AC286 |
| 1b1c:0a14 | Corsair    | VOID PRO Wireless Gaming ... | 32    | snd_usb... | 05E2A24DE1 |
| 08bb:2912 | Texas I... | PCM2912A Audio Codec         | 31    | snd_usb... | 31850CE796 |
| 041e:324d | Creativ... | Sound Blaster Play! 3        | 30    | snd_usb... | 32F7B77B77 |
| 046d:0a1f | Logitech   | G930                         | 30    | snd_usb... | 908638C5F1 |
| 046d:0a45 | Logitech   | 960 Headset                  | 30    | snd_usb... | 0F0078F0E3 |
| 0d8c:000e | C-Media... | Audio Adapter (Planet UP-... | 29    | snd_usb... | 181BD83BDD |
| 08bb:2900 | Texas I... | PCM2900 Audio Codec          | 27    | snd_usb... | E1B676D2A4 |
| 0b0e:245e | GN Netcom  | Jabra Link 370               | 26    | snd_usb... | 40E64A9BD9 |
| 17a0:0310 | Samson ... | Meteor condenser microphone  | 26    | snd_usb... | 6E39F485FA |
| 03f0:056b | Hewlett... | USB Audio                    | 25    | snd_usb... | 36ADE7DD15 |
| 041e:30df | Creativ... | SB X-Fi Surround 5.1 Pro     | 25    | snd_usb... | B0485D3960 |
| 0b0e:0305 | GN Netcom  | Jabra EVOLVE Link MS         | 25    | snd_usb... | 27155EF23C |
| 1038:1294 | SteelSe... | Arctis Pro Wireless          | 25    | snd_usb... | 31E45B375E |
| 1532:0520 | Razer USA  | Kraken Tournament Edition    | 23    | snd_usb... | 31A93C68CB |
| 17ef:306a | Lenovo     | ThinkPad Thunderbolt 3 Do... | 23    | snd_usb... | 988050AAA4 |
| 041e:3237 | Creativ... | SB X-Fi Surround 5.1 Pro     | 22    | snd_usb... | 4D4959DF32 |
| 17ef:3063 | Lenovo     | ThinkPad Dock Audio          | 22    | snd_usb... | 356AB18B7D |
| 18c3:6255 | Elite S... | USB Audio Device             | 22    | snd_usb... | 1AC850D5B7 |
| 041e:3040 | Creativ... | SoundBlaster Live! 24-bit... | 21    | snd_usb... | A2FB8F6B18 |
| 046d:0a37 | Logitech   | USB Headset H540             | 21    | snd_usb... | EF235EBF04 |
| 0b0e:245d | GN Netcom  | Jabra Link 370               | 21    | snd_usb... | C2267F8DD1 |
| 0c76:160c | JMTek      | USB Speaker                  | 21    | snd_usb... | 073E1FC192 |
| 19f7:0003 | RODE Mi... | RODE NT-USB                  | 21    | snd_usb... | 14C78A00B9 |
| 28de:2102 | Valve S... | Valve VR Radio & HMD Mic     | 21    | snd_usb... | 1CDF133D3B |
| 041e:3232 | Creativ... | Sound Blaster Premium HD ... | 20    | snd_usb... | 9358C3AFBF |
| 046d:0a15 | Logitech   | G35 Headset                  | 20    | snd_usb... | C11404A76B |
| 047f:02f7 | Plantro... | BT600                        | 20    | snd_usb... | F0DC31F93D |
| 047f:c056 | Plantro... | Blackwire 3220 Series        | 20    | snd_usb... | D80338F3E9 |
| 0d8c:0008 | C-Media... | USB Audio Device             | 20    | snd_usb... | 9756CE58FC |
| 047f:c025 | Plantro... | C320-M                       | 19    | snd_usb... | 83DFC4B9D8 |
| 05a7:1020 | Bose       | USB Audio                    | 19    | snd_usb... | 2CFB272CEC |
| 0a12:1243 | Cambrid... | CSRA64110 USB Audio          | 19    | snd_usb... | D2A62B6AFB |
| 0c76:1607 | JMTek      | audio controller             | 19    | snd_usb... | 184BEDF2FD |
| 0d8c:0001 | C-Media... | Audio Device                 | 19    | snd_usb... | 62E4205A0F |
| 0d8c:016c | C-Media... | DH-60B                       | 19    | snd_usb... | DA200F9E64 |
| 046d:0a0c | Logitech   | Clear Chat Comfort USB He... | 18    | snd_usb... | DBA6F46C4C |
| 0d8c:0126 | C-Media... | USB Audio Device             | 18    | snd_usb... | CB9D4B0462 |
| 046d:0a01 | Logitech   | USB Headset                  | 17    | snd_usb... | F759AD1793 |
| 046d:0a03 | Logitech   | Logitech USB Microphone      | 17    | snd_usb... | DCEA776F2D |
| 08bb:2904 | Texas I... | PCM2904 Audio Codec          | 17    | snd_usb... | 21CB07B99E |
| 1038:1260 | SteelSe... | Arctis 7 wireless adapter    | 17    | snd_usb... | 43A19D8280 |
| 1532:0510 | Razer USA  | Kraken 7.1 V2                | 17    | snd_usb... | 5BA9AAE44B |
| 2188:6533 | No brand   | Thunderbolt 3 Audio          | 17    | snd_usb... | C6CC14214F |
| 041e:30d3 | Creativ... | Sound Blaster Play!          | 16    | snd_usb... | D93369F8D6 |
| 046d:0a5c | Logitech   | G633 Gaming Headset          | 16    | snd_usb... | FBEFA3CD0B |
| 047f:c012 | Plantro... | Audio 628 USB                | 16    | snd_usb... | 580B3A3082 |
| 05e1:0408 | Syntek     | STK1160 Video Capture Device | 16    | stk1160    | 143436EBD4 |
| 0d8c:0139 | C-Media... | Multimedia Headset [Gigaw... | 16    | snd_usb... | 128169DD93 |
| 047f:02ee | Plantro... | BT600                        | 15    | snd_usb... | 2B158EA18F |
| 0b0e:0420 | GN Netcom  | Jabra SPEAK 510              | 15    | snd_usb... | 2739F08A4C |
| 0d8c:0105 | C-Media... | CM108 Audio Controller       | 15    | snd_usb... | EEE4E7256B |
| 1532:0504 | Razer USA  | CONEXANT USB AUDIO           | 15    | snd_usb... | 73ECE6C322 |
| 17a0:0305 | Samson ... | GoMic compact condenser mic  | 15    | snd_usb... | 8E54C83E67 |
| 262a:9023 | SAVITECH   | SA9023 audio controller      | 15    | snd_usb... | EE7AF3845B |
| 041e:3256 | Creativ... | Sound BlasterX G6            | 14    | snd_usb... | 57A08FFCEB |
| 046d:0a04 | Logitech   | V20 portable speakers (US... | 14    | snd_usb... | F72E765EF0 |
| 046d:0aaa | Logitech   | PRO X                        | 14    | snd_usb... | 7A8809AE8A |
| 0763:2012 | M-Audio    | M-Audio Fast Track Pro       | 14    | snd_usb... | DE44F5F457 |
| 093a:2625 | Pixart ... | Multimedia audio controller  | 14    | gspca_p... | 6FA1EAC5DB |
| 09da:2701 | A4Tech     | Bloody Gaming Audio Device   | 14    | snd_usb... | EEE40A5557 |
| 0b0e:0306 | GN Netcom  | Jabra EVOLVE LINK            | 14    | snd_usb... | B753C3D9A0 |
| 1038:1250 | SteelSe... | SteelSeries Arctis 5         | 14    | snd_usb... | 48FDA84B8C |
| 1a86:752d | QinHeng... | CH345 MIDI adapter           | 14    | snd_usb... | AABBAA4370 |

### Touchpad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 06cb:2970 | Synaptics  | touchpad                     | 65    | usbhid     | BC9E6C4910 |
| 044e:1218 | Alps El... | Touchpad                     | 16    | usbhid     | 1ABEA9314A |
| 044e:120d | Alps El... | Touchpad                     | 8     | usbhid     | 09240A2A3F |
| 06cb:0009 | Synaptics  | Composite TouchPad and Tr... | 8     | synapti... | CEF790F685 |
| 044e:1216 | Alps El... | Touchpad                     | 7     | usbhid     | D6AB5352B8 |
| 044e:1217 | Alps El... | Touchpad                     | 5     | usbhid     | 3196DC7C2A |
| 17ef:6046 | Lenovo     | Wireless Touchpad K5923      | 5     | usbhid     | 05BC374383 |
| 044e:120f | Alps El... | Touchpad                     | 4     | usbhid     | A8551FD24E |
| 06cb:5710 | Synaptics  | SynapticsTouch Pad V 1.03U3  | 4     | usbhid     | 5834B6321D |
| 044e:1210 | Alps El... | Touchpad                     | 2     | usbhid     | 4FA01CCEE6 |
| 0488:0280 | Cirque     | 9925 AG Touchpad             | 2     | usbhid     | 6D0120C876 |
| 06cb:7af9 | Synaptics  | HIDUSB TouchPad V07          | 2     | usbhid     | 3C4E95F3C6 |
| 044e:1221 | Alps El... | Touchpad                     | 1     | usbhid     | 4937A2C0A8 |
| 0488:8010 | Cirque     | 9925 AG Touchpad             | 1     | usbhid     | 1498A5A5A4 |
| 04b4:fef3 | Cypress... | PenPower Touchpad            | 1     | usbhid     | AC3E990070 |
| 062a:19b5 | MosArt ... | TouchPad                     | 1     | usbhid     | 61BB547684 |
| 06cb:0001 | Synaptics  | TouchPad                     | 1     | synapti... | 7023DC94DA |
| 06cb:0096 | Synaptics  | HIDUSB TouchPad V01          | 1     | usbhid     | 1E10940254 |
| 06cb:5711 | Synaptics  | Touch Pad V 103u9            | 1     | usbhid     | 2D9527DBD4 |
| 06cb:7d29 | Synaptics  | HIDUSB TouchPad V03          | 1     | usbhid     | 49A6D8DEC1 |
| 413c:2507 | Dell       | TP713 Wireless Touchpad      | 1     | usbhid     | 8A10AE7D58 |

### Touchscreen (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04f3:20d0 | Elan Mi... | Touchscreen                  | 52    | usbhid     | 4EE08E92AE |
| 0eef:0001 | D-WAV S... | Titan6001 Surface Acousti... | 40    | usbhid     | BAD7484C1A |
| 04f3:2494 | Elan Mi... | Touchscreen                  | 36    | usbhid     | A638ECEE38 |
| 04f3:250e | Elan Mi... | Touchscreen                  | 36    | usbhid     | A7BDFE8774 |
| 0408:3008 | Quanta     | OpticalTouchScreen           | 25    | usbhid     | 15268C0CCC |
| 04f3:012d | Elan Mi... | Touchscreen                  | 21    | usbhid     | 0D732D9421 |
| 04f3:0254 | Elan Mi... | Touchscreen                  | 18    | usbhid     | D3455FCB23 |
| 04f3:21d5 | Elan Mi... | Touchscreen                  | 18    | usbhid     | EA3FABAB64 |
| 04f3:016f | Elan Mi... | Touchscreen                  | 17    | usbhid     | 93B4F5B14E |
| 04f3:2234 | Elan Mi... | Touchscreen                  | 17    | usbhid     | CB72DB0851 |
| 04f3:2013 | Elan Mi... | Touchscreen                  | 16    | usbhid     | 7DD454CDEE |
| 04f3:24a0 | Elan Mi... | Touchscreen                  | 16    | usbhid     | 6DD46EBB68 |
| 04f3:24a1 | Elan Mi... | Touchscreen                  | 16    | usbhid     | F788FD5E9D |
| 1926:0006 | NextWindow | 1950 HID Touchscreen         | 14    | usbhid     | 0E1FA2C583 |
| 04f3:000a | Elan Mi... | Touchscreen                  | 13    | usbhid     | 43A9DC51D9 |
| 04f3:0042 | Elan Mi... | Touchscreen                  | 12    | usbhid     | 9FC71241E6 |
| 04f3:0085 | Elan Mi... | Touchscreen                  | 12    | usbhid     | 0A2158EFE0 |
| 04f3:010c | Elan Mi... | Touchscreen                  | 12    | usbhid     | 1A2E40A1A3 |
| 04f3:2337 | Elan Mi... | Touchscreen                  | 12    | usbhid     | 9CE7A63C1A |
| 04f3:2398 | Elan Mi... | Touchscreen                  | 12    | usbhid     | 1649C0AE85 |
| 04f3:0224 | Elan Mi... | Touchscreen                  | 11    | usbhid     | 7BE9AF227C |
| 04f3:034e | Elan Mi... | Touchscreen                  | 11    | usbhid     | 2170036527 |
| 04f3:289b | Elan Mi... | Touchscreen                  | 11    | usbhid     | 4688DC5B46 |
| 04f3:2acc | Elan Mi... | Touchscreen                  | 11    | usbhid     | 901F37D11B |
| 04f3:002a | Elan Mi... | Touchscreen                  | 10    | usbhid     | B977195EB4 |
| 04f3:0034 | Elan Mi... | Touchscreen                  | 10    | usbhid     | CAC5BCFFE9 |
| 04f3:22c3 | Elan Mi... | Touchscreen                  | 10    | usbhid     | 6F45622DEC |
| 04f3:24e1 | Elan Mi... | Touchscreen                  | 10    | usbhid     | A87267AB19 |
| 1926:0003 | NextWindow | 1900 HID Touchscreen         | 10    | usbhid     | 7985ADDC49 |
| 04e7:0020 | Elo Tou... | Touchscreen Interface (2700) | 9     | usbhid     | 7A38C478BB |
| 04f3:2753 | Elan Mi... | Touchscreen                  | 9     | usbhid     | D2185EBE9F |
| 04f3:2793 | Elan Mi... | Touchscreen                  | 9     | usbhid     | E2A4A5E396 |
| 1926:0bce | NextWindow | Touchscreen                  | 9     | usbhid     | 626BFE0484 |
| 04f3:0303 | Elan Mi... | Touchscreen                  | 8     | usbhid     | D75AFF5A0A |
| 04f3:036e | Elan Mi... | Touchscreen                  | 8     | usbhid     | 8EFEEF8292 |
| 04f3:2012 | Elan Mi... | Touchscreen                  | 8     | usbhid     | 88D0F731FD |
| 04f3:2083 | Elan Mi... | Touchscreen                  | 8     | usbhid     | DBF3D3F2BB |
| 04f3:2672 | Elan Mi... | Touchscreen                  | 8     | usbhid     | CE8E9AF30D |
| 04f3:0135 | Elan Mi... | Touchscreen                  | 7     | usbhid     | F17B6F7270 |
| 04f3:0206 | Elan Mi... | Touchscreen                  | 7     | usbhid     | E471FD0BF4 |
| 04f3:0301 | Elan Mi... | Touchscreen                  | 7     | usbhid     | 999ED8DB39 |
| 04f3:2033 | Elan Mi... | Touchscreen                  | 7     | usbhid     | BD1D84D6E7 |
| 04f3:0023 | Elan Mi... | Touchscreen                  | 6     | usbhid     | E499AC500B |
| 04f3:003d | Elan Mi... | Touchscreen                  | 6     | usbhid     | E47E46D26F |
| 04f3:034f | Elan Mi... | Touchscreen                  | 6     | usbhid     | F12F66242D |
| 04f3:0363 | Elan Mi... | Touchscreen                  | 6     | usbhid     | E15D1F937B |
| 04f3:0389 | Elan Mi... | Touchscreen                  | 6     | usbhid     | D81E5AB43C |
| 04f3:0428 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 2A367A6EE4 |
| 04f3:0436 | Elan Mi... | Touchscreen                  | 6     | usbhid     | A3D7181425 |
| 04f3:0439 | Elan Mi... | Touchscreen                  | 6     | usbhid     | C689AD926B |
| 04f3:2070 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 236EFC033E |
| 04f3:2071 | Elan Mi... | Touchscreen                  | 6     | usbhid     | B37CBA5DF4 |
| 04f3:2089 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 615C03D3C6 |
| 04f3:20d6 | Elan Mi... | Touchscreen                  | 6     | usbhid     | 68AA81EE30 |
| 04f3:22ea | Elan Mi... | Touchscreen                  | 6     | usbhid     | 566FA6B1D5 |
| 04f3:2313 | Elan Mi... | Touchscreen                  | 6     | usbhid     | CF08166AE9 |
| 04f3:245a | Elan Mi... | Touchscreen                  | 6     | usbhid     | D42F5B1F3C |
| 04f3:24dd | Elan Mi... | Touchscreen                  | 6     | usbhid     | 26524BC478 |
| 1926:0dbe | NextWindow | Touchscreen                  | 6     | usbhid     | 94ED550685 |
| 1926:1846 | NextWindow | Touchscreen                  | 6     | usbhid     | CA3F4AA75A |
| 0408:3003 | Quanta     | OpticalTouchScreen           | 5     | usbhid     | 1CBEE8A7EF |
| 04f3:0089 | Elan Mi... | Touchscreen                  | 5     | usbhid     | D63ABB12EE |
| 04f3:024b | Elan Mi... | Touchscreen                  | 5     | usbhid     | 46F59CAC87 |
| 04f3:0268 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 5998C38555 |
| 04f3:0307 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 2548D4154B |
| 04f3:038a | Elan Mi... | Touchscreen                  | 5     | usbhid     | AAF45F99A4 |
| 04f3:0396 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 366DCDAD53 |
| 04f3:2020 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 233F101468 |
| 04f3:206f | Elan Mi... | Touchscreen                  | 5     | usbhid     | 6946FFB375 |
| 04f3:2073 | Elan Mi... | Touchscreen                  | 5     | usbhid     | E5C02D2922 |
| 04f3:2085 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 871B9656F1 |
| 04f3:21b4 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 4C55449378 |
| 04f3:21c3 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 801535D049 |
| 04f3:21d4 | Elan Mi... | Touchscreen                  | 5     | usbhid     | D403FA5702 |
| 04f3:2252 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 00123E7E27 |
| 04f3:228a | Elan Mi... | Touchscreen                  | 5     | usbhid     | 261B38075F |
| 04f3:228b | Elan Mi... | Touchscreen                  | 5     | usbhid     | 5F15030F71 |
| 04f3:2754 | Elan Mi... | Touchscreen                  | 5     | usbhid     | 74D1170C9D |
| 1926:0082 | NextWindow | 1950 HID Touchscreen         | 5     | usbhid     | DD4A0707BA |
| 1926:0093 | NextWindow | Touchscreen                  | 5     | usbhid     | 29ECAF9382 |
| 1926:0344 | NextWindow | Touchscreen                  | 5     | usbhid     | 73FE3F4EE7 |
| 1926:0e17 | NextWindow | Touchscreen                  | 5     | usbhid     | EEB433BF77 |
| 04f3:000c | Elan Mi... | Touchscreen                  | 4     | usbhid     | B00AE19B84 |
| 04f3:0021 | Elan Mi... | Touchscreen                  | 4     | usbhid     | 831F0DF544 |
| 04f3:0022 | Elan Mi... | Touchscreen                  | 4     | usbhid     | E6FB44B84D |
| 04f3:005a | Elan Mi... | Touchscreen                  | 4     | usbhid     | F34A20ACA3 |
| 04f3:009c | Elan Mi... | Touchscreen                  | 4     | usbhid     | 9AA1575740 |
| 04f3:009d | Elan Mi... | Touchscreen                  | 4     | usbhid     | EA8B2BD7A1 |
| 04f3:0111 | Elan Mi... | Touchscreen                  | 4     | usbhid     | C59D5358B3 |
| 04f3:0117 | Elan Mi... | Touchscreen                  | 4     | usbhid     | CD2D5D3F77 |
| 04f3:0140 | Elan Mi... | Touchscreen                  | 4     | usbhid     | 5DC10377AB |
| 04f3:0201 | Elan Mi... | Touchscreen                  | 4     | usbhid     | 385C30D3A6 |
| 04f3:020b | Elan Mi... | Touchscreen                  | 4     | usbhid     | 5B544A78F4 |
| 04f3:020d | Elan Mi... | Touchscreen                  | 4     | usbhid     | ED5C16C955 |
| 04f3:0261 | Elan Mi... | Touchscreen                  | 4     | usbhid     | DDE984D114 |
| 04f3:034a | Elan Mi... | Touchscreen                  | 4     | usbhid     | 3E1EF3D0D5 |
| 04f3:040d | Elan Mi... | Touchscreen                  | 4     | usbhid     | 57E753215C |
| 04f3:0417 | Elan Mi... | Touchscreen                  | 4     | usbhid     | FFEE376E78 |
| 04f3:2039 | Elan Mi... | Touchscreen                  | 4     | usbhid     | 22E687348D |
| 04f3:2044 | Elan Mi... | Touchscreen                  | 4     | usbhid     | 5BEA7A53E7 |

### Tv card (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:0892 | Logitech   | OrbiCam                      | 125   | gspca_v... | 75B4FE35CF |
| 0402:5602 | ALi        | M5602 Video Camera Contro... | 80    | gspca_m... | D38F5B09D2 |
| 1415:2000 | Nam Tai... | Sony Playstation Eye         | 69    | gspca_o... | 16D7B82A2C |
| 045e:00f7 | Microsoft  | LifeCam VX-1000              | 51    | gspca_s... | 53AB757A21 |
| 0ac8:303b | Z-Star ... | ZC0303 Webcam                | 48    | gspca_z... | 94CFDBC88F |
| 093a:2620 | Pixart ... | TV Card                      | 46    | gspca_p... | EB32AAA9EB |
| 046d:08d7 | Logitech   | QuickCam Communicate STX     | 42    | gspca_z... | FC3B27ABAC |
| 046d:0896 | Logitech   | OrbiCam                      | 35    | gspca_v... | 287952FB68 |
| 05e1:0501 | Syntek     | DC-1125 Webcam               | 30    | stkwebcam  | 05D9306FCC |
| 045e:00f5 | Microsoft  | LifeCam VX-3000              | 29    | gspca_s... | 7943FF718E |
| 046d:08da | Logitech   | QuickCam Messanger           | 26    | gspca_z... | 945B05BEE8 |
| 0ac8:305b | Z-Star ... | ZC0305 Webcam                | 26    | gspca_z... | 91021B3EF2 |
| 093a:2468 | Pixart ... | SoC PC-Camera                | 23    | gspca_p... | DCAC9505B1 |
| 093a:2622 | Pixart ... | Webcam Genius                | 23    | gspca_p... | 93307C26CD |
| 046d:089d | Logitech   | QuickCam E2500 series        | 22    | gspca_z... | D18540842D |
| 046d:08d9 | Logitech   | QuickCam IM/Connect          | 22    | gspca_z... | 3480D8EE33 |
| 174f:a311 | Syntek     | 1.3MPixel Web Cam - Asus ... | 20    | stkwebcam  | B5C6B1E6C5 |
| 093a:262c | Pixart ... | TV Card                      | 19    | gspca_p... | 01D9208EEB |
| 0c45:624f | Microdia   | PC Camera (SN9C201 + OV9650) | 18    | gspca_s... | 1A587EFF16 |
| 046d:08ad | Logitech   | QuickCam Communicate STX     | 17    | gspca_z... | 168EB58716 |
| 0ac8:307b | Z-Star ... | USB 1.1 Webcam               | 14    | gspca_z... | 93004B8E8F |
| 093a:2624 | Pixart ... | Webcam                       | 12    | gspca_p... | B453E98364 |
| 046d:08af | Logitech   | QuickCam Easy/Cool           | 11    | gspca_z... | CAB5B52CA0 |
| 093a:2621 | Pixart ... | PAC731x Trust Webcam         | 11    | gspca_p... | 3E710C5B09 |
| 2040:7200 | Hauppauge  | WinTV HVR-950                | 11    | au0828     | B93392EC91 |
| 041e:4052 | Creativ... | Live! Cam Vista IM           | 10    | gspca_o... | DF4338099C |
| 045e:00f4 | Microsoft  | LifeCam VX-6000 (SN9C20x ... | 10    | gspca_s... | 535D0016E2 |
| 093a:2460 | Pixart ... | Q-TEC WEBCAM 100             | 10    | gspca_p... | 58DB0EEF1F |
| 0ac8:301b | Z-Star ... | ZC0301 Webcam                | 10    | gspca_z... | 83F55D5BF7 |
| 046d:092f | Logitech   | QuickCam Express Plus        | 9     | gspca_s... | 83DFC4B9D8 |
| 093a:2476 | Pixart ... | CIF Single Chip              | 9     | gspca_p... | 324E08922C |
| 093a:2626 | Pixart ... | TV Card                      | 9     | gspca_p... | F4AE9B990F |
| 046d:08f0 | Logitech   | QuickCam Messenger           | 8     | gspca_s... | BAA382CC01 |
| 0ac8:c002 | Z-Star ... | Visual Communication Came... | 8     | gspca_v... | C5A6B34C91 |
| 0c45:608f | Microdia   | PC Camera (SN9C103 + OV7630) | 8     | gspca_s... | 21833C414E |
| 0471:0329 | Philips... | SPC 900NC PC Camera / ORI... | 7     | pwc        | 8ED81A9451 |
| 093a:2472 | Pixart ... | CIF Single Chip              | 7     | gspca_p... | 0DC7C8F9DC |
| 0c45:6007 | Microdia   | VideoCAM Eye                 | 7     | gspca_s... | 39C5751F26 |
| 0c45:600d | Microdia   | TwinkleCam USB camera        | 7     | gspca_s... | 584063E568 |
| 041e:405f | Creativ... | WebCam Vista (VF0330)        | 6     | gspca_o... | ECAB02A7DF |
| 046d:08a2 | Logitech   | Labtec Webcam Pro            | 6     | gspca_z... | 72DD85EA81 |
| 0733:0401 | ViewQue... | CS330 Webcam                 | 6     | gspca_s... | 16640D2961 |
| 093a:2608 | Pixart ... | PAC7311 Trust WB-3300p       | 6     | gspca_p... | A43D67CD48 |
| 0ac8:0328 | Z-Star ... | A4Tech PK-130MG              | 6     | gspca_v... | A3D54DEE1B |
| 0c45:6028 | Microdia   | Typhoon Easycam USB 330K ... | 6     | gspca_s... | CC9D06DBBB |
| eb1a:2861 | eMPIA T... | EasyCAP DC60+ [EM2861]       | 6     | em28xx     | 25822EE96D |
| 041e:4064 | Creativ... | VF0420 Live! Cam Vista IM    | 5     | gspca_o... | E0FF71901E |
| 046d:08dd | Logitech   | QuickCam for Notebooks       | 5     | gspca_z... | 1CDAE8BCC1 |
| 046d:092e | Logitech   | QuickCam Chat                | 5     | gspca_s... | 3A04E52D73 |
| 0c45:613c | Microdia   | PC Camera (SN9C120)          | 5     | gspca_s... | D3399DF5A4 |
| 0c45:6242 | Microdia   | PC Camera (SN9C201 + MI1310) | 5     | gspca_s... | ABDD5F9208 |
| 0c45:6260 | Microdia   | PC Camera (SN9C201 + OV76... | 5     | gspca_s... | 43B40CA9ED |
| 2304:021a | Pinnacl... | Dazzle DVC100 Audio Device   | 5     | em28xx     | 5C844EEF2D |
| 041e:4034 | Creativ... | Webcam Instant               | 4     | gspca_z... | 4929B0E708 |
| 041e:4036 | Creativ... | Webcam Live!/Live! Pro       | 4     | gspca_z... | BA80D79115 |
| 046d:08ae | Logitech   | QuickCam for Notebooks       | 4     | snd_usb... | 4152D7A631 |
| 046d:0928 | Logitech   | QuickCam Express             | 4     | gspca_s... | 1604193C0F |
| 093a:2600 | Pixart ... | Typhoon Easycam USB 330K ... | 4     | gspca_p... | EEF3509B24 |
| 093a:260e | Pixart ... | PAC7311 Gigaware VGA PC C... | 4     | gspca_p... | 2462C80A14 |
| 0ac8:0321 | Z-Star ... | Vimicro generic vc0321 Ca... | 4     | gspca_v... | 2466DF7773 |
| 0c45:6128 | Microdia   | PC Camera (SN9C325 + OM6802) | 4     | gspca_s... | F75214C8D9 |
| 0c45:6270 | Microdia   | PC Camera (SN9C201 + MI03... | 4     | gspca_s... | 37EADD87D7 |
| 041e:4061 | Creativ... | Live! Cam Notebook Pro [V... | 3     | gspca_o... | AAB6789435 |
| 041e:4068 | Creativ... | Live! Cam Notebook [VF0470]  | 3     | gspca_o... | 3FDF6B4559 |
| 046d:08f5 | Logitech   | QuickCam Messenger Commun... | 3     | gspca_s... | 139478F373 |
| 046d:092b | Logitech   | Labtec Webcam Plus           | 3     | gspca_s... | 966D2650E0 |
| 046d:092c | Logitech   | QuickCam Chat                | 3     | gspca_s... | 40CF3439DB |
| 0471:032d | Philips... | SPC 210NC PC Camera          | 3     | gspca_z... | 5BD94422D2 |
| 04fc:0561 | Sunplus... | Flexcam 100                  | 3     | gspca_s... | 2B44D73E4B |
| 054c:0155 | Sony       | Eyetoy Video Device          | 3     | gspca_o... | 2C2DFBF127 |
| 05a9:8519 | OmniVis... | OV519 Webcam                 | 3     | gspca_o... | DBFE603100 |
| 093a:2470 | Pixart ... | SoC PC-Camera                | 3     | gspca_p... | 43D324FA29 |
| 0ac8:0302 | Z-Star ... | ZC0302 Webcam                | 3     | gspca_z... | 18B6043332 |
| 0c45:602c | Microdia   | Clas Ohlson TWC-30XOP Webcam | 3     | gspca_s... | 84AB3C0A57 |
| 0c45:602e | Microdia   | VideoCAM Messenger           | 3     | gspca_s... | 11B0CECD6B |
| 0c45:613a | Microdia   | PC Camera (SN9C120)          | 3     | gspca_s... | 93490E7142 |
| 0c45:613b | Microdia   | Win2 PC Camera               | 3     | gspca_s... | AB98B73D62 |
| 041e:401e | Creativ... | Webcam NX Pro                | 2     | gspca_z... | 8EBC1639B1 |
| 041e:401f | Creativ... | Webcam Notebook [PD1171]     | 2     | gspca_z... | 46242D579F |
| 0458:7004 | KYE Sys... | VideoCAM Express V2          | 2     | gspca_s... | 7B80116745 |
| 046d:0870 | Logitech   | QuickCam Express             | 2     | gspca_s... | 496B2FCD96 |
| 046d:08a9 | Logitech   | Notebook Deluxe              | 2     | gspca_z... | F81A55F416 |
| 046d:08d8 | Logitech   | QuickCam for Notebook Deluxe | 2     | gspca_z... | 1280EBBEDF |
| 046d:08f6 | Logitech   | QuickCam Messenger Plus      | 2     | gspca_s... | F55F5434E6 |
| 046d:0920 | Logitech   | QuickCam Express             | 2     | gspca_t... | 9494E60693 |
| 046d:0929 | Logitech   | Labtec Webcam Pro            | 2     | gspca_s... | 7BDF714AF6 |
| 0553:0002 | STMicro... | CPiA Webcam                  | 2     | gspca_c... | D5FFD1FF38 |
| 05a9:4519 | OmniVis... | Webcam Classic               | 2     | gspca_o... | 5BF965D2F1 |
| 06f8:3008 | Guillemot  | USB camera                   | 2     | gspca_s... | 7966B612A9 |
| 0923:010f | IC Media   | SIIG MobileCam               | 2     | gspca_t... | C00289E6ED |
| 093a:2471 | Pixart ... | SoC PC-Camera                | 2     | gspca_p... | 340C0B2610 |
| 0c45:6001 | Microdia   | Genius VideoCAM NB           | 2     | gspca_s... | D165244F3B |
| 0c45:60b0 | Microdia   | Genius VideoCam Look         | 2     | gspca_s... | 8C929530B7 |
| 0c45:60c0 | Microdia   | PC Camera with Mic (SN9C105) | 2     | gspca_s... | 7DC713CD9F |
| 0c45:624e | Microdia   | PC Camera (SN9C201 + SOI968) | 2     | gspca_s... | 7CD8FE006C |
| 0c45:627b | Microdia   | PC Camera (SN9C201 + OV7660) | 2     | gspca_s... | 4071FE6BE9 |
| 0c45:62b3 | Microdia   | PC Camera with Microphone... | 2     | gspca_s... | BECF5103D5 |
| 0ccd:0096 | TerraTe... | Grabby                       | 2     | em28xx     | FF2A743691 |
| 2040:6513 | Hauppauge  | WinTV HVR-950/HVR-980        | 2     | em28xx     | 143436EBD4 |
| 2304:0208 | Pinnacl... | Studio PCTV USB2             | 2     | em28xx,... | 4365F32962 |

### Ups (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 051d:0002 | America... | Uninterruptible Power Supply | 430   | usbhid     | 74D4CDFFC4 |
| 0764:0501 | Cyber P... | CP1500 AVR UPS               | 170   | usbhid     | 44A240B27D |
| 0463:ffff | MGE UPS... | UPS                          | 32    | usbhid     | 4BEFD5F360 |
| 0d9f:0004 | Powercom   | HID UPS Battery              | 24    | usbhid     | 246D6321DE |
| 0764:0601 | Cyber P... | PR1500LCDRT2U UPS            | 20    | usbhid     | A04EB698F8 |
| 051d:0003 | America... | UPS                          | 18    | usbhid     | 0E290CC57A |
| 06da:ffff | Phoenix... | Offline UPS                  | 11    | usbhid     | 6D05038359 |
| 06da:0003 | Phoenix... | 1300VA UPS                   | 8     | usbhid     | 6A1741B4B2 |
| 0925:1234 | Lakevie... | UPS USB MON V1.4             | 7     | usbhid     | 6994939B1D |
| 0d9f:00a2 | Powercom   | Imperial Uninterruptible ... | 5     | usbhid     | AEEDCA54FC |
| 0592:0002 | Powerware  | UPS (X-Slot)                 | 4     | usbfs      | F9E5B1D3C6 |
| 09ae:3016 | Tripp Lite | UPS                          | 4     | usbhid     | 7AEE1156D8 |
| 0d9f:00a3 | Powercom   | Smart King PRO Uninterrup... | 4     | usbhid     | 89CC93BB0F |
| 0d9f:00a6 | Powercom   | Black Knight PRO Uninterr... | 4     | usbhid     | 49BD48F97D |
| 0d9f:00a4 | Powercom   | WOW Uninterruptible Power... | 3     | usbhid     | 0C982DF6CC |
| 05dd:a011 | Delta E... | MINUTEMAN UPS                | 2     | usbhid     | 1BAE5B1DC6 |
| 09ae:2012 | Tripp Lite | UPS                          | 2     | usbhid     | 8D6C4235C3 |
| 03f0:1fe2 | Hewlett... | T1000 G3 UPS                 | 1     | usbhid     | 19AE174CC7 |
| 050d:0751 | Belkin ... | Belkin UPS                   | 1     | usbhid     | 71F7F3AD8A |
| 06da:0002 | Phoenix... | UPS                          | 1     |            | 4F5E89A87E |
| 09ae:2010 | Tripp Lite | UPS                          | 1     | usbhid     | 5D1A48EE4E |
| 09ae:4004 | Tripp Lite | UPS                          | 1     | usbfs      | 52D5275C7F |

### Video (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 048d:9006 | Integra... | IT9135 BDA Afatech DVB-T ... | 8     | dvb_usb... | A40F61B08A |
| 0fd9:0066 | Elgato ... | Cam Link 4K                  | 6     | snd_usb... | F323B316A2 |
| 1164:1ee9 | YUAN Hi... | Polaris AV Capture           | 4     |            | E1BB0618FD |
| 2304:0224 | Pinnacl... | Pinnacle High Speed USB D... | 4     |            | 97D31BFF69 |
| 0fd9:0051 | Elgato ... | GameCapture HD               | 2     |            | 3A3874784C |
| 0fd9:0067 | Elgato ... | Cam Link 4K                  | 2     | snd_usb... | B1D2BA527C |
| 04b4:00f9 | Cypress... | Ninja Dock                   | 1     | usbhid     | 79FA3F7509 |
| 0fd9:0061 | Elgato ... | Cam Link                     | 1     | uvcvideo   | 5114B3BC7A |
| 0fd9:0062 | Elgato ... | Cam Link                     | 1     | snd_usb... | D0234C90FB |
| 0fd9:006a | Elgato ... | Game Capture HD60 S+         | 1     | usbhid     | 2DC1AA4155 |
| 1b80:a41c | Afatech    | Polaris AV Capture           | 1     |            | F20674C0B8 |
| 5555:3382 | Epiphan... | VGA2USB Frame Grabber        | 1     |            | 37A831391B |

### Webcam (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 145f:013c | Trust      | Multimedia audio controller  | 3     | gspca_p... | B85703D1E4 |

### Wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 2717:ff88 | Xiaomi     | Mi/Redmi series (RNDIS + ... | 68    | rndis_host | 008B548654 |
| 22b8:2e25 | Motorol... | moto g power (2021)          | 43    | rndis_host | 471FDFC5A9 |
| 0489:e0a6 | Foxconn... | Android                      | 11    | rndis_host | CA8DCD489C |
| 12d1:1039 | Huawei ... | Ideos (tethering mode)       | 10    | rndis_host | E15B3DCFA3 |
| 2a70:9024 | OnePlus... | AC2001                       | 10    | rndis_host | 3F02204090 |
| 18d1:4ee4 | Google     | Nexus/Pixel Device (tethe... | 7     | rndis_host | 132ED957BA |
| 12d1:107c | Huawei ... | Android                      | 6     | rndis_host | C1273267FF |
| 0b05:7782 | ASUSTek... | Android                      | 5     | rndis_host | F93423F14D |
| 1286:4e31 | Marvell... | Mobile Composite Device Bus  | 5     | rndis_host | E9C14779DF |
| 2d95:6ffa | vivo       | 1904                         | 5     | rndis_host | 581EC6A7F1 |
| 0b05:7775 | ASUSTek... | Zenfone GO (ZB500KL) (Deb... | 4     | rndis_host | 5DC8528948 |
| 22d9:2766 | OPPO El... | RMX2161                      | 4     | rndis_host | B0FBEA4680 |
| 05c6:f626 | Qualcomm   | MDM9607-MTP _SN:17438E36     | 3     | rndis_host | 332DDF27C1 |
| 17ef:782f | Lenovo     | Lenovo                       | 3     | rndis_host | 0504CFE362 |
| 04b7:88d4 | Compal ... | Android                      | 2     | rndis_host | 63AC92DFF4 |
| 0bb4:0ffc | HTC (Hi... | Android Phone                | 2     | rndis_host | ACC6C85624 |
| 0fce:71aa | Sony Er... | D2303                        | 2     | rndis_host | 0014DBBEAD |
| 0fce:71e8 | Sony Er... | F5321                        | 2     | rndis_host | 70D66C5819 |
| 0fce:71fa | Sony Er... | H8216                        | 2     | rndis_host | 6BF9D537A8 |
| 1271:0541 | Android    | Android                      | 2     | rndis_host | 0C8768F146 |
| 15a9:003a | Gemtek     | Modem YOTA 4G LTE            | 2     | rndis_host | 03FF45BD03 |
| 216f:0044 | Altair ... | Alt38XX devboard             | 2     | rndis_host | 92A7F0EA0B |
| 271d:3004 | SPA Con... | Allure M1                    | 2     | rndis_host | B4EF87DE2D |
| 2d95:600b | Android    | Android                      | 2     | rndis_host | B6FA661FDD |
| 2d95:6ffb | MediaTek   | vivo 1714                    | 2     | rndis_host | 47AA9C9E14 |
| 0421:06eb | Nokia M... | Nokia_X (RM-980)             | 1     | rndis_host | E8E340D720 |
| 0421:0704 | Nokia M... | Nokia_X2 (RM-1013)           | 1     | rndis_host | 2762E434EB |
| 04dd:97f2 | Sharp      | SH05F                        | 1     | rndis_host | B10FE6845E |
| 05c6:0a02 | Qualcomm   | Jolla C                      | 1     | rndis_host | A08DCFFB5A |
| 05c6:902d | Qualcomm   | Android                      | 1     | rndis_host | E6C85F7E85 |
| 05c6:90b6 | Qualcomm   | Android                      | 1     | rndis_host | DBCA41493B |
| 0e79:52b7 | Archos     | Archos                       | 1     | rndis_host | 4E4EF907A0 |
| 0fce:7193 | Sony Er... | C6603                        | 1     | rndis_host | F748A62EBE |
| 0fce:71ba | Sony Er... | D6603                        | 1     | rndis_host | 5974A74BFD |
| 0fce:71de | Sony Er... | F3111                        | 1     | rndis_host | D1BA1C9EFA |
| 0fce:71f3 | Sony Er... | G8341                        | 1     | rndis_host | 3AF551E450 |
| 0fce:71f6 | Sony Er... | H4311                        | 1     | rndis_host | C9FFEA0EA6 |
| 0fce:7201 | Sony Er... | I4113                        | 1     | rndis_host | A8B162F110 |
| 0fce:81a9 | Sony Er... | D5322                        | 1     | rndis_host | 502EF11B75 |
| 0fce:81bb | Sony Er... | D5803                        | 1     | rndis_host | 7D93192AAE |
| 0fce:81e8 | Sony Er... | F5321                        | 1     | rndis_host | D1E41EC5C0 |
| 0fce:81f1 | Sony Er... | Android                      | 1     | rndis_host | 535EA77E4F |
| 0fce:8207 | Sony Er... | I3312                        | 1     | rndis_host | 1DBF9CCED7 |
| 0fce:820e | Sony Er... | XQ-AD51                      | 1     | rndis_host | F2418E15EC |
| 109b:5d20 | Hisense    | U972                         | 1     | rndis_host | B95A7FC433 |
| 12d1:2607 | Huawei ... | HUAWEI                       | 1     | rndis_host | A6385534C5 |
| 15a9:0046 | Gemtek     | 4G Modem                     | 1     | rndis_host | FBF317133B |
| 17ef:79bb | Lenovo     | Android                      | 1     | rndis_host | 0B5B82FFE2 |
| 17ef:7a2f | Lenovo     | Karate                       | 1     | rndis_host | 59C3CB6EA6 |
| 17ef:7be6 | Lenovo     | Android                      | 1     | rndis_host | 750413CC61 |
| 17ef:7c4b | Lenovo     | TB-X606F                     | 1     | rndis_host | 0A0EFAE900 |
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

### Others (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0b05:18f3 | ASUSTek... | AURA LED Controller          | 409   | usbhid     | D94C194BA5 |
| 27c6:538d | Shenzhe... | FingerPrint                  | 194   | usbfs      | B81492DB2B |
| 0b05:1939 | ASUSTek... | AURA LED Controller          | 176   | usbhid     | 37BE0C0682 |
| 05ac:8300 | Apple      | Built-in iSight (no firmw... | 124   | isight_... | E31DDE7E74 |
| 2109:0100 | VIA Labs   | USB 2.0 BILLBOARD            | 111   |            | 1761317692 |
| 2109:8888 | VIA Labs   | USB Billboard Device         | 99    |            | 02F641EA60 |
| 2109:0102 | VIA Labs   | USB 2.0 BILLBOARD            | 97    |            | DB75E4E24F |
| 06cb:00da | Synaptics  |                              | 89    |            | 0271A8FD47 |
| 22b8:2e82 | Motorol... | XT1541 [Moto G 3rd Gen]      | 68    | usbfs      | FB464C433D |
| 1b1c:0c09 | Corsair    | H100i v2                     | 50    |            | 02FEE32807 |
| 04f3:0c00 | Elan Mi... | ELAN:ARM-M4                  | 49    |            | B40784D2C7 |
| 04f3:0c4c | Elan Mi... | ELAN:ARM-M4                  | 48    |            | F49F22766B |
| 27c6:521d | Shenzhe... | FingerPrint                  | 47    |            | ADD3CC76EE |
| 04f3:0c4f | Elan Mi... | ELAN:Fingerprint             | 45    |            | 390085B056 |
| 1c7a:0575 | LighTun... | EgisTec EH575                | 44    |            | 2FFEC0ACAE |
| 2109:8818 | VIA Labs   | USB Billboard Device         | 42    |            | 6B2493EB16 |
| 04f3:0c4d | Elan Mi... | ELAN:Fingerprint             | 38    |            | 4D1B4591DD |
| 1d5c:7102 | Fresco ... | Generic Billboard Device     | 36    |            | 348BE4B537 |
| 2433:b200 | ASETEK     | [NZXT Kraken X60]            | 36    | usbfs      | 5DBE42CF75 |
| 06cb:00d8 | Synaptics  | Synaptics FS7604 Touch Fi... | 33    |            | 88E51BFD39 |
| 2109:0103 | VIA Labs   | USB 2.0 BILLBOARD            | 32    |            | B21D98595A |
| 04f3:0c4b | Elan Mi... | ELAN:Fingerprint             | 31    |            | F367112B19 |
| 0424:2740 | Microch... | Hub Controller               | 29    |            | 1CDF133D3B |
| 1b1c:0c08 | Corsair    | H80i v2                      | 29    |            | 90F906F5F9 |
| 045e:02d1 | Microsoft  | Xbox One Controller          | 28    | xpad       | DBA6F46C4C |
| 1b1c:0c13 | Corsair    | H115i Platinum               | 26    |            | EB55E9A1CD |
| 03f0:046b | Hewlett... | USB-C Dock G5                | 25    | usbhid     | 36ADE7DD15 |
| 0483:3748 | STMicro... | ST-LINK/V2                   | 24    |            | F2D9EEF592 |
| 04f3:0c28 | Elan Mi... | ELAN:Fingerprint             | 24    | usbfs      | 6CEB83052E |
| 1b1c:0c15 | Corsair    | H100i Platinum               | 24    |            | AA3A28C4B3 |
| 27c6:532d | Shenzhe... | Fingerprint                  | 24    |            | AD3C1FB56A |
| 413c:b080 | Dell       | DA20 Adapter                 | 24    |            | B17A5C4CD5 |
| 0b05:7772 | ASUSTek... | Zenfone GO (ZB500KL) (MTP... | 23    | usbfs      | 235D55372B |
| 17e9:4301 | Display... | USB3.0 UHD DisplayPort Ad... | 23    | snd_usb... | 1EEA89F8BB |
| 2833:0211 | Oculus VR  | Rift Sensor                  | 23    | uvcvideo   | FBA004A752 |
| 17ef:3060 | Lenovo     | ThinkPad Dock                | 22    | usbhid     | 356AB18B7D |
| 1b1c:0c12 | Corsair    | H150i Platinum               | 22    |            | FA126D0D5F |
| 0bda:5400 | Realtek... | BillBoard Device             | 21    |            | 1FA6A4756A |
| 2109:0101 | VIA Labs   | USB-C to Multiport Adapte... | 21    |            | C6407E2AC9 |
| 17e9:6015 | Display... | ThinkPad Hybrid USB-C wit... | 20    | snd_usb... | 69510C22F1 |
| 04eb:e033 | Northst... | eHome Infrared Transceiver   | 18    |            | 523DACC90C |
| 17ef:3074 | Lenovo     | USB Billboard                | 18    | usbhid     | 3C1D98DCE9 |
| 04b8:014a | Seiko E... | Perfection V37/V370          | 17    |            | BBC8131C67 |
| 1d50:6089 | OpenMoko   | Great Scott Gadgets HackR... | 17    | hackrf     | 0EE18BF1AE |
| 22b8:2e76 | Motorol... | moto g stylus                | 17    | usbfs      | 0B46E13FD1 |
| 22b8:2e81 | Motorol... | Moto G (5) Plus              | 17    | usbfs      | AB4F7CC66D |
| 04b4:5217 | Cypress... | Billboard Device             | 16    | usbhid     | 31850CE796 |
| 0bda:5442 | Realtek... | Cable Matters USB-C 8K Vi... | 16    |            | 0391795292 |
| 1366:0101 | SEGGER     | J-Link PLUS                  | 16    | usbfs      | 5E3023334C |
| 0819:0101 | eLicenser  | License Management and Co... | 15    |            | B75E43228A |
| 1b71:3002 | Fushicai   | USBTV007 Video Grabber [E... | 15    | usbtv      | D75B7FBBB8 |
| 2a70:4ee7 | OnePlus... | ONEPLUS A3010 [OnePlus 3T... | 15    | usbfs      | 9D8401675E |
| 0451:82ee | Texas I... |                              | 14    |            | 790712327C |
| 06cb:0088 | Synaptics  | Kensington Fingerprint Ke... | 14    |            | DA913ED8D3 |
| 1934:5168 | Feature... | F71610A or F71612A Consum... | 14    | mceusb     | C8E4E068F4 |
| 2109:8887 | VIA Labs   | 40AN                         | 14    |            | 65666A7BEC |
| 054c:01bb | Sony       | FeliCa S320 [PaSoRi]         | 13    |            | D32BF9DCED |
| 05ac:1460 | Apple      | USB-C Digital AV Multipor... | 13    |            | FFA207ED1E |
| 0711:5601 | Magic C... | T6 USB Station               | 13    |            | CF555F92BC |
| 0e8d:201c | MediaTek   | F2                           | 13    | usbfs      | 31119F3EBF |
| 16c0:05dc | Van Ooi... | shared ID for use with li... | 13    |            | E5C076C975 |
| 17e9:4300 | Display... | USB3.0 to VGA Adapter        | 13    | snd_usb... | 881E9BB0DD |
| 1934:0702 | Feature... | Integrated Consumer Infra... | 13    | mceusb     | 4982DA1FE4 |
| 1b1c:0c0a | Corsair    | Hydro Series H115i Liquid... | 13    |            | 3E5431B4CD |
| 1e71:3008 | NZXT       | KrakenZ Device               | 13    | usbhid     | 203F012110 |
| 03f0:0667 | Hewlett... | WinUSB                       | 12    | usbhid     | BC7C58F248 |
| 0424:2530 | Microch... | Bridge device                | 12    |            | 4E210308E7 |
| 0471:0815 | Philips... | eHome Infrared Receiver      | 12    | mceusb     | 4C755699D3 |
| 06cb:00cb | Synaptics  |                              | 12    |            | D2D2EB910A |
| 0bda:2171 | Realtek... | BillBoard Device             | 12    |            | EB3D04E089 |
| 1d5c:5100 | Fresco ... | Generic Billboard Device     | 12    |            | 78C640D460 |
| 0451:ace1 | Texas I... | TPS65983b                    | 11    |            | 5ECEA84320 |
| 045e:02dd | Microsoft  | Xbox One Controller (Firm... | 11    | xpad       | D786545448 |
| 0835:2a01 | Action ... | BILLBOARD DEVICE             | 11    |            | F001BDDEA6 |
| 187f:0600 | Siano M... | MDTV Receiver                | 11    | smsusb     | A6C445344B |
| 24c6:543a | ThrustM... | PowerA Wired Controller f... | 11    | xpad       | C424D5C53D |
| 2717:ff08 | Xiaomi     | Redmi Note 3 (ADB Interface) | 11    | usbfs      | 5C45DFB686 |
| 03f0:484a | Hewlett... | Elite USB-C Dock G4          | 10    | usbhid     | DBFDC51AC7 |
| 04b8:0202 | Seiko E... | Interface Card UB-U05 for... | 10    | usblp      | 5FCE34F2B6 |
| 2040:0265 | Hauppauge  | WinTV-dualHD DVB             | 10    | em28xx     | 1CDCECADAB |
| 2109:8883 | VIA Labs   | USB Billboard Device         | 10    |            | 3E5F76719A |
| 0483:374b | STMicro... | ST-LINK/V2.1                 | 9     | cdc_acm    | D180569750 |
| 0499:1509 | Yamaha     | Steinberg UR22               | 9     | snd_usb... | 8EF532D4EC |
| 04b8:013c | Seiko E... | Perfection V19               | 9     |            | D855B9BF0F |
| 04b8:013d | Seiko E... | Perfection V39               | 9     |            | 81676A0984 |
| 04f3:0c11 | Elan Mi... | ELAN:Fingerprint             | 9     | usbfs      | F7A69152B9 |
| 04f3:0c3d | Elan Mi... | ELAN:Fingerprint             | 9     |            | F9D1627578 |
| 04f3:0c57 | Elan Mi... | ELAN:Fingerprint             | 9     |            | 2FE8E30909 |
| 04f3:0c63 | Elan Mi... | ELAN:Fingerprint             | 9     |            | 2FEAA5043C |
| 0572:c68a | Conexan... | EyeTV Stick                  | 9     | dvb_usb... | 21BB7408E3 |
| 06cb:00f0 | Synaptics  |                              | 9     |            | E20B51102D |
| 0955:0007 | Nvidia     | stereo controller            | 9     |            | E212314FD1 |
| 0af0:7601 | Option     | Globetrotter MO40x 3G Mod... | 9     | hso        | 71E55F44FC |
| 0b05:19af | ASUSTek... | AURA LED Controller          | 9     | usbhid     | 60F7FA9FE7 |
| 1b1c:0c03 | Corsair    | H100iGTX Cooler              | 9     |            | DB1E5DAD24 |
| 1b20:0400 | MStar S... | BillBoard                    | 9     |            | BFDC7B65CA |
| 2040:8268 | Hauppauge  | soloHD                       | 9     | em28xx     | 3C0A297EDE |
| 04f3:0c02 | Elan Mi... | ELAN:Fingerprint             | 8     |            | 022AB6DECB |
| 06cb:00c4 | Synaptics  | Synaptics FS7604 Touch Fi... | 8     |            | D284325FCF |
| 088e:5036 | iLok       | Portable secure storage f... | 8     | usbfs      | 91BDB65672 |

