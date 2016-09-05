##### Applied AI Internal Project

# Applied AI Daft PGM Demo
_Autumn 2016_


This is a very barebones repo to demonstrate usage of `daft-pgm`, a small package for drawing plate notation diagrams purely in Python.

I have found it quite useful for documenting projects that use Bayesian
inference, so perhaps others will also find a set of worked examples helpful.

The package is developed by [Dan Foreman-Mackey](http://dan.iel.fm), and there's lots of info and some demos at the project website [http://daft-pgm.org](http://daft-pgm.org)

_Taken from the project_: Daft is a Python package that uses `matplotlib` to render
pixel-perfect probabilistic graphical models for publication in a journal or
on the internet. With a short Python script and an intuitive model-building
syntax you can design directed (Bayesian Networks, directed acyclic graphs)
and undirected (Markov random fields) models and save them in any formats
that `matplotlib` supports (including PDF, PNG, EPS and SVG).

Copyright Applied AI Ltd 2016


---

# Development


## Install Continuum Anaconda Python 3.5 64bit for your OS

Main site: [https://www.continuum.io/downloads](https://www.continuum.io/downloads)

e.g. for MacOSX: [http://repo.continuum.io/archive/Anaconda3-4.0.0-MacOSX-x86_64.pkg](http://repo.continuum.io/archive/Anaconda3-4.0.0-MacOSX-x86_64.pkg)



## Git clone the repo to your workspace.

e.g. in Mac OSX terminal:

        $> git clone https://github.com/appliedailtd/appliedai_daftpgmdemo.git
        $> cd appliedai_daftpgmdemo



## To work on Python code, setup a virtual environment for Python libraries

1. Using create a new virtualenv, install packages from env YAML file:


        $> conda env create --file condaenv_appliedai_daftpgmdemo.yml
        $> source activate appliedai_daftpgmdemo


2. Launch Jupyter Notebook server

        (appliedai_daftpgmdemo)$> jupyter notebook


---

# General Notes:

AOB

