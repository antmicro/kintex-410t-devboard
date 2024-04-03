# Kintex K410T Devboard

Copyright (c) 2022-2023 [Antmicro](https://www.antmicro.com)

[![View on opensource.antmicro.com](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Source%20Portal-332d37?style=flat-square)](https://opensource.antmicro.com/projects/kintex-410t-devboard)

![K410T devboard](/img/k410t-devboard.png)

## Overview

This repository contains open hardware design files for a devkit created for AMD-Xilinx [Kintex-7 K410T](https://www.xilinx.com/products/silicon-devices/fpga/kintex-7.html) FPGA.

This development board routes the I/O interfaces from the SoM and provides the necessary power buses.
The design files were prepared in KiCad 7.

## Repository structure

The main repository directory contains KiCad PCB project files, a [LICENSE](LICENSE), and a README.
The remaining files are stored in the following directories:

* `doc` - contains generated schematics and other documentation
* `img` - contains graphics for this README
* `assets` - contains visual assets for showcasing the board on Antmicro [Open Hardware Portal](https://openhardware.antmicro.com)

## Key features

* AMD-Xilinx Kintex-7 K410T FPGA
* 512MB of DDR3L memory
* 256MB of SPI NOR flash
* 8MB of SRAM memory
* Assembly option for 2x QSPI
* Gigabit Ethernet
* HDMI output
* USB Type-C connector for FTDI JTAG and debug
* 2x PMOD
* FMC+ connector

## Block diagram

![K410T devboard block diagram](/doc/kintex-410t-devboard-block-diagram.png)

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
