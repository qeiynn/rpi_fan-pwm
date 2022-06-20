# Rpi_Fan-PWM

Python script to control the curve of a 5V PWM. Optimized for NF-A4x10 and NF-A4x20 5V PWM noctua fans. 

## Install

1. [Connect to your Raspberry Pi via SSH]
2. Clone this repo: 
```
sudo git clone https://github.com/qeiynn/rpi_fan-pwm.git
```
3. Inside folder run the installation script: 
```
sudo bash install
```
4. Delete the downloaded directory. From one directory up, run:
```
sudo rm -r rpi_power-button
```

## Hardware / Wiring

A normally-open (NO) push button is required.
Connect the power button to the GPIO's Pin 5 (SCL) and Pin 6 (GND).

```
40-Pin Layout - RPI 3b(+), 4, Zero (W)

  5v  gnd      pwm   
· |·| |·| ·  · |·| ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·  · 
·  ·   ·  ·  ·  ·  ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·  · 
        
(microSD input)
      (HDMI input)
```
