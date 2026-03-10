# Crypt-OpenSSL-EC

This is Crypt::OpenSSL::EC, an XS-wrapper around the OpenSSL EC (Elliptic
Curves) library.

## INSTALLATION

To install this module type the following:

```shell
perl Makefile.PL
make
make test
make install
```

## DEPENDENCIES

This module requires these other modules and libraries:

* Crypt::OpenSSL::Bignum 0.04 or later
* OpenSSL 0.9.8i or later headers and libraries for compilation

To build you will also need (but may already be installed on your OS):

* make
* gcc
* ExtUtils::MakeMaker
* Test::Simple

## COPYRIGHT AND LICENCE

Copyright (C) 2012 by Mike McCauley  
Copyright (C) 2026 by Heikki Vatiainen

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself, either Perl version 5.14.2 or,
at your option, any later version of Perl 5 you may have available.

Terms of Perl version 5.14.2 are:

a) the GNU General Public License as published by the Free
   Software Foundation; either version 1, or (at your option) any
   later version, or

b) the "Artistic License"
