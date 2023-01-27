# K410T devboard

Copyright (c) 2022 [Antmicro](https://www.antmicro.com)

![K410T devboard](/img/K410T-devboard.png)

### Overview

This repository contains open hardware design files for a devkit created for AMD-Xilinx [Kintex-7 K410T](https://www.xilinx.com/products/silicon-devices/fpga/kintex-7.html) FPGA.

This development board routes the I/O interfaces from the SoM and provides the necessary power buses.
The design files were prepared in KiCad 6.

## Repository structure

The main repository directory contains KiCad PCB project files, a [LICENSE](LICENSE), and a README.
The remaining files are stored in the following directories:

* `lib` - contains the KiCad 6 component libraries
* `doc` - contains generated schematics and other documentation
* `img` - contains graphics for this README

## Key features

* AMD-Xilinx Kintex-7 K410T FPGA
* 512MB of DDR3L memory
* 256MB of SPI NOR flash
* 8MB of SRAM memory
* mounting option for 2x QSPI
* Gigabit Ethernet
* HDMI output
* USB Type-C connector for FTDI JTAG and debug
* 2x PMOD
* FMC+ connector


## Licensing

This project is published under the [Apache-2.0](LICENSE) License.
