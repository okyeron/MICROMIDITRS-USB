# MICROMIDITRS-USB
 

A DIY USBMIDI to TRS MIDI adapter for Adafruit QTPy.

The SAMD21 QTPy variant is recommended. Code for other variants will be released here over time.

### Features

* Auto sensing TRS MIDI Type-A/Type-B input with [LPZW](http://leipzigwest.org/) Auto Crossover circuit
* Switch for TRS MIDI Type-A/Type-B output
* Activity LEDs for input/output
* USB-C connector on QTPy

![<#MMTRS-USB.jpeg#>](<MMTRS-USB.jpeg>)

### Firmware

Firmware is available as a pre-compiled UF2 file. See [Releases page](https://github.com/okyeron/MICROMIDITRS-USB/releases) for download

To load the firmware, connect the QTPy to your computer and then double click the reset button on the QTPy to drop it into bootloader mode. This should now show you a QTPY_BOOT drive on your computer desktop. Drag the UF2 file to QTPY_BOOT and it should dismount/reboot and come back as the `MMTRS-USB`.



