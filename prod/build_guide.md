# build instructions

## what do you need?

#### parts
| #     | name                 | comments                                  |
|-------|----------------------|-------------------------------------------|
| 1     | main PCB             | [gerber files](PCB)                       |
| 1     | Seeed Xiao (optional BLE) | Controller board                          |
| 3     | R - 0805 - 10k       | resistor                                  |
| 1     | C - 0805 - 100nF     | capacitor                                 |
| 1     | PCA9555PW            | IO Expander                               |
| 38    | 1N4148 - SOD-123     | diodes                                    |
| 38-41 | HS Sockets           | MX hotswap sockets                        |
| 1     | ec11 12mm            | encoder                                   |
| 1     | 0.91'' 128x32px      | OLED module                               |
| 1     | MSK-12C02            | power switch                              |
| 1     | JST GSH 1.25mm pitch | battery connector, 2pin (optional)        |
| 1     | 3.7V LiPo            | battery (optional)                        |
| 1     | case top             | [case files](prod/case)                   |
| 1     | case botom           | [case files](prod/case)                   |
| 1     | acryl inserts        | [case files](prod/case) optional          |
| 6     | heat inserts m2      |                                           |
| 6     | M2 screws - 6mm      |                                           |
| 14    | magnets              | 3x3 cylindrical N35                       |
| 38    | switches             | MX                                        |
|       | keycaps              |                                           |

#### tools
- soldering iron
- 
## build 
### pcb
- connect the Xiao, enter bootloader by double clicking the reset button, flash firmware and check if it is recognized correctly.
- solder the Xiao to the pcb
- solder IO expander, diodes, capacitor and resistors to the pcb.
- check if all switches work by shorting the pads.
- If everything works, solder everything except the OLED to the pcb

### case
- add heat inserts (either by melting them in, or file the hole a bit larger and just press them in)
- try if magnets fit the holes tightly. Add a bit of superglue if they don't stay in place. Make sure the polarity is correct!
- insert some switches to the plate edges so the pcb stays in place. Add the OLED, don't solder just yet. Alignt the plate and check if the OLED is aligned to the invader cutouts. You should be able to activate the OLED without soldering it if you angle it a bit. If it is not aligned, use some sharp/flat knife to loose the display a bit from it's pcb and reposition it.
- fix the plate with a few screws, the oled should rest on the top case, solder the OLED.
- add remaining switches
- screw in the plate
- put together both case parts.
- (optional) add acryl parts. If they don't stay in place use some double sided tape and/or superglue to keep them in place


ENJOY
