Most popular USB devices in System On Chips
===========================================

See more info in the [README](https://github.com/linuxhw/LsUSB).

Contents
--------

1. [ USB Devices in System On Chips ](#usb-devices)
   * [ Bluetooth ](#bluetooth-usb)
   * [ Camera ](#camera-usb)
   * [ Cdrom ](#cdrom-usb)
   * [ Disk ](#disk-usb)
   * [ Gamepad ](#gamepad-usb)
   * [ Hub ](#hub-usb)
   * [ Human interface ](#human-interface-usb)
   * [ Input/keyboard ](#inputkeyboard-usb)
   * [ Input/mouse ](#inputmouse-usb)
   * [ Net/wireless ](#netwireless-usb)
   * [ Network ](#network-usb)
   * [ Printer ](#printer-usb)
   * [ Serial controller ](#serial-controller-usb)
   * [ Sound ](#sound-usb)
   * [ Touchscreen ](#touchscreen-usb)

USB Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bluetooth (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 8087:0a2b | Intel      | Bluetooth Device             | 2     | btusb      | B301762DE6 |
| 04ca:3015 | Lite-On... | Lite-On Bluetooth Device     | 1     | btusb      | 5E682A0733 |
| 0a12:0001 | Cambrid... | Bluetooth Dongle (HCI mode)  | 1     | btusb      | C72F8C76F7 |
| 8087:0a2a | Intel      | Bluetooth Device             | 1     | btusb      | C72F8C76F7 |

### Camera (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:082d | Logitech   | HD Pro Webcam C920           | 1     | uvcvideo   | 0F6BF93DE7 |

### Cdrom (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 152d:0578 | JMicron... | JMS567 SATA 6Gb/s bridge     | 4     | uas        | 7BF31C69BE |
| 152d:0562 | JMicron... | MK2035GSS                    | 1     | uas        | 97C0D626A3 |
| 152d:2329 | JMicron... | JM20329 SATA Bridge          | 1     | usb_sto... | C9D96D72E1 |

### Disk (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0781:5530 | SanDisk    | Cruzer                       | 1     | usb_sto... | 5E682A0733 |
| 0781:5581 | SanDisk    | Ultra 128GB                  | 1     | uas, us... | D722433AB1 |
| 07ab:fc98 | Freecom... | rive II 250GB                | 1     | usb_sto... | A2AB91716A |
| 0951:16a3 | Kingsto... | DT microDuo 3.0 16GB         | 1     | usb_sto... | 72113080A2 |
| 125f:a76a | A-DATA ... | ADATA ED600 USB Device       | 1     | uas        | C72F8C76F7 |
| 152d:2509 | JMicron... | JMS539 SuperSpeed SATA II... | 1     | usb_sto... | 61DE4E9C89 |
| 154b:f00b | PNY        | PRO ELITE PSSD               | 1     | uas        | AE618F7BCA |
| 174c:0825 | ASMedia... | X825                         | 1     | uas        | 986AF27AB5 |
| 174c:1153 | ASMedia... | ASM2115 SATA 6Gb/s bridge    | 1     | usb_sto... | C9D96D72E1 |
| 174c:5136 | ASMedia... | ASM1053 SATA 6Gb/s bridge    | 1     | usb_sto... | 61DE4E9C89 |
| abcd:1234 | Chipsbnk   | Alu Line 16GB                | 1     | uas, us... | E2D2936DF6 |

### Gamepad (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:028e | Microsoft  | Xbox360 Controller           | 1     | xpad       | BB777A3A5A |

### Hub (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1d6b:0002 | Linux F... | 2.0 root hub                 | 43    | hub        | 7BF31C69BE |
| 1d6b:0003 | Linux F... | 3.0 root hub                 | 21    | hub        | B301762DE6 |
| 2109:3431 | VIA Labs   | USB2.0 Hub                   | 12    | hub        | 401B4E187B |
| 0424:9514 | Standar... | SMC9514 Hub                  | 11    | hub        | 213D7241FD |
| 1d6b:0001 | Linux F... | 1.1 root hub                 | 10    | hub        | 7BF31C69BE |
| 0bda:0411 | Realtek... | 4-Port USB 3.0 Hub           | 6     | hub        | B301762DE6 |
| 0bda:5411 | Realtek... | 4-Port USB 2.0 Hub           | 6     | hub        | B301762DE6 |
| 0424:2514 | Standar... | USB 2.0 Hub                  | 4     | hub        | 66A253B82B |
| 05e3:0608 | Genesys... | USB-2.0 4-Port HUB           | 3     | hub        | C9D96D72E1 |
| 1a40:0101 | incompl... | 4-Port HUB                   | 3     | hub        | 213D7241FD |
| 05e3:0610 | Genesys... | 4-port hub                   | 2     | hub        | C4D5FA2F23 |
| 05e3:0616 | Genesys... | hub                          | 2     | hub        | C4D5FA2F23 |
| 2001:f103 | D-Link     | DUB-H7 7-port USB 2.0 hub    | 1     | hub        | 7A64B606B6 |
| 2109:2811 | VIA Labs   | USB2.0 Hub                   | 1     | hub        | AE618F7BCA |
| 2109:8110 | VIA Labs   | USB 3.0 Hub                  | 1     | hub        | AE618F7BCA |
| 8564:4100 | Transcend  | USB2.0 Hub                   | 1     | hub        | 2BA95DA510 |

### Human interface (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 05ac:055b | Apple      | Gamesir-G3w                  | 1     | usbhid     | C9D96D72E1 |

### Input/keyboard (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 046d:c52b | Logitech   | Unifying Receiver            | 3     | usbhid     | 401B4E187B |
| 046d:c534 | Logitech   | Unifying Receiver            | 2     | usbhid     | C0C7973B78 |
| 0e8f:00a7 | GreenAsia  | 2.4G RX                      | 2     | usbhid     | D722433AB1 |
| 03f0:0024 | Hewlett... | KU-0316 Keyboard             | 1     | usbhid     | FABEFC2647 |
| 03f0:0d4a | Hewlett... | USB Multimedia Keyboard      | 1     | usbhid     | 6700057FD0 |
| 045e:07f8 | Microsoft  | Wired Keyboard 600 (model... | 1     | usbhid     | AE618F7BCA |
| 0461:0010 | Primax ... | HP PR1101U / Primax PMX-K... | 1     | usbhid     | 5E682A0733 |
| 046d:c52e | Logitech   | MK260 Wireless Combo Rece... | 1     | usbhid     | C72F8C76F7 |
| 09da:f613 | A4Tech     | USB Device                   | 1     | usbhid     | C9D96D72E1 |
| 09da:f624 | A4Tech     | USB Device                   | 1     | usbhid     | C9D96D72E1 |
| 0c45:7603 | Microdia   | USB Keyboard                 | 1     | usbhid     | 3EE1EB4EE7 |
| 0c45:7605 | Microdia   | USB Keyboard                 | 1     | usbhid     | D590264685 |
| 17ef:6018 | Lenovo     | Low Profile USB Keyboard     | 1     | usbhid     | EF679BF628 |
| 1997:2433 |            | Mini Keyboard                | 1     | usbhid     | 5DC469AF93 |
| 1a2c:2124 | China R... | USB Keyboard                 | 1     | usbhid     | 7A64B606B6 |
| 1a2c:2d23 | China R... | USB Keyboard                 | 1     | usbhid     | 0F6BF93DE7 |
| 1a2c:4c5e | China R... | USB Keyboard                 | 1     | usbhid     | B301762DE6 |
| 1c4f:0026 | SiGma M... | Keyboard                     | 1     | usbhid     | 2BA95DA510 |
| 258a:0001 | SINO WE... | USB KEYBOARD                 | 1     | usbhid     | EC7B6F39F6 |
| 413c:2005 | Dell       | RT7D50 Keyboard              | 1     | usbhid     | E2D2936DF6 |
| 413c:2113 | Dell       | KB216 Wired Keyboard         | 1     | usbhid     | 213D7241FD |

### Input/mouse (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 03f0:0941 | Hewlett... | X500 USB Optical Mouse       | 1     | usbhid     | 213D7241FD |
| 0451:062b | Texas I... | Gamesir-GK300                | 1     | usbhid     | 9FC908D9A4 |
| 045e:0039 | Microsoft  | IntelliMouse Optical         | 1     | usbhid     | E2D2936DF6 |
| 045e:076c | Microsoft  | Comfort Mouse 4500           | 1     | usbhid     | AE618F7BCA |
| 0461:4d65 | Primax ... | USB Optical Mouse            | 1     | usbhid     | 5E682A0733 |
| 046d:c016 | Logitech   | Optical Wheel Mouse          | 1     | usbhid     | 6700057FD0 |
| 046d:c050 | Logitech   | RX 250 Optical Mouse         | 1     | usbhid     | 2BA95DA510 |
| 046d:c077 | Logitech   | M105 Optical Mouse           | 1     | usbhid     | 7A64B606B6 |
| 093a:2510 | Pixart ... | Optical Mouse                | 1     | usbhid     | 3EE1EB4EE7 |
| 093a:2521 | Pixart ... | Optical Mouse                | 1     | usbhid     | D590264685 |
| 1267:0210 | Logic3 ... | LG Optical Mouse 3D-310      | 1     | usbhid     | EC7B6F39F6 |
| 1915:1028 | Nordic ... | Smart Control                | 1     | usbhid     | 5458E9A8B8 |
| 1c4f:0048 | SiGma M... | Usb Mouse                    | 1     | usbhid     | D722433AB1 |
| 258a:1007 | SINOWEALTH | Game Mouse                   | 1     | usbhid     | B301762DE6 |
| 25a7:fa23 | Compx      | 2.4G Receiver                | 1     | usbhid     | D60186B2B3 |

### Net/wireless (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0a5c:bd1e | Broadcom   | BCM43143 802.11bgn (1x1) ... | 1     | brcmfmac   | 7A64B606B6 |
| 0bda:8179 | Realtek... | RTL8188EUS 802.11n Wirele... | 1     | r8188eu    | 72113080A2 |

### Network (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0424:ec00 | Standar... | SMSC9512/9514 Fast Ethern... | 11    | smsc95xx   | 213D7241FD |
| 0424:7800 | Standar... | Ethernet controller          | 4     | lan78xx    | 66A253B82B |
| 0bda:8153 | Realtek... | RTL8153 Gigabit Ethernet ... | 2     | r8152      | C4D5FA2F23 |
| 0bb4:0003 | HTC (Hi... | Android Incorporated GSM ... | 1     | rndis_host | C72F8C76F7 |
| 0e8d:2005 | MediaTek   | X5max_PRO                    | 1     | rndis_host | 5E682A0733 |
| 1410:b00b | Novatel... | MiFi 5510                    | 1     | rndis_host | 6873B9B896 |

### Printer (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 04f9:0273 | Brother... | DCP-7057 scanner/printer     | 1     | usblp      | 79E8256BFB |

### Serial controller (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 1a86:7523 | QinHeng... | HL-340 USB-Serial adapter    | 1     | ch341      | BF0FF721FB |

### Sound (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 045e:070f | Microsoft  | LifeChat LX-3000 Headset     | 1     | snd_usb... | 3EE1EB4EE7 |

### Touchscreen (USB)

| ID        | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|------------|------------------------------|-------|------------|------------|
| 0eef:0001 | D-WAV S... | eGalax TouchScreen           | 1     | usbhid     | 0F6BF93DE7 |

