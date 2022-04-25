RB02
====

Simple, cheap, hackable, DIY, open-source USB-C input switcher

Background
----------

I couldn't find a good USB-C switch with two outputs that wasn't hundreds of
dollars, so I built my own. (Also I wanted an excuse to learn PCB design, and I
was able to secure a few free sample rotary switches from an electronics
company.) The result is the RB02, a two-output one-input bidirectional USB-C
input switcher smaller than a credit card.

The RB02 has three USB-C ports, one on the front and two on the back. A knob on top has three positions, left, right, and center. In the left or right position, the device connects the USB port on the front to the left or right USB port on the back. 

It's resonable to make as a weekend project as long as you've got a fine
soldering iron for the few surface-mount pads.

Gallery
-------

FIXME

Bill of Materials
-----------------

| Item                                              | Manufacturer  | Part number      | Quantity | Unit price | Total price              |
|---------------------------------------------------|---------------|------------------|----------|------------|--------------------------|
| Rotary switch                                     | NKK Switches  | MRA-403-A        | 1        | $24.17     | $24.17                   |
| 18-8 Stainless Steel Socket Head Screw, M2 x 25mm | McMaster Carr | 91292A032        | 4        |            | $6.21 (pack of 10)       |
| 18-8 Stainless Steel Hex Nut, M2                  | McMaster Carr | 91828A111        | 4        |            | $6.14 (pack of 100)      |
| 1/4" Adhesive-Back Bumper                         | McMaster Carr | 8215K219         | 3        | $2.06      | $6.18                    |
| Custom Printed Circuit Board                      | Aisler        |                  | 1        | $7.04      | $21.10 (minimum order 3) |
| Standard LED                                      |               |                  | 1        |            |                          |
| Standard resistor                                 |               |                  | 1        |            |                          |
| USB-C receptacle                                  | JAE           | DX07S016JA1R1500 | 3        | $1.67      | $5.01                    |
|                                                   |               |                  |          |            | **~$70**                 |

Assembly
--------

### PCB assembly

FIXME

- Different resistor values result in different brightnesses of the LED. 420Ω
  is around full brightness. I like mine pretty dim so I chose FIXMEΩ
- To disable the LED entirely just remove the resistor. Or don't install the
  LED at all. One could easily redesign the case to remove the LED hole.

### Case assembly

FIXME

- Clip off leads sticking through PCB to 2mm or less
- MR-A403 should be installed in this configuration from top to bottom:
  * Knob
  * Hex Face Nut
  * Case
  * Locking Ring (with nub pointing up into hole in case)
  * Factory Assembled switch
  Refer to page 4 of the [datasheet](for definitions and details).

License
-------

[GNU General Public License v3.0](LICENSE)
