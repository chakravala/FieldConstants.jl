# FieldConstants.jl

*Field algbera constants as parametric types*

When using the base Julia language it is frequently necessary to use `Float64` or `Int64` numbers as compile time constants for generating code.
`FieldConstants` implements a parametric type similar to `Val` called `Constant` which satisfies the mathematical field axioms.
