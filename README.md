# jeeves
Simple AUR package tester [developers]

jeeves allows you to quickly test the package that you have just uploaded to AUR.
PLEASE NOTE that this is a simple script to see if any package
that you have just uploaded to AUR installs correctly.
BEFORE INSTALLING any package you have to be sure that you have
all his required dependencies.

    :: --> jeeves-0.2

usage: jeeves [arg] PACKAGE [opt]

examples:

 - jeeves -S foo [download and install your foo from AUR]
 - jeeves -S foo -nv [download and install your foo from AUR with low verbosity]
 - jeeves -s foo [search for foo in AUR]
 - jeeves -R foo [remove foo]
 - jeeves -Rsn foo [remove foo and all its dependencies]
 - jeeves -u . 'Some commit message' [upload current dir to origin (AUR) with commit message]

PLEASE NOTE that this is a simple script to see if the package
that you have just uploaded to AUR installs correctly.
BEFORE INSTALLING a package you have to be sure that you have
all his required dependencies.

THIS IS NOT A REPLACEMENT OF PACMAN OR PACAUR (OR SIMILARS)
