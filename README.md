# Programming for Data Analysis Project


## Introduction

This repository contains a Python Jupyter notebook which looks at dataset of cat information collected by Ronald Fisher[<sup>1</sup>](#f1).<a id='a1'></a> and then generates a simulated dataset based on Fisher's original, as well as adding additional randomly simulated variables to the dataset not contained in the original.  

This repository is part of an project for the module Programming for Data Analysis, for the course HDip in Computing in Data Analytics in GMIT. The assignment overview is as follows: 

> #### Problem statement
>For this project you must create a data set by simulating a real-world phenomenon of
>your choosing. You may pick any phenomenon you wish – you might pick one that is
>of interest to you in your personal or professional life. Then, rather than collect data
>related to the phenomenon, you should model and synthesise such data using Python.     
>We suggest you use the numpy.random package for this purpose.     
>Specifically, in this project you should:    
>• Choose a real-world phenomenon that can be measured and for which you could
>collect at least one-hundred data points across at least four different variables.      
>• Investigate the types of variables involved, their likely distributions, and their
>relationships with each other.      
>• Synthesise/simulate a data set as closely matching their properties as possible.      
>• Detail your research and implement the simulation in a Jupyter notebook – the
>data set itself can simply be displayed in an output cell within the notebook.        
>Note that this project is about simulation – you must synthesise a data set. Some
>students may already have some real-world data sets in their own files. It is okay to
>base your synthesised data set on these should you wish (please reference it if you do),
>but the main task in this project is to create a synthesised data set.     
----------------
## To rerun the analysis on your machine

1. Install Anaconda - https://www.anaconda.com/products/individual   
- Alternatively, if you already have Python installed and do not wish to install Anaconda, you can download the requirements.txt file and run pip3 install -r requirements.txt
2. Open command terminal. If using windows it is recommended to install Cmder - https://cmder.net/
3. Download this repository with the following command using the command line - git clone https://github.com/andrewjscott/Programming-for-Data-Analysis-Project
4. Enter the following command on command line to open Jupyter, will will then open in your web browser - jupyter lab
5. In the Jupyter tab that opens in your browser, navigate to the Simulation.ipynb notebook you wish to run and open
6. Click on Run and then click on Restart Kernal and Run all cells.
-----------
## References 
**1**.<a id='f1'></a> Fisher, R.A., 1947. The analysis of covariance method for the relation between a part and the whole. Biometrics, 3(2), pp.65-68. [online] Doi:  https://doi.org/10.2307/3001641 [Accessed 24 December 2021].[↩](#a1) 