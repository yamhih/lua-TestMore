
lua-TestMore : an Unit Testing Framework
========================================

[![Build Status](https://travis-ci.org/fperrad/lua-TestMore.png)](https://travis-ci.org/fperrad/lua-TestMore)

Introduction
------------

lua-TestMore is a port of the Perl5 module [Test::More](http://search.cpan.org/~mschwern/Test-Simple/).

It uses the [Test Anything Protocol](http://en.wikipedia.org/wiki/Test_Anything_Protocol) as output,
that allows a compatibility with the Perl QA ecosystem.

It's an extensible framework.

It allows a simple and efficient way to write tests (without OO style).

Some tests could be marked as TODO or skipped.

Errors could be fully checked with error_like().

It supplies a Test Suite for Lua itself.

Links
-----

The homepage is at [http://fperrad.github.io/lua-TestMore/](http://fperrad.github.io/lua-TestMore/),
and the sources are hosted at [http://github.com/fperrad/lua-TestMore/](http://github.com/fperrad/lua-TestMore/).

Copyright and License
---------------------

Copyright (c) 2009-2013 Francois Perrad

This library is licensed under the terms of the MIT/X11 license, like Lua itself.

