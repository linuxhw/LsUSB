Most popular USB devices
========================

This is a project to identify most popular USB devices in modern computers and
share detailed lsusb reports collected by Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 332025.

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
   * [ Diagnostic ](#diagnostic-usb)
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
   * [ Monitor ](#monitor-usb)
   * [ Net/ethernet ](#netethernet-usb)
   * [ Net/wimax ](#netwimax-usb)
   * [ Net/wireless ](#netwireless-usb)
   * [ Network ](#network-usb)
   * [ Phone ](#phone-usb)
   * [ Printer ](#printer-usb)
   * [ Scanner ](#scanner-usb)
   * [ Serial controller ](#serial-controller-usb)
   * [ Smartcard ](#smartcard-usb)
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
| 1235:8211 | Focusrite-Nov... | Scarlett Solo (3rd Gen.)             | 92    | snd_usb... | [4681975F9D](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/4681975F9D>) |
| 1235:8210 | Focusrite-Nov... | Scarlett 2i2 Camera                  | 77    | snd_usb... | [EE33A17BAA](<Desktop/ASUSTek Computer/TUF/TUF B450-PLUS GAMING/5071E24FD04D/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/EE33A17BAA>) |
| 1235:8202 | Focusrite-Nov... | Focusrite Scarlett 2i2 2nd Gen       | 69    | snd_usb... | [812906148B](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/205744F95212/KUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/812906148B>) |
| 1235:8205 | Focusrite-Nov... | Scarlett Solo USB                    | 66    | snd_usb... | [3FA24B1A91](<Desktop/Gigabyte Technology/X570/X570 AORUS ULTRA/DE4AD99396B2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3FA24B1A91>) |
| 2972:0047 | FiiO Electron... | USB DAC-E10                          | 65    | snd_usb... | [0295AB04A7](<Desktop/ASRock/B550/B550M-ITX-ac/58A21D9601B8/OPENSUSE-LEAP-15.4/5.14.21-150400.24.55-DEFAULT/X86_64/0295AB04A7>) |
| 046d:0a87 | Logitech         | G935 Gaming Headset                  | 64    | snd_usb... | [C83ED0C49B](<Notebook/Lenovo/ThinkPad/ThinkPad T15 Gen 2i 20W4CTO1WW/C8933F6E73F1/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/C83ED0C49B>) |
| 152a:8750 | Thesycon Syst... | D50s                                 | 60    | snd_usb... | [29ED28536E](<Desktop/ASRock/X370/X370 Gaming-ITX-ac/C8CCD0816161/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/29ED28536E>) |
| 1397:0509 | BEHRINGER Int... | UMC404HD 192k                        | 54    | snd_usb... | [E34348C1B5](<Desktop/MSI/MS-7/MS-7D04/932649C6C043/XUBUNTU-22.10/5.19.0-41-GENERIC/X86_64/E34348C1B5>) |
| 1397:0507 | BEHRINGER Int... | UMC202HD 192k                        | 51    | snd_usb... | [D2FBFE344C](<Desktop/Gigabyte Technology/X79/X79-UD3/D0CFFE9F53C9/FEDORA-38/6.2.10-300.FC38.X86_64/X86_64/D2FBFE344C>) |
| 0b05:1a52 | ASUSTek Computer | USB Audio                            | 49    | snd_usb... | [29B2378B4B](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650E-F GAMING WIFI/B82AA0B20AA7/NIXOS-22.11/6.1.27/X86_64/29B2378B4B>) |
| 041e:322c | Creative Tech... | SB Omni Surround 5.1                 | 47    | snd_usb... | [C5A8CEC4F6](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/4330AC68ACD9/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/C5A8CEC4F6>) |
| 1235:8016 | Focusrite-Nov... | Focusrite Scarlett 2i2               | 47    | snd_usb... | [76748DA9CD](<Desktop/MSI/MS-7/MS-7C95/E2E66E37A3EB/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/76748DA9CD>) |
| 0955:7002 | Nvidia           | stereo controller                    | 46    |            | [2C8AED8334](<Notebook/Dell/System/System XPS L702X/8B4D76523C6F/ROSA-12.4/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/2C8AED8334>) |
| 1397:0508 | BEHRINGER Int... | UMC204HD 192k                        | 42    | snd_usb... | [C38D3E6513](<Notebook/Dell/Inspiron/Inspiron 5458/E8F282A67F65/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/C38D3E6513>) |
| 20b1:3008 | XMOS             | iFi (by AMR) HD USB Audio            | 41    | snd_usb... | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 0b05:1996 | ASUSTek Computer | USB Audio                            | 40    | snd_usb... | [E42327B375](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/402936B429DF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/E42327B375>) |
| 19f7:0015 | RODE Microphones | RODE NT-USB Mini                     | 40    | snd_usb... | [F1F2AD2731](<Desktop/ASUSTek Computer/ROG/ROG STRIX X670E-F GAMING WIFI/33F2EEE05EA7/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/F1F2AD2731>) |
| 0b05:189d | ASUSTek Computer | Xonar SoundCard                      | 36    | usbhid     | [57CC389EFF](<Desktop/Gigabyte Technology/X670/X670 GAMING X AX/B7E5D7EDD611/ARCH-ROLLING/6.2.10-ARCH1-1/X86_64/57CC389EFF>) |
| 0499:170f | Yamaha           | Steinberg UR22mkII                   | 35    | snd_usb... | [A9D1794EEC](<Desktop/MSI/MS-7/MS-7A38/C3487D76EFD3/FEDORA-36/6.1.8-100.FC36.X86_64/X86_64/A9D1794EEC>) |
| b58e:0005 | Blue Microphones | Yeti Nano                            | 35    | snd_usb... | [18C5E3C7C3](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/485130806F6F/RHEL-9/5.14.0-162.22.2.EL9_1.X86_64/X86_64/18C5E3C7C3>) |
| 0b05:180f | ASUSTek Computer | XONAR SOUND CARD                     | 29    | snd_usb... | [1B7398E5E8](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/0651D9942811/SOLYDXK-12/6.1.0-7-AMD64/X86_64/1B7398E5E8>) |
| 0db0:a073 | Micro Star In... | USB Audio                            | 28    | snd_usb... | [8E7095E453](<Desktop/MSI/MS-7/MS-7D54/6DD99ED0BCBF/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/8E7095E453>) |
| 0bda:4c07 | Realtek Semic... | TX-384Khz Hifi Type-C Audio          | 27    | snd_usb... | [A5FF738639](<Desktop/ASRock/Z370/Z370 Gaming K6/873A433A0C20/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/A5FF738639>) |
| 0d8c:0066 | C-Media Elect... | Schiit Modi 3                        | 27    | snd_usb... | [5964CAAA02](<Notebook/Acer/Aspire/Aspire E5-575/A7FCFCC17552/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5964CAAA02>) |
| 0414:a000 | Giga-Byte Tec... | USB Audio                            | 26    | snd_usb... | [A88277B7F9](<Desktop/Gigabyte Technology/TRX40/TRX40 AORUS XTREME/35C9721FE53B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A88277B7F9>) |
| 0414:a001 | Giga-Byte Tec... | USB Audio                            | 26    | snd_usb... | [A88277B7F9](<Desktop/Gigabyte Technology/TRX40/TRX40 AORUS XTREME/35C9721FE53B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A88277B7F9>) |
| 0414:a002 | Giga-Byte Tec... | USB Audio                            | 26    | snd_usb... | [88C24F7E44](<Desktop/Gigabyte Technology/WRX80/WRX80-SU8/428EE4DA675F/UBUNTU-22.10/5.15.0-66-GENERIC/X86_64/88C24F7E44>) |
| 0b05:180d | ASUSTek Computer | STRIX SOUND CARD                     | 26    | snd_usb... | [7226BD3EAB](<Desktop/MSI/MS-7/MS-7B98/93E89D65D248/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/7226BD3EAB>) |
| 1235:8200 | Focusrite-Nov... | Scarlett 2i4 USB                     | 26    | snd_usb... | [06141A871E](<Desktop/ASRock/X470/X470 Master SLI/73C2B6B13620/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/06141A871E>) |
| 1043:857c | iCreate Techn... | Xonar U7                             | 25    | snd_usb... | [7AC461B735](<Desktop/ASUSTek Computer/STRIX/STRIX Z270H GAMING/4C99FC2E61F1/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/7AC461B735>) |
| 26ce:0a01 | ASRock           | USB Audio                            | 25    | snd_usb... | [A810336F3F](<Desktop/ASRock/TRX40/TRX40 Creator/92CB0A816AC8/POP!_OS-22.04/5.17.5-76051705-GENERIC/X86_64/A810336F3F>) |
| 0b05:1a27 | ASUSTek Computer | USB Audio                            | 24    | snd_usb... | [855BED0070](<Desktop/ASUSTek Computer/ROG/ROG Maximus Z690 HERO/5CAC4ACEEE94/GENTOO-2.13/6.3.0-CACHYOS/X86_64/855BED0070>) |
| 0499:170d | Yamaha           | AG06/AG03                            | 23    | snd_usb... | [EF1D9239AB](<Desktop/Alienware/Aurora/Aurora R11/4D2AB33E150D/ZORIN-16/5.15.0-60-GENERIC/X86_64/EF1D9239AB>) |
| 0b05:1918 | ASUSTek Computer | USB Audio                            | 23    | snd_usb... | [09DAE67FD1](<Desktop/ASUSTek Computer/PRIME/PRIME TRX40-PRO/8A5FDDBCD61F/UBUNTU-22.04/5.19.0-37-GENERIC/X86_64/09DAE67FD1>) |
| 17ef:30bb | Lenovo           | ThinkPad Thunderbolt 4 Dock USB A... | 22    | usbhid     | [535B4CA746](<Notebook/Notebook/N141/N141CU/3B78D69E3D0A/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/535B4CA746>) |
| 046d:0a0b | Logitech         | ClearChat Pro USB                    | 21    | snd_usb... | [7AFD2012E8](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G1/6EED3E0EA490/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/7AFD2012E8>) |
| 0d8c:0004 | C-Media Elect... | CM6631A Audio Processor              | 21    | snd_usb... | [71D89005DD](<Desktop/Gigabyte Technology/AB350-Gaming/AB350-Gaming 3/EBAE0A8CED67/ARCH-ROLLING/6.2.10-ZEN1-1-ZEN/X86_64/71D89005DD>) |
| 0b05:1a16 | ASUSTek Computer | USB Audio                            | 20    | snd_usb... | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 0b05:1915 | ASUSTek Computer | USB Audio                            | 19    | usbhid     | [19C80082A1](<Desktop/ASUSTek Computer/ROG/ROG ZENITH II EXTREME/2E30E123A882/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/19C80082A1>) |
| 0b05:1916 | ASUSTek Computer | USB Audio                            | 19    | snd_usb... | [19C80082A1](<Desktop/ASUSTek Computer/ROG/ROG ZENITH II EXTREME/2E30E123A882/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/19C80082A1>) |
| 17ef:30d1 | Lenovo           | ThinkPad USB-C Dock Gen2 USB Audio   | 19    | snd_usb... | [5101F4E19D](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20S0000NRI/E3B6C993F2FB/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/5101F4E19D>) |
| 0499:1703 | Yamaha           | MG-XU                                | 18    | snd_usb... | [4FBB42AFA0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B650E-F GAMING WIFI/AC5A2C87983D/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/4FBB42AFA0>) |
| 0499:170a | Yamaha           | Steinberg UR12                       | 18    | snd_usb... | [A241837604](<Desktop/LTD Delovoy Office/320A3SM/320A3SM MT/67FBE1AE8CE6/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/A241837604>) |
| 0b05:1984 | ASUSTek Computer | USB Audio                            | 18    | snd_usb... | [A82D805AD2](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/9D10B05EF80F/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/A82D805AD2>) |
| 17cc:1001 | Native Instru... | Komplete Audio 6                     | 18    | snd_usb... | [FC2F55C02E](<Desktop/ASUSTek Computer/Pro/Pro WS X570-ACE/A507D7C0F5B4/ARCH-ROLLING/6.1.1-ARCH1-1/X86_64/FC2F55C02E>) |
| 05ac:110a | Apple            | USB-C to 3.5mm Headphone Jack Ada... | 17    | apple_m... | [1CCFDDFBC0](<Desktop/Gigabyte Technology/B450M/B450M S2H/9465C2A6D8FD/ARCH-ROLLING/6.1.14-XANMOD1/X86_64/1CCFDDFBC0>) |
| 0db0:b202 | Micro Star In... | USB Audio                            | 17    | usbhid     | [4CC44F819D](<Desktop/MSI/MS-7/MS-7D32/D539BDD1F72D/DEBIAN-12/6.1.0-7-AMD64/X86_64/4CC44F819D>) |
| 1235:800a | Focusrite-Nov... | Scarlett 2i4                         | 17    | snd_usb... | [04A7CEA7CB](<Desktop/ASRock/X670E/X670E Steel Legend/674C3522ED77/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/04A7CEA7CB>) |
| 152a:85dd | Thesycon Syst... | SMSL USB AUDIO                       | 17    | snd_usb... | [B16E6324ED](<Notebook/HONOR/BBR-WAX/BBR-WAX9/2F4AE263D41F/KDE-NEON-22.04/5.19.0-35-GENERIC/X86_64/B16E6324ED>) |
| 20b1:3023 | XMOS             | aune usb dac                         | 16    | snd_usb... | [28A76B6042](<Desktop/MSI/MS/MS-7978/A9FE7CEA529E/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/28A76B6042>) |

### Bluetooth (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8087:0026 | Intel            | AX201 Bluetooth                      | 7532  | btusb      | [D6C6781535](<Notebook/Avell High Performance/A65/A65 MOB/1D6F35E22C18/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D6C6781535>) |
| 8087:0a2a | Intel            | Bluetooth wireless interface         | 6928  | btusb      | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 8087:0029 | Intel            | AX200 Bluetooth                      | 6773  | btusb      | [AD66608CF0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E039702D1078/CHIMERAOS-41/6.1.21-1-LTS/X86_64/AD66608CF0>) |
| 0a12:0001 | Cambridge Sil... | Bluetooth Dongle (HCI mode)          | 6758  | btusb      | [3CDF8244EF](<Desktop/Acer/Aspire/Aspire M5811/BD71CFB0AF65/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/3CDF8244EF>) |
| 8087:0aaa | Intel            | Bluetooth 9460/9560 Jefferson Pea... | 6670  | btusb      | [535CC48341](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/535CC48341>) |
| 8087:0a2b | Intel            | Bluetooth wireless interface         | 6663  | btusb      | [08DF3C35EE](<Desktop/Dell/OptiPlex/OptiPlex 7040/74B9A8608B3A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/08DF3C35EE>) |
| 8087:07dc | Intel            | Bluetooth wireless interface         | 4334  | btusb      | [CBD0938F3C](<Notebook/Google/Auron_Yuna/Auron_Yuna/8AA8E4B14B50/XUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/CBD0938F3C>) |
| 8087:0aa7 | Intel            | Wireless-AC 3168 Bluetooth           | 2021  | btusb      | [8849D7A1C9](<Notebook/Acer/Aspire/Aspire A315-22/8D36FCBDE2F1/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/8849D7A1C9>) |
| 8087:07da | Intel            | Centrino Bluetooth Wireless Trans... | 1674  | btusb      | [5AFE99ED93](<Notebook/Medion/E/E6234/66BB96E66B62/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/5AFE99ED93>) |
| 0cf3:3005 | Qualcomm Athe... | AR3011 Bluetooth                     | 1602  | btusb      | [99EDE66D8D](<Notebook/ASUSTek Computer/K73/K73SJ/BA1DF2DADB62/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/99EDE66D8D>) |
| 8087:0025 | Intel            | Wireless-AC 9260 Bluetooth Adapter   | 1532  | btusb      | [C7A298018F](<Convertible/Lenovo/ThinkPad/ThinkPad 11e Yoga Gen 6 20SES00200/1485DED24727/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/C7A298018F>) |
| 0cf3:3004 | Qualcomm Athe... | AR3012 Bluetooth 4.0                 | 1487  | ath3k, ... | [DE7D5668D5](<Notebook/Lenovo/G700/G700 20251/D9E47C552B1B/LINUXMINT-20.3/5.4.0-137-GENERIC/X86_64/DE7D5668D5>) |
| 04ca:3015 | Lite-On Techn... | Qualcomm Atheros QCA9377 Bluetooth   | 1480  | btusb      | [D48AFFB6B2](<Notebook/Acer/Aspire/Aspire E5-574/72C42A37942D/ZORIN-16/5.15.0-71-GENERIC/X86_64/D48AFFB6B2>) |
| 0cf3:e500 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 1413  | btusb      | [8BBE8F0A3F](<Notebook/Lenovo/IdeaPad/IdeaPad L340-15API 81LW/8AEA3C0AE9A3/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/8BBE8F0A3F>) |
| 0bda:b00a | Realtek Semic... | Realtek Bluetooth 4.2 Adapter        | 1244  | btusb      | [1D61E5DA8B](<Notebook/Hewlett-Packard/255/255 G8 Notebook PC/2D4B25F24D2B/ROSA-12.4/5.10.176-GENERIC-1ROSA2021.1-X86_64/X86_64/1D61E5DA8B>) |
| 8087:0032 | Intel            | AX210 Bluetooth                      | 1176  | btusb      | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 0cf3:e300 | Qualcomm Athe... | QCA61x4 Bluetooth 4.0                | 991   | btusb      | [100534A570](<Notebook/Dell/XPS/XPS 15 9570/B723043741B6/UBUNTU-UNITY-22.04/5.15.0-57-GENERIC/X86_64/100534A570>) |
| 0cf3:e009 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 986   | btusb      | [F838E48BD3](<Notebook/Dell/Inspiron/Inspiron 5585/C2D030B3EF9D/MANJARO/6.1.26-1-MANJARO/X86_64/F838E48BD3>) |
| 8087:0033 | Intel            | Bluetooth Device                     | 986   | btusb      | [EA808C2E80](<Notebook/Dell/Inspiron/Inspiron 16 Plus 7620/37910A3DDDFF/ARTIX-ROLLING/6.3.1-ARTIX1-1/X86_64/EA808C2E80>) |
| 8086:0189 | Intel            | Centrino Advanced-N 6230 Bluetoot... | 852   | btusb      | [BB84771A09](<Notebook/Samsung Electronics/300V3/300V3A-300V4A-300V5A/745018240E34/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/BB84771A09>) |
| 0bda:b009 | Realtek Semic... | Realtek Bluetooth 4.2 Adapter        | 823   | btusb      | [6A93900FB9](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da0xxx/086AB70E259F/ARCO-ROLLING/6.1.27-1-LTS/X86_64/6A93900FB9>) |
| 0bda:b00c | Realtek Semic... | Bluetooth Radio                      | 823   | btusb      | [0A639BA55D](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dq2xxx/8DCCFC840116/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0A639BA55D>) |
| 05ac:8215 | Apple            | Built-in Bluetooth 2.0+EDR HCI       | 822   | btusb, ... | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 0a5c:217f | Broadcom         | BCM2045B (BDC-2.1)                   | 808   | btusb      | [55756E1659](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2522K3U/FEE106E6195A/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-DEFAULT/X86_64/55756E1659>) |
| 04ca:300b | Lite-On Techn... | Atheros AR3012 Bluetooth             | 755   | ath3k, ... | [AB9FF23D88](<Notebook/Acer/Aspire/Aspire E5-551G/0D9CCBBE9BDD/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/AB9FF23D88>) |
| 0bda:8771 | Realtek Semic... | Bluetooth Radio                      | 708   | btusb      | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 0a5c:21e8 | Broadcom         | BCM20702A0 Bluetooth 4.0             | 697   | btusb      | [BE3DEC1F65](<Notebook/Hewlett-Packard/655/655/0C94F25B3BF3/ZORIN-16/5.15.0-71-GENERIC/X86_64/BE3DEC1F65>) |
| 13d3:3553 | IMC Networks     | 802.11ac WLAN Adapter                | 694   | btusb      | [E6397E7F9F](<Notebook/Valve/Jupiter/Jupiter/DCF5E243D442/STEAMOS-3.4.6/5.13.0-VALVE36-1-NEPTUNE/X86_64/E6397E7F9F>) |
| 03f0:231d | Hewlett-Packard  | Broadcom 2070 Bluetooth Combo        | 686   | btusb      | [8F79A54339](<Notebook/Hewlett-Packard/Pavilion/Pavilion dm4/5FF050311B94/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/8F79A54339>) |
| 0cf3:e005 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 660   | ath3k, ... | [9A510BB01B](<Notebook/Dell/Inspiron/Inspiron 15-3567/60D72C50596C/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/9A510BB01B>) |
| 0cf3:0036 | Qualcomm Athe... | AR9462 Bluetooth                     | 618   | ath3k, ... | [D5F70FC2EB](<Notebook/Dell/Inspiron/Inspiron 5521/B3C0D71F73EB/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/D5F70FC2EB>) |
| 0bda:c123 | Realtek Semic... | Bluetooth Radio                      | 616   | btusb      | [4C3F70E8D3](<Notebook/Lenovo/IdeaPad/IdeaPad 1 15IGL7 82V7/97B6F93508E0/BUNSENLABS-11/5.10.0-22-AMD64/X86_64/4C3F70E8D3>) |
| 0bda:b00b | Realtek Semic... | Realtek Bluetooth 4.2 Adapter        | 613   | btusb      | [CE611516EC](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 13-an0xxx/18AC56B4B084/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/CE611516EC>) |
| 0a5c:21e6 | Broadcom         | BCM20702 Bluetooth 4.0 [ThinkPad]    | 595   | btusb      | [D95CCBF97D](<Notebook/Lenovo/ThinkPad/ThinkPad L530 24812TG/27730FD7F063/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/D95CCBF97D>) |
| 0bda:c024 | Realtek Semic... | Bluetooth Radio                      | 588   | btusb      | [26BB61D72F](<Notebook/Lenovo/IdeaPad/IdeaPad L340-17IRH Gaming 81LL/511177111BBB/ARCH-ROLLING/6.1.26-1-LTS/X86_64/26BB61D72F>) |
| 03f0:171d | Hewlett-Packard  | Bluetooth 2.0 Interface [Broadcom... | 587   | btusb      | [9963ABA3A2](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2530p/5B27555CB81E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/9963ABA3A2>) |
| 0b05:17cb | ASUSTek Computer | Broadcom BCM20702A0 Bluetooth        | 564   | btusb      | [756E372A11](<Desktop/ASUSTek Computer/Z170/Z170-P/BC9CF352F91A/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/756E372A11>) |
| 413c:8187 | Dell             | DW375 Bluetooth Module               | 544   | btusb      | [7A26C45568](<Notebook/Dell/Latitude/Latitude E6420/AC1E7637CF53/UBUNTU-BUDGIE-23.04/6.2.0-20-GENERIC/X86_64/7A26C45568>) |
| 0cf3:e007 | Qualcomm Athe... | Qualcomm Atheros Bluetooth Device    | 530   | btusb      | [4CD3B0701E](<Notebook/Dell/Precision/Precision 7740/F8525F0F515F/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4CD3B0701E>) |
| 13d3:3563 | IMC Networks     | Wireless_Device                      | 516   | btusb      | [679F0C2F88](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TN3402QA_TN3402QA/985AEE5C1866/ARCH-ROLLING/6.1.27-1-LTS/X86_64/679F0C2F88>) |
| 04ca:3016 | Lite-On Techn... | Bluetooth Device                     | 497   | btusb      | [DA1C6920B6](<Notebook/Acer/Aspire/Aspire A715-72G/753782FFE946/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/DA1C6920B6>) |
| 0bda:b728 | Realtek Semic... | RTL8723B Bluetooth                   | 497   | btusb      | [70C3231200](<Notebook/Lenovo/G50-70/G50-70 20351/FDFC1F60D6C7/ORG.KDE.PLATFORM-5.15-21.08/5.15.77-AMD64-DESKTOP/X86_64/70C3231200>) |
| 1358:c123 | Realtek          | Bluetooth Radio                      | 491   | btusb      | [A4F5DCE6D6](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/26116FF2B2E2/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/A4F5DCE6D6>) |
| 13d3:3529 | IMC Networks     | Bluetooth Radio                      | 466   | btusb      | [75FE05267B](<Notebook/ASUSTek Computer/VivoBook_ASUS/VivoBook_ASUS Laptop E410MA_E410MA/DFC1B63712B7/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/75FE05267B>) |
| 13d3:3362 | IMC Networks     | Atheros AR3012 Bluetooth 4.0 Adapter | 464   | ath3k, ... | [B7EB868EC4](<Notebook/ASUSTek Computer/G56/G56JR/3362CC0C3387/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/B7EB868EC4>) |
| 105b:e065 | Foxconn Inter... | BCM43142A0 Bluetooth module          | 451   | btusb      | [8EFA05ADA7](<Notebook/Lenovo/V580c/V580c 20160/0F767C61EAA3/ROSA-12.4/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/8EFA05ADA7>) |
| 05ac:828f | Apple            | Bluetooth USB Host Controller        | 424   | apple_m... | [D681957D5B](<Notebook/Apple/MacBookAir7/MacBookAir7,2/621FFA54E8BE/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D681957D5B>) |
| 0a5c:2101 | Broadcom         | BCM2045 Bluetooth                    | 421   | btusb      | [D655AAD3C5](<Notebook/Acer/TravelMate/TravelMate 6592/87C8AD6BC8DB/UBUNTU-21.04/5.11.0-49-GENERIC/X86_64/D655AAD3C5>) |
| 0bda:0821 | Realtek Semic... | Bluetooth Radio                      | 409   | btusb      | [AD9AF07A7C](<Notebook/Lenovo/IdeaPad/IdeaPad 700-15ISK 80RU/7B6DB8580B80/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/AD9AF07A7C>) |
| 0489:e04e | Foxconn / Hon... | Bluetooth Device                     | 386   | ath3k, ... | [37F3DA239A](<Desktop/MSI/MS/MS-7693/C85B0030F9F4/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/37F3DA239A>) |

### Camera (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:0825 | Logitech         | Webcam C270                          | 1619  | snd_usb... | [31123C256D](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/58F18DE5017C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/31123C256D>) |
| 04e8:6860 | Samsung Elect... | Galaxy A5 (MTP)                      | 1070  | usbfs      | [100534A570](<Notebook/Dell/XPS/XPS 15 9570/B723043741B6/UBUNTU-UNITY-22.04/5.15.0-57-GENERIC/X86_64/100534A570>) |
| 046d:082d | Logitech         | HD Pro Webcam C920                   | 989   | snd_usb... | [D6C6781535](<Notebook/Avell High Performance/A65/A65 MOB/1D6F35E22C18/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D6C6781535>) |
| 05ac:12a8 | Apple            | iPhone 5/5C/5S/6/SE/7/8/X            | 961   | apple_m... | [81024F3DF4](<Notebook/Dell/G15/G15 5520/490AF523329C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/81024F3DF4>) |
| 13d3:5a11 | IMC Networks     | USB2.0 VGA UVC WebCam                | 833   | uvcvideo   | [75FE05267B](<Notebook/ASUSTek Computer/VivoBook_ASUS/VivoBook_ASUS Laptop E410MA_E410MA/DFC1B63712B7/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/75FE05267B>) |
| 13d3:56a2 | IMC Networks     | USB2.0 HD UVC WebCam                 | 727   | uvcvideo   | [F23FB5CCA0](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DT_FX505DT/69E8EF1A2769/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/F23FB5CCA0>) |
| 0408:a061 | Quanta           | HD User Facing                       | 668   | uvcvideo   | [EFB597952F](<Notebook/Acer/Predator/Predator PH315-53/4785A8A66BF1/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/EFB597952F>) |
| 0408:a031 | Quanta           | VGA WebCam                           | 528   | uvcvideo   | [8849D7A1C9](<Notebook/Acer/Aspire/Aspire A315-22/8D36FCBDE2F1/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/8849D7A1C9>) |
| 05ac:8509 | Apple            | FaceTime HD Camera                   | 521   | uvcvideo   | [A8D45AC430](<Notebook/Apple/MacBookPro9/MacBookPro9,2/F2D429C722A3/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/A8D45AC430>) |
| 04f2:b604 | Chicony Elect... | Integrated Camera (1280x720@30)      | 515   | uvcvideo   | [C7CA4B1477](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NK000XBR/F2FC8D92167B/DEBIAN-12/6.1.0-7-AMD64/X86_64/C7CA4B1477>) |
| 5986:2113 | Bison Electro... | SunplusIT Integrated Camera          | 507   | uvcvideo   | [00DF9B6BDA](<Notebook/Lenovo/Legion/Legion Y540-15IRH 81SX/5F4D0AB0905E/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/00DF9B6BDA>) |
| 058f:5608 | Alcor Micro      | USB 2.0 Camera                       | 488   | uvcvideo   | [3174C98E9C](<Notebook/AXDIA International/MYBOOK/MYBOOK 14 PRO/EBB0FDA86030/DEBIAN-11/5.10.0-22-AMD64/X86_64/3174C98E9C>) |
| 0c45:6723 | Microdia         | Integrated_Webcam_HD                 | 485   | uvcvideo   | [8B7B41FDE9](<Notebook/Dell/XPS/XPS 13 9305/E38BCB8078FB/LUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/8B7B41FDE9>) |
| 04f2:b64f | Chicony Elect... | HD User Facing                       | 484   | uvcvideo   | [B76E0E7397](<Notebook/Acer/TravelMate/TravelMate P215-52/1476848F2943/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/B76E0E7397>) |
| 13d3:5a01 | IMC Networks     | USB2.0 VGA UVC WebCam                | 479   | uvcvideo   | [326309C1F1](<Notebook/ASUSTek Computer/X441/X441BA/6A6FA7D22C7E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/326309C1F1>) |
| 064e:a103 | Suyin            | Acer/HP Integrated Webcam [CN0314]   | 470   | uvcvideo   | [EC45EA6206](<Notebook/Acer/Aspire/Aspire 5732Z/1DEB04C271AA/LINUXMINT-20.2/5.4.0-148-GENERIC/X86_64/EC45EA6206>) |
| 0c45:6366 | Microdia         | Webcam Vitade AF                     | 466   | uvcvideo   | [535CC48341](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/535CC48341>) |
| 0408:5365 | Quanta           | HP TrueVision HD Camera              | 458   | uvcvideo   | [A5252D48F3](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-eq0xxx/F1F952DDF238/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/A5252D48F3>) |
| 05ac:8507 | Apple            | Built-in iSight                      | 442   | uvcvideo   | [8349B363F4](<Notebook/Apple/MacBookPro7/MacBookPro7,1/7557BCDCDBF4/MX-21/5.10.0-22-AMD64/X86_64/8349B363F4>) |
| 0c45:671e | Microdia         | Integrated_Webcam_HD                 | 423   | uvcvideo   | [6E70E21E58](<Notebook/Dell/Inspiron/Inspiron 3501/7D36F1F4C348/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/6E70E21E58>) |
| 0ac8:3420 | Z-Star Microe... | Venus USB2.0 Camera                  | 414   | snd_usb... | [E35780D356](<Notebook/Lenovo/IdeaPad/IdeaPad Y510P 20217/9DA8B287B80B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E35780D356>) |
| 13d3:56ff | IMC Networks     | Integrated Camera                    | 401   | uvcvideo   | [ACD4C4AF90](<Notebook/Lenovo/Legion/Legion 5 15ACH6H 82JU/FE76F9E581AF/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/ACD4C4AF90>) |
| 0408:a060 | Quanta           | HD Webcam                            | 393   | uvcvideo   | [DA1C6920B6](<Notebook/Acer/Aspire/Aspire A715-72G/753782FFE946/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/DA1C6920B6>) |
| 05ac:8502 | Apple            | Built-in iSight                      | 391   | uvcvideo   | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 13d3:56b2 | IMC Networks     | Integrated Camera                    | 391   | uvcvideo   | [0D2AC684C8](<Notebook/Lenovo/IdeaPad/IdeaPad 530S-14ARR 81H1/40E4E0D39D59/DEVUAN-4/6.1.25/X86_64/0D2AC684C8>) |
| 1bcf:2c18 | Sunplus Innov... | HD WebCam                            | 383   | uvcvideo   | [58F420D816](<Notebook/Acer/NC-V3/NC-V3-772G-747A8G1TMAKK/F9DA5737F0AA/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/58F420D816>) |
| 046d:081b | Logitech         | Webcam C310                          | 374   | snd_usb... | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 046d:085c | Logitech         | C922 Pro Stream Webcam               | 374   | snd_usb... | [C41D566374](<Notebook/Timi/TM/TM1701/43BDC946763C/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/C41D566374>) |
| 5986:0295 | Acer             | Lenovo Integrated Webcam             | 362   | uvcvideo   | [DE7D5668D5](<Notebook/Lenovo/G700/G700 20251/D9E47C552B1B/LINUXMINT-20.3/5.4.0-137-GENERIC/X86_64/DE7D5668D5>) |
| 046d:0826 | Logitech         | HD Webcam C525                       | 348   | uvcvideo   | [AED14C1E20](<Desktop/Acer/Aspire/Aspire M3920/25FDE4FC074D/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/AED14C1E20>) |
| 1bcf:2883 | Sunplus Innov... | Asus Webcam                          | 344   | uvcvideo   | [09E73CADE8](<Notebook/ASUSTek Computer/K45/K45VM/F2935172AC16/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/09E73CADE8>) |
| 0c45:6340 | Microdia         | Camera                               | 330   | snd_usb... | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 5986:9102 | Bison Electro... | BisonCam,NB Pro                      | 328   | uvcvideo   | [72D9DAC16B](<Notebook/PC Specialist/NP5/NP5x_NP6x_NP7xPNP/AF55848BA941/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/72D9DAC16B>) |
| 04f2:b230 | Chicony Elect... | Integrated HP HD Webcam              | 326   | uvcvideo   | [480E352BF8](<Notebook/Hewlett-Packard/ProBook/ProBook 6570b/D0A579C1EB74/ZORIN-16/5.15.0-71-GENERIC/X86_64/480E352BF8>) |
| 0402:9665 | ALi              | Gateway Webcam                       | 325   | uvcvideo   | [D37B9E6687](<Notebook/Packard Bell/EasyNote/EasyNote LM85/017D6D3021DD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/D37B9E6687>) |
| 05ac:8511 | Apple            | FaceTime HD Camera (Built-in)        | 325   | uvcvideo   | [C8C9C1E591](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF/DEBIAN-11/5.10.0-21-AMD64/X86_64/C8C9C1E591>) |
| 0c45:62c0 | Microdia         | Sonix USB 2.0 Camera                 | 324   | uvcvideo   | [90D59AC61A](<Notebook/Acer/Aspire/Aspire one/169FF7066084/UBUNTU-MATE-18.04/5.4.0-148-GENERIC/I686/90D59AC61A>) |
| 04f2:b52b | Chicony Elect... | USB2.0 VGA UVC WebCam                | 316   | uvcvideo   | [7C6C0C9599](<Notebook/ASUSTek Computer/Z550/Z550SA/6E3A6C873646/LMDE-5/5.10.0-21-AMD64/X86_64/7C6C0C9599>) |
| 04f2:b217 | Chicony Elect... | Lenovo Integrated Camera (0.3MP)     | 314   | uvcvideo   | [6290E7F2FB](<Notebook/Lenovo/ThinkPad/ThinkPad T520 4242A25/D0EDD3D0B834/ZORIN-16/5.15.0-71-GENERIC/X86_64/6290E7F2FB>) |
| 04f2:b47f | Chicony Elect... | VGA Webcam                           | 310   | uvcvideo   | [9C88DE8A31](<Notebook/Acer/Aspire/Aspire ES1-711/D28746E6D958/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/9C88DE8A31>) |
| 13d3:56dd | IMC Networks     | USB2.0 HD UVC WebCam                 | 300   | uvcvideo   | [925B5748B9](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X712FAC_X712FA/C1CF8DE226DD/LINUXMINT-20.2/5.4.0-148-GENERIC/X86_64/925B5748B9>) |
| 058f:a014 | Alcor Micro      | Asus Integrated Webcam               | 296   | uvcvideo   | [4114D6E81C](<Notebook/ASUSTek Computer/K54/K54HR/E28D554E86AB/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/4114D6E81C>) |
| 0bda:57b5 | Realtek Semic... | USB Camera                           | 296   | uvcvideo   | [FEBE8D60FC](<Notebook/ASUSTek Computer/X555/X555LJ/287C0142E54D/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/FEBE8D60FC>) |
| 04ca:7070 | Lite-On Techn... | Integrated Camera                    | 295   | uvcvideo   | [678B4CA4ED](<Notebook/Lenovo/Legion/Legion Y540-17IRH 81Q4/F5BC18F8B347/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/678B4CA4ED>) |
| 04f2:b1d6 | Chicony Elect... | CNF9055 Toshiba Webcam               | 289   | uvcvideo   | [E80DAAA2A0](<Notebook/Toshiba/Satellite/Satellite C660/7D2F74AA85E4/LINUXMINT-20.3/5.4.0-139-GENERIC/X86_64/E80DAAA2A0>) |
| 046d:082b | Logitech         | Webcam C170                          | 287   | snd_usb... | [7AC436D763](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92P 3227BD2/791575E45E29/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/7AC436D763>) |
| 04f2:b6d9 | Chicony Elect... | Integrated Camera                    | 280   | uvcvideo   | [C7A298018F](<Convertible/Lenovo/ThinkPad/ThinkPad 11e Yoga Gen 6 20SES00200/1485DED24727/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/C7A298018F>) |
| 045e:0779 | Microsoft        | LifeCam HD-3000                      | 277   | snd_usb... | [679F0C2F88](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TN3402QA_TN3402QA/985AEE5C1866/ARCH-ROLLING/6.1.27-1-LTS/X86_64/679F0C2F88>) |
| 13d3:5710 | IMC Networks     | UVC VGA Webcam                       | 276   | uvcvideo   | [99EDE66D8D](<Notebook/ASUSTek Computer/K73/K73SJ/BA1DF2DADB62/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/99EDE66D8D>) |
| 04f2:b61e | Chicony Elect... | Integrated Camera                    | 274   | uvcvideo   | [ABC9CE4FA4](<Notebook/Lenovo/ThinkBook/ThinkBook 13s-IWL 20R9/2E8FC5060A14/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/ABC9CE4FA4>) |

### Card reader (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:0129 | Realtek Semic... | RTS5129 Card Reader Controller       | 12113 | rtsx_usb   | [535CC48341](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/535CC48341>) |
| 0bda:0139 | Realtek Semic... | RTS5139 Card Reader Controller       | 1181  | rtsx_usb   | [A799667521](<Notebook/ASUSTek Computer/N550/N550JK/C9A4FBC6CC20/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/A799667521>) |
| 04b4:521a | Cypress Semic... | USB-I2C Bridge                       | 71    |            | [1F2D88BFAE](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 4 21ECS00000/642B185E080D/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/1F2D88BFAE>) |
| 17ef:a38f | Lenovo           | 40AS                                 | 69    | usbhid     | [442A827555](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 4 21ECS00000/642B185E080D/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/442A827555>) |
| 04b4:5218 | Cypress Semic... | USB-Serial Bridge                    | 56    |            | [8A80FD7103](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 3 21AHCTO1WW/3D5B408DCD5C/UBUNTU-BUDGIE-22.04/5.19.0-40-GENERIC/X86_64/8A80FD7103>) |
| 17ef:3075 | Lenovo           | USB Billboard Device                 | 55    |            | [B8A363F717](<Notebook/Lenovo/ThinkPad/ThinkPad T580 20L9CTO1WW/3E2D6C9C7C0A/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/B8A363F717>) |
| 0aec:3260 | Neodio Techno... | 7-in-1 Card Reader                   | 37    | uas, us... | [48EE58DE23](<Desktop/Itautec/Infoway/Infoway ST-4254/CE29C9FBC95A/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/48EE58DE23>) |
| 0c4b:0501 | Reiner SCT Ka... | cyberJack RFID comfort dual inter... | 36    | usbfs      | [4D78DBBDC6](<Desktop/ASUSTek Computer/P5Q/P5Q SE-R/2575946B74AB/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/4D78DBBDC6>) |
| 2ce3:9563 | Alcorlink        | EMV Smartcard Reader                 | 32    | usbfs      | [09D6D7E570](<Notebook/Lenovo/ThinkPad/ThinkPad T16 Gen 1 21BWS11T00/C1BBBC3D6430/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/09D6D7E570>) |
| 0c4b:0500 | Reiner SCT Ka... | cyberJack RFID standard dual inte... | 28    | usbfs      | [58DFB135E4](<Desktop/ASRock/N68-GS4/N68-GS4 FX/420803E3ACAF/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/58DFB135E4>) |
| 072f:9000 | Advanced Card... | ACR38 AC1038-based Smart Card Reader | 21    | usbfs      | [DB058DF07B](<Notebook/Lenovo/V110-15ISK/V110-15ISK 80TL/4B7EA1D625ED/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/DB058DF07B>) |
| 0d8c:5200 | C-Media Elect... | Mass Storage Controller(0D8C,5200)   | 19    |            | [4E46D903AE](<Desktop/Pegatron/IPMIP-GS/IPMIP-GS/0CDCE6CCCEE7/LINUXMINT-20.1/5.4.0-128-GENERIC/X86_64/4E46D903AE>) |
| 0cf2:6250 | ENE Technology   | SD card reader (UB6250)              | 15    | ums_ene... | [1B65896663](<Notebook/Acer/AOD/AOD255/AE6E7A450EF4/BUNSENLABS-11/5.10.0-21-686-PAE/I686/1B65896663>) |
| 0ca6:0010 | Castles Techn... | EZUSB PC/SC Smart Card Reader        | 13    | usbfs      | [EA25A3CC88](<Desktop/Acer/Aspire/Aspire X5950/F8C1EDA60C7C/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/EA25A3CC88>) |
| 0b97:7732 | O2 Micro         | Smart Card Reader                    | 10    |            | [19DC89049D](<Desktop/Hewlett-Packard/Compaq/Compaq dc7600 Small Form Factor/171FB7F56D52/DEBIAN-11/5.10.0-11-AMD64/X86_64/19DC89049D>) |
| 0bda:0150 | Realtek Semic... | Realtek USB 2.0 Card Reader          | 6     | usb_sto... | [4A91953DCB](<Desktop/ASRock/X570/X570 Phantom Gaming 4/19183E7D45F9/LINUXMINT-20.3/5.13.0-39-GENERIC/X86_64/4A91953DCB>) |
| 04e6:e003 | SCM Microsystems | SPR532 PinPad SmartCard Reader       | 5     | usbfs      | [7F89D71E2E](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/AF35E7F8C107/ORG.KDE.PLATFORM-5.15-21.08/6.0.10/X86_64/7F89D71E2E>) |
| 0b0c:003f | Todos AB         | Todos C400 smartcard controller (... | 5     |            | [EFB40BE4E1](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/675615F8D94B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/EFB40BE4E1>) |
| 04e6:511a | SCM Microsystems | SCR3310-NTTCom USB SmartCard Reader  | 4     | usbfs      | [A97C12B513](<Desktop/ASUSTek Computer/PRO/PRO H410M-C/ABEF71E577AC/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A97C12B513>) |
| 04e6:5810 | SCM Microsystems | uTrust 2700 R Smart Card Reader      | 4     | usbfs      | [5A709F059C](<Desktop/ASRock/H470M/H470M Pro4/1EC764406E91/DEBIAN-11/5.10.0-15-AMD64/X86_64/5A709F059C>) |
| 17ef:3078 | Lenovo           | USB Billboard                        | 4     |            | [FF0997B72A](<Notebook/Lenovo/ThinkPad/ThinkPad L590 20Q700AWBM/7F04B53EACA8/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/FF0997B72A>) |
| 04e6:512b | SCM Microsystems | SDI011 Contactless Reader            | 3     |            | [7CF3758630](<Desktop/MSI/MS-7/MS-7B86/B90AD7D7FF07/UBUNTU-21.04/5.11.0-31-GENERIC/X86_64/7CF3758630>) |
| 076b:0596 | OmniKey          | CardMan 2020                         | 3     |            | [A17449F761](<Desktop/ASRock/X670E/X670E Pro RS/F993F20C9215/GENTOO-2.13/6.3.1-GENTOO-X86_64/X86_64/A17449F761>) |
| 0cf2:6220 | ENE Technology   | SD Card Reader (SG361)               | 3     | uas, us... | [C9AC6EB940](<Desktop/Gigabyte Technology/M52/M52S-S3P/9FD6650D13F4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C9AC6EB940>) |
| 11c5:0521 | Inmax            | IMT-0521 Smartcard Reader            | 3     |            | [10C83DEAA9](<Desktop/ASUSTek Computer/P7/P7P55D/D4D4068DBF5C/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/10C83DEAA9>) |
| 174f:1105 | Syntek           | SM-MS/Pro-MMC-XD Card Reader         | 3     | uvcvideo   | [B0B1659E5A](<Notebook/Hewlett-Packard/Mini/Mini 110-1000/D41F7AC4A974/ZORIN-15/5.4.0-45-GENERIC/I686/B0B1659E5A>) |
| 062d:0001 | Taiwan Tai-Ha... | Smart Card Reader                    | 2     | usbfs      | [DD8F32A8D6](<Desktop/MSI/MS-7/MS-7B86/8BE19FF1B402/ARCH-ROLLING/5.12.3-ARCH1-1/X86_64/DD8F32A8D6>) |
| 047b:020b | Silitek          | SK-3105 SmartCard Reader             | 1     | usbhid     | [986AC800BA](<Desktop/Dell/OptiPlex/OptiPlex 3010/5FA9C2F2A894/UBUNTU-18.04/4.15.0-50-GENERIC/X86_64/986AC800BA>) |
| 04e6:2004 | SCM Microsystems | SLB ReflexUSB SmartCard Reader       | 1     |            | [7ACE6808A8](<Desktop/Dell/OptiPlex/OptiPlex 7020/B7AFDA12AC9D/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/7ACE6808A8>) |
| 04e6:5151 | SCM Microsystems | SCR338 Keyboard Smart Card Reader    | 1     | usbhid     | [BD73A86E1F](<Notebook/Dell/Latitude/Latitude E7440/E5F9C0AE9C43/POP!_OS-20.10/5.8.0-7642-GENERIC/X86_64/BD73A86E1F>) |
| 08e6:0435 | Gemalto (was ... | GemPC435 SmartCard Reader            | 1     |            | [2F6BCE8773](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G2/8D1B4AD5F2F1/KDE-NEON-20.04/5.13.0-44-GENERIC/X86_64/2F6BCE8773>) |
| 0c45:1018 | Microdia         | Compact Flash storage memory card... | 1     |            | [696C2127B6](<Desktop/Lenovo/H520S/H520S 10093/1E6D75332EB5/UBUNTU-19.04/5.0.0-25-GENERIC/X86_64/696C2127B6>) |
| 1667:001a | GIGA-TMS         | MagStripe Card Reader                | 1     | usbhid     | [F40A4B7BAC](<Desktop/Panasonic/JS-970/JS-970WS0018/A1766F006B7A/UBUNTU-20.04/5.4.0-26-GENERIC/X86_64/F40A4B7BAC>) |
| 23e7:0006 | Roger sp.j       | EM Card Reader                       | 1     | usbhid     | [0AD2E974BA](<Convertible/Dell/Latitude/Latitude 7330/EAB8DDF25AE4/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/0AD2E974BA>) |

### Cdrom (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0e8d:1887 | MediaTek         | Slim Portable DVD Writer             | 412   | usb_sto... | [77F87DA085](<Desktop/ASRock/H61/H61M-HVS/422642738D60/KDE-NEON-22.04/5.19.0-40-GENERIC/X86_64/77F87DA085>) |
| 12d1:107e | Huawei Techno... | P10 smartphone                       | 223   | uas, us... | [140E5EB8FC](<Notebook/Acer/Aspire/Aspire ES1-731/E23518D72008/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/140E5EB8FC>) |
| 0e8d:1806 | MediaTek         | Samsung SE-208 Slim Portable DVD ... | 219   | usb_sto... | [2A7D35CC4E](<Notebook/ASUSTek Computer/X401/X401A1/D8806E05B716/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/2A7D35CC4E>) |
| 1c6b:a223 | Philips & Lit... | DVD Writer Slimtype eUAU108          | 165   | usb_sto... | [F7709C23A1](<Desktop/MSI/MS-7/MS-7C83/92373390FD01/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/F7709C23A1>) |
| 13fd:3940 | Initio           | external DVD burner ECD819-SU3       | 93    | uas, us... | [2063D4A9FC](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401IV/301AEC1FA106/NIXOS-23.05/6.1.24/X86_64/2063D4A9FC>) |
| 152e:2571 | LG (HLDS)        | GP08NU6W DVD-RW                      | 90    | uas, us... | [DB983DA641](<Desktop/MSI/MS-7/MS-7A93/B3E33AA93032/LINUXMINT-21/5.15.0-71-GENERIC/X86_64/DB983DA641>) |
| 0e8d:1836 | MediaTek         | Samsung SE-S084 Super WriteMaster... | 77    | usb_sto... | [EF975644AD](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO EDITION P2511/B65A7ADB931B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/EF975644AD>) |
| 174c:1351 | ASMedia Techn... | DVDRW DA8AESH                        | 62    | uas, us... | [E4FD112564](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/37F739C18F0A/LINUXMINT-20.3/5.4.0-80-GENERIC/X86_64/E4FD112564>) |
| 152e:1640 | LG (HLDS)        | INIC-1605 SATA Bridge                | 61    | usb_sto... | [9A4BA61D41](<Notebook/Dell/Precision/Precision 5510/6065C667D1D1/FEDORA-38/6.2.14-703.INTTF.FC38.X86_64/X86_64/9A4BA61D41>) |
| 046b:ff20 | American Mega... | Virtual CDROM0                       | 56    | uas, us... | [19C318242F](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-20.04/5.15.0-1023-NVIDIA/X86_64/19C318242F>) |
| 152e:2507 | LG (HLDS)        | PL-2507 IDE Controller               | 50    | uas, us... | [01452C33D1](<Desktop/MSI/MS-7/MS-7B29/5A661AEBFB64/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/01452C33D1>) |
| 08e4:017a | Pioneer          | BD-RW BDR-XS07U                      | 47    | usb_sto... | [A82D805AD2](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/9D10B05EF80F/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/A82D805AD2>) |
| 0b05:7774 | ASUSTek Computer | Zenfone GO (ZB500KL) (RNDIS mode)    | 45    | rndis_host | [679DC6CBC8](<Tablet/ASUSTek Computer/ROG/ROG Flow Z13 GZ301VV_GZ301VV/7B1518D4CC86/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/679DC6CBC8>) |
| 0928:0010 | PLX Technology   | Virtual CDRom                        | 42    | uas, us... | [91930613CB](<Desktop/ASRock/H510M-HDV/H510M-HDV R2.0/FECBCACE2587/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/91930613CB>) |
| 0e8d:1956 | MediaTek         | Samsung SE-506 Portable BluRay Di... | 41    | usb_sto... | [47388F4553](<Desktop/Gigabyte Technology/X570S/X570S AORUS PRO AX/82196083E848/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/47388F4553>) |
| 1058:1110 | Western Digit... | My Book Essential (WDBAAF), My Bo... | 40    | uas, us... | [8D99EF5CC7](<Desktop/Gigabyte Technology/EP45/EP45-UD3P/A4718241208A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/8D99EF5CC7>) |
| 13fd:0940 | Initio           | ASUS SBW-06D2X-U                     | 37    | uas, us... | [AD8009E647](<Desktop/MSI/MS-7/MS-7A32/C07C53EB0598/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/AD8009E647>) |
| 13fd:3e40 | Initio           | ZALMAN ZM-VE350                      | 34    | uas, us... | [A7A0059437](<Desktop/Kllisre x79p V1.0/Socket/Socket LGA-2011/45D4172C4F20/ROSA-2016.1/5.4.32-GENERIC-2ROSA-X86_64/X86_64/A7A0059437>) |
| 12d1:107f | Huawei Techno... | File-CD Gadget                       | 32    | uas, us... | [1C982255FA](<Desktop/Gigabyte Technology/A320/A320M-S2H/C283329DDD8B/LINUXMINT-21/5.15.0-69-GENERIC/X86_64/1C982255FA>) |
| 2e04:c025 | HMD Global       | Nokia 8 (MTP mode)                   | 31    | uas, us... | [2B3F00AC79](<Desktop/ASRock/X79/X79 Extreme6/6813C1E7BD55/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/2B3F00AC79>) |
| 13fd:2040 | Initio           | Samsung Writemaster external DVD ... | 30    | usb_sto... | [4DB9E36520](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX2/AAC10DE05D08/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/4DB9E36520>) |
| 413c:9016 | Dell             | DVD+/-RW DW316                       | 30    | usb_sto... | [946F48CDF6](<Desktop/Dell/OptiPlex/OptiPlex 3050/F8CF98340F55/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/946F48CDF6>) |
| 05ac:1500 | Apple            | SuperDrive [A1379]                   | 29    | apple_m... | [5F8E33221F](<Desktop/BESSTAR Tech/UM/UM700/4F4B52544A49/LINUXMINT-21/5.15.0-60-GENERIC/X86_64/5F8E33221F>) |
| 2a70:f003 | OnePlus          | Device Driver                        | 29    | uas, us... | [B954E4C174](<Desktop/Dell/OptiPlex/OptiPlex 5070/B929F0B35D3F/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/B954E4C174>) |
| 0fe6:9702 | ICS Advent       | Supereal VR DISK                     | 26    | uas, us... | [F1537BEEDF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/8ED828060896/RASPBIAN-12/6.1.21-V7+/ARMV7L/F1537BEEDF>) |
| 12d1:1082 | Huawei Techno... | File-CD Gadget                       | 24    | uas, us... | [6B190BFB4F](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 2 11JAS0CJ00/C5ED616588A2/MX-21/5.10.0-19-AMD64/X86_64/6B190BFB4F>) |
| 13fd:0842 | Initio           | CDDVDW SE-S084C                      | 24    | usb_sto... | [065D244D4B](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS D4/13AC23CEE362/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/065D244D4B>) |
| 1c6b:a222 | Philips & Lit... | DVD Writer Slimtype eTAU108          | 23    | uas, us... | [9D48F53259](<Notebook/Samsung Electronics/300E5/300E5M-300E5L/34B2FC27D683/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/9D48F53259>) |
| 8564:8000 | Transcend        | TRANSCEND                            | 19    | usb_sto... | [7967ED6E8F](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/EC5C2E28D829/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/7967ED6E8F>) |
| 05c6:f000 | Qualcomm         | TA-1004 [Nokia 8]                    | 18    | uas, us... | [ADA19DBE5C](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ITL05 82HS/0B2D78C706F6/FEDORA-37/6.2.9-200.FC37.X86_64/X86_64/ADA19DBE5C>) |
| 0624:0251 | Avocent          | Virtual Mass Storage                 | 18    | uas, us... | [8EF63CB2DE](<Server/Dell/PowerEdge/PowerEdge T420/B103D6C87C65/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8EF63CB2DE>) |
| 054c:02d5 | Sony             | DVD-RAM UJ862PS                      | 17    | uas, us... | [5986F007C8](<Notebook/Sony/VGN-TZ3/VGN-TZ3RXN_B/E747799E7B11/MX-21/5.10.0-19-AMD64/X86_64/5986F007C8>) |
| 05e3:0719 | Genesys Logic    | SATA adapter                         | 16    | uas, us... | [6E08BAAB68](<Server/Supermicro/X8/X8DT6/6ED912FEA9B2/DEBIAN-11/5.15.83-1-PVE/X86_64/6E08BAAB68>) |
| 067b:2571 | Prolific Tech... | LG Electronics GE24LU21              | 16    | uas, us... | [98B6981431](<Desktop/ZOTAC/NM/NM10/FD0FB1E859E9/LUBUNTU-22.04/6.1.0-CUSTOM/X86_64/98B6981431>) |
| 14dd:0002 | Raritan Computer | Multidevice                          | 16    | usbhid     | [49E545591C](<Desktop/Supermicro/X7/X7DCL/8458DFB4B063/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/49E545591C>) |
| 152d:2561 | JMicron Techn... | CEB-2235S-U3 external RAID box       | 16    | uas        | [1E2EDA446C](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/611B709487FE/DEBIAN-11/5.10.0-18-AMD64/X86_64/1E2EDA446C>) |
| 04e8:685b | Samsung Elect... | GT-I9100 Phone [Galaxy S II] (mas... | 15    | uas, us... | [2AD477EA6C](<Server/Hewlett-Packard/Z8/Z8 G4 Workstation/5E9B675190B8/ZORIN-16/5.15.0-67-GENERIC/X86_64/2AD477EA6C>) |
| 0930:0c05 | Toshiba          | DVD-RAM UJ-844S                      | 15    | usb_sto... | [52FFE609B8](<Notebook/Toshiba/Satellite/Satellite R630/BCA2D646BB60/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/52FFE609B8>) |
| 054c:0377 | Sony             | BD ROM BC-5500A                      | 14    | uas, us... | [06B355E1DE](<Notebook/Sony/VGN-FW11/VGN-FW11M/D2F748074AE8/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/06B355E1DE>) |
| 0ecd:a100 | Lite-On IT       | LDW-411SX DVD/CD Rewritable Drive    | 14    | uas, us... | [A5DD0E262B](<Notebook/Dell/Inspiron/Inspiron M5030/34DCD85952B6/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/A5DD0E262B>) |
| 12d1:107d | Huawei Techno... | SDM450-MTP _SN:73B38521              | 14    | rndis_host | [8B44A7DEAA](<Desktop/ASUSTek Computer/All/All Series/3DE7E0A2350F/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/8B44A7DEAA>) |
| 13fd:3609 | Initio           | BD-RE BU40N                          | 14    | usb_sto... | [3C8B130AF7](<Notebook/ASUSTek Computer/X750/X750JN/7F93078FEDBD/FEDORA-36/6.0.5-200.FC36.X86_64/X86_64/3C8B130AF7>) |
| 0411:01dc | BUFFALO          | Ultra-Slim Portable DVD Writer (D... | 13    | usb_sto... | [BCA19A22D8](<Mini Pc/AZW/SER/SER/ADC83AE35DCB/MANJARO/6.2.0-AMD/X86_64/BCA19A22D8>) |
| 04b7:0100 | Compal Electr... | DVDRW GUE1N                          | 13    | uas, us... | [50F90C0B1F](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ca0xxx/4C904A930D47/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.9-1-DEFAULT/X86_64/50F90C0B1F>) |
| 0e8d:1807 | MediaTek         | DVDRAM GP40NB40                      | 13    | usb_sto... | [C123FDBB81](<Desktop/ASUSTek Computer/ROG/ROG Strix GA35DX_G35DX/F2DFBFFC8B3F/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/C123FDBB81>) |
| 0409:0056 | NEC Computers    | CD/DVDW SH-S162L                     | 12    | usb_sto... | [C97E42E738](<Desktop/Dell/OptiPlex/OptiPlex 790/7D35C6F50C30/LINUXMINT-20.3/5.4.0-131-GENERIC/X86_64/C97E42E738>) |
| 0781:5535 | SanDisk          | Ultra Backup                         | 12    | uas, us... | [BEA8C0162F](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv2500/5752828D89E8/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/BEA8C0162F>) |
| 13fd:0841 | Initio           | Samsung SE-T084M DVD-RW              | 12    | usb_sto... | [D3AE118E3B](<Desktop/Gigabyte Technology/B75/B75M-D3V/C035C8B1649A/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/D3AE118E3B>) |
| 2a70:9011 | OnePlus Techn... | Device Driver                        | 12    | usb_sto... | [04AFA2E378](<Notebook/Lenovo/Legion/Legion 5 Pro 16ACH6 82JS/B86824EF148B/MANJARO-22.1.0/6.2.8-1-MANJARO/X86_64/04AFA2E378>) |
| 05c6:9039 | Qualcomm         | Android                              | 11    | usbfs      | [AF99FFB577](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58e 7303BZ2/523EA72F775E/ENDLESS-4.0.4/5.11.0-35-GENERIC/X86_64/AF99FFB577>) |

### Chipcard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 058f:9540 | Alcor Micro      | AU9540 Smartcard Reader              | 2029  | usbfs      | [F945EC106E](<Notebook/Lenovo/ThinkPad/ThinkPad T440 20B7A0CYFR/BE159E2FFF98/DEBIAN-11/5.10.0-21-AMD64/X86_64/F945EC106E>) |
| 0a5c:5800 | Broadcom         | BCM5880 Secure Applications Proce... | 1353  | usbfs      | [535FD92F64](<Notebook/Dell/Latitude/Latitude E6410/89B0555A8505/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/535FD92F64>) |
| 0a5c:5801 | Broadcom         | BCM5880 Secure Applications Proce... | 564   | usbfs      | [3CFD979C60](<Notebook/Dell/Latitude/Latitude XT2/259FA4D4C7EE/BLENDOS/6.2.12-ARCH1-1/X86_64/3CFD979C60>) |
| 0b97:7772 | O2 Micro         | OZ776 CCID Smartcard Reader          | 525   | usbfs      | [0BEF13413F](<Notebook/Dell/Latitude/Latitude D630/41D44A061D5A/DEBIAN-11/5.10.0-21-AMD64/X86_64/0BEF13413F>) |
| 0a5c:5843 | Broadcom         | 58200                                | 486   | usbfs      | [4D8EF45CBC](<Notebook/Dell/Latitude/Latitude 5520/BC262F5312A0/ZORIN-16/5.15.0-71-GENERIC/X86_64/4D8EF45CBC>) |
| 147e:2020 | Upek             | TouchChip Fingerprint Coprocessor... | 462   | usbfs      | [00FF147A9A](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252CG/53AF29E0966C/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/00FF147A9A>) |
| 17ef:1003 | Lenovo           | Integrated Smart Card Reader         | 423   | usbfs      | [10DE9F17E1](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537CC5/4CD8E7447BCF/DEBIAN-11/5.10.0-20-AMD64/X86_64/10DE9F17E1>) |
| 0a5c:5832 | Broadcom         | 5880                                 | 422   | usbfs      | [4EA44288B5](<Notebook/Dell/Latitude/Latitude 7370/7819A10CD1AF/PARROT-5.3/6.1.0-1PARROT1-AMD64/X86_64/4EA44288B5>) |
| 0a5c:5834 | Broadcom         | 5880                                 | 355   | usbfs      | [DC5C96E431](<Notebook/Dell/Latitude/Latitude 7390/B3CA0EFC3725/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC5C96E431>) |
| 0a5c:5842 | Broadcom         | 58200                                | 190   | usbfs      | [4CD3B0701E](<Notebook/Dell/Precision/Precision 7740/F8525F0F515F/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/4CD3B0701E>) |
| 0a5c:5804 | Broadcom         | BCM5880 Secure Applications Proce... | 112   | usbfs      | [0EFF8F87C6](<Notebook/Dell/Latitude/Latitude E7450/9DC8CA3DF416/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/0EFF8F87C6>) |
| 0b97:7762 | O2 Micro         | Oz776 SmartCard Reader               | 89    | usbfs      | [8EF701B61D](<Notebook/Dell/MXG/MXG061/F0E8113D6028/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/8EF701B61D>) |
| 08e6:3437 | Gemalto (was ... | GemPC Twin SmartCard Reader          | 76    | usbfs      | [A6CE7489E1](<Notebook/Panasonic/CF-20/CF-20-1/D68E139EFD24/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/A6CE7489E1>) |
| 0bda:0165 | Realtek Semic... | Smart Card Reader Interface          | 55    | usbfs      | [9ED0395D2C](<Desktop/MSI/Z370/Z370 Gaming Infinite X/B24EAD5A5E61/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/9ED0395D2C>) |
| 04e6:5116 | SCM Microsystems | SCR331-LC1 / SCR3310 SmartCard Re... | 46    | usbfs      | [A526504D18](<Desktop/Gigabyte Technology/B650/B650 AORUS PRO AX/785C335D4DEC/GENTOO-2.9/6.1.12-GENTOO/X86_64/A526504D18>) |
| 0529:0620 | Aladdin Knowl... | Token JC                             | 46    | usbfs      | [A36464850A](<Desktop/MSI/MS-7/MS-7D70/AFD239798CB7/ARCH-ROLLING/6.2.7-ZEN1-1-ZEN/X86_64/A36464850A>) |
| 058f:9520 | Alcor Micro      | Watchdata W 1981                     | 46    | usbfs      | [D1344E36DD](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 TWR/AE205CE4F972/ENDEAVOUROS-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/D1344E36DD>) |
| 072f:90cc | Advanced Card... | ACR38 SmartCard Reader               | 45    | usbfs      | [C6A760CB50](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/E9FD6C026940/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/C6A760CB50>) |
| 08e6:34ec | Gemalto (was ... | Compact Smart Card Reader Writer     | 38    | usbfs      | [5A626F5754](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4291WSH/8D2E1689C232/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/5A626F5754>) |
| 1050:0406 | Yubico.com       | Yubikey 4 U2F+CCID                   | 34    | usbfs      | [1D23894711](<Notebook/Dell/Precision/Precision 7520/430179DA6402/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/1D23894711>) |
| 0a5c:5802 | Broadcom         | BCM5880 Secure Applications Proce... | 33    | usbfs      | [3BF25841B3](<Notebook/Dell/Latitude/Latitude E6540/B03E8ADD495F/GENTOO-2.13/6.2.2-GENTOO-X86_64/X86_64/3BF25841B3>) |
| 076b:3021 | OmniKey          | CardMan 3021 / 3121                  | 24    | usbfs      | [F65CA1E461](<Notebook/Medion/X681/X681X/4F77B2334762/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/F65CA1E461>) |
| 04f2:1469 | Chicony Elect... | HP Skylab USB Smartcard Keyboard     | 23    | usbhid     | [0258B5925F](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/5B2110E93D66/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/0258B5925F>) |
| 20a0:4108 | Clay Logic       | Nitrokey Pro                         | 22    | usbfs      | [D8B2BFB82C](<Notebook/MSI/Modern/Modern 15 A5M/D5CF032B85C4/XUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/D8B2BFB82C>) |
| 076b:1021 | OmniKey          | CardMan 1021                         | 20    | usbfs      | [962BFFED9F](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/8AA5E51F68FC/ARCO-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/962BFFED9F>) |
| 0a89:0025 | Aktiv            | Rutoken lite                         | 20    | usbfs      | [7F787E2E46](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/E56BBEFB761C/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/7F787E2E46>) |
| 04e6:5119 | SCM Microsystems | SCR3340 - ExpressCard54 Smart Car... | 18    | usbfs      | [810CDB1AD1](<Notebook/Hewlett-Packard/Compaq/Compaq 6730b/E28B25537637/DEBIAN-11/5.10.0-20-AMD64/X86_64/810CDB1AD1>) |
| 0c4b:9102 | Reiner SCT Ka... | cyberJack RFID basis contactless ... | 18    | usbfs      | [B9F947FEC3](<Desktop/BESSTAR Tech/DMAF/DMAF5/E2C64EAEE3A5/DEBIAN-11/5.15.94-X86/X86_64/B9F947FEC3>) |
| 03f0:164a | Hewlett-Packard  | SC Keyboard - Apollo (Liteon)        | 17    | usbhid     | [9AFC74ED46](<Desktop/MSI/MS-7/MS-7D54/C32DD3083B58/GENTOO-2.6/5.15.37-GENTOO-DIST-HARDENED/X86_64/9AFC74ED46>) |
| 25dd:3111 | Bit4id           | miniLector EVO                       | 17    | usbfs      | [26681D2879](<Desktop/ASRock/970/970 Pro3 R2.0/6581B9EDA81D/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/26681D2879>) |
| 072f:2200 | Advanced Card... | ACR122U                              | 16    | pn533_usb  | [3089398556](<Notebook/Lenovo/IdeaPad/IdeaPad L340-15IRH Gaming 81LK/C24F9EA0C53B/MANJARO-22.0.2/6.1.9-1-MANJARO/X86_64/3089398556>) |
| 046a:00a1 | Cherry           | SmartCard Reader Keyboard KC 1000 SC | 15    | usbhid     | [48370F2817](<Notebook/Lenovo/Y520-15IKBN/Y520-15IKBN 80WK/886BC195F397/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/48370F2817>) |
| 1a44:0001 | VASCO Data Se... | Digipass 905 SmartCard Reader        | 14    | usbfs      | [F184FF6250](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6305 SFF/A4CD50058CA3/ZORIN-16/5.15.0-60-GENERIC/X86_64/F184FF6250>) |
| 076b:4321 | OmniKey          | CardMan 4321                         | 11    | usbfs      | [D06B40DDF1](<Notebook/Lenovo/ThinkPad/ThinkPad X230 Tablet 34383SG/19DB283F0CF1/POP!_OS-22.04/5.19.0-76051900-GENERIC/X86_64/D06B40DDF1>) |
| 08e6:3438 | Gemalto (was ... | GemPC Key SmartCard Reader           | 11    | usbfs      | [D3D2AFD2C3](<Notebook/Lenovo/IdeaPad/IdeaPad 500-15ISK 80NT/34ECC82369A1/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/D3D2AFD2C3>) |
| 0a5c:5833 | Broadcom         | 5880                                 | 11    | usbfs      | [3DB09E931E](<Notebook/Dell/Precision/Precision 7710/32DE3097D8F4/GARUDA-SOARING/6.1.11-ZEN1-1-ZEN/X86_64/3DB09E931E>) |
| 1050:0111 | Yubico.com       | Yubikey NEO(-N) OTP+CCID             | 11    | usbhid     | [3AADACEFE7](<Notebook/Medion/P/P6816/8C2A7CA83972/XERO-ROLLING/6.0.8-ARCH1-1/X86_64/3AADACEFE7>) |
| 072f:b100 | Advanced Card... | ACR39U                               | 10    | usbfs      | [6A0673F946](<Notebook/ASUSTek Computer/K55/K55VJ/3CB650F6CA09/KUBUNTU-22.10/5.19.0-35-GENERIC/X86_64/6A0673F946>) |
| 0dc3:1004 | Athena Smartc... | ASEDrive CCID                        | 10    | usbfs      | [60865C8DED](<Desktop/ASUSTek Computer/All/All Series/1DAA37BFDAE9/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.19.2-1-DEFAULT/X86_64/60865C8DED>) |
| 04e6:5410 | SCM Microsystems | SCR35xx Smart Card Reader            | 9     | usbfs      | [92F54D6EFD](<Desktop/MSI/MS/MS-7994/2046917A4A6C/UBUNTU-21.10/5.13.0-52-GENERIC/X86_64/92F54D6EFD>) |
| 0a5c:5805 | Broadcom         | 5880                                 | 9     |            | [F69852B39C](<Notebook/Dell/Latitude/Latitude 12 Rugged Tablet 7202/F216997E9784/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/F69852B39C>) |
| 0bf8:1006 | Fujitsu Sieme... | SmartCard Reader 2A                  | 9     | usbfs      | [8A8A256B79](<Notebook/Lenovo/V570/V570 1066EDG/271B62039C65/ZORIN-16/5.15.0-67-GENERIC/X86_64/8A8A256B79>) |
| 24dc:0101 | Aladdin R.D.     | JaCarta                              | 9     | usbfs      | [32AAD1AE25](<Desktop/Others/Intel/Intel X79/31021A44B178/UBUNTU-20.04/5.13.0-44-GENERIC/X86_64/32AAD1AE25>) |
| 04e6:e001 | SCM Microsystems | SCR331 SmartCard Reader              | 8     | usbfs      | [8E4AB9C969](<Desktop/ASUSTek Computer/STRIX/STRIX Z270E GAMING/E5FE56ACF93D/KUBUNTU-22.04/5.15.0-52-GENERIC/X86_64/8E4AB9C969>) |
| 076b:3031 | OmniKey          | 3x21 Smart Card Reader               | 8     | usbfs      | [6694D6E805](<Server/Dell/Precision/Precision 7820 Tower/97883BD78AD3/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/6694D6E805>) |
| 1a44:0870 | VASCO Data Se... | DIGIPASS 870                         | 8     | usbfs      | [2F26E2EC6E](<Notebook/ASUSTek Computer/GL552/GL552VW/138484BF59CB/ZORIN-16/5.13.0-40-GENERIC/X86_64/2F26E2EC6E>) |
| 072f:2224 | Advanced Card... | ACR1281 1S Dual Reader               | 7     | usbfs      | [1940C6417C](<All In One/Dell/OptiPlex/OptiPlex 7450 AIO/A9167F8393F4/DEBIAN-11/5.10.0-21-AMD64/X86_64/1940C6417C>) |
| 0c4b:0580 | Reiner SCT Ka... | cyberJack one                        | 7     |            | [6378111BBD](<Desktop/Fujitsu Siemens/CELSIUS/CELSIUS W360/07F33320B239/UBUNTU-20.04/5.4.0-137-GENERIC/X86_64/6378111BBD>) |
| 1059:0017 | Giesecke & De... | StarSign CUT                         | 7     | usbfs      | [EEDB55E1BA](<Notebook/Acer/Aspire/Aspire A515-54G/7576F114888F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/EEDB55E1BA>) |
| 163c:0407 | Watchdata        | USB Key                              | 7     | usbfs      | [410A9AAE8C](<Notebook/Acer/Predator/Predator G3-572/05680EC80D76/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/410A9AAE8C>) |

### Converter (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0403:7a58 | Future Techno... | USB <-> Serial Cable                 | 23    | usbfs      | [0AFA4006CD](<Desktop/Dell/Precision/Precision Tower 3620/9A891B9FB524/ZORIN-16/5.15.0-69-GENERIC/X86_64/0AFA4006CD>) |
| 0403:1237 | Future Techno... | Z397 GUARD Converter                 | 4     |            | [CF5DEA43E1](<Mini Pc/Hewlett-Packard/260/260 G3 DM/D334B500C95E/UBUNTU-21.10/5.13.0-21-GENERIC/X86_64/CF5DEA43E1>) |
| 03eb:21fe | Atmel            | AVR309:USB to UART protocol conve... | 2     | igorplu... | [032A1A34DF](<Desktop/CompuLab/SBC-FITPC/SBC-FITPC2/74B4C3F47893/ZORIN-15/5.3.0-53-GENERIC/I686/032A1A34DF>) |
| 0c12:0005 | Zeroplus         | PSX Vibration Feedback Converter ... | 2     | usbhid     | [D75CB4D8C6](<Desktop/Gigabyte Technology/Z390/Z390 M GAMING/B959B8FB62A0/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/D75CB4D8C6>) |
| 110a:1110 | Moxa Technolo... | UPort 1110                           | 2     | ti_usb_... | [F815AEE35E](<Notebook/Lenovo/ThinkPad/ThinkPad T60 1951BY8/5D9A1B55704D/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-I586/I686/F815AEE35E>) |
| 051d:c812 | American Powe... | APC USB SERIAL CONVERTER.            | 1     | cdc_acm    | [BDB4EBA3E4](<Desktop/ASRock/Q1900/Q1900M/5B23A80950DA/XUBUNTU-20.04/4.15.0-111-GENERIC/X86_64/BDB4EBA3E4>) |
| 0a12:0042 | Cambridge Sil... | SPI Converter                        | 1     |            | [E1C0C74CA6](<Desktop/ASRock/Z390/Z390 Pro4/1A53A6D86AB6/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/E1C0C74CA6>) |
| 0c12:07f4 | Zeroplus         | NeoGeo Converter                     | 1     |            | [7305C4D766](<Desktop/Gigabyte Technology/F2/F2A88XM-D3H/FFB037856D9C/FEDORA-35/5.16.16-200.FC35.X86_64/X86_64/7305C4D766>) |
| 1f6a:15aa | AJA Video Sys... | AJA Mini-converter                   | 1     | cdc_acm    | [31D8634492](<Desktop/Dell/Precision/Precision WorkStation T3500/6E3A480272C7/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/31D8634492>) |
| 277c:0024 | SIGNALCORE       | SC5308A RF DownConverter             | 1     |            | [1343B5BB5D](<Desktop/ASUSTek Computer/ROG/ROG Maximus XII HERO/3B3EE14AB971/UBUNTU-18.04/4.15.0-144-GENERIC/X86_64/1343B5BB5D>) |

### Diagnostic (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1908:0102 | GEMBIRD          | Digital Photo Frame                  | 6     | usbfs      | [216AD20179](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/8952635F668D/ELEMENTARY-7/5.19.0-32-GENERIC/X86_64/216AD20179>) |
| 09bf:00f5 | Auerswald        | COMfortel 2500 (System telephone)    | 3     |            | [17DEAC9C67](<Desktop/Gigabyte Technology/Z87X-OC/Z87X-OC Force/5DB88AD80EF6/LMDE-5/5.10.0-12-AMD64/X86_64/17DEAC9C67>) |
| 1483:5751 | MyUSB_HID        | By embed-net                         | 1     |            | [16A2E0AB5D](<Desktop/ASRock/G41/G41M-VS3/E4127A1A8A70/LUBUNTU-22.04/5.15.0-40-GENERIC/X86_64/16A2E0AB5D>) |
| 154f:154f | SNBC             |                                      | 1     |            | [EA8698BD14](<Desktop/ASUSTek Computer/P8/P8H67-V/C8932BE3A25F/ROSA-2016.1/4.17.0-DESKTOP-9.1ROSA-X86_64/X86_64/EA8698BD14>) |

### Disk (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 058f:6387 | Alcor Micro      | Transcend                            | 3370  | uas, us... | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 090c:1000 | Silicon Motion   | USB                                  | 3247  | usb_sto... | [AD66608CF0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E039702D1078/CHIMERAOS-41/6.1.21-1-LTS/X86_64/AD66608CF0>) |
| 0951:1666 | Kingston Tech... | DataTraveler 100 G3/G4/SE9 G2        | 3169  | uas, us... | [F5499886E9](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/D04FB50B5F37/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F5499886E9>) |
| 058f:6366 | Alcor Micro      | Multi Flash Reader                   | 2829  | uas, us... | [DE7D5668D5](<Notebook/Lenovo/G700/G700 20251/D9E47C552B1B/LINUXMINT-20.3/5.4.0-137-GENERIC/X86_64/DE7D5668D5>) |
| 058f:6362 | Alcor Micro      | Flash Card Reader/Writer             | 2577  | uas, us... | [EC04C034D3](<Desktop/Dell/OptiPlex/OptiPlex 990/D0B1671560CE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EC04C034D3>) |
| 0781:5567 | SanDisk          | Cruzer Blade                         | 2348  | uas, us... | [6B908B35CC](<Notebook/Acer/Aspire/Aspire 5750G/7713EE2713FC/GARUDA-SOARING/6.1.26-1-LTS/X86_64/6B908B35CC>) |
| 0bda:0138 | Realtek Semic... | RTS5138 Card Reader Controller       | 2216  | ums_rea... | [5C8C1872E4](<Notebook/Acer/Aspire/Aspire 5733Z/BBDFB7B4C795/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/5C8C1872E4>) |
| 8564:1000 | Transcend        | JetFlash                             | 1977  | uas, us... | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 0bda:0158 | Realtek Semic... | USB 2.0 multicard reader             | 1945  | ums_rea... | [712A246CE4](<Desktop/Acer/Aspire/Aspire M1930/0EDA29407810/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/712A246CE4>) |
| 174c:55aa | ASMedia Techn... | ASM1051E SATA 6Gb/s bridge, ASM10... | 1733  | usb_sto... | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 0781:5581 | SanDisk          | Ultra                                | 1610  | uas, us... | [712A246CE4](<Desktop/Acer/Aspire/Aspire M1930/0EDA29407810/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/712A246CE4>) |
| 0930:6545 | Toshiba          | Kingston DataTraveler 102/2.0 / H... | 1168  | uas, us... | [BB9C7992F8](<Notebook/eMachines/E/E725/EE81FA330179/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/BB9C7992F8>) |
| 0781:5583 | SanDisk          | Ultra Fit                            | 1130  | uas, us... | [7A77C66C97](<Notebook/Acer/Aspire/Aspire E5-523G/5A8BB5B67502/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/7A77C66C97>) |
| 152d:0578 | JMicron Techn... | JMS578 SATA 6Gb/s                    | 1093  | uas, us... | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 058f:6364 | Alcor Micro      | AU6477 Card Reader Controller        | 1048  | uas, us... | [2ED500D3E9](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/2ED500D3E9>) |
| 0bda:0316 | Realtek Semic... | SD/MMC                               | 999   | uas, us... | [D6C6781535](<Notebook/Avell High Performance/A65/A65 MOB/1D6F35E22C18/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D6C6781535>) |
| 05e3:0749 | Genesys Logic    | USB3.0 Card Reader                   | 969   | uas, us... | [4D78DBBDC6](<Desktop/ASUSTek Computer/P5Q/P5Q SE-R/2575946B74AB/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/4D78DBBDC6>) |
| 0781:5591 | SanDisk          | Ultra Flair                          | 903   | uas, us... | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 0781:5575 | SanDisk          | Cruzer Glide                         | 824   | uas, us... | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 0930:6544 | Toshiba          | TransMemory-Mini / Kingston DataT... | 749   | uas, us... | [8FF62A5045](<Desktop/MSI/MS-7/MS-7C56/0BC080AA3E4A/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/8FF62A5045>) |
| 13fe:4200 | Kingston Tech... | USB DISK 2.0                         | 746   | uas, us... | [561202C004](<Notebook/Apple/MacBookPro3/MacBookPro3,1/469E66CF314F/UBUNTU-18.04/4.15.0-211-GENERIC/I686/561202C004>) |
| 0bda:0151 | Realtek Semic... | Mass Storage Device (Multicard Re... | 736   | uas, us... | [4ACB37F728](<Desktop/Hewlett-Packard/PPPPP-CCC#MMMMMMMM/PPPPP-CCC#MMMMMMMM/52B2452D254D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/4ACB37F728>) |
| 13fe:4300 | Phison Electr... | USB DISK                             | 711   | uas, us... | [E505FF2542](<Notebook/Lenovo/B590/B590 20208/726CBC5A63D3/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E505FF2542>) |
| 05e3:0751 | Genesys Logic    | microSD Card Reader                  | 642   | uas, us... | [B4F013C967](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Dash F15 FX516PC_FX516PC/2708A8EF0A61/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/B4F013C967>) |
| ffff:5678 | VendorCo         | Disk                                 | 635   | uas, us... | [967E39A2D3](<Notebook/Lenovo/Legion/Legion 5 15ACH6 82JW/2BE152EEFFDD/DEBIAN-11/5.10.0-22-AMD64/X86_64/967E39A2D3>) |
| 05e3:0745 | Genesys Logic    | Logilink CR0012                      | 629   | uas, us... | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 14cd:1212 | Super Top        | microSD card reader (SY-T18)         | 622   | uas, us... | [6EC1762E12](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ULTRA/AA0705BC8FAC/DEBIAN-11/5.10.0-22-AMD64/X86_64/6EC1762E12>) |
| 0951:1665 | Kingston Tech... | Digital DataTraveler SE9             | 615   | uas, us... | [4280750D03](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X510QA_F510QA/A227B1584210/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/4280750D03>) |
| 0bda:0153 | Realtek Semic... | 3-in-1 (SD/SDHC/SDXC) Card Reader    | 614   | ums_rea... | [6184308BD3](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/6184308BD3>) |
| 05ac:8403 | Apple            | Internal Memory Card Reader          | 598   | apple_m... | [EBAFDDB3F1](<All In One/Apple/iMac11/iMac11,3/9C99E007509B/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/EBAFDDB3F1>) |
| 13fe:6300 | Kingston Tech... | SP Mobile C31                        | 596   | uas, us... | [6AF53FB237](<Notebook/Hewlett-Packard/Pro/Pro Tablet 10 EE G1/B7F891A25D5D/MX-21/5.19.0-17.2-LIQUORIX-AMD64/X86_64/6AF53FB237>) |
| 18a5:0302 | Verbatim         | STORE N GO                           | 574   | uas, us... | [282C0C9F11](<Notebook/eMachines/E/E725/16CF786C6540/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/282C0C9F11>) |
| 05ac:8406 | Apple            | SD Card Reader                       | 569   | apple_m... | [D681957D5B](<Notebook/Apple/MacBookAir7/MacBookAir7,2/621FFA54E8BE/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D681957D5B>) |
| abcd:1234 | LogiLink         | UDisk                                | 546   | uas, us... | [6A0AF69B4A](<Server/Dell/PowerEdge/PowerEdge R720/F424DE07066D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6A0AF69B4A>) |
| 152d:2329 | JMicron Techn... | JM20329 SATA Bridge                  | 516   | usb_sto... | [A41ADC3F79](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3 PLUS/AE99A72F5A7C/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/A41ADC3F79>) |
| 0781:5571 | SanDisk          | Cruzer Fit                           | 505   | uas, us... | [A72531BD2D](<Desktop/MouseComputer/B75/B75M-D3V-JP/041627593BC4/LINUXMINT-18.3/4.8.0-58-GENERIC/X86_64/A72531BD2D>) |
| 13fe:4100 | Phison Electr... | Silicon-Power16G                     | 461   | uas, us... | [D99045BE1C](<Notebook/ASUSTek Computer/K75/K75DE/31A8ABE5A2CB/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D99045BE1C>) |
| 152d:2338 | JMicron Techn... | JM20337 Hi-Speed USB to SATA & PA... | 451   | uas, us... | [57E1C14061](<Notebook/Sony/SVF1521/SVF1521C6EW/9465299787D1/LUBUNTU-20.04/5.4.0-148-GENERIC/X86_64/57E1C14061>) |
| 0bda:0328 | Realtek Semic... | SD/MMC CRW                           | 443   | uas, us... | [FE6DC0D9C7](<Server/Dell/Precision/Precision 7820 Tower/FB09ECB98D56/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FE6DC0D9C7>) |
| 1005:b113 | Apacer Techno... | Handy Steno 2.0/HT203                | 434   | uas, us... | [5D0BAE516F](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX R2.0/68175405EDF1/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/5D0BAE516F>) |
| 05e3:0723 | Genesys Logic    | GL827L SD/MMC/MS Flash Card Reader   | 422   | usb_sto... | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 0bc2:231a | Seagate          | Expansion                            | 422   | uas        | [ED03DF615E](<Desktop/ASRock/B650E/B650E PG Riptide WiFi/E45FD3D55523/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/ED03DF615E>) |
| 0bda:0177 | Realtek Semic... | USB2.0-CRW                           | 411   | ums_rea... | [B7BF9F8683](<Notebook/Dell/Inspiron/Inspiron 3501/B976DA6E21D9/ZORIN-16/5.15.0-52-GENERIC/X86_64/B7BF9F8683>) |
| 13fe:5500 | Kingston Tech... | Patriot Memory                       | 401   | uas, us... | [A0B1299BAA](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2540p/E48B9460A6B3/UBUNTU-BUDGIE-20.04/5.18.8-051808-GENERIC/X86_64/A0B1299BAA>) |
| 0bda:0181 | Realtek Semic... | MS/MS-Pro/HG                         | 392   | uas, us... | [8C80FD3109](<Desktop/Lenovo/ThinkStation/ThinkStation D20 4158AF8/EF4EEEE3E2FB/BLACKPANTHER-OS-22.1/6.2.9-DESKTOP-1BP/X86_64/8C80FD3109>) |
| 048d:1234 | Integrated Te... | Mass storage                         | 378   | uas, us... | [D615A9B90F](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Nano Gen 1 20UQS1FX00/11CBF0E15F18/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D615A9B90F>) |
| 0bda:0111 | Realtek Semic... | RTS5111 Card Reader Controller       | 378   | uas, us... | [A89604DCCD](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/804B8CC2C734/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/A89604DCCD>) |
| 048d:1336 | Integrated Te... | SD/MMC Cardreader                    | 376   | uas, us... | [307E22B0D6](<Desktop/Gigabyte Technology/B550/B550 AORUS ELITE AX V2/3443FD568B42/ZORIN-16/5.13.0-48-GENERIC/X86_64/307E22B0D6>) |
| 1908:0226 | GEMBIRD          | MicroSD Card Reader/Writer           | 366   | uas, us... | [45A7E28DB1](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13t-aw100/0E21BFAA559F/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/45A7E28DB1>) |
| 058f:9360 | Alcor Micro      | 8-in-1 Media Card Reader             | 356   | uas, us... | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |

### Dvb card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:2838 | Realtek Semic... | RTL2838 DVB-T                        | 326   | dvb_usb... | [7F1747C3E3](<Desktop/ASUSTek Computer/A88/A88X-PLUS/279BA270C61D/SLACKWARE-CURRENT/6.2.9-SLACK/X86_64/7F1747C3E3>) |
| 07ca:a309 | AVerMedia Tec... | AVerTV DVB-T (A309)                  | 43    | dvb_usb... | [9C24401930](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/BB59E8078966/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/9C24401930>) |
| 0bda:2832 | Realtek Semic... | RTL2832U DVB-T                       | 37    | dvb_usb... | [6788EEA8D2](<Desktop/ASUSTek Computer/All/All Series/CFD5EE21063C/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/6788EEA8D2>) |
| 15f4:0131 | HanfTek          | dvbt2                                | 34    | dvb_usb... | [379F9D7AF7](<Desktop/Dell/Precision/Precision 3630 Tower/D94E30FF92DF/UBUNTU-20.04/5.15.0-69-GENERIC/X86_64/379F9D7AF7>) |
| 048d:9135 | Integrated Te... | Zolid Mini DVB-T Stick               | 19    | dvb_usb... | [67CE5B3AB1](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR VI HERO/89C86BAFAC07/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/67CE5B3AB1>) |
| 07ca:1336 | AVerMedia Tec... | A336 MiniCard Hybrid DVB-T           | 18    |            | [EB106FA5D3](<All In One/Dell/Inspiron/Inspiron One 2310/E46F3B774446/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/EB106FA5D3>) |
| 1164:1f08 | YUAN High-Tec... | STK7700D                             | 17    | dvb_usb... | [4D83FDA5BA](<Notebook/ASUSTek Computer/N71/N71Vg/35340D212BC1/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/4D83FDA5BA>) |
| 07ca:1871 | AVerMedia Tec... | TD310 DVB-T/T2/C dongle              | 15    | dvb_usb... | [AB53417291](<Desktop/Dell/OptiPlex/OptiPlex 390/02D16BA3B823/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/AB53417291>) |
| 15a4:9016 | Afatech          | AF9015 DVB-T USB2.0 stick            | 14    | dvb_usb... | [5B01559647](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/49E161DE9207/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/5B01559647>) |
| 1f4d:c803 | G-Tek Electro... | NotOnlyTV (Lifeview) LV5TDLX DVB-... | 14    | dvb_usb... | [F51082B385](<Desktop/ASRock/FM2A85X/FM2A85X Extreme4-M/B9462B40442C/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/F51082B385>) |
| 1d19:1101 | Dexatek Techn... | DK DVB-T Dongle                      | 13    | dvb_usb... | [7DABC9FC5C](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/7DABC9FC5C>) |
| 048d:9005 | Integrated Te... | DVB-T TV Stick                       | 12    | dvb_usb... | [5995F1C96E](<Desktop/ASUSTek Computer/H110/H110M-C/43B3232128C3/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/5995F1C96E>) |
| 0572:c688 | Conexant Systems | Geniatech T230 DVB-T2 TV Stick       | 12    | dvb_usb... | [FACE5F2EF3](<Desktop/Gigabyte Technology/B550/B550 AORUS ELITE V2/B85429DE2862/OPENMANDRIVA-23.90/6.1.9-DESKTOP-1OMV2390/X86_64/FACE5F2EF3>) |
| 07ca:a310 | AVerMedia Tec... | A310                                 | 12    | dvb_usb... | [4599565D35](<Notebook/Acer/Aspire/Aspire 7720/F4564EE0E0A0/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/4599565D35>) |
| 2304:0237 | Pinnacle Systems | PCTV 73e [DiBcom DiB7000PC]          | 12    | dvb_usb... | [590E39BEF4](<Desktop/Medion/MS/MS-7797/75E51DCA8667/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/590E39BEF4>) |
| 187f:0202 | Siano Mobile ... | Nice                                 | 9     | smsusb     | [118A28442E](<Desktop/ECS/GeForce7050/GeForce7050M-M/5BF3B24534E8/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/118A28442E>) |
| 2040:7070 | Hauppauge        | Nova-T Stick 3                       | 8     | dvb_usb... | [0D964B5339](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/139716A7F3B1/LINUXMINT-20.1/5.4.0-73-GENERIC/X86_64/0D964B5339>) |
| 07ca:0831 | AVerMedia Tec... | H831 USB Hybrid DVB-T/T2             | 7     |            | [62A01ED1F1](<Desktop/Gigabyte Technology/B450M/B450M S2H V2/5FD3F1AD8163/ROSA-12.3/5.17.11-GENERIC-2ROSA2021.1-X86_64/X86_64/62A01ED1F1>) |
| 07ca:1334 | AVerMedia Tec... | H334 MiniCard Hybrid DVB-T           | 7     |            | [A079D28341](<All In One/Lenovo/C560/C560 10150/6C9E3A129538/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/A079D28341>) |
| 2040:9580 | Hauppauge        | NovaT 500Stick                       | 7     | dvb_usb... | [F3DE47AC1F](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15ARR 81D2/D5EDE2A5148A/UBUNTU-22.04/5.15.0-40-GENERIC/X86_64/F3DE47AC1F>) |
| 0572:0320 | Conexant Systems | DVBSky T330 DVB-T2/C tuner           | 6     | dvb_usb... | [EA89B6E705](<Server/Supermicro/H8/H8SGL/4B37E516C354/UBUNTU-20.04/5.13.0-41-GENERIC/X86_64/EA89B6E705>) |
| 07ca:0830 | AVerMedia Tec... | H830 USB Hybrid DVB-T                | 6     |            | [107752EBA8](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/63C45CB46227/PEAROS/6.3.1-ARCH1-1/X86_64/107752EBA8>) |
| 07ca:a373 | AVerMedia Tec... | A373                                 | 6     |            | [2E34D8A2CC](<All In One/Acer/Aspire/Aspire Z5770/1DB05CC1D29C/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2E34D8A2CC>) |
| 0ccd:0038 | TerraTec Elec... | Cinergy TÂ² DVB-T Receiver         | 6     | dvb_usb... | [E6EAC5C882](<Notebook/Lenovo/ThinkPad/ThinkPad P50 20EQS1WW00/258542A3B4FF/DEBIAN-11/5.18.0-0.DEB11.4-AMD64/X86_64/E6EAC5C882>) |
| 13d3:3282 | IMC Networks     | DVB-T + GPS Minicard [RTL2832U]      | 6     |            | [C65E5F04D0](<All In One/ASUSTek Computer/ET2400/ET2400IN-1G/34D8B01527FB/KUBUNTU-22.04/5.15.0-60-GENERIC/X86_64/C65E5F04D0>) |
| 2040:5200 | Hauppauge        | NovaT 500Stick                       | 6     | dvb_usb... | [217971D572](<Desktop/Intel/DH77DF/DH77DF AAG40293-300/5418ABF7C8F0/FEDORA-36/5.19.6-200.FC36.X86_64/X86_64/217971D572>) |
| 07ca:1835 | AVerMedia Tec... | A835B                                | 5     | dvb_usb... | [25EAC72561](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/3A9DF5F55034/UBUNTU-UNITY-22.04/5.19.0-38-GENERIC/X86_64/25EAC72561>) |
| 07ca:a835 | AVerMedia Tec... | A835                                 | 5     | dvb_usb... | [1686897E74](<Desktop/Compaq/WE230AA-ABE/WE230AA-ABE CQ5315ES/5605E4118E6D/LINUXMINT-19.3/4.15.0-189-GENERIC/X86_64/1686897E74>) |
| 1164:0871 | YUAN High-Tec... | STK7700D                             | 5     | dvb_usb... | [7EA81D88F5](<Notebook/Toshiba/Satellite/Satellite P500/1B30765FFE3E/ROSA-12.2/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/7EA81D88F5>) |
| 14f7:0500 | TechniSat Dig... | DVB-PC TV Star HD                    | 5     | dvb_usb... | [002A1F805C](<Desktop/Dell/DXC/DXC061/F0A7208FC2DF/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/002A1F805C>) |
| 15a4:1001 | Afatech          | AF9015/AF9035 DVB-T stick            | 5     | dvb_usb... | [245DB62C73](<Desktop/Hewlett-Packard/h8/h8-1350eo/735D2351FEA5/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/245DB62C73>) |
| 1b80:d393 | Afatech          | DVB-T receiver [RTL2832U]            | 5     | dvb_usb... | [70438D549D](<Desktop/ASUSTek Computer/AT5/AT5IONT-I/67C04CE8310C/KDE-NEON-20.04/5.4.0-117-GENERIC/X86_64/70438D549D>) |
| 07ca:850a | AVerMedia Tec... | AverTV Volar Black HD (A850)         | 4     | dvb_usb... | [8AB143EC6B](<Desktop/ASUSTek Computer/P5Q/P5Q DELUXE/211EE5BEF015/LMDE-4/4.19.0-16-AMD64/X86_64/8AB143EC6B>) |
| 07ca:a867 | AVerMedia Tec... | AVerTV DVB-T (A867)                  | 4     | dvb_usb... | [093DFD12E4](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK E744/737C5D17A498/DEBIAN-11/5.10.0-14-AMD64/X86_64/093DFD12E4>) |
| 1164:3edc | YUAN High-Tec... | STK7700D                             | 4     |            | [DF82BB0E17](<All In One/ASUSTek Computer/ET2011/ET2011A/08966144026E/ENDLESS-3.7.8/5.3.0-28-GENERIC/X86_64/DF82BB0E17>) |
| 2040:7050 | Hauppauge        | Nova-T Stick                         | 4     | dvb_usb... | [0E9A009C11](<Desktop/Gigabyte Technology/X58/X58A-UD3R/4D2C07D9CFD0/UBUNTU-22.04/5.15.0-32-GENERIC/X86_64/0E9A009C11>) |
| 2040:8400 | Hauppauge        | WinTV Nova-T-500                     | 4     | dvb_usb... | [9426D21070](<Desktop/Gigabyte Technology/H270-Gaming/H270-Gaming 3/F64235A79CD0/NOBARA-36/5.19.10-201.FSYNC.FC36.X86_64/X86_64/9426D21070>) |
| 04b4:2102 | Cypress Semic... | EZ-USB FX2                           | 3     | dvb_usb... | [40EE943C1C](<Desktop/ASRock/G31/G31M-VS2/E4CB55304B9A/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/40EE943C1C>) |
| 07ca:a815 | AVerMedia Tec... | AVerTV DVB-T Volar X (A815)          | 3     | dvb_usb... | [E92157B364](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LK/64FE8299E12D/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/E92157B364>) |
| 0ccd:00a9 | TerraTec Elec... | RTL2838 DVB-T COFDM Demodulator [... | 3     | dvb_usb... | [4622016059](<Desktop/Medion/MS/MS-7318/04DDF3A09383/DEBIAN-11/5.10.0-19-AMD64/X86_64/4622016059>) |
| 1044:7002 | Chu Yuen Ente... | Gigabyte U8000 DVB-T tuner           | 3     | dvb_usb... | [2360C35AC1](<Notebook/Dell/Inspiron/Inspiron MM061/4A51319D2D71/UBUNTU-MATE-18.04/5.4.0-122-GENERIC/I686/2360C35AC1>) |
| 1415:0003 | Nam Tai E&E P... | SCEH-0036                            | 3     | dvb_usb... | [2B7E826FFE](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/7E33B0008546/LINUXMINT-21/5.15.0-48-GENERIC/X86_64/2B7E826FFE>) |
| 1f4d:3000 | G-Tek Electro... | USB Stick                            | 3     | dvb_usb... | [8EB4D9E6CE](<Desktop/Dell/Precision/Precision T3600/AD13DC5FD6DD/UBUNTU-20.04/5.8.0-44-GENERIC/X86_64/8EB4D9E6CE>) |
| 0413:6029 | Leadtek Research | WinFast DTV Dongle Gold              | 2     | dvb_usb... | [614DBAA6D1](<Desktop/Gigabyte Technology/B85/B85M-D2V/4867F54E230D/KDE-NEON-18.04/5.3.0-28-GENERIC/X86_64/614DBAA6D1>) |
| 04b4:861f | Cypress Semic... | Anysee E30 USB 2.0 DVB-T Receiver    | 2     | dvb_usb... | [040550CDAA](<Desktop/Gigabyte Technology/B250/B250M-DS3H/A8D870914ABD/MANJARO/5.15.19-1-MANJARO/X86_64/040550CDAA>) |
| 04ca:f000 | Lite-On Techn... | DVB Card                             | 2     | dvb_usb... | [7225AECEFF](<Notebook/Toshiba/Satellite/Satellite P850/F79358A2F822/UBUNTU-20.04/5.4.0-52-GENERIC/X86_64/7225AECEFF>) |
| 04ca:f01c | Lite-On Techn... | TT1280DA DVB-T TV Tuner              | 2     |            | [24FF3CF596](<Notebook/Acer/Aspire/Aspire 8940G/3EB6F0C4396B/ZORIN-16/5.11.0-25-GENERIC/X86_64/24FF3CF596>) |
| 0572:c689 | Conexant Systems | EyeTV Stick                          | 2     | dvb_usb... | [D47493ECAE](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-A/5751A395EDAB/ELEMENTARY-5.1.7/5.4.0-53-GENERIC/X86_64/D47493ECAE>) |
| 07ca:0335 | AVerMedia Tec... | H335                                 | 2     | dvb_usb... | [0362E43257](<All In One/Packard Bell/ONETWO/ONETWO L5871/D9CDC409CC4E/POP!_OS-20.10/5.11.0-7614-GENERIC/X86_64/0362E43257>) |
| 07ca:0810 | AVerMedia Tec... | H810 USB Hybrid DVB-T                | 2     |            | [B46F2FEE35](<Notebook/ASUSTek Computer/E403/E403NA/E3A7CFB90011/FEDORA-29/4.18.3-300.FC29.X86_64/X86_64/B46F2FEE35>) |

### Fingerprint reader (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 06cb:00bd | Synaptics        | Prometheus MIS Touch Fingerprint ... | 1533  | usbfs      | [C5687C048F](<Convertible/Lenovo/ThinkPad/ThinkPad L13 Yoga Gen 2 20VK0019US/E10E74F99078/DEBIAN-11/5.10.0-22-AMD64/X86_64/C5687C048F>) |
| 138a:003f | Validity Sensors | VFS495 Fingerprint Reader            | 1378  | usbfs      | [761B89209D](<Notebook/Hewlett-Packard/ZBook/ZBook Studio G3/A8FA5C81BE84/UBUNTU-22.10/6.3.1-TKG-CFS/X86_64/761B89209D>) |
| 138a:0017 | Validity Sensors | VFS 5011 fingerprint sensor          | 727   | usbfs      | [6BC581F37C](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 3rd 20BTS41M00/1BB051547327/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/6BC581F37C>) |
| 138a:0011 | Validity Sensors | VFS5011 Fingerprint Reader           | 700   | usbfs      | [13A1E30B53](<Notebook/Dell/Vostro/Vostro 3360/934E92F48DBD/UBUNTU-23.04/5.19.0-41-GENERIC/X86_64/13A1E30B53>) |
| 06cb:009a | Synaptics        | Metallica MIS Touch Fingerprint R... | 656   | usbfs      | [4BAD3EE37E](<Notebook/Lenovo/ThinkPad/ThinkPad T580 20L9001HUS/3B9A4C787084/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/4BAD3EE37E>) |
| 147e:2016 | Upek             | Biometric Touchchip/Touchstrip Fi... | 648   | usbfs      | [D655AAD3C5](<Notebook/Acer/TravelMate/TravelMate 6592/87C8AD6BC8DB/UBUNTU-21.04/5.11.0-49-GENERIC/X86_64/D655AAD3C5>) |
| 138a:0018 | Validity Sensors | Fingerprint scanner                  | 458   |            | [5DD1479006](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/2F444A78A6AE/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/5DD1479006>) |
| 138a:003d | Validity Sensors | VFS491                               | 454   | usbfs      | [C941DA38CD](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8470p/E2A51E4B633B/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/C941DA38CD>) |
| 138a:003c | Validity Sensors | VFS471 Fingerprint Reader            | 446   | usbfs      | [CE35B62E32](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2560p/62AC29524293/ELEMENTARY-6.1/5.15.0-69-GENERIC/X86_64/CE35B62E32>) |
| 27c6:533c | Shenzhen Good... | FingerPrint                          | 432   | usbfs      | [3530619C98](<Notebook/Dell/XPS/XPS 13 9310/395DAB403C59/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/3530619C98>) |
| 08ff:2810 | AuthenTec        | AES2810                              | 429   | usbfs      | [9963ABA3A2](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2530p/5B27555CB81E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/9963ABA3A2>) |
| 138a:0097 | Validity Sensors | Synaptics WBDI                       | 422   | usbfs      | [66B49186CB](<Notebook/Lenovo/ThinkPad/ThinkPad T470 20HD0001MX/A3EC1FBD0030/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/66B49186CB>) |
| 06cb:0081 | Synaptics        | Synaptics WBDI                       | 418   |            | [4B23B933B5](<Convertible/Lenovo/Yoga/Yoga 530-14IKB 81EK/4DDB8C367C5E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/4B23B933B5>) |
| 27c6:55b4 | Shenzhen Good... | Fingerprint Reader                   | 416   | usbfs      | [95DBF74D72](<Convertible/Lenovo/Yoga/Yoga 6 13ALC7 82UD/1D240C5A7154/POP!_OS-22.04/6.3.1-060301-GENERIC/X86_64/95DBF74D72>) |
| 1c7a:0570 | LighTuning Te... | EgisTec Touch Fingerprint Sensor     | 405   | usbfs      | [460A286D9A](<Notebook/Acer/Swift/Swift SF314-56G/D59BFA32169B/KALI-2023.1/6.0.0-KALI6-AMD64/X86_64/460A286D9A>) |
| 27c6:55a4 | Shenzhen Good... | Goodix FingerPrint Device            | 399   |            | [A312F0545F](<Notebook/Lenovo/ThinkBook/ThinkBook 15 G2 ARE 20VG/BA29145B1BAF/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/A312F0545F>) |
| 04f3:0c00 | Elan Microele... | ELAN:ARM-M4                          | 396   |            | [0A639BA55D](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dq2xxx/8DCCFC840116/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0A639BA55D>) |
| 27c6:5110 | Shenzhen Good... | Goodix Fingerprint Device            | 377   |            | [A4F5DCE6D6](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/26116FF2B2E2/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/A4F5DCE6D6>) |
| 04f3:0903 | Elan Microele... | ELAN:Fingerprint                     | 365   | usbfs      | [078D3AE45F](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X512DA_F512DA/8F5D0732DFC0/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/078D3AE45F>) |
| 08ff:2580 | AuthenTec        | AES2501 Fingerprint Sensor           | 361   | usbfs      | [953D03DF07](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK S6420/AE64054EAC7F/ZORIN-15/5.4.0-58-GENERIC/X86_64/953D03DF07>) |
| 06cb:00be | Synaptics        | WBDI                                 | 355   | usbfs      | [ECC18E59BC](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ITL05 82HS/126F944404A7/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/ECC18E59BC>) |
| 0483:2016 | STMicroelectr... | Fingerprint Reader                   | 346   | usbfs      | [AD7F7DA4E4](<Notebook/Toshiba/dynabook/dynabook SS M42 210E-3W/258D5EEEFCDD/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/AD7F7DA4E4>) |
| 138a:0007 | Validity Sensors | VFS451 Fingerprint Reader            | 324   | usbfs      | [A0B1299BAA](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2540p/E48B9460A6B3/UBUNTU-BUDGIE-20.04/5.18.8-051808-GENERIC/X86_64/A0B1299BAA>) |
| 138a:0090 | Validity Sensors | VFS7500 Touch Fingerprint Sensor     | 312   | usbfs      | [4229BE0AFA](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20F9CTO1WW/05B8F27B1D2D/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/4229BE0AFA>) |
| 06cb:00b7 | Synaptics        | Synaptics VFS7552 Touch Fingerpri... | 305   | usbfs      | [A86BD404E0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/6214F3DFC9AB/MANJARO-22.1.0/6.2.12-1-MANJARO/X86_64/A86BD404E0>) |
| 138a:00ab | Validity Sensors | Synaptics VFS7552 Touch Fingerpri... | 296   |            | [48D87E5C6E](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G5/12325A990B32/UBUNTU-22.10/5.19.0-41-GENERIC/X86_64/48D87E5C6E>) |
| 06cb:00a2 | Synaptics        | Metallica MOH Touch Fingerprint R... | 272   |            | [DA5F050510](<Notebook/Lenovo/ThinkPad/ThinkPad E580 20KS001JUK/391B5A470702/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/DA5F050510>) |
| 138a:0050 | Validity Sensors | Swipe Fingerprint Sensor             | 266   | usbfs      | [D18F9C3E77](<Notebook/Hewlett-Packard/ENVY/ENVY TS 17/EAAE5C8A6C73/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/D18F9C3E77>) |
| 147e:1002 | Upek             | Biometric Touchchip/Touchstrip Fi... | 255   |            | [8EFA05ADA7](<Notebook/Lenovo/V580c/V580c 20160/0F767C61EAA3/ROSA-12.4/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/8EFA05ADA7>) |
| 06cb:00df | Synaptics        | Synaptics FS7604 Touch Fingerprin... | 250   | usbfs      | [6E086EC096](<Notebook/Hewlett-Packard/EliteBook/EliteBook 855 G7 Notebook PC/1E1EB0F59677/RHEL-9/5.14.0-162.23.1.EL9_1.X86_64/X86_64/6E086EC096>) |
| 1c7a:0603 | LighTuning Te... | ES603 Swipe Fingerprint Sensor       | 228   | usbfs      | [2CBD56ABDC](<Notebook/Notebook/P750/P750ZM/51A3147C30B6/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/2CBD56ABDC>) |
| 08ff:1600 | AuthenTec        | AES1600                              | 227   |            | [0BCA303D94](<Notebook/Acer/Aspire/Aspire 5930/CFAA23789301/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/0BCA303D94>) |
| 06cb:00c9 | Synaptics        | UWP WBDI                             | 204   | usbfs      | [6EC4C764EA](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 15-eb1xxx/7086E97D494A/FEDORA-36/6.2.14-100.FC36.X86_64/X86_64/6EC4C764EA>) |
| 27c6:5125 | Shenzhen Good... | Goodix Fingerprint Device            | 191   |            | [93AAAE065B](<Notebook/HUAWEI/CREM-WXX/CREM-WXX9/98F46C16FFB0/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/93AAAE065B>) |
| 06cb:009b | Synaptics        | WBDI Fingerprint Reader USB 086      | 189   |            | [917D7A7FC9](<Notebook/MSI/Others/Others/E72279394910/DEBIAN-12/6.1.0-7-AMD64/X86_64/917D7A7FC9>) |
| 06cb:00f0 | Synaptics        | FS7604 Touch Fingerprint Sensor w... | 189   |            | [C7308F11CE](<Notebook/Hewlett-Packard/EliteBook/EliteBook 845 14 inch G9 Notebook PC/3C880EC8B0FC/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/C7308F11CE>) |
| 27c6:55a2 | Shenzhen Good... | Goodix FingerPrint Device            | 179   |            | [F428173506](<Notebook/Lenovo/IdeaPad/IdeaPad 5 14ALC05 82LM/F6D3DDA3A0B3/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F428173506>) |
| 138a:0005 | Validity Sensors | VFS301 Fingerprint Reader            | 168   | validit... | [A4425E0654](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/E8D1DF13E28D/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/A4425E0654>) |
| 138a:0001 | Validity Sensors | VFS101 Fingerprint Reader            | 140   |            | [1EC5DF3FC1](<Notebook/Acer/Aspire/Aspire 8930/C4F378803042/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/1EC5DF3FC1>) |
| 147e:1000 | Upek             | Biometric Touchchip/Touchstrip Fi... | 139   |            | [F2BB35C6D3](<Notebook/Lenovo/ThinkPad/ThinkPad SL500 27464DG/061881953EF5/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/F2BB35C6D3>) |
| 1c7a:0801 | LighTuning Te... | Fingerprint Reader                   | 134   |            | [1BA45B2B8F](<Notebook/Acer/Aspire/Aspire 5935/30EC066DF8D7/ALT-20201124/6.2.13-UN-DEF-ALT1/X86_64/1BA45B2B8F>) |
| 04f3:0c03 | Elan Microele... | ELAN:Fingerprint                     | 131   | usbfs      | [DA1C6920B6](<Notebook/Acer/Aspire/Aspire A715-72G/753782FFE946/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/DA1C6920B6>) |
| 04f3:0c1a | Elan Microele... | ELAN:Fingerprint                     | 126   | usbfs      | [C41D566374](<Notebook/Timi/TM/TM1701/43BDC946763C/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/C41D566374>) |
| 27c6:5503 | Shenzhen Good... | Goodix FingerPrint Device            | 124   |            | [8D1F016621](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20YDS02D00/5AE2C39BD43E/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8D1F016621>) |
| 138a:0091 | Validity Sensors | VFS7552 Touch Fingerprint Sensor     | 119   |            | [644110C9B9](<Notebook/Dell/XPS/XPS 15 9560/165115A732D9/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/644110C9B9>) |
| 06cb:00e7 | Synaptics        | UWP WBDI                             | 118   | usbfs      | [5CFDD30FA7](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ay0xxx/E7F46939C8EA/UBUNTU-23.04/6.3.1-060301-GENERIC/X86_64/5CFDD30FA7>) |
| 06cb:00f9 | Synaptics        | UWP WBDI Device                      | 113   | usbfs      | [36334E327A](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 3 21AHCTO1WW/90A9FF66FC65/DEBIAN-12/6.1.0-7-AMD64/X86_64/36334E327A>) |
| 138a:0010 | Validity Sensors | VFS Fingerprint sensor               | 110   |            | [18CC14EEE0](<Notebook/Toshiba/PORTEGE/PORTEGE Z30t-A/6BE8E7B2C3D1/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/18CC14EEE0>) |
| 27c6:530c | Shenzhen Good... | Fingerprint Reader                   | 109   |            | [F838E48BD3](<Notebook/Dell/Inspiron/Inspiron 5585/C2D030B3EF9D/MANJARO/6.1.26-1-MANJARO/X86_64/F838E48BD3>) |
| 27c6:5117 | Shenzhen Good... | Fingerprint Reader                   | 102   |            | [D07874C829](<Notebook/HUAWEI/HN-WX9/HN-WX9X/1A490AF3A690/DEVUAN-4/5.10.0-21-AMD64/X86_64/D07874C829>) |

### Floppy (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 059b:0030 | Iomega           | Zip 250 (Ver 1)                      | 3     | uas, us... | [BFE2966C97](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da0xxx/CF4825367441/UBUNTU-20.04/5.4.0-73-GENERIC/X86_64/BFE2966C97>) |
| 059b:0001 | Iomega           | Zip 100 (Type 1)                     | 2     | usb_sto... | [C59A1FFF0D](<All In One/Apple/iMac13/iMac13,2/D0AC600AD6CB/ZORIN-16/5.11.0-27-GENERIC/X86_64/C59A1FFF0D>) |
| 059b:0031 | Iomega           | Zip 100 (Type 3)                     | 2     | uas, us... | [16611A8ED6](<Desktop/Dell/OptiPlex/OptiPlex 760/7440761DE40F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/16611A8ED6>) |
| 059b:0033 | Iomega           | ZIP 100                              | 2     | uas, us... | [F0912110EB](<Desktop/Hewlett-Packard/Compaq/Compaq dc5850 Small Form Factor/EED5FB81E710/FEDORA-34/5.11.16-300.FC34.X86_64/X86_64/F0912110EB>) |
| 059b:0034 | Iomega           | Zip 100 Driver                       | 1     | usb_sto... | [506F4A7C1D](<Desktop/Gigabyte Technology/B75/B75M-D3H/1CD73ECC584C/LINUXMINT-19.1/4.15.0-47-GENERIC/X86_64/506F4A7C1D>) |
| 059b:0035 | Iomega           | ZIP 750                              | 1     | usb_sto... | [87C89614B1](<Mini Pc/ZOTAC/ZBOX-AD/ZBOX-AD04/AF3EA48DA0B8/LINUXMINT-20.2/5.11.0-37-GENERIC/X86_64/87C89614B1>) |
| 13fe:1e20 | Kingston Tech... | USB DISK Pro                         | 1     | uas, us... | [8902B96F21](<Desktop/ASRock/970M/970M Pro3/DC46E5B8C22B/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/8902B96F21>) |

### Gamepad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:028e | Microsoft        | Xbox360 Controller                   | 894   | xpad       | [72D9DAC16B](<Notebook/PC Specialist/NP5/NP5x_NP6x_NP7xPNP/AF55848BA941/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/72D9DAC16B>) |
| 046d:c21d | Logitech         | F310 Gamepad [XInput Mode]           | 162   | xpad       | [1B7398E5E8](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/0651D9942811/SOLYDXK-12/6.1.0-7-AMD64/X86_64/1B7398E5E8>) |
| 046d:c21f | Logitech         | F710 Wireless Gamepad [XInput Mode]  | 150   | xpad       | [BD81A36394](<Notebook/MSI/GT72S/GT72S 6QE/825FE6306DED/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/BD81A36394>) |
| 045e:0291 | Microsoft        | Xbox 360 Wireless Receiver for Wi... | 101   | xpad       | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 2563:0575 | ShenZhen Shan... | ZD-V+ Wired Gaming Controller        | 73    | usbhid     | [D985B7FA11](<Desktop/Others/X79/X79M2-Q/ADD4862D0303/LILIDOG-22/5.10.0-21-AMD64/X86_64/D985B7FA11>) |
| 0079:0011 | DragonRise       | Gamepad                              | 60    | usbhid     | [0295AB04A7](<Desktop/ASRock/B550/B550M-ITX-ac/58A21D9601B8/OPENSUSE-LEAP-15.4/5.14.21-150400.24.55-DEFAULT/X86_64/0295AB04A7>) |
| 0e8f:0003 | GreenAsia        | MaxFire Blaze2                       | 35    | usbhid     | [86D8D7F80F](<Desktop/ASUSTek Computer/All/All Series/54D5903B2283/MX-21/6.1.15-2-LIQUORIX-AMD64/X86_64/86D8D7F80F>) |
| 0079:181c | DragonRise       | Android Gamepad                      | 33    | usbhid     | [48A539F108](<Notebook/Itautec/Infoway/Infoway w7535/D928F6851B7B/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/48A539F108>) |
| 0810:e501 | Personal Comm... | SNES Gamepad                         | 27    | usbhid     | [4FBBE6E603](<Desktop/Tarox/ECO/ECO 44 G4/16EF7D503221/ZORIN-16/5.15.0-71-GENERIC/X86_64/4FBBE6E603>) |
| 0e6f:0213 | Logic3           | Afterglow Gamepad for Xbox 360       | 13    | xpad       | [B21CD49226](<Desktop/Gigabyte Technology/B460M/B460M DS3H AC V2-Y1/F829F318BE8F/CHIMERAOS-39/6.1.11-ARCH1-1/X86_64/B21CD49226>) |
| 0e6f:011f | Logic3           | Rock Candy Wired Controller for X... | 12    | xpad       | [01195F072E](<Desktop/Supermicro/X9/X9SAE/D7976D9E5CAC/POP!_OS-21.04/5.11.0-7614-GENERIC/X86_64/01195F072E>) |
| 0e6f:0413 | Logic3           | Afterglow AX.1 Gamepad for Xbox 360  | 9     | xpad       | [EA11DF2A20](<Desktop/ASRock/QC5000/QC5000M/C667FAEF468E/OPENMANDRIVA-4.50/5.19.5-DESKTOP-1OMV4090/X86_64/EA11DF2A20>) |
| 046d:c21e | Logitech         | F510 Gamepad [XInput Mode]           | 8     | xpad       | [4CF62D2B87](<Desktop/Intel/DH67CL/DH67CL AAG10212-210/1226CF32B431/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/4CF62D2B87>) |
| 0583:a000 | Padix (Rockfire) | MaxFire G-08XU Gamepad               | 8     | usbhid     | [1F3953650C](<Desktop/ASRock/N68-VS3/N68-VS3 FX/D968CA13888E/LOC-OS-22/5.10.165-LOC-OS/X86_64/1F3953650C>) |
| 7545:1122 | SZ-MYPOWER       | PC Gamepad                           | 7     | usbhid     | [DFBB481B02](<Desktop/MSI/MS-7/MS-7A62/F853E3BA0798/KDE-NEON-22.04/5.15.0-67-GENERIC/X86_64/DFBB481B02>) |
| 07b5:0213 | Mega World In... | Thrustmaster Firestorm Digital 3 ... | 6     | usbhid     | [92981C741D](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/523BF7EA761C/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/92981C741D>) |
| 0e8f:0008 | GreenAsia        | PS Gamepad                           | 6     | usbhid     | [3A087BC020](<Desktop/Compaq/WE144AA-ABU/WE144AA-ABU CQ5305UK/D86495F062BE/XUBUNTU-22.04/5.19.0-35-GENERIC/X86_64/3A087BC020>) |
| 0e8f:0012 | GreenAsia        | Joystick/Gamepad                     | 6     | usbhid     | [55C4E8059C](<Desktop/ASRock/960GM-VGS3/960GM-VGS3 FX/34A023F74C11/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/55C4E8059C>) |
| 0e8f:310d | GreenAsia        | USB Controller                       | 6     | usbhid     | [0239336B7C](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/AD45FC07C7BA/UBUNTU-20.04/5.4.0-33-GENERIC/X86_64/0239336B7C>) |
| 046d:c242 | Logitech         | XUSB Gamepad                         | 5     | xpad       | [8AE6499ADF](<Desktop/ELECTRON-SERVICES/ESTUDIO/ESTUDIO/7E912695E4B2/ROSA-12.2/5.10.118-GENERIC-2ROSA2021.1-X86_64/X86_64/8AE6499ADF>) |
| 145f:01c5 | Trust            | Gamepad                              | 5     | usbhid     | [93A093110A](<Desktop/ASUSTek Computer/All/All Series/180F9B80D6FF/UBUNTU-20.04/5.8.0-55-GENERIC/X86_64/93A093110A>) |
| 0e6f:f501 | Logic3           | Hi-TEC Essentials Wired Gamepad      | 4     | xpad       | [0983BF28B6](<Desktop/ASRock/970M/970M Pro3/D565F9D915AC/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/0983BF28B6>) |
| 11c9:55f0 | Nacon            | GC-100XF                             | 4     | usbhid     | [575A7F4897](<Desktop/MSI/MS-7/MS-7D96/AB7519B92213/GARUDA-SOARING/6.1.12-ZEN1-1-ZEN/X86_64/575A7F4897>) |
| 1345:6006 | Sino Lite Tec... | Defender Wireless Controller         | 4     |            | [1A9077AB60](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 R2/ED33D8263F9F/DEBIAN-10/4.19.0-8-AMD64/X86_64/1A9077AB60>) |
| 145f:0231 | Trust            | USB Gamepad                          | 4     | usbhid     | [C7CA0E9FD1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/25F0D5566E16/FEDORA-37/5.16.2-RT19.FC34.X86_64/X86_64/C7CA0E9FD1>) |
| 0e6f:0201 | Logic3           | TSZ360 Pad                           | 3     | xpad       | [048B7BCF6A](<Desktop/ABIT/I-G/I-G31/AFE1ED3BF69C/UBUNTU-20.04/5.11.0-41-GENERIC/X86_64/048B7BCF6A>) |
| 0e8f:3013 | GreenAsia        | USB GamePad                          | 3     | usbhid     | [DEC0D049F7](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE/33E1B28F5852/ZORIN-16/5.15.0-56-GENERIC/X86_64/DEC0D049F7>) |
| 11c0:5500 | Betop            | USB GAME PAD                         | 3     | usbhid     | [3771B8BF2E](<Desktop/Dell/OptiPlex/OptiPlex 5060/9E0DB76EF8B9/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/3771B8BF2E>) |
| 146b:5500 | BigBen Intera... | Usb Gamepad                          | 3     | usbhid     | [AB62777CB6](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P720/FFF12BD3239C/LINUXMINT-20.2/5.4.0-91-GENERIC/X86_64/AB62777CB6>) |
| 1689:fd00 | Razer USA        | Onza Tournament Edition controller   | 3     | xpad       | [4F32A1C7C6](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/B2A954F82FA2/UBUNTU-20.04/5.15.0-46-GENERIC/X86_64/4F32A1C7C6>) |
| 1bad:f016 | Harmonix Music   | Controller                           | 3     | xpad       | [B17B635FCB](<Desktop/Dell/Inspiron/Inspiron 3650/4CE239AE6540/UBUNTU-20.04/5.15.0-52-GENERIC/X86_64/B17B635FCB>) |
| 1bad:fa01 | Harmonix Music   | Gamepad                              | 3     | xpad       | [4AA6A34C0C](<Notebook/Samsung Electronics/RC530/RC530-RC730/AE11140B6A56/GENTOO-2.6/5.4.80-GENTOO-R1/X86_64/4AA6A34C0C>) |
| 24c6:5b02 | ThrustMaster     | GPX Gamepad                          | 3     | xpad       | [653E8EDAB3](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/D7C334EEC193/UBUNTU-20.04/5.4.0-54-GENERIC/X86_64/653E8EDAB3>) |
| 050d:0805 | Belkin Compon... | Nostromo N50 GamePad                 | 2     | usbhid     | [285B5B2D08](<Desktop/Gigabyte Technology/B450M/B450M S2H/1A51DBD9A55B/KUBUNTU-20.10/5.8.0-44-GENERIC/X86_64/285B5B2D08>) |
| 06d6:0026 | Aashima Techn... | Predator TH 400 Gamepad              | 2     | usbhid     | [372CDC3726](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/726CBD620443/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/372CDC3726>) |
| 07b5:0312 | Mega World In... | Gamepad                              | 2     | usbhid     | [A4A0A9E165](<Desktop/Hewlett-Packard/GZ679AA-ABF/GZ679AA-ABF a6295.fr/9E4431E4B2E5/UBUNTU-20.04/5.13.0-27-GENERIC/X86_64/A4A0A9E165>) |
| 0e6f:011e | Logic3           | Rock Candy Gamepad for PS3           | 2     | usbhid     | [82ABA65015](<Notebook/Dell/Inspiron/Inspiron 3593/BFE606D4F6F4/MANJARO/5.10.0-1-MANJARO/X86_64/82ABA65015>) |
| 1a34:0802 | ACRUX            | Gamepad                              | 2     | usbhid     | [609FFD75B7](<Notebook/Lenovo/B560/B560 43308VG/B3CA7A2AD047/KDE-NEON-20.04/5.13.0-30-GENERIC/X86_64/609FFD75B7>) |
| 24c6:fafc | Performance D... | Afterglow Gamepad for Xbox 360       | 2     | xpad       | [F34C588CFE](<Desktop/ASUSTek Computer/M5A99FX/M5A99FX PRO R2.0/BF3065B532AE/POP!_OS-20.04/5.4.0-7634-GENERIC/X86_64/F34C588CFE>) |
| 24c6:fafe | ThrustMaster     | Rock Candy Gamepad for Xbox 360      | 2     | xpad       | [DEF987E32C](<Desktop/ASRock/B365/B365M-HDV/F0C269B393DF/ARCH-ROLLING/6.2.1-ARCH1-1/X86_64/DEF987E32C>) |
| 2563:058d | ShenZhen Shan... | Cloud Gamepad                        | 2     | xpad       | [B127C7B5E0](<Notebook/ONE-NETBOOK TECHNOLOGY/ONE/ONE XPLAYER/CEAAC50AC7AB/BUILDROOT-2021.08.1/5.14.12/X86_64/B127C7B5E0>) |
| 2dc8:6001 | 8BitDo           | SN30/SF30 Pro gamepad                | 2     | usbhid     | [27343A622F](<Notebook/ASUSTek Computer/ROG/ROG Strix G733QS_G733QS/0D1C348084E3/ARCH-ROLLING/5.18.6-ZEN1-1.1-ZEN/X86_64/27343A622F>) |
| 7545:0104 | SZ-MYPOWER       | DS4 Wired Controller                 | 2     | usbhid     | [11EB2546C1](<Desktop/Vorke/V1/V1 Plus/5DD9E2EFF86F/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/11EB2546C1>) |
| 0079:1855 | DragonRise       | PS3/PC WirelessGamePad               | 1     | usbhid     | [A76227F148](<Desktop/Gigabyte Technology/B450/B450 AORUS PRO/330B4A607473/UBUNTU-20.04/5.7.2/X86_64/A76227F148>) |
| 0079:1879 | DragonRise       | USB GamePad                          | 1     | usbhid     | [E59D15EE54](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/DF34B351DE27/ARCH-ROLLING/5.15.59-2-LTS/X86_64/E59D15EE54>) |
| 0079:954e | DragonRise       | NGC USB Gamepad                      | 1     | usbhid     | [398B45ED60](<Desktop/Dell/OptiPlex/OptiPlex 790/54C6DC6065E9/LINUXMINT-20.2/5.4.0-96-GENERIC/X86_64/398B45ED60>) |
| 040b:6530 | Weltrend Semi... | USB 2A8K GamePad                     | 1     | usbhid     | [0539EEEEB8](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/CCFE86F30A4D/XUBUNTU-20.04/5.4.0-59-LOWLATENCY/X86_64/0539EEEEB8>) |
| 044f:b311 | ThrustMaster     | analog gamepad                       | 1     | usbhid     | [BEE196BACE](<Desktop/ASUSTek Computer/M4/M4A87TD-USB3/C3FE6804A70A/LINUXMINT-19.3/5.4.0-81-GENERIC/X86_64/BEE196BACE>) |
| 044f:b326 | ThrustMaster     | GPX Gamepad                          | 1     | xpad       | [3C19F51786](<Desktop/ASUSTek Computer/P5/P5Q-EM/759343D4D1CF/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/3C19F51786>) |
| 045e:0026 | Microsoft        | SideWinder GamePad Pro               | 1     | usbhid     | [F8BFAA2C3D](<Notebook/Acer/Aspire/Aspire ES1-531/DEA928C93DC0/UBUNTU-19.04/5.0.0-34-GENERIC/X86_64/F8BFAA2C3D>) |

### Hardware key (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0a89:0020 | Aktiv            | Rutoken S                            | 13    | usbfs      | [7B4EEEBDBC](<All In One/Acer/Aspire/Aspire C24-963/E4A4E93BCF0A/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/7B4EEEBDBC>) |
| 0a89:0003 | Aktiv            | Guardant Stealth 2                   | 12    | usbfs      | [5A21B5ACB8](<Desktop/Gigabyte Technology/B75/B75M-D2V/135BE0B8C1AB/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/5A21B5ACB8>) |
| 0471:485d | Philips (or NXP) | Senselock SenseIV v2.x               | 7     |            | [C2766F4AC5](<Notebook/Sony/SVT1313/SVT1313X9RS/2745F3AFB8FF/ROSA-12.3/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/C2766F4AC5>) |
| 14a8:0001 | Soft protecti... | Soft protection device: USB Prote... | 5     |            | [808E7E41C5](<Desktop/ASUSTek Computer/P7/P7H55-M/71BF3B74D8D1/ALT-10.1/5.15.72-UN-DEF-ALT1/X86_64/808E7E41C5>) |

### Hasp (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0529:0001 | Aladdin Knowl... | HASP copy protection dongle          | 97    | usbfs      | [96BF9B40AC](<Desktop/Biostar/G41/G41D3C/107E70C61AF7/ROSA-12.4/5.15.103-GENERIC-1ROSA2021.1-X86_64/X86_64/96BF9B40AC>) |

### Hub (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1d6b:0002 | Linux Foundation | 2.0 root hub                         | 19... | hub        | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 1d6b:0003 | Linux Foundation | 3.0 root hub                         | 13... | hub        | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 1d6b:0001 | Linux Foundation | 1.1 root hub                         | 47458 | hub        | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 8087:0024 | Intel            | Integrated Rate Matching Hub         | 29426 | hub        | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 05e3:0608 | Genesys Logic    | Hub                                  | 13054 | hub        | [1F7840B315](<Notebook/ASUSTek Computer/X200/X200MA/A3B42A7B6114/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/1F7840B315>) |
| 8087:8000 | Intel            | Integrated Rate Matching Hub         | 12907 | hub        | [B5C0679341](<Desktop/MSI/MS/MS-7817/73BC5E06C84D/GENTOO-2.13/6.3.1-GENTOO/X86_64/B5C0679341>) |
| 05e3:0610 | Genesys Logic    | Hub                                  | 10200 | hub        | [535CC48341](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/535CC48341>) |
| 8087:8008 | Intel            | Integrated Rate Matching Hub         | 8731  | hub        | [B5C0679341](<Desktop/MSI/MS/MS-7817/73BC5E06C84D/GENTOO-2.13/6.3.1-GENTOO/X86_64/B5C0679341>) |
| 1a40:0101 | Terminus Tech... | Hub                                  | 7773  | hub        | [C95999B5AD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26/DEBIAN-11/5.10.0-22-AMD64/X86_64/C95999B5AD>) |
| 8087:0020 | Intel            | Integrated Rate Matching Hub         | 6705  | hub        | [3CDF8244EF](<Desktop/Acer/Aspire/Aspire M5811/BD71CFB0AF65/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/3CDF8244EF>) |
| 0a5c:4500 | Broadcom         | BCM2046B1 USB 2.0 Hub (part of BC... | 4226  | hub        | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 8087:8001 | Intel            | Integrated Hub                       | 3863  | hub        | [0EFF8F87C6](<Notebook/Dell/Latitude/Latitude E7450/9DC8CA3DF416/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/0EFF8F87C6>) |
| 0438:7900 | AMD              | Root Hub                             | 3529  | hub        | [DEF28849C6](<Notebook/Lenovo/IdeaPad/IdeaPad 110-15ACL 80TJ/DB0B516E7227/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/DEF28849C6>) |
| 0bda:5411 | Realtek Semic... | RTS5411 Hub                          | 3305  | hub        | [D6C6781535](<Notebook/Avell High Performance/A65/A65 MOB/1D6F35E22C18/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D6C6781535>) |
| 2109:3431 | VIA Labs         | Hub                                  | 2900  | hub        | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 0bda:0411 | Realtek Semic... | Hub                                  | 2604  | hub        | [D6C6781535](<Notebook/Avell High Performance/A65/A65 MOB/1D6F35E22C18/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D6C6781535>) |
| 2109:2817 | VIA Labs         | USB2.0 Hub                           | 2198  | hub        | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 2109:0817 | VIA Labs         | USB3.0 Hub                           | 1899  | hub        | [83C0648D66](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/8E4EC01957FA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/83C0648D66>) |
| 05e3:0626 | Genesys Logic    | Hub                                  | 1877  | hub        | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 0424:2514 | Microchip Tec... | USB 2.0 Hub                          | 1839  | hub        | [08DF3C35EE](<Desktop/Dell/OptiPlex/OptiPlex 7040/74B9A8608B3A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/08DF3C35EE>) |
| 174c:2074 | ASMedia Techn... | ASM1074 High-Speed hub               | 1706  | hub        | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 174c:3074 | ASMedia Techn... | ASM1074 SuperSpeed hub               | 1673  | hub        | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 2109:2813 | VIA Labs         | VL813 Hub                            | 1646  | hub        | [A0073C6FF3](<Notebook/Apple/MacBookAir9/MacBookAir9,1/1060561AE5DA/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/A0073C6FF3>) |
| 05e3:0612 | Genesys Logic    | Hub                                  | 1609  | hub        | [FD830A3568](<Desktop/Gigabyte Technology/P35/P35-DS4/7541C3B6BD81/LINUXMINT-21/5.15.0-71-GENERIC/X86_64/FD830A3568>) |
| 2109:2812 | VIA Labs         | VL812 Hub                            | 1406  | hub        | [9A4BA61D41](<Notebook/Dell/Precision/Precision 5510/6065C667D1D1/FEDORA-38/6.2.14-703.INTTF.FC38.X86_64/X86_64/9A4BA61D41>) |
| 8087:8009 | Intel            | Hub                                  | 1375  | hub        | [2CBD56ABDC](<Notebook/Notebook/P750/P750ZM/51A3147C30B6/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/2CBD56ABDC>) |
| 2109:0813 | VIA Labs         | VL813 Hub                            | 1300  | hub        | [A0073C6FF3](<Notebook/Apple/MacBookAir9/MacBookAir9,1/1060561AE5DA/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/A0073C6FF3>) |
| 214b:7250 | Huasheng Elec... | USB2.0 HUB                           | 1300  | hub        | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 05e3:0620 | Genesys Logic    | GL3523 Hub                           | 1207  | hub        | [535CC48341](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/535CC48341>) |
| 2109:0812 | VIA Labs         | VL812 Hub                            | 1133  | hub        | [8D1F016621](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20YDS02D00/5AE2C39BD43E/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8D1F016621>) |
| 8087:8002 | Intel            | 8 channel internal hub               | 1002  | hub        | [BC30B63CE3](<Desktop/MSI/MS/MS-7885/34D003A502BB/FEDORA-36/6.0.7-200.FC36.X86_64/X86_64/BC30B63CE3>) |
| 8087:800a | Intel            | Hub                                  | 1001  | hub        | [BC30B63CE3](<Desktop/MSI/MS/MS-7885/34D003A502BB/FEDORA-36/6.0.7-200.FC36.X86_64/X86_64/BC30B63CE3>) |
| 0409:005a | NEC Computers    | HighSpeed Hub                        | 916   | hub        | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |
| 058f:6254 | Alcor Micro      | USB Hub                              | 867   | hub        | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 05e3:0606 | Genesys Logic    | USB 2.0 Hub / D-Link DUB-H4 USB 2... | 833   | hub        | [94294C8CF0](<Desktop/Dell/OptiPlex/OptiPlex 360/A182B9C1083D/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/94294C8CF0>) |
| 05e3:0616 | Genesys Logic    | hub                                  | 816   | hub        | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 05ac:1006 | Apple            | Hub in Aluminum Keyboard             | 753   | hub        | [8E19B0629D](<Notebook/Dell/Inspiron/Inspiron 3505/4FD07B29A2E4/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/8E19B0629D>) |
| 0451:8142 | Texas Instrum... | TUSB8041 4-Port Hub                  | 689   | hub        | [4681975F9D](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/4681975F9D>) |
| 1a40:0801 | Terminus Tech... | USB 2.0 Hub                          | 689   | hub        | [D3DE6B6B31](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ee1xxx/EEC49B509995/ARCO-ROLLING/6.2.13-ARCH1-1/X86_64/D3DE6B6B31>) |
| 1a40:0201 | Terminus Tech... | FE 2.1 7-port Hub                    | 682   | hub        | [0C0AD48CC6](<Desktop/ASRock/X670E/X670E Steel Legend/5A578B12BFEA/MANJARO-22.1.0/6.2.12-1-MANJARO/X86_64/0C0AD48CC6>) |
| 0424:2134 | Microchip Tec... | Hub                                  | 676   | hub        | [B5602599F8](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/3BE7A14EC8D5/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/B5602599F8>) |
| 2109:2811 | VIA Labs         | Hub                                  | 675   | hub        | [F23FB5CCA0](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DT_FX505DT/69E8EF1A2769/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/F23FB5CCA0>) |
| 0424:2513 | Microchip Tec... | 2.0 Hub                              | 670   | hub        | [A8D45AC430](<Notebook/Apple/MacBookPro9/MacBookPro9,2/F2D429C722A3/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/A8D45AC430>) |
| 14cd:8601 | Super Top        | 4-Port hub                           | 669   | hub        | [558C305AF2](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/558C305AF2>) |
| 045b:0209 | Hitachi          | Hub                                  | 650   | hub        | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |
| 0424:5534 | Microchip Tec... | Hub                                  | 634   | hub        | [B5602599F8](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/3BE7A14EC8D5/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/B5602599F8>) |
| 0b97:7761 | O2 Micro         | Oz776 1.1 Hub                        | 614   | hub        | [8EF701B61D](<Notebook/Dell/MXG/MXG061/F0E8113D6028/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/8EF701B61D>) |
| 058f:9254 | Alcor Micro      | Hub                                  | 597   | hub        | [3ED55D530A](<Desktop/Gigabyte Technology/H61/H61M-S2PV/DE2D1C5C4F5E/ALT-10.1/5.10.179-STD-DEF-ALT1/X86_64/3ED55D530A>) |
| 0a05:7211 |                  | hub                                  | 572   | hub        | [0458D9F44B](<Desktop/Gigabyte Technology/G41/G41MT-S2/EF1568975525/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0458D9F44B>) |
| 045b:0210 | Hitachi          | Hub                                  | 533   | hub        | [22BD54D6D1](<Desktop/Gigabyte Technology/Z87/Z87X-UD3H/F9D737247AAE/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/22BD54D6D1>) |

### Human interface (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 05ac:8242 | Apple            | Built-in IR Receiver                 | 2300  | usbhid     | [51EBA04846](<All In One/Apple/iMac8/iMac8,1/D19176E847E3/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/51EBA04846>) |
| 048d:5702 | Integrated Te... | RGB LED Controller                   | 1096  | usbhid     | [47388F4553](<Desktop/Gigabyte Technology/X570S/X570S AORUS PRO AX/82196083E848/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/47388F4553>) |
| 1770:ff00 | MSI              | steel series rgb keyboard            | 521   | usbhid     | [370F9304B6](<Notebook/MSI/GS70/GS70 2PC Stealth/4189E50207CD/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/370F9304B6>) |
| 26ce:01a2 | ASRock           | LED Controller                       | 490   | usbhid     | [CF7CF903C0](<Desktop/ASRock/B760/B760 Pro RS-D4/22BCEB943676/DEBIAN-12/6.1.0-8-AMD64/X86_64/CF7CF903C0>) |
| 0483:91d1 | STMicroelectr... | Sensor Hub                           | 435   | usbhid     | [30BD232E19](<Notebook/Dell/Inspiron/Inspiron 13-7359/C7A44F1093EF/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/30BD232E19>) |
| 413c:b06e | Dell             | dock                                 | 359   | usbhid     | [5F962AAEA0](<Notebook/Dell/Precision/Precision 7550/8C478B25D8B8/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/5F962AAEA0>) |
| 413c:b06f | Dell             | dock                                 | 358   | usbhid     | [5F962AAEA0](<Notebook/Dell/Precision/Precision 7550/8C478B25D8B8/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/5F962AAEA0>) |
| 1462:7c37 | Micro Star In... | MYSTIC LIGHT                         | 340   | usbhid     | [46894747B1](<Desktop/MSI/MS-7/MS-7C37/9E9208EB0239/ZORIN-16/5.15.0-71-GENERIC/X86_64/46894747B1>) |
| 0451:82ff | Texas Instrum... | Monitor Control                      | 325   | usbhid     | [1143344E93](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/CA2CCEE62824/ARCO-ROLLING/6.2.13-ARCH1-1/X86_64/1143344E93>) |
| 0b05:1872 | ASUSTek Computer | AURA LED Controller                  | 316   | usbhid     | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 1038:1122 | SteelSeries ApS  | SteelSeries KLC                      | 287   | usbhid     | [E10CCC96BD](<Notebook/MSI/GE75/GE75 Raider 10SF/B41120CA6BCF/ENDLESS-5.0.3/5.15.0-47-GENERIC/X86_64/E10CCC96BD>) |
| 187c:0550 | Alienware        | LED controller                       | 287   | usbhid     | [81024F3DF4](<Notebook/Dell/G15/G15 5520/490AF523329C/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/81024F3DF4>) |
| 0079:0006 | DragonRise       | PC TWIN SHOCK Gamepad                | 275   | usbhid     | [D27392828F](<Desktop/ASRock/A320M-HDV/A320M-HDV R4.0/DDF6FDC2A438/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/D27392828F>) |
| 0424:274c | Microchip Tec... | Hub Controller                       | 226   | usbhid     | [AFFFCCEF92](<Desktop/ASRock/H370/H370 Pro4/F40034DAFD1F/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/AFFFCCEF92>) |
| 0bda:1100 | Realtek Semic... | USB2.0 HID                           | 213   | usbhid     | [4CD6AB54BA](<Notebook/AZW/SEi/SEi/8583C4662416/LMDE-5/5.16.0-0.BPO.4-AMD64/X86_64/4CD6AB54BA>) |
| 0b05:18a3 | ASUSTek Computer | AURA MOTHERBOARD                     | 199   | usbhid     | [A4F7FC7B31](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/D242E68778A8/ARCO-ROLLING/6.1.27-1-LTS/X86_64/A4F7FC7B31>) |
| 1462:7c91 | Micro Star In... | MYSTIC LIGHT                         | 175   | usbhid     | [F0BC6CA2DD](<Desktop/MSI/MS-7/MS-7C91/E8FA683D3AE7/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/F0BC6CA2DD>) |
| 05ac:8240 | Apple            | Built-in IR Receiver                 | 155   | usbhid     | [C7444AC7F0](<All In One/Apple/iMac5/iMac5,1/104264B0BD86/XUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/C7444AC7F0>) |
| 1462:7c56 | Micro Star In... | MYSTIC LIGHT                         | 151   | usbhid     | [8FF62A5045](<Desktop/MSI/MS-7/MS-7C56/0BC080AA3E4A/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/8FF62A5045>) |
| 043e:9a39 | LG Electronics   | LG Monitor Controls                  | 147   | usbhid     | [4681975F9D](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/4681975F9D>) |
| 1b1c:0c04 | Corsair          | Link Cooling Node                    | 147   | usbhid     | [DB1AD69341](<Desktop/MSI/MS-7/MS-7D17/0B3A86521786/REBORNOS-ROLLING/6.3.1-ARCH1-1/X86_64/DB1AD69341>) |
| 1e71:170e | NZXT             | Kraken X                             | 146   | usbhid     | [89A9759DFB](<Desktop/MSI/MS-7/MS-7B10/FFD3A2D868A0/FEDORA-39/6.4.0-0.RC0.20230501GIT58390C8CE1BD.10.FC39.X86_64/X86_64/89A9759DFB>) |
| 054c:0268 | Sony             | Batoh Device / PlayStation 3 Cont... | 139   | usbhid     | [C88845AE9B](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/F6418012BC03/GENTOO-2.13/6.3.1-GENTOO-POLARIS/X86_64/C88845AE9B>) |
| 1e71:2007 | NZXT             | USB Device                           | 139   | usbhid     | [36F1AA431D](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/C7CA1B973424/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/36F1AA431D>) |
| 1b1c:0c1a | Corsair          | Lighting Node CORE                   | 132   | usbhid     | [E34348C1B5](<Desktop/MSI/MS-7/MS-7D04/932649C6C043/XUBUNTU-22.10/5.19.0-41-GENERIC/X86_64/E34348C1B5>) |
| 0b05:1867 | ASUSTek Computer | AURA Custom Human interface          | 130   | usbhid     | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 1b1c:0c0b | Corsair          | Lighting Node Pro                    | 129   | usbhid     | [E42327B375](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/402936B429DF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/E42327B375>) |
| 06c4:c411 | Bizlink Inter... | D6000 Controller                     | 127   | usbhid     | [535CC48341](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/535CC48341>) |
| 0665:5161 | Cypress Semic... | USB to Serial                        | 123   | usbhid     | [A418B302B9](<Desktop/Gigabyte Technology/AX370-Gaming/AX370-Gaming 5/416EA170AA18/KDE-NEON-22.04/6.3.0-060300-GENERIC/X86_64/A418B302B9>) |
| 0765:5010 | X-Rite           | X-Rite Pantone Color Sensor          | 122   | usbhid     | [228AEC8C45](<Notebook/Lenovo/ThinkPad/ThinkPad W540 20BHS1J000/58E500E065B5/LINUXMINT-20.3/5.4.0-139-GENERIC/X86_64/228AEC8C45>) |
| 0451:ca01 | Texas Instrum... | USBtoI2C Solution                    | 107   | usbhid     | [3FC4048A96](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-A/7D43E07684EE/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/3FC4048A96>) |
| 1b1c:0c1c | Corsair          | iCUE Commander CORE                  | 107   | usbhid     | [424F0DCA9D](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/E2B929AE2E0E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/424F0DCA9D>) |
| 10d5:55a2 | Uni Class Tec... | 2Port KVMSwitcher                    | 105   | usbhid     | [A897208085](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 DM 35W/AD547826B46E/ELEMENTARY-7/5.19.0-40-GENERIC/X86_64/A897208085>) |
| 046d:c215 | Logitech         | Extreme 3D Pro                       | 97    | usbhid     | [64B15B4B1D](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/9D0A0487565C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/64B15B4B1D>) |
| 1b1c:0c10 | Corsair          | Commander PRO                        | 96    | usbhid     | [F8D80B7CF0](<Desktop/MSI/MS-7/MS-7B93/9B919BEA6FCB/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/F8D80B7CF0>) |
| 048d:8350 | Integrated Te... | ITE Device(8350)                     | 91    | usbhid     | [EA620E0681](<All In One/Acer/Aspire/Aspire Z3-600/BD66BD02AA7B/LINUX-LITE-6.4/5.15.0-71-GENERIC/X86_64/EA620E0681>) |
| 046d:c216 | Logitech         | F310 Gamepad [DirectInput Mode]      | 89    | usbhid     | [86E2D42F73](<All In One/Apple/iMac10/iMac10,1/3F3B3E1E7298/ZORIN-16/5.15.0-69-GENERIC/X86_64/86E2D42F73>) |
| 046d:c227 | Logitech         | G15 Refresh Keyboard                 | 88    | usbhid     | [5881A47FD0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/DCE3BBAEAA2E/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/5881A47FD0>) |
| 054c:05c4 | Sony             | DualShock 4 [CUH-ZCT1x]              | 88    | usbhid     | [62F2094D3C](<Desktop/Gigabyte Technology/B550/B550 AORUS PRO V2/2A263243EC13/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/62F2094D3C>) |
| 0810:0001 | Personal Comm... | Dual PSX Adaptor                     | 88    | usbhid     | [2E542C241D](<Notebook/Lenovo/Legion/Legion 5 17IMH05 82B3/B59FA762DAD8/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/2E542C241D>) |
| 1e71:2006 | NZXT             | Smart Device V2                      | 87    | usbhid     | [E35B234E43](<Desktop/Lenovo/ThinkCentre/ThinkCentre M83 10AHS0CK14/29258FB520FE/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E35B234E43>) |
| 1462:7c95 | Micro Star In... | MYSTIC LIGHT                         | 84    | usbhid     | [76748DA9CD](<Desktop/MSI/MS-7/MS-7C95/E2E66E37A3EB/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/76748DA9CD>) |
| 056a:00e6 | Wacom            | TPCE6                                | 83    | usbhid     | [2DF9760E40](<Notebook/Lenovo/ThinkPad/ThinkPad X230T 343824G/C9537D73E906/LINUXMINT-20.1/5.4.0-147-GENERIC/X86_64/2DF9760E40>) |
| 1462:7c84 | Micro Star In... | MYSTIC LIGHT                         | 80    | usbhid     | [3A39BF574B](<Desktop/MSI/MS-7/MS-7C84/BB81B9983F93/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/3A39BF574B>) |
| 1462:7c35 | Micro Star In... | MYSTIC LIGHT                         | 77    | usbhid     | [B2311E7CAC](<Desktop/MSI/MS-7/MS-7C35/CB298ECF07E8/ZORIN-16/5.15.0-69-GENERIC/X86_64/B2311E7CAC>) |
| 05ac:1392 | Apple            | Apple Watch charger                  | 76    | usbhid     | [D8582F94DE](<Notebook/Lenovo/Legion/Legion 7 16ACHg6 82N6/3030BDAF960B/ZORIN-16/5.15.0-71-GENERIC/X86_64/D8582F94DE>) |
| 1038:113a | SteelSeries ApS  | SteelSeries KLC                      | 75    | usbhid     | [1396746FBA](<Notebook/MSI/Creator/Creator Z17 A12UHST/307C1ABEEA3B/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/1396746FBA>) |
| 1038:1290 | SteelSeries ApS  | Arctis Pro Wireless                  | 75    | usbhid     | [36F1AA431D](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/C7CA1B973424/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/36F1AA431D>) |
| 1462:7c94 | Micro Star In... | MYSTIC LIGHT                         | 75    | usbhid     | [26C158DF39](<Desktop/MSI/MS-7/MS-7C94/DD638739FE3A/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/26C158DF39>) |
| 10d5:55a4 | Uni Class Tec... | 4 Port KVMSwicther                   | 73    | usbhid     | [405CE5A9C8](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G5/670A4B328593/LINUXMINT-21.1/5.19.0-35-GENERIC/X86_64/405CE5A9C8>) |

### Infrared (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0609:031d | SMK Manufactu... | eHome Infrared Receiver              | 8     | mceusb     | [5EEE2883A9](<Desktop/MSI/MS/MS-7693/FA139E5FA555/LINUXMINT-21/5.15.0-43-GENERIC/X86_64/5EEE2883A9>) |
| 066f:4200 | SigmaTel         | STIr4200 IrDA Bridge                 | 8     | stir4200   | [6A698DDA57](<Desktop/ASRock/G41/G41C-GS/37DB63762575/KUBUNTU-22.10/5.19.0-35-GENERIC/X86_64/6A698DDA57>) |
| 1509:9242 | FIC              | eHome Infrared Transceiver           | 7     | mceusb     | [CB90C411CA](<Notebook/MAXDATA/o.max_5xs/o.max_5xs/3D5216C7071A/GENTOO-2.13/6.1.19-GENTOO/I686/CB90C411CA>) |
| 147a:e017 | Formosa Indus... | eHome Infrared Receiver              | 4     | mceusb     | [B2CC52D381](<Notebook/MSI/GX/GX700/202338DAFBD7/DEBIAN-11/5.10.0-13-AMD64/X86_64/B2CC52D381>) |

### Input/keyboard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:c52b | Logitech         | Unifying Receiver                    | 16933 | usbhid     | [712A246CE4](<Desktop/Acer/Aspire/Aspire M1930/0EDA29407810/LINUXMINT-21/5.15.0-56-GENERIC/X86_64/712A246CE4>) |
| 046d:c534 | Logitech         | Unifying Receiver                    | 9083  | usbhid     | [53D91DCA3C](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/53D91DCA3C>) |
| 046d:c31c | Logitech         | Keyboard K120                        | 3918  | usbhid     | [8E4CBC4837](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/5EE6E0F2768B/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/8E4CBC4837>) |
| 1c4f:0002 | SiGma Micro      | Keyboard TRACER Gamma Ivory          | 3128  | usbhid     | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |
| 062a:4101 | MosArt Semico... | Wireless Keyboard/Mouse              | 2737  | usbhid     | [577E5FE375](<Notebook/Dell/Inspiron/Inspiron N5050/4CDEB7E3AAD9/ROSA-12.4/5.15.103-GENERIC-1ROSA2021.1-X86_64/X86_64/577E5FE375>) |
| 045e:0745 | Microsoft        | Nano Transceiver v1.0 for Bluetooth  | 1927  | usbhid     | [4C3E0A0AC6](<Mini Pc/MSI/MS-B/MS-B120/3412F4B83350/UBUNTU-MATE-23.04/6.3.1-060301-GENERIC/X86_64/4C3E0A0AC6>) |
| 413c:2113 | Dell             | KB216 Wired Keyboard                 | 1449  | usbhid     | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 1a2c:2124 | China Resourc... | Keyboard                             | 1290  | usbhid     | [31123C256D](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/58F18DE5017C/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/31123C256D>) |
| 04d9:1702 | Holtek Semico... | Keyboard LKS02                       | 1201  | usbhid     | [5B240FEAED](<Notebook/Biostar/A320MH/A320MH 2.0/48D7DE9E3414/STEAMOS-3.4/5.13.0-VALVE21.3-1-NEPTUNE/X86_64/5B240FEAED>) |
| 1a2c:2d23 | China Resourc... | Keyboard                             | 1121  | usbhid     | [E80DAAA2A0](<Notebook/Toshiba/Satellite/Satellite C660/7D2F74AA85E4/LINUXMINT-20.3/5.4.0-139-GENERIC/X86_64/E80DAAA2A0>) |
| 413c:2003 | Dell             | Keyboard SK-8115                     | 1078  | usbhid     | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 413c:2107 | Dell             | KB212-B Quiet Key Keyboard           | 1065  | usbhid     | [2D767E0513](<System On Chip/Rockchip/Orange/Orange Pi 5/B6466CB0DFF0/DEBIAN-11/5.10.110-ROCKCHIP-RK3588/AARCH64/2D767E0513>) |
| 09da:9090 | A4Tech           | XL-730K / XL-750BK / XL-755BK Mice   | 1059  | usbhid     | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 04f3:0103 | Elan Microele... | ActiveJet K-2024 Multimedia Keyboard | 1010  | usbhid     | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 09da:054f | A4Tech           | USB Device                           | 969   | usbhid     | [A7FFBB2FE3](<Notebook/HT/C20/C20C/5BB5F8A81892/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/A7FFBB2FE3>) |
| 046d:c539 | Logitech         | Lightspeed Receiver                  | 921   | usbhid     | [894029CC14](<Desktop/Acer/Aspire/Aspire TC-885/084A5D543ADF/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/894029CC14>) |
| 0461:0010 | Primax Electr... | HP PR1101U / Primax PMX-KPR1101U ... | 888   | usbhid     | [2A09FB1D81](<Desktop/Gigabyte Technology/B450M/B450M DS3H/93E61F10B914/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/2A09FB1D81>) |
| 046d:c52e | Logitech         | MK260 Wireless Combo Receiver        | 860   | usbhid     | [15F1EB707F](<Notebook/Gigabyte Technology/G5/G5 KD/8A5AB0EA8453/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/15F1EB707F>) |
| 048d:8297 | Integrated Te... | IT8297 RGB LED Controller            | 824   | usbhid     | [9430B8C328](<Desktop/Gigabyte Technology/X570/X570 GAMING X/856FFDCD7D13/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-VANILLA/X86_64/9430B8C328>) |
| 045e:07b2 | Microsoft        | 2.4GHz Transceiver v8.0 used by m... | 773   | usbhid     | [1445A9B10D](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/D8A0958EB618/GETFREEOS-ROLLING/6.3.1-ARCH1-1/X86_64/1445A9B10D>) |
| 1050:0407 | Yubico.com       | Yubikey 4/5 OTP+U2F+CCID             | 753   | usbhid     | [4681975F9D](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/4681975F9D>) |
| 1c4f:0026 | SiGma Micro      | Keyboard                             | 751   | usbhid     | [68E1C1B5A4](<Desktop/Others/Others/Others/0401B4CF51F2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/68E1C1B5A4>) |
| 1a2c:4c5e | China Resourc... | USB Keyboard                         | 748   | usbhid     | [C88845AE9B](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/F6418012BC03/GENTOO-2.13/6.3.1-GENTOO-POLARIS/X86_64/C88845AE9B>) |
| 0c45:7603 | Microdia         | USB Keyboard                         | 731   | usbhid     | [AFE5236688](<Desktop/ASUSTek Computer/M3/M3A78-CM/A9A7F5C89E5A/GENTOO-2.13/6.1.19-GENTOO/X86_64/AFE5236688>) |
| 1ea7:0066 | SHARKOON Tech... | [Mediatrack Edge Mini Keyboard]      | 710   | usbhid     | [13B1131BEF](<Desktop/ASRock/H67/H67DE3-SI/ED18AAFC18F5/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/13B1131BEF>) |
| 05ac:024f | Apple            | Aluminium Keyboard (ANSI)            | 709   | usbhid     | [8D1F016621](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20YDS02D00/5AE2C39BD43E/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/8D1F016621>) |
| 28de:1205 | Valve Software   | Steam Deck Controller                | 681   | usbhid     | [E6397E7F9F](<Notebook/Valve/Jupiter/Jupiter/DCF5E243D442/STEAMOS-3.4.6/5.13.0-VALVE36-1-NEPTUNE/X86_64/E6397E7F9F>) |
| 1a2c:0e24 | China Resourc... | USB Keyboard                         | 676   | usbhid     | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 03f0:0024 | Hewlett-Packard  | KU-0316 Keyboard                     | 650   | usbhid     | [DC7B257F83](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Small Form Factor/56CDA0F2FEEF/DEBIAN-11/5.10.0-22-AMD64/X86_64/DC7B257F83>) |
| 04d9:1603 | Holtek Semico... | Keyboard                             | 644   | usbhid     | [7C1ACC3B84](<Desktop/Intel/Thurley/Thurley/39FB9806A69E/DEEPIN-23/5.15.45-AMD64-DESKTOP/X86_64/7C1ACC3B84>) |
| 1a2c:2c27 | China Resourc... | USB Keyboard                         | 641   | usbhid     | [C359F42A22](<Desktop/Intel/H/H61/3D6C0125E768/MANJARO/6.1.25-1-MANJARO/X86_64/C359F42A22>) |
| 062a:4c01 | MosArt Semico... | 2,4Ghz Wireless Transceiver [for ... | 599   | usbhid     | [C350F5ED12](<Desktop/Intel/D946GZIS/D946GZIS AAD66165-301/7C5BABF74716/ZORIN-16/5.15.0-71-GENERIC/X86_64/C350F5ED12>) |
| 045e:07f8 | Microsoft        | Wired Keyboard 600 (model 1576)      | 595   | usbhid     | [B979325EEA](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/EDB7A2296562/ROSA-12.4/6.3.1.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/B979325EEA>) |
| 258a:0001 | SINO WEALTH      | USB KEYBOARD                         | 564   | usbhid     | [7DABC9FC5C](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/7DABC9FC5C>) |
| 046d:c517 | Logitech         | LX710 Cordless Desktop Laser         | 531   | usbhid     | [386D7C9DE4](<Desktop/ASUSTek Computer/P8/P8P67-M/D3654512534B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/386D7C9DE4>) |
| 062a:5918 | MosArt Semico... | 2.4G Keyboard Mouse                  | 531   | usbhid     | [7A570EFE74](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20F9003GUS/31F60FA246ED/MX-21/5.10.0-21-AMD64/X86_64/7A570EFE74>) |
| 045e:07fd | Microsoft        | Nano Transceiver 1.1                 | 525   | usbhid     | [408CBD96C0](<Desktop/ASRock/B550/B550M-HDV/892814B13024/ZORIN-16/5.15.0-71-GENERIC/X86_64/408CBD96C0>) |
| 04b3:3025 | IBM              | NetVista Full Width Keyboard         | 522   | usbhid     | [561202C004](<Notebook/Apple/MacBookPro3/MacBookPro3,1/469E66CF314F/UBUNTU-18.04/4.15.0-211-GENERIC/I686/561202C004>) |
| 04d9:1503 | Holtek Semico... | Keyboard                             | 516   | usbhid     | [A702DF382B](<Desktop/ASRock/J4125/J4125M/BD0FBF639942/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/A702DF382B>) |
| 258a:002a | SINO WEALTH      | Gaming KB                            | 508   | usbhid     | [4D039B72A7](<Notebook/Samsung Electronics/530/530XBB/0BF4A84DFE39/LUBUNTU-22.10/5.19.0-41-GENERIC/X86_64/4D039B72A7>) |
| 0b05:1866 | ASUSTek Computer | N-KEY Device                         | 483   | usbhid     | [18B79BBFA4](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus M15 GU502LW_GU502LW/674D96FDF457/ARCO-ROLLING/6.2.11-ARCH1-1/X86_64/18B79BBFA4>) |
| 25a7:fa61 | Areson Techno... | Elecom Co., Ltd MR-K013 Multicard... | 482   | usbhid     | [407098C17F](<Desktop/NEC Computers/PC-MK33/PC-MK33MAZDN/371681A7F908/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/407098C17F>) |
| 05ac:0229 | Apple            | Internal Keyboard/Trackpad (ANSI)    | 456   | appletouch | [3DAF4FBC68](<Notebook/Apple/MacBook4/MacBook4,1/56A7948875F7/LUBUNTU-22.04/5.19.0-41-GENERIC/X86_64/3DAF4FBC68>) |
| 045e:00db | Microsoft        | Natural Ergonomic Keyboard 4000 V1.0 | 442   | usbhid     | [FBE46D0C6E](<Notebook/Lenovo/ThinkBook/ThinkBook 15 G4 IAP 21DJ/5C100EB7D9AD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FBE46D0C6E>) |
| 258a:1006 | Gaming KB        | Gaming KB                            | 436   | usbhid     | [1C9E5EE2A6](<Desktop/ASUSTek Computer/WS/WS X299 SAGE/7F377E5958FC/LINUXMINT-20.3/5.19.0-17.2-LIQUORIX-AMD64/X86_64/1C9E5EE2A6>) |
| 045e:0750 | Microsoft        | Wired Keyboard 600                   | 411   | usbhid     | [EC04C034D3](<Desktop/Dell/OptiPlex/OptiPlex 990/D0B1671560CE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EC04C034D3>) |
| 046d:c328 | Logitech         | Corded Keyboard K280e                | 411   | usbhid     | [E6EAD6E953](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/9C8C09595939/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E6EAD6E953>) |
| 046d:c31d | Logitech         | Media Keyboard K200                  | 403   | usbhid     | [948E1D2358](<Desktop/MSI/MS/MS-7388/31334B58FE3B/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/948E1D2358>) |
| 1a2c:4094 | China Resourc... | USB Keyboard                         | 403   | usbhid     | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 28de:1142 | Valve Software   | Wireless Steam Controller            | 386   | usbhid     | [1095D1EF7F](<Desktop/Gigabyte Technology/P43/P43-ES3G/A4BFA139B00C/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/1095D1EF7F>) |

### Input/mouse (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 093a:2510 | Pixart Imaging   | Optical Mouse                        | 5981  | usbhid     | [E44F7DFAC5](<Desktop/Punch Technology/PDT-702/PDT-702-1020/29C76CB9E8B7/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/E44F7DFAC5>) |
| 046d:c077 | Logitech         | Mouse                                | 5710  | usbhid     | [AFE5236688](<Desktop/ASUSTek Computer/M3/M3A78-CM/A9A7F5C89E5A/GENTOO-2.13/6.1.19-GENTOO/X86_64/AFE5236688>) |
| 046d:c52f | Logitech         | Unifying Receiver                    | 4594  | usbhid     | [ACF61A6132](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2/OPENMANDRIVA-23.03/6.2.10-DESKTOP-2.0OMV4.9MJN/X86_64/ACF61A6132>) |
| 1ea7:0064 | SHARKOON Tech... | 2.4GHz Wireless rechargeable vert... | 3082  | usbhid     | [94294C8CF0](<Desktop/Dell/OptiPlex/OptiPlex 360/A182B9C1083D/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/94294C8CF0>) |
| 275d:0ba6 |                  | USB OPTICAL MOUSE                    | 2304  | usbhid     | [97986B63AD](<Desktop/Gigabyte Technology/F2/F2A68HM-H/458432F727D5/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/97986B63AD>) |
| 0458:003a | KYE Systems (... | NetScroll+ Mini Traveler / Genius... | 2023  | usbhid     | [DE7D5668D5](<Notebook/Lenovo/G700/G700 20251/D9E47C552B1B/LINUXMINT-20.3/5.4.0-137-GENERIC/X86_64/DE7D5668D5>) |
| 1bcf:0005 | Sunplus Innov... | Optical Mouse                        | 2013  | usbhid     | [7D861ACBD6](<Desktop/Gigabyte Technology/Q87/Q87M-D2H/DEF7B8B0BDF0/LMDE-5/5.10.0-22-AMD64/X86_64/7D861ACBD6>) |
| 046d:c05a | Logitech         | M90/M100 Optical Mouse               | 1926  | usbhid     | [FE207B0DF1](<Desktop/Gigabyte Technology/H61/H61M-S2PH/7932DFB49C79/ROSA-12.4/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/FE207B0DF1>) |
| 1c4f:0034 | SiGma Micro      | XM102K Optical Wheel Mouse           | 1799  | usbhid     | [BBF20CFDAD](<Notebook/Acer/Aspire/Aspire V3-772G/5A102FB41E7C/ARCH-ROLLING/6.2.6-ARCH1-1/X86_64/BBF20CFDAD>) |
| 0000:3825 |                  | USB OPTICAL MOUSE                    | 1495  | usbhid     | [C437A16A33](<Notebook/Semp Toshiba/IS/IS 1413G/EC50067C2C26/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/C437A16A33>) |
| 248a:8367 | Maxxter          | Telink Wireless Receiver             | 1493  | usbhid     | [9A4BA61D41](<Notebook/Dell/Precision/Precision 5510/6065C667D1D1/FEDORA-38/6.2.14-703.INTTF.FC38.X86_64/X86_64/9A4BA61D41>) |
| 0000:0538 |                  | USB OPTICAL MOUSE                    | 1438  | usbhid     | [EC04C034D3](<Desktop/Dell/OptiPlex/OptiPlex 990/D0B1671560CE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EC04C034D3>) |
| 413c:301a | Dell             | Dell MS116 Optical Mouse             | 1393  | usbhid     | [58F420D816](<Notebook/Acer/NC-V3/NC-V3-772G-747A8G1TMAKK/F9DA5737F0AA/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/58F420D816>) |
| 18f8:0f97 | [Maxxter]        | Optical Gaming Mouse [Xtrem]         | 1296  | usbhid     | [D63BC9AECA](<Desktop/MSI/MS/MS-7996/30F694CCEC2B/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D63BC9AECA>) |
| 25a7:fa23 | Areson Techno... | 2.4G Receiver                        | 1266  | usbhid     | [7F274B189D](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/9D0877282214/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7F274B189D>) |
| 248a:8514 | Maxxter          | Wireless Receiver                    | 1169  | usbhid     | [169B0A5BC0](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770-US3/13F02D223AC8/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/169B0A5BC0>) |
| 10c4:8108 | Silicon Labs     | USB OPTICAL MOUSE                    | 1039  | usbhid     | [0A639BA55D](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dq2xxx/8DCCFC840116/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0A639BA55D>) |
| 09da:000a | A4Tech           | Optical Mouse Opto 510D / OP-620D    | 1033  | usbhid     | [E9A4F752C5](<Desktop/ASRock/G41/G41M-VS3/21B774A42A5B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/E9A4F752C5>) |
| 045e:00cb | Microsoft        | Basic Optical Mouse v2.0             | 1001  | usbhid     | [FD830A3568](<Desktop/Gigabyte Technology/P35/P35-DS4/7541C3B6BD81/LINUXMINT-21/5.15.0-71-GENERIC/X86_64/FD830A3568>) |
| 093a:2521 | Pixart Imaging   | Optical Mouse                        | 998   | usbhid     | [6B908B35CC](<Notebook/Acer/Aspire/Aspire 5750G/7713EE2713FC/GARUDA-SOARING/6.1.26-1-LTS/X86_64/6B908B35CC>) |
| 046d:c08b | Logitech         | G502 SE HERO Gaming Mouse            | 889   | usbhid     | [77ECF9C05D](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/C1DFDE9A944B/ARCHLABSX-ROLLING/6.2.14-1-CLEAR/X86_64/77ECF9C05D>) |
| 3938:1031 | MOSART Semi.     | 2.4G Wireless Mouse                  | 850   | usbhid     | [758EB60FA3](<Desktop/Dell/OptiPlex/OptiPlex 9020/D2A83135503F/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/758EB60FA3>) |
| 062a:4102 | MosArt Semico... | Wireless Mouse                       | 833   | usbhid     | [D7EE12A01B](<Desktop/AZW/MINI/MINI S/53CF20A09429/ROCKY-9.1/5.14.0-70.26.1.EL9_0.X86_64/X86_64/D7EE12A01B>) |
| 18f8:0f99 | [Maxxter]        | Optical gaming mouse                 | 800   | usbhid     | [8BBE8F0A3F](<Notebook/Lenovo/IdeaPad/IdeaPad L340-15API 81LW/8AEA3C0AE9A3/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/8BBE8F0A3F>) |
| 046d:c016 | Logitech         | Optical Wheel Mouse                  | 768   | usbhid     | [80D7446F47](<Notebook/Acer/Swift/Swift SF515-51T/CF4F2C94E21A/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/80D7446F47>) |
| 046d:c542 | Logitech         | Wireless Receiver                    | 756   | usbhid     | [99EDE66D8D](<Notebook/ASUSTek Computer/K73/K73SJ/BA1DF2DADB62/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/99EDE66D8D>) |
| 046d:c53f | Logitech         | USB Receiver                         | 709   | usbhid     | [A4F5DCE6D6](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/26116FF2B2E2/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/A4F5DCE6D6>) |
| 045e:0040 | Microsoft        | Wheel Mouse Optical                  | 674   | usbhid     | [EBA2B6CE4E](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1/DEBIAN-12/6.1.0-7-AMD64/X86_64/EBA2B6CE4E>) |
| 0458:0186 | KYE Systems (... | Genius DX-120 Mouse                  | 636   | usbhid     | [A56CC8AB0E](<Desktop/Gigabyte Technology/GA-A55/GA-A55M-S2HP/77EBC1829450/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/A56CC8AB0E>) |
| 046d:c018 | Logitech         | Optical Wheel Mouse                  | 618   | usbhid     | [4CD6AB54BA](<Notebook/AZW/SEi/SEi/8583C4662416/LMDE-5/5.16.0-0.BPO.4-AMD64/X86_64/4CD6AB54BA>) |
| 046d:c069 | Logitech         | M-U0007 [Corded Mouse M500]          | 606   | usbhid     | [590E39BEF4](<Desktop/Medion/MS/MS-7797/75E51DCA8667/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/590E39BEF4>) |
| 046d:c050 | Logitech         | RX 250 Optical Mouse                 | 605   | usbhid     | [F41852FA6E](<Notebook/MSI/CR61/CR61 3M/F15A9F4E81F9/UBUNTU-18.04/4.15.0-209-GENERIC/X86_64/F41852FA6E>) |
| 10c4:8105 | Silicon Labs     | USB OPTICAL MOUSE                    | 604   | usbhid     | [38C78AD6B1](<Notebook/Sony/VPCZ23/VPCZ23Q9R/E81BF21D4D94/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/38C78AD6B1>) |
| 17ef:608d | Lenovo           | Optical Mouse                        | 600   | usbhid     | [4E80F798E2](<Desktop/Lenovo/ThinkStation/ThinkStation P330 30CY0075GE/AF0D6FF9A649/DEBIAN-11/5.10.0-22-AMD64/X86_64/4E80F798E2>) |
| 09da:c10a | A4Tech           | USB Mouse                            | 580   | usbhid     | [BB9C7992F8](<Notebook/eMachines/E/E725/EE81FA330179/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/BB9C7992F8>) |
| 046d:c084 | Logitech         | G203 Gaming Mouse                    | 577   | usbhid     | [2CBFF804D8](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 3/EEB9D6F73B6D/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/2CBFF804D8>) |
| 258a:1007 | SINOWEALTH       | Game Mouse                           | 568   | usbhid     | [D36CEC198B](<Desktop/ASRock/Z590/Z590 Steel Legend/A5E561069858/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D36CEC198B>) |
| 248a:8366 | Maxxter          | Wireless Optical Mouse ACT-MUSW-002  | 563   | usbhid     | [F63A54BF5F](<Notebook/Clevo/W240/W240EL-W250ELQ-W270ELQ/6451DAC2C40C/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/F63A54BF5F>) |
| 046d:c332 | Logitech         | G502 Proteus Spectrum Optical Mouse  | 561   | usbhid     | [4681975F9D](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/4681975F9D>) |
| 046d:c05b | Logitech         | M-U0004 810-001317 [B110 Optical ... | 537   | usbhid     | [2CBD56ABDC](<Notebook/Notebook/P750/P750ZM/51A3147C30B6/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/2CBD56ABDC>) |
| 0461:4d0f | Primax Electr... | HP Optical Mouse                     | 527   | usbhid     | [1945CCD76D](<Desktop/Dell/OptiPlex/OptiPlex 3060/0AA7CB57BEDA/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/1945CCD76D>) |
| 1bcf:08a0 | Sunplus Innov... | Gaming mouse [Philips SPK9304]       | 520   | usbhid     | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |
| 1bcf:0007 | Sunplus Innov... | Optical Mouse                        | 507   | usbhid     | [5E5011BDD3](<Desktop/ECS/LIVA/LIVA One H410/8A17C18B544A/UBUNTUSTUDIO-22.10/5.19.0-1023-LOWLATENCY/X86_64/5E5011BDD3>) |
| 1a2c:0042 | China Resourc... | Usb Mouse                            | 495   | usbhid     | [AA4606C36C](<Desktop/Intel/H/H61/6827F97BCD6A/ANTIX-22/5.10.142-ANTIX.2-AMD64-SMP/X86_64/AA4606C36C>) |
| 17ef:6019 | Lenovo           | M-U0025-O Mouse                      | 492   | usbhid     | [07E9099105](<Desktop/Lenovo/ThinkCentre/ThinkCentre M715q 10M2A00YLS/0B86B5EDCD5F/ZORIN-16/5.15.0-71-GENERIC/X86_64/07E9099105>) |
| 046d:c092 | Logitech         | G102/G203 LIGHTSYNC Gaming Mouse     | 424   | usbhid     | [0A66F5D4E4](<Notebook/Acer/Nitro/Nitro AN517-54/4E856D3C37AD/MANJARO/5.15.108-1-MANJARO/X86_64/0A66F5D4E4>) |
| 03f0:094a | Hewlett-Packard  | Optical Mouse [672662-001]           | 411   | usbhid     | [ED36A220C4](<Desktop/Dell/Precision/Precision T1500/3FA84DFAFD76/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/ED36A220C4>) |
| 046d:c03e | Logitech         | Premium Optical Wheel Mouse (M-BT58) | 411   | usbhid     | [0304FDDEC7](<Notebook/SKIKK/Niflheim/Niflheim 17 II/DF26B07687DB/ZORIN-16/5.15.0-71-GENERIC/X86_64/0304FDDEC7>) |
| 03f0:134a | Hewlett-Packard  | Optical Mouse                        | 400   | usbhid     | [101EC0A833](<Desktop/Gigabyte Technology/X470/X470 AORUS GAMING 5 WIFI/9C6521899F59/CHIMERAOS-42/6.1.26-1-LTS/X86_64/101EC0A833>) |
| 046d:c07e | Logitech         | G402 Gaming Mouse                    | 387   | usbhid     | [B6EC076CC6](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/0870723C67EE/UBUNTU-MATE-22.04/5.15.0-48-GENERIC/X86_64/B6EC076CC6>) |

### Isdn adapter (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| ffff:ffff | RAPOO            | AVM A1 PCMCIA                        | 13    | usbhid     | [D1F655B9B1](<Notebook/Notebook/PB50/PB50_70RF,RD,RC/F7638C8D681E/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/D1F655B9B1>) |
| 057c:1000 | AVM              | ISDN-Controller FRITZ!Card v2.0      | 1     |            | [BC685693A6](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK E8310/D00D4EC63607/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/BC685693A6>) |
| 0681:0002 | Siemens Infor... | Gigaset 3075 Passive ISDN            | 1     | bas_gig... | [B11EDA70A9](<Desktop/Gigabyte Technology/Z77/Z77X-UD5H/6AC23D98FB7B/LINUXMINT-20/5.4.0-58-GENERIC/X86_64/B11EDA70A9>) |

### Joystick (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:02ea | Microsoft        | Xbox One S Controller                | 197   | xpad       | [E7F4395ED8](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/1553ADD3C443/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/E7F4395ED8>) |
| 045e:02d1 | Microsoft        | Xbox One Controller                  | 51    | xpad       | [E0687D11BB](<Desktop/MSI/MS-7/MS-7D89/C91BC39F9ABA/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/E0687D11BB>) |
| 24c6:581a | ThrustMaster     | XB1 Classic Controller               | 38    | xpad       | [1DAD85CCF1](<Desktop/MSI/MS-7/MS-7C37/FFA188C93D94/MANJARO-22.1.0/6.1.22-1-MANJARO/X86_64/1DAD85CCF1>) |
| 044f:b687 | ThrustMaster     | TWCS Throttle                        | 27    | usbhid     | [424F0DCA9D](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/E2B929AE2E0E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/424F0DCA9D>) |
| 045e:02dd | Microsoft        | Xbox One Controller (Firmware 2015)  | 21    | xpad       | [4998BE684F](<Desktop/Gigabyte Technology/B650/B650 AORUS PRO AX/785C335D4DEC/GENTOO-2.9/6.1.10-GENTOO/X86_64/4998BE684F>) |
| 24c6:543a | ThrustMaster     | PowerA Wired Controller for Xbox One | 19    | xpad       | [8CB7A3612C](<Desktop/ASUSTek Computer/TUF/TUF Gaming B460M-PLUS/AD11F2772B7F/ARCO-ROLLING/6.2.13-ARCH1-1/X86_64/8CB7A3612C>) |
| 068e:00f2 | CH Products      | Flight Sim Pedals                    | 16    | usbhid     | [269E742EB7](<Desktop/Gigabyte Technology/B660/B660 DS3H DDR4/82FF40E03849/LINUXMINT-20.3/5.4.0-146-GENERIC/X86_64/269E742EB7>) |
| 146b:0603 | BigBen Intera... | PC Compact Controller                | 14    | xpad       | [A88277B7F9](<Desktop/Gigabyte Technology/TRX40/TRX40 AORUS XTREME/35C9721FE53B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A88277B7F9>) |
| 28de:1102 | Valve Software   | Wired Controller                     | 14    | usbhid     | [3924BB4EB5](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/65172E267C32/MANJARO-22.1.0/5.15.104-2-MANJARO/X86_64/3924BB4EB5>) |
| 0e6f:02b8 | Logic3           | Afterglow Wired Controller for Xb... | 12    | xpad       | [31557D5E8C](<Desktop/Biostar/A10/A10N-8800E/EBF954A69292/DEBIAN-12/6.1.0-7-AMD64/X86_64/31557D5E8C>) |
| 2341:8037 | Arduino SA       | Arduino Micro                        | 12    | cdc_acm    | [770C5EEE84](<Notebook/Lenovo/ThinkPad/ThinkPad P15v Gen 1 20TQCTO1WW/8A2043269878/FEDORA-37/6.0.15-300.FC37.X86_64/X86_64/770C5EEE84>) |
| 24c6:530a | ThrustMaster     | ProEX Controller for Xbox 360        | 12    | xpad       | [24D0D12ECA](<Notebook/Dell/System/System XPS L321X/CA12E6ED35E3/POP!_OS-22.04/6.1.11-76060111-GENERIC/X86_64/24D0D12ECA>) |
| 18d1:9400 | Google           | Stadia Controller rev. A             | 11    | usbhid     | [95F75E1344](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-G GAMING/B647CF3822F1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/95F75E1344>) |
| 046d:c262 | Logitech         | G920 Driving Force Racing Wheel      | 10    | usbhid     | [E4D56CA8C8](<Desktop/ASRock/X470/X470 Master SLI/718DBA7A68D6/NOBARA-37/6.2.6-201.FSYNC.FC37.X86_64/X86_64/E4D56CA8C8>) |
| 06a3:0c2d | Saitek           | Pro Flight Quadrant                  | 10    | usbhid     | [71D89005DD](<Desktop/Gigabyte Technology/AB350-Gaming/AB350-Gaming 3/EBAE0A8CED67/ARCH-ROLLING/6.2.10-ZEN1-1-ZEN/X86_64/71D89005DD>) |
| 0e6f:02da | Logic3           | Afterglow Wired Controller for Xb... | 10    | xpad       | [BC798D371A](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/D944EAF481AA/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/BC798D371A>) |
| 145f:01bb | Trust            | Gamepad                              | 9     | usbhid     | [1D1A225CDE](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-H GAMING/5CB7F4097008/POP!_OS-22.04/6.0.6-76060006-GENERIC/X86_64/1D1A225CDE>) |
| 20d6:4002 | PowerA           | XBX Spectra Enhanced Wired Contro... | 9     | xpad       | [A5565D9E6D](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92p 3227A2U/B4AA4776F724/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/A5565D9E6D>) |
| 07b5:0317 | Mega World In... | USB Game Controllers                 | 8     | usbhid     | [EF1594178C](<Desktop/Acer/Aspire/Aspire G7713/50BC3E207941/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/EF1594178C>) |
| 20d6:2005 | PowerA           | Xbox Series X Wired Controller OP... | 8     | xpad       | [1C8D776510](<Desktop/Dell/Inspiron/Inspiron 660/47C85722C89E/NOBARA-37/6.2.10-200.FSYNC.FC37.X86_64/X86_64/1C8D776510>) |
| 2f24:00b7 |                  | ESM GAME FOR WINDOWS 1.02            | 8     | xpad       | [44222BC590](<Desktop/Gigabyte Technology/B85/B85M-DS3H/875D49E38ACF/KDE-NEON-22.04/5.19.0-38-GENERIC/X86_64/44222BC590>) |
| 04d8:fd0a | Microchip Tec... | Lexip Gaming                         | 7     | usbhid     | [A25E0C9862](<Notebook/Dell/G3/G3 3500/C18C566E6430/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/A25E0C9862>) |
| 0e6f:02a4 | Logic3           | PDP Wired Controller for Xbox One... | 7     | xpad       | [BF8EA76F0A](<Desktop/MSI/MS-7/MS-7B79/3D0C74EF7BBB/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.17.4-1-DEFAULT/X86_64/BF8EA76F0A>) |
| 1532:0a14 | Razer USA        | Razer Wolverine Ultimate             | 7     | xpad       | [8302310EAF](<Desktop/ASRock/B650M/B650M PG Riptide WiFi/07AA6029A9F1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/8302310EAF>) |
| 046d:c213 | Logitech         | J-UH16 (Freedom 2.4 Cordless Joys... | 6     | usbhid     | [DF2F924A6E](<Desktop/MSI/MS-7/MS-7A34/093C5872F24E/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/DF2F924A6E>) |
| 0e6f:02a0 | Logic3           | PDP Wired Controller for Xbox One... | 6     | xpad       | [104FB04E91](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A II/0CC2D82F7C89/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/104FB04E91>) |
| 2f24:0091 |                  | GAME FOR WINDOWS 1.02                | 6     | xpad       | [E6A43DD88C](<Notebook/Valve/Jupiter/Jupiter/DCED018696D3/STEAMOS-3.4.4/5.13.0-VALVE36-1-NEPTUNE/X86_64/E6A43DD88C>) |
| 3285:0607 | Nacon            | GC100                                | 6     | xpad       | [A470DA90E8](<All In One/Acidanthera/iMacPro1/iMacPro1,1/4B34D7EAD43E/POP!_OS-22.04/5.19.0-76051900-GENERIC/X86_64/A470DA90E8>) |
| 044f:0407 | ThrustMaster     | TCA Q-Eng 1&2                        | 5     | usbhid     | [22BA7D722F](<Desktop/PC Specialist/Amd/Amd X399/11DB1B72F906/UBUNTU-22.04/5.17.0-1020-OEM/X86_64/22BA7D722F>) |
| 05ac:056b | Apple            | GameSir-T2a                          | 5     | apple_m... | [AC4FA9FD5F](<Desktop/ASUSTek Computer/PRIME/PRIME H270-PRO/461045BD9011/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/AC4FA9FD5F>) |
| 0738:1302 | Mad Catz         | F.L.Y.5 Stick                        | 5     | usbhid     | [93377FDD79](<Desktop/Gigabyte Technology/B450/B450 AORUS M/437BC66F1EF6/UBUNTU-22.04/5.15.0-57-GENERIC/X86_64/93377FDD79>) |
| 0e6f:02a2 | Logic3           | PDP Wired Controller for Xbox One... | 5     | xpad       | [892100E074](<Notebook/Dell/Latitude/Latitude 7390/85B10C95661C/NOBARA-37/6.1.14-201.FSYNC.FC37.X86_64/X86_64/892100E074>) |
| 12bd:a02f | GEMBIRD          | 5-Axis,12-Button with POV            | 5     | usbhid     | [D805E24841](<Desktop/Intel/H/H61/BFF38586427F/UBUNTU-22.04/5.15.0-47-GENERIC/X86_64/D805E24841>) |
| 20bc:5500 | ShenZhen Shan... | Frostbite controller                 | 5     | usbhid     | [49191A1C98](<Desktop/MSI/MS/MS-7817/497F6DF57158/MANJARO/5.15.41-1-MANJARO/X86_64/49191A1C98>) |
| 256f:c62e | 3Dconnexion      | SpaceMouse Wireless                  | 5     | usbhid     | [307E22B0D6](<Desktop/Gigabyte Technology/B550/B550 AORUS ELITE AX V2/3443FD568B42/ZORIN-16/5.13.0-48-GENERIC/X86_64/307E22B0D6>) |
| 2f24:0050 |                  | GAME FOR WINDOWS                     | 5     | xpad       | [7572089DC3](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/82283E2C0644/FEDORA-37/6.1.7-200.FC37.X86_64/X86_64/7572089DC3>) |
| 0428:4001 | Advanced Grav... | GamePad Pro                          | 4     | usbhid     | [B3559AEEC4](<All In One/Dell/Inspiron/Inspiron One 2305/939A63A720E7/MAKULU-2020/5.11.0-43-GENERIC/X86_64/B3559AEEC4>) |
| 0458:1004 | KYE Systems (... | Flight2000 F-23 Joystick             | 4     | usbhid     | [D3BE091EF5](<Desktop/ECS/P43/P43T-A2/553DB4F4DCC6/ASTRALINUXCE-2.12.44/5.10.0-1038.40-HARDENED/X86_64/D3BE091EF5>) |
| 068e:00f3 | CH Products      | Fighterstick                         | 4     | usbhid     | [6A5067B548](<Desktop/MSI/MS-7/MS-7C02/E454AD500B3F/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/6A5067B548>) |
| 06a3:0109 | Saitek           | P880 Pad                             | 4     | usbhid     | [40210AAF34](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AWS0DS0S/EBCD8B846A52/UBUNTU-20.10/5.8.0-44-GENERIC/X86_64/40210AAF34>) |
| 0b05:18e3 | ASUSTek Computer | ROG CHAKRAM                          | 4     | usbhid     | [923AA59AD5](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-P/A9BAF65DA9D9/FEDORA-37/6.1.18-200.FC37.X86_64/X86_64/923AA59AD5>) |
| 0e6f:02a6 | Logic3           | PDP Wired Controller for Xbox One... | 4     | xpad       | [F0C902CE04](<Desktop/MSI/MS/MS-7680/01B95D92089C/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/F0C902CE04>) |
| 11ff:001b | Lite Star Ele... | LS PC Controller                     | 4     | usbhid     | [1FFE9344FF](<Desktop/ASUSTek Computer/P8/P8H61-M/1C61F33C710E/DEBIAN-11/5.10.0-20-AMD64/X86_64/1FFE9344FF>) |
| 20d6:a713 | PowerA           | NSW wired controller                 | 4     | usbhid     | [2D46ECC50E](<Notebook/Alienware/14/14/2225AC6E9130/FEDORA-36/5.19.9-200.FC36.X86_64/X86_64/2D46ECC50E>) |
| 0079:1803 | DragonRise       | Mayflash Wiimote PC Adapter          | 3     | usbhid     | [C56CF68CEF](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/C20A58A68796/FEDORA-37/6.1.13-200.FC37.X86_64/X86_64/C56CF68CEF>) |
| 0079:189c | DragonRise       | Wired Wheel                          | 3     | xpad       | [C0F35FA0D2](<Notebook/Sony/VPCS13/VPCS13V9E/C44BE7DE159E/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/C0F35FA0D2>) |
| 044f:d007 | ThrustMaster     | T Mini Wireless                      | 3     | usbhid     | [F0303DC0A9](<Desktop/Gigabyte Technology/970/970A-DS3P/9C1276141C8A/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/F0303DC0A9>) |
| 044f:d00e | ThrustMaster     | eSwap PRO Controller                 | 3     | snd_usb... | [4A971615E8](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-A R2.0/59251CA279BE/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.1.8-1-DEFAULT/X86_64/4A971615E8>) |
| 045e:000e | Microsoft        | SideWinderГ‚ Freestyle Pro        | 3     | usbhid     | [29CD216C62](<Notebook/Toshiba/Satellite/Satellite C650/320D9F9D1BCC/ARCH/5.8.10-ARCH1-1/X86_64/29CD216C62>) |
| 046d:c211 | Logitech         | iTouch Cordless Receiver             | 3     | usbhid     | [451C626830](<Desktop/ASRock/Z97/Z97 Pro4/BAF192DD9D15/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/451C626830>) |

### Mfp (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 03f0:042a | Hewlett-Packard  | LaserJet M1132 MFP                   | 53    | usblp      | [84DBB8AE74](<Desktop/Gigabyte Technology/B85/B85M-D3V-A/12D3DD49427D/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/84DBB8AE74>) |
| 03f0:222a | Hewlett-Packard  | LaserJet Pro MFP M125nw              | 36    | usblp      | [D7157A7862](<Desktop/ASUSTek Computer/TUF/TUF B450M-PRO GAMING/64BD08958A9D/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/D7157A7862>) |
| 03f0:3b17 | Hewlett-Packard  | LaserJet M1005 MFP                   | 34    | usblp      | [270CD6ED83](<Notebook/Acer/Extensa/Extensa 5235/037DA8C7AA7B/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/270CD6ED83>) |
| 03f0:bf2a | Hewlett-Packard  | LaserJet MFP M28-M31                 | 34    | usbfs      | [1DECA47347](<Mini Pc/AZW/SER/SER/CDBA8041B3A5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/1DECA47347>) |
| 03f0:5617 | Hewlett-Packard  | LaserJet M1120 MFP                   | 28    | usblp      | [799A951714](<Notebook/MSI/Katana/Katana GF66 12UE/BB8D7E7CAD10/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/799A951714>) |
| 03f0:622a | Hewlett-Packard  | LaserJet MFP M129-M134               | 20    | usblp      | [E579AABFDB](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-P WIFI/D2F6FE6CC7A8/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E579AABFDB>) |
| 03f0:052a | Hewlett-Packard  | LaserJet M1212nf MFP                 | 16    | usblp      | [29DF87F87F](<Notebook/Clevo/NL41/NL41MU2/9029F6C5EF5E/MOS-10/5.10.168-STD-DEF-ALT1/X86_64/29DF87F87F>) |
| 03f0:ad2a | Hewlett-Packard  | ColorLaserJet MFP M278-M281          | 16    | usblp      | [D645276B0A](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P700/6FEAEF07D52A/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D645276B0A>) |
| 03f0:f22a | Hewlett-Packard  | Laser MFP 135w                       | 13    | usbfs      | [FA074ED7C9](<Mini Pc/Apple/Macmini7/Macmini7,1/9A4B9DC9209B/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/FA074ED7C9>) |
| 04b8:084d | Seiko Epson      | PX-402A [Stylus SX115/Stylus NX11... | 13    | usblp      | [C044FAAA05](<Notebook/Acer/Extensa/Extensa 2519/C8D4EE1F23DF/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C044FAAA05>) |
| 04b8:082f | Seiko Epson      | PX-A620 [Stylus CX3900/DX4000/DX4... | 12    | usblp      | [94B5586A2C](<Notebook/Dell/Precision/Precision 5510/6065C667D1D1/FEDORA-38/6.2.11-703.INTTF.FC38.X86_64/X86_64/94B5586A2C>) |
| 0924:3cef | Xerox            | Phaser 3100MFP                       | 12    | usblp      | [7AB9D987EB](<Desktop/ASUSTek Computer/M2N68-AM/M2N68-AM Plus/CCBD4EE6AAA6/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-X86_64/X86_64/7AB9D987EB>) |
| 03f0:3b2a | Hewlett-Packard  | Color LaserJet MFP M277dw            | 11    | usblp      | [D02D56F013](<Notebook/TUXEDO/Polaris/Polaris 15 AMD Gen1/CFDF63E6F8CB/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/D02D56F013>) |
| 03f0:322a | Hewlett-Packard  | LaserJet Pro MFP M127fn              | 10    | usblp      | [863B642A91](<Desktop/Gigabyte Technology/B450M/B450M DS3H/F2952F750961/LINUXMINT-21/5.15.0-58-GENERIC/X86_64/863B642A91>) |
| 04b8:083f | Seiko Epson      | Stylus CX4300/CX4400/CX5500/CX560... | 10    | usblp      | [9473725930](<Desktop/Gigabyte Technology/H81/H81M-DS2/59E02CFB88AB/UBUNTU-20.04/5.4.0-65-GENERIC/X86_64/9473725930>) |
| 0924:42af | Xerox            | WorkCentre 3045B                     | 10    | usblp      | [989A2EAABB](<Notebook/eMachines/eME/eME732/0C7DCAFE269A/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/989A2EAABB>) |
| 0924:42da | Xerox            | WorkCentre 3025                      | 10    | usblp      | [1127DFA79C](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/DB636D4B15B5/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/1127DFA79C>) |
| 0482:0495 | Kyocera          | FS-1020MFP                           | 8     | usblp      | [4F2FFB4273](<Notebook/Clevo/NL41/NL41MU2/D013E37077D5/MOS-10/5.10.177-STD-DEF-ALT1/X86_64/4F2FFB4273>) |
| 03f0:5717 | Hewlett-Packard  | LaserJet M1120n MFP                  | 7     | usblp      | [44103309B6](<Desktop/ASUSTek Computer/P7/P7H55/792D1CECDC45/LINUXMINT-20.2/5.4.0-80-GENERIC/X86_64/44103309B6>) |
| 03f0:932a | Hewlett-Packard  | LaserJet Pro MFP M26a                | 7     | usblp      | [FCD708ADC0](<Desktop/Medion/MS/MS-7800/EA1B9A6558CB/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/FCD708ADC0>) |
| 04b8:0841 | Seiko Epson      | PX-401A [ME 300/Stylus NX100]        | 7     | usblp      | [DCD96A2B45](<Desktop/ECS/H61/H61H2-M3/4ED3532E82A0/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/DCD96A2B45>) |
| 03f0:012a | Hewlett-Packard  | LaserJet M1536dnf MFP                | 6     | usblp      | [86C8FABB2D](<Mini Pc/System76/Meerkat/Meerkat/2111A21AC05F/POP!_OS-22.04/5.16.19-76051619-GENERIC/X86_64/86C8FABB2D>) |
| 03f0:5a2a | Hewlett-Packard  | LaserJet MFP M426fdn                 | 6     | usblp      | [86E493728F](<Notebook/Clevo/NL41/NL41MU2/FDFAF7B7120E/MOS-10/5.10.139-STD-DEF-ALT1/X86_64/86E493728F>) |
| 03f0:062a | Hewlett-Packard  | LaserJet 100 colorMFP M175a          | 5     | usblp      | [B03AAAB88C](<Desktop/Huanan/X99/X99-F8/AB9A5F53D1A0/POP!_OS-21.10/5.15.5-76051505-GENERIC/X86_64/B03AAAB88C>) |
| 03f0:142a | Hewlett-Packard  | LaserJet 400 MFP M425dn              | 5     | usblp      | [0900400806](<Desktop/Lenovo/ThinkCentre/ThinkCentre M73 10AXS0HN00/FB1FEEDD4865/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/0900400806>) |
| 03f0:2d2a | Hewlett-Packard  | LaserJet Pro MFP M226dw              | 5     | usblp      | [65210FEFA2](<Desktop/Acer/Veriton/Veriton M2640G/538862E11260/UBUNTU-20.04/5.4.0-144-GENERIC/X86_64/65210FEFA2>) |
| 03f0:0970 | Hewlett-Packard  | ColorLaserJet MFP M282-M285          | 4     | usblp      | [73BF30C596](<Desktop/MSI/MS-7/MS-7B51/C335948F26AA/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/73BF30C596>) |
| 03f0:242a | Hewlett-Packard  | Color LaserJet Pro MFP M176n         | 4     | usblp      | [B625ABC938](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-F GAMING/26198435912A/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/B625ABC938>) |
| 03f0:512a | Hewlett-Packard  | Color LaserJet MFP M477fdw           | 4     | usblp      | [210E6B1755](<Desktop/ASUSTek Computer/P9X79/P9X79 DELUXE/3E4055D71B4C/UBUNTU-22.10/5.19.0-23-GENERIC/X86_64/210E6B1755>) |
| 03f0:642a | Hewlett-Packard  | LaserJet MFP M227-M231               | 4     | usblp      | [480E352BF8](<Notebook/Hewlett-Packard/ProBook/ProBook 6570b/D0A579C1EB74/ZORIN-16/5.15.0-71-GENERIC/X86_64/480E352BF8>) |
| 0482:0497 | Kyocera          | FS-1025MFP                           | 4     | usblp      | [6C8DDCD99B](<Desktop/Intel/H/H55/B951CF589723/MANJARO-21.0.7/5.10.42-1-MANJARO/X86_64/6C8DDCD99B>) |
| 04b8:080e | Seiko Epson      | PX-A550 [CX-3500/3600/3650 MFP]      | 4     | usblp      | [D34B022996](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/6F4F5EDCBFEB/CENTOS-7/5.4.96-200.EL7.X86_64/X86_64/D34B022996>) |
| 0924:3d6f | Xerox            | WorkCentre 6605DN                    | 4     | usblp      | [0B05E41C64](<Desktop/MSI/MS-7/MS-7A64/405A568E5493/FEDORA-36/5.19.11-200.FC36.X86_64/X86_64/0B05E41C64>) |
| 03f0:0372 | Hewlett-Packard  | LaserJet MFP M139-M142               | 3     | usblp      | [C91FA425A5](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ABA7 82RN/3A81F7D5022D/UBUNTU-22.04/6.2.8-060208-GENERIC/X86_64/C91FA425A5>) |
| 03f0:0e2a | Hewlett-Packard  | Smart Install                        | 3     | uas, us... | [B027C83F03](<Desktop/MSI/MS-7/MS-7B22/4696DE406054/UBUNTU-20.04/5.8.0-41-GENERIC/X86_64/B027C83F03>) |
| 03f0:5817 | Hewlett-Packard  | LaserJet M1319f MFP                  | 3     | usblp      | [384B42F2E6](<Desktop/Biostar/H81/H81MHV3/B87328EA0DF0/ROSA-12.3/6.0.12.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/384B42F2E6>) |
| 03f0:eb2a | Hewlett-Packard  | Color Laser MFP 178nw                | 3     | usbfs      | [C48153FE6D](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 TWR/7D9169E0B2B4/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/C48153FE6D>) |
| 03f0:f42a | Hewlett-Packard  | Neverstop Laser MFP 120x             | 3     | usblp      | [4E8759FDA2](<Desktop/MSI/MS/MS-7982/1605B327E579/LINUXMINT-20.3/5.4.0-137-GENERIC/X86_64/4E8759FDA2>) |
| 0924:42db | Xerox            | WorkCentre 3215                      | 3     | usblp      | [0F22425E10](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/44EFF2E7D2F9/UBUNTU-18.04/4.15.0-118-GENERIC/X86_64/0F22425E10>) |
| 0924:42dc | Xerox            | WorkCentre 3225                      | 3     | usblp      | [585BFD5E2A](<Desktop/ASUSTek Computer/P5/P5K/CEA28403C3D8/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/585BFD5E2A>) |
| 03f0:332a | Hewlett-Packard  | Color LaserJet Pro MFP M177fw        | 2     | usblp      | [EBE7E665D6](<Desktop/Gigabyte Technology/B450M/B450M DS3H/6671F3D2D088/ROSA-12.3/6.0.7.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/EBE7E665D6>) |
| 03f0:342a | Hewlett-Packard  | Color LaserJet MFP M476dn            | 2     | usblp      | [BA153350D8](<Desktop/MSI/MS-7/MS-7B79/CD62FA4BE558/DEBIAN-11/6.0.0-0.DEB11.2-AMD64/X86_64/BA153350D8>) |
| 03f0:af2a | Hewlett-Packard  | ColorLaserJet MFP M178-M181          | 2     | usblp      | [7B9F86430D](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 2i 20WK00AJGE/F5EC0165A139/LINUXMINT-20.2/5.10.0-1051-OEM/X86_64/7B9F86430D>) |
| 03f0:d511 | Hewlett-Packard  | PageWide Pro 477dw MFP               | 2     | usbfs      | [4A8C2101E8](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339/DEBIAN-11/5.10.0-22-AMD64/X86_64/4A8C2101E8>) |
| 04b8:0818 | Seiko Epson      | Stylus CX3700/CX3800/DX3800          | 2     | usblp      | [D4567C6F8A](<Notebook/ASUSTek Computer/K55/K55VD/A104E9D59AE9/UBUNTU-20.10/5.8.0-29-GENERIC/X86_64/D4567C6F8A>) |
| 0924:42c4 | Xerox            | WorkCentre 3615                      | 2     | usblp      | [0BF7A6E91D](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8740w/C619FE23190E/ROSA-2014.1/4.0.4-NRJ-DESKTOP-1ROSA-X86_64/X86_64/0BF7A6E91D>) |
| 413c:523b | Dell             | B1265dfw Mono MFP                    | 2     | usblp      | [26B6148847](<Desktop/Medion/MS/MS-7707/B32C8E3A24E6/LINUXMINT-20.2/5.11.0-34-GENERIC/X86_64/26B6148847>) |
| 413c:590b | Dell             | MFP                                  | 2     | usblp      | [CFAE917826](<Desktop/Gigabyte Technology/B75/B75M-D3H/20CE70C40451/POP!_OS-21.04/5.15.11-76051511-GENERIC/X86_64/CFAE917826>) |
| 03f0:0870 | Hewlett-Packard  | ColorLaserJet MFP M182-M185          | 1     | usblp      | [68B84CC1EB](<Desktop/Gigabyte Technology/Z690/Z690 AERO D/5F4F2167F500/UBUNTU-22.10/5.19.0-31-GENERIC/X86_64/68B84CC1EB>) |
| 03f0:0972 | Hewlett-Packard  | LaserJet MFP M232-M237               | 1     | usbfs      | [9C780361AA](<Notebook/Lenovo/B570e/B570e HuronRiver Platform/A10D7185AD19/KDE-NEON-22.04/5.19.0-40-GENERIC/X86_64/9C780361AA>) |

### Miscellaneous (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 2d95:600a | vivo             | V2111                                | 24    | rndis_host | [E8F8F289AC](<Notebook/Hewlett-Packard/Presario/Presario CQ58/A6A3ADF2953B/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/E8F8F289AC>) |
| 2e04:c008 | HMD Global       | Tethering Network Interface          | 7     | rndis_host | [F6CAA753BA](<Notebook/Hewlett-Packard/Laptop/Laptop 14-cf3xxx/CD789610D053/LMDE-4/5.15.59-XANMOD1/X86_64/F6CAA753BA>) |
| 339b:108a | HONOR            | NTH-NX9                              | 5     | rndis_host | [6485870687](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/32ABEAE442FE/ARCH-ROLLING/6.2.2-ARCH1-1/X86_64/6485870687>) |
| 1390:5a01 | TOMTOM           | GO Professional 6250                 | 2     | rndis_host | [BE27200090](<Notebook/Lenovo/V145-15AST/V145-15AST 81MT/83C010F69464/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/BE27200090>) |
| 1ab2:0001 | Allied Vision    | Vision device                        | 2     |            | [85A3C0A47E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M900 10FD001LGE/C7018E549596/UBUNTU-18.04/5.4.0-104-GENERIC/X86_64/85A3C0A47E>) |
| 1e10:4000 | Point Grey Re... | U3V camera                           | 2     |            | [2BC5FA3C88](<Notebook/ASUSTek Computer/X555/X555LJ/19545E88E836/UBUNTU-20.04/5.4.0-29-GENERIC/X86_64/2BC5FA3C88>) |
| 2676:ba02 | Basler           | ace                                  | 2     |            | [A33C598546](<Desktop/CSL-Computer/X/X5939/5D6267012C67/LINUXMINT-20.3/5.4.0-105-GENERIC/X86_64/A33C598546>) |
| 0bb4:0b0c | HTC (High Tec... | Elf / Touch / P3450 / T-Mobile MD... | 1     | rndis_w... | [5E75A35A7D](<Notebook/Hewlett-Packard/Pavilion/Pavilion zx5000/5ED9898B7A22/LUBUNTU-18.04/4.15.0-20-GENERIC/I686/5E75A35A7D>) |
| 0fce:0a02 | Sony Ericsson... | Xperia 10 II - Dual SIM              | 1     | rndis_host | [4A436FB179](<Desktop/ASUSTek Computer/PRIME/PRIME B450-PLUS/6177CA6DD790/MANJARO-22.0.0/5.19.7-1-MANJARO/X86_64/4A436FB179>) |
| 1004:6343 | LG Electronics   | LM-V600                              | 1     | rndis_h... | [B5C18575BF](<Desktop/Gigabyte Technology/H61/H61M-S2-B3/9D85AF0476EC/UBUNTU-UNITY-20.04/5.4.0-42-GENERIC/X86_64/B5C18575BF>) |
| 1409:8000 | IDS Imaging D... | U3-307xCP-M                          | 1     |            | [B7917146D8](<Desktop/ASUSTek Computer/E3/E3 PRO GAMING V5/C263DF48F238/UBUNTU-20.04/5.15.0-58-GENERIC/X86_64/B7917146D8>) |
| 1410:b022 | Novatel Wireless | MiFi 7000                            | 1     | rndis_h... | [9F5C7C160A](<Notebook/Sony/VPCF136/VPCF136FM/C939FAAB434A/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.6.14-1-DEFAULT/X86_64/9F5C7C160A>) |
| 2676:ba05 | Basler           | a2A1920-160ucBAS                     | 1     |            | [273BC677CD](<System On Chip/Nvidia/Tegra/Tegra/C5692083B3F9/UBUNTU-18.04/4.9.140-TEGRA/AARCH64/273BC677CD>) |
| 2bdf:0001 | Hikrobot         | MV-CB013-20UC-C                      | 1     |            | [2690174808](<Desktop/ASUSTek Computer/PRIME/PRIME B460M-A/95F64D371370/LINUXMINT-20/5.4.0-26-GENERIC/X86_64/2690174808>) |
| 341e:1103 | Odm              | Modem_SN:5C3E04DB                    | 1     | rndis_host | [ECF8BE45DE](<Notebook/TUXEDO/Book/Book XUX7 Gen11/59022F6E973A/UBUNTU-BUDGIE-22.04/5.15.0-10041-TUXEDO/X86_64/ECF8BE45DE>) |

### Modem (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 27c6:5395 | Shenzhen Good... | Fingerprint Reader                   | 455   | cdc_acm    | [100534A570](<Notebook/Dell/XPS/XPS 15 9570/B723043741B6/UBUNTU-UNITY-22.04/5.15.0-57-GENERIC/X86_64/100534A570>) |
| 12d1:1506 | Huawei Techno... | Modem/Networkcard                    | 434   | uas, us... | [6DD3E18637](<Desktop/Gigabyte Technology/EX38/EX38-DS4/CF39FC1FF94A/DEBIAN-11/5.10.0-21-686-PAE/I686/6DD3E18637>) |
| 27c6:5301 | Shenzhen Good... | Fingerprint Reader                   | 320   | cdc_acm    | [F9D337A0A1](<Notebook/Dell/Inspiron/Inspiron 3793/3728B363B0FF/KUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/F9D337A0A1>) |
| 27c6:5385 | Shenzhen Good... | Fingerprint Reader                   | 247   | cdc_acm    | [B4E9BB9147](<Notebook/Dell/XPS/XPS 13 9380/1DCA34C82E46/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/B4E9BB9147>) |
| 0bdb:1911 | Ericsson Busi... | F5521gw                              | 173   | cdc_acm    | [082029ECF5](<Notebook/Lenovo/ThinkPad/ThinkPad T420s 4174W2X/8854B2161F24/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/082029ECF5>) |
| 0bdb:1926 | Ericsson Busi... | H5321 gw Mobile Broadband Module     | 169   | cdc_acm    | [00FF147A9A](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252CG/53AF29E0966C/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/00FF147A9A>) |
| 0bdb:193e | Ericsson Busi... | N5321 gw                             | 120   | cdc_acm    | [523DCE6A6D](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS46900/8D52057364EA/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/523DCE6A6D>) |
| 2341:0043 | Arduino SA       | Uno R3 (CDC ACM)                     | 91    | cdc_acm    | [46894747B1](<Desktop/MSI/MS-7/MS-7C37/9E9208EB0239/ZORIN-16/5.15.0-71-GENERIC/X86_64/46894747B1>) |
| 413c:818d | Dell             | DW5550                               | 89    | cdc_acm    | [E71BF9E7BB](<Notebook/Dell/Precision/Precision M6600/AE65C8D597DB/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/E71BF9E7BB>) |
| 0bdb:1900 | Ericsson Busi... | F3507g Mobile Broadband Module       | 76    | cdc_acm... | [F2BB35C6D3](<Notebook/Lenovo/ThinkPad/ThinkPad SL500 27464DG/061881953EF5/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/F2BB35C6D3>) |
| 03f0:3d1d | Hewlett-Packard  | hs2350 HSPA+ MobileBroadband         | 74    | cdc_acm    | [DD76E10243](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2570p/AEB2A16E5163/KUBUNTU-22.04/5.19.0-40-GENERIC/X86_64/DD76E10243>) |
| 413c:818e | Dell             | DW5560 miniPCIe HSPA+ Mobile Broa... | 70    | cdc_acm    | [B532A9756C](<Notebook/Dell/Latitude/Latitude E6330/70432BCBFC5B/DEBIAN-12/6.1.0-7-AMD64/X86_64/B532A9756C>) |
| 03f0:3a1d | Hewlett-Packard  | hs2340 HSPA+ mobile broadband        | 68    | cdc_acm    | [B99510884B](<Notebook/Hewlett-Packard/Others/Others/FD880940E655/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/B99510884B>) |
| 12d1:1436 | Huawei Techno... | Broadband stick                      | 59    | usb_sto... | [0496D0BBCF](<Desktop/Dell/OptiPlex/OptiPlex 7020/342C6699CADE/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/0496D0BBCF>) |
| 413c:8184 | Dell             | F3607gw v2 Mobile Broadband Module   | 55    | cdc_acm    | [58D4C40618](<Notebook/Dell/Latitude/Latitude E6410/3D11B5649907/OPENMANDRIVA-4.50/6.0.0-DESKTOP-1OMV4050/X86_64/58D4C40618>) |
| 413c:8147 | Dell             | F3507g Mobile Broadband Module       | 53    | cdc_ether  | [33B7764234](<Notebook/Dell/Latitude/Latitude E6400/444B406AEB69/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/33B7764234>) |
| 1209:1776 | InterBiometrics  | Io                                   | 49    | system7... | [D48EFC62C4](<Desktop/System76/Thelio/Thelio/638A9F7B01C2/UBUNTU-22.04/5.15.0-70-GENERIC/X86_64/D48EFC62C4>) |
| 12d1:1001 | Huawei Techno... | E161/E169/E620/E800 HSDPA Modem      | 48    | usb_sto... | [D00EBFBC62](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/8A70BC1B82BA/GENTOO-2.13/6.2.11-GENTOO-X86_64/X86_64/D00EBFBC62>) |
| 27c6:5381 | Shenzhen Good... | Fingerprint Reader                   | 44    | cdc_acm    | [4FF3C98FAF](<Notebook/Dell/G5/G5 5587/A59ECE640087/MANJARO-22.0.4/6.1.12-1-MANJARO/X86_64/4FF3C98FAF>) |
| 1546:01a7 | U-Blox           | [u-blox 7]                           | 42    | cdc_acm    | [5BC379EA65](<Desktop/Intel/D34010WYK/D34010WYK H14771-303/9263CE411C7B/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.1.12-1-DEFAULT/X86_64/5BC379EA65>) |
| 0658:0200 | Sigma Designs    | Aeotec Z-Stick Gen5 (ZW090) - UZB    | 37    | cdc_acm    | [051B7F4753](<Desktop/Shuttle/DS81/DS81D/08E1333EE59C/DEBIAN-11/5.15.102-1-PVE/X86_64/051B7F4753>) |
| 1546:01a8 | U-Blox           | [u-blox 8]                           | 37    | cdc_acm    | [6922F7DB46](<Notebook/Dell/Latitude/Latitude 5414/27A5D867E81E/DEBIAN-11/5.10.0-22-AMD64/X86_64/6922F7DB46>) |
| 1cf1:0030 | Dresden Elekt... | ZigBee gateway [ConBee II]           | 36    | cdc_acm    | [2FA64E56FF](<Desktop/Dell/OptiPlex/OptiPlex 3050/871B9902104E/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/2FA64E56FF>) |
| 12d1:1003 | Huawei Techno... | E220 HSDPA Modem / E230/E270/E870... | 32    | usb_sto... | [A61A9A88BC](<Notebook/Lenovo/IdeaPad/IdeaPad L340-15API 81LW/8FB571ED3AB1/RED-OS-7.3.2/6.1.20-2.EL7.3.X86_64/X86_64/A61A9A88BC>) |
| 0483:5740 | STMicroelectr... | Virtual COM Port                     | 31    | cdc_acm    | [68D85DD28F](<Desktop/ASRock/B550M/B550M Steel Legend/A96BC25C46D3/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/68D85DD28F>) |
| 12d1:140c | Huawei Techno... | E180v                                | 28    | usb_sto... | [C9D4C5EA2B](<Desktop/Positivo/P5/P5VD2-MX/3BDB3D92BC7A/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/C9D4C5EA2B>) |
| 12d1:1570 | Huawei Techno... | Mobile Broadband Module              | 26    | option     | [2574EF07FB](<Notebook/Sony/SVD1322/SVD1322X2EW/AF544E8FED5D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/2574EF07FB>) |
| 0424:274d | Microchip Tec... | HTC Hub Controller                   | 25    | cdc_acm    | [342C4594DE](<Desktop/Gigabyte Technology/X399/X399 DESIGNARE EX/6137A3F5E8D0/KDE-NEON-22.04/5.19.0-32-GENERIC/X86_64/342C4594DE>) |
| 0451:16a8 | Texas Instrum... | CC2531 ZigBee                        | 21    | cdc_acm    | [F019265109](<Desktop/ASRock/B650M/B650M PG Riptide/D49A7138A3AE/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/F019265109>) |
| 04d8:00df | Microchip Tec... | MCP2200 USB Serial Port Emulator     | 21    | cdc_acm    | [66A494B2EC](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/F662C2CC6CE3/MANJARO-22.0.2/6.0.19-3-MANJARO/X86_64/66A494B2EC>) |
| 2341:0042 | Arduino SA       | Mega 2560 R3 (CDC ACM)               | 20    | cdc_acm    | [3AC194E77A](<Desktop/Lenovo/IdeaCentre/IdeaCentre 310S-08ASR 90G90059MW/22FBEB97AB40/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/3AC194E77A>) |
| 2833:0051 | Oculus VR        | Rift S                               | 20    | usbhid     | [46894747B1](<Desktop/MSI/MS-7/MS-7C37/9E9208EB0239/ZORIN-16/5.15.0-71-GENERIC/X86_64/46894747B1>) |
| 04e8:6872 | Samsung Elect... | Kiera                                | 16    | cdc_ether  | [D3CF4446D5](<Notebook/Samsung Electronics/600B4/600B4B-600B5B/7DD9205D40D2/DEBIAN-11/5.10.0-21-AMD64/X86_64/D3CF4446D5>) |
| 04e2:1410 | Exar             | XR21V1410 USB-UART IC                | 15    | cdc_acm... | [18BFA2BDD6](<Mini Pc/Intel/NUC7i5BNB/NUC7i5BNB J31144-303/4A24C2865D31/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/18BFA2BDD6>) |
| 12d1:1404 | Huawei Techno... | EM770W miniPCI WCDMA Modem           | 15    | usb_sto... | [AF4E100C16](<Notebook/Acer/AO/AO722/CD4B6FE88F10/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/AF4E100C16>) |
| 1209:2201 | InterBiometrics  | Dygma Shortcut Keyboard              | 14    | usbhid     | [1A7E610C32](<Notebook/Dell/XPS/XPS 15 9520/57E42991B84A/DEBIAN-TESTING/5.19.0-1-AMD64/X86_64/1A7E610C32>) |
| 0e8d:0003 | MediaTek         | MT6227 phone                         | 13    | cdc_acm    | [BE69723341](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 DM/5EC898A09D7B/MANJARO/6.2.8-1-MANJARO/X86_64/BE69723341>) |
| 1366:0105 | SEGGER           | J-Link                               | 13    | cdc_acm    | [B3C97EB801](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 2a 21A00075GE/3E771C1CF612/LINUXMINT-21/5.15.0-46-GENERIC/X86_64/B3C97EB801>) |
| 2341:0001 | Arduino SA       | Uno (CDC ACM)                        | 11    | cdc_acm    | [FC5894DCB4](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-E/83FEEE5F4B66/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/FC5894DCB4>) |
| 2548:1002 | Pulse-Eight      | CEC Adapter                          | 11    | cdc_acm    | [44A3785F1F](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi7/6917428F4B9A/NIXOS-22.11/6.0.6/X86_64/44A3785F1F>) |
| 1a86:55d4 | QinHeng Elect... | USB Single Serial                    | 10    | cdc_acm    | [094563419E](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 400 Rev 1.0/52BB409DF306/DEBIAN-11/5.15.84-V8+/AARCH64/094563419E>) |
| 1c11:b04d | Input Club       | ErgoDox Infinity                     | 10    | usbhid     | [5E5011BDD3](<Desktop/ECS/LIVA/LIVA One H410/8A17C18B544A/UBUNTUSTUDIO-22.10/5.19.0-1023-LOWLATENCY/X86_64/5E5011BDD3>) |
| 2886:8027 | Seeed Technology | Seeeduino_Cortex_M0+                 | 10    | cdc_acm    | [1EE7228BDE](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 SD-BS-CJ41G-300-101-H 07-21-2021 18:16:20/DCE53E7F5D09/UBUNTU-20.04/5.13.0-1017-INTEL/X86_64/1EE7228BDE>) |
| 0930:1319 | Toshiba          | H5321 gw                             | 9     | cdc_acm    | [F87CD6E36C](<Notebook/Toshiba/PORTEGE/PORTEGE Z930/B46CC99FA484/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/F87CD6E36C>) |
| 12d1:14ac | Huawei Techno... | E815                                 | 9     | option     | [984691A38D](<Notebook/Lenovo/G/G480/75A1B5661EBB/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/984691A38D>) |
| 2e8a:0005 | MicroPython      | Board in FS mode                     | 9     | cdc_acm    | [180B0242E8](<Desktop/Medion/MS/MS-7797/8F1D43A83A23/LINUXMINT-21/5.15.0-67-GENERIC/X86_64/180B0242E8>) |
| 067b:2323 | Prolific Tech... | USB-Serial Controller                | 8     | cdc_acm    | [BB51E864A7](<Mini Pc/Intel Client Systems/NUC12/NUC12DCMi7/9DF75800A431/UBUNTU-MATE-22.04/5.15.0-60-GENERIC/X86_64/BB51E864A7>) |
| 0930:1314 | Toshiba          | F5521gw                              | 8     | cdc_acm    | [082F5559C7](<Notebook/Toshiba/TECRA/TECRA R850/A4842B92F0F4/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/082F5559C7>) |
| 0bdb:190d | Ericsson Busi... | F5521gw                              | 8     | cdc_acm    | [B2BC70473D](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4291AY8/72B9FE9CE2DB/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/B2BC70473D>) |
| 19d2:1515 | ZTE WCDMA Tec... | MF195                                | 8     | cdc_acm    | [3954E61E9A](<Notebook/Lenovo/G505s/G505s 20255/D4F5F16D51F5/UBUNTU-20.04/5.8.0-48-GENERIC/X86_64/3954E61E9A>) |

### Monitor (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 17e9:4107 | DisplayLink      | e1649Fwu                             | 3     | usbhid     | [17EEA2B641](<Notebook/Valve/Jupiter/Jupiter/28F9BE6613AF/STEAMOS-3.3.1/5.13.0-VALVE21.1-1-NEPTUNE-02211-GC54CDA5A36F3/X86_64/17EEA2B641>) |

### Net/ethernet (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:8156 | Realtek Semic... | USB 10/100/1G/2.5G LAN               | 59    | cdc_ncm... | [7730EB04FA](<Desktop/Lenovo/ThinkStation/ThinkStation D30 42234T7/7EB1100D92AD/DEBIAN-11/5.15.104-1-PVE/X86_64/7730EB04FA>) |
| 0fe6:9900 | ICS Advent       | 10/100M LAN                          | 47    | cdc_ether  | [E2B1578D42](<Notebook/Apple/MacBookPro14/MacBookPro14,1/CDEE3742EC0B/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/E2B1578D42>) |
| 17e9:430a | DisplayLink      | HP Port Replicator (Composite Dev... | 12    | cdc_ncm... | [8A6C736217](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Extreme Gen 3 20TKCTO1WW/4E873BD9B59A/POP!_OS-22.04/6.1.11-76060111-GENERIC/X86_64/8A6C736217>) |
| 03f0:911d | Hewlett-Packard  | lt4211 Gobi 4G Module                | 11    | cdc_ether  | [28C9B60939](<Notebook/Hewlett-Packard/Elite/Elite x2 1011 G1 Tablet/45582826F18C/DEBIAN/6.0.0-6-AMD64/X86_64/28C9B60939>) |
| 17ef:721e | Lenovo           | Powered Hub                          | 11    | r8152      | [906D900083](<Notebook/Dell/XPS/XPS 13 7390/E5F80BAB444B/MANJARO/6.2.8-1-MANJARO/X86_64/906D900083>) |
| 18d1:4eec | Google           | Pixel 7                              | 11    | cdc_ncm    | [3B852BAD57](<Notebook/MSI/GP65/GP65 Leopard 10SEK/5250262F0789/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/3B852BAD57>) |
| 17e9:430f | DisplayLink      | Kensington Dock (Composite Device)   | 10    | cdc_ncm    | [2E5B18F7C5](<Convertible/ASUSTek Computer/ROG/ROG Flow X13 GV301RC_GV301RC/BF1EDC1D1CAD/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/2E5B18F7C5>) |
| 17e9:4340 | DisplayLink      | ThinkPad USB 3.0 Ultra Dock          | 10    | cdc_ncm    | [E49682836A](<Tablet/Microsoft/Surface/Surface Laptop Go/1E7E9BBF3B2A/ENDEAVOUROS-ROLLING/6.2.13-ARCH1-2-SURFACE/X86_64/E49682836A>) |
| 0b05:1976 | ASUSTek Computer | USB 10/100/1G/2.5G LAN               | 8     | cdc_ncm    | [9E6E8C3986](<Desktop/MicroElectronics/G/G513/CDDCC25C4AB7/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/9E6E8C3986>) |
| 2eca:c101 | Aquantia         | 5G USB Ethernet Adapter              | 7     | aqc111     | [C35B1DB9A1](<Mini Pc/Hewlett-Packard/Z2/Z2 Mini G3 Workstation/C879EA567BC9/UBUNTU-22.04/5.18.12-051812-GENERIC/X86_64/C35B1DB9A1>) |
| 17e9:6004 | DisplayLink      | Targus USB3 DV4K DOCK w PD60W        | 6     | cdc_ncm    | [3F515702D2](<Desktop/MSI/MS/MS-7977/4023F73158C0/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/3F515702D2>) |
| 17ef:3098 | Lenovo           | Mini Dock                            | 6     | cdc_ether  | [DF9EF8C115](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 2i 20W0CTO1WW/E6DBBAE47796/POP!_OS-22.04/6.0.2-76060002-GENERIC/X86_64/DF9EF8C115>) |
| 0424:9500 | Microchip Tec... | LAN9500/LAN9500i                     | 5     | smsc95xx   | [40782BA0A7](<Notebook/Panasonic/CF-31/CF-31WEUEEBE/B0E16EA3A89C/DEBIAN-11/5.10.0-21-AMD64/X86_64/40782BA0A7>) |
| 045e:09a0 | Microsoft        | RTL8153B GigE [Surface Ethernet A... | 5     | cdc_ether  | [A721B1B9D6](<Tablet/Microsoft/Surface/Surface Laptop 4/6FFF009110F6/ARCH-ROLLING/6.2.6-ARCH1-1/X86_64/A721B1B9D6>) |
| 17e9:4357 | DisplayLink      | Kensington SD3600 Dual Video Dock    | 5     | cdc_ncm    | [4638729E72](<Notebook/SLIMBOOK/TITAN/TITAN/934E05EB73BF/UBUNTU-MATE-22.04/5.19.0-32-GENERIC/X86_64/4638729E72>) |
| 17e9:436c | DisplayLink      | Dell D1000 USB3.0 Dock               | 5     | cdc_ncm    | [13C53062B6](<Notebook/Dell/Latitude/Latitude 5320/2BFC68DC749F/UBUNTU-21.10/5.13.0-28-GENERIC/X86_64/13C53062B6>) |
| 2001:b301 | D-Link           | DUBE250 2.5GbE Adapter               | 5     | cdc_ncm... | [F1DB72CDDB](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/F1DB72CDDB>) |
| 17e9:6011 | DisplayLink      | Plugable UD_6950H                    | 4     | cdc_ncm    | [C2227E5F29](<Notebook/Lenovo/ThinkPad/ThinkPad P52 20MAS11D00/B339EBE9393B/FEDORA-37/6.2.10-200.FC37.X86_64/X86_64/C2227E5F29>) |
| 03f0:0857 | Hewlett-Packard  | Snapdragon X12 LTE-A                 | 3     | cdc_ether  | [E8D1866113](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/AC04F34CD8CA/DEBIAN/6.0.0-5-AMD64/X86_64/E8D1866113>) |
| 050d:0128 | Belkin Compon... | Belkin USB 3.0 Hub                   | 3     | ax88179... | [C46B9195F3](<Notebook/Others/Others/Others/458B3CC78C3B/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/C46B9195F3>) |
| 17e9:431f | DisplayLink      | ThinkPad Basic USB 3.0 Dock          | 3     | snd_usb... | [18AC5EDE65](<Tablet/Lenovo/ThinkPad/ThinkPad Helix 2nd 20CHS23W00/01AA1C622890/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/18AC5EDE65>) |
| 17e9:6008 | DisplayLink      | Targus USB3 DV4K DOCK w PD100W       | 3     | cdc_ncm... | [CA85C59FAD](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 2a 20XH005BUS/2F564415C7FF/MANJARO/5.15.76-1-MANJARO/X86_64/CA85C59FAD>) |
| 1c04:0015 | QNAP System      | Pacific                              | 3     | aqc111     | [70105D0F43](<Desktop/ZOTAC/Others/Others/82354A628D90/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/70105D0F43>) |
| 0424:9e00 | Microchip Tec... | LAN9500A/LAN9500Ai                   | 2     | smsc95xx   | [9F69E439BC](<Desktop/ASUSTek Computer/PRIME/PRIME H310T R2.0/62C346E7C248/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/9F69E439BC>) |
| 0df6:0072 | Sitecom Europe   | AX88179 Gigabit Ethernet [Sitecom]   | 2     | ax88179... | [2002EAA403](<Mini Pc/Intel Client Systems/NUC12/NUC12WSHi5/CFC696B02745/OPENSUSE-LEAP-15.4/5.14.21-150400.24.46-DEFAULT/X86_64/2002EAA403>) |
| 17e9:4321 | DisplayLink      | USB3.0 UHD Dual Video Dock           | 2     | cdc_ncm    | [87219BA8E3](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Dash F15 FX516PR_FX516PR/AFDDE613FF5C/ARCH-ROLLING/6.0.9-ARCH1-1/X86_64/87219BA8E3>) |
| 17e9:434d | DisplayLink      | Targus USB3.0 DV-2K Dock w Power     | 2     | cdc_ncm    | [E43DB9718F](<Notebook/Lenovo/IdeaPad/IdeaPad Slim 7 15IIL05 82AD/555C1F8D1675/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/E43DB9718F>) |
| 17e9:4351 | DisplayLink      | HP USB Dock                          | 2     | cdc_ncm    | [DA8FEC7AC4](<Notebook/Lenovo/IdeaPad/IdeaPad 330S-14IKB 81JM/43E0AB99DD44/POP!_OS-22.04/5.19.0-76051900-GENERIC/X86_64/DA8FEC7AC4>) |
| 03f0:0547 | Hewlett-Packard  | L2311c LAN7500 Ethernet              | 1     |            | [EBB304F58E](<Notebook/Dell/Precision/Precision 5520/CC4D70FDB6F0/UBUNTU-19.04/5.0.0-27-GENERIC/X86_64/EBB304F58E>) |
| 056e:4007 | Elecom           | WDC-433DU2HBK                        | 1     | rtl8812au  | [4F8794ED64](<Desktop/ASRock/A300/A300M-STX/FD07F40ED5D5/KUBUNTU-20.04/5.4.0-64-GENERIC/X86_64/4F8794ED64>) |
| 17e9:433e | DisplayLink      | dynadock 4K                          | 1     | cdc_ncm    | [FDC926F819](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2G303/5386512A6B05/LINUXMINT-20.1/5.8.0-48-GENERIC/X86_64/FDC926F819>) |
| 17e9:4355 | DisplayLink      | Kensington SD3650 Dual Video Dock    | 1     | cdc_ncm... | [550D6E5438](<Notebook/ASUSTek Computer/G501/G501VW/987AFF782366/DEBIAN-11/5.10.0-18-AMD64/X86_64/550D6E5438>) |
| 17e9:6019 | DisplayLink      | Targus USB-C Quad 4K Dock with PD... | 1     | cdc_ncm    | [ED3F7B7F50](<Notebook/Hewlett-Packard/ZBook/ZBook Firefly 14 G7 Mobile Workstation/8458C929BAD3/POP!_OS-22.04/5.18.10-76051810-GENERIC/X86_64/ED3F7B7F50>) |
| 17e9:6024 | DisplayLink      | Targus USB-C DV4K Docking Station... | 1     | cdc_ncm... | [523DCE6A6D](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS46900/8D52057364EA/FEDORA-35/5.14.10-300.FC35.X86_64/X86_64/523DCE6A6D>) |
| 17ef:3052 | Lenovo           | ThinkPad TabletDock                  | 1     | cdc_ether  | [1D6F4C02A1](<Tablet/Lenovo/ThinkPad/ThinkPad 10 20C10024GE/CE86374CD564/XUBUNTU-20.04/5.4.0-42-GENERIC/X86_64/1D6F4C02A1>) |
| 2b73:0007 | Pioneer DJ       | USB 10/100 LAN                       | 1     | cdc_ether  | [09D7C3567E](<Desktop/Gigabyte Technology/990/990FXA-UD3/E739A1F28B0B/UBUNTU-20.04/5.11.0-42-GENERIC/X86_64/09D7C3567E>) |
| 9710:7832 | MosChip Semic... | MCS7832 10/100 Mbps Ethernet adapter | 1     | mcs7830    | [B470FF0F63](<Desktop/MSI/MS-7/MS-7B28/6ED9DACEC792/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/B470FF0F63>) |

### Net/wimax (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0186 | Intel            | WiMAX Connection 2400m               | 83    | i2400m_usb | [0485192408](<Notebook/ASUSTek Computer/G73/G73Jh/A21208B759F2/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/0485192408>) |
| 8086:0180 | Intel            | WiMAX Connection 2400m               | 62    | i2400m_usb | [96A0EFC869](<Notebook/Samsung Electronics/NC/NC10/FBC266AD6C77/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-I586/I686/96A0EFC869>) |
| 8087:07d6 | Intel            | Centrino Wireless-N + WiMAX 6150     | 59    | i2400m_usb | [A21BE2B066](<Notebook/Sony/VPCEH14/VPCEH14FM/E075348F80ED/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/A21BE2B066>) |
| 8086:1406 | Intel            | WiMAX Connection 2400m               | 48    | i2400m_usb | [80BE7E8E25](<Notebook/Lenovo/G550/G550 20023/0B45C3140BDF/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/80BE7E8E25>) |
| 8086:0188 | Intel            | WiMAX Connection 2400m               | 34    | i2400m_usb | [C52176294B](<Notebook/Dell/Inspiron/Inspiron N4010/4D8593C9D9B5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C52176294B>) |
| 8086:0187 | Intel            | Centrino Advanced-N + WiMAX 6250     | 22    | i2400m_usb | [18071ACD7E](<Notebook/Lenovo/IdeaPad/IdeaPad Y560/F20A29A7F8DC/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/18071ACD7E>) |
| 8086:0182 | Intel            | WiMAX Connection 2400m               | 2     | i2400m_usb | [01517BE2D7](<Notebook/Dell/Inspiron/Inspiron 1110/AAEB47BE7B9E/ZORIN-15/5.4.0-47-GENERIC/X86_64/01517BE2D7>) |
| 198f:0210 | Beceem Commun... | BCS200 WiMAX Adapter                 | 1     |            | [F1707AB670](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dq0xxx/421CC2D59818/UBUNTU-20.04/5.13.0-44-GENERIC/X86_64/F1707AB670>) |
| 8086:1405 | Intel            | WiMAX Connection 2400m               | 1     | i2400m_usb | [DB9160E089](<Notebook/Lenovo/ThinkPad/ThinkPad W500 4061W8H/D76E4D6B19A7/DEBIAN-11/5.10.0-13-AMD64/X86_64/DB9160E089>) |

### Net/wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 148f:7601 | Ralink Techno... | MT7601U Wireless Adapter             | 1635  | mt7601u    | [BB7835495E](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/BB7835495E>) |
| 0bda:8179 | Realtek Semic... | RTL8188EUS 802.11n Wireless Netwo... | 1530  | r8188eu    | [CF7CF903C0](<Desktop/ASRock/B760/B760 Pro RS-D4/22BCEB943676/DEBIAN-12/6.1.0-8-AMD64/X86_64/CF7CF903C0>) |
| 0bda:b812 | Realtek Semic... | RTL88x2bu [AC1200 Techkey]           | 1009  | 88x2bu     | [100534A570](<Notebook/Dell/XPS/XPS 15 9570/B723043741B6/UBUNTU-UNITY-22.04/5.15.0-57-GENERIC/X86_64/100534A570>) |
| 0cf3:9271 | Qualcomm Athe... | AR9271 802.11n                       | 979   | ath9k_htc  | [812AE9A763](<Desktop/Positivo/POS-EIQ87/POS-EIQ87CY/996C8731CEDA/MANJARO/5.15.108-1-MANJARO/X86_64/812AE9A763>) |
| 148f:5370 | Ralink Techno... | RT5370 Wireless Adapter              | 746   | rt2800usb  | [C359F42A22](<Desktop/Intel/H/H61/3D6C0125E768/MANJARO/6.1.25-1-MANJARO/X86_64/C359F42A22>) |
| 0bda:c811 | Realtek Semic... | 802.11ac NIC                         | 730   | 8821cu     | [AED14C1E20](<Desktop/Acer/Aspire/Aspire M3920/25FDE4FC074D/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/AED14C1E20>) |
| 148f:3070 | Ralink Techno... | RT2870/RT3070 Wireless Adapter       | 663   | rt2800usb  | [9369ACB33C](<Desktop/Acer/Aspire/Aspire XC-330/880DD70E3811/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/9369ACB33C>) |
| 0bda:8178 | Realtek Semic... | RTL8192CU 802.11n WLAN Adapter       | 548   | rtl8192... | [D15B9FB438](<Desktop/ASUSTek Computer/P5/P5K/0772711AD395/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/D15B9FB438>) |
| 2357:0109 | TP-Link          | TL-WN823N v2/v3 [Realtek RTL8192EU]  | 500   | rtl8xxxu   | [DE65A79BF1](<Desktop/ASUSTek Computer/TUF/TUF Gaming B560M-PLUS/929B4939E2C7/NOBARA-37/6.2.12-200.FSYNC.FC37.X86_64/X86_64/DE65A79BF1>) |
| 0bda:8176 | Realtek Semic... | RTL8188CUS 802.11n WLAN Adapter      | 450   | rtl8192... | [590E39BEF4](<Desktop/Medion/MS/MS-7797/75E51DCA8667/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/590E39BEF4>) |
| 2357:010c | TP-Link          | TL-WN722N v2/v3 [Realtek RTL8188EUS] | 427   | r8188eu    | [FE207B0DF1](<Desktop/Gigabyte Technology/H61/H61M-S2PH/7932DFB49C79/ROSA-12.4/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/FE207B0DF1>) |
| 0bda:f179 | Realtek Semic... | RTL8188FTV 802.11b/g/n 1T1R 2.4G ... | 394   | rtl8188fu  | [940D88BFCE](<Desktop/ASRock/945/945GCM-S/9995C9213664/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/940D88BFCE>) |
| 0bda:818b | Realtek Semic... | RTL8192EU 802.11b/g/n WLAN Adapter   | 334   | rtl8xxxu   | [F1DEC1F586](<Desktop/Gigabyte Technology/GA-970/GA-970A-UD3/9A8304B2EB9E/ROSA-2016.1/4.15.0-DESKTOP-122.124.1ROSA-X86_64/X86_64/F1DEC1F586>) |
| 2357:011e | TP-Link          | AC600 wireless Realtek RTL8811AU ... | 319   | 88XXau     | [867E98F955](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/07075421405D/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/867E98F955>) |
| 0bda:8812 | Realtek Semic... | RTL8812AU 802.11a/b/g/n/ac 2T2R D... | 286   | 8812au     | [2A09FB1D81](<Desktop/Gigabyte Technology/B450M/B450M DS3H/93E61F10B914/LINUXMINT-20.3/5.4.0-148-GENERIC/X86_64/2A09FB1D81>) |
| 045e:0719 | Microsoft        | Xbox 360 Wireless Adapter            | 273   | xpad       | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 0bda:8189 | Realtek Semic... | RTL8187B Wireless 802.11g 54Mbps ... | 261   | rtl8187    | [5D5367DC0E](<Notebook/Sony/SVF1521/SVF15212CXW/21DF07AF3421/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/5D5367DC0E>) |
| 0bda:8187 | Realtek Semic... | RTL8187 Wireless Adapter             | 216   | rtl8187    | [89CCDD7262](<Desktop/ASRock/775/775Dual-VSTA/C993403882F6/LMDE-5/5.10.0-22-AMD64/X86_64/89CCDD7262>) |
| 148f:5572 | Ralink Techno... | RT5572 Wireless Adapter              | 198   | rt2800usb  | [ABC091F5C0](<Desktop/Dell/OptiPlex/OptiPlex 7010/96981485B9C1/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/ABC091F5C0>) |
| 0bda:a811 | Realtek Semic... | RTL8811AU 802.11a/b/g/n/ac WLAN A... | 196   | 88XXau     | [C625F3747A](<Desktop/Intel/DB65AL/DB65AL AAG12530-310/F6C8FFD81969/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/C625F3747A>) |
| 1199:9079 | Sierra Wireless  | EM7455                               | 195   | qcseria... | [305CC49AC0](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 460 20ELS0FJ01/060101A7B46D/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/305CC49AC0>) |
| 148f:761a | Ralink Techno... | MT7610U ("Archer T2U" 2.4G+5G WLA... | 192   | mt76x0u    | [D076BCD8A5](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/132B1CAE5360/KALI-2023.1/5.15.44-RE4SON-V7L+/ARMV7L/D076BCD8A5>) |
| 0bda:8172 | Realtek Semic... | RTL8191SU 802.11n WLAN Adapter       | 190   | r8712u     | [C174FCC2D8](<Desktop/ASUSTek Computer/M5A88-V/M5A88-V EVO/8D4188F1156E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/C174FCC2D8>) |
| 7392:7811 | Edimax Techno... | EW-7811Un 802.11n Wireless Adapte... | 190   | rtl8192... | [77150D1166](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P557/9D728F491894/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/77150D1166>) |
| 2357:012d | TP-Link          | Archer T3U [Realtek RTL8812BU]       | 187   | 88x2bu     | [A62E386EAE](<Desktop/Gigabyte Technology/Z97/Z97-D3H/B918E5FAC02C/MAGEIA-8/5.15.106-DESKTOP-2.MGA8/X86_64/A62E386EAE>) |
| 413c:81b6 | Dell             | DW5811e Snapdragonâ¢ X7 LTE      | 187   | qcseria... | [255DA608B8](<Notebook/Dell/Latitude/Latitude 5290/FC89A5E51EAE/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/255DA608B8>) |
| 2357:0107 | TP-Link          | TL-WN821N v5/v6 [RTL8192EU]          | 183   | rtl8xxxu   | [E6EAD6E953](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/9C8C09595939/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E6EAD6E953>) |
| 148f:5372 | Ralink Techno... | RT5372 Wireless Adapter              | 181   | rt2800usb  | [19D78D1685](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/19D78D1685>) |
| 2357:0120 | TP-Link          | Archer T2U PLUS [RTL8821AU]          | 178   | 88XXau     | [F045323C99](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 4 Model B Rev 1.4/DFF914D5971F/RASPBIAN-11/6.1.25-V8+/AARCH64/F045323C99>) |
| 045e:02fe | Microsoft        | Xbox Wireless Adapter for Windows    | 176   | mt76x2u    | [E6EAD6E953](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/9C8C09595939/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E6EAD6E953>) |
| 0846:9053 | NetGear          | A6210                                | 165   | mt76x2u    | [86A89A1986](<Desktop/Medion/MD3410/MD34100-2543/CE18A432A8EF/KALI-2023.1/6.1.0-KALI5-AMD64/X86_64/86A89A1986>) |
| 2357:011f | TP-Link          | 802.11ac WLAN Adapter                | 158   | 88XXau     | [20D6860E43](<Notebook/Hewlett-Packard/630/630/66FE7E8D7F44/FEDORA-38/6.3.1-350.VANILLA.FC38.X86_64/X86_64/20D6860E43>) |
| 0bda:0811 | Realtek Semic... | Realtek 8812AU/8821AU 802.11ac WL... | 149   | 88XXau     | [7DABC9FC5C](<Desktop/ASUSTek Computer/ROG/ROG STRIX B365-G GAMING/AE05EEB1873D/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/7DABC9FC5C>) |
| 2357:0115 | TP-Link          | Archer T4U ver.3                     | 144   | 88x2bu     | [4EA44288B5](<Notebook/Dell/Latitude/Latitude 7370/7819A10CD1AF/PARROT-5.3/6.1.0-1PARROT1-AMD64/X86_64/4EA44288B5>) |
| 0846:9052 | NetGear          | A6100 AC600 DB Wireless Adapter [... | 135   | 8812au     | [01311E320C](<Desktop/Gigabyte Technology/AB350-Gaming/AB350-Gaming 3/DC460EF2714F/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/01311E320C>) |
| 148f:2573 | Ralink Techno... | RT2501/RT2573 Wireless Adapter       | 134   | rt73usb    | [FCCFCD375F](<Notebook/Dell/Inspiron/Inspiron 15-3567/25FC6D98EAE0/XUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/FCCFCD375F>) |
| 0bda:8813 | Realtek Semic... | RTL8814AU 802.11a/b/g/n/ac Wirele... | 122   | 8814au     | [D9A3AFA732](<Desktop/ASUSTek Computer/ROG/ROG STRIX X470-I GAMING/133421F6DBD4/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/D9A3AFA732>) |
| 2357:0138 | TP-Link          | 802.11ac NIC                         | 121   | 88x2bu     | [AC8AD5D3D5](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 705 G4 DM 35W/7A68E0F037A1/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/AC8AD5D3D5>) |
| 2001:3319 | D-Link           | DWA-131 Wireless N Nano Adapter (... | 118   | rtl8xxxu   | [ADA8FF75DD](<Desktop/Gigabyte Technology/Z370M/Z370M D3H/C61BD6ADE0A3/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/ADA8FF75DD>) |
| 045e:02e6 | Microsoft        | Wireless XBox Controller Dongle      | 112   | mt76x2u    | [61873CDE49](<Desktop/Lenovo/IdeaCentre/IdeaCentre Gaming5 14IOB6 90RE004VGE/59E160FDB54F/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/61873CDE49>) |
| 045e:0b12 | Microsoft        | Xbox Wireless Controller (model 1... | 107   | xpad       | [0A66F5D4E4](<Notebook/Acer/Nitro/Nitro AN517-54/4E856D3C37AD/MANJARO/5.15.108-1-MANJARO/X86_64/0A66F5D4E4>) |
| 07d1:3c0a | D-Link System    | DWA-140 RangeBooster N Adapter(re... | 105   | rt2800usb  | [02C2BFEE54](<Desktop/MSI/MS/MS-7758/99B96FCEBE65/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/02C2BFEE54>) |
| 0b05:184c | ASUSTek Computer | 802.11ac NIC                         | 102   | 88x2bu     | [E35B234E43](<Desktop/Lenovo/ThinkCentre/ThinkCentre M83 10AHS0CK14/29258FB520FE/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/E35B234E43>) |
| 2357:0108 | TP-Link          | TL-WN822N Version 4 RTL8192EU        | 100   | rtl8xxxu   | [B8281F77A3](<Desktop/Dell/OptiPlex/OptiPlex 7010/F3C38BD709A2/BLENDOS/6.3.1-ARCH1-1/X86_64/B8281F77A3>) |
| 03f0:9d1d | Hewlett-Packard  | lt4120 Snapdragon X5 LTE             | 98    | cdc_ether  | [9A068C66D5](<Notebook/Hewlett-Packard/EliteBook/EliteBook 850 G3/17912160BE36/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/9A068C66D5>) |
| 0bda:8171 | Realtek Semic... | RTL8188SU 802.11n WLAN Adapter       | 98    | r8712u     | [623FF14300](<Desktop/ASUSTek Computer/P8H77-V/P8H77-V LE/EA0A5CA24B56/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/623FF14300>) |
| 13d3:3306 | IMC Networks     | Mediao 802.11n WLAN [Realtek RTL8... | 96    | r8712u     | [83F7F01BDE](<Desktop/Medion/MS/MS-7728/A9DD034BF656/FEDORA-37/6.2.8-200.FC37.X86_64/X86_64/83F7F01BDE>) |
| 0b05:17ba | ASUSTek Computer | N10 Nano 802.11n Network Adapter ... | 95    | rtl8192... | [6CFF2537AE](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/F529A45B0255/ROSA-12.4/5.10.155-GENERIC-1ROSA2021.1-X86_64/X86_64/6CFF2537AE>) |
| 1199:9041 | Sierra Wireless  | EM7305 Modem                         | 95    | qcseria... | [C964CE47C2](<Notebook/Panasonic/CF-54/CF-54-1/C215D8839BA5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C964CE47C2>) |
| 0cf3:7015 | Qualcomm Athe... | TP-Link TL-WN821N v3 / TL-WN822N ... | 94    | ath9k_htc  | [56DB3A6B44](<Desktop/ASUSTek Computer/PRIME/PRIME B450-PLUS/F6EDBD79FE44/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/56DB3A6B44>) |

### Network (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0bda:8153 | Realtek Semic... | RTL8153 Gigabit Ethernet Adapter     | 4018  | r8152      | [D3DE6B6B31](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ee1xxx/EEC49B509995/ARCO-ROLLING/6.2.13-ARCH1-1/X86_64/D3DE6B6B31>) |
| 04e8:6863 | Samsung Elect... | Galaxy series, misc. (tethering m... | 967   | rndis_host | [82AFA36341](<Convertible/Hewlett-Packard/ENVY/ENVY x360 2-in-1 Laptop 15-ew0xxx/1E71ACC074D2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/82AFA36341>) |
| 0b95:1790 | ASIX Electronics | AX88179 Gigabit Ethernet             | 959   | ax88179... | [0D2AC684C8](<Notebook/Lenovo/IdeaPad/IdeaPad 530S-14ARR 81H1/40E4E0D39D59/DEVUAN-4/6.1.25/X86_64/0D2AC684C8>) |
| 2717:ff80 | Xiaomi           | Mi/Redmi series (RNDIS)              | 616   | rndis_host | [D7B87B2B8C](<All In One/Apple/iMac9/iMac9,1/FCE400D396E6/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/D7B87B2B8C>) |
| 0bda:8152 | Realtek Semic... | RTL8152 Fast Ethernet Adapter        | 565   | r8152      | [A7FFBB2FE3](<Notebook/HT/C20/C20C/5BB5F8A81892/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/A7FFBB2FE3>) |
| 0bda:b720 | Realtek Semic... | RTL8723BU 802.11b/g/n WLAN Adapter   | 395   | rtl8xxxu   | [8AE75BC5A0](<Notebook/Adreamer/PN1308/PN1308P/1123F3517B39/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/8AE75BC5A0>) |
| 04e8:6864 | Samsung Elect... | GT-I9070 (network tethering, USB ... | 384   | rndis_host | [D0233BC511](<Notebook/Fujitsu/T/T900/255277C340F9/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/D0233BC511>) |
| 12d1:108a | Huawei Techno... | STK-LX3                              | 357   | rndis_host | [D5433B46BD](<Desktop/Acer/Aspire/Aspire SA80-AP S280/8CF4F487FD21/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/D5433B46BD>) |
| 12d1:14db | Huawei Techno... | E353/E3131                           | 256   | cdc_ether  | [B68D1B92DE](<Desktop/Apple/MacPro5/MacPro5,1/E3007916032F/BLENDOS/6.2.13-ARCH1-1/X86_64/B68D1B92DE>) |
| 2357:0601 | TP-Link          | UE300 10/100/1000 LAN (ethernet m... | 238   | r8152      | [696525CF17](<Notebook/Lenovo/IdeaPad/IdeaPad S145-15IIL 82DJ/0C9E326A541D/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/696525CF17>) |
| 0e8d:2004 | MediaTek         | ASUS_X008D                           | 221   | rndis_host | [224DC7209E](<Notebook/eMachines/eMG/eMG620/82074F847535/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/224DC7209E>) |
| 0bda:d723 | Realtek Semic... | 802.11n WLAN Adapter                 | 214   | btusb      | [A915E84A9A](<Notebook/GPU Company/GWTC116/GWTC116-2/F85ED92E93ED/XUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/A915E84A9A>) |
| 0bda:c820 | Realtek Semic... | 802.11ac NIC                         | 207   | btusb      | [D27392828F](<Desktop/ASRock/A320M-HDV/A320M-HDV R4.0/DDF6FDC2A438/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/D27392828F>) |
| 22b8:2e24 | Motorola PCS     | moto g71 5G                          | 187   | rndis_host | [E1313AF3E6](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da1xxx/6AF4025C842E/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/E1313AF3E6>) |
| 22d9:276a | OPPO Electronics | Find X3 Neo 5G                       | 169   | rndis_host | [9EF46F7F3E](<Desktop/Acer/Predator/Predator PO3-620/877F4FBC5AE0/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/9EF46F7F3E>) |
| 19d2:1405 | ZTE WCDMA Tec... | DEMO Mobile Boardband                | 160   | cdc_ether  | [88E7444FA5](<Desktop/ASRock/H110M-DGS/H110M-DGS R3.0/E723C61B678A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/88E7444FA5>) |
| 0424:ec00 | Standard Micr... | SMSC9512/9514 Fast Ethernet Adapter  | 145   | smsc95xx   | [50A67AB03C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 2 Model B Rev 1.1/3A28E3EB24BC/RASPBIAN-10/5.10.103-V7+/ARMV7L/50A67AB03C>) |
| 1199:a001 | Sierra Wireless  | EM7345 4G LTE                        | 139   | cdc_mbim   | [E771177CCA](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUA05900/17C990AB3673/DEBIAN-11/5.15.0-0.BPO.3-AMD64/X86_64/E771177CCA>) |
| 05c6:f00e | Qualcomm         | Nokia XR20                           | 138   | rndis_host | [290A99FEE9](<Notebook/Dell/XPS/XPS 13 9380/F5F41F15142A/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/290A99FEE9>) |
| 17e9:6006 | DisplayLink      | Dell Universal Dock D6000            | 129   | cdc_ncm    | [535CC48341](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/535CC48341>) |
| 17ef:3082 | Lenovo           | ThinkPad TBT 3 Dock                  | 127   | r8152      | [7BBDC5E568](<Notebook/Dell/XPS/XPS 13 9300/4E6F55491119/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/7BBDC5E568>) |
| 17ef:a387 | Lenovo           | USB-C Dock Ethernet                  | 127   | r8152      | [1F2D88BFAE](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 4 21ECS00000/642B185E080D/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/1F2D88BFAE>) |
| 0b95:772b | ASIX Electronics | AX88772B                             | 126   | asix       | [C5ADFBD376](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S0FEUK/4C15DC18CCC6/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C5ADFBD376>) |
| 2cb7:0210 | Fibocom          | L830-EB-00 LTE WWAN Modem            | 119   | cdc_acm    | [1259BB0006](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L50003GE/F2AB22C90A04/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/1259BB0006>) |
| 18d1:4ee3 | Google           | Nexus/Pixel Device (tether)          | 113   | rndis_host | [641374C815](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Dash F15 FX516PE_FX516PE/F3EBC4985F5E/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/641374C815>) |
| 17e9:4307 | DisplayLink      | USB 3.0 Dual Video Dock              | 112   | cdc_ncm    | [F23FB5CCA0](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DT_FX505DT/69E8EF1A2769/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/F23FB5CCA0>) |
| 0fe6:9700 | ICS Advent       | DM9601 Fast Ethernet Adapter         | 99    | dm9601,... | [BD05976130](<Desktop/ASRock/X370/X370 Gaming X/10096C4E8D4F/GENTOO-2.13/6.1.19-GENTOO/X86_64/BD05976130>) |
| 2a70:f00e | OnePlus Techn... | OnePlus                              | 92    | rndis_host | [8E09A153F5](<Notebook/Lenovo/ThinkPad/ThinkPad E14 20RAS1DB00/07E3C6AEDFF6/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/8E09A153F5>) |
| 17ef:a359 | Lenovo           | ThinkPad Lan                         | 81    | cdc_ether  | [8A80FD7103](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 3 21AHCTO1WW/3D5B408DCD5C/UBUNTU-BUDGIE-22.04/5.19.0-40-GENERIC/X86_64/8A80FD7103>) |
| 0b95:7720 | ASIX Electronics | AX88772                              | 78    | asix       | [FBCF679BAE](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p0xx/3E2B162A4669/KUBUNTU-22.04/5.15.0-70-GENERIC/X86_64/FBCF679BAE>) |
| 04b3:4010 | IBM              | XClarity Controller                  | 70    | cdc_ether  | [A2FD0BC88C](<Server/Lenovo/ThinkSystem/ThinkSystem SR250 -[7Y51CTO1WW]-/56D35BA12534/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/A2FD0BC88C>) |
| 17e9:6000 | DisplayLink      | USB-C Hybrid UHD Video Dock          | 67    | cdc_ncm    | [3CC902FF5C](<Notebook/Acer/ConceptD/ConceptD CN315-71P/3324548C752E/UBUNTU-23.04/5.19.0-42-GENERIC/X86_64/3CC902FF5C>) |
| 0bda:b82c | Realtek Semic... | 802.11ac NIC                         | 66    | btusb      | [81A4D2AC8B](<Notebook/Semp Toshiba/IS/IS 1413G/EC50067C2C26/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/81A4D2AC8B>) |
| 0e8d:2005 | MediaTek         | BL8800Pro                            | 63    | rndis_host | [2E2B57B3AE](<Desktop/Positivo/POS-EIQ87/POS-EIQ87CY/996C8731CEDA/MANJARO/5.15.108-1-MANJARO/X86_64/2E2B57B3AE>) |
| 17e9:436e | DisplayLink      | Dell D3100 Docking Station           | 60    | cdc_ncm    | [8D0C93E1A8](<Notebook/Dell/XPS/XPS 15 9570/72B52E778037/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/8D0C93E1A8>) |
| 05ac:12ab | Apple            | iPad 4/Mini1                         | 59    | ipheth     | [3C4E911C6D](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X712FA_X712FA/07972FCD7595/KUBUNTU-22.10/5.19.0-35-GENERIC/X86_64/3C4E911C6D>) |
| 2e04:c022 | HMD Global       | Nokia7.2                             | 58    | rndis_host | [8CC87C48D1](<Desktop/Acer/Aspire/Aspire M3910/28CA2ABB5049/FEDORA-38/6.2.8-300.FC38.X86_64/X86_64/8CC87C48D1>) |
| 046b:ffb0 | American Mega... | Virtual Ethernet                     | 56    | cdc_ether  | [19C318242F](<Desktop/Others/Others/Others/C3C1AB1B873D/UBUNTU-20.04/5.15.0-1023-NVIDIA/X86_64/19C318242F>) |
| 05ac:8233 | Apple            | iBridge                              | 56    | apple_m... | [A0073C6FF3](<Notebook/Apple/MacBookAir9/MacBookAir9,1/1060561AE5DA/OPENMANDRIVA-4.3/5.16.13-DESKTOP-1OMV4003/X86_64/A0073C6FF3>) |
| 05c6:9024 | Qualcomm         | SM7250-PICASSO _SN:6897A937          | 56    | rndis_host | [C5824F9CAE](<Desktop/Others/Others/Others/AF08E90FA052/TRISQUEL-11.0/5.10.177-GNU1/ARMV7L/C5824F9CAE>) |
| 045e:07c6 | Microsoft        | RTL8153 GigE [Surface Ethernet Ad... | 54    | r8152      | [67DC214198](<Tablet/Microsoft/Surface/Surface Pro 3/CD0693C63FAF/DEBIAN-12/6.1.0-7-AMD64/X86_64/67DC214198>) |
| 03f0:371d | Hewlett-Packard  | un2430 Mobile Broadband Module       | 53    | qcserial   | [DD23AB1A2E](<Notebook/Hewlett-Packard/ProBook/ProBook 6470b/355576A0B5F6/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/DD23AB1A2E>) |
| 0424:7800 | Standard Micr... | Ethernet controller                  | 46    | lan78xx    | [407CA5845D](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi 3 Model B Plus Rev 1.3/99AA913EF833/RASPBIAN-11/6.1.21-V7+/ARMV7L/407CA5845D>) |
| 0b95:772a | ASIX Electronics | AX88772A Fast Ethernet               | 45    | asix       | [1B44C95410](<Desktop/ASUSTek Computer/All/All Series/167FFE862668/GENTOO-2.13/6.1.19-GENTOO-X86_64/X86_64/1B44C95410>) |
| 17ef:3069 | Lenovo           | ThinkPad TBT3 LAN                    | 45    | r8152      | [2DEFEFF264](<Notebook/Dell/XPS/XPS 15 9550/BB7C0CCD078B/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/2DEFEFF264>) |
| 1004:6344 | LG Electronics   | LM-X420xxx/G2 Android Phone (USB ... | 44    | rndis_h... | [3516608F3C](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi Model B Rev 2/E17DCD62E2FD/RASPBIAN-11/5.4.150+/ARMV6L/3516608F3C>) |
| 0bb4:0003 | HTC (High Tec... | L-EMENT 350                          | 43    | rndis_host | [110D9CB0F9](<Desktop/Gigabyte Technology/M61/M61PME-S2/BAFD0675E869/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/110D9CB0F9>) |
| 18d1:4eeb | Google           | Pixel 6a                             | 42    | cdc_ncm    | [7C56FAE21C](<Notebook/Lenovo/ThinkPad/ThinkPad T530 24297ZG/8A310BA3F997/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/7C56FAE21C>) |
| 19d2:1365 | ZTE WCDMA Tec... | ZTE BLADE A530                       | 42    | rndis_host | [0F9ABE9400](<Desktop/ASUSTek Computer/M3N78/M3N78 PRO/8974B2AB17B3/NOBARA-37/6.2.6-201.FSYNC.FC37.X86_64/X86_64/0F9ABE9400>) |
| 1bbb:0174 | T & A Mobile ... | 5049Z                                | 41    | rndis_host | [FE799BC532](<Notebook/System76/Oryx/Oryx Pro/2E17FD71D927/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/FE799BC532>) |

### Phone (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 18d1:4ee1 | Google           | Nexus/Pixel Device (MTP)             | 153   | usbfs      | [10DE9F17E1](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537CC5/4CD8E7447BCF/DEBIAN-11/5.10.0-20-AMD64/X86_64/10DE9F17E1>) |
| 0e8d:2008 | MediaTek         | Cyrus Technology CS 24               | 152   | usbfs      | [6026E88AD4](<Notebook/System76/Oryx/Oryx Pro/2E17FD71D927/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/6026E88AD4>) |
| 2717:ff48 | Xiaomi           | Mi/Redmi series (MTP + ADB)          | 67    | usbfs      | [4D0DC62D87](<Notebook/Hewlett-Packard/Others/Others/18328F956F7B/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/4D0DC62D87>) |
| 1004:631c | LG Electronics   | LM-X420xxx/G2/Optimus Android Pho... | 54    | usbfs      | [0BEB710E7C](<Notebook/Acer/Aspire/Aspire M5-583P/EBD19CDDB07D/LINUXMINT-20.3/5.15.0-60-GENERIC/X86_64/0BEB710E7C>) |
| 0e8d:201d | MediaTek         | WTCELERO5G                           | 40    | usbfs      | [A684AD4938](<Desktop/Dell/OptiPlex/OptiPlex 7010/7141C8184225/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/A684AD4938>) |
| 04e8:685d | Samsung Elect... | GT-I9100 Phone [Galaxy S II] (Dow... | 28    | cdc_acm    | [E42327B375](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-E GAMING WIFI/402936B429DF/ARCH-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/E42327B375>) |
| 1bbb:0168 | T & A Mobile ... | Alcatel A5                           | 27    | usbfs      | [5BE962CFEA](<Notebook/Lenovo/B570e/B570e HuronRiver Platform/B706EF292161/ROSA-12.1/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/5BE962CFEA>) |
| 1004:6300 | LG Electronics   | G2/Optimus Android Phone [Charge ... | 18    | usbhid     | [D517F63625](<Notebook/Acer/Aspire/Aspire 8942G/475AD9F6AF51/LINUXMINT-19.1/4.15.0-204-GENERIC/X86_64/D517F63625>) |
| 18d1:4ee8 | Google           | Nexus/Pixel Device (MIDI)            | 18    | snd_usb... | [BFE26862F0](<Desktop/ASRock/A320M/A320M Pro4/5855A38B603C/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/BFE26862F0>) |
| 05c6:f003 | Qualcomm         | Nokia 8110 4G                        | 15    | usbfs      | [23B5B8565E](<Notebook/Avell High Performance/B.ON/B.ON/E42D0C46990C/ELEMENTARY-6.1/5.15.0-57-GENERIC/X86_64/23B5B8565E>) |
| 1782:4001 | Spreadtrum Co... | Spreadtrum Phone                     | 14    | usbfs      | [7B3D591E47](<Desktop/Biostar/H61/H61MHV/F2674DACF56D/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/7B3D591E47>) |
| 19d2:0307 | ZTE WCDMA Tec... | Unisoc Phone                         | 12    | usbfs      | [814B71A20C](<Desktop/ASUSTek Computer/P5KPL-AM/P5KPL-AM EPU/17F12F817AB4/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-I686/I686/814B71A20C>) |
| 0bb4:0c02 | HTC (High Tec... | Dream / ADP1 / G1 / Magic / Tatto... | 11    | usbfs      | [F48E29FEF2](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509DJ_D509DJ/3425534963FE/LINUXMINT-21/5.15.0-53-GENERIC/X86_64/F48E29FEF2>) |
| 19d2:0306 | ZTE WCDMA Tec... | KONA-MTP _SN:9BDB1445                | 11    | usbfs      | [E94FD64204](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G5/82EBB9B920D4/DEBIAN/6.0.0-4-AMD64/X86_64/E94FD64204>) |
| 1bbb:0167 | T & A Mobile ... | A509DL                               | 10    | usbfs      | [4333734C92](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DT_FX505DT/C37FC2FE3CE4/UBUNTU-MATE-22.04/5.15.0-58-GENERIC/X86_64/4333734C92>) |
| 0b05:7770 | ASUSTek Computer | ROG Phone 5s Pro                     | 9     | usbfs      | [F149AFB5D1](<Notebook/Dell/XPS/XPS 15 9500/723F073EA41F/DEBIAN-11/5.10.0-19-AMD64/X86_64/F149AFB5D1>) |
| 2a45:2008 | Meizu            | MX Phone (MTP)                       | 9     | usbfs      | [03B27C8CA4](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK AH544/016D5650067E/UBUNTU-21.10/5.13.0-35-GENERIC/X86_64/03B27C8CA4>) |
| 0bb4:2008 | HTC (High Tec... | Android Phone via MTP [Wiko Cink ... | 6     |            | [52ECA6CE50](<Notebook/Lenovo/G570/G570 20079/FA239870D40A/ROSA-2016.1/4.15.0-DESKTOP-68.5ROSA-X86_64/X86_64/52ECA6CE50>) |
| 1004:633a | LG Electronics   | Ultimate 2 Android Phone L41C        | 6     | cdc_acm    | [1F8D567742](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/2144DC3E4E47/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1F8D567742>) |
| 05c6:9092 | Qualcomm         | Wileyfox Swift                       | 5     |            | [050AEE0A5F](<Desktop/ASRock/Z77/Z77 Pro3/1BAEFA5D278F/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/050AEE0A5F>) |
| 0bb4:0c01 | HTC (High Tec... | Dream / ADP1 / G1 / Magic / Tatto... | 5     |            | [AED9AD9E40](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X512DA_F512DA/CFF9B1263FB5/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/AED9AD9E40>) |
| 045e:04ec | Microsoft        | Windows Phone (Zune)                 | 4     | usbfs      | [8DCA736A46](<Desktop/ASUSTek Computer/PRIME/PRIME Z370-A/A5BBFEFF78D7/POP!_OS-22.04/5.17.5-76051705-GENERIC/X86_64/8DCA736A46>) |
| 04e8:685c | Samsung Elect... | GT-I9250 Phone [Galaxy Nexus] (Ma... | 4     | usbfs      | [D9976E30E3](<Notebook/ASUSTek Computer/K75/K75VM/E4A852A4AEF1/KDE-NEON-20.04/5.11.0-37-GENERIC/X86_64/D9976E30E3>) |
| 0bb4:0f0b | HTC (High Tec... | U12+                                 | 4     | usbhid     | [7CBE8BB003](<Desktop/MSI/MS-7/MS-7A35/8EF0854E581C/MANJARO-21.1.2/5.14.0-0-MANJARO/X86_64/7CBE8BB003>) |
| 0bb4:0f87 | HTC (High Tec... | m8                                   | 4     | usbfs      | [6F9489B2E6](<Desktop/EVGA/X299/X299 FTW K/E0352CDBA41D/NIXOS-21.11/5.10.102/X86_64/6F9489B2E6>) |
| 0fce:01c4 | Sony Ericsson... | Android                              | 4     | usbfs      | [6C0BF83741](<Desktop/ASUSTek Computer/M5A78L/M5A78L LE/DE5965167BBF/MANJARO/4.19.91-1-MANJARO/X86_64/6C0BF83741>) |
| 1782:4012 | Spreadtrum Co... | Spreadtrum Phone                     | 4     |            | [3F78A19968](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G6/D1E5323F0B63/UBUNTU-20.04/5.13.0-41-GENERIC/X86_64/3F78A19968>) |
| 17ef:7497 | Lenovo           | A789 (MTP mode)                      | 4     |            | [B60CD6FFC3](<Notebook/Acer/Aspire/Aspire E1-571G/4D6A7182CE38/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/B60CD6FFC3>) |
| 0bb4:f006 | HTC (High Tec... | Android Phone                        | 3     | usbhid     | [5902EF81CA](<Desktop/Dell/OptiPlex/OptiPlex 7010/81048E1FE46E/MANJARO-20.2/5.9.8-2-MANJARO/X86_64/5902EF81CA>) |
| 1004:61fe | LG Electronics   | Optimus Android Phone [USB tether... | 3     | cdc_ether  | [7CE0658B0F](<Desktop/Dell/OptiPlex/OptiPlex 5040/DA886BEEF2C1/SIDUCTION-12/6.2.10-1-SIDUCTION-AMD64/X86_64/7CE0658B0F>) |
| 1782:000c | Spreadtrum Co... | Unisoc Phone                         | 3     | rndis_host | [DA341E3BE8](<Notebook/Toshiba/Satellite/Satellite C55-B/A75A3AA9B306/FEDORA-37/6.2.8-200.FC37.X86_64/X86_64/DA341E3BE8>) |
| 1782:4002 | Spreadtrum Co... | Spreadtrum Phone                     | 3     | usbfs      | [9A1E994BCB](<Notebook/ASUSTek Computer/F3/F3JR/C43F4A89AD21/ROSA-2016.1/5.4.83-GENERIC-2ROSA-I586/I686/9A1E994BCB>) |
| 1782:4003 | Spreadtrum Co... | Unisoc Phone                         | 3     | usbfs      | [CED8851DC3](<Desktop/ASRock/Z370/Z370 Pro4/10DCD13DFB84/FEDORA-36/6.0.8-201.FSYNC.FC36.X86_64/X86_64/CED8851DC3>) |
| 1782:5d31 | Spreadtrum Co... | Unisoc Phone                         | 3     | rndis_host | [503C99202E](<Notebook/Lenovo/ThinkPad/ThinkPad Yoga 11e 3rd Gen 20G8S00W00/40638FC7D2BF/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/503C99202E>) |
| 2717:1240 | Xiaomi           | HM1 Android Phone                    | 3     |            | [01AA74496F](<Notebook/Samsung Electronics/530U3/530U3C-530U4C/6A47299A5F26/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/01AA74496F>) |
| 2916:f003 | Android          | Android                              | 3     | usbfs      | [5595625922](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/E6203EE83F54/LINUXMINT-19/4.15.0-20-GENERIC/X86_64/5595625922>) |
| 2a45:0c02 | Meizu            | MX Phone (MTP & ADB)                 | 3     | usbfs      | [5B337FDB0A](<Notebook/Apple/MacBookPro8/MacBookPro8,1/35BAC947BDBB/UBUNTU-21.10/5.13.0-16-GENERIC/X86_64/5B337FDB0A>) |
| 0471:0003 | Philips (or NXP) | Hub                                  | 2     | hub        | [20FA770830](<Desktop/Others/Others/Others/C3C1AB1B873D/DEBIAN-11/5.4.0-73-GENERIC/X86_64/20FA770830>) |
| 0471:2008 | Philips (or NXP) | W732                                 | 2     |            | [D315AFD57C](<Desktop/ASRock/FM2/FM2A85X-ITX/379C7DB3BEA5/ROSA-2014.1/4.1.25-NRJ-DESKTOP-1ROSA-X86_64/X86_64/D315AFD57C>) |
| 0bb4:0402 | HTC (High Tec... | Android Phone                        | 2     | rndis_host | [EBBD83B0CA](<Desktop/Gigabyte Technology/GA-870/GA-870A-UD3/591AD831287C/DEBIAN-10/4.19.0-5-AMD64/X86_64/EBBD83B0CA>) |
| 0bb4:0c81 | HTC (High Tec... | Android Phone                        | 2     |            | [404A8B3A68](<All In One/Dell/Precision/Precision 5720 AIO/20C5601ED4D8/FEDORA-30/5.2.16-200.FC30.X86_64/X86_64/404A8B3A68>) |
| 0fce:0189 | Sony Ericsson... | C6503                                | 2     |            | [97D00825B7](<Notebook/Hewlett-Packard/Pavilion/Pavilion g7/841C91D45F4A/ROSA-2014.1/3.14.44-NRJ-DESKTOP-2ROSA-X86_64/X86_64/97D00825B7>) |
| 0fce:019b | Sony Ericsson... | Android                              | 2     |            | [49389100FC](<Notebook/Dell/Inspiron/Inspiron 7560/929244539C9A/ROSA-2014.1/4.1.25-NRJ-DESKTOP-1ROSA-X86_64/X86_64/49389100FC>) |
| 0fce:01b5 | Sony Ericsson... | D2105                                | 2     |            | [165BEE2B5C](<Desktop/ASUSTek Computer/P8/P8H61-USB3/2EFDC79D2759/ROSA-2014.1/4.1.19-NRJ-DESKTOP-2ROSA-X86_64/X86_64/165BEE2B5C>) |
| 0fce:51ad | Sony Ericsson... | Android                              | 2     |            | [41B2D085B5](<Desktop/ASUSTek Computer/M5A99FX/M5A99FX PRO R2.0/1F9169D28464/ROSA-2014.1/4.1.34-NRJ-DESKTOP-2ROSA-X86_64/X86_64/41B2D085B5>) |
| 1004:61fc | LG Electronics   | Optimus 3                            | 2     | cdc_acm... | [1EBB6C2E61](<Notebook/Samsung Electronics/R519/R519-R719/F28CF5443841/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/1EBB6C2E61>) |
| 1527:0200 | Silicon Portals  | YAP Phone (no firmware)              | 2     |            | [D99CCC2771](<Notebook/Toshiba/Satellite/Satellite L755D/7EF92AA4EB2F/UBUNTU-MATE-21.10/5.13.0-28-GENERIC/X86_64/D99CCC2771>) |
| 1532:9051 | Razer USA        | Razer Phone 2                        | 2     |            | [CE5A468AEC](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/14560EB0BD3F/KDE-NEON-20.04/5.11.0-38-GENERIC/X86_64/CE5A468AEC>) |
| 1532:9052 | Razer USA        | Razer Phone 2                        | 2     | usbfs      | [F0B799EFBB](<Notebook/Lenovo/ThinkPad/ThinkPad W520 4270CTO/A54DE4BF9430/UBUNTU-20.04/5.8.0-59-GENERIC/X86_64/F0B799EFBB>) |
| 17ef:74f8 | Lenovo           | MT65xx Android Phone                 | 2     |            | [B89D04A41B](<Notebook/Dell/Inspiron/Inspiron 7720/277F63301B21/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/B89D04A41B>) |

### Printer (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 03f0:2b17 | Hewlett-Packard  | LaserJet 1020                        | 120   | usblp      | [F5E2675CDD](<Desktop/ASRock/A320M-HDV/A320M-HDV R4.0/DCEE71D7D246/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/F5E2675CDD>) |
| 03f0:4117 | Hewlett-Packard  | LaserJet 1018                        | 89    | usblp      | [CA172328F1](<Desktop/ASRock/990FX/990FX Extreme3/15E60474A778/ROSA-12.4/5.17.11-GENERIC-2ROSA2021.1-X86_64/X86_64/CA172328F1>) |
| 067b:2305 | Prolific Tech... | PL2305 Parallel Port                 | 85    | usblp      | [D8EC895BEA](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2347GR2/35EE41997F0D/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D8EC895BEA>) |
| 04e8:3321 | Samsung Elect... | M2020 Series                         | 76    | usblp      | [33EF71C7E7](<Desktop/ASUSTek Computer/P5/P5K-EPU/041355B8B8DF/KUBUNTU-18.04/4.15.0-166-GENERIC/X86_64/33EF71C7E7>) |
| 03f0:0053 | Hewlett-Packard  | DeskJet 2620 All-in-One Printer      | 75    | usblp      | [00794346DB](<Desktop/Gigabyte Technology/AB350-Gaming/AB350-Gaming 3/7AB0F3EF8C28/UBUNTU-22.04/6.0.3-060003-GENERIC/X86_64/00794346DB>) |
| 03f0:002a | Hewlett-Packard  | LaserJet P1102                       | 66    | usblp      | [7711289A77](<Desktop/AZW/U/U59/B8FFBB9DEC08/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/7711289A77>) |
| 04a9:176d | Canon            | PIXMA MG2500 Series                  | 64    | usblp      | [690F25D1AB](<All In One/Lenovo/F0/F0D7008DIN/B668AB35C622/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/690F25D1AB>) |
| 04e8:341b | Samsung Elect... | SCX-4200 series                      | 64    | usblp      | [730EEC29F4](<Desktop/MSI/MS-7/MS-7C56/B27C2E1F0760/UBUNTU-22.04/6.2.5-X64V3-XANMOD1/X86_64/730EEC29F4>) |
| 03f0:e111 | Hewlett-Packard  | DeskJet 2130 series                  | 63    | usblp      | [624D23335B](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/21A1C32506E3/DEBIAN-11/5.10.0-21-AMD64/X86_64/624D23335B>) |
| 04e8:3469 | Samsung Elect... | M2070 Series                         | 62    | usblp      | [BADD20D374](<Desktop/Gigabyte Technology/A320/A320M-S2H/52C4F49FD62D/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/BADD20D374>) |
| 04e8:344f | Samsung Elect... | SCX-3400 Series                      | 57    | usblp      | [B91CBF41C0](<Desktop/Intel/X/X99/2180948880F5/ARTIX/5.11.16-ARTIX1-1/X86_64/B91CBF41C0>) |
| 1a86:7584 | QinHeng Elect... | CH340S                               | 56    | usblp      | [920B722009](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/B72BF47EA842/BLACKPANTHER-OS-18.1/5.15.85-DESKTOP-1BP/X86_64/920B722009>) |
| 03f0:3d17 | Hewlett-Packard  | LaserJet P1005                       | 52    | usblp      | [495DDACC93](<Desktop/Gigabyte Technology/A320/A320M-S2H/B9A5AA7152EC/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/495DDACC93>) |
| 03f0:d711 | Hewlett-Packard  | ENVY 4520 series                     | 52    | usblp      | [0D4AD3C608](<Convertible/Acer/Spin/Spin SP313-51N/8409873CA6E7/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.12-1-DEFAULT/X86_64/0D4AD3C608>) |
| 04a9:2676 | Canon            | LBP2900                              | 52    | usblp      | [6F5A8E2F58](<Desktop/ASUSTek Computer/All/All Series/00678CC502C1/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/6F5A8E2F58>) |
| 04f9:0027 | Brother Indus... | HL-2030 Laser Printer                | 45    | usblp      | [1417777BBC](<Desktop/ASRock/X570/X570 Phantom Gaming 4/C210B48D09BF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/1417777BBC>) |
| 03f0:1853 | Hewlett-Packard  | DeskJet 2700 series                  | 43    | usbfs      | [42A38FB30A](<Desktop/Hyrican Informationssysteme/Hyrican/Hyrican PC A320M-S2H/ECBF8C5B99C3/LINUXMINT-21.1/6.1.4-060104-GENERIC/X86_64/42A38FB30A>) |
| 03f0:0c17 | Hewlett-Packard  | LaserJet 1010                        | 42    | usblp      | [914E3F30CC](<Desktop/Gigabyte Technology/Z490/Z490 AORUS PRO AX/36E8662DB5AE/ALT-10.1/5.15.80-UN-DEF-ALT1/X86_64/914E3F30CC>) |
| 03f0:8711 | Hewlett-Packard  | Deskjet 2050 J510                    | 42    | usblp      | [631317F909](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/A7640481CED2/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/631317F909>) |
| 03f0:e311 | Hewlett-Packard  | DeskJet 3630 series                  | 42    | usblp      | [BBC081E43E](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/7AA19EC63101/MANJARO-22.1.0/6.2.10-1-MANJARO/X86_64/BBC081E43E>) |
| 04e8:3292 | Samsung Elect... | ML-1640 Series Laser Printer         | 40    | usblp      | [E9A4F752C5](<Desktop/ASRock/G41/G41M-VS3/21B774A42A5B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/E9A4F752C5>) |
| 04a9:176b | Canon            | PIXMA MX920 Series                   | 39    | usblp      | [A8D1BD3E81](<Notebook/Lenovo/ThinkPad/ThinkPad L13 Yoga Gen 2a 21AES01A00/C5350302448E/POP!_OS-22.04/6.2.0-76060200-GENERIC/X86_64/A8D1BD3E81>) |
| 04f9:0054 | Brother Indus... | HL-1110 series                       | 38    | usblp      | [5DA3166132](<All In One/Apple/iMac18/iMac18,3/4A7201761BFC/LINUXMINT-21.1/6.1.0-1008-OEM/X86_64/5DA3166132>) |
| 04e8:3441 | Samsung Elect... | SCX-3200 Series                      | 36    | usblp      | [B85A76DD7F](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/5F728961080C/ROSA-12.2/5.10.118-GENERIC-2ROSA2021.1-X86_64/X86_64/B85A76DD7F>) |
| 04a9:178a | Canon            | PIXMA MG3600 Series                  | 35    | usblp      | [CFE1766D1A](<Notebook/Others/Others/Others/79A3A10752B8/MANJARO/6.2.10-1-MANJARO/X86_64/CFE1766D1A>) |
| 03f0:c211 | Hewlett-Packard  | Deskjet 2540 series                  | 34    | usblp      | [2E1715F154](<Desktop/Gigabyte Technology/G31/G31M-ES2L/31E3136365EA/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/2E1715F154>) |
| 04a9:10dc | Canon            | iP7200 series                        | 34    | usblp      | [55DD77BF13](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/B3141CC44EFF/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/55DD77BF13>) |
| 03f0:8911 | Hewlett-Packard  | Deskjet 1050 J410                    | 33    | usblp      | [11F1E291A7](<Desktop/ASUSTek Computer/M4/M4A78LT-M/378B11B03AC2/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/11F1E291A7>) |
| 04a9:1913 | Canon            | LiDE 300                             | 33    | usbfs      | [58D0EA734D](<Notebook/Lenovo/ThinkPad/ThinkPad T530 242962G/D7326B59A5B7/DEBIAN-11/5.10.0-21-AMD64/X86_64/58D0EA734D>) |
| 04a9:2737 | Canon            | MF4410                               | 33    | usblp      | [60191A33B8](<Notebook/Clevo/NL41/NL41MU2/BFAB09E9E2C8/MOS-10/5.10.152-STD-DEF-ALT1/X86_64/60191A33B8>) |
| 04e8:330f | Samsung Elect... | ML-216x Series Laser Printer         | 33    | usblp      | [424F0DCA9D](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/E2B929AE2E0E/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/424F0DCA9D>) |
| 04b8:1143 | Seiko Epson      | L3150 Series                         | 32    | usblp      | [70B2A73996](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-C R2.0/63AE0BE5C62A/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/70B2A73996>) |
| 04da:0f0b | Panasonic (Ma... | KX-MB1500RU                          | 32    | usblp      | [A51FE3226F](<Notebook/ASUSTek Computer/U24/U24E/9AFC2F21A57A/ROSA-12.3/5.10.74-GENERIC-2ROSA2021.1-X86_64/X86_64/A51FE3226F>) |
| 03f0:0317 | Hewlett-Packard  | LaserJet 1200                        | 31    | usblp      | [55EAD22EC0](<Desktop/MSI/MS/MS-7592/BE5A1973267D/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/55EAD22EC0>) |
| 03f0:032a | Hewlett-Packard  | LaserJet Professional P1102w         | 31    | usblp      | [DCAE89C3E5](<Desktop/ASUSTek Computer/H61/H61M-K/0543F1967B9D/UBUNTU-MATE-22.04/5.15.0-67-GENERIC/X86_64/DCAE89C3E5>) |
| 04a9:2759 | Canon            | MF3010                               | 30    | usblp      | [0C5D92EBF9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DT003GRU/DFE02E0590AD/RED-OS-7.3/5.15.87-1.EL7.3.X86_64/X86_64/0C5D92EBF9>) |
| 04b8:0005 | Seiko Epson      | Printer                              | 30    | usblp      | [696581B7B6](<Desktop/MSI/MS/MS-7891/1B010B26E57A/LINUXMINT-20.3/5.4.0-70-GENERIC/X86_64/696581B7B6>) |
| 04b8:0007 | Seiko Epson      | Printer                              | 30    | usblp      | [8F8C7F3A02](<Desktop/Dell/OptiPlex/OptiPlex 755/9DED41FF948E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8F8C7F3A02>) |
| 03f0:102a | Hewlett-Packard  | LaserJet Professional P 1102w        | 29    | usblp      | [568F7928B2](<Desktop/Dell/OptiPlex/OptiPlex 755/E39AC234338F/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/568F7928B2>) |
| 04a9:1912 | Canon            | LiDE 400                             | 29    | usbfs      | [147006A71F](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-A/A5F891271BF2/LINUXMINT-20.2/5.4.0-137-GENERIC/X86_64/147006A71F>) |
| 03f0:0853 | Hewlett-Packard  | ENVY 5000 series                     | 28    | usbfs      | [DD49AFBF3F](<Desktop/Dell/OptiPlex/OptiPlex 990/E25D714EC224/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/DD49AFBF3F>) |
| 03f0:1d17 | Hewlett-Packard  | LaserJet 1320                        | 28    | usblp      | [0D4AD3C608](<Convertible/Acer/Spin/Spin SP313-51N/8409873CA6E7/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.2.12-1-DEFAULT/X86_64/0D4AD3C608>) |
| 04b8:002a | Seiko Epson      | USB2.0 Printer (Hi-speed)            | 28    | usblp      | [0C3F2AF7AD](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/7BD4E80F3F5C/LINUXMINT-18.3/4.10.0-38-GENERIC/X86_64/0C3F2AF7AD>) |
| 03f0:2c17 | Hewlett-Packard  | LaserJet 1022                        | 27    | usblp      | [1354E0B47E](<Notebook/Hewlett-Packard/ProBook/ProBook 430 G1/4277D7AB0C19/ARCH-ROLLING/6.1.14-HARDENED1-1-HARDENED/X86_64/1354E0B47E>) |
| 04b8:005e | Seiko Epson      | L120 Series                          | 26    | usblp      | [33CD5127F2](<Desktop/ASUSTek Computer/B75/B75M-PLUS/6A55EC5426DC/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/33CD5127F2>) |
| 04b8:08a1 | Seiko Epson      | L210 Series                          | 26    | usblp      | [CA172328F1](<Desktop/ASRock/990FX/990FX Extreme3/15E60474A778/ROSA-12.4/5.17.11-GENERIC-2ROSA2021.1-X86_64/X86_64/CA172328F1>) |
| 04f9:003f | Brother Indus... | HL-2130 series                       | 26    | usblp      | [89846CDD59](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/9A32E466A2D2/OPENMANDRIVA-23.01/6.1.4-DESKTOP-1OMV2301/X86_64/89846CDD59>) |
| 03f0:0653 | Hewlett-Packard  | DeskJet 3700 series                  | 25    | usbfs      | [1E10EAA9AE](<Mini Pc/Intel Client Systems/NUC12/NUC12WSKi7/99448835CE69/LINUXMINT-21.1/5.19.0-41-GENERIC/X86_64/1E10EAA9AE>) |
| 04e8:326c | Samsung Elect... | ML-2010P Mono Laser Printer          | 25    | usblp      | [45F39402F0](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ITL6 82H8/1E5ED8E528A2/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/45F39402F0>) |
| 04a9:26b4 | Canon            | MF4010 series                        | 24    | usblp      | [5FB80DA27B](<Desktop/DEPO Computers/DPH410/DPH410S/891701B8F688/ALT-8.4/5.10.156-STD-DEF-ALT0.C9F.2/X86_64/5FB80DA27B>) |

### Scanner (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 04a9:1909 | Canon            | CanoScan LiDE 110                    | 116   | usbfs      | [7AC436D763](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92P 3227BD2/791575E45E29/XUBUNTU-20.04/5.15.0-69-GENERIC/X86_64/7AC436D763>) |
| 04a9:2220 | Canon            | CanoScan LIDE 25                     | 86    | usbfs      | [696CC9B57A](<Desktop/Dell/OptiPlex/OptiPlex 3020/BA562E2E47E4/SLACKWARE-15.0/5.15.94/X86_64/696CC9B57A>) |
| 04a9:190a | Canon            | CanoScan LiDE 210                    | 79    |            | [97620AC3E7](<Desktop/MSI/MS-7/MS-7C56/6D5C43A6D204/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/97620AC3E7>) |
| 04a9:220d | Canon            | CanoScan N670U/N676U/LiDE 20         | 79    |            | [E9A4F752C5](<Desktop/ASRock/G41/G41M-VS3/21B774A42A5B/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/E9A4F752C5>) |
| 04a9:190f | Canon            | CanoScan LiDE 220                    | 64    | usbfs      | [D89F9A2346](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-507/128101606584/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/D89F9A2346>) |
| 04a9:190e | Canon            | CanoScan LiDE 120                    | 54    | usbfs      | [DEF987E32C](<Desktop/ASRock/B365/B365M-HDV/F0C269B393DF/ARCH-ROLLING/6.2.1-ARCH1-1/X86_64/DEF987E32C>) |
| 04a9:1904 | Canon            | CanoScan LiDE 100                    | 44    |            | [96099A3217](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ca0xxx/731B71307EB0/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/96099A3217>) |
| 03f0:0a01 | Hewlett-Packard  | ScanJet 2400c                        | 37    | usbfs      | [FD3560384C](<Notebook/Clevo/W240/W240EL-W250ELQ-W270ELQ/895236C8E4E0/ROSA-12.3/5.15.75-GENERIC-1ROSA2021.1-X86_64/X86_64/FD3560384C>) |
| 04a9:220e | Canon            | CanoScan N1240U/LiDE 30              | 36    | usbfs      | [C9E3B1D5EA](<Desktop/Gigabyte Technology/B460/B460HD3/EC540068EF3B/GENTOO-2.13/6.1.19-GENTOO/X86_64/C9E3B1D5EA>) |
| 04b8:0121 | Seiko Epson      | GT-F500/GT-F550 [Perfection 2480/... | 28    |            | [65F96586EC](<Desktop/Huanan/X99-F8D/X99-F8D V2.6/F269F65269B2/FEDORA-37/6.2.7-200.FC37.X86_64/X86_64/65F96586EC>) |
| 04b8:0142 | Seiko Epson      | GT-F730 [GT-S630/Perfection V33/V... | 26    | usbfs      | [3AB4EBDBFD](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/CE519D9CC12C/UBUNTU-20.04/5.11.0-43-GENERIC/X86_64/3AB4EBDBFD>) |
| 04a9:221c | Canon            | CanoScan LiDE 60                     | 25    |            | [310A65BAEA](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92p 3212BD3/39870786B287/LINUXMINT-21.1/5.15.0-60-GENERIC/X86_64/310A65BAEA>) |
| 04b8:0130 | Seiko Epson      | GT-X770 [Perfection V500]            | 24    |            | [474C43577F](<Desktop/MSI/MS-7/MS-7C92/EC7C65BAEBD4/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/474C43577F>) |
| 05d8:4002 | Ultima Electr... | Artec Ultima 2000 (GT6801 based)/... | 24    | usbfs      | [2DC41C0B99](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/E54CED74845D/UBUNTU-20.04/5.13.0-51-GENERIC/X86_64/2DC41C0B99>) |
| 04b8:013a | Seiko Epson      | GT-X820 [Perfection V600 Photo]      | 23    |            | [7D0BDD8606](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/B0D96864496C/KUBUNTU-22.10/5.19.0-29-GENERIC/X86_64/7D0BDD8606>) |
| 04a9:1905 | Canon            | CanoScan LiDE 200                    | 21    |            | [3288BF6604](<Desktop/Fujitsu/ESPRIMO/ESPRIMO E900/F3FA494E8E73/UBUNTU-20.04/5.15.0-60-GENERIC/X86_64/3288BF6604>) |
| 04a9:2213 | Canon            | CanoScan LiDE 50/LiDE 35/LiDE 40     | 20    |            | [FEEED093C0](<Desktop/MSI/MS-7/MS-7C37/336098CF0FE3/XUBUNTU-20.04/5.4.0-137-GENERIC/X86_64/FEEED093C0>) |
| 04b8:0122 | Seiko Epson      | GT-F520/GT-F570 [Perfection 3590 ... | 20    | usbfs      | [FF12FE840D](<Notebook/Lenovo/ThinkPad/ThinkPad L15 Gen 1 20U70001MX/93427B8970E7/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/FF12FE840D>) |
| 04b8:012d | Seiko Epson      | GT-F650 [GT-S600/Perfection V10/V... | 20    |            | [55EAD22EC0](<Desktop/MSI/MS/MS-7592/BE5A1973267D/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/55EAD22EC0>) |
| 055f:021b | Mustek Systems   | BearPaw 1200 CU Plus                 | 16    | usbfs      | [DE63F89D08](<Desktop/Gigabyte Technology/H61/H61M-D2H/8ACC07EA8985/ROSA-2016.1/4.9.60-NRJ-DESKTOP-1ROSA-X86_64/X86_64/DE63F89D08>) |
| 04b8:011f | Seiko Epson      | GT-8400UF [Perfection 1670/1670 P... | 15    |            | [C74B2B540E](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/BCFF47B91DE6/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/C74B2B540E>) |
| 055f:021f | Mustek Systems   | SNAPSCAN e22                         | 14    |            | [3A2E128ECD](<Notebook/Chuwi/MiniBook/MiniBook/F3098A0D3D6C/UBUNTU-20.04/5.4.0-107-LOWLATENCY/X86_64/3A2E128ECD>) |
| 04a9:1907 | Canon            | CanoScan LiDE 700F                   | 13    | usbfs      | [AF24409637](<Desktop/Gigabyte Technology/GA-MA78/GA-MA78GM-S2H/653306D443E6/UBUNTU-19.10/5.3.0-64-GENERIC/X86_64/AF24409637>) |
| 04b8:011b | Seiko Epson      | GT-9300UF [Perfection 2400 PHOTO]    | 13    |            | [9010E03A18](<Desktop/ASUSTek Computer/M4A89TD/M4A89TD PRO USB3/DD0925162355/UBUNTU-18.04/5.4.0-135-GENERIC/X86_64/9010E03A18>) |
| 04b8:0120 | Seiko Epson      | GT-7400U [Perfection 1270]           | 13    |            | [2FCE3F9ABF](<Desktop/Gigabyte Technology/F2/F2A55-DS3/744651733A34/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/2FCE3F9ABF>) |
| 04a9:1900 | Canon            | CanoScan LiDE 90                     | 12    |            | [63C52BC5DB](<Desktop/Gigabyte Technology/B450M/B450M DS3H V2/FA30CEDF9E8C/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/63C52BC5DB>) |
| 04a9:2206 | Canon            | CanoScan N650U/N656U                 | 12    |            | [62048F37D6](<Desktop/Gigabyte Technology/A320/A320M-S2H/1B47CFCEAA5E/LINUXMINT-20.3/5.4.0-132-GENERIC/X86_64/62048F37D6>) |
| 04b8:0119 | Seiko Epson      | GT-X750 [Perfection 4490 Photo]      | 10    |            | [B15A265C66](<Notebook/Hewlett-Packard/ENVY/ENVY dv7/B50D1039DBF5/ZORIN-16/5.13.0-35-GENERIC/X86_64/B15A265C66>) |
| 04b8:0131 | Seiko Epson      | GT-F720 [GT-S620/Perfection V30/V... | 10    |            | [43B4579869](<Desktop/Gigabyte Technology/B150/B150M-D3H/F3481A4CB99E/FEDORA-36/5.18.16-200.FC36.X86_64/X86_64/43B4579869>) |
| 04b8:013b | Seiko Epson      | Scanner                              | 10    |            | [6E5A2E29F4](<Notebook/Packard Bell/EasyNote/EasyNote TE11HC/FFDFCA409720/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/6E5A2E29F4>) |
| 03f0:2605 | Hewlett-Packard  | ScanJet 3800c                        | 9     |            | [43DBFDDD1B](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800p Convertible Minitower/E4B7F0AF9A18/LINUXMINT-21.1/5.15.0-56-GENERIC/X86_64/43DBFDDD1B>) |
| 04a9:190d | Canon            | CanoScan 9000F Mark II               | 9     | usbfs      | [CA004ECEAE](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/1CE869BED262/POP!_OS-22.04/6.1.11-76060111-GENERIC/X86_64/CA004ECEAE>) |
| 04a9:2228 | Canon            | CanoScan 4400F                       | 9     |            | [41F46AC946](<Desktop/Lenovo/ThinkStation/ThinkStation P340 30DH00LNGE/88BEEBA28E49/UBUNTU-20.04/5.10.0-1051-OEM/X86_64/41F46AC946>) |
| 04b8:012e | Seiko Epson      | GT-F670 [Perfection V200 Photo]      | 9     |            | [EDD8B3C5B2](<Desktop/ASUSTek Computer/PRIME/PRIME X399-A/8D222005E7BF/FEDORA-34/5.13.12-200.FC34.X86_64/X86_64/EDD8B3C5B2>) |
| 055f:0006 | Mustek Systems   | ScanExpress 1200 UB                  | 9     |            | [4BBE8325BD](<Desktop/MSI/MS/MS-7721/3ABCE5440401/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/4BBE8325BD>) |
| 03f0:1705 | Hewlett-Packard  | ScanJet 5590                         | 8     |            | [BE0D616E99](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/DB76163FE6D3/FEDORA-35/5.16.18-200.FC35.X86_64/X86_64/BE0D616E99>) |
| 03f0:1c05 | Hewlett-Packard  | Scanjet 200                          | 8     |            | [FEBB5AEE31](<Desktop/Hewlett-Packard/Compaq/Compaq 4000 Pro SFF PC/BDB5B57704B3/LINUXMINT-19.3/5.4.0-47-GENERIC/X86_64/FEBB5AEE31>) |
| 03f0:1d05 | Hewlett-Packard  | Scanjet 300                          | 8     |            | [FFC55DE046](<Desktop/Acer/Aspire/Aspire M7720/3F14ABFEBF42/LINUXMINT-21.1/5.15.0-67-GENERIC/X86_64/FFC55DE046>) |
| 03f0:2305 | Hewlett-Packard  | ScanJet 3970c                        | 8     |            | [B887990C12](<Desktop/Hewlett-Packard/Z1/Z1 Entry Tower G5/60AFD0FE52EA/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/B887990C12>) |
| 04a9:2224 | Canon            | CanoScan LiDE 600F                   | 8     |            | [912F409B37](<Notebook/Dell/Studio/Studio 1735/BC2303B841C5/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/912F409B37>) |
| 04a9:2225 | Canon            | CanoScan LiDE 70                     | 8     |            | [49D8A19239](<Desktop/ASUSTek Computer/P8P67/P8P67 PRO/A676DFF54379/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/49D8A19239>) |
| 04b8:011d | Seiko Epson      | GT-7300U [Perfection 1260/1260 PH... | 8     |            | [95E7B7D833](<Notebook/Samsung Electronics/350V5/350V5C-351V5C-3540VC-3440VC/C50E5D8F750C/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/95E7B7D833>) |
| 055f:021d | Mustek Systems   | BearPaw 2400 CU Plus                 | 8     |            | [A5CA2582B6](<Desktop/ASUSTek Computer/M2N-MX/M2N-MX SE Plus/BFA5BBD7D3FC/ROSA-2016.1/4.9.155-NRJ-DESKTOP-1ROSA-X86_64/X86_64/A5CA2582B6>) |
| 03f0:0605 | Hewlett-Packard  | ScanJet 2200c                        | 7     |            | [7B827ACAC4](<Desktop/Gigabyte Technology/EP45/EP45-DS3/F60BF171F74E/ROSA-2016.1/5.4.32-GENERIC-2ROSA-I586/I686/7B827ACAC4>) |
| 03f0:0b01 | Hewlett-Packard  | ScanJet 82x0C                        | 7     | usbfs      | [3070F4E7DA](<Desktop/Dell/Vostro/Vostro 430/F5EC54FE6532/ROCKY-8.7/4.18.0-425.19.2.EL8_7.X86_64/X86_64/3070F4E7DA>) |
| 03f0:2f11 | Hewlett-Packard  | PSC 1200                             | 7     | usblp      | [B8F3A58A03](<Desktop/Lenovo/H30-05/H30-05 90BJ00CNMT/1FE0A2E8CD7B/ZORIN-16/5.15.0-46-GENERIC/X86_64/B8F3A58A03>) |
| 04a9:1908 | Canon            | CanoScan                             | 7     | usbfs      | [8EE3D68631](<Desktop/MSI/MS-7/MS-7B86/D81D4029A3DB/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/8EE3D68631>) |
| 04a9:221b | Canon            | CanoScan 4200F                       | 7     |            | [8B560B455E](<Desktop/Gigabyte Technology/Z97/Z97-HD3/CDDE5B0BA711/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/8B560B455E>) |
| 04b8:010f | Seiko Epson      | GT-7200U [Perfection 1250/1250 PH... | 7     |            | [AE15BD941D](<Notebook/MSI/GT/GT70/C29DA523610A/UBUNTU-21.10/5.13.0-19-GENERIC/X86_64/AE15BD941D>) |
| 04b8:012c | Seiko Epson      | GT-X900 [Perfection V700/V750 Photo] | 7     |            | [595B975199](<Convertible/ASUSTek Computer/ZenBook/ZenBook UX463FL_UX463FL/2FD4C08DE73F/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/595B975199>) |

### Serial controller (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a86:7523 | QinHeng Elect... | CH340 serial converter               | 543   | ch341      | [561202C004](<Notebook/Apple/MacBookPro3/MacBookPro3,1/469E66CF314F/UBUNTU-18.04/4.15.0-211-GENERIC/I686/561202C004>) |
| 0403:6001 | Future Techno... | FT232 Serial (UART) IC               | 419   | ftdi_sio   | [E40D8038DA](<Desktop/Gigabyte Technology/Z370/Z370 HD3P/06D2617A49D3/DEBIAN-11/5.10.0-20-AMD64/X86_64/E40D8038DA>) |
| 067b:2303 | Prolific Tech... | PL2303 Serial Port / Mobile Actio... | 342   | pl2303     | [00794346DB](<Desktop/Gigabyte Technology/AB350-Gaming/AB350-Gaming 3/7AB0F3EF8C28/UBUNTU-22.04/6.0.3-060003-GENERIC/X86_64/00794346DB>) |
| 10c4:ea60 | Silicon Labs     | CP210x UART Bridge                   | 317   | cp210x     | [AF2BAA1787](<Notebook/Dell/Latitude/Latitude E4200/A727046F6BE9/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/AF2BAA1787>) |
| 05c6:9204 | Qualcomm         | Gobi 2000                            | 125   | qcserial   | [8DAF9AF9B5](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2522PT3/684F9A3B3ABC/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/8DAF9AF9B5>) |
| 03f0:521d | Hewlett-Packard  | HP hs3110 HSPA+ Mobile Broadband ... | 109   | option     | [43F6A6180A](<Notebook/Hewlett-Packard/ProBook/ProBook 11 G2/6DD1DDE2E353/XUBUNTU-22.04/5.19.0-40-GENERIC/X86_64/43F6A6180A>) |
| 2c7c:0125 | Quectel Wirel... | EC25 LTE modem                       | 81    | qmi_wwan   | [6EA31CC2ED](<Mini Pc/AMI/Aptio/Aptio CRB/5AEFCC18D04F/UBUNTU-22.04/5.15.0-69-GENERIC/X86_64/6EA31CC2ED>) |
| 12d1:15c1 | Huawei Techno... | ME906s LTE M.2 Module                | 70    | option     | [E81EB02947](<Notebook/Lenovo/ThinkPad/ThinkPad X260 20F6CTO1WW/AB15C0B2C0CA/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/E81EB02947>) |
| 03f0:a31d | Hewlett-Packard  | lt4132 LTE/HSPA+ 4G Module           | 67    | option     | [08A19AE7B9](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/2CCDD2110E85/FEDORA-38/6.2.9-300.FC38.X86_64/X86_64/08A19AE7B9>) |
| 0451:3410 | Texas Instrum... | TUSB3410 Microcontroller             | 61    | ti_usb_... | [25EAC72561](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/3A9DF5F55034/UBUNTU-UNITY-22.04/5.19.0-38-GENERIC/X86_64/25EAC72561>) |
| 03f0:241d | Hewlett-Packard  | Gobi 2000 Wireless Modem (QDL mode)  | 60    | qcserial   | [DD6FFB8639](<Notebook/Hewlett-Packard/ProBook/ProBook 6450b/743DD52562B5/ROSA-12.4/5.15.103-GENERIC-1ROSA2021.1-X86_64/X86_64/DD6FFB8639>) |
| 0403:6010 | Future Techno... | FT2232C/D/H Dual UART/FIFO IC        | 52    | ftdi_sio   | [383B9D3AEC](<Notebook/Dell/Latitude/Latitude 7490/63BD8A8EB2D4/UBUNTU-20.04/5.15.0-71-GENERIC/X86_64/383B9D3AEC>) |
| 0403:6015 | Future Techno... | Bridge(I2C/SPI/UART/FIFO)            | 52    | ftdi_sio   | [629ADAF380](<Desktop/ASRock/Z790/Z790 Taichi Carrara/552260AE6CC2/DEBIAN-11/6.3.0-RC1-RECOMPV5/X86_64/629ADAF380>) |
| 1199:9013 | Sierra Wireless  | Sierra Wireless Gobi 3000 Modem d... | 51    | qcserial   | [F45E2448AA](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236PA8/D92E3357AE6B/XUBUNTU-22.04/5.15.0-60-GENERIC/X86_64/F45E2448AA>) |
| 1b1c:1c00 | Corsair          | Controller for Corsair Link          | 38    | cp210x     | [E1D1BDEF81](<Desktop/Gigabyte Technology/X99-Gaming/X99-Gaming 5/FD256B0D0F49/MANJARO-22.1.0/6.1.25-1-MANJARO/X86_64/E1D1BDEF81>) |
| 0403:6014 | Future Techno... | FT232H Single HS USB-UART/FIFO IC    | 34    | ftdi_sio   | [9E668FF813](<Desktop/ASRock/B760M/B760M Steel Legend WiFi/75DB047FD17D/UBUNTU-22.04/6.1.0-1007-OEM/X86_64/9E668FF813>) |
| 03f0:201d | Hewlett-Packard  | un2400 Gobi Wireless Modem (QDL m... | 27    | qcserial   | [519D2A4D5A](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2530p/BD5EC8AEF33E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/519D2A4D5A>) |
| 1199:9000 | Sierra Wireless  | Gobi 2000 Wireless Modem (QDL mode)  | 27    | qcserial   | [82EA6E2287](<Notebook/Getac/B300/B300-X/500CF3054A80/LINUXMINT-20.3/5.4.0-144-GENERIC/X86_64/82EA6E2287>) |
| 05c6:9224 | Qualcomm         | Sony Gobi 2000 Wireless Modem (QD... | 26    | qcserial   | [512DA95FB0](<Notebook/Sony/VPCZ12/VPCZ12C5E/1637E7C20BD6/UBUNTU-22.04/5.19.0-32-GENERIC/X86_64/512DA95FB0>) |
| 10c4:ea70 | Cygnal Integr... | CP210x UART Bridge                   | 26    | cp210x     | [A1584C31EC](<Notebook/Acer/Aspire/Aspire V3-772/E4A24E888A11/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.5.7-1-DEFAULT/X86_64/A1584C31EC>) |
| 19d2:0016 | ZTE WCDMA Tec... | ZTE Technologies MSM                 | 25    | option     | [CE95ADE177](<Convertible/Acer/Spin/Spin SP314-53/5DA43514AAAB/UBUNTU-22.04/5.15.0-43-GENERIC/X86_64/CE95ADE177>) |
| 0403:6011 | Future Techno... | FT4232H Quad HS USB-UART/FIFO IC     | 21    | ftdi_sio   | [3B2AC9206C](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/63F68F9C401C/GENTOO-2.13/6.2.11-GENTOO-X86_64/X86_64/3B2AC9206C>) |
| 0fcf:1008 | Dynastream In... | ANTUSB2 Stick                        | 21    | usb_ser... | [A38BF561F7](<Desktop/ASRock/Z170/Z170 Gaming K4/19138DC977DF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/A38BF561F7>) |
| 0fcf:1009 | Dynastream In... | ANTUSB-m Stick                       | 21    | usb_ser... | [D84840D5C9](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7002CUS/5CFC5EAFB4A1/UBUNTU-UNITY-22.04/5.15.0-58-GENERIC/X86_64/D84840D5C9>) |
| 413c:8185 | Dell             | Gobi 2000 Wireless Modem (QDL mode)  | 20    | qcserial   | [CF7E033A17](<Notebook/Dell/Precision/Precision M4500/03C4EE3AB0E6/ZORIN-16/5.15.0-69-GENERIC/X86_64/CF7E033A17>) |
| 05c6:9008 | Qualcomm         | Gobi Wireless Modem (QDL mode)       | 19    | qcserial   | [CD68A79E95](<Desktop/ASUSTek Computer/B150/B150M-A-M.2/55D646FFB8E7/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/CD68A79E95>) |
| 0557:2008 | ATEN Internat... | UC-232A Serial Port [pl2303]         | 17    | pl2303     | [F090AA4D60](<Notebook/Lenovo/ThinkPad/ThinkPad X61s 7667CG7/54E944F5A492/ARCH-ROLLING/6.1.12-ARCH1-1/X86_64/F090AA4D60>) |
| 2c7c:030a | Quectel Wirel... | Quectel EM05-G                       | 17    | cdc_mbim   | [23D2C52019](<Convertible/Lenovo/ThinkPad/ThinkPad L13 Yoga Gen 3 21BCS01R00/428CFC9ED602/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/23D2C52019>) |
| 413c:81d7 | Dell             | DW5821e Snapdragon X20 LTE           | 16    | option     | [3807975438](<Notebook/Dell/Latitude/Latitude 7430/F173DEE0FE44/UBUNTU-22.10/5.19.0-29-GENERIC/X86_64/3807975438>) |
| 03f0:1e1d | Hewlett-Packard  | hs2300 HSDPA Broadband Wireless M... | 14    | sierra     | [C2C6B63123](<Notebook/THD/PX/PX1/B2C611FBE9FA/BLACKPANTHER-OS-18.1/5.6.14-DESKTOP-2BP/X86_64/C2C6B63123>) |
| 057c:6201 | AVM              | AVM Fritz!WLAN v1.1 [Texas Instru... | 13    | option     | [89AE1A3E9D](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/1DCD288DE1CB/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/89AE1A3E9D>) |
| 067b:23a3 | Prolific Tech... | USB-Serial Controller                | 13    | pl2303     | [D1344E36DD](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 TWR/AE205CE4F972/ENDEAVOUROS-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/D1344E36DD>) |
| 0d9f:0002 | Powercom         | Black Knight PRO / WOW Uninterrup... | 13    | cypress... | [74C7BDE15C](<Desktop/ASRock/A75/A75M-HVS/7076D7DE8D97/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/74C7BDE15C>) |
| 19d2:2003 | ZTE WCDMA Tec... | ZTE WCDMA Technologies MSM           | 13    | option     | [F125F4CD03](<Desktop/ASRock/775/775Dual-880Pro/1F74339C25D8/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/F125F4CD03>) |
| 04b4:5500 | Cypress Semic... | HID->COM RS232 Adapter               | 12    | cypress... | [1ABE984576](<Desktop/Dell/OptiPlex/OptiPlex 9020/428944E768AC/RISIOS-37/6.1.6-200.FC37.X86_64/X86_64/1ABE984576>) |
| 10c4:8a2a | Silicon Labs     | HubZ Smart Home Controller           | 12    | cp210x     | [2D767E0513](<System On Chip/Rockchip/Orange/Orange Pi 5/B6466CB0DFF0/DEBIAN-11/5.10.110-ROCKCHIP-RK3588/AARCH64/2D767E0513>) |
| 1199:683c | Sierra Wireless  | Mobile Broadband 3G/UMTS (MC8790 ... | 12    | sierra     | [953D03DF07](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK S6420/AE64054EAC7F/ZORIN-15/5.4.0-58-GENERIC/X86_64/953D03DF07>) |
| 0af0:6901 | Option           | Globetrotter HSDPA Modem             | 10    | option     | [EE6FDF4608](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile D9500/DF33913DD5B2/MX-21/5.10.0-8-AMD64/X86_64/EE6FDF4608>) |
| 10c4:ea71 | Silicon Labs     | CP2108 Quad UART Bridge              | 10    | cp210x     | [96E896465A](<Server/Supermicro/Super/Super Server/264448779CFE/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/96E896465A>) |
| 05c6:9221 | Qualcomm         | Gobi Wireless Modem (QDL mode)       | 8     | qcserial   | [BD0B916FE7](<Notebook/Sony/VGN-P688/VGN-P688E/E654EB2F5BD2/ROSA-2016.1/5.4.83-GENERIC-2ROSA-I586/I686/BD0B916FE7>) |
| 1199:6813 | Sierra Wireless  | Mini Card                            | 8     | sierra     | [BC0E60B586](<Notebook/Lenovo/ThinkPad/ThinkPad T61 7661A16/60AAD72775BB/LMDE-5/5.10.0-20-AMD64/X86_64/BC0E60B586>) |
| 1199:6832 | Sierra Wireless  | MC8780 Device                        | 7     | sierra     | [3B7266D323](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK S6410/66E7AC9B5367/OPENMANDRIVA-4.50/5.12.4-DESKTOP-1OMV4050/X86_64/3B7266D323>) |
| 1199:68c0 | Sierra Wireless  | MC7304                               | 7     | qcserial   | [40782BA0A7](<Notebook/Panasonic/CF-31/CF-31WEUEEBE/B0E16EA3A89C/DEBIAN-11/5.10.0-21-AMD64/X86_64/40782BA0A7>) |
| 1e0e:9001 | Qualcomm / Op... | SimTech SIM7000                      | 7     | option     | [24182862CD](<Notebook/Valve/Jupiter/Jupiter/A562B04AD7E0/STEAMOS-3.4/5.13.0-VALVE35-1-NEPTUNE/X86_64/24182862CD>) |
| 413c:8133 | Dell             | Wireless 5720 VZW Mobile Broadban... | 7     | option     | [712B22AD9B](<Notebook/Dell/Latitude/Latitude D630/1F554D557F80/UBUNTU-20.04/5.11.0-46-GENERIC/X86_64/712B22AD9B>) |
| 0711:0230 | Magic Control... | MCT-232 Serial Port                  | 6     | mct_u232   | [228A05B70F](<Notebook/Medion/P6687/P6687 MD60815/F113B192EF67/LINUXMINT-20/4.19.163-0419163-GENERIC/X86_64/228A05B70F>) |
| 091e:0003 | Garmin Intern... | GPS (various models)                 | 6     | garmin_gps | [3A524796F6](<Desktop/ASUSTek Computer/Z170/Z170-DELUXE/CC40DF32FE07/DEBIAN-11/5.10.0-20-AMD64/X86_64/3A524796F6>) |
| 1b1c:1c02 | Corsair          | AX1500i Power Supply                 | 6     | cp210x     | [7A65820BE2](<Desktop/ASUSTek Computer/All/All Series/DDE3B44F4615/DEBIAN-11/6.0.3/X86_64/7A65820BE2>) |
| 413c:819b | Dell             | Novatel Wireless HSPA                | 6     | cdc_eth... | [95B7617708](<Notebook/Dell/Latitude/Latitude E6430/A487F9B02433/DEVUAN-4/5.10.0-14-AMD64/X86_64/95B7617708>) |
| 413c:81e0 | Dell             | DW5821e-eSIM Snapdragon X20 LTE      | 6     | option     | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |

### Smartcard (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1209:beee | Generic          | Solo 2 Security Key                  | 3     | usbfs, ... | [966EB5BB18](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE/21F9A4DB3C4D/GENTOO-2.8/5.15.74-GENTOO/X86_64/966EB5BB18>) |
| 20a0:42b2 | Clay Logic       | Nitrokey 3                           | 2     | cdc_acm    | [066F0CD17B](<Notebook/TUXEDO/Aura/Aura 15 Gen1/78F7C63CBEFD/ENDEAVOUROS-ROLLING/6.2.6-ARCH1-1/X86_64/066F0CD17B>) |
| 0483:00df | STMicroelectr... | SCAN-BIO                             | 1     |            | [07C752AA8C](<Tablet/ZoomSmart/A/A1002/F1BBB3E02B52/ROSA-2019.05/5.4.60-NICKEL-2ROSA2019.05-X86_64/X86_64/07C752AA8C>) |

### Sound (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0d8c:0014 | C-Media Elect... | Audio Adapter (Unitek Y-247A)        | 757   | snd_usb... | [761B89209D](<Notebook/Hewlett-Packard/ZBook/ZBook Studio G3/A8FA5C81BE84/UBUNTU-22.10/6.3.1-TKG-CFS/X86_64/761B89209D>) |
| 1b3f:2008 | Generalplus T... | YC1006                               | 596   | snd_usb... | [558C305AF2](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/558C305AF2>) |
| 08bb:2902 | Texas Instrum... | PCM2902 Audio Codec                  | 470   | snd_usb... | [F86E67C005](<Desktop/Gigabyte Technology/Z97/Z97-D3H/A009D543E318/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F86E67C005>) |
| 0d8c:0012 | C-Media Elect... | USB Audio Device                     | 427   | snd_usb... | [C7A298018F](<Convertible/Lenovo/ThinkPad/ThinkPad 11e Yoga Gen 6 20SES00200/1485DED24727/ENDEAVOUROS-ROLLING/6.3.1-ARCH1-1/X86_64/C7A298018F>) |
| 0d8c:013c | C-Media Elect... | CM108 Audio Controller               | 347   | snd_usb... | [FB7920C5F9](<Desktop/ASUSTek Computer/M3N/M3N WS/208D21EEB6BD/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FB7920C5F9>) |
| 0951:16a4 | Kingston Tech... | HyperX 7.1 Audio                     | 339   | snd_usb... | [1EDDB3203A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/1EDDB3203A>) |
| 0d8c:0005 | C-Media Elect... | Blue Snowball                        | 319   | snd_usb... | [6BC581F37C](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 3rd 20BTS41M00/1BB051547327/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/6BC581F37C>) |
| 0c76:161f | JMTek            | USB PnP Audio Device                 | 262   | snd_usb... | [55F6CAEC2D](<System On Chip/Others/Others/Others/3584471355A1/DEBIAN-11/4.9.318-SUN50IW9/AARCH64/55F6CAEC2D>) |
| 0bda:4014 | Realtek Semic... | USB Audio                            | 260   | snd_usb... | [9E0A1BD8EF](<Notebook/Dell/Precision/Precision 7720/549B690E7A8B/ARCH-ROLLING/6.1.27-1-LTS/X86_64/9E0A1BD8EF>) |
| 0bda:402e | Realtek Semic... | USB Audio                            | 239   | snd_usb... | [05EDD845DF](<Tablet/Lenovo/Tablet/Tablet 10 20L3000KGE/7130A0BB6850/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/05EDD845DF>) |
| 8086:0808 | Intel            | USB PnP Sound Device                 | 233   | snd_usb... | [0CBC314C84](<Notebook/Hewlett-Packard/ProBook/ProBook 650 G1/AA455B6A4622/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/0CBC314C84>) |
| b58e:9e84 | Blue Microphones | Yeti Stereo Microphone               | 222   | snd_usb... | [CABB24B0E7](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC/UBUNTU-20.04/5.4.0-147-GENERIC/X86_64/CABB24B0E7>) |
| 0c76:161e | JMTek            | USB PnP Audio Device                 | 204   | snd_usb... | [B979325EEA](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/EDB7A2296562/ROSA-12.4/6.3.1.XM1-1.KLP-XANMOD-ROSA2021.1-X86_64/X86_64/B979325EEA>) |
| 1130:1620 | Tenx Technology  | USB AUDIO                            | 190   | snd_usb... | [B638694274](<Desktop/Dell/Vostro/Vostro 400/9FEBBAB61593/DEBIAN-11/5.10.0-20-AMD64/X86_64/B638694274>) |
| 0d8c:000c | C-Media Elect... | Audio Adapter                        | 182   | snd_usb... | [1714BFFA0E](<Notebook/Lenovo/V15/V15 G2 IJL 82QY/149E36C01FCA/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/1714BFFA0E>) |
| 0d8c:0102 | C-Media Elect... | CM106 Like Sound Device              | 182   | snd_usb... | [5C00E2D415](<Server/Intel/S5520/S5520HC/42DF18E9A677/FEDORA-38/6.2.13-300.FC38.X86_64/X86_64/5C00E2D415>) |
| 0d8c:0134 | C-Media Elect... | BIRD UM1                             | 149   | snd_usb... | [EE33A17BAA](<Desktop/ASUSTek Computer/TUF/TUF B450-PLUS GAMING/5071E24FD04D/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/EE33A17BAA>) |
| 046d:0a8f | Logitech         | H390 headset with microphone         | 148   | snd_usb... | [C8B7FFA6DC](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/AD75E2FE7BA1/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/C8B7FFA6DC>) |
| 413c:a503 | Dell             | AC511 Sound Bar                      | 145   | snd_usb... | [08DF3C35EE](<Desktop/Dell/OptiPlex/OptiPlex 7040/74B9A8608B3A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/08DF3C35EE>) |
| 046d:0a44 | Logitech         | Headset H390                         | 131   | snd_usb... | [F78F58795C](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8460p/3F2589B2E265/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F78F58795C>) |
| 1038:12ad | SteelSeries ApS  | SteelSeries Arctis 7                 | 124   | snd_usb... | [B3ED654FDE](<Desktop/ASRock/X570/X570 Phantom Gaming 4/6A927400912B/POP!_OS-22.04/6.3.1-X64V1-XANMOD1/X86_64/B3ED654FDE>) |
| 1852:7022 | GYROCOM C&C      | Fiio E10                             | 121   | snd_usb... | [063E548538](<Desktop/ASRock/X570/X570 Taichi/886C493D94EB/GENTOO-2.13/6.1.22-GENTOO-DIST/X86_64/063E548538>) |
| 17ef:3083 | Lenovo           | ThinkPad Thunderbolt 3 Dock USB A... | 120   | snd_usb... | [7BBDC5E568](<Notebook/Dell/XPS/XPS 13 9300/4E6F55491119/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/7BBDC5E568>) |
| 17ef:a396 | Lenovo           | ThinkPad USB-C Dock Gen2 USB Audio   | 117   | snd_usb... | [1F2D88BFAE](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 4 21ECS00000/642B185E080D/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/1F2D88BFAE>) |
| 054c:09cc | Sony             | DualShock 4 [CUH-ZCT2x]              | 114   | snd_usb... | [DB1AD69341](<Desktop/MSI/MS-7/MS-7D17/0B3A86521786/REBORNOS-ROLLING/6.3.1-ARCH1-1/X86_64/DB1AD69341>) |
| 046d:0a29 | Logitech         | H600 [Wireless Headset]              | 108   | snd_usb... | [D9AD034D8C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A90014US/5207707CA9E6/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/D9AD034D8C>) |
| 03f0:056b | Hewlett-Packard  | USB Audio                            | 105   | snd_usb... | [6E086EC096](<Notebook/Hewlett-Packard/EliteBook/EliteBook 855 G7 Notebook PC/1E1EB0F59677/RHEL-9/5.14.0-162.23.1.EL9_1.X86_64/X86_64/6E086EC096>) |
| 045e:070f | Microsoft        | LifeChat LX-3000 Headset             | 98    | snd_usb... | [BBFE51BF3C](<Notebook/Dell/Inspiron/Inspiron 7460/AA5879F9E476/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/BBFE51BF3C>) |
| 0d8c:0103 | C-Media Elect... | CM102-A+/102S+ Audio Controller      | 96    | snd_usb... | [53C03D6942](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427/FEDORA-37/6.0.11-300.FC37.X86_64/X86_64/53C03D6942>) |
| 046d:0a4d | Logitech         | G430 Surround Sound Gaming Headset   | 89    | snd_usb... | [7A8B075B23](<Notebook/Lenovo/ThinkPad/ThinkPad T470s 20HGS07D04/ADEC7ECCA727/FEDORA-38/6.2.8-300.FC38.X86_64/X86_64/7A8B075B23>) |
| 0b0e:245e | GN Netcom        | Jabra Link 370                       | 88    | snd_usb... | [8D3458BFF6](<Notebook/Dell/Latitude/Latitude 5531/CA4BEE6F3C34/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/8D3458BFF6>) |
| 1395:0025 | Sennheiser Co... | Headset [PC 8]                       | 87    | snd_usb... | [EF98A330E6](<Notebook/HUAWEI/BOD-WXX/BOD-WXX9/1D0AAA445015/UBUNTU-22.04/5.15.0-50-GENERIC/X86_64/EF98A330E6>) |
| 046d:0a66 | Logitech         | [G533 Wireless Headset Dongle]       | 86    | snd_usb... | [8BA78B7B0B](<Desktop/MSI/MS/MS-7816/083D7991B10B/DEBIAN-11/5.18.0-0.DEB11.4-AMD64/X86_64/8BA78B7B0B>) |
| 08bb:2704 | Texas Instrum... | PCM2704 16-bit stereo audio DAC      | 81    | snd_usb... | [47388F4553](<Desktop/Gigabyte Technology/X570S/X570S AORUS PRO AX/82196083E848/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/47388F4553>) |
| 046d:0a45 | Logitech         | 960 Headset                          | 79    | snd_usb... | [69B2B1C95F](<Notebook/Lenovo/ThinkPad/ThinkPad T16 Gen 1 21BVCTO1WW/66F9AC1B9D3A/OPENSUSE-LEAP-15.4/5.14.21-150400.24.60-DEFAULT/X86_64/69B2B1C95F>) |
| 17ef:306f | Lenovo           | ThinkPad Dock USB Audio              | 79    | snd_usb... | [B8A363F717](<Notebook/Lenovo/ThinkPad/ThinkPad T580 20L9CTO1WW/3E2D6C9C7C0A/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/B8A363F717>) |
| 046d:0a38 | Logitech         | Headset H340                         | 77    | snd_usb... | [4E80F798E2](<Desktop/Lenovo/ThinkStation/ThinkStation P330 30CY0075GE/AF0D6FF9A649/DEBIAN-11/5.10.0-22-AMD64/X86_64/4E80F798E2>) |
| 046d:0ab7 | Logitech         | Blue Microphones                     | 75    | snd_usb... | [D7ED216BE7](<All In One/Dell/Inspiron/Inspiron 24 5415 All-in-One/FBE2C11F8067/ARCH-22.10/6.3.1-ARCH1-1/X86_64/D7ED216BE7>) |
| 041e:324d | Creative Tech... | Sound Blaster Play! 3                | 74    | snd_usb... | [8EF63CB2DE](<Server/Dell/PowerEdge/PowerEdge T420/B103D6C87C65/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/8EF63CB2DE>) |
| 046d:0aaa | Logitech         | Logitech G PRO X Gaming Headset      | 71    | snd_usb... | [BFF38BC725](<Desktop/MSI/MS-7/MS-7C13/BF4D7DC0CD18/FEDORA-37/6.2.10-200.FC37.X86_64/X86_64/BFF38BC725>) |
| 046d:0a5b | Logitech         | G933 Wireless Headset Dongle         | 70    | snd_usb... | [CC262BB41A](<Desktop/ASUSTek Computer/Maximus/Maximus VIII HERO ALPHA/0EC9D2353F66/GENTOO-2.9/6.1.3-GENTOO/X86_64/CC262BB41A>) |
| 19f7:0003 | RODE Microphones | RODE NT-USB                          | 70    | snd_usb... | [1EDDB3203A](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3/ARCO-ROLLING/6.3.1-ARCH1-1/X86_64/1EDDB3203A>) |
| 1038:1294 | SteelSeries ApS  | Arctis Pro Wireless                  | 69    | snd_usb... | [6686A91041](<Notebook/Lenovo/ThinkPad/ThinkPad P16 Gen 1 21D6S0AK00/D8C229281AC7/ARCH-ROLLING/6.2.11-ARCH1-1/X86_64/6686A91041>) |
| 08bb:2912 | Texas Instrum... | PCM2912A Audio Codec                 | 67    | snd_usb... | [AEE22EE8B3](<Notebook/Lenovo/ThinkPad/ThinkPad L14 Gen 3 21C6S08E00/CF8153B01241/ENDEAVOUROS-ROLLING/6.2.10-ARCH1-1/X86_64/AEE22EE8B3>) |
| 0951:16df | Kingston Tech... | HyperX QuadCast                      | 66    | snd_usb... | [AD66608CF0](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E039702D1078/CHIMERAOS-41/6.1.21-1-LTS/X86_64/AD66608CF0>) |
| 0b0e:245d | GN Netcom        | Jabra Link 370                       | 66    | snd_usb... | [D71B834A1C](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/4440A0D853F2/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/D71B834A1C>) |
| 1532:0520 | Razer USA        | Kraken Tournament Edition            | 65    | snd_usb... | [C203C197B7](<Desktop/Gigabyte Technology/B660/B660 GAMING X DDR4/EF868DCF63D9/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/C203C197B7>) |
| 047f:02ee | Plantronics      | BT600                                | 62    | snd_usb... | [AA81655AF9](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 SFF/6C84003478A6/LINUXMINT-21.1/5.15.0-70-GENERIC/X86_64/AA81655AF9>) |
| 1b1c:0a14 | Corsair          | VOID PRO Wireless Gaming Headset     | 62    | snd_usb... | [96FCC41161](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/84DCE5E974C7/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/96FCC41161>) |
| 054c:0ce6 | Sony             | DualSense wireless controller (PS5)  | 57    | snd_usb... | [AA2AF0A4BC](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/94E45CAB4EE0/GENTOO-2.13/6.1.19-GENTOO/X86_64/AA2AF0A4BC>) |

### Touchpad (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 06cb:2970 | Synaptics        | touchpad                             | 105   | usbhid     | [AB9FF23D88](<Notebook/Acer/Aspire/Aspire E5-551G/0D9CCBBE9BDD/KDE-NEON-22.04/5.19.0-41-GENERIC/X86_64/AB9FF23D88>) |
| 044e:1218 | Alps Electric    | Touchpad                             | 49    | usbhid     | [2DE1D6F6F5](<Tablet/Dell/Latitude/Latitude 7210 2-in-1/7A5FB94B1DE2/ARCH-ROLLING/6.2.12-ZEN1-1-ZEN/X86_64/2DE1D6F6F5>) |
| 044e:120d | Alps Electric    | Touchpad                             | 27    | usbhid     | [20DCC3E6B3](<Notebook/Hewlett-Packard/Elite/Elite x2 1012 G1/14194E554C93/BLENDOS/6.2.13-ARCH1-1/X86_64/20DCC3E6B3>) |
| 044e:1216 | Alps Electric    | Touchpad                             | 16    | usbhid     | [DBBCF4A29A](<Tablet/Hewlett-Packard/Elite/Elite x2 1012 G2/5C54BEB47475/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/DBBCF4A29A>) |
| 06cb:0009 | Synaptics        | Composite TouchPad and TrackPoint    | 13    | synapti... | [2EBBAA4052](<Desktop/Medion/Pentino_H-Series/Pentino_H-Series A_SFF_B85-2/D4682A095B48/DEBIAN-11/5.10.0-16-AMD64/X86_64/2EBBAA4052>) |
| 044e:120f | Alps Electric    | Touchpad                             | 10    | usbhid     | [D1A55F8F55](<Notebook/Dell/Latitude/Latitude 7275/26FF484E6CF5/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/D1A55F8F55>) |
| 044e:1217 | Alps Electric    | Touchpad                             | 9     | usbhid     | [6ECC8F0BAD](<Tablet/Hewlett-Packard/Pro/Pro x2 612 G2/7A82B39E3BAF/FEDORA-37/6.1.15-200.FC37.X86_64/X86_64/6ECC8F0BAD>) |
| 17ef:6046 | Lenovo           | Wireless Touchpad K5923              | 8     | usbhid     | [7C3751C888](<Desktop/SiYW/V200/V200 Series/D5C3940B70A3/LMDE-5/5.10.0-21-AMD64/X86_64/7C3751C888>) |
| 0488:0280 | Cirque           | 9925 AG Touchpad                     | 7     | usbhid     | [1E76ECBAA7](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/82CCFF03A0EE/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/1E76ECBAA7>) |
| 06cb:7af9 | Synaptics        | HIDUSB TouchPad V07                  | 6     | usbhid     | [0C480BD74D](<Notebook/Hewlett-Packard/Spectre/Spectre x2 Detachable/DE3E1A668214/DEBIAN-11/5.10.0-19-AMD64/X86_64/0C480BD74D>) |
| 044e:1221 | Alps Electric    | Touchpad                             | 5     | usbhid     | [E8D1866113](<Tablet/Hewlett-Packard/Elite/Elite x2 1013 G3/AC04F34CD8CA/DEBIAN/6.0.0-5-AMD64/X86_64/E8D1866113>) |
| 06cb:5710 | Synaptics        | SynapticsTouch Pad V 1.03U3          | 5     | usbhid     | [FBB6D3B97E](<Notebook/Hewlett-Packard/Pavilion/Pavilion 13 x2 PC/BC1B8877ECE1/UBUNTU-20.04/5.13.0-40-GENERIC/X86_64/FBB6D3B97E>) |
| 044e:1210 | Alps Electric    | Touchpad                             | 4     | usbhid     | [E2E7D9CE38](<Tablet/Dell/Latitude/Latitude 5179/597547DCB08C/POP!_OS-21.10/5.16.11-76051611-GENERIC/X86_64/E2E7D9CE38>) |
| 04b4:fef3 | Cypress Semic... | KingSon TouchPad                     | 3     | usbhid     | [0B79772DFA](<Desktop/Hewlett-Packard/KT541AA-UUB/KT541AA-UUB a6528hk/E860C4C6D9E4/LUBUNTU-18.04/4.15.0-147-GENERIC/X86_64/0B79772DFA>) |
| 06cb:5711 | Synaptics        | Touch Pad V 103u9                    | 3     | usbhid     | [9B67243691](<Notebook/Hewlett-Packard/Spectre/Spectre 13 x2 PC/A094F6311BEA/UBUNTU-22.04/5.15.0-33-GENERIC/X86_64/9B67243691>) |
| 06cb:0096 | Synaptics        | HIDUSB TouchPad V01                  | 2     | usbhid     | [7D44E4C760](<Tablet/Acer/Switch/Switch SW512-52/9061A4CB688E/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/7D44E4C760>) |
| 0488:8010 | Cirque           | 9925 AG Touchpad                     | 1     | usbhid     | [1498A5A5A4](<Desktop/System76/Thelio/Thelio/28033514E7BA/POP!_OS-20.04/5.4.0-7642-GENERIC/X86_64/1498A5A5A4>) |
| 062a:19b5 | MosArt Semico... | TouchPad                             | 1     | usbhid     | [61BB547684](<Desktop/ASUSTek Computer/B150/B150M-A/0034453C1345/UBUNTU-18.04/4.18.0-17-GENERIC/X86_64/61BB547684>) |
| 06cb:0001 | Synaptics        | TouchPad                             | 1     | synapti... | [7023DC94DA](<Notebook/Packard Bell/EasyNote/EasyNote ME69BMP/C61580A9F1CA/UBUNTU-MATE-20.04/5.4.0-31-GENERIC/X86_64/7023DC94DA>) |
| 06cb:7d29 | Synaptics        | HIDUSB TouchPad V03                  | 1     | usbhid     | [49A6D8DEC1](<Notebook/Hewlett-Packard/Pavilion/Pavilion x2 Detachable/EFCCF32E3904/MANJARO-21.0.5/5.10.36-2-MANJARO/X86_64/49A6D8DEC1>) |
| 258a:0010 | HAILUCK          | PTP TouchPad                         | 1     | usbhid     | [C8932DBFD0](<Desktop/Gigabyte Technology/X570/X570 AORUS ULTRA/A25B28905CE4/POP!_OS-21.10/5.15.11-76051511-GENERIC/X86_64/C8932DBFD0>) |
| 413c:2507 | Dell             | TP713 Wireless Touchpad              | 1     | usbhid     | [8A10AE7D58](<Desktop/ASUSTek Computer/M3N78/M3N78 PRO/CF3804C072FE/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/8A10AE7D58>) |

### Touchscreen (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0eef:0001 | D-WAV Scientific | Titan6001 Surface Acoustic Wave T... | 86    | usbhid     | [EAAC4C0BA0](<Desktop/Gigabyte Technology/Z97/Z97X-UD3H/4229EE8F4975/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/EAAC4C0BA0>) |
| 04f3:20d0 | Elan Microele... | Touchscreen                          | 76    | usbhid     | [AEA99797DB](<Notebook/Dell/XPS/XPS 13 9350/3325F203BE29/UBUNTU-22.10/5.19.0-38-GENERIC/X86_64/AEA99797DB>) |
| 04f3:2494 | Elan Microele... | Touchscreen                          | 58    | usbhid     | [BCB18AE818](<Notebook/Dell/Inspiron/Inspiron 13-5378/33A319DBE008/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/BCB18AE818>) |
| 04f3:250e | Elan Microele... | Touchscreen                          | 58    | usbhid     | [C40DAC306C](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bs2xx/57FC92AABA1F/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/C40DAC306C>) |
| 0408:3008 | Quanta           | OpticalTouchScreen                   | 51    | usbhid     | [EB106FA5D3](<All In One/Dell/Inspiron/Inspiron One 2310/E46F3B774446/BLACKPANTHER-OS-18.1/4.18.16-DESKTOP-1BP/X86_64/EB106FA5D3>) |
| 04f3:24a0 | Elan Microele... | Touchscreen                          | 37    | usbhid     | [644110C9B9](<Notebook/Dell/XPS/XPS 15 9560/165115A732D9/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/644110C9B9>) |
| 04f3:21d5 | Elan Microele... | Touchscreen                          | 31    | usbhid     | [200495D065](<Notebook/Dell/XPS/XPS 15 9550/84DF32A0C12B/FEDORA-37/6.1.9-200.FC37.X86_64/X86_64/200495D065>) |
| 04f3:0254 | Elan Microele... | Touchscreen                          | 30    | usbhid     | [54CDA388D8](<Notebook/Lenovo/ThinkPad/ThinkPad S1 Yoga 20CD0034TX/B0C143E9A04A/PARDUS-21.4/5.10.0-21-AMD64/X86_64/54CDA388D8>) |
| 04f3:24a1 | Elan Microele... | Touchscreen                          | 30    | usbhid     | [15160B0649](<Notebook/Dell/XPS/XPS 15 9560/B1C9C12E2484/ZORIN-16/5.15.0-71-GENERIC/X86_64/15160B0649>) |
| 04f3:010c | Elan Microele... | Touchscreen                          | 29    | usbhid     | [BB5D069D90](<Notebook/ASUSTek Computer/N550/N550JK/6171A3B82D37/LINUXMINT-20.3/5.4.0-144-GENERIC/X86_64/BB5D069D90>) |
| 04f3:2234 | Elan Microele... | Touchscreen                          | 29    | usbhid     | [95B5E79487](<Notebook/Dell/XPS/XPS 13 9350/B4B9DEF2E77F/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/95B5E79487>) |
| 04f3:289b | Elan Microele... | Touchscreen                          | 28    | usbhid     | [F7CE1B2AB5](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20S1S6D700/AD37D345A569/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F7CE1B2AB5>) |
| 04f3:2acc | Elan Microele... | Touchscreen                          | 26    | usbhid     | [4B20311834](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y10002GE/2D4E011B7C6E/FEDORA-37/6.1.14-200.FC37.X86_64/X86_64/4B20311834>) |
| 04f3:012d | Elan Microele... | Touchscreen                          | 25    | usbhid     | [8FDE9CAB5C](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 3rd 20BS00AFMS/C0C4059F899F/KALI-2022.4/6.0.0-KALI6-AMD64/X86_64/8FDE9CAB5C>) |
| 04f3:016f | Elan Microele... | Touchscreen                          | 25    | usbhid     | [F762C7CC29](<Notebook/Lenovo/Yoga/Yoga 2 Pro 20266/6BCDE944F53A/DEBIAN-12/6.1.0-6-AMD64/X86_64/F762C7CC29>) |
| 04f3:000a | Elan Microele... | Touchscreen                          | 24    | usbhid     | [89B64BBFB6](<Notebook/Lenovo/IdeaPad/IdeaPad Yoga 13 20175/D099EB54717B/GENTOO-2.13/6.2.11-ZEN1/X86_64/89B64BBFB6>) |
| 04f3:0085 | Elan Microele... | Touchscreen                          | 24    | usbhid     | [A2E6CAE633](<Notebook/Acer/Aspire/Aspire V5-572P/69B0259FCB51/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/A2E6CAE633>) |
| 04f3:0141 | Elan Microele... | Touchscreen                          | 24    | usbhid     | [7F0E2D07B5](<Notebook/Toshiba/dynabook/dynabook T653-46JR/C908DEB9E731/OPENMANDRIVA-23.03/6.1.1-DESKTOP-1OMV2290/X86_64/7F0E2D07B5>) |
| 04f3:2013 | Elan Microele... | Touchscreen                          | 24    | usbhid     | [9DEDE41C5D](<Notebook/Dell/Inspiron/Inspiron 5547/F963A5B4B905/UBUNTU-22.10/5.19.0-26-GENERIC/X86_64/9DEDE41C5D>) |
| 1926:0003 | NextWindow       | 1900 HID Touchscreen                 | 22    | usbhid     | [0FDCF4A5BC](<Desktop/Hewlett-Packard/NY456AA-ABG/NY456AA-ABG IQ545a/6CF0E7D5FE06/DEBIAN-11/6.0.0-0.DEB11.6-AMD64/X86_64/0FDCF4A5BC>) |
| 1926:0006 | NextWindow       | 1950 HID Touchscreen                 | 22    | usbhid     | [60C37E2DDA](<Desktop/Hewlett-Packard/WC731AA-ABU/WC731AA-ABU 300-1115uk/A117BFF4209E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/60C37E2DDA>) |
| 04f3:2398 | Elan Microele... | Touchscreen                          | 21    | usbhid     | [1259BB0006](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L50003GE/F2AB22C90A04/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/1259BB0006>) |
| 04f3:2753 | Elan Microele... | Touchscreen                          | 21    | usbhid     | [EADF220620](<Notebook/Hewlett-Packard/Laptop/Laptop 15-dy2xxx/37E785AA7973/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/EADF220620>) |
| 04f3:0042 | Elan Microele... | Touchscreen                          | 19    | usbhid     | [971055139B](<Notebook/Dell/Inspiron/Inspiron 5537/32BC57718864/DEBIAN-11/5.10.0-21-AMD64/X86_64/971055139B>) |
| 04f3:0224 | Elan Microele... | Touchscreen                          | 19    | usbhid     | [A2E7B3B9B7](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS2V900/B99B8A154155/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.1.8-1-DEFAULT/X86_64/A2E7B3B9B7>) |
| 04f3:2012 | Elan Microele... | Touchscreen                          | 18    | usbhid     | [42908A7AB7](<Notebook/Dell/Inspiron/Inspiron 5548/63FAE252421C/ARCO-ROLLING/6.1.25-1-LTS/X86_64/42908A7AB7>) |
| 04f3:034e | Elan Microele... | Touchscreen                          | 17    | usbhid     | [686DB926DA](<Notebook/Dell/Inspiron/Inspiron 3542/5A79260B6BED/NOBARA-37/6.1.11-201.FSYNC.FC37.X86_64/X86_64/686DB926DA>) |
| 04f3:0034 | Elan Microele... | Touchscreen                          | 16    | usbhid     | [7890BF1C68](<Notebook/Dell/Inspiron/Inspiron 3537/8563BC1F0E9A/CLEAR-LINUX-OS-38280/6.1.12-1265.NATIVE/X86_64/7890BF1C68>) |
| 04f3:22c3 | Elan Microele... | Touchscreen                          | 15    | usbhid     | [4A502B4E1D](<Notebook/Hewlett-Packard/15/15 Notebook PC/85E24F5BD92F/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/4A502B4E1D>) |
| 04f3:2337 | Elan Microele... | Touchscreen                          | 15    | usbhid     | [6B1D418929](<Notebook/Dell/Inspiron/Inspiron 11-3168/A0DB417F38A1/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/6B1D418929>) |
| 04f3:24e1 | Elan Microele... | Touchscreen                          | 15    | usbhid     | [56D14A3B3F](<Convertible/Dell/Latitude/Latitude 3390 2-in-1/85C1EF097337/ARCH-ROLLING/6.0.6-ARCH1-1/X86_64/56D14A3B3F>) |
| 04f3:0023 | Elan Microele... | Touchscreen                          | 14    | usbhid     | [2BB77BE32B](<Notebook/Acer/Aspire/Aspire V5-571P/0D263D3267F2/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/2BB77BE32B>) |
| 04f3:0303 | Elan Microele... | Touchscreen                          | 14    | usbhid     | [895F57E6D5](<Notebook/Lenovo/Yoga/Yoga 2 13 20344/A5FC70135937/ZORIN-16/5.15.0-69-GENERIC/X86_64/895F57E6D5>) |
| 04f3:036e | Elan Microele... | Touchscreen                          | 14    | usbhid     | [2E537D8CDA](<Notebook/Dell/Inspiron/Inspiron 11 - 3147/21CEEFE297B4/UBUNTU-22.04/5.19.0-40-GENERIC/X86_64/2E537D8CDA>) |
| 04f3:2070 | Elan Microele... | Touchscreen                          | 14    | usbhid     | [A695D92FBC](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible/FFE9A8B1E2C9/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/A695D92FBC>) |
| 04f3:2497 | Elan Microele... | Touchscreen                          | 14    | usbhid     | [F5717FC896](<Notebook/Dell/Inspiron/Inspiron 17-7779/B6FE2AA991F6/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/F5717FC896>) |
| 04e7:0020 | Elo TouchSystems | Touchscreen Interface (2700)         | 13    | usbhid     | [D9DB201F72](<Desktop/Hewlett-Packard/t620/t620 Dual Core TC/50EBB30C9211/KALI-2023.1/6.1.0-KALI7-AMD64/X86_64/D9DB201F72>) |
| 04f3:0439 | Elan Microele... | Touchscreen                          | 13    | usbhid     | [C1B400B6E6](<Notebook/Hewlett-Packard/ENVY/ENVY 15/61605D120326/UBUNTU-22.04/5.15.0-58-GENERIC/X86_64/C1B400B6E6>) |
| 04f3:2793 | Elan Microele... | Touchscreen                          | 13    | usbhid     | [3E71E40BA0](<Notebook/Hewlett-Packard/Laptop/Laptop 17-by2xxx/62677864CA4A/UBUNTU-22.04/5.15.0-48-GENERIC/X86_64/3E71E40BA0>) |
| 04f3:2884 | Elan Microele... | Touchscreen                          | 13    | usbhid     | [80BD0AED09](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20S1S4RB26/DC73B66255B2/ARCH-ROLLING/6.2.9-ARCH1-1/X86_64/80BD0AED09>) |
| 1926:0dbe | NextWindow       | Touchscreen                          | 13    | usbhid     | [13355A7D07](<Desktop/Hewlett-Packard/520/520-1030a/1B9A1B44E7E8/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/13355A7D07>) |
| 04f3:002a | Elan Microele... | Touchscreen                          | 12    | usbhid     | [3E3F5AC9AB](<Notebook/Dell/Latitude/Latitude 3440/9D94A609D686/LINUXMINT-21/5.15.0-46-GENERIC/X86_64/3E3F5AC9AB>) |
| 04f3:0206 | Elan Microele... | Touchscreen                          | 12    | usbhid     | [4206AF54DD](<Notebook/Dell/Inspiron/Inspiron 7537/95D8D98992A1/KDE-NEON-22.04/5.19.0-35-GENERIC/X86_64/4206AF54DD>) |
| 04f3:228a | Elan Microele... | Touchscreen                          | 12    | usbhid     | [5EBCBA8C52](<Notebook/Dell/Inspiron/Inspiron 13-7353/41DE680BA56C/POP!_OS-22.04/6.0.12-76060006-GENERIC/X86_64/5EBCBA8C52>) |
| 04f3:22ed | Elan Microele... | Touchscreen                          | 12    | usbhid     | [7A8B075B23](<Notebook/Lenovo/ThinkPad/ThinkPad T470s 20HGS07D04/ADEC7ECCA727/FEDORA-38/6.2.8-300.FC38.X86_64/X86_64/7A8B075B23>) |
| 04f3:0135 | Elan Microele... | Touchscreen                          | 11    | usbhid     | [BFBA694531](<Notebook/Lenovo/ThinkPad/ThinkPad T440 20B7S0JC0K/2E67539CCAB1/ENDEAVOUROS-ROLLING/6.2.8-ARCH1-1/X86_64/BFBA694531>) |
| 04f3:034f | Elan Microele... | Touchscreen                          | 11    | usbhid     | [FF88BCBAFC](<Notebook/Dell/Inspiron/Inspiron 5547/FDED89F5D36F/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/FF88BCBAFC>) |
| 04f3:0389 | Elan Microele... | Touchscreen                          | 11    | usbhid     | [DD68B81B43](<Notebook/Acer/Aspire/Aspire E5-571P/435FEB50DDB8/ZORIN-16/5.13.0-35-GENERIC/X86_64/DD68B81B43>) |
| 04f3:038a | Elan Microele... | Touchscreen                          | 11    | usbhid     | [5C4E966FDA](<Notebook/Hewlett-Packard/15/15 TS Notebook PC/44DCB5710755/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/5C4E966FDA>) |
| 04f3:2033 | Elan Microele... | Touchscreen                          | 11    | usbhid     | [5D6E6F5C03](<Notebook/Dell/Inspiron/Inspiron 7348/F7C9472E8241/UBUNTU-22.04/5.15.0-41-GENERIC/X86_64/5D6E6F5C03>) |

### Tv card (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 046d:0892 | Logitech         | C920 HD Pro Webcam                   | 343   | gspca_v... | [C6DBE0270A](<Desktop/Alienware/Aurora/Aurora R8/32367D40A9B5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/C6DBE0270A>) |
| 1415:2000 | Nam Tai E&E P... | Sony Playstation Eye                 | 131   | gspca_o... | [03C6B8486E](<Desktop/Dell/OptiPlex/OptiPlex 755/F8A80185DE25/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/03C6B8486E>) |
| 0402:5602 | ALi              | M5602 Video Camera Controller        | 111   | gspca_m... | [449779FBE4](<Notebook/Fujitsu Siemens/AMILO/AMILO Pa 2548/4436EB48BD16/UBUNTU-22.04/5.19.0-42-GENERIC/X86_64/449779FBE4>) |
| 046d:08d7 | Logitech         | QuickCam Communicate STX             | 64    | gspca_z... | [3CDF8244EF](<Desktop/Acer/Aspire/Aspire M5811/BD71CFB0AF65/UBUNTU-22.10/5.19.0-40-GENERIC/X86_64/3CDF8244EF>) |
| 045e:00f7 | Microsoft        | LifeCam VX-1000                      | 63    | gspca_s... | [C8D5686C80](<Desktop/Biostar/H61/H61MHB/850396312344/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/C8D5686C80>) |
| 0ac8:303b | Z-Star Microe... | ZC0303 Webcam                        | 60    | gspca_z... | [6B554016FE](<Desktop/Fujitsu/D3220/D3220-A1/3CF0BA605B2C/DEBIAN-11/5.10.0-9-AMD64/X86_64/6B554016FE>) |
| 093a:2620 | Pixart Imaging   | TV Card                              | 54    | gspca_p... | [89A7F8F7E7](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/FE51A60992A1/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/89A7F8F7E7>) |
| 046d:0896 | Logitech         | OrbiCam                              | 44    | gspca_v... | [B4B7EBE3F9](<Notebook/Acer/Aspire/Aspire 5680/3B586D5A849D/LINUXMINT-21.1/5.15.0-58-GENERIC/X86_64/B4B7EBE3F9>) |
| 045e:00f5 | Microsoft        | LifeCam VX-3000                      | 43    | gspca_s... | [E3BA0EF4B7](<Desktop/Dell/Precision/Precision T1700/D4CDABBDFD25/KALI-2022.4/6.0.0-KALI6-AMD64/X86_64/E3BA0EF4B7>) |
| 046d:08da | Logitech         | QuickCam Messanger                   | 42    | gspca_z... | [E2ED275252](<Desktop/Kraftway/GEG/GEG/82E4CDAE7890/RED-OS-7.3.2/5.15.87-1.EL7.3.X86_64/X86_64/E2ED275252>) |
| 05e1:0501 | Syntek           | DC-1125 Webcam                       | 35    | stkwebcam  | [E561213582](<Notebook/ASUSTek Computer/F3/F3JP/357DFA9B9E6F/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/E561213582>) |
| 0ac8:305b | Z-Star Microe... | ZC0305 Webcam                        | 34    | gspca_z... | [86B607E7D4](<Desktop/ASUSTek Computer/PRIME/PRIME X670-P WIFI/EBDEB86FD0FB/DEBIAN-11/6.1.20-BOOTES0-P-1000/X86_64/86B607E7D4>) |
| 093a:2468 | Pixart Imaging   | SoC PC-Camera                        | 31    | gspca_p... | [94F2408A63](<Desktop/Others/RS780/RS780-SB700/9EA5FE457EA9/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/94F2408A63>) |
| 174f:a311 | Syntek           | 1.3MPixel Web Cam - Asus A3A, A6J... | 30    | stkwebcam  | [3828D5841D](<Notebook/ASUSTek Computer/A7/A7U/7DD35B7A8A79/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/3828D5841D>) |
| 046d:089d | Logitech         | QuickCam E2500 series                | 27    | gspca_z... | [781DC9DA09](<Desktop/Gigabyte Technology/B450M/B450M DS3H V2/0DE166143AE6/FEDORA-37/6.1.9-200.FC37.X86_64/X86_64/781DC9DA09>) |
| 093a:2622 | Pixart Imaging   | Webcam Genius                        | 27    | gspca_p... | [97F08BD689](<Desktop/Gigabyte Technology/Z87/Z87-HD3/B6044F413AD0/MANJARO/5.15.85-1-MANJARO/X86_64/97F08BD689>) |
| 046d:08d9 | Logitech         | QuickCam IM/Connect                  | 26    | gspca_z... | [415B7CE80B](<Desktop/Gigabyte Technology/X299/X299 AORUS Ultra Gaming Pro/FD0816A73C61/ARCO-ROLLING/6.2.10-ARCH1-1/X86_64/415B7CE80B>) |
| 093a:262c | Pixart Imaging   | TV Card                              | 24    | gspca_p... | [57E3CFA7DC](<Desktop/ASUSTek Computer/P5/P5Q/5FA3807D02EE/ZORIN-16/5.15.0-58-GENERIC/X86_64/57E3CFA7DC>) |
| 046d:08ad | Logitech         | QuickCam Communicate STX             | 23    | gspca_z... | [9B39BC4979](<System On Chip/Rockchip/Orange/Orange Pi 5/5E1E10BA1F21/UBUNTU-22.04/5.10.110-ROCKCHIP-RK3588/AARCH64/9B39BC4979>) |
| 046d:08af | Logitech         | QuickCam Easy/Cool                   | 20    | gspca_z... | [0CF17A3787](<Desktop/Intel/DG41RQ/DG41RQ AAE54511-205/0AD8C224D5D2/OPENMANDRIVA-23.90/6.2.1-DESKTOP-1OMV2390/X86_64/0CF17A3787>) |
| 0c45:624f | Microdia         | PC Camera (SN9C201 + OV9650)         | 19    | gspca_s... | [9711AB00D7](<Desktop/Dell/OptiPlex/OptiPlex GX280/64A7BC440B20/LINUXMINT-19.3/5.4.0-120-GENERIC/I686/9711AB00D7>) |
| 045e:00f4 | Microsoft        | LifeCam VX-6000 (SN9C20x + OV9650)   | 17    | gspca_s... | [FDFF0F112E](<Desktop/Gigabyte Technology/H410M/H410M S2 V3/92DC52D7628E/ZORIN-16/5.15.0-69-GENERIC/X86_64/FDFF0F112E>) |
| 093a:2624 | Pixart Imaging   | Webcam                               | 16    | gspca_p... | [76F456D63A](<Desktop/Gigabyte Technology/H61/H61M-S2PV/E4D3A86B7420/UBUNTU-22.04/5.19.0-35-GENERIC/X86_64/76F456D63A>) |
| 0ac8:307b | Z-Star Microe... | USB 1.1 Webcam                       | 16    | gspca_z... | [FE19BB609E](<Desktop/ASRock/G41/G41M-VS3/DB5E3A2D033D/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/FE19BB609E>) |
| 093a:2460 | Pixart Imaging   | Q-TEC WEBCAM 100                     | 15    | gspca_p... | [82E5831486](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 USDT/50EEBCB45CF8/UBUNTU-23.04/6.1.0-16-GENERIC/X86_64/82E5831486>) |
| 046d:08f0 | Logitech         | QuickCam Messenger                   | 14    | gspca_s... | [9F1F002F51](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Dash F15 FX516PR_FX516PR/99651CC9DCC8/UBUNTU-20.04/5.15.0-1021-INTEL-IOTG/X86_64/9F1F002F51>) |
| 2040:7200 | Hauppauge        | WinTV HVR-950                        | 14    | au0828     | [AB7B403321](<Desktop/Apple/MacPro3/MacPro3,1/3212D6A73605/UBUNTU-18.04/5.4.0-1472304060810-GENERIC/X86_64/AB7B403321>) |
| 046d:092e | Logitech         | QuickCam Chat                        | 13    | gspca_s... | [0DA080327F](<Desktop/ASRock/Z77/Z77 Extreme3/7F778DC75AC8/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/0DA080327F>) |
| 0ac8:301b | Z-Star Microe... | ZC0301 Webcam                        | 13    | gspca_z... | [A49F180F2D](<Desktop/Dell/OptiPlex/OptiPlex 9010/CBCA418BC5E3/LINUXMINT-21/5.15.0-52-GENERIC/X86_64/A49F180F2D>) |
| 041e:4052 | Creative Tech... | Live! Cam Vista IM                   | 12    | gspca_o... | [592ADC6C9B](<Desktop/ASRock/970/970 Pro3 R2.0/7F752E3C441C/ZORIN-16/5.15.0-48-GENERIC/X86_64/592ADC6C9B>) |
| 046d:08a2 | Logitech         | Labtec Webcam Pro                    | 12    | gspca_z... | [8C0A201199](<Desktop/ASUSTek Computer/P5Q/P5Q Premium/C394E5A30DBE/LINUXMINT-19.3/5.4.0-125-GENERIC/X86_64/8C0A201199>) |
| 093a:2621 | Pixart Imaging   | PAC731x Trust Webcam                 | 12    | gspca_p... | [84C21454EF](<Notebook/Lenovo/G500/G500 20236/E38CAE785FC1/LINUXMINT-20.3/5.13.0-40-GENERIC/X86_64/84C21454EF>) |
| 046d:092f | Logitech         | QuickCam Express Plus                | 11    | gspca_s... | [9DB352CE8B](<Desktop/MSI/MS/MS-7808/1006D1F0FF52/LINUXMINT-20.3/5.4.0-131-GENERIC/X86_64/9DB352CE8B>) |
| 093a:2476 | Pixart Imaging   | CIF Single Chip                      | 11    | gspca_p... | [182A43F2B4](<Desktop/ASRock/B450M/B450M Pro4-F/598B7B6ADAF4/UBUNTU-UNITY-16.04/4.15.0-142-GENERIC/I686/182A43F2B4>) |
| 093a:2626 | Pixart Imaging   | TV Card                              | 11    | gspca_p... | [CAAA97E4BA](<Desktop/Dell/OptiPlex/OptiPlex 790/D7A067995CA5/UBUNTU-22.10/5.19.0-35-GENERIC/X86_64/CAAA97E4BA>) |
| 0ac8:c002 | Z-Star Microe... | Visual Communication Camera VGP-VCC1 | 11    | gspca_v... | [C59F41ADB7](<Notebook/Sony/VGN-FE/VGN-FE770G/220BCC93A928/UBUNTU-22.04/5.15.0-53-GENERIC/X86_64/C59F41ADB7>) |
| 0471:0329 | Philips (or NXP) | SPC 900NC PC Camera / ORITE CCD W... | 10    | pwc        | [4CF17A7B6F](<Desktop/ASUSTek Computer/P5/P5K/9E9721D3E8DA/LINUXMINT-21/5.15.0-47-GENERIC/X86_64/4CF17A7B6F>) |
| 093a:2600 | Pixart Imaging   | Typhoon Easycam USB 330K (newer)/... | 10    | gspca_p... | [43113791E9](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH Z77/0574AA0E4D8C/KUBUNTU-20.04/5.15.0-67-GENERIC/X86_64/43113791E9>) |
| 0c45:608f | Microdia         | PC Camera (SN9C103 + OV7630)         | 10    | gspca_s... | [53EB92EFDA](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570w/EAD0172784FA/DEBIAN-11/5.10.0-20-AMD64/X86_64/53EB92EFDA>) |
| 054c:0155 | Sony             | Eyetoy Video Device                  | 9     | gspca_o... | [E89DA96576](<Desktop/ASRock/Z77/Z77 Extreme3/7F778DC75AC8/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/E89DA96576>) |
| 0c45:600d | Microdia         | TwinkleCam USB camera                | 9     | gspca_s... | [88B38DA161](<Desktop/Hewlett-Packard/Compaq/Compaq 8000 Elite SFF PC/AEC664318F67/FEDORA-36/5.18.10-200.FC36.X86_64/X86_64/88B38DA161>) |
| 0c45:6242 | Microdia         | PC Camera (SN9C201 + MI1310)         | 9     | gspca_s... | [2718026D03](<Notebook/Dell/Latitude/Latitude E7270/05D8BF3D5FBC/FEDORA-37/6.1.13-200.FC37.X86_64/X86_64/2718026D03>) |
| 0c45:6270 | Microdia         | PC Camera (SN9C201 + MI0360/MT9V0... | 9     | gspca_s... | [69B7C755DC](<Desktop/Gigabyte Technology/A320/A320M-S2H/76B725B9BC0A/UBUNTU-20.04/5.4.0-31-GENERIC/X86_64/69B7C755DC>) |
| 0c45:627b | Microdia         | PC Camera (SN9C201 + OV7660)         | 9     | gspca_s... | [5AA66EDD35](<Notebook/Lenovo/ThinkPad/ThinkPad Z61m 9450HAG/1A58B3BE609F/LMDE-5/5.10.0-21-AMD64/X86_64/5AA66EDD35>) |
| 2304:021a | Pinnacle Systems | Dazzle DVC100 Audio Device           | 9     | em28xx     | [8CEF4990B1](<All In One/Apple/iMac11/iMac11,1/A1F81C1485BF/UBUNTU-22.04/5.15.0-25-GENERIC/X86_64/8CEF4990B1>) |
| 046d:0870 | Logitech         | QuickCam Express                     | 8     | gspca_s... | [E46A95080D](<Desktop/Dell/OptiPlex/OptiPlex 760/6C5D94E39079/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/E46A95080D>) |
| 046d:0928 | Logitech         | QuickCam Express                     | 8     | gspca_s... | [B796AC9A1D](<Desktop/Gigabyte Technology/Z87/Z87N-WIFI/25C51BD2977E/MANJARO/6.1.1-1-MANJARO/X86_64/B796AC9A1D>) |
| 0c45:6007 | Microdia         | VideoCAM Eye                         | 8     | gspca_s... | [AB5CE36275](<Notebook/Dell/Latitude/Latitude E5400/BDE40F600FE3/ARCO-ROLLING/5.4.181-1-LTS54/X86_64/AB5CE36275>) |
| 0c45:613c | Microdia         | PC Camera (SN9C120)                  | 8     | gspca_s... | [C0E43C3894](<Desktop/Gateway/SX/SX2370/254EAB8BCC08/UBUNTU-20.04/5.15.0-67-GENERIC/X86_64/C0E43C3894>) |
| eb1a:2861 | eMPIA Technology | EasyCAP DC60+ [EM2861]               | 8     | em28xx     | [3AADACEFE7](<Notebook/Medion/P/P6816/8C2A7CA83972/XERO-ROLLING/6.0.8-ARCH1-1/X86_64/3AADACEFE7>) |

### Ups (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 051d:0002 | American Powe... | Uninterruptible Power Supply         | 741   | usbhid     | [A702DF382B](<Desktop/ASRock/J4125/J4125M/BD0FBF639942/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/A702DF382B>) |
| 0764:0501 | Cyber Power S... | CP1500 AVR UPS                       | 323   | usbhid     | [9430B8C328](<Desktop/Gigabyte Technology/X570/X570 GAMING X/856FFDCD7D13/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.3.1-1-VANILLA/X86_64/9430B8C328>) |
| 0463:ffff | MGE UPS Systems  | UPS                                  | 94    | usbhid     | [15B900CF50](<Desktop/MSI/MS-7/MS-7C37/1B2BC2C59BBA/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/15B900CF50>) |
| 0764:0601 | Cyber Power S... | PR1500LCDRT2U UPS                    | 59    | usbhid     | [A3A13C5CB1](<Notebook/Acer/Aspire/Aspire A515-56/A458F4254BB5/LMDE-5/6.1.0-0.DEB11.5-AMD64/X86_64/A3A13C5CB1>) |
| 051d:0003 | American Powe... | UPS                                  | 41    | usbhid     | [7673380766](<Desktop/Gigabyte Technology/Z690/Z690 AERO G/65E936DD740C/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/7673380766>) |
| 0d9f:0004 | Powercom         | HID UPS Battery                      | 36    | usbhid     | [7E864DC271](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/B34915A36C85/ROSA-12.3/5.15.79-GENERIC-1ROSA2021.1-X86_64/X86_64/7E864DC271>) |
| 06da:ffff | Phoenixtec Power | Offline UPS                          | 20    | usbhid     | [7CF5E54F5B](<Desktop/AZW/Speed/Speed S/245412618F03/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/7CF5E54F5B>) |
| 06da:0003 | Phoenixtec Power | 1300VA UPS                           | 12    | usbhid     | [0FA5809533](<Desktop/ASUSTek Computer/M3A32-MVP/M3A32-MVP DELUXE/4391053EDDEA/DEBIAN/6.0.0-6-AMD64/X86_64/0FA5809533>) |
| 0925:1234 | Lakeview Rese... | UPS USB MON V1.4                     | 11    | usbhid     | [D64F06FD5A](<Desktop/Gigabyte Technology/B460/B460MD3H/7746545E9850/LINUXMINT-20.3/5.4.0-96-GENERIC/X86_64/D64F06FD5A>) |
| 09ae:3016 | Tripp Lite       | UPS                                  | 8     | usbhid     | [1ABE023ED7](<Server/Dell/PowerEdge/PowerEdge R630/0354475C3BDD/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/1ABE023ED7>) |
| 0d9f:00a2 | Powercom         | Imperial Uninterruptible Power Su... | 7     | usbhid     | [F2AE77CC0C](<Desktop/Gigabyte Technology/970/970A-D3/8EA984CA40B2/RED-OS-7.3.1/5.15.35-1.EL7.3.X86_64/X86_64/F2AE77CC0C>) |
| 0d9f:00a6 | Powercom         | Black Knight PRO Uninterruptible ... | 5     | usbhid     | [982BF94727](<Desktop/MSI/MS/MS-7816/C8523EA1567E/UBUNTU-22.04/5.15.0-56-GENERIC/X86_64/982BF94727>) |
| 0592:0002 | Powerware        | UPS (X-Slot)                         | 4     | usbfs      | [9F255EB7D5](<Desktop/Gigabyte Technology/H170/H170-D3H/DC58DF777DE6/MAGEIA-8/5.17.4-DESKTOP-2.MGA8/X86_64/9F255EB7D5>) |
| 0d9f:00a3 | Powercom         | Smart King PRO Uninterruptible Po... | 4     | usbhid     | [89CC93BB0F](<Server/Supermicro/Super/Super Server/1751A0B4EDAF/DEBIAN-9/4.15.18-15-PVE/X86_64/89CC93BB0F>) |
| 0d9f:00a4 | Powercom         | WOW Uninterruptible Power Supply ... | 3     | usbhid     | [0C982DF6CC](<Desktop/MSI/MS-7/MS-7C37/73B8B020B62C/KDE-NEON-20.04/5.4.0-64-GENERIC/X86_64/0C982DF6CC>) |
| 05dd:a011 | Delta Electro... | MINUTEMAN UPS                        | 2     | usbhid     | [1BAE5B1DC6](<Desktop/ASUSTek Computer/Z170/Z170 PRO GAMING/35E5770AE57B/UBUNTU-19.10/5.3.0-21-GENERIC/X86_64/1BAE5B1DC6>) |
| 09ae:2012 | Tripp Lite       | UPS                                  | 2     | usbhid     | [8D6C4235C3](<Desktop/ASUSTek Computer/P8/P8Z68-V/11E74299D197/UBUNTU-18.04/4.15.0-66-GENERIC/X86_64/8D6C4235C3>) |
| 09ae:4004 | Tripp Lite       | UPS                                  | 2     | usbfs      | [8D400B49F8](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/SLACKWARE-15.0/5.15.19/X86_64/8D400B49F8>) |
| 10af:0001 | Liebert          | PowerSure PSA UPS                    | 2     | usbhid     | [6EC1762E12](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ULTRA/AA0705BC8FAC/DEBIAN-11/5.10.0-22-AMD64/X86_64/6EC1762E12>) |
| 03f0:1fe1 | Hewlett-Packard  | T750 G2 UPS                          | 1     | usbhid     | [EA89B6E705](<Server/Supermicro/H8/H8SGL/4B37E516C354/UBUNTU-20.04/5.13.0-41-GENERIC/X86_64/EA89B6E705>) |
| 03f0:1fe2 | Hewlett-Packard  | T1000 G3 UPS                         | 1     | usbhid     | [19AE174CC7](<Desktop/ECS/Z77/Z77H2-A4/4A995FDCC7F9/UBUNTU-18.04/4.18.0-25-GENERIC/X86_64/19AE174CC7>) |
| 0403:e520 | Future Techno... | ECO Pro Series UPS                   | 1     | ftdi_sio   | [E599511F33](<Desktop/MSI/MS-7/MS-7B79/0E28B9FF4F84/UBUNTU-20.04/5.4.0-91-GENERIC/X86_64/E599511F33>) |
| 050d:0751 | Belkin Compon... | Belkin UPS                           | 1     | usbhid     | [E4FDAFF878](<Desktop/ASUSTek Computer/M2/M2A-VM/81D7E88C664A/UBUNTU-21.04/5.11.0-18-GENERIC/X86_64/E4FDAFF878>) |
| 06da:0002 | Phoenixtec Power | UPS                                  | 1     |            | [4F5E89A87E](<Desktop/Gigabyte Technology/Z77/Z77X-D3H/B6558AB4A76F/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/4F5E89A87E>) |
| 09ae:2007 | Tripp Lite       | UPS                                  | 1     | usbhid     | [213D0D1A6A](<Mini Pc/AZW/S/S5/83D15A1076CE/UBUNTU-UNITY-22.04/5.15.0-58-GENERIC/X86_64/213D0D1A6A>) |
| 09ae:2010 | Tripp Lite       | UPS                                  | 1     | usbhid     | [5D1A48EE4E](<Desktop/ASUSTek Computer/P9X79/P9X79 WS/920162AF2BF5/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/5D1A48EE4E>) |
| 10af:0002 | Liebert          | PowerSure PST UPS                    | 1     | usbhid     | [4B47FACE39](<Desktop/Dell/XPS/XPS 8940/5D168DFC0C61/OPENSUSE-LEAP-15.4/5.14.21-150400.24.46-DEFAULT/X86_64/4B47FACE39>) |

### Video (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0fd9:0066 | Elgato Systems   | Cam Link 4K                          | 25    | snd_usb... | [A17449F761](<Desktop/ASRock/X670E/X670E Pro RS/F993F20C9215/GENTOO-2.13/6.3.1-GENTOO-X86_64/X86_64/A17449F761>) |
| 048d:9006 | Integrated Te... | IT9135 BDA Afatech DVB-T HDTV Dongle | 19    | dvb_usb... | [83603A9AA8](<Mini Pc/AZW/GTR/GTR/C2116ED1D5B5/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/83603A9AA8>) |
| 0fd9:006a | Elgato Systems   | Game Capture HD60 S+                 | 8     | snd_usb... | [DC91C0E32B](<Desktop/Gigabyte Technology/X570/X570 AORUS ELITE WIFI/98F5CA9A5522/NOBARA-37/6.1.9-200.FSYNC.FC37.X86_64/X86_64/DC91C0E32B>) |
| 1164:1ee9 | YUAN High-Tec... | Polaris AV Capture                   | 5     |            | [7600B0715D](<Desktop/ASUSTek Computer/ET2311/ET2311I/EC5E10BE0E58/UBUNTU-20.04/5.11.0-37-GENERIC/X86_64/7600B0715D>) |
| 2304:0224 | Pinnacle Systems | Pinnacle High Speed USB Device       | 5     |            | [8BA917619E](<Desktop/Dell/Inspiron/Inspiron 580/EC96A893ADA2/UBUNTU-20.04/5.13.0-35-GENERIC/X86_64/8BA917619E>) |
| 0fd9:0067 | Elgato Systems   | Cam Link 4K                          | 4     | snd_usb... | [A545753206](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/669DE5FA5731/ARCO-ROLLING/6.1.10-ARCH1-1/X86_64/A545753206>) |
| 0fd9:0051 | Elgato Systems   | GameCapture HD                       | 3     |            | [A381B573F6](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/33CA90A8BB89/MANJARO/5.15.49-1-MANJARO/X86_64/A381B573F6>) |
| 0fd9:0061 | Elgato Systems   | Cam Link                             | 2     | snd_usb... | [9CB7EBEA38](<Notebook/ASUSTek Computer/X580/X580VD/F521653612FB/ARCH-ROLLING/5.16.0-ARCH1-1/X86_64/9CB7EBEA38>) |
| 1b80:a41c | Afatech          | Polaris AV Capture                   | 2     |            | [6DE34F58AF](<Notebook/Toshiba/PORTEGE/PORTEGE M800/79DF89B29C5F/FEDORA-33/5.9.16-200.FC33.X86_64/X86_64/6DE34F58AF>) |
| 04b4:00f9 | Cypress Semic... | Ninja Dock                           | 1     | usbhid     | [79FA3F7509](<Notebook/Lenovo/ThinkPad/ThinkPad P15v Gen 1 20TQ004JAU/244A0ACE6641/UBUNTU-20.04/5.8.0-53-GENERIC/X86_64/79FA3F7509>) |
| 0fd9:0062 | Elgato Systems   | Cam Link                             | 1     | snd_usb... | [D0234C90FB](<Notebook/Lenovo/G50-80/G50-80 80E5/2F41BB9D338F/UBUNTU-18.04/4.18.0-25-GENERIC/X86_64/D0234C90FB>) |
| 0fd9:006b | Elgato Systems   | Game Capture HD60 S+                 | 1     | snd_usb... | [C530BF4283](<Desktop/ASRock/Z790/Z790 Pro RS WiFi/1B282C00B785/FEDORA-37/6.1.10-200.FC37.X86_64/X86_64/C530BF4283>) |
| 5555:3382 | Epiphan Systems  | VGA2USB Frame Grabber                | 1     |            | [37A831391B](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv8/D8B9EB76B074/ROSA-2014.1/3.14.25-NRJ-DESKTOP-1ROSA/X86_64/37A831391B>) |

### Webcam (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 145f:013c | Trust            | Multimedia audio controller          | 3     | gspca_p... | [B85703D1E4](<Desktop/MSI/MS/MS-7387/66739E36F2FF/XUBUNTU-18.04/4.15.0-102-GENERIC/X86_64/B85703D1E4>) |

### Wireless (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 2717:ff88 | Xiaomi           | Mi/Redmi series (RNDIS + ADB)        | 169   | rndis_host | [CB89261339](<Notebook/Hewlett-Packard/Notebook/Notebook/FD7F08CB1AA2/UBUNTU-22.04/5.15.0-71-GENERIC/X86_64/CB89261339>) |
| 22b8:2e25 | Motorola PCS     | Moto G (4)                           | 86    | rndis_host | [DCF5CD4CA2](<Desktop/ASRock/N68C-GS/N68C-GS FX/CD0566A64BB2/FEDORA-37/6.2.14-200.FC37.X86_64/X86_64/DCF5CD4CA2>) |
| 2a70:9024 | OnePlus Techn... | OnePlus                              | 33    | rndis_host | [83A1144BE6](<Notebook/Lenovo/ThinkPad/ThinkPad T430s 23539MU/F938DF83613C/KUBUNTU-22.04/5.19.0-40-GENERIC/X86_64/83A1144BE6>) |
| 18d1:4ee4 | Google           | Nexus/Pixel Device (tether+ debug)   | 31    | rndis_host | [140992E52D](<Tablet/Acer/One/One S1003/B46527D9300A/ARCH-ROLLING/6.1.8-ARCH1-1/X86_64/140992E52D>) |
| 22d9:2766 | OPPO Electronics | RMX2180                              | 25    | rndis_host | [D7951530F0](<Notebook/Dell/Vostro/Vostro 1550/546687CC85F9/PARROT-5.2/6.0.0-12PARROT1-AMD64/X86_64/D7951530F0>) |
| 12d1:1039 | Huawei Techno... | Ideos (tethering mode)               | 15    | rndis_host | [E3921E4DA9](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/0DD93308AFFF/ROSA-2016.1/5.4.83-GENERIC-2ROSA-X86_64/X86_64/E3921E4DA9>) |
| 0489:e0a6 | Foxconn / Hon... | Android                              | 11    | rndis_host | [CA8DCD489C](<Desktop/HCL Infosystems Limited/HCL/HCL Desktop/5231B2B389D0/UBUNTU-20.04/5.4.0-58-GENERIC/X86_64/CA8DCD489C>) |
| 1286:4e31 | Marvell Semic... | Mobile Composite Device Bus          | 11    | rndis_host | [B6DB5398BF](<Desktop/ASUSTek Computer/H110/H110M-K/EA15435D666F/ROSA-12.4/6.1.20-GENERIC-2ROSA2021.1-X86_64/X86_64/B6DB5398BF>) |
| 2d95:6ffa | vivo             | 1808                                 | 11    | rndis_host | [6A6E2F88F4](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK S6420/DD2F4B64F47D/OPENMANDRIVA-4.3/5.16.7-DESKTOP-1OMV4003/X86_64/6A6E2F88F4>) |
| 05c6:f626 | Qualcomm         | MDM9207-MTP _SN:F91BE809             | 7     | rndis_host | [21091D13E4](<Desktop/MSI/MS-7/MS-7B86/A8F7FD200798/LINUXMINT-21.1/5.15.0-69-GENERIC/X86_64/21091D13E4>) |
| 0b05:7775 | ASUSTek Computer | Zenfone GO (ZB500KL) (Debug, RNDI... | 6     | rndis_host | [3EB97735B3](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-E/B7890276AAFC/FEDORA-36/5.18.6-200.FC36.X86_64/X86_64/3EB97735B3>) |
| 0b05:7782 | ASUSTek Computer | Android                              | 6     | rndis_host | [A56935A751](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/04C8222C212F/FEDORA-34/5.13.7-200.FC34.X86_64/X86_64/A56935A751>) |
| 12d1:107c | Huawei Techno... | Android                              | 6     | rndis_host | [C1273267FF](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da1xxx/DE7D849D0D82/UBUNTU-18.04/5.0.0-23-GENERIC/X86_64/C1273267FF>) |
| 2d95:600b | Android          | Android                              | 6     | rndis_host | [7077A00B02](<Notebook/Apple/MacBook5/MacBook5,1/14A8ECA4D8C4/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/7077A00B02>) |
| 05c6:90b6 | Qualcomm         | Android                              | 4     | rndis_host | [5384DE4DF1](<Mini Pc/Apple/Macmini7/Macmini7,1/21F3151F07F5/UBUNTU-22.04/5.15.0-52-GENERIC/X86_64/5384DE4DF1>) |
| 0fce:720c | Sony Ericsson... | XQ-CC54                              | 4     | rndis_host | [57CC389EFF](<Desktop/Gigabyte Technology/X670/X670 GAMING X AX/B7E5D7EDD611/ARCH-ROLLING/6.2.10-ARCH1-1/X86_64/57CC389EFF>) |
| 17ef:7c4b | Lenovo           | TB-X606F                             | 4     | rndis_host | [CCEAB9EF33](<Desktop/MSI/MS-7/MS-7D45/ECCD99322122/OPENMANDRIVA-23.01/6.1.2-DESKTOP-1OMV2301/X86_64/CCEAB9EF33>) |
| 2d95:6ffb | vivo             | 1819                                 | 4     | rndis_host | [A8D131CD6A](<Notebook/AVITA/NS14/NS14A8/D91E6488D9FA/KALI-2021.2/5.5.0-KALI2-AMD64/X86_64/A8D131CD6A>) |
| 04b7:88d4 | Compal Electr... | Android                              | 3     | rndis_host | [F6981692E0](<Notebook/Hewlett-Packard/Compaq/Compaq Presario CQ60/D18C7E8FE301/PEPPERMINT-11.4/5.10.0-16-AMD64/X86_64/F6981692E0>) |
| 0fce:71e8 | Sony Ericsson... | F5321                                | 3     | rndis_host | [AF750ADD66](<Desktop/MSI/MS/MS-7641/44EB926CF9CA/LINUXMINT-21/5.15.0-48-GENERIC/X86_64/AF750ADD66>) |
| 0fce:720d | Sony Ericsson... | SO-52B                               | 3     | rndis_host | [F20E47B9D7](<Notebook/HUAWEI/KLVL-WXXW/KLVL-WXXW/BA4846205BC0/OPENSUSE-TUMBLEWEED-XXXXXXXX/6.1.8-1-DEFAULT/X86_64/F20E47B9D7>) |
| 12d1:2607 | Huawei Techno... | HUAWEI                               | 3     | rndis_host | [DCC1CCB590](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-408/59A86BD4C203/LINUXMINT-19.3/5.4.0-80-GENERIC/X86_64/DCC1CCB590>) |
| 15a9:003a | Gemtek           | Modem YOTA 4G LTE                    | 3     | rndis_host | [99F2FBC2FE](<Notebook/Hewlett-Packard/Pavilion/Pavilion 15/1A52BA85F4D8/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/99F2FBC2FE>) |
| 17ef:782f | Lenovo           | Lenovo                               | 3     | rndis_host | [0504CFE362](<Notebook/Toshiba/Satellite/Satellite L30/BA7F43548DE3/LUBUNTU-16.04/4.15.0-122-GENERIC/I686/0504CFE362>) |
| 0b05:5603 | ASUSTek Computer | Android                              | 2     | rndis_host | [1B15A2E740](<Notebook/Hewlett-Packard/Pavilion/Pavilion 14/302DBD34E065/KUBUNTU-20.04/5.13.0-37-GENERIC/X86_64/1B15A2E740>) |
| 0bb4:0ffc | HTC (High Tec... | Android Phone                        | 2     | rndis_host | [ACC6C85624](<Notebook/Hewlett-Packard/ZBook/ZBook 15 G3/E1C27D8F48C8/OPENSUSE-TUMBLEWEED-XXXXXXXX/5.8.4-1-DEFAULT/X86_64/ACC6C85624>) |
| 0fce:71aa | Sony Ericsson... | D2303                                | 2     | rndis_host | [0014DBBEAD](<Desktop/Intel/X79/X79 (INTEL Xeon E5-Corei7 DMI2 - C600-C200 Cipset V3.5B/48D01368F3D2/MANJARO-20.1/5.8.3-2-MANJARO/X86_64/0014DBBEAD>) |
| 0fce:71f3 | Sony Ericsson... | G8341                                | 2     | rndis_host | [4A196739F5](<Notebook/Quanta/TW9/TW9-SW9/18DFD7183CFC/PARROT-5.1/6.0.0-12PARROT1-AMD64/X86_64/4A196739F5>) |
| 0fce:71fa | Sony Ericsson... | H8216                                | 2     | rndis_host | [6BF9D537A8](<Notebook/Lenovo/ThinkPad/ThinkPad E595 20NFCTO1WW/41CBB9C71701/PARROT-4.8/5.4.0-4PARROT1-AMD64/X86_64/6BF9D537A8>) |
| 0fce:81f1 | Sony Ericsson... | Android                              | 2     | rndis_host | [020ABF67F6](<Notebook/Valve/Jupiter/Jupiter/1DB741DB6B2C/STEAMOS-3.4.4/5.13.0-VALVE36-1-NEPTUNE/X86_64/020ABF67F6>) |
| 109b:5d20 | Hisense          | Spreadtrum Phone                     | 2     | rndis_host | [0B0D4DD23F](<Notebook/Lenovo/ThinkPad/ThinkPad T410 25376B8/485335904AC5/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/0B0D4DD23F>) |
| 1271:0541 | Android          | Android                              | 2     | rndis_host | [0C8768F146](<Desktop/Gigabyte Technology/F2/F2A68HM-S1/09717554DC82/ROSA-2016.1/4.9.20-NRJ-DESKTOP-1ROSA-X86_64/X86_64/0C8768F146>) |
| 15a9:0046 | Gemtek           | 4G Modem                             | 2     | rndis_host | [196C8EB317](<Server/Neousys Technology/Nuvo-7100VTC/Nuvo-7100VTC Series/E44E3E216941/UBUNTU-20.04/5.15.0-56-GENERIC/X86_64/196C8EB317>) |
| 1949:2005 | Lab126           | KFKAWI                               | 2     | rndis_host | [0792D1E257](<Convertible/GPU Company/GWTC116/GWTC116-2/2DF22BFE2434/UBUNTU-22.04/5.15.0-60-GENERIC/X86_64/0792D1E257>) |
| 19d2:1611 | ZTE WCDMA Tec... | Yota Router                          | 2     | rndis_host | [2EF180BAD0](<Desktop/ASRock/H310/H310CM-DVS/AF0955483602/ROSA-12.3/6.1.20-GENERIC-1ROSA2021.1-X86_64/X86_64/2EF180BAD0>) |
| 1bbb:9024 | T & A Mobile ... | QM215-QRD _SN:6B7D8716               | 2     | rndis_host | [835B5AF3C7](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X515DA_M515DA/485BB370257C/KALI-2022.2/5.15.0-KALI3-AMD64/X86_64/835B5AF3C7>) |
| 1ecb:02e2 | AMTelecom        | JMR1140                              | 2     | rndis_host | [7F0F38DC4D](<Notebook/Hewlett-Packard/15/15/877B5258AEB7/UBUNTU-20.04/5.13.0-30-GENERIC/X86_64/7F0F38DC4D>) |
| 216f:0044 | Altair Semico... | Alt38XX devboard                     | 2     | rndis_host | [92A7F0EA0B](<Desktop/ASUSTek Computer/Rampage/Rampage IV EXTREME/C4FC1BD7B711/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-X86_64/X86_64/92A7F0EA0B>) |
| 271d:3004 | SPA Condor El... | Allure M1                            | 2     | rndis_host | [B4EF87DE2D](<Desktop/ECS/P4/P4M900T-M2/156C90BAB416/UBUNTU-19.10/5.3.0-55-GENERIC/X86_64/B4EF87DE2D>) |
| 2a45:0004 | Meizu            | 18                                   | 2     | rndis_host | [8382D0F8EB](<Notebook/Apple/MacBookPro15/MacBookPro15,1/DE6E12D84876/UBUNTU-22.04/5.15.0-59-GENERIC/X86_64/8382D0F8EB>) |
| 0421:06eb | Nokia Mobile ... | Nokia_X (RM-980)                     | 1     | rndis_host | [E8E340D720](<Notebook/Lenovo/B50-45/B50-45 20388/5432CBE9F415/OPENMANDRIVA-4.2/5.10.14-DESKTOP-1OMV4002/X86_64/E8E340D720>) |
| 0421:0704 | Nokia Mobile ... | Nokia_X2 (RM-1013)                   | 1     | rndis_host | [2762E434EB](<Desktop/MSI/MS/MS-7309/B75258124D4D/ROSA-2016.1/4.9.124-NRJ-DESKTOP-1ROSA-X86_64/X86_64/2762E434EB>) |
| 0471:2005 | Philips (or NXP) | X586                                 | 1     | rndis_host | [84A631B3D1](<Desktop/MSI/MS/MS-7592/0E8A5F8510C0/ROSA-2016.1/4.15.0-DESKTOP-45.1ROSA-I586/I686/84A631B3D1>) |
| 04b7:88f5 | Compal Electr... | S62 Pro                              | 1     | rndis_host | [5A875DEF3F](<Desktop/Compaq/NQ890AA-ABZ/NQ890AA-ABZ CQ5011IT/5F601F01E4E8/UBUNTU-22.04/5.19.0-38-GENERIC/X86_64/5A875DEF3F>) |
| 04b7:88f6 | Compal Electr... | S62 Pro                              | 1     | rndis_host | [64CFF39A82](<Desktop/ASUSTek Computer/ROG/ROG STRIX X670E-F GAMING WIFI/77A86E60A328/MANJARO-22.0.0/6.0.8-1-MANJARO/X86_64/64CFF39A82>) |
| 04dd:97f2 | Sharp            | SH05F                                | 1     | rndis_host | [B10FE6845E](<Notebook/Acer/Aspire/Aspire 4740/C3BF1BF6536E/UBUNTU-18.04/4.15.0-65-LOWLATENCY/X86_64/B10FE6845E>) |
| 0502:3950 | Acer             | B3-A40                               | 1     | rndis_host | [75EF8688A2](<All In One/Acer/Aspire/Aspire ZC-606/7E3C8CE0B8C9/LINUXMINT-19.3/5.4.0-96-GENERIC/X86_64/75EF8688A2>) |
| 05c6:0a02 | Qualcomm         | Jolla C                              | 1     | rndis_host | [A08DCFFB5A](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-0xxx/A7BE62182FA3/UBUNTU-18.04/4.15.0-72-GENERIC/X86_64/A08DCFFB5A>) |
| 05c6:902d | Qualcomm         | Android                              | 1     | rndis_host | [E6C85F7E85](<Notebook/Dell/Latitude/Latitude E6510/88F57FBE8570/UBUNTU-20.04/5.4.0-42-GENERIC/X86_64/E6C85F7E85>) |
| 05c6:90b4 | Qualcomm         | Android                              | 1     | rndis_host | [76621DA580](<Notebook/Lenovo/IdeaPad/IdeaPad 1 15ADA7 82R1/F3E908B9B977/ENDLESS-5.0.0/5.15.0-47-GENERIC/X86_64/76621DA580>) |

### Xbox (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 045e:0289 | Microsoft        | Xbox Controller S                    | 5     | xpad       | [F39178BEFB](<Desktop/ASUSTek Computer/G11/G11CD/FFE6696AAF3C/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/F39178BEFB>) |
| 045e:0285 | Microsoft        | Xbox Controller S                    | 1     | usbfs      | [3B240B1EF9](<Desktop/Gigabyte Technology/H61/H61M-S2PV/CA33710088DF/DEBIAN-TESTING/5.7.0-1-AMD64/X86_64/3B240B1EF9>) |
| 0c12:880a | Zeroplus         | Pelican Eclipse PL-2023              | 1     |            | [C5BABDFD30](<Notebook/Lenovo/ThinkPad/ThinkPad T420s 4174EK3/9DE5DCA43A62/LINUXMINT-20/5.4.0-48-GENERIC/X86_64/C5BABDFD30>) |
| 0e4c:3510 | Radica Games     | Gamester for Xbox                    | 1     | xpad       | [933234F294](<Desktop/Dell/Precision/Precision T3600/05AC24D0BC52/MANJARO/5.10.70-1-MANJARO/X86_64/933234F294>) |

### Others (USB)

| ID        | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0b05:18f3 | ASUSTek Computer | AURA LED Controller                  | 1228  | usbhid     | [4E424E0AD2](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2E14927B3139/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/4E424E0AD2>) |
| 0b05:1939 | ASUSTek Computer | AURA LED Controller                  | 830   | usbhid     | [DC43E4A7E3](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/1FF7B8E0562A/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/DC43E4A7E3>) |
| 05ac:8300 | Apple            | Built-in iSight (no firmware loaded) | 620   | isight_... | [FCA1201C9F](<Notebook/Apple/MacBook3/MacBook3,1/25DC47FCD4CF/LINUXMINT-21.1/5.15.0-71-GENERIC/X86_64/FCA1201C9F>) |
| 0b05:19af | ASUSTek Computer | AURA LED Controller                  | 594   | usbhid     | [401DB07B93](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D/DEBIAN-12/6.1.0-7-AMD64/X86_64/401DB07B93>) |
| 27c6:538d | Shenzhen Good... | FingerPrint                          | 512   | usbfs      | [B7BF9F8683](<Notebook/Dell/Inspiron/Inspiron 3501/B976DA6E21D9/ZORIN-16/5.15.0-52-GENERIC/X86_64/B7BF9F8683>) |
| 04f3:0c4b | Elan Microele... | ELAN:Fingerprint                     | 358   | usbfs      | [30581D3BEF](<Notebook/Lenovo/ThinkBook/ThinkBook 16p Gen 2 20YM/391EED81DBAB/ROSA-12.4/5.15.103-GENERIC-1ROSA2021.1-X86_64/X86_64/30581D3BEF>) |
| 2109:0102 | VIA Labs         | USB 2.0 BILLBOARD                    | 274   |            | [D3DE6B6B31](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ee1xxx/EEC49B509995/ARCO-ROLLING/6.2.13-ARCH1-1/X86_64/D3DE6B6B31>) |
| 27c6:639c | Shenzhen Good... | Goodix USB2.0 MISC                   | 241   | usbfs      | [EA808C2E80](<Notebook/Dell/Inspiron/Inspiron 16 Plus 7620/37910A3DDDFF/ARTIX-ROLLING/6.3.1-ARTIX1-1/X86_64/EA808C2E80>) |
| 27c6:521d | Shenzhen Good... | FingerPrint                          | 233   |            | [0767486BB6](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401IV_GA401IV/FDD83E37A5CE/POP!_OS-22.04/6.3.1-060301-GENERIC/X86_64/0767486BB6>) |
| 04f3:0c4c | Elan Microele... | ELAN:ARM-M4                          | 227   |            | [D3DE6B6B31](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ee1xxx/EEC49B509995/ARCO-ROLLING/6.2.13-ARCH1-1/X86_64/D3DE6B6B31>) |
| 1c7a:0575 | LighTuning Te... | EgisTec EH575                        | 223   |            | [E290126C8D](<Notebook/Acer/Swift/Swift SFX14-41G/EEF938884A7C/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/E290126C8D>) |
| 2109:0100 | VIA Labs         | USB 2.0 BILLBOARD                    | 222   |            | [7C378D88A2](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506IU_FA506IU/EC1EA29D66BA/KALI-2023.1/6.0.0-KALI6-AMD64/X86_64/7C378D88A2>) |
| 27c6:63ac | Shenzhen Good... | Goodix USB2.0 MISC                   | 213   |            | [FBD91068D3](<Notebook/Dell/XPS/XPS 15 9510/9772EE1F1F5B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FBD91068D3>) |
| 04f3:0c6e | Elan Microele... | ELAN:Fingerprint                     | 201   | usbfs      | [3CF83F50F0](<Notebook/ASUSTek Computer/Zenbook/Zenbook UM6702RC_RM6702RC_BM6702RC UM6702RC_UM6702RC/EC57F19586FE/KUBUNTU-23.04/6.3.1-060301-GENERIC/X86_64/3CF83F50F0>) |
| 06cb:00da | Synaptics        | UWP WBDI                             | 197   |            | [AF9591CEDC](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 2 20T60029RT/CF04095B1306/ARCH-ROLLING/6.2.8-ARCH1-1/X86_64/AF9591CEDC>) |
| 04f3:0c4f | Elan Microele... | ELAN:Fingerprint                     | 190   | usbfs      | [9D7736A816](<Notebook/Acer/Aspire/Aspire AV15-51/8F79CD741C6A/DEBIAN-11/5.10.0-21-AMD64/X86_64/9D7736A816>) |
| 1d5c:7102 | Fresco Logic     | Generic Billboard Device             | 154   | fl2000     | [4EA44288B5](<Notebook/Dell/Latitude/Latitude 7370/7819A10CD1AF/PARROT-5.3/6.1.0-1PARROT1-AMD64/X86_64/4EA44288B5>) |
| 2109:0103 | VIA Labs         | USB 2.0 BILLBOARD                    | 140   |            | [DF056EC6F1](<Desktop/ASRock/4X4-4000/4X4-4000 Series/512CE5A79924/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/DF056EC6F1>) |
| 25a4:9311 | USB C            | Video Adaptor                        | 130   |            | [BAC25FA124](<Notebook/Dell/Inspiron/Inspiron 5402/5B106C2A8296/ENDEAVOUROS-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/BAC25FA124>) |
| 06cb:00fc | Synaptics        | UWP WBDI Device                      | 121   | usbfs      | [B734A6D6F3](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon Gen 10 21CBCTO1WW/67B3C459995E/OPENMANDRIVA-23.03/6.2.6-DESKTOP-1OMV2390/X86_64/B734A6D6F3>) |
| 04f3:0c4d | Elan Microele... | ELAN:Fingerprint                     | 118   | usbfs      | [65DDEDBD24](<Notebook/Lenovo/IdeaPad/IdeaPad 5 14ALC05 82LM/DB66F0E66039/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/65DDEDBD24>) |
| 22b8:2e82 | Motorola PCS     | XT1541 [Moto G 3rd Gen]              | 114   | usbfs      | [7F1E3CF271](<Desktop/Gigabyte Technology/GA-990/GA-990FX-GAMING/28A23C2D8B69/OPENMANDRIVA-23.01/6.1.1-DESKTOP-1OMV2290/X86_64/7F1E3CF271>) |
| 27c6:609c | Shenzhen Good... | Goodix USB2.0 MISC                   | 112   | usbfs      | [2509256CEA](<Notebook/Framework/Laptop/Laptop/453CE7B4F380/ARCO-ROLLING/6.3.1-ZEN1-1-ZEN/X86_64/2509256CEA>) |
| 03f0:046b | Hewlett-Packard  | USB-C Dock G5                        | 102   | usbhid     | [6E086EC096](<Notebook/Hewlett-Packard/EliteBook/EliteBook 855 G7 Notebook PC/1E1EB0F59677/RHEL-9/5.14.0-162.23.1.EL9_1.X86_64/X86_64/6E086EC096>) |
| 413c:b080 | Dell             | DA20 Adapter                         | 100   |            | [FBD91068D3](<Notebook/Dell/XPS/XPS 15 9510/9772EE1F1F5B/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/FBD91068D3>) |
| 2433:b200 | ASETEK           | [NZXT Kraken X60]                    | 95    | usbfs      | [C80B811F3E](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-PLUS/666FE60103ED/NOBARA-37/6.2.11-202.FSYNC.FC37.X86_64/X86_64/C80B811F3E>) |
| 2109:8818 | VIA Labs         | USB Billboard Device                 | 91    |            | [7BBDC5E568](<Notebook/Dell/XPS/XPS 13 9300/4E6F55491119/KUBUNTU-22.04/5.15.0-71-GENERIC/X86_64/7BBDC5E568>) |
| 8086:0b63 | Intel            | USB Bridge                           | 90    | ljca       | [B9CFD37540](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon Gen 10 21CBA002CD/668FBAF731C4/UBUNTU-23.04/6.2.0-20-GENERIC/X86_64/B9CFD37540>) |
| 1b1c:0c09 | Corsair          | H100i v2                             | 89    |            | [15B900CF50](<Desktop/MSI/MS-7/MS-7C37/1B2BC2C59BBA/FEDORA-38/6.2.12-300.FC38.X86_64/X86_64/15B900CF50>) |
| 04f3:0c5e | Elan Microele... | ELAN:ARM-M4                          | 86    |            | [DE3AD583AB](<Notebook/Hewlett-Packard/ProBook/ProBook 445 G8 Notebook PC/D2E137A183C8/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/DE3AD583AB>) |
| 0424:2740 | Microchip Tec... | Hub Controller                       | 82    |            | [B7E67F8130](<Server/AMD/Volcano/Volcano/59C634EF9C63/DEBIAN-11/5.10.0-21-AMD64/X86_64/B7E67F8130>) |
| 17e9:6015 | DisplayLink      | ThinkPad Hybrid USB-C with USB-A ... | 82    | snd_usb... | [8A80FD7103](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 3 21AHCTO1WW/3D5B408DCD5C/UBUNTU-BUDGIE-22.04/5.19.0-40-GENERIC/X86_64/8A80FD7103>) |
| 06cb:00d8 | Synaptics        | Synaptics FS7604 Touch Fingerprin... | 74    |            | [C78F20F332](<Notebook/Hewlett-Packard/ProBook/ProBook 445 G7/CF2DAC92FEBB/FEDORA-38/6.2.14-300.FC38.X86_64/X86_64/C78F20F332>) |
| 04f3:0c63 | Elan Microele... | ELAN:Fingerprint                     | 69    |            | [7D642208EC](<Notebook/TUXEDO/Aura/Aura 15 Gen1/AEC2A0DBF7AA/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/7D642208EC>) |
| 27c6:532d | Shenzhen Good... | Fingerprint                          | 66    |            | [0CFE2B34F5](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/5E99B6664C26/BLENDOS/6.2.12-ARCH1-1/X86_64/0CFE2B34F5>) |
| 04f3:0c3d | Elan Microele... | Elan:Fingerprint                     | 65    | usbfs      | [8DB6F88FD3](<Desktop/MSI/MS-7/MS-7B79/86959A8E1FCB/NOBARA-37/6.2.11-202.FSYNC.FC37.X86_64/X86_64/8DB6F88FD3>) |
| 2109:8883 | VIA Labs         | USB Billboard Device                 | 64    |            | [9B013EBF89](<Desktop/Gigabyte Technology/X570/X570 AORUS MASTER/D4AAC9699323/ARCH-ROLLING/6.3.1-ARCH1-1/X86_64/9B013EBF89>) |
| 17e9:4301 | DisplayLink      | USB3 to HDMI                         | 56    | snd_usb... | [9FCB4F708C](<Notebook/Dell/Inspiron/Inspiron 7737/1A6B1F5043D2/BLACKPANTHER-OS-22.1/5.15.85-DESKTOP-1BP/X86_64/9FCB4F708C>) |
| 1b1c:0c13 | Corsair          | H115i Platinum                       | 56    | usbfs      | [F115308631](<Desktop/Gigabyte Technology/X670E/X670E AORUS MASTER/3BF5FA76FD15/LINUXMINT-21.1/6.2.13-060213-GENERIC/X86_64/F115308631>) |
| 10a5:9800 | FPC              | Sensor Controller L:0001 FW:16.26... | 54    |            | [1F2D88BFAE](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 4 21ECS00000/642B185E080D/KUBUNTU-23.04/6.2.0-20-GENERIC/X86_64/1F2D88BFAE>) |
| 28de:2001 | Valve Software   | USB Billboard Device                 | 54    |            | [55ACF244C5](<Notebook/Valve/Jupiter/Jupiter/29ABCFAE75B5/STEAMOS-3.4.6/5.13.0-VALVE36-1-NEPTUNE/X86_64/55ACF244C5>) |
| 0bda:2171 | Realtek Semic... | BillBoard Device                     | 52    |            | [BB189B2507](<Desktop/Micro Computer (HK) Tech Limited/UM/UM690/74269EC20F30/GARUDA-SOARING/6.2.11-ZEN1-1-ZEN/X86_64/BB189B2507>) |
| 1e71:3008 | NZXT             | KrakenZ Device                       | 52    | usbhid     | [5989CC1AC0](<Desktop/ASUSTek Computer/ProArt/ProArt B550-CREATOR/A21E2F18A61D/MANJARO/6.2.12-1-MANJARO/X86_64/5989CC1AC0>) |
| 17ef:3074 | Lenovo           | USB Billboard                        | 50    | usbhid     | [B8A363F717](<Notebook/Lenovo/ThinkPad/ThinkPad T580 20L9CTO1WW/3E2D6C9C7C0A/FEDORA-37/6.2.11-200.FC37.X86_64/X86_64/B8A363F717>) |
| 1b1c:0c08 | Corsair          | H80i v2                              | 50    |            | [9E3F14CF8D](<Desktop/Gigabyte Technology/X99/X99-UD4-CF/0D79DC579ADB/ARCH-ROLLING/6.2.13-ARCH1-1/X86_64/9E3F14CF8D>) |
| 1b1c:0c15 | Corsair          | H100i Platinum                       | 50    | usbfs      | [352A47B8A0](<Desktop/Corsair/VENGEANCE/VENGEANCE 5180/E08B86617521/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/352A47B8A0>) |
| 27c6:6594 | Shenzhen Good... | Goodix USB2.0 MISC                   | 49    | usbfs      | [34420E9478](<Notebook/Lenovo/ThinkPad/ThinkPad P1 Gen 5 21DCCTO1WW/F37505221A04/ARCH-ROLLING/6.2.12-ARCH1-1/X86_64/34420E9478>) |
| 2833:0211 | Oculus VR        | Rift CV1 Sensor                      | 48    | uvcvideo   | [4681975F9D](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C/FEDORA-38/6.2.11-300.FC38.X86_64/X86_64/4681975F9D>) |
| 32ac:0002 | Framework        | HDMI Expansion Card                  | 48    | usbhid     | [78E63B3BD3](<Notebook/Framework/Laptop/Laptop/CA1EEDA4FE48/UBUNTU-22.04/5.19.0-41-GENERIC/X86_64/78E63B3BD3>) |
| 0711:5601 | Magic Control... | T6 USB Station                       | 47    |            | [F8F0F0125F](<Notebook/Dell/Latitude/Latitude 5590/704E1696F0B1/POP!_OS-22.04/6.2.6-76060206-GENERIC/X86_64/F8F0F0125F>) |

