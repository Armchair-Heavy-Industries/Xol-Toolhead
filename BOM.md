# Xol Toolhead Bill of Materials (BOM)
Read **ALL** of the sections below to understand your hardware requirements, there's some bits here that aren't on a standard Voron build BOM.
The chances are that something was missed, but if you have a good mix of M2, M2.5 and M3 hardware you'll probably still end up with a working printer.

## Carriage

#### Required Hardware
| Qty | Item | Notes|
|-----|------|------|
|5 | M3 Heatset Insert| Standard Voron spec: 5mm Outer Diameter x 4mm Length|
|6* | M3 x 6 BHCS | `Only 2 required if using MGN9H carriage`<br/>4x MGN12H carriage mounting<br/>2x probe module|
|8* | M3 x 8 SHCS | `only 4 required if using MGN12H carriage`<br/>4x Join carriage front to carriage rear<br/>4x MGN9H carriage mounting |
| 4 | M3 Hex Nut | |
| 2* | M3 x 25 Pin | Belt mounting system for 6mm belts | 
| 2* | M3 x 30 Pin | Belt mounting system for 9mm belts |

#### Optional Hardware
| Qty | Item | Notes|
|-----|------|------|
|2 | M3 Heatset Insert| If not using m2.5 heatsets for toolhead feet attachment|

#### Probe Hardware
Follow probe instructions for required hardware. Where possible, self tapping screws have been replaced with heatset hardware, usually M2.

`* If using Voron Design TAP RC8+ it is recommended to replace the two M3 x 50 SHCS with M3 x 50 BHCS to improve build plate clearance.`

## Toolhead

#### Required Hardware
| Qty | Item | Notes|
|-----|------|------|
|4 | M3 Heatset Insert| Standard Voron spec: 5mm Outer Diameter x 4mm Length <br/> * 2x HE Mount <br/>* 2x Adapter plate|
|6* | M2.5 Heatset Insert | 3.5mm Outer Diameter x 4mm Length <br/> 2x HE Mount "Feet" rear mount <br/> *4x hotend fan if using "fan HS" versions|
|4 | M2 Heatset Insert | 3.5mm Outer Diameter x 4mm Length <br/> Part cooling fan and duct mounting|
|2 | M3 x 20 Metal Stand-off | CAN/EBB Mounting |
|2 | M3 x 20 SCHS | HE Mount |
|2 | M3 x ?? SHCS | Extruder to HE Mount. Length varies depending on extruder used |
|4*| M3 x 16 SHCS | 2x Extruder stepper to standoff<br/>*2x HE Mount feet if using Voron TAP or not using M2.5 hardware |
|2 | M2 x 12 SHCS | CAN/EBB 36 mount
|3 | M3 x 8 SHCS | 2x HE Adapter to carriage, 1x EBB Mount |
|4 | M2.5 x 20 SHCS | HE Fan <br/>`The bottom two HE fan screws may impact on Dragon UHF silicone sock. Remove a couple of milimetres of thread with a file or cutters if needed.` |
|2 | M2.5 x 10 SHCS | HE Mount "Feet" rear mount|
|6 | M2 x 12 SHCS | Part cooling fan and duct mounting |
|2 | M2 x 8 SHCS | Part cooling fan and duct mounting - top rear screws |
|1 | Short PTFE tube | Between extruder and hotend |

#### Fans
| Qty | Fan Type | Recommended Fan | Notes |
|-----|------|------|-----|
| 1 | 2510 Axial Fan <br/> Hotend Fan | Delta Electronics 5v <br/> ASB02505SHA-AY6B | <a href="https://www.digikey.com/en/products/detail/delta-electronics/ASB02505SHA-AY6B/7491489">Purchase Link</a> <br/> `This fan is highly recommended in heated chambers`<br/>`No other 2510 fan comes close to the performance`<br/>`of this fan.` | 
| 2 | 4010 Blower Fan <br/> Part Cooling Fans | Delta Electronics <br/> BFB0412HHA-A (12V) <a href="https://www.digikey.com/en/products/detail/delta-electronics/BFB0412HHA-A/2560487">Purchase Link</a> <br/> BFB0405HHA-A (5V)  <a href="https://www.digikey.com/en/products/detail/delta-electronics/BFB0405HHA-A/1014444">Purchase Link</a> <br/> |  `GDStime fans are fine.`<br/>`The Deltas, however, have better durability`<br/>`in heated chambers and always hit their performance claims.`<br/>`Its not uncommon for other fan manufacturers`<br/>`to overstate performance, GDStime included.`|

Additional notes: Delta's 5V and 12V variants provide the same airflow, pick whichever suits your setup better. If you only have 24V available, you can use a 24V-12V buck converter like [K78L12-500R3](https://www.digikey.com/en/products/detail/mornsun-america-llc/K78L12-500R3/16784476).

#### Optional Hardware
| Qty | Item | Notes|
|-----|------|------|
|1 | M3 Heatset Insert| Sherpa-Mini K-plate attachment|
|1 | M3 Heatset Insert| DFA Custom bottom|
|2 | M3 Heatset Insert| *If not using M2.5 hardware for HE Mount "feet" |
|1 | M2 Heatset Insert | 3.5mm Outer Diameter x 4mm Length <br/>X End stop|
|1 | M2 x 10 SHCS | X End stop|
|1 | Stealthburner Neopixel LED harness | If using LED ducts and faceplate <br/>`custom neopixel harness if using only duct LEDs` |


⬅ [README](README.md) - [Printed Parts](printing.md) ➡
