<p align="center">
  <img style="float: right;" src="https://raijin.ucar.edu/_static/images/logos/ProjectRaijin_Logo.png" width="225" />
  <img style="float: right;" src="https://github.com/UXARRAY/unstructured-grid-viz-cookbook/blob/main/notebooks/images/logos/SEATSLogoTransparent.png" width="250" />
  <img style="float: right;" src="https://geocat-comp.readthedocs.io/en/latest/_static/GeoCAT_nsf.svg" width="275" />
</p>

# Unstructured Grid Visualization Cookbook

[![nightly-build](https://github.com/UXARRAY/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/UXARRAY/unstructured-grid-viz-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)

This Cookbook is a comprehensive showcase of workflows & techniques for visualizing Unstructured Grids using [UXarray](https://uxarray.readthedocs.io/).

## Authors

[Philip Chmielowiec (NCAR GeoCAT)](@philipc2)

[Orhan Eroglu (NCAR GeoCAT)](@erogluorhan)

[Rajeev Jain (Argonne National Lab)](@rajeeja)

[Ian Franda (NCAR SIParCS 2023 Intern)](@ifranda)

### Contributors

<a href="https://github.com/UXARRAY/unstructured-grid-viz-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=UXARRAY/unstructured-grid-viz-cookbook" />
</a>

## Structure

This cookbook is split up into three chapters that provide a comprehensive overview of how to use UXarray to work with and visualuze unstructured grid datasets.

#### **1. Introduction to UXarray & Unstructured Grids**

#### **2. Methods & Libraries for Unstructured Grid Visualization**

#### **3. UXarray Visualization**

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
