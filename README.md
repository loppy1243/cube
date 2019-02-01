## Isometries of the Cube

The LaTeX source of my writeup is under `writeup/`; you cannot build this, unfortunately,
since it uses macros I have elsewhere on my computer and collecting those all here etc. etc.
would be a pain. There is, however, a compiled version included as `writeup/writeup.pdf`.

The Julia program for generating tilings is `cube.jl`. To install dependencies, open a Julia
prompt in this directory and type
```
julia> import Pkg
julia> Pkg.activate(".")
julia> Pkg.instantiate()
```
To use the code,
```
julia> include("cube.jl")
julia> Cube.call_the_function_you_want()
```
All of the core functions have help strings, which can be accessed with
```
julia> ?Cube.the_function_you_want
```
