# CROSSROAD-LAB-MICRO-1284P-LoRa

![MICRO 1284P + LoRa](https://user-images.githubusercontent.com/83240004/137491478-bcd28afb-2a56-4892-b1c9-c72da33535a1.png)

## GENERAL INFORMATION

#### MICRO 1284P + LoRa is an open-source microcontroller based on the ATmega1284P. It has 24 digital input / output pins (6 of which can be PWM outputs), 8 analog input pins, a 16 MHz crystal oscillator, a pin header for the ICSP, a reset button, a led and there is a LoRa module for wireless communication. To power the microcontroller you can use the 5 volts of the serial or from 7 volts to 35 volts from the Vin pin (use one of the two methods, not both together). With its small size it allows its insertion in very compact projects and thanks to the presence of the LoRa module it is suitable for IoT applications.

## CORE SPECIFICATION

| Syntax      | Description | 
| :----:        |    :----:   |
| Memory type      | Flash       |
| Memory dimension (KB)   | 128        | 
| CPU Speed (MIPS/DMIPS)      | 20       |
| SRAM (B)   | 16384        | 
| EEPROM/HEF (bytes)      | 4096       |
| Communication Devices   | 2-UART, 3-SPI, 1-I2C        | 
| PWM      | 6 PWM pin       |
| Timer   | 2x8-bit, 2x16-bit        | 
| Number of comparators      | 1       |
| Operating temperature (°C)   | -40 to 85        | 
| Operating voltage   | 1.8 to 5.5        |

## PINOUT
#### Coming Soon

##WHAT IS LoRa?

#### LoRa (Long Range) is an expanded spectrum frequency modulation technology that uses free sub-gigahertz radio frequency bands such as 433 MHz, 868 MHz (Europe) and 915 MHz (North America). LoRa allows long-range transmissions (over 10 km in rural areas, 3–5 km in highly urbanized areas) with low energy consumption.

## HOW TO USE THE MODULE

#### The module used is a Ra-01 LoRa SX1278. There is a logic level converter between the module and the MICRO that allows the correct operation of the LoRa module and a switch to activate it. 

| Semtech SX1276/77/78/79 | MICRO 1284P |
| :---------------------: | :------:|
| VCC | 3.3V |
| GND | GND |
| SCK | D7 (SCK) |
| MISO | D6 (MISO) |
| MOSI | D5 (MOSI) |
| NSS | D4 (SS) |
| NRESET | 3 |
| DIO0 | 2 |

#### The libraries used for its operation were created by Sandeep Mistry and suitably modified for full operation with MICRO 1284P + LoRa. For more information, you can visit the libraries GitHub page (https://github.com/sandeepmistry/arduino-LoRa#readme).
#### To install the libraries you can follow this guide: https://www.arduino.cc/en/guide/libraries#toc4



