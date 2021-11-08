# Hardware Wallets Digital Forensics List
List of Hardware Wallet vendor IDs and Product IDs to be used for Digital Forensics detection.  

The below list may be used for forenscis analysis of a suspect's machine's logs of USB devices connected.  
List is provided as best-effort and is not exhaustive.  


### Vendors and Products Identifiers
Below is a list of Vendor and Product IDs as would be found in USB devices logs.  
Forensics examiners may use this list to identify if such a device has been seen on the suspect's machines.  

| _VID(0x) | _PID(0x) | Vendor name | Device desc. | Attribution URI |
| :------- | :------- | :----------- | :---------- | --------------- |
| 03eb | 2402 | ShiftCrypto  | BitBox01 (DigitalBitBox)   | [shiftcrypto.com](https://shiftcrypto.support/help/en-us/9-troubleshooting/15-usb-connection-issues-my-bitbox02-is-not-detected) |
| 03eb | 2403 | ShiftCrypto  | BitBox02                   | [shiftcrypto.com](https://shiftcrypto.support/help/en-us/9-troubleshooting/15-usb-connection-issues-my-bitbox02-is-not-detected) |
| 096e | 0891 | Feitian Tech | JuBiter Blade              | [Github](https://github.com/search?q=user%3AJubiterWallet+VID&type=code) |
| 1209 | aaaa | Prokey       | Optimum                    | [Github](https://github.com/prokey-io/prokey-optimum-firmware/blob/a0ad6a323a4e51dd1d2d09d7e2786b6f5c65d575/firmware/usb.c) |
| 1209 | abba | Generic      | SafeWISE CoinSafe          | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | b0b0 | Generic      | Monero Hardware bootloader | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | c0dA | Generic      | Monero Hardware            | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | d00d | Generic      | Monero Hardware developer  | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | 53c0 | SatoshiLabs  | Trezor v2 bootloader       | [Github](https://github.com/trezor/trezor-suite/blob/130b17ff0d52b67079d29b4e7250637528be1def/packages/suite-native/android/app/src/main/res/xml/devices.xml) |
| 1209 | 53c1 | SatoshiLabs  | Trezor v2                  | [Github](https://github.com/trezor/trezor-suite/blob/130b17ff0d52b67079d29b4e7250637528be1def/packages/suite-native/android/app/src/main/res/xml/devices.xml) |
| 1209 | 7000 | Secalot      | Secalot Dongle             | [secalot.com/downloads/ HID Rules](https://s3.eu-central-1.amazonaws.com/secalot.com/99-hid.rules) |
| 1209 | 7001 | Secalot      | Secalot Bootloader         | [secalot.com/downloads/ HID Rules](https://s3.eu-central-1.amazonaws.com/secalot.com/99-hid.rules) |
| 1209 | 7551 | Generic      | OpenDime DAFU bootloader   | [Github](https://github.com/opendime/DAFU/blob/master/Makefile) |
| 1209 | 9998 | Opolo        | Cosmos Bootloader          | [pid.codes](https://pid.codes/1209/) |
| 1209 | 9999 | Opolo        | Cosmos Firmware            | [pid.codes](https://pid.codes/1209/) |
| 2341 | 003d | Bitlox       | Ultimate aka lockbox 3A8C  | [Github](https://github.com/BitLox/bitlox-firmware/blob/074f009b5052b3df0c7f562649d393cfaa3e1dd1/.settings/org.eclipse.cdt.core.prefs) |
| 2341 | 003e | Bitlox       | Ultimate aka lockbox       | [Github](https://github.com/BitLox/bitlox-firmware/blob/074f009b5052b3df0c7f562649d393cfaa3e1dd1/.settings/org.eclipse.cdt.core.prefs) |
| 2581 | 1b7c | Ledger       | HW1                        | [Github](https://github.com/LedgerHQ/ledger-starter-iso/blob/b5f02dcf3c7388717a6decdc98afe26a9a54b011/README.md) |
| 2581 | 2b7c | Ledger       | HW1                        | [Github](https://github.com/LedgerHQ/ledger-starter-iso/blob/b5f02dcf3c7388717a6decdc98afe26a9a54b011/README.md) |
| 2581 | 3b7c | Ledger       | HW1                        | [Github](https://github.com/LedgerHQ/ledger-starter-iso/blob/b5f02dcf3c7388717a6decdc98afe26a9a54b011/README.md) |
| 2581 | 4b7c | Ledger       | HW1                        | [Github](https://github.com/LedgerHQ/ledger-starter-iso/blob/b5f02dcf3c7388717a6decdc98afe26a9a54b011/README.md) |
| 2581 | 1807 | Ledger       | HW1                        | [Github](https://github.com/LedgerHQ/ledger-starter-iso/blob/b5f02dcf3c7388717a6decdc98afe26a9a54b011/README.md) |
| 2581 | 1808 | Ledger       | HW1                        | [Github](https://github.com/LedgerHQ/ledger-starter-iso/blob/b5f02dcf3c7388717a6decdc98afe26a9a54b011/README.md) |
| 2b24 | All  | KeepKey      | Bitcoin Wallet             | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 2c97 | All  | Ledger       | Ledger Nano S, X and Blue  | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 2f48 | 2130 | D'CENT       | Biometric Wallet           | [Github](https://github.com/DcentWallet/user-manual/blob/95a219e02c966f05a3d97b03404bef106580df10/biometric-wallet/firmware-update/firmware-trouble-shooting-windows.md) |
| 534c | 0001 | SatoshiLabs  | Trezor v1                  | [Github](https://github.com/trezor/trezor-suite/blob/130b17ff0d52b67079d29b4e7250637528be1def/packages/suite-native/android/app/src/main/res/xml/devices.xml) |
| d13e | cc10 | CoinKite     | ColdCard                   | [Github](https://github.com/Coldcard/firmware/search?q=pid) |


### Missing or further research required
- SafePal Ltd. Officially backed-up by Binance. Product: SFP SafePal S1
- SecuX Technology Inc., Taiwan. Products: W10, W20, V20 Stone
- Opolo Inc., Hong-Kong and Opolo SARL, Luxembourg. Product: Cosmos. May appear as Interbiometrics (_VID 1209 and _PID 0x1000 to 0x1FFF)  
- Ngrave.IO NV, Belgium. Product: Zero. Is air-gapped but does have a USB-C for charging and firmware update.

### Specific no-USB HD Wallets
- Embedded Agency LLC, Canada and USA. Product: Husky HDW20 - This HD Wallet is only using Wifi, including for OTA Firmware update (Over-The-Air)
- Cobo Global Ltd, Cayman Islands. Products: Keystone Essential, Keystone Pro - Cobo Vault is an open source air-gapped HD wallet. It is not using USB (other than for Firmware burning). Cobo Vault uses QRcodes only. Its hardware is based on an ARM Cortex A7. Refer to [Github](https://github.com/CoboVault/cobo-vault-docs/tree/master/hardware)
- Ellipal Ltd., Hong-Kong. Products: EC01 and Titan Cold Wallet. This is an air-gapped wallet. The Firmware update is done via micro SD card inserted in a seperate "security module". The micro-USB port of the security module is only for charging
- C∞lBitX (CoolBitx), Taiwan. Products: CoolWallet S and CoolWallet Pro. These are Bluetooth only cards, uses NFC to charge. CoolBitX is also the creator of the Sygna Bridge, a compliance tool used as a gateway for the exchange and querying of data accross Financial actors
- CoinKite Inc., Canada. Products: OpenDime and ColdCard. Although these are air-gapped cards, the ColdCard Firmware update is done in DFU mode via USB

### Related hardware
- Axell Corporation, Japan. Product: VIPPool Wallet. Sometimes mentioned as "a cold wallet for transfers" but our research tends to show theses are not cold wallets but licensing USB sticks also manufactured by Axell Corporation, Japan as product "[Shalo](https://shalo.jp)". \_VID and \_PID information not found.

### Pictures
The below are images from manufacturer website (links above).
Provided here for examiners who may have to search a scene for exhibits.  
  
| Brand | Model |
| :-------- | :--: |
| NGRAVE | ![NGRAVE Zero Hardware Wallet](Images/NGRAVE-Zero.png) <br/> NGrave Zero |
| LEDGER | ![Ledger HW1](Images/LEDGER-HW1.png) <br/> HW1|
| LEDGER | ![Ledger Nano S](Images/LEDGER-Nano-S.png) <br/> Nano S |
| LEDGER | ![Ledger Nano X](Images/LEDGER-Nano-X.png) <br/> Nano X |
| LEDGER | ![Ledger Nano Blue](Images/LEDGER-Nano-Blue.png) <br/> Nano Blue |
| TREZOR | ![Trezor One](Images/TREZOR-Model-One.png) <br/> Model One |
| TREZOR | ![Trezor T](Images/TREZOR-Model-T.png) <br/> Model T or "v2" |
| SecuX | ![SecuX W10](Images/SECUX-W10.png) <br/> W10 |
| SecuX | ![SecuX W20](Images/SECUX-W20.png) <br/> W20 |
| SecuX | ![SecuX V20](Images/SECUX-V20.png) <br/> V20 Front <br/> ![SecuX V20](Images/SECUX-V20-Back.png) <br/> V20 Back |
| ShapeShift | ![KeepKey](Images/SHAPESHIFT-KeepKey.png) <br/> KeepKey |
| ShiftCrypto | ![BitBox01](Images/SHIFTCRYPTO-Bitbox01.png) <br/> BitBox 01 aka Digital BitBox |
| ShiftCrypto | ![BitBox01](Images/SHIFTCRYPTO-Bitbox02.png) <br/> BitBox 02 |
| CoolBitX | ![CoolWallet S](Images/COOLBITX-Coolwallet-S.png) <br/> CoolWallet S (OKEX branded, but could be Binance and others)|
| CoolBitX | ![CoolWallet Pro](Images/COOLBITX-Coolwallet-Pro.png) <br/> CoolWallet Pro (Crypto.com branded) |
| Cobo Global | ![Cobo Vault Pro and Essential](Images/COBO-Vault-Pro.png) <br/> Cobo Vault Pro and Essential (aka Keystone Pro) |
| Coinkite | ![Coldcard](Images/COINKITE-Coldcard.png) <br/> Coldcard |
| Coinkite | ![OpenDime](Images/COINKITE-OpenDime.png) <br/> OpenDime |
| Ellipal | ![EC01](Images/ELLIPAL-EC01.png) <br/> EC01 |
| Ellipal | ![Titan](Images/ELLIPAL-Titan.png) <br/> Titane |
| Bitlox | ![Ultimate](Images/BITLOX-Ultimate.png) <br/> Ultimate |
| Prokey | ![Optimum](Images/PROKEY-Optimum.png) <br/> Optimum |
| Secalot | ![Dongle](Images/SECALOT-Dongle.png) <br/> Dongle |

### Sources

A list of Hardware wallets is available at [https://en.bitcoin.it](https://en.bitcoin.it/wiki/Hardware_wallet)   
 
Ledger	https://www.ledger.com/  
Trezor	https://trezor.io/  
Keepkey	https://shapeshift.com/keepkey  
BitBox	https://shiftcrypto.ch/  
C∞lWallet (CoolWallet) https://www.coolwallet.io/  
Cobo Vault https://cobo.com/about?locale=en  
Cold Card Wallet https://coldcardwallet.com/  
Ellipal	https://www.ellipal.com/  
JuBiter Blade https://www.ftsafe.com/store/product/cryptocurrency-wallet/  
SafeWize CoinSafe https://safewise.io/#/home  
Husky HDW20 https://www.huskywallet.com  
SFP SafePal https://safepal.io  
D'CENT https://dcentwallet.com  
Cosmos https://opolo.io  
VIPPool Wallet https://www.axell.co.jp  
Zero https://www.ngrave.io  
W10, W20, V20 Stone https://secuxtech.com  
Ultimate https://www.bitlox.com  
Optimum https://prokey.io  
Dongle https://www.secalot.com  