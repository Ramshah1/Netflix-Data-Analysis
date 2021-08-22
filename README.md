# Netflix-Data-Analysis

## Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#project-motivation)
3. [File Description](#file-description)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing-authors-and-acknowledgements)

## Installation
### Dependencies
* Python >=3.7
* matplotlib >= 3.4.2
* numpy >= 1.21.1
* pandas >= 1.3.1
* seaborn >= 0.11.1

### User Installation
Assuming you already have Python>3.7 up and running, the easiest way to install 
the requirements is using **pip** or **conda**. This tutorial assumes using _pip_
for the installation purposes.

Create a virtual environment to set up the project. (Optional Step)

``
python3 -m venv <my_env>
``

cd to the root directory of the code and install the requirements using

``
pip install -r requirements.txt
``

## Project Motivation
For this project, I was interested in Netflix data available as of 2021. The
questions of interest that we will be exploring are:
* In what month of the year, does the most new content gets added to netflix?
* What is the average delay between release of a show and its arrival on netflix.
* How does the different genres relate to the target audience belonging to different age groups?
* Which Country has most content available on netflix?

## File Description
For the purpose of answering above questions, this project contains a single notebook
that addresses the questions. The data under consideration is available as a csv
file which is also publicly available as [Netflix Movies and TV Shows on Kaggle.](https://www.kaggle.com/shivamb/netflix-shows)

## Results
The findings of the analysis are discussed in the jupyter notebook as well as in
a blog post here.

## Licensing, Authors, and Acknowledgements
All data credit to Netflix for data. You can find the Licensing for the data and
other descriptive information on Kaggle at [Netflix Movies and TV Shows.](https://www.kaggle.com/shivamb/netflix-shows).
