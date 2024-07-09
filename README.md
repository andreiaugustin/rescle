This project is modified from Rescle written by yoshio.okumura@gmail.com: http://code.google.com/p/rescle/

# rescle
Command line resource editor for Windows PE format file. 

Rescle(RESource Command Line Editor) is not a resource compiler, but poweful tool for Windows application developers.

### Purpose
customize resource without build
i.e. for multi-distribution products

### Features
You can edit resouces at x86/x64 PE files (EXE/DLL/OCX..). * Version Information * String Table * Manifest * Icon * Bitmap * Cursor * Any Binary

### Limitations
works on windows only
command line interface
but you can do it to edit update.py
cannot change binary same resource id but language is different
digital signed PE files is not supported
