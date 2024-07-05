# Build instructions for Xol Toolhead LED harness
> [!WARNING]
> ## Sequin PCB thickness   
> The hotend mounts are only compatible with thin PCB board sequins.  
> Known compatible sources:<br/>
> RGBW: [LAB4450 (EU)](https://lab4450.com/product/rgbw-sequins/)<br/>
> RGBW: [Replimat[labs] (EU)](https://www.replimat.eu/4x-rgbw-sequins-for-xol-minisb/rt10179)<br/>
> RGB:  [FYSETC (Ali Express)](https://www.aliexpress.com/item/1005006023213341.html)


> [!IMPORTANT]
> ## LED Order
> Wiring as shown will result in the LED order being the same as for the popular StealthBurner LED harness.<br/>
> This should enable the use of popular LED control macros without complex modifications.

| Notes           | Image               |
|---------------- | ------------------- |
| Required Tools  | Wire cutters<br/>Wire strippers<br/>Soldering equipment<br/>Helping hands<br/>Crimping tools to suit your connection type |
| Get all the bits together (BoM) <br/><br/>(11x) Lengths of 26 or 28AWG electrical wire:<br/>- (3x) ~200mm `+/-/D` with one end stripped and tinned <br/>- (4x) ~35mm `+/-`with one end stripped and tinned (+/-)<br/>- (3x) 70mm `+/-/D` stripped and tinned at both ends<br/>- (1x) ~135mm `D` stripped and tinned at both ends<br/>(1x) Neopixel LED PCB<br/>(2x) Sequin LED PCB (0.8mm thick PCB board)<br/>JST XH (or similar) connector and pins to suit your printer<br/><br/>`+` = 5V+ wire <br/>`-` = Ground wire<br/>`D` = Data/Signal wire <br/><br/>Lengths given are for a harness that works with either UHF or standard length toolheads | <img src='assets/images/led_harness/LED_Harness.jpg' width=400 />                                                         |
| Follow the wiring diagram above. <br/> The completed harness should look similar to the photos shown.  <br/><br/> Completed Harness  | <img src='assets/images/led_harness/complete_harness.png' width=400 /> |
| Neopixel `Status LED`     | <img src='assets/images/led_harness/neopixel_rear.png' width=400 />       |
| Sequin #1 `Part Lighting` | <img src='assets/images/led_harness/sequin_1_rear.png' width=400 />       |
| Sequin #2 `Part Ligting`  | <img src='assets/images/led_harness/sequin_2_rear.png' width=400 />       |
| Powered up!               | <img src='assets/images/led_harness/powered_on_harness.png' width=400 />  |

⬅  [Toolhead assembly](toolhead_assembly.md)