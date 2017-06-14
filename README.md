# ST7735
Hello world Graphics LCD way! This code uses the ST7735 library written by
Oleg Yakovlev (https://github.com/OlegUA/ST7735) with some small modifications 
in order to make it work with the STM32L432KC and newer HAL functions.
UART2 is also enabled and can be used to communicate with the host computer 
using ST-LINK's builtin VCP.
Target board: STM NUCLEO32 (STM32L432KC based)
Pins used:
- PA2 		- UART2 TX (connected do the VCP)
- PA15		- UART2 RX (connected to the VCP)
- PB0 (D3)	- LCD_A0
- PB1 (D6)	- LCD_CS
- PB3 (D13)	- LCD_SCK (SPI1 clock)
- PB4 (D12)	- LCD_RESET
- PB5 (D11)	- LCD_SDA (SPI1 MOSI)

Author:              Fábio Pereira
Date:                06/12/2017
