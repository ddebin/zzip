# Zzip

(original home page at [debin.net/zzip](http://debin.net/zzip/))

A compression tool based on the Burrows-Wheeler Transform method.

Zzip compression algorithm is mainly based on the Burrows-Wheeler Transform method developped by Mike Burrows and David Wheeler.

Here are the different steps:

- RLE packing if necessary
- some transformations for text, multimedia and win32 binary files (eol coding, delta-encoding,...)
- Burrows-Wheeler Transformation, it's a suffix sorting (Bentley-Sedgewick ternary sorting with initial bucket sorting)
- MTF like transformation
- arithmetic coding (two groups, ternary sequence & structured model)

Here is a list of its features:

- great compression ratio and good decompression speed
- build/extract/test/list archive files
- built-in multimedia detection/compression
- number of files in one operation is only limited by available memory
- support for file attributes and file date/time stamps
- support for file integrity tests (CRC-32 checksums)
- support for win95 long filenames
- self-extracting archive (.exe file)

Current release of Zzip / Zzlib is 0.36c, **04-Jun-2001** (so pretty old stuff !).
