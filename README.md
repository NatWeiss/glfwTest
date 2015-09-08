GLFW3 Xcode Project
===================

This is a simple example Xcode project using GLFW3 to display a rotating colored triangle on the screen.

It relies on GLFW3 being compiled and installed statically in `/usr/local/lib/`. To install using homebrew:

1. `brew update`
2. `brew tap homebrew/versions`
3. `brew install --static glfw3`

Then simply open this Xcode project and run. You should be able to replace `simple.c` with one of `[glfw/examples](https://github.com/glfw/glfw/tree/master/examples)`.
