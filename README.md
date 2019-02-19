## STM32MPU_EmbSW_Overall_Offer Overview

STM32MPU Embedded Software distribution is a set of software components, system build and development tools created to ease the development to be done on top of STM32MPU devices. 

STM32MPU Embedded Software distribution includes: 
* a Linux® distribution, running on the Arm® Cortex®-A processor(s) : [OpenSTLinux distribution](https://wiki.st.com/stm32mpu/index.php/OpenSTLinux_distribution)
* a STM32Cube Package, running on the Arm® Cortex®-M processor : [STM32Cube package](https://wiki.st.com/stm32mpu/index.php/STM32CubeMP1_Package)

**OpenSTLinux distribution** is a Linux® distribution based on the OpenEmbedded build framework.
It includes the following collection of software components: 
* OpenSTLinux BSP (OP-TEE secure OS, boot chain and Linux kernel) 
** The boot chain based on TF-A and U-Boot 
** The OP-TEE secure OS running on the Cortex-A in secure mode 
** The Linux kernel running on the Cortex-A in non-secure mode 
* Application frameworks such as the following Linux application frameworks (non-exhaustive list): 
** Wayland-Weston as a display/graphic framework 
** Gstreamer as a multimedia framework 
** Advanced Linux Sound Architecture (ALSA) libraries 

**STM32Cube™** is a comprehensive embedded software libraries and drivers, delivered for each STM32 series.
   * The CMSIS modules (core and device) corresponding to the ARM(tm) core implemented in this STM32 product
   * The STM32 HAL-LL drivers : an abstraction drivers layer, the API ensuring maximized portability across the STM32 portfolio 
   * The BSP Drivers of each evaluation or demonstration board provided by this STM32 series 
   * A consistent set of middlewares components such as RTOS, OpenAMP, ...
   * A full set of software projects (basic examples, applications or demonstrations) for each board provided by this STM32 series

## Description

This repo is a simple Readme describing all STM32MP1 related GitHub projects, the open source offer for the STM32 MPU products.

### STM32MPU Embedded Software packages 
STM32MP1 Packages | Description
---------------------- | -----------
[oe-manifest](https://github.com/STMicroelectronics/oe-manifest) | STM32MP1 Embedded Software overall manifest
[meta-st-stm32mp](https://github.com/STMicroelectronics/meta-st-stm32mp) | STM32MP1 OpenEmbedded/Yocto BSP layer 
[meta-st-scripts](https://github.com/STMicroelectronics/meta-st-scripts) | STM32MP1 OpenEmbedded/Yocto front-end scripts
[meta-st-openstlinux](https://github.com/STMicroelectronics/meta-st-openstlinux) | STM32MP1 OpenEmbedded/Yocto frameworks layer (demonstrators, images examples, ...)
[meta-st-stm32mp-addons](https://github.com/STMicroelectronics/meta-st-stm32mp-addons) | STM32MP1 OpenEmbedded/Yocto BSP layer addons (CubeMX machine, ...)
[linux](https://github.com/STMicroelectronics/linux) | STM32MP1 linux kernel
[u-boot](https://github.com/STMicroelectronics/u-boot) | STM32MP1 u-boot
[arm-trusted-firmware](https://github.com/STMicroelectronics/arm-trusted-firmware) | STM32MP1 arm trusted firmware (for A7)
[optee_os](https://github.com/STMicroelectronics/optee_os) | STM32MP1 OPTEE OS
[gcnano-binaries](https://github.com/STMicroelectronics/optee_os) | GPU binaries, GPU kernel driver source code
[STM32CubeMP1](https://github.com/STMicroelectronics/STM32CubeMP1) | STM32MP1 Cube co-processing firmware
[linux-examples](https://github.com/STMicroelectronics/linux-examples) | some linux examples
[devicetree-addons](https://github.com/STMicroelectronics/devicetree-addons) | STM32MP1 Boards user sections for CubeMX and device tree examples 

### Communication and support 
For communication and support, you can use
* [ST Support Center](https://my.st.com/ols#/ols/) for any defect
* [ST Community Forum](https://st-microelectronics.jiveon.com/welcome) forum 

