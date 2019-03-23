# Ctrl+L functionality in Xv6 Operating System.

Xv6 is a teaching Operating System developed in the summer of 2006 for MIT's Operating Systems Course, 6.828: Operating System Engineering. As a part of the Operating Systems Course in PES University we were asked to mimic various Kernel functionalities  of Ubuntu Linux OS in Xv6.

More about Xv6 - https://pdos.csail.mit.edu/6.828/2012/xv6.html

Link to Xv6 Repo - https://github.com/mit-pdos/xv6-public

This Repo contains an Xv6 equivalent implementation of the Ctrl+L functionality present in Linux (Ubuntu). I directly edited the ***consoleintr*** function found in ***console.c*** file from the Xv6 repository. Here you need to add a new case to handle the Ctrl+L interrupt.There are already default implementations for other interrupts.

Navigate to the consoleintr function in the console.c file to understand the implementation. Then replace the console.c file in Xv6 directory with the console.c file in this repo & run xv6 to check if the ctrl+L interrupt is working as intended.
 
