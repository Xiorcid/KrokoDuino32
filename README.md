# KrokoDuino32
Prototyping board with ATmega16/32/8535 MCU and USB-UART converter

![изображение](https://user-images.githubusercontent.com/128717394/227247465-9b1ca533-6510-4b5c-b8e7-752fb4afa702.png)
<br></br>
Supported MCUs - find the best:
|                  | MEGA32 | MEGA16 | MEGA8535 |
|------------------|--------|--------|----------|
| **Flash**        | 32k    | 16k    | 8k       |
| **RAM**          | 2k     | 1k     | 512b     |
| **EEPROM**       | 512b   | 512b   | 512b     |
| **PWM pins**     | 4      | 4      | 4        |
| **IO pins**      | 32     | 32     | 32       |

Board has CH340G (CH340C supported, don't solder X2, C3, C4) USB-UART converter, you can use bootloader and upload programs from Arduino IDE (with core for your MCU).
