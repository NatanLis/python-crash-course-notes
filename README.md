# python-crash-course-notes
Notes and thoughts from "Python Crash Course, 3rd Edition: A Hands-On, Project-Based Introduction to Programming" written by Eric Matthes

## Setup

### Environment setup

To setup the environment, first you'll need to install either [anaconda](https://www.anaconda.com/download) or [mamba](https://mamba.readthedocs.io/en/latest/installation.html) (a faster and recommended version of conda) - both are package managers for Python with capabilities to create virtual environments.

Then you can create a new environment using the `environment.yml` file (please note that for mamba installation you can use both `conda` and `mamba` commands as they are interchangeable):

```bash
conda env create -f environment.yml
```
### Environment management

To activate the environment (named `python-basics` in the environment.yml), use:

```bash
conda activate python-basics
``````

To update the environment, use:

```bash
scripts/update

# or

conda env update -f environment.yml --prune
```
