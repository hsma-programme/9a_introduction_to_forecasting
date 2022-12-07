[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hsma5/9a_introduction_to_forecasting/HEAD)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-360+/)

# HSMA5: An introduction to forecasting

**Welcome to the HSMA forecasting repo**.  In the 3 hour class you will be introduced to forecasting applied to operational problems in health and social care.

## Course structure

1. Lecture introducing you to the theory and practice of forecasting;
2. A series of short, code-along lectures in Jupyter notebooks (to go through with instructor); and
3. Two 20 minute practical exercises to give you experience of visualising time series data and producing simple forecasts. 

## Learning outcomes

**By the end of the class you will have...**

* New tools to appraise and question forecasting studies;
* Hands on experience of manipulating time series in python; and
* Hands on experience of producing simple benchmark forecasts using the [`forecast-tools`](https://pypi.org/project/forecast-tools/) python package.

## Setup for the course

You are provided with a conda environment (see `binder/environment.yml`) that you can use to create and install the necessary dependencies.  To install follow these instructions.

1. Open an anaconda prompt (or terminal on Mac and Linux) in the same directory as the course files.  Run the following commands

   * `conda update conda`
   * `conda env create -f binder/environment.yml`

2. Conda will resolve the environment and ask if you wish to install it.  Answer 'y'. Installation will take several minutes.  It installs an environment called `hsma5_forecast9a`.  You then need to activate it using the command below.

   * `conda activate hsma5_forecast9a`

3. To follow the code along lectures and complete the exercises please use Jupyter-Lab.  To run it enter the following command into your anaconda prompt or terminal (making sure you are in the same directory as the files).

   * `jupyter-lab`

Jupyter will then open.


# Launch Notebooks in Google Colab

If you are experiencing issues with Jupyter-Lab on your personal computer then you can also run the notebooks in Google Colab.  Use the links below to launch them:

> Note you require a Google account to use Colab.

## Code along lectures
* Code along 1: Loading time series using pandas [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma5/9a_introduction_to_forecasting/blob/main/code_along/9a_01_pandas_time_series.ipynb)
* Code along 2: Exploring time series [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma5/9a_introduction_to_forecasting/blob/main/code_along/9a_02_exploring_ts.ipynb) 
* Code along 3: Simple forecasting [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma5/9a_introduction_to_forecasting/blob/main/code_along/9a_03_benchmark_forecasts.ipynb)


## Practical Exercises
* Exercise 1: Exploring time series [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma5/9a_introduction_to_forecasting/blob/main/exercises/Practical_1.ipynb)
* Exercise 2: Simple forecasting [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hsma5/9a_introduction_to_forecasting/blob/main/exercises/Practical_2.ipynb)

## Solutions to Exercises

> Solutions to practical exercises will be released following the live lecture, scheduled for 21 February 2023.
