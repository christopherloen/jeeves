# jeeves
Simple AUR package tester [developers]

jeeves allows you to quickly install or upload packages from AUR.

:: --> jeeves-0.3.1

usage: jeeves [arg] PACKAGE [opt]

examples:

 - jeeves -S foo [download and install your foo from AUR]
 - jeeves -S foo -nv [download and install your foo from AUR with low verbosity]
 - jeeves -s foo [search for foo in AUR]
 - jeeves -u 'Some message' [upload current dir to origin (AUR) with commit message]

BEFORE INSTALLING a package you have to be sure that you have
all his required dependencies. makepkg is run with option -d,
so you won't see if you are missing some deps.

THIS IS NOT A REPLACEMENT OF PACMAN OR PACAUR (OR SIMILARS)
