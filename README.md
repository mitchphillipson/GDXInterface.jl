GDXInterface.jl
=============

High-level GDX file API for reading and writing [GDX files](https://gams-dev.github.io/gdx/index.html).

The `gdx_jll` package provides the GDX library (libgdx) independently of GAMS.

Therefore, no GAMS software installation is required.

In this prototype version, installation requires that you do the following
```julia
pkg> dev https://github.com/jd-foster/gdx_jll.jl.git

pkg> add https://github.com/jd-foster/GDXInterface.jl.git
```

Test using
```julia
pkg> test GDXInterface
```

These instructions will be updated if or when the above packages are registered.
