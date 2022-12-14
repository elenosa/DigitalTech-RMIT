# DigitalTech-RMIT

[![Open In Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/elenosa/DigitalTech-RMIT/blob/main/Hello_pandemicWorld.ipynb)  

This repository contains the materials for the HDR course Digital Technologies. The program of the course is located [here](./program.md) and several additional resources, from python tutorials to jupyter notebooks in science and engineering, are collected in the folder [additional_resources](./additional_resources).

## Contents

- Module_1: This folder contains Jupyter Notebooks on Python essentials (W0-2)  

    - Lesson_0 - Getting started with SageMaker Studio Lab
    - Lesson_1 - Python Objects
    - Lesson_2 - Operating on Objects
    - Lesson_3 - Function and classes  
  
(The topics of Lessons 2 and 3 may change)
 
- Module_2: This folder contains Jupyter Notebooks on Python in Engineering Data  

    - Lesson_1 - Time series
    - Lesson_2 - Data processing and statistical analysis
    - Lesson_3 - Data visualisation with matplotlib  


(Above topics may change)  

- Quizzes: This folder contains the solutions of the designed quizzes for each module lesson

- Assignments: This folder contains the Jupyter Noteboooks with the solution of the assignments 

## Downloading the Tutorial Materials

For SageMaker Studio Lab, copy this repo URL into the Git tab:

    https://github.com/elenosa/DigitalTech-RMIT

You can also clone the repo to your local machine:

    git clone https://github.com/elenosa/DigitalTech-RMIT  

or directly use the download option from GitHub.

## Installation Instructions

This repository includes [Jupyter Notebooks](https://jupyter.org/). To run these, you will need [Python](https://www.python.org/) and some packages:

- [IPython](http://ipython.org/), a command shell for interactive computing in multiple programming languages that offers introspection, rich media, shell syntax, tab completion, and history.

- [NumPy](http://www.numpy.org/), an extension to the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large library of high-level mathematical functions to operate on these arrays.

- [SciPy](http://www.scipy.org/), an open source Python library used for scientific computing and technical computing.

- [matplotlib](http://matplotlib.org/),  a plotting library for the Python programming language and its numerical mathematics extension NumPy.

- And [Sympy](http://www.sympy.org/), a [Computer Algebra System (CAS)](https://en.wikipedia.org/wiki/Computer_algebra_system). 

The course is thought to be developed with [SageMaker Studio Lab](https://studiolab.sagemaker.aws/) and therefore, the suggested method is to clone the repository there and build the Anaconda [environment.yml](./environment.yml)  

You can create the Anaconda environment (``.yml``) directly from the terminal in the Studio Lab using  

    conda env create -f environment.yml

or just right-click the ``environment.yml`` file and select "Y: Build Conda Environment"  

To run the notebooks in your local machine you need to download a Python Distribution, preferably [Anaconda](https://www.continuum.io/downloads). This will include all the packages mentioned above.

## SageMaker Studio Lab and CANVAS RMIT

The progress of the course is monitored through [RMIT CANVAS](https://www.rmit.edu.au/students/my-course/canvas) platform. In the first module of the course students can find the instructions and a step-by-step video on how to create an account in [SageMaker Studio Lab](https://studiolab.sagemaker.aws/) and the basics to run Jupyter Notebooks.  

A quick introduction to the Studio Lab can be found in this [Youtube tutorial](https://www.youtube.com/watch?v=ue7LuQtE6Pw&ab_channel=TinyTechnicalTutorials) developed by Tiny Technical Tutorials.


## .md files

To visualise Markdown (``.md``) files on the Studio Lab you can open the ``.html`` version. They were compiled with [``pandoc``](http://pandoc.org/) using

     pandoc -t slidy --css style.css -s slides.md -o slides.html

or

     pandoc -t slidy --css style.css --mathjax -s slides.md -o slides.html

to use [MathJax](https://www.mathjax.org/) to render the equations.

## License
All code is under MIT license and media under Creative Commons Attribute.

The content of this reposirtory is licensed under the [Creative Commons Attribution 4.0 license](http://choosealicense.com/licenses/cc-by-4.0/), and the source code that accompany the content is licensed under the [MIT license](https://opensource.org/licenses/mit-license.php).



