# The MAGEEC WAND Energy Measurement Kit

![The assembled WAND kit](/images/Completed.jpg)

The WAND is capable of measuring energy consumption at 3 independent points and with simultaneous measurement of targets at 2,000,000 samples/second. 

The platform is comprised of an ARM Cortex M4-based STM32F4DISCOVERY board plus a custom shield, which is connected via USB to a host computer.

The shield, STM32F4DISCOVERY firmware, and a Python framework and applications, were developed as part of the [MAGEEC project](http://mageec.org/).

## Repository contents

The case design is provided in the following formats:

* SVG (Inkscape source)
* PDF

The top and bottom panels are laser cut from 3mm clear acrylic.

The energy measurement shield design files can be found in the [GitHub repo](https://github.com/mageec/powersense-shield).

## Bill of materials

The WAND-01 kit contains:

| Qty | Item                                |
| --- | ----------------------------------- |
|  1  | Acrylic top panel                   |
|  1  | Acrylic bottom panel                |
|  1  | STM32F4DIUSCOVERY board             |
|  1  | Energy measurement shield           |
|  6  | 0.1" pin jumper                     |
|  1  | USB A Male to Micro B Male cable    |
|  1  | USB A Male to Mini B Male cable     |
|  1  | Female-Female jumper wire           |
|  4  | Clear 10mm diameter rubber bumper   |
|  4  | Universal edge holding PCB spacer   |
|  4  | M3 x 30mm F-F hex nylon spacer      |
|  8  | M3 x 12mm nylon screw               |
|  4  | 6 x 3/8" self-tapping screw pan pozi|

## Assembly

1. Remove the protective  from the acrylic panels.

2. Affix the rubber bumpers to the bottom panel.

3. Secure the STM32F4DISCOVERY PCB assembly in place using the edge holding spacers and self-tapping screws.

4. Affix the hex spacers to the bottom panel with 4x nylon screws.

5. Secure the top acrylic panel with the 4x remaining nylon screws.

## Usage

For details of how to load firmware onto the STM32F4DISCOVERY, connect up targets and run the energy measurement software, please see the [MAGEEC wiki](
 

## Licence

MAGEEC WAND Kit design by Chelsea Back, copyright 2015 [AB Open Ltd](http://abopen.com).

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
