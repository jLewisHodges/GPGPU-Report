# GPGPU-Report
An Academic paper on the usefulness of General Purpose Computing on Graphics Processing Units.

# Abstract:
General-Purpose computation on Graphics Processing Unit (GPGPU) is growing in popularity since its introduction in 2007 with the release of Compute Unified Device Architecture (CUDA) a parallel computing framework developed by NVIDIA. The scientific community has taken special interest in GPGPU due to its ability to solve highly computational problems that can be run in parallel.

In this paper, an example program using exclusively the CPU to execute matrix-matrix multiplication of different sizes was compared against a GPGPU program executing the same sized matrix-matrix multiplication. The results of this experiment are analyzed and explained with a focus on the speed up between the CPU and GPGPU program.

In general, there are two GPGPU frameworks that can be used to create programs utilizing the GPU including CUDA and OpenCL. Both allow data to be computed on the graphics card which improves performance in larger datasets that are able to be run in parallel. There are small differences between CUDA and OpenCL which will be discussed in this paper.
