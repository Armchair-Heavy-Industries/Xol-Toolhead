---
title: Toolhead BOM
description: Bill Of Materials and required parts for the Xol Toolhead
---

# Bill Of Materials

## Required Hardware

| Qty | Item                    | Notes                                                                                                                                                        |
| --- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 5   | M3 Heatset Insert       | Standard Voron spec: 5mm Outer Diameter x 4mm Length <br/> * 2x HE Mount <br/>* 2x Adapter plate <br/>* 1x Hotend Mount mount for Extruder Block             |
| 6*  | M2.5 Heatset Insert     | 3.5mm Outer Diameter x 4mm Length <br/> 2x HE Mount "Feet" rear mount <br/> *4x hotend fan if using "fan HS" versions                                        |
| 6   | M2 Heatset Insert       | 3.5mm Outer Diameter x 4mm Length <br/> Part cooling fan and duct mounting <br/> * 2x Optional Bones                                                         |
| 2   | M3 x 20 Metal Stand-off | CAN/EBB Mounting                                                                                                                                             |
| 2   | M3 x 20 SCHS            | HE Mount                                                                                                                                                     |
| 2   | M3 x ?? SHCS            | Extruder to HE Mount. Length varies depending on extruder used                                                                                               |
| 4*  | M3 x 16 SHCS            | 2x Extruder stepper to standoff<br/>*2x HE Mount feet if using Voron TAP or not using M2.5 hardware                                                          |
| 2   | M3 x 12 SHCS            | CAN/EBB 36 mount                                                                                                                                             |
| 2   | M2 x 30 SHCS            | Optiona Bones                                                                                                                                                |
| 3   | M3 x 8 SHCS             | 2x HE Adapter to carriage, 1x EBB Mount                                                                                                                      |
| 1   | M3 x 8 BHCS             | Extruder Mount to Hotend Mount at front                                                                                                                      |
| 4   | M2.5 x 20 SHCS          | HE Fan <br/>`The bottom two HE fan screws may impact on Dragon UHF silicone sock. Remove a couple of milimetres of thread with a file or cutters if needed.` |
| 2   | M2.5 x 10 SHCS          | HE Mount "Feet" rear mount                                                                                                                                   |
| 6   | M2 x 12 SHCS            | Part cooling fan and duct mounting                                                                                                                           |
| 2   | M2 x 8 SHCS             | Part cooling fan and duct mounting - top rear screws                                                                                                         |
| 1   | Short PTFE tube         | Between extruder and hotend                                                                                                                                  |

## Fans

| Qty | Item            | Purpose                       | Notes     |
| --- | --------------- | ----------------------------- | --------- |
| 1   | 2510 axial fan  | [Hot end](#hot-end)           | See below |
| 2   | 4010 radial fan | [Part cooling](#part-cooling) | See below |

### Hot end

Recommendations:

1. Delta Electronics ASB02505SHA-AY6B
    - 5V
    - This fan is highly recommended in heated chambers. No other 2510 fan comes close to the performance of this fan.
    - Available at [Digikey][ASB02505SHA-AY6B]

### Part cooling

Recommendations:

1. Delta Electronics BFB0412HHA-A
    - 12V
    - Available at [Digikey][BFB0412HHA-A]
2. Delta Electronics BFB0405HHA-A
    - 5V
    - Available at [Digikey][BFB0405HHA-A]

The Delta Electronics BFB0412HHA-A and BFB0405HHA-A provide the same airflow; pick whichever suits your setup better. Higher voltage (V) fans require less current (A) for the same power consumption (W).

Alternatively, GDStime fans are fine. Known negatives are the very short lifetime, often overstated specifications, and overall worse durability.  The Delta Electronics fans are our recommendation. They have better durability in heated chambers and always hit their performance claims.  
It's not uncommon for other fan manufacturers to overstate performance, GDStime included.

If you only have 24V available, you can use a step-down regulator like the [K78L12-500R3](https://www.digikey.com/en/products/detail/mornsun-america-llc/K78L12-500R3/16784476), or add an additional 12V power supply.

## Optional Hardware

| Qty | Item                               | Notes                                                                                   |
| --- | ---------------------------------- | --------------------------------------------------------------------------------------- |
| 1   | M3 Heatset Insert                  | Sherpa-Mini K-plate attachment                                                          |
| 1   | M3 Heatset Insert                  | DFA Custom bottom                                                                       |
| 2   | M3 Heatset Insert                  | *If not using M2.5 hardware for HE Mount "feet"                                         |
| 1   | M2 Heatset Insert                  | 3.5mm Outer Diameter x 4mm Length <br/>X End stop                                       |
| 1   | M2 x 10 SHCS                       | X End stop                                                                              |
| 1   | Stealthburner Neopixel LED harness | If using LED ducts and faceplate <br/>`custom neopixel harness if using only duct LEDs` |

[ASB02505SHA-AY6B]: https://www.digikey.com/en/products/detail/delta-electronics/ASB02505SHA-AY6B/7491489
[BFB0412HHA-A]: https://www.digikey.com/en/products/detail/delta-electronics/BFB0412HHA-A/2560487
[BFB0405HHA-A]: https://www.digikey.com/en/products/detail/delta-electronics/BFB0405HHA-A/1014444
