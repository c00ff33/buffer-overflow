// helloworld.asm

helloworld.asm

This is an assembly helloworld program running on Windows 32 bit OS.

Test platform: Microsoft Windows Server 2003 R2 Base (Windows, Windows 2003 R2 5.2 | 32-bit (x86) Amazon Machine Image (AMI) | Updated: 1/23/19)

Installed software:
MASM32 SDK Version 11 Downloads
http://www.masm32.com/download.htm

Post config:
Add path "C:\masm32\bin" to Environment Variables's System Variables' "Path"

Compile the program and link it
C:\OSCP>ml /c /coff helloworld.asm
Microsoft (R) Macro Assembler Version 6.14.8444
Copyright (C) Microsoft Corp 1981-1997.  All rights reserved.

 Assembling: helloworld.asm

C:\OSCP>link /subsystem:windows /defaultlib:C:\masm32\lib\kernel32.lib /defaultl
ib:C:\masm32\lib\user32.lib helloworld.obj
Microsoft (R) Incremental Linker Version 5.12.8078
Copyright (C) Microsoft Corp 1992-1998. All rights reserved.


C:\OSCP>ml /c /coff helloworld.asm
Microsoft (R) Macro Assembler Version 6.14.8444
Copyright (C) Microsoft Corp 1981-1997.  All rights reserved.

 Assembling: helloworld.asm

C:\OSCP>link /subsystem:windows /defaultlib:C:\masm32\lib\kernel32.lib /defaultl
ib:C:\masm32\lib\user32.lib helloworld.obj
Microsoft (R) Incremental Linker Version 5.12.8078
Copyright (C) Microsoft Corp 1992-1998. All rights reserved.
