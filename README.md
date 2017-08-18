![board](https://raw.githubusercontent.com/stahlnow/amiga_drive/master/doc/board_gerber_v1.1.png "gerber screenshot")

This is a SMD board layout for the amiga pi drive from Maurizio Ramondo
http://amigadrive.blogspot.ch/

# BOM

| Part                     | Value                | Package     | Description                                        |
|--------------------------|----------------------|-------------|----------------------------------------------------|
| BUTTONS                  | gnd | chg | wrt      | 1X03        | Pin Header                                         |
| C1                       | 10uF                 | PANASONIC_B | Electrolytic Capacitor                             |
| C2                       | 100nF                | 1206        | Capacitor                                          |
| C3                       | 220pf                | 1206        | Capacitor                                          |
| "D1 – D5, D7"            | SB140                | DO41-10     | Schottky Diode                                     |
| D6                       | 1N4148               | SOD-123     | Diode                                              |
| IC1                      | 74LS06D              | SO14        | "Hex INVERTER, open collector high-voltage output" |
| JP1                      | Amiga Floppy Power   | 1X04/90     | Pin Header                                         |
| JP2                      | Amiga Internal Drive | 2X17        | Pin Header                                         |
| JP3                      | Raspberry PI         | RPI_P1      | Pin Header                                         |
| LED1                     | BLUE                 | LED3MM      | LED                                                |
| R1 – R7                  | 1k                   | 1206        | Resistor                                           |
| "R8, R14, R16, R26, R27" | 4k7                  | 1206        | Resistor                                           |
| "R9 – R13, R17, R18"     | 2k7                  | 1206        | Resistor                                           |
| R15                      | 10k                  | 1206        | Resistor                                           |
| R19 – R25                | 6k8                  | 1206        | Resistor                                           |
| R28                      | 330                  | 1206        | Resistor                                           |
| S1                       | SEL1                 | DS-01       | Switch                                             |

