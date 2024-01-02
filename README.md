# TypeStationX

AKA PS2-KB

# Update
PCB arrived now waiting for parts to arrive

# About
a single mcu RP2040 based keyboard that uses ps2 controller connectors

currently in development
when ordering pcbs make sure to upload and order both<a href="https://github.com/scaarix/ps2-keyboard-thing/blob/main/TypeStationX/gerbers/left.zip"> left</a> and <a href="https://github.com/scaarix/ps2-keyboard-thing/blob/main/TypeStationX/gerbers/left.zip">right</a> sides
Findings:
I don't think there are any ps2 controller extension cables that have all 9 pins available. Because one of the pins aren't needed, they get rid of it to save a few cents. So making your own cable is nessisary.
If i make a rev2 (i probably won't) it would most likely have an IO expander on the other half using spi (6 pins on the connector) so that I can use the cable instead of having to create my own.

# TODO:
- [x] Create firmware
- [ ] Create build guide
- [ ] Buy pcb and assemble
- [ ] Add photos

# Parts
| Part name                         | Amount       |Link                                                                                                   |
| --------------------------------- | ------------ | ------------------------------------------------------------------------------------------            |
| KB2040                            | 1            | <a href="https://www.adafruit.com/product/5302">Adafruit</a>|
| 1N4148W Diode                     | 32           |<a href="https://www.adafruit.com/product/5099">AdaFruit</a> |
| 1N4148TR Diode (THT)              | 32           | <a href="https://www.aliexpress.com/item/32729204179.html">Aliexpress</a>|
| Female controller ports           | 2            |<a href="https://www.aliexpress.com/item/1005005547168036.html?spm=a2g0o.productlist.main.47.63aa6e50gPBv1v&algo_pvid=186e3400-9a3a-4116-adb0-feedf2eab064">Aliexpress</a>|
| Male Controller Port              | 2            |<a href="https://www.aliexpress.com/item/1005003234151343.html">Aliexpress</a>|
| Your choice of mx switches        | 32           |                                                                                                       |
| 6mmx3mm magnets                   | 10           |<a href="https://www.amazon.com/FINDMAG-Magnets-Magnetic-Whiteboard-Refrigerator/dp/B08M3YP56J">Amazon</a>|

WARNING: Your PS2 controller cable extension may only have 8 out of the 9 pins needed. You can dissasemble the connector piece and add another pin yourself. Depending on your case it may be better just to use two ps2 controllers to make your own cable!

# HUGE THANKS TO
Chewiedies for helping make the stunning case :)

Corvett for giving me the idea for using the ps2 connector to bridge the two halfs of the keyboard

The absolem server for putting up with my sometimes stupid questions and helping me along the way
