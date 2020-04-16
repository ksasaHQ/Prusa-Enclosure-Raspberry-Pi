# Prusa I3 MK3S Einsy + Raspberry Pi Enclosure

This is a remix of [martin_au's](https://www.thingiverse.com/martin_au) excellent [Embiggened, braced, reversed, Prusa Mk3 Einsy enclosure.](https://www.thingiverse.com/thing:3424832) to include a Raspberry Pi 2.

Rather than adding another box for the Raspberry Pi to go in, we wanted a clean, integrated solution: So here it is!

## Caveats:

- It should fit a Raspberry Pi 3 but we have not tested this. (If you do, please let us know!)
- Space within the enclosure is a quite cramped, so connecting the wires to the Pi can be a bit, well, fiddly. We suggest you brew yourself a cup of tea before doing this. (Or issue a pull request with a higher case 😉)
- In our experience it is perfectly possible to power the Raspberry Pi from the Einsy Board, even when using the Multi Material Upgrade. If you are planning to power additional devices from the Pi however, consider adding a separate power adapter or upgrade the one that came with your printer.
- This design blocks the Pi’s power connector, so it needs to be powered via the 5V rail (Pins 2 and 6, see schematic below). Please be aware that other than the USB power connector, the rail does not feature a regulator or fuse. An incorrect voltage or current spike could fry the Pi. In all the time that we have used this setup, this has never been a problem. If you are concerned about this, be sure to add a fuse.
  ![Raspberry Pi GPIO Pinout Diagram](https://github.com/ksasaHQ/Prusa-Enclosure-Raspberry-Pi/raw/master/images/GPIO-Pinout-Diagram.jpg "Raspberry Pi GPIO Pinout Diagram")
  By the [Raspberry Pi Foundation](https://www.raspberrypi.org/documentation/usage/gpio/)
