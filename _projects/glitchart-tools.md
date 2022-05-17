---
name: Glitch Art Tools
year: 2021
brief: Python scripts and a GUI for making glitch art images
github: glitchart-tools
made-with:
  - python
  - qt
---
Glitch Art Tools make it easy to mess with your favorite pictures. You can do pixel sorts, channel swaps, and image bends. The GUI uses Qt so it works easily cross-platform.

## Features
Pixel Sorting
: A very common (and sometimes divisive) type of glitch art is pixel sorting. It's exactly as it sounds, you sort pixels in an image.
: I made use of generators and higer order functions to make all sorts of effects.

Swizzling / Swabbing RGB Channels
: Pretty self-explanatory. Take all of the values for the red pixels and swap them with the blue pixels, or any combination of RGB you can imagine. You can even do RRR!

Image Bending / Line Offsets
: You can use this feature to simply wrap an image around the edges or you can make it wavy using sin/cos functions.

Qt GUI
: It's made with Qt so it's easy to use cross-platform.