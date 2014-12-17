# NeuroAnalysis
___

Julia package for neural signal analysis

[![Build Status](https://travis-ci.org/babaq/NeuroAnalysis.jl.svg?branch=master)](https://travis-ci.org/babaq/NeuroAnalysis.jl)
[![Coverage Status](https://img.shields.io/coveralls/babaq/NeuroAnalysis.jl.svg)](https://coveralls.io/r/babaq/NeuroAnalysis.jl)

## 3D Transformation
```julia
a = Vec3(1.0,1.0,0.0)
b = Vec3(1.0,0.0,0.0)
norm(a)
a+b
a-b
5*a
b/3
a==b
a.x
a.y
a.z
a[1]=4
transform(a,rotationxyz(Vec3(0.0,0.0,pi/2)))
translate(b,Vec3(0.0,2.0,0.0))
```
