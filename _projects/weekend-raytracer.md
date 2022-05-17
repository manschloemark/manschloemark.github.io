---
name: Weekend Raytracing
year: 2021
github: weekend-raytracing
brief: An extension of the ray tracer from Peter Shirley's book series, written in C++
made-with:
  - cpp
---
This is my implementation of Peter Shirley's ray tracer from his book series [_Ray Tracing in One Weekend_](https://raytracing.github.io/). It's seriously awesome and aptly named. Since I hadn't really worked with C++ I was mostly following along and using my experience with C to get by. I ended up extending the program in a few interesing ways, most notably by implementing parallel processing.

I recently wrote another similar path tracer in C instead of C++. Mostly to practice C but I also made some of my own changes to the architecture.

## Personal Additions
- Parallelized the program to speed up renders
- Command-line argument parsing
- Triangle rendering using the M&ouml;ller Trumbore algorithm
- Various textures created using math