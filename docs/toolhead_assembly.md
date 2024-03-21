# Xol Toolhead Assembly

<img src='assets/images/Xol-Toolhead_render_with_both.png' width=100% />


`The details below are for Rapido and Sherpa-Mini. We have faith that you can work it out from here if you're using a different combination of hotend and extruder. If you have trouble look for the #xol-toolhead channel on the Discord.`
|	Notes	|	Image	|
|	--------------------	|	--------------------	|
|	Remove the included supports. They're going to get in the way if you don’t.	|	<img src='assets/images/xol_toolhead/supports_he_mount.png' width=300 /><img src='assets/images/xol_toolhead/supports_extruder_mount.png' width=300 />	|
|	An easy one to start, put one M3 hexnut into the hotend mount. <br/>`Pushes in from below on most, slides in from the side for NF-Crazy & XG`	|	<img src='assets/images/xol_toolhead/em_hexnut.png' width=400 />	|
|	LEDs are next (if you're using them). <br/>Push them into the slots provided. <br/><br/> Build instructions for the LED harness can be found [here](led_harness.md)	|	<img src='assets/images/xol_toolhead/led_wires_1.png' width=400 /><br/><img src='assets/images/xol_toolhead/led_wires_2.png' width=300 /><br/><img src='assets/images/xol_toolhead/led_wires_3.png' width=300 />	|
|	Push the diffuser (or accent logo piece) into the faceplate.	|	<img src='assets/images/xol_toolhead/faceplate_install_diffuser.png' width=400 />	|
|	Install the 2510 hotend fan. Make sure you don't squash any LED wires, and secure with <br/>4x M2.5x16 SHCS.<br/><br/>⚠️ **Screws are going into plastic. Do NOT over tighten**	|	<img src='assets/images/xol_toolhead/toolhead_2510_faceplate2.png' width=400 />	|
|	Put the screws into the "feet" now, your hotend may be in the way later.<br/>2x M3x12 SHCS	|	<img src='assets/images/xol_toolhead/feet_screws.png' width=400 />	|
|	Install your hotend into the mount. Don't forget the PTFE tube. |	<img src='assets/images/xol_toolhead/install_he.png' width=400 />	|
|	⚠️ **If installing Rapido, you will need to make sure that it has the correct alignment.** <br/>You should see the grub screw in the heat sink slightly to the right of center when the wires are coming out to the left side.	|	<img src='assets/images/xol_toolhead/rapido_orrientation.png' width=400 />	|
|	Slide the fans in and fix with printed parts and screws. `The printed parts protect the 4010 blower mounting ears. Don't skip them`<br/>4x M2.5 saver [printed part]<br/>4x M2.5x8 SCHS<br/><br/>⚠️ **Screws are going into plastic. Do NOT over tighten**<br/><br/><br/><br/><br/>XolPAP users can skip this step. Those ducts are put on at the end.	|	<img src='assets/images/xol_toolhead/complete_he_mount2.png' width=300 /><img src='assets/images/xol_toolhead/complete_he_mount1.png' width=300 /><br/><img src='assets/images/xol_toolhead/complete_he_mount_xolpap.png' width=300 />	|
|	Time to move onto the extruder mount assembly. Install 4 or 5 heatset inserts into your extruder mount.	|	<img src='assets/images/xol_toolhead/extruder_mount_heatsets.png' width=400 />	|
|	Attach the extruder to the extruder mount.<br/>2x M3x20 SHCS for Sherpa-Mini (usually M3x8 SHCS for others)<br/>1x M3x6 BHCS for extruder faceplate where applicable.	|	<img src='assets/images/xol_toolhead/extruder_to_extruder_mount.png' width=400 />	|
|	Screw your 20mm stand-offs onto the long screws you used to attach your extruders stepper motor.	|	<img src='assets/images/xol_toolhead/20mm_standoffs.png' width=400 />	|
|	Now you can mount your toolhead board/CAN board/strain relief printed part etc. to the stand-offs<br/>2x M3x16 SHCS	|	<img src='assets/images/xol_toolhead/attach_ebb-CAN.png' width=400 />	|
|	The extruder assembly is now combined with the HE mount assembly.<br/>1x M3x6 BHCS<br/>2x M3x16 SHCS `Just through enough to hold it all together`	|	<img src='assets/images/xol_toolhead/attach_extruder-to_he-mount.png' width=400 />	|
|	Now that everything is together, those using CAN or other toolhead boards can cut/crimp/tidy wiring to the right lengths before final assembly.	|	<img src='assets/images/xol_toolhead/mess.jpg' width=400 />	|
|	⚠️ **Tap/Standard Voron carriage users only!**<br/><br/>Now you have to undo your cables from your toolhead board and pull the extruder assembly off again.<br/><br/>Take the extruder off the extruder mount, and attach it to the top of the Tap/Voron carriage with 2x M3x8 SHCS.<br/><br/>Slide the HE mount assembly up under the extruder mount and re-attach the HE mount to the extruder mount.`Rember you're probably screwing into plastic on a Voron carriage here!`<br/><br/>Now you can put your extruder/toolhead board bits back on and reconnect all your wires.	|	<img src='assets/images/xol_toolhead/tap_extruder_mount.png' width=400 /><br/><img src='assets/images/xol_toolhead/tap_extruder_and_hotend_mounts.png' width=400 /><br/><img src='assets/images/xol_toolhead/tap_extruder_and_thb.png' width=400 />	|
|	Now that we have that Tap stuff out of the way. Time to get things attached for Xol Carriage.<br/><br/>Start with the two front, upper screws<br/>2x M3x16 that were already there but need to be tightened.	|	<img src='assets/images/xol_toolhead/toolhead_to_carriage_upper_screws.png' width=400 />	|
|	⚠️ **The front lower screws need a ball head hex driver. Don't strip your SHCS.**<img src='assets/images/ball-driver.png' width=190 align='right' /><br/><br/>Tighten the feet<br/>2x M3x16 SHCS, that were also already there. <br/><br/>`This is for Tap/Voron Carriages too.`	|	<img src='assets/images/xol_toolhead/toolhead_to_carriage_lower_screws.png' width=400 />	|
|	Reach around the back for the last 3 screws!<br>3x M3x8 SHCS <br/><br/>`Sorry XolPAP users, you have some more screws`<br/><br/>`Don't forget to connect your probe`	|	<img src='assets/images/xol_toolhead/toolhead_to_carriage_rear_screws.png' width=400 />	|
|	Alright XolPAP fans, we're finally here. Slide the ducts over the toolhead and attach with<br/>8x M2.5x8 SHCS `4 per side`<br/><br/>⚠️ **Screws are going into plastic. Do NOT over tighten**	|	<img src='assets/images/xol_toolhead/xolpap_screws.png' width=400 />	|
|Don't forget your software configuration!| ⚠️ Things are probably different with your new setup. <br/> <br/> * Endstop positions for X: `[stepper_x]` check `position_endstop` and `position_max` <br/> * Your probe offset: Do a `probe_calibrate` <br/> You know your printer better than anyone else. Check your work. |


<br/><br/><br/><br/>
 ⬅ [Carriage assembly](xol_carriage_assembly.md) - [LED Harness instructions](led_harness.md) ➡
