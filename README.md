# Rasterazor

A pure javascript software rasterizer for razor sharp images.


## Goals

With descending importance:

1. Correctness - Rasterizations must be sub-pixel perfect
2. Code Quality - The code must be beautiful
	- Easy to read
	- No weird constructs just to optimize speed
	- No unnecessary abbreviations
3. Simplicity - Less complex algorithms are preferred

This is not supposed to be a real time renderer.
Therefore speed is of little importance.
