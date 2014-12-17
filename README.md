# Awesome C #

A curated list of C good stuff. I give preference to [free software][13] for code, and sellers who aren't evil for physical resources.

This is released under the GNU Free Documentation License - its text is provided in the LICENSE file.

Compilers
=========

* [Clang][38] - A C compiler for LLVM. Supports C11. [NCSA][39].
* [GCC][40] - Provides a C compiler as part of its compiler set. Supports C11 and OpenMP. [GNU GPL3][41].
* [PCC][74] - A very old C compiler. Supports C99. [Various licenses][75]
* [TCC][58] - Tiny C Compiler; a small, fast C compiler. Supports C99 (except complex types). [GNU GPL2.1][8].
* [LCC][142] - A Retargetable Compiler for ANSI C. [License][143].


Database
========

This lists databases and data stores with C APIs.

* [leveldb][46] - A simple persistent key-value store. Available via [clib][26]. [3-clause BSD][6].
* [LMDB][105] - An ultra-fast, ultra-compact key-value embedded data store. [newOpenLDAP][106].
* [MariaDB][25] - A robust, scalable and reliable SQL server, designed to be a drop-in replacement for MySQL. [3-clause BSD][6].
* [PostgreSQL][121] - A powerful object-relational database system. [PostgreSQL licence][122]
* [Redis][51] - An advanced key-value store. [3-clause BSD][6].
* [SQLite][22] - A self-contained, serverless, zero-configuration, transactional SQL database engine with a C interface. Public domain.
* [UnQLite][23] - A self-contained, serverless, zero-configuration, transactional NoSQL engine with a C interface. [FreeBSD][24].

Editors
=======

These are specifically fancier, IDE-type editors. If you want a programmer's text editor, and yours *doesn't* support C, I'd be quite surprised.

* [Anjuta DevStudio][42] - The GNOME IDE. [GNU GPL3][41].
* [CodeLite][45] - A cross-platform IDE. [GNU GPL2.1][8].
* [Geany][43] - A very small and fast IDE. [GNU GPL2.1][8].
* [KDevelop][44] - The KDE IDE. [GNU GPL2.1][8].

Frameworks
==========

This section has big libraries that provide data structures and other stuff you expect of a 'modern' standard library.

* [APR][78] - Apache Portable Runtime; another library of cross-platform utility functions. [Apache2.0][32].
* [C Algorithms][88] - A collection of common algorithms and data structures for C. [ISC][61].
* [EFL][119] - A large collection of useful data structures and functions. Various licenses, all free.
* [GLib][1] - A library of utility functions and structures, designed to be portable, efficient and powerful. [GNU LGPL3][5].
* [GIO][2] - A modern and easy-to-use VFS API. [GNU LGPL3][5].
* [GObject][3] - An object-oriented system and object model for C. [GNU LGPL3][5].
* [libnih][93] - A lightweight library of C functions and structures. [GNU GPL2.1][8].
* [libU][28] - A small library of basic utilities, including memory allocation, string manipulation and logging. [3-clause BSD][6].
* [stb][114] - A range of single-file libraries for C. Public domain.

Game Programming
================

* [Allegro][48] - A cross-platform, video game development and multimedia library. [zlib][49].
* [Corange][101] - A game engine in pure C. [FreeBSD][24].
* [CSFML][90] - A binding for [SFML][91] in C. [zlib][49].
* [FreeGLUT][99] - An alternative to the OpenGL Utility Toolkit. Allows the creation and management of windows with OpenGL contexts. [X11][100].
* [GLFW][98] - A multi-platform library for creating windows with OpenGL contexts. [zlib][49].
* [ioquake3][107] - The Quake3 engine, freed at last. [GNU GPL2.1][8]
* [SDL][50] - A cross-platform library designed to provide low-level access to audio, keyboard, mouse, joystick and graphics hardware via OpenGL. [zlib][49].


Generic Programming
===================

* [klib][76] - Small and lightweight implementations of common algorithms and data structures. [Expat][11].
* [SGLIB][30] - Simple Generic Library; an implementation of a range of generic programming structures and idioms in C. [GNU GPL3][41].

