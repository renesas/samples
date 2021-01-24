--- 
# Renesas comments
* This reposiory wiki has:
  * some information about Renesas specific tools.
  * some other experimental projects for example:
    * GR-ROSE (RX65N)
    * etc
--- 
# Microfost reference
--- 
# Azure RTOS - Additional samples

This repository hosts additional samples for Azure RTOS.

Additional Azure IoT SDK Plug and Play API support can be found on the [feature/iot_pnp](https://github.com/azure-rtos/netxduo/tree/feature/iot_pnp) branch.

## Embedded IDE samples

You can find Embedded IDE (IAR Workbench and semi's IDE) sample projects in addition to the content in the [getting-started repository](https://github.com/azure-rtos/getting-started). Each board-specific sample project contains a series of projects that cover Azure RTOS components (ThreadX, NetX Duo, GUIX, FileX and USBX) as well as connecting to Azure IoT samples using Azure IoT Middleware for Azure RTOS depending on the actual capability of the board.

The following ZIP files can be downloaded from the [release](https://github.com/azure-rtos/samples/releases) associated with this repository or the direct links:

* [Azure_RTOS_6.1_ATSAME54-XPRO_IAR_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_ATSAME54-XPRO_IAR_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_ATSAME54-XPRO_MPLab_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_ATSAME54-XPRO_MPLab_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_MIMXRT1060_IAR_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_MIMXRT1060_IAR_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_MIMXRT1060_MCUXpresso_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_MIMXRT1060_MCUXpresso_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_STM32F746G-DISCO_IAR_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_STM32F746G-DISCO_IAR_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_STM32F746G-DISCO_STM32CubeIDE_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_STM32F746G-DISCO_STM32CubeIDE_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_STM32L4+-DISCO_IAR_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_STM32L4+-DISCO_IAR_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_STM32L4+-DISCO_STM32CubeIDE_Samples_2020_10_10.zip
](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_STM32L4+-DISCO_STM32CubeIDE_Samples_2020_10_10.zip)
* [Azure_RTOS_6.1_Renesas_RZA1_RSK_IAR_Samples_2020_12_09.zip](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_Renesas_RZA1_RSK_IAR_Samples_2020_12_09.zip)
* [Azure_RTOS_6.1_Renesas_RZA1_RSK_E2Studio_2021_01_08.zip](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_Renesas_RZA1_RSK_E2Studio_2021_01_08.zip)
* [Azure_RTOS_6.1_Renesas_RX65N_RSK_2MB_e2studio_ccrx_Sample_2021_01_08.zip](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_Renesas_RX65N_RSK_2MB_e2studio_ccrx_Sample_2021_01_08.zip)
* [Azure_RTOS_6.1_Renesas_RX65N_RSK_2MB_e2studio_gnurx_Sample_2021_01_08.zip](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_Renesas_RX65N_RSK_2MB_e2studio_gnurx_Sample_2021_01_08.zip)
* [Azure_RTOS_6.1_Renesas_RX65N_RSK_2MB_IAR_Sample_2021_01_08.zip](https://github.com/azure-rtos/samples/releases/download/v6.1_rel/Azure_RTOS_6.1_Renesas_RX65N_RSK_2MB_IAR_Sample_2021_01_08.zip)

> NOTE: These zip files are completely self-contained and include appropriate code from the other Azure RTOS repositories. Please refer to the LICENSE.txt file in each ZIP file for licensing requirements.

The [MXChip AZ3166 IoT DevKit](https://aka.ms/iot-devkit) is currently supported by the [getting-started](https://github.com/azure-rtos/getting-started/tree/master/MXChip/AZ3166) guide. And you can also download the whole CMake project as ZIP file from:

* [Getting_started_with_the_MXChip_AZ3166_IoT_DevKit.zip
](https://github.com/azure-rtos/getting-started/releases/download/183899/Getting_started_with_the_MXChip_AZ3166_IoT_DevKit.zip)

## Azure RTOS with Azure Sphere samples

The Azuure RTOS and Azure Sphere better together sample can be found at:

https://github.com/Azure-Samples/Azure-RTOS-on-Azure-Sphere-Mediatek-MT3620

This sample demonstrates how Azure Sphere and Azure RTOS are able to run together on the MediaTek MT3620 Development Kit.
