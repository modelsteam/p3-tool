p3-tool
===========

A reconfigurator tool for fPromela with support for variability abstractions.

> Info: The tool now supports basic features (June 3rd 2015)

You can retrieve the tool from <http://ahmadsalim.github.io/p3-tool>; to install the tool, download the repository, get the latest version of the [Haskell Platform](https://www.haskell.org/platform/) and run `cabal install` in the directory containing the `p3-tool` cabal file.

The tool has been tested on Mac OS X 10.10, but should work on any *nix platform.
It _may_ work on Windows with Cygwin or *nix-like environment, but this has not been tested.
Assuming that Haskell binaries are in your `PATH`, you can run the tool by writing `p3-fpromela --input [input_file]` where `[input_file]` is the path to your fPromela and corresponding TVL file without file extension.


An accompanying suite of benchmarks is available from <https://github.com/ahmadsalim/p3-benchmarks>.
