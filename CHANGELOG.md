* **0.36c** (04-Jun-01)
  + bug fixes
  + unix version doesn't work any more, it will be delayed until I can get access to a unix machine
* **0.36b** (18-Dec-00)
  + source code is released under the GNU LGPL !
  + a new option '-s' to get stats about the (de)compression (only available for x86 cpus)
  + bug fixes (unix version works !)
* **0.36a** (30-Nov-00)
  + zzip-sfx, a new utility (only available for Win9x/NT/2000) for building self-extracting archives from zzip archives
  + a new adaptive block size reduction algorithm (switch -a)
  + bug fixes
  + a new web site ;) http://www.zzip.f2s.com/
* **0.35g** (10-Oct-00)
  + bug fixes
* **0.35f** (25-Sep-00)
  + compression and uncompression are somewhat faster (5% I think for regular processors)
  + a new filter for text files (phrase replacement) has been implemented
  + better detection of multimedia files
  + bug fixes
* **0.35e** (21-Aug-00)
  + compression is 5% faster, uncompression is 20% faster
  + the three algorithms have been merged into a single, please use now '-mx' to get the best compression ratio
  + memory footprint has been reduced, the new memory usage is :
    - 6 times block_size during compression
    - 5 times block_size during uncompression
  + the range of block size has been enlarged up to 20*256kb=4Mb (-b20)
  + a new switch (-mm) enables a new algorithm for image and wav files
* **0.35d** (06-Aug-00)
  + a lot of functions have been added to the dll to manipulate archives
  + you can specify now which files you want to extract
  + Linux and Solaris versions have been updated
* **0.35c** (27-Jul-00)
  + zzip has been turned into a dll, zzlib, so that you can use zzip as a command line software or as a library in your program
  + compression/uncompression is slightly faster
* **0.35b** (19-Jul-00)
  + the compression ratio has improved by about 1%, especially with Win32 exe and text files ; I can now compress the Calgary Corpus within 816,000 bytes and the Canterbury Corpus within 471,000 bytes
* **0.35a** (09-Jun-00)
  + a major release
  + some nice commands have been added : deleting files in an archive, adding files (recursively or not) to an existing/new archive, extracting files with full pathname, listing contents of archive, testing archives (command line options have changed !)
  + some bug fixes (as usual ;)
* **0.34f** (15-May-00)
  + some important bug fixes
  + the compression ratio improved by 1% thanks to Szymon Grabowski
* **0.34e** (27-Apr-00)
  + compression is about 5% faster
  + some bug fixes
* **0.34d** (14-Apr-00)
  + (un)compression is about 10% faster
  + the compression ratio improved slightly (0.5%)
  + some bugfixes
  + options -b256,-b512... have been replaced by -b1,-b2...
  + a new compression mode for multimedia files (-mm)
* **0.34c** (05-Apr-00)
  + uncompression is 10% faster
  + the algorithm selection is more efficient and faster
* **0.34b** (02-Apr-00)
  + Another speed improvement, Zzip **0.34b is 15% faster than **0.34a, but memory usage has increased, so that there is now a new option '-lowmem' which limits memory usage
* **0.34a** (27-Mar-00)
  + Zzip is now 15% faster
  + Zzip uses now 40% less memory, 7x block size instead of 10x
  + bugfixes concerning the archive feature and the i/o error handler
* **0.33b** (24-Mar-00)
  + some various bug fixes
  + speed improvements (about 5% faster)
* **0.33a** (17-Mar-00)
  + multiple-files-in-a-single-archive feature added
  + CRC32 control for each file of the archive
* **0.32b,c,d** (Feb-00)
  + bug fix versions
  + unix platform
* **0.32** (Dec-99)
  + first quite stable version