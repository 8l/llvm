Low Level Virtual Machine (LLVM)
================================

This directory and its subdirectories contain source code for LLVM,
a toolkit for the construction of highly optimized compilers,
optimizers, and runtime environments.

LLVM is open source software. You may freely distribute it under the terms of
the license agreement found in LICENSE.txt.

Please see the documentation provided in docs/ for further
assistance with LLVM, and in particular docs/GettingStarted.rst for getting
started with LLVM and docs/README.txt for an overview of LLVM's
documentation setup.

If you are writing a package for LLVM, see docs/Packaging.rst for our
suggestions.

sudo apk add cmake 
sudo apk add libffi-dev
sudo apk add sphinx
sudo apk add sphinx-doc
sudo apk add sphinx-python
sudo apk add py2-sphinx
sudo apk add binutils-gold

# manual build and install z3
https://github.com/Z3Prover/z3

$ mkdir ../build && cp run.sh ../build && cd ../build
$ ./run.sh
$ sudo make install

$ clang --version
clang version 5.0.0 (tags/RELEASE_500/final)
Target: x86_64-alpine-linux-musl
Thread model: posix
InstalledDir: /usr/bin

