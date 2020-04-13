# Jupiter Notebook for the Compute Course      "Reproducible and Interactive Data Science"

Eleni Skorda
April , 2020

[DOI:10.5281/zenodo.3749240](https://doi.org/10.5281/zenodo.3749240)



## Important note
Since this is a notebook designed for demonstration I will not save images or the generated data by default. I left the code the figures according to the [project requirements](https://github.com/mlund/jupyter-course#notebook-requirements) but it is user activated in the beginning of the note book. If you chose to activate this know that **all** and generated data are going to be stored in your laptop in the same folder where you placed the notebook.

## What is this notebook for?
This notebook is designed to introduce students to the basic concepts of random number generators and show simple examples of Monte Carlo methods by calculating the pi and a simple integral. 

To be able to follow the presentation students should be familiar with: 
* basic concepts of probability theory and statistics
* programming in python 

The intended learning outcomes of this introduction are:
* Students to be introduced to the concept of pseudo-random number generators
* Be introduced to the concepts of "uniformity" and "randomness" of a generator by looking at a spectral analysis of a simple generator
* After going through the presentation students should be able to use the Monte Carlo methods presented to calculate a simple integral or draw a random number from a distribution.
  

## This git repository contains 
* The notebook file [IntroToMC.ipynb](https://github.com/teokem/project-work-2020-elskorda/blob/master/IntroToMC.ipynb)
* The environment for this notebook [environment.yml](https://github.com/teokem/project-work-2020-elskorda/blob/master/environment.yml)

## Instructions on how to run 
* Download or clone this repository if you have an SSH key you can do :
```
git clone git@github.com:teokem/project-work-2020-elskorda.git
```
* **SKIP THIS step if you already have anaconda and python 3** 
To run this notebook you will need to have python3 and anaconda.You can find more information on how to install those [here](https://github.com/mlund/jupyter-course#preparation-before-the-first-session). You will also need, in this case (i.e to  be able to install anaconda and python NOT TO RUN this particular notebook), this [enviroment.yml](https://github.com/mlund/jupyter-course/blob/master/environment.yml) **INSTEAD** which contains pip in the dependencies.  
* The next step is to create the environment with all necessary dependencies. In an anaconda terminal run the command ( inside the folder you store the repository) (**use the environment.yml included in this repository**) : 

```
conda env create -f environment.yml
conda activate MCIntro
jupyter notebook
```
* There is an abstract and instructions in the notebook to guide you through. You will have to execute **each code** cell. It is advisable to restart the kernel and clear all outputs  
