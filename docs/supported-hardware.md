---
title: Supported hardware
description: A list of hot ends, extruders and other printer toolhead parts that are currently compatible with the Xol toolhead and carriage through the provided parts and components
---

# Supported hardware

This list provides a comprehensive yet incomplete summary of the hardware parts and setups that are deemed compatible with the currently available Xol toolhead and carriage parts and components.

## Hotends

* Phætus [Rapido](https://www.phaetus.com/products/rapido-hotend)
* DropEffect [XG](https://www.dropeffect.com/products/xg-hotend)
* DropEffect NeXt-G `when released`
* Haldis 3D Red Lizard K1-UHF
* Phætus [Dragon UHF/Mini](https://github.com/Phaetus/Dragon-UHF)
* Phætus [Dragon ST](https://github.com/Phaetus/Dragon-ST)
* Phætus [Dragon HF](https://github.com/Phaetus/Dragon-HF)
* Trianglelab [Dragon Ace](https://www.trianglelab.net/products/dragon-ace%E2%84%A2-hotend)
* E3D [Revo Voron](https://e3d-online.com/products/revo-voron)
* Mellow3D [NF-Crazy](https://github.com/Mellow-3D/NF-Crazy) (*without duct LEDs)

## Extruders

* Annex Engineering [Sherpa Mini](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder)
* Annex Engineering [Double Folded Ascender](https://github.com/Annex-Engineering/Folded_Ascender-Extruder)
* [Galileo G2SA](https://github.com/JaredC01/Galileo2) (Standalone)
* Escapement
* [Vz-Hextrudort-Low](https://github.com/VzBoT3D/Vz-HextrudORT)
* Bondtech [LGX-Lite](https://www.bondtech.se/product/lgx-lite-large-gears-extruder/)
* [Orbiter V2.0](https://www.orbiterprojects.com/orbiter-v2-0/)

## Probes

* PCB Klicky
* Klicky
* KlickyNG
* Beacon
* Euclid
* Voron Design TAP `For RC8+ we suggest to use m3x50 BHCS instead of SHCS`

## X-axis rail & belts

The following combinations of linear rail and timing belt are currently supported:

* MGN12H - 6mm Belts
* MGN9H - 6mm Belts
* MGN9H - 9mm Belts

All belts are assumed to be Gates 2GT specification belts

## Front Idlers

!!! note "Voron front idlers"

    Xol-Toolhead can colide with the stock voron front idlers for Trident and 2.4 when the toolhead is in the front corners of the build area. This can cause also issues with the homing sequence when homing X if the toolhead is at the front of the gantry on Y.

Fully compatible idlers:

* clee's [BFI (Beefy Front Idlers)](https://github.com/clee/VoronBFI)
* Ramalama2's [Front Idlers](https://github.com/Ramalama2/Voron-2-Mods/tree/main/Front_Idlers)
