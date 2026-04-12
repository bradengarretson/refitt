
# refitt

The Reccomender Engine for Intelligent Tracking (REFITT) is a reccomender engine that autonomously designs optimal observing strategies in real time that utilize the diverse capabilities provided by different telescopes and instruments, weighted by their respective costs vs. benefits to, to achieve community-directed scientific objectives. Unlike existing follow-up programs that focus on detailed characterization of individual supernovae, REFITT prioritizes observations that maximize expected information gain of physical model parameters, enabling improved population-level inference from LSST supernova data through more efficient use of limited follow-up resources. 

[![Template](https://img.shields.io/badge/Template-LINCC%20Frameworks%20Python%20Project%20Template-brightgreen)](https://lincc-ppt.readthedocs.io/en/latest/)

[![PyPI](https://img.shields.io/pypi/v/refitt?color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/refitt/)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/bradengarretson/refitt/smoke-test.yml)](https://github.com/bradengarretson/refitt/actions/workflows/smoke-test.yml)
[![Codecov](https://codecov.io/gh/bradengarretson/refitt/branch/main/graph/badge.svg)](https://codecov.io/gh/bradengarretson/refitt)
[![Read The Docs](https://img.shields.io/readthedocs/refitt)](https://refitt-pipeline.readthedocs.io/)
[![Benchmarks](https://img.shields.io/github/actions/workflow/status/bradengarretson/refitt/asv-main.yml?label=benchmarks)](https://bradengarretson.github.io/refitt/)

This project was automatically generated using the LINCC-Frameworks 
[python-project-template](https://github.com/lincc-frameworks/python-project-template).

A repository badge was added to show that this project uses the python-project-template, however it's up to
you whether or not you'd like to display it!

For more information about the project template see the 
[documentation](https://lincc-ppt.readthedocs.io/en/latest/).

## Dev Guide - Getting Started

Before installing any dependencies or writing code, it's a great idea to create a
virtual environment. LINCC-Frameworks engineers primarily use `conda` to manage virtual
environments. If you have conda installed locally, you can run the following to
create and activate a new environment.

```
>> conda create -n <env_name> python=3.11
>> conda activate <env_name>
```

Once you have created a new environment, you can install this project for local
development using the following commands:

```
>> ./.setup_dev.sh
>> conda install pandoc
```

Notes:
1. `./.setup_dev.sh` will initialize pre-commit for this local repository, so
   that a set of tests will be run prior to completing a local commit. For more
   information, see the Python Project Template documentation on 
   [pre-commit](https://lincc-ppt.readthedocs.io/en/latest/practices/precommit.html)
2. Install `pandoc` allows you to verify that automatic rendering of Jupyter notebooks
   into documentation for ReadTheDocs works as expected. For more information, see
   the Python Project Template documentation on
   [Sphinx and Python Notebooks](https://lincc-ppt.readthedocs.io/en/latest/practices/sphinx.html#python-notebooks)
