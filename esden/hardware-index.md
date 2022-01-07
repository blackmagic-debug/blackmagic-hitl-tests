# This is @esden's hardware collection

This index is currently a work in progress. The goal is to collect all the hardware I can test Black Magic Probe with.

All of the hardware can be used for a manual test. Some of the the hardware will be hooked up to the automated HITL CI test system.

## Target boards

### ARM
* Atmel
  * ATSAMD10D14A-MUT - SAMD10 XMINI
  * ATSAMD51J19A-U - Adafruit Metro M4 express
* Freescale
  * MCIMX7D5EVM10SC - Toradex Aster Rev. 1.1
  * MK20DX128VLH5 - FRDM-K20D50M
  * MK22FN512VLH12 - FRDM-K22F
  * MKL03Z32VFK4 - FRDM-KL03Z
  * MKL25Z128FRDM - FRDM-KL25Z
  * PK20DX256VLL7 - TWR-K20D72M
  * PK21DN512V - TWR-K21D50M
  * PK21FN1M0VMC10 - TWR-K21D50M
* GigaDevice
  * GD32F103VCT6 - GD32103C-EVAL 2020-4 V1.2
  * GD32E231C8T6 - GD32E231C-START 2019-1 V1.0
* Nordic Semiconductor
  * nRF51822 - Adafruit Bluefruit LE Friend
  * nRF52832 - Sparkfun nRF52832 Breakout
  * nRF52832 - PineTime
* Nuvoton
  * NUC505Y013Y - NuTiny-EVB-NUC505_QFN88 V1.8
* NXP
  * LPC4330FBD144 - GreatFET One
  * LPC804M101JDH24 - OM40001 LPCXpresso804 Rev B
  * LPC812M101JDH24 - LPCXpresso LPC812
  * LPC824J - LPC82x Xpresso V2/mbed
  * MIMXRT1011DAE5A - MIMXRT1010-EVK
  * MIMXRT1052DVL6B - IMXRT1050-EVKB
* ST
  * STM32F051RBT6 - STM32F0DISCOVERY
  * STM32F100RBT6B - STM32VLDISCOVERY
  * STM32F303VCT6 - STM32F3DISCOVERY
  * STM32F407VGT6 - STM32F407G-DISC1
  * STM32F417IGH6U - STM3241G-EVAL
  * STM32F429ZIT6U - STM32F429I-DISCO
  * STM32F746NGH6U - STM32F746G-DISCO
  * STM32F769NIH6U - STM32F769I-DISCO
  * STM32G431CBU6U - B-G431B-ESC1
  * STM32L053C8T6 - STM32L0538-DISCO MB1143B
* TI
  * AM3358BZCZ100 - Beaglebone Black
  * MSP432P401R - MSP-EXP432P401R
  * TM4C123GH6PMI - EK-TM4C123GXL
  * TM4C1294NCPDTT3 - EK-TM4C1294XL

### RISC-V
* open-isa.org / NXP
  * RV32M1 - RV32M1-VEGA
* GigaDevice
  * GD32VF103CBT6 - GD32VF103C-START 2019-9 V1.0
  * GD32VF103CBT6 - Sipeed Longan nano
  * GD32VF103VBT6 - SeeedStudio GD32 RISC-V Dev Board
* SiFive
  * HiFive 1 Rev A01

### AVR XMEGA

None at the moment, this will change with the upcoming AVR XMEGA support.

## Host boards
* Black Magic Probe V1.?
* Black Magic Probe V2.x
* STLink Clone
* ST Discovery Boards

## Black Magic PC Hosted hardware
* Black Magic Probe
* Tigard
* ST-Link

## Legend

* Target boards: These are the boards that BMP can be connected to.
* Host boards: These are the boards that BMP can be flashed on.

The board listings show the exact MCU vendor number fist and the dev board name second if available. As we care more about the chips than the specific dev board.
