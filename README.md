sodiumoxide
===========

> [NaCl](http://nacl.cr.yp.to) (pronounced "salt") is a new easy-to-use high-speed software library for network communication, encryption, decryption, signatures, etc. NaCl's goal is to provide all of the core operations needed to build higher-level cryptographic tools.
> Of course, other libraries already exist for these core operations. NaCl advances the state of the art by improving security, by improving usability, and by improving speed.

> [Sodium](https://github.com/jedisct1/libsodium) is a portable, cross-compilable, installable, packageable fork of NaCl (based on the latest released upstream version nacl-20110221), with a compatible API.

This package aims to provide a type-safe and efficient Rust binding that's just
as easy to use.

**Primary Maintainer:** Fraser Hutchison (fraser.hutchison@maidsafe.net)

Dependencies
------------

[Sodium](https://github.com/jedisct1/libsodium)

Building
--------
    cargo build

Testing
-------
    cargo test

Documentation
-------------
    cargo doc

Documentation will be generated in target/doc/...

Most documentation is taken from NaCl, with minor modification where the API
differs between the C and Rust versions.

Documentation for the latest build can be found at
[http://maidsafe.net/sodiumoxide](http://maidsafe.net/sodiumoxide).

Examples
--------
TBD

Join in
=======
File bugs in the issue tracker

Master git repository

    git clone https://github.com/maidsafe/sodiumoxide.git

License
-------
MIT

Status
------

| Crate | Linux | Windows | OSX |
|:-----:|:-----:|:-------:|:---:|
| [![](http://meritbadge.herokuapp.com/maidsafe_sodiumoxide)](https://crates.io/crates/maidsafe_sodiumoxide) |[![Build Status](https://travis-ci.org/maidsafe/sodiumoxide.svg?branch=master)](https://travis-ci.org/maidsafe/sodiumoxide)| [![Build Status](http://ci.maidsafe.net:8080/buildStatus/icon?job=sodiumoxide_win64_status_badge)](http://ci.maidsafe.net:8080/job/sodiumoxide_win64_status_badge/) | [![Build Status](http://ci.maidsafe.net:8080/buildStatus/icon?job=sodiumoxide_osx_status_badge)](http://ci.maidsafe.net:8080/job/sodiumoxide_osx_status_badge/) |
