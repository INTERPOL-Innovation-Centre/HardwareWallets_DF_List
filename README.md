# Hardware Wallets Digital Forensics List
List of Hardware Wallet vendor IDs and Product IDs to be used for Digital Forensics detection.  

The below list may be used for forenscis analysis of a suspect's machine's logs of USB devices connected.  
List is provided as best-effort and is not exhaustive.  

| _VID(0x) | _PID(0x) | Vendor desc. | Description | Attribution URI |
| :------- | :------- | :----------- | :---------- | --------------- |
| 03eb | 2402  | ShiftCrypto | BitBox01 (DigitalBitBox)  | [shiftcrypto.com](https://shiftcrypto.support/help/en-us/9-troubleshooting/15-usb-connection-issues-my-bitbox02-is-not-detected) |
| 03eb | 2403  | ShiftCrypto | BitBox02                  | [shiftcrypto.com](https://shiftcrypto.support/help/en-us/9-troubleshooting/15-usb-connection-issues-my-bitbox02-is-not-detected) |
| 096e | 0891 | Feitian Tech | JuBiter Balde              | [Github](https://github.com/search?q=user%3AJubiterWallet+VID&type=code) |
| 1209 | 7551 | Generic      | OpenDime DAFU bootloader   | [Github](https://github.com/opendime/DAFU/blob/master/Makefile) |
| 1209 | abba | Generic      | SafeWISE CoinSafe          | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | b0b0 | Generic      | Monero Hardware bootloader | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | c0dA | Generic      | Monero Hardware            | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | d00d | Generic      | Monero Hardware developer  | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 1209 | 53c0 | SatoshiLabs  | Trezor v2 bootloader       | [Github](https://github.com/trezor/trezor-suite/blob/130b17ff0d52b67079d29b4e7250637528be1def/packages/suite-native/android/app/src/main/res/xml/devices.xml) |
| 1209 | 53c1 | SatoshiLabs  | Trezor v2                  | [Github](https://github.com/trezor/trezor-suite/blob/130b17ff0d52b67079d29b4e7250637528be1def/packages/suite-native/android/app/src/main/res/xml/devices.xml) |
| 2b24 | All  | KeepKey      | Bitcoin Wallet             | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 2c97 | All  | Ledger       | Ledger Nano S, X and Blue  | [Linux-usb.org](http://www.linux-usb.org/usb.ids) |
| 534c | 0001 | SatoshiLabs  | Trezor v1                  | [Github](https://github.com/trezor/trezor-suite/blob/130b17ff0d52b67079d29b4e7250637528be1def/packages/suite-native/android/app/src/main/res/xml/devices.xml) |
| d13e | cc10 | CoinKite     | ColdCard                   | [Github](https://github.com/Coldcard/firmware/search?q=pid) |

### Missing - further research required
- SafePal Ltd. Officially backed-up by Binance. Product: SFP SafePal S1
- SecuX Technology Inc., Taiwan and its products: W10, W20, V20 Stone

### Specific no-USB HD Wallets
- Embedded Agency LLC, Canada and USA. Product: Husky HDW20 - This HD Wallet is only using Wifi, including for OTA Firmware update (Over-The-Air).
- Cobo Global Ltd, Cayman Islands. Products: Keystone Essential, Keystone Pro - Cobo Vault is an open source air-gapped HD wallet. It is not using USB (other than for Firmware burning). Cobo Vault uses QRcodes only. Its hardware is based on an ARM Cortex A7. Refer to [Github](https://github.com/CoboVault/cobo-vault-docs/tree/master/hardware)
- Ellipal Ltd., Hong-Kong. Products: EC01 and Titan Cold Wallet. This is an air-gapped wallet. The Firmware update is done via micro SD card inserted in a seperate "security module". The micro-USB port of the security module is only for charging.
- C∞lBitX (CoolBitx), Taiwan. Products: CoolWallet S and WoolWallet Pro. These are Bluetooth only cards, uses NFC to charge. CoolBitX is also the creator of the Sygna Bridge, a compliance tool used as a gateway for the exchange and querying of data accross Financial actors.
- CoinKite Inc., Canada. Products: OpenDime and ColdCard. Although these are air-gapped cards, the ColdCard Firmware update is done in DFU mode via USB.

### Links
Ledger	https://www.ledger.com/  
Trezor	https://trezor.io/  
Keepkey	https://shapeshift.com/keepkey  
BitBox	https://shiftcrypto.ch/  
C∞lWallet (CoolWallet) https://www.coolwallet.io/  
Cobo Vault https://cobo.com/about?locale=en 
Cold Card Wallet	https://coldcardwallet.com/  
Ellipal	https://www.ellipal.com/  
JuBiter Blade https://www.ftsafe.com/store/product/cryptocurrency-wallet/
SafeWize CoinSafe https://safewise.io/#/home
Husky HDW20 https://www.huskywallet.com
SFP SafePal https://safepal.io
