## FRSKYF3 Board

The Frsky F3 flight controller integrated Frsky's X8R Receiver,OSD and SD Card in one board. This board can select to use MPU6050 or MPU6000(Now the board is mounted with MPU6050).This board has no problem running fast loop times and ESC protocols. There is an On Screen Display (OSD) chip directly connected to the main processor (MCU). And the FC connect to the Receiver with SBUS and S.Port inner. You no longer need to mount another Reciver,and you can transimit FC's messages to Remote by Betaflight.
For maximum ease of use, some FrskyF3's board has an onboard PDB up to 6s with a battery XT60 JACK.Just plug your battery straight into the flight controller and you're ready to go!

## MCU, Sensors and Features

## Hardware

  MCU: STM32F3
  IMU: MPU6050(I2C) [--MPU6000 (SPI)]
  IMU Interrupt: Yes
  VCP: Yes
  Hardware UARTS: 3(UART2-->SBUS UART3-->S.PORT)
  OSD: BFOSD
  Blackbox: SD Card
  Battery Voltage Sensor: yes
  Integrated Voltage Regulator: Yes, supports up to 6S, 1AMP
  Brushed Motor Mosfets: No
  Buttons: 2 (1: DFU, 2:Receiver Bind)

## Features

  Current Sensor: PB2
  BlHeli passthrough: Yes
  WS2811 Led Strip: Yes
  Transponder: Yes
  Beeper: Inverted
  Receiver: Frsky X8R
  RSSI:SBUS channel 8

## Manufacturers and Distributors
  Frsky(Manufacturers)

  Available here soon:http://www.frsky-rc.com

## Designers

  Frsky Co.Lt

## Maintainers

  shang2017

## Differences:

  add Receiver with FC on one board

