NXLIB
=====

NXLIB (Not eXactly LIBraries) is a collection of libraries for the LEGO NXT brick.
The libraries are written in NXC programming language.
In addition to the libraries there are also some example programs that may be useful to understand how to use a particular library and may be used as a starting point for some other program.

Contents:
---------

 - **/UI** UI libraries
   - **/menu.nxc** Menu UI library
   - **/edit_number.nxc** Displays UI for editing number with arrow keys
 - **/examples** Example files
   - **/menu_test.nxc** Demonstration of menu UI
    
Usage:
------

To use one of the features offered by these libraries inside a program follow these simple steps:
 - Download the entire repository or the needed library;
 - Add this line on the top of your program: "#include path/to/lib/file.nxc" (without quotes and replacing the path with the relative path of the library program.
 - Compile and donwload the program to your brick.
 - Enjoy your program!

To use libraries and the example programs you must have the [Enhanced Firmware] (http://bricxcc.sourceforge.net/firmware.html) installed on your NXT brick.

**IMPORTANT:** When compiling with NBC from command line don't forget to add the -EF option (Enhanced Firmware).

License:
--------

Read **LICENSE**.

Documentation:
--------------

At the moment there isn't any documentation for the libraries (apart from this file).
To understand how a particular function works you can read the code and the comments in the source file.
If you would like to write some documentation for the libraries feel free to start a pull request.

To learn about the NXC language I recommend you read [this] (http://bricxcc.sourceforge.net/nbc/nxcdoc/NXC_tutorial.pdf) tutorial. For a complete reference take a look [here] (http://bricxcc.sourceforge.net/nbc/nxcdoc/nxcapi/).

Bugs:
-----

Found a bug?
Create an issue here on GitHub describing well the problem and adding some additonal info as the compiler you are using or your OS.

Contributing:
-------------

Want to contribute?
Open a pull request. Every contribution must be licensed under the terms of the GNU General Public License v2.