Graphics
========

* [Cogl][127] - A GPU graphics and utilities API. [GNU LGPL2.1][15].
* [Clutter][126] - A UI library based on OpenGL. [GNU LGPL2.1][15].



Graphical User Interface
========================

These are specifically [widget toolkits][12].

* [Elementary][17] - A widget toolkit. Part of the [EFL][18]. [GNU LGPL2.1][15].
* [GTK+][14] - A cross-platform widget toolkit. [GNU LGPL2.1][15].
* [IUP][16] - Another cross-platform widget toolkit. [Expat][11].
* [Tk][19] - A basic widget toolkit. Part of Tcl/Tk. [Tcl/Tk License][20].
* [XForms Toolkit][21] - A widget toolkit designed for the XWindow system. [GNU LGPL2.1][15].

JSON
=======

* [Jannson][53] - A C library for encoding, decoding and manipulating JSON. [Expat][11].
* [jsmn][120] - A minimalistic JSON parser. [Expat][11].
* [WJElement][77] - Advanced JSON manipulation library, with support for JSON Schema. [GNU GPL3][41].
* [YAJL][60] - A fast C JSON streaming parser library. [ISC][61]


Learning and Tutorials
======================

This is a list of resources for learning C programming in general, or something useful relating to C programming.

## Online ##

* [Bit twiddling hacks][73]
* [The C Programming Language 2E][7] (online PDF)
* [The lost art of C structure packing][34]
* [Writing efficient C and C code optimization][33]

## Physical ##

* [21st Century C][35] - A very good *second* programming book on C.
* [C Programming: A Modern Approach][64] - An excellent book to learn the basics from C from.
* [Expert C Programming: Deep C Secrets][55] - An interesting, in-depth and *entertaining* look at the innards of C.
* [Head First C][102] - A 'head-first' style book for learning C.
* [Understanding and Using C Pointers][36] - An in-depth resource on pointers in C.

Multimedia
==========

* [FFMPEG][63] - A complete, cross-platform solution to record, convert and stream audio and video. [GNU LGPL2.1][15], with some parts under [GNU GPL2.1][8].
* [GStreamer][123] - A framework for audio and visual media. [GNU LGPL2.1][15].
* [lodepng][69] - A simple PNG image decoder and encoder, requiring no other dependencies. [3-clause BSD][6].

Networking and Internet
=======================

* [asnlc][138] - A compiler of ASN.1 specifications into C source code. [FreeBSD][24].
* [GnuTLS][112] - A secure communication library, implementing SSL, TLS and DTLS. [GNU LGPL2.1][15]
* [libcurl][65] - A client-side URL transfer library, supporting a wide range of formats. [curl license][66]
* [libevent][124] - An event loop replacement for network servers. [3-clause BSD][6].
* [nanomsg][139] - A C-based implementation of ZeroMQ. [Expat][11].
* [OpenSSL][110] - Implementation of the SSL and TLS protocols, and also includes a cryptography library. [Dual Licensed under the OpenSSL License and the SSLeay License][111]
* [ZeroMQ][52] - High-performance message passing networking library. Implemented in C++, but has a C interface. [GNU LGPL3][41].

Numerical
=========

* [ATLAS][137] - Automatically Tuned Linear Algebra Software. [3-clause BSD][6].
* [BLAS][135] - Basic Linear Algebra Subprograms; a set of routines that provide vector and matrix operations. [BLAS license][136]
* [FFTW][70] - The Fastest Fourier Transform in the West; a highly-optimized fast Fourier transform routine. [GNU GPL2.1][8].
* [GMP][79] - GNU Multple Precision Arithmetic Library; a library for arbitrary-precision arithmetic. [GNU GPL2.1][8] and [GNU LGPL2.1][15].
* [GSL][47] - The GNU Scientific Library; a sophisticated numerical library. [GNU GPL3][41].
* [KISS FFT][71] - A very simple fast Fourier transform library. [3-clause BSD][6].
* [LAPACKE][133] - A C interface to [LAPACK][134]. [3-clause BSD][6].
* [Yeppp!][72] - Very fast, SIMD-optimized mathematical library. [3-clause BSD][6].


