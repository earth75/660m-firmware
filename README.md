# 660m-pcb-firmware
A C firmware for the 660m based on STM32CubeMX config files.
See adrientetar/660m for details on the associated hardware.

## Structure
This is sample code that was generated using STM32CUbeMX.

The pin settings, clock and peripherals configuration is described in the STM32CubeMX project (CUBEMX.ioc).

I then added the necessary tools and configuration to automatically build the executable binary into a dfu file, and, if available, load it into a STM32F0 in DFU mode.

The actual code in main.c only blinks the onboard led ATM.
