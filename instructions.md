# Things:
- Raspberry Pi Zero 2. Click [here](https://rpilocator.com/?cat=PIZERO2) to find a Raspberry Pi.
- Battery. (Listed in the [parts to buy](p2b) section)
- Altoids Tin.
- The Sensors. (Listed in the [parts to buy](p2b) section)
- The Display, Buttons, Switches, and Speakers (Listed in the [parts to buy](p2b) section).
- [3D printed parts](stls).
- A drill.
- An SD Card.
- A Windows, Linux, or Mac machine.
- The [image](Alto.img) provided.
- A Marker.
- A Small Blade.
- Electrical Tape.

# Steps to Follow
## Prep work
1. Download the image and flash it to your SD card of choice. Set off to side.
2. 3D print all of the STL files in any color you want (or you could make it match the tin color!).
3. Grab the [Outside Stencil](stls/outside_stencil.stl) and your drill with a small drill bit.
4. Put the stencil on the bottom of your tin and drill in the places where the ports and sensors will be (Be very careful NOT to drill into the 3D printed part!).
5. Place Electrical Tape on the inside of the tin.
## Top
1. Lay the tin down so the hinge is at a 180 Degree angle.
2. Place the display in the top of the tin and secure with some glue.
3. Put the 3D printed part in the top of the tin with some glue and pull the ribbon cable down.
4. Let dry.
## Bottom
1. Place the SD Card into the Pi and plug all of the cables into there respective slots.
2. Fit all sensors into the GPIO pins as shown [here](gpio.png).
3. Place the charging circut and battery into the tin.
4. Place the button pcb and the buttons of choice into the tin.
5. Place the speakers into the 3D print and plug them into the pi
6. Charge the battery and turn it on.
7. Glue it together
## After Setup
1. Press and hold the AltOS Button:![restart_alt_FILL1_wght400_GRAD0_opsz48](https://github.com/tired-tux/AltoPi/assets/121198893/58d3840a-9cbd-4004-be6a-60f77a44e91a) to go into the menu.
## Change from stable to other branch
1. Power Off Device.
2. Press and hold the 'Y' and AltOS Button
3. Press the Power Button while still holding down the 'Y' and AltOS Button.
4. A Menu will show up with 3 options:
- Stable :white_check_mark:
- Canary ❎
- Nightly ❎
5. Choose the branch you want.
6. The OS will update itself.