Package Manager
===============

* [CCAN][103] - Modelled after Perl's CPAN, this is a big collection of C code that does stuff. The full list is [here][104]. Various licenses (all free software).
* [clib][26] - Something of a package manager for C. Comes with a [bunch of libraries of its own][27]. [Expat][11].

Parallel Programming
====================

* [OpenMP][37] - A set of C pragmas designed to allow for easy parallelization of code. Standard (licensing not applicable).
* [TinyCThread][115] - A portable, small implementation of the C11 threads API. [zlib][49].

Regex
=====

> "Some people, when confronted with a problem, think 'I know, I'll use regular expressions'. Now they have two problems." - Jamie Zawinski.

* [PCRE][83] - An implementation of regexes identical to that of Perl 5. [3-clause BSD][6].
* [SLRE][80] - Super Light Regular Expression library; a very small implementation of a subset of Perl regex syntax. [GNU GPL2.1][8].
* [TRE][82] - A POSIX-compliant, feature-full regex library. [FreeBSD][24].
* [T-Rex][81] - Another tiny regex library. [zlib][49].

Serialization
=============

* [c-capnproto][130] - An implementation of the Cap'n Proto serialization protocol. [Expat][11].
* [libavro][140] - A C implementation of the Avro data serialization system. [Apache2.0][32].
* [msgpackalt][132] - A simple, light and fast binary serialization library. [3-clause BSD][6].
* [protobuf-c][129] - An implementation of Google Protocol Buffer in C. [FreeBSD][24].
* [xdr][131] - External Data Representation; a standard for data serialization. Standard (no license applicable).

Standard Libraries
==================

This contains standard C libraries.

* [Bionic][4] - Google's C standard library, developed for Android. [3-clause BSD][6]
* [dietlibc][9] - A C standard library designed for the smallest possible binaries. [GNU GPL2.1][8].
* [glibc][57] - The GNU C Library; an implementation of the C standard library. [GNU LGPL3][5]. 
* [musl][10] - A standard C library, compatible with POSIX 2008 and C11. Designed for static linking. [Expat][11].

Testing
=======

* [CHEAT][84] - A very simple unit testing framework. [FreeBSD][24].
* [Check][59] - A unit testing framework for C. [GNU LGPL2.1][15].
* [cmocka][141] - A unit testing framework with support for mock objects. [Apache2.0][32].
* [CUnit][94] - Another unit testing framework for C. [GNU LGPL2.1][15].
* [minunit][92] - Minimal unit testing framework for C. [Expat][11].

Tools
=====

This is a list of useful programs to help you write and debug C code which are *not* editors, libraries or compilers.

* [aimake][97] - A build tool designed to avoid complex configurations. [GNU GPL3][41].
* [c99sh][113] - Run C files using hash-bang. No license specified.
* [GDB][87] - The GNU Project debugger; a debugger for C. [GNU GPL3][41].
* [gprof][86] - A performance analysis tool. Part of GNU binutils. [GNU GPL3][41].
* [rr][95] - A debugger that records non-deterministic executions to allow for deterministic debugging. [FreeBSD][24].
* [Valgrind][85] - A range of dynamic analysis tools, including a leak checker. [GNU GPL2.1][8].

Utilities
=========

This is a 'catch-all' category for anything that doesn't fit well anywhere else.

* [bstrlib][116] - The Better String Library. [3-clause BSD][6] or [GNU GPL2.1][8].
* [Hans Boehm GC][125] - Garbage collection for C? Don't mind if I do! Various licenses, all free.
* [ICU][67] - International Components for Unicode; a library for Unicode support. [ICU license][68].
* [libCello][96] - A library introducing higher-level programming to C. [3-clause BSD][6].
* [libffi][128] - A portable foreign-function interface library. [Expat][11].
* [libgit2][108] - Pure C implementation of Git. [GNU GPL2 with a linking exception][109].
* [libPhenom][31] - An eventing framework for building high-scalability and high-performance systems. [Apache2.0][32].
* [libuv][56] - Cross-platform asynchronous I/O. [Expat][11].
* [Ragel][54] - A DSL for state machines that compiles to C. [GNU GPL3][41].
* [SDS][29] - Simple Dynamic Strings; a library for handling C strings in a simpler way, but one that is compatible with normal C string functions. Available via [clib][26]. [FreeBSD][24].
* [uthash][117] - A hash table implementation, allowing existing structures to be stored in a hash table easily. [1-clause BSD][118]

