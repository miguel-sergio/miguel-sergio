# Miguel Sergio

*Embedded Firmware Engineer - MCU/MPU, RTOS, bare-metal and low-level drivers.*

## Who I am

I build embedded firmware for MCU/MPU-based products. I focus on bare-metal and RTOS systems with clear architecture, observability and fault handling. I build firmware that not only works, but can be trusted in production.

I navigate datasheets and reference manuals to bring up peripherals from scratch, mapping register-level behavior, understanding clock trees, and configuring hardware without relying on vendor HALs. Platform or silicon family doesn't matter. If there's documentation, I can work with it.

## What I'm working on

Embedded Linux RFID Access Control System: A minimal Linux image built with Buildroot running on a Raspberry Pi. The system reads RFID cards over SPI (RC522 module), validates access against a local list, and logs every entry event. No cloud dependency or unnecessary packages, purpose-built for a deployment in a commercial product where reliability and a lean footprint matter more than features.

## Tools I work with

```
MCUs & cores     ARM Cortex-M (M0/M3/M4/M7), adaptable to any architecture
Embedded Linux   Buildroot, custom Linux images, SPI/I2C peripheral drivers
Languages        C, C++, Python (scripting, validation, tooling)
RTOS             FreeRTOS
Peripherals      UART, SPI, I2C, ADC, PWM, DMA, EXTI, IWDG, MPU
Toolchain        cross-compilation toolchain (GCC-based), Make, CMake
Debug            GDB, OpenOCD, JTAG/SWD
Quality          CppUTest, gcovr, cppcheck, lizard, Doxygen
CI / infra       GitHub Actions, Docker
```
