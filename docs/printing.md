# Printing Xol Parts

### Xol parts are not scaled to suit any particular filament. You will need to calibrate your printer/filament appropriately before printing Xol Parts

It is recommended to print a calibration part of a known size and adjust slicer shrinkage compensation.

### Printer tuning
Making Xol easier to assemble also meant making the main hotend mount part a more difficult print. You will need to have a reasonably well callibrated printer (although it was tested on a barely tuned Ender 3). <br/>
Some things in particular to note:
* Support removal `If you're printing too hot or with insufficient cooling the built in supports may be difficult to remove.`
* Overhangs `They're not too steep, but will be a problem if your not printing your perimeters "inside to outside".`
* Wall widths `Some of the supports have a built in "interface" layers. Make sure your printer profile allows printing of walls down to at least 0.4mm. Check that you can see them in your slicer before you print them. DO NOT use walls wider than 0.55mm`

## What to print
There are many combinations of carriages/hotends/extruders that can be used with Xol. The tables below outline what you should print.

### Carriage
#### Xol Carriage
Pick the parts you need from the lists below and follow the instructions in [xol_carriage_assembly.md](xol_carriage_assembly.md) to build.

Carriage Size
* MGN12H: [Xol-Carriage_MGN12H.stl](../STL/Xol-Carriage/Xol-Carriage_MGN12H.stl)
* MGN9H: [Xol-Carriage_MGN9H.stl](../STL/Xol-Carriage/Xol-Carriage_MGN9H.stl)

Belt Width
* 6MM: [[a]_belt_clamp_6mm_x2.stl](../STL/Xol-Carriage/[a]_belt_clamp_6mm_x2.stl)
* 9MM: [[a]_belt_clamp_9mm_x2.stl](../STL/Xol-Carriage/[a]_belt_clamp_9mm_x2.stl)

Probe Modules
* Pick the module to match your supported probe from the [Probe Modules](<../STL/Xol-Carriage/Probe Modules>) folder. <br/>
`Probe length should match the hotend length (standard or UHF)`

#### Voron Design TAP
Follow instructions from Voron Design <br /> _`For TAP RC8, replace the M3x50 SCHS with M3x50 BHCS to avoid bed clearance issues with regular length Xol Ducts`_

### Hotend Mount
Pick one option from the table below, depending of if you're using 4010 blower fans or remote cooling (XolPAP) for part cooling.

| Hotend                              | 4010 Blower                                                                                             | XolPAP (Remote Cooling)                                                                                       | Duct Length (for probe module / XolPAP) |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| Rapido HF                           | [Xol_HE_Mount-Rapido_HF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_HF_Fan.stl>) <br/><br/> [Xol_HE_Mount-Rapido_v2_HF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_v2_HF_Fan.stl>)                   | [Xol_HE_Mount-Rapido_HF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_HF_XolPAP.stl>) <br/><br/> [Xol_HE_Mount-Rapido_v2_HF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_v2_HF_XolPAP.stl>)                    | Standard                                |
| Rapido UHF                          | [Xol_HE_Mount-Rapido_UHF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_UHF_Fan.stl>) <br/><br/> [Xol_HE_Mount-Rapido_v2_UHF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_v2_UHF_Fan.stl>)                  | [Xol_HE_Mount-Rapido_UHF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_UHF_XolPAP.stl>) <br/><br/> [Xol_HE_Mount-Rapido_v2_UHF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_v2_UHF_XolPAP.stl>)                  | UHF                                     |
| DropEffect XG                       | [Xol_HE_Mount-XG_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-XG_Fan.stl>)                                   | [Xol_HE_Mount-XG_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-XG_XolPAP.stl>)                                   | Standard                                |
| DropEffect NeXtG (without extender) | [Xol_HE_Mount-DragonSF-HF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonSF-HF_Fan.stl>)                 | [Xol_HE_Mount-DragonSF-HF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonSF-HF_XolPAP.stl>)                 | Standard                                |
| DropEffect NeXtG (with extender)    | [Xol_HE_Mount-DragonUHF_Mini_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonUHF_Mini_Fan.stl>)           | [Xol_HE_Mount-DragonUHF_Mini_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonUHF_Mini_XolPAP.stl>)           | Standard                                |
| Red Lizard K1-UHF                   | [Xol_HE_Mount-Rapido_UHF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_UHF_Fan.stl>)                   | [Xol_HE_Mount-Rapido_UHF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Rapido_UHF_XolPAP.stl>)                   | UHF                                     |
| Dragon UHF                          | [Xol_HE_Mount-DragonUHF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonUHF_Fan.stl>)                     | [Xol_HE_Mount-DragonUHF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonUHF_XolPAP.stl>)                     | UHF                                     |
| Dragon UHF-Mini (extender removed)  | [Xol_HE_Mount-DragonUHF_Mini_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonUHF_Mini_Fan.stl>)           | [Xol_HE_Mount-DragonUHF_Mini_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonUHF_Mini_XolPAP.stl>)           | Standard                                |
| Dragon Standard / High Flow         | [Xol_HE_Mount-DragonSF-HF_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonSF-HF_Fan.stl>)                 | [Xol_HE_Mount-DragonSF-HF_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-DragonSF-HF_XolPAP.stl>)                 | Standard                                |
| Dragon Ace (without extender)       | [Xol_HE_Mount-Dragon-Ace_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Dragon-Ace_Fan.stl>)                   | [Xol_HE_Mount-Dragon-Ace_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Dragon-Ace_XolPAP.stl>)                   | Standard                                |
| Dragon Ace (with extender)          | [Xol_HE_Mount-Dragon-Ace_Extender_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Dragon-Ace_Extender_Fan.stl>) | [Xol_HE_Mount-Dragon-Ace_Extender_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Dragon-Ace_Extender_XolPAP.stl>) | UHF                                     |
| Revo Voron                          | [Xol_HE_Mount-Revo-Voron_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-Revo-Voron_Fan.stl>)                   | [Xol_HE_Mount-Revo-Voron_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-Revo-Voron_XolPAP.stl>)                   | Standard                                |
| NF-Crazy Volcano                    | [Xol_HE_Mount-NF-Crazy_Volcano_Fan.stl](<../STL/HE Mounts/Xol_HE_Mount-NF-Crazy_Volcano_Fan.stl>)       | [Xol_HE_Mount-NF-Crazy_Volcano_XolPAP.stl](<../STL/HE Mounts/Xol_HE_Mount-NF-Crazy_Volcano_XolPAP.stl>)       | UHF                                     |

