<a href="https://mufpga.github.io/"><img src="https://raw.githubusercontent.com/mufpga/mufpga.github.io/main/img/logo_title.png" alt="Overview"/>

</a>

![version](https://img.shields.io/badge/version-3.1.1-blue)[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)[![DOI](https://zenodo.org/badge/410023495.svg)](https://zenodo.org/badge/latestdoi/410023495)



# Overview

MicroFPGA is an FPGA-based platform for the electronic control of microscopes. It aims at using affordable FPGA to generate or read signals from a variety of devices, including cameras, lasers, servomotors, filter-wheels, etc. It can be controlled via [Micro-Manager](https://micro-manager.org/MicroFPGA), or its [Java](https://github.com/mufpga/MicroFPGA-java), [Python](https://github.com/mufpga/MicroFPGA-py) and [LabView](https://github.com/mufpga/MicroFPGA-labview) communication libraries, and comes with optional complementary [electronics](https://github.com/mufpga/MicroFPGA-electronics).

Documentation and tutorials are available on [https://mufpga.github.io/](https://mufpga.github.io/).



<img src="https://raw.githubusercontent.com/mufpga/mufpga.github.io/main/img/figs/G_overview.png" alt="Overview"/>

## Content

This repository contains the (optional) complementary electronics for MicroFPGA. Documentation for the electronics is available on the [project's website](https://mufpga.github.io/resource1_electronics.html) and in the papers.

Design files are available for the following elements:
- [Box](Box)
- [Box panel 1](Box_panel_1)
- [Box panel 2](Box_panel_2)
- [Box panel 3](Box_panel_3)
- [Analog conversion board (ACB)](Analog_conversion_board)
- [Signal conversion board (SCB)](Signal_conversion_board)
- [Custom FPGA shield](FPGA_shield)
- [Servo distribution board (SDB)](Servo_distribution_board)
- [AOTF conversion board (AOTF-CB)](AOTF_conversion_board)


## Cite us
Joran Deschamps, Christian Kieser, Philipp Hoess, Takahiro Deguchi, Jonas Ries, "MicroFPGA: An affordable FPGA platform for microscope control",
HardwareX 2023 (13): e00407, doi:[10.1016/j.ohx.2023.e00407](https://doi.org/10.1016/j.ohx.2023.e00407).
