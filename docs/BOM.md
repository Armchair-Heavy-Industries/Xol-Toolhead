# Xol Toolhead Bill of Materials (BOM)
Read **ALL** of the sections below to understand your hardware requirements, there's some bits here that aren't on a standard Voron build BOM.
The chances are that something was missed, but if you have a good mix of M2, M2.5 and M3 hardware you'll probably still end up with a working printer.

## Carriage

#### Required Hardware
| Qty | Item                                          | Notes                                                                                     |
| --- | --------------------------------------------- | ----------------------------------------------------------------------------------------- |
| 5   | M3 Heatset Insert                             | Standard Voron spec: 5mm Outer Diameter x 4mm Length                                      |
| 6   | M3 x 8 SHCS                                   | 4x MGN carriage mounting, 2x MGN carriage clamps                                          |
| 4   | M3 Hex Nut                                    | 2x MGN carriage clamps, 2x toolhead mounting                                              |
| 2   | M3 DIN9021 flat washer  | MGN Carriage clamping. `Alternatively use M3 + M5 stacked washers`                                                                  |
| 2   | M3 x 30 Pin                                   | Belt mounting system                                                                      |
| 2   | 22.5mm lenght M4 metal tube                   | 4mm OD, 0.45mm wall width. Belt mounting system.`4/3mm PTFE tube can be used temporarily` |
| 2   | 1.8mm wide cable tie or 0.5mm solid core wire | To attach M4 tube to belt clips as per Archetype clips                                    |

#### Probe/Extruder Hardware
Follow probe or extruder instructions for required hardware.

`* If using Voron Design TAP RC8+ it is recommended to replace the two M3 x 50 SHCS with M3 x 50 BHCS to improve build plate clearance.`

## Toolhead

#### Required Hardware
| Qty | Item                    | Notes                                                                                                                               |
| --- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| 5*  | M3 Heatset Insert       | Standard Voron spec: 5mm Outer Diameter x 4mm Length <br/> * Extruder Mount `5th heatset for extruders with additional front screw` |
| 1   | M3 Hex Nut              | Hotend Mount mount, front of Extruder Block                                                                                         |
| 2   | M3 x 20 Metal Stand-off | CAN/EBB Mounting                                                                                                                    |
| 2   | M3 x 16 SCHS            | HE Mount                                                                                                                            |
| 2   | M3 x [20][8] SHCS       | Extruder to HE Mount. Length varies depending on extruder used <br/> `M3x20 used for Sherpa-Mini, M3x8 used for most others`        |
| 4   | M3 x 16 SHCS            | 2x Extruder stepper to standoff <br/>2x CAN/EBB36 mount                                                                              |
| 7   | M3 x 8 SHCS             | 2x HE Mount feet, 2x HE Adapter to carriage, 2x MGN carriage clamping, 1x EBB Mount                                                                   |
| 2*  | M3 x 6 BHCS             | Extruder Mount to Hotend Mount at front. `*additional 1 if using extruder with front faceplate that includes extra point.`          |
| 4   | M2.5 x 16 SHCS          | HE Fan <br/>                                                                                                                        |
| 4   | M2.5 x 8 SHCS           | Part cooling fan mounting                                                                                                           |
| 4*  | M2.5 x 8 SHCS           | *additional to above if using XolPAP ducts                                                                                          |
| 1   | Short PTFE tube         | Between extruder and hotend                                                                                                         |

#### Fans
> :information_source: **Understand your electronics and voltages** <br/>
> Do you have the correct voltage at your toolhead or will you need a converter?<br/>
> If using the _recommended_ parts you need 5v, 12v and 24v at the toolhead.

| Qty | Fan Type                                       | Recommended Fan                                                                                                                                                                                                                                                                                       | Notes                                                                                                                                                                                                                                                                                      |
| --- | ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | 2510 Axial Fan <br/> Hotend Fan                | Delta Electronics 5v <br/> ASB02505SHA-AY6B                                                                                                                                                                                                                                                           | <a href="https://www.digikey.com/en/products/detail/delta-electronics/ASB02505SHA-AY6B/7491489">Purchase Link</a> <br/> `This fan is highly recommended in heated chambers`<br/>`No other 2510 fan comes close to the performance`<br/>`of this fan.`                                      |
| 2   | 4010 Blower Fan <br/> Part Cooling Fans        | Delta Electronics <br/> BFB0412HHA-A (12V) <a href="https://www.digikey.com/en/products/detail/delta-electronics/BFB0412HHA-A/2560487">Purchase Link</a> <br/> BFB0405HHA-A (5V)  <a href="https://www.digikey.com/en/products/detail/delta-electronics/BFB0405HHA-A/1014444">Purchase Link</a> <br/> | `24v GDStime fans are fine and many have used them successfully.`<br/>`The Deltas, however, have better durability`<br/>`in heated chambers and always hit their performance claims.`<br/>`It's not uncommon for other fan manufacturers`<br/>`to overstate performance, GDStime included.` |
| 1*  | 7040 or other suitable CPAP remote cooling fan |                                                                                                                                                                                                                                                                                                       | XolPAP only                                                                                                                                                                                                                                                                                |
| 1*  | 15mm ID CPAP flexible hose                     |                                                                                                                                                                                                                                                                                                       | XolPAP only                                                                                                                                                                                                                                                                                |

Additional notes: Delta's 5V and 12V variants provide the same airflow, pick whichever suits your setup better. If you only have 24V available, you can use a 24V-12V buck converter like [K78L12-500R3](https://www.digikey.com/en/products/detail/mornsun-america-llc/K78L12-500R3/16784476), or run an additional wire in your umbilical for 12v+.

#### Optional Hardware
| Qty | Item                        | Notes                                                                                                                                          |
| --- | --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | M3 Heatset Insert           | Sherpa-Mini and G2 / WristWatch front plate attachment                                                                                         |
| 1   | M3 Heatset Insert           | DFA Custom bottom                                                                                                                              |
| 2   | M2 x 10 self tapping screws | X End stop                                                                                                                                     |
| 1   | LED harness                 | 1x RGB Neopixel LEDs, and <br/> 2x RGB Sequin LEDs (0.8mm board thickness) <br/> 26 or 28 AWG wire. <br/> [Build instructions](led_harness.md)<br/>`Only compatible with the thin PCB board sequins. Known working source:` [FYSETC (Ali Express)](https://www.aliexpress.com/item/1005006023213341.html) |

<br/><br/><br/><br/>
⬅ [README](README.md) - [Printed Parts](printing.md) ➡
