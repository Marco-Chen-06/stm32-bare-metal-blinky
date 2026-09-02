# stm32-bare-metal-blinky

A bare-metal blinky for the STM32L476RG Nucleo. Built with no CubeMX, no HAL, and no IDE. This is the toolchain foundation for an A/B bootloader I am writing, so I wanted to start from the very minimum build.

CMSIS headers are register definitions so I still use them rather than retyping base addresses.

## Notes
The startup file and linker script are from ST. I will work on replacing them with my own minimal ones.
