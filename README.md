PYNQ SD Build Examples
======================

This repository contains a number of examples of PYNQ board specifications
based on a set of work flows all built on the ZC706 board.

To build all examples check out the PYNQ repo on the sdbuild\_refactor branch,
ensure that the system is setup correctly by using the `setup_host.sh` and run
`make BOARDDIR=$(sdbuild_examples)`. To build only a specific example run `make
BOARDDIR=$(sdbuild_examples) BOARDS=$(board)`

For more details for each example see the corresponding subdirectory.

Petalinux BSP Only (ZC706\_BSP)
-------------------------------

This example contains just the pre-existing BSP (with pre-builts stripped to
save space) and a spec file to describe the platform.

Petalinux BSP from HDF (ZC706\_HDF)
-----------------------------------

This example contains a BSP created from an HDF file in turn created from a
board preset. Instructions for generating the BSP are included in the
sub-folder.

BSP+Bitstream (ZC706\_Bitstream)
--------------------------------

BSP+Notebooks (ZC706\_Notebook)
-------------------------------

BSP+Python (ZC706\_Python)
--------------------------

