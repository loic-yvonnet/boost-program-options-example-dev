# Simple Boost Program Options example

The only aim of this tiny project is to be built with either:
* **boost-program-options-example-build-docker**: Build this project with a Ubuntu docker container, with GCC 9, CMake 3.16, and vcpkg. It may be found [here](https://github.com/loic-yvonnet/boost-program-options-example-build-docker). This is basically the "native" build.
* **boost-program-options-example-build-yocto**: Build this project with the Yocto thanks to BitBake and OpenEmbedded for the arm64 platform in QEMU. It may be found [here](https://github.com/loic-yvonnet/boost-program-options-example-build-yocto). This is basically the "embedded" build.

In both cases, it takes Boost as an excuse to see a way to manage dependencies in C++ with vcpkg ("native" build) and Yocto (cross-compilation).
