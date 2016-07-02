# jeeves
Simple AUR package tester [developers]

jeeves allows you to quickly test the package that you have just uploaded to AUR.
PLEASE NOTE that this is a simple script to see if any package
that you have just uploaded to AUR installs correctly.
BEFORE INSTALLING any package you have to be sure that you have
all his required dependencies.

usage: jeeves [arg] PACKAGE

examples:

   - jeeves -S foo [download and install your foo from AUR]
   - jeeves -s foo [search for foo in AUR]
   - jeeves -R foo [remove foo]
   - jeeves -Rsn foo [remove foo and all its dependencies]
