# lwtools
LW Tool Chain for building binaries for MC6809/HD6309 CPUs, with some fixes.

By Robert Belleman, University of Amsterdam.

## Changes
This version is different from the original (lwtools-4.23) as follows:
- The "padsize" directive in linking scripts for lwlink did not do anything for the output. This version adds that functionality for "raw" output files.
- There was a bug in the parsing of the "stacksize" directive in linking scripts; this version fixes that.
