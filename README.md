# ccminer-htmlcoin
Heavy optimized for Windows, build from Visual Studio 2015, CUDA 9.1.

Based on gelotus fork of ccminer 

Check the [ccminer](https://github.com/gelotus/ccminer) for additional info and how to build.

HTMLCOIN donation address: Hjyo3KdT7qnRHtF5WQQwU9ppUe6LwN6UoZ  (mghtthr)

Benchmarks for HTMLCOIN (sha256d)
------------------------------

2x 1080ti with power-target @70%   -> 2309.11 MH/s

1x 1080ti with power-target @90%   -> 1278.16 MH/s



How to use
------------------------------

run the following command for solo mining (make sure to adjust PORT, USERNAME and PASSWORD)

ccminer -a htmlcoin -o http://127.0.0.1:PORT/ -u USERNAME -p PASSWORD

# Building

Open ccminer.sln in VS2015 and compile, the release archive will be in ./dist folder.
