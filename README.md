# Prefetch
Windows Prefetch parser. Supports all known versions from Windows XP to Windows 10.

I still have to clean up some code, refactor a bit, and add properties for things like trace chains and file metrics collections, but everything else is functional.

Many more unit tests will also be added soon

#NOTE
You need to run this code on at least Windows 8 in order for the decompression of Windows 10 prefetch files to work. I still have to some testing on failing gracefully if run on < Windows 8 if Windows 10 prefetch (version 30) files are found.

# TODO
- Split out Win8x into Win80 and Win81 for test cases