
<p align="center">
  <img style="float: right;" src="https://raijin.ucar.edu/_static/images/logos/ProjectRaijin_Logo.png" width="300" /> 
  <img style="float: right;" src="https://raw.githubusercontent.com/UXARRAY/unstructured-grid-viz-cookbook/main/notebooks/images/logos/siparcs.png" width="150" />
</p>


# Unstructured Grid Visualization Cookbook

[![nightly-build](https://github.com/UXARRAY/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/UXARRAY/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)

This Cookbook showcases how to visualize Unstructured Grids using UXarray paired with community tool sets such as HoloViz and Matplotlib. It was put together as part of 
Project Raijin's NCAR Summer Internships in Parallel Computational Science (SIParCS) project, which is titled "Python Data Analysis and Visualization for Unstructured Grid Data."
## Motivation

(Add a few sentences stating why this cookbook will be useful. What skills will you, "the chef", gain once you have reached the end of the cookbook?)

## Authors

[Ian Franda (NCAR SIParCS 2023 Intern)](@ifranda)

[Philip Chmielowiec (NCAR GeoCAT)](@philipc2)

### Contributors

<a href="https://github.com/UXARRAY/unstructured-grid-viz-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=UXARRAY/unstructured-grid-viz-cookbook" />
</a>

## Structure

This notebook is broken down into four individual notebooks which outline the necessary workflows to visualize unstructured grids. 

### Using UXarray to Work with Unstructured Grid Datasets

(Add content for this section, e.g., "The foundational content includes ... ")

### Plotting with HoloViz

(Add content for this section, e.g., "Example workflows include ... ")

### Plotting with Matplotlib

### Comparison Between Methods

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

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/cookbook-example` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```


