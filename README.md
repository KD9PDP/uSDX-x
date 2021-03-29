# uSDX-x
uSDX-x: Microcontroller SDR QRP Transceiver Designed for Experimentation

The goal of this project is to make an uSDX platform that:
* Is Open Hardware Licensed: [TAPR Open Hardware License](https://tapr.org/the-tapr-open-hardware-license/)
* Is modular such that you can use the default on board components or easily add your own
  * Default 1 band on board, but can also add on filter modules for other bands (can experiment with filter modules)
  * Either a 1602 LCD or any LCD using I2C/TWI (e.g., OLED)
  * On board single PA MOSFET or connector for your own experimental evaluation of different MOSFETs (e.g., 3x parallel BS170s)
* Exposes all the key nodes in a way that you can just plug in an Arduino nano module to control them, or you can experiment with other MCU development boards (e.g., 32-bit MCU from various manufacturers such as ARM Cortex-M based MCUs).
* "Semiconductor shortage friendly" (uses si5351 modules instead of chips, which are sold out everywhere until 2022)
  * Contains connectors both for the Adafruit and Etherkit style si5351 modules.
* Compatible with jlcpcb PCBA for low-cost PCB manufacturing and assembly
  * Maximize usage of "basic" parts (e.g., uses a BJT gate driver instead of a 74ACT logic gate driver, possibly with improved performance. NE5532 for the AF op amp instead of LM4562.)

This is based on and compatible with:
https://github.com/threeme3/QCX-SSB
by Guido (PE1NNZ)

For more info on development of uSDX platforms, see: https://groups.io/g/ucx

Two other excellent boards:
https://groups.io/g/ucx/wiki/23416 by Barbaros Asuroglu (WB2CBA)
and
https://dl2man.de/ by Manual (DL2MAN)


Copyright 2021
Scott Howard KD9PDP
