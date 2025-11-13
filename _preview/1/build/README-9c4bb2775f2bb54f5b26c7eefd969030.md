# Snow Observations Cookbook

<img src="thumbnails/thumbnail.png" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)


This Project Pythia Cookbook is a compilation of tutorials and training 
materials in support of the NASA snow reserach community. Some tutorials
come from the 2020 to 2024 SnowEx Hackweek program hosted at the UW eScience 
Institute. Other materials are drawn from the NASA Goddard "SnowPit" Science
Task Group or STG. The purpose of the tutorials is to help people with data 
access and to demonstrate a variety of disciplinary use cases.

## Motivation

There are numerous data products and methods for accessing and analyzing 
snow observations. These include field, airborne, and satellite missions.
The goal of these tutorials is to streamline data access, reduce duplication 
of effort and build an open science community around snow research 
datasets, algorithms and software.

## Authors

[Zach Fair](@zachghiaccio)
[Anthony Arendt](@aaarendt),
[Mark Welden-Smith](@markweldensmith)

more to be added

### Contributors

<a href="https://github.com/SnowEx/snow-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=SnowEx/snow-cookbook" />
</a>

## Structure

This cookbook is broken up into three main sections: "Data Access", "Observations", and "Analysis and Machine Learning". The current listing of subtopics is currently a work in progress.

### Section 1: Data Access

* Field Campaigns Overview
* SnowExSQL Database

### Section 2: Observations

* GPR and Lidar
* Time-lapse Cameras
* UAVSAR
* Microstructure
* AVIRIS-NG
* Terrestrial Laser Scanning

### Section 3: Analysis and Machine Learning

* Neural Networks with PyTorch
* Snow Modeling
* UCLA Reanalysis
* MERRA-2
* ERA5

## Running the Notebooks

You can either run the notebook using 
[Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of 
how this works are not important for now. All you need to know is how to launch 
a Pythia Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, 
you will need to follow this workflow:


1. Clone the `https://github.com/ProjectPythia/snow-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/snow-cookbook.git
   ```

1. Move into the `snow-cookbook` directory
   ```bash
   cd snow-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate snow-cookbook
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
