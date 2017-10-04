---
layout: project
title: Phase field modeling of spinodal decomposition using GPU computing
categories: projects
permalink: research/gpu-computing
---

The [CUDA-FFT][fft] library was utilized to solve [Cahn-Hilliard][ch] equation using the spectral technique. The CUDA-FFT library enables one to utilize the CUDA cores present in NVIDIA GPU. 
The Cahn-Hilliard equation being a partial differential equation, gets transformed into algebraic equations by application of Fourier transform. These algebraic equations could be solved in a much faster pace when the GPU is put to use.

A domain size of 4096*4096 was simulated in my laptop which is equipped with a NVIDIA GTX 850m GPU. The 640 CUDA cores were able to perform 10000 timesteps in around 20 minutes. 

<figure>
  <img class="full" src="/images/research/GPU/4000.jpeg" alt="Microstructure">
  <figcaption>The microstructure at 4000 time steps</figcaption>
</figure>

[fft]: https://developer.nvidia.com/cufft "Link for library"
[ch]: https://en.wikipedia.org/wiki/Cahn%E2%80%93Hilliard_equation "ch equation"
