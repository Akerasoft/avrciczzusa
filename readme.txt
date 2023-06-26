avrciczz.asm - source code
avrciczz.elf - binary + fuse bits settings
avrciczz.hex - binary only.

SUT_CKSEL fuse should be set to "ext clock + 0ms" in case if avrciczz.hex was used, avrciczz.elf already contains this setting
This was changed to USA/Canada only.  So reset might need to be just one time.  Changing region won't work.  Old instructions were reset one 4 to 8 times.
Chip pinout inside of avrciczz.asm file


