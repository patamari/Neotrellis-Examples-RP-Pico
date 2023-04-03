# Neotrellis-Examples-RP-Pico
Edited the Adafruit examples to work with Raspberry Pi Pico in Arduino IDE

I recently built a Neotrellis Grid and wanted to test the seesaw boards before committing to soldering. These are the two little test programs for the Neotrellis boards provided by Adafruit but modified so it knows how to use the i2c bus. I used Arduino IDE, you will need the RP2040 board manager and the adafruit seesaw libraries downloaded for this to work. This is also assuming you use GPIOs 26 and 27 for SDA and SCL over I2C1. You can use different IO ports and I2C0 if you want but you will have to edit the files to do so.

Huge thanks to Denki Oto for making this happen.

One other thing I noticed is that the multitrellis example would crash and loop my pico, depending on which USB port on my computer I was using. I guess some of the ports don't provide as much current.
