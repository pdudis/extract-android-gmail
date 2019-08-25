Extract, parse, and decompress data from an Android Gmail database.

This is a standalone script.

Changelog 20190127 [changes by [Petro Dudi](https://github.com/pdudis)]:

- Adapted for Python 3.x
- Added bad_chars_sub() to replace subject fields containing "/" and "\\" with "-", and return a string of 50 chars max
- Added unicode support when writing decompressed body field to file
- Prints account names and number of processed emails to standard output

## Like what you see?

If you find my modifications interesting then why not buy me a coffee?

[![BuyMeACoffee](https://user-images.githubusercontent.com/4114200/63639089-672f6a00-c698-11e9-9fac-3b6fcac47901.png)](https://www.buymeacoffee.com/ADYsLjqfi)
