---
title: Update log
description: Release update logs documenting changes, additions, removals and fixes.
---

# Update log

## `Xol-Toolhead Release 2023-09-15`

* Modular approach to hotend mounts and extruders
  * Hotend mounts and extruder mounts are now separate parts
  * Extruder mounts incorporate the old Xol-Carriage or TAP adapter plates (same number of printed parts overall)
  * "Xol with bones" option: Add some screws for extra rigidity in the hotend mount
* Minimal BOM change
  * 1x M3x8 BHCS
  * 1x M3 Heatset
  * Optional "bones"
    * 2x M2x30 SHCS
    * 2x M2 Heatset
* Xol-Carriage update
  * Stronger belt clips
  * bigger probe cable channel with cable tie slot

## `Xol-Toolhead Release 2023-07-14`

* Standardised hotend mounts around the Voron Design CW2/TAP carriage bolt hole pattern.
  * This approach reduces the number of hotend mounts and ducts by half - You don't have to search for TAP or non-TAP and we don't have to maintain twice as many parts
* Xol-Carriage
  * A new carriage built for Xol-Toolhead
  * Uses metal pins and a belt clip to secure the belts instead of having them squashed between mgn9/12 carriage and toolhead carriage
  * Improved serviceability - remove the toolhead from the carriage without disassembly in the printer. Unless you use Voron TAP or refuse to buy M2.5 hardware for Xol Carriage. Buy the m2.5 hardware, it's worth it trust us.
  * Modular probe mounting system - change probes without changing the whole carriage _`*Except for KlickyNG`_
* These carriage changes mean you can use any carriage that a Stealthburner bolts onto. (Our Xol-Carriage, or the stock voron carriage even.)
