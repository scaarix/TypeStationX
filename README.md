# TypeStationX

AKA PS2-KB

a single mcu RP2040 based keyboard that uses ps2 controller connectors

currently in development
when ordering pcbs make sure to upload and order both<a href="https://github.com/scaarix/ps2-keyboard-thing/blob/main/TypeStationX/gerbers/left.zip"> left</a> and <a href="https://github.com/scaarix/ps2-keyboard-thing/blob/main/TypeStationX/gerbers/left.zip">right</a> sides

# TODO:
- [x] Create firmware
- [ ] Add atmega32u4 support

# Parts
| Part name                         | Amount       |Link                                                                                                   |
| --------------------------------- | ------------ | ------------------------------------------------------------------------------------------            |
| KB2040                            | 1            | <a href="https://www.adafruit.com/product/5302">KB2040</a>|
| 1N4148W Diode                     | 32           |<a href="https://www.adafruit.com/product/5099">SMD Diode</a> |
|1N4148TR Diode (For through hole)  | 32            | <a href="https://www.aliexpress.com/item/32729204179.html">THT Diodes</a>|
| PLaystation extension cable       | 2            |<a href="https://www.adafruit.com/product/5773">Cable</a>|
| Female controller ports           | 2            |<a href="https://www.aliexpress.com/item/1005005547168036.html?spm=a2g0o.productlist.main.47.63aa6e50gPBv1v&algo_pvid=186e3400-9a3a-4116-adb0-feedf2eab064">Controller ports</a>|
| Your choice of mx switches        | 32            |                                                                                                       |
| 6mmx3mm magnets                   | 10           |<a href="https://www.amazon.com/FINDMAG-Magnets-Magnetic-Whiteboard-Refrigerator/dp/B08M3YP56J">magnets</a>|

WARNING: Your PS2 controller cable extension may only have 8 out of the 9 pins needed. It may be better just to use two ps2 controllers to make your own cable!

# HUGE THANKS TO
Chewiedies for helping make the stunning case :)

Corvett for giving me the idea for using the ps2 connector to bridge the two halfs of the keyboard

The absolem server for putting up with my sometimes stupid questions and helping me along the way
