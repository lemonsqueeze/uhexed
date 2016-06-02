uhexed
======

Simple terminal multi-byte hex editor / hexdump.

Usage: uhexed [-e encoding] binary_file

Type 'h' for key help

Encoding can be pretty much any encoding that perl supports.
For BOM-type encodings you must specify byte order explicitly (so utf-16le or utf-16be for utf-16).

Tested so far:
- ascii
- cp932 - Windows codepage 932 - Japanese Shift JIS
- utf-16le/utf-16be
- utf-8
- iso-8859-1

![Screenshot](https://raw.githubusercontent.com/lemonsqueeze/uhexed/master/screenshot.png)

Bugs
----

Probably many. 

Make sure your term is big enough or it'll look like garbage.
