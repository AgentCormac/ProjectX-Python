ProjectX-Python
===============
ProjectX-Python is a noddy project just to explore the integrations and benefits of using Jenkins with Python for quality and testing purposes.

I am using Python 2.7.

Prerequisites
--------------
1. pip
1. unittest - It should be part of the standard Python install.
1. mock
1. nose
1. coverage
1. pylint

Install Python.

Get the get-pip.py script from [here](https://bootstrap.pypa.io/get-pip.py).

**pip install** each package.

In-line (developer) Testing
-------
### Unit tests
To run unit tests, simply type ```nosetests``` from the project root directory.  Nose will scan your whole directory structure looking for unit tests to run.
### Coverage
To run a coverage test, use this command:
```
nosetests --with-coverage --cover-package=projectx_python
```
### Code Quality
To run ***pylint*** use the following command:
```
pylint -rn projectx_python
```
or for more verbose output:
```
pylint -ry projectx_python
```