About this
==========

abixcode allow building AbiWord using XCode, for development purpose.
abixcode is NOT the official build system nor the one used to make
the binaries.

abixcode require "brew: to work.
abixcode is for XCode 5.1.1 to build against MacOS 10.8 SDK.
abixcode may not work on your system however care has been made to try
to make it work. Tweaking is allowed.

Setup
-----

Checkout abiword as a peer to abixcode.

Build AbiWord.app from XCode. The Debug target is actually the only one.


Adding files to the project
---------------------------

Source files must use UTF-8 encoding, and be referenced using a relative
path.
Objective-C++ file with a .cpp extension must have a type of
"sourcecode.cpp.objcpp" set in XCode, or they won't build.
Frameworks and libraries must have an absolute path. If they are not part
of the system standard distro, install them with brew.


-- Hub
