# Awesome M5Stack Cardputer

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<img src="m5stack cardputer.jpg" alt="m5stack cardputer" width="400">

M5Stack Cardputer is a S3 Stamp cheap ($30) and complete mini computer in a credit-card size, weighing 92.8g.  
[Official website](https://shop.m5stack.com/products/m5stack-cardputer-with-m5stamps3-v1-1) | [Docs](https://docs.m5stack.com/en/core/Cardputer)

Cardputer Reddit Community: https://www.reddit.com/r/CardPuter  
An Unofficial Cardputer Discord Server: https://discord.gg/zuzSVDgxvx  
Unofficial Cardputer Development Reference Manual: https://cardputer.free.nf/

## Specs

### Processor

From ESP32-S3Fn8 ([Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf)):

- Dual 32bit Xtensa LX7 cores running up to **240Mhz**
- RISC-V Ultra Low Power Co-processor
- ULTRA LOW Deep Sleep Current

### Memory

- 128-bit data bus and SIMD commands
- 384 KB ROM - for booting and core functions
- 512 KB SRAM - for data and instructions, running at a configurable frequency of up to 240 MHz
- 16 KB SRAM in RTC - can retain data in Deep-sleep mode
- 4 Kbit eFuse - reserved for user data, such as encryption key and device ID
- 8 MB Flash
- SPI, Dual SPI, Quad SPI, Octal SPI, QPI and OPI interfaces that allow connection to multiple flash and external RAM

### Devices/Resources

- Bluetooth: 5.0, BLE + Mesh
- Wi-Fi: 802.11b/g/n 2.4Ghz
- Display: ST7789V2 - IPS LCD, 1,14", 240px x 135px
- Battery: internal 120mAh + 1400mAh (in the base) lithium battery
- 1 TF-Card (MicroSD) slot
- 1 USB-C OTG in/out
- 1 Grove 1 x HY2.0-4P input/output
- 4x14 Keyboard: 56 keys, QWERTY type, ortholinear with tactile click switches
- Infrared G44 ∠0° : 410cm, < 90° : 66cm, < 45° : 170cm
- Digital MEMS Microphone PDM-MIC SPM1423
- Sound: I2S-Speaker NS4168 - 8Ω@1W 
- 2 magnets on the back to stick it somewhere metallic
- It comes with a little hexagonal screwdriver to open it
- Dimensions: 85mm x 54mm x 19.7mm
- Operating Current: IR transmission mode: DC-4.2V/148.07mA | Key mode: DC-4.2V/138.93mA
- Sleep Current: DC-4.2V @ 0.15uA
- Product Weight: 90g


**Note: no builtin NFC, RFID or LoRa module**

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
- [M5 Launcher](https://github.com/bmorcelli/Launcher) - App launcher for M5StickC, M5StickC Plus, M5StickC Plus 2 and M5Cardputer
  - [250+ prebuilt binaries](https://bmorcelli.github.io/Launcher/catalog.html)
  - [Laucher website](https://bmorcelli.github.io/Launcher/)
- [MicroHydra Launcher](https://github.com/echo-lalia/MicroHydra)
  - [MicroHydra Apps](https://github.com/echo-lalia/MicroHydra-Apps)
  - [PicoChat Client](https://github.com/PixelDud/CardPuter-PicoChat) To use with MicroHydra
  - [HydraMenu app](https://github.com/Gabriel-F-Sousa/HydraMenu)
- [Simple App Launcher for Cardputer](https://github.com/shikarunochi/CardputerSimpleLaucher)
- [HydraOS](https://github.com/WauHundeland/HydraOS) - Micro OS for Cardputer
- [BerylliumOS](https://github.com/beryllium-org/OS) - Another Micro OS for Cardputer
- [PyDOS + PyBASIC](https://github.com/RetiredWizard/PyDOS) 

### Cybersecurity Related
- [M5 Stick NEMO](https://github.com/n0xa/m5stick-nemo) - Hacking tools for cardputer
- [Cardputer Marauder ESP32](https://github.com/justcallmekoko/ESP32Marauder)
- [Evil-M5Project](https://github.com/7h30th3r0n3/Evil-M5Project)
- [Bruce](https://github.com/pr3y/Bruce)
- [Palnagotchi](https://github.com/viniciusbo/m5-palnagotchi)
- [433Mhz sniffer](https://github.com/bmorcelli/io433)
- [ESP32 Bus Pirate](https://github.com/geo-tp/ESP32-Bus-Pirate)

### Game Related
- [TinyKnight Game](https://github.com/foopod/tinyKnight)
- [Sun Rider Game](https://github.com/Treblewolf/M5Cardputer-Sun-Rider)
- [Classic Snake Game](https://github.com/ostaquet/M5Snake/tree/master/src/M5Snake)
- [Anarch Game port from ESPBoy](https://github.com/TheBricktop/Anarch-Cardputer)
- [DOOM port](https://github.com/Logimancer/Cardputer-doom) - Yes, of course we have Doom
- [Some games experiments](https://github.com/polyphasicdevs/Cardputer-experiments)
- [Gameboy emulator](https://github.com/Mr-PauI/Gameboy-Enhanced-Firmware-m5stack-cardputer-)
- [Conway's Game of Life](https://github.com/Mystereon/CardLife)
- [Math Game](https://github.com/seanbutler/M5CardputerMathGame)
- [Gameboy Emulator Port of Peanut-GB by matthew-5pl](https://github.com/matthew-5pl/gb_cardputer) | [By yonxji](https://github.com/yongxji/cardputer-gameboy-emu) | [By Mr-Paul](https://github.com/Mr-PauI/Gameboy-Enhanced-Firmware-m5stack-cardputer-) | By geo-tp (see next on the list)
- [Cardputer Game Station Emulators](https://github.com/geo-tp/Cardputer-Game-Station-Emulators) - Emulator for cardputer that supports nine different consoles
- [Tamaputer Tamagotchi P1 Emulator](https://github.com/mindovermiles262/tamaputer)

### Misc.
- [User Demo extended with some more apps](https://github.com/JohnZ03/M5Cardputer-UserDemo)
- [Cardputer WebRadio](https://github.com/cyberwisk/M5Cardputer_WebRadio)
- [M5Cardputer WebRadio Dutch version](https://github.com/rolandbreedveld/M5Cardputer_WebRadio_Dutch/)
- [HID Bluetooth Keyboard](https://github.com/Gitshaoxiang/M5Cardputer-BLE-HID-Keyboard)
- [SSH Client By aat440z](https://github.com/aat440hz/SSHClient-M5Cardputer) | [By fernandofatech](https://github.com/fernandofatech/M5Cardputer-SSHClient) | [By SUB0PT1MAL](https://github.com/aat440hz/SSHClient-M5Cardputer)
- [Telnet Client](https://github.com/aat440hz/TelnetClient-M5Cardputer)
- [Lora Chat App](https://github.com/nonik0/CardputerLoRaChat)
- [Volos Cardputer TV Remote](https://github.com/VolosR/M5CardRemote/)
- [Universal remote control](https://github.com/geo-tp/Ultimate-Remote)
- [MDX (mxdrv) file Player for Cardputer](https://github.com/Layer812/mdxPC)
- [M5CardForth - Forth Programming Language for Cardputer](https://github.com/ryu10/M5CardForth)
- [VGM Player for Cardputer](https://github.com/Layer812/vgmPC)
- [M5Cardputer C64 Emulator](https://github.com/iele/M5Cardputer-C64-Emulator)
- [Eliza Chatbot](https://github.com/Layer812/cardputer_eliza)
- [Audio Stream Server](https://github.com/geo-tp/M5Cardputer-Audio-Stream-Server)
- [Fake Windows XP UI](https://github.com/prashantkamdar/M5StickCPLUS.fakeWinXP)
- [AI Gadget assistant for Cardputer](https://github.com/jeftheone/M5CardputerAIWiFiConnection)
- [ESP Console Emulator Server](https://github.com/IncursioHack/ESP-Game-Server)
- [Rust firmware hal and examples](https://github.com/Kezii/Rust-M5Stack-Cardputer)
- [Simple StopWatch](https://github.com/qubiX00/stopwatch-cardputer)
- [Weather App](https://github.com/qubiX00/weather-cardputer)
- [MiniAcid](https://github.com/urtubia/miniacid)
  - [Demo site](https://miniacid.mrbook.org)