XML
===

> "XML is crap. Really. There are no excuses. XML is nasty to parse for humans, and it's a disaster to parse even for computers. There's just no reason for that horrible crap to exist." - Linus Torvalds

* [Expat][89] - A stream-oriented XML parser. [Expat][11].
* [libxml2][62] - A standards-compliant, portable XML parser. [Expat][11].


[1]: https://developer.gnome.org/glib/
[2]: https://developer.gnome.org/gio/
[3]: https://developer.gnome.org/gobject/stable/
[4]: https://github.com/android/platform_bionic
[5]: http://www.gnu.org/licenses/lgpl.html
[6]: http://directory.fsf.org/wiki/License:BSD_3Clause
[7]: http://books.cat-v.org/computer-science/c-programming-language/The.C.Programming.Language.2nd.Edition.pdf
[8]: http://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[9]: http://www.fefe.de/dietlibc/
[10]: http://www.musl-libc.org/
[11]: http://directory.fsf.org/wiki/License:Expat
[12]: http://en.wikipedia.org/wiki/Widget_toolkit
[13]: http://en.wikipedia.org/wiki/Free_software
[14]: http://www.gtk.org/
[15]: http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html
[16]: http://webserver2.tecgraf.puc-rio.br/iup/
[17]: http://docs.enlightenment.org/auto/elementary/
[18]: http://www.enlightenment.org/p.php?p=about/libs
[19]: http://www.tcl.tk/
[20]: http://www.tcl.tk/software/tcltk/license.html
[21]: http://xforms-toolkit.org/
[22]: http://www.sqlite.org/
[23]: http://unqlite.org/
[24]: http://directory.fsf.org/wiki?title=License:FreeBSD
[25]: https://mariadb.com/
[26]: https://github.com/clibs/clib
[27]: https://github.com/clibs/clib/wiki/Packages
[28]: http://www.koanlogic.com/libu/
[29]: https://github.com/antirez/sds
[30]: https://github.com/stefanct/sglib
[31]: http://facebook.github.io/libphenom/index.html
[32]: http://directory.fsf.org/wiki/License:Apache2.0
[33]: http://www.codeproject.com/Articles/6154/Writing-Efficient-C-and-C-Code-Optimization
[34]: http://www.catb.org/esr/structure-packing/
[35]: http://shop.oreilly.com/product/0636920033677.do
[36]: http://shop.oreilly.com/product/0636920028000.do
[37]: http://openmp.org/wp/about-openmp/
[38]: http://clang.llvm.org/
[39]: http://directory.fsf.org/wiki/License:IllinoisNCSA
[40]: https://gcc.gnu.org/
[41]: http://www.gnu.org/licenses/gpl.html
[42]: http://anjuta.org/
[43]: http://www.geany.org/
[44]: https://www.kdevelop.org/
[45]: http://www.codelite.org/
[46]: https://github.com/clibs/leveldb
[47]: http://www.gnu.org/software/gsl/
[48]: http://alleg.sourceforge.net/readme.html
[49]: http://directory.fsf.org/wiki/License:Zlib
[50]: https://www.libsdl.org/
[51]: http://redis.io/
[52]: http://zeromq.org/
[53]: http://www.digip.org/jansson/
[54]: http://www.colm.net/open-source/ragel/
[55]: http://dl.acm.org/citation.cfm?id=179241
[56]: https://github.com/libuv/libuv
[57]: http://www.gnu.org/software/libc/
[58]: http://bellard.org/tcc/
[59]: http://check.sourceforge.net/
[60]: https://lloyd.github.io/yajl/
[61]: http://directory.fsf.org/wiki/License:ISC
[62]: http://xmlsoft.org/
[63]: https://www.ffmpeg.org/
[64]: http://knking.com/books/c2/index.html
[65]: http://curl.haxx.se/libcurl/
[66]: http://curl.haxx.se/docs/copyright.html
[67]: http://site.icu-project.org/
[68]: http://source.icu-project.org/repos/icu/icu/trunk/license.html
[69]: http://lodev.org/lodepng/
[70]: http://www.fftw.org/
[71]: http://sourceforge.net/projects/kissfft/
[72]: http://www.yeppp.info/
[73]: https://graphics.stanford.edu/~seander/bithacks.html
[74]: http://pcc.ludd.ltu.se/
[75]: http://pcc.ludd.ltu.se/licenses/
[76]: https://github.com/attractivechaos/klib
[77]: https://github.com/netmail-open/wjelement/
[78]: http://apr.apache.org/
[79]: https://gmplib.org/
[80]: https://github.com/cesanta/slre
[81]: http://tiny-rex.sourceforge.net/
[82]: https://github.com/laurikari/tre/
[83]: http://www.pcre.org/
[84]: https://github.com/Tuplanolla/cheat
[85]: http://www.valgrind.org/
[86]: http://www.gnu.org/software/binutils/
[87]: http://www.gnu.org/software/gdb/
[88]: https://github.com/fragglet/c-algorithms
[89]: http://www.libexpat.org/
[90]: http://www.sfml-dev.org/download/csfml/
[91]: http://www.sfml-dev.org/index.php
[92]: https://github.com/siu/minunit
[93]: https://github.com/keybuk/libnih
[94]: http://cunit.sourceforge.net/
[95]: http://rr-project.org/
[96]: http://libcello.org/
[97]: http://nethack4.org/projects/aimake/
[98]: http://www.glfw.org/
[99]: http://freeglut.sourceforge.net/
[100]: http://directory.fsf.org/wiki/License:X11
[101]: https://github.com/orangeduck/Corange
[102]: http://shop.oreilly.com/product/0636920015482.do
[103]: http://ccodearchive.net/
[104]: http://ccodearchive.net/list.html
[105]: http://symas.com/mdb/
[106]: http://directory.fsf.org/wiki/License:OpenLDAPv2.7
[107]: http://ioquake3.org/
[108]: https://libgit2.github.com/
[109]: https://github.com/libgit2/libgit2/blob/master/COPYING
[110]: https://www.openssl.org/
[111]: https://www.openssl.org/source/license.html
[112]: http://www.gnutls.org/
[113]: https://github.com/RhysU/c99sh
[114]: https://github.com/nothings/stb
[115]: https://tinycthread.github.io/
[116]: http://bstring.sourceforge.net/
[117]: http://troydhanson.github.io/uthash/
[118]: http://troydhanson.github.io/uthash/license.html
[119]: https://www.enlightenment.org/p.php?p=about/efl
[120]: http://zserge.com/jsmn.html
[121]: http://www.postgresql.org/
[122]: http://opensource.org/licenses/postgresql
[123]: http://gstreamer.freedesktop.org/
[124]: http://libevent.org/
[125]: http://www.hboehm.info/gc/
[126]: http://blogs.gnome.org/clutter/about/
[127]: http://www.cogl3d.org/
[128]: https://github.com/atgreen/libffi
[129]: https://github.com/protobuf-c/protobuf-c
[130]: https://github.com/jmckaskill/c-capnproto
[131]: http://en.wikipedia.org/wiki/External_Data_Representation
[132]: https://code.google.com/p/msgpackalt/
[133]: http://www.netlib.org/lapack/lapacke.html
[134]: http://www.netlib.org/lapack/
[135]: http://www.netlib.org/blas/
[136]: http://www.netlib.org/blas/#_licensing
[137]: http://math-atlas.sourceforge.net/
[138]: http://lionet.info/asn1c/compiler.html
[139]: https://github.com/nanomsg/nanomsg
[140]: http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c
[141]: http://cmocka.org/
[142]: https://sites.google.com/site/lccretargetablecompiler/
[143]: https://github.com/drh/lcc/blob/master/CPYRIGHT
