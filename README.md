# Awesome M5Stack Cardputer

<img src="m5stack cardputer.jpg" alt="m5stack cardputer" width="400">

M5Stack Cardputer is a S3 Stamp cheap ($30) and complete mini computer in a credit-card size, weighing 92.8g.  
[Official website](https://shop.m5stack.com/products/m5stack-cardputer-kit-w-m5stamps3) | [Docs](https://docs.m5stack.com/en/core/Cardputer)

Cardputer Reddit Community: https://www.reddit.com/r/CardPuter

## Specs

### Processor

From ESP32-S3Fn8 ([Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)):

- Dual 32bit Xtensa LX7 cores running up to **240Mhz**
- RISC-V Ultra Low Power Co-processor
- ULTRA LOW Deep Sleep Current

### Memory

- 128-bit data bus and SIMD commands
- 384 KB ROM - for booting and core functions
- 512 KB SRAM - for data and instructions, running at a configurable frequency of up to 240 MH
- 16 KB SRAM in RTC - can retain data in Deep-sleep mode
- 4 Kbit eFuse - reserved for user data, such as encryption key and device ID
- SPI, Dual SPI, Quad SPI, Octal SPI, QPI and OPI interfaces that allow connection to multiple flash and external RAM

### Devices/Resources

- Bluetooth: 5.0, BLE + Mesh
- Wi-Fi: 802.11b/g/n 2.4Ghz
- Display: IPS LCD, 1,14", 240x135px
- Battery: internal 120mAh + 1400mAh (in the base) lithium battery
- TF-Card (MicroSD) slot
- 1 USB-C OTG in/out
- Keyboard: 56 keys, QWERTY type, ortholinear with tactile click switches
- Infrared ∠0° : 410cm, < 90° : 66cm, < 45° : 170cm
- Digital MEMS Microphone
- Sound: I2S-Speaker, 8Ω@1W
- 2 magnets on the back to stick it somewhere metallic
- It comes with a little hexagonal screwdriver to open it

**Note: no builtin NFC or RFID**

---

## Pre-installed apps

- Wi-Fi Scanner
- Audio recorder
- ESP Chat - to communicate with other cardputers or similars
- IR remote data send manually
- Pika Python REPL
- Set WiFi
- Timer
- Keyboard (USB or Bluetooth) connector

These builtin apps can be found at: https://github.com/m5stack/M5Cardputer-UserDemo

## Community Apps

### Launchers
- [MicroHydra Launcher](https://github.com/echo-lalia/Cardputer-MicroHydra)
- [Simple App Launcher for Cardputer](https://github.com/shikarunochi/CardputerSimpleLaucher)

### Vulnerability Testing
- [M5 Stick NEMO](https://github.com/n0xa/m5stick-nemo) - Hacking tools for cardputer
- [M5 Stick Bruce - Fork of NEMO](https://github.com/pr3y/Bruce)
- [Cardputer Marauder ESP32](https://github.com/marivaaldo/ESP32Marauder/tree/feature/add-m5cardputer-support)
- [Evil-Cardputer](https://github.com/7h30th3r0n3/Evil-M5Core2)

### Misc.
- [User Demo extended with some more apps](https://github.com/JohnZ03/M5Cardputer-UserDemo)
- [Cardputer WebRadio](https://github.com/cyberwisk/M5Cardputer_WebRadio)
- [Math Game](https://github.com/seanbutler/M5CardputerMathGame)
- [Gameboy Emulator Port of Peanut-GB by matthew-5pl](https://github.com/matthew-5pl/gb_cardputer) | [By yonxji](https://github.com/yongxji/cardputer-gameboy-emu)
- [HID Bluetooth Keyboard](https://github.com/Gitshaoxiang/M5Cardputer-BLE-HID-Keyboard)
- [SSH Client By aat440z](https://github.com/aat440hz/SSHClient-M5Cardputer) | [By fernandofatech](https://github.com/fernandofatech/M5Cardputer-SSHClient)
- [Telnet Client](https://github.com/aat440hz/TelnetClient-M5Cardputer)
- [Lora Chat App](https://github.com/nonik0/CardputerLoRaChat)
- [Volos Cardputer TV Remote](https://github.com/VolosR/M5CardRemote/)
