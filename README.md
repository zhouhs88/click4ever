# Click4Ever

A tool that simulates multiple mouse clicks quickly in succession for Linux.


## Usage

You start by running the following command:

	$ click4ever

Now the program is waiting for you to make the first click. Once you click
somewhere, it will start dispatching mouse clicks at that coordinate until you
move the mouse away.

I like to assign a hotkey (ex: CTRL+C) that automatically runs the command for
me, then I just need to click somewhere.


## Installation

**Note**: If you have a clean state of the source repository you will need to
prepare the build tools before you can start the installation process by
running the following command:

	$ autoreconf -i

A normal installation requires running these 3 commands:

	$ ./configure

	$ make

	$ make install

The first one will check if your system has the needed functionalities
available for the program to work and set up a suitable build system. The
second one will compile the program. The third and last one will install the
program on your system.

If it fails to build on your system feel free to report as a bug. Read the
Contributing section for how to do it.

To change how the program is compiled and installed, see the options you have
available for the first command by running `./configure -h`.


## Contributing

Found a bug or want to contribute code? Feel free to create an issue or send a
pull request on GitHub [[1]].


## License

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

[1]: https://github.com/daniel-araujo/click4ever
