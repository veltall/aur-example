# ttf-monda

<p><img src="./res/preview.png" alt="Monda preview" width="650px" /></p>

### Manual Installation
Download/extract the tarball 

    $ tar zxvf ttf-monda.tar.gz

or clone the repo to your local machine

    $ git clone https://github.com/veltall/ttf-monda.git

allow the files to be read by users

    $ chmod 0555 ./fonts
    $ chmod 0444 .fonts/*.ttf

copy the `.ttf` files to your font folder(s), consult [the wiki](https://wiki.archlinux.org/index.php/fonts#Manual_installation) for more details

    $ cd fonts
    # cp *.ttf /usr/share/fonts/TTF
    $ cp ~/.local/share/fonts

Then update the fontconfig font cache

    $ fc-cache
