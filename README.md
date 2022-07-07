<img src="thumbnail.png" alt="Two world maps with temperature contours and one colorbar." width="300"/>

# Maplotlib Colorbars Cookbook

[![nightly-build](https://github.com/ProjectPythiaCookbooks/mpl-colorbar-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythiaCookbooks/mpl-colorbar-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder-staging.2i2c.cloud/badge_logo.svg)](https://binder-staging.2i2c.cloud/v2/gh/ProjectPythiaCookbooks/mpl-colorbar-cookbook/main?labpath=notebooks)

This Project Pythia Cookbook covers how to assign the same colorbar to multiple plots in Matplotlib. It also covers the recommended best practices when using color in visualizations.

## Motivation

This cookbook walks the user through assigning a colorbar to multiple plots, how to manipulate some select features of a colorbar, and how to choose colormaps appropriately.
## Authors

[Heather Craker](https://github.com/hCraker) and the [Project Pythia](https://projectpythia.org/) Community

### Contributors

<a href="https://github.com/ProjectPythiaCookbooks/mpl-colorbar-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythiaCookbooks/mpl-colorbar-cookbook" />
</a>

## Structure
This cookbook is broken up into three main sections - "Getting Set Up", "Making the Plot", and "Colormap Best Practices"

### Getting Set Up
The setup for this cookbook includes importing the required packages and loading in the data. A brief description of the data and how to use xarray to read the dataset is included.

### Making the Plot
This is the primary section of the cookbook. It shows how to display two contour plots on the same figure and use the same colorbar for both plots.

### Colormap Best Practices
This section explains how to make accessible figures by carefully choosing the colormaps used. It shows how our figure appears in grayscale and to someone with deuteranomaly color deficiency (color blindness).

## Running the Notebooks
You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
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

1. Clone the `https://github.com/ProjectPythiaCookbooks/mpl-colorbar-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythiaCookbooks/mpl-colorbar-cookbook.git
    ```  
1. Move into the `mpl-colorbar-cookbook` directory
    ```bash
    cd mpl-colorbar-cookbook
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f mpl-colorbar-cookbook-dev.yml
    conda activate mpl-colorbar-cookbook
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
