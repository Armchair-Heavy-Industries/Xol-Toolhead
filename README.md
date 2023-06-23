# BETA EXPERIMENTAL
# Xol Toolhead
A reboot of Xol 2 (<https://github.com/Armchair-Engineering/Mantis-Xol>) aimed at modularity and quality of life improvements for installation and serviceability.

[![Join me on Discord](https://discord.com/api/guilds/1029426383614648421/widget.png?style=banner2)](https://discord.gg/armchairengineeringsux)

## What's new
* Standardised hotend mounts around the Voron Design CW2/TAP carriage bolt hole pattern.
  * This approach reduces the number of hotend mounts and ducts by half - No more searching for TAP or non-TAP parts
* Xol-Carriage
  * A new carriage built for Xol-Toolhead
  * Metal pins and clamp/clip used to secure belts instead of squashed between mgn9/12 carriage and toolhead carriage
  * Improved serviceability - remove the toolhead from the carriage without disassembly in the printer
  * Modular probe mounting system - change probes without changing the whole carriage _*Except for KlickyNG_

## Supported hardware
### Hotends
* Rapido
* DropEffect XG
* Red Lizard K1-UHF
* Dragon UHF/Mini
* Dragon SF/HF
* Revo Voron

### Extruders
* Sherpa Mini
* Annex Double Folded Ascender
* Vz-Hextrudort-Low
* LGX-Lite
* Orbiter v2.0

### Probes
* PCB Klicky
* Klicky
* KlickyNG
* Beacon
* Euclid
* Voron Design TAP (For RC8+, suggest to use m3x50 BHCS instead of SHCS)

### X-Rail/Belts
* MGN12H - 6mm Belts
* MGN9H - 6mm Belts
* MGN9H - 9mm Belts

## Please follow the documents below for BOM, printing and assembly instructions
* [Bill of Materials (BOM)](BOM.md)
* [Printing parts](printing.md)
* [Carriage assembly](xol_carriage_assembly.md)
* [Toolhead assembly](toolhead_assembly.md)