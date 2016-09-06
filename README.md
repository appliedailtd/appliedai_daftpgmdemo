##### Applied AI Internal Project

# Applied AI Daft PGM Demo
_Autumn 2016_


Barebones repo to demonstrate usage of `daft-pgm`, a small package for drawing plate notation diagrams purely in Python. The package is developed by [Dan Foreman-Mackey](http://dan.iel.fm), and there's lots of info and some demos at the project website [http://daft-pgm.org](http://daft-pgm.org)

>_As per the project_: Daft is a Python package that uses `matplotlib` to render pixel-perfect probabilistic graphical models for publication in a journal or on the internet. With a short Python script and an intuitive model building syntax you can design directed (Bayesian Networks, directed acyclic graphs) and undirected (Markov random fields) models and save them in any formats that `matplotlib` supports (including `.pdf`, `.png`, `.eps` and `.svg`).


This repo accompanies a larger project called **pymc3_vs_pystan** by Jonathan Sedar of Applied AI Ltd, which was written primarily for presentation at the PyData London 2016 Conference.

Applied AI Ltd &copy; 2016


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

