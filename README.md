Extract, parse, and decompress data from an Android Gmail database.

This is a standalone script.

Changelog 20190127 [changes by [Petro Dudi](https://github.com/pdudis)]:

- Adapted for Python 3.x
- Added bad_chars_sub() to replace subject fields containing "/" and "\\" with "-", and return a string of 50 chars max
- Added unicode support when writing decompressed body field to file
- Prints account names and number of processed emails to standard output
