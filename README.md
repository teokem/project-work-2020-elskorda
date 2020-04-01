# Jupiter Notebook for the Compute Cource      "Reproducible and Interactive Data Science"

Eleni Skorda
April , 2020

## This git repository contains 
* The notebook file [IntroToMC.ipynb](https://github.com/teokem/project-work-2020-elskorda/blob/master/IntroToMC.ipynb)
* The enviroment for this notebook [environment.yml](https://github.com/teokem/project-work-2020-elskorda/blob/master/environment.yml)

## Instructions on how to run 
* Download or clone this repository if you have an SSH key you can do :
```
git clone git@github.com:teokem/project-work-2020-elskorda.git
```
* To run this notebook you will need to have python3 and anaconda.You can find more information on how to install those [here](https://github.com/mlund/jupyter-course#preparation-before-the-first-session). You will also need, in this case, this [enviroment.yml](https://github.com/mlund/jupyter-course/blob/master/environment.yml) instead which contains pip in the dependences. 
\
* The next step is to create the enviroment with all necessary dipendencies. In an anaconda terminal run the comand ( inside the folder you store the repository) : 

```
conda env create -f environment.yml
conda activate MCIntro
jupyter notebook
```
* There is an abstract and instructions in the notebook to guide you through. You will have to execute each code cell. It is advisable to restart the kernel and clear all outputs  
