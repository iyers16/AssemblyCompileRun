#!/bin/bash

asmfile="$1.asm"
lisfile="$1.lis"
ofile="$1.o"

nasm -f elf $asmfile -l $lisfile
ld -melf_i386 -o $1 $ofile
gdb $1
