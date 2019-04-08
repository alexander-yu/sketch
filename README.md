# Sketch

Sketch is a Go library for stochastic/approximation streaming algorithms. In other words, this is a library for algorithms that compute statistics for data sets where only one pass is feasible, and the size of the data is too large to compute an exact value. These algorithms, often referred to as _sketches_, stochastically compute approximate results within certain error bounds.

For a library that does compute exact statistics in a one-pass manner, see the [stream](https://github.com/alexander-yu/stream) library.
