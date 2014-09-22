FreeDOS-BIOS-Updater
====================

A script that will quickly and easily add DOS-based BIOS update executables to a FreeDOS CD/DVD image suitable for burning.

You will need a FreeDOS bootable CD image. Download one at: http://freedos.org/

1- Place your update .exe files in the bios/

2- Run ./update [freedos image file name]

3- Burn the resulting .iso file to CD/DVD

4- Boot, select "1- Boot FreeDOS CD"

5- Select "1. Install to harddisk using FreeDOS SETUP (default)"

6- Select your language

7- Select "Run FreeDOS from CD-ROM (return to command prompt)"

8- Type "cd bios" and hit enter

9- Run the BIOS update executable for your hardware
