
BriefLZ - small fast Lempel-Ziv
===============================

Version 1.05

Copyright (c) 2002-2015 Joergen Ibsen

<http://www.ibsensoftware.com/>


About
-----

BriefLZ is a small and fast open source implementation of a Lempel-Ziv
style compression algorithm. The main focus is on speed, but the ratios
achieved are quite good compared to similar algorithms.


Usage
-----

The include file `brieflz.h` contains documentation in the form of [doxygen][]
comments. A configuration file is included, so you can simply run `doxygen`
to generate documentation in HTML format.

If you wish to compile BriefLZ on 16-bit systems, make sure to adjust the
constants `BLZ_HASH_BITS` and `BLOCK_SIZE`.

[doxygen]: http://www.doxygen.org/


License
-------

BriefLZ - small fast Lempel-Ziv

Copyright (c) 2002-2015 Joergen Ibsen

This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must
     not claim that you wrote the original software. If you use this
     software in a product, an acknowledgment in the product
     documentation would be appreciated but is not required.

  2. Altered source versions must be plainly marked as such, and must
     not be misrepresented as being the original software.

  3. This notice may not be removed or altered from any source
     distribution.
