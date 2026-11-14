# XD75HE

XD75HE is a 60% Hall-effect keyboard PCB with 8kHz polling rate designed in the layout of the KPRepublic XD75RE.

## Features

- GH60 cases.
- Support for gummy O-ring mount cases **if the USB-C port is not soldered** e.g., Bakeneko60, and SingaKBD Unikorn (required 10mm JST cable).
- [libhmk](https://github.com/peppapighs/libhmk) firmware.
- [hmkconf](https://hmk.prasertsuk.com) web-based configurator.

## Disclaimer

- Work in progress. Do not attempt to fabricate yet.

You may change the Hall-effect sensors during the component selection based on your preference, and availability. Different sensors require different calibration values, which can be adjusted using the web-based configurator. Here are some options that I have used:

- GH39FKSW (Cheapest)
- MT9102ET
- SS39ET
- DRV5055A3
- OH49E-S (Discontinued)

The fabrication files above are available [here](https://github.com/peppapighs/HE60/releases).

## Firmware

Head to [libhmk](https://github.com/peppapighs/libhmk/releases) for a pre-compiled firmware. The firmware can be flashed using DFU mode, which can be entered by holding the BOOT button before plugging in. You may need to install the DFU bootloader driver using Zadig. See [libhmk](https://github.com/peppapighs/libhmk) for more information for firmware flashing instructions.
