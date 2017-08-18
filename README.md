![board](https://raw.githubusercontent.com/stahlnow/amiga_drive/master/doc/board_gerber.png "gerber screenshot")

This is a SMD board layout for the amiga pi drive from Maurizio Ramondo
http://amigadrive.blogspot.ch/

# Board Errata

All B340A diodes need to be replaced by SB140 diodes (Through hole, need to make little feets to solder).

# BOM

| Part                   | Value                | Device               | Package     | Description                                      |
|------------------------|----------------------|----------------------|-------------|--------------------------------------------------|
| C1                     | 10uF                 | CPOL-EUB             | PANASONIC_B | POLARIZED CAPACITOR, European symbol             |
| C2                     | 100nF                | CAP1206              | 1206        | Capacitor                                        |
| C3                     | 220pf                | CAP1206              | 1206        | Capacitor                                        |
| D1 – D5, D7            | SB140                | DIODE-SCHOTTKY-SB140 | Schottky Diode  |       |
| D6                     | 1N4148               | DIODESOD123          | SOD-123     | Diode                                            |
| IC1                    | 74LS06D              | 74LS06D              | SO14        | Hex INVERTER, open collector high-voltage output |
| LED1                   | BLUE                 | LED-BLUE1206         | LED-1206    | Blue LEDs for production use                     |
| R1 – R7                | 1k                   | RESISTOR1206         | 1206        | Resistor                                         |
| R8, R14, R16, R26, R27 | 4k7                  | RESISTOR1206         | 1206        | Resistor                                         |
| R9 – R13, R17, R18     | 2k7                  | RESISTOR1206         | 1206        | Resistor                                         |
| R15                    | 10k                  | RESISTOR1206         | 1206        | Resistor                                         |
| R19 – R25              | 6k8                  | RESISTOR1206         | 1206        | Resistor                                         |
| R28                    | 330                  | RESISTOR1206         | 1206        | Resistor                                         |
| S1                     | SEL1                 | DS01E                | DS-01       | DIL/CODE SWITCH                                  |
| BUTTONS                | gnd | chg | wrt      | PINHD-1X3            | 1X03        | PIN HEADER                                       |
| JP1                    | Amiga Floppy Power   | PINHD-1X4/90         | 1X04/90     | PIN HEADER                                       |
| JP2                    | Amiga Internal Drive | PINHD-2X17           | 2X17        | PIN HEADER                                       |
| JP3                    | Raspberry PI         | RPI_P1               | RPI_P1      | PIN HEADER                                       |


# Placement

![board](https://raw.githubusercontent.com/stahlnow/amiga_drive/master/doc/parts_placement_top.png "placement top")

![board](https://raw.githubusercontent.com/stahlnow/amiga_drive/master/doc/parts_placement_bottom.png "placement bottom")

