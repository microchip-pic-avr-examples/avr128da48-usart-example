<img src="images/microchiptechnologyinc.png" height="60">

# AVR128DA48 USART Hello World Example

This repository provides an Atmel Studio solution with a bare metal code example for a basic USART communication.

The example demonstrates the basic functionality of the USART peripheral. The message "Hello world!" is sent through TXd pin.

## Configurations

- USART1:
  * Baud rate 9600
  * Transmitter enabled
  * Data format to 8-bit
  * PC0 as TXd
  * PC1 as RXd

<img src="images/AVR128DA48_CNANO_instructions.PNG" height="250">

## Required Tools

- Atmel Studio 7.0.2397 or newer
- AVR-Dx 1.0.18 or newer Device Pack
- AVR128DA48 Curiosity Nano (DM164151)

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.
