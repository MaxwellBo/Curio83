### Julia Installation

- [Using Homebrew](http://brew.sh/) `brew tap staticfloat/julia`  then `brew install julia`
- If you want some useful libraries, you can:
    + `julia` (opens the REPL)
    + `Pkg.add("Gadfly")` (for graphing)
    + `Pkg.add("Cairo")` (to support Gadfly)
    + `Pkg.add("Match")` (for advanced pattern matching)
- If you want Jupyter, (a useful development environment) for JUlia
    - `pip3 install jupyter`
    - `Pkg.add("IJulia")`
    
### Documentation

#### Core
- [Julia Manual](http://docs.julialang.org/en/release-0.4/)
- [Julia by Example](http://samuelcolvin.github.io/JuliaByExample/)
- [Introducing Julia/DataFrames](https://en.wikibooks.org/wiki/Introducing_Julia/DataFrames)

#### Plotting

- [Gladfly.jl](https://github.com/dcjones/Gadfly.jl)
- [Bokeh.jl](http://bokeh.github.io/Bokeh.jl/)
- [TextPlots.jl](https://github.com/sunetos/TextPlots.jl) (for rapid prototyping)
