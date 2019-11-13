# GOTO19-MC-Data-Science
Material for GOTO Chicago 2019 data science masterclass

## Welcome to Data Science!

Data science is a science; it is not magic. From this workshop, we will explain what data science and present you some popular data science modeling techniques.

**Note**: There is a learning curve for data science. If you don't understand what's being covered today, it is OK! Revisit the materials after this workshop as many times as you need and eventually you will understand what's going on. Fun fact: it took me 5 times to actually understand linear regression.

---
## Setup

**1. Download Anaconda [here](https://www.anaconda.com/distribution/)**

Anaconda is the most popular workspace for data scientists. It manages different versions of Python and virtual environments for you. However, if you are comfortable with [pyenv](https://github.com/pyenv/pyenv) and [virtualenv](https://virtualenv.pypa.io/en/latest/), please feel free to skip the installation of Anaconda. Instead, please install a Python version of 3.6 or greater.

**2. Clone this repo into your local file system**

```bash
git clone 'https://github.com/taha-hdvi/GOTO19-MC-Data-Science.git'
```

**3. Create a virtual environment**

This guide is for those who installed Anaconda.

```bash
# this installs virtual environment management
conda install virtualenv

# create a virtual environment folder in the project
python -m venv venv --copies
```

Test if your environment is good to go

```bash
# activate the environment
source venv/bin/activate

# list all the packages
pip list 
```

You should have an output like this

```bash
Package    Version
---------- -------
pip        18.1
setuptools 40.6.2
You are using pip version 18.1, however version 19.3.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.
```

**4. Install all packages**

Make sure your project has [requirements.txt](./requirements.txt) downloaded, and your console should have a `(venv)` indicating that you're in the virtual environment.

```bash
pip install -r requirements.txt
```

**5. Test installation**

```bash
python -c 'import pandas; import numpy; import sklearn; import matplotlib'
```

If no error is prompted, you're good to go!

## Managing Virtual Environment With Conda

The above tutorial doesn't use Anaconda's native virtual environment management functionality. Please see this [documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for a full tutorial.

@Copyright Taha Hamid
