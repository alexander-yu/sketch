# Sketch

[![GoDoc](https://godoc.org/github.com/alexander-yu/sketch?status.svg)](https://godoc.org/github.com/alexander-yu/sketch)
[![Build Status](https://travis-ci.org/alexander-yu/sketch.svg?branch=master)](https://travis-ci.org/alexander-yu/sketch)
[![Go Report Card](https://goreportcard.com/badge/github.com/alexander-yu/sketch)](https://goreportcard.com/report/github.com/alexander-yu/sketch)
[![codecov](https://codecov.io/gh/alexander-yu/sketch/branch/master/graph/badge.svg)](https://codecov.io/gh/alexander-yu/sketch)
[![GitHub license](https://img.shields.io/github/license/alexander-yu/sketch.svg)](https://github.com/alexander-yu/sketch/blob/master/LICENSE)

Sketch is a Go library for stochastic/approximation streaming algorithms. In other words, this is a library for algorithms that compute statistics for data sets where only one pass is feasible, and the size of the data is too large to compute an exact value. These algorithms, often referred to as _sketches_, stochastically compute approximate results within certain error bounds.

For a library that does compute exact statistics in a one-pass manner, see the [stream](https://github.com/alexander-yu/stream) library.
