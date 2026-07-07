## Tiny Pascal compiler
Initial relase contains .bas files and .prg files (the native files for c64) of a Tiny Pascal compiler written in basic. Project was originated in 1978 by Kin-Man Chung and Herbert Yuen for the TRS-80. This port was created by Bill Fahle in 1985 from the book "The Byte Book of Pascal", and reprised in July 2026. This initial release just creates bytecodes in memory, but has no mechanism for interpreting them or executing them.

The samplem.bas file is a basic file that can write a .seq file (sequential binary file) to disk which can then be read by the compiler.
# Future work
A runtime written in assembly for the 6510/c64

A translator to convert p-code to 6510 machine code
