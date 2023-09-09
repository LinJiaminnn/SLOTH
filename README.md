# SLOTH
Hi, there! I'm having a go at writing a n-dim(n≤3) linear algebra tensor lib in c++ which provides access to GPU-based operations relying on CUDA Toolkit for GPU support. (Still There are many issues concerning of efficiency, robustness and code migration to be sorted out, but it's an interesting start for beginners like me? Haha. )
## Get Started
To include the library in your C++ projects, simply include libcumat.h in the include/ folder.

Although this is a header-only library, it does require CUDA libraries to be linked in order to compile successfully. 
