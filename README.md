# mnaranjo msys2/mingw repository

# Usage

    $ wget https://raw.githubusercontent.com/manuelnaranjo/mnaranjo-msys-repository/master/mirrorlist.mnaranjo-msys -O /etc/pacman.d/mirrorlist.mnaranjo-msys
    $ vim /etc/pacman.conf
    # add the following section
    # [mnaranjo-msys]
    # Include = /etc/pacman.d/mirrorlist.mnaranjo-msys

    $ pacman -Syy

Now you can install packages from my repo
