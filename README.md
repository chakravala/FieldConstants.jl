# FieldConstants.jl

*Field algbera constants as parametric types*

When using the base Julia language it is frequently necessary to use `Float64` or `Int64` numbers as compile time constants for generating code.
`FieldConstants` implements a parametric type similar to `Val` called `Constant` which satisfies the mathematical field axioms.

Used in [UnitSystems.jl](https://github.com/chakravala/UnitSystems.jl), [FieldAlgebra.jl](https://github.com/chakravala/FieldAlgebra.jl), [Similitude.jl](https://github.com/chakravala/Similitude.jl), and [MeasureSystems.jl](https://github.com/chakravala/MeasureSystems.jl).
