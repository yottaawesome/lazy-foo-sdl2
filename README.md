# Lazy Foo' Productions' SDL2 tutorial

## Introduction

My in-development walkthrough of Lazy Foo' Productions' [SDL2 tutorial](https://lazyfoo.net/tutorials/SDL/index.php). All code that has been copied remains the copyright of Lazy Foo' Productions, and is simply reproduced here as part of my learning process.

## Using this code

The SDL2 binaries and headers for Windows have been included in this repository, so running the code in this repo should just be a case of cloning and opening the solution in VS2019. For a clean set-up of a project with SDL2, please consult [lesson one](https://lazyfoo.net/tutorials/SDL/01_hello_SDL/windows/msvc2019/index.php).

## Deviations from the tutorials

### General

The steps followed in this repository are mostly identical to the tutorial steps for all projects. However, I've chosen to add the `SDL2.dll` module path to each project individually via `Configuration Properties > Debugging > Environment` instead of modifying the `PATH` environment variable globally, as per [here](https://stackoverflow.com/questions/2119539/how-do-i-set-the-path-to-a-dll-file-in-visual-studio).

### Project-specific

Where I've deviated from the tutorials by making my own changes (whether that be doing something novel or doing a different thing that achieves the same goal as the tutorial), I've added a `README.md` to each relevant project that outlines these deviations. Please consult these files for additional details.
