# Picise

Prototype for a time / location accessory for a Raspberry Pi 40-pin GPIO.

## Goals:

- high quality time (including pps) and location source
- low cost but not cheap
- all 3.3VDC to keep things simple
- clearance for Pi52's ICE Tower coolers

Vertical GPIO riser with 
- HAT EEPROM, 
- GNSS, 
- GNSS battery backup, 
- indicators for power and GNSS fix,
- 3.3VDC fan header.

## BOM:

[Digikey](https://www.digikey.com/short/rnq4tnz8)

## Status:

**2022-11-25: rev2 design in progress.**

**2022-11-24: rev1 assembled, working (click on video below). Planning rev2 improvements.**

### PCB:

<img src="artifacts/rev1%20pcb%201.jpg?raw=true" width=50%><p><img src="artifacts/rev1%20pcb%202.jpg?raw=true" width=50%>

### Video:

[![working picise module showing 1 per second timing pulse with blue LED](https://img.youtube.com/vi/lg2OkTD7_zg/0.jpg)](https://www.youtube.com/shorts/lg2OkTD7_zg)


**2022-11-01: rev1 prototype boards received, pending assembly.**

<img src="artifacts/picise%20front%20render.png?raw=true" width=50%><p><img src="artifacts/picise%20back%20render.png?raw=true" width=47.7%>

Library not published at this time.  Can't remember what has which licensing where I used stuff from vendors.

## License:

CC BY-SA 4.0, see [LICENSE](LICENSE) file.
