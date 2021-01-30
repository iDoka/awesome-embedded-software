# :construction: A curated list of awesome sources and libs for Embedded Systems

There is my attempt to create list of software for Embedded Systems

URL: https://github.com/iDoka/awesome-embedded-software


## Contents

Under construct


## Common

* [embxx](https://github.com/arobenko/embxx) - Embedded C++ Library
* [embedded-libs](https://github.com/MaJerle/embedded-libs) - Libraries for embedded software (mainly for STM32)
* [RegExp](https://github.com/MaJerle/RegExp) - Regular expressions library for embedded systems
* [ETLCPP](https://github.com/ETLCPP/etl) - Embedded Template Library where the user can declare the size, or maximum size of any object upfront
* [eFLL](https://github.com/zerokol/eFLL) - Embedded Fuzzy Logic Library is a standard library for Embedded Systems

### Protocol Parsers

* [LwGPS](https://github.com/MaJerle/lwgps) - Lightweight GPS NMEA parser for embedded systems
* [LwESP](https://github.com/MaJerle/lwesp) - lightweight ESP AT commands parser library to communicate with ESP8266 or ESP32 Wi-Fi module using AT commands
* [LwGSM](https://github.com/MaJerle/lwgsm) - Library for SIMCOM GSM modules to communicate with AT commands and RTOS from host device
* [GSM_Engine](https://github.com/MikroElektronika/GSM_Engine) - Generic AT parser for AT command based modules

#### AT command parser

* [atat](https://github.com/esynr3z/atat) - Lib for AT-like custom commands processing
* [cAT](https://github.com/marcinbor85/cAT) - Plain C library for parsing AT commands for use in host devices
* [gzat](https://github.com/gzhouct/gzat) - Portable AT command parsing library in C++ language
* [ATParser](https://github.com/ARMmbed/ATParser) - An mbed-os compatible AT command parser
* [atcommander](https://github.com/malachi-iot/atcommander) - Portable C++ library for sending AT commands and parsing their responses


#### Various protocols

* [lwpkt](https://github.com/MaJerle/lwpkt) - Lightweight packet protocol structure for multi-device communication focused on RS-485
* [lwow](https://github.com/MaJerle/lwow) - Lightweight onewire protocol library optimized for UART hardware on embedded systems
* []() -


### Memory

* [libmemory](https://github.com/embeddedartistry/libmemory) - memory management library with implementations for malloc(), free(), and other useful memory management functions
* [lwmem](https://github.com/MaJerle/lwmem) - Lightweight dynamic memory manager library for embedded systems with memory constraints. It implements malloc, calloc, realloc and free functions


### Logging

* [embedded-log](https://github.com/to9/embedded-log) - a small and beautiful embedded log library for mcu


### Ring Buffer

* [LwRB](https://github.com/MaJerle/lwrb) - Lightweight generic ring buffer manager library
* [RingBuffer](https://github.com/wizard97/ArduinoRingBuffer) - Simple Interrupt Safe Ring (Circular) Buffer Queuing Library for Embedded platforms

### printf

* [lwprintf](https://github.com/MaJerle/lwprintf) - Lightweight printf library optimized for embedded systems
* [Embedded_Printf](https://github.com/agaelema/Embedded_Printf) - Embedded version of the famous "printf( )" function. The idea is create an simple and efficient library to meet some common needs in embedded systems
* [tinyprintf](https://github.com/cjlano/tinyprintf) - tiny printf and sprintf library for small embedded systems


### CLI

* [cli](https://github.com/letgo0007/cli) - a CLI (Command Line Interface) example build in pure C. Designed for MCU, support block/non-block mode input
* [terminal](https://github.com/JingoC/terminal) - a Command Line Interface for microcontrollers. Flexible terminal settings allow you to integrate it with any microcontroller, without much effort
* []() -
* []() -
* []() -
* []() -
* []() -
* []() -

### Menu

* [ProMenu](https://github.com/marcinbor85/ProMenu) - Advanced Generic Application Menu Library. ProMenu Library is used for fast implementing advanced user menus. It supports nesting, numeric settings, text settings, boolean values and events. Library is implemented in C++ with build-in Arduino port, but it is easy to port to different architecture.
* []() -
* []() -
* []() -


### Thread management

* [C-Thread-Pool](https://github.com/Pithikos/C-Thread-Pool) - minimal but powerful thread pool in ANSI C


### IO

* [FastIO](https://github.com/xillion/FastIO) - Fast GPIO forked from http://os.mbed.com/users/Sissors/code/FastIO/
* []() -
* []() -
* []() -







## Snippets

* [Collection of miscellaneous portable C snippets](https://github.com/nemequ/portable-snippets)

## HW

* [embedded-driver](https://github.com/InfiniteYuan/embedded-driver-library) - Embedded driver library for various peripheral
* [tinyusb](https://github.com/hathach/tinyusb) - cross-platform USB stack for embedded system
* []() -



## Protocols

* [xmodem](https://github.com/bsail/xmodem) - XMODEM Library for embedded, mobile, iot, and desktop systems
* [microrl](https://github.com/Helius/microrl) - micro read line library for small and embedded devices with basic VT100 support
* [TinyFrame](https://github.com/MightyPork/TinyFrame) - a simple library for building and parsing data frames for serial interfaces (like UART / RS232)
* []() -
* []() -
* []() -

### RF

* [RadioHead](https://github.com/hallard/RadioHead) - Packet Radio library for embedded microprocessors
* [Adafruit's RadioHead](https://github.com/adafruit/RadioHead) - Packet Radio library for embedded microprocessors with [docs](http://www.airspayce.com/mikem/arduino/RadioHead/)
* []() -

### MQTT

* [libemqtt 1](https://github.com/menudoproblema/libemqtt) - Embedded C client library for the MQTT protocol
* [libumqtt 2](https://github.com/zhaojh329/libumqtt) - a Lightweight and fully asynchronous MQTT client C library based on libev
* [Paho MQTT](https://github.com/eclipse/paho.mqtt.embedded-c) - C client library for embedded systems
* []() -
* []() -



## Data processing

* [liquid-fpm](https://github.com/jgaeddert/liquid-fpm) - Software-Defined Radio Fixed-Point Math Library for embedded signal processing
* [liquid-dsp](https://github.com/jgaeddert/liquid-dsp) - digital signal processing library for software-defined radios
* []() -


### Random Number Generation

* [pcg-c-basic](https://github.com/imneme/pcg-c-basic) - code provides a minimal implementation of one member of the PCG family of random number generators, which are fast, statistically excellent, and offer a number of useful features
* [pcg-c](https://github.com/imneme/pcg-c) -  code provides an implementation of the PCG family of random number generators, which are fast, statistically excellent, and offer a number of useful features


### Cryptography

* [wolfSSH](https://www.wolfssl.com/products/wolfssh/) - a lightweight SSHv2 client and server library written in ANSI C and targeted for embedded, RTOS, and resource-constrained environments - primarily because of its small size, speed, and feature set
* [LibHydrogen](https://github.com/jedisct1/libhydrogen) - a lightweight, secure, easy-to-use crypto library suitable for constrained environments
* [krypton](https://github.com/ezhangle/krypton) - Embedded TLS/DTLS library, source and binary compatible OpenSSL subset
* [wolfTPM](https://github.com/wolfSSL/wolfTPM) - a highly portable TPM 2.0 library, designed for embedded use
* [mbedTLS]()

### Compression

* [heatshrink](https://github.com/atomicobject/heatshrink) - data compression library for embedded/real-time systems
* [shoco](https://github.com/Ed-von-Schleck/shoco) - a C library to compress and decompress short strings. It is very fast and easy to use. The default compression model is optimized for english words, but you can generate your own compression model


### DSP and Filtering

* [kalman-clib](https://github.com/sunsided/kalman-clib) - Microcontroller targeted naive Kalman filter implementation in pure C
* []() -


### CV

* [Embedded SOD](https://github.com/symisc/sod) - an Embedded Computer Vision & Machine Learning Library (CPU Optimized & IoT Capable)
* [QR-Image-embedded](https://github.com/swex/QR-Image-embedded) - QR library fork for embedded systems
* []() -


### AI ML

* [Cranium](https://github.com/100/Cranium) - a portable, header-only, feedforward artificial neural network library written in vanilla C99
* [μTensor](https://github.com/uTensor/uTensor) - TinyML AI inference library
* [Fido](https://github.com/FidoProject/Fido) - lightweight C++ machine learning library for embedded electronics and robotics
* [nnom](https://github.com/majianjia/nnom) - Neural Network on Microcontroller (NNoM) is a high-level inference Neural Network library specifically for microcontrollers
* [caffepresso](https://github.com/gplhegde/caffepresso) - an Optimized Library for Deep Learning on Embedded Accelerator-based platforms
* [libonnx](https://github.com/xboot/libonnx) -  lightweight, portable pure C99 onnx inference engine for embedded devices with hardware acceleration support
* []() -
* []() -
* []() -

### DataBases

* [PureDB](https://github.com/jedisct1/PureDB) - a portable and tiny set of libraries for creating and reading constant databases
* []() -



## WEB

* [uIP](https://github.com/adamdunkels/uip) - is a very small implementation of the TCP/IP stack that is written by Adam Dunkels
* [LwIP](http://savannah.nongnu.org/projects/lwip/) - a small independent implementation of the TCP/IP protocol suite that has been initially developed by Adam Dunkels. lwIP suitable for use in embedded systems with tens of kilobytes of free RAM and room for around 40 kilobytes of code ROM.
* [HttpClient](https://github.com/nmattisson/HttpClient) - Http Client Library
* []() -
* []() -

### web-server

* [mongoose](https://github.com/cesanta/mongoose) - Embedded Web Server Library. It is a multi-protocol embedded networking library with functions including TCP, HTTP client and server, WebSocket client and server, MQTT client and broker and much more.
* [libevhtp](https://github.com/criticalstack/libevhtp) - extremely-fast and secure embedded HTTP servers with ease
* [libμhttpd](https://github.com/zhaojh329/libuhttpd) - very flexible, lightweight and fully asynchronous HTTP server library based on libev and http-parser
* []() -
* []() -


## Filesystem

* [lwext4](https://github.com/gkostka/lwext4) - ext2/ext3/ext4 filesystem library for microcontrollers
* [FatFS](http://elm-chan.org/fsw/ff/00index_e.html) - FAT filesystem implementation
* [LevelX](https://github.com/azure-rtos/levelx) - Provides Flash Wear Leveling for FileX and Stand Alone purposes
* [ufat](https://github.com/dlbeer/ufat) - Low-memory feature-complete VFAT implementation
* [fat_io_lib](https://github.com/ultraembedded/fat_io_lib) - Small footprint, low dependency, C code implementation of a FAT16 & FAT32 driver


## GUI

* [lvgl](https://github.com/lvgl/lvgl) - Powerful and easy-to-use embedded GUI with many widgets, advanced visual effects (opacity, antialiasing, animations) and low memory requirements (16K RAM, 64K Flash)
* [EasyGUI](https://github.com/MaJerle/EasyGUI) - EasyGUI for embedded systems (highly optimized for STM32)
* [TouchGFX](https://www.touchgfx.com/product/overview/) - a user-friendly graphical C++ tool integrated as a free tool in the STM32 ecosystem
* [eGUI](https://github.com/NXPmicro/eGUI) - eGUI embedded graphic library
* [Embedded-graphics](https://github.com/embedded-graphics/embedded-graphics) - a 2D graphics library that is focused on memory constrained embedded devices
* [ESLowGraphics](https://github.com/errorcalc/ESLowGraphicsLibrary) - Low level software graphics library by ErrorSoft (ESLGL)
* [ftk](https://github.com/prife/ftk) -  gui library for embedded system
* [u8glib](https://github.com/pabigot/u8glib) - Universal Graphics Library for 8 Bit Embedded Systems
* [u8g2](https://github.com/olikraus/u8g2) - U8glib library for monochrome displays, version 2
* [SGFX](https://github.com/rprata/sgfx) - a lightweight embedded library for displays and touchscreens providing everything required to build a fully featured embedded GUI
* [GUIX](https://github.com/azure-rtos/guix) - provides a complete, embedded graphical user interface (GUI) library and design environment, facilitating the creation and maintenance of all graphical elements needed by your device
* [GUILib](https://github.com/Nikolay-Kha/GUILib) - GUI library for embedded systems
* [HMI_Library](https://github.com/kgrze/HMI_Library) - Human Machine Interface suitable for embedded system
* [AFGUI](https://github.com/AndreyFursov/AFGUI) - Embedded GUI Library
* [MakiseGUI](https://github.com/SL-RU/MakiseGUI) - Graphics and GUI library for embed systems
* [emGUI](https://github.com/libEmGUI/emGUI) - Simple C UI Library for embedded platforms
* [micromenu-v2](https://github.com/abcminiuser/micromenu-v2) - Tiny text-orientated menu library in C for embedded use
* []() -



* [lv_gui_designer](https://github.com/kaiakz/lv_gui_designer) - a drag-and-drop, simple GUI designer built with LittlevGL
* [walv](https://github.com/kaiakz/walv) - Online, WYSIWYG GUI designer for LittlevGL. Cross-platform supported(Even Android and IOS)

## RTOS

* [FreeRTOS](https://github.com/FreeRTOS/FreeRTOS)
* [Zephyr](https://github.com/zephyrproject-rtos/zephyr) -  a new generation, scalable, optimized, secure RTOS for multiple hardware architectures
* [Apache NuttX]() -
* [scmRTOS](https://github.com/scmrtos/scmrtos) -  tiny Real-Time Preemptive Operating System intended for use with Single-Chip Microcontrollers. scmRTOS is capable to run on tiny uCs with as small amount of RAM as 512 bytes. The RTOS is written on C++ and supports various platforms.
* [ChibiOS]() -
* [Azure RTOS ThreadX](https://github.com/azure-rtos/threadx) - is an advanced real-time operating system (RTOS) designed specifically for deeply embedded applications
* [eCos]() -
* [embox](https://github.com/embox/embox) - a configurable RTOS designed for resource constrained and embedded systems. Embox main idea is using Linux software without Linux
* [RIOT](https://github.com/RIOT-OS/RIOT) - a real-time multi-threading operating system that supports a range of devices that are typically found in the Internet of Things (IoT): 8-bit, 16-bit and 32-bit microcontrollers. RIOT is based on the following design principles: energy-efficiency, real-time capabilities, small memory footprint, modularity, and uniform API access, independent of the underlying hardware (this API offers partial POSIX compliance).
* [Arm Mbed OS](https://github.com/ARMmbed/mbed-os) - a platform operating system designed for the Internet of Things. It includes all the features you need to develop a connected product based on an Arm Cortex-M microcontroller, including security, connectivity, an RTOS and drivers for sensors and I/O devices.



## Uncategorized

* [TimeLib](https://github.com/geekfactory/TimeLib) - Time management library for embedded devices
* [μtz](https://github.com/evq/utz) - a ime zone library for tiny embedded systems

* [tslib](https://github.com/libts/tslib) - Touchscreen access library
* [wiselib](https://github.com/ibr-alg/wiselib) - generic algorithms library for heterogeneous, distributed, embedded systems
* [Apache NuttX Apps](https://github.com/apache/incubator-nuttx-apps) - a collection of tools, shells, network utilities, libraries, interpreters and can be used with the NuttX RTOS
* [util.embedded](https://github.com/malachib/util.embedded) - Useful support code for embedded development
* []() -
* []() -
* []() -

## etc

Follow this root-repo for lastest updates: https://github.com/iDoka/awesome-embedded-software


## Tags

#awesome
#awesome-list
#embedded
#embedded-systems
#rtos
#stm32
#cortex-m
#risc-v
#mcu
#uc
#lightweight
#gui
#iot
#crossplatform
#portable
#lightweight-embedded-library
#embedded-library
