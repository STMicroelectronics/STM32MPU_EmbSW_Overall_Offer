## STM32MPU_EmbSW_Overall_Offer Overview


STM32MPU Embedded Software distribution is a set of software components, system build and development tools created to ease the development to be done on top of STM32MPU devices. 

STM32MPU Embedded Software distribution includes: 
* A Linux® distribution, running on the Arm® Cortex®-A processor(s) : [OpenSTLinux distribution](https://wiki.st.com/stm32mpu/index.php/OpenSTLinux_distribution)
* A STM32Cube Package, running on the Arm® Cortex®-M processor : [STM32Cube package](https://wiki.st.com/stm32mpu/index.php/STM32CubeMP1_Package)

**OpenSTLinux distribution** is a Linux® distribution based on the OpenEmbedded build framework.
It includes the following collection of software components. 
* OpenSTLinux BSP (OP-TEE secure OS, boot chain and Linux kernel): 
  * The boot chain based on TF-A and U-Boot 
  * The OP-TEE secure OS running on the Cortex®-A in secure mode 
  * The Linux kernel running on the Cortex®-A in non-secure mode 
* Application frameworks such as the following Linux application frameworks (non-exhaustive list): 
  * Wayland-Weston as a display/graphic framework 
  * Gstreamer as a multimedia framework 
  * Advanced Linux Sound Architecture (ALSA) libraries 

**STM32Cube™** is a comprehensive embedded software libraries and drivers, delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the Arm® core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio 
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series 
   * A consistent set of middlewares components such as RTOS, OpenAMP, ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series

## Description

This repo is a simple Readme describing all STM32MPU related GitHub projects, the open source offer for the STM32 MPU products.

### STM32MPU Embedded Software packages 
OpenSTLinux Packages | Description
---------------------- | -----------
[oe-manifest](https://github.com/STMicroelectronics/oe-manifest) | STM32MPU Embedded Software overall manifest
[meta-st-stm32mp](https://github.com/STMicroelectronics/meta-st-stm32mp) | STM32MPU OpenEmbedded/Yocto BSP layer 
[meta-st-scripts](https://github.com/STMicroelectronics/meta-st-scripts) | STM32MPU OpenEmbedded/Yocto front-end scripts
[meta-st-openstlinux](https://github.com/STMicroelectronics/meta-st-openstlinux) | STM32MPU OpenEmbedded/Yocto frameworks layer (demonstrators, images examples, ...)
[meta-st-stm32mp-addons](https://github.com/STMicroelectronics/meta-st-stm32mp-addons) | STM32MPU OpenEmbedded/Yocto BSP layer addons (CubeMX machine, ...)
[linux](https://github.com/STMicroelectronics/linux) | STM32MPU linux kernel on ***-stm32mp branch**
[u-boot](https://github.com/STMicroelectronics/u-boot) | STM32MPU u-boot on ***-stm32mp branch**
[arm-trusted-firmware](https://github.com/STMicroelectronics/arm-trusted-firmware) | STM32MPU arm trusted firmware (for A7) on ***-stm32mp branch**
[optee_os](https://github.com/STMicroelectronics/optee_os) | STM32MPU OPTEE OS on ***-stm32mp branch**
[gcnano-binaries](https://github.com/STMicroelectronics/gcnano-binaries) | GPU binaries, GPU kernel driver source code
[linux-examples](https://github.com/STMicroelectronics/linux-examples) | Some linux examples
[st-openstlinux-application](https://github.com/STMicroelectronics/st-openstlinux-application) | STM32MPU boards default applications
[optee-stm32mp-addons](https://github.com/STMicroelectronics/optee-stm32mp-addons) | STM32MPU features and add-ons around the OP-TEE ecosystem
[dt-stm32mp](https://github.com/STMicroelectronics/dt-stm32mp) | STM32MP2 STM32 MPU embedded software device tree configurations addons
[ddr-phy](https://github.com/STMicroelectronics/stm32-ddr-phy-binary) | Firmware for DDR PHY on STM32MP2


Other MPU Packages | Description
---------------------- | -----------
[STM32CubeMP2](https://github.com/STMicroelectronics/STM32CubeMP2) | STM32MP2 Cube running in non secure M33 context
[STM32CubeMP1](https://github.com/STMicroelectronics/STM32CubeMP1) | STM32MP1 Cube running in non secure M4 context
[STM32CubeMP13](https://github.com/STMicroelectronics/STM32CubeMP13) | STM32MP13 Cube A7 firmware
[trusted-firmware-m](https://github.com/STMicroelectronics/trusted-firmware-m) | STM32MP2 Trusted Firmware-M running in secure M33 context
[SCP-firmware](https://github.com/STMicroelectronics/SCP-firmware) | STM32MPU SCP-firmware on ***-stm32mp branch-***
[OpenBMC-stm32mpu](https://github.com/STMicroelectronics/openbmc-stm32mpu) | How to set up openBMC for STM32MPU
[meta-st-ota](https://github.com/STMicroelectronics/meta-st-ota) | STM32MPU Yocto layer to demonstrate how the secure firmware update is working in OpenSTLinux.

### STM32MPU Tools packages 
STM32MPU Packages | Description
---------------------- | -----------
[STM32DDRFW-UTIL](https://github.com/STMicroelectronics/STM32DDRFW-UTIL) | STM32MPU firmware used to initialize DDR and perform DDR tests
[STM32PRGFW-UTIL](https://github.com/STMicroelectronics/STM32PRGFW-UTIL) | STM32MPU multiple applications to manage the One-time Programmable (OTP)
[stm32wrapper4dbg](https://github.com/STMicroelectronics/stm32wrapper4dbg) | STM32MPU tool that adds a debug wrapper to a stm32 fsbl image
[wiki-stm32mp-addons](https://github.com/STMicroelectronics/wiki-stm32mp-addons) | STM32MPU wiki content outside wiki

### STM32 MPU Expansion Packages 
X-LINUX Packages | Description
---------------------- | -----------
[X-LINUX-AI](https://github.com/STMicroelectronics/meta-st-stm32mpu-ai) | OE meta layer to install AI frameworks and tools for the STM32MPU
[X-LINUX-RT](https://github.com/STMicroelectronics/meta-st-x-linux-rt) |  OE meta layer to get the [X-LINUX-RT](https://www.st.com/en/embedded-software/x-linux-rt.html) expansion package
[X-LINUX-PREDMNT](https://github.com/STMicroelectronics/meta-predmnt) | OE meta layer to get the ST Predictive Maintenance Platform application
[X-LINUX-GNSS1](https://github.com/STMicroelectronics/meta-st-x-linux-gnss1) | OE meta layer to get the [X-LINUX-GNSS1](https://www.st.com/en/embedded-software/x-linux-gnss1.html) expansion package
[X-LINUX-SPN1](https://github.com/STMicroelectronics/x-linux-spn1) | OE meta layer to get the [X-LINUX-SPN1](https://www.st.com/en/embedded-software/x-linux-spn1.html) expansion package
[X-LINUX-TSNSWCH](https://github.com/STMicroelectronics/meta-st-stm32mp-tsn-swch) | STM32MP2 Expansion Package that targets the Time-Sensitive Networking (TSN) switch
[X-LINUX-ACM](https://github.com/STMicroelectronics/meta-st-stm32mp-tsn-acm) | STM32MP2 Expansion Package providing a distribution package to generate a series of software to manage ACM
[X-LINUX-AZURE](https://github.com/STMicroelectronics/meta-st-x-linux-azure) | STM32 MPU OpenSTLinux Expansion Package that targets Microsoft Azure IoT Edge for STM32MP25xx product microprocessors
[X-LINUX-AWS](https://github.com/STMicroelectronics/meta-st-x-linux-aws) | STM32 MPU OpenSTLinux Expansion Package that targets Amazon Web Services® AWS IoT GreengrassTM V2 for STM32MP13 and STM32MP25 product microprocessors
[X-LINUX-QT](https://github.com/STMicroelectronics/meta-st-x-linux-qt) | STM32 MPU OpenSTLinux Expansion Package that targets Qt based application and graphical user interface (GUI) development for the STM32MP25xx series microprocessors
[X-LINUX-TPM](https://github.com/STMicroelectronics/meta-st-x-linux-tpm) | It brings the support of STPM4RasPI expansion board into the OpenSTLinux distribution
[X-LINUX-ISP](https://github.com/STMicroelectronics/meta-st-x-linux-isp) | Open-source software package providing ISP (Image Signal Processing) image quality software targeting the STM32MP25x series that embed an ISP camera pipeline called
[X-LINUX-IGWWSN1](https://github.com/STMicroelectronics/x-linux-igwwsn1) | STM32 MPU OpenSTLinux Expansion Package for Industrial WSN edge gateway - Connecting Sensors to the Cloud
[X-LINUX-IGTW1](https://github.com/STMicroelectronics/x-linux-igtw1) | Linux-based expansion software package designed for industrial application development on STM32 MPU


X-Cube Packages | Description
---------------------- | -----------
[x-cube-freertos-mpu](https://github.com/STMicroelectronics/x-cube-freertos-mpu) | Full integration of FreeRTOS in the STM32Cube environment for the STM32CUBEMP13 series V1.1.0. 

## Communication and support 
For communication and support, you can use
* [ST Support Center](https://my.st.com/ols#/ols/) for any defect
* [ST Community MPU](https://community.st.com/s/topic/0TO0X0000003u2AWAQ/stm32-mpus) forum 

