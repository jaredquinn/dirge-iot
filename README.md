# dirge-iot
Multipurpose ESP based IoT vehicle system.

Work in progress.  Currently Untested

Hardware initial revisions.

## The Name

This project is named for my good friend Caitlin's Roller Derby Name "Dirge" who asked me about solutions for placing sensors and automation around her bus conversion project.

## Features

* TPS54202 Based 12V to 5V Converter
* Dual AO4407A 30V 12A Switching channels (12V SW1 & SW2)
* 12V Input Voltage Monitoring
* AHT20 Temperature/Humidity Sensor
* Jumper selectable Supply MCU 5V from USB, 5V BUS or 12V Supply
* Enable/Disable 12V to 5V buck jumper

* MCP2562 / MCP2515 5V CAN (Controller Area Network) Bus Driver
* 4 Normally Open Button Inputs (supports momentary & toggles)
* 2 TTL (3V3) Output Signals (not for power supply)
* TXB0104PWR IC 4bit Bi-directional Level Shifter
  * UART TX / RX
  * LED Pixel Pusher 5V Data CH1/CH2
* 6 DIP Switches 
  * 1-4=Config/Multiplexed with BTN INs
  * 5=Enable 5V Level Shifter PXL/UARTs
  * 6=Terminate CAN bus with 120Ohm


# TODO

Test Design
