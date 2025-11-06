# GPU Programming and HPC Optimization: A CUDA-Based Research

## Project Status: Academic Research & Experimental Validation

This repository documents the research and experimental work conducted on leveraging **NVIDIA CUDA (Compute Unified Device Architecture)** for High-Performance Computing (HPC) optimization.

The project validates the efficacy of parallel processing on GPUs by comparing CPU and GPU performance across varying data scales.

## Key Research Highlights

* [cite_start]**Objective:** To explore CUDA architecture, programming models, memory hierarchy, and optimization strategies to transform general-purpose GPUs into powerful accelerators[cite: 1469].
* [cite_start]**Core Finding:** GPU acceleration is critical for large, highly parallel workloads[cite: 1674].
    * [cite_start]**Small Dataset:** CPU outperformed GPU due to kernel launch and data transfer overhead[cite: 1556].
    * [cite_start]**Large Dataset:** GPU achieved a **2.88x speedup** over CPU, confirming the benefits of massive parallelism[cite: 1595, 1588].
* [cite_start]**Methods Explored:** Memory coalescing, shared memory usage, and occupancy tuning[cite: 1599, 1602, 1605].
* [cite_start]**Tools Used:** NVIDIA CUDA Toolkit, NVCC compiler, and Nsight profiling tools[cite: 1576, 1612].

## Repository Structure

| Directory | Content |
| :--- | :--- |
| `Paper/` | Full research paper PDF and BibTeX citation file. |
| `Presentation/` | Presentation slides (PDF) used for the seminar. |
| `Code/` | CUDA C++ source code (`.cu` files) used for the CPU vs. GPU vector addition experiments. |

## Related Publication (TechRxiv)

The full findings of this work have been published as a preprint:

* [cite_start]**Title:** GPU Programming and High-Performance Computing Optimization: A CUDA-Based Research Perspective [cite: 1462]
* **Authors:** Jaltare, Abhas Ajay and Pai, Anusha Raghavendra
* **DOI:** [10.36227/techrxiv.175427098.84903580/v1](http://dx.doi.org/10.36227/techrxiv.175427098.84903580/v1)

## 🛠️ Technologies Used
* **Platform:** NVIDIA CUDA
* **Language:** C/C++ (with CUDA Kernels)
* **Compiler:** NVCC