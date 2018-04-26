# IFFL systemCadaver (Lasse Öörni)'s Integrated File Flexible Loader for Commodore 1541/1541-II drives.Originally published on Covert Bitops' [C64 page](https://cadaver.github.io/rants/iffl.html).## Notes- Assemble with dasm. Version 2.12.04 from Covert Bitops' [Tools page](https://cadaver.github.io/tools.html) has been tested.- Use the extended version of the ByteBoozer2 cruncher from [here](https://github.com/luigidifraia/ByteBoozer2).- Windows users might want to run win32/ifflvar.bat to setup their build environment.## Extensions contributed by Luigi Di Fraia- Added 1-bit transfer support for using sprites and interrupts while loading.- Added optional buffer-less block receive support (RECEIVE_BUFFER = 0 saves 254 bytes on the C=64, with some sped trade-off).- Added support for ByteBoozer 2.0 (which does not require a depack buffer on the C=64), Pucrunch and Exomizer files.## To do- Add support for 1571/1581, FD2000/4000, IDE64, and SD2IEC