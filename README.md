# ZedBoard Petalinux Repository

This repository contains all Petalinux projects that target the ZedBoard.

For more information about the ZedBoard, visit its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/ZedBoard/start) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki, links in the table below.

| Wiki Link | Description |
|-----------|-------------|
| [ZedBoard Pmod DA1]() | Demonstrates the usage of the PmodDA1 module in linux together with a ZedBoard. |
| [ZedBoard Pmod OLEDrgb]() | Demonstrates the usage of the PmodOLEDrgb module in linux together with a ZedBoard. |

## Repository Description

This repository contains the Petalinux projects for each of the demos requireing them provided for the ZedBoard. As each of these demos also requires a hardware design, and potentially software sources, this repository should not be used directly. The [ZedBoard](https://github.com/Digilent/ZedBoard) repository contains all sources for these demos across all tools, and pulls in all of this repository's sources by using it as a submodule.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:

## (Additional Section?)