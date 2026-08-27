Project 0 Getting Started
====================

**University of Pennsylvania, CIS 5650: GPU Programming and Architecture, Project 0**

* Ethan Yang
  * github.com/eyang72004
* Tested on: Windows 11, NVIDIA GeForce RTX 5060 Laptop GPU (Personal Computer)
* CUDA Compute Capability: 12.0

## CUDA / OpenGL

Got the CUDA/OpenGL check running on my laptop.

![CUDA GL Check](images/cuda-gl-check.png)

## Nsight Debugging

I used Nsight Visual Studio Edition to step through the CUDA kernel, inspect thread/block values, and try a conditional breakpoint.

![CUDA Debug Breakpoint](images/cuda-debug-breakpoint.png)

![Nsight Warp Info 1](images/nsight-warp-info-1.png)

![Nsight Warp Info 2](images/nsight-warp-info-2.png)

## Nsight Systems

I ran the CUDA/OpenGL program through Nsight Systems and looked through the timeline and CUDA activity.

![Nsight Systems Timeline](images/nsight-systems-timeline.png)

## Nsight Compute

I profiled the `createVersionVisualization` kernel using Nsight Compute.

![Nsight Compute Summary](images/nsight-compute-summary.png)

![Nsight Compute Throughput / Launch / Occupancy](images/nsight-compute-throughput-launch-occupancy.png)

![Nsight Compute Occupancy / Workload Distribution](images/nsight-compute-occupancy-workload-dist.png)

## WebGL

WebGL 1 and WebGL 2 both work on my machine.

![WebGL 1 Report](images/webgl1-report.png)

![WebGL 2 Report](images/webgl2-report.png)

## WebGPU

WebGPU also works on my machine.

![WebGPU Report](images/webgpu-report.png)
