# Pasta_Loader_MSET_4.X
MSET entrypoint for the ARM9 loader.bin of PASTA CFW


Thi is a mod of <a href="https://github.com/nop90/FirmLaunch_MSET_4.X">FirmLaunch for MSET</a> that , instead of running an included arm9 payload before performing the firm reboot, load it form the 3DS SD.

It's intended for loading the PASTA CFW loader.bin in ther \3ds\PastaCFW folder, but renaming the path and filename in the source can load any arm9 payload created for Brahma.

It works with the ar9_code.bin payload from the Firmlaunch for MSET build, but hangs with the PastaCFW payload.

I'm investigating the reason. Let me know if you have an hint.

NOP90
