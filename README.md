# Dandelion

A theme for the Plymouth graphical boot system for linux.

[![Dandelion screenshot](screenshot.png)](http://brej.org/blog/wp-content/uploads/2009/12/dandelion.ogg)


# Installation

To install without a package manager, copy the dandelion subdirectory
into your system's /usr/share/plymouth/themes directory, and then run
these commands:

    sudo update-alternatives --install \
      /usr/share/plymouth/themes/default.plymouth default.plymouth \
      /usr/share/plymouth/themes/dandelion/dandelion.plymouth 100
    sudo update-alternatives --config default.plymouth
    sudo update-initramfs -u


# License

Copyright 2009-2019 Charles Brej and contributors

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.


# History

This theme was created by [Charlie Brej](mailto:plymouth@brej.org) as
a test example for his Plymouth script interpreter, and
[published](http://brej.org/blog/wp-content/uploads/2009/12/dandelion.tar.gz)
in a [2009 blog post](http://brej.org/blog/?p=238).

In 2019, [Forest](https://github.com/foresto) obtained permission from Charlie
to modify and publish the theme with a GPL or BSD license.  The GPL was chosen.
A source code repository was created here:

https://github.com/foresto/plymouth-dandelion
