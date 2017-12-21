# Simulation Demo


Overview
============
This project creates a Terminal-based version of John Conway's famous [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life). This is the code for 'Build a Simulation in 5 Min' on [Youtube]()


Added feature:
============

* Random grid fill

## The Rules

For a space that is 'populated':

* Each cell with one or no neighbors dies, as if by solitude.
* Each cell with four or more neighbors dies, as if by overpopulation.
* Each cell with two or three neighbors survives.

For a space that is 'empty' or 'unpopulated'

* Each cell with three neighbors becomes populated.

Dependencies
============
Everything comes with Python natively!

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies

Basic Usage
===========
Run life.py, that's it! 


Credits
===========
Credit for the vast majority of code here goes to [yamadapc](https://github.com/yamadapc)! I've merely created a wrapper around all of the important functions to get people started.
