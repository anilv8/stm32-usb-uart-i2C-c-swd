# STM32 with USB + UART + I2C + SWD
STM32F103C8T6 with USM micro B, UART, I2C and SWD.
Dimensions: 42 mm x 30 mm
# Schematic of circuit
![stm32-schematic-](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/a39be852-f537-4776-9b62-07ca1ed63107)

### ERC Result
![stm32-erc](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/e754d8cd-73cd-46c9-8e1e-9053cf024656)

# PCB Board
![stm32-pcb-front-copper](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/d1f61f0b-a2f8-4324-b178-103c8ec8be87)
![stm32-pcb-back-copper](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/4d277870-99e1-4488-8148-54ddc79f34aa)
![stm32-pcb-front-silkscreen](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/56c3c98f-1689-45cf-8653-edeed01e2ea3)


### DRC Result
![stm32-drc](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/7635af0a-f724-41aa-9d86-54b24afc4f18)

### 3D view of PCB
Front:
![stm32-3d-front](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/895b1a41-4377-4b27-8c16-733a91673106)

Back:
![stm32-3d-back](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/6e116820-403e-4438-b38c-f98dd038ebf5)

# Gerber
![stm32-gerber-front-copper](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/6a6a438e-b507-4b29-b859-b939e29b948c)
![stm32-gerber-back-copper](https://github.com/anilv8/stm32-usb-uart-i2c-swd/assets/81171588/39482d16-88c0-4cea-8039-6082638e0764)

# BOM
| Ref | Qnty | Value | Cmp name | Footprint | Description | Vendor | DNP |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| C1 C2 C3 C4 C9 | 5 | 100n | C | Capacitor_SMD:C_0402_1005Metric | Unpolarized capacitor |  | |
| C5 | 1 | 10u | C | Capacitor_SMD:C_0603_1608Metric | Unpolarized capacitor | | |
| C6 | 1 | 10n | C | Capacitor_SMD:C_0402_1005Metric | Unpolarized capacitor | | |
| C7 C8 | 2 | 1u | C | Capacitor_SMD:C_0402_1005Metric | Unpolarized capacitor | | |
| C10 C11 | 2 | 10p | C | Capacitor_SMD:C_0402_1005Metric | Unpolarized capacitor | | |
| C12 C13 | 2 | 22u | C | Capacitor_SMD:C_0805_2012Metric | Unpolarized capacitor | | |
| D1 | 1 | RED| LED | LED_SMD:LED_0603_1608Metric | Light emitting diode | | |
| FB1 | 1 | 120R | FerriteBead | Inductor_SMD:L_0603_1608Metric | Ferrite bead | | |
| J1 | 1 | USB_B_Micro | USB_B_Micro | Connector_USB:USB_Micro-B_Wuerth_629105150521 | USB Micro Type B connector | | |
| J2 J3 J4 | 3 | Conn_01x04_Pin| Conn_01x04_Pin | Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Vertical | Generic connector, single row, 01x04, script generated | | |
| R1 | 1 | 10k | R | Resistor_SMD:R_0402_1005Metric | Resistor | | |
| R2 R3 R4 R5 | 4 | 1k5 | R | Resistor_SMD:R_0402_1005Metric | Resistor | | |
| SW1 | 1 | SW_SPDT | SW_SPDT | Button_Switch_SMD:SW_SPDT_PCM12 | Switch, single pole double throw | | |
| U1 | 1 | STM32F103C8T6 | STM32F103C8Tx | Package_QFP:LQFP-48_7x7mm_P0.5mm | STMicroelectronics Arm Cortex-M3 MCU, 64KB flash, 20KB RAM, 72 MHz, 2.0-3.6V, 37 GPIO, LQFP48  | | |
| U2 | 1 | AMS1117-3.3 | AMS1117-3.3 | Package_TO_SOT_SMD:SOT-223-3_TabPin2 | 1A Low Dropout regulator, positive, 3.3V fixed output, SOT-223 | | |
| Y1 | 1 | 16MHz | Crystal_GND24 | Crystal:Crystal_SMD_3225-4Pin_3.2x2.5mm |Four pin crystal, GND on pins 2 and 4 | | |

# REFERENCES
[1]  https://www.udemy.com/course/learn-kicad-v6-and-stm32-hardware-design/
