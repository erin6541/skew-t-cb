<img src="thumbnail.png" alt="thumbnail" width="300"/>

# MetPy Skew-T Cookbook

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/erin6541/skew-t-cb/HEAD)

This Project Pythia Cookbook covers creating various styles of Skew-T Plots using MetPy.

## Motivation

This cookbook will walkthrough creating a simple Skew-T plot with MetPy. This simple Skew-T will serve as a base to add different features on top of with MetPy.  

## Authors

[Erin Rhoades](https://github.com/erin6541)

### Contributors

<a href="https://github.com/ProjectPythia/cookbook-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/cookbook-template" />
</a>

## Structure

This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."

This cookbook consists of multiple notebooks. The initial notebook provides a comprehensive tutorial on constructing a basic sounding. Subsequent notebooks showcase example workflows with advanced features that build upon the fundamental sounding code.

### Foundational Sounding 

This notebook is an indepth tutorial going over creating a Skew-T. This will build our base code that is used in the Example Workflows section.

### Example Workflows

Example workflows include:
- Sounding with Advanced Features 
- Skew-T Analysis
- Skew-T with Hodograph Inset
- Skew-T with Separate Hodograph
- Sounding with Xarray Dataset
- Sounding Plotter
- Common Sounding Calculations 

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/skew-t-cb` repository:

   ```bash
    git clone https://github.com/ProjectPythia/skew-t-cb.git
   ```

1. Move into the `skew-t-cb` directory
   ```bash
   cd skew-t-cb
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate skew-t-cb
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
