# solutions
A set of solution files for Maths and Science problems in various languages / formats

## Instructions for Reproducibility
Depending on the commands used, a solution might run in your own environment IE JupyterLab in Anaconda. To reproduce the environments that the solution was developed in follow the relevant instructions

Install the environment for your hardware detailed at - http://www.bunsen.site
Then depending on solution format:
### Pluto / Julia
In a terminal:
cd to environment directory created in bunsen instructions.

julia18 --project=.

import Pluto

Pluto.run()

In the Pluto notebook add the following to a cell

using Pkg

Pkg.activate(“Project.toml”)

### JupyterLab / Python
EITHER

In a terminal:

conda activate YOURENV (IE a3105)

export JUPYTER_CONFIG_DIR=~/miniforge3/envs/YOURENV

jupyter lab

OR
In a terminal:
conda activate YOURENV (IE a3105)

export JUPYTER_CONFIG_DIR=~/miniforge3/envs/YOURENV

jupyter lab --no-browser --ip-addr=YOURIP --port=YOURPORT
Start VS code

Select the python environment

Connect to the jupyter session above using the URL in the terminal

Open the solution file

### R
EITHER

Start RStudio application

Open the solution file

OR

Start VS code

Open the solution file

### Octave
On Apple Intel or Apple Silicon or Linux

octave --gui

On Raspberry Pi

Menu Raspberry > Education > GNU Octave

### Wolfram
In a terminal:

conda activate YOURENV (IE a3105)

jupyter lab

Ensure the Wolfram 13 kernel is selected

OR

Start VScode

Open the solution file

### Grapher
On a Mac run the Grapher application

Open the solution file

### GeoGebra
On your platform run the Geogebra application

Open the solution file

### Maxima
In a terminal:

wxmaxima

Open the solution file