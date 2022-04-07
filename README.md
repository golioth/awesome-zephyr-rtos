![Dark Logo](assets/awesome_zephyr_rtos_logo_dark.png#gh-dark-mode-only)
![Ligh Logo](assets/awesome_zephyr_rtos_logo_light.png#gh-light-mode-only)

# 🪁 Awesome Zephyr RTOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> The Zephyr RTOS is based on a small-footprint kernel designed for use on resource-constrained and embedded systems: from simple embedded environmental sensors and LED wearables to sophisticated embedded controllers, smart watches, and IoT wireless applications.

[What is an awesome list?](https://github.com/sindresorhus/awesome/blob/main/awesome.md)


## Contents

- [Official Resources](#official-resources)
- [Libraries](#libraries)
- [Tools](#tools)
- [Hardware](#hardware)
- [Videos](#videos)
- [Learning Material](#learning-material)


## Official Resources

- [zephyrproject.org](https://www.zephyrproject.org/) - Official website.
- [docs.zephyrproject.org](https://docs.zephyrproject.org/) - Project documentation.
- [github](https://github.com/zephyrproject-rtos) - Project GitHub organization.
  - [zephyr](https://github.com/zephyrproject-rtos/zephyr) - Main repo.
  - [west](https://github.com/zephyrproject-rtos/west) - Swiss-army knife command line tool.
  - [sdk-ng](https://github.com/zephyrproject-rtos/sdk-ng) - Next generation toolchains & host tools.
  - [example-application](https://github.com/zephyrproject-rtos/example-application) - Example out-of-tree application that is also a module.
  - [docker-image](https://github.com/zephyrproject-rtos/docker-image) - Docker image suitable for development and CI.
- [discord](https://discord.com/invite/Ck7jw53nU2) - Community chat hosted on Discord.
- [mailing list](https://lists.zephyrproject.org/g/main/subgroups) - Mail & web based mailing list powere by Groups.io.
- [youtube](https://www.youtube.com/c/ZephyrProject) - Conferences videos and event highlights.
- [blog](https://www.zephyrproject.org/community/#blog) / [RSS](https://www.zephyrproject.org/category/blog/feed/) - Posts from the project and community.
- [twitter](https://twitter.com/zephyriot) / [linkedin](https://www.linkedin.com/company/the-zephyr-project) / [facebook](https://www.facebook.com/ZephyrIoT/) - Various social feeds.
- [newsletter](https://www.zephyrproject.org/newsletter/) - Quarterly newsletter.
- [ambassadors](https://www.zephyrproject.org/ambassadors/) - List of community experts.
- [vulnerability alert registry](https://www.zephyrproject.org/vulnerability-registry/) - Email notifications of vulnerabilties.
- [store](https://zephyr-project.myspreadshop.com/) - Get merch.
- [job board](https://www.zephyrproject.org/careers/) - Search roles from Zephyr member companies.


## Libraries

### Application frameworks

- [arduino-on-zephyr](https://github.com/soburi/arduino-on-zephyr) - Early attempt at an Arduino API layer and distribution through the Arduino IDE.
- [chre](https://github.com/zephyrproject-rtos/chre) - Context Hub Runtime Environment (CHRE) is Android’s platform for developing always-on applications, called nanoapps.
- [micro_ros_zephyr_module](https://github.com/micro-ROS/micro_ros_zephyr_module) - ROS 2 for microcontrollers.
- [open-amp](https://github.com/zephyrproject-rtos/open-amp) - Open Asymmetric Multi Processing (OpenAMP) framework.
- [Sense-VM](https://github.com/svenssonjoel/Sense-VM) - Bytecode virtual machine for microcontrollers.
- [wasm-micro-runtime](https://github.com/bytecodealliance/wasm-micro-runtime) - Lightweight standalone WebAssembly (WASM) runtime.
- [zpp](https://github.com/lowlander/zpp) - C++20 framework.

### Filesystem

- [fats](https://github.com/zephyrproject-rtos/fatfs) - Generic FAT/exFAT filesystem module for small embedded systems.
- [littlefs](https://github.com/zephyrproject-rtos/littlefs) - Little fail-safe filesystem designed for microcontrollers.
- [nffs](https://github.com/zephyrproject-rtos/nffs) - Flash file system prioritizing minimal ram usage & reliability.

### HAL/PAL

- [cmsis](https://github.com/zephyrproject-rtos/cmsis) - Standardized API for the Cortex-M processor core and peripherals.
- [libmetal](https://github.com/zephyrproject-rtos/libmetal) - Abstraction layer across user-space Linux, baremetal, and RTOS environments.

### IoT & Cloud

- [Anjay-zephyr](https://github.com/AVSystem/Anjay-zephyr) - C implementation of the client-side OMA LwM2M protocol.
- [Edge Impulse](https://github.com/edgeimpulse/example-standalone-inferencing-zephyr) - Machine learning on edge devices.
- [Golioth](https://github.com/golioth/zephyr-sdk) - Device Management & cloud enablement platform.
- [Memfault](https://github.com/memfault/memfault-firmware-sdk/tree/master/ports/zephyr) - Cloud-based debugging & observability.
- [openhaystack-zephyr](https://github.com/koenvervloesem/openhaystack-zephyr) - Track personal Bluetooth devices via Apple's massive Find My network.
- [send-my-sensor](https://github.com/koenvervloesem/send-my-sensor) - Upload sensor data from a device without internet connection by (ab)using Apple's Find My network.

### Networking & Protocols

- [canopennode](https://github.com/zephyrproject-rtos/canopennode) - CANopen Stack.
- [civetweb](https://github.com/zephyrproject-rtos/civetweb) - Embeddable web server.
- [CBOR](https://cbor.io/) - Concise Binary Object Representation.
  - [tinycbor](https://github.com/zephyrproject-rtos/tinycbor) - Small CBOR library.
  - [QCBOR](https://github.com/laurencelundblade/QCBOR) - Comprehensive CBOR library.
  - [zcbor](https://github.com/NordicSemiconductor/zcbor/) - CBOR library that includes support for CDDL.
- [cosy](https://github.com/lindemer/cozy) - CBOR Object Signing and Encryption (COSE).
- [greybus-for-zephyr](https://github.com/cfriedt/greybus-for-zephyr) - Protocol for hotpluggable devices.
- [nanopb](https://github.com/zephyrproject-rtos/nanopb) - Protocol Buffers for Embedded Systems.
- [openthread](https://github.com/zephyrproject-rtos/openthread) - Thread mesh networking protocol.
- [pjon](https://github.com/gioblu/PJON) - Multi-master, multi-media network protocol.

### Security

- [mbed TLS](https://github.com/zephyrproject-rtos/mbedtls) - C library that implements cryptographic primitives, X.509 certificate manipulation and the SSL/TLS and DTLS protocols.
- [MCUboot](https://github.com/zephyrproject-rtos/mcuboot) - A secure bootloader for 32-bits microcontrollers.
- [TF - M](https://github.com/zephyrproject-rtos/trusted-firmware-m) - Platform Security Architecture (PSA) for ARMv7-M and Armv8-M.
- [tinycrypt](https://github.com/zephyrproject-rtos/tinycrypt) - Cryptographic library with a minimal set of standard cryptography primitives.

### Misc

- [ecfw-zephyr](https://github.com/intel/ecfw-zephyr) - Embedded Controller for low-level tasks on a motherboard like power sequencing.
- [grbl](https://github.com/iwasz/zephyr-grbl) -Motion control for CNC milling.
- [lvgl](https://github.com/zephyrproject-rtos/lvgl) - Complete graphics library.
- [lz4](https://github.com/zephyrproject-rtos/lz4) - Extremely Fast Compression algorithm.
- [pinetime-zephyr](https://github.com/najnesnaj/pinetime-zephyr) - Smartwatch operating system.
- [zephyr-rust](https://github.com/tylerwhall/zephyr-rust) - API bindings, libstd, and Cargo integration for Rust.
- [linaro_sensor_pipeline](https://github.com/microbuilder/linaro_sensor_pipeline) - Secure data pipelines.
- [sof](https://github.com/zephyrproject-rtos/sof) - Audio Digital Signal Processing (DSP) firmware infrastructure and SDK.
- [tflite-micro](https://github.com/zephyrproject-rtos/tflite-micro) - TensorFlow Lite for Microcontrollers.
- [zscilib](https://github.com/zephyrproject-rtos/zscilib) - Scientific computing library.
- [zcalendar](https://github.com/bpbradley/zcalendar) - Calendar API with RTC integration.
- [zmk](https://github.com/zmkfirmware/zmk) - Keyboard firmware with a rich featureset and broad hardware support.

## Tools

### Build & Config

- [bazel2zephyr](https://github.com/GatCode/bazel2zephyr) - Embedded/bare-metal development using bazel.
- CMake
- Device Tree
- KConfig
- Make
- Ninja

### Compilers

Note: the official SDK includes several compilers.

- GNU Arm Embedded
- Arm Compiler 6
- Intel oneAPI Toolkit
- DesignWare ARC MetaWare Development Toolkit (MWDT)
- Cadence Tensilica Xtensa C/C++ Compiler (XCC)
- Espressif tools

### Editors & IDEs

- [Eclipse](https://github.com/zephyrproject-rtos/eclipse-plugin)
- [nRF Connect for VS Code](https://marketplace.visualstudio.com/items?itemName=nordic-semiconductor.nrf-connect)
- [PlatformIO](https://docs.zephyrproject.org/latest/guides/platformio/index.html)
- [VS Code importer](https://github.com/smrtos/Zephyr2VSC)
- [Zephyrus](https://github.com/tuScale/vscode-zephyrus)

### Flash, Debug & Test

- Atmel SAM-BA
- [EDTT (Embedded Device Test Tool)](https://github.com/zephyrproject-rtos/edtt)
- esptool
- [GNU Tools (GDB, Binutils)](https://github.com/zephyrproject-rtos/binutils-gdb)
- [mcumgr](https://github.com/zephyrproject-rtos/mcumgr)
  - [Android](https://github.com/NordicSemiconductor/Android-nRF-Connect-Device-Manager)
  - [iOS](https://github.com/NordicSemiconductor/IOS-nRF-Connect-Device-Manager)
  - [Web](https://github.com/boogie/mcumgr-web)
- [OpenOCD](https://github.com/zephyrproject-rtos/openocd)
- pyOCD
- [SEGGER](https://github.com/zephyrproject-rtos/segger) / [J-Link](https://github.com/zephyrproject-rtos/libjaylink)
- Twister

### Simulation

- ACRN
- [QEMU](https://github.com/zephyrproject-rtos/qemu)
  - [Network Tools](https://github.com/zephyrproject-rtos/net-tools)
  - [SeaBIOS](https://github.com/zephyrproject-rtos/seabios)
- [Renode](https://zephyr-dashboard.renode.io/)
- XEN


## Hardware


## Videos

- [Zephyr Developer Summit - June 2021](https://www.youtube.com/playlist?list=PLzRQULb6-ipG39tVb-DEkIoSS5wQlbK6i)
- [Embedded Linux Conference/Open Source Summit (Sept. 2021)](https://www.youtube.com/playlist?list=PLzRQULb6-ipEfltSXvM0xBuU84B8-sum7)
- [Zephyr videos from Golioth](https://www.youtube.com/playlist?list=PLXGira7Qd83DljhI7F3euGgsf4hbvhoNp)
- [#zephyrrtos](https://www.youtube.com/hashtag/zephyrrtos) - Videos tagged with `#zephyrrtos`.


## Learning Material

- [Tutorial for Beginners](https://github.com/maksimdrachov/zephyr-rtos-tutorial)
- [Nordic Developer Academy](https://www.nordicsemi.com/Support/Nordic-Developer-Academy)


## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
