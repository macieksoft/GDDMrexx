# GDDMrexx
Various GDDM-REXX and GDDM-PGF programs for 3270 terminal graphics.
Software distributed as REXX execs in ASCII format, you may upload them using IND$FILE function of you'r terminal emulator.

Notes:

-Terminal emulator needs to have support for host graphics feature with vector graphics. Many terminal emulators (like free X3270) don't have that feature.
-Requires GDDM-REXX and some of the execs also require GDDM-PGF.
-Coded to work on MVS series systems (like Z/Os or Os/390). It is possible to make it work under VM by replacing ADDRESS LINK with ADDRESS COMMAND.
