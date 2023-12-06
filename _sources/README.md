<p align="center">
  <img style="float: right;" src="https://raijin.ucar.edu/_static/images/logos/ProjectRaijin_Logo.png" width="225" />
  <img style="float: right;" src="https://raw.githubusercontent.com/ProjectPythia/unstructured-grid-viz-cookbook/main/notebooks/images/logos/SEATSLogoTransparent.png" width="250" />
  <img style="float: right;" src="https://geocat-comp.readthedocs.io/en/latest/_static/GeoCAT_nsf.svg" width="275" />
</p>

# Unstructured Grid Visualization Cookbook

[![nightly-build](https://github.com/ProjectPythia/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)

This Cookbook is a comprehensive showcase of workflows & techniques for visualizing Unstructured Grids using [UXarray](https://uxarray.readthedocs.io/).

## Motivation

High-level, scalable visualization of the native unstructured grids is a much-needed ability in the scientific Python ecosystem. To achieve this, the process needs:

- Not to regrid the unstructured grids into structured grids,
- To use the vital information such as connectivity that comes with the grid,
- Not to require a lot of pre-processing as it happens in the majority of the Python visualization tools that are specialed for structured grids

UXarray enables such visualization methods to operate directly on unstructured grid data, providing Xarray-styled functionality to better read in and use unstructured grid datasets that follow standard conventions. UXarray supports a variety of unstructured grid formats including UGRID, MPAS, SCRIP, and Exodus, and is extensable for other formats.

This cookbook covers the overview of unstructured grids and UXarray in particular, provides an overview of the visualization methods and libraries, and showcases several UXarray visualizaition functions.

## Authors

[Philip Chmielowiec (NSF NCAR)](https://github.com/philipc2)

[Orhan Eroglu (NSF NCAR)](https://github.com/erogluorhan)

[Rajeev Jain (Argonne National Laboratory)](https://github.com/rajeeja)

[Ian Franda (University of Wisconsin-Madison)](https://github.com/ifranda)

### Contributors

<a href="https://github.com/ProjectPythia/unstructured-grid-viz-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/unstructured-grid-viz-cookbook" />
</a>

## Structure

This cookbook is split up into a few chapters that provide a detailed overview of how to use UXarray to work with and visualize unstructured grid datasets:

**1. Introduction to UXarray & Unstructured Grids**

Here we cover what unstructured grids are and how they are different than structured grids as well as whay UXarray could play a significant role in unstructured grid visualization.

**2. Methods & Libraries for Unstructured Grid Visualization**

In this chapter, we briefly introduce plotting libraries and their specific technologies as well as rendering techniques that could be used for unstructured grid plotting and are used as part of UXarray.

**3. UXarray Visualization**

Several visualization cases and examples that can be realized using UXarray are provided in this chapter; grid topology plots, polygons, points, to name a few. Also in this section, the usage of UXarray plotting API and a discussion of visualization at scale are also provided.

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

1. Clone the `https://github.com/ProjectPythia/unstructured-grid-viz-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/unstructured-grid-viz-cookbook.git
   ```

1. Move into the `unstructured-grid-viz-cookbook` directory
   ```bash
   cd unstructured-grid-viz-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate unstructured-grid-viz-cookbook-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
