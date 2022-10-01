<a href="https://mufpga.github.io/"><img src="https://raw.githubusercontent.com/mufpga/mufpga.github.io/main/img/logo_title.png" alt="Overview"/>

</a>

![version](https://img.shields.io/badge/version-3.1.0-blue)[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)



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
- [AOTF-CB board](AOTF_conversion_board)


## Cite us
Joran Deschamps, Christian Kieser, Philipp Hoess, Takahiro Deguchi and Jonas Ries, "MicroFPGA: an affordable FPGA platform for microscope control", bioRxiv 2022.06.07.495178.

The electronics was developed by Christian Kieser, EMBL (2020).
