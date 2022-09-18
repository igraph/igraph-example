
# This makefile is meant as a starting point that you should edit,
# and adapt to the specifics of your system.

# If pkg-config is available and igraph is installed in a standard location,
# or if the location of igraph.pc is added to the PKG_CONFIG_PATH environment
# variable, then we can retrieve the necessary compiler and linker options
# as follows. If igraph was installed a static library, then add --static
# to the pkg-config call that retrieves the linker options.
CFLAGS = $(shell pkg-config --cflags igraph)
LDFLAGS = $(shell pkg-config --libs igraph)

all: diameter

clean:
	rm -f diameter
