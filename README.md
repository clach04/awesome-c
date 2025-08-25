# awesome-c

My personal list of useful (or interesting) C related resources.

  * [Compilers](#compilers)
    + [Windows](#windows)
  * [Tools](#tools)
  * [Documentation](#documentation)
  * [Libraries](#libraries)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


## Compilers

  * SDCC - Small Device C Compiler - https://sdcc.sourceforge.net/
  * TinyCC / TCC - https://bellard.org/tcc/
      * https://repo.or.cz/w/tinycc.git
      * https://github.com/TinyCC/tinycc
      * https://en.wikipedia.org/wiki/Tiny_C_Compiler
      * https://download.savannah.gnu.org/releases/tinycc/

### Windows

  * Strawberry Perl https://strawberryperl.com/ for Windows includes an easy-to-use GCC-based C/C++ compiler
      * mingw32 with make/gmake, fortran, dos2unix, iconv, patch, openssl, NSSM (The non-sucking service manager)
      * Perl5
  * https://github.com/skeeto/w64devkit - Portable C, C++, and Fortran Development Kit for x64 and x86 Windows
      * https://nullprogram.com/blog/2020/09/25/ - w64devkit: (Almost) Everything You Need
      * includes busybox-w32 : standard unix utilities, including sh
      * gmake. gdb, ctags, vim/gvim
  * https://winlibs.com/
      * http://mingw-w64.org/
      * Code::Blocks https://www.codeblocks.org/
  * https://sourceforge.net/projects/mingw/ - last update 2021
  * http://www.smorgasbordet.com/pellesc/ - Pelles C based on LCC - Pelles C is a complete development kit for Desktop Windows.

## Tools

## Debug

### assert

   * https://www.pixelbeat.org/programming/gcc/static_assert.html
#### Memory

  * https://github.com/DynamoRIO/drmemory - Memory Debugger for Windows, Linux, Mac, and Android
  * https://github.com/rxi/dmt - Dynamic memory tracker for C (malloc replacement)

### Formatting

  *  http://uncrustify.sourceforge.net/ reformatter/indenter (safe than GNU indent and astyle)

## Documentation

  * Pre-defined Compiler Macros - https://github.com/cpredef/predef
      * Originally at https://sourceforge.net/projects/predef/
  * https://www.pixelbeat.org/programming/profiling/
  * https://nullprogram.com/blog/2017/08/20/ - A Tutorial on Portable Makefiles by Chris Wellons


## Books

  * Expert C Programming: Deep C Secrets by Peter van der Linden
  * TODO Harvard recommended one
  * TODO K&R Programming in C (2nd)

## Libraries

  * https://monocypher.org/
      * https://github.com/LoupVaillant/Monocypher

## C++ Libraries

  * https://github.com/sharkdp/dbg-macro

## TODO

Things that look interesting but I've not researched/used properly

  * w64devkit for Windows compiler set of tools
      * Downloads flagged as virus and blocked (by Windows Defender/Chrome/Edge) - https://github.com/skeeto/w64devkit/issues/185
