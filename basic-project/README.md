### Basic igraph project

This is a barebones project skeleton that illustrates the usage of igraph. You must adapt it to the specifics of your own system before it can be used.

In order to use igraph (or any other library) in a project, the following is necessary:

 - Indicate the location of the igraph header files.
 - Link to the igraph library, and indicate the location of this library to the compiler.
 - If igraph was compiled as a static library, you must manually link in all of igraph's own dependencies. Which these are depends on how igraph was configured.

How to do these depends on the specific compiler and operating system that you are using. On Unix-like system, the required compiler options can often be retrieved using the `pkg-config` utility. The included makefile shows how to do this.

See the tutorial for more information:

https://igraph.org/c/html/latest/igraph-Tutorial.html#tut-lesson-1-compiling-without-cmake

