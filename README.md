# JWasm general info

JWasm is a free MASM-compatible assembler with these features:

- native support for output formats Intel OMF, MS Coff (32/64-bit), Elf (32/64-bit), Binary, Windows PE (32/64-bit) and DOS MZ.
- precompiled JWasm binaries are available for DOS, Windows and Linux. For OS/2 and FreeBSD, makefiles are supplied.
- Instructions up to AVX are supported.
- JWasm is written in C. The source is portable and has successfully been tested with Open Watcom, MS VC, GCC and more.
- As far as programming for MS Windows is concerned, JWasm can be used with both WinInc (32/64-bit) and Masm32 (32-bit). Since v2.01, it will also work with Sven B. Schreiber's ancient WALK32.
- C header files can be converted to include files for JWasm with h2incX.
- JWasm's source code is released under the Sybase Open Watcom Public License, which allows free commercial and non-commercial use.
- There's a bunch of source samples available - they are supplied with the precompiled binary packages.

# JWasm source code

[JWasm](https://github.com/JWasm/JWasm)

[JWasm-regressions](https://github.com/JWasm/JWasm-regressions)

# Building status

[![Build Status](https://travis-ci.org/JWasm/JWasm.svg)](https://travis-ci.org/JWasm/JWasm.svg)

# JWlink

JWlink is a linker for x86 that can create 16-, 32- and 64-bit binaries.
It's a modified Open Watcom Wlink. Some features have been added and a
few bugs have been fixed. Generally, it has been made more compatible with
the MS linker (the cmdline syntax is still quite different).
 
Besides JWlink's source code there are also precompiled binaries available
for Windows, DOS and Linux. The packages containing precompiled binaries
also include a Manual (in HtmlHelp format for Windows, else in plain Html).

# JWlink source code

[JWlink](https://github.com/JWasm/JWlink)
