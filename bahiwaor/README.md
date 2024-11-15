# bahiwaor-diffusion2d

## Project description

Diffusion2D-Python-Package is a Python package that simulates the two-dimensional diffusion equation. It uses numerical methods to calculate the spread of heat or particles over time across a grid, making it useful for scientific and educational purposes in physics, engineering, and computational science.

## Installing the package

You can install it locally by cloning this repository and running:

```bash
git clone https://github.com/ombahiwal/diffusion2d-fork.git
cd diffusion2d-fork
pip3 install .
```

### Using pip3 to install from PyPI

To install the package, you can either use `pip` to download it from PyPI or clone the repository and install it locally.

```bash
pip3 install bahiwaor-diffusion2d
```

### Required dependencies

The following dependencies are required and will be installed automatically:

- numpy: Used for numerical calculations and array manipulation.
- matplotlib: Used for visualizing the diffusion process.

You can install them manually with:

```bash
pip3 install numpy matplotlib
```

## Running this package

After installation, you can run the diffusion simulation using the command line. The package includes a `solve` command that will start the simulation with default parameters, or you can call the main `solve()` function in Python to adjust parameters as needed.

run:

```bash
solve
```

## Citing

Omkar Bahiwal, "bahiwaor-diffusion2d", 
[GitHub repository](https://github.com/ombahiwal/diffusion2d-fork)
Implemented as [a task for this course](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).