#### XolPAP Ducts
If you're using XolPAP remote cooling, you will need either standard or UHF length ducts:
* Standard: [XolPAP Standard Length Duct.stl](<../STL/XolPAP ducts/XolPAP Standard Length Duct.stl>)
* UHF: [XolPAP UHF Length Duct.stl](<../STL/XolPAP ducts/XolPAP UHF Length Duct.stl>)

`⚠️ * G2SA and WWG2 extruders not compatible with XolPAP `

### Extruder Mount

Pick one extruder mount from the table below to match your extruder, and if it's going on Xol-Carriage or on TAP/Voron carriage.

| Extruder                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Xol-Carriage                                                                                                                                                                                                | TAP / Voron Carriage                                                                                                                                                                                                     |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Sherpa-Mini / <br/> Sharkfin  <br/>`K-face plate and optional` <br/> `short idler arm for Sherpa-Mini ` <br/> `from Annex Engineering`<br/> [Sherpa front k-face](<https://github.com/Annex-Engineering/Sherpa_Mini-Extruder/blob/master/STLs/optional_parts/%5Ba%5D_housing_front_k_x1_rev15.STL>) <br/> [Sherpa short idler arm](<https://github.com/Annex-Engineering/Sherpa_Mini-Extruder/blob/master/STLs/optional_parts/%5Ba%5D_idler_arm_short_x1_rev16a.STL>) | [Xol Extruder Mount - Sherpa-Mini.3mf](<../STL/Extruder Mounts/Xol Extruder Mount - Sherpa-Mini.3mf>)                                                                                                       | [Xol Extruder Mount - Sherpa Mini - TAP.3mf](<../STL/Extruder Mounts/Xol Extruder Mount - Sherpa Mini - TAP.3mf>)                                                                                                        |
| Annex Double Folded Ascender                                                                                                                                                                                                                                                                                                                                                                                                                                         | [Xol Extruder Mount - DFA.stl](<../STL/Extruder Mounts/Xol Extruder Mount - DFA.stl>) <br/>   *License [Note](<DFA_MOD_License.md>)                                                                         | Not Supported                                                                                                                                                                                                            |
| Vz-Hextrudort-Low / <br/> LGX-Lite                                                                                                                                                                                                                                                                                                                                                                                                                                   | [Xol Extruder Mount - VZ-Hex+LGX-L.stl](<../STL/Extruder Mounts/Xol Extruder Mount - VZ-Hex+LGX-L.stl>)                                                                                                     | [Xol Extruder Mount - VZ-Hex+LGX-L - TAP.stl](<../STL/Extruder Mounts/Xol Extruder Mount - VZ-Hex+LGX-L - TAP.stl>)                                                                                                      |
| Galileo G2SA (Orbiter mount pattern) <br/> `NOT XolPAP Compatible`                                                                                                                                                                                                                                                                                                                                                                                                                                | [Xol Extruder Mount - G2SA.stl](<../STL/Extruder Mounts/Xol Extruder Mount - G2SA.stl>), AND <br/>  [G2SA front for Xol Extruder Mount.stl](<../STL/Extruder Mounts/G2SA front for Xol Extruder Mount.stl>) | [Xol Extruder Mount - G2SA - TAP.stl](<../STL/Extruder Mounts/Xol Extruder Mount - G2SA - TAP.stl>) , AND <br/>  [G2SA front for Xol Extruder Mount.stl](<../STL/Extruder Mounts/G2SA front for Xol Extruder Mount.stl>) |
| WristWatch G2 (Orbiter mount pattern)  <br/> `NOT XolPAP Compatible`                                                                                                                                                                                                                                                                                                                                                                                                                                | [Xol Extruder Mount - G2SA.stl](<../STL/Extruder Mounts/Xol Extruder Mount - G2SA.stl>), AND <br/>  [WWG2 front for Xol Extruder Mount.stl](<../STL/Extruder Mounts/WWG2 front for Xol Extruder Mount.stl>) | [Xol Extruder Mount - G2SA - TAP.stl](<../STL/Extruder Mounts/Xol Extruder Mount - G2SA - TAP.stl>) , AND <br/>  [WWG2 front for Xol Extruder Mount.stl](<../STL/Extruder Mounts/WWG2 front for Xol Extruder Mount.stl>) |
| WristWatch BMG                                                                                                                                                                                                                                                                                                                                                                                                                                | [Xol Extruder Mount - G2SA.stl](<../STL/Extruder Mounts/Xol Extruder Mount - G2SA.stl>), AND <br/>  [WWBMG front for Xol Extruder Mount.stl](<../STL/Extruder Mounts/WWBMG front for Xol Extruder Mount.stl>) | [Xol Extruder Mount - G2SA - TAP.stl](<../STL/Extruder Mounts/Xol Extruder Mount - G2SA - TAP.stl>) , AND <br/>  [WWBMG front for Xol Extruder Mount.stl](<../STL/Extruder Mounts/WWBMG front for Xol Extruder Mount.stl>) |
| Escapement                                                                                                                                                                                                                                                                                                                                                                                                                                                           | [Xol Extruder Mount - Escapement.stl](<../STL/Extruder Mounts/Xol Extruder Mount - Escapement.stl>)                                                                                                         | [Xol Extruder Mount - Escapement - TAP.stl](<../STL/Extruder Mounts/Xol Extruder Mount - Escapement - TAP.stl>)                                                                                                          |
| Orbiter v2.0                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [Xol Extruder Mount - Orbiter V2.stl](<../STL/Extruder Mounts/Xol Extruder Mount - Orbiter V2.stl>)                                                                                                         | [Xol Extruder Mount - Orbiter V2 - TAP.stl](<../STL/Extruder Mounts/Xol Extruder Mount - Orbiter V2 - TAP.stl>)                                                                                                          |

 
 ### Faceplate
There's only one option for the faceplate now. If you don't want an LED in the status light area, print the "diffuser" in a contrasting colour to the main faceplate part to show off the Xol logo.
* [Faceplate.stl](../STL/Faceplate/Faceplate.stl)
* [[t] Logo LED diffuser.stl](<../STL/Faceplate/[t] Logo LED diffuser.stl>) `Clear/translucent for diffuser, or contrasting colour for no LED`


 #### EBB 36 Mount
 Print the EBB 36 mount for Xol-Carriage to suit your CAN or break-out board / extruder combination.<br/>
 `If you aren't using Xol-Carriage (TAP users) there are numerous EBB mounts availble like these from KayosMaker:`[CANboard_Mounts](https://github.com/KayosMaker/CANboard_Mounts)
| Extruder | Without strain relief | With strain relief|
|-----|------|------|
|Sherpa-Mini |[EBB36 Mount - Sherpa-Mini.stl](<../STL/EBB Mounts/EBB36 Mount - Sherpa-Mini.stl>)|[EBB36 Mount - Sherpa-Mini [strain relief].stl](<../STL/EBB Mounts/EBB36 Mount - Sherpa-Mini [strain relief].stl>) |
|DFA | {todo} | {todo} |
| Galileo 2SA | {todo} | {todo} |
| Escapement | {todo} | {todo} |
|VZ-Hextrudort-Low | [EBB36 Mount - VZ-Hextrudort-Low.stl](<../STL/EBB Mounts/EBB36 Mount - VZ-Hextrudort-Low.stl>) | [EBB36 Mount - VZ-Hextrudort-Low [strain relief].stl](<../STL/EBB Mounts/EBB36 Mount - VZ-Hextrudort-Low [strain relief].stl>) |
| LGX-Lite | {todo} | {todo} |
|Orbiter v2.0 | [EBB36 Mount - Orbiter2.0.stl](<../STL/EBB Mounts/EBB36 Mount - Orbiter2.0.stl>) | [EBB36 Mount - Orbiter2.0 [strain relief].stl](<../STL/EBB Mounts/EBB36 Mount - Orbiter2.0 [strain relief].stl>) |


### M2.5 Savers
 Add a little colour, and protect your delicate 4010 blower fans <br/>
* [[a]_M2.5_saver_x4.stl](../STL/Faceplate/[a]_M2.5_saver_x4.stl) `These aren't optional extras, you need them to protect your fans. Also the screw holes are too shalow without them`


### Trident stepper spacer
On some Trident printers, the leadscrews are slightly too high and may collide with the Xol ducts when the toolhead is at the very front corners of the printer (usually only the right side when homing at Y,0). <br/>
To avoid this colision, there is a spacer available on printables that will lower the leadscrew stepper motors: [https://www.printables.com/model/486638-voron-trident-z-steppers-spacers](https://www.printables.com/model/486638-voron-trident-z-steppers-spacers)

<br/><br/><br/><br/>


⬅ [BOM](BOM.md) - [Carriage assembly](xol_carriage_assembly.md) ➡
