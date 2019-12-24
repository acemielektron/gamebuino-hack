# gamebuino-hack
A diy clone of open source gamebuino classic (http://legacy.gamebuino.com/wiki)

<p><h1>Changes</h1><br>
- Hack is based on Atmega328 PDIP so it does not have A6 and A7 (PC6 and PC7) pins<br>
- Button C is moved to D5 (PD5) -> rebuilding all games and bootloader needed for this change to work<br>
- Battery sensor is moved to ADC3 (PC3) -> rebuilding all games are needed for this change to work<br>
- No ambient light sensor<br>
- No pwm control for background led<br></p>

<p><h1>Bootloader</h1><br>
- gamebuino requires a custom bootloader for loading games from sd-card to work (https://github.com/ghalfacree/Arduino-Sketches/tree/master/hardware/arduino/bootloaders/gamebuino_boot)
