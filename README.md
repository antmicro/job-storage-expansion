# Jetson Orin Baseboard Storage Expansion Board

Copyright (c) 2022-2023 [Antmicro](https://www.antmicro.com)

[![image](https://img.shields.io/badge/View%20on-Antmicro%20Open%20Source%20Portal-332d37?style=flat-square)](https://opensource.antmicro.com/projects/)

![](img/storage-expansion-board.png)

## Overview

This project contains open hardware design files for a storage expansion board. The board is designed for baseboard supporting NVIDIA Jetson Orin Nano and Jetson Orin NX System on Modules (SoMs). It uses baseboard's expansion connector, and clips onto the board. For more secure connection user can use screws to attach expansion board to the orin baseboard. If user decides to only use the 2242 size, it is possible to break out the 2280 mounting parts, and enjoy smaller footprint.

The board allows the user to connect M.2 NVMe discs wit the M key. 
Supported sizes: 2280 and 2242

Additionally, it features MicroSD card slot, with USB 2.0 controller.

The design files were prepared in KiCad 6.x.

## Key features

* M.2 key M
* MicroSD card reader with USB 2.0 interface


## Licensing

This project is published under the [Apache-2.0](LICENSE) license.

