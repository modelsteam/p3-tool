p3-tool
===========

A reconfigurator tool for fPromela with support for variability abstractions.

You can retrieve the tool from <http://ahmadsalim.github.io/p3-tool>; to install the tool, download the repository, get the latest version of the [Haskell Platform](https://www.haskell.org/platform/) and run `cabal install` in the directory containing the `p3-tool` cabal file. 

The Z3 theorem prover is a prerequisite for running the tool, and the tool assumes that the `z3` executable is available on the `PATH` in your environment. You can retrieve the Z3 binaries from <https://github.com/Z3Prover/z3/releases>.

The tool has been tested on Mac OS X 10.10 and Windows 7, but should otherwise also work on any *nix platform and newer Windows versions.
Assuming that Haskell binaries are in your `PATH`, you can run the tool by writing `p3-fpromela --input [input_file]` where `[input_file]` is the path to your fPromela and corresponding TVL file without file extension.


An accompanying suite of benchmarks is available from <https://github.com/ahmadsalim/p3-benchmarks>.
