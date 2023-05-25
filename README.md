![Dark Logo](assets/awesome_zephyr_rtos_logo_dark.png#gh-dark-mode-only)
![Ligh Logo](assets/awesome_zephyr_rtos_logo_light.png#gh-light-mode-only)

# 🪁 Awesome Zephyr RTOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> The Zephyr RTOS is based on a small-footprint kernel designed for use on resource-constrained and embedded systems: from simple embedded environmental sensors and LED wearables to sophisticated embedded controllers, smart watches, and IoT wireless applications.

[What is an awesome list?](https://github.com/sindresorhus/awesome/blob/main/awesome.md)


## Contents

- [Official Resources](#official-resources)
- [Libraries](#libraries)
- [Tools](#tools)
- [Open Source Hardware](#open-source-hardware)
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

- [gsoc-2022-arduino-core](https://github.com/zephyrproject-rtos/gsoc-2022-arduino-core) - Arduino Core API module with an Arduino-C++ style abtraction layer.
- [chre](https://github.com/zephyrproject-rtos/chre) - Context Hub Runtime Environment (CHRE) is Android’s platform for developing always-on applications, called nanoapps.
- [control](https://github.com/swedishembedded/control) - A control systems design library written in pure C that provides you with advanced algorithms for control, state estimation and model identification specifically designed for use on embedded systems.
- [micro_ros_zephyr_module](https://github.com/micro-ROS/micro_ros_zephyr_module) - ROS 2 for microcontrollers.
- [open-amp](https://github.com/zephyrproject-rtos/open-amp) - Open Asymmetric Multi Processing (OpenAMP) framework.
- [Sense-VM](https://github.com/svenssonjoel/Sense-VM) - Bytecode virtual machine for microcontrollers.
- [Swedish Embedded Platform SDK](https://github.com/swedishembedded/sdk) - Swedish Embedded Platform SDK is a comprehensive platform for firmware development.
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
- [Golioth](https://github.com/golioth/golioth-zephyr-sdk) - Device Management & cloud enablement platform.
- [Memfault](https://github.com/memfault/memfault-firmware-sdk/tree/master/ports/zephyr) - Cloud-based debugging & observability.
- [openhaystack-zephyr](https://github.com/koenvervloesem/openhaystack-zephyr) - Track personal Bluetooth devices via Apple's massive Find My network.
- [send-my-sensor](https://github.com/koenvervloesem/send-my-sensor) - Upload sensor data from a device without internet connection by (ab)using Apple's Find My network.
- [thingset-zephyr-sdk](https://github.com/ThingSet/thingset-zephyr-sdk) - A software development kit (SDK) based on Zephyr RTOS to integrate communication interfaces using the ThingSet protocol into an application with minimum effort. See https://thingset.io/.

### Networking & Protocols

- [BACnet Stack](https://github.com/bacnet-stack/bacnet-stack) - BACnet open source protocol stack for embedded systems, Linux, and Windows.
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
- [S2OPC](https://gitlab.com/systerel/S2OPC) - Open-source OPC-UA Toolkit designed with security and embedded devices in mind.

### Security

- [aerology](https://github.com/Linaro/aerology) - Inspect Zephyr and TF-M applications, post mortem.
- [mbed TLS](https://github.com/zephyrproject-rtos/mbedtls) - C library that implements cryptographic primitives, X.509 certificate manipulation and the SSL/TLS and DTLS protocols.
- [MCUboot](https://github.com/zephyrproject-rtos/mcuboot) - A secure bootloader for 32-bits microcontrollers.
- [TF - M](https://github.com/zephyrproject-rtos/trusted-firmware-m) - Platform Security Architecture (PSA) for ARMv7-M and Armv8-M.
- [tinycrypt](https://github.com/zephyrproject-rtos/tinycrypt) - Cryptographic library with a minimal set of standard cryptography primitives.

### Misc

- [ecfw-zephyr](https://github.com/intel/ecfw-zephyr) - Embedded Controller for low-level tasks on a motherboard like power sequencing.
- [grbl](https://github.com/iwasz/zephyr-grbl) - Motion control for CNC milling.
- [lvgl](https://github.com/zephyrproject-rtos/lvgl) - Complete graphics library.
- [lz4](https://github.com/zephyrproject-rtos/lz4) - Extremely Fast Compression algorithm.
- [pinetime-zephyr](https://github.com/najnesnaj/pinetime-zephyr) - Smartwatch operating system.
- [zephyr-rust](https://github.com/tylerwhall/zephyr-rust) - API bindings, libstd, and Cargo integration for Rust.
- [linaro_sensor_pipeline](https://github.com/microbuilder/linaro_sensor_pipeline) - Secure data pipelines.
- [pysvd2dts](https://github.com/thedigitaledge/pysvd2dts) - Creates a Zephyr Devicetree file from an ARM CMSIS-SVD file.
- [sof](https://github.com/zephyrproject-rtos/sof) - Audio Digital Signal Processing (DSP) firmware infrastructure and SDK.
- [spinner](https://github.com/teslabs/spinner) - Motor control firmware based on the Field Oriented Control (FOC) principles.
- [tflite-micro](https://github.com/zephyrproject-rtos/tflite-micro) - TensorFlow Lite for Microcontrollers.
- [zbus](https://github.com/zephyr-bus/zbus) - Inter thread communication bus.
- [zscilib](https://github.com/zephyrproject-rtos/zscilib) - Scientific computing library.
- [zcalendar](https://github.com/bpbradley/zcalendar) - Calendar API with RTC integration.
- [zmk](https://github.com/zmkfirmware/zmk) - Keyboard firmware with a rich featureset and broad hardware support.

## Tools

### Build & Config

- [bazel2zephyr](https://github.com/GatCode/bazel2zephyr) - Embedded/bare-metal development using bazel.
- CMake
- Device Tree
  - [dtsh](https://github.com/dottspina/dtsh) - Shell-like interface to devicetrees.
- KConfig
- Make
- Ninja
- [Swedish Embedded Platform SDK Docker Image](https://github.com/swedishembedded/develop) - Docker containers for CI & development.

### Compilers

Note: the official SDK includes several compilers.

- GNU Arm Embedded
- Arm Compiler 6
- Intel oneAPI Toolkit
- DesignWare ARC MetaWare Development Toolkit (MWDT)
- Cadence Tensilica Xtensa C/C++ Compiler (XCC)
- Espressif tools

### Editors & IDEs

#### Visual Studio Code

- [Ardesco-VSCode-Extension](https://github.com/Ericsson/Ardesco-VSCode-Extension) - Ericsson Ardesco device development extension.
- [Zephyr Tools for VSCode](https://github.com/circuitdojo/zephyr-tools) - Circuit Dojo designed Zephyr Tools to make getting started with Zephyr a snap.
- [Embedded Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-embedded-tools) - A register viewer for CMSIS-SVD files and an RTOS data viewer
- [nRF Connect for VS Code](https://marketplace.visualstudio.com/items?itemName=nordic-semiconductor.nrf-connect)
- [PlatformIO](https://docs.zephyrproject.org/latest/guides/platformio/index.html)
- [VS Code importer](https://github.com/smrtos/Zephyr2VSC)
- [Zephyrus](https://github.com/tuScale/vscode-zephyrus)

#### Other Editors & IDEs

- [Eclipse](https://github.com/zephyrproject-rtos/eclipse-plugin)
- [CMake Zephyr helpers](https://github.com/thirdpin/Zephyr-CMake-Helpers) - Enhance CMake automation for use with VS Code.

### Flash, Debug & Test

- [Aerology](https://github.com/Linaro/aerology) - Inspect Zephyr and TF-M applications, post mortem.
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


## Open Source Hardware

- [ZSWatch](https://github.com/jakkra/ZSWatch) - The Open Source Zephyr™ based Smartwatch, including both HW and FW.

## Videos

- [Zephyr Developer Summit - June 2021](https://www.youtube.com/playlist?list=PLzRQULb6-ipG39tVb-DEkIoSS5wQlbK6i)
- [Embedded Linux Conference/Open Source Summit (Sept. 2021)](https://www.youtube.com/playlist?list=PLzRQULb6-ipEfltSXvM0xBuU84B8-sum7)
- [Zephyr videos from Golioth](https://www.youtube.com/playlist?list=PLXGira7Qd83DljhI7F3euGgsf4hbvhoNp)
- [#zephyrrtos](https://www.youtube.com/hashtag/zephyrrtos) - Videos tagged with `#zephyrrtos`.


## Learning Material

- [Tutorial for Beginners](https://github.com/maksimdrachov/zephyr-rtos-tutorial)
- [Nordic Developer Academy](https://www.nordicsemi.com/Support/Nordic-Developer-Academy)
- [Ultimate Embedded Firmware DevOps Infrastructure](https://www.udemy.com/course/ultimate-embedded-firmware-devops-infrastructure/)


## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
