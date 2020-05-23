# DefineSingletons

Define singleton and it's pretty-printing `show` in one go:

```julia
julia> using DefineSingletons

julia> @def_singleton mysingleton;

julia> mysingleton
mysingleton

julia> Base.issingletontype(typeof(mysingleton))
true
```

See more in the docstring of `@def_singleton`.
