# The MAGEEC WAND Energy Measurement Kit

![The assembled WAND kit](/images/Completed.jpg)

The WAND is capable of measuring energy consumption at 3 independent points and with simultaneous measurement of targets at 2,000,000 samples/second. 

The platform is comprised of an ARM Cortex M4-based STM32F4DISCOVERY board plus a custom shield, which is connected via USB to a host computer.

The shield, STM32F4DISCOVERY firmware, and a Python framework and applications, were developed as part of the [MAGEEC project](http://mageec.org/).

Hardware has been made available to members of the MAGEEC project, other research groups and as part of a [workshop at FOSDEM 2014](https://archive.fosdem.org/2014/schedule/event/mageec/).

[Embecosm](http://www.embecosm.com/) have funded the production of a final batch of kits which are [being made generally available](http://www.embecosm.com/2014/08/29/opportunity-to-obtain-mageec-energy-measurement-hardware-2/). 

## Repository contents

The case design is provided in the following formats:

* SVG (Inkscape source)
* DXF 

The top and bottom panels are laser cut from 3mm clear acrylic.

Note:

* The energy measurement shield was designed by Simon Hollis of University of Bristol, and the KiCAD and manufacturing files can be found in the [MAGEEC hardware repo](https://github.com/mageec/powersense-shield).
* The STM32F4DISCOVERY firmware and Python framework was developed by James Pallister of Embecosm/University of Bristol, and can be found in the [stm32f4-energy-monitor repo](https://github.com/jpallister/stm32f4-energy-monitor).

## Bill of materials

The WAND-01 kit contains:

| Qty | Item                                |
| --- | ----------------------------------- |
|  1  | Acrylic top panel                   |
|  1  | Acrylic bottom panel                |
|  1  | STM32F4DISCOVERY board              |
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

1. Remove the protective film from the acrylic panels.

2. Affix the rubber bumpers to the bottom panel.

3. Secure the STM32F4DISCOVERY PCB assembly in place using the edge holding spacers and self-tapping screws.

4. Affix the hex spacers to the bottom panel with 4x nylon screws.

5. Secure the top acrylic panel with the 4x remaining nylon screws.

## Usage

For details of how to load firmware onto the STM32F4DISCOVERY, connect up targets and run the energy measurement software, please see the [MAGEEC wiki](http://mageec.org/wiki/Workshop).

## Licence

MAGEEC WAND Kit mechanical design by Chelsea Back, copyright 2015 [AB Open Ltd](http://abopen.com).

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
