# CaPTk diffusion derivatives

Flywheel gear that implements CaPTk's application for generating measurements for a [diffusion weighted image](https://cbica.github.io/CaPTk/Diffusion_Derivatives.html). 

## Dependencies:
- CaPTk (gear uses the existing Docker container 2021.03.29)

## Required inputs:
- DWI
- mask (binary)
- bval
- bvec

## Optional inputs:
- reg-fixed

## Optional configuration:
- which measurements to output (by default all will be generated)
