* README_EN.txt
* 2020.04.12
* tacklelib--3dparty--fmt

1. DESCRIPTION
2. LICENSE
3. REPOSITORIES
4. INSTALLATION
5. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
fmt sources fork from: https://github.com/fmtlib/fmt

From author:

  {fmt} is an open-source formatting library for C++. It can be used as a safe
  and fast alternative to (s)printf and iostreams.

  Documentation:
    https://fmt.dev

  Q&A: ask questions on StackOverflow with the tag fmt.
    https://stackoverflow.com/questions/tagged/fmt

  Features
    * Replacement-based format API with positional arguments for localization.
    * Format string syntax similar to the one of str.format in Python.
    * Safe printf implementation including the POSIX extension for positional
      arguments.
    * Implementation of C++20 std::format.
    * Support for user-defined types.
    * High performance: faster than common standard library implementations of
      printf and iostreams. See Speed tests and Fast integer to string
      conversion in C++.
    * Small code size both in terms of source code (the minimum configuration
      consists of just three header files, core.h, format.h and format-inl.h)
      and compiled code. See Compile time and code bloat.
    * Reliability: the library has an extensive set of unit tests.
    * Safety: the library is fully type safe, errors in format strings can be
      reported at compile time, automatic memory management prevents buffer
      overflow errors.
    * Ease of use: small self-contained code base, no external dependencies,
      permissive BSD license
    * Portability with consistent output across platforms and support for older
      compilers.
    * Clean warning-free codebase even on high warning levels
      (-Wall -Wextra -pedantic).
    * Support for wide strings.
    * Optional header-only configuration enabled with the FMT_HEADER_ONLY
      macro.

  See the documentation for more details.

-------------------------------------------------------------------------------
2. LICENSE
-------------------------------------------------------------------------------
MIT license.
(see included text file "LICENSE.rst" or
https://github.com/fmtlib/fmt/blob/master/ChangeLog.rst )

NOTE:
  Switch from BSD 2-Clause "Simplified" License, see the `ChangeLog.rst`.

-------------------------------------------------------------------------------
3. REPOSITORIES
-------------------------------------------------------------------------------
Primary:
  * https://sf.net/p/tacklelib/3dparty--fmt/HEAD/tree/trunk
    https://svn.code.sf.net/p/tacklelib/3dparty--fmt/trunk
First mirror:
  * https://github.com/andry81/tacklelib--3dparty--fmt/tree/trunk
    https://github.com/andry81/tacklelib--3dparty--fmt.git
Second mirror:
  * https://bitbucket.org/andry81/tacklelib-3dparty-fmt/src/trunk
    https://bitbucket.org/andry81/tacklelib-3dparty-fmt.git

-------------------------------------------------------------------------------
4. INSTALLATION
-------------------------------------------------------------------------------
N/A

-------------------------------------------------------------------------------
5. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
