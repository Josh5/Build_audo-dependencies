Build_audo-dependencies
=======================

Build environment for audo-dependencies

* Author: Josh Sunnex (tinyhtpc@gmail.com)
* Github: https://github.com/Josh5/Build_audo-dependencies

## Introduction
This is a really gash build script for cross-compiling audo dependencies.
Currently supported ARCH:
* armv7l

## How to use
I run a 32-bit Ubuntu 12.04.2 LTS. Can't guarantee it will run on any other system.
**Dependencies:**
```
sudo apt-get install autoconf autogen build-essential libtool pkg-config cmake bison flex cvs bzr git subversion nano zlib1g-dev
```

Execute the build script by running ./build_dependencies [ARCH]
