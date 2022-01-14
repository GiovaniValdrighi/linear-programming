# Linear and Integer Programming

Notes and exercises of the discipline of _Linear and Integer Programming_ at the undergradute course of Applied Mathematics at EMAp FGV. The implementation of the programs was with the language Julia and with the library JuMP.

# Files organization

The files of the project are separated in the following folders:

- `exercises/`: some implementations of exercises of the course.

- `setgame/`: implementation of a solution of the [Set Game](https://www.setgame.com/set/puzzle) using LIP.

- `simplex-algorithm/`: two implementations of the simplex algorithm.

# Requirements

The implementations used [Julia](https://julialang.org/) with Jupyter Notebooks in the [Anaconda](https://www.anaconda.com/).

1. After installing Julia and Anaconda, in the command line terminal of Julia install the library `IJulia` ([tutorial](https://datatofish.com/add-julia-to-jupyter/)). Now you can create Jupyter Notebooks with Julia.

2. Install the libraries used in Julia: Printf, LinearAlgebra, [JuMP](https://jump.dev/JuMP.jl/stable/), Cbc, Clp.

# How to run

1. All the implementations were created in Notebooks, so to run your desired code, just run all cells.

# Reference

- Applied Mathematical Programming by Bradley, Hax, and Magnanti (Addison-Wesley, 1977)

