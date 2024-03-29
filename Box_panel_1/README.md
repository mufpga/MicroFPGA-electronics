<a href="https://mufpga.github.io/"><img src="https://raw.githubusercontent.com/mufpga/mufpga.github.io/main/img/logo_title.png" alt="Overview"/>

</a>

![version](https://img.shields.io/badge/version-3.1.1-blue)[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)[![DOI](https://zenodo.org/badge/410023495.svg)](https://zenodo.org/badge/latestdoi/410023495)


## Content

The first box panel is connected to the laser (DO:LX:EN) and PWM signals (DO:LX:POW), as well as camera trigger input and the servos. The lasers outputs can be used directly to trigger diode lasers. The servo DSUB9 is connected to the [servo distribution board (SDB)](https://github.com/mufpga/MicroFPGA-electronics/tree/main/Servo_distribution_board). The other DSUB9 connector can be used with the [LaserEngine](https://github.com/ries-lab/LaserEngine) electronics. Finally, both laser and PWM signals could be used as inputs to the [AOTF conversion board (AOTF-CB)](https://github.com/mufpga/MicroFPGA-electronics/tree/main/AOTF_conversion_board) in order to control an AOTF or an AOM.

- [Altium project](Altium_project)
- [Bill of materials](BOM)
- [Gerber files](Gerber)
- [Drill instructions](NC_Drill)

![Box panel 1](Box_panel_1_soldered.jpg)

Photography credit: EMBL Photolab - Stuart Ingham.
