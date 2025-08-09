# GingerRust
A game engine made in Rust, because I got bored of C.

The documentation will be split into multiple readme files, inside of the docs folder. Each file will explain how to use the corresponding feature, and my thought process when making it. I will try my best to make them look nice, but I'm not that good with design, hence the experience with programming.

The game engine is named after my cat, Ginger. Gingey for short.

# Build Instructions
Before you build the project, you need to have Rust installed and added to your path. Instructions for that can be found at [https://doc.rust-lang.org/book/ch01-01-installation.html](https://www.rust-lang.org/tools/install)

In order to build the entire project, all you need to do is run ```cargo build``` in the project's root dir. If you want to run it, run ```cargo run```.

If you want to just build the engine for use in your game, just run ```cargo build``` in the engine dir. You can then find the lib in the target dir. It will be called libengine.lib

I'm sure there's a better way to do this, but I want to start working on the actual project.

Also, one day I will probably make all the engine functions available for usage in C based languages for scripting.
