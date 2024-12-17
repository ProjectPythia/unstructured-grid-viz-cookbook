<p align="center">
  <img style="float: right;" src="https://raijin.ucar.edu/_static/images/logos/ProjectRaijin_Logo.png" width="225" />
  <img style="float: right;" src="https://raw.githubusercontent.com/ProjectPythia/unstructured-grid-viz-cookbook/main/notebooks/images/logos/SEATSLogoTransparent.png" width="250" />
</p>

# Unstructured Grid Visualization Cookbook

[![nightly-build](https://github.com/ProjectPythia/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/unstructured-grid-viz-cookbook.git/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10403389.svg)](https://doi.org/10.5281/zenodo.10403389)

This Cookbook is a comprehensive showcase of workflows & techniques for visualizing Unstructured Grids using [UXarray](https://uxarray.readthedocs.io/),  
foundational information on unstructrued grids also provided.

## Motivation

The ability to natively visualize unstructured grids is much needed within the Scientific Python Ecosystem,
which poses multiple challenges and needs to:

- Not regrid the source unstructured grid to structured grid
- Take advantage of grid information, such as connectivity variables
- Limit the amount of pre-processing needed to prepare the data for Python visualization tools

UXarray enables such visualization methods that operate directly on unstructured grid data, providing 
Xarray-styled functionality to better read in and use unstructured grid datasets that follow standard 
conventions.

UXarray supports a variety of unstructured grid formats and file types including UGRID, MPAS, ICON, CAM-SE, 
SCRIP, Exodus, ESMF, GEOS, and FESOM2, and is extensible for other formats.

This cookbook covers an introduction to unstructured grids and UXarray from a visualization standpoint, 
providing foundational information about unstructured grids, visualization methods and libraries, and 
introducing UXarray, and showcasing several UXarray visualization functions and workflows.

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

This cookbook is split up into several chapters to communicate the content efffectively with different 
levels of readers:

**1. Foundations**

Here, we cover overview of the foundational topics necessary to understand the content in this cookbook, 
e.g. what unstructured grids are and how they are different than structured grids, what plotting libraries 
and visualization techniques exist that can be helpful for unstructured grid visualization, and we briefly 
mention how UXarray is related to these.

**2. Introduction to UXarray**

In this chapter, we provide an overview of UXarray: An Xarray-extension for unstructured grid-formatted 
climate and global weather data analysis and visualization.

**3. Plotting with UXarray**

We provide an overview of the UXarray plotting API along with several visualization functionality, and cases 
and examples that can be realized using such UXarray functionality; Grid visualization, Data visualization, 
Geographic projections and features, to name a few. Also in this section, customization and interactivaity 
with UXarray plotting and considerations with high-resolution plotting are also provided.

**4. Visualization Workflows**

In this last chapter, we offer to the interested readers a set of focused workflows that can be realized 
with UXarray; MPAS analysis across resolutions, e3SM radiative feedback analysis, to name a few

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
