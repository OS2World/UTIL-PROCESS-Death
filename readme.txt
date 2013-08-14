Death (originally by Holger Veit)

This is a small applet that does a hard-kill on processes.
It requires XF86SUP.SYS driver by Holger Veit.
Read the original readmes (README1.ORG and README2.ORG) for more information.

I enhanced this applet to accept also PIDs in hexadecimal notation like in C.
Examples: death 0x5f
          death 95
          These calls kill all the same process.

The DEATH.EXE in this package needs EMX runtime library to run.
But you can compile your own version with your favourite C compiler. :-)

Daniel KrÅger
daniel.krueger@web.de

Thanks to Holger Veit for his great work with XFree86.

