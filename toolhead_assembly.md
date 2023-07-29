# Xol Toolhead Assembly

<img src='images/xol_toolhead/toolhead-sherpa-rapido.png' width=250 />

### These instructions are for off-printer assembly using Xol Carriage. If you use Voron TAP, scroll down, you have to do things differently.
The details below are for Rapido and Sherpa-Mini. We have faith that you can work it out from here if you're using a different combination of hotend and extruder. If you have trouble look for the #xol-toolhead channel on the Discord.
|Notes | Image |
|---------|----------|
| Warm up the soldering iron again. It's time for heatsets<br/>* 2x M3 (+1 if using Sherpa Mini)<br/>* 2x M2.5 in the feet<br/> * 4x M2.5 if you're using them for the hotend fan <br/> * 4x M2 for Part cooling fan rear mounting points <br/><br/>`If you're using TAP don't put M2.5 heatsets in the feet. Also, if you're using TAP why are you reading this? Your instructions are at the bottom of the page` | <img src='images\xol_toolhead\HE_mount_heatsets.png' width=400 /> |
| 4x M2 in the faceplate rear (LED or standard) <br/> <br/><br/><br/> `The top two heatsets go in on the same angle as the bottom two, not straight in from the side` | <img src='images\xol_toolhead\Faceplate_heatsets_LED.png' width=105 /><img src='images\xol_toolhead\Faceplate_heatsets.png' width=95 /><br/><img src='images\xol_toolhead\Faceplate_heatsets_side.png' width=200> |
| Don't forget these 2 in the back of the adapter plate | <img src='images\xol_toolhead\xol_adapter_heatsets.png' width=300 /> |
| Screw on the hotend. | <img src='images\xol_toolhead\Mount_hotend.png' width=500 /> |
| Insert the [correct length PTFE](PTFE_Length.md) tube and get your adapter plate ready.| <table><tr><td> <img src='images\xol_toolhead\HE_mount_ptfe.png' width=120> <br/> Sherpa Mini </td><td> <img src='images\xol_toolhead\adapter_DFA.png' width=120> <br/> DFA</td> </tr> <tr><td> <img src='images\xol_toolhead\adapter_vz-hextrudort-low.png' width=120> <br/> Vz-Hextrudort-Low<br/> / LGX-Lite</td><td> <img src='images\xol_toolhead\adapter_obiter.png' width=120> <br/> Orbiter v2.0</td> </tr> </table> |
| Attach your extruder with <br/> M3 x [correct length and type for your extruder] | <img src='images\xol_toolhead\attach_extruder.png' width=300 /> |
| Attach your stepper motor with M3 screws long enough to securely attach the M3 x 20mm metal stand offs | <img src='images\xol_toolhead\attach_motor.png' width=300 /> |
| Can you do the can-can? me either. Attach your CAN or breakout board with <br/> * 2x M3 x 16 SHCS | <img src='images\xol_toolhead\attach_ebb-CAN.png' width=300 /> |
| If you're using the LED faceplate, make sure the diffuser is in place. A little drop of super glue helps a lot here.| <img src='images\xol_toolhead\LED_faceplate_diffuser.png' width=100 /> |
| Four screws to attach the hotend cooling fan. They go through the front and rear faceplate printed parts, and the 2510 fan. <br/> 4x M2.5 x 20 SHCS (no fan heatsets `*don't over tighten`) <br/> 4x M2.5 x 16 SCHS (with fan heatsets) <br/> <br/>`If you're using LEDs, the middle one should be in the rear faceplate, with one hanging down each side towards where the ducts will go. The wires go over the top of the 2510 fan.` <br/><br/> `**For Dragon UHF the two lower M2.5 screws must be M2.5 x16 SHCS even with no fan heatset inserts**` | <img src='images\xol_toolhead\fan_faceplate.png' width=300 /> |
| Don't make a mess of it now. <br/> Think about where you're wires will go | <img src='images\xol_toolhead\wire_exit.png' width=300 /> |
| Each fan attaches with <br/> * 3x M2 x 12 SHCS, and <br/> * 1x M2 x 8 SCHS `top rear` <br/><br/> `If you're using LEDs, push them into the sockets on the ducts before you attach the fans/duct to the toolhead` | <img src='images\xol_toolhead\fan_screws.png' width=300 /> |
| Finish off your wiring and tidy up with the cable tie slots. It's finally time to put this thing on the printer.| <img src='images\xol_toolhead\mess.jpg' width=300 /> |
| * 2x M3 x 20 SHCS from the front | <img src='images\xol_toolhead\toolhead_to_carriage_front.png' width=300 /> |
|Sneak up from the rear with your Allen keys <br/> * 3x M3 x 8 SHCS at the top, and <br/> * 2x M2.5 x 10 SHCS at the bottom | <img src='images\xol_toolhead\toolhead_to_carriage_rear.png' width=300 /> |
|Plug in your probe wires `end stop too if you haven't converted to sensorless homing yet` <br/> Connect your toolhead board or umbilical stuff. You're not using drag chains, are you? <br/> <br/>You're done! `but don't forgot your software. Check [stepper_x] section for position_endstop and position_max.` | <img src='images\xol_toolhead\keep_it_tidy.png' width=300 /><img src='images\xol_toolhead\photo_rear.png' width=300 /> |


### Here lie the instructions for installing Xol Toolhead on Voron TAP. 
If you haven't noticed yet, it's easier on Xol Carriage, but we get it TAP is TAP.


|Notes | Image |
|---------|----------|
| `Install TAP into your printer as per Voron Design instructions` <br/> <br/> Once that's done, install the TAP adapter printed part for your extruder with <br/> * 2x M3 x 8 SHCS | <img src='images\tap_toolhead\attach_tap_adapter.png' width=300 /> |
| Install heatsets as per instructions above <br/> `Make sure not to put any in the feet. You may need to run an M3 drill through the feet too.` | <img src='images\tap_toolhead\lower_toolhead_no_heatsets.png' width=300 /> |
| Assemble the hotend mount with your hotend, 2510 HE cooling fan, faceplate parts and loosly attach the part cooling fans using the top screws only.  | <img src='images\tap_toolhead\lower_toolhead_no_ducts.png' width=300 /> |
| Now you can put the mostly assembled hotent mount parts onto TAP using <br/> * 2x M3 x 20 SHCS, and <br/> * 2x M3 x 12 SCHS <br/> <br/> <br/> `Make sure you have the PTFE tube that goes between the extruder and hotend installed before moving onto the next step. Failure to do so will end in tears` <br/> [PTFE Tube Lengths](PTFE_Length.md) | <img src='images\tap_toolhead\hotend_mount_to_TAP.png' width=300 /> |
| Now you can attach the ducts and tighten all the M2 screws holding them, and the part cooling fans, on.  | <img src='images\tap_toolhead\attach_ducts.png' width=300 /> |
| Put your extruder, stand offs, EBB board mount and EBB board together. | <img src='images\tap_toolhead\extruder_and_board.png' width=300 /> |
| Attach your extruder/board etc. to the top of the TAP adapter plate. <br/> You're ready to finish wiring, software config and start printing. Sounds simples right? | <img src='images\tap_toolhead\tap_dragonUHF_orbiter.png' width=300 /> |


 ⬅ [Carriage assembly](xol_carriage_assembly.md)
