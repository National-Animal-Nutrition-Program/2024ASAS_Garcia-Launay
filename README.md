# Hands On ASAS2024

In order to import and use these materials, it is necessary to work with google colab at https://colab.research.google.com/

The first step is to open one of the jupyter notebooks available on the github repository - for instance FGL_NANP2024_Step0.ipynb

Then, add a new cell at the start of the notebook and paste the following command line

!git clone https://github.com/florencegarcialaunay/2024ASAS_Garcia-Launay.git

or 

!git clone https://github.com/National-Animal-Nutrition-Program/2024ASAS_Garcia-Launay.git

Then run this command line and check that the whole folder has been sent as a folder in Google colab

Then, add a new cell in the notebook and paste the following code in it

import sys

sys.path.insert(0,'/content/2024ASAS_Garcia-Launay')

Run this code.

This is also necessary to define properly the working directory with the wolloing code :

import os

pwd = os.getcwd() + '/2024ASAS_Garcia-Launay'

os.chdir(pwd)



