# RISC OS SystemVars module in C

## Summary

This is a module for RISC OS which provides an implementation of the `OS_ReadVarVal` and `OS_SetVarVal` RISC OS
SWI calls. The implementation is pretty simple, and provides both OS_* SWI implementations and a non-OS implementation.

The repository is intended for use on RISC OS 32bit and 64bit systems.

## Functionality

The code here supports building for 32bit and 64bit environments, allowing it to be used on RISC OS Classic, RISC OS Pyromaniac and RISC OS Pyromaniac running in AArch64 ('RISC OS 64').

The implementation supports:

* String variable
* Number variables
* Macro variables
* Setting variables literally and with GSTrans.
* Creating, Reading, Updating and Deleting variables.

## Development

The development of this module is documented through a live coding series on YouTube. The full playlist of all the live sessions can be found here: https://www.youtube.com/watch?v=qLWrBmpvj5s&list=PLVVIu906Y7rErDqQiC48sWdsrD-AeQ8wS


## License

The code is released under the [3-clause BSD license](LICENCE).
