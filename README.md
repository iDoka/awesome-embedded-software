# Awesome Embedded Resources for Developers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://badgen.net/github/stars/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/stargazers/)
[![GitHub forks](https://badgen.net/github/forks/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/network/)
[![GitHub watchers](https://badgen.net/github/watchers/iDoka/awesome-embedded-software/)](https://GitHub.com/iDoka/awesome-embedded-software/watchers/)
<!--
[![GitHub contributors](https://badgen.net/github/contributors/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/graphs/contributors/)
[![GitHub pull-requests merged](https://badgen.net/github/merged-prs/iDoka/awesome-embedded-software)](https://github.com/iDoka/awesome-embedded-software/pulls?q=is%3Amerged)
[![GitHub latest commit](https://badgen.net/github/last-commit/iDoka/awesome-embedded-software)](https://GitHub.com/iDoka/awesome-embedded-software/commit/)
-->

> Awesome List of Sources and Libs for Embedded Systems Development

Implementation of Sources and Libs in this list are specifically suitable for resource-constrained Embedded Systems (low-memory and low-power) like 8-bit, 16-bit and 32-bit microcontrollers.

> **Warning**
> This list does'nt cover any linux-related topics (like Raspberry Pi platform or any other SBCs (Single Board Computer)).


Permanent URL to this list: https://github.com/iDoka/awesome-embedded-software


## Contents

* [Common](#common)
* [Memory](#memory)
  * [Memory management](#memory-management)
  * [Buffers](#buffers)
  * [Ring Buffer](#ring-buffer)
  * [FIFO](#fifo)
* [Storage](#storage)
  * [Filesystems](#filesystems)
  * [Data Bases](#data-bases)
  * [Flash Memory](#flash-memory)
* [Protocols](#protocols)
  * [Radio Frequency Protocols](#radio-frequency-protocols)
  * [Network protocols](#network-protocols)
  * [Web Server](#web-server)
  * [MQTT](#mqtt)
  * [Protocol Parsers](#protocol-parsers)
* [Data processing](#data-processing)
  * [Math](#math)
  * [DSP and Filtering](#dsp-and-filtering)
  * [Compression](#compression)
  * [AI ML](#ai-ml)
  * [CV](#cv)
* [Cryptography](#cryptography)
  * [General](#general)
  * [Elliptic Curve Cryptography](#elliptic-curve-cryptography)
  * [Random Number Generation](#random-number-generation)
* [OS](#os)
  * [RTOS](#rtos)
  * [Event based scheduler](#event-based-scheduler)
* [User Interface](#user-interface)
  * [CLI](#cli)
  * [Menu](#menu)
  * [printf](#printf)
  * [Logging](#logging)
* [GUI](#gui)
  * [GUI editors](#gui-editors)
  * [Font utils](#font-utils)
  * [Picture manupulation tools](#picture-manupulation-tools)
* [Hardware](#hardware)
  * [IO](#io)
  * [USB](#usb)
  * [Flash](#flash)
  * [CAN bus](#can-bus)
* [Others](#others)
  * [Thread management](#thread-management)
  * [Bootloaders](#bootloaders)
  * [Firmware updates](#firmware-updates)
  * [Touch Screen](#touch-screen)
  * [Time Management Libs](#time-management-libs)
* [Compilers](#compilers)
* [Uncategorized](#uncategorized)


## Common

* [wiselib](https://github.com/ibr-alg/wiselib) - Generic algorithms library for heterogeneous, distributed, embedded systems.
* [util.embedded](https://github.com/malachib/util.embedded) - Useful support code for embedded development.
* [embxx](https://github.com/arobenko/embxx) - Embedded C++ Library.
* [embedded-libs](https://github.com/MaJerle/embedded-libs) - Libraries for embedded software (mainly for STM32).
* [ETLCPP](https://github.com/ETLCPP/etl) - Embedded Template Library where the user can declare the size, or maximum size of any object upfront.
* [eFLL](https://github.com/zerokol/eFLL) - Embedded Fuzzy Logic Library is a standard library for Embedded Systems.
* [Collection of miscellaneous portable C snippets](https://github.com/nemequ/portable-snippets) - Collection of miscellaneous portable C snippets.
* [sc](https://github.com/tezc/sc) - Portable, stand-alone C libraries and data structures (C99).
* [MicroTBX](https://github.com/feaser/microtbx) - Open source Microcontroller ToolBoX consisting of software components commonly needed in embedded software applications. MicroTBX is written in the C programming language (C99) with MISRA compliance in mind.
* [umlibc](https://github.com/rhempel/umlibc) - A bare-bones libc for memory constrained systems.


## Memory

### Memory management

* [libmemory](https://github.com/embeddedartistry/libmemory) - Memory management library with implementations for malloc(), free(), and other useful memory management functions.
* [lwmem](https://github.com/MaJerle/lwmem) - Lightweight dynamic memory manager library for embedded systems with memory constraints. It implements malloc, calloc, realloc and free functions.
* [umm_malloc](https://github.com/rhempel/umm_malloc) - Memory Manager For Small(ish) Microprocessors.

### Buffers

* [EmbeddedProto](https://github.com/Embedded-AMS/EmbeddedProto) -  C++ Protocol Buffers implementation specifically suitable for ARM Cortex-M microcontrollers. It is small, reliable and easy to use.
* [protobuf-embedded-c](https://github.com/berezovskyi/protobuf-embedded-c) - Protocol buffers generator for resource constrained embedded applications written in the C programming language.

### Ring Buffer

* [LwRB](https://github.com/MaJerle/lwrb) - Lightweight generic ring buffer manager library.
* [RingBuffer](https://github.com/wizard97/ArduinoRingBuffer) - Simple Interrupt Safe Ring (Circular) Buffer Queuing Library for Embedded platforms.

### FIFO

* [fifofast](https://github.com/nqtronix/fifofast) - A fast, generic fifo for MCUs.



## Storage

### Filesystems

* [lwext4](https://github.com/gkostka/lwext4) - An ext2/ext3/ext4 filesystem library for microcontrollers.
* [FatFS](http://elm-chan.org/fsw/ff/00index_e.html) - FAT filesystem implementation.
* [LevelX](https://github.com/azure-rtos/levelx) - Provides Flash Wear Leveling for FileX and Stand Alone purposes.
* [ufat](https://github.com/dlbeer/ufat) - Low-memory feature-complete VFAT implementation.
* [fat_io_lib](https://github.com/ultraembedded/fat_io_lib) - Small footprint, low dependency, C code implementation of a FAT16 & FAT32 driver.
* [SdFat](https://github.com/greiman/SdFat) - Arduino FAT16/FAT32 exFAT Library.
* [fat32](https://github.com/strawberryhacker/fat32) - Lighweight FAT32 file system written in C with no thirdparty dependencies. It requires a small port which provide functions for initializing, reading and writing to the MSD.
* [emfat](https://github.com/fetisov/emfat) - FAT32 emulation library for stm32f4.
* [OpenFAT](https://github.com/tmolteno/openfat) - FAT filesystem implementation for embedded processors.
* [uC-FS](https://github.com/weston-embedded/uC-FS) - Compact, reliable, high-performance, and thread-safe embedded file system for microprocessors, microcontrollers, and DSPs. An optional journaling component provides fail-safe operation while maintaining FAT compatibility.
* [littlefs](https://github.com/littlefs-project/littlefs) - Little fail-safe filesystem designed for microcontrollers.

### Data Bases

* [FlashDB](https://github.com/armink/FlashDB) - Ultra-lightweight database that supports key-value and time series data.
* [PureDB](https://github.com/jedisct1/PureDB) - Portable and tiny set of libraries for creating and reading constant databases.

### Flash Memory

* [EasyFlash](https://github.com/armink/EasyFlash#1-introduction) - Lightweight embedded flash memory library.
* [FlashAlgo](https://github.com/pyocd/FlashAlgo) - Framework for building Arm Cortex-M "FLM" style flash programming algorithms.
* [FCB](https://docs.zephyrproject.org/latest/services/storage/fcb/fcb.html) - Flash Circular Buffer provides an abstraction through which you can treat flash like a FIFO.




## Protocols

* [nanoPB](https://github.com/nanopb/nanopb) - Small code-size Protocol Buffers implementation in ANSI C. It is especially suitable for use in microcontrollers, but fits any memory restricted system.
* [interchange](https://github.com/trussed-dev/interchange) - Request/response mechanism for embedded development, using atomics.
* [xmodem](https://github.com/bsail/xmodem) - XMODEM Library for embedded, mobile, iot, and desktop systems.
* [microrl](https://github.com/Helius/microrl) - Micro read line library for small and embedded devices with basic VT100 support.
* [TinyFrame](https://github.com/MightyPork/TinyFrame) - Simple library for building and parsing data frames for serial interfaces (like UART / RS232).

### Radio Frequency Protocols

* [RadioHead](https://github.com/hallard/RadioHead) - Packet Radio library for embedded microprocessors.
* [Adafruit's RadioHead](https://github.com/adafruit/RadioHead) - Packet Radio library for embedded microprocessors with [docs](http://www.airspayce.com/mikem/arduino/RadioHead/).

### Network protocols

* [uIP](https://github.com/adamdunkels/uip) - Very small implementation of the TCP/IP stack that is written by Adam Dunkels.
* [LwIP](http://savannah.nongnu.org/projects/lwip/) - Small independent implementation of the TCP/IP protocol suite that has been initially developed by Adam Dunkels. lwIP suitable for use in embedded systems with tens of kilobytes of free RAM and room for around 40 kilobytes of code ROM.
* [HttpClient](https://github.com/nmattisson/HttpClient) - Http Client Library.
* [httpio](https://github.com/fetisov/httpio) - Stand-Alone Cross Platform request parser and response generator for the HTTP protocol.
* [PicoTCP](https://github.com/Tubbz-alt/picotcp) - Small-footprint, modular TCP/IP stack designed for embedded systems and the Internet of Things.
* [RawTCP_Lib](https://github.com/h3xduck/RawTCP_Lib) - C library for creating and using TCP/IP packets with raw network sockets.
* [LRNDIS](https://github.com/fetisov/lrndis) - Ethernet over USB (rndis + lwip).

### Web Server

* [mongoose](https://github.com/cesanta/mongoose) - Embedded Web Server and Embedded Networking Library. It implements event-driven non-blocking APIs for TCP, UDP, HTTP, WebSocket, MQTT.
* [libevhtp](https://github.com/criticalstack/libevhtp) - Extremely-fast and secure embedded HTTP servers with ease.
* [libμhttpd](https://github.com/zhaojh329/libuhttpd) - Very flexible, lightweight and fully asynchronous HTTP server library based on libev and http-parser.
* [sandbird](https://github.com/rxi/sandbird) - Tiny (800sloc) embeddable HTTP server written in C89.

### MQTT

* [libemqtt 1](https://github.com/menudoproblema/libemqtt) - Embedded C client library for the MQTT protocol.
* [libumqtt 2](https://github.com/zhaojh329/libumqtt) - Lightweight and fully asynchronous MQTT client C library based on libev.
* [Paho MQTT](https://github.com/eclipse/paho.mqtt.embedded-c) - C client library for embedded systems.


### Protocol Parsers


#### Regular Expressions Parsers

* [RegExp](https://github.com/MaJerle/RegExp) - Regular expressions library for embedded systems.

#### GSM

* [LwGSM](https://github.com/MaJerle/lwgsm) - Library for SIMCOM GSM modules to communicate with AT commands and RTOS from host device.
* [GSM_Engine](https://github.com/MikroElektronika/GSM_Engine) - Generic AT parser for AT command based modules.
* [TinyGSM](https://github.com/vshymanskyy/TinyGSM) - Small Arduino library for GSM modules, that just works.

#### GPS

* [LwGPS](https://github.com/MaJerle/lwgps) - Lightweight GPS NMEA parser for embedded systems.

#### AT command parser

* [atat](https://github.com/esynr3z/atat) - Lib for AT-like custom commands processing.
* [cAT](https://github.com/marcinbor85/cAT) - Plain C library for parsing AT commands for use in host devices.
* [gzat](https://github.com/gzhouct/gzat) - Portable AT command parsing library in C++ language.
* [ATParser](https://github.com/ARMmbed/ATParser) - An mbed-os compatible AT command parser.
* [atcommander](https://github.com/malachi-iot/atcommander) - Portable C++ library for sending AT commands and parsing their responses.
* [LwESP](https://github.com/MaJerle/lwesp) - Lightweight ESP AT commands parser library to communicate with ESP8266 or ESP32 Wi-Fi module using AT commands.

#### Various protocols

* [lwpkt](https://github.com/MaJerle/lwpkt) - Lightweight packet protocol structure for multi-device communication focused on RS-485.
* [lwow](https://github.com/MaJerle/lwow) - Lightweight onewire protocol library optimized for UART hardware on embedded systems.
* [panStamp-SWAP](https://github.com/panStamp/swap) - Simple Wireless Abstract Protocol for any existing ISM radio.
* [panStamp-uSWAP](https://github.com/panStamp/uswap) - Micro SWAP stack for MCU's connected via UART.
* [MIN](https://github.com/min-protocol/min) - Microcontroller Interconnect Network protocol version 2.0.
* [libCoAP](https://github.com/obgm/libcoap) - C implementation of a lightweight application-protocol for devices that are constrained their resources such as computing power, RF range, memory, bandwidth, or network packet sizes. This protocol, CoAP, is standardized by the IETF as RFC 7252.



## Data processing

### Math

* [liquid-fpm](https://github.com/jgaeddert/liquid-fpm) - Software-Defined Radio Fixed-Point Math Library for embedded signal processing.
* [FPM](https://github.com/MikeLankamp/fpm) - C++ header-only fixed-point math library.
* [Eigen](https://gitlab.com/libeigen/eigen) - C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.


### DSP and Filtering

* [liquid-dsp](https://github.com/jgaeddert/liquid-dsp) - Digital signal processing library for software-defined radios.
* [minfft](https://github.com/aimukhin/minfft) - Small and fast Discrete Fourier Transform library.
* [iir1](https://github.com/berndporr/iir1) - DSP IIR realtime filter library written in C++.
* [kalman-clib](https://github.com/sunsided/kalman-clib) - Microcontroller targeted naive Kalman filter implementation in pure C.
* [libdspl](https://sourceforge.net/p/libdspl-2-0/code/ci/master/tree/) - Cross-platform digital signal processing algorithm library, written in C language.
* [pocketfft](https://github.com/mreineck/pocketfft) - Heavily modified implementation of FFTPack.
* [KISS FFT](https://github.com/mborgerding/kissfft) - Mixed-radix Fast Fourier Transform based up on the principle, "Keep It Simple, Stupid".
* [CMSIS-DSP](https://github.com/ARM-software/CMSIS-DSP) - Embedded compute library for Cortex-M and Cortex-A.
* [SigLib](https://github.com/Numerix-DSP/siglib) - Digital Signal Processing and Machine Learning Library (x86, Cortex-A and Cortex-M, RISC-V, DSPs from TI, ADI etc).

### Compression

* [heatshrink](https://github.com/atomicobject/heatshrink) - Data compression library for embedded/real-time systems.
* [shoco](https://github.com/Ed-von-Schleck/shoco) - C library to compress and decompress short strings. It is very fast and easy to use. The default compression model is optimized for english words, but you can generate your own compression model.
* [ECL](https://github.com/Nonoum/ECL) - Embedded Compression Library is not only for embedded, it is mostly oriented for small data and has special optimized low-memory modes for restricted environments.

### AI ML

Artificial Intelligence and Machine Learning

* [Cranium](https://github.com/100/Cranium) - Portable, header-only, feedforward artificial neural network library written in vanilla C99.
* [μTensor](https://github.com/uTensor/uTensor) - TinyML AI inference library.
* [Fido](https://github.com/FidoProject/Fido) - Lightweight C++ machine learning library for embedded electronics and robotics.
* [nnom](https://github.com/majianjia/nnom) - Neural Network on Microcontroller (NNoM) is a high-level inference Neural Network library specifically for microcontrollers.
* [caffepresso](https://github.com/gplhegde/caffepresso) - Optimized Library for Deep Learning on Embedded Accelerator-based platforms.
* [libonnx](https://github.com/xboot/libonnx) - Lightweight, portable pure C99 onnx inference engine for embedded devices with hardware acceleration support.

### CV

Computer Vision

* [Embedded SOD](https://github.com/symisc/sod) - Embedded Computer Vision & Machine Learning Library (CPU Optimized & IoT Capable).
* [QR-Image-embedded](https://github.com/swex/QR-Image-embedded) - QR library fork for embedded systems.




## Cryptography

### General

* [trussed](https://github.com/trussed-dev/trussed) - Minimal, modular way to write cryptographic applications on microcontroller platforms (Rust).
* [wolfSSH](https://www.wolfssl.com/products/wolfssh/) - Lightweight SSHv2 client and server library written in ANSI C and targeted for embedded, RTOS, and resource-constrained environments - primarily because of its small size, speed, and feature set.
* [LibHydrogen](https://github.com/jedisct1/libhydrogen) - Lightweight, secure, easy-to-use crypto library suitable for constrained environments.
* [krypton](https://github.com/ezhangle/krypton) - Embedded TLS/DTLS library, source and binary compatible OpenSSL subset.
* [wolfTPM](https://github.com/wolfSSL/wolfTPM) - Highly portable TPM 2.0 library, designed for embedded use.
* [mbedTLS](https://github.com/Mbed-TLS/mbedtls) - Open source, portable, easy to use, readable and flexible TLS library, and reference implementation of the PSA Cryptography API.
* 🔝[liblithium](https://github.com/teslamotors/liblithium) - Lightweight cryptography library that is portable by design. It requires only standard C99 and does not assume 8-bit addressability, making it suitable for use on some DSP architectures as well as mainstream architectures.
* 🔝[trezor-crypto](https://github.com/trezor/trezor-firmware/tree/master/crypto) - Heavily optimized cryptography algorithms for embedded Devices.
* [poly1305-donna](https://github.com/floodyberry/poly1305-donna) -  Implementations of a fast Message-Authentication Code (8 bit, 16 bit, 32 bit and 64 bit multiplies versions).
* [arduinolibs](https://github.com/rweather/arduinolibs) - Arduino Cryptography Library.
* [tlse](https://github.com/eduardsui/tlse) - Single C file TLS 1.2/1.3 implementation, using tomcrypt as crypto library.
* [LibTomCrypt](https://github.com/libtom/libtomcrypt) - Fairly comprehensive, modular and portable cryptographic toolkit that provides developers with a vast array of well known published block ciphers, one-way hash functions, chaining modes, pseudo-random number generators, public key cryptography and a plethora of other routines.
* [Monocypher](https://github.com/LoupVaillant/Monocypher) - Easy to use, easy to deploy, auditable crypto library written in portable C.
* [minicrypt](https://github.com/IanHarvey/minicrypt) - Library of crypto primitives for embedded systems.
* [tinycrypt](https://github.com/intel/tinycrypt) - Library of cryptographic algorithms provides an implementation for constrained devices of a minimal set of standard cryptography primitives.

### Elliptic Curve Cryptography

* [salty](https://github.com/ycrypto/salty) - Ed25519 signatures with assembly optimizations for Cortex-M4 and Cortex-M33.
* [micro-ecc](https://github.com/kmackay/micro-ecc) - ECDH and ECDSA for 8-bit, 32-bit, and 64-bit processors.
* [libuecc](https://github.com/NeoRaider/libuecc) - Very small generic-purpose Elliptic Curve Cryptography library compatible with Ed25519.

### Random Number Generation

* [pcg-c-basic](https://github.com/imneme/pcg-c-basic) - Code provides a minimal implementation of one member of the PCG family of random number generators, which are fast, statistically excellent, and offer a number of useful features.
* [pcg-c](https://github.com/imneme/pcg-c) - Code provides an implementation of the PCG family of random number generators, which are fast, statistically excellent, and offer a number of useful features.




## OS

* [citrus](https://github.com/strawberryhacker/citrus) - Bare metal ARM® Cortex®-A5 operating system.
* [vanilla](https://github.com/strawberryhacker/vanilla) - Bare metal ARM® Cortex®-M7 operating system.
* 🔝[chaos](https://github.com/strawberryhacker/chaos) - Bare metal multicore ARM® Cortex®-A operating system based on a microkernel architecture.
* [LK kernel](https://github.com/littlekernel/lk) - The Little Kernel Embedded Operating System is SMP-aware kernel designed for small systems ported to a variety of platforms and cpu architectures.
* [QuarkTS](https://github.com/kmilo17pet/QuarkTS) - OS for embedded applications that supports prioritized cooperative scheduling, time control, inter-task communications primitives, hierarchical state machines and CoRoutines.
* [micro-ROS](https://micro.ros.org/) - Micro-ROS puts ROS 2 onto microcontrollers.


### RTOS

* 🔝[FreeRTOS™](https://github.com/FreeRTOS/FreeRTOS) - FreeRTOS.
* [Zephyr](https://github.com/zephyrproject-rtos/zephyr) - New generation, scalable, optimized, secure RTOS for multiple hardware architectures.
* [Apache NuttX](https://github.com/apache/incubator-nuttx) - Apache NuttX is a mature, real-time embedded operating system (RTOS).
* [scmRTOS](https://github.com/scmrtos/scmrtos) - Tiny Real-Time Preemptive Operating System intended for use with Single-Chip Microcontrollers. scmRTOS is capable to run on tiny uCs with as small amount of RAM as 512 bytes. The RTOS is written on C++ and supports various platforms.
* [ChibiOS/RT](https://github.com/ChibiOS/ChibiOS) - Compact and fast real-time operating system supporting multiple architectures designed for embedded applications on microcontrollers of 8-, 16-, and 32-bits.
* [Azure RTOS ThreadX](https://github.com/azure-rtos/threadx) - Advanced real-time operating system (RTOS) designed specifically for deeply embedded applications.
* [eCos](https://ecos.sourceware.org/) - Real-time operating system intended for embedded applications _(Closed source)_.
* [embox](https://github.com/embox/embox) - Configurable RTOS designed for resource constrained and embedded systems. Embox main idea is using Linux software without Linux.
* [RIOT](https://github.com/RIOT-OS/RIOT) - Real-time multi-threading operating system that supports a range of devices that are typically found in the Internet of Things (IoT): 8-bit, 16-bit and 32-bit microcontrollers. RIOT is based on the following design principles: energy-efficiency, real-time capabilities, small memory footprint, modularity, and uniform API access, independent of the underlying hardware (this API offers partial POSIX compliance).
* [Arm Mbed OS](https://github.com/ARMmbed/mbed-os) - Platform operating system designed for the Internet of Things. It includes all the features you need to develop a connected product based on an Arm Cortex-M microcontroller, including security, connectivity, an RTOS and drivers for sensors and I/O devices.
* [RT-Thread](https://github.com/RT-Thread/rt-thread) - RT-Thread was born in 2006, it is an open source, neutral, and community-based real-time operating system (RTOS). RT-Thread has Standard version and Nano version. For resource-constrained microcontroller (MCU) systems, the NANO kernel version that requires only 3KB Flash and 1.2KB RAM memory resources can be tailored with easy-to-use tools; And for resource-rich IoT devices, RT-Thread can use the on-line software package management tool, together with system configuration tools, to achieve intuitive and rapid modular cutting, seamlessly import rich software packages, thus achieving complex functions like Android's graphical interface and touch sliding effects, smart voice interaction effects, and so on.
* [distortos](https://github.com/DISTORTEC/distortos) - Object-oriented C++ RTOS for microcontrollers.
* [R3-OS](https://github.com/r3-os/r3) - Experimental static (μITRON-esque) RTOS for deeply embedded systems, testing the limit of Rust's const eval and generics _(Rust)_.
* [Tock Embedded OS](https://github.com/tock/tock) - Embedded operating system designed for running multiple concurrent, mutually distrustful applications on low-memory and low-power microcontrollers _(Rust)_.
* [dandelion](https://github.com/AntoineSebert/dandelion) - Microkernel Real-Time Operating System in Rust.
* [MuditaOS](https://github.com/mudita/MuditaOS) - Mobile operating system based on FreeRTOS optimized for E Ink displays - developed for Mudita Pure minimalist phone.
* [µC/OS-II](https://github.com/weston-embedded/uC-OS2) - Preemptive, highly portable, and scalable real-time kernels. Designed for ease of use on a huge number of CPU architectures.
* [µC/OS-III](https://github.com/weston-embedded/uC-OS3) - Preemptive, highly portable, and scalable real-time kernel. Designed for ease of use on a huge number of CPU architectures.


### Event based scheduler

* [uevloop](https://github.com/andsmedeiros/uevloop) - Fast and lightweight event loop for embedded platforms.
* [lwevt](https://github.com/MaJerle/lwevt) - Lightweight event management system for embedded systems.
* [async](https://github.com/eerimoq/async) - Asynchronous framework in C for systems where low memory usage is important.
* [Protothreads](http://dunkels.com/adam/pt/) - Provide linear code execution for event-driven systems implemented in C designed for severely memory constrained systems, such as small embedded systems or wireless sensor network nodes.
* [EventOS](https://github.com/natnqweb/EventOS) - Event based system designed for Arduino Framework.


## User Interface

### CLI

* [cli](https://github.com/letgo0007/cli) - CLI (Command Line Interface) example build in pure C. Designed for MCU, support block/non-block mode input.
* [terminal](https://github.com/JingoC/terminal) - Command Line Interface for microcontrollers. Flexible terminal settings allow you to integrate it with any microcontroller, without much effort.
* [SerialMenu](https://github.com/sonyhome/SerialMenu) - Arduino library to easily create menus on the serial console.
* [terminal-server](https://github.com/NeoProg2013/terminal-server) - Terminal server for MCU.
* [microsh](https://github.com/dimmykar/microsh) - Shell for Small Embedded Devices.
* [cmd-l](https://github.com/Lambosaurus/cmd-l) - Command line handler for embedded devices.

### Menu

* [ProMenu](https://github.com/marcinbor85/ProMenu) - Advanced Generic Application Menu Library. ProMenu Library is used for fast implementing advanced user menus. It supports nesting, numeric settings, text settings, boolean values and events. Library is implemented in C++ with build-in Arduino port, but it is easy to port to different architecture.
* [BBmenu](https://github.com/vborchsh/bbmenu) - Simple portable CLI menu for misc tasks (it is based on text menus, easily defined in a file).

### printf

* [lwprintf](https://github.com/MaJerle/lwprintf) - Lightweight printf library optimized for embedded systems.
* [Embedded_Printf](https://github.com/agaelema/Embedded_Printf) - Embedded version of the famous "printf( )" function. The idea is create an simple and efficient library to meet some common needs in embedded systems.
* [tinyprintf](https://github.com/cjlano/tinyprintf) - Tiny printf and sprintf library for small embedded systems.
* [xprintf-fp](https://github.com/MarioViara/xprintfc) - Printf for embedded system with floating point support.
* [xprintf-io](https://github.com/sinferwu/xprintf) - Compact string I/O library. It is ideal for tiny microcontrollers that has insufficient program memory for regular printf function. The recommended use is: writing formatted strings into LCD or UART and for debug/maintenance console.
* [xprintf](https://github.com/robbesol/xprintf) - Complete fprintf() formatting implementation, suitable for embedded use.
* [tiny-printf](https://github.com/mpaland/printf) - Tiny, fast, non-dependent and fully loaded printf implementation for embedded systems. Extensive test suite passing.
* [tiny-printf new](https://github.com/eyalroz/printf) - Enhanced and maintained fork of `tiny-printf`. Tiny, fast(ish), self-contained and fully loaded printf, sprinf etc.
* [mini-printf](https://github.com/ldoolitt/mini-printf) - Minimal printf() implementation for embedded projects.
* [nanoprintf](https://github.com/charlesnicholson/nanoprintf) - The smallest public printf implementation for its feature set.
* [fmt](https://github.com/fmtlib/fmt) - Modern formatting library providing a fast and safe alternative to C stdio and C++ iostreams.

### Logging

* [embedded-log](https://github.com/to9/embedded-log) - Small and beautiful embedded log library for mcu.
* [EasyLogger](https://github.com/armink/EasyLogger) - Ultra-lightweight (ROM<1.6K, RAM<0.3k), high-performance C/C++ log library.
* [trice](https://github.com/rokath/trice) - Super fast and tiny embedded device C printf-like trace code (works also inside interrupts) and real-time PC logging (trace ID visualization).
* [embedded-diagnostic-logger](https://github.com/binarymaker/embedded-diagnostic-logger) - Lightweight logger framework for small microcontroller based projects. Multilevel log and token based string transfer. 
* [spdlog](https://github.com/gabime/spdlog) - Very fast, header-only/compiled, C++ logging library.
* [elog](https://github.com/martinribelotta/elog) - Log system is thinked for embedded systems with mininmal resource utilization. The log system is designed to minimize memory compsumition in flash or RAM, enable an eficient in-ram loggin buffer with very efficient storage.


## GUI

* [lvgl](https://github.com/lvgl/lvgl) - Powerful and easy-to-use embedded GUI with many widgets, advanced visual effects (opacity, antialiasing, animations) and low memory requirements (16K RAM, 64K Flash).
* [EasyGUI](https://github.com/MaJerle/EasyGUI) - EasyGUI for embedded systems (highly optimized for STM32).
* [TouchGFX](https://www.touchgfx.com/product/overview/) - User-friendly graphical C++ tool integrated as a free tool in the STM32 ecosystem.
* [eGUI](https://github.com/NXPmicro/eGUI) - An eGUI embedded graphic library.
* [Embedded-graphics](https://github.com/embedded-graphics/embedded-graphics) - 2D graphics library that is focused on memory constrained embedded devices.
* [ESLowGraphics](https://github.com/errorcalc/ESLowGraphicsLibrary) - Low level software graphics library by ErrorSoft (ESLGL).
* [ftk](https://github.com/prife/ftk) - GUI library for embedded system.
* [u8glib](https://github.com/pabigot/u8glib) - Universal Graphics Library for 8 Bit Embedded Systems.
* 🔝[u8g2](https://github.com/olikraus/u8g2) - U8glib library for monochrome displays, version 2.
* [SGFX](https://github.com/rprata/sgfx) - Lightweight embedded library for displays and touchscreens providing everything required to build a fully featured embedded GUI.
* [GUIX](https://github.com/azure-rtos/guix) - Provides a complete, embedded graphical user interface (GUI) library and design environment, facilitating the creation and maintenance of all graphical elements needed by your device.
* [GUILib](https://github.com/Nikolay-Kha/GUILib) - GUI library for embedded systems.
* [HMI_Library](https://github.com/kgrze/HMI_Library) - Human Machine Interface suitable for embedded system.
* [AFGUI](https://github.com/AndreyFursov/AFGUI) - Embedded GUI Library.
* [MakiseGUI](https://github.com/SL-RU/MakiseGUI) - Graphics and GUI library for embed systems.
* [emGUI](https://github.com/libEmGUI/emGUI) - Simple C UI Library for embedded platforms.
* [micromenu-v2](https://github.com/abcminiuser/micromenu-v2) - Tiny text-orientated menu library in C for embedded use.

### GUI editors

* [lv_gui_designer](https://github.com/kaiakz/lv_gui_designer) - Drag-and-drop, simple GUI designer built with LittlevGL.
* [walv](https://github.com/kaiakz/walv) - Online, WYSIWYG GUI designer for LittlevGL. Cross-platform supported(Even Android and IOS).

### Font utils

* [bitmap-OSD-font](https://github.com/frisnit/bitmap-OSD-font) - A 'C' bitmap font for on screen display.
* [ttf2mesh](https://github.com/fetisov/ttf2mesh) - Library for TrueType font tessellation. Allows to convert font glyphs to mesh objects without rasterization.
* [sfam_generator](https://github.com/SL-RU/sfam_generator) - Simple scripts for generating bit fonts for STM32, AVR, Arduino or other MCU.
* [mcufont](https://github.com/mcufont/mcufont) - A font rendering library for microcontrollers.

#### Fonts and Icons

* [picon](https://github.com/yne/picon) - Pico-icon set with Hackable Ligature (Designed on a 8-grid: to be readable at 8px 16px 24px 32px 48px).

### Picture manupulation tools

* [lcd-image-converter](https://github.com/riuson/lcd-image-converter) - Tool to create bitmaps and fonts for embedded applications; allows you to create bitmaps and fonts, and transform them to "C" source format for embedded applications.




## Hardware

* [embedded-driver](https://github.com/InfiniteYuan/embedded-driver-library) - Embedded driver library for various peripheral.

### IO

* [FastIO](https://github.com/xillion/FastIO) - Fast GPIO forked from http://os.mbed.com/users/Sissors/code/FastIO/ .

### USB

* [tinyusb](https://github.com/hathach/tinyusb) - Cross-platform USB stack for embedded system.
* [libusb_stm32](https://github.com/dmitrystu/libusb_stm32) - Lightweight USB device Stack for STM32 microcontrollers.
* [CherryUSB](https://github.com/CherryUSB) - Tiny, beautiful and portable USB host and device stack for embedded system with USB.

### Flash

* [SFUD](https://github.com/armink/SFUD) - Serial Flash Universal Driver (using JEDEC's SFDP standard serial (SPI) flash universal driver library).

### CAN bus

* [libcanard](https://github.com/UAVCAN/libcanard) - Compact implementation of the UAVCAN/CAN protocol in C for high-integrity real-time embedded systems.
* [Canbus-Message](https://github.com/ReFil/Canbus-Message) - CAN message assembly and disassembly library for teensy & stm32.
* [CanBoot](https://github.com/Arksine/CanBoot) -  Can Bootloader for MCUs (Currently lpc176x, stm32 and rp2040 MCUs are supported).



## Others

### Thread management

* [C-Thread-Pool](https://github.com/Pithikos/C-Thread-Pool) - Minimal but powerful thread pool in ANSI C.

### Bootloaders

* [mcuboot](https://github.com/mcu-tools/mcuboot) - Secure boot for 32-bit Microcontrollers.
* [OpenBLT](https://github.com/feaser/openblt) - Open source bootloader for STM32, XMC, HCS12 and other microcontroller targets. It supports communication interfaces such as: RS232, CAN, USB, TCP/IP and it ships with the easy-to-use [MicroBoot](https://www.feaser.com/openblt/doku.php?id=manual:microboot) PC tool for initiating and monitoring the firmware update. Performing firmware updates directly from an SD-card is also supported.

### Firmware updates

* [SWupdate](https://github.com/sbabic/swupdate) - Software Update for Embedded Linux Devices to update system in field. SWUpdate supports local and OTA updates, multiple update strategies and it is designed with security in mind.

### Touch Screen

* [tslib](https://github.com/libts/tslib) - Touchscreen access library.

### Time Management Libs

* [TimeLib](https://github.com/geekfactory/TimeLib) - Time management library for embedded devices.
* [μtz](https://github.com/evq/utz) - Time zone library for tiny embedded systems.



## Compilers

* [SDCC](https://sdcc.sourceforge.net/) - Small Device C Compiler (that targets the Intel MCS51 based microprocessors (8031, 8032, 8051, 8052, etc.), Maxim (formerly Dallas) DS80C390 variants, Freescale (formerly Motorola) HC08 based (hc08, s08), Zilog Z80 based MCUs (Z80, Z180, SM83, Rabbit 2000, 2000A, 3000A, TLCS-90), Padauk (pdk14, pdk15) and STMicroelectronics STM8).
* [tcc](https://bellard.org/tcc/) - Tiny C Compiler (~ 100KB for x86 TCC executable, including C preprocessor, C compiler, assembler and linker).
* [lcc](https://github.com/drh/lcc) - Retargetable ANSI C Compiler (fork for [ULP in ESP32](https://github.com/jasonful/lcc)).
* [pcc](http://pcc.ludd.ltu.se/) - Portable C Compiler ([mirror](https://github.com/IanHarvey/pcc)).
* [TinyGo](https://github.com/tinygo-org/tinygo) - Go compiler for small things: Microcontrollers, WebAssembly (WASM/WASI), and command-line tools (Based on LLVM).
* [chibicc](https://github.com/rui314/chibicc) - Yet another small C compiler that implements most C11 features.


## Uncategorized

* [Apache NuttX Apps](https://github.com/apache/incubator-nuttx-apps) - Collection of tools, shells, network utilities, libraries, interpreters and can be used with the NuttX RTOS.
* [modm](https://github.com/modm-io/modm) - Barebone embedded C++20 library generator for AVR, SAM and ARM Cortex-M Microcontrollers (supported 3534 devices).
* [cembed](https://github.com/rxi/cembed) - Small utility for embedding files in a C header.

---


## Contributing

* Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

## Footnotes

Please follow [this](https://github.com/iDoka/awesome-embedded-software) root-repo for lastest updates.


<!--
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
-->
