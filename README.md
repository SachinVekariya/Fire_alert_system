# Fire_alert_system

We develop a system which can detect fire and them alert the owner by sending SMS.

## Component Uses
MQ135 (Smoke Sensor)
BMP180 (Temperature Sensor)
GSM900 (GSM Module)

## I2C_Protocol

Here we use i2c protocol to interface the BMP180 temperature sensor which give the output in binary form.

## UART_Communication

We use uart communication for interfacing the GSM module with microcontroller to send the Messages.Here we use the AVR Atmega128 microcontroller.
