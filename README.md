# Blender

Windows 7 CUDA & OptiX support for Blender 4.x and newer with VxKex.

## Description

This repository contains releases of files to replace in the official portable install
of Blender to have CUDA and.or OptiX cycles working when VxKex is used.

Build environment:
```
Visual Studio 2019, version 16.11.46
Windows SDK 10.0.22000.0
NVIDIA CUDA 11.8
NVIDIA OptiX 7.3
```
When you use VxKex on the official portable install of Blender it will work but cycles
CUDA or OptiX will not. For CUDA you'll have an error:
Failed to load CUDA kernel from '...\kernel_sm_XX.cubin.zst' (Invalid kernel image)

It will work if you replace files from BlenderCUDAOptiXPatch_4_x_x.zip but you will still
need to use VxKex.
