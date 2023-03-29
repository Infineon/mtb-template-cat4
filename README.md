# ModusToobox CAT4 BSP Template Library

## Overview

mtb-template-cat4 provides BSP template files for the BSP Assistant tool. mtb-template-cat4 contains files for the following devices:

* 43907
* 54907

## BSP Configuration

The BSP has a few hooks that allow its behavior to be configured. Some of these items are enabled by default while others must be explicitly enabled. Items enabled by default are specified in the {{ name }}.mk file. The items that are enabled can be changed by creating a custom BSP or by editing the application makefile.

Defines:
* CYBSP_CUSTOM_SYSCLK_PM_CALLBACK - This define, disabled by default, causes the BSP to skip registering its default SysClk Power Management callback, if any, and instead to invoke the application-defined function `cybsp_register_custom_sysclk_pm_callback` to register an application-specific callback.


## More information
* [Development Board Documentation](https://www.cypress.com/documentation/development-kitsboards)
* [Cypress Semiconductor, an Infineon Technologies Company](https://www.cypress.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox™](https://www.cypress.com/products/modustoolbox-software-environment)

---
© Cypress Semiconductor Corporation (an Infineon company) or an affiliate of Cypress Semiconductor Corporation, 2022.
