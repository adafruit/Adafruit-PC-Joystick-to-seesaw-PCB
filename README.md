## Adafruit PC Joystick to seesaw I2C Adapter - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/5753"><img src="assets/5753.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PC Joystick to seesaw I2C Adapter - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5753

### Description

Back in Ladyada's day, we used to have these big chunky PC joysticks that would plug into the back of your PC. No, not through USB, they had a DE-15 port and they'd go into the Game Port your sound effects card. Now, of course, we have tons of USB ports and quality audio is built into every computer. But what if you want to re-live your Commander Keen days?

This board has a 15 pin D-Sub socket port, that you can plug any classic PC joystick into. Onboard is a ATtiny816 helper chip that acts as a I2C peripheral using our 'seesaw' library. Two STEMMA QT ports mean you can plug this board in using a 4-pin JST SH cable to any microcontroller or microcomputer with I2C support and read the joystick X & Y plus the two buttons, even if your main chip doesn't have analog inputs. There's even a 5V power generator on-board since joysticks are expecting that voltage.

Great for converting old controllers without needing to cut any cables. We have example code for Arduino and CircuitPython / Python to make your next pew pew project a breeze.

Ships fully assembled and tested. If you prefer working on a breadboard, each order comes with a small piece of header. You'll need to solder the header onto the PCB, but it's fairly easy and takes only a few minutes even for a beginner. 

## DE-15 Connector Wiring

We suggest referring to the diagrams on [this page](https://allpinouts.org/pinouts/connectors/input_device/joystick-pc-gameport/) and on [Wikipedia](https://en.wikipedia.org/wiki/Game_port).

The original IBM Game Control Adapter manual is [here](https://www.minuszerodegrees.net/oa/OA%20-%20IBM%20Game%20Control%20Adapter.pdf).

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
