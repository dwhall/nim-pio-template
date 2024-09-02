nim-pio-template
================

A project to serve as a template for a nim project using
PlatformIO to build for a microcontroller.


History
-------

Steps:

0) create subdir, enter subdir, save VsCode workspace
1) git init, add README.txt
2) add `.vscode/extensions.json` to recommend PlatformIO extension to VSCode
3) add `lib_deps = https://github.com/dwhall/nim-platformio#v0.3.3` to
   `platformio.ini` to have this project depend on nim-platformio to build Nim source code
