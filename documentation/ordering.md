# Ordering

Upload the Gerbers, BOM and CPL from the [release](https://github.com/Maggy-the-maglev-lab/maggy-hardware/releases) to JLCPCB. Size and layer count should be detected from the Gerbers. Ensure that the following options are selected:

| Option             | Value                        |
| ------------------ | ---------------------------- |
| Base material      | FR4                          |
| Thickness          | 1.6 mm                       |
| Solder mask colour | Black (optional)             |
| Silkscreen         | White (optional)             |
| PCB assembly       | Standard, top side only      |

> [!IMPORTANT]
> Always double check component placement and rotation before submitting an order for PCB assembly. Terminal blocks, the USB-C port and the hall-effect sensors have been known to require manual rotation in JLCPCB's editor as the final step before placing an order.

All parts are on the top side. The screw terminals (J1–J4) and Teensy sockets (J5/J6) are through-hole, so include THT assembly for them.

## Sourced separately

- Teensy 4.1 with pre-soldered male pin headers to plug it into the sockets
- Solenoids
- Permanent magnets
- USB-C PD power supply with **12 V** support
