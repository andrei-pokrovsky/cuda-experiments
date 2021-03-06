# cuda-experiments

## Quick Start

    ./configure && make && make bench

## Configuring

TO auto-detect CC version and create `config.mk`, try

    `./configure`

Otherwise, create `config.mk` and set the variable `CUDA_CC` to the version of code you want to generate.
For example

    CUDA_CC=35

## Building

Build all supported tests

    make

## Running

Run all supported tests and dump outputs in `$MODULE.csv`

    make bench

Run individual tests, with outputs to stdout:

    <module>/main

## stream-thread

https://devblogs.nvidia.com/maximizing-unified-memory-performance-cuda/

## stream-warp

https://devblogs.nvidia.com/maximizing-unified-memory-performance-cuda/

## Other Benchmarks

[mgbench](https://github.com/tbennun/mgbench)

[blackjackbench](https://sourceforge.net/projects/blackjackbench/)

