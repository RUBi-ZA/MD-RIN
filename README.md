[![Build Status](https://travis-ci.com/RUBi-ZA/MD-TASK.svg?branch=master)](https://travis-ci.com/RUBi-ZA/MD-TASK)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ece0a51e7cf4436abf71795051f4ee7b)](https://www.codacy.com/gh/RUBi-ZA/MD-TASK?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=RUBi-ZA/MD-TASK&amp;utm_campaign=Badge_Grade)

Take a look at our web application [MDM-TASK-web](https://mdmtaskweb.rubi.ru.ac.za/) and find the [BioRxiv article here](https://www.biorxiv.org/content/10.1101/2021.01.29.428734v1)

# MD-TASK

A suite of Python scripts that have been developed to analyze molecular dynamics trajectories. Detailed documentation on how to install and use MD-TASK can be found on our [ReadTheDocs](http://md-task.readthedocs.io/en/latest/index.html) site.

## Installation

*Download the project:*
```bash
git clone https://github.com/RUBi-ZA/MD-TASK.git
cd MD-TASK
```
*Install dependencies and set up Python virtual environment:*
```bash
sudo apt-get install virtualenvwrapper python-dev libblas-dev liblapack-dev libatlas-base-dev gfortran libpng-dev libfreetype6-dev python-tk r-base
sh install.sh
```
*Install igraph package for R:*
```bash
R
> install.packages("igraph")
```

## Usage

The scripts are located in the root directory of the project. To run the scripts, ensure that the virtual environment is activated. For more info, find detailed documentation [here](http://md-task.readthedocs.io/en/latest/index.html).
