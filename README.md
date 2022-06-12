# Steg USB-UART Pmod™ compatible module

## Overview

The Steg USB-UART protocol converter module provides a bridge between a USB host and a 12-pin Pmod™ compatible socket configured as a UART.

This repo contains documentation, schematics and pinouts.

Find more information on the [Steg product page](https://machdyne.com/product/steg-usb-uart-pmod/).

## Configuration

Steg can be configured with an MCP2200 utility such as [mcp2200](https://github.com/ipaton0/mcp2200).

## Usage Example

```
$ minicom -D /dev/ttyACM0 -b 115200
```

## Pinout

### 12-pin PMOD Header

| Pin | Signal |
| --- | ------ |
| 1 | RTS |
| 2 | RX |
| 3 | TX |
| 4 | CTS |
| 5 | GND |
| 6 | 3V3 |
| 7 | GPIO0 / SSPND |
| 8 | GPIO1 / USB-CFG |
| 9 | GPIO2 |
| 10 | GPIO3 |
| 11 | GND |
| 12 | 3V3 |

Note: The 3V3 signals are not connected.
