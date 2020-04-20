# EMF-Exam
Take home exam for electromagnetic fields I at the University of Windsor, Windsor ON.

To run the jupyter notebook housed by this repository, it is easiest to have
an anaconda distribution of python so that the environment setup will be simple.
Anaconda can be downloaded here: https://www.anaconda.com/distribution/.  Additionally,
the commands given below for running this notebook assume you have git installed on your
computer.  It is possible to download the zip instead, or by getting git from here:
https://git-scm.com/downloads.

Once anaconda and git(optional) is installed,
if on linux, the following commands can be run from terminal.
If on windows, run the following commands on the anaconda command prompt.

```commandline
git clone https://github.com/dmorle/EMF-Exam.git
cd EMF-Exam
conda env create --file environment.yml
conda activate Take-Home-Exam
jupyter notebook
```

The last command should launch your default web browser.  If it does not, open the link
here: http://127.0.0.1:8888.  On this screen, open main.ipynb and run all of the cells.