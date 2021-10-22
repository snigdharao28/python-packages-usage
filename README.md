# python-packages-usage

This repository contains different scripts that describe the usage of different python packages that we use in day to day life.


### pip  
`pip` is a python package installer.   
basic usage: `pip install <package_name>`  
user-specific installation: `pip install --user <package_name>`  
installation through requirements.txt: `pip install -r requirements.txt`

### Package v/ Module
Module: a single python file
Package: a collection of python modules in a directory. Contains a `__init__.py` file.


### commonly used packages & modules
- `os` (module) : provides operational system dependency functionality.
- `shutil` (module) : offers a number of high-level operations on files and collections of files.
- `numpy` (package) : this is a fundamental project which provides scientific computing in Python.
- `scipy` (package) : open-source Python library which is used to solve scientific and mathematical problems. It is built on the NumPy extension and allows the user to manipulate and visualize data with a wide range of high-level commands.



`multiprocessing` - is a package that supports spawning processes using an API similar to the threading module. The multiprocessing package offers both local and remote concurrency, effectively side-stepping the Global Interpreter Lock by using subprocesses instead of threads. Due to this, the multiprocessing module allows the programmer to fully leverage multiple processors on a given machine. It runs on both Unix and Windows.  