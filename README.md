# AUR Packaging Example : ttf-monda

Inside the folder `ttf-monda` is the files necessary for "installing" the font to the system. These files are to be hosted externally in a tarball.

![](./res/monda-git.png)

An example is to host the "source files" on github and have the Github system generate a tarball when you **release** a tagged version.

Add this tarball URL to the `PKGBUILD` when modifying/updating other information.

Add a checksum to the PKGBUILD

    $ makepkg -g >> PKGBUILD

Voila.
