# Hi, I'm Felix

I've been writing C++ since I was about 13 and never really stopped. These days I'm doing my M.Sc. in
Computer Science at the University of Stuttgart and working as a working student at Vector Informatik.
Before that I spent almost seven years at Bosch, most of it building simulation software: boundary element
methods for eddy currents, a ray tracer, and a lot of Python tooling around them.

Leaving Bosch didn't end my interest in simulation. I still work on simulations and the tooling around
them, now at university and in my free time. What I like most: numerics, simulation, making things
fast (more cores, the GPU, or just a better algorithm), and visualization. Seeing the data is usually how I
find the bug, and the easiest way to explain a problem to someone else.

When something looks interesting or a problem needs it, I pick up whatever language or tool fits, so you'll
find a bit of C, C#, Python, CUDA and Java in here too.

## Things I've built for fun

Coming soon (not public yet, still cleaning them up):

- **mesh_tools**: C++23 tools for unstructured volume meshes: VTK `.vtu` I/O with Python bindings, mesh
  processing, and a lightweight Vulkan viewer as a ParaView replacement for everyday use
- **ASTra**: a small language for matrix expressions with a compiler that understands the math (cheapest
  order of matrix products, memory planned at compile time), running on the GPU or the CPU with BLAS

Already here:

- **[mandelbrot](https://github.com/FelixKimmerle/mandelbrot)**: deep zooms past `double` precision
  with perturbation theory, computed with CUDA *or* HIP from the same source and shown via Vulkan interop
- **[chess](https://github.com/FelixKimmerle/chess)**: bitboard engine in C++23; rewriting my old
  move generator took it from ~5.6 M to ~300 M nodes/s
- **[lix](https://github.com/FelixKimmerle/lix)**: a small statically typed language with templates,
  a bytecode VM and a garbage collector
- **[nobcpp](https://github.com/FelixKimmerle/nobcpp)**: a C++ build tool whose build scripts are
  plain C++ (because why not)
- **[field-extension](https://github.com/FelixKimmerle/field-extension)**: finite fields and field
  extensions as C++20 templates, straight out of a math lecture
- **[ft-robotx](https://github.com/FelixKimmerle/ft-robotx)**: bringing an old fischertechnik
  controller back to life over USB and Bluetooth

Some of the code goes back to high school (a 3D plotter for complex functions, a 4D tesseract, a Fourier
"winding machine"). I've cleaned it up, but that's where it all started. Most repos moved here from my
self-hosted GitLab, so some creation dates and commit histories don't match when things were actually written.

Most of my professional work lives in closed company repos, unfortunately.

Find me on [LinkedIn](https://www.linkedin.com/in/felix-kimmerle-cpp/).
