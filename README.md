SiZ

### Copyright (c) 2018, SiZ, The Monero Project ###

### Development and Community Resources ###

# Web :

# Reddit:

# Github:


### Introduction ###

SiZ is a private, secure, untraceable, decentralised digital currency. 



### About this Project ###


This is the core implementation of SiZ. It is open source and completely free to use without restrictions, except for those specified in the license agreement below. 

There are no restrictions on anyone creating an alternative implementation of SiZ that uses the protocol and network in a compatible manner.

As with many development projects, the repository on Github is considered to be the "staging" area for the latest changes. 

Before changes are merged into that master repo, they are tested by individual developers, as well as contributors who focus on thorough testing and code reviews. 

That having been said, the repository should be carefully considered before using it in a production environment, unless there is a patch in the repository for a particular show-stopping issue you are experiencing. 

It is generally a better idea to use a tagged release for stability.

Anyone is able to contribute to SiZ. 

If you have a fix or code change, feel free to submit is as a pull request. 

In cases where the change is relatively small or does not affect other parts of the codebase it may be merged in immediately by any one of the collaborators. 

On the other hand, if the change is particularly large or complex, it is expected that it will be discussed at length either well in advance of the pull request being submitted, or even directly on the pull request.




## Building SiZ 

### On Linux

### Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows ###

Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.
Good luck!

### Copyright ###

Copyright (c) 2018, SiZ, The Monero Project

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

    Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

    Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

    Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Parts of the project are originally copyright (c) 2012-2013 The Cryptonote developers