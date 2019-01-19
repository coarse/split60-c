# Split60-C

![Plain60-C PCB](https://i.imgur.com/OwOP9Vb.png)
This PCB is a fork of the [Plain60-C] which introduces split space compatibility and nothing more.

## Features
- QMK Firmware
- Compatible with most universal 60% cases and HHKB/WKL Tofu by KBDfans
- USB type-C
- ESD protection and fuse
- No LEDs and no underglow
- Minimal layout support
- ISP header

## Supported layouts
![Supported layouts of the Plain60-C](https://i.imgur.com/dq04Csv.png)

## Building
If you feel like building a few of these PCBs yourself, go to the 'Releases' tab and download the latest gerber files. Order those at your favourite PCB manufacturer, get the components needed (see below) and solder them on! A hot air station is not required but a soldering iron is. Flux is recommended.

## Bill of materials (BOM)
Amount is per PCB, multiply as needed.

| LCSC part # | Description   | Value | Package  | Amount |
| ----------- | ------------- | ----- | -------- | ------:|
| C296091     | Capacitor     | 22pF  | 0805     | 2      |
| C128353     | Capacitor     | 0.1uF | 0805     | 4      |
| C131056     | Capacitor     | 4.7uF | 0805     | 1      |
| C215803     | Capacitor     | 1uF   | 0805     | 1      |
| C53365      | Diode         |       | 0805     | 65     |
| C261942     | Fuse          |       | 0805     | 1      |
| C165948     | Connector     |       | SMD/THT  | 1      |
| C103904     | Resistor      | 10K   | 0805     | 2      |
| C147798     | Resistor      | 5.1K  | 0805     | 2      |
| C325772     | Resistor      | 22    | 0805     | 2      |
| C44854      | MCU           | 32U4  | QFP-44   | 1      |
| C7519       | ESD chip      |       | SOT23-6  | 1      |
| C255909     | Crystal       | 16MHz | TSX-3225 | 1      |
| C92584      | Switch        |       | SMD      | 1      |
