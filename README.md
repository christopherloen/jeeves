# jeeves
jeeves is a simple script that automates the main processes of package creation for Arch Linux User Repository.
These are, for example, the cloning of a new empty directory, the uploading of a directory to AUR
and the testing of a package (downloading and installing).

# Usage
:: --> jeeves-0.3.1

usage: jeeves [arg] PACKAGE [opt]

examples:

 - jeeves -S foo [download and install your foo from AUR]
 - jeeves -S foo -nv [download and install your foo from AUR with low verbosity]
 - jeeves -s foo [search for foo in AUR]
 - jeeves -u 'Some message' [upload current dir to origin (AUR) with commit message]
 - jeeves -c 'some-package' [clone 'some-package' dir from AUR]

BEFORE INSTALLING a package you have to be sure that you have
all his required dependencies. makepkg is run with option -d,
so you won't see if you are missing some deps.

THIS IS NOT A REPLACEMENT OF PACMAN OR PACAUR (OR SIMILARS)

# Installation
Before installing, make sure you are an AUR user ready to maintain packages,
otherwise jeeves can't work.

Installing from github:

git clone https://github.com/christopherloen/jeeves.git

cd jeeves

chmod +x jeeves

cp jeeves /usr/bin/jeeves      (this as root)

Otherwise you can install jeeves directly from AUR using your favourite AUR helper
