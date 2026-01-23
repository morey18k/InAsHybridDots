# Data for manuscript "Hybrid metal-semiconductor quantum dots in InAs as a platform for quantum simulation"

This digital repository contains the data and analysis code used in the manuscript "Hybrid metal-semiconductor quantum dots in InAs as a platform for quantum simulation". This README contains very important information about the requirements for running the code and understanding information about the analysis.

## Installation

The data can be downloaded from the Stanford Digital repository https://purl.stanford.edu/nh213xs3377, which contains all the necessary data and analysis files. 

Unfortunately, the analysis and figure Python notebooks are only configured to work with very specific versions of Python as well as certain packages. Please follow the instructions below.

First, navigate to the home directory of the digital repository by going to the download location and entering the directory.

```bash
cd InAsHybridDots
```

Using Homebrew or an equivalent package manager, install Python 3.10.19 using

```bash
brew install python@3.10 
```

Then install a Python virtual environment containing the specific version of Python that is needed. For example

```bash
python3.10 -m venv hybriddotvenv
```

Activate the virtual environment

```bash
source hybriddotvenv/bin/activate 
```

Then install all the requirements for this project using the requirements file.

```bash
pip install -r requirements.txt 
```
Once this has been installed, one can run any of the figure notebooks through any of the figure directories, and can access any of the raw data through any of the data-specific directories.



## License

This work is licensed under a Creative Commons Attribution 4.0 International license (CC BY).
