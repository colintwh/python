# Python Basics

   This site seeks to introduce the basics of the Python programming language. The goal of this site serves as a reference source for those (myself included) who needs to recall some of the basic concepts in Python. It also serves as a learning site for those who want to pick up basics of programming quickly.

   You'll need to have a recent version of Python installed on your computer to run the codes. You'll also need to install a text editor or Integrated Development Environment (IDE) to work with your Python programs.

### Python versions

Python underwent a major version change from 2 to 3. We will be using Python 3. Python 2 is still widely used, and although Python 3 is not fully backwards compatible the two versions are very similar. Everything in the notebooks on this site should run on Python 3.6 or later. 

### Python on Different Operating Systems

Python is a cross-platform programming language, which means it runs on all major operating systems - Windows, macOS and Linux. To check whether a recent version of Python is installed on your system, open a command (Windows) or terminal (macOS/Linux) window and enter `python` or `python3` in lowercase. When Python is installed, this command will start the Python interpreter. You should see output indicating which version of Python is installed and a`>>>` prompt where you can start entering Python commands:

```
    Python 3.7.6 (default, Jan 8, 2020, 19:59:22)
    [GCC 7.3.0] on linux
    Type "help", "copyright", "credits" or "license" for more information
    >>>
```

### Running programs from files

The interpreter is useful for testing code snippets and exploring functions and modules, but to save a program permanently we need to write it into a file. Python files are commonly given the suffix .py. Once you have written a program and saved it, you can run it by using the python command with the file name as a parameter:

    python hello_world.py

### Installing new packages

The [Python Package Index (PyPI)](https://pypi.org/) is a large repository of Python packages. You can install packages from this repository using a tool like `conda install` or `pip`. Both of these utilities are cross-platform. Here is how you install a package called sqlobject with pip:

    pip install sqlobject


## Contents:

The basic concepts you'll need to write Python programs are organised in the following chapters, in the form of Jupyter notebooks hosted on GitHub:

   + [Variables, Data Types and Scope](https://github.com/colintanwh/python-basics/blob/master/variables.ipynb)
   + [Collection](https://github.com/colintanwh/python-basics/blob/master/collection.ipynb)
   + [Loop control statements](https://github.com/colintanwh/python-basics/blob/master/loops.ipynb)
   + [Selection control statements](https://github.com/colintanwh/python-basics/blob/master/flowcontrol.ipynb)
   + [Functions](https://github.com/colintanwh/python-basics/blob/master/functions.ipynb)
   + Classes
   + Files and Exceptions
   + Testing your code
   + Useful modules in standard library

*Contents adapted from https://python-textbok.readthedocs.io and the book "Python Crash Course by Eric Matthes"* 