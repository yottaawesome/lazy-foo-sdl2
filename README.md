# Lazy Foo' Productions' SDL2 tutorial

## Introduction

My in-development walkthrough of Lazy Foo' Productions' [SDL2 tutorial](https://lazyfoo.net/tutorials/SDL/index.php) for Windows. All code that has been copied remains the copyright of Lazy Foo' Productions, and is simply reproduced here as part of my learning process and for my reference. The code contained here is of little use without the associated tutorials, so I encourage you to go through them carefully.

## Using this repository

The SDL2 binaries and headers for Windows have been included in this repository, so running the code in this repo should just be a case of cloning and opening the solution file in any version of Visual Studio 2019 that has the _Desktop development with C++_ workload. For a clean set-up of a project with SDL2, please consult [lesson one](https://lazyfoo.net/tutorials/SDL/01_hello_SDL/windows/msvc2019/index.php).

This repository is intended to be used alongside reading the tutorials, hence each tutorial comprises a different project in the solution. While going through the code, it's important to note that it's written as part of a tutorial; it's deliberately simplistic in order to highlight the key concepts of working with SDL2. Real world programs utilising SDL2 would be structured and written quite differently to what is contained here.

## Deviations from the tutorials

### General

The steps followed in this repository are mostly identical to the tutorial steps for all projects. However, I've chosen to add the `SDL2.dll` and `SDL2_image.dll` module paths to each project individually via `Configuration Properties > Debugging > Environment` instead of modifying the `PATH` environment variable globally, as per [here](https://stackoverflow.com/questions/2119539/how-do-i-set-the-path-to-a-dll-file-in-visual-studio). This means that running the samples should just be a case of cloning, building and running them -- there is no need to modify your global `PATH`. In addition to this, I've moved all media files for each project into their own directories with the name `<n>-media`.

### Project-specific

Where I've deviated from the tutorials by making my own changes (whether that be doing something novel or doing a different thing that achieves the same goal as the tutorial), I've added a `README.md` to each relevant project that outlines these deviations. Please consult these files for additional details.

## Additional resources

* [Lazy Foo' Productions](https://lazyfoo.net/)
* [SDL website](https://www.libsdl.org/)
* [SDL Wiki](http://wiki.libsdl.org/FrontPage)
* [SDL GitHub mirror](https://github.com/SDL-mirror/SDL)
* [SDL_image 2.0](http://www.libsdl.org/projects/SDL_image/)
