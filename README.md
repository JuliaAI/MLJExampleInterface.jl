# MLJExampleInterface

This repository is a template for repositories providing code to
implement the
[MLJ]((https://alan-turing-institute.github.io/MLJ.jl/dev/) model
interface, that is, for creating a so called *interface-only
packages*.


## When to use this template

This template is intended for use when a package providing a machine
learning model algorithm is not hosting the code that implements the
MLJ model API, and a separate package for this purpose is to be
created. For more see
[here](https://alan-turing-institute.github.io/MLJ.jl/dev/adding_models_for_general_use/#Where-to-place-code-implementing-new-models). This
repo is itself a a working implementation but is should be used in
conjunction with the more detailed [model implementation
guidelines](https://alan-turing-institute.github.io/MLJ.jl/dev/adding_models_for_general_use/).

## Instructions in brief

1. Clone this repository or use it as a template if available from your organization. 

2. Rename this repository, replacing the word "Example" with the name of the model-providing package.

1. Develop the contents of src/MLJExampleInterface.jl appropriately

2. Rename src/MLJExampleInterface.jl appropriately

3. Remove Example from Project.toml and instead add the model-providing package

3. **GENERATE A NEW UUID in Project.toml**

4. Replace every instance of "Example" in this README.md with the name of the model-providing package and adjust the organization name in the link.

5. Remove everything in this REAMDE.md except what is below the line you are currently reading &#128521;


# MLJ.jl <--> Example.jl

Repository implementing the [MLJ](https://alan-turing-institute.github.io/MLJ.jl/dev/) model interface for models provided by
[Example.jl](https://github.com/JuliaLang/Example.jl).

| Linux | Coverage |
| :------------ | :------- |
| [![Build Status](https://github.com/JuliaAI/MLJInterfaceTemplate.jl.jl/workflows/CI/badge.svg)](https://github.com/JuliaAI/MLJInterfaceTemplate.jl.jl/actions) | [![Coverage](https://codecov.io/gh/JuliaAI/MLJInterfaceTemplate.jl.jl/branch/master/graph/badge.svg)](https://codecov.io/github/JuliaAI/MLJInterfaceTemplate.jl.jl?branch=master) |
