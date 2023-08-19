# Xol Toolhead
A soft reboot of Xol 2 (<https://github.com/Armchair-Engineering/Mantis-Xol>) aimed at modularity and quality of life improvements for installation and serviceability. We have left the mantis carriage behind, and thus are now just Xol sans Mantis. Don't worry, it's still ugly, we couldn't fix that.

Project lead: [DW-Tas](https://github.com/DW-Tas)

[![Join me on Discord](https://discord.com/api/guilds/1029426383614648421/widget.png?style=banner2)](https://discord.gg/armchairengineeringsux)

<img src='images/full_assembly.png' width=600 />

## What's new
* Standardised hotend mounts around the Voron Design CW2/TAP carriage bolt hole pattern.
  * This approach reduces the number of hotend mounts and ducts by half - You don't have to search for TAP or non-TAP and we don't have to maintain twice as many parts
* Xol-Carriage
  * A new carriage built for Xol-Toolhead
  * Uses metal pins and a belt clip to secure the belts instead of having them squashed between mgn9/12 carriage and toolhead carriage
  * Improved serviceability - remove the toolhead from the carriage without disassembly in the printer. Unless you use Voron TAP or refuse to buy M2.5 hardware for Xol Carriage. Buy the m2.5 hardware, it's worth it trust us.
  * Modular probe mounting system - change probes without changing the whole carriage _`*Except for KlickyNG`_
* These carriage changes mean you can use any carriage that a Stealthburner bolts onto. (Our Xol-Carriage, or the stock voron carriage even.)

## Supported hardware
### Hotends
* Rapido
* DropEffect XG
* Red Lizard K1-UHF
* Dragon UHF/Mini
* Dragon ST/HF
* Crazy Dragon (Dragon with crazy volcano heat block)
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

### Front Idlers
Xol can colide with the stock voron front idlers for Trident and 2.4 when the toolhead is in the front corners of the build area. This can cause also issues with the homing sequence when homing X if the toolhead is at the front of the gantry on Y. <br/>
Fully compatible idlers:
* clee's [BFI (Beefy Front Idlers)](https://github.com/clee/VoronBFI)
* Ramalama2's [Front Idlers](https://github.com/Ramalama2/Voron-2-Mods/tree/main/Front_Idlers)

## We've made some instructions for printing and assembly.
They took ages to make, please read them.
* [Bill of Materials (BOM)](BOM.md)
* [Printing parts](printing.md)
* [Carriage assembly](xol_carriage_assembly.md)
* [Toolhead assembly](toolhead_assembly.md)


## Acknowledgements
* [DW-Tas](https://github.com/DW-Tas) for giving Xol the giant refresh it needed.
* [Long/Mandryd](https://github.com/mandryd/VoronUsers/tree/master/printer_mods/Long/Mantis_Dual_5015) for the Mantis toolhead.
* [Derpimus](https://github.com/lraithel15133) for the exegesis, some CAD work, feedback, and just being a rad dude.
* [KayosMaker](https://github.com/KayosMaker) for the CAN board mounts and spacers.
* [JosAr](https://github.com/jlas1/Klicky-Probe) for Klicky.
* [WhoppingPochard](https://github.com/tanaes) and [VinnyCordeiro](https://github.com/VinnyCordeiro/) for PCB Klicky.
* [Nionio6915](https://github.com/nionio6915/Euclid_Probe) for Euclid.
* [VoronDesign](https://github.com/VoronDesign) for this particular CoreXY flavor.
* [AnnexEngineering](https://github.com/Annex-Engineering) for the Sherpa Mini and Double Folded Ascender extruders, and the K3 that influenced the air management of the ducts. And also for giving access to an early revision of the new DFA so it could be adapted for this toolhead.
* [clee](https://github.com/clee), you know what you did.
