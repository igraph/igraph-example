# Using igraph as a CMake subproject

This method of linking to igraph will compile your project and igraph at the same time. This way, it is not necessary to install igraph separately.

After checking out this repository, run `git submodule update --init`. This will download the latest igraph sources into the `igraph` subdirectory. Then the CMake project can be compiled in the usual way:

 - Create a build directory and enter it: `mkdir build && cd build`
 - Configure the project: `cmake ..`
 - Build the project: `cmake --build .`
